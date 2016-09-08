#### Test 830701771a7aee8_thali03_samsung-SM-A500FU Logs


```
--------- beginning of main
09-08 18:23:27.521   315   315 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-08 18:23:27.521   315   315 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-08 18:23:28.481   289   289 E SMD     : DCD OFF
09-08 18:23:28.621  6136  6136 D AndroidRuntime: 
09-08 18:23:28.621  6136  6136 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-08 18:23:28.621  6136  6136 D AndroidRuntime: CheckJNI is OFF
09-08 18:23:28.621  6136  6136 D AndroidRuntime: readGMSProperty: start
09-08 18:23:28.621  6136  6136 D AndroidRuntime: readGMSProperty: already setted!!
09-08 18:23:28.621  6136  6136 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-08 18:23:28.621  6136  6136 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-08 18:23:28.621  6136  6136 D AndroidRuntime: readGMSProperty: end
09-08 18:23:28.621  6136  6136 D AndroidRuntime: addProductProperty: start
09-08 18:23:28.781  6136  6136 E AffinityControl: AffinityControl: registerfunction enter
09-08 18:23:28.801  6136  6136 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-08 18:23:28.811  1015  3224 E PersonaManagerService: inState():  stateMachine is null !!
09-08 18:23:28.811  1015  3224 I PersonaManagerService: PersonaId don't exist
09-08 18:23:28.811  1015  3224 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-08 18:23:28.811  1015  3224 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
09-08 18:23:28.831  1015  3224 W ActivityManager: mDVFSHelper.acquire()
09-08 18:23:28.841  1015  3224 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:28.841  1015  3224 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:28.841  1015  3224 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:28.841  1015  3224 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:28.841  1015  1046 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-08 18:23:28.841  1015  1046 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-08 18:23:28.851  6147  6147 E Zygote  : MountEmulatedStorage()
09-08 18:23:28.851  6147  6147 E Zygote  : v2
09-08 18:23:28.851  6147  6147 I libpersona: KNOX_SDCARD checking this for 10155
09-08 18:23:28.851  6147  6147 I libpersona: KNOX_SDCARD not a persona
09-08 18:23:28.851  1015  3224 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6147 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-08 18:23:28.851  1015  3224 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
09-08 18:23:28.851  1015  3224 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-08 18:23:28.851  1015  3224 D InputDispatcher: Focused application set to: xxxx
09-08 18:23:28.851  1015  3224 D InputDispatcher: Focus left window: 3201
09-08 18:23:28.851  6136  6136 D AndroidRuntime: Shutting down VM
09-08 18:23:28.851  6147  6147 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-08 18:23:28.861  1015  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-08 18:23:28.861  1015  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-08 18:23:28.861  6147  6147 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-08 18:23:28.861   256   256 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
09-08 18:23:28.861  6147  6147 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-08 18:23:28.881  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-08 18:23:28.881  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
09-08 18:23:28.891  6147  6147 D TimaKeyStoreProvider: TimaSignature is unavailable
09-08 18:23:28.891  6147  6147 D ActivityThread: Added TimaKeyStore provider
09-08 18:23:28.901  1015  1015 V ActivityManager: Display changed displayId=0
09-08 18:23:28.911  1015  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-08 18:23:28.921  1015  3002 D PersonaManager: isKioskContainerExistOnDevice
09-08 18:23:28.951   256   444 I SurfaceFlinger: id=11 Removed YUIInstallC (5/9)
09-08 18:23:28.961  3201  3201 V ActivityThread: updateVisibility : ActivityRecord{145118e1 token=android.os.BinderProxy@1a66c30c {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
09-08 18:23:29.031  6147  6147 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
09-08 18:23:29.051  6147  6147 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 421-423)
09-08 18:23:29.051  6147  6147 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 18:23:29.061  6136  6136 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-08 18:23:29.081  6147  6147 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1b3ace6d},
,09-08 18:23:29.081  6147  6147 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-08 18:23:29.081  6147  6147 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0,
,09-08 18:23:29.121  6147  6147 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-08 18:23:29.121  6147  6147 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-08 18:23:29.121  6147  6147 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-08 18:23:29.141  6147  6147 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,09-08 18:23:29.151  6147  6147 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,09-08 18:23:29.151  6147  6147 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,09-08 18:23:29.151  6147  6147 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-08 18:23:29.151  6147  6147 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-08 18:23:29.151  6147  6147 I Adreno-EGL: Build Date: 04/06/15 Mon
09-08 18:23:29.151  6147  6147 I Adreno-EGL: Local Branch: 
09-08 18:23:29.151  6147  6147 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-08 18:23:29.151  6147  6147 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-08 18:23:29.151  6147  6147 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-08 18:23:29.271  6147  6173 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,09-08 18:23:29.321  6147  6147 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-08 18:23:29.331  6147  6147 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-08 18:23:29.341  6147  6147 D PhoneWindow: *FMB* installDecor mIsFloating : false
,09-08 18:23:29.341  6147  6147 D PhoneWindow: *FMB* installDecor flags : -2139027200
,09-08 18:23:29.351  6147  6147 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-08 18:23:29.351  6147  6147 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-08 18:23:29.351  6147  6147 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-08 18:23:29.391  6147  6186 D OpenGLRenderer: Render dirty regions requested: true
,09-08 18:23:29.401  1015  1383 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false,
09-08 18:23:29.401  1015  1383 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-08 18:23:29.401  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
09-08 18:23:29.401  1015  1383 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-08 18:23:29.401  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,09-08 18:23:29.411  6147  6147 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,09-08 18:23:29.411  6147  6147 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,09-08 18:23:29.421   256   256 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
,09-08 18:23:29.441  1015  1564 D InputDispatcher: Focus entered window: 6147
,09-08 18:23:29.441  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
09-08 18:23:29.441  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
09-08 18:23:29.441  6147  6147 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
09-08 18:23:29.441  6147  6186 I OpenGLRenderer: Initialized EGL, version 1.4
,09-08 18:23:29.451  6147  6186 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
09-08 18:23:29.451  6147  6186 D OpenGLRenderer: Enabling debug mode 0
,09-08 18:23:29.481  6147  6147 V ActivityThread: updateVisibility : ActivityRecord{2a17ea4c token=android.os.BinderProxy@de56f9e {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-08 18:23:29.521  1015  3002 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-08 18:23:29.521  1174  1174 D PanelView: There is/are notification(s) 
,09-08 18:23:29.531  1015  6189 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-08 18:23:29.541  1015  1046 I ActivityManager: Displayed Component not be shown by security: +607ms (total +701ms)
,09-08 18:23:29.541  1015  1046 W ActivityManager: mDVFSHelper.release()
09-08 18:23:29.541  1015  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{ab87da0 u0 com.test.thalitest/.MainActivity t128} time:110913
,09-08 18:23:29.541  1883  1883 I SamsungIME: getCurrentCandidateView
,09-08 18:23:29.551  6147  6147 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,09-08 18:23:29.551   256  1037 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
09-08 18:23:29.551  6147  6147 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@de56f9e time:110921
,09-08 18:23:29.551   256   444 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
,09-08 18:23:29.591  6147  6147 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6147
,09-08 18:23:29.641  1883  1883 D SamsungIME: Dismiss ExpandCandiate
,09-08 18:23:29.711  6147  6147 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-08 18:23:29.781  1883  1883 I SamsungIME: getDebugLevel  : 0x4f4c
,09-08 18:23:29.821  6147  6190 D jxcore_app_log: JniHelper::setJavaVM(0xb7fb3328), pthread_self() = -1202623376
,09-08 18:23:29.821  1883  1883 I SamsungIME: getDebugLevel  : 0x4f4c
,09-08 18:23:29.831  6147  6190 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-08 18:23:29.831  6147  6190 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-08 18:23:29.831  6147  6190 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-08 18:23:29.831  6147  6190 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-08 18:23:29.831  6147  6190 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-08 18:23:29.831  6147  6190 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18907e7c added. We now have 1 listener(s)
,09-08 18:23:29.831  1883  1883 I SamsungIME: KeybaordView init() : load resources
,09-08 18:23:29.831  6147  6190 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,09-08 18:23:29.831  6147  6190 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-08 18:23:29.831  6147  6190 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-08 18:23:29.841  6147  6190 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 18:23:29.841  6147  6190 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-08 18:23:29.841  6147  6190 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-08 18:23:29.841  6147  6190 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-08 18:23:29.841  6147  6190 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
09-08 18:23:29.841  6147  6190 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-08 18:23:29.841  6147  6190 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-08 18:23:29.841  6147  6190 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-08 18:23:29.841  6147  6190 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-08 18:23:29.841  6147  6190 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-08 18:23:29.841  6147  6190 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-08 18:23:29.841  6147  6190 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-08 18:23:29.841  6147  6190 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-08 18:23:29.841  6147  6190 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-08 18:23:29.841  6147  6190 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-08 18:23:29.841  6147  6190 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@249ca58b added. We now have 1 listener(s)
,09-08 18:23:29.841  6147  6190 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:23:29.851  6147  6190 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 18:23:29.851  6147  6190 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-08 18:23:29.851  6147  6190 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-08 18:23:29.851  6147  6190 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-08 18:23:29.851  6147  6190 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-08 18:23:29.851  6147  6190 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:23:29.861  6147  6190 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,09-08 18:23:29.861  1883  1883 I SamsungIME: getCurrentKeyboard
09-08 18:23:29.861  1883  1883 I SamsungIME: getTextKeyboard
,09-08 18:23:29.871  6147  6190 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-08 18:23:29.871  6147  6190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:23:29.871  6147  6190 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:29.871  6147  6190 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:29.871  6147  6190 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:23:29.871  6147  6190 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:23:29.871  6147  6190 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:29.871  6147  6190 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:23:29.871  6147  6190 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 18:23:29.871  6147  6190 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-08 18:23:29.871  6147  6190 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 18:23:29.871  6147  6190 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-08 18:23:29.871  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:29.871  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:29.881  1883  1883 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-08 18:23:29.901  6147  6147 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-08 18:23:30.411  1883  6198 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-08 18:23:30.431  6147  6197 W jxcore-log: Initializing JXcore engine
09-08 18:23:30.431  6147  6197 W jxcore-log: JXcore engine is ready
,09-08 18:23:30.491  1881  1881 E audit   : type=1400 msg=audit(1473351810.491:205): avc:  denied  { ioctl } for  pid=6197 comm="Thread-1064" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-08 18:23:30.491  1881  1881 E audit   :  SEPF_SM-A500FU_5.0.2-1_0051
09-08 18:23:30.491  1881  1881 E audit   : type=1300 msg=audit(1473351810.491:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9e7ea8f8 items=0 ppid=305 ppcomm=main pid=6197 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-1064" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-08 18:23:30.491  1881  1881 E audit   : type=1320 msg=audit(1473351810.491:205): 
,09-08 18:23:30.501  6147  6197 W jxcore-log: Starting JXcore engine
,09-08 18:23:30.611  6147  6197 W jxcore-log: Platform android,
09-08 18:23:30.611  6147  6197 W jxcore-log: 
09-08 18:23:30.611  6147  6197 W jxcore-log: Process ARCH arm
09-08 18:23:30.611  6147  6197 W jxcore-log: 
,09-08 18:23:30.821  6147  6197 I jxcore-log: JXcore Cordova bridge is ready!
09-08 18:23:30.821  6147  6197 I jxcore-log: 
,09-08 18:23:30.821  6147  6197 W jxcore-log: JXcore engine is started
,09-08 18:23:30.831  6147  6190 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-08 18:23:30.831  6147  6147 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-08 18:23:31.491   289   289 E SMD     : DCD OFF,
,09-08 18:23:32.521   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,09-08 18:23:32.721  5380  5380 D FactoryTest: Not factory mode
,09-08 18:23:32.721  5380  5380 D FactoryTest: Not factory mode. isFactoryMode() returend false
,09-08 18:23:32.721  5380  5380 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,09-08 18:23:32.721  5380  5380 D MTPRx   : still no open session command from host, so toast
,09-08 18:23:32.721  5380  5380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,09-08 18:23:32.721  5380  5380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,09-08 18:23:32.731  5380  5380 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:114100,
09-08 18:23:32.731  1015  1383 E PersonaManagerService: inState():  stateMachine is null !!
09-08 18:23:32.731  1015  1383 I PersonaManagerService: PersonaId don't exist
09-08 18:23:32.731  1015  1383 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,09-08 18:23:32.731  1015  1383 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
,09-08 18:23:32.731  1015  1383 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:32.731  1015  1383 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:32.731  1015  1383 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,09-08 18:23:32.731  1015  1383 W ActivityManager: mDVFSHelper.acquire()
,09-08 18:23:32.751  1015  1383 D PersonaManager: isKioskContainerExistOnDevice
,09-08 18:23:32.751  1015  1383 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-08 18:23:32.761  1015  1383 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-08 18:23:32.761  1015  1383 D InputDispatcher: Focused application set to: xxxx
09-08 18:23:32.761  1015  1383 D InputDispatcher: Focus left window: 6147
,09-08 18:23:32.761  5380  5380 E MTPRx   : started activity for popup
,09-08 18:23:32.761  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-08 18:23:32.761  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-08 18:23:32.781  5380  5380 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,09-08 18:23:32.791  5380  5380 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-08 18:23:32.791  5380  5380 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-08 18:23:32.791  5380  5380 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-08 18:23:32.791  5380  5380 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-08 18:23:32.791  5380  5380 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-08 18:23:32.801  5380  5380 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,09-08 18:23:32.811  1015  1027 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-08 18:23:32.811  1015  1027 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-08 18:23:32.811  1015  1027 D InputDispatcher: Focused application set to: xxxx
,09-08 18:23:32.811  1015  1027 D InputDispatcher: Focus entered window: 6147
,09-08 18:23:32.811  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-08 18:23:32.811  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-08 18:23:32.811  1015  1342 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-08 18:23:32.811  1015  1342 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@f173273 attribute=null, token = android.os.BinderProxy@28f8a283
,09-08 18:23:32.851  5380  5380 D SettingsReceiverActivity: dev.kiessupport is : TRUE,
,09-08 18:23:32.861  5380  5380 D PhoneWindow: *FMB* installDecor mIsFloating : true
09-08 18:23:32.861  5380  5380 D PhoneWindow: *FMB* installDecor flags : 8388610
,09-08 18:23:32.881  6147  6147 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-08 18:23:32.881  6147  6147 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,09-08 18:23:32.881  6147  6147 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-08 18:23:32.881  6147  6147 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,09-08 18:23:32.881  1015  3002 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-08 18:23:32.881  1015  3002 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-08 18:23:32.881  1015  3002 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-08 18:23:32.881  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,09-08 18:23:32.891  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
,09-08 18:23:32.901  6147  6147 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-08 18:23:32.901  6147  6147 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-08 18:23:32.901  6147  6147 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@28392cdd Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@2149a225, 16908290=android.view.AbsSavedState$1@2149a225}, android:focusedViewId=100}]}]
,09-08 18:23:32.901  6147  6147 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-08 18:23:32.901  6147  6147 V ActivityThread: updateVisibility : ActivityRecord{2a17ea4c token=android.os.BinderProxy@de56f9e {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-08 18:23:32.901  6147  6147 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-08 18:23:32.901  6147  6147 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-08 18:23:32.911  6147  6147 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@de56f9e time:114280
,09-08 18:23:32.911  1015  1487 D PersonaManager: isKioskContainerExistOnDevice
,09-08 18:23:33.521   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,09-08 18:23:34.491   289   289 E SMD     : DCD OFF
,09-08 18:23:34.521   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,09-08 18:23:34.691  1015  1564 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-08 18:23:34.691  1015  1564 D BatteryService: level:83, scale:100, status:2, health:2, present:true, voltage: 4092, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,09-08 18:23:34.691  1015  1564 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-08 18:23:34.691  1015  1564 D BatteryService: stay LED for charging
,09-08 18:23:34.691  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-08 18:23:34.691  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-08 18:23:34.691  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-08 18:23:34.691  1015  1015 I MotionRecognitionService: Plugged
,09-08 18:23:34.691  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,09-08 18:23:34.691  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-08 18:23:34.701  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 83
,09-08 18:23:34.711  2649  2649 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-08 18:23:34.711  2649  2722 D HeadsetStateMachine: Disconnected process message: 10
,09-08 18:23:34.721  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:83 status:2 health:2
,09-08 18:23:34.721  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:83 status:2 health:2
,09-08 18:23:34.721  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:83 status:2 health:2
,09-08 18:23:35.161  1015  2769 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-08 18:23:35.461  1015  2723 D SSRM:n  : SIOP:: AP = 340
,09-08 18:23:35.521   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,09-08 18:23:35.731  1015  1041 W ActivityManager: mDVFSHelper.release()
,09-08 18:23:36.521   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,09-08 18:23:37.491   289   289 E SMD     : DCD OFF,
,09-08 18:23:37.521   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,09-08 18:23:38.631  1015  1094 V AlarmManager: waitForAlarm result :4
,09-08 18:23:38.631  1015  1094 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,09-08 18:23:38.651  1907  1907 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,09-08 18:23:38.681  1015  3238 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-08 18:23:38.681  1015  3238 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,09-08 18:23:38.681  1015  3238 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:38.681  1015  3238 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:38.681  1015  3238 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:38.731  3786  3786 D ConnectivityManager: CallingUid : 10012, CallingPid : 3786
,09-08 18:23:38.731  1015  1487 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-08 18:23:38.731  1015  1128 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,09-08 18:23:38.731  1015  1128 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
09-08 18:23:38.731  1015  1128 D ConnectivityService: apparently satisfied.  currentScore=60
,09-08 18:23:38.731  3786  6209 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-08 18:23:38.781  3786  6210 W DriveInitializer: Background init thread started
,09-08 18:23:38.801   255   534 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
09-08 18:23:38.801   255   534 W Vold    : Returning OperationFailed - no handler for errno 0
,09-08 18:23:38.801  3786  6210 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,09-08 18:23:38.851  1015  3003 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-08 18:23:38.851  1015  3003 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,09-08 18:23:38.861  1015  3003 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:38.861  1015  3003 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:38.861  1015  3003 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:38.881  1015  1487 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,09-08 18:23:38.881  1015  1487 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,09-08 18:23:38.891  1015  1056 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-08 18:23:38.891  3786  6210 W DriveInitializer: Background init thread ended
,09-08 18:23:38.911  1015  3223 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-08 18:23:38.911  1015  3223 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,09-08 18:23:38.911  1015  3223 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:38.911  1015  3223 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:38.911  1015  3223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:38.941  3786  6218 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
09-08 18:23:38.941  3786  6218 D SchedPeriodicTask: Scheduled AdAttestation task.
,09-08 18:23:38.961  1907  1907 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-08 18:23:38.981  1015  1041 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:38.981  1015  1041 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:38.981  1015  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:39.091  1015  3223 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-08 18:23:39.091  1015  3223 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,09-08 18:23:39.091  1015  3223 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:39.091  1015  3223 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:39.091  1015  3223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:39.121  1015  3002 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-08 18:23:39.121  1015  3002 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,09-08 18:23:39.121  1015  3002 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:39.121  1015  3002 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:39.121  1015  3002 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:39.171  1015  1383 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 18:23:39.181  1015  1383 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:39.181  1015  1383 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:39.181  1015  1383 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:39.201  1015  3224 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 18:23:39.201  1015  3224 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:39.201  1015  3224 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:39.201  1015  3224 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:39.221  1015  3235 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 18:23:39.221  1015  3235 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:39.221  1015  3235 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-08 18:23:39.221  1015  3235 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:39.231  1015  3235 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:39.231  1015  3235 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:39.231  1015  3235 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:39.231  1015  3235 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:39.251  6222  6222 E Zygote  : MountEmulatedStorage(),
,09-08 18:23:39.251  6222  6222 E Zygote  : v2,
09-08 18:23:39.251  6222  6222 I libpersona: KNOX_SDCARD checking this for 10012
09-08 18:23:39.251  6222  6222 I libpersona: KNOX_SDCARD not a persona
,09-08 18:23:39.251  6222  6222 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-08 18:23:39.251  1015  3235 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6222 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,09-08 18:23:39.251  6222  6222 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-08 18:23:39.251  6222  6222 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,09-08 18:23:39.281  6222  6222 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:39.281  6222  6222 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:39.301  6222  6222 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-08 18:23:39.301  6222  6222 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-08 18:23:39.341  6222  6222 I MultiDex: VM with version 2.1.0 has multidex support
09-08 18:23:39.341  6222  6222 I MultiDex: install
09-08 18:23:39.341  6222  6222 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-08 18:23:39.371  6222  6222 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...,
,09-08 18:23:39.431  6222  6222 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-08 18:23:39.431  6222  6222 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@29e514fe: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-08 18:23:39.441  6222  6222 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL,
,09-08 18:23:39.461  6222  6222 D ChimeraCfgMgr: Reading stored module config
,09-08 18:23:39.531  1015  1487 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,09-08 18:23:39.541  1015  1251 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 18:23:39.541  1015  1251 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:39.541  1015  1251 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:39.541  1015  1251 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:39.551  6222  6237 I art     : Background sticky concurrent mark sweep GC freed 27809(1309KB) AllocSpace objects, 2(32KB) LOS objects, 5% free, 10MB/11MB, paused 13.916ms total 73.988ms
,09-08 18:23:39.561  1015  1564 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 18:23:39.561  1015  1564 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:39.561  1015  1564 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:39.561  1015  1564 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:39.581  6222  6240 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,09-08 18:23:39.611  6222  6222 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-08 18:23:39.611  6222  6222 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-08 18:23:39.681  1907  2115 I art     : Explicit concurrent mark sweep GC freed 59871(3MB) AllocSpace objects, 10(400KB) LOS objects, 39% free, 13MB/23MB, paused 1.442ms total 82.692ms
,09-08 18:23:39.701  1907  1907 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=4708255a-6d80-490f-934d-33ab04c56a60
,09-08 18:23:39.701  1015  1383 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
09-08 18:23:39.701  1015  1383 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-08 18:23:39.701  1015  1383 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:39.701  1015  1383 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:39.701  1015  1383 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:39.711  1907  1907 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-08 18:23:39.711  1907  1907 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-08 18:23:39.721  1015  3235 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 18:23:39.731  1015  3235 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:39.731  1015  3235 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:39.731  1015  3235 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:39.781   284   675 D WVCdm   : Instantiating CDM.
,09-08 18:23:39.781   284   284 I WVCdm   : CdmEngine::OpenSession
,09-08 18:23:39.781   284   284 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,09-08 18:23:39.801   284   284 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,09-08 18:23:39.831   284   284 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
09-08 18:23:39.831   284   284 D DrmWidevineDash: Service_Initialize: starts!
09-08 18:23:39.831   284   284 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,09-08 18:23:39.831   284   284 D QSEECOMAPI: : App is not loaded in QSEE
,09-08 18:23:39.831   284   284 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
09-08 18:23:39.831   284   284 E QSEECOMAPI: : Error::Loading image failed with ret = -1
09-08 18:23:39.831   284   284 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
09-08 18:23:39.831   284   284 D QSEECOMAPI: : App is not loaded in QSEE
,09-08 18:23:39.831   284   284 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
09-08 18:23:39.831   284   284 E QSEECOMAPI: : Error::Loading image failed with ret = -1
09-08 18:23:39.831   284   284 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
09-08 18:23:39.831   284   284 D QSEECOMAPI: : App is not loaded in QSEE
,09-08 18:23:39.861   284   284 D QSEECOMAPI: : Loaded image: APP id = 12
,09-08 18:23:39.861   284   284 D DrmWidevineDash: Service_Initialize: ends! returns 0
,09-08 18:23:39.881   284   284 D QSAPPSVER: qsapps_get_capabilities: Capability from secure side: 0x0
09-08 18:23:39.881   284   284 D QSAPPSVER: qsapps_get_capabilities: returns 0
09-08 18:23:39.881   284   284 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1772000
09-08 18:23:39.881   284   284 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1772000
09-08 18:23:39.881   284   284 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-08 18:23:39.881   435   442 D DrmLibTime: got the req here! ret=0
09-08 18:23:39.881   435   442 D DrmLibTime: command id, time_cmd_id = 770
09-08 18:23:39.881   435   442 D DrmLibTime: time_getutcsec starts!
09-08 18:23:39.881   435   442 D DrmLibTime: QSEE Time Listener: time_getutcsec
09-08 18:23:39.881   435   442 D DrmLibTime: QSEE Time Listener: get_utc_seconds
09-08 18:23:39.881   435   442 D DrmLibTime: QSEE Time Listener: time_get_modem_time
09-08 18:23:39.881   435   442 D DrmLibTime: QSEE Time Listener: Checking if ATS_MODEM is set or not.
,09-08 18:23:39.881   435   442 D QC-time-services: Lib:time_genoff_operation: pargs->base = 13
09-08 18:23:39.881   435   442 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 2,
09-08 18:23:39.881   435   442 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 0
09-08 18:23:39.881   435   442 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
09-08 18:23:39.881   317   432 D QC-time-services: Daemon: Connection accepted:time_genoff,
,09-08 18:23:39.891   317  6246 D QC-time-services: Daemon:Received base = 13, unit = 1, operation = 2,value = 0
,09-08 18:23:39.891   317  6246 D QC-time-services: Daemon:genoff_opr: Base = 13, val = 0, operation = 2
09-08 18:23:39.891   317  6246 D QC-time-services: offset is: 0 for base: 0,
,09-08 18:23:39.891   435   442 E QC-time-services: Receive Passed == base = 13, unit = 1, operation = 2, result = 0,
09-08 18:23:39.891   435   442 D DrmLibTime: QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
,09-08 18:23:39.891   435   442 D DrmLibTime: QSEE Time Listener: Retrieved Android system time: 1473351819
09-08 18:23:39.891   435   442 D DrmLibTime: time_getutcsec returns 0, sec = 1473351819; nsec = 0
09-08 18:23:39.891   435   442 D DrmLibTime: time_getutcsec finished! 
09-08 18:23:39.891   435   442 D DrmLibTime: iotcl_continue_command finished! and return 0 
09-08 18:23:39.891   435   442 D DrmLibTime: before calling ioctl to read the next time_cmd
,09-08 18:23:39.891   284   284 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-08 18:23:39.891   317   432 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,09-08 18:23:39.891  1651  3428 I art     : Explicit concurrent mark sweep GC freed 1424(48KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 737us total 24.187ms
,09-08 18:23:39.911   284   284 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
09-08 18:23:39.911   284   284 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
09-08 18:23:39.911   284   284 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-08 18:23:39.911   284   284 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-08 18:23:39.911   284   284 D DrmWidevineDash: hlos api version =  9
09-08 18:23:39.911   284   284 D DrmWidevineDash: tz api version =  9
09-08 18:23:39.911   284   284 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
09-08 18:23:39.911   284   284 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
09-08 18:23:39.911   284   284 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-08 18:23:39.911  6222  6233 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
09-08 18:23:39.911  6222  6233 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-08 18:23:39.911  6222  6233 I System.out: (HTTPLog)-Static: isShipBuild true
09-08 18:23:39.911  6222  6233 I System.out: (HTTPLog)-Thread-1045-158853875: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
09-08 18:23:39.911  6222  6233 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-08 18:23:39.911   279   993 D EnterpriseController: uids 10012
09-08 18:23:39.911   279   993 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-08 18:23:39.911   279   993 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,09-08 18:23:39.921   284   284 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,09-08 18:23:39.921   284   284 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
09-08 18:23:39.931   284   284 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
,09-08 18:23:39.931   284   284 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xbea861b0
09-08 18:23:39.931   284   284 D DrmWidevineDash: OEMCrypto_OpenSession Session ID = 0
09-08 18:23:39.931   284   284 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
09-08 18:23:39.931   284   284 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-08 18:23:39.931   284   284 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
09-08 18:23:39.931   284   284 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
09-08 18:23:39.931   284   284 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb77c0e60, dataLength=8
09-08 18:23:39.931   284   284 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-08 18:23:39.931   284   284 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-08 18:23:39.931   284   284 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0,
,09-08 18:23:39.931   284   284 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xb773a978, wrapped_rsa_key_length=1280
,09-08 18:23:39.931   284   284 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-08 18:23:39.931   284   284 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,09-08 18:23:39.931   284   284 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
09-08 18:23:39.931   284   284 I WVCdm   : CdmEngine::QueryKeyControlInfo
,09-08 18:23:39.931   284   720 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,09-08 18:23:39.931   284   720 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
09-08 18:23:39.931   284   720 I WVCdm   : CdmEngine::GenerateKeyRequest
09-08 18:23:39.931   284   720 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb775a050, idLength=0xb1751730
,09-08 18:23:39.931   284   720 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-08 18:23:39.951   284   720 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,09-08 18:23:39.951   284   720 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
09-08 18:23:39.951   284   720 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
09-08 18:23:39.951   284   720 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
09-08 18:23:39.951   284   720 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-08 18:23:39.951   284   720 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
09-08 18:23:39.951   284   720 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 24
09-08 18:23:39.951   284   720 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0
09-08 18:23:39.951   284   720 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!, current = 0xb1751746, maximum = 0xb1751747
09-08 18:23:39.951   284   720 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
09-08 18:23:39.951   284   720 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-08 18:23:39.951   284   720 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0
09-08 18:23:39.951   284   720 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
09-08 18:23:39.951   284   720 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
09-08 18:23:39.951   284   720 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-08 18:23:39.951   284   720 D DrmWidevineDash: hlos api version =  9
09-08 18:23:39.951   284   720 D DrmWidevineDash: tz api version =  9
09-08 18:23:39.951   284   720 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
09-08 18:23:39.951   284   720 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xb17517b4
09-08 18:23:39.951   284   720 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-08 18:23:39.951   284   720 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-08 18:23:39.951   284   720 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
09-08 18:23:39.951   284   720 D WVCdm   : PrepareKeyRequest: nonce=2927666761
09-08 18:23:39.951   284   720 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb773a488
09-08 18:23:39.951   284   720 D DrmWidevineDash: message_length=1599, signature=0xb773b118, signature_length=0xb1751714,
09-08 18:23:39.951   284   720 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-08 18:23:39.961  6222  6233 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-08 18:23:39.971  6222  6233 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6222, getuid(): 10012
,09-08 18:23:40.021  1907  2105 W GCoreFlp: No location to return for getLastLocation()
,09-08 18:23:40.051  1015  3235 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 18:23:40.051  1015  3235 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:40.051  1015  3235 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-08 18:23:40.051  1015  3235 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:40.051  1015  1487 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 18:23:40.061  1015  1487 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:40.061  1015  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:40.061  1015  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:40.061  1015  1383 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 18:23:40.061  1015  1383 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:40.061  1015  1383 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-08 18:23:40.061  1015  1383 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:40.101   284   720 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-08 18:23:40.101   284   720 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,09-08 18:23:40.101   284   675 I WVCdm   : CdmEngine::CloseSession
09-08 18:23:40.101   284   675 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
09-08 18:23:40.101   284   675 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-08 18:23:40.101   284   675 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-08 18:23:40.101   284   675 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
09-08 18:23:40.101   284   675 I WVCdm   : L3 Terminate.
09-08 18:23:40.101   284   675 D DrmWidevineDash: OEMCrypto_Terminate: starts!
09-08 18:23:40.101   284   675 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-08 18:23:40.101   284   675 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,09-08 18:23:40.101   284   675 D DrmWidevineDash: Service_Uninitialize: starts!
,09-08 18:23:40.101   284   675 D QSEECOMAPI: : QSEECom_dealloc_memory 
,09-08 18:23:40.111   284   675 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 12
,09-08 18:23:40.111   284   675 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
09-08 18:23:40.111   284   675 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,09-08 18:23:40.111  3786  6219 D UdcContextInitService: registered all accounts: true
,09-08 18:23:40.111  1907  2110 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-08 18:23:40.121  1907  2122 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,09-08 18:23:40.271  6222  6233 I qtaguid : Untagging socket 30
,09-08 18:23:40.341  1015  3238 I art     : Explicit concurrent mark sweep GC freed 36007(1960KB) AllocSpace objects, 22(352KB) LOS objects, 33% free, 27MB/41MB, paused 2.546ms total 152.989ms
,09-08 18:23:40.451  1015  1342 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
09-08 18:23:40.451  1015  1342 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-08 18:23:40.451  1015  1342 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:40.451  1015  1342 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:40.451  1015  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:40.491   289   289 E SMD     : DCD OFF
,09-08 18:23:40.841  6254  6254 I dex2oat : ----------------------------------------------------
09-08 18:23:40.841  6254  6254 I dex2oat : <SS>: S T A R T I N G . . .
09-08 18:23:40.841  6254  6254 I dex2oat : <SS>: Zip is absent. Canceled.
,09-08 18:23:40.841  6254  6254 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=44 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-08 18:23:40.881  6254  6254 I dex2oat : dex2oat took 35.635ms (threads: 4)
,09-08 18:23:40.891  6222  6233 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-08 18:23:40.891  6222  6233 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-08 18:23:40.891  6222  6233 I Adreno-EGL: Build Date: 04/06/15 Mon
09-08 18:23:40.891  6222  6233 I Adreno-EGL: Local Branch: 
09-08 18:23:40.891  6222  6233 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-08 18:23:40.891  6222  6233 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-08 18:23:40.891  6222  6233 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-08 18:23:41.121  6222  6233 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
09-08 18:23:41.121  6222  6233 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-08 18:23:41.121  6222  6233 I Adreno-EGL: Build Date: 04/06/15 Mon
09-08 18:23:41.121  6222  6233 I Adreno-EGL: Local Branch: 
09-08 18:23:41.121  6222  6233 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-08 18:23:41.121  6222  6233 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-08 18:23:41.121  6222  6233 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-08 18:23:41.171  6222  6233 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
09-08 18:23:41.171  6222  6233 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-08 18:23:41.171  6222  6233 I Adreno-EGL: Build Date: 04/06/15 Mon
09-08 18:23:41.171  6222  6233 I Adreno-EGL: Local Branch: 
09-08 18:23:41.171  6222  6233 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-08 18:23:41.171  6222  6233 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-08 18:23:41.171  6222  6233 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-08 18:23:41.261  1015  1494 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,09-08 18:23:41.261  1015  1494 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,09-08 18:23:41.261  1015  1494 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:41.261  1015  1494 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:41.261  1015  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:41.271  1907  6221 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-08 18:23:41.271   279   993 D EnterpriseController: uids 10012
09-08 18:23:41.271   279   993 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-08 18:23:41.271   279   993 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,09-08 18:23:41.271  1907  6221 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-08 18:23:41.271  1907  6221 I qtaguid : Tagging socket 55 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1907, getuid(): 10012
,09-08 18:23:41.321  1907  6221 I qtaguid : Tagging socket 62 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1907, getuid(): 10012
,09-08 18:23:41.461  1907  2122 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-08 18:23:41.461  1907  2122 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,09-08 18:23:41.481  1907  2122 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-09-08 18:23:40.371+0200, stopTime=2016-09-08 18:23:41.490+0200, duration=1119ms
,09-08 18:23:41.491  1907  6263 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-08 18:23:41.491   279   993 D EnterpriseController: uids 10012
09-08 18:23:41.491   279   993 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-08 18:23:41.491   279   993 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,09-08 18:23:41.491  1907  6263 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
09-08 18:23:41.491  1907  6263 I qtaguid : Tagging socket 63 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1907, getuid(): 10012
,09-08 18:23:41.521  1015  3224 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,09-08 18:23:41.531  1907  6263 I qtaguid : Tagging socket 68 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1907, getuid(): 10012
,09-08 18:23:41.841  1907  6263 I qtaguid : Untagging socket 63
,09-08 18:23:41.871  1015  1342 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-08 18:23:41.871  1015  1342 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,09-08 18:23:41.871  1015  1342 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:41.871  1015  1342 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:41.871  1015  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:41.901  1907  2122 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,09-08 18:23:41.951  1015  3140 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 18:23:41.951  1015  3140 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:41.951  1015  3140 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-08 18:23:41.951  1015  3140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:41.981  1015  3223 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 18:23:41.981  1015  3223 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:41.981  1015  3223 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-08 18:23:41.981  1015  3223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:42.041  1015  3238 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 18:23:42.041  1015  3238 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:42.041  1015  3238 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:42.041  1015  3238 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:42.041  1907  6271 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-08 18:23:42.041  1907  6269 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-08 18:23:42.041  1015  1138 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 18:23:42.041  1015  1138 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:42.041  1015  1138 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:42.041  1015  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:42.071  1015  3224 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 18:23:42.071  1015  3224 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:42.071  1015  3224 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:42.071  1015  3224 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:42.071  1907  6271 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-08 18:23:42.071  1907  6269 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-08 18:23:42.071  1015  3223 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 18:23:42.071  1015  3223 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:42.071  1015  3223 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-08 18:23:42.081  1015  3223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:42.101  1015  1383 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 18:23:42.101  1015  1383 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:42.101  1015  1383 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:42.101  1015  1383 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:42.101  1907  6271 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-08 18:23:42.101  1907  6269 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-08 18:23:42.101  1907  6269 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,09-08 18:23:42.111  1907  6269 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-08 18:23:42.161  1015  1027 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-08 18:23:42.191  1907  6269 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-08 18:23:42.191   279   993 D EnterpriseController: uids 10012
09-08 18:23:42.191   279   993 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-08 18:23:42.191   279   993 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,09-08 18:23:42.201  1907  6269 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-08 18:23:42.201  1907  6269 I qtaguid : Tagging socket 81 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1907, getuid(): 10012
,09-08 18:23:42.251  1907  6269 I qtaguid : Tagging socket 84 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1907, getuid(): 10012
,09-08 18:23:42.511  1015  3140 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-08 18:23:42.521  1907  6269 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-08 18:23:42.521  1907  6269 I qtaguid : Tagging socket 81 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1907, getuid(): 10012
,09-08 18:23:42.521   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,09-08 18:23:42.661  1015  1342 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-08 18:23:42.671  1907  6269 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-08 18:23:42.671  1907  6269 I qtaguid : Tagging socket 81 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 1907, getuid(): 10012
,09-08 18:23:42.811  1015  3140 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-08 18:23:42.811  1907  6269 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-08 18:23:42.811  1907  6269 I qtaguid : Tagging socket 81 with tag 11065b5800000000{285629272,0} for uid -1, pid: 1907, getuid(): 10012
,09-08 18:23:43.481  6147  6197 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-08 18:23:43.481  6147  6197 I jxcore-log: 
,09-08 18:23:43.481  6147  6197 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-08 18:23:43.481  6147  6197 I jxcore-log: 
,09-08 18:23:43.491  6147  6197 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:23:43.491  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:43.491  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:43.491  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:23:43.491  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:23:43.491  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:43.491  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:23:43.491  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 18:23:43.491  6147  6197 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 18:23:43.491  6147  6197 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-08 18:23:43.491  6147  6197 I jxcore-log: 
,09-08 18:23:43.491   289   289 E SMD     : DCD OFF
,09-08 18:23:43.491  6147  6197 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-08 18:23:43.491  6147  6197 I jxcore-log: 
,09-08 18:23:43.521   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,09-08 18:23:43.621  1907  6264 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-08 18:23:43.621  1907  6264 I qtaguid : Tagging socket 63 with tag 1000310200000000{268448002,0} for uid 10012, pid: 1907, getuid(): 10012
,09-08 18:23:43.801  1907  6264 I qtaguid : Untagging socket 63
,09-08 18:23:43.811  1907  2122 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,09-08 18:23:43.831  1015  1564 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,09-08 18:23:44.161  6147  6197 D executeNativeTests: Running unit tests
,09-08 18:23:44.241  6147  6197 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 18:23:44.241  6147  6197 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2897dbaa added. We now have 2 listener(s)
,09-08 18:23:44.241  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-08 18:23:44.241  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:23:44.241  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 18:23:44.241  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:23:44.241  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d12839b added. We now have 2 listener(s)
09-08 18:23:44.241  6147  6197 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:23:44.241  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 18:23:44.241  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:23:44.251  6147  6197 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:23:44.251  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:44.251  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:44.251  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:23:44.251  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:23:44.251  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:44.251  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:23:44.251  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 18:23:44.251  6147  6197 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 18:23:44.251  6147  6197 D io.jxcore.node.ConnectivityMonitor: start: OK,
,09-08 18:23:44.251  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-08 18:23:44.251  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-08 18:23:44.251  6147  6197 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1,
09-08 18:23:44.251  6147  6197 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 18:23:44.251  6147  6197 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-08 18:23:44.251  6147  6197 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-08 18:23:44.251  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-08 18:23:44.251  6147  6197 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 18:23:44.251  6147  6197 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 18:23:44.251  6147  6197 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:44.251  6147  6197 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:44.251  6147  6197 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:44.261  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:44.261  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.261  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:23:44.261  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:23:44.261  6147  6197 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2897dbaa removed from the list
09-08 18:23:44.261  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.261  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d12839b removed from the list
09-08 18:23:44.261  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:44.261  6147  6197 D io.jxcore.node.ConnectivityMonitor: stop,
09-08 18:23:44.261  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.261  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.261  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.261  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:44.261  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 18:23:44.261  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.261  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d12839b not in the list
,09-08 18:23:44.261  6147  6197 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported,
09-08 18:23:44.261  6147  6197 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:44.261  6147  6197 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 18:23:44.261  6147  6197 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:44.261  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:44.261  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.261  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.261  6147  6197 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2897dbaa not in the list
,09-08 18:23:44.261  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.261  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d12839b not in the list
09-08 18:23:44.261  6147  6197 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:44.261  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.261  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,09-08 18:23:44.261  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-08 18:23:44.261  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.261  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:44.261  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:44.261  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.261  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d12839b not in the list
,09-08 18:23:44.271  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55],
09-08 18:23:44.271  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-08 18:23:44.271  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-08 18:23:44.271  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-08 18:23:44.271  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-08 18:23:44.271  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-08 18:23:44.271  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-08 18:23:44.271  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-08 18:23:44.271  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-08 18:23:44.271  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-08 18:23:44.271  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-08 18:23:44.271  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-08 18:23:44.271  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-08 18:23:44.271  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-08 18:23:44.271  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-08 18:23:44.271  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410],
09-08 18:23:44.271  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-08 18:23:44.271  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-08 18:23:44.271  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-08 18:23:44.271  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-08 18:23:44.271  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-08 18:23:44.271  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-08 18:23:44.271  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-08 18:23:44.271  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-08 18:23:44.271  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-08 18:23:44.271  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-08 18:23:44.271  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-08 18:23:44.271  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-08 18:23:44.271  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-08 18:23:44.271  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,09-08 18:23:44.271  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-08 18:23:44.271  6147  6197 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:44.271  6147  6197 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:44.271  6147  6197 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 18:23:44.271  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:44.271  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.271  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.271  6147  6197 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2897dbaa not in the list
09-08 18:23:44.271  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 18:23:44.271  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d12839b not in the list
09-08 18:23:44.271  6147  6197 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:44.271  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.271  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.271  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:23:44.271  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.271  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:44.271  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:44.271  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.271  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d12839b not in the list
,09-08 18:23:44.271  6147  6197 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-08 18:23:44.271  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:23:44.281  6147  6197 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-08 18:23:44.281  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:44.281  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED,
09-08 18:23:44.281  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:23:44.281  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:23:44.281  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:44.281  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:23:44.281  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 18:23:44.281  6147  6197 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:44.281  6147  6197 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 18:23:44.281  6147  6197 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 18:23:44.281  6147  6197 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 18:23:44.281  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 18:23:44.281  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 18:23:44.281  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 18:23:44.281  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:44.281  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:44.281  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 18:23:44.291  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 18:23:44.291  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 18:23:44.291  6147  6197 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage,
,09-08 18:23:44.301  6147  6197 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-08 18:23:44.301  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-08 18:23:44.301  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-08 18:23:44.301  6147  6197 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-08 18:23:44.311  2649  2662 D BtGatt.GattService: registerClient() - UUID=4b4b2ecc-2123-49a3-a847-fc28a45ac02b
,09-08 18:23:44.351  2649  2717 D BtGatt.GattService: onClientRegistered() - UUID=4b4b2ecc-2123-49a3-a847-fc28a45ac02b, clientIf=6
,09-08 18:23:44.351  6147  6155 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-08 18:23:44.361  2649  2658 D BtGatt.GattService: start scan with filters
,09-08 18:23:44.361  2649  2720 D BtGatt.ScanManager: handling starting scan
,09-08 18:23:44.361  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-08 18:23:44.361  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 18:23:44.361  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 18:23:44.361  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 18:23:44.361  2649  2720 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b3ace6d
,09-08 18:23:44.371  6147  6197 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 18:23:44.371  6147  6197 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 18:23:44.371  6147  6147 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 18:23:44.371  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 18:23:44.371  2649  2717 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-08 18:23:44.381  2649  2717 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:23:44.381  2649  2720 D BtGatt.ScanManager: allow scan with filters
09-08 18:23:44.381  2649  2720 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-08 18:23:44.381  2649  2720 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-08 18:23:44.381  6147  6197 I io.jxcore.node.ConnectionHelper: start: OK
,09-08 18:23:44.391  2649  2717 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-08 18:23:44.391  2649  2717 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:23:44.391  2649  2720 D BtGatt.ScanManager: Starting BLE batch scan
,09-08 18:23:44.391  2649  2720 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-08 18:23:44.391  6147  6197 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 18:23:44.391  6147  6197 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-08 18:23:44.391  6147  6197 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 18:23:44.391  6147  6197 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 18:23:44.391  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:23:44.391  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 18:23:44.391  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 18:23:44.391  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-08 18:23:44.391  6147  6197 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-08 18:23:44.391  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-08 18:23:44.401  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 18:23:44.401  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-08 18:23:44.401  2649  2662 D BtGatt.GattService: stopScan() - queue size =1
,09-08 18:23:44.401  2649  2724 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-08 18:23:44.401  2649  2717 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-08 18:23:44.401  2649  2717 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:23:44.401  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 18:23:44.401  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 18:23:44.401  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 18:23:44.401  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 18:23:44.401  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 18:23:44.411  6147  6197 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 18:23:44.411  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-08 18:23:44.411  6147  6197 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-08 18:23:44.411  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 18:23:44.411  2649  2717 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-08 18:23:44.411  2649  2717 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:23:44.421  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:23:44.421  6147  6147 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:23:44.421  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:44.421  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.421  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:23:44.421  6147  6197 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2897dbaa not in the list
09-08 18:23:44.421  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.421  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d12839b not in the list
09-08 18:23:44.421  6147  6197 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:44.421  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.421  6147  6197 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-08 18:23:44.421  6147  6147 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:23:44.421  6147  6147 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 18:23:44.421  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:23:44.431  6147  6197 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:23:44.431  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:44.431  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:44.431  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:23:44.431  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:23:44.431  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:44.431  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:23:44.431  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 18:23:44.431  6147  6197 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 18:23:44.431  6147  6197 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 18:23:44.431  6147  6197 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 18:23:44.431  6147  6197 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 18:23:44.431  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 18:23:44.431  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 18:23:44.431  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 18:23:44.441  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:44.441  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:44.441  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 18:23:44.451  2649  2720 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 42
,09-08 18:23:44.451  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 18:23:44.451  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 18:23:44.451  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-08 18:23:44.451  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 18:23:44.451  6147  6197 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-08 18:23:44.461  2649  2658 D BtGatt.GattService: registerClient() - UUID=34bdca27-07e2-4744-a6d7-3b863fc5e944
,09-08 18:23:44.461  2649  2720 D BtGatt.ScanManager: filter size is 1
,09-08 18:23:44.461  2649  2720 D BtGatt.ScanManager: delete FilterIndex - 3
,09-08 18:23:44.461  2649  2717 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-08 18:23:44.471  2649  2717 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-08 18:23:44.471  2649  2720 D BtGatt.ScanManager: stopping BLe Batch
,09-08 18:23:44.471  2649  2717 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-08 18:23:44.471  2649  2717 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:23:44.471  2649  2720 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-08 18:23:44.481  2649  2717 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-08 18:23:44.481  2649  2717 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:23:44.501  2649  2717 D BtGatt.GattService: onClientRegistered() - UUID=34bdca27-07e2-4744-a6d7-3b863fc5e944, clientIf=6
,09-08 18:23:44.501  6147  6155 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-08 18:23:44.501  2649  2662 D BtGatt.GattService: start scan with filters
,09-08 18:23:44.501  2649  2720 D BtGatt.ScanManager: handling starting scan
,09-08 18:23:44.501  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-08 18:23:44.501  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-08 18:23:44.511  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 18:23:44.511  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 18:23:44.511  2649  2717 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-08 18:23:44.511  2649  2717 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:23:44.511  2649  2720 D BtGatt.ScanManager: allow scan with filters
,09-08 18:23:44.511  2649  2720 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-08 18:23:44.511  2649  2720 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,09-08 18:23:44.511  6147  6197 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 18:23:44.521  6147  6197 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 18:23:44.521  6147  6147 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 18:23:44.521  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 18:23:44.521   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,09-08 18:23:44.521  2649  2717 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-08 18:23:44.521  2649  2717 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:23:44.521  2649  2720 D BtGatt.ScanManager: Starting BLE batch scan
,09-08 18:23:44.521  2649  2720 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-08 18:23:44.531  6147  6197 I io.jxcore.node.ConnectionHelper: start: OK
,09-08 18:23:44.531  6147  6197 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:44.531  6147  6197 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-08 18:23:44.531  6147  6197 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:44.531  6147  6197 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 18:23:44.531  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.531  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 18:23:44.531  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 18:23:44.531  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 18:23:44.531  6147  6197 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 18:23:44.531  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 18:23:44.531  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 18:23:44.531  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-08 18:23:44.531  2649  2724 D BtGatt.GattService: stopScan() - queue size =1
,09-08 18:23:44.531  2649  2658 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-08 18:23:44.531  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 18:23:44.531  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 18:23:44.531  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 18:23:44.531  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 18:23:44.531  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 18:23:44.541  6147  6197 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 18:23:44.541  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-08 18:23:44.541  6147  6197 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-08 18:23:44.541  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 18:23:44.541  2649  2717 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-08 18:23:44.541  2649  2717 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-08 18:23:44.541  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:23:44.541  6147  6147 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 18:23:44.541  6147  6147 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 18:23:44.551  6147  6147 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 18:23:44.551  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:44.551  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.551  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:23:44.551  6147  6197 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2897dbaa not in the list
09-08 18:23:44.551  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.551  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d12839b not in the list
09-08 18:23:44.551  6147  6197 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:44.551  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.551  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.551  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:23:44.551  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 18:23:44.551  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:44.551  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.551  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d12839b not in the list
,09-08 18:23:44.551  6147  6197 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-08 18:23:44.551  2649  2717 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-08 18:23:44.551  2649  2717 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-08 18:23:44.551  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:23:44.561  6147  6197 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:23:44.561  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:44.561  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:44.561  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:23:44.561  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:23:44.561  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:44.561  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:23:44.561  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 18:23:44.571  2649  2720 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 43
,09-08 18:23:44.571  2649  2720 D BtGatt.ScanManager: filter size is 1
,09-08 18:23:44.571  2649  2720 D BtGatt.ScanManager: delete FilterIndex - 4
,09-08 18:23:44.571  2649  2717 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-08 18:23:44.571  2649  2717 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:23:44.571  2649  2720 D BtGatt.ScanManager: stopping BLe Batch
,09-08 18:23:44.571  6147  6197 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 18:23:44.571  6147  6197 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 18:23:44.581  6147  6197 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 18:23:44.581  6147  6197 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 18:23:44.581  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 18:23:44.581  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 18:23:44.581  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 18:23:44.581  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:44.581  2649  2717 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
09-08 18:23:44.581  2649  2717 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-08 18:23:44.581  2649  2720 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-08 18:23:44.581  2649  2717 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-08 18:23:44.581  2649  2717 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:23:44.581  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 18:23:44.581  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:44.591  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 18:23:44.591  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 18:23:44.591  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-08 18:23:44.591  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-08 18:23:44.591  6147  6197 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-08 18:23:44.601  2649  2658 D BtGatt.GattService: registerClient() - UUID=e4e02680-3772-46d0-ad1d-4c94f6f315b8
,09-08 18:23:44.641  2649  2717 D BtGatt.GattService: onClientRegistered() - UUID=e4e02680-3772-46d0-ad1d-4c94f6f315b8, clientIf=6
,09-08 18:23:44.641  6147  6157 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-08 18:23:44.641  2649  2662 D BtGatt.GattService: start scan with filters
,09-08 18:23:44.641  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-08 18:23:44.641  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 18:23:44.641  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 18:23:44.641  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 18:23:44.641  6147  6197 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 18:23:44.641  6147  6147 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 18:23:44.641  6147  6197 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 18:23:44.651  2649  2720 D BtGatt.ScanManager: handling starting scan
,09-08 18:23:44.651  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 18:23:44.651  6147  6197 I io.jxcore.node.ConnectionHelper: start: OK
,09-08 18:23:44.651  6147  6197 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 18:23:44.651  6147  6197 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-08 18:23:44.661  6147  6197 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 18:23:44.661  2649  2717 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-08 18:23:44.661  2649  2717 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:23:44.661  2649  2720 D BtGatt.ScanManager: allow scan with filters
09-08 18:23:44.661  2649  2720 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-08 18:23:44.661  2649  2720 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-08 18:23:44.661  6147  6197 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-08 18:23:44.661  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.661  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 18:23:44.661  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 18:23:44.661  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-08 18:23:44.661  6147  6197 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 18:23:44.661  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-08 18:23:44.661  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-08 18:23:44.661  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-08 18:23:44.661  2649  2724 D BtGatt.GattService: stopScan() - queue size =1
,09-08 18:23:44.671  2649  2717 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-08 18:23:44.671  2649  2717 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:23:44.671  2649  2658 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-08 18:23:44.671  2649  2720 D BtGatt.ScanManager: Starting BLE batch scan
,09-08 18:23:44.671  2649  2720 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-08 18:23:44.671  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-08 18:23:44.671  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-08 18:23:44.671  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 18:23:44.671  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-08 18:23:44.671  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 18:23:44.671  6147  6197 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 18:23:44.671  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-08 18:23:44.671  6147  6197 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 18:23:44.671  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 18:23:44.671  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:23:44.681  2649  2717 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-08 18:23:44.681  2649  2717 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:23:44.681  6147  6147 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:23:44.681  6147  6197 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:44.681  6147  6197 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-08 18:23:44.681  6147  6197 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:44.681  6147  6197 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:44.681  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:44.681  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.681  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:23:44.681  6147  6197 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2897dbaa not in the list
09-08 18:23:44.681  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.681  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d12839b not in the list
09-08 18:23:44.681  6147  6197 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:44.681  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:23:44.681  6147  6147 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:23:44.681  6147  6147 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 18:23:44.681  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.681  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:23:44.681  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 18:23:44.681  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:44.681  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.681  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d12839b not in the list
,09-08 18:23:44.681  6147  6197 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-08 18:23:44.681  6147  6197 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:44.681  6147  6197 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:44.681  6147  6197 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:44.681  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:44.681  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.681  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.681  6147  6197 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2897dbaa not in the list
09-08 18:23:44.681  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.681  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d12839b not in the list
09-08 18:23:44.681  6147  6197 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:44.681  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.681  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.681  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.681  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.681  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:44.681  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:44.681  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.681  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d12839b not in the list
09-08 18:23:44.681  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-08 18:23:44.681  6147  6197 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:44.681  6147  6197 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:44.681  6147  6197 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:44.681  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:44.681  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.691  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.691  6147  6197 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2897dbaa not in the l,ist
09-08 18:23:44.691  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.691  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d12839b not in the list
09-08 18:23:44.691  6147  6197 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:44.691  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.691  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.691  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.691  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.691  2649  2717 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-08 18:23:44.691  2649  2717 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-08 18:23:44.691  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:44.691  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:44.691  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.691  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d12839b not in the list
09-08 18:23:44.691  6147  6197 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-08 18:23:44.691  6147  6197 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:44.691  6147  6197 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:44.691  6147  6197 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:44.691  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:44.691  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.691  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.691  6147  6197 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2897dbaa not in the list
09-08 18:23:44.691  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.691  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d12839b not in the list
09-08 18:23:44.691  6147  6197 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:44.691  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.691  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.691  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.691  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.691  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:44.691  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:44.691  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.691  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d12839b not in the list
09-08 18:23:44.691  6147  6197 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-08 18:23:44.691  6147  6197 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:44.691  6147  6197 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:44.691  6147  6197 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:44.691  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:44.691  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.691  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.691  6147  6197 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2897dbaa not in the list
09-08 18:23:44.691  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.691  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d12839b not in the list
09-08 18:23:44.691  6147  6197 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:44.691  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.691  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.691  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.691  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.691  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:44.691  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:44.691  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.691  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d12839b not in the list
09-08 18:23:44.691  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-08 18:23:44.691  6147  6197 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 18:23:44.691  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 18:23:44.691  6147  6197 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 18:23:44.691  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-08 18:23:44.691  6147  6197 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 18:23:44.691  6147  6197 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:44.691  6147  6197 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:44.691  6147  6197 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:44.701  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:44.701  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.701  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.701  6147  6197 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2897dbaa not in the list
09-08 18:23:44.701  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.701  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d12839b not in the list
09-08 18:23:44.701  6147  6197 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:44.701  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.701  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.701  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.701  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.701  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:44.701  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:44.701  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.701  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d12839b not in the list
09-08 18:23:44.701  6147  6197 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 18:23:44.701  6147  6197 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-08 18:23:44.701  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-08 18:23:44.701  6147  6197 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 18:23:44.701  6147  6197 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-08 18:23:44.701  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-08 18:23:44.701  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-08 18:23:44.701  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-08 18:23:44.701  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-08 18:23:44.701  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-08 18:23:44.701  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-08 18:23:44.701  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-08 18:23:44.701  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-08 18:23:44.701  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-08 18:23:44.701  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-08 18:23:44.701  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-08 18:23:44.701  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-08 18:23:44.701  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-08 18:23:44.701  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-08 18:23:44.701  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-08 18:23:44.701  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-08 18:23:44.701  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-08 18:23:44.701  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-08 18:23:44.701  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-08 18:23:44.701  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-08 18:23:44.701  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-08 18:23:44.701  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-08 18:23:44.701  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-08 18:23:44.701  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-08 18:23:44.701  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-08 18:23:44.701  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-08 18:23:44.701  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-08 18:23:44.701  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-08 18:23:44.701  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-08 18:23:44.701  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-08 18:23:44.701  6147  6197 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-08 18:23:44.701  6147  6197 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 18:23:44.701  6147  6197 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-08 18:23:44.711  6147  6197 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 18:23:44.711  6147  6197 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 18:23:44.711  6147  6197 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-08 18:23:44.711  6147  6197 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 18:23:44.711  6147  6197 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 18:23:44.711  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-08 18:23:44.711  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-08 18:23:44.711  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-08 18:23:44.711  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-08 18:23:44.711  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-08 18:23:44.711  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-08 18:23:44.711  6147  6197 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-08 18:23:44.711  6147  6197 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 18:23:44.711  6147  6197 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-08 18:23:44.711  6147  6197 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:44.711  6147  6197 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:44.711  6147  6197 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:44.711  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:44.711  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.711  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.711  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-08 18:23:44.711  6147  6197 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2897dbaa not in the list
09-08 18:23:44.711  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.711  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d12839b not in the list
09-08 18:23:44.711  6147  6197 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:44.711  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.711  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.711  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.711  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.711  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:44.711  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:44.711  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.711  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d12839b not in the list
09-08 18:23:44.711  6147  6197 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-08 18:23:44.711  6147  6197 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:44.711  6147  6197 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:44.711  6147  6197 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:44.711  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:44.711  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.721  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.721  6147  6197 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2897dbaa not in the list
09-08 18:23:44.721  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.721  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d12839b not in the list
09-08 18:23:44.721  6147  6197 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:44.721  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.721  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.721  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.721  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.721  6147  6280 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1128)
09-08 18:23:44.721  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:44.721  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:44.721  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.721  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d12839b not in the list
09-08 18:23:44.721  6147  6197 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-08 18:23:44.721  6147  6197 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:44.721  6147  6281 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1128
09-08 18:23:44.721  6147  6197 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:44.721  6147  6197 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:44.721  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:44.721  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.721  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.721  6147  6197 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2897dbaa not in the list
09-08 18:23:44.721  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.721  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d12839b not in the list
09-08 18:23:44.721  6147  6197 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:44.721  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.721  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.721  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.721  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.721  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:44.721  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:44.721  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.721  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d12839b not in the list
09-08 18:23:44.721  6147  6197 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-08 18:23:44.721  6147  6197 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-08 18:23:44.721  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 18:23:44.721  6147  6197 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-08 18:23:44.721  6147  6197 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-08 18:23:44.721  6147  6197 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-08 18:23:44.721  2649  2720 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 44
09-08 18:23:44.721  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 18:23:44.721  6147  6197 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-08 18:23:44.721  6147  6197 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-08 18:23:44.721  6147  6197 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-08 18:23:44.721  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 18:23:44.721  6147  6197 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-08 18:23:44.721  6147  6197 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:44.721  6147  6197 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:44.721  6147  6197 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:44.721  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:44.721  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.721  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.721  6147  6197 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2897dbaa not in the list
09-08 18:23:44.721  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.721  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d12839b not in the list
09-08 18:23:44.721  6147  6197 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:44.721  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.721  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.721  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.721  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.721  2649  2720 D BtGatt.ScanManager: filter size is 1
09-08 18:23:44.721  2649  2720 D BtGatt.ScanManager: delete FilterIndex - 5
09-08 18:23:44.721  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:44.721  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:44.721  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.721  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d12839b not in the list
09-08 18:23:44.721  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:44.721  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.721  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.721  6147  6197 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2897dbaa not in the list
09-08 18:23:44.721  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.721  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d12839b not in the list
09-08 18:23:44.721  6147  6197 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:44.721  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.721  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.721  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.721  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d12839b not in the list
09-08 18:23:44.721  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:44.721  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.721  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.721  6147  6197 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2897dbaa not in the list
09-08 18:23:44.721  6147  6197 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:44.721  6147  6197 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:44.721  6147  6197 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:44.721  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:44.721  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.721  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.721  6147  6197 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2897dbaa not in the list
09-08 18:23:44.721  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.721  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d12839b not in the list
09-08 18:23:44.721  6147  6197 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:44.721  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.721  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.721  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.721  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.731  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:44.731  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:44.731  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.731  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d12839b not in the list
,09-08 18:23:44.731  6147  6280 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
09-08 18:23:44.731  6147  6197 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-08 18:23:44.731  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 18:23:44.731  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-08 18:23:44.731  2649  2717 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-08 18:23:44.731  2649  2717 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-08 18:23:44.731  2649  2720 D BtGatt.ScanManager: stopping BLe Batch
09-08 18:23:44.731  6147  6197 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-08 18:23:44.731  6147  6197 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-08 18:23:44.731  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-08 18:23:44.731  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 18:23:44.731  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:44.731  6147  6147 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-08 18:23:44.731  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-08 18:23:44.731  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-08 18:23:44.731  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-08 18:23:44.731  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.731  6147  6197 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-08 18:23:44.731  6147  6197 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2897dbaa not in the list
09-08 18:23:44.731  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.731  6147  6147 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-08 18:23:44.731  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 18:23:44.731  6147  6197 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 18:23:44.731  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 18:23:44.731  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.731  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.731  6147  6280 D BluetoothSocket: connect(): myUserId = 0
09-08 18:23:44.731  6147  6282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-08 18:23:44.731  6147  6280 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 18:23:44.731  6147  6282 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-08 18:23:44.731  6147  6197 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 18:23:44.731  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d12839b not in the list
09-08 18:23:44.731  6147  6197 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:44.731  6147  6197 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:44.731  6147  6197 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:44.731  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:44.731  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.731  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.731  6147  6197 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2897dbaa not in the list
09-08 18:23:44.731  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.731  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d12839b not in the list
09-08 18:23:44.731  6147  6197 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:44.731  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.731  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.731  6147  6147 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:23:44.731  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.731  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.741  2649  2662 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:23:44.741  6147  6147 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:23:44.741  6147  6147 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-08 18:23:44.741  6147  6147 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 18:23:44.741  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:44.741  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:44.741  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.741  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d12839b not in the list
09-08 18:23:44.741  6147  6197 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-08 18:23:44.741  6147  6197 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-08 18:23:44.741  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 18:23:44.741  6147  6197 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 18:23:44.741  6147  6197 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:44.741  6147  6197 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:44.741  6147  6197 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:44.741  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:44.741  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.741  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.741  6147  6197 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2897dbaa not in the list
09-08 18:23:44.741  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.741  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d12839b not in the list
09-08 18:23:44.741  6147  6197 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:44.741  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.741  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.741  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.741  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.741  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:44.741  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:44.741  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.741  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d12839b not in the list
09-08 18:23:44.751  2649  2717 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-08 18:23:44.751  2649  2717 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-08 18:23:44.751  2649  2720 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-08 18:23:44.751  6147  6280 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[109]}
09-08 18:23:44.751  6147  6197 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:44.751  6147  6197 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:44.751  6147  6197 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:44.751  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:44.751  1015  1342 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-08 18:23:44.751  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.751  1015  1342 D BatteryService: level:83, scale:100, status:2, health:2, present:true, voltage: 4086, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
09-08 18:23:44.751  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.751  1015  1342 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-08 18:23:44.751  6147  6197 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2897dbaa not in the list
09-08 18:23:44.751  1015  1342 D BatteryService: stay LED for charging
09-08 18:23:44.751  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.751  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-08 18:23:44.751  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d12839b not in the list
09-08 18:23:44.751  6147  6197 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:44.751  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.751  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.751  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.751  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.751  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:44.751  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:44.751  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.751  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d12839b not in the list
09-08 18:23:44.761  6147  6197 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:44.761  6147  6197 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:44.761  6147  6197 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:44.761  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:44.761  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.761  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.761  6147  6197 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2897dbaa not in the list
09-08 18:23:44.761  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.761  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d12839b not in the list
09-08 18:23:44.761  6147  6197 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:44.761  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.761  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.761  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:44.761  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:44.761  2649  2717 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-08 18:23:44.761  2649  2717 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-08 18:23:44.761  1015  1015 I MotionRecognitionService: Plugged
09-08 18:23:44.761  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
09-08 18:23:44.761  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:44.761  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:44.761  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:44.761  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d12839b not in the list
09-08 18:23:44.761  6147  6197 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-08 18:23:44.761  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 18:23:44.761  6147  6197 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-08 18:23:44.761  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 18:23:44.761  6147  6197 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-08 18:23:44.761  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 18:23:44.761  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-08 18:23:44.761  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-08 18:23:44.761  6147  6197 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-08 18:23:44.761  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-08 18:23:44.761  6147  6197 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-08 18:23:44.761  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-08 18:23:44.761  6147  6197 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-08 18:23:44.761  6147  6197 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-08 18:23:44.761  6147  6197 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-08 18:23:44.761  6147  6197 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-08 18:23:44.771  6147  6197 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-08 18:23:44.771  6147  6197 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-08 18:23:44.771  6147  6197 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-08 18:23:44.771  6147  6197 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-08 18:23:44.771  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:23:44.771  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@24971705 added. We now have 2 listener(s)
09-08 18:23:44.771  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-08 18:23:44.771  6147  6197 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 18:23:44.771  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-08 18:23:44.771  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-08 18:23:44.771  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 83
,09-08 18:23:44.771  6147  6197 D BluetoothAdapter: enable()
,09-08 18:23:44.781  2649  2649 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-08 18:23:44.781  2649  2722 D HeadsetStateMachine: Disconnected process message: 10
,09-08 18:23:44.781  6147  6197 D BluetoothAdapter: enable(): BT is already enabled..!
,09-08 18:23:44.781  1015  1487 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-08 18:23:44.781  1015  1487 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-08 18:23:44.781  1015  1487 D SecContentProvider2: mCursor = null
,09-08 18:23:44.781  1015  1487 D WifiService: setWifiEnabled: true pid=6147, uid=10155
,09-08 18:23:44.781  1015  1487 W ActivityManager: Permission Denial: getCurrentUser() from pid=6147, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-08 18:23:44.781  1015  1487 W WifiService: Failed getting userId using ActivityManagerNative
09-08 18:23:44.781  1015  1487 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6147, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-08 18:23:44.781  1015  1487 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-08 18:23:44.781  1015  1487 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-08 18:23:44.781  1015  1487 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-08 18:23:44.781  1015  1487 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-08 18:23:44.781  1015  1487 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-08 18:23:44.781  1015  1487 D SettingsProvider: name = wifi_on
,09-08 18:23:44.791  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 18:23:44.791  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3036835a added. We now have 3 listener(s)
09-08 18:23:44.791  6147  6197 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:23:44.791  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:83 status:2 health:2
,09-08 18:23:44.791  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:83 status:2 health:2
09-08 18:23:44.791  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:83 status:2 health:2
,09-08 18:23:44.791  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:23:44.791  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@14d7898b added. We now have 4 listener(s)
09-08 18:23:44.791  6147  6197 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:23:44.791  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 18:23:44.801  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@38301a68 added. We now have 5 listener(s)
09-08 18:23:44.801  6147  6197 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:23:44.801  1015  1028 D SecContentProvider: uri = 18 selection = isWifiEnabled,
09-08 18:23:44.801  1015  1028 D WifiService: setWifiEnabled: false pid=6147, uid=10155
09-08 18:23:44.801  1015  1028 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-08 18:23:44.801  1015  1028 D SecContentProvider2: mCursor = null
09-08 18:23:44.801  1015  1028 D SettingsProvider: name = wifi_on
,09-08 18:23:44.811  6147  6197 D BluetoothAdapter: disable()
,09-08 18:23:44.811  1015  1126 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-08 18:23:44.811  1015  3235 D SettingsProvider: name = bluetooth_on
09-08 18:23:44.811  2102  2102 I wpa_supplicant: reset timer : RESET_TIMER 0
09-08 18:23:44.811  2102  2102 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
09-08 18:23:44.811  2102  2102 I wpa_supplicant: P2P: Current p2p state = IDLE
09-08 18:23:44.811  2102  2102 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
09-08 18:23:44.821  1015  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 18:23:44.831  1015  1126 E WifiNative-wlan0: do suspend true
,09-08 18:23:44.831  2102  2102 I wpa_supplicant: Scan aborted because the firmware maybe busy.
09-08 18:23:44.831  2102  2102 I wpa_supplicant: Therefore we will repeat the scan command after 1 seconds.
,09-08 18:23:44.831  2102  2102 I wpa_supplicant: wlan0: Setting scan request: 1 sec 0 usec
,09-08 18:23:44.831  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:23:44.841  2649  2714 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
09-08 18:23:44.841  2649  2714 D BluetoothAdapterProperties: Setting state to 13
09-08 18:23:44.841  2649  2714 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-08 18:23:44.841  2649  2714 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-08 18:23:44.841  2649  2714 D BluetoothAdapterService: updateAdapterState state is 13
,09-08 18:23:44.841  1015  3003 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:23:44.841  1015  3003 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-08 18:23:44.841  1015  3003 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:44.841  1015  3003 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:44.841  1015  3003 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:44.841  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:44.841  6147  6197 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:23:44.841  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:44.841  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:44.841  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:23:44.841  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:23:44.841  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:44.841  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:23:44.841  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 18:23:44.841  2649  2649 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-08 18:23:44.841  2649  2714 D BluetoothAdapterService: Autoconnection is available 
09-08 18:23:44.841  2649  2649 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1e43a057, channel: 19, state: LISTENING
,09-08 18:23:44.841  2649  2649 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1e43a057, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1d63845f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@17eff744mSocket: android.net.LocalSocket@111b302d impl:android.net.LocalSocketImpl@10f6962 fd:FileDescriptor[74]
09-08 18:23:44.841  1015  3235 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
09-08 18:23:44.841  2649  2649 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@111b302d impl:android.net.LocalSocketImpl@10f6962 fd:FileDescriptor[74]
09-08 18:23:44.841  2649  2714 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-08 18:23:44.841  2649  2714 D BluetoothAdapterService: terminating service from this receiver
09-08 18:23:44.841  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:44.841  6147  6197 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:44.841  6147  6197 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 18:23:44.841  1015  3235 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:44.841  1015  3235 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:44.841  1015  3235 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:44.841  2649  2714 D BluetoothAdapterProperties: onBluetoothDisable()
09-08 18:23:44.841  2649  2714 D BluetoothAdapterProperties: mDiscovering is false
,09-08 18:23:44.841  1015  1138 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-08 18:23:44.841  2649  2714 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-08 18:23:44.851  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:44.851  1300  1300 D BluetoothPbap: Proxy object disconnected
,09-08 18:23:44.851  1300  1300 D PbapServerProfile: Bluetooth service disconnected
09-08 18:23:44.851  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:44.851  1015  1015 I InputMethodManagerService: [BT Setting State] State =13
,09-08 18:23:44.851  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-08 18:23:44.851  1174  1174 D BluetoothTile:  onBluetoothStateChange:
,09-08 18:23:44.861  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-08 18:23:44.861  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:44.861  1174  1702 D BluetoothTile:  handleUpdatestate:false name:null
,09-08 18:23:44.861  1174  1174 D BluetoothTile:  getBluetoothState : 13
,09-08 18:23:44.861  1174  1702 D BluetoothTile:  handleUpdatestate:false name:null
,09-08 18:23:44.861  1174  1702 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-08 18:23:44.861  1883  1883 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-08 18:23:44.861  1015  3140 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-08 18:23:44.871  1015  3223 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-08 18:23:44.871  1300  1300 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:44.871  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-08 18:23:44.881  1015  3235 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-08 18:23:44.881  1015  3235 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-08 18:23:44.881  6147  6147 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
09-08 18:23:44.881  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:44.881  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:44.881  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,09-08 18:23:44.881  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:23:44.881  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:23:44.881  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:44.881  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:23:44.881  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 18:23:44.881  1015  3235 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:44.881  1015  3235 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:44.881  1015  3235 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-08 18:23:44.881  6147  6147 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:44.881  6147  6147 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:44.881  2649  2717 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-08 18:23:44.881  2649  2717 D BluetoothAdapterProperties: Scan Mode:20
09-08 18:23:44.891  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:44.891  2649  2714 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-08 18:23:44.891  2649  2714 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,09-08 18:23:44.891  2649  2714 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,09-08 18:23:44.891  2649  2714 E bt-btif : cmd socket is not created
09-08 18:23:44.891  2649  4939 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-08 18:23:44.891  2649  2714 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-08 18:23:44.891  2649  2811 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
09-08 18:23:44.891  2649  2811 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-08 18:23:44.901  2649  2649 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3c9743b0, channel: 5, state: LISTENING
09-08 18:23:44.901  1300  1300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-08 18:23:44.901  2649  2649 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3c9743b0, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@162e7eac, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2d27a229mSocket: android.net.LocalSocket@21feb9ae impl:android.net.LocalSocketImpl@209c434f fd:FileDescriptor[76]
09-08 18:23:44.901  2649  2649 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@21feb9ae impl:android.net.LocalSocketImpl@209c434f fd:FileDescriptor[76]
09-08 18:23:44.901  2649  2811 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 18:23:44.901  2649  2811 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 18:23:44.901  2649  2811 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-08 18:23:44.901  2649  2649 I BtOppRfcommListener: stopping Accept Thread
09-08 18:23:44.901  2649  2649 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1d24eadc, channel: 12, state: LISTENING
09-08 18:23:44.901  2649  2649 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1d24eadc, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@234c5d6, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2a6f37e5mSocket: android.net.LocalSocket@1480c2ba impl:android.net.LocalSocketImpl@c03c56b fd:FileDescriptor[80]
09-08 18:23:44.901  2649  2649 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1480c2ba impl:android.net.LocalSocketImpl@c03c56b fd:FileDescriptor[80]
09-08 18:23:44.901  1015  1383 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-08 18:23:44.901  1015  1383 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-08 18:23:44.901  2649  4939 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-08 18:23:44.901  1015  1383 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:44.901  1015  1383 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:44.901  1015  1383 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-08 18:23:44.901  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:44.911  6147  6280 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@15497b26, channel: -1, state: INIT
09-08 18:23:44.911  6147  6280 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@15497b26, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@19333367, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3d207514mSocket: android.net.LocalSocket@bf621bd impl:android.net.LocalSocketImpl@2b4223b2 fd:FileDescriptor[109]
09-08 18:23:44.911  6147  6280 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@bf621bd impl:android.net.LocalSocketImpl@2b4223b2 fd:FileDescriptor[109]
,09-08 18:23:44.911  6147  6280 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1128)
,09-08 18:23:44.911  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:44.911  2649  2649 V BluetoothOppManager: cleanUp...
,09-08 18:23:44.921  1300  1300 D DockEventReceiver: finishStartingService: stopping service
,09-08 18:23:44.921  1300  1300 D BluetoothNotiBroadcastReceiver: onReceive
,09-08 18:23:44.921  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-08 18:23:44.931  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-08 18:23:44.931  1015  3224 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-08 18:23:44.931  1015  3224 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:44.931  1015  3224 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:44.931  1015  3224 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:44.931  1015  3224 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:44.941  6290  6290 E Zygote  : MountEmulatedStorage(),
09-08 18:23:44.941  6290  6290 E Zygote  : v2
09-08 18:23:44.941  6290  6290 I libpersona: KNOX_SDCARD checking this for 10003
,09-08 18:23:44.941  6290  6290 I libpersona: KNOX_SDCARD not a persona
,09-08 18:23:44.941  6290  6290 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
09-08 18:23:44.941  1015  3224 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6290 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,09-08 18:23:44.951  6290  6290 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-08 18:23:44.951  6290  6290 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-08 18:23:44.971   305   305 I art     : Explicit concurrent mark sweep GC freed 8701(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 607us total 26.595ms,
,09-08 18:23:44.981  6290  6290 D TimaKeyStoreProvider: TimaSignature is unavailable
09-08 18:23:44.981  1015  1125 D WifiP2pService: InactiveState{ what=143375 }
,09-08 18:23:44.981  1015  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
09-08 18:23:44.981  6290  6290 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:44.981   279   997 D CommandListener: Clearing all IP addresses on wlan0
09-08 18:23:44.991   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 633us total 18.164ms
09-08 18:23:44.991  1907  4582 V NativeCrypto: Read error: ssl=0xb8522f18: I/O error during system call, Connection timed out
09-08 18:23:44.991  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 18:23:44.991  1015  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 18:23:44.991  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-08 18:23:44.991  1015  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
09-08 18:23:44.991  1015  1128 E ConnectivityService: updateNetworkInfo()
09-08 18:23:44.991  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:44.991  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:44.991  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:44.991  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:23:44.991  1907  4582 V NativeCrypto: SSL shutdown failed: ssl=0xb8522f18: I/O error during system call, Broken pipe
,09-08 18:23:45.001  1907  4582 E GCM     : Wifi connection closed with errorCode 20,
09-08 18:23:45.001  1015  2232 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:45.001  1015  1138 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
09-08 18:23:45.001  1015  2232 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:45.001  1015  2232 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
,09-08 18:23:45.001  1015  2232 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:45.001  1015  2232 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,09-08 18:23:45.001  1015  2232 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-08 18:23:45.001  1015  2232 I qtaguid : Tagging socket 352 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1015, getuid(): 1000
,09-08 18:23:45.001  1015  1126 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-08 18:23:45.001  1015  1125 D WifiP2pService: InactiveState{ what=131204 }
09-08 18:23:45.001  1015  1125 D WifiP2pService: P2pEnabledState{ what=131204 }
,09-08 18:23:45.011   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 842us total 17.211ms
,09-08 18:23:45.011  1015  1125 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-08 18:23:45.011  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-08 18:23:45.021  1015  2232 I qtaguid : Untagging socket 352
,09-08 18:23:45.021  1015  2232 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-08 18:23:45.021  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 18:23:45.021  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-08 18:23:45.021  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:23:45.021  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1
09-08 18:23:45.021  1015  1149 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,09-08 18:23:45.021  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:45.021  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:45.021  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:23:45.031  1015  1015 D RttService: SCAN_AVAILABLE : 1
09-08 18:23:45.031  1015  1150 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-08 18:23:45.031  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-08 18:23:45.031  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
,09-08 18:23:45.031  1015  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-08 18:23:45.031  6290  6290 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
09-08 18:23:45.031  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-08 18:23:45.041  1015  1125 D WifiP2pService: P2pDisablingState
09-08 18:23:45.041  1015  1125 D WifiP2pService: P2pDisablingState{ what=147458 }
09-08 18:23:45.041  1015  1125 D WifiP2pService: p2p socket connection lost
,09-08 18:23:45.041  1015  1125 D WifiP2pService: P2pDisabledState
09-08 18:23:45.041  1015  1126 E WifiNative-wlan0: do suspend true
,09-08 18:23:45.041  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-08 18:23:45.041  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
09-08 18:23:45.041  1015  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false,
09-08 18:23:45.041  1015  1125 D WifiP2pService: P2pDisabledState{ what=143375 }
09-08 18:23:45.041  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-08 18:23:45.041  1015  1046 D WifiDisplayController: disconnect
09-08 18:23:45.041  1015  1046 D WifiDisplayController: updateConnection
,09-08 18:23:45.041  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-08 18:23:45.041  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-08 18:23:45.041  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
09-08 18:23:45.041  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer,
09-08 18:23:45.041  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
09-08 18:23:45.041  1015  1125 D WifiP2pService: DefaultState{ what=143375 }
09-08 18:23:45.041  1015  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-08 18:23:45.051  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 18:23:45.051  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-08 18:23:45.051  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:45.051  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:45.051  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:45.051  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:45.051  1174  1174 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-08 18:23:45.051  1015  3224 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-08 18:23:45.051  1174  1174 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-08 18:23:45.061   279   997 D CommandListener: Clearing all IP addresses on wlan0
09-08 18:23:45.061   279   993 D EnterpriseController: uids 1000
09-08 18:23:45.061   279   993 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-08 18:23:45.061   279   993 D Netd    : getNetworkForDns: using netid 0 for uid 1000
09-08 18:23:45.061  1015  1128 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-08 18:23:45.061  1015  1128 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
09-08 18:23:45.061  1174  1695 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-08 18:23:45.071  1015  1128 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 18:23:45.071  1015  1125 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-08 18:23:45.071  3786  6209 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-08 18:23:45.071  1015  1128 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
09-08 18:23:45.071  1015  1128 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,09-08 18:23:45.071  1015  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-08 18:23:45.071  1015  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-08 18:23:45.071  1452  1452 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-08 18:23:45.071  1452  1452 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 18:23:45.071  6290  6290 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
09-08 18:23:45.071  1015  2232 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
09-08 18:23:45.071  1015  2232 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-08 18:23:45.071  1015  2232 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:45.071  6290  6290 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-08 18:23:45.071  6290  6290 D UserAnalysis: Create SecureDbHelper
,09-08 18:23:45.071  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-08 18:23:45.071  2102  2102 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-08 18:23:45.081  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 18:23:45.081  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-08 18:23:45.081  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:45.081  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:45.081  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:45.081  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:23:45.081  1015  1128 D ConnectivityService: nai.networkMonitor.doQuit()
09-08 18:23:45.081  1015  1128 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-08 18:23:45.081  1015  1128 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-08 18:23:45.081  1015  1128 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 18:23:45.081  1015  1128 E ConnectivityService: updateNetworkInfo()
09-08 18:23:45.081  1015  1128 E ConnectivityService: updateNetworkInfo()
,09-08 18:23:45.081  1015  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-08 18:23:45.091  6290  6290 D IntelligenceServiceApplication: onCreate()
,09-08 18:23:45.091  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-08 18:23:45.091  1015  1126 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-08 18:23:45.091  1015  1129 D Tethering: MasterInitialState.processMessage what=3
,09-08 18:23:45.091  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:23:45.091  1015  1123 V NetworkStats: updateIfacesLocked()
09-08 18:23:45.091  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
,09-08 18:23:45.091  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-08 18:23:45.091  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-08 18:23:45.091  1174  1174 D StatusBar.NetworkController: EthernetConnected: false
09-08 18:23:45.091  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-08 18:23:45.091  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-08 18:23:45.091  1174  1174 D StatusBar.NetworkController: updateDataNetType()
09-08 18:23:45.091  1174  1174 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-08 18:23:45.091  1174  1174 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-08 18:23:45.091  1015  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-08 18:23:45.091  1015  1126 D SecContentProvider2: mCursor = null
,09-08 18:23:45.091  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:23:45.091  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:23:45.091  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:23:45.091  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:23:45.091  1015  1124 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-08 18:23:45.091  2649  2811 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 18:23:45.091  2649  2811 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 18:23:45.091  2649  2811 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-08 18:23:45.091  2649  2811 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 18:23:45.091  2649  2811 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 18:23:45.101  2649  2811 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-08 18:23:45.101  2649  2811 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 18:23:45.101  2649  2811 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 18:23:45.101  2649  2811 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-08 18:23:45.101  2649  2811 W bt-btif : ag scb idx 1 not allocated
09-08 18:23:45.101  2649  2811 W bt-btif : ag scb idx 2 not allocated
,09-08 18:23:45.101  1174  1174 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-08 18:23:45.101  2649  2811 E bt-btif : btif_mce_execute_service enable:0
09-08 18:23:45.101  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-08 18:23:45.101  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-08 18:23:45.101  6290  6290 D IntelligenceServiceApplication: no applications having user consent for prediction
09-08 18:23:45.101  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 18:23:45.101  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-08 18:23:45.101  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:45.101  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:45.101  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:45.101  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:45.101  2649  2861 I bt_userial_mct: exiting userial_read_thread
09-08 18:23:45.101  2649  2861 D bt_userial_mct: Leaving userial_evt_read_thread()
09-08 18:23:45.101  2649  2717 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-08 18:23:45.101  2649  2813 I bt_vendor: hw_epilog_process
09-08 18:23:45.101  2649  2717 D bt_userial_mct: userial_close
09-08 18:23:45.101  2649  2717 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-08 18:23:45.101  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:23:45.101  1015  1123 V NetworkStats: performPollLocked() took 13ms
,09-08 18:23:45.101  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 18:23:45.101  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-08 18:23:45.101  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:45.101  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:45.101  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:45.101  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:45.101  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-08 18:23:45.101  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,09-08 18:23:45.101  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-08 18:23:45.101  1174  1702 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-08 18:23:45.101  1174  1174 D HotspotTile: onReceive : 0, 0
,09-08 18:23:45.101  1300  1300 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-08 18:23:45.111  6147  6147 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:45.111  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:45.111  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:45.111  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:45.111  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:23:45.111  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:23:45.111  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:23:45.111  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:23:45.111  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 18:23:45.111  6147  6147 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:45.111  6147  6147 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 18:23:45.111  1015  3238 I ActivityManager: Killing 5306:com.google.android.talk/u0a104 (adj 15): empty #31
,09-08 18:23:45.111  6147  6147 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:45.111  1015  1138 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
09-08 18:23:45.111  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:45.111  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:45.111  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:45.111  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:23:45.111  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:23:45.111  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:23:45.111  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:23:45.111  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 18:23:45.111  6147  6147 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:45.111  6147  6147 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 18:23:45.111  6290  6290 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,09-08 18:23:45.121  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:23:45.121  1015  3238 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
09-08 18:23:45.121  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:23:45.121  1015  3238 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:45.121  1015  3238 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:45.121  1015  3238 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:45.121  1015  3238 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:45.121  6290  6290 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-08 18:23:45.141  6316  6316 E Zygote  : MountEmulatedStorage(),
09-08 18:23:45.141  6316  6316 I libpersona: KNOX_SDCARD checking this for 10107
09-08 18:23:45.141  6316  6316 E Zygote  : v2
09-08 18:23:45.141  6316  6316 I libpersona: KNOX_SDCARD not a persona
,09-08 18:23:45.141  1015  3238 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6316 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
09-08 18:23:45.141  6316  6316 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-08 18:23:45.151  6316  6316 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-08 18:23:45.151  6316  6316 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-08 18:23:45.171  6316  6316 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:45.171  6316  6316 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:45.191  2102  2102 I wpa_supplicant: Blacklist: Clear (all) 
,09-08 18:23:45.211  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-08 18:23:45.221  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-08 18:23:45.221  2102  2102 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-08 18:23:45.221  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-08 18:23:45.221  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
09-08 18:23:45.221  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,09-08 18:23:45.221  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-08 18:23:45.221  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-08 18:23:45.221  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-08 18:23:45.221  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-08 18:23:45.221  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-08 18:23:45.231  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-08 18:23:45.231  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-08 18:23:45.231  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-08 18:23:45.231  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-08 18:23:45.231  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-08 18:23:45.231  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-08 18:23:45.231  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-08 18:23:45.231  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-08 18:23:45.231  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-08 18:23:45.231  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-08 18:23:45.241  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
09-08 18:23:45.241  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-08 18:23:45.241  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
09-08 18:23:45.241  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-08 18:23:45.241  6147  6147 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-08 18:23:45.241  2102  2102 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,09-08 18:23:45.241  2102  2102 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-08 18:23:45.241  2102  2102 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
,09-08 18:23:45.241  2102  2102 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-08 18:23:45.241  2102  2102 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
09-08 18:23:45.241  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-08 18:23:45.241  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-08 18:23:45.241  1015  1043 D Tethering: interfaceStatusChanged wlan0, false,
09-08 18:23:45.241  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-08 18:23:45.241  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-08 18:23:45.241  1015  1129 D Tethering: InitialState.processMessage what=4
,09-08 18:23:45.241  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
09-08 18:23:45.241  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-08 18:23:45.241  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-08 18:23:45.241  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-08 18:23:45.241  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,09-08 18:23:45.241  1015  1129 E Tethering: No numeric data
09-08 18:23:45.251  1015  1126 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
09-08 18:23:45.241  1015  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-08 18:23:45.251  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-08 18:23:45.251  1015  1129 D Tethering: clearTetheredNotification()
09-08 18:23:45.251  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
09-08 18:23:45.251  1015  1043 D Tethering: interfaceStatusChanged wlan0, false,
09-08 18:23:45.251  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
09-08 18:23:45.251  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:23:45.251  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-08 18:23:45.251  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-08 18:23:45.251  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-08 18:23:45.251  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-08 18:23:45.251  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-08 18:23:45.251  1174  1174 D HotspotTile: updateTetherState():false, false
,09-08 18:23:45.251  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-08 18:23:45.251  1015  1123 V NetworkStats: performPollLocked() took 4ms
09-08 18:23:45.251  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:23:45.251  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-08 18:23:45.251  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:23:45.251  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:23:45.251  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-08 18:23:45.291  1015  1048 I PowerManagerService: [PWL] Off : 50s ago
,09-08 18:23:45.291  1015  1048 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
09-08 18:23:45.291  1015  1048 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
09-08 18:23:45.291  1015  1048 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=2649, ws=null) (elapsedTime=921)
09-08 18:23:45.291  1015  1048 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1015, ws=null) (elapsedTime=205)
,09-08 18:23:45.301   271   271 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb84b27c8
09-08 18:23:45.301   271   271 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
,09-08 18:23:45.301   271   271 I rmt_storage: wakelock acquired: 1, error no: 42
09-08 18:23:45.301   271   324 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1203033976)
,09-08 18:23:45.321  2649  2717 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-08 18:23:45.321  2649  2717 I bt_vendor: bluetooth satus is on
09-08 18:23:45.321  2649  2717 I bt_vendor: bt-vendor : resetting BT status
09-08 18:23:45.321  2649  2717 I bt_vendor: Starting hciattach daemon
09-08 18:23:45.321  2649  2717 I bt_vendor: try to set false
,09-08 18:23:45.321  2649  2717 I bt_vendor: Starting hciattach daemon
,09-08 18:23:45.321  2649  2717 I bt_vendor: try to set false
,09-08 18:23:45.321  2649  2717 I bt_vendor: cleanup,
,09-08 18:23:45.321  2649  2811 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-08 18:23:45.321  2649  2717 I GKI_LINUX: GKI_exit_task 0 done
09-08 18:23:45.321  2649  2717 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated,
,09-08 18:23:45.321  2649  2714 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-08 18:23:45.321  2649  2714 D BtConfig.SecureMode: isSecureModeOn:false
09-08 18:23:45.321  2649  2714 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-08 18:23:45.321  2649  2714 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-08 18:23:45.321  2649  2714 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-08 18:23:45.331  2649  2714 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService,
,09-08 18:23:45.331  1015  1342 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-08 18:23:45.331  1015  1342 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:45.331  1015  1342 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
09-08 18:23:45.331  1015  1342 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:45.331  1015  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-08 18:23:45.331  2649  2714 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-08 18:23:45.331  2649  2714 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-08 18:23:45.331  2649  2714 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-08 18:23:45.331  2649  2649 D BtGatt.DebugUtils: handleDebugAction() action=null
09-08 18:23:45.331  2649  2649 D BtGatt.GattService: Received stop request...Stopping profile...
09-08 18:23:45.331  1015  1251 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:23:45.331  1015  1251 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-08 18:23:45.331  2649  2649 D BtGatt.GattService: stop()
09-08 18:23:45.331  1015  1251 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:45.331  1015  1251 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:45.331  1015  1251 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-08 18:23:45.331  2649  2649 D BtGatt.AdvertiseManager: advertise clients cleared
09-08 18:23:45.331  2649  2714 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-08 18:23:45.331  2649  2714 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-08 18:23:45.331  2649  2714 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
09-08 18:23:45.331  1015  1251 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:23:45.331  1015  1251 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-08 18:23:45.331  1015  1251 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:45.331  1015  1251 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 18:23:45.331  1015  1251 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:45.341  2649  2649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b3ace6d
09-08 18:23:45.341  2649  2714 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-08 18:23:45.341  2649  2714 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-08 18:23:45.341  2649  2714 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-08 18:23:45.341  2649  2649 D HeadsetService: Received stop request...Stopping profile...
09-08 18:23:45.341  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:23:45.341  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-08 18:23:45.341  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:45.341  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:45.341  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:45.341  2649  2649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b3ace6d
,09-08 18:23:45.341  2649  2714 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-08 18:23:45.341  2649  2714 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-08 18:23:45.341  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-08 18:23:45.341  2649  2714 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-08 18:23:45.341   271   324 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
09-08 18:23:45.341  1015  3238 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:23:45.341   271   324 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
09-08 18:23:45.341  1015  3238 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
09-08 18:23:45.341   271   324 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1203033976) wakelock released: 1, error no: 0
09-08 18:23:45.341   271   324 I rmt_storage: 
09-08 18:23:45.341  1015  3238 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:45.341  1015  3238 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:45.341  1015  3238 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-08 18:23:45.341   271   271 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb84b27c8
,09-08 18:23:45.351  2649  2714 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-08 18:23:45.351  1015  3235 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:23:45.351  2649  2714 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-08 18:23:45.351  1015  3235 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-08 18:23:45.351  2649  2714 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
09-08 18:23:45.351  1300  1300 D HeadsetProfile: Bluetooth service disconnected
09-08 18:23:45.351  1015  3235 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:45.351  1015  3235 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:45.351  1015  3235 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-08 18:23:45.351  2649  2714 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-08 18:23:45.351  2649  2714 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-08 18:23:45.351  2649  2714 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
09-08 18:23:45.351  1015  3003 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:23:45.351  1015  3003 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-08 18:23:45.351  1015  3003 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:45.351  1015  3003 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:45.351  1015  3003 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-08 18:23:45.351  2649  2714 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-08 18:23:45.351  2649  2714 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-08 18:23:45.351  2649  2714 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
09-08 18:23:45.351  1015  3238 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:23:45.351  1015  3238 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-08 18:23:45.361  1015  3238 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:45.361  1015  3238 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:45.361  1015  3238 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:45.361  2649  2714 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-08 18:23:45.361  2649  2714 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-08 18:23:45.361  2649  2714 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-08 18:23:45.361  2649  2714 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-08 18:23:45.361  2649  2714 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-08 18:23:45.361  2649  2714 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-08 18:23:45.361  2649  2714 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-08 18:23:45.361  2649  2714 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-08 18:23:45.361  2649  2714 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-08 18:23:45.361  2649  2714 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-08 18:23:45.361  2649  2714 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-08 18:23:45.361  2649  2714 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-08 18:23:45.361  2649  2714 D BluetoothAdapterState: Stopping profile services that were post enabled
09-08 18:23:45.361  2649  2649 E BluetoothAdapterService(456838765): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
09-08 18:23:45.361  2649  2649 D A2dpService: Received stop request...Stopping profile...
,09-08 18:23:45.361  2649  2730 D A2dpStateMachine: Exit Disconnected: -1
,09-08 18:23:45.361  2649  2649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b3ace6d
,09-08 18:23:45.361  2865  2865 D BluetoothA2dp: Proxy object disconnected
09-08 18:23:45.361  2649  2649 E BluetoothAdapterService(456838765): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-08 18:23:45.361  2649  2649 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-08 18:23:45.361  2649  2649 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-08 18:23:45.361  1015  1015 D BluetoothA2dp: Proxy object disconnected
09-08 18:23:45.361  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-08 18:23:45.371  2649  2649 D HidService: Received stop request...Stopping profile...
09-08 18:23:45.371  2649  2649 D HidService: Stopping Bluetooth HidService
09-08 18:23:45.371  2649  2649 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-08 18:23:45.371  2649  2649 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-08 18:23:45.371  2649  2649 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-08 18:23:45.371  1300  1300 D BluetoothA2dp: Proxy object disconnected
09-08 18:23:45.371  1300  1300 D A2dpProfile: Bluetooth service disconnected
,09-08 18:23:45.371  2649  2649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b3ace6d,
09-08 18:23:45.371  1300  1300 D BluetoothInputDevice: Proxy object disconnected
09-08 18:23:45.371  1300  1300 D HidProfile: Bluetooth service disconnected
,09-08 18:23:45.371  2649  2649 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-08 18:23:45.371  2649  2649 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-08 18:23:45.371  2649  2649 D HealthService: Received stop request...Stopping profile...
,09-08 18:23:45.371  2649  2649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b3ace6d
,09-08 18:23:45.371  2649  2649 D PanService: Received stop request...Stopping profile...
09-08 18:23:45.371  2649  2649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b3ace6d
,09-08 18:23:45.381  1015  1015 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-08 18:23:45.381  2649  2649 D BluetoothMapService: Received stop request...Stopping profile...
,09-08 18:23:45.381  1300  1300 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-08 18:23:45.381  1300  1300 D PanProfile: Bluetooth service disconnected
,09-08 18:23:45.381  2649  2649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b3ace6d
,09-08 18:23:45.381  2649  2649 D SapService: Received stop request...Stopping profile...
09-08 18:23:45.381  1300  1300 D BluetoothMap: Proxy object disconnected
09-08 18:23:45.381  1300  1300 D MapProfile: Bluetooth service disconnected
,09-08 18:23:45.381  2649  2649 D SapService: Stopping Bluetooth SapService,
09-08 18:23:45.381  2649  2649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b3ace6d
,09-08 18:23:45.391  2649  2649 E BluetoothAdapterService(456838765): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true,
09-08 18:23:45.391  2649  2649 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-08 18:23:45.391  1300  1300 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-08 18:23:45.391  1300  1300 D SapProfile: Bluetooth service disconnected
09-08 18:23:45.391  2649  2649 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-08 18:23:45.391  2649  2649 D BluetoothA2dp: Proxy object disconnected
09-08 18:23:45.391  2649  2649 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-08 18:23:45.391  2649  2733 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-08 18:23:45.391  2649  2649 I GKI_LINUX: GKI_exit_task 2 done
09-08 18:23:45.391  2649  2649 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-08 18:23:45.391  2649  2649 E BluetoothAdapterService(456838765): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-08 18:23:45.391  2649  2649 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-08 18:23:45.391  2649  2649 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-08 18:23:45.391  2649  2649 E BluetoothAdapterService(456838765): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-08 18:23:45.391  2649  2649 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-08 18:23:45.391  2649  2649 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-08 18:23:45.391  2649  2649 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-08 18:23:45.391  2649  2649 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-08 18:23:45.391  2649  2649 E BluetoothAdapterService(456838765): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-08 18:23:45.391  2649  2649 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-08 18:23:45.391  2649  2649 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-08 18:23:45.391  2649  2649 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-08 18:23:45.391  2649  2649 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-08 18:23:45.391  2649  2649 E BluetoothAdapterService(456838765): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-08 18:23:45.391  2649  2649 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-08 18:23:45.391  2649  2649 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
09-08 18:23:45.391  2649  2649 E BluetoothAdapterService(456838765): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-08 18:23:45.391  2649  2649 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-08 18:23:45.391  2649  2649 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
09-08 18:23:45.391  2649  2714 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
09-08 18:23:45.391  2649  2714 D BluetoothAdapterProperties: Setting state to 10
09-08 18:23:45.391  2649  2714 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-08 18:23:45.391  2649  2714 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-08 18:23:45.391  2649  2714 D BluetoothAdapterService: updateAdapterState state is 10
09-08 18:23:45.391  1015  1045 D BluetoothAdapter: onBluetoothStateChange: up=false
09-08 18:23:45.391  1015  1045 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-08 18:23:45.391  2649  2714 D BluetoothAdapterService: Autoconnection is available 
09-08 18:23:45.391  2649  2714 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-08 18:23:45.391  2649  2714 I BluetoothAdapterState: Entering OffState
,09-08 18:23:45.401  2865  2876 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-08 18:23:45.401  1300  1311 D BluetoothAdapter: onBluetoothStateChange: up=false
09-08 18:23:45.401  1300  1311 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-08 18:23:45.401  1015  1045 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-08 18:23:45.401  1439  1450 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-08 18:23:45.401  1439  1450 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-08 18:23:45.411  1300  1311 D Bluetoothsap: onBluetoothStateChange: up=false
09-08 18:23:45.411  1300  1311 D Bluetoothsap: Unbinding service...
09-08 18:23:45.411  2102  2102 I wpa_supplicant: Blacklist: Clear (all) 
,09-08 18:23:45.411  6147  6157 D BluetoothAdapter: onBluetoothStateChange: up=false
09-08 18:23:45.411  6147  6157 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-08 18:23:45.411  6147  6157 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-08 18:23:45.411  6147  6157 D BluetoothLeAdvertiser: Exit stop advertising
09-08 18:23:45.411  6147  6157 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-08 18:23:45.411  6147  6157 D BluetoothLeScanner: Exiting stopAllScan
,09-08 18:23:45.411  2649  2662 D BluetoothAdapter: onBluetoothStateChange: up=false
09-08 18:23:45.411  2649  2662 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-08 18:23:45.411  1452  1785 D BluetoothAdapter: onBluetoothStateChange: up=false
09-08 18:23:45.411  1452  1785 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-08 18:23:45.411  1300  1311 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-08 18:23:45.411  1300  1317 D BluetoothPbap: onBluetoothStateChange: up=false
09-08 18:23:45.411  1174  1193 D BluetoothAdapter: onBluetoothStateChange: up=false
09-08 18:23:45.411  1174  1193 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-08 18:23:45.411  2865  2895 D BluetoothAdapter: onBluetoothStateChange: up=false
09-08 18:23:45.411  2865  2895 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-08 18:23:45.411  1431  6352 D BluetoothAdapter: onBluetoothStateChange: up=false
09-08 18:23:45.411  1431  6352 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-08 18:23:45.411  2649  2724 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-08 18:23:45.421  1300  1311 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-08 18:23:45.421  1907  1917 D BluetoothAdapter: onBluetoothStateChange: up=false
09-08 18:23:45.421  1907  1917 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-08 18:23:45.421  1300  1317 D BluetoothMap: onBluetoothStateChange: up=false
,09-08 18:23:45.421  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-08 18:23:45.421  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-08 18:23:45.431  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:45.431  1015  1015 I InputMethodManagerService: [BT Setting State] State =10
09-08 18:23:45.431  1015  1015 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-08 18:23:45.431  2649  2717 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-08 18:23:45.431  2649  2649 I GKI_LINUX: GKI_exit_task 1 done
09-08 18:23:45.431  2649  2649 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,09-08 18:23:45.431  2649  2649 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-08 18:23:45.441  1174  1174 D BluetoothAdapter: 460716354: getState() :  mService = null. Returning STATE_OFF
,09-08 18:23:45.441  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-08 18:23:45.441  1174  1702 D BluetoothAdapter: 460716354: getState() :  mService = null. Returning STATE_OFF
,09-08 18:23:45.441  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-08 18:23:45.441  1174  1174 D BluetoothTile:  getBluetoothState : 10
09-08 18:23:45.441  1174  1702 D BluetoothAdapter: 460716354: getState() :  mService = null. Returning STATE_OFF
09-08 18:23:45.441  1015  1564 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-08 18:23:45.441  1174  1174 D BluetoothAdapter: 460716354: getState() :  mService = null. Returning STATE_OFF
09-08 18:23:45.441  1015  3003 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-08 18:23:45.441  1174  1174 D BluetoothAdapter: 460716354: getState() :  mService = null. Returning STATE_OFF,
09-08 18:23:45.441  2649  2649 I art     : System.exit called, status: 0
09-08 18:23:45.441  2649  2649 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-08 18:23:45.441  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-08 18:23:45.441  1883  1883 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-08 18:23:45.451  1907  2121 D BluetoothAdapter: 117873335: getState() :  mService = null. Returning STATE_OFF
09-08 18:23:45.451  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-08 18:23:45.451  1907  2121 D BluetoothAdapter: 117873335: getState() :  mService = null. Returning STATE_OFF
09-08 18:23:45.451  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-08 18:23:45.451  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
09-08 18:23:45.451  2102  2102 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-08 18:23:45.451  1300  1300 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-08 18:23:45.451  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:45.451  1015  3235 D ActivityManager: bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
09-08 18:23:45.451  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:45.451  1015  3235 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
09-08 18:23:45.451  1015  3235 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:45.451  1015  3235 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:45.451  1015  3235 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-08 18:23:45.461  1015  1494 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-08 18:23:45.461  1015  1494 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
09-08 18:23:45.461  1015  1494 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:45.461  1015  1494 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:45.461  1015  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:45.461  1015  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
09-08 18:23:45.461  1015  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
09-08 18:23:45.461  1015  1126 E WifiConfigStore: setLastSelectedConfiguration -1
,09-08 18:23:45.471  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 18:23:45.471  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-08 18:23:45.471  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:45.471  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:45.471  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:45.471  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:23:45.471  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-08 18:23:45.471  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,09-08 18:23:45.471  1174  1702 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-08 18:23:45.471  1907  2121 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
09-08 18:23:45.471  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-08 18:23:45.471  1300  1300 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-08 18:23:45.481  1174  1174 D HotspotTile: onReceive : 1, 0
,09-08 18:23:45.481  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:45.481  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:45.481  1015  2723 D SSRM:n  : SIOP:: AP = 360
,09-08 18:23:45.501  6316  6316 D StrictMode: StrictMode policy violation; ~duration=259 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-08 18:23:45.501  6316  6316 D StrictMode: StrictMode policy violation; ~duration=250 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.g,mm.base.app.a.a(PG:1211)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-08 18:23:45.501  6316  6316 D StrictMode: StrictMode policy violation; ~duration=205 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at java.io.File.exists(File.java:363)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.ActivityTh,read.main(ActivityThread.java:6145)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-08 18:23:45.501  6316  6316 D StrictMode: StrictMode policy violation; ~duration=205 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-08 18:23:45.501  6316  6316 D StrictMode: StrictMode policy violation; ~duration=203 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-08 18:23:45.501  6316  6316 D StrictMode: StrictMode policy violation; ~duration=201 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.r.k.c(PG:1187)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.r.v.a(PG:1206)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.r.y.a(PG:2233)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.r.e.b(PG:170)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.r.e.b(PG:13188)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-08 18:23:45.501  6316  6316 D StrictMode: StrictMode policy violation; ~duration=183 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.r.k.c(PG:1187)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.r.k.b(PG:14147)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.r.k.c(PG:583)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.r.v.a(PG:1206)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.r.y.a(PG:2233)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.r.e.b(PG:170)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.r.e.b(PG:13188)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-08 18:23:45.501  6316  6316 D StrictMode: StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at java.io.File.exists(File.java:363)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-08 18:23:45.501  6316  6316 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-08 18:23:45.501  1015  1342 I ActivityManager: Killing 4985:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
09-08 18:23:45.521  1907  1907 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
09-08 18:23:45.521  1907  1907 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
09-08 18:23:45.521   315   315 I ServiceManager: Waiting for service AtCmdFwd...
09-08 18:23:45.521  1015  1494 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-08 18:23:45.531  1015  1494 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-08 18:23:45.531  1015  1494 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:45.531  1015  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:45.531  1015  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-08 18:23:45.531  3600  3600 I Hs20UtilService: Starting #8
09-08 18:23:45.531  3600  3625 I Hs20UtilService: Message received 5007
09-08 18:23:45.531  1300  1300 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-08 18:23:45.531  1300  1300 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-08 18:23:45.531  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-08 18:23:45.531  1015  1383 I ActivityManager: Process com.android.bluetooth (pid 2649)(adj 0) has died(47,1085)
09-08 18:23:45.531  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-08 18:23:45.531  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-08 18:23:45.531  1300  1300 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-08 18:23:45.541  1300  3096 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-08 18:23:45.541  1300  1300 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-08 18:23:45.541  1300  1300 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-08 18:23:45.541  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-08 18:23:45.541  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-08 18:23:45.551  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-08 18:23:45.551  1300  1300 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-08 18:23:45.551  1300  3096 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-08 18:23:45.551  1015  3223 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
09-08 18:23:45.551  1015  3223 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:45.551  1015  3223 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:45.551  1015  3223 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:45.551  1015  3223 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:45.561  6362  6362 E Zygote  : MountEmulatedStorage()
09-08 18:23:45.561  6362  6362 E Zygote  : v2
09-08 18:23:45.561  6362  6362 I libpersona: KNOX_SDCARD checking this for 10068
09-08 18:23:45.561  6362  6362 I libpersona: KNOX_SDCARD not a persona
09-08 18:23:45.561  6362  6362 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-08 18:23:45.561  6316  6349 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
09-08 18:23:45.561  1015  3223 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6362 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-08 18:23:45.571  6362  6362 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-08 18:23:45.571  6362  6362 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-08 18:23:45.581  1015  3238 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-08 18:23:45.581  1015  3238 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:45.581  1015  3238 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:45.581  1015  3238 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-08 18:23:45.581  1015  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 18:23:45.591  1015  1015 I ApplicationPolicy: updateDataUsageMap
,09-08 18:23:45.601  1015  1040 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-08 18:23:45.601  6362  6362 D TimaKeyStoreProvider: TimaSignature is unavailable
09-08 18:23:45.601  6362  6362 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:45.611  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-08 18:23:45.611  3201  3201 I DBG_DM  : [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,09-08 18:23:45.621  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:45.621  6362  6362 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-08 18:23:45.621  3201  3201 I DBG_DM  : [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,09-08 18:23:45.651  6362  6362 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-08 18:23:45.651  6362  6362 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-08 18:23:45.681  1907  2111 I art     : Explicit concurrent mark sweep GC freed 60853(3MB) AllocSpace objects, 74(3MB) LOS objects, 40% free, 14MB/24MB, paused 1.376ms total 87.577ms
,09-08 18:23:45.681  6362  6362 D FileShare-Client: Outbound.stopDelayTimer - 
,09-08 18:23:45.691  1015  1487 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,09-08 18:23:45.691  1015  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:45.691  1015  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:45.691  1015  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:45.691  1015  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:45.701  1015  1487 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6377 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-08 18:23:45.701  6377  6377 E Zygote  : MountEmulatedStorage()
09-08 18:23:45.701  6377  6377 I libpersona: KNOX_SDCARD checking this for 10069
09-08 18:23:45.701  6377  6377 E Zygote  : v2
09-08 18:23:45.701  6377  6377 I libpersona: KNOX_SDCARD not a persona
,09-08 18:23:45.701  6377  6377 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-08 18:23:45.711  6377  6377 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-08 18:23:45.711  6377  6377 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-08 18:23:45.711  1015  1487 I ActivityManager: Killing 5437:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,09-08 18:23:45.731  6377  6377 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:45.731  6377  6377 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:45.751  6377  6377 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-08 18:23:45.751  1015  1487 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:45.761  1015  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:45.761  1015  1487 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
09-08 18:23:45.761  1015  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,09-08 18:23:45.761  1015  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:45.761  1015  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:45.761  1015  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:45.761  1015  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:45.771  6392  6392 E Zygote  : MountEmulatedStorage()
,09-08 18:23:45.771  1015  1487 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6392 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a,
09-08 18:23:45.771  6392  6392 E Zygote  : v2
09-08 18:23:45.771  6392  6392 I libpersona: KNOX_SDCARD checking this for 10104
09-08 18:23:45.771  6392  6392 I libpersona: KNOX_SDCARD not a persona,
09-08 18:23:45.771  1015  1487 I ActivityManager: Killing 5741:com.sec.pcw.device/1000 (adj 15): empty #31
,09-08 18:23:45.771  6392  6392 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-08 18:23:45.781  6392  6392 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-08 18:23:45.781  6392  6392 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-08 18:23:45.801  6392  6392 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:45.801  6392  6392 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:45.811  6392  6392 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-08 18:23:45.981  6392  6415 I Babel   : MmsConfig: mnc/mcc: 0/0
,09-08 18:23:45.981  6392  6415 I Babel   : MmsConfig.loadMmsSettings
,09-08 18:23:45.981  6392  6415 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
09-08 18:23:45.981  6392  6415 I Babel   : MmsConfig.loadFromDatabase
,09-08 18:23:45.991  6392  6415 E Babel   : canonicalizeMccMnc: invalid mccmnc 
,09-08 18:23:45.991  6392  6415 I Babel   : MmsConfig.loadFromResources
,09-08 18:23:46.001  6392  6415 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,09-08 18:23:46.001  6392  6415 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,09-08 18:23:46.001  1015  1342 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,09-08 18:23:46.001  1015  1342 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,09-08 18:23:46.001  1015  1342 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:46.001  1015  1342 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:46.001  1015  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-08 18:23:46.011  6392  6392 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 18:23:46.021  1015  1043 D Tethering: interfaceRemoved wlan0
,09-08 18:23:46.021  1015  1043 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-08 18:23:46.041  6392  6392 I Babel_StickerModule: App launched.
,09-08 18:23:46.051  1015  3003 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-08 18:23:46.051  1015  3003 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-08 18:23:46.051  1015  3003 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:46.061  1015  3003 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:46.061  1015  3003 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-08 18:23:46.061  1300  1300 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-08 18:23:46.061  3600  3600 I Hs20UtilService: Starting #9
,09-08 18:23:46.061  1300  1300 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-08 18:23:46.061  3600  3625 I Hs20UtilService: Message received 5007
,09-08 18:23:46.061  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-08 18:23:46.061  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-08 18:23:46.061  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-08 18:23:46.061  1300  1300 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-08 18:23:46.061  1300  3096 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-08 18:23:46.071  1015  1251 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-08 18:23:46.071   284   284 W QCamera2Factory: getCameraInfo: E, camera_id = 0
09-08 18:23:46.071  1015  1251 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-08 18:23:46.071   284   284 W QCamera2Factory: getCameraInfo: X
,09-08 18:23:46.071  1015  1251 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:46.071  1015  1251 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:46.071  1015  1251 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-08 18:23:46.071   284   720 W QCamera2Factory: getCameraInfo: E, camera_id = 1
09-08 18:23:46.071   284   720 W QCamera2Factory: getCameraInfo: X
,09-08 18:23:46.071  3600  3600 I Hs20UtilService: Starting #10
,09-08 18:23:46.071  3600  3625 I Hs20UtilService: Message received 5011
09-08 18:23:46.071  1015  3238 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,09-08 18:23:46.081  1015  3238 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:46.081  1015  3238 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:46.081  1015  3238 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:46.081  1015  3238 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:46.091  6417  6417 E Zygote  : MountEmulatedStorage(),
09-08 18:23:46.091  6417  6417 E Zygote  : v2
09-08 18:23:46.091  6417  6417 I libpersona: KNOX_SDCARD checking this for 1000
09-08 18:23:46.091  6417  6417 I libpersona: KNOX_SDCARD not a persona
,09-08 18:23:46.091  6417  6417 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-08 18:23:46.091  1015  3238 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6417 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
09-08 18:23:46.091  6417  6417 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-08 18:23:46.101  6392  6392 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-08 18:23:46.101  6417  6417 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-08 18:23:46.101  6392  6392 W AudioCapabilities: Unsupported mime audio/evrc
,09-08 18:23:46.101  6392  6392 W AudioCapabilities: Unsupported mime audio/qcelp
,09-08 18:23:46.111  6392  6392 W AudioCapabilities: Unsupported mime audio/mpeg-L1
09-08 18:23:46.111  6392  6392 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,09-08 18:23:46.111  6392  6392 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-08 18:23:46.111  6392  6392 W AudioCapabilities: Unsupported mime audio/x-ima
,09-08 18:23:46.121  6392  6392 W AudioCapabilities: Unsupported mime audio/qcelp
,09-08 18:23:46.121  6392  6392 W AudioCapabilities: Unsupported mime audio/evrc
,09-08 18:23:46.121  6417  6417 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:46.121  6417  6417 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:46.131  1015  1043 D Tethering: interfaceRemoved p2p0
09-08 18:23:46.131  1015  1043 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-08 18:23:46.141  6392  6392 W VideoCapabilities: Unsupported mime video/wvc1
,09-08 18:23:46.141  6392  6392 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-08 18:23:46.151  6392  6392 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,09-08 18:23:46.151  6392  6392 W VideoCapabilities: Unsupported mime video/wvc1
,09-08 18:23:46.151  6392  6392 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-08 18:23:46.151  6392  6392 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,09-08 18:23:46.151  6392  6392 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,09-08 18:23:46.161  6392  6392 W VideoCapabilities: Unsupported mime video/mp43
,09-08 18:23:46.161  6392  6392 W VideoCapabilities: Unsupported mime video/sorenson
,09-08 18:23:46.161  6417  6417 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-08 18:23:46.171  6392  6392 W VideoCapabilities: Unsupported mime video/mp4v-esdp
09-08 18:23:46.171  6417  6417 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-08 18:23:46.171  6417  6417 D SecurityLogAgent: StateMachine : Current State = 1
,09-08 18:23:46.171  6417  6417 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-08 18:23:46.171  1015  1342 I ActivityManager: Killing 5526:com.google.android.apps.plus/u0a120 (adj 15): empty #31
,09-08 18:23:46.181  1015  3003 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:46.181  1015  3003 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:46.181  1015  3003 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 18:23:46.181  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:46.181  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:46.181  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 18:23:46.191  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:46.191  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:46.191  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 18:23:46.191  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:46.191  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:46.191  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 18:23:46.191  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:46.191  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:46.191  6392  6392 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-08 18:23:46.191  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 18:23:46.201  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:46.201  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 18:23:46.201  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 18:23:46.201  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:46.201  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:46.201  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 18:23:46.211  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:46.211  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 18:23:46.211  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 18:23:46.211  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:46.211  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:46.211  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 18:23:46.211  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:46.211  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:46.211  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 18:23:46.221  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:46.221  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:46.221  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 18:23:46.221  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:46.221  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:46.221  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 18:23:46.221  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:46.221  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:46.221  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 18:23:46.231  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:46.231  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:46.231  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 18:23:46.231  1015  3223 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
09-08 18:23:46.231  1015  3223 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,09-08 18:23:46.231  1015  3223 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:46.231  1015  3223 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:46.231  1015  3223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-08 18:23:46.231  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:46.231  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:46.231  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 18:23:46.241  1015  1028 I ActivityManager: Killing 5460:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,09-08 18:23:46.251  1300  1300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 18:23:46.251  1015  1487 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-08 18:23:46.251  1015  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-08 18:23:46.251  1015  1487 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:46.251  1015  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 18:23:46.251  1015  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-08 18:23:46.251  1015  3238 I ActivityManager: Killing 5053:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,09-08 18:23:46.261  1300  1300 D DockEventReceiver: finishStartingService: stopping service
,09-08 18:23:46.271  1300  1300 D BluetoothNotiBroadcastReceiver: onReceive
,09-08 18:23:46.271  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-08 18:23:46.271  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-08 18:23:46.271  1015  1251 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,09-08 18:23:46.281  1015  1251 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:46.281  1015  1251 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:46.281  1015  1251 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:46.281  1015  1251 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:46.291  1015  1251 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6435 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a,
09-08 18:23:46.291  6435  6435 E Zygote  : MountEmulatedStorage()
09-08 18:23:46.291  6435  6435 I libpersona: KNOX_SDCARD checking this for 1002
09-08 18:23:46.291  6435  6435 E Zygote  : v2
09-08 18:23:46.291  6435  6435 I libpersona: KNOX_SDCARD not a persona
,09-08 18:23:46.291  6435  6435 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-08 18:23:46.301  6435  6435 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-08 18:23:46.301  6435  6435 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-08 18:23:46.321  6435  6435 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:46.321  6435  6435 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:46.331  6435  6435 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-08 18:23:46.331  6435  6435 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-08 18:23:46.361  6435  6435 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-08 18:23:46.391  6435  6435 D BtSettings.ProfileConfig: Adding GattService
,09-08 18:23:46.391  6435  6435 D BtSettings.ProfileConfig: Adding HeadsetService
,09-08 18:23:46.391  6435  6435 D BtSettings.ProfileConfig: Adding A2dpService
,09-08 18:23:46.391  6435  6435 D BtSettings.ProfileConfig: Adding HidService
,09-08 18:23:46.391  6435  6435 D BtSettings.ProfileConfig: Adding HealthService
,09-08 18:23:46.391  6435  6435 D BtSettings.ProfileConfig: Adding PanService
,09-08 18:23:46.391  6435  6435 D BtSettings.ProfileConfig: Adding BluetoothMapService
,09-08 18:23:46.401  6435  6435 D BtSettings.ProfileConfig: Adding SapService
,09-08 18:23:46.401  6435  6435 D BtSettings.ProfileConfig: Adding HeadsetClientService
09-08 18:23:46.401  6435  6435 D BtSettings.ProfileConfig: Adding A2dpSinkService
,09-08 18:23:46.401  6435  6435 D BtSettings.ProfileConfig: Adding SapClientService
,09-08 18:23:46.401  6435  6435 D BtSettings.ProfileConfig: Adding HidDevService
,09-08 18:23:46.401  6435  6435 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-08 18:23:46.401  1015  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,09-08 18:23:46.401  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-08 18:23:46.401  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-08 18:23:46.401  1015  1028 D SettingsProvider: selectionArgs: false
09-08 18:23:46.401  1015  1028 D SettingsProvider: selectionArgs: 1002
09-08 18:23:46.401  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-08 18:23:46.401  1015  1028 D SettingsProvider: ret = -1
,09-08 18:23:46.401  1015  1564 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
09-08 18:23:46.401  1015  1564 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-08 18:23:46.401  1015  1564 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-08 18:23:46.401  1015  1564 D SettingsProvider: selectionArgs: false
09-08 18:23:46.401  1015  1564 D SettingsProvider: selectionArgs: 1002
,09-08 18:23:46.401  1015  1564 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-08 18:23:46.401  1015  1564 D SettingsProvider: ret = -1
,09-08 18:23:46.401  1015  1251 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,09-08 18:23:46.401  1015  1251 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-08 18:23:46.401  1015  1251 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-08 18:23:46.401  1015  1251 D SettingsProvider: selectionArgs: false
09-08 18:23:46.401  1015  1251 D SettingsProvider: selectionArgs: 1002
09-08 18:23:46.401  1015  1251 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-08 18:23:46.401  1015  1251 D SettingsProvider: ret = -1
,09-08 18:23:46.411  1015  3002 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,09-08 18:23:46.411  1015  3002 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-08 18:23:46.411  1015  3002 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-08 18:23:46.411  1015  3002 D SettingsProvider: selectionArgs: false
09-08 18:23:46.411  1015  3002 D SettingsProvider: selectionArgs: 1002
,09-08 18:23:46.411  1015  3002 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-08 18:23:46.411  1015  3002 D SettingsProvider: ret = -1
,09-08 18:23:46.411  1015  3003 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
,09-08 18:23:46.411  1015  3003 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-08 18:23:46.411  1015  3003 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-08 18:23:46.411  1015  3003 D SettingsProvider: selectionArgs: false
09-08 18:23:46.411  1015  3003 D SettingsProvider: selectionArgs: 1002
,09-08 18:23:46.411  1015  3003 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-08 18:23:46.411  1015  3003 D SettingsProvider: ret = -1
,09-08 18:23:46.411  1015  3235 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService,
09-08 18:23:46.411  1015  3235 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-08 18:23:46.411  1015  3235 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-08 18:23:46.411  1015  3235 D SettingsProvider: selectionArgs: false
,09-08 18:23:46.411  1015  3235 D SettingsProvider: selectionArgs: 1002
,09-08 18:23:46.411  1015  3235 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-08 18:23:46.411  1015  3235 D SettingsProvider: ret = -1
,09-08 18:23:46.411  1015  1487 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService,
,09-08 18:23:46.411  1015  1487 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-08 18:23:46.411  1015  1487 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-08 18:23:46.411  1015  1487 D SettingsProvider: selectionArgs: false,
09-08 18:23:46.411  1015  1487 D SettingsProvider: selectionArgs: 1002
09-08 18:23:46.411  1015  1487 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-08 18:23:46.411  1015  1487 D SettingsProvider: ret = -1
,09-08 18:23:46.411  1015  3224 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
09-08 18:23:46.411  1015  3224 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-08 18:23:46.411  1015  3224 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-08 18:23:46.411  1015  3224 D SettingsProvider: selectionArgs: false
,09-08 18:23:46.411  1015  3224 D SettingsProvider: selectionArgs: 1002
09-08 18:23:46.411  1015  3224 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-08 18:23:46.411  1015  3224 D SettingsProvider: ret = -1
09-08 18:23:46.411  1015  3223 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService,
09-08 18:23:46.411  1015  3223 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-08 18:23:46.411  1015  3223 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-08 18:23:46.411  1015  3223 D SettingsProvider: selectionArgs: false
,09-08 18:23:46.411  1015  3223 D SettingsProvider: selectionArgs: 1002
09-08 18:23:46.411  1015  3223 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-08 18:23:46.411  1015  3223 D SettingsProvider: ret = -1
09-08 18:23:46.411  1015  3238 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,09-08 18:23:46.411  1015  3238 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-08 18:23:46.411  1015  3238 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-08 18:23:46.411  1015  3238 D SettingsProvider: selectionArgs: false
,09-08 18:23:46.411  1015  3238 D SettingsProvider: selectionArgs: 1002
09-08 18:23:46.411  1015  3238 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-08 18:23:46.411  1015  3238 D SettingsProvider: ret = -1
09-08 18:23:46.411  1015  1383 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
09-08 18:23:46.411  1015  1383 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-08 18:23:46.411  1015  1383 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-08 18:23:46.411  1015  1383 D SettingsProvider: selectionArgs: false
09-08 18:23:46.411  1015  1383 D SettingsProvider: selectionArgs: 1002
09-08 18:23:46.421  1015  1383 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-08 18:23:46.421  1015  1383 D SettingsProvider: ret = -1
09-08 18:23:46.421  1015  1342 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
09-08 18:23:46.421  1015  1342 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-08 18:23:46.421  1015  1342 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-08 18:23:46.421  1015  1342 D SettingsProvider: selectionArgs: false
09-08 18:23:46.421  1015  1342 D SettingsProvider: selectionArgs: 1002
09-08 18:23:46.421  1015  1342 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-08 18:23:46.421  1015  1342 D SettingsProvider: ret = -1,
09-08 18:23:46.431  1015  1027 I ActivityManager: Killing 5761:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,09-08 18:23:46.431  1907  1907 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-08 18:23:46.431  1015  1564 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-08 18:23:46.431  1015  1564 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-08 18:23:46.431  1015  1564 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:46.431  1015  1564 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:46.431  1015  1564 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:46.441  1907  6451 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-08 18:23:46.441  1907  1907 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-08 18:23:46.441  1015  1383 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 18:23:46.451  1015  1383 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:46.451  1015  1383 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:46.451  1015  1383 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:46.451  1015  1342 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-08 18:23:46.451  1015  1342 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-08 18:23:46.451  1015  1342 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:46.451  1015  1342 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:46.451  1015  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-08 18:23:46.451  3600  3600 I Hs20UtilService: Starting #11
,09-08 18:23:46.451  3600  3625 I Hs20UtilService: Message received 5011
,09-08 18:23:46.451  6417  6417 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-08 18:23:46.451  6417  6417 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-08 18:23:46.451  6417  6417 D SecurityLogAgent: StateMachine : Current State = 1
09-08 18:23:46.461  6417  6417 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-08 18:23:46.461  1015  1251 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-08 18:23:46.461  1015  1251 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:46.461  1015  1251 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:46.461  1015  1251 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:46.461  1015  1251 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:46.481  6452  6452 E Zygote  : MountEmulatedStorage()
09-08 18:23:46.481  6452  6452 E Zygote  : v2
09-08 18:23:46.481  6452  6452 I libpersona: KNOX_SDCARD checking this for 1000
09-08 18:23:46.481  6452  6452 I libpersona: KNOX_SDCARD not a persona
,09-08 18:23:46.481  6452  6452 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-08 18:23:46.481  6452  6452 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-08 18:23:46.481  6452  6452 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-08 18:23:46.481  1015  1251 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6452 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
09-08 18:23:46.481  1015  3238 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 18:23:46.491  1015  3238 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:46.491  1015  3238 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:46.491  1015  3238 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:46.491   289   289 E SMD     : DCD OFF
09-08 18:23:46.491  1907  6451 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,09-08 18:23:46.501  6452  6452 D TimaKeyStoreProvider: TimaSignature is unavailable
09-08 18:23:46.501  6452  6452 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:46.521   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,09-08 18:23:46.521  6452  6452 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,09-08 18:23:46.521  6452  6452 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-08 18:23:46.521  6452  6452 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance,
,09-08 18:23:46.541  6452  6452 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-08 18:23:46.541  6452  6452 I PCWCLIENTTRACE_PushUtil: sales region : global
09-08 18:23:46.541  6452  6452 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-08 18:23:46.541  6452  6452 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-08 18:23:46.541  1015  3224 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
,09-08 18:23:46.541  6452  6467 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
09-08 18:23:46.541  1015  3224 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,09-08 18:23:46.541  1015  3224 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,09-08 18:23:46.541  1015  3224 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:46.541  1015  3224 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:46.541  1015  3224 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:46.541  1015  3224 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:46.561  6469  6469 E Zygote  : MountEmulatedStorage(),
09-08 18:23:46.561  6469  6469 E Zygote  : v2
09-08 18:23:46.561  6469  6469 I libpersona: KNOX_SDCARD checking this for 10111
09-08 18:23:46.561  6469  6469 I libpersona: KNOX_SDCARD not a persona
,09-08 18:23:46.561  6469  6469 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-08 18:23:46.561  1015  3224 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6469 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-08 18:23:46.561  1015  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast,
09-08 18:23:46.561  6469  6469 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-08 18:23:46.561  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:46.561  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:46.561  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:46.561  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:46.571  6469  6469 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,09-08 18:23:46.581  6480  6480 E Zygote  : MountEmulatedStorage()
,09-08 18:23:46.581  6480  6480 I libpersona: KNOX_SDCARD checking this for 10009
09-08 18:23:46.581  6480  6480 E Zygote  : v2
09-08 18:23:46.581  6480  6480 I libpersona: KNOX_SDCARD not a persona
09-08 18:23:46.581  6480  6480 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-08 18:23:46.581  1015  1041 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6480 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-08 18:23:46.591  6480  6480 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-08 18:23:46.591  6480  6480 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-08 18:23:46.591  1015  1041 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
09-08 18:23:46.591  1718  1718 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-08 18:23:46.591  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:46.591  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:46.591  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:46.591  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:46.601  6469  6469 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:46.601  6469  6469 D ActivityThread: Added TimaKeyStore provider,
,09-08 18:23:46.611  6495  6495 E Zygote  : MountEmulatedStorage()
,09-08 18:23:46.611  6495  6495 E Zygote  : v2
09-08 18:23:46.611  6495  6495 I libpersona: KNOX_SDCARD checking this for 10145
09-08 18:23:46.611  6495  6495 I libpersona: KNOX_SDCARD not a persona
09-08 18:23:46.611  6495  6495 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-08 18:23:46.611  1015  1041 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6495 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,09-08 18:23:46.611  6495  6495 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-08 18:23:46.621  6495  6495 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-08 18:23:46.621  1718  1718 D accuweather: [KK AccuPhone]>>> U:4106 [0:0] getPWC : surface = 0, remote = 1
09-08 18:23:46.621  1718  1718 D accuweather: [KK AccuPhone]>>> U:4284 [0:0] Store PWC = 1
09-08 18:23:46.621  1718  1718 D accuweather: [KK AccuPhone]>>> U:4158 [0:0] addPWC = 1
09-08 18:23:46.621  1718  1718 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-08 18:23:46.631  1718  1718 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-08 18:23:46.631  1718  1718 D accuweather: [KK AccuPhone]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,09-08 18:23:46.631  1015  3140 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,09-08 18:23:46.631  1321  1336 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 7
09-08 18:23:46.631  1015  3140 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:46.631  6480  6480 D TimaKeyStoreProvider: TimaSignature is unavailable
09-08 18:23:46.631  1015  3140 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:46.631  1015  3140 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:46.631  1015  3140 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:46.641  6480  6480 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:46.641  6495  6495 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:46.651  6495  6495 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:46.651  6514  6514 E Zygote  : MountEmulatedStorage()
09-08 18:23:46.651  6514  6514 E Zygote  : v2
09-08 18:23:46.651  6514  6514 I libpersona: KNOX_SDCARD checking this for 10081
09-08 18:23:46.651  6514  6514 I libpersona: KNOX_SDCARD not a persona
,09-08 18:23:46.661  6514  6514 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-08 18:23:46.661  1015  3140 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6514 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,09-08 18:23:46.661  6514  6514 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-08 18:23:46.661  6514  6514 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,09-08 18:23:46.681   305   305 I art     : Explicit concurrent mark sweep GC freed 8725(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 643us total 25.211ms
,09-08 18:23:46.681  1718  1718 D accuweather: [KK AccuPhone]>>> U:4250 [0:0] Store PWC succeed
,09-08 18:23:46.691  6495  6495 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,09-08 18:23:46.691  6514  6514 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:46.691  6514  6514 D ActivityThread: Added TimaKeyStore provider
09-08 18:23:46.691  6495  6495 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-08 18:23:46.691  6495  6495 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,09-08 18:23:46.701  6495  6495 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-08 18:23:46.701  6495  6495 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-08 18:23:46.701   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 631us total 17.024ms,
,09-08 18:23:46.721   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 630us total 17.521ms
,09-08 18:23:46.731  6469  6469 I MusicStore: Database version: 108
,09-08 18:23:46.761  1015  1342 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-08 18:23:46.761  1015  1342 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-08 18:23:46.761  1015  1342 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:46.761  1015  1342 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:46.761  1015  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-08 18:23:46.761  1015  3003 D RCPManagerService: exchangeData() failure , invalid userId
,09-08 18:23:46.761  1015  3002 I ActivityManager: Killing 5205:com.sec.spp.push/u0a35 (adj 15): empty #31
,09-08 18:23:46.771  3637  3637 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Sep 08 18:23:46 GMT+02:00 2016
,09-08 18:23:46.771  1015  1494 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-08 18:23:46.771  1015  1494 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-08 18:23:46.771  1015  1494 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:46.771  1015  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:46.771  1015  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-08 18:23:46.781  3637  3637 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,09-08 18:23:46.781  3637  3637 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,09-08 18:23:46.791  1015  3224 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,09-08 18:23:46.791  3637  3637 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-08 18:23:46.791  1015  1027 D RCPManagerService: exchangeData() failure , invalid userId
,09-08 18:23:46.791  1015  3224 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:46.791  1015  3224 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:46.791  1015  3224 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:46.791  1015  3224 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:46.791  3637  3637 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-08 18:23:46.791  3637  6535 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
09-08 18:23:46.801  3637  6535 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
09-08 18:23:46.801  3637  6535 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,09-08 18:23:46.801  6539  6539 E Zygote  : MountEmulatedStorage()
09-08 18:23:46.801  6539  6539 I libpersona: KNOX_SDCARD checking this for 10034
09-08 18:23:46.801  6539  6539 E Zygote  : v2
09-08 18:23:46.801  6539  6539 I libpersona: KNOX_SDCARD not a persona
09-08 18:23:46.801  6539  6539 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-08 18:23:46.801  1015  3224 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6539 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
09-08 18:23:46.811  6539  6539 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-08 18:23:46.811  6539  6539 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-08 18:23:46.811  3637  6535 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,09-08 18:23:46.811  3637  3637 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,09-08 18:23:46.831  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,09-08 18:23:46.831  1015  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-08 18:23:46.831  6539  6539 D TimaKeyStoreProvider: TimaSignature is unavailable
09-08 18:23:46.831  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:46.831  6539  6539 D ActivityThread: Added TimaKeyStore provider
09-08 18:23:46.831  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:46.831  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:46.831  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:46.841  6557  6557 E Zygote  : MountEmulatedStorage(),
09-08 18:23:46.841  6557  6557 E Zygote  : v2
09-08 18:23:46.841  6557  6557 I libpersona: KNOX_SDCARD checking this for 10113,
09-08 18:23:46.841  6557  6557 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-08 18:23:46.841  6557  6557 I libpersona: KNOX_SDCARD not a persona,
,09-08 18:23:46.851  1015  1027 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6557 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-08 18:23:46.851  6557  6557 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
09-08 18:23:46.851  1015  1251 D RCPManagerService: exchangeData() failure , invalid userId
09-08 18:23:46.851  6557  6557 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-08 18:23:46.871  6557  6557 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:46.871  1015  1342 D RCPManagerService: exchangeData() failure , invalid userId
,09-08 18:23:46.871  6557  6557 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:46.891  6469  6469 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-08 18:23:46.891  6469  6469 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-08 18:23:46.901  6539  6539 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,09-08 18:23:46.921  1015  3140 I ActivityManager: Killing 5770:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,09-08 18:23:46.941  6469  6469 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-08 18:23:46.941  1015  3223 D RCPManagerService: exchangeData() failure , invalid userId
,09-08 18:23:46.951  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-08 18:23:46.951  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:46.951  1015  3002 D RCPManagerService: exchangeData() failure , invalid userId
,09-08 18:23:46.951  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:46.951  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:46.951  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:46.961  3177  6575 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,09-08 18:23:46.971  3177  6575 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,09-08 18:23:46.971  3177  6575 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,09-08 18:23:46.971  3177  6575 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,09-08 18:23:46.971  3177  6575 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... ,
09-08 18:23:46.971  1015  1028 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6577 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-08 18:23:46.971  6577  6577 E Zygote  : MountEmulatedStorage(),
,09-08 18:23:46.981  5884  5913 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,09-08 18:23:46.991  6577  6577 E Zygote  : v2
09-08 18:23:46.991  6577  6577 I libpersona: KNOX_SDCARD checking this for 10035
09-08 18:23:46.991  6577  6577 I libpersona: KNOX_SDCARD not a persona
,09-08 18:23:46.991  6577  6577 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-08 18:23:46.991  6577  6577 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-08 18:23:46.991  6577  6577 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-08 18:23:47.001  6469  6469 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-08 18:23:47.011  6469  6469 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@388b25f1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-08 18:23:47.011  6469  6469 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-08 18:23:47.011  6469  6469 D AndroidMusic: GMSCore installation verified
,09-08 18:23:47.011  1015  3224 D RCPManagerService: exchangeData() failure , invalid userId
,09-08 18:23:47.031  1478  1478 D Launcher.Model: reloadBadges entered.
,09-08 18:23:47.031  5884  5899 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
,09-08 18:23:47.031  6577  6577 D TimaKeyStoreProvider: TimaSignature is unavailable
09-08 18:23:47.031  5884  5899 D BadgeProvider: sendNotify, [notify] : null
09-08 18:23:47.031  5884  5899 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
09-08 18:23:47.031  5884  5899 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-08 18:23:47.031  5884  5899 D BadgeProvider: update, [UpdateCount] : 1
,09-08 18:23:47.031  6577  6577 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:47.031  1015  1028 D RCPManagerService: exchangeData() failure , invalid userId
,09-08 18:23:47.041  1015  3224 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-08 18:23:47.041  1015  3224 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,09-08 18:23:47.041  1015  3224 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:47.041  1015  3224 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:47.041  1015  3224 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-08 18:23:47.071  6417  6417 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-08 18:23:47.071  6417  6417 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-08 18:23:47.071  6417  6417 D SecurityLogAgent: StateMachine : Current State = 1
09-08 18:23:47.071  6417  6417 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-08 18:23:47.071  1015  3235 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,09-08 18:23:47.071  6469  6469 I ConfigStore: Config Database version: 1
,09-08 18:23:47.071  1015  3235 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:47.071  1015  3235 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:47.071  1015  3235 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:47.071  1015  3235 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:47.081  1015  3235 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6595 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-08 18:23:47.091  6595  6595 E Zygote  : MountEmulatedStorage(),
09-08 18:23:47.091  6595  6595 I libpersona: KNOX_SDCARD checking this for 10159
09-08 18:23:47.091  6595  6595 E Zygote  : v2
09-08 18:23:47.091  6595  6595 I libpersona: KNOX_SDCARD not a persona,
,09-08 18:23:47.101  6595  6595 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-08 18:23:47.101  6595  6595 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-08 18:23:47.101  6595  6595 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,09-08 18:23:47.131  6595  6595 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:47.131  6595  6595 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:47.141  6577  6604 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
09-08 18:23:47.141  6577  6604 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-08 18:23:47.141  6577  6577 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,09-08 18:23:47.141  1015  1251 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,09-08 18:23:47.141  1015  1251 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,09-08 18:23:47.151  5971  5971 I SA      : [DM] init START
,09-08 18:23:47.151  1015  1251 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:47.151  1015  1251 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-08 18:23:47.151  1015  1251 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,09-08 18:23:47.161  5971  5971 I SA      : [DM] This device is not a Vodafone
,09-08 18:23:47.161  5971  5971 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,09-08 18:23:47.171  5971  5971 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,09-08 18:23:47.171  5971  5971 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
09-08 18:23:47.171  5971  5971 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,09-08 18:23:47.171  5971  5971 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,09-08 18:23:47.171  5971  5971 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
09-08 18:23:47.171  5971  5971 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,09-08 18:23:47.171  5971  5971 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-08 18:23:47.171  5971  5971 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,09-08 18:23:47.171  5971  5971 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,09-08 18:23:47.171  5971  5971 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,09-08 18:23:47.171  5971  5971 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,09-08 18:23:47.171  5971  5971 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,09-08 18:23:47.171  5971  5971 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
09-08 18:23:47.171  5971  5971 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,09-08 18:23:47.171  5971  5971 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,09-08 18:23:47.171  5971  5971 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,09-08 18:23:47.181  6577  6604 D SPPClientService: PushLog.txt file is not deleted.
,09-08 18:23:47.181  6577  6604 D SPPClientService: PushLog.txt file is not deleted.
09-08 18:23:47.181  6577  6604 D SPPClientService: ============PushLog. stop!
,09-08 18:23:47.181  5971  5971 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,09-08 18:23:47.181  5971  5971 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,09-08 18:23:47.181  6577  6612 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
09-08 18:23:47.181  5971  5971 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,09-08 18:23:47.181  5971  5971 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,09-08 18:23:47.191  5971  5971 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
09-08 18:23:47.191  5971  5971 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,09-08 18:23:47.191  5971  5971 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,09-08 18:23:47.191  5971  5971 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
09-08 18:23:47.191  5971  5971 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,09-08 18:23:47.201  1015  3140 I art     : Explicit concurrent mark sweep GC freed 54067(2MB) AllocSpace objects, 5(128KB) LOS objects, 33% free, 27MB/41MB, paused 2.746ms total 165.544ms
,09-08 18:23:47.211  1015  3002 I ActivityManager: Killing 5494:com.sec.knox.bridge/1000 (adj 15): empty #31
,09-08 18:23:47.221  5971  5971 I SA      : [SCU] isHaveSA() - false
09-08 18:23:47.221  5971  5971 I SA      : support phone number id : false
09-08 18:23:47.221  5971  5971 I SA      : [DM] Supports Ref Jpn : true
,09-08 18:23:47.221  5971  5971 I SA      : [DM] init END
09-08 18:23:47.221  5971  5971 I SA      : [OR] onReceive log=[SA = 2.1.0240 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOJ6 PSS = 4.978878039476607  ]
,09-08 18:23:47.221  1015  3003 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-08 18:23:47.221  1015  3003 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-08 18:23:47.221  1015  3003 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:47.221  1015  3003 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:47.221  1015  3003 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:47.221  5971  5971 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
09-08 18:23:47.221  5971  5971 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-08 18:23:47.221  5971  5971 I SA      : [SLFUCHKMGR] constructor called
,09-08 18:23:47.221  1015  1383 I ActivityManager: Killing 5825:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,09-08 18:23:47.231   255   534 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
09-08 18:23:47.231   255   534 W Vold    : Returning OperationFailed - no handler for errno 0
,09-08 18:23:47.231  6469  6469 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,09-08 18:23:47.231   255   534 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
09-08 18:23:47.231   255   534 W Vold    : Returning OperationFailed - no handler for errno 0
,09-08 18:23:47.231  6469  6469 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,09-08 18:23:47.231   255   534 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
09-08 18:23:47.231   255   534 W Vold    : Returning OperationFailed - no handler for errno 0
,09-08 18:23:47.241  6469  6469 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,09-08 18:23:47.241  3786  3786 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-08 18:23:47.241  5971  5971 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-08 18:23:47.241  5971  5971 I SA      : [OR] == isSIMCardReady false ==
,09-08 18:23:47.241  5971  5971 I SA      : [SCU] == networkStateCheck == false
09-08 18:23:47.241  5971  5971 I SA      : [OR] onReceive END
,09-08 18:23:47.241  3786  4533 I iu.UploadsManager: num queued entries: 0
,09-08 18:23:47.241  3786  4533 I iu.UploadsManager: num updated entries: 0
,09-08 18:23:47.251  1015  3235 I ActivityManager: Killing 5861:com.sec.android.app.samsungapps/u0a10 (adj 15): empty #31
,09-08 18:23:47.251  3786  4533 I iu.SyncManager: NEXT; no task
,09-08 18:23:47.251  1226  1226 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-08 18:23:47.251  1015  3223 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,09-08 18:23:47.251  1015  3223 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,09-08 18:23:47.251  1015  3223 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:47.251  1015  3223 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:47.251  1015  3223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-08 18:23:47.271  1015  1494 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-08 18:23:47.271  1015  1494 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,09-08 18:23:47.271  1015  1494 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:47.271  1015  1494 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:47.271  1015  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-08 18:23:47.291   255   534 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-08 18:23:47.291   255   534 W Vold    : Returning OperationFailed - no handler for errno 0
,09-08 18:23:47.291  6557  6619 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-08 18:23:47.291  1015  3224 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-08 18:23:47.301   255   534 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-08 18:23:47.301   255   534 W Vold    : Returning OperationFailed - no handler for errno 0
,09-08 18:23:47.301  6557  6619 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-08 18:23:47.301  1015  3140 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-08 18:23:47.311  1015  3238 I AudioService: getStreamVolume 3 index 0
,09-08 18:23:47.311   255   534 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-08 18:23:47.311   255   534 W Vold    : Returning OperationFailed - no handler for errno 0
,09-08 18:23:47.311  6469  6469 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,09-08 18:23:47.321  6557  6622 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-08 18:23:47.321   255   534 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-08 18:23:47.321   255   534 W Vold    : Returning OperationFailed - no handler for errno 0
,09-08 18:23:47.321  6469  6469 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,09-08 18:23:47.321  6557  6622 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-08 18:23:47.351  1015  3223 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-08 18:23:47.351  1015  3223 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-08 18:23:47.351  1015  3223 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:47.351  1015  3223 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:47.351  1015  3223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-08 18:23:47.361  1015  3002 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-08 18:23:47.361  1015  3002 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,09-08 18:23:47.361  1015  3002 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:47.361  1015  3002 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:47.361  1015  3002 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-08 18:23:47.361  1015  3224 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-08 18:23:47.361  1015  3224 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,09-08 18:23:47.361  1015  3224 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:47.361  1015  3224 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:47.361  1015  3224 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-08 18:23:47.371  1015  3003 I ActivityManager: Killing 5728:com.android.mms/u0a46 (adj 15): empty #31
,09-08 18:23:47.371  1015  3235 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-08 18:23:47.391  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-08 18:23:47.391  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:47.391  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:47.391  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:47.391  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:47.401  6627  6627 E Zygote  : MountEmulatedStorage()
,09-08 18:23:47.401  6627  6627 I libpersona: KNOX_SDCARD checking this for 10002
09-08 18:23:47.401  6627  6627 E Zygote  : v2
09-08 18:23:47.401  6627  6627 I libpersona: KNOX_SDCARD not a persona
,09-08 18:23:47.401  6627  6627 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-08 18:23:47.401  1015  1015 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6627 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
09-08 18:23:47.401  6627  6627 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-08 18:23:47.411  6627  6627 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-08 18:23:47.421  1015  3238 D CountryDetector: No listener is left
,09-08 18:23:47.431  6627  6627 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:47.441  6627  6627 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:47.441  1015  3140 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
09-08 18:23:47.441  1015  3140 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,09-08 18:23:47.441  1015  1487 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,09-08 18:23:47.441  1015  1487 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,09-08 18:23:47.441  1015  1487 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:47.441  1015  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:47.441  1015  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,09-08 18:23:47.451  1015  1342 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,09-08 18:23:47.451  6469  6469 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,09-08 18:23:47.451  1015  1028 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-08 18:23:47.451  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-08 18:23:47.451  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:47.451  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:47.451  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-08 18:23:47.451  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,09-08 18:23:47.481  1015  1028 I ActivityManager: Killing 5901:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,09-08 18:23:47.491  1015  1251 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 18:23:47.491  1015  1251 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:47.491  1015  1251 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:47.491  1015  1251 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-08 18:23:47.511  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,09-08 18:23:47.511  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:47.511  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:47.511  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:47.511  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:47.511  6557  6557 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,09-08 18:23:47.521  6659  6659 E Zygote  : MountEmulatedStorage()
,09-08 18:23:47.521  6659  6659 E Zygote  : v2
,09-08 18:23:47.521  6659  6659 I libpersona: KNOX_SDCARD checking this for 1000
,09-08 18:23:47.521  6659  6659 I libpersona: KNOX_SDCARD not a persona
,09-08 18:23:47.521   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-08 18:23:47.521  1015  1027 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6659 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
09-08 18:23:47.521  6659  6659 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-08 18:23:47.531  6659  6659 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-08 18:23:47.531  6659  6659 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-08 18:23:47.541  6557  6557 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 8909-8911)
09-08 18:23:47.541  6557  6557 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-08 18:23:47.541  6557  6557 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {21feb9ae}
,09-08 18:23:47.551  6557  6557 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-08 18:23:47.551  6557  6557 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,09-08 18:23:47.551  6659  6659 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:47.551  6659  6659 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:47.571  6557  6557 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-08 18:23:47.571  6557  6557 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-08 18:23:47.571  6557  6557 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-08 18:23:47.591  6659  6659 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-08 18:23:47.591  6557  6557 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,09-08 18:23:47.591  6557  6557 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
09-08 18:23:47.591  6557  6557 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,09-08 18:23:47.601  6557  6557 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-08 18:23:47.601  6557  6557 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-08 18:23:47.601  6557  6557 I Adreno-EGL: Build Date: 04/06/15 Mon
09-08 18:23:47.601  6557  6557 I Adreno-EGL: Local Branch: 
09-08 18:23:47.601  6557  6557 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-08 18:23:47.601  6557  6557 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-08 18:23:47.601  6557  6557 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-08 18:23:47.651  6557  6686 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-08 18:23:47.661  6557  6557 I NSApplication: Starting up...
,09-08 18:23:47.671  1015  1494 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,09-08 18:23:47.671  1015  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:47.671  1015  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:47.671  1015  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:47.671  1015  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:47.681  1015  1494 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6691 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-08 18:23:47.681  6691  6691 E Zygote  : MountEmulatedStorage()
09-08 18:23:47.681  6691  6691 E Zygote  : v2
09-08 18:23:47.681  6691  6691 I libpersona: KNOX_SDCARD checking this for 10120
09-08 18:23:47.681  6691  6691 I libpersona: KNOX_SDCARD not a persona
,09-08 18:23:47.681  6691  6691 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-08 18:23:47.691  1015  1494 I ActivityManager: Killing 5789:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #31
,09-08 18:23:47.691  1015  1494 I ActivityManager: Killing 5926:com.wsomacp/u0a25 (adj 15): empty #32,
,09-08 18:23:47.691  6691  6691 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-08 18:23:47.691  6691  6691 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-08 18:23:47.711  6691  6691 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:47.711  6691  6691 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:47.721  6659  6659 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,09-08 18:23:47.731  6659  6659 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,09-08 18:23:47.731  6659  6659 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-08 18:23:47.731  6659  6659 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-08 18:23:47.731  6659  6659 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,09-08 18:23:47.731  6659  6659 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-08 18:23:47.731  6691  6691 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-08 18:23:47.731  1015  1494 I ActivityManager: Killing 5951:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
,09-08 18:23:47.841  1015  3224 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-08 18:23:47.841  1015  3224 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-08 18:23:47.841  1015  3224 D SecContentProvider2: mCursor = null
,09-08 18:23:47.851  1015  3224 D WifiService: setWifiEnabled: true pid=6147, uid=10155
,09-08 18:23:47.851  1015  3224 W ActivityManager: Permission Denial: getCurrentUser() from pid=6147, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-08 18:23:47.851  1015  3224 W WifiService: Failed getting userId using ActivityManagerNative
09-08 18:23:47.851  1015  3224 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6147, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-08 18:23:47.851  1015  3224 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-08 18:23:47.851  1015  3224 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-08 18:23:47.851  1015  3224 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-08 18:23:47.851  1015  3224 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-08 18:23:47.851  1015  3224 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-08 18:23:47.851  1015  3224 D SettingsProvider: name = wifi_on
,09-08 18:23:47.851  1015  1126 E WifiHW  : ##################### set firmware type 0 #####################
,09-08 18:23:48.071  1015  1383 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-08 18:23:48.071  1015  1383 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:48.071  1015  1383 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:23:48.071  1015  1383 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:48.071  1015  1383 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:23:48.081  6719  6719 E Zygote  : MountEmulatedStorage()
09-08 18:23:48.081  6719  6719 E Zygote  : v2
09-08 18:23:48.081  6719  6719 I libpersona: KNOX_SDCARD checking this for 10125
09-08 18:23:48.081  6719  6719 I libpersona: KNOX_SDCARD not a persona
,09-08 18:23:48.091  6719  6719 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-08 18:23:48.091  1015  1383 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6719 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
09-08 18:23:48.091  1015  1383 I ActivityManager: Killing 5808:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,09-08 18:23:48.091  6719  6719 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-08 18:23:48.091  6719  6719 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-08 18:23:48.111  6719  6719 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:23:48.111  6719  6719 D ActivityThread: Added TimaKeyStore provider
,09-08 18:23:48.131  6719  6719 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-08 18:23:48.131  6719  6719 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-08 18:23:48.131  6719  6719 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-08 18:23:48.141  6719  6719 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-08 18:23:48.141  6719  6719 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,09-08 18:23:48.141  6719  6719 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-08 18:23:48.151  1015  1487 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,09-08 18:23:48.151  1015  1487 I ActivityManager: Killing 6009:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,09-08 18:23:48.221  1015  1043 D Tethering: interfaceAdded wlan0
,09-08 18:23:48.221  1015  1129 E Tethering: No numeric data
,09-08 18:23:48.231  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
09-08 18:23:48.231  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
09-08 18:23:48.231  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-08 18:23:48.231  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-08 18:23:48.231  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-08 18:23:48.231  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-08 18:23:48.231  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
09-08 18:23:48.231  1015  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-08 18:23:48.231  1015  1129 D Tethering: clearTetheredNotification()
09-08 18:23:48.231  1015  1129 D Tethering: InitialState.processMessage what=4
,09-08 18:23:48.231  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-08 18:23:48.231  1174  1174 D HotspotTile: updateTetherState():false, false
,09-08 18:23:48.241  1015  1129 E Tethering: No numeric data
09-08 18:23:48.241  1015  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-08 18:23:48.241  1015  1129 D Tethering: clearTetheredNotification()
,09-08 18:23:48.241  1015  1043 D Tethering: interfaceAdded p2p0
,09-08 18:23:48.241  1015  1123 V NetworkStats: performPollLocked() took 15ms
09-08 18:23:48.241  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:23:48.241  1015  1043 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-08 18:23:48.251  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
09-08 18:23:48.251  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
,09-08 18:23:48.251  1174  1174 D HotspotTile: updateTetherState():false, false
09-08 18:23:48.251  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
09-08 18:23:48.251  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-08 18:23:48.251   279   997 I WifiHW  : wifi_change_fw_path(): fwpath = sta,
09-08 18:23:48.251  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
09-08 18:23:48.251  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:23:48.251   279   997 D SoftapController: Softap fwReload - Ok
09-08 18:23:48.251  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:23:48.251  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:23:48.261  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-08 18:23:48.261  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-08 18:23:48.261   279   997 D CommandListener: Setting iface cfg
09-08 18:23:48.261   279   997 D CommandListener: Trying to bring down wlan0
,09-08 18:23:48.261   279   997 D CommandListener: Clearing all IP addresses on wlan0
,09-08 18:23:48.261  1015  1123 V NetworkStats: performPollLocked() took 7ms
09-08 18:23:48.261  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:23:48.261  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:23:48.261  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:23:48.261  1015  1126 E WifiHW  : supplicant_name : p2p_supplicant
,09-08 18:23:48.271  1015  1126 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-08 18:23:48.271  1015  1126 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,09-08 18:23:48.271  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 18:23:48.271  1174  1702 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-08 18:23:48.271  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-08 18:23:48.271  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:48.271  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:48.271  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:48.271  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:48.271  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-08 18:23:48.271  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,09-08 18:23:48.281  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-08 18:23:48.281  1174  1174 D HotspotTile: onReceive : 2, 0
,09-08 18:23:48.281  1300  1300 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-08 18:23:48.281  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:48.291  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:48.291  1015  1494 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-08 18:23:48.291  1015  1494 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-08 18:23:48.291  1015  1494 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:48.291  1015  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:48.291  1015  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-08 18:23:48.291  3600  3600 I Hs20UtilService: Starting #12
,09-08 18:23:48.291  3600  3625 I Hs20UtilService: Message received 5011
,09-08 18:23:48.291  6417  6417 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-08 18:23:48.291  6417  6417 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-08 18:23:48.291  6417  6417 D SecurityLogAgent: StateMachine : Current State = 1
09-08 18:23:48.291  6417  6417 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-08 18:23:48.321  6735  6735 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-08 18:23:48.321  6735  6735 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-08 18:23:48.321  6735  6735 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-08 18:23:48.341  6735  6735 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,09-08 18:23:48.341   375   375 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6735,
09-08 18:23:48.341   375   375 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-08 18:23:48.341  6735  6735 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-08 18:23:48.341  6735  6735 I wpa_supplicant: ssSupport state is = 1
09-08 18:23:48.341  6735  6735 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-08 18:23:48.341  6735  6735 I SecureStorage: [INFO]: SPID(0x00000000)Processing data,
09-08 18:23:48.341   375   375 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6735
09-08 18:23:48.341   375   375 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,09-08 18:23:48.481   375   375 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,09-08 18:23:48.491  6735  6735 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed,
,09-08 18:23:48.561  6735  6735 I wpa_supplicant: Ctrl_iface: loading cred from phone,
09-08 18:23:48.561  6735  6735 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-08 18:23:48.561  6735  6735 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,09-08 18:23:48.571   375   375 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6735
09-08 18:23:48.571   375   375 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-08 18:23:48.571  6735  6735 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-08 18:23:48.571  6735  6735 I wpa_supplicant: ssSupport state is = 1
09-08 18:23:48.571  6735  6735 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
,09-08 18:23:48.571  6735  6735 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-08 18:23:48.571  6735  6735 E wpa_supplicant: SIM READ ERROR
09-08 18:23:48.571  6735  6735 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-08 18:23:48.571  6735  6735 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-08 18:23:48.571  6735  6735 E wpa_supplicant: SIM READ ERROR
09-08 18:23:48.571  6735  6735 I wpa_supplicant: Blacklist: Clear (all) 
09-08 18:23:48.571  6735  6735 I wpa_supplicant: wpa_default_ap_write_once
09-08 18:23:48.571  6735  6735 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-08 18:23:48.571  6735  6735 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-08 18:23:48.571  6735  6735 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-08 18:23:48.571  6735  6735 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-08 18:23:48.571  6735  6735 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-08 18:23:48.571  6735  6735 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-08 18:23:48.571  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-08 18:23:48.571  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-08 18:23:48.571  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,09-08 18:23:48.611  6735  6735 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-08 18:23:48.841  6735  6735 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-08 18:23:48.841  6735  6735 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-08 18:23:48.851  6735  6735 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,09-08 18:23:48.861   375   375 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6735
09-08 18:23:48.861   375   375 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,09-08 18:23:48.861  6735  6735 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-08 18:23:48.861  6735  6735 I wpa_supplicant: ssSupport state is = 1
09-08 18:23:48.861  6735  6735 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-08 18:23:48.861  6735  6735 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,09-08 18:23:48.871  6735  6735 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-08 18:23:48.871   375   375 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6735
09-08 18:23:48.871   375   375 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
09-08 18:23:48.871  6735  6735 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
09-08 18:23:48.881  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-08 18:23:48.871  6735  6735 I wpa_supplicant: ssSupport state is = 1,
09-08 18:23:48.881  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-08 18:23:48.871  6735  6735 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-08 18:23:48.871  6735  6735 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-08 18:23:48.871  6735  6735 E wpa_supplicant: SIM READ ERROR
09-08 18:23:48.871  6735  6735 I wpa_supplicant: wpa_default_ap_write_once
09-08 18:23:48.871  6735  6735 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
09-08 18:23:48.871  6735  6735 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-08 18:23:48.881  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
09-08 18:23:48.881  1015  1043 D Tethering: interfaceStatusChanged p2p0, false,
09-08 18:23:48.881  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
09-08 18:23:48.881  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,09-08 18:23:48.921  6735  6735 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-08 18:23:48.921  6735  6735 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-08 18:23:49.061  6735  6735 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,09-08 18:23:49.061  6735  6735 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-08 18:23:49.061  6735  6735 I wpa_supplicant: Skip scan - bUseNetwork false
,09-08 18:23:49.231  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
09-08 18:23:49.231  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-08 18:23:49.231  1015  1043 D Tethering: interfaceStatusChanged p2p0, false,
,09-08 18:23:49.271  1015  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
09-08 18:23:49.271  1015  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-08 18:23:49.281  6735  6735 I wpa_supplicant: HOTSPOT20_ENABLE called
09-08 18:23:49.281  6735  6735 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-08 18:23:49.281  6735  6735 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-08 18:23:49.281  6735  6735 E wpa_supplicant: SIM READ ERROR
09-08 18:23:49.281  6735  6735 I wpa_supplicant: Blacklist: Clear (all) 
,09-08 18:23:49.301  6735  6735 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-08 18:23:49.311  1015  1126 D WifiNative-wlan0: callSECApiInt - ID [210]
,09-08 18:23:49.311  6735  6735 I wpa_supplicant: Skip scan - bUseNetwork false
,09-08 18:23:49.311  1015  1126 D WifiConfigStore: Loading config and enabling all networks ,
,09-08 18:23:49.311  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 18:23:49.311  1174  1702 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi,
,09-08 18:23:49.311  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-08 18:23:49.311  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-08 18:23:49.311  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:49.311  1174  1174 D HotspotTile: onReceive : 3, 0
,09-08 18:23:49.311  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:49.311  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:49.311  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:49.311  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-08 18:23:49.311  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3),
09-08 18:23:49.321  1300  1300 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-08 18:23:49.321  6147  6147 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 18:23:49.321  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:49.321  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:49.321  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:49.321  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:23:49.321  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:23:49.321  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:23:49.321  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:23:49.321  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 18:23:49.321  6147  6147 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:49.321  6147  6147 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 18:23:49.321  1015  1126 E WifiConfigStore: Not a HS20
,09-08 18:23:49.321  6147  6147 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:49.321  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:49.321  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:49.321  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:49.321  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:23:49.321  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:23:49.321  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:23:49.321  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:23:49.321  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 18:23:49.321  6147  6147 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:49.321  6147  6147 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 18:23:49.321  1015  1126 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-08 18:23:49.331  1015  3003 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-08 18:23:49.331  1015  3003 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-08 18:23:49.331  1015  3003 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:49.331  1015  3003 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:49.331  1015  3003 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-08 18:23:49.331  3600  3600 I Hs20UtilService: Starting #13
09-08 18:23:49.331  1015  1126 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-08 18:23:49.331  1015  1126 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-08 18:23:49.331  6735  6735 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-08 18:23:49.331  6735  6735 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-08 18:23:49.331  6735  6735 I wpa_supplicant: reset timer : RESET_TIMER 0
,09-08 18:23:49.341  6735  6735 I wpa_supplicant: P2P: Current p2p state = IDLE
09-08 18:23:49.341  6735  6735 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-08 18:23:49.341  6735  6735 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-08 18:23:49.341  6735  6735 I wpa_supplicant: First Scan Start
09-08 18:23:49.341  6735  6735 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-08 18:23:49.341  6417  6417 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-08 18:23:49.341  3600  3625 I Hs20UtilService: Message received 5011
09-08 18:23:49.341  6417  6417 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-08 18:23:49.341  6417  6417 D SecurityLogAgent: StateMachine : Current State = 1
09-08 18:23:49.341  6417  6417 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-08 18:23:49.341  1015  1126 D WifiNative-wlan0: Setting external_sim to 1
,09-08 18:23:49.341  1015  1126 D WifiStateMachine: Setting OUI to DA-A1-19
09-08 18:23:49.341  1015  1126 I WifiNative-HAL: startHal
09-08 18:23:49.341  1015  1126 E wifi    : getStaticLongField sWifiHalHandle 0x9ca3f88c
09-08 18:23:49.341  1015  1126 I WifiNative-HAL: Could not start hal
,09-08 18:23:49.341  6392  6392 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 18:23:49.351  1015  1126 E WifiNative-wlan0: do suspend true
,09-08 18:23:49.351  1015  1125 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-08 18:23:49.351  1015  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-08 18:23:49.351  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3
,09-08 18:23:49.351  1015  1149 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:49.351  1015  1149 I WifiNative-HAL: startHal
09-08 18:23:49.351  1015  1149 E wifi    : getStaticLongField sWifiHalHandle 0x9dbf19bc
09-08 18:23:49.351  1015  1149 I WifiNative-HAL: Could not start hal
09-08 18:23:49.351  1015  1149 E WifiScanningService: could not start HAL
09-08 18:23:49.351   279   997 D CommandListener: Setting iface cfg
09-08 18:23:49.351   279   997 D CommandListener: Trying to bring up p2p0
,09-08 18:23:49.351  1015  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-08 18:23:49.351  1015  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-08 18:23:49.351  1015  1126 E WifiNative-wlan0: invaild command id : 215
,09-08 18:23:49.351  1015  1125 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-08 18:23:49.351  1015  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-08 18:23:49.351  1015  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-08 18:23:49.351  1015  1126 E WifiNative-wlan0: invaild command id : 215
,09-08 18:23:49.351  1015  1015 D RttService: SCAN_AVAILABLE : 3
09-08 18:23:49.351  1015  1150 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-08 18:23:49.361  6735  6735 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-08 18:23:49.361  1015  1125 D WifiP2pService: P2pEnablingState
09-08 18:23:49.361  1015  1125 D WifiP2pService: P2pEnablingState{ what=147457 }
09-08 18:23:49.361  1015  1125 D WifiP2pService: P2p socket connection successful
,09-08 18:23:49.361  6735  6735 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-08 18:23:49.361  1015  1125 D WifiP2pService: P2pEnabledState
,09-08 18:23:49.361  1015  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-08 18:23:49.361  6735  6735 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,09-08 18:23:49.361  1015  1128 E ConnectivityService: updateNetworkInfo()
,09-08 18:23:49.361  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-08 18:23:49.361  1015  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-08 18:23:49.361  1015  1126 D SecContentProvider2: mCursor = null
09-08 18:23:49.361  1015  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-08 18:23:49.361  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-08 18:23:49.361  1015  1046 D WifiDisplayController: disconnect,
,09-08 18:23:49.361  1015  1046 D WifiDisplayController: updateConnection
09-08 18:23:49.361  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-08 18:23:49.361  1015  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-08 18:23:49.371  1300  1300 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE,
09-08 18:23:49.371  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 18:23:49.371  1300  1300 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-08 18:23:49.371  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
09-08 18:23:49.371  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-08 18:23:49.371  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-08 18:23:49.371  1015  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-08 18:23:49.371  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
09-08 18:23:49.371  1015  1126 D SecContentProvider2: mCursor = null
09-08 18:23:49.371  1015  1125 D WifiNative-p2p0: p2pGetDeviceAddress
,09-08 18:23:49.371  1015  1125 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
,09-08 18:23:49.371  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-08 18:23:49.371  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-08 18:23:49.371  1300  1300 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-08 18:23:49.371  1300  3096 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-08 18:23:49.371  1174  1174 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-08 18:23:49.371  1015  1487 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-08 18:23:49.371  1174  1174 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-08 18:23:49.381  1015  1125 D WifiP2pService: DeviceAddress: 7e:96:ac
,09-08 18:23:49.381  1015  1046 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
09-08 18:23:49.381  1015  1046 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
09-08 18:23:49.381  1015  1046 D WifiDisplayController:  primary type: 10-0050F204-5
09-08 18:23:49.381  1015  1046 D WifiDisplayController:  secondary type: null
09-08 18:23:49.381  1015  1046 D WifiDisplayController:  wps: 0
09-08 18:23:49.381  1015  1046 D WifiDisplayController:  grpcapab: 0
09-08 18:23:49.381  1015  1046 D WifiDisplayController:  devcapab: 0
09-08 18:23:49.381  1015  1046 D WifiDisplayController:  status: 3
09-08 18:23:49.381  1015  1046 D WifiDisplayController:  wfdInfo: null
09-08 18:23:49.381  1015  1046 D WifiDisplayController:  groupownerAddress: null
09-08 18:23:49.381  1015  1046 D WifiDisplayController:  GOdeviceName: null
09-08 18:23:49.381  1015  1046 D WifiDisplayController:  interfaceAddress: 
09-08 18:23:49.381  1015  1046 D WifiDisplayController:  SConnectInfo : null
,09-08 18:23:49.381  6362  6362 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-08 18:23:49.381  6362  6362 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-08 18:23:49.381  6362  6362 D FileShare-Client: Outbound.stopDelayTimer - 
,09-08 18:23:49.391  6377  6377 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-08 18:23:49.401  1015  1125 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-08 18:23:49.401  1015  1125 D WifiP2pService: InactiveState
,09-08 18:23:49.401  1015  1125 D WifiP2pService: InactiveState{ what=143376 }
,09-08 18:23:49.401  1015  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-08 18:23:49.401  6735  6735 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,09-08 18:23:49.401  1015  1125 D WifiP2pService: InactiveState{ what=143376 }
,09-08 18:23:49.401  1015  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-08 18:23:49.491   289   289 E SMD     : DCD OFF,
,09-08 18:23:50.511  6735  6735 I wpa_supplicant: nl80211: Received scan results (29 BSSes),
09-08 18:23:50.511  6735  6735 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-08 18:23:50.511  6735  6735 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,09-08 18:23:50.511  6735  6735 I wpa_supplicant: Trying to associate with  'G700'
09-08 18:23:50.511  6735  6735 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING,
09-08 18:23:50.511  6735  6735 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
09-08 18:23:50.521  1015  6740 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700',
,09-08 18:23:50.551  1015  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-08 18:23:50.551  1015  1126 D SecContentProvider2: mCursor = null
,09-08 18:23:50.671  6735  6735 E wpa_supplicant: Cmd 35605 not handled
,09-08 18:23:50.671  6735  6735 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-08 18:23:50.671  6735  6735 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-08 18:23:50.671  6735  6735 I wpa_supplicant: Associated with F4.99.3E
09-08 18:23:50.671  6735  6735 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,09-08 18:23:50.671  6735  6735 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-08 18:23:50.671  6735  6735 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
09-08 18:23:50.671  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-08 18:23:50.671  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-08 18:23:50.671  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,09-08 18:23:50.681  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-08 18:23:50.681  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-08 18:23:50.681  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,09-08 18:23:50.681  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-08 18:23:50.681  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-08 18:23:50.681  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,09-08 18:23:50.681  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, true
09-08 18:23:50.681  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-08 18:23:50.681  1015  1043 D Tethering: interfaceStatusChanged wlan0, true
09-08 18:23:50.681  1015  1129 E Tethering: No numeric data
09-08 18:23:50.681  1015  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-08 18:23:50.681  1015  1129 D Tethering: clearTetheredNotification()
09-08 18:23:50.691  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
09-08 18:23:50.691  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:23:50.691  6735  6735 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,09-08 18:23:50.691  6735  6735 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
09-08 18:23:50.691  6735  6735 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-08 18:23:50.691  6735  6735 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
09-08 18:23:50.691  1015  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-08 18:23:50.691  1015  1126 D SecContentProvider2: mCursor = null,
09-08 18:23:50.691  6735  6735 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-08 18:23:50.691  6735  6735 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-08 18:23:50.691  6735  6735 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-08 18:23:50.691  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-08 18:23:50.691  6735  6735 I wpa_supplicant: Blacklist: Clear (temp) 
09-08 18:23:50.691  1174  1174 D HotspotTile: updateTetherState():false, false
09-08 18:23:50.691  6735  6735 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-08 18:23:50.691  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-08 18:23:50.691  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-08 18:23:50.691  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-08 18:23:50.691  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, true
09-08 18:23:50.691  1015  1043 D Tethering: interfaceStatusChanged wlan0, true
,09-08 18:23:50.701  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
09-08 18:23:50.701  1015  1123 V NetworkStats: performPollLocked() took 13ms
09-08 18:23:50.701  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:23:50.701  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:23:50.701  1015  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
09-08 18:23:50.701  1015  1126 D SecContentProvider2: mCursor = null
,09-08 18:23:50.711  1015  1126 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-08 18:23:50.711  1015  1126 E WifiConfigStore: setLastSelectedConfiguration -1
,09-08 18:23:50.721  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 18:23:50.721  1015  1126 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,09-08 18:23:50.721  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-08 18:23:50.721  1015  1128 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-08 18:23:50.721  1015  1128 E ConnectivityService: updateNetworkInfo()
09-08 18:23:50.721  1015  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 18:23:50.721  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:23:50.721  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:23:50.721  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:50.721  1015  1041 I ActivityManager: Killing 5708:com.samsung.android.sm/1000 (adj 15): empty #31
09-08 18:23:50.721  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:23:50.731  1015  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 18:23:50.731  1015  1342 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-08 18:23:50.731  1015  1342 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-08 18:23:50.731  1015  1342 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:50.731  1015  1342 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:50.731  1015  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-08 18:23:50.731  3600  3600 I Hs20UtilService: Starting #14
,09-08 18:23:50.731  3600  3625 I Hs20UtilService: Message received 5007
,09-08 18:23:50.741  1300  1300 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-08 18:23:50.741  1300  1300 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-08 18:23:50.751  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-08 18:23:50.751  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-08 18:23:50.751  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-08 18:23:50.751  1015  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 18:23:50.751  1300  1300 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-08 18:23:50.751  1300  3096 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-08 18:23:50.761   279   997 D CommandListener: Setting iface cfg
,09-08 18:23:50.761  1015  1126 E WifiStateMachine: Start Dhcp Watchdog 2
,09-08 18:23:50.771  1015  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-08 18:23:50.771  1015  1126 D SecContentProvider2: mCursor = null
,09-08 18:23:50.771  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-08 18:23:50.771  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-08 18:23:50.781  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:50.781  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:50.781  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:50.781  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:23:50.781  1015  1126 E WifiNative-wlan0: do suspend false
,09-08 18:23:50.781  1015  1125 D WifiP2pService: InactiveState{ what=143375 }
,09-08 18:23:50.791  1015  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-08 18:23:50.791  1015  1126 D SecContentProvider2: mCursor = null
,09-08 18:23:50.791  1015  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-08 18:23:50.861  1015  3140 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-08 18:23:50.861  1015  3140 D WifiService: setWifiEnabled: false pid=6147, uid=10155
09-08 18:23:50.861  1015  3140 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-08 18:23:50.861  1015  3140 D SecContentProvider2: mCursor = null
09-08 18:23:50.861  1015  3140 D SettingsProvider: name = wifi_on
,09-08 18:23:50.871  1015  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 18:23:50.881  1015  1126 E WifiNative-wlan0: do suspend true
,09-08 18:23:50.901   279   997 D CommandListener: Clearing all IP addresses on wlan0
,09-08 18:23:50.901  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-08 18:23:50.901  1015  1125 D WifiP2pService: InactiveState{ what=143375 }
,09-08 18:23:50.911  1015  1128 E ConnectivityService: updateNetworkInfo()
09-08 18:23:50.911  1015  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 18:23:50.911  1015  1128 E ConnectivityService: updateNetworkInfo()
09-08 18:23:50.911  1015  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
,09-08 18:23:50.911  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-08 18:23:50.911  1015  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
09-08 18:23:50.911  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:50.911  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:50.911  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:50.911  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:50.911   279   997 E Netd    : no such netId 503
,09-08 18:23:50.911  1015  1128 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '75 network destroy 503' failed with '400 75 destroyNetwork() failed (Machine is not on the network)'
09-08 18:23:50.911  1015  1128 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-08 18:23:50.911  1015  1128 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
09-08 18:23:50.911  1015  6746 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:23:50.911  1015  1128 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,09-08 18:23:50.911  1015  1128 D ConnectivityService: nai.networkMonitor.doQuit()
09-08 18:23:50.911  1015  6746 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-08 18:23:50.911  1015  1128 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
,09-08 18:23:50.911  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-08 18:23:50.921  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 18:23:50.921  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-08 18:23:50.921  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:50.921  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:50.921  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:50.921  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:23:50.921  1015  1125 D WifiP2pService: InactiveState{ what=131204 }
,09-08 18:23:50.931  1015  1126 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-08 18:23:50.931  1015  1125 D WifiP2pService: P2pEnabledState{ what=131204 }
,09-08 18:23:50.931  1015  1125 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-08 18:23:50.931  1015  1128 E ConnectivityService: updateNetworkInfo()
09-08 18:23:50.931  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1
,09-08 18:23:50.931  1015  1149 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,09-08 18:23:50.931  1015  1015 D RttService: SCAN_AVAILABLE : 1
,09-08 18:23:50.931  1015  1150 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-08 18:23:50.931  1015  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-08 18:23:50.931  1015  1128 E ConnectivityService: updateNetworkInfo()
,09-08 18:23:50.931  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-08 18:23:50.931  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
,09-08 18:23:50.931  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-08 18:23:50.931  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-08 18:23:50.941  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-08 18:23:50.941  1015  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,09-08 18:23:50.941  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,09-08 18:23:50.941  1015  1046 D WifiDisplayController: disconnect
09-08 18:23:50.941  1015  1046 D WifiDisplayController: updateConnection
,09-08 18:23:50.941  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-08 18:23:50.941  1015  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-08 18:23:50.941  1015  1487 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-08 18:23:50.941  1015  1487 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-08 18:23:50.941  1015  1487 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:50.941  1015  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 18:23:50.941  1015  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-08 18:23:50.941  3600  3600 I Hs20UtilService: Starting #15
,09-08 18:23:50.941  1015  1125 D WifiP2pService: P2pDisablingState
09-08 18:23:50.941  3600  3625 I Hs20UtilService: Message received 5007
,09-08 18:23:50.941  1015  1125 D WifiP2pService: P2pDisablingState{ what=147458 }
09-08 18:23:50.941  1015  1125 D WifiP2pService: p2p socket connection lost
,09-08 18:23:50.951  1015  1125 D WifiP2pService: P2pDisabledState
,09-08 18:23:50.951  1015  1126 E WifiNative-wlan0: do suspend true
09-08 18:23:50.951  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-08 18:23:50.951  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
09-08 18:23:50.951  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-08 18:23:50.951  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-08 18:23:50.951  1174  1174 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-08 18:23:50.951  1015  1251 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-08 18:23:50.951  1174  1174 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-08 18:23:50.951  1300  1300 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-08 18:23:50.951  1300  1300 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-08 18:23:50.961  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-08 18:23:50.961  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-08 18:23:50.961  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-08 18:23:50.961  1300  1300 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-08 18:23:50.961  1300  3096 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-08 18:23:50.971  1300  1300 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-08 18:23:50.971  1300  1300 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-08 18:23:50.971  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-08 18:23:50.971  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-08 18:23:50.971  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-08 18:23:50.971  1300  1300 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-08 18:23:50.971  1300  3096 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-08 18:23:50.981  6362  6362 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-08 18:23:50.981  6362  6362 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-08 18:23:50.981  6362  6362 D FileShare-Client: Outbound.stopDelayTimer - 
,09-08 18:23:50.981  1015  1125 D WifiP2pService: P2pDisabledState{ what=143375 }
,09-08 18:23:50.981  1015  1125 D WifiP2pService: DefaultState{ what=143375 }
,09-08 18:23:50.981   279   997 D CommandListener: Clearing all IP addresses on wlan0
,09-08 18:23:50.991  6377  6377 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-08 18:23:50.991  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-08 18:23:50.991  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-08 18:23:50.991  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:23:50.991  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:50.991  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:23:50.991  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:23:51.001  6735  6735 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-08 18:23:51.001  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-08 18:23:51.001  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 18:23:51.001  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-08 18:23:51.001  6749  6749 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
09-08 18:23:51.001  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:51.001  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:51.001  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:51.001  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:23:51.001  6749  6749 I dhcpcd  : version 5.5.6 starting
,09-08 18:23:51.011  6749  6749 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-08 18:23:51.011  1015  1027 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
09-08 18:23:51.011  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
09-08 18:23:51.011  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:51.011  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 18:23:51.011  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-08 18:23:51.011  3600  3600 I Hs20UtilService: Starting #16
,09-08 18:23:51.021  3600  3625 I Hs20UtilService: Message received 5007
,09-08 18:23:51.021  1015  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
09-08 18:23:51.021  1015  1126 D SecContentProvider2: mCursor = null,
09-08 18:23:51.021  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 18:23:51.021  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-08 18:23:51.021  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:51.021  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:51.021  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:51.021  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:51.021  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-08 18:23:51.021  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
09-08 18:23:51.021  1174  1702 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-08 18:23:51.021  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-08 18:23:51.021  1174  1174 D HotspotTile: onReceive : 0, 0
,09-08 18:23:51.031  1300  1300 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-08 18:23:51.031  6147  6147 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:51.031  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:51.031  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:51.031  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:51.031  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:23:51.031  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:23:51.031  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:23:51.031  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:23:51.031  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 18:23:51.031  6147  6147 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:51.031  6147  6147 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 18:23:51.031  6147  6147 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:51.031  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:51.031  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:51.031  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:51.031  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:23:51.031  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:23:51.031  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:23:51.031  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:23:51.031  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 18:23:51.031  1300  1300 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-08 18:23:51.031  6147  6147 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:51.031  6147  6147 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 18:23:51.031  1300  1300 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-08 18:23:51.031  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-08 18:23:51.031  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-08 18:23:51.031  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-08 18:23:51.031  1300  1300 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-08 18:23:51.041  1300  3096 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-08 18:23:51.051  1015  1251 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-08 18:23:51.051  1015  1251 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-08 18:23:51.051  1015  1251 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:51.051  1015  1251 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:51.051  1015  1251 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-08 18:23:51.051  3600  3600 I Hs20UtilService: Starting #17
,09-08 18:23:51.051  3600  3625 I Hs20UtilService: Message received 5011
,09-08 18:23:51.051  6417  6417 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-08 18:23:51.051  6417  6417 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-08 18:23:51.051  6417  6417 D SecurityLogAgent: StateMachine : Current State = 1
09-08 18:23:51.051  6417  6417 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-08 18:23:51.071  6749  6749 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
09-08 18:23:51.071  6749  6749 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-08 18:23:51.071  6749  6749 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
09-08 18:23:51.071  6749  6749 I dhcpcd  : bssid match
,09-08 18:23:51.071  6749  6749 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111
,09-08 18:23:51.151  6749  6749 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1,
,09-08 18:23:51.221  6735  6735 I wpa_supplicant: Blacklist: Clear (all) ,
,09-08 18:23:51.291  6749  6749 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds,
,09-08 18:23:51.291  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
09-08 18:23:51.291  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-08 18:23:51.291  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
09-08 18:23:51.291  6735  6735 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING ,
,09-08 18:23:51.321  1015  1126 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 ,
09-08 18:23:51.321  6735  6735 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
09-08 18:23:51.321  6735  6735 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-08 18:23:51.321  6735  6735 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
,09-08 18:23:51.321  6735  6735 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-08 18:23:51.321  6735  6735 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
09-08 18:23:51.331  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-08 18:23:51.331  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-08 18:23:51.331  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,09-08 18:23:51.331  1015  1129 D Tethering: InitialState.processMessage what=4
,09-08 18:23:51.331  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-08 18:23:51.331  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-08 18:23:51.331  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
09-08 18:23:51.331  1015  1129 E Tethering: No numeric data
09-08 18:23:51.331  1015  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-08 18:23:51.331  1015  1129 D Tethering: clearTetheredNotification()
,09-08 18:23:51.341  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:23:51.341  1015  1123 V NetworkStats: performPollLocked(flags=0x1),
09-08 18:23:51.341  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-08 18:23:51.341  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-08 18:23:51.341  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
09-08 18:23:51.341  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-08 18:23:51.341  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-08 18:23:51.341  1174  1174 D HotspotTile: updateTetherState():false, false
09-08 18:23:51.341  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
09-08 18:23:51.341  1015  1123 V NetworkStats: performPollLocked() took 5ms,
09-08 18:23:51.341  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:23:51.341  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:23:51.341  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:23:51.561  6735  6735 I wpa_supplicant: Blacklist: Clear (all) 
,09-08 18:23:51.671  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
,09-08 18:23:51.671  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
09-08 18:23:51.671  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,09-08 18:23:51.691  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
09-08 18:23:51.691  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-08 18:23:51.691  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,09-08 18:23:51.691  6735  6735 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-08 18:23:51.801  1015  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0,
,09-08 18:23:51.801  1015  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
09-08 18:23:51.801  1015  1126 E WifiConfigStore: setLastSelectedConfiguration -1
,09-08 18:23:51.801  6392  6392 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 18:23:51.811  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-08 18:23:51.811  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,09-08 18:23:51.811  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:51.811  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:23:51.811  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:23:51.811  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:23:51.811  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-08 18:23:51.811  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,09-08 18:23:51.811  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-08 18:23:51.821  1174  1702 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-08 18:23:51.821  1174  1174 D HotspotTile: onReceive : 1, 0
,09-08 18:23:51.821  1907  2121 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 18:23:51.821  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:51.821  1300  1300 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-08 18:23:51.821  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:51.831  1015  1028 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-08 18:23:51.831  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-08 18:23:51.831  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:51.831  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 18:23:51.831  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-08 18:23:51.841  3600  3600 I Hs20UtilService: Starting #18
,09-08 18:23:51.841  3600  3625 I Hs20UtilService: Message received 5011
,09-08 18:23:51.841  6417  6417 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-08 18:23:51.841  6417  6417 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-08 18:23:51.841  6417  6417 D SecurityLogAgent: StateMachine : Current State = 1
,09-08 18:23:51.841  6417  6417 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-08 18:23:52.291  1015  1041 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:52.291  1015  1041 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-08 18:23:52.291  1015  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-08 18:23:52.301  1015  3224 D ActivityManager: bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,09-08 18:23:52.301  1015  3224 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
09-08 18:23:52.301  1015  3224 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:52.301  1015  3224 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:52.301  1015  3224 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-08 18:23:52.311  6557  6620 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,09-08 18:23:52.311  1015  1138 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
09-08 18:23:52.311  1015  1138 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,09-08 18:23:52.311  1015  1138 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:52.311  1015  1138 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-08 18:23:52.311  1015  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-08 18:23:52.331  1015  3140 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:52.331  1015  3140 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-08 18:23:52.331  1015  3140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-08 18:23:52.341  1015  1342 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-08 18:23:52.341  1015  1342 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,09-08 18:23:52.351  1015  1342 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:52.351  1015  1342 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:52.351  1015  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-08 18:23:52.351  1015  3003 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-08 18:23:52.351  1015  3003 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,09-08 18:23:52.351  1015  3003 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:52.351  1015  3003 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-08 18:23:52.351  1015  3003 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-08 18:23:52.361  1015  3223 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-08 18:23:52.361  1015  3223 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-08 18:23:52.361  1015  3223 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:52.361  1015  3223 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-08 18:23:52.361  1015  3223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-08 18:23:52.381  1015  1494 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,09-08 18:23:52.381  1015  1494 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,09-08 18:23:52.381  1015  1494 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:52.381  1015  1494 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-08 18:23:52.381  1015  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-08 18:23:52.411  1015  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 18:23:52.411  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:52.411  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:52.411  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,09-08 18:23:52.421  1907  1907 D WearableService: callingUid 10012, callindPid: 1907
,09-08 18:23:52.441  1015  1342 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-08 18:23:52.441  1015  1342 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-08 18:23:52.441  1015  1342 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:52.441  1015  1342 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:52.441  1015  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-08 18:23:52.471  6469  6779 I MusicLeanback: Conditions not met for autocaching.
,09-08 18:23:52.471  6469  6779 I MusicLeanback: Stop autocaching.
,09-08 18:23:52.481   279   991 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,09-08 18:23:52.481  1015  1043 D Tethering: interfaceRemoved wlan0
,09-08 18:23:52.481  1015  1043 E Tethering: attempting to remove unknown iface (wlan0), ignoring
09-08 18:23:52.481  6469  6469 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,09-08 18:23:52.481  6469  6784 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,09-08 18:23:52.501   289   289 E SMD     : DCD OFF
,09-08 18:23:52.661  1015  1043 D Tethering: interfaceRemoved p2p0
,09-08 18:23:52.661  1015  1043 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-08 18:23:53.481  1015  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1,
,09-08 18:23:53.871  6147  6197 D BluetoothAdapter: enable()
,09-08 18:23:53.871  1015  3238 W ActivityManager: Permission Denial: getCurrentUser() from pid=6147, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-08 18:23:53.871  1015  3238 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-08 18:23:53.871  1015  3238 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6147, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-08 18:23:53.871  1015  3238 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-08 18:23:53.871  1015  3238 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
09-08 18:23:53.871  1015  3238 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
09-08 18:23:53.871  1015  3238 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
09-08 18:23:53.871  1015  3238 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-08 18:23:53.871  1015  3238 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-08 18:23:53.871  1015  3238 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-08 18:23:53.881  1015  3238 D SettingsProvider: name = bluetooth_on,
,09-08 18:23:53.881  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-08 18:23:53.881  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-08 18:23:53.881  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,09-08 18:23:53.881  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,09-08 18:23:53.921  6435  6435 D BluetoothAdapterState: make
,09-08 18:23:53.931  6435  6435 I bluedroid: init
,09-08 18:23:53.941  6435  6786 I BluetoothAdapterState: Entering OffState,
09-08 18:23:53.941  6435  6435 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-08 18:23:53.941  6435  6435 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-08 18:23:53.941  6435  6435 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-08 18:23:53.941  6435  6435 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-08 18:23:53.941  6435  6435 E bt-btif : btif_fetch_local_ble_random_bdaddr,
09-08 18:23:53.941  6435  6435 I bluedroid: get_profile_interface socket
09-08 18:23:53.941  6435  6435 I bluedroid: get_profile_interface map_client
,09-08 18:23:53.941  6435  6789 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting,
,09-08 18:23:53.941  6435  6435 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,09-08 18:23:53.941  6435  6789 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,09-08 18:23:53.951  6435  6789 E BluetoothServiceJni: populateRssiValuesNative
,09-08 18:23:53.951  6435  6789 I bluedroid: getModelRssiValues
,09-08 18:23:53.951  6435  6789 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127,
09-08 18:23:53.951  6435  6789 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-08 18:23:53.951  6435  6789 D BluetoothAdapterProperties: Name is: A5-1
,09-08 18:23:53.951  1015  1015 D SettingsProvider: name = bluetooth_name
,09-08 18:23:53.951  6435  6435 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-08 18:23:53.951  1015  1028 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-08 18:23:53.951  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-08 18:23:53.951  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:53.961  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:53.961  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:53.961  6435  6443 I bluedroid: config_hci_snoop_log
,09-08 18:23:53.961  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,09-08 18:23:53.971  1015  1045 D BluetoothManagerService: Ble is always on enable gatt
,09-08 18:23:53.971  1015  1045 I BluetoothManagerService: enableGattForLeMode, doBind called
,09-08 18:23:53.971  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,09-08 18:23:53.971  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-08 18:23:53.971  6435  6435 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,09-08 18:23:53.981  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-08 18:23:53.981  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-08 18:23:53.981  1015  1045 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-08 18:23:53.981  6435  6786 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-08 18:23:53.981  6435  6786 D BluetoothAdapterProperties: Setting state to 11
,09-08 18:23:53.981  6435  6786 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-08 18:23:53.981  6435  6786 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-08 18:23:53.991  6435  6786 D BluetoothAdapterService: updateAdapterState state is 11
,09-08 18:23:53.991  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-08 18:23:53.991  1015  1015 I InputMethodManagerService: [BT Setting State] State =11
,09-08 18:23:53.991  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-08 18:23:53.991  6435  6786 D BluetoothAdapterService: Autoconnection is available 
09-08 18:23:53.991  6435  6786 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-08 18:23:54.001  6435  6786 D BluetoothSecureManager: getInstant: null
09-08 18:23:54.001  6435  6786 D BluetoothSecureManager: calling getMethod for getService
09-08 18:23:54.001  6435  6786 D BluetoothSecureManager: calling getService
,09-08 18:23:54.001  6435  6786 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@2c6e408
,09-08 18:23:54.001  1015  3140 D BluetoothSecureManagerService: isSecureModeEnabled
,09-08 18:23:54.001  1015  3140 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,09-08 18:23:54.001  6435  6786 D BtConfig.SecureMode: isSecureModeOn:false
09-08 18:23:54.001  6435  6786 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-08 18:23:54.001  6435  6786 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
09-08 18:23:54.001  6435  6786 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-08 18:23:54.001  1883  1883 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-08 18:23:54.001  6435  6786 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
09-08 18:23:54.001  6435  6786 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-08 18:23:54.001  6435  6786 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
09-08 18:23:54.001  6435  6786 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-08 18:23:54.001  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-08 18:23:54.001  6435  6786 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
09-08 18:23:54.001  6435  6786 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-08 18:23:54.001  6435  6786 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
09-08 18:23:54.001  6435  6786 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-08 18:23:54.001  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-08 18:23:54.001  6435  6786 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
09-08 18:23:54.001  1174  1174 D BluetoothTile:  getBluetoothState : 11
09-08 18:23:54.001  6435  6786 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-08 18:23:54.001  6435  6786 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
,09-08 18:23:54.001  6435  6786 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-08 18:23:54.011  6435  6786 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
09-08 18:23:54.011  6435  6786 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-08 18:23:54.011  6435  6786 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-08 18:23:54.011  6435  6786 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-08 18:23:54.011  1174  1702 D BluetoothTile:  handleUpdatestate:false name:null
09-08 18:23:54.011  1174  1702 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-08 18:23:54.011  6435  6786 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-08 18:23:54.011  6435  6786 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-08 18:23:54.011  6435  6786 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
,09-08 18:23:54.011  6435  6786 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-08 18:23:54.011  6435  6786 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
09-08 18:23:54.011  1015  3002 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-08 18:23:54.011  1015  3238 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-08 18:23:54.011  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-08 18:23:54.021  1300  1300 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-08 18:23:54.021  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:54.021  6435  6786 D BluetoothBondStateMachine: make
,09-08 18:23:54.021  1015  3223 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-08 18:23:54.021  1015  3223 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-08 18:23:54.021  1015  3223 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:54.021  1015  3223 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:54.021  1015  3223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:54.021  6435  6786 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,09-08 18:23:54.021  6435  6786 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-08 18:23:54.021  6435  6786 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-08 18:23:54.021  6435  6790 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-08 18:23:54.021  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:54.021  1015  3003 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:23:54.021  1015  3003 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-08 18:23:54.021  1015  3003 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:54.021  1015  3003 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.021  1015  3003 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:54.031  6435  6786 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,09-08 18:23:54.031  6435  6786 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-08 18:23:54.031  6435  6786 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-08 18:23:54.031  6435  6435 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 18:23:54.031  6435  6435 D BtGatt.GattService: Received start request. Starting profile...
09-08 18:23:54.031  6435  6435 D BtGatt.GattService: start()
09-08 18:23:54.031  6435  6435 D BtGatt.GattService: start()
09-08 18:23:54.031  6435  6435 I bluedroid: get_profile_interface gatt
,09-08 18:23:54.031  6435  6435 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a225333
09-08 18:23:54.031  6435  6435 D BtGatt.AdvertiseManager: advertise manager created
,09-08 18:23:54.031  1300  1300 D BluetoothNotiBroadcastReceiver: onReceive
,09-08 18:23:54.031  1015  3235 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:23:54.031  1015  3235 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-08 18:23:54.031  1015  3235 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:54.031  1015  3235 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.031  1015  3235 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:54.041  6435  6786 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,09-08 18:23:54.041  6435  6786 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-08 18:23:54.041  6435  6786 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-08 18:23:54.041  1015  3140 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:23:54.041  1015  3140 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-08 18:23:54.041  6435  6435 D BtGatt.GattService: mStartError = false
09-08 18:23:54.041  6435  6435 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a225333
,09-08 18:23:54.041  1015  3140 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:54.041  1015  3140 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.041  1015  3140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:54.051  6435  6435 D HeadsetService: Received start request. Starting profile...
09-08 18:23:54.051  6435  6435 D HeadsetService: start()
,09-08 18:23:54.051  6435  6435 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-08 18:23:54.051  6435  6435 D HeadsetStateMachine: make
09-08 18:23:54.051  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-08 18:23:54.051  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-08 18:23:54.051  6435  6435 E HeadsetStateMachine: # of Max HF connection is 2
,09-08 18:23:54.061  6435  6786 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,09-08 18:23:54.061  6435  6786 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-08 18:23:54.061  6435  6786 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-08 18:23:54.061  1015  1027 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,09-08 18:23:54.061  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-08 18:23:54.061  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:54.061  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.061  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-08 18:23:54.061  1015  1383 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:23:54.061  1015  1383 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-08 18:23:54.071  1015  1383 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:54.071  1015  1383 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.071  1015  1383 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:54.071  6435  6786 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-08 18:23:54.071  6435  6786 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-08 18:23:54.071  6435  6786 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-08 18:23:54.071  1015  1383 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,09-08 18:23:54.071  1015  1383 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-08 18:23:54.071  1015  1383 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:54.071  1015  1383 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.071  1015  1383 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-08 18:23:54.071  1015  1138 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:23:54.071  6435  6435 I bluedroid: get_profile_interface handsfree
,09-08 18:23:54.081  1015  1138 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-08 18:23:54.081  1015  1138 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:54.081  1015  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.081  1015  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:54.081  6435  6786 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,09-08 18:23:54.081  6435  6786 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-08 18:23:54.081  6435  6786 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-08 18:23:54.081  1015  3224 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:23:54.081  1015  3224 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-08 18:23:54.081  1015  3224 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:54.081  1015  3224 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.081  1015  3224 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:54.091  6435  6786 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-08 18:23:54.091  6435  6786 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-08 18:23:54.091  6435  6786 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-08 18:23:54.091  1015  1251 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:23:54.091  1015  1251 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-08 18:23:54.091  1015  1251 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:54.091  1015  1251 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.091  1015  1251 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:54.091  6435  6786 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService,
09-08 18:23:54.091  6435  6786 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-08 18:23:54.091  6435  6786 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-08 18:23:54.091  1015  3223 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:23:54.101  1015  3223 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-08 18:23:54.101  1015  3223 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:54.101  1015  3223 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.101  1015  3223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:54.101  6435  6435 I DualScoManager: Instantiating Dual Sco Manager
09-08 18:23:54.101  6435  6435 I DualScoManager: Set HeadsetServiceHelper
,09-08 18:23:54.101  6435  6786 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-08 18:23:54.101  6435  6786 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-08 18:23:54.101  6435  6786 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,09-08 18:23:54.101  6435  6786 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-08 18:23:54.101  6435  6786 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-08 18:23:54.101  6435  6435 D BluetoothAtMessage: createCMTIContentObservers
,09-08 18:23:54.101  6435  6786 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-08 18:23:54.101  6435  6786 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
,09-08 18:23:54.101  6435  6786 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-08 18:23:54.101  6435  6786 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-08 18:23:54.101  6435  6786 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-08 18:23:54.101  6435  6786 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-08 18:23:54.101  6435  6786 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-08 18:23:54.101  6435  6786 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-08 18:23:54.101  1015  1494 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
09-08 18:23:54.101  1015  1494 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-08 18:23:54.101  1015  1494 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-08 18:23:54.101  1015  1494 D SettingsProvider: selectionArgs: false
09-08 18:23:54.101  1015  1494 D SettingsProvider: selectionArgs: 1002
09-08 18:23:54.101  1015  1494 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-08 18:23:54.101  1015  1494 D SettingsProvider: ret = -1
,09-08 18:23:54.101  6435  6794 D HeadsetStateMachine: Enter Disconnected: -2
,09-08 18:23:54.111  6435  6435 D HeadsetService: mStartError = false
09-08 18:23:54.111  6435  6435 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a225333
,09-08 18:23:54.111  6435  6435 E BluetoothAdapterService(438457139): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,09-08 18:23:54.111  6435  6794 D HeadsetStateMachine: Clear mHeadsetBrsf
09-08 18:23:54.111  6435  6794 D HeadsetStateMachine: map size, before remove : 0
09-08 18:23:54.111  6435  6794 D HeadsetStateMachine: map size, after remove: 0
,09-08 18:23:54.111  6435  6435 D A2dpService: Received start request. Starting profile...
,09-08 18:23:54.111  6435  6435 D A2dpService: start()
,09-08 18:23:54.111  6435  6435 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-08 18:23:54.111  6435  6435 I bluedroid: get_profile_interface avrcp
,09-08 18:23:54.121  6435  6435 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-08 18:23:54.131  6435  6435 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-08 18:23:54.131  6435  6800 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-08 18:23:54.141  6435  6435 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-08 18:23:54.141  6435  6435 D A2dpStateMachine: make
,09-08 18:23:54.141  6435  6435 I bluedroid: get_profile_interface a2dp
,09-08 18:23:54.141  6435  6802 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-08 18:23:54.141  6435  6435 E bt-btif : warning : media task started media_task_refcnt 1 
,09-08 18:23:54.141  6435  6435 D A2dpService: mStartError = false
09-08 18:23:54.141  6435  6435 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a225333
,09-08 18:23:54.141  6435  6435 D HeadsetStateMachine: Try to query the phonestate on bind
,09-08 18:23:54.141  6435  6801 D A2dpStateMachine: Enter Disconnected: -2
,09-08 18:23:54.141  1431  6352 I Telecom : BluetoothPhoneService: queryPhoneState
,09-08 18:23:54.141  1431  1431 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,09-08 18:23:54.151  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-08 18:23:54.151  1431  6352 I Telecom : BluetoothPhoneService: Result of Message : true
,09-08 18:23:54.151  6435  6435 I BluetoothHidServiceJni: classInitNative: succeeds
,09-08 18:23:54.151  6435  6435 D HidService: Received start request. Starting profile...
09-08 18:23:54.151  6435  6435 D HidService: start()
09-08 18:23:54.151  6435  6435 I bluedroid: get_profile_interface hidhost
09-08 18:23:54.151  6435  6435 D HidService: setHidService(): set to: null
09-08 18:23:54.151  6435  6435 D HidService: mStartError = false
09-08 18:23:54.151  6435  6435 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a225333
,09-08 18:23:54.151  6435  6435 D HeadsetStateMachine: Proxy object connected
,09-08 18:23:54.151  6435  6435 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-08 18:23:54.151  6435  6435 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-08 18:23:54.151  6435  6794 D HeadsetStateMachine: Disconnected process message: 11
,09-08 18:23:54.151  6435  6435 D HealthService: Received start request. Starting profile...
09-08 18:23:54.151  6435  6435 D HealthService: start()
,09-08 18:23:54.161  6435  6800 D BluetoothMediaBrowser: no now playing list
,09-08 18:23:54.161  6435  6800 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-08 18:23:54.161  6435  6435 I bluedroid: get_profile_interface health
09-08 18:23:54.161  6435  6435 D HealthService: mStartError = false
09-08 18:23:54.161  6435  6435 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a225333
,09-08 18:23:54.161  6435  6435 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-08 18:23:54.161  6435  6435 D PanService: Received start request. Starting profile...
09-08 18:23:54.161  6435  6435 D PanService: start()
09-08 18:23:54.161  6435  6435 D BluetoothPanServiceJni: initializeNative(L110): pan
09-08 18:23:54.161  6435  6435 I bluedroid: get_profile_interface pan
,09-08 18:23:54.161  6435  6435 D PanService: mStartError = false
09-08 18:23:54.161  6435  6435 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a225333
,09-08 18:23:54.161  1907  1907 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-08 18:23:54.161  6435  6435 D HeadsetPhoneState: sendDeviceDataStateChanged
09-08 18:23:54.171  6435  6794 D HeadsetStateMachine: Disconnected process message: 18
,09-08 18:23:54.171  6435  6435 D BluetoothMapService: Received start request. Starting profile...
09-08 18:23:54.171  6435  6435 D BluetoothMapService: start()
,09-08 18:23:54.171  1907  1907 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-08 18:23:54.171  6435  6435 D BluetoothMapService: mStartError = false
,09-08 18:23:54.171  6435  6435 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a225333
,09-08 18:23:54.171  6435  6435 D HeadsetPhoneState: Signal level : previous=0 curr=0
,09-08 18:23:54.171  6435  6435 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,09-08 18:23:54.171  6435  6435 D SapService: Received start request. Starting profile...
09-08 18:23:54.171  6435  6435 D SapService: start()
09-08 18:23:54.171  6435  6435 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-08 18:23:54.171  6435  6435 I bluedroid: get_profile_interface sap
09-08 18:23:54.171  6435  6435 D SapService: mStartError = false
09-08 18:23:54.171  6435  6435 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a225333
09-08 18:23:54.171  6435  6435 E BluetoothAdapterService(438457139): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,09-08 18:23:54.171  6435  6435 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-08 18:23:54.171  6435  6435 D BluetoothA2dp: Proxy object connected
09-08 18:23:54.171  6435  6435 D BluetoothAdapterService: Bluetooth A2dp source service connected
09-08 18:23:54.171  6435  6435 E BluetoothAdapterService(438457139): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-08 18:23:54.171  6435  6794 D HeadsetStateMachine: Disconnected process message: 10
09-08 18:23:54.171  6435  6435 E BluetoothAdapterService(438457139): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,09-08 18:23:54.171  6435  6794 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
09-08 18:23:54.171  6435  6794 D HeadsetStateMachine: Disconnected process message: 11
,09-08 18:23:54.181  6435  6435 E BluetoothAdapterService(438457139): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-08 18:23:54.181  6435  6435 E BluetoothAdapterService(438457139): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-08 18:23:54.201  6435  6435 E BluetoothAdapterService(438457139): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-08 18:23:54.201  6435  6435 E BluetoothAdapterService(438457139): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-08 18:23:54.211  6435  6786 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-08 18:23:54.211  6435  6786 I bluedroid: enable
,09-08 18:23:54.211  6435  6786 I bt_hci_bdroid: init
,09-08 18:23:54.211  6435  6807 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,09-08 18:23:54.211  6435  6786 I bt_vendor: bt-vendor : init
,09-08 18:23:54.211  6435  6786 I bt_vendor: bt-vendor : get_bt_soc_type
09-08 18:23:54.211  6435  6786 E bt_vendor: get_bt_soc_type: Failed to get soc type
,09-08 18:23:54.211  6435  6786 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
09-08 18:23:54.211  6435  6786 D bt_userial_mct: userial_init
,09-08 18:23:54.211  6435  6786 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-08 18:23:54.211  6435  6786 I bt_vendor: Starting hciattach daemon
09-08 18:23:54.211  6435  6786 I bt_vendor: try to set false
,09-08 18:23:54.221  6435  6786 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,09-08 18:23:54.221  6435  6786 I bt_vendor: Starting hciattach daemon
09-08 18:23:54.221  6435  6786 I bt_vendor: try to set true
,09-08 18:23:54.231  6811  6811 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,09-08 18:23:54.281  6817  6817 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,09-08 18:23:54.291  6818  6818 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-08 18:23:54.301  6820  6820 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-08 18:23:54.311  6821  6821 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,09-08 18:23:54.321  6822  6822 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-08 18:23:54.331  6823  6823 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,09-08 18:23:54.591  6826  6826 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,09-08 18:23:54.601  6827  6827 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-08 18:23:54.631  6435  6786 I bt_vendor: bluetooth satus is on,
09-08 18:23:54.631  6435  6809 D bt_userial_mct: userial_open(port:0)
09-08 18:23:54.631  6435  6809 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-08 18:23:54.631  6435  6809 I bt_vendor: Done intiailizing UART,
,09-08 18:23:54.631  6435  6809 I bt_vendor: Done intiailizing UART
09-08 18:23:54.631  6435  6809 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-08 18:23:54.631  6435  6809 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-08 18:23:54.641  6435  6829 D bt_userial_mct: Entering userial_read_thread()
,09-08 18:23:54.641  6435  6807 I         : BTE_InitTraceLevels -- TRC_HCI
,09-08 18:23:54.641  6435  6807 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-08 18:23:54.641  6435  6807 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-08 18:23:54.641  6435  6807 I         : BTE_InitTraceLevels -- TRC_AVDT
09-08 18:23:54.641  6435  6807 I         : BTE_InitTraceLevels -- TRC_AVRC
09-08 18:23:54.641  6435  6807 I         : BTE_InitTraceLevels -- TRC_A2D
09-08 18:23:54.641  6435  6807 I         : BTE_InitTraceLevels -- TRC_BNEP
09-08 18:23:54.641  6435  6807 I         : BTE_InitTraceLevels -- TRC_BTM
,09-08 18:23:54.641  6435  6807 I         : BTE_InitTraceLevels -- TRC_GAP
09-08 18:23:54.641  6435  6807 I         : BTE_InitTraceLevels -- TRC_PAN
09-08 18:23:54.641  6435  6807 I         : BTE_InitTraceLevels -- TRC_SAP
09-08 18:23:54.641  6435  6807 I         : BTE_InitTraceLevels -- TRC_SDP
09-08 18:23:54.641  6435  6807 I         : BTE_InitTraceLevels -- TRC_GATT
09-08 18:23:54.641  6435  6807 I         : BTE_InitTraceLevels -- TRC_SMP
09-08 18:23:54.641  6435  6807 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-08 18:23:54.641  6435  6807 I         : BTE_InitTraceLevels -- TRC_BTIF
09-08 18:23:54.641  6435  6807 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,09-08 18:23:54.741  6435  6807 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,09-08 18:23:54.751  6435  6807 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa40826e9 
,09-08 18:23:54.751  6435  6807 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa40826e9 
,09-08 18:23:54.771  6435  6789 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,09-08 18:23:54.771  6435  6789 E bt-btif : Calling BTA_HhEnable
,09-08 18:23:54.771  6435  6789 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-08 18:23:54.771  6435  6789 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
09-08 18:23:54.771  6435  6789 E BluetoothServiceJni: populateRssiValuesNative
,09-08 18:23:54.771  6435  6789 I bluedroid: getModelRssiValues
09-08 18:23:54.771  6435  6789 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-08 18:23:54.771  6435  6789 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-08 18:23:54.771  6435  6789 D BluetoothAdapterProperties: Name is: A5-1
,09-08 18:23:54.771  1015  1015 D SettingsProvider: name = bluetooth_name
,09-08 18:23:54.781  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:54.781  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:54.781  6435  6789 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-08 18:23:54.781  6435  6789 D BluetoothAdapterProperties: Scan Mode:20
09-08 18:23:54.781  6435  6789 D BluetoothAdapterProperties: Discoverable Timeout:120
09-08 18:23:54.781  6435  6789 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
09-08 18:23:54.781  6435  6789 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
09-08 18:23:54.781  6435  6789 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
09-08 18:23:54.781  6435  6789 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-08 18:23:54.781  6435  6789 E bt-btif : btif_sock_init: !vhci_init
09-08 18:23:54.781  6435  6789 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,09-08 18:23:54.781  6435  6789 D IOP_DB_BT: db_open: db_open : handle 3023798288l, read 13894 bytes onto local cache
,09-08 18:23:54.781  6435  6789 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,09-08 18:23:54.781  6435  6789 D IOP_DB_BT: db_query: result 1
09-08 18:23:54.781  6435  6789 I         : iop_db_open: iop_db_open status 0
,09-08 18:23:54.791  6435  6789 D bte_conf: Device ID record 1 : primary
09-08 18:23:54.791  6435  6789 D bte_conf:   vendorId            = 0075
09-08 18:23:54.791  6435  6789 D bte_conf:   vendorIdSource      = 0001
,09-08 18:23:54.791  6435  6789 D bte_conf:   product             = 0100
09-08 18:23:54.791  6435  6789 D bte_conf:   version             = 0200
09-08 18:23:54.791  6435  6789 D bte_conf:   clientExecutableURL = 
,09-08 18:23:54.791  6435  6789 D bte_conf:   serviceDescription  = 
09-08 18:23:54.791  6435  6789 D bte_conf:   documentationURL    = 
09-08 18:23:54.791  6435  6789 D bte_conf: bte_load_did_conf no section named DID2.
,09-08 18:23:54.791  6435  6829 E bt_mct  : hci lib postload completed
,09-08 18:23:54.791  6435  6789 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-08 18:23:54.791  6435  6786 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-08 18:23:54.791  6435  6786 D BluetoothAdapterProperties: ScanMode =  20
09-08 18:23:54.791  6435  6786 D BluetoothAdapterProperties: State =  11
,09-08 18:23:54.791  1015  1138 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-08 18:23:54.791  6435  6786 D BluetoothAdapterProperties: Setting state to 12
09-08 18:23:54.791  6435  6786 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-08 18:23:54.801  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:54.801  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:54.801  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:54.801  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:23:54.801  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:23:54.801  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:23:54.801  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:23:54.801  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 18:23:54.801  6147  6147 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null,
,09-08 18:23:54.811  6435  6789 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-08 18:23:54.811  6435  6789 D BluetoothAdapterProperties: Scan Mode:21
09-08 18:23:54.811  6435  6789 D BluetoothAdapterProperties: Discoverable Timeout:120
09-08 18:23:54.811  1015  1494 D SettingsProvider: name = bluetooth_a2dp_sink_mode
09-08 18:23:54.811  1015  1494 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-08 18:23:54.811  1015  1494 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-08 18:23:54.811  1015  1494 D SettingsProvider: selectionArgs: false
09-08 18:23:54.811  1015  1494 D SettingsProvider: selectionArgs: 1002
09-08 18:23:54.811  1015  1494 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-08 18:23:54.811  1015  1494 D SettingsProvider: ret = -1
09-08 18:23:54.811  6435  6786 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-08 18:23:54.811  6435  6786 D BluetoothAdapterService: updateAdapterState state is 12
09-08 18:23:54.811  1015  1494 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:23:54.811  1015  1494 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
09-08 18:23:54.811  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:54.811  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:54.811  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:54.811  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:23:54.811  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:23:54.811  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:23:54.811  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:23:54.811  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 18:23:54.821  1015  1494 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:54.821  1015  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.821  1015  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:54.821  1015  1045 D BluetoothAdapter: onBluetoothStateChange: up=true
09-08 18:23:54.821  1015  1045 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-08 18:23:54.821  6435  6786 D BluetoothAdapterService: Autoconnection is available 
09-08 18:23:54.821  6435  6786 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-08 18:23:54.821  6435  6786 D BluetoothAdapterService: starting service from this receiver
,09-08 18:23:54.821  1015  1342 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-08 18:23:54.831  1015  1342 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-08 18:23:54.831  1015  3223 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-08 18:23:54.831  1015  1342 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:54.831  1015  1342 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 18:23:54.831  1015  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-08 18:23:54.831  2865  2895 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-08 18:23:54.831  6435  6786 I BluetoothAdapterState: Entering On State from state = 11
,09-08 18:23:54.831  1015  3223 D BatteryService: level:83, scale:100, status:2, health:2, present:true, voltage: 4081, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,09-08 18:23:54.831  1015  3223 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,09-08 18:23:54.841  1015  3223 D BatteryService: stay LED for charging
09-08 18:23:54.841  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-08 18:23:54.841  2865  2895 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-08 18:23:54.841  6147  6147 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 18:23:54.841  6435  6435 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-08 18:23:54.841  1015  1015 I MotionRecognitionService: Plugged
,09-08 18:23:54.841  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,09-08 18:23:54.851  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-08 18:23:54.851  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-08 18:23:54.851  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-08 18:23:54.851  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 83
,09-08 18:23:54.861  1015  1045 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-08 18:23:54.861  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-08 18:23:54.861  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:54.861  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.861  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:54.871  1300  1317 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-08 18:23:54.871  1300  1317 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-08 18:23:54.871  1300  1311 D BluetoothPan: Binding service...
,09-08 18:23:54.871  2865  2865 D BluetoothA2dp: Proxy object connected
,09-08 18:23:54.871  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-08 18:23:54.871  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-08 18:23:54.871  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:54.871  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.871  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:54.871  1452  1868 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-08 18:23:54.871  6435  6435 I BluetoothPbapService: Handler(): got msg=1
09-08 18:23:54.871  1015  1045 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-08 18:23:54.871  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-08 18:23:54.881  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:54.881  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.881  1015  3003 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
09-08 18:23:54.881  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:54.881  1452  1868 E BluetoothHeadset: BluetoothHeadset service is binded
09-08 18:23:54.881  6316  6327 D BluetoothAdapter: onBluetoothStateChange: up=true
09-08 18:23:54.881  6316  6327 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-08 18:23:54.881  1015  1045 D BluetoothPan: Binding service...
,09-08 18:23:54.881  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-08 18:23:54.881  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-08 18:23:54.881  1015  1045 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 18:23:54.881  1015  1045 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-08 18:23:54.881  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-08 18:23:54.881  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-08 18:23:54.881  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:83 status:2 health:2
09-08 18:23:54.881  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:83 status:2 health:2
,09-08 18:23:54.881  1439  1464 D BluetoothAdapter: onBluetoothStateChange: up=true
09-08 18:23:54.881  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:83 status:2 health:2
09-08 18:23:54.881  1015  1015 D BluetoothA2dp: Proxy object connected
09-08 18:23:54.881  1439  1464 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-08 18:23:54.881  6435  6435 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-08 18:23:54.881  6435  6794 D HeadsetStateMachine: Disconnected process message: 10
,09-08 18:23:54.881  1015  1045 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-08 18:23:54.881  1300  1300 D BluetoothPan: BluetoothPAN Proxy object connected
09-08 18:23:54.881  1015  1015 D BluetoothPan: BluetoothPAN Proxy object connected
09-08 18:23:54.881  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-08 18:23:54.881  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-08 18:23:54.881  1015  1045 E BluetoothHeadset: BluetoothHeadset service is binded
09-08 18:23:54.881  1300  1300 D PanProfile: Bluetooth service connected
09-08 18:23:54.881  1300  1311 D Bluetoothsap: onBluetoothStateChange: up=true
09-08 18:23:54.881  1300  1311 D Bluetoothsap: Binding service...
,09-08 18:23:54.881  6435  6833 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-08 18:23:54.881  1300  1311 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-08 18:23:54.891  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-08 18:23:54.891  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-08 18:23:54.891  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:54.891  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.891  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:54.891  1300  1311 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-08 18:23:54.891  6435  6795 D BluetoothAdapter: onBluetoothStateChange: up=true
09-08 18:23:54.891  6435  6795 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-08 18:23:54.891  1431  1444 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-08 18:23:54.891  1300  1300 D Bluetoothsap: BluetoothSAP Proxy object connected
09-08 18:23:54.891  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-08 18:23:54.891  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-08 18:23:54.891  1300  1300 D SapProfile: Bluetooth service connected
,09-08 18:23:54.891  6435  6833 D BluetoothSocket: bindListen(): myUserId = 0
09-08 18:23:54.891  1300  1300 D Bluetoothsap: getConnectedDevices()
09-08 18:23:54.891  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:54.891  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.891  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:54.891  1431  1444 E BluetoothHeadset: BluetoothHeadset service is binded
09-08 18:23:54.891  6435  6833 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 18:23:54.891  6147  6157 D BluetoothAdapter: onBluetoothStateChange: up=true
09-08 18:23:54.891  6147  6157 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-08 18:23:54.891  1300  1311 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-08 18:23:54.901  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-08 18:23:54.901  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-08 18:23:54.901  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:54.901  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.901  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:54.901  1300  1311 E BluetoothHeadset: BluetoothHeadset service is binded
,09-08 18:23:54.901  1300  1300 D HeadsetProfile: Bluetooth service connected
09-08 18:23:54.901  1452  1785 D BluetoothAdapter: onBluetoothStateChange: up=true
09-08 18:23:54.901  6435  6833 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
09-08 18:23:54.901  6435  6833 D BluetoothSocket: bindListen(), new LocalSocket 
09-08 18:23:54.901  6435  6833 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-08 18:23:54.901  6435  6833 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@162e7eac
,09-08 18:23:54.901  1452  1785 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-08 18:23:54.901  6435  6833 D BluetoothSocket: channel: 19
09-08 18:23:54.901  6435  6796 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 18:23:54.901  6435  6833 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-08 18:23:54.901  1300  1317 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-08 18:23:54.901  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
09-08 18:23:54.901  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-08 18:23:54.901  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:54.901  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.901  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:54.901  1300  1311 D BluetoothPbap: onBluetoothStateChange: up=true
,09-08 18:23:54.911  1300  1300 D BluetoothInputDevice: Proxy object connected
,09-08 18:23:54.911  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-08 18:23:54.911  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
09-08 18:23:54.911  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:54.911  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.911  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-08 18:23:54.911  1300  1300 D HidProfile: Bluetooth service connected
,09-08 18:23:54.911  1174  1679 D BluetoothAdapter: onBluetoothStateChange: up=true
09-08 18:23:54.911  1174  1679 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-08 18:23:54.911  1431  2721 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-08 18:23:54.911  1300  1300 D BluetoothPbap: Proxy object connected
09-08 18:23:54.911  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-08 18:23:54.911  1300  1300 D PbapServerProfile: Bluetooth service connected
09-08 18:23:54.911  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-08 18:23:54.911  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:54.911  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.911  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:54.911  1431  2721 E BluetoothHeadset: BluetoothHeadset service is binded
,09-08 18:23:54.911  2865  2876 D BluetoothAdapter: onBluetoothStateChange: up=true
09-08 18:23:54.911  2865  2876 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-08 18:23:54.911  1431  1449 D BluetoothAdapter: onBluetoothStateChange: up=true
09-08 18:23:54.911  1431  1449 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-08 18:23:54.911  1300  6834 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-08 18:23:54.911  1300  6834 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-08 18:23:54.911  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-08 18:23:54.911  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-08 18:23:54.921  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:54.921  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.921  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:54.921  1300  1300 D BluetoothA2dp: Proxy object connected
,09-08 18:23:54.921  1300  1300 D A2dpProfile: Bluetooth service connected
09-08 18:23:54.921  2865  2879 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-08 18:23:54.921  1015  1045 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-08 18:23:54.921  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-08 18:23:54.921  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:54.921  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.921  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:54.921  2865  2879 E BluetoothHeadset: BluetoothHeadset service is binded
,09-08 18:23:54.921  1431  1444 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-08 18:23:54.921  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-08 18:23:54.921  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-08 18:23:54.921  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:54.921  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.921  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:54.931  1431  1444 E BluetoothHeadset: BluetoothHeadset service is binded
,09-08 18:23:54.931  1907  1917 D BluetoothAdapter: onBluetoothStateChange: up=true
09-08 18:23:54.931  1907  1917 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-08 18:23:54.931  1300  1317 D BluetoothMap: onBluetoothStateChange: up=true
,09-08 18:23:54.931  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
09-08 18:23:54.931  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-08 18:23:54.931  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:54.931  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:54.931  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:54.931  1300  1300 D BluetoothMap: Proxy object connected
09-08 18:23:54.931  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-08 18:23:54.931  1300  1300 D MapProfile: Bluetooth service connected
09-08 18:23:54.931  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
09-08 18:23:54.931  1300  1300 D BluetoothMap: getConnectedDevices()
,09-08 18:23:54.931  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:54.931  1015  1015 I InputMethodManagerService: [BT Setting State] State =12
09-08 18:23:54.931  1015  1015 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-08 18:23:54.941  1174  1174 D BluetoothTile:  onBluetoothStateChange:
,09-08 18:23:54.941  1431  1431 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@249ca58b, true
,09-08 18:23:54.941  1431  1431 D BluetoothHeadset: registerMessageListener
,09-08 18:23:54.941  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-08 18:23:54.941  1883  1883 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-08 18:23:54.941  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:54.941  1174  1174 D BluetoothTile:  getBluetoothState : 12
,09-08 18:23:54.951  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:54.951  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:54.951  1174  1702 D BluetoothTile:  handleUpdatestate:false name:null
,09-08 18:23:54.951  1015  3140 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-08 18:23:54.951  1015  3140 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-08 18:23:54.951  1015  3140 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:54.951  1015  3140 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
09-08 18:23:54.951  1174  1702 D BluetoothTile:  handleUpdatestate:false name:null
09-08 18:23:54.951  1015  3140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-08 18:23:54.961  1300  1300 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:54.961  6435  6795 D HeadsetService: registerMessageListener
,09-08 18:23:54.961  6435  6795 D HeadsetService: registerMessageListener
09-08 18:23:54.961  6435  6836 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-08 18:23:54.961  1431  1431 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-08 18:23:54.961  6435  6794 D HeadsetStateMachine: Disconnected process message: 70
09-08 18:23:54.961  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-08 18:23:54.961  6435  6794 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@16c8775
09-08 18:23:54.961  1015  3235 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-08 18:23:54.961  1300  1300 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-08 18:23:54.961  1015  1251 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-08 18:23:54.961  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-08 18:23:54.961  1431  1431 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-08 18:23:54.961  1431  1431 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
09-08 18:23:54.961  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
09-08 18:23:54.961  1300  1300 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-08 18:23:54.961  1174  1702 D BluetoothTile:  handleUpdatestate:false name:null
,09-08 18:23:54.961  1300  1300 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-08 18:23:54.961  1300  1300 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-08 18:23:54.961  6435  6836 D BluetoothSocket: bindListen(): myUserId = 0
09-08 18:23:54.961  6435  6836 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 18:23:54.971  6435  6794 D HeadsetStateMachine: Disconnected process message: 9
09-08 18:23:54.971  6435  6794 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
09-08 18:23:54.971  6435  6836 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
09-08 18:23:54.971  6435  6836 D BluetoothSocket: bindListen(), new LocalSocket 
09-08 18:23:54.971  6435  6836 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-08 18:23:54.971  6435  6836 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@25f9830a
,09-08 18:23:54.971  6435  6836 D BluetoothSocket: channel: 5
,09-08 18:23:54.971   284   284 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,09-08 18:23:54.971   284   284 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-08 18:23:54.971   284   284 V voice   : voice_set_parameters: exit with code(-2)
09-08 18:23:54.971   284   284 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
,09-08 18:23:54.971   284   284 V msm8974_platform: platform_set_parameters: exit with code(-2)
,09-08 18:23:54.971   284   284 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-08 18:23:54.971   284   284 V audio_hw_primary: adev_set_parameters: exit
09-08 18:23:54.981  6435  6794 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-08 18:23:54.981  1300  1300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 18:23:54.981  1015  1027 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-08 18:23:54.981  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-08 18:23:54.981  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:54.981  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 18:23:54.981  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-08 18:23:54.991  1300  1300 D DockEventReceiver: finishStartingService: stopping service
,09-08 18:23:54.991  1300  1300 D BluetoothNotiBroadcastReceiver: onReceive
,09-08 18:23:55.001  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:55.001  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-08 18:23:55.011  6435  6435 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a225333
,09-08 18:23:55.011  6435  6435 D BtConfig.SecureMode: isSecureModeOn:false
,09-08 18:23:55.011  1015  1251 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-08 18:23:55.011  1015  1251 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-08 18:23:55.011  1015  1251 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:55.011  1015  1251 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:55.011  1015  1251 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:55.031  1907  1907 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-08 18:23:55.031  1015  1494 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-08 18:23:55.031  1015  1494 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-08 18:23:55.031  1015  1494 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:55.031  1015  1494 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:55.031  1015  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:55.041  1015  3223 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-08 18:23:55.051  1907  6845 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-08 18:23:55.051  1907  1907 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-08 18:23:55.051  1015  3003 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 18:23:55.061  1015  3003 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:55.061  1015  3003 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:55.061  1015  3003 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:55.071  1015  1138 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 18:23:55.071  6435  6846 D BluetoothSocket: bindListen(): myUserId = 0
09-08 18:23:55.071  6435  6846 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 18:23:55.071  1015  1138 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:55.071  1015  1138 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:55.071  1015  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:55.081  6435  6846 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
,09-08 18:23:55.081  6435  6846 D BluetoothSocket: bindListen(), new LocalSocket 
09-08 18:23:55.081  6435  6846 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-08 18:23:55.081  6435  6846 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@234c5d6
09-08 18:23:55.081  6435  6846 D BluetoothSocket: channel: 12
09-08 18:23:55.081  6435  6846 I BtOppRfcommListener: Accept thread started.
,09-08 18:23:55.081  1907  6845 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,09-08 18:23:55.161  1015  2769 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-08 18:23:55.501   289   289 E SMD     : DCD OFF
,09-08 18:23:55.521  1015  2723 D SSRM:n  : SIOP:: AP = 370
,09-08 18:23:56.871  1015  1307 E Watchdog: !@Sync 4,
,09-08 18:23:56.891  6147  6197 D BluetoothAdapter: disable()
,09-08 18:23:56.891  1015  1494 D SettingsProvider: name = bluetooth_on
,09-08 18:23:56.901  6435  6786 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
09-08 18:23:56.901  6435  6786 D BluetoothAdapterProperties: Setting state to 13
09-08 18:23:56.901  6435  6786 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-08 18:23:56.901  6435  6786 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-08 18:23:56.901  6435  6786 D BluetoothAdapterService: updateAdapterState state is 13
,09-08 18:23:56.901  1015  1564 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:23:56.901  1015  1564 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-08 18:23:56.901  1015  1564 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:56.901  1015  1564 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:56.901  1015  1564 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:56.911  6435  6435 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-08 18:23:56.911  6435  6435 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1e43a057, channel: 19, state: LISTENING
09-08 18:23:56.911  6435  6435 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1e43a057, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@162e7eac, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@17eff744mSocket: android.net.LocalSocket@111b302d impl:android.net.LocalSocketImpl@10f6962 fd:FileDescriptor[75]
09-08 18:23:56.911  6435  6435 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@111b302d impl:android.net.LocalSocketImpl@10f6962 fd:FileDescriptor[75]
09-08 18:23:56.911  6435  6786 D BluetoothAdapterService: Autoconnection is available 
09-08 18:23:56.911  6435  6786 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-08 18:23:56.911  6435  6786 D BluetoothAdapterService: terminating service from this receiver
,09-08 18:23:56.911  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:56.911  1015  1015 I InputMethodManagerService: [BT Setting State] State =13
,09-08 18:23:56.911  1174  1174 D BluetoothTile:  onBluetoothStateChange:
,09-08 18:23:56.921  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-08 18:23:56.921  1174  1702 D BluetoothTile:  handleUpdatestate:false name:null
,09-08 18:23:56.921  1174  1702 D BluetoothTile:  handleUpdatestate:false name:null
,09-08 18:23:56.921  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-08 18:23:56.921  1174  1174 D BluetoothTile:  getBluetoothState : 13
,09-08 18:23:56.921  1174  1702 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-08 18:23:56.931  1883  1883 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-08 18:23:56.931  1300  1300 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:56.931  1015  3235 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-08 18:23:56.931  1015  1027 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-08 18:23:56.931  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-08 18:23:56.931  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-08 18:23:56.931  6147  6147 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:56.931  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:56.931  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:56.931  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:56.931  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:23:56.931  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:23:56.931  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:23:56.931  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:23:56.931  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 18:23:56.941  6147  6147 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:56.941  6147  6147 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 18:23:56.941  1015  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-08 18:23:56.941  6435  6435 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@977eaf3, channel: 5, state: LISTENING
09-08 18:23:56.941  6435  6435 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@977eaf3, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@25f9830a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3c9743b0mSocket: android.net.LocalSocket@2d27a229 impl:android.net.LocalSocketImpl@21feb9ae fd:FileDescriptor[77]
09-08 18:23:56.941  6435  6435 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2d27a229 impl:android.net.LocalSocketImpl@21feb9ae fd:FileDescriptor[77]
,09-08 18:23:56.941  1015  1487 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:56.941  1015  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:56.941  6435  6435 I BtOppRfcommListener: stopping Accept Thread
09-08 18:23:56.941  1015  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-08 18:23:56.941  6435  6435 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@209c434f, channel: 12, state: LISTENING
09-08 18:23:56.941  6435  6435 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@209c434f, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@234c5d6, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1d24eadcmSocket: android.net.LocalSocket@2a6f37e5 impl:android.net.LocalSocketImpl@1480c2ba fd:FileDescriptor[79]
09-08 18:23:56.941  6435  6435 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2a6f37e5 impl:android.net.LocalSocketImpl@1480c2ba fd:FileDescriptor[79]
09-08 18:23:56.941  6435  6846 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-08 18:23:56.941  6435  6846 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-08 18:23:56.941  6435  6786 D BluetoothAdapterProperties: onBluetoothDisable()
09-08 18:23:56.941  1015  1383 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-08 18:23:56.941  6435  6786 D BluetoothAdapterProperties: mDiscovering is false
09-08 18:23:56.941  1015  1383 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
09-08 18:23:56.941  1015  1383 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:56.941  1015  1383 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:56.941  1015  1383 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-08 18:23:56.941  1015  3235 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-08 18:23:56.951  1300  1300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-08 18:23:56.951  6435  6786 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-08 18:23:56.951  1015  3003 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-08 18:23:56.951  1015  3003 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-08 18:23:56.951  1015  3003 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:56.951  6147  6147 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:56.951  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:56.951  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:56.951  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:56.951  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:23:56.951  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:23:56.951  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:23:56.951  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:23:56.951  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 18:23:56.951  1015  3003 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:56.951  1015  3003 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-08 18:23:56.951  6147  6147 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:56.951  6147  6147 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 18:23:56.961  1300  1300 D BluetoothPbap: Proxy object disconnected
09-08 18:23:56.961  1300  1300 D PbapServerProfile: Bluetooth service disconnected
,09-08 18:23:56.961  6435  6789 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-08 18:23:56.961  6435  6789 D BluetoothAdapterProperties: Scan Mode:20
,09-08 18:23:56.961  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:56.961  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:56.971  6435  6786 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,09-08 18:23:56.971  6435  6786 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1,
,09-08 18:23:56.971  6435  6786 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
09-08 18:23:56.971  6435  6786 E bt-btif : cmd socket is not created
09-08 18:23:56.971  6435  6786 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-08 18:23:56.971  6435  6807 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
09-08 18:23:56.971  6435  6807 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-08 18:23:56.971  6435  6807 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 18:23:56.971  6435  6807 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-08 18:23:56.971  6435  6807 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-08 18:23:56.971  1300  1300 D DockEventReceiver: finishStartingService: stopping service
,09-08 18:23:56.981  1300  1300 D BluetoothNotiBroadcastReceiver: onReceive
,09-08 18:23:56.981  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-08 18:23:56.981  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-08 18:23:57.001  6435  6435 V BluetoothOppManager: cleanUp...
,09-08 18:23:57.011  1907  1907 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-08 18:23:57.021  1907  1907 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-08 18:23:57.171  6435  6807 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-08 18:23:57.171  6435  6807 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 18:23:57.171  6435  6807 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-08 18:23:57.171  6435  6807 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 18:23:57.171  6435  6807 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-08 18:23:57.171  6435  6807 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-08 18:23:57.171  6435  6807 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-08 18:23:57.171  6435  6807 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 18:23:57.181  6435  6829 I bt_userial_mct: exiting userial_read_thread
09-08 18:23:57.181  6435  6829 D bt_userial_mct: Leaving userial_evt_read_thread()
09-08 18:23:57.181  6435  6789 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-08 18:23:57.181  6435  6809 I bt_vendor: hw_epilog_process
09-08 18:23:57.181  6435  6807 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-08 18:23:57.181  6435  6807 W bt-btif : ag scb idx 1 not allocated
09-08 18:23:57.181  6435  6807 W bt-btif : ag scb idx 2 not allocated
09-08 18:23:57.181  6435  6807 E bt-btif : BTA AG is already disabled, ignoring ...
09-08 18:23:57.181  6435  6789 D bt_userial_mct: userial_close
09-08 18:23:57.181  6435  6789 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-08 18:23:57.521   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,09-08 18:23:57.621  6435  6789 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,09-08 18:23:57.621  6435  6789 I bt_vendor: bluetooth satus is on
09-08 18:23:57.621  6435  6789 I bt_vendor: bt-vendor : resetting BT status
09-08 18:23:57.621  6435  6789 I bt_vendor: Starting hciattach daemon
09-08 18:23:57.621  6435  6789 I bt_vendor: try to set false
,09-08 18:23:57.621  6435  6789 I bt_vendor: Starting hciattach daemon
09-08 18:23:57.621  6435  6789 I bt_vendor: try to set false
,09-08 18:23:57.621  6435  6789 I bt_vendor: cleanup
,09-08 18:23:57.621  6435  6807 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-08 18:23:57.621  6435  6789 I GKI_LINUX: GKI_exit_task 0 done
09-08 18:23:57.621  6435  6789 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,09-08 18:23:57.621  6435  6786 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true,
09-08 18:23:57.621  6435  6786 D BtConfig.SecureMode: isSecureModeOn:false
,09-08 18:23:57.621  6435  6786 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-08 18:23:57.621  6435  6786 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService,
09-08 18:23:57.621  6435  6786 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-08 18:23:57.621  6435  6786 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-08 18:23:57.621  1015  3003 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-08 18:23:57.621  1015  3003 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-08 18:23:57.631  1015  3003 W ActivityManager: userId = 0, bbcId = -10000,
09-08 18:23:57.631  1015  3003 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:57.631  1015  3003 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:57.631  6435  6786 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-08 18:23:57.631  6435  6786 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-08 18:23:57.631  6435  6786 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-08 18:23:57.631  6435  6435 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 18:23:57.631  1015  1564 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:23:57.631  1015  1564 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-08 18:23:57.631  1015  1564 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:57.631  1015  1564 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:57.631  1015  1564 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-08 18:23:57.631  6435  6786 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-08 18:23:57.631  6435  6786 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-08 18:23:57.631  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:23:57.631  6435  6435 D BtGatt.GattService: Received stop request...Stopping profile...
09-08 18:23:57.631  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-08 18:23:57.631  6435  6786 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
09-08 18:23:57.631  6435  6435 D BtGatt.GattService: stop()
09-08 18:23:57.631  6435  6435 D BtGatt.AdvertiseManager: advertise clients cleared
09-08 18:23:57.631  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:57.631  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:57.631  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:57.641  6435  6435 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a225333
09-08 18:23:57.641  6435  6435 D HeadsetService: Received stop request...Stopping profile...
09-08 18:23:57.641  6435  6786 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-08 18:23:57.641  6435  6786 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-08 18:23:57.641  6435  6786 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
09-08 18:23:57.641  6435  6435 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a225333
,09-08 18:23:57.641  1015  3235 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-08 18:23:57.641  1015  3235 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-08 18:23:57.641  6435  6435 D A2dpService: Received stop request...Stopping profile...
,09-08 18:23:57.641  6435  6801 D A2dpStateMachine: Exit Disconnected: -1
,09-08 18:23:57.651  1015  3235 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:57.651  1015  3235 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:57.651  1015  3235 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:57.651  6435  6786 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-08 18:23:57.651  6435  6786 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-08 18:23:57.651  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-08 18:23:57.651  6435  6786 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-08 18:23:57.651  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:23:57.651  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-08 18:23:57.651  1300  1300 D HeadsetProfile: Bluetooth service disconnected
09-08 18:23:57.651  6435  6435 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a225333
09-08 18:23:57.651  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:57.651  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:57.651  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:57.651  6435  6786 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-08 18:23:57.651  6435  6786 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-08 18:23:57.651  6435  6786 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
09-08 18:23:57.651  1015  1015 D BluetoothA2dp: Proxy object disconnected
09-08 18:23:57.651  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-08 18:23:57.651  1015  3238 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-08 18:23:57.651  1015  3238 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-08 18:23:57.651  1300  1300 D BluetoothA2dp: Proxy object disconnected
,09-08 18:23:57.661  1015  3238 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:57.661  1300  1300 D A2dpProfile: Bluetooth service disconnected
09-08 18:23:57.661  1015  3238 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:57.661  1015  3238 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:57.661  2865  2865 D BluetoothA2dp: Proxy object disconnected
09-08 18:23:57.661  6435  6786 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-08 18:23:57.661  6435  6786 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-08 18:23:57.661  6435  6786 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-08 18:23:57.661  1015  1342 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:23:57.661  1015  1342 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-08 18:23:57.661  1015  1342 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:57.661  1015  1342 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:57.661  1015  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:57.661  6435  6786 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-08 18:23:57.661  6435  6786 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-08 18:23:57.661  6435  6786 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-08 18:23:57.661  1015  1487 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:23:57.661  1015  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-08 18:23:57.661  1015  1487 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:57.661  1015  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:23:57.671  1015  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:23:57.671  6435  6786 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-08 18:23:57.671  6435  6786 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-08 18:23:57.671  6435  6786 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,09-08 18:23:57.671  6435  6786 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-08 18:23:57.671  6435  6786 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-08 18:23:57.671  6435  6786 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-08 18:23:57.671  6435  6786 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-08 18:23:57.671  6435  6786 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-08 18:23:57.671  6435  6786 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-08 18:23:57.671  6435  6786 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
,09-08 18:23:57.671  6435  6786 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-08 18:23:57.671  6435  6786 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,09-08 18:23:57.671  6435  6435 E BluetoothAdapterService(438457139): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,09-08 18:23:57.671  6435  6435 E BluetoothAdapterService(438457139): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-08 18:23:57.671  6435  6435 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-08 18:23:57.671  6435  6435 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-08 18:23:57.671  6435  6786 D BluetoothAdapterState: Stopping profile services that were post enabled
,09-08 18:23:57.671  6435  6435 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-08 18:23:57.681  6435  6435 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-08 18:23:57.681  6435  6435 D HidService: Received stop request...Stopping profile...
,09-08 18:23:57.681  6435  6435 D HidService: Stopping Bluetooth HidService
09-08 18:23:57.681  6435  6435 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-08 18:23:57.681  6435  6435 W bt-btif : cleanup: HH disabling or disabled already, status = 0
,09-08 18:23:57.681  6435  6435 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-08 18:23:57.681  6435  6435 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a225333
,09-08 18:23:57.681  6435  6435 E BluetoothAdapterService(438457139): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-08 18:23:57.681  6435  6435 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-08 18:23:57.681  6435  6435 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-08 18:23:57.681  6435  6435 D HealthService: Received stop request...Stopping profile...
09-08 18:23:57.681  6435  6435 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a225333
,09-08 18:23:57.681  6435  6435 D BluetoothA2dp: Proxy object disconnected
,09-08 18:23:57.691  6435  6435 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-08 18:23:57.691  1300  1300 D BluetoothInputDevice: Proxy object disconnected
09-08 18:23:57.691  1300  1300 D HidProfile: Bluetooth service disconnected
,09-08 18:23:57.691  6435  6802 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,09-08 18:23:57.691  6435  6435 I GKI_LINUX: GKI_exit_task 2 done
09-08 18:23:57.691  6435  6435 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,09-08 18:23:57.691  6435  6435 D PanService: Received stop request...Stopping profile...
09-08 18:23:57.691  6435  6435 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a225333
,09-08 18:23:57.691  1015  1015 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-08 18:23:57.691  1300  1300 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-08 18:23:57.691  1300  1300 D PanProfile: Bluetooth service disconnected
,09-08 18:23:57.691  6435  6435 D BluetoothMapService: Received stop request...Stopping profile...
,09-08 18:23:57.701  6435  6435 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a225333
,09-08 18:23:57.701  1300  1300 D BluetoothMap: Proxy object disconnected
09-08 18:23:57.701  1300  1300 D MapProfile: Bluetooth service disconnected
,09-08 18:23:57.701  6435  6435 D SapService: Received stop request...Stopping profile...
09-08 18:23:57.701  6435  6435 D SapService: Stopping Bluetooth SapService
09-08 18:23:57.701  6435  6435 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a225333
,09-08 18:23:57.701  6435  6435 E BluetoothAdapterService(438457139): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-08 18:23:57.701  6435  6435 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-08 18:23:57.701  6435  6435 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-08 18:23:57.701  6435  6435 E BluetoothAdapterService(438457139): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-08 18:23:57.701  6435  6435 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-08 18:23:57.701  6435  6435 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-08 18:23:57.701  6435  6435 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-08 18:23:57.701  6435  6435 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-08 18:23:57.701  6435  6435 E BluetoothAdapterService(438457139): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-08 18:23:57.701  6435  6435 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-08 18:23:57.701  6435  6435 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-08 18:23:57.701  6435  6435 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-08 18:23:57.701  6435  6435 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-08 18:23:57.701  1300  1300 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-08 18:23:57.701  1300  1300 D SapProfile: Bluetooth service disconnected
,09-08 18:23:57.711  6435  6435 E BluetoothAdapterService(438457139): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,09-08 18:23:57.711  6435  6435 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-08 18:23:57.711  6435  6435 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
09-08 18:23:57.711  6435  6435 E BluetoothAdapterService(438457139): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-08 18:23:57.711  6435  6435 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-08 18:23:57.711  6435  6435 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-08 18:23:57.711  6435  6786 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
09-08 18:23:57.711  6435  6786 D BluetoothAdapterProperties: Setting state to 10
,09-08 18:23:57.711  6435  6786 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-08 18:23:57.711  6435  6786 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-08 18:23:57.711  6435  6786 D BluetoothAdapterService: updateAdapterState state is 10
09-08 18:23:57.711  1015  1045 D BluetoothAdapter: onBluetoothStateChange: up=false
09-08 18:23:57.711  1015  1045 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-08 18:23:57.711  6435  6786 D BluetoothAdapterService: Autoconnection is available 
09-08 18:23:57.711  2865  2895 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-08 18:23:57.711  6435  6786 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-08 18:23:57.711  6435  6786 I BluetoothAdapterState: Entering OffState
,09-08 18:23:57.711  1300  1311 D BluetoothAdapter: onBluetoothStateChange: up=false
09-08 18:23:57.711  1300  1311 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-08 18:23:57.721  6316  6324 D BluetoothAdapter: onBluetoothStateChange: up=false
09-08 18:23:57.721  6316  6324 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-08 18:23:57.721  1015  1045 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 18:23:57.721  1439  1464 D BluetoothAdapter: onBluetoothStateChange: up=false
09-08 18:23:57.721  1439  1464 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-08 18:23:57.721  1300  1317 D Bluetoothsap: onBluetoothStateChange: up=false
09-08 18:23:57.721  1300  1317 D Bluetoothsap: Unbinding service...
09-08 18:23:57.721  6435  6443 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-08 18:23:57.721  6435  6443 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-08 18:23:57.721  6147  6157 D BluetoothAdapter: onBluetoothStateChange: up=false
09-08 18:23:57.721  6147  6157 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-08 18:23:57.721  6147  6157 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-08 18:23:57.721  6147  6157 D BluetoothLeAdvertiser: Exit stop advertising
,09-08 18:23:57.721  6147  6157 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-08 18:23:57.721  6147  6157 D BluetoothLeScanner: Exiting stopAllScan
09-08 18:23:57.721  1452  1868 D BluetoothAdapter: onBluetoothStateChange: up=false
09-08 18:23:57.721  1452  1868 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-08 18:23:57.721  6435  6449 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 18:23:57.721  1300  6834 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-08 18:23:57.721  1300  1317 D BluetoothPbap: onBluetoothStateChange: up=false
09-08 18:23:57.721  1174  4740 D BluetoothAdapter: onBluetoothStateChange: up=false
09-08 18:23:57.721  1174  4740 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-08 18:23:57.721  2865  2879 D BluetoothAdapter: onBluetoothStateChange: up=false
09-08 18:23:57.721  2865  2879 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-08 18:23:57.721  1431  2721 D BluetoothAdapter: onBluetoothStateChange: up=false
09-08 18:23:57.721  1431  2721 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-08 18:23:57.721  1300  1311 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 18:23:57.721  1907  2115 D BluetoothAdapter: onBluetoothStateChange: up=false
09-08 18:23:57.721  1907  2115 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-08 18:23:57.721  1300  6834 D BluetoothMap: onBluetoothStateChange: up=false
,09-08 18:23:57.731  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 11 receivers.,
,09-08 18:23:57.731  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-08 18:23:57.741  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:57.741  1015  1015 I InputMethodManagerService: [BT Setting State] State =10
09-08 18:23:57.741  1015  1015 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-08 18:23:57.741  1174  1174 D BluetoothAdapter: 460716354: getState() :  mService = null. Returning STATE_OFF
,09-08 18:23:57.741  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-08 18:23:57.741  1174  1702 D BluetoothAdapter: 460716354: getState() :  mService = null. Returning STATE_OFF
,09-08 18:23:57.741  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:57.741  1174  1174 D BluetoothTile:  getBluetoothState : 10
09-08 18:23:57.741  1174  1702 D BluetoothAdapter: 460716354: getState() :  mService = null. Returning STATE_OFF
,09-08 18:23:57.741  6435  6789 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-08 18:23:57.741  6435  6435 I GKI_LINUX: GKI_exit_task 1 done
09-08 18:23:57.741  6435  6435 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-08 18:23:57.751  1174  1174 D BluetoothAdapter: 460716354: getState() :  mService = null. Returning STATE_OFF
09-08 18:23:57.751  6435  6435 I BluetoothServiceJni: cleanupNative: return from cleanup
09-08 18:23:57.751  1174  1174 D BluetoothAdapter: 460716354: getState() :  mService = null. Returning STATE_OFF
,09-08 18:23:57.751  1883  1883 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
09-08 18:23:57.751  1015  1564 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-08 18:23:57.751  1015  3002 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-08 18:23:57.751  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-08 18:23:57.751  1907  2121 D BluetoothAdapter: 117873335: getState() :  mService = null. Returning STATE_OFF
09-08 18:23:57.751  1907  2121 D BluetoothAdapter: 117873335: getState() :  mService = null. Returning STATE_OFF
,09-08 18:23:57.751  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:57.751  6435  6435 I art     : System.exit called, status: 0
09-08 18:23:57.751  6435  6435 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-08 18:23:57.751  1015  1028 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-08 18:23:57.751  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-08 18:23:57.751  1300  1300 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:57.751  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:57.761  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:23:57.761  1300  1300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-08 18:23:57.761  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:57.761  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:57.761  1015  1251 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-08 18:23:57.761  1015  1251 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-08 18:23:57.761  1015  1251 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:57.761  1015  1251 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 18:23:57.761  1015  1251 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-08 18:23:57.771  1300  1300 D DockEventReceiver: finishStartingService: stopping service
,09-08 18:23:57.771  1300  1300 D BluetoothNotiBroadcastReceiver: onReceive
,09-08 18:23:57.771  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:57.771  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-08 18:23:57.851  1015  1342 I ActivityManager: Process com.android.bluetooth (pid 6435)(adj 0) has died(69,1071)
,09-08 18:23:57.861  1907  1907 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-08 18:23:57.861  1015  1487 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-08 18:23:57.861  1015  1487 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-08 18:23:57.861  1015  1487 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:57.861  1015  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:57.861  1015  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:57.871  1907  6863 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-08 18:23:57.871  1907  1907 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-08 18:23:57.871  1015  1138 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 18:23:57.881  1015  1138 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:23:57.881  1015  1138 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:23:57.881  1015  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:23:57.891  1907  6863 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,09-08 18:23:58.501   289   289 E SMD     : DCD OFF
,09-08 18:23:58.521   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,09-08 18:23:59.531   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,09-08 18:23:59.901  6147  6197 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 18:23:59.901  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:23:59.991  1015  1094 V AlarmManager: waitForAlarm result :8
,09-08 18:24:00.531   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,09-08 18:24:00.891  1015  1958 V SAMP_SPCM_test: CSC File load.. 
,09-08 18:24:00.901  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,09-08 18:24:00.901  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
09-08 18:24:00.901  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
,09-08 18:24:00.901  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
09-08 18:24:00.901  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
09-08 18:24:00.901  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming,
09-08 18:24:00.901  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
09-08 18:24:00.901  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
,09-08 18:24:00.901  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
,09-08 18:24:00.901  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
,09-08 18:24:00.901  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
09-08 18:24:00.901  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
09-08 18:24:00.901  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
09-08 18:24:00.901  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
,09-08 18:24:00.901  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
09-08 18:24:00.901  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
09-08 18:24:00.901  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
09-08 18:24:00.901  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
09-08 18:24:00.901  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
,09-08 18:24:00.901  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
09-08 18:24:00.901  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,09-08 18:24:00.941  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,09-08 18:24:00.941  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
09-08 18:24:00.941  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
09-08 18:24:00.941  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time,
09-08 18:24:00.941  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
09-08 18:24:00.941  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
09-08 18:24:00.941  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
,09-08 18:24:00.941  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
09-08 18:24:00.941  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
09-08 18:24:00.941  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
09-08 18:24:00.941  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
,09-08 18:24:00.941  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
09-08 18:24:00.941  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
09-08 18:24:00.941  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
09-08 18:24:00.941  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
,09-08 18:24:00.941  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
09-08 18:24:00.941  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
09-08 18:24:00.941  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
09-08 18:24:00.941  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
09-08 18:24:00.941  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn,
09-08 18:24:00.941  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,09-08 18:24:00.951  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
,09-08 18:24:00.951  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
09-08 18:24:00.951  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
09-08 18:24:00.951  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
,09-08 18:24:00.951  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
09-08 18:24:00.951  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
09-08 18:24:00.951  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
09-08 18:24:00.951  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
,09-08 18:24:00.951  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
09-08 18:24:00.951  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
09-08 18:24:00.951  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
09-08 18:24:00.951  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
,09-08 18:24:00.951  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
09-08 18:24:00.951  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
09-08 18:24:00.951  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
09-08 18:24:00.951  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
,09-08 18:24:00.951  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
09-08 18:24:00.951  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
09-08 18:24:00.951  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
09-08 18:24:00.951  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
,09-08 18:24:00.951  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
09-08 18:24:00.951  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
,09-08 18:24:00.951  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
09-08 18:24:00.951  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
,09-08 18:24:00.951  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
09-08 18:24:00.961  1015  1958 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
09-08 18:24:00.951  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
09-08 18:24:00.951  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account,
09-08 18:24:00.951  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
,09-08 18:24:00.951  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
09-08 18:24:00.951  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
,09-08 18:24:00.961  1015  1958 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:24:00.951  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
09-08 18:24:00.961  1015  1958 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:24:00.951  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
,09-08 18:24:00.961  1015  1958 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:24:00.951  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
09-08 18:24:00.961  1015  1958 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:24:00.951  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
09-08 18:24:00.951  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
09-08 18:24:00.951  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
09-08 18:24:00.951  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
09-08 18:24:00.951  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
09-08 18:24:00.951  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,09-08 18:24:00.971  6866  6866 E Zygote  : MountEmulatedStorage()
09-08 18:24:00.971  6866  6866 I libpersona: KNOX_SDCARD checking this for 1000
09-08 18:24:00.971  6866  6866 E Zygote  : v2
09-08 18:24:00.971  6866  6866 I libpersona: KNOX_SDCARD not a persona
,09-08 18:24:00.971  1015  1958 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=6866 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,09-08 18:24:00.981  6866  6866 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-08 18:24:00.981  6866  6866 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-08 18:24:00.981  6866  6866 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-08 18:24:01.011  6866  6866 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:24:01.011  6866  6866 D ActivityThread: Added TimaKeyStore provider,
,09-08 18:24:01.031  6866  6866 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-08 18:24:01.081  1015  1958 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,09-08 18:24:01.501   289   289 E SMD     : DCD OFF,
,09-08 18:24:01.531   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,09-08 18:24:02.531   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,09-08 18:24:02.901  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 18:24:02.901  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1fb59f03 added. We now have 6 listener(s)
09-08 18:24:02.901  6147  6197 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:24:02.901  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 18:24:02.901  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1619ce80 added. We now have 7 listener(s)
09-08 18:24:02.901  6147  6197 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:24:02.901  6147  6197 I System.out: IsBluetoothEnabled,
,09-08 18:24:02.911  6147  6197 D BluetoothAdapter: disable()
,09-08 18:24:02.911  1015  1494 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,09-08 18:24:02.911  6147  6197 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:24:02.911  6147  6197 D BluetoothAdapter: enable()
,09-08 18:24:02.921  1015  1028 W ActivityManager: Permission Denial: getCurrentUser() from pid=6147, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-08 18:24:02.921  1015  1028 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-08 18:24:02.921  1015  1028 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6147, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-08 18:24:02.921  1015  1028 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-08 18:24:02.921  1015  1028 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
09-08 18:24:02.921  1015  1028 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
09-08 18:24:02.921  1015  1028 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
09-08 18:24:02.921  1015  1028 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-08 18:24:02.921  1015  1028 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-08 18:24:02.921  1015  1028 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-08 18:24:02.921  1015  1028 D SettingsProvider: name = bluetooth_on
,09-08 18:24:02.921  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-08 18:24:02.921  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-08 18:24:02.931  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,09-08 18:24:02.931  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,09-08 18:24:02.931  1015  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:24:02.931  1015  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:24:02.931  1015  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:24:02.931  1015  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:24:02.951  6885  6885 E Zygote  : MountEmulatedStorage()
,09-08 18:24:02.951  6885  6885 E Zygote  : v2
09-08 18:24:02.951  6885  6885 I libpersona: KNOX_SDCARD checking this for 1002
,09-08 18:24:02.951  6885  6885 I libpersona: KNOX_SDCARD not a persona
,09-08 18:24:02.951  6885  6885 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-08 18:24:02.951  1015  1045 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6885 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a,
,09-08 18:24:02.961  6885  6885 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-08 18:24:02.961  6885  6885 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-08 18:24:02.981  6885  6885 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 18:24:02.981  6885  6885 D ActivityThread: Added TimaKeyStore provider
,09-08 18:24:03.001  6885  6885 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-08 18:24:03.001  6885  6885 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-08 18:24:03.031  6885  6885 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-08 18:24:03.061  6885  6885 D BtSettings.ProfileConfig: Adding GattService
,09-08 18:24:03.061  6885  6885 D BtSettings.ProfileConfig: Adding HeadsetService
,09-08 18:24:03.061  6885  6885 D BtSettings.ProfileConfig: Adding A2dpService
,09-08 18:24:03.061  6885  6885 D BtSettings.ProfileConfig: Adding HidService
,09-08 18:24:03.061  6885  6885 D BtSettings.ProfileConfig: Adding HealthService
09-08 18:24:03.061  6885  6885 D BtSettings.ProfileConfig: Adding PanService
,09-08 18:24:03.071  6885  6885 D BtSettings.ProfileConfig: Adding BluetoothMapService
,09-08 18:24:03.071  6885  6885 D BtSettings.ProfileConfig: Adding SapService
09-08 18:24:03.071  6885  6885 D BtSettings.ProfileConfig: Adding HeadsetClientService
,09-08 18:24:03.071  6885  6885 D BtSettings.ProfileConfig: Adding A2dpSinkService
,09-08 18:24:03.071  6885  6885 D BtSettings.ProfileConfig: Adding SapClientService
09-08 18:24:03.071  6885  6885 D BtSettings.ProfileConfig: Adding HidDevService
,09-08 18:24:03.071  6885  6885 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-08 18:24:03.071  1015  3238 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
09-08 18:24:03.071  1015  3238 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-08 18:24:03.071  1015  3238 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-08 18:24:03.071  1015  3238 D SettingsProvider: selectionArgs: false
09-08 18:24:03.071  1015  3238 D SettingsProvider: selectionArgs: 1002
09-08 18:24:03.071  1015  3238 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-08 18:24:03.071  1015  3238 D SettingsProvider: ret = -1
,09-08 18:24:03.071  1015  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
09-08 18:24:03.071  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-08 18:24:03.071  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-08 18:24:03.071  1015  1027 D SettingsProvider: selectionArgs: false
09-08 18:24:03.071  1015  1027 D SettingsProvider: selectionArgs: 1002
09-08 18:24:03.071  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-08 18:24:03.071  1015  1027 D SettingsProvider: ret = -1
,09-08 18:24:03.071  1015  1383 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,09-08 18:24:03.071  1015  1383 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-08 18:24:03.071  1015  1383 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-08 18:24:03.071  1015  1383 D SettingsProvider: selectionArgs: false
09-08 18:24:03.071  1015  1383 D SettingsProvider: selectionArgs: 1002
,09-08 18:24:03.071  1015  1383 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-08 18:24:03.071  1015  1383 D SettingsProvider: ret = -1
,09-08 18:24:03.071  1015  3002 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,09-08 18:24:03.081  1015  3002 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-08 18:24:03.081  1015  3002 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-08 18:24:03.081  1015  3002 D SettingsProvider: selectionArgs: false
09-08 18:24:03.081  1015  3002 D SettingsProvider: selectionArgs: 1002
09-08 18:24:03.081  1015  3002 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-08 18:24:03.081  1015  3002 D SettingsProvider: ret = -1
,09-08 18:24:03.081  1015  3140 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
09-08 18:24:03.081  1015  3140 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-08 18:24:03.081  1015  3140 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-08 18:24:03.081  1015  3140 D SettingsProvider: selectionArgs: false
09-08 18:24:03.081  1015  3140 D SettingsProvider: selectionArgs: 1002
09-08 18:24:03.081  1015  3140 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-08 18:24:03.081  1015  3140 D SettingsProvider: ret = -1
,09-08 18:24:03.081  1015  1251 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
09-08 18:24:03.081  1015  1251 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-08 18:24:03.081  1015  1251 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-08 18:24:03.081  1015  1251 D SettingsProvider: selectionArgs: false
09-08 18:24:03.081  1015  1251 D SettingsProvider: selectionArgs: 1002
09-08 18:24:03.081  1015  1251 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-08 18:24:03.081  1015  1251 D SettingsProvider: ret = -1
,09-08 18:24:03.081  1015  3223 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
09-08 18:24:03.081  1015  3223 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-08 18:24:03.081  1015  3223 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-08 18:24:03.081  1015  3223 D SettingsProvider: selectionArgs: false
09-08 18:24:03.081  1015  3223 D SettingsProvider: selectionArgs: 1002
09-08 18:24:03.081  1015  3223 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-08 18:24:03.081  1015  3223 D SettingsProvider: ret = -1
,09-08 18:24:03.081  1015  1564 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
09-08 18:24:03.081  1015  1564 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-08 18:24:03.081  1015  1564 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-08 18:24:03.081  1015  1564 D SettingsProvider: selectionArgs: false
09-08 18:24:03.081  1015  1564 D SettingsProvider: selectionArgs: 1002
09-08 18:24:03.081  1015  1564 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-08 18:24:03.081  1015  1564 D SettingsProvider: ret = -1
09-08 18:24:03.081  1015  1342 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,09-08 18:24:03.081  1015  1342 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-08 18:24:03.081  1015  1342 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-08 18:24:03.081  1015  1342 D SettingsProvider: selectionArgs: false
09-08 18:24:03.081  1015  1342 D SettingsProvider: selectionArgs: 1002
09-08 18:24:03.081  1015  1342 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-08 18:24:03.081  1015  1342 D SettingsProvider: ret = -1
,09-08 18:24:03.081  1015  3003 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
09-08 18:24:03.081  1015  3003 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-08 18:24:03.081  1015  3003 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-08 18:24:03.081  1015  3003 D SettingsProvider: selectionArgs: false
,09-08 18:24:03.081  1015  3003 D SettingsProvider: selectionArgs: 1002
09-08 18:24:03.081  1015  3003 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-08 18:24:03.081  1015  3003 D SettingsProvider: ret = -1
09-08 18:24:03.081  1015  1138 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
09-08 18:24:03.081  1015  1138 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-08 18:24:03.081  1015  1138 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-08 18:24:03.081  1015  1138 D SettingsProvider: selectionArgs: false
09-08 18:24:03.081  1015  1138 D SettingsProvider: selectionArgs: 1002
09-08 18:24:03.081  1015  1138 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-08 18:24:03.081  1015  1138 D SettingsProvider: ret = -1
09-08 18:24:03.081  1015  1494 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
09-08 18:24:03.081  1015  1494 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
09-08 18:24:03.081  1015  1494 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-08 18:24:03.081  1015  1494 D SettingsProvider: selectionArgs: false
09-08 18:24:03.081  1015  1494 D SettingsProvider: selectionArgs: 1002
09-08 18:24:03.081  1015  1494 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-08 18:24:03.081  1015  1494 D SettingsProvider: ret = -1
,09-08 18:24:03.101  6885  6885 D BluetoothAdapterState: make,
,09-08 18:24:03.101  6885  6885 I bluedroid: init,
09-08 18:24:03.101  6885  6900 I BluetoothAdapterState: Entering OffState
,09-08 18:24:03.101  6885  6885 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf,
09-08 18:24:03.101  6885  6885 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-08 18:24:03.101  6885  6885 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-08 18:24:03.101  6885  6885 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-08 18:24:03.101  6885  6885 E bt-btif : btif_fetch_local_ble_random_bdaddr,
09-08 18:24:03.101  6885  6885 I bluedroid: get_profile_interface socket
09-08 18:24:03.101  6885  6885 I bluedroid: get_profile_interface map_client
09-08 18:24:03.101  6885  6903 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,09-08 18:24:03.111  6885  6885 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,09-08 18:24:03.111  6885  6903 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,09-08 18:24:03.111  6885  6903 E BluetoothServiceJni: populateRssiValuesNative
09-08 18:24:03.111  6885  6903 I bluedroid: getModelRssiValues
09-08 18:24:03.111  6885  6903 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-08 18:24:03.111  6885  6903 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-08 18:24:03.111  1015  1015 D SettingsProvider: name = bluetooth_name
,09-08 18:24:03.111  6885  6903 D BluetoothAdapterProperties: Name is: A5-1
,09-08 18:24:03.111  6885  6885 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-08 18:24:03.121  1015  1342 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-08 18:24:03.121  1015  1342 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-08 18:24:03.121  1015  1342 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:03.121  1015  1342 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:03.121  1015  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:24:03.121  6885  6893 I bluedroid: config_hci_snoop_log
,09-08 18:24:03.121  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,09-08 18:24:03.121  1015  1045 D BluetoothManagerService: Ble is always on enable gatt
,09-08 18:24:03.121  1015  1045 I BluetoothManagerService: enableGattForLeMode, doBind called
,09-08 18:24:03.121  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-08 18:24:03.121  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-08 18:24:03.131  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-08 18:24:03.131  6885  6885 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
09-08 18:24:03.131  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-08 18:24:03.131  1015  1045 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-08 18:24:03.131  6885  6900 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-08 18:24:03.141  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
09-08 18:24:03.141  6885  6900 D BluetoothAdapterProperties: Setting state to 11
,09-08 18:24:03.141  6885  6900 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-08 18:24:03.141  6885  6900 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-08 18:24:03.141  6885  6900 D BluetoothAdapterService: updateAdapterState state is 11
,09-08 18:24:03.141  6885  6900 D BluetoothAdapterService: Autoconnection is available 
,09-08 18:24:03.141  6885  6900 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-08 18:24:03.141  6885  6900 D BluetoothSecureManager: getInstant: null
,09-08 18:24:03.141  6885  6900 D BluetoothSecureManager: calling getMethod for getService
09-08 18:24:03.141  6885  6900 D BluetoothSecureManager: calling getService
,09-08 18:24:03.141  6885  6900 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@3ce18bfa
,09-08 18:24:03.141  1015  1028 D BluetoothSecureManagerService: isSecureModeEnabled
,09-08 18:24:03.141  1015  1028 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
09-08 18:24:03.141  6885  6900 D BtConfig.SecureMode: isSecureModeOn:false
,09-08 18:24:03.141  6885  6900 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-08 18:24:03.141  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-08 18:24:03.151  1015  1015 I InputMethodManagerService: [BT Setting State] State =11
,09-08 18:24:03.151  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-08 18:24:03.151  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-08 18:24:03.151  1174  1174 D BluetoothTile:  getBluetoothState : 11
,09-08 18:24:03.151  1883  1883 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-08 18:24:03.161  6885  6900 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
09-08 18:24:03.161  6885  6900 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-08 18:24:03.161  6885  6900 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
09-08 18:24:03.161  6885  6900 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-08 18:24:03.161  1300  1300 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:24:03.161  6885  6900 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
09-08 18:24:03.161  6885  6900 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-08 18:24:03.161  6885  6900 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
09-08 18:24:03.161  6885  6900 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-08 18:24:03.161  1174  1702 D BluetoothTile:  handleUpdatestate:false name:null
09-08 18:24:03.161  1174  1702 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-08 18:24:03.161  6885  6900 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
,09-08 18:24:03.171  6885  6900 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-08 18:24:03.171  6885  6900 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
,09-08 18:24:03.171  1015  1487 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-08 18:24:03.171  6885  6900 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-08 18:24:03.171  1015  1251 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-08 18:24:03.171  6885  6900 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
09-08 18:24:03.171  6885  6900 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-08 18:24:03.171  6885  6900 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
09-08 18:24:03.171  6885  6900 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-08 18:24:03.171  1015  3002 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-08 18:24:03.171  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:24:03.171  1015  3002 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
09-08 18:24:03.171  6885  6900 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-08 18:24:03.171  6885  6900 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-08 18:24:03.171  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-08 18:24:03.171  6885  6900 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-08 18:24:03.171  6885  6900 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-08 18:24:03.171  1015  3002 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:03.171  1015  3002 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:24:03.171  1015  3002 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:24:03.171  6885  6900 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-08 18:24:03.171  6885  6900 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-08 18:24:03.171  6885  6900 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,09-08 18:24:03.181  1300  1300 D BluetoothNotiBroadcastReceiver: onReceive
,09-08 18:24:03.181  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-08 18:24:03.181  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-08 18:24:03.181  6885  6900 D BluetoothBondStateMachine: make
,09-08 18:24:03.191  6885  6900 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-08 18:24:03.191  6885  6900 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-08 18:24:03.191  6885  6900 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-08 18:24:03.191  6885  6906 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-08 18:24:03.191  1015  1487 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:24:03.191  1015  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-08 18:24:03.191  1015  1487 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:03.191  1015  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 18:24:03.191  1015  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-08 18:24:03.191  6885  6900 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-08 18:24:03.191  6885  6900 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-08 18:24:03.201  6885  6900 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-08 18:24:03.201  6885  6885 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 18:24:03.201  6885  6885 D BtGatt.GattService: Received start request. Starting profile...
09-08 18:24:03.201  6885  6885 D BtGatt.GattService: start()
09-08 18:24:03.201  6885  6885 D BtGatt.GattService: start()
09-08 18:24:03.201  6885  6885 I bluedroid: get_profile_interface gatt
,09-08 18:24:03.201  6885  6885 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b3ace6d
09-08 18:24:03.201  6885  6885 D BtGatt.AdvertiseManager: advertise manager created
09-08 18:24:03.201  1015  1251 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-08 18:24:03.201  1015  1251 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-08 18:24:03.201  1015  1251 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:03.201  1015  1251 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:03.201  1015  1251 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:24:03.201  6885  6900 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-08 18:24:03.201  6885  6900 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-08 18:24:03.201  6885  6900 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-08 18:24:03.211  1015  1564 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-08 18:24:03.211  1015  1564 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-08 18:24:03.211  1015  1564 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:03.211  1015  1564 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 18:24:03.211  1015  1564 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:24:03.221  6885  6900 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-08 18:24:03.221  6885  6900 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-08 18:24:03.221  6885  6900 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-08 18:24:03.221  1015  1342 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-08 18:24:03.221  1015  1342 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-08 18:24:03.221  1015  1342 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:24:03.221  1015  1342 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:03.221  1907  1907 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
09-08 18:24:03.221  1015  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:24:03.221  6885  6885 D BtGatt.GattService: mStartError = false
09-08 18:24:03.221  6885  6885 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b3ace6d
,09-08 18:24:03.221  6885  6900 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,09-08 18:24:03.221  6885  6900 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-08 18:24:03.221  6885  6900 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-08 18:24:03.231  6885  6885 D HeadsetService: Received start request. Starting profile...
09-08 18:24:03.231  6885  6885 D HeadsetService: start()
,09-08 18:24:03.231  6885  6885 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-08 18:24:03.231  6885  6885 D HeadsetStateMachine: make
,09-08 18:24:03.231  6885  6885 E HeadsetStateMachine: # of Max HF connection is 2
,09-08 18:24:03.231  1907  1907 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-08 18:24:03.231  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-08 18:24:03.231  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-08 18:24:03.241  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:24:03.241  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 18:24:03.241  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:24:03.241  1015  3223 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,09-08 18:24:03.241  1015  3223 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-08 18:24:03.241  1015  3223 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:24:03.241  1015  3223 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:03.241  1015  3223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
09-08 18:24:03.241  6885  6900 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-08 18:24:03.241  6885  6900 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-08 18:24:03.241  6885  6900 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-08 18:24:03.241  1015  1564 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:24:03.241  1015  1564 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-08 18:24:03.251  1015  1564 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:24:03.251  1015  1564 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:03.251  1015  1564 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:24:03.251  1015  1487 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
09-08 18:24:03.251  1015  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-08 18:24:03.251  1015  1487 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:03.251  6885  6900 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-08 18:24:03.251  6885  6900 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-08 18:24:03.251  6885  6900 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-08 18:24:03.251  1015  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 18:24:03.251  1015  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-08 18:24:03.251  6885  6885 I bluedroid: get_profile_interface handsfree
,09-08 18:24:03.261  1015  3238 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-08 18:24:03.261  1015  3238 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-08 18:24:03.261  1015  3238 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:24:03.261  1015  3238 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:03.261  1015  3238 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:24:03.261  6885  6900 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,09-08 18:24:03.261  6885  6900 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-08 18:24:03.261  6885  6900 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-08 18:24:03.261  1015  1251 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:24:03.261  1015  1251 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-08 18:24:03.271  1015  1251 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:03.271  1015  1251 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:03.271  1015  1251 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:24:03.271  6885  6900 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-08 18:24:03.271  6885  6900 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-08 18:24:03.271  6885  6900 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-08 18:24:03.271  6885  6900 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-08 18:24:03.271  6885  6900 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-08 18:24:03.271  6885  6900 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-08 18:24:03.271  6885  6900 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-08 18:24:03.271  6885  6900 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-08 18:24:03.271  6885  6900 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-08 18:24:03.271  6885  6900 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
,09-08 18:24:03.271  6885  6900 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-08 18:24:03.271  6885  6900 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-08 18:24:03.271  6885  6900 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-08 18:24:03.271  6885  6885 I DualScoManager: Instantiating Dual Sco Manager
,09-08 18:24:03.271  6885  6885 I DualScoManager: Set HeadsetServiceHelper
,09-08 18:24:03.271  6885  6885 D BluetoothAtMessage: createCMTIContentObservers
,09-08 18:24:03.281  1015  3224 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,09-08 18:24:03.281  1015  3224 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-08 18:24:03.281  1015  3224 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-08 18:24:03.281  1015  3224 D SettingsProvider: selectionArgs: false
09-08 18:24:03.281  1015  3224 D SettingsProvider: selectionArgs: 1002
09-08 18:24:03.281  1015  3224 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-08 18:24:03.281  1015  3224 D SettingsProvider: ret = -1
,09-08 18:24:03.281  6885  6911 D HeadsetStateMachine: Enter Disconnected: -2
,09-08 18:24:03.281  6885  6885 D HeadsetService: mStartError = false
09-08 18:24:03.281  6885  6885 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b3ace6d
,09-08 18:24:03.281  6885  6885 D A2dpService: Received start request. Starting profile...
09-08 18:24:03.281  6885  6885 D A2dpService: start()
,09-08 18:24:03.291  6885  6911 D HeadsetStateMachine: Clear mHeadsetBrsf
,09-08 18:24:03.291  6885  6911 D HeadsetStateMachine: map size, before remove : 0
09-08 18:24:03.291  6885  6911 D HeadsetStateMachine: map size, after remove: 0
,09-08 18:24:03.291  6885  6885 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-08 18:24:03.291  6885  6885 I bluedroid: get_profile_interface avrcp
,09-08 18:24:03.291  6885  6885 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-08 18:24:03.311  6885  6885 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-08 18:24:03.311  6885  6913 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-08 18:24:03.311  6885  6885 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-08 18:24:03.311  6885  6885 D A2dpStateMachine: make
,09-08 18:24:03.311  6885  6885 I bluedroid: get_profile_interface a2dp
,09-08 18:24:03.311  6885  6915 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-08 18:24:03.311  6885  6885 E bt-btif : warning : media task started media_task_refcnt 1 
,09-08 18:24:03.311  6885  6885 D A2dpService: mStartError = false
09-08 18:24:03.311  6885  6885 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b3ace6d
,09-08 18:24:03.321  6885  6885 E BluetoothAdapterService(456838765): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
09-08 18:24:03.321  6885  6914 D A2dpStateMachine: Enter Disconnected: -2
,09-08 18:24:03.321  6885  6885 I BluetoothHidServiceJni: classInitNative: succeeds
,09-08 18:24:03.321  6885  6885 D HidService: Received start request. Starting profile...
09-08 18:24:03.321  6885  6885 D HidService: start()
09-08 18:24:03.321  6885  6885 I bluedroid: get_profile_interface hidhost
09-08 18:24:03.321  6885  6885 D HidService: setHidService(): set to: null
09-08 18:24:03.321  6885  6885 D HidService: mStartError = false
09-08 18:24:03.321  6885  6885 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b3ace6d
,09-08 18:24:03.321  6885  6885 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-08 18:24:03.321  6885  6885 D HealthService: Received start request. Starting profile...
09-08 18:24:03.321  6885  6885 D HealthService: start()
,09-08 18:24:03.331  6885  6885 I bluedroid: get_profile_interface health
09-08 18:24:03.331  6885  6885 D HealthService: mStartError = false
09-08 18:24:03.331  6885  6885 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b3ace6d
,09-08 18:24:03.331  6885  6885 D HeadsetStateMachine: Try to query the phonestate on bind
,09-08 18:24:03.331  1431  6352 I Telecom : BluetoothPhoneService: queryPhoneState
,09-08 18:24:03.331  1431  1431 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
09-08 18:24:03.331  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-08 18:24:03.331  1431  6352 I Telecom : BluetoothPhoneService: Result of Message : true
,09-08 18:24:03.331  6885  6885 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-08 18:24:03.331  6885  6885 D PanService: Received start request. Starting profile...
09-08 18:24:03.331  6885  6913 D BluetoothMediaBrowser: no now playing list
09-08 18:24:03.331  6885  6885 D PanService: start()
09-08 18:24:03.331  6885  6885 D BluetoothPanServiceJni: initializeNative(L110): pan
09-08 18:24:03.331  6885  6885 I bluedroid: get_profile_interface pan
,09-08 18:24:03.331  6885  6913 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-08 18:24:03.331  6885  6885 D PanService: mStartError = false
09-08 18:24:03.331  6885  6885 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b3ace6d
09-08 18:24:03.331  6885  6885 D HeadsetStateMachine: Proxy object connected
,09-08 18:24:03.331  6885  6885 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-08 18:24:03.341  6885  6911 D HeadsetStateMachine: Disconnected process message: 11
,09-08 18:24:03.341  6885  6885 D BluetoothMapService: Received start request. Starting profile...
,09-08 18:24:03.341  6885  6885 D BluetoothMapService: start()
,09-08 18:24:03.341  6885  6885 D BluetoothMapService: mStartError = false
,09-08 18:24:03.341  6885  6885 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b3ace6d
,09-08 18:24:03.341  6885  6885 D HeadsetPhoneState: sendDeviceDataStateChanged
,09-08 18:24:03.341  6885  6911 D HeadsetStateMachine: Disconnected process message: 18
09-08 18:24:03.341  6885  6885 D HeadsetPhoneState: Signal level : previous=0 curr=0,
09-08 18:24:03.341  6885  6885 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,09-08 18:24:03.351  6885  6885 D SapService: Received start request. Starting profile...
,09-08 18:24:03.351  6885  6885 D SapService: start()
09-08 18:24:03.351  6885  6885 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-08 18:24:03.351  6885  6885 I bluedroid: get_profile_interface sap
,09-08 18:24:03.351  6885  6885 D SapService: mStartError = false
,09-08 18:24:03.351  6885  6885 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b3ace6d
09-08 18:24:03.351  6885  6885 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-08 18:24:03.351  6885  6911 D HeadsetStateMachine: Disconnected process message: 10
09-08 18:24:03.351  6885  6885 E BluetoothAdapterService(456838765): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-08 18:24:03.351  6885  6911 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
09-08 18:24:03.351  6885  6885 D BluetoothA2dp: Proxy object connected
09-08 18:24:03.351  6885  6885 D BluetoothAdapterService: Bluetooth A2dp source service connected,
09-08 18:24:03.351  6885  6911 D HeadsetStateMachine: Disconnected process message: 11
09-08 18:24:03.351  6885  6885 E BluetoothAdapterService(456838765): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-08 18:24:03.351  6885  6885 E BluetoothAdapterService(456838765): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-08 18:24:03.351  6885  6885 E BluetoothAdapterService(456838765): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-08 18:24:03.351  6885  6885 E BluetoothAdapterService(456838765): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-08 18:24:03.381  6885  6885 E BluetoothAdapterService(456838765): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-08 18:24:03.381  6885  6885 E BluetoothAdapterService(456838765): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-08 18:24:03.381  6885  6900 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-08 18:24:03.381  6885  6900 I bluedroid: enable
,09-08 18:24:03.381  6885  6900 I bt_hci_bdroid: init
,09-08 18:24:03.381  6885  6900 I bt_vendor: bt-vendor : init
09-08 18:24:03.381  6885  6900 I bt_vendor: bt-vendor : get_bt_soc_type
09-08 18:24:03.381  6885  6900 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-08 18:24:03.381  6885  6900 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
09-08 18:24:03.381  6885  6900 D bt_userial_mct: userial_init
09-08 18:24:03.381  6885  6919 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-08 18:24:03.381  6885  6900 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-08 18:24:03.381  6885  6900 I bt_vendor: Starting hciattach daemon
09-08 18:24:03.381  6885  6900 I bt_vendor: try to set false
,09-08 18:24:03.391  6885  6900 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-08 18:24:03.391  6885  6900 I bt_vendor: Starting hciattach daemon
09-08 18:24:03.391  6885  6900 I bt_vendor: try to set true
,09-08 18:24:03.411  6923  6923 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,09-08 18:24:03.461  6929  6929 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,09-08 18:24:03.471  6930  6930 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-08 18:24:03.481  6932  6932 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-08 18:24:03.491  6933  6933 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,09-08 18:24:03.501  6934  6934 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-08 18:24:03.511  6935  6935 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,09-08 18:24:03.751  6938  6938 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,09-08 18:24:03.761  6939  6939 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-08 18:24:03.791  6885  6900 I bt_vendor: bluetooth satus is on,
09-08 18:24:03.791  6885  6921 D bt_userial_mct: userial_open(port:0)
09-08 18:24:03.791  6885  6921 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-08 18:24:03.791  6885  6921 I bt_vendor: Done intiailizing UART,
,09-08 18:24:03.801  6885  6921 I bt_vendor: Done intiailizing UART,
09-08 18:24:03.801  6885  6921 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
09-08 18:24:03.801  6885  6921 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-08 18:24:03.801  6885  6941 D bt_userial_mct: Entering userial_read_thread()
,09-08 18:24:03.801  6885  6919 I         : BTE_InitTraceLevels -- TRC_HCI
09-08 18:24:03.801  6885  6919 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-08 18:24:03.801  6885  6919 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-08 18:24:03.801  6885  6919 I         : BTE_InitTraceLevels -- TRC_AVDT
09-08 18:24:03.801  6885  6919 I         : BTE_InitTraceLevels -- TRC_AVRC,
09-08 18:24:03.801  6885  6919 I         : BTE_InitTraceLevels -- TRC_A2D
09-08 18:24:03.801  6885  6919 I         : BTE_InitTraceLevels -- TRC_BNEP
09-08 18:24:03.801  6885  6919 I         : BTE_InitTraceLevels -- TRC_BTM
,09-08 18:24:03.801  6885  6919 I         : BTE_InitTraceLevels -- TRC_GAP
09-08 18:24:03.801  6885  6919 I         : BTE_InitTraceLevels -- TRC_PAN
09-08 18:24:03.801  6885  6919 I         : BTE_InitTraceLevels -- TRC_SAP
,09-08 18:24:03.801  6885  6919 I         : BTE_InitTraceLevels -- TRC_SDP
09-08 18:24:03.801  6885  6919 I         : BTE_InitTraceLevels -- TRC_GATT
09-08 18:24:03.801  6885  6919 I         : BTE_InitTraceLevels -- TRC_SMP
,09-08 18:24:03.801  6885  6919 I         : BTE_InitTraceLevels -- TRC_BTAPP,
09-08 18:24:03.801  6885  6919 I         : BTE_InitTraceLevels -- TRC_BTIF
09-08 18:24:03.801  6885  6919 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,09-08 18:24:03.901  6885  6919 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,09-08 18:24:03.911  6885  6919 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa407c6e9 
,09-08 18:24:03.911  6885  6919 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa407c6e9 
,09-08 18:24:03.931  6885  6903 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,09-08 18:24:03.941  6885  6903 E bt-btif : Calling BTA_HhEnable
,09-08 18:24:03.941  6885  6903 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-08 18:24:03.941  6885  6903 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,09-08 18:24:03.941  6885  6903 E BluetoothServiceJni: populateRssiValuesNative
09-08 18:24:03.941  6885  6903 I bluedroid: getModelRssiValues
,09-08 18:24:03.941  6885  6903 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-08 18:24:03.941  6885  6903 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-08 18:24:03.941  1015  1015 D SettingsProvider: name = bluetooth_name
,09-08 18:24:03.941  6885  6903 D BluetoothAdapterProperties: Name is: A5-1
,09-08 18:24:03.951  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:24:03.951  6885  6903 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-08 18:24:03.951  6885  6903 D BluetoothAdapterProperties: Scan Mode:20
09-08 18:24:03.951  6885  6903 D BluetoothAdapterProperties: Discoverable Timeout:120,
09-08 18:24:03.951  6885  6903 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
09-08 18:24:03.951  6885  6903 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
09-08 18:24:03.951  6885  6903 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
09-08 18:24:03.951  6885  6903 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-08 18:24:03.951  6885  6903 E bt-btif : btif_sock_init: !vhci_init
09-08 18:24:03.951  6885  6903 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,09-08 18:24:03.951  6885  6903 D IOP_DB_BT: db_open: db_open : handle 3023872016l, read 13894 bytes onto local cache
,09-08 18:24:03.951  6885  6903 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1,
09-08 18:24:03.961  6885  6903 D IOP_DB_BT: db_query: result 1
09-08 18:24:03.961  6885  6903 I         : iop_db_open: iop_db_open status 0,
09-08 18:24:03.961  6885  6903 D bte_conf: Device ID record 1 : primary,
09-08 18:24:03.961  6885  6903 D bte_conf:   vendorId            = 0075
09-08 18:24:03.961  6885  6903 D bte_conf:   vendorIdSource      = 0001
09-08 18:24:03.961  6885  6903 D bte_conf:   product             = 0100
09-08 18:24:03.961  6885  6903 D bte_conf:   version             = 0200,
09-08 18:24:03.961  6885  6903 D bte_conf:   clientExecutableURL = 
09-08 18:24:03.961  6885  6903 D bte_conf:   serviceDescription  = 
09-08 18:24:03.961  6885  6903 D bte_conf:   documentationURL    = 
09-08 18:24:03.961  6885  6903 D bte_conf: bte_load_did_conf no section named DID2.
09-08 18:24:03.961  6885  6903 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-08 18:24:03.961  6885  6900 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-08 18:24:03.961  6885  6900 D BluetoothAdapterProperties: ScanMode =  20
09-08 18:24:03.961  6885  6900 D BluetoothAdapterProperties: State =  11
09-08 18:24:03.961  1015  3140 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-08 18:24:03.961  6885  6941 E bt_mct  : hci lib postload completed
09-08 18:24:03.961  6885  6900 D BluetoothAdapterProperties: Setting state to 12
09-08 18:24:03.961  6885  6900 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-08 18:24:03.961  6885  6903 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-08 18:24:03.961  6885  6903 D BluetoothAdapterProperties: Scan Mode:21
09-08 18:24:03.961  6885  6903 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-08 18:24:03.971  1015  1027 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,09-08 18:24:03.971  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-08 18:24:03.971  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-08 18:24:03.971  1015  1027 D SettingsProvider: selectionArgs: false
,09-08 18:24:03.971  1015  1027 D SettingsProvider: selectionArgs: 1002
09-08 18:24:03.971  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-08 18:24:03.971  1015  1027 D SettingsProvider: ret = -1
,09-08 18:24:03.971  6885  6900 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-08 18:24:03.971  6885  6900 D BluetoothAdapterService: updateAdapterState state is 12
,09-08 18:24:03.971  1015  3002 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:24:03.971  1015  3002 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-08 18:24:03.971  1015  3002 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:24:03.971  1015  3002 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:03.971  1015  3002 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:24:03.981  1015  1045 D BluetoothAdapter: onBluetoothStateChange: up=true
09-08 18:24:03.981  1015  1045 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-08 18:24:03.981  6885  6900 D BluetoothAdapterService: Autoconnection is available 
09-08 18:24:03.981  6885  6900 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-08 18:24:03.981  6885  6900 D BluetoothAdapterService: starting service from this receiver
,09-08 18:24:03.981  1015  3238 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:24:03.981  1015  3238 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-08 18:24:03.981  1015  3238 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:03.981  1015  3238 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:03.981  1015  3238 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:24:03.981  2865  2876 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-08 18:24:03.981  6885  6900 I BluetoothAdapterState: Entering On State from state = 11
09-08 18:24:03.981  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:24:03.981  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:03.981  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:24:03.981  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:24:03.981  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:24:03.981  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:24:03.981  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:24:03.981  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 18:24:03.981  2865  2876 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-08 18:24:03.991  6147  6147 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 18:24:04.001  6885  6885 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-08 18:24:04.151  1015  1045 I art     : Explicit concurrent mark sweep GC freed 85838(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 27MB/41MB, paused 2.401ms total 166.903ms
,09-08 18:24:04.151  1015  1045 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-08 18:24:04.151  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-08 18:24:04.151  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:04.151  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:04.151  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
09-08 18:24:04.151  2865  2865 D BluetoothA2dp: Proxy object connected
,09-08 18:24:04.151  1300  1317 D BluetoothAdapter: onBluetoothStateChange: up=true
09-08 18:24:04.151  1300  1317 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-08 18:24:04.161  1300  6834 D BluetoothPan: Binding service...,
,09-08 18:24:04.161  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-08 18:24:04.161  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-08 18:24:04.161  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:04.161  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:04.161  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-08 18:24:04.161  1452  1868 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-08 18:24:04.161  6885  6885 I BluetoothPbapService: Handler(): got msg=1
,09-08 18:24:04.161  1015  1045 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-08 18:24:04.161  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-08 18:24:04.161  1015  1138 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
09-08 18:24:04.161  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:04.161  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:04.161  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-08 18:24:04.161  1452  1868 E BluetoothHeadset: BluetoothHeadset service is binded
,09-08 18:24:04.161  6316  6327 D BluetoothAdapter: onBluetoothStateChange: up=true
09-08 18:24:04.161  6316  6327 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-08 18:24:04.161  1015  1045 D BluetoothPan: Binding service...
,09-08 18:24:04.171  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-08 18:24:04.171  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-08 18:24:04.171  6885  6904 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-08 18:24:04.171  6885  6904 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-08 18:24:04.171  1015  1045 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-08 18:24:04.171  1015  1045 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-08 18:24:04.171  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-08 18:24:04.171  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-08 18:24:04.171  1015  1015 D BluetoothA2dp: Proxy object connected
09-08 18:24:04.171  6885  6945 V BluetoothPbapService: PBAP Service initSocket try: 0
09-08 18:24:04.171  1439  1450 D BluetoothAdapter: onBluetoothStateChange: up=true
09-08 18:24:04.171  1439  1450 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-08 18:24:04.171  1015  1045 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-08 18:24:04.171  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-08 18:24:04.171  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-08 18:24:04.171  1015  1045 E BluetoothHeadset: BluetoothHeadset service is binded
,09-08 18:24:04.171  1300  6834 D Bluetoothsap: onBluetoothStateChange: up=true
09-08 18:24:04.171  1300  6834 D Bluetoothsap: Binding service...
,09-08 18:24:04.171  1300  1300 D BluetoothPan: BluetoothPAN Proxy object connected
09-08 18:24:04.171  1300  1300 D PanProfile: Bluetooth service connected
,09-08 18:24:04.171  1015  1015 D BluetoothPan: BluetoothPAN Proxy object connected
,09-08 18:24:04.171  1300  6834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-08 18:24:04.171  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-08 18:24:04.171  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-08 18:24:04.181  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:04.181  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:04.181  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-08 18:24:04.181  1300  6834 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-08 18:24:04.181  6885  6945 D BluetoothSocket: bindListen(): myUserId = 0
09-08 18:24:04.181  6885  6945 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 18:24:04.181  1431  6352 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-08 18:24:04.181  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-08 18:24:04.181  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-08 18:24:04.181  1300  1300 D Bluetoothsap: BluetoothSAP Proxy object connected
09-08 18:24:04.181  1300  1300 D SapProfile: Bluetooth service connected
09-08 18:24:04.181  1300  1300 D Bluetoothsap: getConnectedDevices()
09-08 18:24:04.181  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:04.181  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:04.181  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-08 18:24:04.181  1431  6352 E BluetoothHeadset: BluetoothHeadset service is binded
,09-08 18:24:04.181  6147  6155 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-08 18:24:04.181  6885  6945 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
09-08 18:24:04.181  6885  6945 D BluetoothSocket: bindListen(), new LocalSocket 
09-08 18:24:04.181  6885  6945 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-08 18:24:04.181  6885  6945 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@29e514fe
,09-08 18:24:04.191  6885  6945 D BluetoothSocket: channel: 19
09-08 18:24:04.191  6885  6945 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
09-08 18:24:04.191  6147  6155 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-08 18:24:04.191  1300  1317 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-08 18:24:04.191  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-08 18:24:04.191  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-08 18:24:04.191  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:24:04.191  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:04.191  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-08 18:24:04.191  1300  1300 D HeadsetProfile: Bluetooth service connected
,09-08 18:24:04.191  1300  1317 E BluetoothHeadset: BluetoothHeadset service is binded
09-08 18:24:04.191  1452  1470 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-08 18:24:04.191  1452  1470 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-08 18:24:04.191  1300  1311 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-08 18:24:04.191  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
09-08 18:24:04.191  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-08 18:24:04.191  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:04.191  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:04.191  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-08 18:24:04.191  1300  6834 D BluetoothPbap: onBluetoothStateChange: up=true
,09-08 18:24:04.201  1300  1300 D BluetoothInputDevice: Proxy object connected
09-08 18:24:04.201  1300  1300 D HidProfile: Bluetooth service connected
,09-08 18:24:04.201  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-08 18:24:04.201  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-08 18:24:04.201  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:04.201  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:04.201  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-08 18:24:04.201  1174  2338 D BluetoothAdapter: onBluetoothStateChange: up=true
09-08 18:24:04.201  1174  2338 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-08 18:24:04.201  1431  1444 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-08 18:24:04.201  1300  1300 D BluetoothPbap: Proxy object connected
09-08 18:24:04.201  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-08 18:24:04.201  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-08 18:24:04.201  1300  1300 D PbapServerProfile: Bluetooth service connected
09-08 18:24:04.201  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:04.201  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:04.201  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-08 18:24:04.201  1431  1444 E BluetoothHeadset: BluetoothHeadset service is binded
09-08 18:24:04.201  2865  2876 D BluetoothAdapter: onBluetoothStateChange: up=true
09-08 18:24:04.201  2865  2876 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-08 18:24:04.201  1431  6352 D BluetoothAdapter: onBluetoothStateChange: up=true
09-08 18:24:04.201  1431  6352 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-08 18:24:04.201  6885  6894 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 18:24:04.201  1300  1317 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-08 18:24:04.201  1300  1317 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-08 18:24:04.211  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-08 18:24:04.211  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-08 18:24:04.211  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:04.211  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:04.211  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-08 18:24:04.211  1300  1300 D BluetoothA2dp: Proxy object connected
,09-08 18:24:04.211  1300  1300 D A2dpProfile: Bluetooth service connected
09-08 18:24:04.211  2865  2879 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-08 18:24:04.211  1015  1045 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-08 18:24:04.211  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-08 18:24:04.211  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:24:04.211  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:04.211  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,09-08 18:24:04.211  2865  2879 E BluetoothHeadset: BluetoothHeadset service is binded
,09-08 18:24:04.221  1431  1449 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-08 18:24:04.221  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-08 18:24:04.221  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-08 18:24:04.221  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:04.221  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:04.221  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-08 18:24:04.221  1431  1449 E BluetoothHeadset: BluetoothHeadset service is binded
,09-08 18:24:04.221  1907  1916 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-08 18:24:04.221  1907  1916 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-08 18:24:04.221  1300  1311 D BluetoothMap: onBluetoothStateChange: up=true
,09-08 18:24:04.221  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
09-08 18:24:04.221  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-08 18:24:04.221  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:04.221  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:04.221  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-08 18:24:04.221  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-08 18:24:04.221  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-08 18:24:04.231  1300  1300 D BluetoothMap: Proxy object connected
09-08 18:24:04.231  1300  1300 D MapProfile: Bluetooth service connected
09-08 18:24:04.231  1300  1300 D BluetoothMap: getConnectedDevices()
,09-08 18:24:04.231  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-08 18:24:04.231  1015  1015 I InputMethodManagerService: [BT Setting State] State =12
09-08 18:24:04.231  1015  1015 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-08 18:24:04.231  1174  1174 D BluetoothTile:  onBluetoothStateChange:
,09-08 18:24:04.231  1431  1431 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@25a50668, true
,09-08 18:24:04.241  1431  1431 D BluetoothHeadset: registerMessageListener
,09-08 18:24:04.241  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-08 18:24:04.241  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:24:04.241  1174  1174 D BluetoothTile:  getBluetoothState : 12
,09-08 18:24:04.241  1174  1702 D BluetoothTile:  handleUpdatestate:false name:null
,09-08 18:24:04.241  1883  1883 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-08 18:24:04.241  1174  1702 D BluetoothTile:  handleUpdatestate:false name:null
,09-08 18:24:04.251  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:24:04.251  1015  3224 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-08 18:24:04.251  1015  1383 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-08 18:24:04.251  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-08 18:24:04.251  1174  1702 D BluetoothTile:  handleUpdatestate:false name:null
,09-08 18:24:04.251  6885  6948 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-08 18:24:04.251  1015  1487 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-08 18:24:04.251  1015  1487 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-08 18:24:04.251  1015  1487 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:24:04.251  1015  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:24:04.251  6885  6894 D HeadsetService: registerMessageListener
09-08 18:24:04.251  1015  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:24:04.261  6885  6894 D HeadsetService: registerMessageListener
09-08 18:24:04.261  6885  6911 D HeadsetStateMachine: Disconnected process message: 70
09-08 18:24:04.261  6885  6911 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@1d63845f
09-08 18:24:04.261  1431  1431 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,09-08 18:24:04.261  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-08 18:24:04.261  1300  1300 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-08 18:24:04.261  1431  1431 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,09-08 18:24:04.261  1431  1431 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
09-08 18:24:04.261  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-08 18:24:04.261  1300  1300 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-08 18:24:04.261  1300  1300 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-08 18:24:04.261  1300  1300 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-08 18:24:04.261  1300  1300 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-08 18:24:04.261  6885  6948 D BluetoothSocket: bindListen(): myUserId = 0
09-08 18:24:04.261  6885  6948 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 18:24:04.261  6885  6948 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
09-08 18:24:04.261  6885  6948 D BluetoothSocket: bindListen(), new LocalSocket 
09-08 18:24:04.261  6885  6948 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-08 18:24:04.261  6885  6948 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@162e7eac
,09-08 18:24:04.261  6885  6948 D BluetoothSocket: channel: 5
,09-08 18:24:04.261  6885  6911 D HeadsetStateMachine: Disconnected process message: 9
,09-08 18:24:04.271  6885  6911 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-08 18:24:04.281   284   720 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,09-08 18:24:04.281  1300  1300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-08 18:24:04.281   284   720 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-08 18:24:04.281   284   720 V voice   : voice_set_parameters: exit with code(-2)
09-08 18:24:04.281   284   720 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-08 18:24:04.281  1015  1487 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-08 18:24:04.281  1015  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-08 18:24:04.281   284   720 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-08 18:24:04.281   284   720 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-08 18:24:04.281   284   720 V audio_hw_primary: adev_set_parameters: exit
09-08 18:24:04.281  1015  1487 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:04.281  1015  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:04.281  1015  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-08 18:24:04.281  6885  6911 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-08 18:24:04.291  1300  1300 D DockEventReceiver: finishStartingService: stopping service
,09-08 18:24:04.291  1300  1300 D BluetoothNotiBroadcastReceiver: onReceive
,09-08 18:24:04.291  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-08 18:24:04.291  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-08 18:24:04.301  6885  6885 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b3ace6d
,09-08 18:24:04.301  6885  6885 D BtConfig.SecureMode: isSecureModeOn:false
,09-08 18:24:04.311  1015  1383 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 18:24:04.311  1015  1383 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-08 18:24:04.311  1015  1383 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:04.311  1015  1383 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:04.311  1015  1383 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 18:24:04.321  1907  1907 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-08 18:24:04.321  1015  3003 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-08 18:24:04.321  1015  3003 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-08 18:24:04.321  1015  3003 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:04.321  1015  3003 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:24:04.321  1015  3003 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:24:04.331  1907  6954 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-08 18:24:04.331  1907  1907 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-08 18:24:04.331  1015  3235 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 18:24:04.341  1015  3235 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:24:04.341  1015  3235 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:24:04.341  1015  3235 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:24:04.341  1015  3002 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-08 18:24:04.351  1015  1383 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 18:24:04.351  1015  1383 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:04.351  1015  1383 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 18:24:04.351  1015  1383 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:24:04.351  6885  6958 D BluetoothSocket: bindListen(): myUserId = 0
,09-08 18:24:04.351  6885  6958 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 18:24:04.361  1907  6954 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,09-08 18:24:04.361  6885  6958 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
09-08 18:24:04.361  6885  6958 D BluetoothSocket: bindListen(), new LocalSocket 
09-08 18:24:04.361  6885  6958 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-08 18:24:04.361  6885  6958 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@234c5d6
,09-08 18:24:04.361  6885  6958 D BluetoothSocket: channel: 12
,09-08 18:24:04.361  6885  6958 I BtOppRfcommListener: Accept thread started.
,09-08 18:24:04.501   289   289 E SMD     : DCD OFF
,09-08 18:24:04.891  1015  1494 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-08 18:24:04.891  1015  1494 D BatteryService: level:83, scale:100, status:2, health:2, present:true, voltage: 4082, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,09-08 18:24:04.891  1015  1494 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-08 18:24:04.891  1015  1494 D BatteryService: stay LED for charging
09-08 18:24:04.891  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-08 18:24:04.891  1015  1015 I MotionRecognitionService: Plugged,
09-08 18:24:04.891  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,09-08 18:24:04.891  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
09-08 18:24:04.891  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate,
09-08 18:24:04.901  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-08 18:24:04.901  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 83
,09-08 18:24:04.911  6885  6885 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-08 18:24:04.911  6885  6911 D HeadsetStateMachine: Disconnected process message: 10
,09-08 18:24:04.921  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:83 status:2 health:2
,09-08 18:24:04.921  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:83 status:2 health:2
,09-08 18:24:04.921  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:83 status:2 health:2
,09-08 18:24:04.931  6147  6197 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:24:04.931  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:04.931  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:24:04.931  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:24:04.931  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:24:04.931  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:24:04.931  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:24:04.931  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 18:24:04.941  6147  6197 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 18:24:04.941  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 18:24:04.941  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3ce81cb9 added. We now have 8 listener(s)
,09-08 18:24:04.941  6147  6197 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:24:04.941  1015  3224 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-08 18:24:04.941  1015  3224 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-08 18:24:04.941  1015  3224 D SecContentProvider2: mCursor = null
,09-08 18:24:04.951  1015  3224 D WifiService: setWifiEnabled: false pid=6147, uid=10155
,09-08 18:24:04.951  1015  3224 D SettingsProvider: name = wifi_on
,09-08 18:24:04.951  6147  6197 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:24:04.951  1015  1487 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-08 18:24:04.951  1015  1487 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-08 18:24:04.951  1015  1487 D SecContentProvider2: mCursor = null
,09-08 18:24:04.961  1015  1487 D WifiService: setWifiEnabled: true pid=6147, uid=10155
,09-08 18:24:04.961  1015  1487 W ActivityManager: Permission Denial: getCurrentUser() from pid=6147, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-08 18:24:04.961  1015  1487 W WifiService: Failed getting userId using ActivityManagerNative
09-08 18:24:04.961  1015  1487 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6147, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-08 18:24:04.961  1015  1487 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-08 18:24:04.961  1015  1487 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-08 18:24:04.961  1015  1487 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-08 18:24:04.961  1015  1487 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-08 18:24:04.961  1015  1487 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-08 18:24:04.961  1015  1487 D SettingsProvider: name = wifi_on
,09-08 18:24:04.961  1015  1126 E WifiHW  : ##################### set firmware type 0 #####################
,09-08 18:24:05.321  1015  1043 D Tethering: interfaceAdded wlan0
,09-08 18:24:05.331  1015  1129 E Tethering: No numeric data
,09-08 18:24:05.331  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-08 18:24:05.331  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-08 18:24:05.331  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,09-08 18:24:05.331  1015  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-08 18:24:05.331  1015  1129 D Tethering: clearTetheredNotification()
,09-08 18:24:05.341  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
,09-08 18:24:05.341  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
,09-08 18:24:05.341  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-08 18:24:05.341  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-08 18:24:05.341  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-08 18:24:05.341  1174  1174 D HotspotTile: updateTetherState():false, false
09-08 18:24:05.351  1015  1129 D Tethering: InitialState.processMessage what=4
09-08 18:24:05.351  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
09-08 18:24:05.351  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-08 18:24:05.351  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,09-08 18:24:05.351   279   997 I WifiHW  : wifi_change_fw_path(): fwpath = sta
09-08 18:24:05.351  1015  1129 E Tethering: No numeric data
,09-08 18:24:05.351   279   997 D SoftapController: Softap fwReload - Ok
09-08 18:24:05.351  1015  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-08 18:24:05.351  1015  1129 D Tethering: clearTetheredNotification(),
,09-08 18:24:05.361   279   997 D CommandListener: Setting iface cfg
09-08 18:24:05.361  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-08 18:24:05.361   279   997 D CommandListener: Trying to bring down wlan0
09-08 18:24:05.361  1174  1174 D HotspotTile: updateTetherState():false, false
,09-08 18:24:05.361  1015  1043 D Tethering: interfaceAdded p2p0
09-08 18:24:05.361  1015  1123 V NetworkStats: performPollLocked() took 23ms
09-08 18:24:05.361   279   997 D CommandListener: Clearing all IP addresses on wlan0
09-08 18:24:05.361  1015  1043 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-08 18:24:05.361  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:24:05.361  1015  1126 E WifiHW  : supplicant_name : p2p_supplicant
09-08 18:24:05.361  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
09-08 18:24:05.361  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:24:05.371  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated,
09-08 18:24:05.371  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-08 18:24:05.371  1015  1123 V NetworkStats: performPollLocked() took 4ms
09-08 18:24:05.371  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:24:05.371  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:24:05.371  1015  1126 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-08 18:24:05.371  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:24:05.381  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 18:24:05.381  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-08 18:24:05.381  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-08 18:24:05.381  1174  1702 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-08 18:24:05.381  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:05.381  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:05.381  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:05.381  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:05.381  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-08 18:24:05.381  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,09-08 18:24:05.381  1174  1174 D HotspotTile: onReceive : 2, 0
,09-08 18:24:05.381  1300  1300 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-08 18:24:05.381  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:24:05.391  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:24:05.391  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:24:05.391  1015  3140 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-08 18:24:05.391  1015  3140 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-08 18:24:05.391  1015  3140 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:05.391  1015  3140 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:05.391  1015  3140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-08 18:24:05.391  3600  3600 I Hs20UtilService: Starting #19
09-08 18:24:05.391  3600  3625 I Hs20UtilService: Message received 5011
,09-08 18:24:05.401  6417  6417 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-08 18:24:05.401  6417  6417 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-08 18:24:05.401  6417  6417 D SecurityLogAgent: StateMachine : Current State = 1
09-08 18:24:05.401  6417  6417 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-08 18:24:05.421  6972  6972 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,09-08 18:24:05.421  6972  6972 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-08 18:24:05.421  6972  6972 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-08 18:24:05.431  6972  6972 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
09-08 18:24:05.431   375   375 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6972
09-08 18:24:05.431   375   375 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
09-08 18:24:05.441  6972  6972 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-08 18:24:05.441  6972  6972 I wpa_supplicant: ssSupport state is = 1,
09-08 18:24:05.441  6972  6972 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-08 18:24:05.441  6972  6972 I SecureStorage: [INFO]: SPID(0x00000000)Processing data,
09-08 18:24:05.441   375   375 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6972
09-08 18:24:05.441   375   375 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,09-08 18:24:05.531  1015  2723 D SSRM:n  : SIOP:: AP = 340
,09-08 18:24:05.611   375   375 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0,
,09-08 18:24:05.611  6972  6972 I SecureStorage: [INFO]: SPID(0x00000004)Processing data has been completed,
,09-08 18:24:05.681  6972  6972 I wpa_supplicant: Ctrl_iface: loading cred from phone,
09-08 18:24:05.681  6972  6972 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,09-08 18:24:05.691  6972  6972 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
,09-08 18:24:05.691   375   375 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6972
09-08 18:24:05.691   375   375 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
09-08 18:24:05.691  6972  6972 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
09-08 18:24:05.691  6972  6972 I wpa_supplicant: ssSupport state is = 1
09-08 18:24:05.691  6972  6972 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-08 18:24:05.691  6972  6972 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-08 18:24:05.691  6972  6972 E wpa_supplicant: SIM READ ERROR
09-08 18:24:05.691  6972  6972 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-08 18:24:05.691  6972  6972 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-08 18:24:05.691  6972  6972 E wpa_supplicant: SIM READ ERROR
09-08 18:24:05.691  6972  6972 I wpa_supplicant: Blacklist: Clear (all) 
09-08 18:24:05.691  6972  6972 I wpa_supplicant: wpa_default_ap_write_once
09-08 18:24:05.691  6972  6972 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
09-08 18:24:05.691  6972  6972 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-08 18:24:05.691  6972  6972 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-08 18:24:05.691  6972  6972 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-08 18:24:05.691  6972  6972 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-08 18:24:05.691  6972  6972 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-08 18:24:05.691  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-08 18:24:05.691  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-08 18:24:05.691  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,09-08 18:24:05.761  6972  6972 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-08 18:24:06.031  6972  6972 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,09-08 18:24:06.031  6972  6972 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage,
,09-08 18:24:06.041  6972  6972 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
,09-08 18:24:06.051   375   375 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6972
09-08 18:24:06.051   375   375 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C,
,09-08 18:24:06.051  6972  6972 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
09-08 18:24:06.051  6972  6972 I wpa_supplicant: ssSupport state is = 1
,09-08 18:24:06.051  6972  6972 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-08 18:24:06.051  6972  6972 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,09-08 18:24:06.061  6972  6972 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
,09-08 18:24:06.061   375   375 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6972
09-08 18:24:06.061   375   375 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
09-08 18:24:06.071  6972  6972 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running,
09-08 18:24:06.071  6972  6972 I wpa_supplicant: ssSupport state is = 1
09-08 18:24:06.071  6972  6972 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-08 18:24:06.071  6972  6972 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-08 18:24:06.071  6972  6972 E wpa_supplicant: SIM READ ERROR
09-08 18:24:06.071  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
09-08 18:24:06.071  6972  6972 I wpa_supplicant: wpa_default_ap_write_once,
09-08 18:24:06.071  6972  6972 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-08 18:24:06.071  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-08 18:24:06.071  6972  6972 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-08 18:24:06.071  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
09-08 18:24:06.071  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
09-08 18:24:06.071  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
09-08 18:24:06.071  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,09-08 18:24:06.181  6972  6972 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
09-08 18:24:06.181  6972  6972 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-08 18:24:06.261  6972  6972 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,09-08 18:24:06.261  6972  6972 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-08 18:24:06.261  6972  6972 I wpa_supplicant: Skip scan - bUseNetwork false
,09-08 18:24:06.271  1015  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
09-08 18:24:06.271  1015  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21],
09-08 18:24:06.271  6972  6972 I wpa_supplicant: HOTSPOT20_ENABLE called
09-08 18:24:06.271  6972  6972 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-08 18:24:06.271  6972  6972 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-08 18:24:06.271  6972  6972 E wpa_supplicant: SIM READ ERROR
09-08 18:24:06.271  6972  6972 I wpa_supplicant: Blacklist: Clear (all) ,
09-08 18:24:06.291  6972  6972 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
09-08 18:24:06.301  1015  1126 D WifiNative-wlan0: callSECApiInt - ID [210]
09-08 18:24:06.301  6972  6972 I wpa_supplicant: Skip scan - bUseNetwork false
09-08 18:24:06.301  1015  1126 D WifiConfigStore: Loading config and enabling all networks 
09-08 18:24:06.301  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 18:24:06.311  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-08 18:24:06.311  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:06.311  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:06.311  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:06.311  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:06.311  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-08 18:24:06.311  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
09-08 18:24:06.311  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-08 18:24:06.311  1174  1702 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-08 18:24:06.311  1174  1174 D HotspotTile: onReceive : 3, 0
,09-08 18:24:06.321  1300  1300 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-08 18:24:06.321  1015  1126 E WifiConfigStore: Not a HS20
,09-08 18:24:06.321  1015  1126 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-08 18:24:06.321  1015  1342 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-08 18:24:06.321  1015  1342 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-08 18:24:06.321  1015  1342 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:06.321  1015  1342 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:06.321  1015  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-08 18:24:06.331  1015  1126 D WifiNative-wlan0: callSECApiInt - ID [65]
09-08 18:24:06.331  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-08 18:24:06.331  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
09-08 18:24:06.331  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,09-08 18:24:06.331  3600  3600 I Hs20UtilService: Starting #20
,09-08 18:24:06.331  1015  1126 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-08 18:24:06.331  6972  6972 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-08 18:24:06.331  6972  6972 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-08 18:24:06.331  6972  6972 I wpa_supplicant: reset timer : RESET_TIMER 0
09-08 18:24:06.331  6972  6972 I wpa_supplicant: P2P: Current p2p state = IDLE
,09-08 18:24:06.331  6972  6972 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-08 18:24:06.331  6972  6972 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,09-08 18:24:06.331  6972  6972 I wpa_supplicant: First Scan Start
09-08 18:24:06.331  6972  6972 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds,
09-08 18:24:06.341  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:24:06.341  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:06.341  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:24:06.341  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:24:06.341  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:24:06.341  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null,
09-08 18:24:06.341  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:24:06.341  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 18:24:06.341  1015  1126 D WifiNative-wlan0: Setting external_sim to 1
,09-08 18:24:06.341  1015  1126 D WifiStateMachine: Setting OUI to DA-A1-19
09-08 18:24:06.341  1015  1126 I WifiNative-HAL: startHal
09-08 18:24:06.341  1015  1126 E wifi    : getStaticLongField sWifiHalHandle 0x9ca3f88c
09-08 18:24:06.341  1015  1126 I WifiNative-HAL: Could not start hal
,09-08 18:24:06.341  3600  3625 I Hs20UtilService: Message received 5011
,09-08 18:24:06.341  6392  6392 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 18:24:06.351  6417  6417 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-08 18:24:06.351  6417  6417 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-08 18:24:06.351  6417  6417 D SecurityLogAgent: StateMachine : Current State = 1
09-08 18:24:06.351  6417  6417 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-08 18:24:06.351  6147  6147 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 18:24:06.351  1015  1126 E WifiNative-wlan0: do suspend true
,09-08 18:24:06.351  1015  1125 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-08 18:24:06.361   279   997 D CommandListener: Setting iface cfg
09-08 18:24:06.361   279   997 D CommandListener: Trying to bring up p2p0
,09-08 18:24:06.361  1015  1125 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-08 18:24:06.361  1015  1125 D WifiP2pService: P2pEnablingState
,09-08 18:24:06.361  1015  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-08 18:24:06.361  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3
,09-08 18:24:06.361  1015  1149 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:24:06.361  1015  1149 I WifiNative-HAL: startHal
09-08 18:24:06.361  1015  1149 E wifi    : getStaticLongField sWifiHalHandle 0x9dbf19bc
09-08 18:24:06.361  1015  1149 I WifiNative-HAL: Could not start hal
09-08 18:24:06.361  1015  1149 E WifiScanningService: could not start HAL
,09-08 18:24:06.361  1015  1015 D RttService: SCAN_AVAILABLE : 3
09-08 18:24:06.361  1015  1125 D WifiP2pService: P2pEnablingState{ what=147457 }
09-08 18:24:06.361  1015  1150 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:24:06.361  1015  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-08 18:24:06.361  1015  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-08 18:24:06.361  1015  1126 E WifiNative-wlan0: invaild command id : 215
09-08 18:24:06.371  1015  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-08 18:24:06.371  1015  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-08 18:24:06.371  1015  1126 E WifiNative-wlan0: invaild command id : 215
,09-08 18:24:06.371  1015  1125 D WifiP2pService: P2p socket connection successful
,09-08 18:24:06.371  1015  1125 D WifiP2pService: P2pEnabledState
,09-08 18:24:06.371  6972  6972 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
09-08 18:24:06.371  1015  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-08 18:24:06.371  1015  1128 E ConnectivityService: updateNetworkInfo()
,09-08 18:24:06.371  6972  6972 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-08 18:24:06.371  1015  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-08 18:24:06.371  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-08 18:24:06.371  1015  1046 D WifiDisplayController: disconnect
09-08 18:24:06.371  1015  1046 D WifiDisplayController: updateConnection
09-08 18:24:06.371  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-08 18:24:06.371  6972  6972 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
09-08 18:24:06.371  1015  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-08 18:24:06.371  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-08 18:24:06.381  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-08 18:24:06.381  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
09-08 18:24:06.381  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-08 18:24:06.381  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
09-08 18:24:06.381  1300  1300 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-08 18:24:06.381  1300  1300 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-08 18:24:06.381  1015  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-08 18:24:06.381  1015  1126 D SecContentProvider2: mCursor = null
,09-08 18:24:06.381  1174  1174 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-08 18:24:06.381  1015  3140 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-08 18:24:06.381  1174  1174 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-08 18:24:06.381  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-08 18:24:06.381  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-08 18:24:06.381  1015  1125 D WifiNative-p2p0: p2pGetDeviceAddress
09-08 18:24:06.381  1015  1125 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
09-08 18:24:06.381  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-08 18:24:06.381  1015  1125 D WifiP2pService: DeviceAddress: 7e:96:ac
09-08 18:24:06.381  1015  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-08 18:24:06.381  1015  1126 D SecContentProvider2: mCursor = null
09-08 18:24:06.381  1015  1046 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
09-08 18:24:06.381  1015  1046 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
09-08 18:24:06.381  1015  1046 D WifiDisplayController:  primary type: 10-0050F204-5
09-08 18:24:06.381  1015  1046 D WifiDisplayController:  secondary type: null
09-08 18:24:06.381  1015  1046 D WifiDisplayController:  wps: 0
09-08 18:24:06.381  1015  1046 D WifiDisplayController:  grpcapab: 0
09-08 18:24:06.381  1015  1046 D WifiDisplayController:  devcapab: 0
09-08 18:24:06.381  1015  1046 D WifiDisplayController:  status: 3
09-08 18:24:06.381  1015  1046 D WifiDisplayController:  wfdInfo: null
09-08 18:24:06.381  1015  1046 D WifiDisplayController:  groupownerAddress: null
09-08 18:24:06.381  1015  1046 D WifiDisplayController:  GOdeviceName: null
09-08 18:24:06.381  1015  1046 D WifiDisplayController:  interfaceAddress: 
09-08 18:24:06.381  1015  1046 D WifiDisplayController:  SConnectInfo : null
,09-08 18:24:06.391  1300  1300 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-08 18:24:06.391  1300  3096 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-08 18:24:06.391  6362  6362 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-08 18:24:06.391  6362  6362 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-08 18:24:06.391  6362  6362 D FileShare-Client: Outbound.stopDelayTimer - 
,09-08 18:24:06.401  6377  6377 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-08 18:24:06.411  1015  1125 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-08 18:24:06.411  1015  1125 D WifiP2pService: InactiveState
,09-08 18:24:06.411  1015  1125 D WifiP2pService: InactiveState{ what=143376 }
,09-08 18:24:06.411  1015  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-08 18:24:06.411  6972  6972 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
09-08 18:24:06.411  1015  1125 D WifiP2pService: InactiveState{ what=143376 }
09-08 18:24:06.411  1015  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-08 18:24:06.981  6147  6197 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:24:06.981  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:06.981  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:24:06.981  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:24:06.981  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:24:06.981  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:24:06.981  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:24:06.981  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 18:24:06.981  6147  6197 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 18:24:06.991  6147  6197 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-08 18:24:06.991  6147  6197 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-08 18:24:06.991  6147  6197 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@28392cdd Bundle[{}]
,09-08 18:24:07.001  6147  6197 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-08 18:24:07.001  6147  6197 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-08 18:24:07.001  6147  6197 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-08 18:24:07.001  6147  6197 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-08 18:24:07.001  6147  6197 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-08 18:24:07.001  6147  6197 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-08 18:24:07.011  6147  6197 I System.out: Running OutgoingSocketThread
,09-08 18:24:07.011  6147  6979 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1158)
,09-08 18:24:07.011  6147  6979 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 52914
,09-08 18:24:07.011  6147  6979 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-08 18:24:07.371  6972  6972 I wpa_supplicant: nl80211: Received scan results (25 BSSes),
09-08 18:24:07.371  6972  6972 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-08 18:24:07.371  6972  6972 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-08 18:24:07.371  6972  6972 I wpa_supplicant: Trying to associate with  'G700'
,09-08 18:24:07.371  6972  6972 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING,
09-08 18:24:07.371  6972  6972 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
09-08 18:24:07.371  1015  6977 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-08 18:24:07.401  1015  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-08 18:24:07.401  1015  1126 D SecContentProvider2: mCursor = null
,09-08 18:24:07.481  6972  6972 E wpa_supplicant: Cmd 35605 not handled
,09-08 18:24:07.481  6972  6972 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-08 18:24:07.481  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-08 18:24:07.481  6972  6972 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-08 18:24:07.481  6972  6972 I wpa_supplicant: Associated with F4.99.3E
09-08 18:24:07.481  6972  6972 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,09-08 18:24:07.481  6972  6972 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-08 18:24:07.481  6972  6972 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-08 18:24:07.481  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-08 18:24:07.491  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-08 18:24:07.481  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
09-08 18:24:07.491  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-08 18:24:07.491  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
09-08 18:24:07.491  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-08 18:24:07.491  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, true
09-08 18:24:07.491  1015  1043 D Tethering: interfaceStatusChanged wlan0, true
,09-08 18:24:07.491  1015  1129 E Tethering: No numeric data
,09-08 18:24:07.491  1015  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-08 18:24:07.491  1015  1129 D Tethering: clearTetheredNotification()
09-08 18:24:07.491  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
09-08 18:24:07.491  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:24:07.491  1015  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-08 18:24:07.491  1015  1126 D SecContentProvider2: mCursor = null
09-08 18:24:07.491  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-08 18:24:07.491  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-08 18:24:07.491  6972  6972 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,09-08 18:24:07.491  6972  6972 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
09-08 18:24:07.491  6972  6972 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-08 18:24:07.491  6972  6972 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,09-08 18:24:07.491  6972  6972 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-08 18:24:07.491  6972  6972 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-08 18:24:07.491  6972  6972 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-08 18:24:07.491  6972  6972 I wpa_supplicant: Blacklist: Clear (temp) 
09-08 18:24:07.491  6972  6972 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-08 18:24:07.491  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:24:07.491  1015  1123 V NetworkStats: performPollLocked() took 4ms
,09-08 18:24:07.501  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, true
09-08 18:24:07.501  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-08 18:24:07.501  1015  1043 D Tethering: interfaceStatusChanged wlan0, true
,09-08 18:24:07.501  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-08 18:24:07.501  1174  1174 D HotspotTile: updateTetherState():false, false
,09-08 18:24:07.501  1015  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-08 18:24:07.501  1015  1126 D SecContentProvider2: mCursor = null
,09-08 18:24:07.501   289   289 E SMD     : DCD OFF
,09-08 18:24:07.501  1015  1126 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-08 18:24:07.511  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:24:07.511  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:24:07.511  1015  1126 E WifiConfigStore: setLastSelectedConfiguration -1,
,09-08 18:24:07.511  1015  1126 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-08 18:24:07.511  1015  1128 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-08 18:24:07.511  1015  1128 E ConnectivityService: updateNetworkInfo()
09-08 18:24:07.511  1015  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-08 18:24:07.521  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-08 18:24:07.521  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-08 18:24:07.521  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:24:07.521  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:07.521  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:07.521  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:24:07.521  1015  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 18:24:07.521  1015  1487 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-08 18:24:07.531  1015  1487 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:07.531  1015  1487 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-08 18:24:07.531  1015  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:07.531  1015  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-08 18:24:07.531  3600  3600 I Hs20UtilService: Starting #21
09-08 18:24:07.531  3600  3625 I Hs20UtilService: Message received 5007
,09-08 18:24:07.531  1300  1300 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
09-08 18:24:07.531  1300  1300 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-08 18:24:07.541  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-08 18:24:07.541  1015  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 18:24:07.541  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-08 18:24:07.541  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-08 18:24:07.541  1300  1300 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-08 18:24:07.541  1300  3096 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-08 18:24:07.551   279   997 D CommandListener: Setting iface cfg
,09-08 18:24:07.561  1015  1126 E WifiStateMachine: Start Dhcp Watchdog 3
,09-08 18:24:07.561  1015  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-08 18:24:07.561  1015  1126 D SecContentProvider2: mCursor = null
,09-08 18:24:07.571  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-08 18:24:07.571  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-08 18:24:07.571  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:24:07.571  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:24:07.571  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:07.571  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:24:07.581  1015  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-08 18:24:07.581  1015  1126 D SecContentProvider2: mCursor = null
,09-08 18:24:07.581  1015  1126 E WifiNative-wlan0: do suspend false
,09-08 18:24:07.591  1015  1125 D WifiP2pService: InactiveState{ what=143375 }
,09-08 18:24:07.591  1015  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-08 18:24:07.801  6982  6982 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-08 18:24:07.801  6982  6982 I dhcpcd  : version 5.5.6 starting
,09-08 18:24:07.811  6982  6982 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-08 18:24:07.851  6982  6982 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
09-08 18:24:07.861  6982  6982 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-08 18:24:07.861  6982  6982 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,09-08 18:24:07.861  6982  6982 I dhcpcd  : bssid match
09-08 18:24:07.861  6982  6982 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111
,09-08 18:24:08.011  6147  6197 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1159)
,09-08 18:24:08.011  6147  6197 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1159)
,09-08 18:24:08.011  6147  6197 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1164)
,09-08 18:24:08.011  6147  6197 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-08 18:24:08.011  6147  6197 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1165)
,09-08 18:24:08.021  6147  6197 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 18:24:08.021  6147  6197 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17aac8fe added. We now have 2 listener(s)
,09-08 18:24:08.021  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-08 18:24:08.021  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:24:08.021  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 18:24:08.021  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:24:08.021  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f69285f added. We now have 9 listener(s)
,09-08 18:24:08.031  6147  6197 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 18:24:08.031  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 18:24:08.031  6982  6982 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1
09-08 18:24:08.031  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 18:24:08.031  6147  6197 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:24:08.031  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:08.031  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:24:08.031  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:24:08.031  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:24:08.031  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:24:08.031  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:24:08.031  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 18:24:08.041  6147  6197 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 18:24:08.041  6147  6197 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 18:24:08.041  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:24:08.041  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:24:08.041  6147  6197 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 18:24:08.041  6147  6197 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3264cb75 added. We now have 3 listener(s)
09-08 18:24:08.051  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-08 18:24:08.051  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:24:08.051  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 18:24:08.051  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:24:08.051  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c66770a added. We now have 10 listener(s)
09-08 18:24:08.051  6147  6197 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 18:24:08.051  6147  6197 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:24:08.051  6147  6197 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:24:08.051  6147  6197 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:24:08.051  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:24:08.051  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:08.051  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:24:08.051  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:24:08.051  6147  6197 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17aac8fe removed from the list
09-08 18:24:08.051  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:08.051  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f69285f removed from the list
09-08 18:24:08.051  6147  6197 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:24:08.061  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:08.061  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:08.061  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:08.061  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:24:08.061  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:24:08.061  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:08.061  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f69285f not in the list
09-08 18:24:08.061  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:08.061  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:24:08.061  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 18:24:08.061  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:24:08.061  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 18:24:08.061  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c66770a removed from the list
09-08 18:24:08.061  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:24:08.061  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:24:08.061  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:08.061  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:24:08.061  6147  6197 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3264cb75 removed from the list
,09-08 18:24:08.061  6147  6197 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 18:24:08.061  6147  6197 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ba1eb7b added. We now have 2 listener(s)
,09-08 18:24:08.071  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-08 18:24:08.071  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:24:08.071  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 18:24:08.071  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:24:08.071  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25d2ed98 added. We now have 9 listener(s)
09-08 18:24:08.071  6147  6197 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:24:08.071  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 18:24:08.071  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:24:08.081  6147  6197 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:24:08.081  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:08.081  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:24:08.081  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:24:08.081  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:24:08.081  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:24:08.081  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:24:08.081  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 18:24:08.081  6147  6197 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 18:24:08.081  6147  6197 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 18:24:08.081  6147  6197 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 18:24:08.081  6147  6197 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47cf9d6 added. We now have 3 listener(s)
,09-08 18:24:08.081  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:24:08.081  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:24:08.081  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-08 18:24:08.091  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-08 18:24:08.091  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 18:24:08.091  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 18:24:08.091  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed9c457 added. We now have 10 listener(s)
09-08 18:24:08.091  6147  6197 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 18:24:08.091  6147  6197 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 18:24:08.091  6147  6197 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 18:24:08.091  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 18:24:08.091  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 18:24:08.091  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 18:24:08.091  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 18:24:08.101  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 18:24:08.101  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-08 18:24:08.101  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-08 18:24:08.101  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 18:24:08.101  6147  6197 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-08 18:24:08.101  6885  6947 D BtGatt.GattService: registerClient() - UUID=1e54886e-8c67-4ed7-a63d-096bc8d4455f
,09-08 18:24:08.141  6982  6982 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds,
,09-08 18:24:08.141  6885  6903 D BtGatt.GattService: onClientRegistered() - UUID=1e54886e-8c67-4ed7-a63d-096bc8d4455f, clientIf=6
,09-08 18:24:08.151  6147  6155 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-08 18:24:08.151  6885  6893 D BtGatt.GattService: start scan with filters
,09-08 18:24:08.151  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-08 18:24:08.151  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 18:24:08.151  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-08 18:24:08.151  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 18:24:08.151  6885  6909 D BtGatt.ScanManager: handling starting scan
,09-08 18:24:08.161  6885  6909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b3ace6d
,09-08 18:24:08.161  6147  6197 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 18:24:08.161  6147  6197 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 18:24:08.161  6147  6147 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 18:24:08.171  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
09-08 18:24:08.171  6147  6197 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-08 18:24:08.171  6147  6197 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-08 18:24:08.171  6147  6197 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything,
09-08 18:24:08.171  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:08.171  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 18:24:08.171  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 18:24:08.171  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
09-08 18:24:08.171  6147  6197 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 18:24:08.171  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-08 18:24:08.181  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 18:24:08.181  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-08 18:24:08.181  6885  6903 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-08 18:24:08.181  6885  6903 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-08 18:24:08.181  6885  6909 D BtGatt.ScanManager: allow scan with filters
09-08 18:24:08.181  6885  6909 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-08 18:24:08.181  6885  6909 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-08 18:24:08.181  6885  6893 D BtGatt.GattService: stopScan() - queue size =1
,09-08 18:24:08.181  6885  6903 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-08 18:24:08.181  6885  6903 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
09-08 18:24:08.181  6885  6909 D BtGatt.ScanManager: Starting BLE batch scan
09-08 18:24:08.181  6885  6909 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-08 18:24:08.181  6885  6894 D BtGatt.GattService: unregisterClient() - clientIf=6
09-08 18:24:08.191  6885  6903 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-08 18:24:08.191  6885  6903 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-08 18:24:08.191  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 18:24:08.191  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 18:24:08.191  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 18:24:08.191  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-08 18:24:08.191  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 18:24:08.191  6147  6197 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 18:24:08.191  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 18:24:08.191  6147  6197 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 18:24:08.191  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 18:24:08.191  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:24:08.191  6147  6147 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:24:08.191  6147  6147 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 18:24:08.191  6147  6147 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 18:24:08.191  6885  6903 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-08 18:24:08.191  6885  6903 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:24:08.201  6147  6197 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:24:08.201  6147  6197 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:24:08.201  6147  6197 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:24:08.201  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 18:24:08.201  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:08.201  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:24:08.201  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:24:08.201  6147  6197 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ba1eb7b removed from the list
09-08 18:24:08.201  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:08.201  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25d2ed98 removed from the list
,09-08 18:24:08.201  6147  6197 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:24:08.201  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:24:08.201  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:08.201  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:24:08.201  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
,09-08 18:24:08.201  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:24:08.201  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:08.201  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25d2ed98 not in the list
,09-08 18:24:08.201  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:08.201  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:08.201  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-08 18:24:08.201  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:24:08.201  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:08.201  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed9c457 removed from the list
,09-08 18:24:08.201  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:24:08.201  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:08.201  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:24:08.201  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:24:08.201  6147  6197 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47cf9d6 removed from the list
,09-08 18:24:08.211  6147  6197 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 18:24:08.211  6147  6197 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@174c4ef3 added. We now have 2 listener(s)
,09-08 18:24:08.211  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-08 18:24:08.211  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:24:08.211  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 18:24:08.211  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:24:08.211  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7dd7b0 added. We now have 9 listener(s)
09-08 18:24:08.211  6147  6197 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 18:24:08.211  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 18:24:08.221  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:24:08.231  6885  6909 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 45,
,09-08 18:24:08.231  6885  6909 D BtGatt.ScanManager: filter size is 1
09-08 18:24:08.231  1015  1041 W ProcessCpuTracker: Skipping unknown process pid 6991
,09-08 18:24:08.231  6885  6909 D BtGatt.ScanManager: delete FilterIndex - 3
,09-08 18:24:08.231  6147  6197 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:24:08.231  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:08.231  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,09-08 18:24:08.231  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:24:08.231  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:24:08.231  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:24:08.231  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
,09-08 18:24:08.231  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 18:24:08.241  6885  6903 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-08 18:24:08.241  6885  6903 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:24:08.241  6885  6909 D BtGatt.ScanManager: stopping BLe Batch
,09-08 18:24:08.241  6147  6197 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
09-08 18:24:08.241  6147  6197 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 18:24:08.241  6147  6197 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 18:24:08.241  6147  6197 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36996dae added. We now have 3 listener(s)
,09-08 18:24:08.241  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:24:08.241  6885  6903 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-08 18:24:08.241  6885  6903 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:24:08.241  6885  6909 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-08 18:24:08.241  6885  6903 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-08 18:24:08.241  6885  6903 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-08 18:24:08.241  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:24:08.241  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-08 18:24:08.241  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:24:08.241  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 18:24:08.251  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:24:08.251  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@152e74f added. We now have 10 listener(s)
09-08 18:24:08.251  6147  6197 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 18:24:08.251  6147  6197 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 18:24:08.251  6147  6197 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 18:24:08.251  6147  6197 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 18:24:08.251  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 18:24:08.251  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:24:08.251  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 18:24:08.251  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 18:24:08.261  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 18:24:08.261  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 18:24:08.271  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-08 18:24:08.271  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 18:24:08.271  6147  6197 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-08 18:24:08.271  6885  6893 D BtGatt.GattService: registerClient() - UUID=09128c76-ddb0-4a4f-8dfe-cb058e06f06b
,09-08 18:24:08.311  6885  6903 D BtGatt.GattService: onClientRegistered() - UUID=09128c76-ddb0-4a4f-8dfe-cb058e06f06b, clientIf=6
,09-08 18:24:08.311  6147  6157 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-08 18:24:08.311  6885  6904 D BtGatt.GattService: start scan with filters
,09-08 18:24:08.321  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-08 18:24:08.321  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 18:24:08.321  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 18:24:08.321  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 18:24:08.321  6885  6909 D BtGatt.ScanManager: handling starting scan
,09-08 18:24:08.321  6147  6197 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 18:24:08.321  6147  6147 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
09-08 18:24:08.321  6147  6197 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 18:24:08.321  6885  6903 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
09-08 18:24:08.321  6885  6903 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
09-08 18:24:08.321  6885  6909 D BtGatt.ScanManager: allow scan with filters
09-08 18:24:08.321  6885  6909 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-08 18:24:08.321  6885  6909 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
09-08 18:24:08.321  6885  6903 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15,
09-08 18:24:08.321  6885  6903 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-08 18:24:08.321  6885  6909 D BtGatt.ScanManager: Starting BLE batch scan
09-08 18:24:08.321  6885  6909 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
09-08 18:24:08.331  6885  6903 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
09-08 18:24:08.331  6885  6903 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-08 18:24:08.331  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 18:24:08.331  6885  6903 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
09-08 18:24:08.331  6885  6903 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:24:08.331  6147  6197 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 18:24:08.331  6147  6197 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-08 18:24:08.331  6147  6197 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:24:08.331  6147  6197 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:24:08.331  6147  6197 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:24:08.331  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:24:08.331  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:08.331  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 18:24:08.331  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:24:08.331  6147  6197 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@174c4ef3 removed from the list
09-08 18:24:08.331  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:08.331  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7dd7b0 removed from the list
09-08 18:24:08.331  6147  6197 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:24:08.331  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:24:08.341  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:08.341  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-08 18:24:08.341  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:08.341  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:24:08.341  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 18:24:08.341  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:24:08.341  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:08.341  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7dd7b0 not in the list
,09-08 18:24:08.341  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 18:24:08.341  6147  6197 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 18:24:08.341  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 18:24:08.341  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 18:24:08.341  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-08 18:24:08.351  6885  6904 D BtGatt.GattService: stopScan() - queue size =1
,09-08 18:24:08.351  6885  6909 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 46
,09-08 18:24:08.351  6885  6909 D BtGatt.ScanManager: filter size is 1,
09-08 18:24:08.351  6885  6909 D BtGatt.ScanManager: delete FilterIndex - 4
09-08 18:24:08.351  6885  6947 D BtGatt.GattService: unregisterClient() - clientIf=6
09-08 18:24:08.351  6885  6903 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
09-08 18:24:08.351  6885  6903 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-08 18:24:08.351  6885  6909 D BtGatt.ScanManager: stopping BLe Batch,
09-08 18:24:08.351  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-08 18:24:08.351  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 18:24:08.351  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 18:24:08.351  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 18:24:08.351  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 18:24:08.351  6147  6197 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 18:24:08.351  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 18:24:08.351  6885  6903 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-08 18:24:08.351  6885  6903 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-08 18:24:08.351  6147  6197 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 18:24:08.351  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 18:24:08.361  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:08.361  6885  6909 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-08 18:24:08.361  6885  6903 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-08 18:24:08.361  6885  6903 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:24:08.361  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-08 18:24:08.361  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:24:08.361  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:08.361  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@152e74f removed from the list
09-08 18:24:08.361  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:24:08.361  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:08.361  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:08.361  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:24:08.361  6147  6197 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36996dae removed from the list
09-08 18:24:08.361  6147  6197 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 18:24:08.361  6147  6197 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b80a96b added. We now have 2 listener(s)
,09-08 18:24:08.371  6147  6147 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 18:24:08.371  6147  6147 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:24:08.371  6147  6147 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 18:24:08.371  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB",
09-08 18:24:08.371  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:24:08.371  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 18:24:08.371  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:24:08.371  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d28ecc8 added. We now have 9 listener(s)
09-08 18:24:08.371  6147  6197 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:24:08.371  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 18:24:08.381  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:24:08.381  6147  6197 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:24:08.381  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:08.381  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:24:08.381  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:24:08.381  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:24:08.381  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:24:08.381  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:24:08.381  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 18:24:08.381  6147  6197 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 18:24:08.381  6147  6197 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 18:24:08.381  6147  6197 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 18:24:08.381  6147  6197 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ea58486 added. We now have 3 listener(s)
,09-08 18:24:08.381  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-08 18:24:08.381  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-08 18:24:08.381  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:24:08.381  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 18:24:08.381  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:24:08.381  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:24:08.381  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7147 added. We now have 10 listener(s)
09-08 18:24:08.381  6147  6197 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:24:08.381  6147  6197 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 18:24:08.381  6147  6197 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 18:24:08.381  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 18:24:08.381  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 18:24:08.381  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 18:24:08.391  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 18:24:08.391  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 18:24:08.391  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 18:24:08.401  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-08 18:24:08.401  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 18:24:08.401  6147  6197 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-08 18:24:08.401  6885  6894 D BtGatt.GattService: registerClient() - UUID=cc6f48db-1dfb-4bac-a908-86774cda9538
,09-08 18:24:08.401  1015  1126 E WifiNative-wlan0: do suspend true
,09-08 18:24:08.431  1015  1125 D WifiP2pService: InactiveState{ what=143375 }
,09-08 18:24:08.431  1015  1126 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-08 18:24:08.431  1015  1126 E WifiStateMachine: VerifyingLinkState enter
,09-08 18:24:08.431  1015  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-08 18:24:08.431  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 18:24:08.431  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-08 18:24:08.431  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:08.431  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:08.431  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:08.431  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:24:08.431  1015  1126 D WifiNative-wlan0: callSECApiInt - ID [210],
09-08 18:24:08.431  1015  1128 E ConnectivityService: updateNetworkInfo()
,09-08 18:24:08.441  1015  1128 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,09-08 18:24:08.441  1015  1128 D ConnectivityService: Adding iface wlan0 to network 504
,09-08 18:24:08.441  6885  6903 D BtGatt.GattService: onClientRegistered() - UUID=cc6f48db-1dfb-4bac-a908-86774cda9538, clientIf=6
09-08 18:24:08.441  1015  1143 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
09-08 18:24:08.441  1015  1143 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-08 18:24:08.441  1015  1143 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-08 18:24:08.441  1015  1143 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-08 18:24:08.441  1015  1143 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-08 18:24:08.441  6147  6157 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-08 18:24:08.451  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 18:24:08.451  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-08 18:24:08.451  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:08.451  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:08.451  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:08.451  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:24:08.451  6885  6947 D BtGatt.GattService: start scan with filters
,09-08 18:24:08.451  6885  6909 D BtGatt.ScanManager: handling starting scan
,09-08 18:24:08.451  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-08 18:24:08.451  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-08 18:24:08.451  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 18:24:08.451  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 18:24:08.451  6147  6197 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 18:24:08.451  6885  6903 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-08 18:24:08.451  6885  6903 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-08 18:24:08.451  6885  6909 D BtGatt.ScanManager: allow scan with filters
09-08 18:24:08.461  6885  6909 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-08 18:24:08.461  6885  6909 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-08 18:24:08.461  6147  6197 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 18:24:08.461  6147  6147 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 18:24:08.461  1015  3224 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-08 18:24:08.461  1015  1128 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
09-08 18:24:08.461  1015  3224 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-08 18:24:08.461  1015  3224 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:24:08.461  1015  3224 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:08.461  1015  1126 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,09-08 18:24:08.461  1015  3224 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-08 18:24:08.471  1015  1128 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,09-08 18:24:08.471  6885  6903 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-08 18:24:08.471  6885  6903 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-08 18:24:08.471  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 18:24:08.471  1015  1128 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
09-08 18:24:08.471  6885  6909 D BtGatt.ScanManager: Starting BLE batch scan
09-08 18:24:08.471  6885  6909 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-08 18:24:08.471  1015  1128 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-08 18:24:08.471  1015  1128 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
09-08 18:24:08.471  1015  1128 D ConnectivityService: LTETest block dns file not exists
,09-08 18:24:08.471  3600  3600 I Hs20UtilService: Starting #22
,09-08 18:24:08.471  1300  1300 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-08 18:24:08.471  1015  1128 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
09-08 18:24:08.471  1300  1300 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-08 18:24:08.481  3600  3625 I Hs20UtilService: Message received 5007
,09-08 18:24:08.481  1015  1128 E ConnectivityService: updateNetworkInfo()
,09-08 18:24:08.481  6885  6903 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-08 18:24:08.481  6885  6903 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:24:08.491  6147  6197 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 18:24:08.491  6147  6197 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:24:08.491  6147  6197 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:24:08.491  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 18:24:08.491  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:08.491  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 18:24:08.491  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:24:08.491  6147  6197 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b80a96b removed from the list
,09-08 18:24:08.491  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:08.491  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d28ecc8 removed from the list
09-08 18:24:08.491  6147  6197 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:24:08.491  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:24:08.491  6885  6903 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-08 18:24:08.491  6885  6903 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:24:08.501  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:08.501  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-08 18:24:08.501  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:08.501  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:24:08.501  1015  1126 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-08 18:24:08.501  1015  1126 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-08 18:24:08.501  1015  1128 E ConnectivityService: updateNetworkInfo()
09-08 18:24:08.501  1015  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 18:24:08.501  1015  1128 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
,09-08 18:24:08.501  1015  1128 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
,09-08 18:24:08.501  1015  6980 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:24:08.501  1015  6980 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
,09-08 18:24:08.501  1015  6980 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-08 18:24:08.501  1015  6980 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
09-08 18:24:08.501  1015  6980 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-08 18:24:08.511   279   993 D EnterpriseController: uids 1000
09-08 18:24:08.511   279   993 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-08 18:24:08.511   279   993 D Netd    : getNetworkForDns: using netid 504 for uid 1000
09-08 18:24:08.511  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:24:08.511  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:24:08.511  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:08.511  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d28ecc8 not in the list
09-08 18:24:08.511  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 18:24:08.511  6147  6197 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 18:24:08.511  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 18:24:08.511  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-08 18:24:08.511  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-08 18:24:08.511  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-08 18:24:08.511  6885  6909 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 47
,09-08 18:24:08.511  1015  1128 D ConnectivityService:    accepting network in place of null
,09-08 18:24:08.511  1015  1125 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-08 18:24:08.511  1015  1126 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,09-08 18:24:08.511  1452  1452 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-08 18:24:08.511  1452  1452 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-08 18:24:08.511  6885  6904 D BtGatt.GattService: stopScan() - queue size =1
,09-08 18:24:08.511  6885  6909 D BtGatt.ScanManager: filter size is 1
09-08 18:24:08.511  6885  6909 D BtGatt.ScanManager: delete FilterIndex - 5
09-08 18:24:08.511  6885  6894 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-08 18:24:08.521  1015  1128 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-08 18:24:08.521  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 18:24:08.521  1015  1128 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
09-08 18:24:08.521  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 18:24:08.521  1015  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-08 18:24:08.521  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 18:24:08.521  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 18:24:08.521  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 18:24:08.521  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-08 18:24:08.521  6147  6197 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 18:24:08.521  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-08 18:24:08.521  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 18:24:08.521  6147  6197 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 18:24:08.521  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 18:24:08.521  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:08.521  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:08.521  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:08.521  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:24:08.521  6885  6903 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-08 18:24:08.521  6885  6903 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-08 18:24:08.521  6885  6909 D BtGatt.ScanManager: stopping BLe Batch
,09-08 18:24:08.521  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-08 18:24:08.521  1015  1015 I WifiTrafficPoller: mBoosterFLAG : 0
09-08 18:24:08.521  1015  1015 I WifiTrafficPoller: current booster mode : FullMode
,09-08 18:24:08.531  1015  1015 D WifiNative-wlan0: callSECApiVoid - ID [212]
,09-08 18:24:08.531  6885  6903 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-08 18:24:08.531  6885  6903 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-08 18:24:08.531  6885  6909 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-08 18:24:08.531  6885  6903 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-08 18:24:08.531  6885  6903 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 18:24:08.531  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 18:24:08.531  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-08 18:24:08.531  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:24:08.531  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:08.531  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:08.531  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:24:08.541  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:08.541  1015  3002 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-08 18:24:08.541  1015  3002 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-08 18:24:08.541  1015  1128 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
09-08 18:24:08.541  1015  3002 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:08.541  1015  3002 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:08.541  1015  3002 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-08 18:24:08.541  1015  1128 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,09-08 18:24:08.541  3600  3600 I Hs20UtilService: Starting #23
09-08 18:24:08.541  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-08 18:24:08.541  1015  1129 D Tethering: MasterInitialState.processMessage what=3
,09-08 18:24:08.541  3600  3625 I Hs20UtilService: Message received 5007
,09-08 18:24:08.541  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:24:08.541  1015  1123 V NetworkStats: updateIfacesLocked()
09-08 18:24:08.541  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
09-08 18:24:08.541  1015  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-08 18:24:08.541  1174  1695 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-08 18:24:08.541  3786  6209 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-08 18:24:08.551  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-08 18:24:08.551  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-08 18:24:08.551  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:24:08.551  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:24:08.551  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:08.551  1015  1123 V NetworkStats: performPollLocked() took 5ms
09-08 18:24:08.551  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e7147 removed from the list
09-08 18:24:08.551  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:24:08.551  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:08.551  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:08.551  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:24:08.551  6147  6197 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ea58486 removed from the list
09-08 18:24:08.551  6147  6147 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:24:08.551  6147  6147 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:24:08.551  6147  6147 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 18:24:08.551  6147  6197 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 18:24:08.551  6147  6197 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a6dae3 added. We now have 2 listener(s)
09-08 18:24:08.551  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:24:08.551  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:24:08.551  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:24:08.551  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:24:08.551  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:24:08.551  1015  1124 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,09-08 18:24:08.551  1174  1174 D StatusBar.NetworkController: EthernetConnected: false
09-08 18:24:08.551  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-08 18:24:08.551  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-08 18:24:08.551  1174  1174 D StatusBar.NetworkController: updateDataNetType()
09-08 18:24:08.551  1174  1174 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-08 18:24:08.551  1174  1174 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-08 18:24:08.561  1300  1300 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-08 18:24:08.561  1300  1300 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-08 18:24:08.561  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,09-08 18:24:08.561  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-08 18:24:08.561  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:24:08.561  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 18:24:08.561  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:24:08.561  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@264e8ce0 added. We now have 9 listener(s)
09-08 18:24:08.561  6147  6197 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:24:08.561  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 18:24:08.561  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-08 18:24:08.561  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
09-08 18:24:08.561  1300  1300 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-08 18:24:08.561  1174  1174 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-08 18:24:08.561  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-08 18:24:08.561  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,09-08 18:24:08.561  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 18:24:08.561  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-08 18:24:08.561  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:08.561  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:08.561  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:08.561  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:24:08.571  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:24:08.571  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:24:08.571  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:24:08.571  6147  6197 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:24:08.571  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:08.571  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:24:08.571  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:24:08.571  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:24:08.571  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:24:08.571  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:24:08.571  6147  6197 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 18:24:08.571  6147  6197 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 18:24:08.581  6147  6197 D io.jxcore.node.ConnectivityMonitor: start: OK,
09-08 18:24:08.581  6147  6197 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 18:24:08.581  1015  1028 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-08 18:24:08.581  6147  6197 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30929e5e added. We now have 3 listener(s)
09-08 18:24:08.581  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
,09-08 18:24:08.581  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:24:08.581  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:24:08.581  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:24:08.581  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:08.581  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-08 18:24:08.581  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-08 18:24:08.581  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-08 18:24:08.581  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 18:24:08.591  3600  3600 I Hs20UtilService: Starting #24
,09-08 18:24:08.591  3600  3625 I Hs20UtilService: Message received 5007
,09-08 18:24:08.591  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:24:08.591  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3562423f added. We now have 10 listener(s)
09-08 18:24:08.591  6147  6197 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:24:08.591  6147  6197 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:24:08.591  6147  6197 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:24:08.591  6147  6197 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:24:08.591  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:24:08.591  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:08.591  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:24:08.591  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:24:08.591  6147  6197 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a6dae3 removed from the list
09-08 18:24:08.591  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:08.591  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@264e8ce0 removed from the list
09-08 18:24:08.591  6147  6197 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:24:08.591  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:08.591  1300  1300 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-08 18:24:08.591  1300  1300 I NearbySettings: MountReceiver.onReceive - Keep current state
09-08 18:24:08.591  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:08.591  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:24:08.591  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 18:24:08.591  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:24:08.591  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 18:24:08.591  6147  6197 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@264e8ce0 not in the list
09-08 18:24:08.591  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:08.591  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:24:08.591  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:24:08.591  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:24:08.591  6147  6197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:08.591  6147  6197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3562423f removed from the list
09-08 18:24:08.591  6147  6197 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:24:08.591  6147  6197 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:08.591  6147  6197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:08.591  6147  6197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:24:08.591  6147  6197 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30929e5e removed from the list
09-08 18:24:08.601  6147  6197 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-08 18:24:08.601  6147  6197 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-08 18:24:08.601  6147  6197 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-08 18:24:08.601  6147  6197 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 18:24:08.601  6147  6197 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-08 18:24:08.601  6147  6197 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 18:24:08.601  1015  1028 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0,
,09-08 18:24:08.601  1015  3002 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState,
09-08 18:24:08.601  1015  3002 D SecContentProvider2: mCursor = null
,09-08 18:24:08.601  1015  3224 D SecContentProvider2: uri = 15 selection = getToastGravity
09-08 18:24:08.601  1015  3224 D SecContentProvider2: mCursor = null,
,09-08 18:24:08.601  1015  1342 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
09-08 18:24:08.601  1015  1342 D SecContentProvider2: mCursor = null
,09-08 18:24:08.611  1015  1564 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
09-08 18:24:08.611  1015  1564 D SecContentProvider2: mCursor = null
,09-08 18:24:08.611  6147  7020 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1172, name: My test thread name)
,09-08 18:24:08.611  6147  7020 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1172, thread name: My test thread name)
09-08 18:24:08.611  6147  7020 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1172, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-08 18:24:08.611  1015  1494 D SecContentProvider2: uri = 15 selection = getToastEnabledState
09-08 18:24:08.611  1015  1494 D SecContentProvider2: mCursor = null
,09-08 18:24:08.611  6147  7021 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1174, name: My test thread name)
09-08 18:24:08.611  6147  7021 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1174, thread name: My test thread name)
09-08 18:24:08.611  6147  7021 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1174, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-08 18:24:08.611  1015  1138 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
09-08 18:24:08.611  1015  1138 D SecContentProvider2: mCursor = null
,09-08 18:24:08.611  6147  6197 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,09-08 18:24:08.611  6147  6197 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-08 18:24:08.611  6147  6197 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-08 18:24:08.611  6147  6197 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-08 18:24:08.611  1015  6980 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
09-08 18:24:08.611  6147  6197 D com.test.thalitest.ThaliTestRunner: Total duration: 24380 ms
09-08 18:24:08.621  6147  6197 I jxcore-log: *Native tests were executed*
09-08 18:24:08.621  6147  6197 I jxcore-log: 
09-08 18:24:08.621  6147  6197 I jxcore-log: Total number of executed tests:  80
09-08 18:24:08.621  6147  6197 I jxcore-log: 
,09-08 18:24:08.621  6147  6197 I jxcore-log: Number of passed tests:  80
09-08 18:24:08.621  6147  6197 I jxcore-log: 
09-08 18:24:08.621  6147  6197 I jxcore-log: Number of failed tests:  0
09-08 18:24:08.621  6147  6197 I jxcore-log: 
09-08 18:24:08.621  6147  6197 I jxcore-log: Number of ignored tests:  0
09-08 18:24:08.621  6147  6197 I jxcore-log: 
,09-08 18:24:08.621  6147  6197 I jxcore-log: Total duration:  24380
09-08 18:24:08.621  6147  6197 I jxcore-log: 
09-08 18:24:08.621  6147  6197 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-08 18:24:08.621  6147  6197 I jxcore-log: 
,09-08 18:24:08.621  6147  6197 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:08.621  6147  6197 I jxcore-log: 
09-08 18:24:08.621  6147  6197 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:08.621  6147  6197 I jxcore-log: 
09-08 18:24:08.621  6147  6197 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:08.621  6147  6197 I jxcore-log: 
09-08 18:24:08.631  6147  6197 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:08.631  6147  6197 I jxcore-log: 
09-08 18:24:08.631  6147  6197 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:08.631  6147  6197 I jxcore-log: 
09-08 18:24:08.631  6147  6197 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:08.631  6147  6197 I jxcore-log: 
09-08 18:24:08.631  6147  6147 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-08 18:24:08.631  6147  6197 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
09-08 18:24:08.631  6147  6197 I jxcore-log: 
,09-08 18:24:08.631  6147  6197 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
,09-08 18:24:08.631  6147  6197 I jxcore-log: 
09-08 18:24:08.631  6147  6197 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 18:24:08.631  6147  6197 I jxcore-log: 
,09-08 18:24:08.631  6147  6197 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 18:24:08.631  6147  6197 I jxcore-log: 
09-08 18:24:08.631  6147  6197 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 18:24:08.631  6147  6197 I jxcore-log: 
09-08 18:24:08.641  6147  6197 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 18:24:08.641  6147  6197 I jxcore-log: 
09-08 18:24:08.641  6147  6197 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 18:24:08.641  6147  6197 I jxcore-log: 
09-08 18:24:08.641  6147  6197 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 18:24:08.641  6147  6197 I jxcore-log: 
09-08 18:24:08.641  6147  6197 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 18:24:08.641  6147  6197 I jxcore-log: 
09-08 18:24:08.641  6147  6197 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 18:24:08.641  6147  6197 I jxcore-log: 
09-08 18:24:08.641  6147  6197 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 18:24:08.641  6147  6197 I jxcore-log: 
,09-08 18:24:08.641  6147  6197 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 18:24:08.641  6147  6197 I jxcore-log: 
09-08 18:24:08.641  6147  6197 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 18:24:08.641  6147  6197 I jxcore-log: 
,09-08 18:24:08.641  6147  6197 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 18:24:08.641  6147  6197 I jxcore-log: 
,09-08 18:24:08.641  6147  6197 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 18:24:08.641  6147  6197 I jxcore-log: 
09-08 18:24:08.641  6147  6197 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 18:24:08.641  6147  6197 I jxcore-log: 
09-08 18:24:08.641  6147  6197 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 18:24:08.641  6147  6197 I jxcore-log: 
09-08 18:24:08.641  6147  6197 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 18:24:08.641  6147  6197 I jxcore-log: 
09-08 18:24:08.641  6147  6197 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 18:24:08.641  6147  6197 I jxcore-log: 
,09-08 18:24:08.641   256   256 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=4, Uoast
09-08 18:24:08.641  6147  6197 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 18:24:08.641  6147  6197 I jxcore-log: 
,09-08 18:24:08.641  6147  6197 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:08.641  6147  6197 I jxcore-log: 
,09-08 18:24:08.661  1015  3223 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015,
,09-08 18:24:08.661  1174  1174 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! ,
,09-08 18:24:08.691  1015  6980 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 08 Sep 2016 16:24:08 GMT], X-Android-Received-Millis=[1473351848698], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473351848663]},
09-08 18:24:08.691  1015  6980 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.,
09-08 18:24:08.691  1015  1128 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
,09-08 18:24:08.691  1015  6980 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-08 18:24:08.691  1015  1128 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
09-08 18:24:08.691  1174  1695 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-08 18:24:08.691  1015  1128 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
09-08 18:24:08.691  3786  6209 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-08 18:24:08.691  1015  1128 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
09-08 18:24:08.691  6147  6147 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 18:24:08.691  1015  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-08 18:24:08.701  6147  6197 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 18:24:08.701  6147  6197 I jxcore-log: 
,09-08 18:24:08.711  1174  1174 D StatusBar.NetworkController: EthernetConnected: false
,09-08 18:24:08.711  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-08 18:24:08.711  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-08 18:24:08.711  1174  1174 D StatusBar.NetworkController: updateDataNetType()
,09-08 18:24:08.711  1174  1174 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-08 18:24:08.711  1174  1174 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-08 18:24:08.721  1174  1174 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false,
09-08 18:24:08.721  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte,
09-08 18:24:08.721  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal,
09-08 18:24:08.721  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-08 18:24:08.721  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,09-08 18:24:08.721  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:08.721  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 18:24:08.721  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:24:08.721  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 18:24:08.871  6147  6147 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
09-08 18:24:08.871  6147  6197 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 18:24:08.871  6147  6197 I jxcore-log: 
,09-08 18:24:08.911  7023  7023 D AndroidRuntime: 
09-08 18:24:08.911  7023  7023 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-08 18:24:08.911  7023  7023 D AndroidRuntime: CheckJNI is OFF,
09-08 18:24:08.911  7023  7023 D AndroidRuntime: readGMSProperty: start
,09-08 18:24:08.911  7023  7023 D AndroidRuntime: readGMSProperty: already setted!!
09-08 18:24:08.911  7023  7023 D AndroidRuntime: propertySet: couldn't set property (it is from app)
,09-08 18:24:08.911  7023  7023 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-08 18:24:08.911  7023  7023 D AndroidRuntime: readGMSProperty: end
09-08 18:24:08.911  7023  7023 D AndroidRuntime: addProductProperty: start,
,09-08 18:24:09.041  1015  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,09-08 18:24:09.041  7023  7023 E AffinityControl: AffinityControl: registerfunction enter,
,09-08 18:24:09.051  6147  6147 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 18:24:09.051  1015  1040 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-08 18:24:09.051  6147  6197 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
09-08 18:24:09.051  6147  6197 I jxcore-log: 
,09-08 18:24:09.061  3201  3201 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,09-08 18:24:09.071  6469  6469 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-08 18:24:09.071  7023  7023 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-08 18:24:09.071  6147  6147 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:24:09.071  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:09.071  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:24:09.071  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:24:09.071  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:24:09.071  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:24:09.071  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:24:09.071  6147  6147 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 18:24:09.081  6147  6147 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
09-08 18:24:09.081  6147  6197 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:09.081  6147  6197 I jxcore-log: 
,09-08 18:24:09.091  6452  6452 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-08 18:24:09.091  6452  6452 I PCWCLIENTTRACE_PushUtil: sales region : global
09-08 18:24:09.091  6452  6452 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-08 18:24:09.091  6452  6452 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-08 18:24:09.091  1015  3003 D PackageManager: START PACKAGE DELETE: observer{217917422}
09-08 18:24:09.091  1015  3003 D PackageManager: pkg{<packageName>}
09-08 18:24:09.091  1015  3003 D PackageManager: user{0}
09-08 18:24:09.091  1015  3003 D PackageManager: caller{2000}
09-08 18:24:09.091  1015  3003 D PackageManager: flags{2}
09-08 18:24:09.091  1015  1251 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
09-08 18:24:09.091  1015  1251 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,09-08 18:24:09.091  1015  3003 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
,09-08 18:24:09.091  1015  3003 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-08 18:24:09.091  1015  3003 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-08 18:24:09.091  1015  3003 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-08 18:24:09.091  1015  3003 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-08 18:24:09.101  1015  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0,
09-08 18:24:09.101  1015  1056 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-08 18:24:09.101  1015  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-08 18:24:09.101  1015  1056 D ApplicationPolicy: getApplicationUninstallationEnabled
09-08 18:24:09.101  1015  1056 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
09-08 18:24:09.101  6469  6469 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,09-08 18:24:09.101  1015  1056 D PackageManager: !@killApplicatoin: 10155, uninstall pkg
,09-08 18:24:09.111  1718  1718 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-08 18:24:09.211  1015  1041 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
,09-08 18:24:09.211  1015  1041 I ActivityManager: Killing 6147:com.test.thalitest/u0a155 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-08 18:24:09.211  1015  1564 D RCPManagerService: exchangeData() failure , invalid userId
,09-08 18:24:09.221  1015  1251 D RCPManagerService: exchangeData() failure , invalid userId
,09-08 18:24:09.221  1015  1041 I ActivityManager:   Force finishing activity ActivityRecord{ab87da0 u0 com.test.thalitest/.MainActivity t128}
,09-08 18:24:09.221  1015  1041 W ActivityManager: mDVFSHelper.acquire()
,09-08 18:24:09.231  1015  1494 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-08 18:24:09.231  1015  1494 D SecContentProvider2: mCursor = null
,09-08 18:24:09.241  6480  6480 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,09-08 18:24:09.241  1015  1056 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=0: pkg removed
09-08 18:24:09.241  1718  1718 D accuweather: [KK AccuPhone]>>> U:4106 [0:0] getPWC : surface = 0, remote = 1
,09-08 18:24:09.241  1718  1718 D accuweather: [KK AccuPhone]>>> U:4284 [0:0] Store PWC = 1,
09-08 18:24:09.241  1718  1718 D accuweather: [KK AccuPhone]>>> U:4158 [0:0] addPWC = 1
,09-08 18:24:09.241  1718  1718 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-08 18:24:09.241  1015  1056 I ActivityManager:   Force finishing activity ActivityRecord{ab87da0 u0 com.test.thalitest/.MainActivity t128 f}
09-08 18:24:09.241  1015  1056 W ActivityManager: Duplicate finish request for ActivityRecord{ab87da0 u0 com.test.thalitest/.MainActivity t128 f}
,09-08 18:24:09.261  1015  1056 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,09-08 18:24:09.271  3201  3201 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,09-08 18:24:09.281  5622  5622 I art     : Explicit concurrent mark sweep GC freed 2068(118KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 695us total 25.454ms
,09-08 18:24:09.291  6417  6417 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-08 18:24:09.291  6417  6417 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-08 18:24:09.291  6417  6417 D SecurityLogAgent: StateMachine : Current State = 1
,09-08 18:24:09.291  1321  1336 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,09-08 18:24:09.291  6417  6417 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-08 18:24:09.301  3201  3201 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 6
,09-08 18:24:09.311  1015  1097 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-08 18:24:09.311  3201  3201 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,09-08 18:24:09.311  1907  2110 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-08 18:24:09.321  1883  1883 E SamsungIME: mOCRHelper is null
,09-08 18:24:09.321  5418  5418 I art     : Explicit concurrent mark sweep GC freed 399(27KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 8MB/11MB, paused 761us total 59.016ms
,09-08 18:24:09.321  3201  3201 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,09-08 18:24:09.321  3201  3201 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 6
,09-08 18:24:09.331  3201  3201 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,09-08 18:24:09.341  3786  3786 I art     : Explicit concurrent mark sweep GC freed 22921(1384KB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 15MB/26MB, paused 1.337ms total 80.968ms
,09-08 18:24:09.351  3201  3201 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,09-08 18:24:09.351  3201  3201 I DBG_DM  : [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(649/IIIIllIlIIlIIIIlllIl)] nWidgetStatus : 2
,09-08 18:24:09.351  3201  3201 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.wssyncmldm.ui.llllIIIllIlIIIIllllI.IIIIllIlIIlIIIIlllIl:652 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:172 com.wssyncmldm.ui.XUIInstallConfirmActivity.onResume:446 
,09-08 18:24:09.351  1718  1718 D accuweather: [KK AccuPhone]>>> U:4250 [0:0] Store PWC succeed
,09-08 18:24:09.351  1718  1718 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-08 18:24:09.361  1718  1718 D accuweather: [KK AccuPhone]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,09-08 18:24:09.361  1439  1439 D PersonaManager: isKioskContainerExistOnDevice
,09-08 18:24:09.371  6480  6480 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,09-08 18:24:09.371  6480  6480 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,09-08 18:24:09.371  6480  6480 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,09-08 18:24:09.381  1015  1123 V NetworkStats: removeUidsLocked() for UIDs [10155]
09-08 18:24:09.381  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 18:24:09.381  1015  1123 V NetworkStats: performPollLocked(flags=0x3)
,09-08 18:24:09.381  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-08 18:24:09.381  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-08 18:24:09.391  1015  1123 V NetworkStats: performPollLocked() took 8ms
09-08 18:24:09.391  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:24:09.391  1015  1041 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-08 18:24:09.401  1015  3003 D SettingsProvider: name = SOFTWARE_UPDATE_NOTIFICATION_STATUS
,09-08 18:24:09.411  1015  1041 D InputDispatcher: Focus left window: 6147
,09-08 18:24:09.411  1015  1041 D InputDispatcher: Focused application released
,09-08 18:24:09.411  1015  1046 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
09-08 18:24:09.411  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-08 18:24:09.411  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-08 18:24:09.421  1174  1174 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-08 18:24:09.421  3201  3201 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,09-08 18:24:09.421   256  1037 I SurfaceFlinger: id=14 Removed NainActivit (6/9)
09-08 18:24:09.421  1015  1251 I WindowState: WIN DEATH: Window{27b34c00 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-08 18:24:09.421   256   444 I SurfaceFlinger: id=14 Removed NainActivit (-2/9)
,09-08 18:24:09.441  3201  3201 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
09-08 18:24:09.441  1015  1251 E WindowState: getStack: Window{27b34c00 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowState.getWindowList:1991 com.android.server.wm.WindowManagerService.removeWindowInnerLocked:3693 com.android.server.wm.WindowManagerService.removeWindowLocked:3559 
,09-08 18:24:09.441  1015  1251 E WindowState: getStack: Window{27b34c00 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowManagerService.removeWindowInnerLocked:3698 com.android.server.wm.WindowManagerService.removeWindowLocked:3559 com.android.server.wm.WindowState$DeathRecipient.binderDied:1650 
,09-08 18:24:09.451  1439  1439 D RegisteredServicesCache: empty dynamic service
,09-08 18:24:09.471  1015  3223 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,09-08 18:24:09.471  1015  3223 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,09-08 18:24:09.471  3637  3637 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Sep 08 18:24:09 GMT+02:00 2016
,09-08 18:24:09.471  3201  3201 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 6
,09-08 18:24:09.481  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:24:09.481  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 18:24:09.481  3201  3201 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,09-08 18:24:09.491  6659  6659 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-08 18:24:09.491  1015  3140 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-08 18:24:09.491  1015  3140 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-08 18:24:09.501  1015  3140 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:24:09.501  6659  6659 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-08 18:24:09.501  6659  6659 I DIAGMON_AGENT: ./extraInfo: "NG700"
09-08 18:24:09.501  3201  3201 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
09-08 18:24:09.501  6659  6659 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,09-08 18:24:09.501  3201  3201 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,09-08 18:24:09.501  3201  3201 I DBG_DM  : [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,09-08 18:24:09.501  1015  3140 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:09.501  1015  3140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-08 18:24:09.501  3201  3201 I DBG_DM  : [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,09-08 18:24:09.511  1015  3002 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-08 18:24:09.521  1015  3002 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-08 18:24:09.521  1015  3002 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:24:09.521  1015  3002 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-08 18:24:09.521  1015  3002 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 18:24:09.521  1015  1494 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-08 18:24:09.521  1015  1494 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-08 18:24:09.521  1015  1494 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-08 18:24:09.531  3201  3201 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,09-08 18:24:09.531   256   256 I SurfaceFlinger: id=16 createSurf (720x1280),1 flag=404, YUIInstallC
,09-08 18:24:09.541  1015  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-08 18:24:09.541  3637  3637 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,09-08 18:24:09.541  1015  1128 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,09-08 18:24:09.541  1015  1027 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-08 18:24:09.541  1015  1027 D SecContentProvider2: mCursor = null
,09-08 18:24:09.551   279   993 D EnterpriseController: uids 10012
09-08 18:24:09.551   279   993 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-08 18:24:09.551   279   993 D Netd    : getNetworkForDns: using netid 504 for uid 10012
,09-08 18:24:09.551  1015  1251 D InputDispatcher: Focus entered window: 3201
,09-08 18:24:09.551  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-08 18:24:09.551  3201  3201 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-08 18:24:09.551  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-08 18:24:09.561  3637  3637 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,09-08 18:24:09.561  3637  3637 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-08 18:24:09.561  3637  3637 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-08 18:24:09.561  3201  3201 V ActivityThread: updateVisibility : ActivityRecord{145118e1 token=android.os.BinderProxy@1a66c30c {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,09-08 18:24:09.571  3637  7037 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-08 18:24:09.571  1015  1040 D EnterpriseDeviceManagerService: Package has changed for user 0
,09-08 18:24:09.571  1015  1040 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,09-08 18:24:09.571  1015  1040 W TextServicesManagerService: no available spell checker services found
,09-08 18:24:09.581  1015  1383 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-08 18:24:09.591  1015  7040 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-08 18:24:09.591  1015  1383 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6147 uid 10155
,09-08 18:24:09.591  3637  7037 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-08 18:24:09.601  3786  3786 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-08 18:24:09.601  3201  3201 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1a66c30c time:150977
,09-08 18:24:09.611  3786  4533 I iu.UploadsManager: num queued entries: 0
,09-08 18:24:09.611  3786  4533 I iu.UploadsManager: num updated entries: 0
09-08 18:24:09.611  3786  4533 I iu.SyncManager: NEXT; no task
,09-08 18:24:09.611  1883  1883 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,09-08 18:24:09.611  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-08 18:24:09.621  1015  1046 W ActivityManager: mDVFSHelper.release()
,09-08 18:24:09.621  3637  7037 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,09-08 18:24:09.621  1015  3224 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
09-08 18:24:09.621  1439  1439 D RegisteredComponentCache: Collect Tech packages for Knox
,09-08 18:24:09.621  1015  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1a7d19a9 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t127} time:150998
09-08 18:24:09.621  1015  1056 I art     : Explicit concurrent mark sweep GC freed 78379(5MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 28MB/42MB, paused 7.495ms total 260.879ms
,09-08 18:24:09.621  1015  3224 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
09-08 18:24:09.621  3637  7037 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().START
,09-08 18:24:09.631  1015  3224 W ActivityManager: userId = 0, bbcId = -10000
,09-08 18:24:09.631  1015  1015 D RCPManagerService: PackageReceiver onReceive()
09-08 18:24:09.631  1015  1015 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
09-08 18:24:09.631  1015  3224 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:09.631  1015  3224 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,09-08 18:24:09.631  3637  7037 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().START 
,09-08 18:24:09.631  1015  1015 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,09-08 18:24:09.631  1015  1015 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,09-08 18:24:09.641  3637  7037 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().END 
,09-08 18:24:09.641  1015  1015 D OTPFW   : OtpDbHelper::getInstance New instance created
,09-08 18:24:09.641  3637  7037 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,09-08 18:24:09.641  1015  1015 D OTPFW   : DBIntegrity::getInstance - New instance created
,09-08 18:24:09.641  1439  1439 D PersonaManager: isKioskContainerExistOnDevice
,09-08 18:24:09.651  1015  1056 D PackageManager: delete codoeFile: 
,09-08 18:24:09.651  1015  1015 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0,
,09-08 18:24:09.661  3637  3637 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,09-08 18:24:09.671  1015  1015 I OTPFW   : ProvisionData::getAllEntries Enter
,09-08 18:24:09.671  1015  1056 D AASAuninstall: userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
,09-08 18:24:09.671  1015  1015 E OTPFW   : ProvisionData::getAllEntries Table is empty
09-08 18:24:09.671  1015  1056 I AASA_removePackage: UID=10155 Target=com.test.thalitest
,09-08 18:24:09.671  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-08 18:24:09.671  1015  1056 D PackageManager: result of delete: 1{217917422}
,09-08 18:24:09.681  1015  1015 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-08 18:24:09.681  1015  1015 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-08 18:24:09.681  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-08 18:24:09.681  1015  1015 V EnterpriseBillingPolicy: uID is 10155
09-08 18:24:09.681  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
09-08 18:24:09.681  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-08 18:24:09.681  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-08 18:24:09.681  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-08 18:24:09.681  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-08 18:24:09.681  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-08 18:24:09.681  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-08 18:24:09.681  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-08 18:24:09.691  1907  7036 I qtaguid : Tagging socket 58 with tag 1000040700000000{268436487,0} for uid -1, pid: 1907, getuid(): 10012
,09-08 18:24:09.701  7023  7023 D AndroidRuntime: Shutting down VM
,09-08 18:24:09.701  1015  1015 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-08 18:24:09.701  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-08 18:24:09.701  1015  1015 V EnterpriseBillingPolicy: uID is 10155
09-08 18:24:09.701  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
09-08 18:24:09.701  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-08 18:24:09.701  1015  2723 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,09-08 18:24:09.711  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-08 18:24:09.711  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-08 18:24:09.711  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-08 18:24:09.711  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-08 18:24:09.711  1015  3002 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,09-08 18:24:09.711  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-08 18:24:09.711  1015  1015 V AlarmManagerEXT: com.test.thalitest(10155) is removed.
,09-08 18:24:09.711  1015  3002 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:24:09.711  1015  3002 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:24:09.711  1015  3002 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 18:24:09.711  1015  3002 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 18:24:09.721  1015  1056 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-08 18:24:09.721  1015  1056 D PackageManager: userId{-1}
09-08 18:24:09.721  1015  1056 D PackageManager: andCode{true}
,09-08 18:24:09.731  7048  7048 E Zygote  : MountEmulatedStorage()
09-08 18:24:09.731  7048  7048 E Zygote  : v2
09-08 18:24:09.731  7048  7048 I libpersona: KNOX_SDCARD checking this for 10010
09-08 18:24:09.731  7048  7048 I libpersona: KNOX_SDCARD not a persona
,09-08 18:24:09.731  7048  7048 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-08 18:24:09.731  7048  7048 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-08 18:24:09.731  7048  7048 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
09-08 18:24:09.741  1015  3002 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7048 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
09-08 18:24:09.741  1015  1015 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,09-08 18:24:09.741  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,09-08 18:24:09.741  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
09-08 18:24:09.751  1174  1174 D PanelView: There is/are notification(s) 
,09-08 18:24:09.751  6719  6719 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-08 18:24:09.751   305   305 I art     : Explicit concurrent mark sweep GC freed 8724(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 665us total 22.764ms
,09-08 18:24:09.771  1015  1056 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-08 18:24:09.771   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 622us total 17.219ms
09-08 18:24:09.771  6719  6719 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,09-08 18:24:09.771  7048  7048 D TimaKeyStoreProvider: TimaSignature is unavailable
09-08 18:24:09.771  6719  6719 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
09-08 18:24:09.771  7048  7048 D ActivityThread: Added TimaKeyStore provider
,09-08 18:24:09.781  3177  7066 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,09-08 18:24:09.781  3177  7066 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,09-08 18:24:09.791  3177  7066 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-08 18:24:09.791   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 606us total 16.827ms
09-08 18:24:09.791  1015  1040 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,09-08 18:24:09.801  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-08 18:24:09.801  6577  6577 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,09-08 18:24:09.811  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-08 18:24:09.811  5971  5971 I SA      : [OR] onReceive log=[SA = 2.1.0240 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOJ6 PSS = 4.978878039476607  ]
,09-08 18:24:09.811  5971  5971 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
09-08 18:24:09.811  5971  5971 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-08 18:24:09.831  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-08 18:24:09.831  1015  1160 D TaskPersister: removeObsoleteFile: deleting file=128_task.xml
,09-08 18:24:09.831  1015  1160 D TaskPersister: removeObsoleteFile: deleting file=127_task.xml
,09-08 18:24:09.831  5971  5971 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-08 18:24:09.831  5971  5971 I SA      : [OR] == isSIMCardReady false ==
,09-08 18:24:09.831  5971  5971 I SA      : [SCU] == networkStateCheck == true
,09-08 18:24:09.841  5971  5971 I SA      : [DM] getCountryCodeFromCSC : PL
,09-08 18:24:09.841  5971  5971 I SA      : isChinaCountryCode : false
09-08 18:24:09.841  5971  5971 I SA      : [SCU] is ChinestModel Data Restricted   : false
09-08 18:24:09.841  5971  5971 I SA      : [OR] == networkStateCheck true ==
,09-08 18:24:09.841  1015  1040 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-08 18:24:09.841  1015  1040 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-08 18:24:09.841  1015  1040 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-08 18:24:09.841  5971  5971 I SA      : [OR] GetMyCountryZoneTask
,09-08 18:24:09.841  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-08 18:24:09.851  5971  5971 I SA      : [OR] onReceive END
,09-08 18:24:09.851  3177  7066 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,09-08 18:24:09.861  1226  1226 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-08 18:24:09.861  1015  1383 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,09-08 18:24:09.861  1015  1383 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
09-08 18:24:09.861  3177  7066 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,09-08 18:24:09.861  3177  7066 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,09-08 18:24:09.861  1015  1383 W ActivityManager: userId = 0, bbcId = -10000
09-08 18:24:09.861  1015  1383 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 18:24:09.861  1015  1383 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,09-08 18:24:09.861  3177  7066 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,09-08 18:24:09.861  3177  7066 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,09-08 18:24:09.861  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-08 18:24:09.871  3177  7066 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,09-08 18:24:09.871  1174  1174 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,09-08 18:24:09.871  3177  7066 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,09-08 18:24:09.871  1174  1174 D PersonaManager: isKioskContainerExistOnDevice
09-08 18:24:09.871  3177  7066 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
09-08 18:24:09.871  1174  1174 D PersonaManager: isKioskContainerExistOnDevice
,09-08 18:24:09.871  1174  1174 D PanelView: There is/are notification(s) 
09-08 18:24:09.871  1174  1174 D PanelView: kidsfalse mQsExpansionEnabled:true
,09-08 18:24:09.871  1174  1174 D PersonaManager: isKioskContainerExistOnDevice
,09-08 18:24:09.871  1174  1174 D PanelView: There is/are notification(s) 
09-08 18:24:09.871  1174  1174 D PanelView: kidsfalse mQsExpansionEnabled:true
,09-08 18:24:09.871  5971  7068 I SA      : [SRS] prepareGetMyCountryZone
,09-08 18:24:09.881  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-08 18:24:09.881  3177  7066 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,09-08 18:24:09.881  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-08 18:24:09.881  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-08 18:24:09.891  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-08 18:24:09.891  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-08 18:24:09.891  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-08 18:24:09.891  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-08 18:24:09.891  1015  3003 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
09-08 18:24:09.891  1015  3003 D SecContentProvider2: mCursor = null
09-08 18:24:09.891  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-08 18:24:09.901  5971  7068 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-08 18:24:09.901  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-08 18:24:09.901  5971  7068 I SA      : [SSP] query invoked
,09-08 18:24:09.901  5971  7068 I SA      : [TPMU] GetMccFromDB : null
09-08 18:24:09.901  5971  7068 I SA      : [SCU] getMccFromPreferece mcc = 260
09-08 18:24:09.901  1015  1040 D UsbSettingsManager: clearDefaults: com.test.thalitest
09-08 18:24:09.901  1015  1040 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,09-08 18:24:09.911  5971  7068 I SA      : [LBE] isSupportCheckDomainRegion : false
09-08 18:24:09.911  7023  7023 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
09-08 18:24:09.911  5971  7068 I SA      : [TPM] isNoProxy(default) : true
,09-08 18:24:09.911  3177  7066 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,09-08 18:24:09.921  5971  7068 E File    : fail readDirectory() errno=2
,09-08 18:24:09.931  7048  7048 D WaitQueueForNetworkActivate: notifyNetworkActivated
,09-08 18:24:09.941  1174  1174 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,09-08 18:24:09.971  6885  6901 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new

```
