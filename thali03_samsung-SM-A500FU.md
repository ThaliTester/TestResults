#### Test 80598852b8a90be_thali03_samsung-SM-A500FU Logs


```
--------- beginning of system
08-16 18:14:57.787  1014  1330 E Watchdog: !@Sync 3
,--------- beginning of main
08-16 18:14:58.317  6157  6157 D AndroidRuntime: 
08-16 18:14:58.317  6157  6157 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-16 18:14:58.317  6157  6157 D AndroidRuntime: CheckJNI is OFF
08-16 18:14:58.317  6157  6157 D AndroidRuntime: readGMSProperty: start
08-16 18:14:58.317  6157  6157 D AndroidRuntime: readGMSProperty: already setted!!
08-16 18:14:58.317  6157  6157 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-16 18:14:58.317  6157  6157 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-16 18:14:58.317  6157  6157 D AndroidRuntime: readGMSProperty: end
08-16 18:14:58.317  6157  6157 D AndroidRuntime: addProductProperty: start
08-16 18:14:58.417   318   318 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-16 18:14:58.417   318   318 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
08-16 18:14:58.457  6157  6157 E AffinityControl: AffinityControl: registerfunction enter
08-16 18:14:58.477  6157  6157 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-16 18:14:58.487  1014  1557 E PersonaManagerService: inState():  stateMachine is null !!
08-16 18:14:58.487  1014  1557 I PersonaManagerService: PersonaId don't exist
08-16 18:14:58.487  1014  1557 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-16 18:14:58.497  1014  1557 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-16 18:14:58.507  1014  1557 W ActivityManager: mDVFSHelper.acquire()
08-16 18:14:58.517  1014  1045 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-16 18:14:58.517  1014  1045 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-16 18:14:58.517  1014  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:14:58.517  1014  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:14:58.517  1014  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:14:58.517  1014  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:14:58.537  6168  6168 E Zygote  : MountEmulatedStorage()
08-16 18:14:58.537  6168  6168 E Zygote  : v2
08-16 18:14:58.537  6168  6168 I libpersona: KNOX_SDCARD checking this for 10155
08-16 18:14:58.537  1014  1557 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
08-16 18:14:58.537  6168  6168 I libpersona: KNOX_SDCARD not a persona
08-16 18:14:58.537  1014  1557 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-16 18:14:58.537  1014  1557 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6168 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-16 18:14:58.537  1014  1557 D InputDispatcher: Focused application set to: xxxx
08-16 18:14:58.537  1014  1557 D InputDispatcher: Focus left window: 3119
08-16 18:14:58.537  1014  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-16 18:14:58.537  1014  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-16 18:14:58.537  6157  6157 D AndroidRuntime: Shutting down VM
08-16 18:14:58.537   256   256 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
08-16 18:14:58.547  6168  6168 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-16 18:14:58.547  6168  6168 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-16 18:14:58.547  6168  6168 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-16 18:14:58.557  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-16 18:14:58.557  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
08-16 18:14:58.577  6168  6168 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 18:14:58.577  6168  6168 D ActivityThread: Added TimaKeyStore provider
08-16 18:14:58.577  1014  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-16 18:14:58.587  1014  1014 V ActivityManager: Display changed displayId=0
08-16 18:14:58.607  1014  1026 D PersonaManager: isKioskContainerExistOnDevice
08-16 18:14:58.627   256   451 I SurfaceFlinger: id=10 Removed YUIInstallC (5/9)
08-16 18:14:58.627   256  1036 I SurfaceFlinger: id=10 Removed YUIInstallC (-2/9)
08-16 18:14:58.637  3119  3119 V ActivityThread: updateVisibility : ActivityRecord{2255361c token=android.os.BinderProxy@70f23a3 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
08-16 18:14:58.727  6168  6168 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
08-16 18:14:58.737  6168  6168 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 9066-9067)
08-16 18:14:58.737  6168  6168 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 18:14:58.747  6157  6157 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-16 18:14:58.777  6168  6168 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2877fa98}
,08-16 18:14:58.777  6168  6168 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 18:14:58.777  6168  6168 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,08-16 18:14:58.817  6168  6168 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-16 18:14:58.817  6168  6168 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 18:14:58.817  6168  6168 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-16 18:14:58.837  6168  6168 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,08-16 18:14:58.837  6168  6168 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,08-16 18:14:58.837  6168  6168 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,08-16 18:14:58.847  6168  6168 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-16 18:14:58.847  6168  6168 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-16 18:14:58.847  6168  6168 I Adreno-EGL: Build Date: 04/06/15 Mon
08-16 18:14:58.847  6168  6168 I Adreno-EGL: Local Branch: 
08-16 18:14:58.847  6168  6168 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-16 18:14:58.847  6168  6168 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-16 18:14:58.847  6168  6168 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-16 18:14:58.967  6168  6194 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,08-16 18:14:59.007  6168  6168 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 18:14:59.027  6168  6168 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-16 18:14:59.037  6168  6168 D PhoneWindow: *FMB* installDecor mIsFloating : false
,08-16 18:14:59.037  6168  6168 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-16 18:14:59.037  6168  6168 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-16 18:14:59.047  6168  6168 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 18:14:59.047  6168  6168 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 18:14:59.087  6168  6207 D OpenGLRenderer: Render dirty regions requested: true
,08-16 18:14:59.097  1014  1026 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-16 18:14:59.097  1014  1026 D KnoxTimeoutHandler: postActiveUserChange for user 0
,08-16 18:14:59.097  1014  1026 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-16 18:14:59.097  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-16 18:14:59.097  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
,08-16 18:14:59.107  6168  6168 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,08-16 18:14:59.107  6168  6168 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-16 18:14:59.117   256   256 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
,08-16 18:14:59.137  1014  1027 D InputDispatcher: Focus entered window: 6168
,08-16 18:14:59.137  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-16 18:14:59.137  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-16 18:14:59.137  6168  6168 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-16 18:14:59.137  6168  6207 I OpenGLRenderer: Initialized EGL, version 1.4
,08-16 18:14:59.147  6168  6207 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,08-16 18:14:59.147  6168  6207 D OpenGLRenderer: Enabling debug mode 0
,08-16 18:14:59.177  6168  6168 V ActivityThread: updateVisibility : ActivityRecord{15295be3 token=android.os.BinderProxy@267f9b9d {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-16 18:14:59.207  1014  3070 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-16 18:14:59.207  1171  1171 D PanelView: There is/are notification(s) ,
08-16 18:14:59.207  1014  6210 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-16 18:14:59.217  1014  1045 I ActivityManager: Displayed Component not be shown by security: +609ms (total +702ms)
,08-16 18:14:59.227  1014  1045 W ActivityManager: mDVFSHelper.release()
08-16 18:14:59.227  1014  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2f69af33 u0 com.test.thalitest/.MainActivity t128} time:109550
,08-16 18:14:59.227  1773  1773 I SamsungIME: getCurrentCandidateView
08-16 18:14:59.227  6168  6168 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-16 18:14:59.227  6168  6168 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@267f9b9d time:109558
08-16 18:14:59.237   256   451 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
,08-16 18:14:59.237   256   445 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
,08-16 18:14:59.287  6168  6168 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6168
,08-16 18:14:59.297  1773  1773 D SamsungIME: Dismiss ExpandCandiate,
,08-16 18:14:59.397  6168  6168 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-16 18:14:59.427  1773  1773 I SamsungIME: getDebugLevel  : 0x4f4c
,08-16 18:14:59.447   286   286 E SMD     : DCD OFF
,08-16 18:14:59.467  1773  1773 I SamsungIME: getDebugLevel  : 0x4f4c
,08-16 18:14:59.477  1773  1773 I SamsungIME: KeybaordView init() : load resources
,08-16 18:14:59.507  1773  1773 I SamsungIME: getCurrentKeyboard
08-16 18:14:59.507  1773  1773 I SamsungIME: getTextKeyboard
,08-16 18:14:59.517  6168  6211 D jxcore_app_log: JniHelper::setJavaVM(0xb7ddd328), pthread_self() = -1204548456
,08-16 18:14:59.527  1773  1773 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-16 18:14:59.527  6168  6211 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-16 18:14:59.527  6168  6211 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-16 18:14:59.527  6168  6211 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-16 18:14:59.527  6168  6211 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-16 18:14:59.527  6168  6211 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-16 18:14:59.527  6168  6211 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@251903d3 added. We now have 1 listener(s)
,08-16 18:14:59.527  6168  6211 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,08-16 18:14:59.527  6168  6211 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-16 18:14:59.527  6168  6211 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 18:14:59.537  6168  6211 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 18:14:59.537  6168  6211 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-16 18:14:59.537  6168  6211 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-16 18:14:59.537  6168  6211 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-16 18:14:59.537  6168  6211 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
08-16 18:14:59.537  6168  6211 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-16 18:14:59.537  6168  6211 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-16 18:14:59.537  6168  6211 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-16 18:14:59.537  6168  6211 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-16 18:14:59.537  6168  6211 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-16 18:14:59.537  6168  6211 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-16 18:14:59.537  6168  6211 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-16 18:14:59.537  6168  6211 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-16 18:14:59.537  6168  6211 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-16 18:14:59.537  6168  6211 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-16 18:14:59.537  6168  6211 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e89d00e added. We now have 1 listener(s)
,08-16 18:14:59.537  6168  6211 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 18:14:59.547  6168  6211 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 18:14:59.547  6168  6211 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-16 18:14:59.547  6168  6211 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-16 18:14:59.547  6168  6211 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-16 18:14:59.547  6168  6211 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-16 18:14:59.547  6168  6211 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 18:14:59.547  6168  6211 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,08-16 18:14:59.557  6168  6211 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-16 18:14:59.557  6168  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:14:59.557  6168  6211 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:14:59.557  6168  6211 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:14:59.557  6168  6211 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:14:59.557  6168  6211 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:14:59.557  6168  6211 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:14:59.557  6168  6211 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:14:59.557  6168  6211 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 18:14:59.557  6168  6211 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-16 18:14:59.557  6168  6211 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 18:14:59.557  6168  6211 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-16 18:14:59.567  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:14:59.567  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:14:59.597  6168  6168 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-16 18:14:59.997  1014  1093 V AlarmManager: waitForAlarm result :8
,08-16 18:15:00.027  6168  6220 W jxcore-log: Initializing JXcore engine
08-16 18:15:00.027  6168  6220 W jxcore-log: JXcore engine is ready
,08-16 18:15:00.057  1773  6216 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-16 18:15:00.077  1916  1916 E audit   : type=1400 msg=audit(1471364100.077:205): avc:  denied  { ioctl } for  pid=6220 comm="Thread-1068" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-16 18:15:00.077  1916  1916 E audit   :  SEPF_SM-A500FU_5.0.2-1_0051
08-16 18:15:00.077  1916  1916 E audit   : type=1300 msg=audit(1471364100.077:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9d6008f8 items=0 ppid=308 ppcomm=main pid=6220 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-1068" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-16 18:15:00.077  1916  1916 E audit   : type=1320 msg=audit(1471364100.077:205): 
,08-16 18:15:00.087  6168  6220 W jxcore-log: Starting JXcore engine
,08-16 18:15:00.197  6168  6220 W jxcore-log: Platform android
08-16 18:15:00.197  6168  6220 W jxcore-log: 
08-16 18:15:00.197  6168  6220 W jxcore-log: Process ARCH arm
08-16 18:15:00.197  6168  6220 W jxcore-log: 
,08-16 18:15:00.377  6168  6220 I jxcore-log: JXcore Cordova bridge is ready!
08-16 18:15:00.377  6168  6220 I jxcore-log: 
,08-16 18:15:00.377  6168  6220 W jxcore-log: JXcore engine is started
,08-16 18:15:00.387  6168  6211 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-16 18:15:00.387  6168  6168 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-16 18:15:02.447   286   286 E SMD     : DCD OFF
,08-16 18:15:03.417   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-16 18:15:03.507  5409  5409 D FactoryTest: Not factory mode
,08-16 18:15:03.507  5409  5409 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-16 18:15:03.507  5409  5409 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-16 18:15:03.507  5409  5409 D MTPRx   : still no open session command from host, so toast
,08-16 18:15:03.507  5409  5409 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,08-16 18:15:03.507  5409  5409 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-16 18:15:03.507  5409  5409 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:113839
,08-16 18:15:03.507  1014  1359 E PersonaManagerService: inState():  stateMachine is null !!
,08-16 18:15:03.517  1014  1359 I PersonaManagerService: PersonaId don't exist
08-16 18:15:03.517  1014  1359 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-16 18:15:03.517  1014  1359 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-16 18:15:03.517  1014  1359 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:03.517  1014  1359 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:03.517  1014  1359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-16 18:15:03.517  1014  1359 W ActivityManager: mDVFSHelper.acquire()
,08-16 18:15:03.537  1014  1359 D PersonaManager: isKioskContainerExistOnDevice
,08-16 18:15:03.537  1014  1359 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-16 18:15:03.547  1014  1359 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
08-16 18:15:03.547  1014  1359 D InputDispatcher: Focused application set to: xxxx
,08-16 18:15:03.547  1014  1359 D InputDispatcher: Focus left window: 6168
,08-16 18:15:03.547  5409  5409 E MTPRx   : started activity for popup
,08-16 18:15:03.547  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-16 18:15:03.547  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-16 18:15:03.577  5409  5409 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-16 18:15:03.577  5409  5409 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,08-16 18:15:03.577  5409  5409 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-16 18:15:03.577  5409  5409 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 18:15:03.577  5409  5409 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-16 18:15:03.577  5409  5409 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-16 18:15:03.597  5409  5409 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-16 18:15:03.597  1014  1719 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-16 18:15:03.597  1014  1719 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-16 18:15:03.597  1014  1719 D InputDispatcher: Focused application set to: xxxx
,08-16 18:15:03.597  1014  1719 D InputDispatcher: Focus entered window: 6168
,08-16 18:15:03.607  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-16 18:15:03.607  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-16 18:15:03.607  1014  1558 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-16 18:15:03.607  1014  1558 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@2d4bfbb2 attribute=null, token = android.os.BinderProxy@3e300e02
,08-16 18:15:03.657  5409  5409 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-16 18:15:03.667  5409  5409 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-16 18:15:03.667  5409  5409 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-16 18:15:03.677  6168  6168 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-16 18:15:03.677  6168  6168 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-16 18:15:03.687  6168  6168 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-16 18:15:03.687  6168  6168 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-16 18:15:03.687  1014  1483 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-16 18:15:03.687  1014  1483 D KnoxTimeoutHandler: postActiveUserChange for user 0
,08-16 18:15:03.687  1014  1483 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-16 18:15:03.687  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-16 18:15:03.687  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
,08-16 18:15:03.697  6168  6168 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-16 18:15:03.697  6168  6168 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-16 18:15:03.707  6168  6168 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@dab39c8 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@2f5aa1d6, 16908290=android.view.AbsSavedState$1@2f5aa1d6}, android:focusedViewId=100}]}]
08-16 18:15:03.707  6168  6168 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-16 18:15:03.707  6168  6168 V ActivityThread: updateVisibility : ActivityRecord{15295be3 token=android.os.BinderProxy@267f9b9d {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-16 18:15:03.707  6168  6168 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-16 18:15:03.707  6168  6168 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-16 18:15:03.707  6168  6168 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@267f9b9d time:114033
,08-16 18:15:03.707  1014  1491 D PersonaManager: isKioskContainerExistOnDevice
,08-16 18:15:04.417   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 18:15:05.417   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 18:15:05.457   286   286 E SMD     : DCD OFF
,08-16 18:15:05.717  1014  1133 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-16 18:15:05.727  1014  1133 D BatteryService: level:91, scale:100, status:2, health:2, present:true, voltage: 4167, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,08-16 18:15:05.727  1014  1133 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-16 18:15:05.727  1014  1133 D BatteryService: stay LED for charging
,08-16 18:15:05.727  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-16 18:15:05.727  1171  1171 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-16 18:15:05.727  1171  1171 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-16 18:15:05.727  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-16 18:15:05.727  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 91
,08-16 18:15:05.737  1014  1014 I MotionRecognitionService: Plugged
,08-16 18:15:05.737  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,08-16 18:15:05.737  2651  2651 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-16 18:15:05.747  2651  2741 D HeadsetStateMachine: Disconnected process message: 10
,08-16 18:15:05.757  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:91 status:2 health:2
,08-16 18:15:05.757  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:91 status:2 health:2
08-16 18:15:05.757  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:91 status:2 health:2
,08-16 18:15:06.187  1014  2752 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-16 18:15:06.417   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-16 18:15:06.517  1014  1040 W ActivityManager: mDVFSHelper.release(),
,08-16 18:15:06.937  1014  2723 D SSRM:n  : SIOP:: AP = 330,
,08-16 18:15:07.417   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 18:15:08.417   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-16 18:15:08.457   286   286 E SMD     : DCD OFF
,08-16 18:15:08.567  1014  1055 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS,
,08-16 18:15:09.677  1014  1093 V AlarmManager: waitForAlarm result :4
,08-16 18:15:09.687  1014  1093 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,08-16 18:15:09.707  1014  1014 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,08-16 18:15:09.707  1014  1014 V AlarmManagerEXT: <AppSync3 Whitelist>
,08-16 18:15:09.707  1014  1014 V AlarmManagerEXT: (AppSync) ### 0 added ###
,08-16 18:15:09.707  1171  1171 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-16 18:15:09.707  1171  1171 D KeyguardUpdateMonitor: handleTimeUpdate
,08-16 18:15:09.717  1931  1931 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-16 18:15:09.727  1171  1171 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-16 18:15:09.727  1171  1171 D SecKeyguardClockView: HomeTimezone(): 1
,08-16 18:15:09.737  1171  1171 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
08-16 18:15:09.737  1171  1171 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
08-16 18:15:09.737  1171  1171 I KeyguardEffectViewController: *** don't update sliding image ***
,08-16 18:15:09.757  1014  1491 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 18:15:09.757  1014  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,08-16 18:15:09.757  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:09.757  1014  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:09.757  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:09.777  1171  1171 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-16 18:15:09.787  1171  1171 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-16 18:15:09.797  1171  1171 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-16 18:15:09.817  1171  1171 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-16 18:15:09.837  3812  3812 D ConnectivityManager: CallingUid : 10012, CallingPid : 3812
,08-16 18:15:09.837  1014  1345 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-16 18:15:09.837  1014  1125 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,08-16 18:15:09.837  1014  1125 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
,08-16 18:15:09.837  1014  1125 D ConnectivityService: apparently satisfied.  currentScore=60
,08-16 18:15:09.837  3812  6230 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-16 18:15:09.887  3812  6231 W DriveInitializer: Background init thread started
,08-16 18:15:09.907   255   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-16 18:15:09.907   255   520 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 18:15:09.907  3812  6231 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-16 18:15:09.957  1014  1558 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 18:15:09.957  1014  1558 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-16 18:15:09.967  1014  1558 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:09.967  1014  1558 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:09.967  1014  1558 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:09.997  1014  1359 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
08-16 18:15:09.997  1014  1359 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-16 18:15:10.007  1014  1719 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 18:15:10.007  1014  1719 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-16 18:15:10.007  1014  1719 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:10.007  1014  1719 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 18:15:10.007  1014  1719 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:10.017  3812  6231 W DriveInitializer: Background init thread ended
,08-16 18:15:10.027  3812  6239 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,08-16 18:15:10.027  3812  6239 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-16 18:15:10.047  1931  1931 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-16 18:15:10.087  1014  1040 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:10.087  1014  1040 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:10.087  1014  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:10.187  1014  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 18:15:10.187  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-16 18:15:10.187  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:10.187  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:10.187  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:10.227  1014  1557 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 18:15:10.227  1014  1557 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,08-16 18:15:10.227  1014  1557 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:10.227  1014  1557 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:10.227  1014  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:10.277  1014  1133 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 18:15:10.277  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:10.277  1014  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:10.277  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:10.297  1014  3070 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 18:15:10.297  1014  3070 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:10.297  1014  3070 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:10.297  1014  3070 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:10.337  1014  1483 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 18:15:10.337  1014  1483 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:10.337  1014  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:10.337  1014  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:10.337  1014  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-16 18:15:10.337  1014  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:10.337  1014  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:10.337  1014  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-16 18:15:10.357  6244  6244 E Zygote  : MountEmulatedStorage(),
,08-16 18:15:10.357  6244  6244 I libpersona: KNOX_SDCARD checking this for 10012
08-16 18:15:10.357  6244  6244 E Zygote  : v2
08-16 18:15:10.357  6244  6244 I libpersona: KNOX_SDCARD not a persona
,08-16 18:15:10.357  1014  1483 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6244 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,08-16 18:15:10.367  6244  6244 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-16 18:15:10.367  6244  6244 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-16 18:15:10.367  6244  6244 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-16 18:15:10.377   308   308 I art     : Explicit concurrent mark sweep GC freed 8712(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 2.232ms total 24.131ms
,08-16 18:15:10.397   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 605us total 18.442ms,
,08-16 18:15:10.407  6244  6244 D TimaKeyStoreProvider: TimaSignature is unavailable,
,08-16 18:15:10.407  6244  6244 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:10.417   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 641us total 17.213ms
,08-16 18:15:10.427  6244  6244 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-16 18:15:10.427  6244  6244 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-16 18:15:10.467  6244  6244 I MultiDex: VM with version 2.1.0 has multidex support
08-16 18:15:10.467  6244  6244 I MultiDex: install
08-16 18:15:10.467  6244  6244 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-16 18:15:10.497  6244  6244 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-16 18:15:10.557  1014  1093 V AlarmManager: waitForAlarm result :4
,08-16 18:15:10.557  6244  6244 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-16 18:15:10.557  6244  6244 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@37d72c7d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-16 18:15:10.557  6244  6244 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-16 18:15:10.577  6244  6244 D ChimeraCfgMgr: Reading stored module config
,08-16 18:15:10.617  1014  1215 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,08-16 18:15:10.627  1014  1719 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 18:15:10.627  1014  1719 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:10.627  1014  1719 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:10.627  1014  1719 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:10.637  1014  1215 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 18:15:10.637  1014  1215 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:10.637  1014  1215 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:10.637  1014  1215 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:10.677  6244  6258 I art     : Background sticky concurrent mark sweep GC freed 28610(1350KB) AllocSpace objects, 3(133KB) LOS objects, 5% free, 10MB/11MB, paused 10.413ms total 81.627ms
,08-16 18:15:10.687  1931  1931 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=8561da5a-90a5-410e-ac36-7f2238efa012
08-16 18:15:10.687  6244  6244 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-16 18:15:10.687  6244  6244 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-16 18:15:10.717  1014  1026 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-16 18:15:10.717  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-16 18:15:10.717  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:10.717  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 18:15:10.717  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:10.727  1931  1931 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-16 18:15:10.727  1931  1931 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-16 18:15:10.737  6244  6261 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-16 18:15:10.747  1014  1215 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 18:15:10.747  1014  1215 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:10.747  1014  1215 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:10.747  1014  1215 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:10.797   281  1012 D WVCdm   : Instantiating CDM.
,08-16 18:15:10.797   281   706 I WVCdm   : CdmEngine::OpenSession
08-16 18:15:10.797   281   706 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-16 18:15:10.827   281   706 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-16 18:15:10.847   281   706 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
08-16 18:15:10.847   281   706 D DrmWidevineDash: Service_Initialize: starts!
08-16 18:15:10.847   281   706 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,08-16 18:15:10.847   281   706 D QSEECOMAPI: : App is not loaded in QSEE
,08-16 18:15:10.847   281   706 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
08-16 18:15:10.847   281   706 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-16 18:15:10.847   281   706 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-16 18:15:10.847   281   706 D QSEECOMAPI: : App is not loaded in QSEE
08-16 18:15:10.847   281   706 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
08-16 18:15:10.847   281   706 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-16 18:15:10.847   281   706 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-16 18:15:10.847   281   706 D QSEECOMAPI: : App is not loaded in QSEE
,08-16 18:15:10.877   281   706 D QSEECOMAPI: : Loaded image: APP id = 11
,08-16 18:15:10.877   281   706 D DrmWidevineDash: Service_Initialize: ends! returns 0
,08-16 18:15:10.877   281   706 D QSAPPSVER: qsapps_get_capabilities: Capability from secure side: 0x0
08-16 18:15:10.877   281   706 D QSAPPSVER: qsapps_get_capabilities: returns 0
08-16 18:15:10.877   281   706 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb16da000
08-16 18:15:10.877   281   706 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb16da000
,08-16 18:15:10.877   281   706 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 18:15:10.887   428   435 D DrmLibTime: got the req here! ret=0
08-16 18:15:10.887   428   435 D DrmLibTime: command id, time_cmd_id = 770
08-16 18:15:10.887   428   435 D DrmLibTime: time_getutcsec starts!
08-16 18:15:10.887   428   435 D DrmLibTime: QSEE Time Listener: time_getutcsec
08-16 18:15:10.887   428   435 D DrmLibTime: QSEE Time Listener: get_utc_seconds
08-16 18:15:10.887   428   435 D DrmLibTime: QSEE Time Listener: time_get_modem_time
08-16 18:15:10.887   428   435 D DrmLibTime: QSEE Time Listener: Checking if ATS_MODEM is set or not.
,08-16 18:15:10.887   428   435 D QC-time-services: Lib:time_genoff_operation: pargs->base = 13,
08-16 18:15:10.887   428   435 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 2
08-16 18:15:10.887   428   435 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 0
08-16 18:15:10.887   428   435 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!,
08-16 18:15:10.887   324   558 D QC-time-services: Daemon: Connection accepted:time_genoff
,08-16 18:15:10.887   324  6267 D QC-time-services: Daemon:Received base = 13, unit = 1, operation = 2,value = 0
,08-16 18:15:10.897   324  6267 D QC-time-services: Daemon:genoff_opr: Base = 13, val = 0, operation = 2
08-16 18:15:10.897   324  6267 D QC-time-services: offset is: 0 for base: 0
08-16 18:15:10.897   428   435 E QC-time-services: Receive Passed == base = 13, unit = 1, operation = 2, result = 0
08-16 18:15:10.897   428   435 D DrmLibTime: QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
08-16 18:15:10.897   428   435 D DrmLibTime: QSEE Time Listener: Retrieved Android system time: 1471364110
08-16 18:15:10.897   428   435 D DrmLibTime: time_getutcsec returns 0, sec = 1471364110; nsec = 0
08-16 18:15:10.897   428   435 D DrmLibTime: time_getutcsec finished! 
08-16 18:15:10.897   428   435 D DrmLibTime: iotcl_continue_command finished! and return 0 
08-16 18:15:10.897   428   435 D DrmLibTime: before calling ioctl to read the next time_cmd
08-16 18:15:10.897   324   558 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
08-16 18:15:10.897   281   706 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,08-16 18:15:10.897   281   706 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,08-16 18:15:10.897   281   706 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
08-16 18:15:10.897   281   706 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 18:15:10.897   281   706 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 18:15:10.897   281   706 D DrmWidevineDash: hlos api version =  9
,08-16 18:15:10.897   281   706 D DrmWidevineDash: tz api version =  9
08-16 18:15:10.897   281   706 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
08-16 18:15:10.897   281   706 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
08-16 18:15:10.897   281   706 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 18:15:10.907  1659  1725 I art     : Explicit concurrent mark sweep GC freed 1449(49KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 726us total 32.847ms
,08-16 18:15:10.917   281   706 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 18:15:10.917   281   706 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
08-16 18:15:10.917   281   706 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
08-16 18:15:10.917   281   706 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb182e960
08-16 18:15:10.917   281   706 D DrmWidevineDash: OEMCrypto_OpenSession Session ID = 0
08-16 18:15:10.917   281   706 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-16 18:15:10.917   281   706 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 18:15:10.917   281   706 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
08-16 18:15:10.917   281   706 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
08-16 18:15:10.917   281   706 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb85c78a8, dataLength=8
08-16 18:15:10.917   281   706 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 18:15:10.917   281   706 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 18:15:10.917   281   706 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,08-16 18:15:10.927   281   706 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xb854eb18, wrapped_rsa_key_length=1280
08-16 18:15:10.927   281   706 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 18:15:10.927   281   706 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 18:15:10.927   281   706 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
08-16 18:15:10.927   281   706 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-16 18:15:10.927   281   683 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,08-16 18:15:10.927   281   683 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
,08-16 18:15:10.927   281   683 I WVCdm   : CdmEngine::GenerateKeyRequest
,08-16 18:15:10.937   281   683 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb85c61c0, idLength=0xb192e730
,08-16 18:15:10.937   281   683 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 18:15:10.937  6244  6253 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-16 18:15:10.937  6244  6253 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 18:15:10.947  6244  6253 I System.out: (HTTPLog)-Static: isShipBuild true
08-16 18:15:10.947  6244  6253 I System.out: (HTTPLog)-Thread-1050-613204374: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-16 18:15:10.947  6244  6253 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 18:15:10.947   276   974 D EnterpriseController: uids 10012
08-16 18:15:10.947   276   974 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-16 18:15:10.947   276   974 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-16 18:15:10.967   281   683 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 18:15:10.967   281   683 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
08-16 18:15:10.967   281   683 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
08-16 18:15:10.967   281   683 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 18:15:10.967   281   683 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 18:15:10.967   281   683 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
08-16 18:15:10.967   281   683 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 24
08-16 18:15:10.967   281   683 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0
08-16 18:15:10.967   281   683 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!, current = 0xb192e746, maximum = 0xb192e747
08-16 18:15:10.967   281   683 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-16 18:15:10.967   281   683 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 18:15:10.967   281   683 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0
08-16 18:15:10.967   281   683 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
08-16 18:15:10.967   281   683 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-16 18:15:10.967   281   683 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 18:15:10.967   281   683 D DrmWidevineDash: hlos api version =  9
08-16 18:15:10.967   281   683 D DrmWidevineDash: tz api version =  9
08-16 18:15:10.967   281   683 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
08-16 18:15:10.967   281   683 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xb192e7b4
08-16 18:15:10.967   281   683 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-16 18:15:10.967   281   683 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 18:15:10.967   281   683 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
08-16 18:15:10.967   281   683 D WVCdm   : PrepareKeyRequest: nonce=1198734996
08-16 18:15:10.967   281   683 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb854c070
08-16 18:15:10.967   281   683 D DrmWidevineDash: message_length=1599, signature=0xb8575020, signature_length=0xb192e714
08-16 18:15:10.967   281   683 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 18:15:10.997  6244  6253 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-16 18:15:10.997  6244  6253 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6244, getuid(): 10012
,08-16 18:15:11.017  1931  2095 W GCoreFlp: No location to return for getLastLocation()
,08-16 18:15:11.097  1931  2095 I art     : Explicit concurrent mark sweep GC freed 55445(3MB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 14MB/23MB, paused 1.594ms total 76.748ms
,08-16 18:15:11.137  6244  6258 I art     : Background partial concurrent mark sweep GC freed 7860(561KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 10MB/17MB, paused 9.431ms total 60.585ms
,08-16 18:15:11.137   281   683 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 18:15:11.137   281   683 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,08-16 18:15:11.147   281  1012 I WVCdm   : CdmEngine::CloseSession
08-16 18:15:11.147   281  1012 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
08-16 18:15:11.147   281  1012 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 18:15:11.147   281  1012 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 18:15:11.147   281  1012 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
08-16 18:15:11.147   281  1012 I WVCdm   : L3 Terminate.
08-16 18:15:11.147   281  1012 D DrmWidevineDash: OEMCrypto_Terminate: starts!
08-16 18:15:11.147   281  1012 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-16 18:15:11.147   281  1012 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 18:15:11.147   281  1012 D DrmWidevineDash: Service_Uninitialize: starts!
08-16 18:15:11.147   281  1012 D QSEECOMAPI: : QSEECom_dealloc_memory 
08-16 18:15:11.147   281  1012 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 11
,08-16 18:15:11.147   281  1012 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
08-16 18:15:11.147   281  1012 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,08-16 18:15:11.147  1014  1491 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 18:15:11.147  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:11.147  1014  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:11.147  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:11.157  1014  1558 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 18:15:11.157  1014  1558 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:11.157  1014  1558 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:11.157  1014  1558 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:11.157  1014  1557 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 18:15:11.157  1014  1557 W ActivityManager: userId = 0, bbcId = -10000,
08-16 18:15:11.157  1014  1557 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:11.157  1014  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:11.177  3812  6240 D UdcContextInitService: registered all accounts: true
,08-16 18:15:11.277  6244  6253 I qtaguid : Untagging socket 30
,08-16 18:15:11.337  1014  1555 I art     : Explicit concurrent mark sweep GC freed 39865(2MB) AllocSpace objects, 20(320KB) LOS objects, 33% free, 27MB/41MB, paused 2.561ms total 154.206ms
,08-16 18:15:11.337  1931  2101 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-16 18:15:11.347  1931  2117 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-16 18:15:11.457   286   286 E SMD     : DCD OFF
,08-16 18:15:11.527  1014  1026 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-16 18:15:11.527  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-16 18:15:11.537  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:11.537  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:11.537  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:11.607  1014  1719 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-16 18:15:11.607  1014  1719 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-16 18:15:11.607  1014  1719 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:11.607  1014  1719 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:11.607  1014  1719 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:11.617  1931  2117 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 18:15:11.617   276   974 D EnterpriseController: uids 10012
08-16 18:15:11.617   276   974 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-16 18:15:11.617   276   974 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-16 18:15:11.617  1931  2117 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-16 18:15:11.617  1931  2117 I qtaguid : Tagging socket 65 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1931, getuid(): 10012
,08-16 18:15:11.667  6277  6277 I dex2oat : ----------------------------------------------------
08-16 18:15:11.667  6277  6277 I dex2oat : <SS>: S T A R T I N G . . .
08-16 18:15:11.667  6277  6277 I dex2oat : <SS>: Zip is absent. Canceled.
08-16 18:15:11.667  6277  6277 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=44 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-16 18:15:11.677  1931  2117 I qtaguid : Tagging socket 68 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1931, getuid(): 10012
,08-16 18:15:11.707  6277  6277 I dex2oat : dex2oat took 33.353ms (threads: 4)
,08-16 18:15:11.717  6244  6253 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-16 18:15:11.717  6244  6253 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-16 18:15:11.717  6244  6253 I Adreno-EGL: Build Date: 04/06/15 Mon
08-16 18:15:11.717  6244  6253 I Adreno-EGL: Local Branch: 
08-16 18:15:11.717  6244  6253 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-16 18:15:11.717  6244  6253 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-16 18:15:11.717  6244  6253 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-16 18:15:11.797  6244  6253 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-16 18:15:11.797  6244  6253 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-16 18:15:11.797  6244  6253 I Adreno-EGL: Build Date: 04/06/15 Mon
08-16 18:15:11.797  6244  6253 I Adreno-EGL: Local Branch: 
08-16 18:15:11.797  6244  6253 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-16 18:15:11.797  6244  6253 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-16 18:15:11.797  6244  6253 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-16 18:15:11.847  6244  6253 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
08-16 18:15:11.847  6244  6253 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-16 18:15:11.847  6244  6253 I Adreno-EGL: Build Date: 04/06/15 Mon
08-16 18:15:11.847  6244  6253 I Adreno-EGL: Local Branch: 
08-16 18:15:11.847  6244  6253 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-16 18:15:11.847  6244  6253 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-16 18:15:11.847  6244  6253 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-16 18:15:12.277  1931  6242 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 18:15:12.277  1931  6242 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-16 18:15:12.277  1931  6242 I qtaguid : Tagging socket 69 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1931, getuid(): 10012
,08-16 18:15:12.317  1931  6242 I qtaguid : Tagging socket 72 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1931, getuid(): 10012
,08-16 18:15:12.457  1931  2117 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-16 18:15:12.467  1931  2117 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-16 18:15:12.467  1931  2117 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-16 18:15:11.432+0200, stopTime=2016-08-16 18:15:12.478+0200, duration=1046ms
,08-16 18:15:12.477  1931  6285 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 18:15:12.477   276   974 D EnterpriseController: uids 10012
08-16 18:15:12.477   276   974 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-16 18:15:12.477   276   974 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-16 18:15:12.477  1931  6285 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-16 18:15:12.477  1931  6285 I qtaguid : Tagging socket 73 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1931, getuid(): 10012
,08-16 18:15:12.527  1931  6285 I qtaguid : Tagging socket 76 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1931, getuid(): 10012
,08-16 18:15:12.527  1014  1345 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-16 18:15:12.767  1931  6285 I qtaguid : Untagging socket 73
,08-16 18:15:12.797  1014  1215 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 18:15:12.797  1014  1215 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,08-16 18:15:12.797  1014  1215 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:12.797  1014  1215 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:12.797  1014  1215 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:12.827  1931  2117 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-16 18:15:12.877  1014  1359 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 18:15:12.877  1014  1359 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:12.877  1014  1359 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:12.877  1014  1359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:12.907  1014  1359 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 18:15:12.907  1014  1359 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:12.907  1014  1359 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 18:15:12.907  1014  1359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:12.947  1014  1345 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 18:15:12.947  1014  1345 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:12.947  1014  1345 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:12.947  1014  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:12.947  1931  6292 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-16 18:15:12.947  1931  6290 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-16 18:15:12.947  1014  3070 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 18:15:12.947  1014  3070 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:12.957  1014  3070 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 18:15:12.957  1014  3070 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:12.977  1014  1483 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 18:15:12.977  1014  1483 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:12.977  1014  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:12.977  1014  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:12.977  1931  6292 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-16 18:15:12.977  1931  6290 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-16 18:15:12.977  1014  1491 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 18:15:12.977  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:12.977  1014  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:12.977  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:13.007  1014  1026 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 18:15:13.007  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:13.007  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:13.007  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:13.007  1931  6292 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-16 18:15:13.007  1931  6290 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-16 18:15:13.007  1931  6290 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,08-16 18:15:13.017  1931  6290 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-16 18:15:13.057  1014  1027 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-16 18:15:13.097  1931  6290 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 18:15:13.097   276   974 D EnterpriseController: uids 10012
08-16 18:15:13.097   276   974 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-16 18:15:13.097   276   974 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-16 18:15:13.107  1931  6290 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-16 18:15:13.107  1931  6290 I qtaguid : Tagging socket 85 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1931, getuid(): 10012
,08-16 18:15:13.147  1931  6290 I qtaguid : Tagging socket 88 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1931, getuid(): 10012
,08-16 18:15:13.387  1014  1558 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-16 18:15:13.397  1931  6290 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 18:15:13.397  1931  6290 I qtaguid : Tagging socket 85 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1931, getuid(): 10012
,08-16 18:15:13.427   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-16 18:15:13.537  1014  1558 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-16 18:15:13.537  1931  6290 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 18:15:13.547  1931  6290 I qtaguid : Tagging socket 85 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 1931, getuid(): 10012
,08-16 18:15:13.557  6168  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-16 18:15:13.557  6168  6220 I jxcore-log: 
,08-16 18:15:13.557  6168  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-16 18:15:13.557  6168  6220 I jxcore-log: 
,08-16 18:15:13.567  6168  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:15:13.567  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:13.567  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:13.567  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:13.567  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:13.567  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:13.567  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:15:13.567  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 18:15:13.567  6168  6220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 18:15:13.577  6168  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-16 18:15:13.577  6168  6220 I jxcore-log: 
,08-16 18:15:13.577  6168  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-16 18:15:13.577  6168  6220 I jxcore-log: 
,08-16 18:15:14.017  6168  6220 D ExecuteNativeTests: Running unit tests
,08-16 18:15:14.097  6168  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:15:14.097  6168  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2340f947 added. We now have 2 listener(s)
,08-16 18:15:14.107  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-16 18:15:14.107  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:15:14.107  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:15:14.107  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:15:14.107  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2287f574 added. We now have 2 listener(s)
08-16 18:15:14.107  6168  6220 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 18:15:14.107  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 18:15:14.107  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 18:15:14.107  6168  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:15:14.107  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:14.107  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:14.107  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:14.107  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:14.107  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:14.107  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:15:14.107  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 18:15:14.107  6168  6220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 18:15:14.117  6168  6220 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 18:15:14.117  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:14.117  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 18:15:14.117  6168  6220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 18:15:14.117  6168  6220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 18:15:14.117  6168  6220 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-16 18:15:14.117  6168  6220 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-16 18:15:14.117  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 18:15:14.117  6168  6220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 18:15:14.117  6168  6220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 18:15:14.117  6168  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:14.117  6168  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:14.117  6168  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:14.117  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:14.117  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.117  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:15:14.117  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:15:14.117  6168  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2340f947 removed from the list
08-16 18:15:14.117  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.117  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2287f574 removed from the list
08-16 18:15:14.117  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:14.117  6168  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:14.117  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:14.127  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 18:15:14.127  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:14.127  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:14.127  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:14.127  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.127  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2287f574 not in the list
,08-16 18:15:14.127  6168  6220 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-16 18:15:14.127  6168  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:14.127  6168  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 18:15:14.127  6168  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:14.127  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:14.127  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.127  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.127  6168  6220 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2340f947 not in the list
,08-16 18:15:14.127  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.127  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2287f574 not in the list
08-16 18:15:14.127  6168  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:14.127  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.127  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.127  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.127  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.127  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:14.127  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:14.127  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 18:15:14.127  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2287f574 not in the list
,08-16 18:15:14.137  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55],
08-16 18:15:14.137  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 18:15:14.137  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 18:15:14.137  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 18:15:14.137  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 18:15:14.137  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-16 18:15:14.137  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 18:15:14.137  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 18:15:14.137  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 18:15:14.137  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 18:15:14.137  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 18:15:14.137  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 18:15:14.137  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 18:15:14.137  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 18:15:14.137  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 18:15:14.137  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 18:15:14.137  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 18:15:14.137  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 18:15:14.137  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 18:15:14.137  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 18:15:14.137  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 18:15:14.137  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 18:15:14.137  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 18:15:14.137  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 18:15:14.137  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 18:15:14.137  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 18:15:14.137  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-16 18:15:14.137  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 18:15:14.137  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 18:15:14.137  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 18:15:14.137  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 18:15:14.137  6168  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:14.137  6168  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:14.137  6168  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:14.137  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:14.137  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.137  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.137  6168  6220 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2340f947 not in the list
08-16 18:15:14.137  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.137  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2287f574 not in the list
08-16 18:15:14.137  6168  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:14.137  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.137  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.137  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.137  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.137  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:14.137  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:14.137  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.137  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2287f574 not in the list
08-16 18:15:14.137  6168  6220 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 18:15:14.137  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:15:14.137  6168  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:15:14.137  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:14.137  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:14.137  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:14.137  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:14.137  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:14.137  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:15:14.137  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 18:15:14.147  6168  6220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:14.147  6168  6220 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 18:15:14.147  6168  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 18:15:14.147  6168  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 18:15:14.147  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 18:15:14.147  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:15:14.147  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 18:15:14.147  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:14.147  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 18:15:14.147  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:14.157  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 18:15:14.157  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 18:15:14.157  6168  6220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-16 18:15:14.167  6168  6220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-16 18:15:14.167  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 18:15:14.167  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-16 18:15:14.177  6168  6220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 18:15:14.187  2651  2660 D BtGatt.GattService: registerClient() - UUID=1ed4daa2-d7b2-497b-9e0b-789af9a6c0ed
,08-16 18:15:14.237  2651  2719 D BtGatt.GattService: onClientRegistered() - UUID=1ed4daa2-d7b2-497b-9e0b-789af9a6c0ed, clientIf=6
,08-16 18:15:14.237  6168  6178 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-16 18:15:14.237  2651  2977 D BtGatt.GattService: start scan with filters
,08-16 18:15:14.247  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 18:15:14.247  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-16 18:15:14.247  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 18:15:14.247  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 18:15:14.247  6168  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 18:15:14.247  2651  2738 D BtGatt.ScanManager: handling starting scan
,08-16 18:15:14.247  2651  2738 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2877fa98
,08-16 18:15:14.257  6168  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 18:15:14.257  6168  6168 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 18:15:14.257  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 18:15:14.257  6168  6220 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 18:15:14.267  2651  2719 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-16 18:15:14.267  2651  2719 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:14.267  2651  2738 D BtGatt.ScanManager: allow scan with filters
08-16 18:15:14.267  2651  2738 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-16 18:15:14.267  2651  2738 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-16 18:15:14.267  6168  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 18:15:14.267  6168  6220 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-16 18:15:14.277  6168  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:14.277  6168  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 18:15:14.277  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.277  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 18:15:14.277  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 18:15:14.277  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 18:15:14.277  6168  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 18:15:14.277  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 18:15:14.277  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-16 18:15:14.277  2651  2719 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-16 18:15:14.277  2651  2719 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 18:15:14.277  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 18:15:14.277  2651  2738 D BtGatt.ScanManager: Starting BLE batch scan
08-16 18:15:14.277  2651  2738 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-16 18:15:14.277  2651  2660 D BtGatt.GattService: stopScan() - queue size =1
,08-16 18:15:14.277  2651  2977 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-16 18:15:14.287  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 18:15:14.287  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 18:15:14.287  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 18:15:14.287  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 18:15:14.287  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 18:15:14.287  6168  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 18:15:14.287  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-16 18:15:14.287  6168  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 18:15:14.287  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 18:15:14.287  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 18:15:14.297  2651  2719 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-16 18:15:14.297  2651  2719 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:14.297  6168  6168 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 18:15:14.297  6168  6168 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 18:15:14.297  6168  6168 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 18:15:14.297  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:14.297  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.297  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:15:14.297  6168  6220 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2340f947 not in the list
08-16 18:15:14.297  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.297  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2287f574 not in the list
08-16 18:15:14.297  6168  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:14.297  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:14.297  6168  6220 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-16 18:15:14.297  2651  2719 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-16 18:15:14.297  2651  2719 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:14.307  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 18:15:14.317  6168  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:15:14.317  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:14.317  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:14.317  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:14.317  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:14.317  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:14.317  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:15:14.317  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 18:15:14.317  6168  6220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:14.317  6168  6220 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 18:15:14.317  6168  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 18:15:14.317  6168  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 18:15:14.317  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 18:15:14.317  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:15:14.317  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 18:15:14.317  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:14.327  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 18:15:14.327  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:14.327  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 18:15:14.327  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 18:15:14.337  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 18:15:14.337  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 18:15:14.337  6168  6220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 18:15:14.337  2651  2738 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 30
,08-16 18:15:14.337  2651  2662 D BtGatt.GattService: registerClient() - UUID=6b38c138-b5e1-4a30-bbc2-5774379e93ae
,08-16 18:15:14.337  2651  2738 D BtGatt.ScanManager: filter size is 1
,08-16 18:15:14.337  2651  2738 D BtGatt.ScanManager: delete FilterIndex - 3
,08-16 18:15:14.347  2651  2719 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-16 18:15:14.347  2651  2719 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:14.347  2651  2738 D BtGatt.ScanManager: stopping BLe Batch
,08-16 18:15:14.357  2651  2719 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-16 18:15:14.357  2651  2719 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:14.357  2651  2738 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-16 18:15:14.367  2651  2719 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-16 18:15:14.367  2651  2719 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:14.377  2651  2719 D BtGatt.GattService: onClientRegistered() - UUID=6b38c138-b5e1-4a30-bbc2-5774379e93ae, clientIf=6
,08-16 18:15:14.377  6168  6182 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-16 18:15:14.377  2651  2660 D BtGatt.GattService: start scan with filters
,08-16 18:15:14.377  2651  2738 D BtGatt.ScanManager: handling starting scan
,08-16 18:15:14.387  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 18:15:14.387  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 18:15:14.387  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 18:15:14.387  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 18:15:14.387  6168  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 18:15:14.387  6168  6168 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 18:15:14.387  6168  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 18:15:14.387  2651  2719 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-16 18:15:14.387  2651  2719 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:14.387  2651  2738 D BtGatt.ScanManager: allow scan with filters
08-16 18:15:14.387  2651  2738 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-16 18:15:14.387  2651  2738 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-16 18:15:14.397  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 18:15:14.397  6168  6220 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 18:15:14.397  2651  2719 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-16 18:15:14.397  2651  2719 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:14.397  2651  2738 D BtGatt.ScanManager: Starting BLE batch scan
,08-16 18:15:14.397  2651  2738 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-16 18:15:14.407  6168  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 18:15:14.407  6168  6220 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-16 18:15:14.407  6168  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 18:15:14.407  6168  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 18:15:14.407  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.407  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 18:15:14.407  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 18:15:14.407  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 18:15:14.407  6168  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-16 18:15:14.407  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 18:15:14.407  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-16 18:15:14.407  2651  2719 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-16 18:15:14.407  2651  2719 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:14.407  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 18:15:14.407  2651  2977 D BtGatt.GattService: stopScan() - queue size =1
,08-16 18:15:14.417  2651  2662 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-16 18:15:14.417  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 18:15:14.417  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 18:15:14.417  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 18:15:14.417  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 18:15:14.417  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 18:15:14.417  6168  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 18:15:14.417  2651  2719 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-16 18:15:14.417  2651  2719 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:14.427  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 18:15:14.427  6168  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 18:15:14.427  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 18:15:14.427   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
08-16 18:15:14.427  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 18:15:14.427  6168  6168 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 18:15:14.427  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:14.427  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.427  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:15:14.427  6168  6220 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2340f947 not in the list
08-16 18:15:14.427  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.427  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2287f574 not in the list
08-16 18:15:14.427  6168  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:14.427  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:14.427  6168  6168 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-16 18:15:14.427  6168  6168 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 18:15:14.427  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.427  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:14.427  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 18:15:14.427  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:14.427  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 18:15:14.427  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2287f574 not in the list
,08-16 18:15:14.427  6168  6220 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-16 18:15:14.437  2651  2738 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 31
,08-16 18:15:14.437  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 18:15:14.437  2651  2738 D BtGatt.ScanManager: filter size is 1
,08-16 18:15:14.437  2651  2738 D BtGatt.ScanManager: delete FilterIndex - 4
,08-16 18:15:14.437  6168  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:15:14.437  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:14.437  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:14.437  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:14.437  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:14.437  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:14.437  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:15:14.437  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 18:15:14.447  6168  6220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 18:15:14.447  6168  6220 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 18:15:14.447  6168  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 18:15:14.447  6168  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 18:15:14.447  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 18:15:14.447  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:15:14.447  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 18:15:14.447  2651  2719 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-16 18:15:14.447  2651  2719 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 18:15:14.447  2651  2738 D BtGatt.ScanManager: stopping BLe Batch
,08-16 18:15:14.447  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:14.447  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:14.447  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 18:15:14.457  2651  2719 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
08-16 18:15:14.457  2651  2719 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 18:15:14.457  2651  2738 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-16 18:15:14.457  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 18:15:14.457   286   286 E SMD     : DCD OFF
08-16 18:15:14.457  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 18:15:14.457  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 18:15:14.457  2651  2719 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-16 18:15:14.457  2651  2719 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 18:15:14.457  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 18:15:14.457  6168  6220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 18:15:14.467  2651  2977 D BtGatt.GattService: registerClient() - UUID=52f9281b-4408-4532-9a77-73754ec1251a
,08-16 18:15:14.507  2651  2719 D BtGatt.GattService: onClientRegistered() - UUID=52f9281b-4408-4532-9a77-73754ec1251a, clientIf=6
,08-16 18:15:14.507  6168  6182 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-16 18:15:14.507  2651  2662 D BtGatt.GattService: start scan with filters
,08-16 18:15:14.507  2651  2738 D BtGatt.ScanManager: handling starting scan
08-16 18:15:14.507  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 18:15:14.507  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-16 18:15:14.507  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 18:15:14.507  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-16 18:15:14.507  6168  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 18:15:14.507  6168  6168 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 18:15:14.507  6168  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 18:15:14.517  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 18:15:14.517  2651  2719 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-16 18:15:14.517  2651  2719 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:14.517  2651  2738 D BtGatt.ScanManager: allow scan with filters
,08-16 18:15:14.517  2651  2738 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-16 18:15:14.517  2651  2738 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-16 18:15:14.517  6168  6220 I io.jxcore.node.ConnectionHelper: start: OK
08-16 18:15:14.517  6168  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:14.517  6168  6220 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 18:15:14.517  6168  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:14.517  6168  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 18:15:14.517  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.517  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 18:15:14.517  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 18:15:14.517  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 18:15:14.517  6168  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 18:15:14.517  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 18:15:14.517  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 18:15:14.517  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 18:15:14.517  2651  2719 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-16 18:15:14.517  2651  2719 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 18:15:14.517  2651  2738 D BtGatt.ScanManager: Starting BLE batch scan
,08-16 18:15:14.517  2651  2738 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-16 18:15:14.527  2651  2660 D BtGatt.GattService: stopScan() - queue size =1
,08-16 18:15:14.527  2651  2977 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-16 18:15:14.527  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 18:15:14.527  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 18:15:14.527  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-16 18:15:14.527  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 18:15:14.527  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED],
08-16 18:15:14.527  2651  2719 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-16 18:15:14.527  2651  2719 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:14.527  6168  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 18:15:14.527  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-16 18:15:14.527  2651  2719 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-16 18:15:14.527  6168  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 18:15:14.527  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 18:15:14.527  2651  2719 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:14.537  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 18:15:14.537  6168  6168 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 18:15:14.537  6168  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:14.537  6168  6220 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 18:15:14.537  6168  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:14.537  6168  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:14.537  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:14.537  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.537  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:15:14.537  6168  6220 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2340f947 not in the list
08-16 18:15:14.537  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.537  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2287f574 not in the list
08-16 18:15:14.537  6168  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:14.537  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:14.537  6168  6168 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 18:15:14.537  6168  6168 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 18:15:14.537  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.537  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:14.547  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 18:15:14.547  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:14.547  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.547  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2287f574 not in the list
,08-16 18:15:14.547  6168  6220 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-16 18:15:14.547  6168  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 18:15:14.547  6168  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:14.547  6168  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:14.547  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:14.547  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.547  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.547  6168  6220 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2340f947 not in the list
08-16 18:15:14.547  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.547  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2287f574 not in the list
08-16 18:15:14.547  6168  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:14.547  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.547  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.547  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.547  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:14.547  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:14.547  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 18:15:14.547  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.547  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2287f574 not in the list
,08-16 18:15:14.547  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 18:15:14.547  6168  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:14.547  6168  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:14.547  6168  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:14.547  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:14.547  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.547  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.547  6168  6220 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2340f947 not in the list
08-16 18:15:14.547  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.547  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2287f574 not in the list
08-16 18:15:14.547  6168  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:14.547  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.547  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.547  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.547  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:14.547  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 18:15:14.547  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:14.547  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.547  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2287f574 not in the list
,08-16 18:15:14.547  6168  6220 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-16 18:15:14.547  6168  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 18:15:14.547  6168  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:14.547  6168  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 18:15:14.557  2651  2738 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 32
,08-16 18:15:14.557  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:14.557  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.557  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.557  6168  6220 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2340f947 not in the list
08-16 18:15:14.557  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 18:15:14.557  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2287f574 not in the list
08-16 18:15:14.557  6168  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:14.557  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.557  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.557  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.557  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.557  2651  2738 D BtGatt.ScanManager: filter size is 1
,08-16 18:15:14.557  2651  2738 D BtGatt.ScanManager: delete FilterIndex - 5
,08-16 18:15:14.557  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 18:15:14.557  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 18:15:14.557  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.557  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2287f574 not in the list
08-16 18:15:14.557  6168  6220 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-16 18:15:14.557  6168  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:14.557  6168  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:14.557  6168  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 18:15:14.557  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:14.557  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.557  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.557  6168  6220 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2340f947 not in the list
08-16 18:15:14.557  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 18:15:14.557  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2287f574 not in the list
08-16 18:15:14.557  6168  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:14.557  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.557  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.557  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 18:15:14.557  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.557  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:14.557  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:14.557  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.557  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2287f574 not in the list
08-16 18:15:14.567  2651  2719 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-16 18:15:14.567  2651  2719 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 18:15:14.567  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 18:15:14.567  6168  6220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 18:15:14.567  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 18:15:14.567  6168  6220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 18:15:14.567  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-16 18:15:14.567  6168  6220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 18:15:14.567  6168  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:14.567  6168  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:14.567  6168  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:14.567  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:14.567  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.567  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.567  6168  6220 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2340f947 not in the list,
08-16 18:15:14.567  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.567  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2287f574 not in the list
08-16 18:15:14.567  6168  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:14.567  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.567  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.567  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.567  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:14.567  2651  2738 D BtGatt.ScanManager: stopping BLe Batch
,08-16 18:15:14.567  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:14.567  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:14.567  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.567  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2287f574 not in the list
,08-16 18:15:14.567  6168  6220 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 18:15:14.567  6168  6220 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 18:15:14.567  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-16 18:15:14.567  6168  6220 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 18:15:14.567  6168  6220 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-16 18:15:14.567  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 18:15:14.567  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 18:15:14.567  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 18:15:14.567  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 18:15:14.567  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 18:15:14.567  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 18:15:14.567  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 18:15:14.567  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 18:15:14.567  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 18:15:14.567  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 18:15:14.567  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 18:15:14.567  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 18:15:14.567  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 18:15:14.567  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 18:15:14.567  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 18:15:14.567  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-16 18:15:14.567  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 18:15:14.567  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 18:15:14.567  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 18:15:14.567  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 18:15:14.567  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 18:15:14.567  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 18:15:14.567  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-16 18:15:14.567  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 18:15:14.567  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 18:15:14.567  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 18:15:14.567  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 18:15:14.567  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 18:15:14.567  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 18:15:14.567  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 18:15:14.567  2651  2719 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-16 18:15:14.567  2651  2719 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 18:15:14.567  6168  6220 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-16 18:15:14.567  6168  6220 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 18:15:14.567  6168  6220 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-16 18:15:14.567  2651  2738 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-16 18:15:14.567  6168  6220 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 18:15:14.567  6168  6220 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 18:15:14.567  6168  6220 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-16 18:15:14.567  6168  6220 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-16 18:15:14.567  6168  6220 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 18:15:14.567  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-16 18:15:14.577  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-16 18:15:14.577  2651  2719 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-16 18:15:14.577  2651  2719 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:14.577  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-16 18:15:14.577  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-16 18:15:14.577  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-16 18:15:14.577  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-16 18:15:14.577  6168  6220 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-16 18:15:14.577  6168  6220 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 18:15:14.577  6168  6220 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,08-16 18:15:14.577  6168  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:14.577  6168  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:14.577  6168  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:14.577  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:14.577  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.577  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.577  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-16 18:15:14.577  6168  6220 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2340f947 not in the list
08-16 18:15:14.577  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.577  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2287f574 not in the list
08-16 18:15:14.577  6168  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:14.577  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.577  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.577  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.577  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:14.587  6168  6302 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1132
08-16 18:15:14.587  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:14.587  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:14.587  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 18:15:14.587  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2287f574 not in the list
08-16 18:15:14.587  6168  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1132)
,08-16 18:15:14.587  6168  6220 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-16 18:15:14.587  6168  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:14.587  6168  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:14.587  6168  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:14.587  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:14.587  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.587  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.587  6168  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1132)
08-16 18:15:14.587  6168  6220 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2340f947 not in the list
08-16 18:15:14.587  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.587  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2287f574 not in the list
08-16 18:15:14.587  6168  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:14.587  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.587  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.587  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.587  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:14.587  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:14.587  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:14.587  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.587  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2287f574 not in the list
,08-16 18:15:14.587  6168  6220 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-16 18:15:14.587  6168  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:14.587  6168  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:14.587  6168  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:14.587  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:14.587  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.587  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.587  6168  6220 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2340f947 not in the list
08-16 18:15:14.587  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.587  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2287f574 not in the list
08-16 18:15:14.587  6168  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:14.587  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.587  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.587  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.587  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:14.587  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:14.587  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:14.587  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.587  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2287f574 not in the list
,08-16 18:15:14.587  6168  6220 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-16 18:15:14.587  6168  6220 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-16 18:15:14.587  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 18:15:14.587  6168  6220 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-16 18:15:14.587  6168  6220 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 18:15:14.587  6168  6220 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-16 18:15:14.587  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 18:15:14.587  6168  6220 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-16 18:15:14.587  6168  6220 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 18:15:14.587  6168  6220 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 18:15:14.587  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 18:15:14.587  6168  6220 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-16 18:15:14.587  6168  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:14.587  6168  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:14.587  6168  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:14.587  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:14.587  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.587  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.587  6168  6220 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2340f947 not in the list
08-16 18:15:14.587  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.587  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2287f574 not in the list
08-16 18:15:14.587  6168  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:14.587  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.587  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.587  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.587  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release:, 1 listener(s) left
08-16 18:15:14.587  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:14.587  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:14.587  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.587  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2287f574 not in the list
,08-16 18:15:14.587  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:14.587  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.587  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.587  6168  6220 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2340f947 not in the list
08-16 18:15:14.587  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-16 18:15:14.587  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2287f574 not in the list
08-16 18:15:14.587  6168  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:14.587  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.587  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-16 18:15:14.587  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.597  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2287f574 not in the list
,08-16 18:15:14.597  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:14.597  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.597  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.597  6168  6220 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2340f947 not in the list
08-16 18:15:14.597  6168  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:14.597  6168  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:14.597  6168  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-16 18:15:14.597  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:14.597  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.597  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.597  6168  6220 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2340f947 not in the list
,08-16 18:15:14.597  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.597  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2287f574 not in the list
08-16 18:15:14.597  6168  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:14.597  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 18:15:14.597  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.597  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.597  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:14.597  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:14.597  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:14.597  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.597  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2287f574 not in the list
,08-16 18:15:14.597  6168  6220 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-16 18:15:14.597  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 18:15:14.597  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-16 18:15:14.597  6168  6220 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-16 18:15:14.597  6168  6220 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-16 18:15:14.597  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-16 18:15:14.597  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 18:15:14.597  6168  6168 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-16 18:15:14.597  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:14.597  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-16 18:15:14.597  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 18:15:14.597  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-16 18:15:14.597  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.597  6168  6220 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 18:15:14.597  6168  6220 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2340f947 not in the list
08-16 18:15:14.607  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.607  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 18:15:14.607  6168  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 18:15:14.607  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 18:15:14.607  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.607  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:14.607  6168  6168 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-16 18:15:14.607  6168  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 18:15:14.607  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2287f574 not in the list
08-16 18:15:14.607  6168  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:14.607  6168  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:14.607  6168  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:14.607  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:14.607  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.607  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.607  6168  6220 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2340f947 not in the list
08-16 18:15:14.607  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.607  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2287f574 not in the list
08-16 18:15:14.607  6168  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:14.607  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.607  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.607  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.607  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:14.607  6168  6168 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 18:15:14.607  6168  6168 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 18:15:14.607  6168  6168 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
08-16 18:15:14.607  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:14.607  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:14.607  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.607  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2287f574 not in the list
,08-16 18:15:14.607  6168  6220 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-16 18:15:14.607  6168  6220 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 18:15:14.607  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 18:15:14.607  6168  6220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 18:15:14.607  6168  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:14.607  6168  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:14.607  6168  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:14.607  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:14.607  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.607  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.607  6168  6220 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2340f947 not in the list
08-16 18:15:14.607  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.607  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2287f574 not in the list
08-16 18:15:14.607  6168  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:14.607  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.607  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:14.607  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.607  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.607  6168  6303 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 18:15:14.607  6168  6303 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-16 18:15:14.607  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:14.607  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:14.607  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.607  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2287f574 not in the list
08-16 18:15:14.607  6168  6168 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-16 18:15:14.617  6168  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:14.617  6168  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:14.617  6168  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:14.617  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:14.617  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.617  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.617  6168  6220 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2340f947 not in the list
08-16 18:15:14.617  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.617  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2287f574 not in the list
08-16 18:15:14.617  6168  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:14.617  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.617  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.617  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.617  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:14.617  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:14.617  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:14.617  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.617  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2287f574 not in the list
,08-16 18:15:14.617  6168  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:14.617  6168  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:14.617  6168  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:14.617  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:14.617  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.617  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.617  6168  6220 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2340f947 not in the list
08-16 18:15:14.617  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.617  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2287f574 not in the list
08-16 18:15:14.617  6168  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:14.617  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.617  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:14.617  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:14.617  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:14.617  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:14.617  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:14.617  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:14.617  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2287f574 not in the list
,08-16 18:15:14.617  1931  6286 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 18:15:14.617  6168  6220 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-16 18:15:14.617  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 18:15:14.617  6168  6220 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-16 18:15:14.617  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 18:15:14.617  6168  6220 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-16 18:15:14.617  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-16 18:15:14.617  1931  6286 I qtaguid : Tagging socket 73 with tag 1000310200000000{268448002,0} for uid 10012, pid: 1931, getuid(): 10012
,08-16 18:15:14.617  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 18:15:14.617  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-16 18:15:14.627  6168  6220 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-16 18:15:14.627  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 18:15:14.627  6168  6220 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-16 18:15:14.627  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 18:15:14.627  6168  6220 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-16 18:15:14.627  6168  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-16 18:15:14.627  6168  6220 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed,
08-16 18:15:14.627  6168  6220 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-16 18:15:14.627  6168  6220 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-16 18:15:14.627  6168  6220 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-16 18:15:14.627  6168  6220 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-16 18:15:14.627  6168  6220 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-16 18:15:14.627  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 18:15:14.627  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1befc336 added. We now have 2 listener(s)
08-16 18:15:14.627  6168  6220 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 18:15:14.627  6168  6220 D BluetoothAdapter: enable()
,08-16 18:15:14.627  6168  6220 D BluetoothAdapter: enable(): BT is already enabled..!
,08-16 18:15:14.627  1014  1491 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-16 18:15:14.627  1014  1491 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-16 18:15:14.627  1014  1491 D SecContentProvider2: mCursor = null
,08-16 18:15:14.637  1014  1491 D WifiService: setWifiEnabled: true pid=6168, uid=10155
,08-16 18:15:14.637  1014  1491 W ActivityManager: Permission Denial: getCurrentUser() from pid=6168, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,08-16 18:15:14.637  1014  1491 W WifiService: Failed getting userId using ActivityManagerNative
08-16 18:15:14.637  1014  1491 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6168, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-16 18:15:14.637  1014  1491 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-16 18:15:14.637  1014  1491 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-16 18:15:14.637  1014  1491 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-16 18:15:14.637  1014  1491 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-16 18:15:14.637  1014  1491 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-16 18:15:14.637  1014  1491 D SettingsProvider: name = wifi_on
,08-16 18:15:14.637  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:15:14.637  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2454c237 added. We now have 3 listener(s)
08-16 18:15:14.637  6168  6220 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 18:15:14.637  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 18:15:14.637  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@38cda3a4 added. We now have 4 listener(s)
,08-16 18:15:14.637  6168  6220 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 18:15:14.647  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 18:15:14.647  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c42d50d added. We now have 5 listener(s)
08-16 18:15:14.647  6168  6220 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 18:15:14.647  1014  1483 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-16 18:15:14.647  1014  1483 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-16 18:15:14.647  1014  1483 D SecContentProvider2: mCursor = null
,08-16 18:15:14.647  1014  1483 D WifiService: setWifiEnabled: false pid=6168, uid=10155
,08-16 18:15:14.647  1014  1483 D SettingsProvider: name = wifi_on
,08-16 18:15:14.657  1014  1123 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-16 18:15:14.657  2123  2123 I wpa_supplicant: reset timer : RESET_TIMER 0,
,08-16 18:15:14.657  2123  2123 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-16 18:15:14.657  2123  2123 I wpa_supplicant: P2P: Current p2p state = IDLE
08-16 18:15:14.657  2123  2123 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds,
08-16 18:15:14.657  6168  6220 D BluetoothAdapter: disable()
,08-16 18:15:14.667  1014  1123 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 18:15:14.667  1014  1345 D SettingsProvider: name = bluetooth_on,
,08-16 18:15:14.677  2651  2714 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-16 18:15:14.677  2651  2714 D BluetoothAdapterProperties: Setting state to 13
08-16 18:15:14.677  2651  2714 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 18:15:14.677  2651  2714 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 18:15:14.677  2651  2714 D BluetoothAdapterService: updateAdapterState state is 13
,08-16 18:15:14.677  1014  1123 E WifiNative-wlan0: do suspend true
,08-16 18:15:14.677  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 18:15:14.677  1014  3070 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:14.677  1014  3070 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-16 18:15:14.687  1014  3070 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:14.687  1014  3070 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:14.687  1014  3070 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:14.687  2651  2651 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-16 18:15:14.687  2651  2714 D BluetoothAdapterService: Autoconnection is available ,
08-16 18:15:14.687  2651  2714 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-16 18:15:14.687  2651  2651 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@25f542ca, channel: 19, state: LISTENING
08-16 18:15:14.687  2651  2714 D BluetoothAdapterService: terminating service from this receiver
,08-16 18:15:14.687  2651  2651 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@25f542ca, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3bda3772, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@16032c3bmSocket: android.net.LocalSocket@775ff58 impl:android.net.LocalSocketImpl@371ab8b1 fd:FileDescriptor[74]
08-16 18:15:14.687  2651  2651 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@775ff58 impl:android.net.LocalSocketImpl@371ab8b1 fd:FileDescriptor[74]
08-16 18:15:14.687  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-16 18:15:14.687  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:14.687  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:14.687  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 18:15:14.687  2651  2714 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 18:15:14.687  2651  2714 D BluetoothAdapterProperties: mDiscovering is false
08-16 18:15:14.687  1014  1555 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-16 18:15:14.687  2651  2714 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-16 18:15:14.697  1322  1322 D BluetoothPbap: Proxy object disconnected
08-16 18:15:14.697  1322  1322 D PbapServerProfile: Bluetooth service disconnected
,08-16 18:15:14.697  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:15:14.697  6168  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:15:14.697  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:14.697  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:14.697  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:14.697  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:15:14.697  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:14.697  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:15:14.697  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 18:15:14.697  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 18:15:14.697  6168  6220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:14.697  6168  6220 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 18:15:14.697  2651  2719 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-16 18:15:14.697  2651  2719 D BluetoothAdapterProperties: Scan Mode:20
,08-16 18:15:14.697  2651  2714 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-16 18:15:14.697  2651  2714 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-16 18:15:14.697  2651  2714 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-16 18:15:14.697  2651  2714 E bt-btif : cmd socket is not created
08-16 18:15:14.697  2651  2714 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-16 18:15:14.697  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:14.707  2651  4961 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-16 18:15:14.707  2651  2816 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
,08-16 18:15:14.707  2651  2816 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-16 18:15:14.707  2651  2816 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-16 18:15:14.707  2651  2816 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 18:15:14.707  2651  2816 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-16 18:15:14.707  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:14.737  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-16 18:15:14.737  1014  1014 I InputMethodManagerService: [BT Setting State] State =13
,08-16 18:15:14.737  6168  6168 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 18:15:14.747  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:14.747  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:14.747  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:14.747  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:14.747  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:15:14.747  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:14.747  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:15:14.747  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 18:15:14.747  6168  6168 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 18:15:14.747  6168  6168 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 18:15:14.747  1171  1171 D BluetoothTile:  onBluetoothStateChange:
08-16 18:15:14.747  1773  1773 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 18:15:14.747  1171  1171 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-16 18:15:14.757  1171  1171 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:14.757  2651  2651 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2ee5117, channel: 5, state: LISTENING
08-16 18:15:14.757  2651  2651 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2ee5117, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@cfa87c3, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2af7b904mSocket: android.net.LocalSocket@22f12eed impl:android.net.LocalSocketImpl@154b6122 fd:FileDescriptor[76]
08-16 18:15:14.757  2651  2651 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@22f12eed impl:android.net.LocalSocketImpl@154b6122 fd:FileDescriptor[76]
,08-16 18:15:14.757  1171  1171 D BluetoothTile:  getBluetoothState : 13
08-16 18:15:14.757  1322  1322 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:14.757  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:14.757  2651  2651 I BtOppRfcommListener: stopping Accept Thread
08-16 18:15:14.757  2651  2651 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@afce7b3, channel: 12, state: LISTENING
08-16 18:15:14.757  1171  1720 D BluetoothTile:  handleUpdatestate:false name:null
08-16 18:15:14.757  2651  2651 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@afce7b3, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2a846e35, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@23b96170mSocket: android.net.LocalSocket@3e3ecce9 impl:android.net.LocalSocketImpl@8626d6e fd:FileDescriptor[80]
08-16 18:15:14.757  2651  2651 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3e3ecce9 impl:android.net.LocalSocketImpl@8626d6e fd:FileDescriptor[80]
,08-16 18:15:14.757  2651  4961 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 18:15:14.757  1171  1720 D BluetoothTile:  handleUpdatestate:false name:null
08-16 18:15:14.757  1014  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 18:15:14.757  1171  1720 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-16 18:15:14.757  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-16 18:15:14.757  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:14.757  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:14.757  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:14.757  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:14.757  1014  1345 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 18:15:14.757  1014  1719 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-16 18:15:14.757  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:14.767  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-16 18:15:14.767  2651  2651 V BluetoothOppManager: cleanUp...
,08-16 18:15:14.767  1322  1322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-16 18:15:14.767  1014  1555 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-16 18:15:14.767  1014  1555 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-16 18:15:14.777  1014  1555 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:14.777  1014  1555 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:14.777  1014  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-16 18:15:14.787  1322  1322 D DockEventReceiver: finishStartingService: stopping service
,08-16 18:15:14.787  1322  1322 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 18:15:14.797  1171  1171 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:14.797  1171  1171 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-16 18:15:14.797  1014  1557 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-16 18:15:14.797  1014  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:14.797  1014  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:14.797  1014  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:14.797  1014  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:14.807  6310  6310 E Zygote  : MountEmulatedStorage()
,08-16 18:15:14.807  6310  6310 I libpersona: KNOX_SDCARD checking this for 10003
08-16 18:15:14.807  6310  6310 E Zygote  : v2
08-16 18:15:14.807  6310  6310 I libpersona: KNOX_SDCARD not a persona
08-16 18:15:14.817  1014  1557 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6310 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
08-16 18:15:14.817  6310  6310 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 18:15:14.817  6310  6310 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 18:15:14.817  6310  6310 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 18:15:14.857  6310  6310 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:14.857  6310  6310 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:14.897  6310  6310 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-16 18:15:14.907  2651  2816 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-16 18:15:14.907  2651  2816 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-16 18:15:14.907  2651  2816 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-16 18:15:14.907  2651  2816 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-16 18:15:14.907  2651  2816 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-16 18:15:14.907  2651  2816 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 18:15:14.907  2651  2816 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 18:15:14.907  2651  2816 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 18:15:14.907  2651  2816 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 18:15:14.907  2651  2816 W bt-btif : ag scb idx 1 not allocated
08-16 18:15:14.907  2651  2816 W bt-btif : ag scb idx 2 not allocated
08-16 18:15:14.907  2651  2816 E bt-btif : BTA AG is already disabled, ignoring ...
08-16 18:15:14.907  2651  2920 I bt_userial_mct: exiting userial_read_thread
08-16 18:15:14.907  2651  2920 D bt_userial_mct: Leaving userial_evt_read_thread()
08-16 18:15:14.907  2651  2719 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-16 18:15:14.907  2651  2818 I bt_vendor: hw_epilog_process
,08-16 18:15:14.907  2651  2719 D bt_userial_mct: userial_close
08-16 18:15:14.907  2651  2719 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-16 18:15:14.947  6310  6310 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-16 18:15:14.947  6310  6310 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
,08-16 18:15:14.947  6310  6310 D UserAnalysis: Create SecureDbHelper
,08-16 18:15:14.957  6310  6310 D IntelligenceServiceApplication: onCreate()
,08-16 18:15:14.957  1014  1026 I ActivityManager: Killing 5324:com.google.android.talk/u0a104 (adj 15): empty #31
,08-16 18:15:14.967  1014  1483 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-16 18:15:14.967  1014  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:14.967  1014  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:14.967  1014  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:14.967  1014  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:14.967  6310  6310 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-16 18:15:14.987  6329  6329 E Zygote  : MountEmulatedStorage()
08-16 18:15:14.987  1014  1483 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6329 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-16 18:15:14.987  6329  6329 E Zygote  : v2,
08-16 18:15:14.987  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-16 18:15:14.987  6329  6329 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-16 18:15:14.987  6329  6329 I libpersona: KNOX_SDCARD checking this for 10107
08-16 18:15:14.987  6310  6310 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-16 18:15:14.987  6329  6329 I libpersona: KNOX_SDCARD not a persona
,08-16 18:15:14.987  6329  6329 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 18:15:14.997  6329  6329 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-16 18:15:14.997  6310  6310 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-16 18:15:15.017  6329  6329 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:15.017  6329  6329 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:15.107  6168  6168 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 18:15:15.177  2651  2719 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-16 18:15:15.177  2651  2719 I bt_vendor: bluetooth satus is on
08-16 18:15:15.177  2651  2719 I bt_vendor: bt-vendor : resetting BT status
08-16 18:15:15.177  2651  2719 I bt_vendor: Starting hciattach daemon
,08-16 18:15:15.177  2651  2719 I bt_vendor: try to set false
,08-16 18:15:15.177  2651  2719 I bt_vendor: Starting hciattach daemon,
08-16 18:15:15.177  2651  2719 I bt_vendor: try to set false
,08-16 18:15:15.177  2651  2719 I bt_vendor: cleanup
,08-16 18:15:15.177  2651  2816 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-16 18:15:15.177  2651  2719 I GKI_LINUX: GKI_exit_task 0 done
08-16 18:15:15.177  2651  2719 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-16 18:15:15.187  2651  2714 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-16 18:15:15.187  2651  2714 D BtConfig.SecureMode: isSecureModeOn:false
,08-16 18:15:15.187  2651  2714 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,08-16 18:15:15.187  2651  2714 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-16 18:15:15.187  2651  2714 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-16 18:15:15.187  2651  2714 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-16 18:15:15.187  1014  1558 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 18:15:15.187  1014  1558 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-16 18:15:15.187  1014  1558 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:15.187  1014  1558 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:15.187  1014  1558 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:15.187  2651  2651 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 18:15:15.187  2651  2714 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-16 18:15:15.197  2651  2714 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-16 18:15:15.197  2651  2714 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-16 18:15:15.197  2651  2651 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 18:15:15.197  2651  2651 D BtGatt.GattService: stop()
08-16 18:15:15.197  2651  2651 D BtGatt.AdvertiseManager: advertise clients cleared
,08-16 18:15:15.197  1014  1359 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:15.197  1014  1359 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-16 18:15:15.197  1014  1359 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:15.197  1014  1359 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 18:15:15.197  1014  1359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:15.197  2651  2714 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-16 18:15:15.197  2651  2714 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-16 18:15:15.197  2651  2651 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2877fa98
,08-16 18:15:15.197  2651  2714 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-16 18:15:15.207  1014  1345 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-16 18:15:15.207  2651  2651 D HeadsetService: Received stop request...Stopping profile...
08-16 18:15:15.207  1014  1345 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0,
,08-16 18:15:15.207  1014  1345 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:15.207  1014  1345 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:15.207  1014  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 18:15:15.207  2651  2714 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-16 18:15:15.207  2651  2714 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 18:15:15.207  2651  2651 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2877fa98
08-16 18:15:15.207  2651  2714 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-16 18:15:15.207  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-16 18:15:15.207  1014  1359 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:15.207  1014  1359 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-16 18:15:15.217  1014  1359 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:15.217  1014  1359 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:15.217  1014  1359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:15.217  2651  2714 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-16 18:15:15.217  2651  2714 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-16 18:15:15.217  1322  1322 D HeadsetProfile: Bluetooth service disconnected
,08-16 18:15:15.217  2651  2714 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-16 18:15:15.217  1014  1557 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 18:15:15.217  1014  1557 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-16 18:15:15.217  1014  1557 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:15.217  1014  1557 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:15.217  1014  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 18:15:15.217  2651  2714 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-16 18:15:15.217  2651  2714 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-16 18:15:15.227  2651  2714 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-16 18:15:15.227  1014  3070 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:15.227  1014  3070 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 18:15:15.227  1014  3070 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:15.227  1014  3070 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:15.227  1014  3070 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:15.227  2651  2714 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-16 18:15:15.227  2651  2714 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-16 18:15:15.227  2651  2714 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-16 18:15:15.227  1014  1483 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:15.227  1014  1483 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-16 18:15:15.237  1014  1483 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:15.237  1014  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:15.237  1014  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:15.237  2651  2714 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-16 18:15:15.237  2651  2714 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-16 18:15:15.237  2651  2714 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-16 18:15:15.237  1014  1555 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 18:15:15.237  1014  1555 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-16 18:15:15.247  1014  1555 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:15.247  1014  1555 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:15.247  1014  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:15.247  2651  2714 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-16 18:15:15.247  2651  2714 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-16 18:15:15.247  2651  2714 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-16 18:15:15.247  2651  2714 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-16 18:15:15.247  2651  2714 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-16 18:15:15.247  2651  2714 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-16 18:15:15.247  2651  2714 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-16 18:15:15.247  2651  2714 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-16 18:15:15.247  2651  2714 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-16 18:15:15.247  2651  2714 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-16 18:15:15.247  2651  2714 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-16 18:15:15.247  2651  2714 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-16 18:15:15.247  2651  2714 D BluetoothAdapterState: Stopping profile services that were post enabled
08-16 18:15:15.247  2651  2651 E BluetoothAdapterService(678951576): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-16 18:15:15.247  2651  2651 D A2dpService: Received stop request...Stopping profile...
,08-16 18:15:15.257  2651  2753 D A2dpStateMachine: Exit Disconnected: -1
,08-16 18:15:15.257  2651  2651 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2877fa98
,08-16 18:15:15.257  1014  1014 D BluetoothA2dp: Proxy object disconnected
08-16 18:15:15.257  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-16 18:15:15.257  2651  2651 E BluetoothAdapterService(678951576): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-16 18:15:15.257  2651  2651 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 18:15:15.257  2651  2651 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-16 18:15:15.257  2864  2864 D BluetoothA2dp: Proxy object disconnected
,08-16 18:15:15.257  1322  1322 D BluetoothA2dp: Proxy object disconnected
08-16 18:15:15.257  1322  1322 D A2dpProfile: Bluetooth service disconnected
,08-16 18:15:15.257  2651  2651 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-16 18:15:15.257  2651  2651 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-16 18:15:15.267  2651  2651 D HidService: Received stop request...Stopping profile...
,08-16 18:15:15.267  2651  2651 D HidService: Stopping Bluetooth HidService
08-16 18:15:15.267  2651  2651 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-16 18:15:15.267  2651  2651 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-16 18:15:15.267  2651  2651 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-16 18:15:15.267  2651  2651 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2877fa98
,08-16 18:15:15.267  2651  2651 D HealthService: Received stop request...Stopping profile...
,08-16 18:15:15.267  2651  2651 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2877fa98
,08-16 18:15:15.277  2651  2651 D PanService: Received stop request...Stopping profile...
,08-16 18:15:15.277  2651  2651 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2877fa98
,08-16 18:15:15.277  1014  1014 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 18:15:15.277  2651  2651 D BluetoothMapService: Received stop request...Stopping profile...
,08-16 18:15:15.277  1322  1322 D BluetoothInputDevice: Proxy object disconnected
,08-16 18:15:15.277  1322  1322 D HidProfile: Bluetooth service disconnected
,08-16 18:15:15.277  2651  2651 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2877fa98
,08-16 18:15:15.277  2651  2651 D SapService: Received stop request...Stopping profile...
08-16 18:15:15.277  1322  1322 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 18:15:15.277  1322  1322 D PanProfile: Bluetooth service disconnected
08-16 18:15:15.287  2651  2651 D SapService: Stopping Bluetooth SapService
08-16 18:15:15.287  2651  2651 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2877fa98
08-16 18:15:15.287  1322  1322 D BluetoothMap: Proxy object disconnected
,08-16 18:15:15.287  2651  2651 E BluetoothAdapterService(678951576): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-16 18:15:15.287  2651  2651 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 18:15:15.287  2651  2651 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-16 18:15:15.287  2651  2651 D BluetoothA2dp: Proxy object disconnected
08-16 18:15:15.287  2651  2651 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-16 18:15:15.287  2651  2754 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-16 18:15:15.287  2651  2651 I GKI_LINUX: GKI_exit_task 2 done
08-16 18:15:15.287  2651  2651 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-16 18:15:15.287  1322  1322 D MapProfile: Bluetooth service disconnected
08-16 18:15:15.287  2651  2651 E BluetoothAdapterService(678951576): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-16 18:15:15.287  2651  2651 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 18:15:15.287  2651  2651 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-16 18:15:15.287  2651  2651 E BluetoothAdapterService(678951576): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-16 18:15:15.287  2651  2651 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 18:15:15.287  2651  2651 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-16 18:15:15.287  2651  2651 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-16 18:15:15.287  2651  2651 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-16 18:15:15.287  2651  2651 E BluetoothAdapterService(678951576): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-16 18:15:15.287  2651  2651 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 18:15:15.287  2651  2651 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-16 18:15:15.287  2651  2651 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 18:15:15.287  2651  2651 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 18:15:15.287  1322  1322 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-16 18:15:15.287  1322  1322 D SapProfile: Bluetooth service disconnected
,08-16 18:15:15.287  2651  2651 E BluetoothAdapterService(678951576): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-16 18:15:15.287  2651  2651 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-16 18:15:15.287  2651  2651 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-16 18:15:15.287  2651  2651 E BluetoothAdapterService(678951576): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-16 18:15:15.287  2651  2651 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-16 18:15:15.287  2651  2651 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-16 18:15:15.287  2651  2714 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-16 18:15:15.287  2651  2714 D BluetoothAdapterProperties: Setting state to 10
08-16 18:15:15.287  2651  2714 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-16 18:15:15.287  2651  2714 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 18:15:15.287  2651  2714 D BluetoothAdapterService: updateAdapterState state is 10
,08-16 18:15:15.287  2651  2714 D BluetoothAdapterService: Autoconnection is available 
08-16 18:15:15.287  2651  2714 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-16 18:15:15.287  2651  2714 I BluetoothAdapterState: Entering OffState
,08-16 18:15:15.297  1322  1331 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 18:15:15.297  2651  6306 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 18:15:15.297  2651  6306 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-16 18:15:15.297  1014  1044 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 18:15:15.297  1322  1333 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-16 18:15:15.297  2651  2662 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 18:15:15.297  1322  1331 D BluetoothMap: onBluetoothStateChange: up=false
,08-16 18:15:15.297  1322  1333 D Bluetoothsap: onBluetoothStateChange: up=false
08-16 18:15:15.297  1322  1333 D Bluetoothsap: Unbinding service...
08-16 18:15:15.297  1014  1044 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 18:15:15.297  1014  1044 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 18:15:15.307  1014  1133 D ActivityManager: bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
08-16 18:15:15.307  1014  1133 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-16 18:15:15.307  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:15.307  1014  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:15.307  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-16 18:15:15.307  1439  1458 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 18:15:15.307  1439  1458 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 18:15:15.307  6168  6178 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 18:15:15.307  6168  6178 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-16 18:15:15.307  6168  6178 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-16 18:15:15.307  6168  6178 D BluetoothLeAdvertiser: Exit stop advertising
08-16 18:15:15.307  6168  6178 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-16 18:15:15.307  6168  6178 D BluetoothLeScanner: Exiting stopAllScan
,08-16 18:15:15.307  2864  2882 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 18:15:15.307  2864  2882 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 18:15:15.307  1322  1333 D BluetoothPbap: onBluetoothStateChange: up=false
,08-16 18:15:15.317  1454  1469 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 18:15:15.317  1454  1469 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-16 18:15:15.317  2864  2873 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 18:15:15.317  1931  1946 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 18:15:15.317  1931  1946 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 18:15:15.317  1430  1443 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 18:15:15.317  1430  1443 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 18:15:15.317  1322  1333 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 18:15:15.317  1322  1333 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 18:15:15.317  1171  1928 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 18:15:15.327  1171  1928 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 18:15:15.327  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-16 18:15:15.327  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-16 18:15:15.337  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:15.337  1014  1014 I InputMethodManagerService: [BT Setting State] State =10
08-16 18:15:15.337  1014  1014 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
08-16 18:15:15.337  2651  2719 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-16 18:15:15.337  2651  2651 I GKI_LINUX: GKI_exit_task 1 done
08-16 18:15:15.337  2651  2651 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-16 18:15:15.337  2651  2651 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-16 18:15:15.337  2651  2651 I art     : System.exit called, status: 0
08-16 18:15:15.337  2651  2651 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-16 18:15:15.337  1171  1171 D BluetoothAdapter: 224888337: getState() :  mService = null. Returning STATE_OFF
,08-16 18:15:15.337  1171  1171 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-16 18:15:15.347  1171  1720 D BluetoothAdapter: 224888337: getState() :  mService = null. Returning STATE_OFF
,08-16 18:15:15.347  1171  1171 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:15.347  1171  1171 D BluetoothTile:  getBluetoothState : 10
08-16 18:15:15.347  1171  1720 D BluetoothAdapter: 224888337: getState() :  mService = null. Returning STATE_OFF
,08-16 18:15:15.347  1171  1171 D BluetoothAdapter: 224888337: getState() :  mService = null. Returning STATE_OFF
08-16 18:15:15.347  1171  1171 D BluetoothAdapter: 224888337: getState() :  mService = null. Returning STATE_OFF
,08-16 18:15:15.347  1014  1719 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 18:15:15.347  1014  1133 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-16 18:15:15.347  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-16 18:15:15.347  1322  1322 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 18:15:15.347  1014  1026 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 18:15:15.347  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-16 18:15:15.347  1931  2109 D BluetoothAdapter: 107551660: getState() :  mService = null. Returning STATE_OFF
08-16 18:15:15.347  1931  2109 D BluetoothAdapter: 107551660: getState() :  mService = null. Returning STATE_OFF
,08-16 18:15:15.347  1773  1773 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 18:15:15.347  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:15.347  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:15.347  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:15.357  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:15.357  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:15.367  6329  6329 D StrictMode: StrictMode policy violation; ~duration=287 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 18:15:15.367  6329  6329 D StrictMode: StrictMode policy violation; ~duration=278 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.g,mm.base.app.a.a(PG:1211)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 18:15:15.367  6329  6329 D StrictMode: StrictMode policy violation; ~duration=205 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at java.io.File.exists(File.java:363)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.ActivityTh,read.main(ActivityThread.java:6145)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 18:15:15.367  6329  6329 D StrictMode: StrictMode policy violation; ~duration=205 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 18:15:15.367  6329  6329 D StrictMode: StrictMode policy violation; ~duration=204 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 18:15:15.367  6329  6329 D StrictMode: StrictMode policy violation; ~duration=202 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.r.k.c(PG:1187)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.r.v.a(PG:1206)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.r.y.a(PG:2233)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.r.e.b(PG:170)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.r.e.b(PG:13188)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 18:15:15.367  6329  6329 D StrictMode: StrictMode policy violation; ~duration=199 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.r.k.c(PG:1187)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.r.k.b(PG:14147)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.r.k.c(PG:583)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.r.v.a(PG:1206)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.r.y.a(PG:2233)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.r.e.b(PG:170)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.r.e.b(PG:13188)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 18:15:15.367  6329  6329 D StrictMode: StrictMode policy violation; ~duration=154 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at java.io.File.exists(File.java:363)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 18:15:15.367  6329  6329 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 18:15:15.377  1931  1931 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-16 18:15:15.377  1014  1359 I ActivityManager: Killing 4998:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
08-16 18:15:15.387  1931  1931 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-16 18:15:15.387  1014  1558 I ActivityManager: Process com.android.bluetooth (pid 2651)(adj 0) has died(47,1087)
08-16 18:15:15.397  1322  1322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-16 18:15:15.397  1014  1719 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-16 18:15:15.397  1014  1719 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-16 18:15:15.397  1014  1719 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:15.397  1014  1719 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:15.397  1014  1719 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-16 18:15:15.407  1322  1322 D DockEventReceiver: finishStartingService: stopping service
08-16 18:15:15.407  1322  1322 D BluetoothNotiBroadcastReceiver: onReceive
08-16 18:15:15.407  1171  1171 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:15.407  1171  1171 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
08-16 18:15:15.417  1014  1345 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
08-16 18:15:15.417  1014  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:15.417  1014  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:15.417  1014  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:15.417  1014  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:15.427  6329  6346 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-16 18:15:15.427   318   318 I ServiceManager: Waiting for service AtCmdFwd...
08-16 18:15:15.427  6360  6360 E Zygote  : MountEmulatedStorage()
08-16 18:15:15.437  6360  6360 E Zygote  : v2
08-16 18:15:15.437  6360  6360 I libpersona: KNOX_SDCARD checking this for 1002
08-16 18:15:15.437  6360  6360 I libpersona: KNOX_SDCARD not a persona
08-16 18:15:15.437  6360  6360 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-16 18:15:15.437  6360  6360 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-16 18:15:15.437  1014  1345 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6360 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
08-16 18:15:15.437  6360  6360 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-16 18:15:15.447  1014  1557 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 18:15:15.447  1014  1557 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:15.447  1014  1557 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:15.447  1014  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-16 18:15:15.467  6360  6360 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:15.467  6360  6360 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:15.477  1014  1122 D WifiP2pService: InactiveState{ what=143375 }
,08-16 18:15:15.477  1014  1122 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-16 18:15:15.477   276   978 D CommandListener: Clearing all IP addresses on wlan0
,08-16 18:15:15.487  1014  1122 D WifiP2pService: InactiveState{ what=131204 }
08-16 18:15:15.487  1171  1171 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 18:15:15.487  1014  1122 D WifiP2pService: P2pEnabledState{ what=131204 }
08-16 18:15:15.487  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-16 18:15:15.487  1014  1125 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 18:15:15.487  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:15.487  1014  1125 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
08-16 18:15:15.487  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:15.487  1014  1122 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-16 18:15:15.487  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:15.487  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:15.487  1931  6286 I qtaguid : Untagging socket 73
08-16 18:15:15.487  1931  4544 V NativeCrypto: Read error: ssl=0xb8310508: I/O error during system call, Connection timed out
08-16 18:15:15.487  1014  1125 E ConnectivityService: updateNetworkInfo()
08-16 18:15:15.487  1014  1125 E ConnectivityService: updateNetworkInfo()
,08-16 18:15:15.487  1014  1123 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 18:15:15.487  1931  6286 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-16 18:15:15.487  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-16 18:15:15.497  1931  4544 V NativeCrypto: SSL shutdown failed: ssl=0xb8310508: I/O error during system call, Broken pipe
08-16 18:15:15.497  1931  4544 E GCM     : Wifi connection closed with errorCode 20
,08-16 18:15:15.497  1014  2260 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:15.497  1014  1555 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
08-16 18:15:15.497  1014  2260 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 18:15:15.497  1014  2260 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation,
08-16 18:15:15.497  1014  2260 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:15.497  1014  2260 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
08-16 18:15:15.497  1014  2260 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 18:15:15.497  1014  2260 I qtaguid : Tagging socket 358 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1014, getuid(): 1000
08-16 18:15:15.497  1014  2260 I qtaguid : Untagging socket 358
08-16 18:15:15.497  1014  2260 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 18:15:15.507  6360  6360 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-16 18:15:15.507  6360  6360 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-16 18:15:15.507  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 1
,08-16 18:15:15.507  1014  1148 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:15.507  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 18:15:15.507  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 18:15:15.507  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:15.517  1014  1014 D RttService: SCAN_AVAILABLE : 1
08-16 18:15:15.517  1014  1149 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 18:15:15.517  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:15.517  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:15.517  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:15.517  1014  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:15:15.517  1014  1045 D WifiDisplayAdapter: onP2pDisconnected
08-16 18:15:15.517  1014  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-16 18:15:15.517  1014  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-16 18:15:15.537  6360  6360 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink,
,08-16 18:15:15.537  1014  1122 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-16 18:15:15.537  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED,
08-16 18:15:15.537  1014  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false,
08-16 18:15:15.537  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 18:15:15.537  1014  1045 D WifiDisplayController: disconnect
08-16 18:15:15.537  1014  1045 D WifiDisplayController: updateConnection
08-16 18:15:15.537  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 18:15:15.537  1014  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-16 18:15:15.537  1014  1122 D WifiP2pService: P2pDisablingState,
08-16 18:15:15.537  1014  1122 D WifiP2pService: P2pDisablingState{ what=147458 }
08-16 18:15:15.537  1014  1122 D WifiP2pService: p2p socket connection lost
,08-16 18:15:15.537  1014  1122 D WifiP2pService: P2pDisabledState
,08-16 18:15:15.547  1014  1123 E WifiNative-wlan0: do suspend true
08-16 18:15:15.547  1014  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,08-16 18:15:15.547  1014  1045 D WifiDisplayAdapter: onP2pDisconnected,
08-16 18:15:15.547  1014  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-16 18:15:15.547  1014  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
08-16 18:15:15.547  1171  1171 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-16 18:15:15.547  1014  1557 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-16 18:15:15.547  1171  1171 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-16 18:15:15.567  6360  6360 D BtSettings.ProfileConfig: Adding GattService
,08-16 18:15:15.567  6360  6360 D BtSettings.ProfileConfig: Adding HeadsetService
,08-16 18:15:15.567  6360  6360 D BtSettings.ProfileConfig: Adding A2dpService
08-16 18:15:15.567  6360  6360 D BtSettings.ProfileConfig: Adding HidService
08-16 18:15:15.567  6360  6360 D BtSettings.ProfileConfig: Adding HealthService
,08-16 18:15:15.567  6360  6360 D BtSettings.ProfileConfig: Adding PanService
08-16 18:15:15.567  6360  6360 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-16 18:15:15.567  6360  6360 D BtSettings.ProfileConfig: Adding SapService
08-16 18:15:15.567  6360  6360 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-16 18:15:15.567  6360  6360 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-16 18:15:15.567  6360  6360 D BtSettings.ProfileConfig: Adding SapClientService
08-16 18:15:15.567  6360  6360 D BtSettings.ProfileConfig: Adding HidDevService
,08-16 18:15:15.567  6360  6360 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-16 18:15:15.577  1014  1558 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-16 18:15:15.577  1014  1558 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 18:15:15.577  1014  1558 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 18:15:15.577  1014  1558 D SettingsProvider: selectionArgs: false
08-16 18:15:15.577  1014  1558 D SettingsProvider: selectionArgs: 1002
08-16 18:15:15.577  1014  1558 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 18:15:15.577  1014  1558 D SettingsProvider: ret = -1
08-16 18:15:15.577  1014  1359 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,08-16 18:15:15.577  1014  1359 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 18:15:15.577  1014  1359 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 18:15:15.577  1014  1359 D SettingsProvider: selectionArgs: false
08-16 18:15:15.577  1014  1359 D SettingsProvider: selectionArgs: 1002
08-16 18:15:15.577  1014  1359 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 18:15:15.577  1014  1359 D SettingsProvider: ret = -1
,08-16 18:15:15.577  1014  1555 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,08-16 18:15:15.577  1014  1555 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-16 18:15:15.577  1014  1555 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 18:15:15.577  1014  1555 D SettingsProvider: selectionArgs: false
08-16 18:15:15.577  1014  1555 D SettingsProvider: selectionArgs: 1002
08-16 18:15:15.577  1014  1555 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-16 18:15:15.577  1014  1555 D SettingsProvider: ret = -1
,08-16 18:15:15.577  1014  1345 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-16 18:15:15.577  1014  1345 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 18:15:15.577  1014  1345 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 18:15:15.577  1014  1345 D SettingsProvider: selectionArgs: false
,08-16 18:15:15.577  1014  1345 D SettingsProvider: selectionArgs: 1002
08-16 18:15:15.577  1014  1345 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 18:15:15.577  1014  1345 D SettingsProvider: ret = -1
08-16 18:15:15.577  1014  1491 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-16 18:15:15.577  1014  1491 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 18:15:15.577  1014  1491 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 18:15:15.577  1014  1491 D SettingsProvider: selectionArgs: false
,08-16 18:15:15.577  1014  1491 D SettingsProvider: selectionArgs: 1002
08-16 18:15:15.577  1014  1491 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 18:15:15.577  1014  1491 D SettingsProvider: ret = -1
,08-16 18:15:15.577  1014  3070 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-16 18:15:15.577  1014  3070 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 18:15:15.577  1014  3070 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 18:15:15.577  1014  3070 D SettingsProvider: selectionArgs: false,
08-16 18:15:15.577  1014  3070 D SettingsProvider: selectionArgs: 1002
08-16 18:15:15.577  1014  3070 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 18:15:15.577  1014  3070 D SettingsProvider: ret = -1
08-16 18:15:15.577  1014  1026 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-16 18:15:15.577  1014  1026 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 18:15:15.577  1014  1026 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 18:15:15.577  1014  1026 D SettingsProvider: selectionArgs: false
08-16 18:15:15.577  1014  1026 D SettingsProvider: selectionArgs: 1002
,08-16 18:15:15.577  1014  1026 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 18:15:15.577  1014  1026 D SettingsProvider: ret = -1
08-16 18:15:15.577  1014  1215 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-16 18:15:15.587  1014  1215 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 18:15:15.587  1014  1215 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 18:15:15.587  1014  1215 D SettingsProvider: selectionArgs: false
08-16 18:15:15.587  1014  1215 D SettingsProvider: selectionArgs: 1002
08-16 18:15:15.587  1014  1215 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
08-16 18:15:15.587  1014  1215 D SettingsProvider: ret = -1
08-16 18:15:15.587  1014  1215 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-16 18:15:15.587  1014  1215 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 18:15:15.587  1014  1215 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-16 18:15:15.587  1014  1215 D SettingsProvider: selectionArgs: false
,08-16 18:15:15.587  1014  1215 D SettingsProvider: selectionArgs: 1002
,08-16 18:15:15.587  1014  1215 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 18:15:15.587  1014  1215 D SettingsProvider: ret = -1
,08-16 18:15:15.587  1014  1719 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-16 18:15:15.587  1014  1719 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 18:15:15.587  1014  1719 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 18:15:15.587  1014  1719 D SettingsProvider: selectionArgs: false
08-16 18:15:15.587  1014  1719 D SettingsProvider: selectionArgs: 1002,
08-16 18:15:15.587  1014  1719 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 18:15:15.587  1014  1719 D SettingsProvider: ret = -1
08-16 18:15:15.587  1014  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-16 18:15:15.587  1014  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-16 18:15:15.587  1014  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 18:15:15.587  1014  1027 D SettingsProvider: selectionArgs: false
08-16 18:15:15.587  1014  1027 D SettingsProvider: selectionArgs: 1002
08-16 18:15:15.587  1014  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-16 18:15:15.587  1014  1027 D SettingsProvider: ret = -1
08-16 18:15:15.587  1014  1483 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-16 18:15:15.587  1014  1483 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 18:15:15.587  1014  1483 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 18:15:15.587  1014  1483 D SettingsProvider: selectionArgs: false
,08-16 18:15:15.587  1014  1483 D SettingsProvider: selectionArgs: 1002
08-16 18:15:15.587  1014  1483 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 18:15:15.587  1014  1483 D SettingsProvider: ret = -1
,08-16 18:15:15.597  1014  1133 I ActivityManager: Killing 5500:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,08-16 18:15:15.597  1931  1931 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-16 18:15:15.597  1014  1491 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 18:15:15.597  1014  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-16 18:15:15.607  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:15.607  1014  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:15.607  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:15.607  1931  6380 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-16 18:15:15.607  1931  1931 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-16 18:15:15.617  1014  3070 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 18:15:15.617  1014  3070 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:15.617  1014  3070 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 18:15:15.617  1014  3070 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:15.627  1014  1483 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 18:15:15.627  1014  1483 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 18:15:15.627  1014  1483 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:15.627  1014  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:15.627  1014  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 18:15:15.627  3616  3616 I Hs20UtilService: Starting #8
,08-16 18:15:15.627  3616  3649 I Hs20UtilService: Message received 5007
,08-16 18:15:15.637  1322  1322 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-16 18:15:15.637  1322  1322 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-16 18:15:15.637  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-16 18:15:15.637  1014  1345 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 18:15:15.637  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
08-16 18:15:15.637  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 18:15:15.637  1322  1322 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-16 18:15:15.637  1322  3077 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 18:15:15.637  1014  1345 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:15.637  1014  1345 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:15.637  1014  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:15.647  1931  6380 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-16 18:15:15.657  1322  1322 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-16 18:15:15.657  1322  1322 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 18:15:15.657  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 18:15:15.657  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
08-16 18:15:15.657  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 18:15:15.657  1322  1322 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-16 18:15:15.657  1322  3077 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 18:15:15.657  1014  1491 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-16 18:15:15.657  1014  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:15.657  1014  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:15.657  1014  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:15.657  1014  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:15.667  6381  6381 E Zygote  : MountEmulatedStorage()
,08-16 18:15:15.667  6381  6381 E Zygote  : v2
08-16 18:15:15.667  6381  6381 I libpersona: KNOX_SDCARD checking this for 10068
08-16 18:15:15.667  6381  6381 I libpersona: KNOX_SDCARD not a persona
,08-16 18:15:15.677  1014  1491 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6381 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 18:15:15.677  6381  6381 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-16 18:15:15.677  6381  6381 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-16 18:15:15.677  6381  6381 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 18:15:15.717  6381  6381 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:15.717  6381  6381 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:15.737  6381  6381 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-16 18:15:15.747  6381  6381 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 18:15:15.747  6381  6381 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-16 18:15:15.777  6381  6381 D FileShare-Client: Outbound.stopDelayTimer - 
,08-16 18:15:15.777  1014  1558 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-16 18:15:15.777  1014  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:15.777  1014  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:15.777  1014  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:15.777  1014  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:15.787  1014  3070 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-16 18:15:15.787  1014  3070 D BatteryService: level:91, scale:100, status:2, health:2, present:true, voltage: 4151, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-16 18:15:15.787  1014  3070 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-16 18:15:15.787  1014  3070 D BatteryService: stay LED for charging
08-16 18:15:15.787  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-16 18:15:15.797  1014  1558 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6398 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 18:15:15.797  6398  6398 E Zygote  : MountEmulatedStorage()
,08-16 18:15:15.797  6398  6398 E Zygote  : v2
08-16 18:15:15.797  6398  6398 I libpersona: KNOX_SDCARD checking this for 10069
08-16 18:15:15.797  6398  6398 I libpersona: KNOX_SDCARD not a persona
,08-16 18:15:15.797  1014  1014 I MotionRecognitionService: Plugged
08-16 18:15:15.797  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,08-16 18:15:15.797  6398  6398 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-16 18:15:15.797  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-16 18:15:15.797  1171  1171 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-16 18:15:15.797  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 91
08-16 18:15:15.797  1171  1171 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-16 18:15:15.807  6398  6398 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 18:15:15.807  6398  6398 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 18:15:15.817  6398  6398 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:15.817  6398  6398 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:15.827  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:91 status:2 health:2
08-16 18:15:15.827  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:91 status:2 health:2
08-16 18:15:15.827  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:91 status:2 health:2
,08-16 18:15:15.837  6398  6398 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 18:15:15.847  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:15.847  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:15.847  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
08-16 18:15:15.847  1014  1026 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-16 18:15:15.847  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:15.847  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:15.847  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:15.847  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:15.857  6413  6413 E Zygote  : MountEmulatedStorage(),
08-16 18:15:15.857  6413  6413 E Zygote  : v2
08-16 18:15:15.857  6413  6413 I libpersona: KNOX_SDCARD checking this for 10104
08-16 18:15:15.857  6413  6413 I libpersona: KNOX_SDCARD not a persona,
08-16 18:15:15.857  6413  6413 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 18:15:15.867  1014  1026 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6413 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a,
08-16 18:15:15.867  6413  6413 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 18:15:15.867  6413  6413 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,08-16 18:15:15.867  1014  1026 I ActivityManager: Killing 5588:com.google.android.apps.plus/u0a120 (adj 15): empty #31
,08-16 18:15:15.887  6413  6413 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:15.887  6413  6413 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:15.907  6413  6413 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-16 18:15:16.087  6413  6436 I Babel   : MmsConfig: mnc/mcc: 0/0
,08-16 18:15:16.087  6413  6436 I Babel   : MmsConfig.loadMmsSettings
,08-16 18:15:16.087  6413  6436 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,08-16 18:15:16.087  6413  6436 I Babel   : MmsConfig.loadFromDatabase
,08-16 18:15:16.107  6413  6436 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-16 18:15:16.107  6413  6436 I Babel   : MmsConfig.loadFromResources
,08-16 18:15:16.107  1014  1345 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-16 18:15:16.107  6413  6436 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-16 18:15:16.107  1014  1345 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-16 18:15:16.117  6413  6436 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,08-16 18:15:16.117  1014  1345 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:16.117  1014  1345 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:16.117  1014  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-16 18:15:16.117  6413  6413 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 18:15:16.157  6413  6413 I Babel_StickerModule: App launched.
,08-16 18:15:16.177   281  1012 W QCamera2Factory: getCameraInfo: E, camera_id = 0
,08-16 18:15:16.177   281  1012 W QCamera2Factory: getCameraInfo: X
,08-16 18:15:16.177   281   281 W QCamera2Factory: getCameraInfo: E, camera_id = 1
,08-16 18:15:16.177   281   281 W QCamera2Factory: getCameraInfo: X
,08-16 18:15:16.197  6413  6413 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 18:15:16.197  6413  6413 W AudioCapabilities: Unsupported mime audio/evrc
,08-16 18:15:16.197  6413  6413 W AudioCapabilities: Unsupported mime audio/qcelp
,08-16 18:15:16.207  6413  6413 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-16 18:15:16.207  6413  6413 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-16 18:15:16.207  6413  6413 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-16 18:15:16.207  6413  6413 W AudioCapabilities: Unsupported mime audio/x-ima
,08-16 18:15:16.207  6413  6413 W AudioCapabilities: Unsupported mime audio/qcelp
,08-16 18:15:16.207  6413  6413 W AudioCapabilities: Unsupported mime audio/evrc
,08-16 18:15:16.217  6413  6413 W VideoCapabilities: Unsupported mime video/wvc1
,08-16 18:15:16.217  6413  6413 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-16 18:15:16.227  6413  6413 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-16 18:15:16.237  6413  6413 W VideoCapabilities: Unsupported mime video/wvc1
,08-16 18:15:16.237  6413  6413 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-16 18:15:16.237  6413  6413 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-16 18:15:16.237  6413  6413 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-16 18:15:16.237  6413  6413 W VideoCapabilities: Unsupported mime video/mp43
,08-16 18:15:16.237  6413  6413 W VideoCapabilities: Unsupported mime video/sorenson
,08-16 18:15:16.247  6413  6413 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-16 18:15:16.267  6413  6413 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-16 18:15:16.297  1014  1133 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
08-16 18:15:16.297  1014  1133 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,08-16 18:15:16.297  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:16.297  1014  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:16.297  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-16 18:15:16.297  1014  1215 I ActivityManager: Killing 5746:com.sec.pcw.device/1000 (adj 15): empty #31
,08-16 18:15:16.347  1014  1122 D WifiP2pService: P2pDisabledState{ what=143375 },
08-16 18:15:16.347  1014  1122 D WifiP2pService: DefaultState{ what=143375 }
,08-16 18:15:16.357   276   974 D EnterpriseController: uids 10012
,08-16 18:15:16.357   276   974 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-16 18:15:16.357   276   974 D Netd    : getNetworkForDns: using netid 0 for uid 10012
08-16 18:15:16.357  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
,08-16 18:15:16.357  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
08-16 18:15:16.357   276   974 D EnterpriseController: uids 1000
08-16 18:15:16.357  1014  1125 E NetdConnector: NDC Command {53 network destroy 502} took too long (866ms)
08-16 18:15:16.357   276   974 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-16 18:15:16.357  1014  1125 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-16 18:15:16.357   276   974 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-16 18:15:16.357  1014  1125 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
08-16 18:15:16.357  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:16.357  1014  1125 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-16 18:15:16.357  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:16.357  1014  1125 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-16 18:15:16.357  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:16.357  1014  1125 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,08-16 18:15:16.357  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:16.357  1014  1125 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 18:15:16.357   276   978 D CommandListener: Clearing all IP addresses on wlan0
08-16 18:15:16.367  1014  1120 V NetworkStats: updateIfacesLocked()
08-16 18:15:16.357  1931  1931 E ctxmgr  : [BaseServerTask]Server task (WriteInterestRecordTask) got error response.
,08-16 18:15:16.367  1014  1120 V NetworkStats: performPollLocked(flags=0x1)
08-16 18:15:16.357  1171  1712 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-16 18:15:16.367  1014  1125 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 18:15:16.357  1454  1454 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-16 18:15:16.357  1454  1454 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 18:15:16.357  3812  6230 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-16 18:15:16.357  1014  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-16 18:15:16.357  1014  1122 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-16 18:15:16.357  1014  2260 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-16 18:15:16.357  1014  2260 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-16 18:15:16.357  1014  2260 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:16.357  1014  1014 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-16 18:15:16.357  1014  1128 D Tethering: MasterInitialState.processMessage what=3
,08-16 18:15:16.367  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:16.367  1014  1125 D ConnectivityService: nai.networkMonitor.doQuit()
08-16 18:15:16.367  1014  1125 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-16 18:15:16.367  1014  1125 E ConnectivityService: updateNetworkInfo()
08-16 18:15:16.367  1014  1120 V NetworkStats: performPollLocked() took 4ms
08-16 18:15:16.367  1014  1125 E ConnectivityService: updateNetworkInfo()
,08-16 18:15:16.367  1931  2117 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = -1
08-16 18:15:16.367  1014  1120 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 18:15:16.367  1014  1120 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-16 18:15:16.367  1014  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-16 18:15:16.367  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:16.367  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:16.367  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:16.367  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:16.367  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:16.367  1014  1121 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,08-16 18:15:16.367  2123  2123 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-16 18:15:16.367  1171  1171 D StatusBar.NetworkController: EthernetConnected: false
08-16 18:15:16.367  1171  1171 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-16 18:15:16.367  1171  1171 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-16 18:15:16.367  1171  1171 D StatusBar.NetworkController: updateDataNetType()
08-16 18:15:16.367  1171  1171 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-16 18:15:16.367  1171  1171 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-16 18:15:16.377  1171  1171 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-16 18:15:16.377  1171  1171 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,08-16 18:15:16.377  1171  1171 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-16 18:15:16.377  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 18:15:16.377  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 18:15:16.377  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:16.377  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:16.377  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:16.377  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:16.377  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-16 18:15:16.387  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 18:15:16.387  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 18:15:16.387  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:16.387  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:16.387  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:16.387  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:16.387  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:16.387  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:16.387  1014  1123 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-16 18:15:16.387  1014  1123 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 18:15:16.387  1014  1123 D SecContentProvider2: mCursor = null
,08-16 18:15:16.397  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 18:15:16.397  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-16 18:15:16.397  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:16.397  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:16.397  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:16.397  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:16.397  1171  1171 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-16 18:15:16.397  1171  1171 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-16 18:15:16.397  1171  1171 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-16 18:15:16.397  1171  1171 D HotspotTile: onReceive : 0, 0
08-16 18:15:16.397  1171  1720 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-16 18:15:16.407  1322  1322 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
08-16 18:15:16.407  6168  6168 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-16 18:15:16.407  1014  1133 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 18:15:16.407  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:16.407  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:16.407  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:16.407  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:15:16.407  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:15:16.407  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:16.407  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:16.407  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:15:16.407  1014  1133 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-16 18:15:16.407  6168  6168 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:15:16.407  6168  6168 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:15:16.407  6168  6168 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:15:16.407  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
,08-16 18:15:16.407  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:16.407  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:16.407  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:15:16.407  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:15:16.407  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:16.407  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:16.407  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 18:15:16.407  6168  6168 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:15:16.407  6168  6168 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 18:15:16.407  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:16.407  1014  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:16.407  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 18:15:16.407  3616  3616 I Hs20UtilService: Starting #9
,08-16 18:15:16.407  3616  3649 I Hs20UtilService: Message received 5007
,08-16 18:15:16.417  1322  1322 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-16 18:15:16.417  1322  1322 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 18:15:16.417  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 18:15:16.427  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-16 18:15:16.427  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-16 18:15:16.427  1322  1322 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-16 18:15:16.427  1322  3077 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 18:15:16.427   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 18:15:16.437  1014  1359 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:16.437  1014  1359 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 18:15:16.437  1014  1359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 18:15:16.457  1014  1133 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 18:15:16.457  1014  1133 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 18:15:16.457  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:16.457  1014  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:16.457  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 18:15:16.457  3616  3616 I Hs20UtilService: Starting #10
,08-16 18:15:16.457  3616  3649 I Hs20UtilService: Message received 5011
,08-16 18:15:16.457  1014  1491 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,08-16 18:15:16.457  1014  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:16.457  1014  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:16.457  1014  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:16.457  1014  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:16.477  6443  6443 E Zygote  : MountEmulatedStorage()
,08-16 18:15:16.477  6443  6443 E Zygote  : v2
08-16 18:15:16.477  6443  6443 I libpersona: KNOX_SDCARD checking this for 1000
08-16 18:15:16.477  6443  6443 I libpersona: KNOX_SDCARD not a persona
08-16 18:15:16.477  1014  1491 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6443 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,08-16 18:15:16.477  6443  6443 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-16 18:15:16.477  6443  6443 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 18:15:16.487  6443  6443 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 18:15:16.497  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 18:15:16.497  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 18:15:16.497  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-16 18:15:16.497  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 18:15:16.497  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 18:15:16.507  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 18:15:16.507  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 18:15:16.507  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 18:15:16.507  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 18:15:16.517  6443  6443 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:16.517  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-16 18:15:16.517  6443  6443 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:16.517  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 18:15:16.517  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 18:15:16.517  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 18:15:16.517  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 18:15:16.517  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 18:15:16.527  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 18:15:16.527  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 18:15:16.527  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 18:15:16.527  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 18:15:16.527  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 18:15:16.527  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 18:15:16.527  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 18:15:16.527  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 18:15:16.527  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 18:15:16.527  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-16 18:15:16.537  2123  2123 I wpa_supplicant: Blacklist: Clear (all) 
,08-16 18:15:16.537  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 18:15:16.537  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 18:15:16.537  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 18:15:16.537  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 18:15:16.537  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 18:15:16.547  6443  6443 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-16 18:15:16.547  6443  6443 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-16 18:15:16.547  6443  6443 D SecurityLogAgent: StateMachine : Current State = 1
,08-16 18:15:16.557  6443  6443 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 18:15:16.557  1014  1215 I ActivityManager: Killing 5066:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,08-16 18:15:16.557  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:16.557  1014  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:16.557  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 18:15:16.567  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:16.567  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:16.567  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 18:15:16.567  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:16.567  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:16.567  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 18:15:16.567  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:16.567  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 18:15:16.567  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 18:15:16.577  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:16.577  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 18:15:16.577  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 18:15:16.577  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:16.577  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 18:15:16.577  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 18:15:16.587  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:16.587  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:16.587  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 18:15:16.587  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:16.587  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:16.587  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 18:15:16.587  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:16.587  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:16.587  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 18:15:16.587  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:16.597  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 18:15:16.597  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 18:15:16.597  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:16.597  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 18:15:16.597  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 18:15:16.597  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:16.597  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:16.597  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 18:15:16.607  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:16.607  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:16.607  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 18:15:16.607  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:16.607  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:16.607  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 18:15:16.647  2123  2123 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING ,
08-16 18:15:16.647  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 18:15:16.647  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-16 18:15:16.647  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-16 18:15:16.667  1014  1047 I PowerManagerService: [PWL] Off : 50s ago
,08-16 18:15:16.667  1014  1047 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-16 18:15:16.667  1014  1047 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,08-16 18:15:16.667  1014  1047 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1014, ws=null) (elapsedTime=307)
,08-16 18:15:16.667  2123  2123 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-16 18:15:16.677  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 18:15:16.677  2123  2123 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-16 18:15:16.677  2123  2123 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-16 18:15:16.677  2123  2123 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-16 18:15:16.677  2123  2123 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-16 18:15:16.677  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-16 18:15:16.677  1014  1128 D Tethering: InitialState.processMessage what=4
08-16 18:15:16.677  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-16 18:15:16.677  1014  1123 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 ,
,08-16 18:15:16.677  1014  1128 E Tethering: No numeric data,
,08-16 18:15:16.687  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 18:15:16.687  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-16 18:15:16.687  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-16 18:15:16.687  1014  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-16 18:15:16.687  1014  1128 D Tethering: clearTetheredNotification()
08-16 18:15:16.687  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 18:15:16.687  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 18:15:16.687  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-16 18:15:16.687  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit,
08-16 18:15:16.687  1014  1120 V NetworkStats: performPollLocked(flags=0x1)
,08-16 18:15:16.687  1171  1171 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-16 18:15:16.687  1171  1171 D HotspotTile: updateTetherState():false, false
,08-16 18:15:16.697  1014  1120 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 18:15:16.697  1014  1120 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 18:15:16.697  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit,
08-16 18:15:16.697  1014  1120 V NetworkStats: performPollLocked() took 8ms
08-16 18:15:16.697  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit,
08-16 18:15:16.697  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:16.727   271   271 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8c507c8
08-16 18:15:16.727   271   271 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
08-16 18:15:16.727   271   271 I rmt_storage: wakelock acquired: 1, error no: 42
08-16 18:15:16.727   271   350 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1195046776)
,08-16 18:15:16.857   271   350 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504,
08-16 18:15:16.857   271   350 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
08-16 18:15:16.857   271   350 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1195046776) wakelock released: 1, error no: 0
08-16 18:15:16.857   271   350 I rmt_storage: 
,08-16 18:15:16.857   271   271 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb8c507c8,
,08-16 18:15:16.857  1014  1125 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:15:16.867  1014  1014 I ApplicationPolicy: updateDataUsageMap
,08-16 18:15:16.877  1014  1039 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-16 18:15:16.877  3119  3119 I DBG_DM  : [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,08-16 18:15:16.887  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:16.887  1014  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
08-16 18:15:16.887  3119  3119 I DBG_DM  : [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
08-16 18:15:16.887  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:16.887  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:16.887  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:16.887  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:16.887  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:16.897  6475  6475 E Zygote  : MountEmulatedStorage()
,08-16 18:15:16.897  6475  6475 I libpersona: KNOX_SDCARD checking this for 1000
08-16 18:15:16.897  6475  6475 E Zygote  : v2
08-16 18:15:16.897  6475  6475 I libpersona: KNOX_SDCARD not a persona
,08-16 18:15:16.897  6475  6475 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-16 18:15:16.897  1014  1040 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6475 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,08-16 18:15:16.907  6475  6475 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
08-16 18:15:16.907  6475  6475 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 18:15:16.917  6475  6475 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:16.917  6475  6475 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:16.937  6475  6475 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-16 18:15:16.937  6475  6475 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-16 18:15:16.937  6475  6475 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-16 18:15:16.947  1014  2723 D SSRM:n  : SIOP:: AP = 340
,08-16 18:15:16.957  6475  6475 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-16 18:15:16.957  6475  6475 I PCWCLIENTTRACE_PushUtil: sales region : global
08-16 18:15:16.957  6475  6475 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-16 18:15:16.957  6475  6475 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:15:16.957  6475  6490 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-16 18:15:16.957  1014  1359 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
08-16 18:15:16.957  1014  1359 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-16 18:15:16.957  1014  1359 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast,
,08-16 18:15:16.957  1014  1359 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:16.957  1014  1359 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:16.957  1014  1359 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:16.957  1014  1359 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:16.977  6492  6492 E Zygote  : MountEmulatedStorage()
08-16 18:15:16.977  6492  6492 I libpersona: KNOX_SDCARD checking this for 10111
08-16 18:15:16.977  6492  6492 E Zygote  : v2
08-16 18:15:16.977  6492  6492 I libpersona: KNOX_SDCARD not a persona
08-16 18:15:16.977  6492  6492 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-16 18:15:16.977  1014  1359 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6492 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 18:15:16.977  1014  1359 I ActivityManager: Killing 5764:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,08-16 18:15:16.977  6492  6492 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 18:15:16.977  6492  6492 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-16 18:15:16.977  1014  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-16 18:15:16.977  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:16.977  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:16.977  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:16.977  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:16.987  6492  6492 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 18:15:16.987  6492  6492 D ActivityThread: Added TimaKeyStore provider
08-16 18:15:16.997  2123  2123 I wpa_supplicant: Blacklist: Clear (all) 
,08-16 18:15:16.997  6507  6507 E Zygote  : MountEmulatedStorage(),
08-16 18:15:16.997  6507  6507 I libpersona: KNOX_SDCARD checking this for 10009
08-16 18:15:16.997  6507  6507 E Zygote  : v2
08-16 18:15:16.997  6507  6507 I libpersona: KNOX_SDCARD not a persona
08-16 18:15:16.997  6507  6507 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-16 18:15:16.997  1014  1040 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6507 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 18:15:17.007  6507  6507 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 18:15:17.007  1729  1729 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-16 18:15:17.007  6507  6507 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-16 18:15:17.007  1014  1040 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-16 18:15:17.017  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:17.017  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:17.017  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:17.017  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:17.037  1014  1040 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6520 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
08-16 18:15:17.037  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 18:15:17.037  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 18:15:17.037  2123  2123 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-16 18:15:17.037  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-16 18:15:17.047  6520  6520 E Zygote  : MountEmulatedStorage()
08-16 18:15:17.047  6520  6520 E Zygote  : v2
08-16 18:15:17.047  6520  6520 I libpersona: KNOX_SDCARD checking this for 10145
08-16 18:15:17.047  6520  6520 I libpersona: KNOX_SDCARD not a persona
08-16 18:15:17.047  6520  6520 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-16 18:15:17.047  6520  6520 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-16 18:15:17.047  6520  6520 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-16 18:15:17.047  6507  6507 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 18:15:17.047  6507  6507 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:17.057  1014  1123 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-16 18:15:17.057  1014  1123 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-16 18:15:17.057  1014  1123 E WifiConfigStore: setLastSelectedConfiguration -1
08-16 18:15:17.057  6413  6413 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,08-16 18:15:17.067   308   308 I art     : Explicit concurrent mark sweep GC freed 8721(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 650us total 28.222ms,
,08-16 18:15:17.077  6520  6520 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:17.077  6520  6520 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:17.077  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 18:15:17.077  1171  1171 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 18:15:17.077  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-16 18:15:17.077  1171  1720 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-16 18:15:17.077  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:17.077  1171  1171 D HotspotTile: onReceive : 1, 0
08-16 18:15:17.077  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:17.077  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:17.077  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:17.077  1171  1171 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 18:15:17.077  1171  1171 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-16 18:15:17.087  1931  2109 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 18:15:17.087  1322  1322 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-16 18:15:17.087  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:17.087  1729  1729 D accuweather: [KK AccuPhone]>>> U:4106 [0:0] getPWC : surface = 0, remote = 1
08-16 18:15:17.087  1729  1729 D accuweather: [KK AccuPhone]>>> U:4284 [0:0] Store PWC = 1
08-16 18:15:17.087  1729  1729 D accuweather: [KK AccuPhone]>>> U:4158 [0:0] addPWC = 1
08-16 18:15:17.087  1729  1729 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-16 18:15:17.087   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 615us total 17.517ms
,08-16 18:15:17.087  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:17.107  1729  1729 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
08-16 18:15:17.107   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 620us total 17.339ms
,08-16 18:15:17.107  1729  1729 D accuweather: [KK AccuPhone]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,08-16 18:15:17.107  1014  1359 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-16 18:15:17.107  1014  1359 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:17.107  1014  1359 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:17.107  1014  1359 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:17.107  1014  1359 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:17.117  1292  1305 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,08-16 18:15:17.117  6520  6520 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
08-16 18:15:17.117  6520  6520 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 18:15:17.117  6520  6520 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-16 18:15:17.117  6520  6520 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-16 18:15:17.117  6520  6520 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-16 18:15:17.127  6539  6539 E Zygote  : MountEmulatedStorage()
08-16 18:15:17.127  6539  6539 I libpersona: KNOX_SDCARD checking this for 10081
08-16 18:15:17.127  6539  6539 E Zygote  : v2
08-16 18:15:17.127  6539  6539 I libpersona: KNOX_SDCARD not a persona
08-16 18:15:17.127  6539  6539 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 18:15:17.127  6539  6539 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 18:15:17.127  6539  6539 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
08-16 18:15:17.127  1014  1359 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6539 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 18:15:17.137  1729  1729 D accuweather: [KK AccuPhone]>>> U:4250 [0:0] Store PWC succeed
,08-16 18:15:17.147  6492  6492 I MusicStore: Database version: 108
,08-16 18:15:17.147  6539  6539 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 18:15:17.147  6539  6539 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:17.187  1014  1491 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-16 18:15:17.187  1014  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-16 18:15:17.187  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:17.187  1014  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 18:15:17.187  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 18:15:17.197  1014  1345 I ActivityManager: Killing 5523:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,08-16 18:15:17.197  1014  1027 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 18:15:17.207  3652  3652 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 16 18:15:17 GMT+02:00 2016
,08-16 18:15:17.207  1014  1555 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-16 18:15:17.207  1014  1555 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-16 18:15:17.207  1014  1555 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:17.207  1014  1555 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 18:15:17.217  1014  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-16 18:15:17.217  3652  3652 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,08-16 18:15:17.227  1014  1557 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-16 18:15:17.227  1014  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:17.227  1014  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:17.227  1014  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:17.227  1014  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:17.227  1014  1133 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 18:15:17.237  3652  3652 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,08-16 18:15:17.237  3652  3652 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-16 18:15:17.237  6561  6561 E Zygote  : MountEmulatedStorage(),
08-16 18:15:17.237  6561  6561 E Zygote  : v2
08-16 18:15:17.237  6561  6561 I libpersona: KNOX_SDCARD checking this for 10034
,08-16 18:15:17.237  1014  1557 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6561 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
08-16 18:15:17.237  6561  6561 I libpersona: KNOX_SDCARD not a persona,
,08-16 18:15:17.247  6561  6561 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 18:15:17.247  6561  6561 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 18:15:17.247  6561  6561 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 18:15:17.247  3652  3652 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-16 18:15:17.257  3652  6557 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-16 18:15:17.257  3652  6557 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-16 18:15:17.257  3652  6557 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-16 18:15:17.257  3652  6557 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,08-16 18:15:17.267  1014  1483 I ActivityManager: Killing 5779:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31,
,08-16 18:15:17.267  6561  6561 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:17.267  6561  6561 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:17.287  3652  3652 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,08-16 18:15:17.317  1014  1133 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 18:15:17.327  6561  6561 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-16 18:15:17.327  6492  6492 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-16 18:15:17.327  6492  6492 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-16 18:15:17.327  1014  1483 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-16 18:15:17.337  1014  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:17.337  1014  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:17.337  1014  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:17.337  1014  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:17.347  6582  6582 E Zygote  : MountEmulatedStorage()
08-16 18:15:17.347  6582  6582 E Zygote  : v2
08-16 18:15:17.347  6582  6582 I libpersona: KNOX_SDCARD checking this for 10113
08-16 18:15:17.347  6582  6582 I libpersona: KNOX_SDCARD not a persona
,08-16 18:15:17.347  1014  1483 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6582 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 18:15:17.347  1014  1483 I ActivityManager: Killing 5556:com.sec.knox.bridge/1000 (adj 15): empty #31
,08-16 18:15:17.357  6582  6582 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 18:15:17.357  6582  6582 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 18:15:17.357  6582  6582 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-16 18:15:17.357  1014  1719 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 18:15:17.367  3177  6589 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-16 18:15:17.377  6582  6582 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:17.377  6582  6582 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:17.377  3177  6589 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-16 18:15:17.377  3177  6589 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
08-16 18:15:17.377  5794  5794 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
08-16 18:15:17.387  3177  6589 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
08-16 18:15:17.387  3177  6589 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-16 18:15:17.387  5993  5993 I SA      : [DM] init START
,08-16 18:15:17.397  1014  1027 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-16 18:15:17.397  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,08-16 18:15:17.397  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:17.397  1014  1027 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-16 18:15:17.397  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-16 18:15:17.397  5993  5993 I SA      : [DM] This device is not a Vodafone
,08-16 18:15:17.407  6492  6492 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-16 18:15:17.407  5993  5993 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,08-16 18:15:17.407  5993  5993 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
08-16 18:15:17.407  5993  5993 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,08-16 18:15:17.407  5993  5993 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,08-16 18:15:17.407  5993  5993 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,08-16 18:15:17.417  5993  5993 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,08-16 18:15:17.417  5993  5993 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,08-16 18:15:17.417  5993  5993 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-16 18:15:17.417  5993  5993 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,08-16 18:15:17.427  5794  6598 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-16 18:15:17.427  5993  5993 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-16 18:15:17.427  5993  5993 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,08-16 18:15:17.427  5993  5993 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-16 18:15:17.427  5993  5993 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,08-16 18:15:17.437  5993  5993 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75),
,08-16 18:15:17.437  5993  5993 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-16 18:15:17.437   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-16 18:15:17.437  5993  5993 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-16 18:15:17.437  5993  5993 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
08-16 18:15:17.437  5993  5993 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
08-16 18:15:17.437  5993  5993 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
08-16 18:15:17.437  5993  5993 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,08-16 18:15:17.437  5993  5993 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
08-16 18:15:17.437  5993  5993 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
08-16 18:15:17.437  5993  5993 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
08-16 18:15:17.437  5993  5993 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
08-16 18:15:17.437  5993  5993 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
08-16 18:15:17.437  5993  5993 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,08-16 18:15:17.437  5993  5993 I SA      : [SCU] isHaveSA() - false
08-16 18:15:17.437  5993  5993 I SA      : support phone number id : false
08-16 18:15:17.437  5993  5993 I SA      : [DM] Supports Ref Jpn : true
,08-16 18:15:17.447  5993  5993 I SA      : [DM] init END
,08-16 18:15:17.447  5993  5993 I SA      : [OR] onReceive log=[SA = 2.1.0240 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOJ6 PSS = 4.978878039476607  ]
,08-16 18:15:17.447  5993  5993 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-16 18:15:17.447  5993  5993 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-16 18:15:17.447  5993  5993 I SA      : [SLFUCHKMGR] constructor called
,08-16 18:15:17.457   286   286 E SMD     : DCD OFF
,08-16 18:15:17.467  5905  5936 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-16 18:15:17.467  1014  1557 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 18:15:17.477  5905  5936 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-16 18:15:17.477  5905  5936 D BadgeProvider: sendNotify, [notify] : null
08-16 18:15:17.477  5905  5936 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-16 18:15:17.477  5905  5936 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-16 18:15:17.477  5905  5936 D BadgeProvider: update, [UpdateCount] : 1
08-16 18:15:17.477  1475  1475 D Launcher.Model: reloadBadges entered.
,08-16 18:15:17.477  5993  5993 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-16 18:15:17.477  6492  6492 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-16 18:15:17.477  5993  5993 I SA      : [OR] == isSIMCardReady false ==
08-16 18:15:17.477  6492  6492 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3e2ec86c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-16 18:15:17.477  6492  6492 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-16 18:15:17.477  6492  6492 D AndroidMusic: GMSCore installation verified
08-16 18:15:17.477  5993  5993 I SA      : [SCU] == networkStateCheck == false
,08-16 18:15:17.477  5993  5993 I SA      : [OR] onReceive END
,08-16 18:15:17.487  1226  1226 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:15:17.497  1014  3070 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 18:15:17.527  1014  1345 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 18:15:17.527  1014  1557 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-16 18:15:17.527  1014  1557 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,08-16 18:15:17.527  1014  1557 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:17.527  1014  1557 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:17.527  1014  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 18:15:17.537  1014  1215 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 18:15:17.537  6492  6492 I ConfigStore: Config Database version: 1
,08-16 18:15:17.537  6443  6443 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-16 18:15:17.537  6443  6443 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 18:15:17.537  6443  6443 D SecurityLogAgent: StateMachine : Current State = 1
08-16 18:15:17.537  6443  6443 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 18:15:17.547  1014  1042 D Tethering: interfaceRemoved wlan0
,08-16 18:15:17.547  1014  1042 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-16 18:15:17.557  1014  1555 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,08-16 18:15:17.557  1014  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:17.557  1014  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:17.557  1014  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:17.557  1014  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:17.577  6608  6608 E Zygote  : MountEmulatedStorage()
,08-16 18:15:17.577  6608  6608 I libpersona: KNOX_SDCARD checking this for 10159
08-16 18:15:17.577  6608  6608 E Zygote  : v2
08-16 18:15:17.577  6608  6608 I libpersona: KNOX_SDCARD not a persona
08-16 18:15:17.577  6608  6608 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-16 18:15:17.577  1014  1555 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6608 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 18:15:17.577  6608  6608 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-16 18:15:17.577  6608  6608 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,08-16 18:15:17.597  6608  6608 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:17.597  6608  6608 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:17.647  1014  1215 I ActivityManager: Killing 5826:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,08-16 18:15:17.657  1014  1555 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 18:15:17.657  1014  1555 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-16 18:15:17.657  1014  1555 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:17.657  1014  1555 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:17.657  1014  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:17.667  1014  1359 I art     : Explicit concurrent mark sweep GC freed 53040(2MB) AllocSpace objects, 5(128KB) LOS objects, 33% free, 27MB/41MB, paused 2.759ms total 180.659ms
,08-16 18:15:17.677  3812  3812 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-16 18:15:17.677  3812  4527 I iu.UploadsManager: num queued entries: 0
,08-16 18:15:17.677  3812  4527 I iu.UploadsManager: num updated entries: 0
,08-16 18:15:17.677  3812  4527 I iu.SyncManager: NEXT; no task
,08-16 18:15:17.697   255   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-16 18:15:17.697   255   520 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 18:15:17.707  1014  1719 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-16 18:15:17.707  1014  1719 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed,
08-16 18:15:17.707  1014  1719 D SecContentProvider2: mCursor = null
,08-16 18:15:17.707  1014  1719 W WifiService: Failed getting userId using ActivityManagerNative
08-16 18:15:17.707  1014  1719 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6168, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-16 18:15:17.707  1014  1719 W WifiService: 	,at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-16 18:15:17.707  1014  1719 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-16 18:15:17.707  1014  1719 W WifiService: ,	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-16 18:15:17.707  1014  1719 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-16 18:15:17.707  1014  1719 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-16 18:15:17.707  1014  1719 D WifiService: setWifiEnabled: true pid=6168, uid=10155
,08-16 18:15:17.707  1014  1719 D SettingsProvider: name = wifi_on,
,08-16 18:15:17.707  1014  1719 W ActivityManager: Permission Denial: getCurrentUser() from pid=6168, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-16 18:15:17.707  6492  6492 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files,
08-16 18:15:17.707  1014  1042 D Tethering: interfaceRemoved p2p0
08-16 18:15:17.707  1014  1042 E Tethering: attempting to remove unknown iface (p2p0), ignoring,
08-16 18:15:17.717   255   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-16 18:15:17.717   255   520 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 18:15:17.717  6492  6492 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-16 18:15:17.717  1014  1026 I ActivityManager: Killing 5728:com.android.mms/u0a46 (adj 15): empty #31
,08-16 18:15:17.727   255   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-16 18:15:17.727   255   520 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 18:15:17.727  6492  6492 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
08-16 18:15:17.727  1014  1133 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,08-16 18:15:17.727  1014  1133 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,08-16 18:15:17.727  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:17.727  1014  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 18:15:17.737  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 18:15:17.737  1014  1026 D CountryDetector: No listener is left
,08-16 18:15:17.747  1014  1557 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-16 18:15:17.747  1014  1557 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,08-16 18:15:17.757  1014  1557 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:17.757  1014  1557 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:17.757  1014  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 18:15:17.767  1014  1558 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,08-16 18:15:17.767  1014  1558 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-16 18:15:17.767  1014  1555 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-16 18:15:17.777  1014  1215 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-16 18:15:17.777   255   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-16 18:15:17.777   255   520 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 18:15:17.777  6582  6630 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-16 18:15:17.777   255   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-16 18:15:17.777   255   520 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 18:15:17.777  6582  6630 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-16 18:15:17.787  1014  1483 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-16 18:15:17.787  1014  1026 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-16 18:15:17.787  1014  1133 I AudioService: getStreamVolume 3 index 0
,08-16 18:15:17.797   255   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-16 18:15:17.797   255   520 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 18:15:17.797  6582  6633 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-16 18:15:17.797  6492  6492 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,08-16 18:15:17.797  6492  6492 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
08-16 18:15:17.797   255   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-16 18:15:17.797   255   520 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 18:15:17.797  6582  6633 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-16 18:15:17.817  1014  1719 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-16 18:15:17.817  1014  1719 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-16 18:15:17.817  1014  1719 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:17.817  1014  1719 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:17.817  1014  1719 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 18:15:17.817  1014  3070 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-16 18:15:17.817  1014  3070 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,08-16 18:15:17.817  1014  3070 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:17.827  1014  3070 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:17.827  1014  3070 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 18:15:17.827  1014  1345 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-16 18:15:17.827  1014  1345 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,08-16 18:15:17.827  1014  1345 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:17.827  1014  1345 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:17.827  1014  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 18:15:17.837  1014  1133 I ActivityManager: Killing 5912:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,08-16 18:15:17.837  1014  1483 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-16 18:15:17.847  1014  1014 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-16 18:15:17.857  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:17.857  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:17.857  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:17.857  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:17.867  6637  6637 E Zygote  : MountEmulatedStorage(),
08-16 18:15:17.867  6637  6637 E Zygote  : v2
08-16 18:15:17.867  6637  6637 I libpersona: KNOX_SDCARD checking this for 10002
08-16 18:15:17.867  6637  6637 I libpersona: KNOX_SDCARD not a persona
,08-16 18:15:17.867  6637  6637 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 18:15:17.867  6637  6637 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-16 18:15:17.877  6637  6637 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 18:15:17.877  1014  1014 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6637 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 18:15:17.907  6637  6637 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:17.907  6637  6637 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:17.907  1014  1491 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,08-16 18:15:17.907  1014  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-16 18:15:17.907  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:17.907  1014  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:17.907  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,08-16 18:15:17.907  6492  6492 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,08-16 18:15:17.917  1014  1345 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-16 18:15:17.917  1014  1345 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-16 18:15:17.927  1014  1345 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:17.927  1014  1345 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:17.927  1014  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 18:15:17.957  1014  3070 I ActivityManager: Killing 5945:com.wsomacp/u0a25 (adj 15): empty #31
,08-16 18:15:17.967  1014  1133 I ActivityManager: Killing 5846:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #31
,08-16 18:15:17.967  1014  1345 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-16 18:15:17.967  1014  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:17.967  1014  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:17.967  1014  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:17.967  1014  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:17.987  6668  6668 E Zygote  : MountEmulatedStorage()
08-16 18:15:17.987  6668  6668 E Zygote  : v2
08-16 18:15:17.987  6668  6668 I libpersona: KNOX_SDCARD checking this for 1000
08-16 18:15:17.987  6668  6668 I libpersona: KNOX_SDCARD not a persona
,08-16 18:15:17.987  6668  6668 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 18:15:17.987  1014  1345 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6668 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
08-16 18:15:17.987  6668  6668 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 18:15:17.987  6668  6668 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 18:15:17.997  1014  1026 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 18:15:18.007  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:18.007  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 18:15:18.007  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-16 18:15:18.017  6668  6668 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:18.017  6668  6668 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:18.027  6582  6582 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,08-16 18:15:18.037  6582  6582 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 8363-8364)
08-16 18:15:18.037  6582  6582 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 18:15:18.047  6582  6582 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {22f12eed}
,08-16 18:15:18.047  6582  6582 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 18:15:18.047  6582  6582 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,08-16 18:15:18.057  6668  6668 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-16 18:15:18.067  6582  6582 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-16 18:15:18.077  6582  6582 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 18:15:18.077  6582  6582 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-16 18:15:18.097  6582  6582 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,08-16 18:15:18.097  6582  6582 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
,08-16 18:15:18.097  6582  6582 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,08-16 18:15:18.097  6582  6582 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-16 18:15:18.097  6582  6582 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-16 18:15:18.097  6582  6582 I Adreno-EGL: Build Date: 04/06/15 Mon
08-16 18:15:18.097  6582  6582 I Adreno-EGL: Local Branch: 
08-16 18:15:18.097  6582  6582 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-16 18:15:18.097  6582  6582 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-16 18:15:18.097  6582  6582 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-16 18:15:18.157  6582  6696 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-16 18:15:18.157  6582  6582 I NSApplication: Starting up...
,08-16 18:15:18.167  1014  1557 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-16 18:15:18.167  1014  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-16 18:15:18.167  1014  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:18.167  1014  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:18.167  1014  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:18.177  6668  6668 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0,
,08-16 18:15:18.187  6668  6668 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !,
,08-16 18:15:18.187  6668  6668 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:15:18.187  6668  6668 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:,
08-16 18:15:18.187  6668  6668 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
08-16 18:15:18.187  6668  6668 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-16 18:15:18.187  6701  6701 E Zygote  : MountEmulatedStorage()
,08-16 18:15:18.187  6701  6701 E Zygote  : v2
08-16 18:15:18.187  6701  6701 I libpersona: KNOX_SDCARD checking this for 10120
08-16 18:15:18.187  6701  6701 I libpersona: KNOX_SDCARD not a persona
,08-16 18:15:18.187  6701  6701 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 18:15:18.187  1014  1557 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6701 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-16 18:15:18.197  6701  6701 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-16 18:15:18.197  1014  1557 I ActivityManager: Killing 5970:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
,08-16 18:15:18.197  6701  6701 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-16 18:15:18.197  1014  1557 I ActivityManager: Killing 5805:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,08-16 18:15:18.217  6701  6701 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:18.217  6701  6701 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:18.237  6701  6701 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 18:15:18.427  1014  1123 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-16 18:15:18.427  1014  1123 E WifiHW  : ##################### set firmware type 0 #####################
,08-16 18:15:18.437   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-16 18:15:18.497  1014  1558 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-16 18:15:18.507  1014  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:18.507  1014  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:18.507  1014  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:18.507  1014  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:18.517  6722  6722 E Zygote  : MountEmulatedStorage()
08-16 18:15:18.517  6722  6722 E Zygote  : v2
08-16 18:15:18.517  6722  6722 I libpersona: KNOX_SDCARD checking this for 10125
08-16 18:15:18.517  6722  6722 I libpersona: KNOX_SDCARD not a persona
,08-16 18:15:18.517  6722  6722 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 18:15:18.517  6722  6722 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-16 18:15:18.517  1014  1558 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6722 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
08-16 18:15:18.517  1014  1558 I ActivityManager: Killing 6028:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
08-16 18:15:18.527  6722  6722 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 18:15:18.547  6722  6722 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:18.547  6722  6722 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:18.557  6722  6722 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 18:15:18.557  6722  6722 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-16 18:15:18.557  6722  6722 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-16 18:15:18.577  6722  6722 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:15:18.577  6722  6722 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-16 18:15:18.577  6722  6722 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-16 18:15:18.587  1014  1491 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-16 18:15:18.587  1014  1491 I ActivityManager: Killing 6054:com.samsung.helphub/1000 (adj 15): empty #31
,08-16 18:15:18.587  1014  1133 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 18:15:18.587  1014  1133 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-16 18:15:18.587  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:18.587  1014  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:18.587  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 18:15:18.597  3616  3616 I Hs20UtilService: Starting #11
08-16 18:15:18.597  3616  3649 I Hs20UtilService: Message received 5011
,08-16 18:15:18.597  6443  6443 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-16 18:15:18.597  6443  6443 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 18:15:18.597  6443  6443 D SecurityLogAgent: StateMachine : Current State = 1
08-16 18:15:18.597  6443  6443 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 18:15:18.787  1014  1042 D Tethering: interfaceAdded wlan0
,08-16 18:15:18.797  1014  1128 E Tethering: No numeric data
,08-16 18:15:18.797  1014  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-16 18:15:18.797  1014  1128 D Tethering: clearTetheredNotification()
,08-16 18:15:18.797  1014  1120 V NetworkStats: performPollLocked(flags=0x1),
,08-16 18:15:18.797  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:18.797  1014  1120 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 18:15:18.797  1014  1120 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 18:15:18.807  1171  1171 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-16 18:15:18.807  1171  1171 D HotspotTile: updateTetherState():false, false
,08-16 18:15:18.807  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 18:15:18.807  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-16 18:15:18.807  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-16 18:15:18.807  1014  1128 D Tethering: InitialState.processMessage what=4
,08-16 18:15:18.807  1014  1120 V NetworkStats: performPollLocked() took 11ms
08-16 18:15:18.807  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:18.817  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:18.817  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:18.817  1014  1128 E Tethering: No numeric data
,08-16 18:15:18.817  1014  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 18:15:18.817  1014  1128 D Tethering: clearTetheredNotification()
,08-16 18:15:18.817  1014  1042 D Tethering: interfaceAdded p2p0
08-16 18:15:18.817  1014  1120 V NetworkStats: performPollLocked(flags=0x1)
08-16 18:15:18.817  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:18.817  1014  1120 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 18:15:18.817  1171  1171 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-16 18:15:18.817  1014  1120 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-16 18:15:18.817  1171  1171 D HotspotTile: updateTetherState():false, false
,08-16 18:15:18.827  1014  1042 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-16 18:15:18.827  1014  1120 V NetworkStats: performPollLocked() took 10ms
,08-16 18:15:18.827  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 18:15:18.827  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-16 18:15:18.827  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-16 18:15:18.827  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:18.837   276   978 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,08-16 18:15:18.837   276   978 D SoftapController: Softap fwReload - Ok
,08-16 18:15:18.837  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:18.837  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:18.837   276   978 D CommandListener: Setting iface cfg
08-16 18:15:18.837   276   978 D CommandListener: Trying to bring down wlan0
,08-16 18:15:18.837   276   978 D CommandListener: Clearing all IP addresses on wlan0
,08-16 18:15:18.837  1014  1123 E WifiHW  : supplicant_name : p2p_supplicant
,08-16 18:15:18.847  1014  1123 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
,08-16 18:15:18.857  1322  1322 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
08-16 18:15:18.857  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 18:15:18.857  1171  1171 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 18:15:18.857  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-16 18:15:18.857  1171  1720 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-16 18:15:18.857  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:18.857  1171  1171 D HotspotTile: onReceive : 2, 0
08-16 18:15:18.857  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:18.857  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:18.857  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:18.857  1171  1171 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 18:15:18.857  1171  1171 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-16 18:15:18.857  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:18.857  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:18.867  1014  1345 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 18:15:18.867  1014  1345 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 18:15:18.867  1014  1345 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:18.867  1014  1345 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:18.867  1014  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 18:15:18.877  3616  3616 I Hs20UtilService: Starting #12
,08-16 18:15:18.877  3616  3649 I Hs20UtilService: Message received 5011
08-16 18:15:18.877  6443  6443 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-16 18:15:18.877  6443  6443 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 18:15:18.877  6443  6443 D SecurityLogAgent: StateMachine : Current State = 1
08-16 18:15:18.877  6443  6443 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 18:15:18.897  6744  6744 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,08-16 18:15:18.897  6744  6744 I wpa_supplicant: Successfully initialized wpa_supplicant
08-16 18:15:18.897  6744  6744 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-16 18:15:18.907  6744  6744 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
08-16 18:15:18.907   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6744
08-16 18:15:18.907   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-16 18:15:18.917  6744  6744 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running,
08-16 18:15:18.917  6744  6744 I wpa_supplicant: ssSupport state is = 1
08-16 18:15:18.917  6744  6744 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-16 18:15:18.917  6744  6744 I SecureStorage: [INFO]: SPID(0x00000000)Processing data,
08-16 18:15:18.917   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6744
08-16 18:15:18.917   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-16 18:15:19.067   374   374 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,08-16 18:15:19.077  6744  6744 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed,
,08-16 18:15:19.147  6744  6744 I wpa_supplicant: Ctrl_iface: loading cred from phone
,08-16 18:15:19.147  6744  6744 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-16 18:15:19.157  6744  6744 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,08-16 18:15:19.157   374   374 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6744,
08-16 18:15:19.157   374   374 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-16 18:15:19.157  6744  6744 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
,08-16 18:15:19.157  6744  6744 I wpa_supplicant: ssSupport state is = 1
08-16 18:15:19.157  6744  6744 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 18:15:19.157  6744  6744 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-16 18:15:19.157  6744  6744 E wpa_supplicant: SIM READ ERROR
08-16 18:15:19.157  6744  6744 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-16 18:15:19.167  6744  6744 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 18:15:19.167  6744  6744 E wpa_supplicant: SIM READ ERROR
08-16 18:15:19.167  6744  6744 I wpa_supplicant: Blacklist: Clear (all) 
,08-16 18:15:19.167  6744  6744 I wpa_supplicant: wpa_default_ap_write_once,
08-16 18:15:19.167  6744  6744 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-16 18:15:19.167  6744  6744 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 18:15:19.167  6744  6744 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory,
08-16 18:15:19.167  6744  6744 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 18:15:19.167  6744  6744 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-16 18:15:19.167  6744  6744 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-16 18:15:19.167  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
08-16 18:15:19.167  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
08-16 18:15:19.177  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
,08-16 18:15:19.267  6744  6744 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-16 18:15:19.407  6744  6744 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-16 18:15:19.407  6744  6744 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-16 18:15:19.417  6744  6744 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-16 18:15:19.417   374   374 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6744
08-16 18:15:19.417   374   374 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
,08-16 18:15:19.417  6744  6744 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-16 18:15:19.417  6744  6744 I wpa_supplicant: ssSupport state is = 1
08-16 18:15:19.427  6744  6744 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-16 18:15:19.427  6744  6744 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-16 18:15:19.437  6744  6744 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-16 18:15:19.437   374   374 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6744
08-16 18:15:19.437   374   374 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-16 18:15:19.437  6744  6744 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
08-16 18:15:19.437  6744  6744 I wpa_supplicant: ssSupport state is = 1
08-16 18:15:19.437  6744  6744 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 18:15:19.437  6744  6744 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 18:15:19.437  6744  6744 E wpa_supplicant: SIM READ ERROR,
08-16 18:15:19.437  6744  6744 I wpa_supplicant: wpa_default_ap_write_once
08-16 18:15:19.437  6744  6744 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-16 18:15:19.437  6744  6744 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-16 18:15:19.447  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 18:15:19.447  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-16 18:15:19.447  1014  1042 D Tethering: interfaceStatusChanged p2p0, false,
08-16 18:15:19.447  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 18:15:19.447  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-16 18:15:19.447  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-16 18:15:19.587  6744  6744 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-16 18:15:19.587  6744  6744 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-16 18:15:19.747  6744  6744 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,08-16 18:15:19.747  6744  6744 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-16 18:15:19.747  6744  6744 I wpa_supplicant: Skip scan - bUseNetwork false
,08-16 18:15:19.757  1014  1123 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
08-16 18:15:19.757  1014  1123 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-16 18:15:19.757  6744  6744 I wpa_supplicant: HOTSPOT20_ENABLE called
08-16 18:15:19.757  6744  6744 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 18:15:19.757  6744  6744 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-16 18:15:19.757  6744  6744 E wpa_supplicant: SIM READ ERROR
08-16 18:15:19.757  6744  6744 I wpa_supplicant: Blacklist: Clear (all) 
,08-16 18:15:19.777  6744  6744 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-16 18:15:19.797  6744  6744 I wpa_supplicant: Skip scan - bUseNetwork false
,08-16 18:15:19.797  1014  1123 D WifiNative-wlan0: callSECApiInt - ID [210]
,08-16 18:15:19.797  1014  1123 D WifiConfigStore: Loading config and enabling all networks 
,08-16 18:15:19.807  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
,08-16 18:15:19.807  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-16 18:15:19.807  1014  1123 E WifiConfigStore: Not a HS20
,08-16 18:15:19.807  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-16 18:15:19.807  1014  1123 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-16 18:15:19.807  1014  1123 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-16 18:15:19.807  1014  1123 D WifiNative-wlan0: callSECApiBoolean - ID [13],
08-16 18:15:19.807  6744  6744 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-16 18:15:19.807  6744  6744 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-16 18:15:19.807  6744  6744 I wpa_supplicant: reset timer : RESET_TIMER 0
08-16 18:15:19.807  6744  6744 I wpa_supplicant: P2P: Current p2p state = IDLE
08-16 18:15:19.807  6744  6744 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-16 18:15:19.807  6744  6744 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-16 18:15:19.807  6744  6744 I wpa_supplicant: First Scan Start
08-16 18:15:19.807  6744  6744 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-16 18:15:19.807  1014  1123 D WifiNative-wlan0: Setting external_sim to 1
,08-16 18:15:19.817  1014  1123 D WifiStateMachine: Setting OUI to DA-A1-19
,08-16 18:15:19.817  1014  1123 I WifiNative-HAL: startHal
08-16 18:15:19.817  1014  1123 E wifi    : getStaticLongField sWifiHalHandle 0x9cac988c
08-16 18:15:19.817  1014  1123 I WifiNative-HAL: Could not start hal
,08-16 18:15:19.817  1014  1123 E WifiNative-wlan0: do suspend true
,08-16 18:15:19.817  1014  1122 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-16 18:15:19.817  1014  1123 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-16 18:15:19.817   276   978 D CommandListener: Setting iface cfg
08-16 18:15:19.817   276   978 D CommandListener: Trying to bring up p2p0
,08-16 18:15:19.817  1014  1122 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-16 18:15:19.817  6744  6744 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-16 18:15:19.827  1014  1122 D WifiP2pService: P2pEnablingState
,08-16 18:15:19.827  1014  1122 D WifiP2pService: P2pEnablingState{ what=147457 }
,08-16 18:15:19.827  6744  6744 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-16 18:15:19.827  1014  1122 D WifiP2pService: P2p socket connection successful
,08-16 18:15:19.827  1014  1122 D WifiP2pService: P2pEnabledState
08-16 18:15:19.827  1014  1122 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-16 18:15:19.827  1014  1125 E ConnectivityService: updateNetworkInfo()
,08-16 18:15:19.827  6744  6744 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN,
,08-16 18:15:19.827  1014  1123 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 18:15:19.827  1014  1123 D SecContentProvider2: mCursor = null
,08-16 18:15:19.837  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 18:15:19.837  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 18:15:19.837  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:19.837  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:19.837  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:19.837  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:19.837  1014  1122 D WifiNative-p2p0: p2pGetDeviceAddress
08-16 18:15:19.837  1014  1122 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
,08-16 18:15:19.837  1171  1171 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 18:15:19.837  1171  1171 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-16 18:15:19.837  1171  1720 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-16 18:15:19.837  1171  1171 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 18:15:19.837  1322  1322 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-16 18:15:19.837  1171  1171 D HotspotTile: onReceive : 3, 0
,08-16 18:15:19.837  6168  6168 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 18:15:19.837  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:19.837  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:19.837  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:19.837  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:19.837  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:15:19.837  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:19.837  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:19.837  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:15:19.837  6168  6168 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:15:19.837  6168  6168 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 18:15:19.847  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 3
08-16 18:15:19.847  1014  1014 D RttService: SCAN_AVAILABLE : 3
08-16 18:15:19.847  6413  6413 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:15:19.847  1014  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-16 18:15:19.847  1014  1148 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:19.847  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 18:15:19.847  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-16 18:15:19.847  1014  1045 D WifiDisplayController: disconnect
08-16 18:15:19.847  1014  1148 I WifiNative-HAL: startHal
08-16 18:15:19.847  1014  1045 D WifiDisplayController: updateConnection
08-16 18:15:19.847  1014  1148 E wifi    : getStaticLongField sWifiHalHandle 0x9dc7b9bc,
08-16 18:15:19.847  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 18:15:19.847  1014  1148 I WifiNative-HAL: Could not start hal
08-16 18:15:19.847  1014  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-16 18:15:19.847  1014  1148 E WifiScanningService: could not start HAL
,08-16 18:15:19.847  1014  1149 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:19.847  6168  6168 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:15:19.847  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:19.847  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:19.847  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:19.847  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true,
08-16 18:15:19.847  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:15:19.847  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:19.847  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:19.847  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 18:15:19.847  6168  6168 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:15:19.847  6168  6168 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 18:15:19.847  1014  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:15:19.847  1014  1122 D WifiP2pService: DeviceAddress: 7e:96:ac
,08-16 18:15:19.847  1014  1045 D WifiDisplayAdapter: onP2pDisconnected
08-16 18:15:19.847  1014  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-16 18:15:19.847  1014  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-16 18:15:19.847  1014  1123 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
,08-16 18:15:19.847  1014  1123 D SecContentProvider2: mCursor = null,
08-16 18:15:19.847  1014  1045 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
08-16 18:15:19.847  1014  1045 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
08-16 18:15:19.847  1014  1045 D WifiDisplayController:  primary type: 10-0050F204-5,
08-16 18:15:19.847  1014  1045 D WifiDisplayController:  secondary type: null
08-16 18:15:19.847  1014  1045 D WifiDisplayController:  wps: 0
08-16 18:15:19.847  1014  1045 D WifiDisplayController:  grpcapab: 0
08-16 18:15:19.847  1014  1045 D WifiDisplayController:  devcapab: 0
08-16 18:15:19.847  1014  1045 D WifiDisplayController:  status: 3
08-16 18:15:19.847  1014  1045 D WifiDisplayController:  wfdInfo: null
08-16 18:15:19.847  1014  1045 D WifiDisplayController:  groupownerAddress: null
08-16 18:15:19.847  1014  1045 D WifiDisplayController:  GOdeviceName: null
08-16 18:15:19.847  1014  1045 D WifiDisplayController:  interfaceAddress: 
08-16 18:15:19.847  1014  1045 D WifiDisplayController:  SConnectInfo : null
,08-16 18:15:19.847  1171  1171 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-16 18:15:19.847  1014  1491 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-16 18:15:19.847  1014  1215 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 18:15:19.857  1014  1215 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:19.847  1014  1215 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-16 18:15:19.857  1014  1215 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:19.857  1014  1215 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-16 18:15:19.857  1171  1171 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-16 18:15:19.857  3616  3616 I Hs20UtilService: Starting #13
08-16 18:15:19.857  3616  3649 I Hs20UtilService: Message received 5011
,08-16 18:15:19.857  1014  1123 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-16 18:15:19.857  1014  1123 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-16 18:15:19.857  1014  1123 E WifiNative-wlan0: invaild command id : 215
,08-16 18:15:19.857  1014  1123 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-16 18:15:19.857  1014  1123 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-16 18:15:19.857  1014  1123 E WifiNative-wlan0: invaild command id : 215
,08-16 18:15:19.857  6443  6443 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-16 18:15:19.857  6443  6443 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 18:15:19.857  6443  6443 D SecurityLogAgent: StateMachine : Current State = 1
08-16 18:15:19.857  6443  6443 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 18:15:19.867  1014  1122 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-16 18:15:19.867  1014  1122 D WifiP2pService: InactiveState
08-16 18:15:19.867  1014  1122 D WifiP2pService: InactiveState{ what=143376 }
,08-16 18:15:19.867  1014  1122 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-16 18:15:19.867  6744  6744 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-16 18:15:19.867  1014  1122 D WifiP2pService: InactiveState{ what=143376 }
,08-16 18:15:19.867  1014  1122 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-16 18:15:19.867  1322  1322 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-16 18:15:19.877  1322  1322 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 18:15:19.877  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 18:15:19.877  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-16 18:15:19.877  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 18:15:19.877  1322  1322 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-16 18:15:19.877  1322  3077 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 18:15:19.877  6381  6381 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 18:15:19.877  6381  6381 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-16 18:15:19.877  6381  6381 D FileShare-Client: Outbound.stopDelayTimer - 
,08-16 18:15:19.887  6398  6398 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 18:15:20.457   286   286 E SMD     : DCD OFF,
,08-16 18:15:20.657  1014  1558 I ActivityManager: Killing 4753:com.samsung.android.sm/1000 (adj 15): empty #31
,08-16 18:15:20.717  1014  1557 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-16 18:15:20.717  1014  1557 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-16 18:15:20.717  1014  1557 D SecContentProvider2: mCursor = null
,08-16 18:15:20.717  1014  1557 D WifiService: setWifiEnabled: false pid=6168, uid=10155
,08-16 18:15:20.717  1014  1557 D SettingsProvider: name = wifi_on
,08-16 18:15:20.737  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 1
,08-16 18:15:20.737  1014  1148 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:20.737  1014  1122 D WifiP2pService: InactiveState{ what=131204 }
08-16 18:15:20.737  1014  1122 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-16 18:15:20.747  1014  1014 D RttService: SCAN_AVAILABLE : 1
08-16 18:15:20.747  1014  1149 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:20.747  1014  1125 E ConnectivityService: updateNetworkInfo()
08-16 18:15:20.747  1014  1122 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-16 18:15:20.757  1014  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 18:15:20.767  1014  1045 D WifiDisplayAdapter: onP2pDisconnected
08-16 18:15:20.767  1014  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-16 18:15:20.767  1014  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-16 18:15:20.767  1014  1122 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-16 18:15:20.767  1014  1125 E ConnectivityService: updateNetworkInfo()
,08-16 18:15:20.767  1014  1122 D WifiP2pService: P2pDisablingState
08-16 18:15:20.767  1014  1122 D WifiP2pService: P2pDisablingState{ what=147458 }
08-16 18:15:20.767  1014  1122 D WifiP2pService: p2p socket connection lost
08-16 18:15:20.777   276   978 D CommandListener: Clearing all IP addresses on wlan0
08-16 18:15:20.767  1014  1122 D WifiP2pService: P2pDisabledState
,08-16 18:15:20.777  1322  1322 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-16 18:15:20.777  1322  1322 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 18:15:20.777  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-16 18:15:20.777  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-16 18:15:20.777  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 18:15:20.777  1322  1322 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-16 18:15:20.777  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-16 18:15:20.777  1014  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,08-16 18:15:20.777  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 18:15:20.777  1014  1045 D WifiDisplayController: disconnect
08-16 18:15:20.777  1014  1045 D WifiDisplayController: updateConnection
08-16 18:15:20.777  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 18:15:20.777  1014  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-16 18:15:20.787  1322  3077 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 18:15:20.787  6744  6744 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
08-16 18:15:20.787  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-16 18:15:20.797  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 18:15:20.797  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 18:15:20.797  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:20.797  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:20.797  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:20.797  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:20.797  6381  6381 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 18:15:20.797  1014  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-16 18:15:20.797  6381  6381 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-16 18:15:20.797  1014  1045 D WifiDisplayAdapter: onP2pDisconnected
08-16 18:15:20.797  6381  6381 D FileShare-Client: Outbound.stopDelayTimer - 
08-16 18:15:20.797  1014  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-16 18:15:20.797  1014  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-16 18:15:20.807  1171  1171 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-16 18:15:20.807  1014  1719 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-16 18:15:20.807  1171  1171 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-16 18:15:20.817  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 18:15:20.817  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-16 18:15:20.817  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:20.817  1171  1720 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-16 18:15:20.817  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:20.817  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:20.817  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:20.817  1171  1171 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 18:15:20.817  1171  1171 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-16 18:15:20.817  1171  1171 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-16 18:15:20.817  1171  1171 D HotspotTile: onReceive : 0, 0
,08-16 18:15:20.817  1322  1322 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-16 18:15:20.817  6168  6168 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:15:20.817  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:20.817  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:20.817  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:20.817  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:15:20.817  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:15:20.817  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:20.817  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:20.817  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 18:15:20.817  6168  6168 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:15:20.817  6168  6168 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 18:15:20.817  6168  6168 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 18:15:20.827  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:20.827  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:20.827  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:20.827  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:15:20.827  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:15:20.827  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:20.827  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:20.827  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 18:15:20.827  6168  6168 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 18:15:20.827  6168  6168 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 18:15:20.827  6398  6398 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 18:15:20.827  1322  1322 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-16 18:15:20.827  1322  1322 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 18:15:20.827  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 18:15:20.837  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-16 18:15:20.837  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-16 18:15:20.837  1322  1322 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-16 18:15:20.837  1322  3077 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 18:15:20.837  6381  6381 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 18:15:20.837  6381  6381 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-16 18:15:20.837  6381  6381 D FileShare-Client: Outbound.stopDelayTimer - 
,08-16 18:15:20.847  6398  6398 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 18:15:20.847  1014  1215 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 18:15:20.857  1014  1215 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 18:15:20.857  1014  1215 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:20.857  1014  1215 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:20.857  1014  1215 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 18:15:20.857  3616  3616 I Hs20UtilService: Starting #14
,08-16 18:15:20.857  3616  3649 I Hs20UtilService: Message received 5007
,08-16 18:15:20.857  1322  1322 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-16 18:15:20.857  1322  1322 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 18:15:20.857  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 18:15:20.867  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED,
,08-16 18:15:20.867  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 18:15:20.867  1322  1322 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-16 18:15:20.867  1322  3077 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 18:15:20.867  1014  1483 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 18:15:20.867  1014  1483 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 18:15:20.867  1014  1483 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:20.877  1014  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:20.877  1014  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 18:15:20.877  3616  3616 I Hs20UtilService: Starting #15
,08-16 18:15:20.877  3616  3649 I Hs20UtilService: Message received 5011
,08-16 18:15:20.877  6443  6443 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-16 18:15:20.877  6443  6443 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 18:15:20.877  6443  6443 D SecurityLogAgent: StateMachine : Current State = 1
08-16 18:15:20.877  6443  6443 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 18:15:20.907  6744  6744 I wpa_supplicant: Blacklist: Clear (all) 
,08-16 18:15:20.967  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false,
08-16 18:15:20.967  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-16 18:15:20.967  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-16 18:15:20.967  6744  6744 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-16 18:15:20.967  6744  6744 I wpa_supplicant: wlan0: State: SCANNING -> DISCONNECTED
08-16 18:15:20.967  6744  6744 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-16 18:15:21.267  6744  6744 I wpa_supplicant: Blacklist: Clear (all) ,
,08-16 18:15:21.347  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 18:15:21.347  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 18:15:21.347  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
08-16 18:15:21.347  6744  6744 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-16 18:15:21.447  1014  1123 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-16 18:15:21.457  1014  1123 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-16 18:15:21.457  1014  1123 E WifiConfigStore: setLastSelectedConfiguration -1
08-16 18:15:21.457  6413  6413 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,08-16 18:15:21.467  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 18:15:21.467  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-16 18:15:21.467  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:21.467  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:21.467  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:21.467  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:21.467  1171  1171 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 18:15:21.467  1171  1720 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-16 18:15:21.467  1171  1171 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-16 18:15:21.467  1171  1171 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-16 18:15:21.467  1931  2109 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 18:15:21.467  1171  1171 D HotspotTile: onReceive : 1, 0
,08-16 18:15:21.477  1322  1322 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-16 18:15:21.477  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:21.477  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:21.477  1014  1345 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 18:15:21.477  1014  1345 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 18:15:21.487  1014  1345 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:21.487  1014  1345 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 18:15:21.487  1014  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 18:15:21.487  6443  6443 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-16 18:15:21.487  6443  6443 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-16 18:15:21.487  6443  6443 D SecurityLogAgent: StateMachine : Current State = 1
08-16 18:15:21.487  6443  6443 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 18:15:21.497  3616  3616 I Hs20UtilService: Starting #16
,08-16 18:15:21.497  3616  3649 I Hs20UtilService: Message received 5011
,08-16 18:15:22.147  1014  1042 D Tethering: interfaceRemoved wlan0
,08-16 18:15:22.147  1014  1042 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-16 18:15:22.367  1014  1042 D Tethering: interfaceRemoved p2p0
,08-16 18:15:22.367  1014  1042 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-16 18:15:22.777  1014  1345 D ActivityManager: bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,08-16 18:15:22.787  1014  1345 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,08-16 18:15:22.787  1014  1345 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:22.787  1014  1345 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 18:15:22.787  1014  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-16 18:15:22.797  1014  1040 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:22.797  1014  1040 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 18:15:22.797  6582  6631 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-16 18:15:22.797  1014  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 18:15:22.807  1014  1719 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,08-16 18:15:22.807  1014  1719 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,08-16 18:15:22.817  1014  1719 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:22.817  1014  1719 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 18:15:22.817  1014  1719 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 18:15:22.827  1014  1555 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:22.827  1014  1555 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 18:15:22.827  1014  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 18:15:22.837  1014  1215 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-16 18:15:22.837  1014  1215 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,08-16 18:15:22.837  1014  1215 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:22.837  1014  1215 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 18:15:22.837  1014  1215 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 18:15:22.847  1014  1558 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-16 18:15:22.847  1014  1558 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,08-16 18:15:22.847  1014  1558 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:22.847  1014  1558 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 18:15:22.847  1014  1558 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 18:15:22.857  1014  3070 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-16 18:15:22.857  1014  3070 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-16 18:15:22.857  1014  3070 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:22.857  1014  3070 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:22.857  1014  3070 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 18:15:22.867  1014  1719 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
08-16 18:15:22.867  1014  1719 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,08-16 18:15:22.867  1014  1719 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:22.867  1014  1719 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:22.867  1014  1719 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 18:15:22.887  1014  1133 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 18:15:22.897  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:22.897  1014  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:22.897  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,08-16 18:15:22.897  1931  1931 D WearableService: callingUid 10012, callindPid: 1931
,08-16 18:15:22.917  1014  1483 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-16 18:15:22.917  1014  1483 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-16 18:15:22.917  1014  1483 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:22.917  1014  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:22.917  1014  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 18:15:22.937  6492  6759 I MusicLeanback: Conditions not met for autocaching.
,08-16 18:15:22.937  6492  6759 I MusicLeanback: Stop autocaching.
,08-16 18:15:22.947  6492  6492 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,08-16 18:15:22.957  6492  6764 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,08-16 18:15:23.207  1014  1123 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-16 18:15:23.467   286   286 E SMD     : DCD OFF
,08-16 18:15:23.737  6168  6220 D BluetoothAdapter: enable()
,08-16 18:15:23.737  1014  1027 W ActivityManager: Permission Denial: getCurrentUser() from pid=6168, uid=10155 requires android.permission.INTERACT_ACROSS_USERS,
,08-16 18:15:23.747  1014  1027 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
08-16 18:15:23.747  1014  1027 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6168, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-16 18:15:23.747  1014  1027 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-16 18:15:23.747  1014  1027 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270),
08-16 18:15:23.747  1014  1027 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
08-16 18:15:23.747  1014  1027 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
08-16 18:15:23.747  1014  1027 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-16 18:15:23.747  1014  1027 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-16 18:15:23.747  1014  1027 D SettingsProvider: name = bluetooth_on
,08-16 18:15:23.747  1014  1027 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 18:15:23.757  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 18:15:23.757  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
08-16 18:15:23.757  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
08-16 18:15:23.757  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-16 18:15:23.797  6360  6360 D BluetoothAdapterState: make
,08-16 18:15:23.807  6360  6360 I bluedroid: init
08-16 18:15:23.807  6360  6766 I BluetoothAdapterState: Entering OffState
,08-16 18:15:23.807  6360  6360 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-16 18:15:23.807  6360  6360 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-16 18:15:23.807  6360  6360 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 18:15:23.807  6360  6360 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-16 18:15:23.817  6360  6360 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-16 18:15:23.817  6360  6360 I bluedroid: get_profile_interface socket
08-16 18:15:23.817  6360  6360 I bluedroid: get_profile_interface map_client
,08-16 18:15:23.817  6360  6769 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting,
08-16 18:15:23.817  6360  6360 D BluetoothAdapterService: checkAddrForIOP: Loading from conf,
,08-16 18:15:23.827  6360  6769 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,08-16 18:15:23.827  6360  6360 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-16 18:15:23.827  6360  6769 E BluetoothServiceJni: populateRssiValuesNative
,08-16 18:15:23.827  6360  6769 I bluedroid: getModelRssiValues
08-16 18:15:23.827  6360  6769 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-16 18:15:23.827  6360  6769 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-16 18:15:23.827  1014  1014 D SettingsProvider: name = bluetooth_name
,08-16 18:15:23.827  1014  1557 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-16 18:15:23.827  1014  1557 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 18:15:23.827  6360  6769 D BluetoothAdapterProperties: Name is: A5-1
08-16 18:15:23.827  1014  1557 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:23.827  1014  1557 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:23.827  1014  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:23.827  6360  6369 I bluedroid: config_hci_snoop_log
,08-16 18:15:23.837  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,08-16 18:15:23.837  1014  1044 D BluetoothManagerService: Ble is always on enable gatt
,08-16 18:15:23.837  1014  1044 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-16 18:15:23.837  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-16 18:15:23.837  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-16 18:15:23.847  6360  6360 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-16 18:15:23.847  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 18:15:23.857  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 18:15:23.857  1014  1044 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-16 18:15:23.857  6360  6766 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-16 18:15:23.857  6360  6766 D BluetoothAdapterProperties: Setting state to 11
,08-16 18:15:23.857  6360  6766 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-16 18:15:23.857  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-16 18:15:23.857  6360  6766 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 18:15:23.857  6360  6766 D BluetoothAdapterService: updateAdapterState state is 11
,08-16 18:15:23.857  6360  6766 D BluetoothAdapterService: Autoconnection is available 
08-16 18:15:23.857  6360  6766 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-16 18:15:23.867  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-16 18:15:23.867  1014  1014 I InputMethodManagerService: [BT Setting State] State =11
,08-16 18:15:23.877  1171  1171 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-16 18:15:23.877  6360  6766 D BluetoothSecureManager: getInstant: null
08-16 18:15:23.877  6360  6766 D BluetoothSecureManager: calling getMethod for getService
08-16 18:15:23.877  6360  6766 D BluetoothSecureManager: calling getService
,08-16 18:15:23.877  6360  6766 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@13e83bdc
08-16 18:15:23.877  1171  1171 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:23.877  1171  1171 D BluetoothTile:  getBluetoothState : 11
,08-16 18:15:23.877  1014  1558 D BluetoothSecureManagerService: isSecureModeEnabled
08-16 18:15:23.877  1773  1773 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
08-16 18:15:23.877  1014  1558 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-16 18:15:23.877  6360  6766 D BtConfig.SecureMode: isSecureModeOn:false
08-16 18:15:23.877  6360  6766 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-16 18:15:23.877  6360  6766 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-16 18:15:23.877  6360  6766 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-16 18:15:23.877  6360  6766 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-16 18:15:23.877  6360  6766 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-16 18:15:23.887  6360  6766 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-16 18:15:23.887  1014  1027 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-16 18:15:23.887  6360  6766 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-16 18:15:23.887  6360  6766 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-16 18:15:23.887  6360  6766 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-16 18:15:23.887  1322  1322 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 18:15:23.887  1014  1491 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-16 18:15:23.887  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-16 18:15:23.887  6360  6766 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-16 18:15:23.887  6360  6766 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-16 18:15:23.887  1014  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 18:15:23.887  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-16 18:15:23.887  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:23.887  6360  6766 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-16 18:15:23.887  6360  6766 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-16 18:15:23.887  1171  1720 D BluetoothTile:  handleUpdatestate:false name:null
08-16 18:15:23.887  1171  1720 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-16 18:15:23.887  6360  6766 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-16 18:15:23.897  6360  6766 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-16 18:15:23.897  6360  6766 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-16 18:15:23.897  6360  6766 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-16 18:15:23.897  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:23.897  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:23.897  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:23.897  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:23.897  6360  6766 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-16 18:15:23.897  6360  6766 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-16 18:15:23.897  6360  6766 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-16 18:15:23.897  6360  6766 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-16 18:15:23.897  6360  6766 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-16 18:15:23.897  6360  6766 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-16 18:15:23.897  6360  6766 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-16 18:15:23.897  6360  6766 D BluetoothBondStateMachine: make
,08-16 18:15:23.907  1322  1322 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 18:15:23.907  6360  6766 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,08-16 18:15:23.907  6360  6766 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-16 18:15:23.907  6360  6771 I BluetoothBondStateMachine: StableState(): Entering Off State
08-16 18:15:23.907  6360  6766 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-16 18:15:23.907  1171  1171 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 18:15:23.907  1171  1171 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-16 18:15:23.917  1014  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 18:15:23.917  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-16 18:15:23.917  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:23.917  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:23.917  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:23.917  6360  6766 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,08-16 18:15:23.917  6360  6766 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-16 18:15:23.917  6360  6766 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-16 18:15:23.917  6360  6360 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 18:15:23.917  6360  6360 D BtGatt.GattService: Received start request. Starting profile...
08-16 18:15:23.917  6360  6360 D BtGatt.GattService: start()
08-16 18:15:23.917  6360  6360 D BtGatt.GattService: start()
08-16 18:15:23.917  6360  6360 I bluedroid: get_profile_interface gatt
,08-16 18:15:23.917  6360  6360 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e014ed6
08-16 18:15:23.917  6360  6360 D BtGatt.AdvertiseManager: advertise manager created
,08-16 18:15:23.917  1014  1555 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 18:15:23.927  1014  1555 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0,
08-16 18:15:23.927  1014  1555 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:23.927  1014  1555 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:23.927  1014  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:23.927  6360  6766 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,08-16 18:15:23.927  6360  6766 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-16 18:15:23.927  6360  6766 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-16 18:15:23.927  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:23.927  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 18:15:23.927  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:23.927  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:23.927  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:23.927  6360  6360 D BtGatt.GattService: mStartError = false
,08-16 18:15:23.927  6360  6360 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e014ed6
,08-16 18:15:23.927  6360  6766 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-16 18:15:23.927  6360  6766 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 18:15:23.927  6360  6766 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-16 18:15:23.937  6360  6360 D HeadsetService: Received start request. Starting profile...
,08-16 18:15:23.937  6360  6360 D HeadsetService: start()
,08-16 18:15:23.937  6360  6360 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-16 18:15:23.937  6360  6360 D HeadsetStateMachine: make
08-16 18:15:23.937  1014  1133 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:23.937  1014  1133 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-16 18:15:23.937  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:23.937  1014  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:23.937  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:23.937  6360  6360 E HeadsetStateMachine: # of Max HF connection is 2
,08-16 18:15:23.947  6360  6766 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-16 18:15:23.947  6360  6766 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-16 18:15:23.947  6360  6766 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-16 18:15:23.947  1014  1345 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-16 18:15:23.957  1014  1345 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-16 18:15:23.957  1014  1345 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:23.957  1014  1345 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 18:15:23.957  1014  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-16 18:15:23.957  1014  1557 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 18:15:23.957  1014  1557 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-16 18:15:23.957  1014  1557 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:23.957  1014  1557 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:23.957  1014  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:23.957  1014  1555 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-16 18:15:23.957  6360  6766 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-16 18:15:23.957  6360  6766 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-16 18:15:23.957  6360  6766 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-16 18:15:23.957  1014  1555 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-16 18:15:23.957  1014  1555 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:23.957  1014  1555 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 18:15:23.957  1014  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-16 18:15:23.957  6360  6360 I bluedroid: get_profile_interface handsfree
,08-16 18:15:23.967  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:23.967  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 18:15:23.967  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:23.967  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:23.967  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:23.967  6360  6766 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-16 18:15:23.967  6360  6766 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 18:15:23.967  6360  6766 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-16 18:15:23.967  1014  1359 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:23.967  1014  1359 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-16 18:15:23.967  1014  1359 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:23.967  1014  1359 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:23.967  1014  1359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:23.977  6360  6360 I DualScoManager: Instantiating Dual Sco Manager
,08-16 18:15:23.977  6360  6360 I DualScoManager: Set HeadsetServiceHelper
,08-16 18:15:23.987  6360  6360 D BluetoothAtMessage: createCMTIContentObservers
,08-16 18:15:23.987  6360  6766 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-16 18:15:23.987  6360  6766 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-16 18:15:23.987  6360  6766 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-16 18:15:23.987  1014  1719 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 18:15:23.987  1014  1483 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-16 18:15:23.987  1014  1483 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 18:15:23.987  1014  1483 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 18:15:23.987  1014  1483 D SettingsProvider: selectionArgs: false
08-16 18:15:23.987  1014  1483 D SettingsProvider: selectionArgs: 1002,
08-16 18:15:23.987  1014  1483 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 18:15:23.987  1014  1719 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-16 18:15:23.987  1014  1483 D SettingsProvider: ret = -1,
08-16 18:15:23.987  6360  6775 D HeadsetStateMachine: Enter Disconnected: -2
08-16 18:15:23.987  1014  1719 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:23.987  1014  1719 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 18:15:23.987  1014  1719 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:23.987  6360  6766 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-16 18:15:23.987  6360  6766 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-16 18:15:23.987  6360  6766 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-16 18:15:23.987  6360  6766 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-16 18:15:23.987  6360  6766 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-16 18:15:23.987  6360  6766 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-16 18:15:23.987  6360  6766 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-16 18:15:23.987  6360  6766 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-16 18:15:23.987  6360  6766 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-16 18:15:23.987  6360  6766 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-16 18:15:23.987  6360  6766 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-16 18:15:23.987  6360  6766 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-16 18:15:23.987  6360  6766 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-16 18:15:23.987  6360  6360 D HeadsetService: mStartError = false
08-16 18:15:23.987  6360  6360 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e014ed6
,08-16 18:15:23.987  6360  6360 E BluetoothAdapterService(503402198): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-16 18:15:23.997  6360  6775 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-16 18:15:23.997  6360  6775 D HeadsetStateMachine: map size, before remove : 0
08-16 18:15:23.997  6360  6775 D HeadsetStateMachine: map size, after remove: 0
08-16 18:15:23.997  6360  6360 D A2dpService: Received start request. Starting profile...
08-16 18:15:23.997  6360  6360 D A2dpService: start()
,08-16 18:15:23.997  6360  6360 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-16 18:15:23.997  6360  6360 I bluedroid: get_profile_interface avrcp
,08-16 18:15:24.007  6360  6360 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 18:15:24.017  6360  6360 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-16 18:15:24.017  6360  6779 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include,
,08-16 18:15:24.017  6360  6360 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 18:15:24.017  6360  6360 D A2dpStateMachine: make
,08-16 18:15:24.027  6360  6360 I bluedroid: get_profile_interface a2dp
08-16 18:15:24.027  6360  6781 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-16 18:15:24.027  6360  6360 E bt-btif : warning : media task started media_task_refcnt 1 
,08-16 18:15:24.027  6360  6360 D A2dpService: mStartError = false
08-16 18:15:24.027  6360  6360 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e014ed6
,08-16 18:15:24.027  6360  6360 I BluetoothHidServiceJni: classInitNative: succeeds
,08-16 18:15:24.027  6360  6360 D HidService: Received start request. Starting profile...
08-16 18:15:24.027  6360  6360 D HidService: start()
08-16 18:15:24.027  6360  6360 I bluedroid: get_profile_interface hidhost
08-16 18:15:24.027  6360  6360 D HidService: setHidService(): set to: null
08-16 18:15:24.027  6360  6360 D HidService: mStartError = false
08-16 18:15:24.027  6360  6360 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e014ed6
,08-16 18:15:24.027  6360  6360 D HeadsetStateMachine: Try to query the phonestate on bind
08-16 18:15:24.027  6360  6780 D A2dpStateMachine: Enter Disconnected: -2
,08-16 18:15:24.037  1430  2739 I Telecom : BluetoothPhoneService: queryPhoneState
,08-16 18:15:24.037  1430  1430 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-16 18:15:24.037  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-16 18:15:24.037  1430  2739 I Telecom : BluetoothPhoneService: Result of Message : true
,08-16 18:15:24.037  1931  1931 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-16 18:15:24.037  6360  6360 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-16 18:15:24.047  6360  6360 D HealthService: Received start request. Starting profile...
08-16 18:15:24.047  6360  6360 D HealthService: start()
,08-16 18:15:24.047  6360  6779 D BluetoothMediaBrowser: no now playing list
08-16 18:15:24.047  6360  6779 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-16 18:15:24.047  1931  1931 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-16 18:15:24.047  6360  6360 I bluedroid: get_profile_interface health
08-16 18:15:24.047  6360  6360 D HealthService: mStartError = false
08-16 18:15:24.047  6360  6360 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e014ed6
,08-16 18:15:24.047  6360  6360 D HeadsetStateMachine: Proxy object connected
,08-16 18:15:24.047  6360  6360 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-16 18:15:24.047  6360  6360 D PanService: Received start request. Starting profile...
,08-16 18:15:24.047  6360  6360 D PanService: start()
08-16 18:15:24.047  6360  6360 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-16 18:15:24.047  6360  6360 I bluedroid: get_profile_interface pan
,08-16 18:15:24.057  6360  6360 D PanService: mStartError = false
,08-16 18:15:24.057  6360  6360 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e014ed6
,08-16 18:15:24.057  6360  6360 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-16 18:15:24.057  6360  6360 D BluetoothMapService: Received start request. Starting profile...
08-16 18:15:24.057  6360  6360 D BluetoothMapService: start()
,08-16 18:15:24.057  6360  6775 D HeadsetStateMachine: Disconnected process message: 11
,08-16 18:15:24.057  6360  6360 D BluetoothMapService: mStartError = false
,08-16 18:15:24.057  6360  6360 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e014ed6
,08-16 18:15:24.057  6360  6360 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-16 18:15:24.057  6360  6360 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-16 18:15:24.057  6360  6775 D HeadsetStateMachine: Disconnected process message: 18
,08-16 18:15:24.057  6360  6360 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-16 18:15:24.067  6360  6360 D SapService: Received start request. Starting profile...
,08-16 18:15:24.067  6360  6360 D SapService: start()
08-16 18:15:24.067  6360  6360 D BluetoothSAPServiceJni: initializeNative(L209): sap
,08-16 18:15:24.067  6360  6360 I bluedroid: get_profile_interface sap
08-16 18:15:24.067  6360  6360 D SapService: mStartError = false
,08-16 18:15:24.067  6360  6360 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e014ed6
08-16 18:15:24.067  6360  6360 E BluetoothAdapterService(503402198): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,08-16 18:15:24.067  6360  6360 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-16 18:15:24.067  6360  6360 D BluetoothA2dp: Proxy object connected
08-16 18:15:24.067  6360  6360 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-16 18:15:24.067  6360  6360 E BluetoothAdapterService(503402198): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-16 18:15:24.067  6360  6775 D HeadsetStateMachine: Disconnected process message: 10
08-16 18:15:24.067  6360  6360 E BluetoothAdapterService(503402198): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-16 18:15:24.067  6360  6775 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 18:15:24.067  6360  6775 D HeadsetStateMachine: Disconnected process message: 11
,08-16 18:15:24.067  6360  6360 E BluetoothAdapterService(503402198): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,08-16 18:15:24.067  6360  6360 E BluetoothAdapterService(503402198): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-16 18:15:24.087  6360  6360 E BluetoothAdapterService(503402198): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-16 18:15:24.097  6360  6360 E BluetoothAdapterService(503402198): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-16 18:15:24.097  6360  6766 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-16 18:15:24.097  6360  6766 I bluedroid: enable
,08-16 18:15:24.097  6360  6766 I bt_hci_bdroid: init
08-16 18:15:24.097  6360  6785 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-16 18:15:24.097  6360  6766 I bt_vendor: bt-vendor : init
,08-16 18:15:24.097  6360  6766 I bt_vendor: bt-vendor : get_bt_soc_type
08-16 18:15:24.097  6360  6766 E bt_vendor: get_bt_soc_type: Failed to get soc type
,08-16 18:15:24.097  6360  6766 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
08-16 18:15:24.107  6360  6766 D bt_userial_mct: userial_init
,08-16 18:15:24.107  6360  6766 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-16 18:15:24.107  6360  6766 I bt_vendor: Starting hciattach daemon
08-16 18:15:24.107  6360  6766 I bt_vendor: try to set false
,08-16 18:15:24.107  6360  6766 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,08-16 18:15:24.107  6360  6766 I bt_vendor: Starting hciattach daemon
08-16 18:15:24.107  6360  6766 I bt_vendor: try to set true
,08-16 18:15:24.127  6789  6789 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-16 18:15:24.167  6795  6795 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-16 18:15:24.177  6796  6796 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-16 18:15:24.197  6798  6798 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-16 18:15:24.197  6799  6799 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-16 18:15:24.207  6800  6800 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-16 18:15:24.217  6801  6801 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-16 18:15:24.477  6804  6804 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,08-16 18:15:24.487  6805  6805 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-16 18:15:24.517  6360  6766 I bt_vendor: bluetooth satus is on
,08-16 18:15:24.517  6360  6787 D bt_userial_mct: userial_open(port:0)
08-16 18:15:24.517  6360  6787 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-16 18:15:24.517  6360  6787 I bt_vendor: Done intiailizing UART,
,08-16 18:15:24.517  6360  6787 I bt_vendor: Done intiailizing UART
08-16 18:15:24.517  6360  6787 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-16 18:15:24.517  6360  6787 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-16 18:15:24.527  6360  6807 D bt_userial_mct: Entering userial_read_thread()
,08-16 18:15:24.527  6360  6785 I         : BTE_InitTraceLevels -- TRC_HCI
,08-16 18:15:24.527  6360  6785 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 18:15:24.527  6360  6785 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-16 18:15:24.527  6360  6785 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 18:15:24.527  6360  6785 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 18:15:24.527  6360  6785 I         : BTE_InitTraceLevels -- TRC_A2D
,08-16 18:15:24.527  6360  6785 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 18:15:24.527  6360  6785 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 18:15:24.527  6360  6785 I         : BTE_InitTraceLevels -- TRC_GAP
,08-16 18:15:24.527  6360  6785 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 18:15:24.527  6360  6785 I         : BTE_InitTraceLevels -- TRC_SAP
08-16 18:15:24.527  6360  6785 I         : BTE_InitTraceLevels -- TRC_SDP
,08-16 18:15:24.527  6360  6785 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 18:15:24.527  6360  6785 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 18:15:24.527  6360  6785 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-16 18:15:24.527  6360  6785 I         : BTE_InitTraceLevels -- TRC_BTIF
08-16 18:15:24.527  6360  6785 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-16 18:15:24.637  6360  6785 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-16 18:15:24.637  6360  6785 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa3fde6e9 
,08-16 18:15:24.637  6360  6785 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3fde6e9 
,08-16 18:15:24.657  6360  6769 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-16 18:15:24.657  6360  6769 E bt-btif : Calling BTA_HhEnable
,08-16 18:15:24.657  6360  6769 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-16 18:15:24.657  6360  6769 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,08-16 18:15:24.657  6360  6769 E BluetoothServiceJni: populateRssiValuesNative
08-16 18:15:24.657  6360  6769 I bluedroid: getModelRssiValues
,08-16 18:15:24.667  6360  6769 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-16 18:15:24.667  6360  6769 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-16 18:15:24.667  6360  6769 D BluetoothAdapterProperties: Name is: A5-1
,08-16 18:15:24.667  1014  1014 D SettingsProvider: name = bluetooth_name
,08-16 18:15:24.667  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:24.677  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:24.677  6360  6769 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-16 18:15:24.677  6360  6769 D BluetoothAdapterProperties: Scan Mode:20
,08-16 18:15:24.677  6360  6769 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 18:15:24.677  6360  6769 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
,08-16 18:15:24.677  6360  6769 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,08-16 18:15:24.677  6360  6769 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-16 18:15:24.677  6360  6769 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-16 18:15:24.677  6360  6769 E bt-btif : btif_sock_init: !vhci_init
,08-16 18:15:24.677  6360  6769 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-16 18:15:24.687  6360  6769 D IOP_DB_BT: db_open: db_open : handle 3028029456l, read 13894 bytes onto local cache
,08-16 18:15:24.687  6360  6807 E bt_mct  : hci lib postload completed
,08-16 18:15:24.687  6360  6769 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-16 18:15:24.687  6360  6769 D IOP_DB_BT: db_query: result 1
,08-16 18:15:24.687  6360  6769 I         : iop_db_open: iop_db_open status 0
,08-16 18:15:24.687  6360  6769 D bte_conf: Device ID record 1 : primary
08-16 18:15:24.687  6360  6769 D bte_conf:   vendorId            = 0075
08-16 18:15:24.687  6360  6769 D bte_conf:   vendorIdSource      = 0001
08-16 18:15:24.687  6360  6769 D bte_conf:   product             = 0100
08-16 18:15:24.687  6360  6769 D bte_conf:   version             = 0200
08-16 18:15:24.687  6360  6769 D bte_conf:   clientExecutableURL = 
08-16 18:15:24.687  6360  6769 D bte_conf:   serviceDescription  = 
08-16 18:15:24.687  6360  6769 D bte_conf:   documentationURL    = 
08-16 18:15:24.687  6360  6769 D bte_conf: bte_load_did_conf no section named DID2.
,08-16 18:15:24.687  6360  6769 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-16 18:15:24.697  6360  6766 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-16 18:15:24.697  6360  6766 D BluetoothAdapterProperties: ScanMode =  20
,08-16 18:15:24.697  6360  6766 D BluetoothAdapterProperties: State =  11
,08-16 18:15:24.697  1014  1483 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-16 18:15:24.697  6360  6766 D BluetoothAdapterProperties: Setting state to 12
,08-16 18:15:24.697  6360  6766 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-16 18:15:24.707  6360  6769 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-16 18:15:24.707  6360  6769 D BluetoothAdapterProperties: Scan Mode:21
08-16 18:15:24.707  6360  6769 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 18:15:24.707  1014  3070 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-16 18:15:24.707  1014  3070 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 18:15:24.707  1014  3070 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 18:15:24.707  1014  3070 D SettingsProvider: selectionArgs: false
08-16 18:15:24.707  1014  3070 D SettingsProvider: selectionArgs: 1002
08-16 18:15:24.707  1014  3070 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 18:15:24.707  1014  3070 D SettingsProvider: ret = -1
,08-16 18:15:24.707  6360  6766 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 18:15:24.707  6360  6766 D BluetoothAdapterService: updateAdapterState state is 12
,08-16 18:15:24.707  1014  1215 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:24.707  1014  1215 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-16 18:15:24.707  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:24.707  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:24.707  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:24.707  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:15:24.707  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:24.707  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:24.707  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:24.707  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:15:24.707  1014  1215 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:24.707  1014  1215 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:24.707  1014  1215 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:24.717  1322  6625 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 18:15:24.717  6360  6766 D BluetoothAdapterService: Autoconnection is available 
,08-16 18:15:24.717  6360  6766 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-16 18:15:24.717  6360  6766 D BluetoothAdapterService: starting service from this receiver
,08-16 18:15:24.717  1014  1555 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 18:15:24.717  1014  1555 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-16 18:15:24.717  1014  1555 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:24.717  1014  1555 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 18:15:24.717  1014  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:24.727  6360  6766 I BluetoothAdapterState: Entering On State from state = 11
,08-16 18:15:24.727  1322  6625 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-16 18:15:24.727  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-16 18:15:24.727  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 18:15:24.727  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:24.727  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:24.727  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:24.727  1322  1322 D BluetoothA2dp: Proxy object connected
,08-16 18:15:24.727  1322  1322 D A2dpProfile: Bluetooth service connected
,08-16 18:15:24.727  6168  6168 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 18:15:24.737  6360  6360 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-16 18:15:24.737  1430  1438 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 18:15:24.737  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:24.737  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:24.737  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:24.737  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:15:24.737  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:24.737  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:24.737  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:24.737  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:15:24.747  1014  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 18:15:24.747  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 18:15:24.747  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:24.747  6168  6168 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:15:24.747  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:24.747  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:24.747  1430  1438 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 18:15:24.747  6360  6770 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-16 18:15:24.747  6360  6770 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 18:15:24.747  1014  1044 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 18:15:24.757  1014  1044 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-16 18:15:24.757  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-16 18:15:24.757  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 18:15:24.757  1322  1333 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 18:15:24.757  1014  1014 D BluetoothA2dp: Proxy object connected
,08-16 18:15:24.757  6360  6360 I BluetoothPbapService: Handler(): got msg=1
,08-16 18:15:24.757  1014  1491 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-16 18:15:24.757  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-16 18:15:24.757  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-16 18:15:24.757  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:24.757  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:24.757  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:24.767  1014  1044 D BluetoothPan: Binding service...
08-16 18:15:24.767  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-16 18:15:24.767  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 18:15:24.767  6360  6811 V BluetoothPbapService: PBAP Service initSocket try: 0
08-16 18:15:24.767  1322  1331 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 18:15:24.767  1322  1322 D BluetoothInputDevice: Proxy object connected
08-16 18:15:24.767  1322  1322 D HidProfile: Bluetooth service connected
,08-16 18:15:24.767  1014  1014 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 18:15:24.767  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-16 18:15:24.767  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-16 18:15:24.767  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:24.767  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:24.767  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:24.767  1322  6625 D Bluetoothsap: onBluetoothStateChange: up=true
08-16 18:15:24.767  1322  6625 D Bluetoothsap: Binding service...
,08-16 18:15:24.767  1322  6625 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-16 18:15:24.777  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-16 18:15:24.777  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-16 18:15:24.777  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:24.777  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:24.777  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:24.777  1322  6625 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-16 18:15:24.777  1014  1044 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 18:15:24.777  1014  1044 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 18:15:24.777  1322  1322 D BluetoothMap: Proxy object connected
08-16 18:15:24.777  1322  1322 D MapProfile: Bluetooth service connected
,08-16 18:15:24.777  1322  1322 D BluetoothMap: getConnectedDevices()
08-16 18:15:24.777  1430  2739 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 18:15:24.777  6360  6811 D BluetoothSocket: bindListen(): myUserId = 0
,08-16 18:15:24.777  6360  6811 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 18:15:24.777  1014  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 18:15:24.777  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 18:15:24.777  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:24.777  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:24.777  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:24.777  1430  2739 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 18:15:24.777  1454  1469 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 18:15:24.777  1322  1322 D Bluetoothsap: BluetoothSAP Proxy object connected
08-16 18:15:24.777  1322  1322 D SapProfile: Bluetooth service connected
08-16 18:15:24.777  1322  1322 D Bluetoothsap: getConnectedDevices()
,08-16 18:15:24.777  1014  1044 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 18:15:24.777  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 18:15:24.787  6360  6811 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
08-16 18:15:24.787  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:24.787  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:24.787  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:24.787  6360  6811 D BluetoothSocket: bindListen(), new LocalSocket 
08-16 18:15:24.787  6360  6811 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-16 18:15:24.787  6360  6811 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@cfa87c3
08-16 18:15:24.787  6360  6811 D BluetoothSocket: channel: 19
08-16 18:15:24.787  6360  6811 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-16 18:15:24.787  1454  1469 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 18:15:24.787  2864  2882 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 18:15:24.787  1014  1044 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-16 18:15:24.787  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 18:15:24.787  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:24.787  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:24.787  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:24.797  2864  2882 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 18:15:24.797  1322  1333 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 18:15:24.797  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-16 18:15:24.797  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 18:15:24.797  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:24.797  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:24.797  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:24.797  1322  1333 E BluetoothHeadset: BluetoothHeadset service is binded,
,08-16 18:15:24.797  1322  1322 D HeadsetProfile: Bluetooth service connected,
08-16 18:15:24.807  1439  1453 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 18:15:24.807  1439  1453 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 18:15:24.807  6168  6178 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 18:15:24.807  6168  6178 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 18:15:24.807  2864  2873 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 18:15:24.807  2864  2873 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 18:15:24.807  1322  1331 D BluetoothPbap: onBluetoothStateChange: up=true
,08-16 18:15:24.807  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap,
08-16 18:15:24.807  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:24.807  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-16 18:15:24.807  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:24.807  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:24.807  1322  1333 D BluetoothPan: Binding service...
,08-16 18:15:24.807  1322  1322 D BluetoothPbap: Proxy object connected
08-16 18:15:24.807  1322  1322 D PbapServerProfile: Bluetooth service connected
,08-16 18:15:24.807  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-16 18:15:24.807  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 18:15:24.807  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:24.817  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:24.817  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:24.817  1322  1322 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 18:15:24.817  1322  1322 D PanProfile: Bluetooth service connected
08-16 18:15:24.817  6329  6338 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 18:15:24.817  6329  6338 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 18:15:24.817  1014  1044 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 18:15:24.817  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 18:15:24.817  1014  1044 E BluetoothHeadset: BluetoothHeadset service is binded
08-16 18:15:24.817  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-16 18:15:24.817  1454  1468 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 18:15:24.817  1454  1468 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 18:15:24.817  2864  2882 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 18:15:24.817  2864  2882 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-16 18:15:24.817  1014  1044 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-16 18:15:24.817  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 18:15:24.817  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:24.817  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:24.817  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
08-16 18:15:24.817  2864  2864 D BluetoothA2dp: Proxy object connected
,08-16 18:15:24.817  1931  1946 D BluetoothAdapter: onBluetoothStateChange: up=true,
08-16 18:15:24.817  1931  1946 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 18:15:24.817  1430  1443 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 18:15:24.817  1014  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 18:15:24.817  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-16 18:15:24.827  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:24.827  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:24.827  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:24.827  1430  1443 E BluetoothHeadset: BluetoothHeadset service is binded
08-16 18:15:24.827  6360  6369 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 18:15:24.827  1430  2739 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 18:15:24.827  1430  2739 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 18:15:24.827  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-16 18:15:24.827  1322  1331 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 18:15:24.827  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2,
08-16 18:15:24.827  1322  1331 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 18:15:24.827  1171  1928 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 18:15:24.827  1171  1928 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 18:15:24.827  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED,
08-16 18:15:24.827  1014  1014 I InputMethodManagerService: [BT Setting State] State =12
08-16 18:15:24.827  1014  1014 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-16 18:15:24.827  1171  1171 D BluetoothTile:  onBluetoothStateChange:
,08-16 18:15:24.837  1430  1430 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@1e89d00e, true
08-16 18:15:24.837  1171  1171 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:24.837  1171  1171 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-16 18:15:24.837  1171  1171 D BluetoothTile:  getBluetoothState : 12
,08-16 18:15:24.837  1773  1773 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
08-16 18:15:24.837  1430  1430 D BluetoothHeadset: registerMessageListener
,08-16 18:15:24.837  1322  1322 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 18:15:24.837  1014  1555 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 18:15:24.837  1014  1027 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
08-16 18:15:24.837  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 18:15:24.837  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:24.847  1171  1720 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 18:15:24.847  1014  1557 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 18:15:24.847  1014  1557 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-16 18:15:24.847  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:24.847  1014  1557 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:24.847  1014  1557 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:24.847  1014  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:24.847  1171  1720 D BluetoothTile:  handleUpdatestate:false name:null
08-16 18:15:24.847  6360  6368 D HeadsetService: registerMessageListener
,08-16 18:15:24.847  6360  6368 D HeadsetService: registerMessageListener
08-16 18:15:24.847  6360  6775 D HeadsetStateMachine: Disconnected process message: 70
08-16 18:15:24.847  1430  1430 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-16 18:15:24.847  6360  6775 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@1fdb6840
08-16 18:15:24.847  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-16 18:15:24.847  1322  1322 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-16 18:15:24.847  1171  1720 D BluetoothTile:  handleUpdatestate:false name:null
08-16 18:15:24.847  1322  1322 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-16 18:15:24.847  1322  1322 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-16 18:15:24.847  1322  1322 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-16 18:15:24.857  1430  1430 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-16 18:15:24.857  1430  1430 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-16 18:15:24.857  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-16 18:15:24.857  6360  6815 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-16 18:15:24.857  6360  6775 D HeadsetStateMachine: Disconnected process message: 9
,08-16 18:15:24.857  6360  6775 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-16 18:15:24.867   281   683 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false,
08-16 18:15:24.867   281   683 V voice   : voice_set_parameters: enter: A2dpSuspended=false
,08-16 18:15:24.867   281   683 V voice   : voice_set_parameters: exit with code(-2)
08-16 18:15:24.867  1322  1322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-16 18:15:24.867   281   683 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-16 18:15:24.867   281   683 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-16 18:15:24.867   281   683 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
,08-16 18:15:24.867  1014  1026 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-16 18:15:24.867   281   683 V audio_hw_primary: adev_set_parameters: exit
08-16 18:15:24.867  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-16 18:15:24.867  6360  6775 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
08-16 18:15:24.867  6360  6815 D BluetoothSocket: bindListen(): myUserId = 0
08-16 18:15:24.867  6360  6815 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 18:15:24.867  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:24.867  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-16 18:15:24.867  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-16 18:15:24.867  6360  6815 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
08-16 18:15:24.867  6360  6815 D BluetoothSocket: bindListen(), new LocalSocket 
08-16 18:15:24.867  6360  6815 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-16 18:15:24.877  6360  6815 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@baf1379
08-16 18:15:24.877  6360  6815 D BluetoothSocket: channel: 5
,08-16 18:15:24.877  1322  1322 D DockEventReceiver: finishStartingService: stopping service
,08-16 18:15:24.877  1322  1322 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 18:15:24.887  1171  1171 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:24.887  1171  1171 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-16 18:15:24.887  6360  6360 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e014ed6
08-16 18:15:24.887  6360  6360 D BtConfig.SecureMode: isSecureModeOn:false
,08-16 18:15:24.897  1014  1555 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:24.897  1014  1555 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-16 18:15:24.897  1014  1555 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:24.897  1014  1555 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:24.897  1014  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:24.907  1931  1931 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-16 18:15:24.917  1014  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 18:15:24.917  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-16 18:15:24.917  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:24.917  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 18:15:24.917  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:24.927  1014  1719 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-16 18:15:24.927  1931  6824 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-16 18:15:24.927  1931  1931 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-16 18:15:24.937  6360  6825 D BluetoothSocket: bindListen(): myUserId = 0
,08-16 18:15:24.937  6360  6825 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 18:15:24.937  6360  6825 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
,08-16 18:15:24.937  6360  6825 D BluetoothSocket: bindListen(), new LocalSocket 
08-16 18:15:24.937  6360  6825 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,08-16 18:15:24.937  6360  6825 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2a846e35
,08-16 18:15:24.947  6360  6825 D BluetoothSocket: channel: 12
08-16 18:15:24.947  6360  6825 I BtOppRfcommListener: Accept thread started.
,08-16 18:15:25.097  1014  1555 I art     : Explicit concurrent mark sweep GC freed 46084(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 2.477ms total 162.528ms
,08-16 18:15:25.097  1014  1555 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 18:15:25.097  1014  1555 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:25.097  1014  1555 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:25.097  1014  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:25.107  1014  1483 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 18:15:25.107  1014  1483 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:25.107  1014  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:25.107  1014  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:25.117  1931  6824 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-16 18:15:25.857  1014  1491 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-16 18:15:25.857  1014  1491 D BatteryService: level:91, scale:100, status:2, health:2, present:true, voltage: 4168, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,08-16 18:15:25.857  1014  1491 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,08-16 18:15:25.857  1171  1171 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-16 18:15:25.857  1014  1491 D BatteryService: stay LED for charging,
,08-16 18:15:25.857  1171  1171 D KeyguardUpdateMonitor: handleBatteryUpdate
08-16 18:15:25.857  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-16 18:15:25.857  1014  1014 I MotionRecognitionService: Plugged,
08-16 18:15:25.857  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,08-16 18:15:25.867  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
,08-16 18:15:25.867  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 91
,08-16 18:15:25.877  6360  6360 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-16 18:15:25.877  6360  6775 D HeadsetStateMachine: Disconnected process message: 10
,08-16 18:15:25.887  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:91 status:2 health:2
,08-16 18:15:25.887  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:91 status:2 health:2
,08-16 18:15:25.887  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:91 status:2 health:2
,08-16 18:15:26.197  1014  2752 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-16 18:15:26.467   286   286 E SMD     : DCD OFF
,08-16 18:15:26.757  6168  6220 D BluetoothAdapter: disable(),
,08-16 18:15:26.757  1014  1558 D SettingsProvider: name = bluetooth_on,
,08-16 18:15:26.767  6360  6766 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-16 18:15:26.767  6360  6766 D BluetoothAdapterProperties: Setting state to 13
08-16 18:15:26.767  6360  6766 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 18:15:26.767  6360  6766 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 18:15:26.767  6360  6766 D BluetoothAdapterService: updateAdapterState state is 13
,08-16 18:15:26.767  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:26.767  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-16 18:15:26.767  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:26.767  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:26.767  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:26.777  6360  6360 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-16 18:15:26.777  6360  6360 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@25f542ca, channel: 19, state: LISTENING
08-16 18:15:26.777  6360  6360 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@25f542ca, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@cfa87c3, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@16032c3bmSocket: android.net.LocalSocket@775ff58 impl:android.net.LocalSocketImpl@371ab8b1 fd:FileDescriptor[75]
,08-16 18:15:26.777  6360  6360 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@775ff58 impl:android.net.LocalSocketImpl@371ab8b1 fd:FileDescriptor[75]
,08-16 18:15:26.777  1322  1322 D BluetoothPbap: Proxy object disconnected
08-16 18:15:26.777  6360  6766 D BluetoothAdapterService: Autoconnection is available 
08-16 18:15:26.777  6360  6766 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-16 18:15:26.777  6360  6766 D BluetoothAdapterService: terminating service from this receiver
,08-16 18:15:26.777  1322  1322 D PbapServerProfile: Bluetooth service disconnected
,08-16 18:15:26.777  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-16 18:15:26.777  1014  1014 I InputMethodManagerService: [BT Setting State] State =13
,08-16 18:15:26.787  1171  1171 D BluetoothTile:  onBluetoothStateChange:
,08-16 18:15:26.787  1171  1171 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-16 18:15:26.787  1171  1171 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:26.787  1171  1171 D BluetoothTile:  getBluetoothState : 13
,08-16 18:15:26.787  1171  1720 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 18:15:26.797  1171  1720 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 18:15:26.797  1773  1773 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 18:15:26.797  1322  1322 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 18:15:26.797  1014  1719 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 18:15:26.797  6360  6360 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2ee5117, channel: 5, state: LISTENING
,08-16 18:15:26.797  6360  6360 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2ee5117, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@baf1379, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2af7b904mSocket: android.net.LocalSocket@22f12eed impl:android.net.LocalSocketImpl@154b6122 fd:FileDescriptor[77]
08-16 18:15:26.797  6360  6360 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@22f12eed impl:android.net.LocalSocketImpl@154b6122 fd:FileDescriptor[77]
,08-16 18:15:26.807  1014  3070 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-16 18:15:26.807  6360  6360 I BtOppRfcommListener: stopping Accept Thread
08-16 18:15:26.807  6360  6360 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@afce7b3, channel: 12, state: LISTENING
08-16 18:15:26.807  6360  6360 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@afce7b3, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2a846e35, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@23b96170mSocket: android.net.LocalSocket@3e3ecce9 impl:android.net.LocalSocketImpl@8626d6e fd:FileDescriptor[80]
08-16 18:15:26.807  6360  6360 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3e3ecce9 impl:android.net.LocalSocketImpl@8626d6e fd:FileDescriptor[80]
08-16 18:15:26.807  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 18:15:26.807  1171  1720 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-16 18:15:26.807  6360  6825 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 18:15:26.807  6360  6825 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-16 18:15:26.807  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-16 18:15:26.807  6168  6168 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 18:15:26.807  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:26.807  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:26.807  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:26.807  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:15:26.807  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:15:26.807  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:26.807  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:26.807  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:15:26.807  6168  6168 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 18:15:26.807  1014  1359 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-16 18:15:26.807  1014  1359 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:26.807  1014  1359 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:26.807  1014  1359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 18:15:26.817  6168  6168 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 18:15:26.817  1014  1555 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 18:15:26.817  1014  1555 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-16 18:15:26.817  6360  6766 D BluetoothAdapterProperties: onBluetoothDisable()
,08-16 18:15:26.817  6360  6766 D BluetoothAdapterProperties: mDiscovering is false
,08-16 18:15:26.817  1014  3070 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-16 18:15:26.817  1014  1555 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:26.817  1014  1555 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:26.817  1014  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:26.817  6360  6766 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-16 18:15:26.817  1322  1322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 18:15:26.817  6168  6168 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 18:15:26.817  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:26.817  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:26.817  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:26.817  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:15:26.817  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:15:26.817  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:26.817  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:26.817  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:15:26.827  6168  6168 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:15:26.827  6168  6168 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 18:15:26.827  6360  6769 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-16 18:15:26.827  6360  6769 D BluetoothAdapterProperties: Scan Mode:20
,08-16 18:15:26.827  1014  1557 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-16 18:15:26.827  1014  1557 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-16 18:15:26.827  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:26.827  1014  1557 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:26.827  1014  1557 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 18:15:26.837  1014  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
08-16 18:15:26.837  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:26.837  6360  6766 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-16 18:15:26.837  6360  6766 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-16 18:15:26.837  6360  6766 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-16 18:15:26.837  6360  6766 E bt-btif : cmd socket is not created
,08-16 18:15:26.837  6360  6766 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 18:15:26.837  6360  6785 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
,08-16 18:15:26.847  6360  6785 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-16 18:15:26.847  6360  6785 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 18:15:26.847  6360  6785 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 18:15:26.847  6360  6785 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-16 18:15:26.857  1322  1322 D DockEventReceiver: finishStartingService: stopping service
,08-16 18:15:26.857  6360  6360 V BluetoothOppManager: cleanUp...
,08-16 18:15:26.857  1322  1322 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 18:15:26.867  1171  1171 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:26.867  1171  1171 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-16 18:15:26.887  1931  1931 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-16 18:15:26.887  1931  1931 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-16 18:15:26.967  1014  2723 D SSRM:n  : SIOP:: AP = 330
,08-16 18:15:27.047  6360  6785 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-16 18:15:27.047  6360  6785 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 18:15:27.047  6360  6785 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 18:15:27.047  6360  6785 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 18:15:27.047  6360  6785 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 18:15:27.047  6360  6785 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 18:15:27.047  6360  6785 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 18:15:27.047  6360  6785 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 18:15:27.047  6360  6785 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 18:15:27.047  6360  6785 W bt-btif : ag scb idx 1 not allocated
08-16 18:15:27.047  6360  6785 W bt-btif : ag scb idx 2 not allocated
08-16 18:15:27.047  6360  6785 E bt-btif : BTA AG is already disabled, ignoring ...
08-16 18:15:27.047  6360  6807 I bt_userial_mct: exiting userial_read_thread
08-16 18:15:27.047  6360  6807 D bt_userial_mct: Leaving userial_evt_read_thread()
08-16 18:15:27.047  6360  6769 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-16 18:15:27.047  6360  6787 I bt_vendor: hw_epilog_process
08-16 18:15:27.047  6360  6769 D bt_userial_mct: userial_close
08-16 18:15:27.047  6360  6769 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-16 18:15:27.367  6360  6769 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-16 18:15:27.367  6360  6769 I bt_vendor: bluetooth satus is on
08-16 18:15:27.367  6360  6769 I bt_vendor: bt-vendor : resetting BT status
08-16 18:15:27.367  6360  6769 I bt_vendor: Starting hciattach daemon
08-16 18:15:27.367  6360  6769 I bt_vendor: try to set false
,08-16 18:15:27.367  6360  6769 I bt_vendor: Starting hciattach daemon
08-16 18:15:27.367  6360  6769 I bt_vendor: try to set false
,08-16 18:15:27.367  6360  6769 I bt_vendor: cleanup
,08-16 18:15:27.367  6360  6785 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-16 18:15:27.367  6360  6769 I GKI_LINUX: GKI_exit_task 0 done
08-16 18:15:27.367  6360  6769 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-16 18:15:27.367  6360  6766 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-16 18:15:27.367  6360  6766 D BtConfig.SecureMode: isSecureModeOn:false
08-16 18:15:27.367  6360  6766 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,08-16 18:15:27.367  6360  6766 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService,
,08-16 18:15:27.367  6360  6766 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService,
08-16 18:15:27.367  1014  1558 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
,08-16 18:15:27.367  6360  6766 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-16 18:15:27.367  1014  1558 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-16 18:15:27.367  1014  1558 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:27.367  1014  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:27.367  1014  1558 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:27.367  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0,
08-16 18:15:27.367  1014  1558 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 18:15:27.377  1014  3070 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:27.367  6360  6766 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-16 18:15:27.377  1014  3070 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-16 18:15:27.367  6360  6766 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-16 18:15:27.377  1014  1555 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:27.367  6360  6766 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-16 18:15:27.377  1014  1555 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-16 18:15:27.367  6360  6360 D BtGatt.DebugUtils: handleDebugAction() action=null,
08-16 18:15:27.377  6360  6360 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 18:15:27.377  1014  1359 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:27.377  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:27.377  1014  1359 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-16 18:15:27.377  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:27.377  6360  6360 D BtGatt.GattService: stop()
08-16 18:15:27.377  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 18:15:27.377  6360  6360 D BtGatt.AdvertiseManager: advertise clients cleared
08-16 18:15:27.377  6360  6360 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e014ed6
08-16 18:15:27.377  6360  6766 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-16 18:15:27.377  6360  6766 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-16 18:15:27.377  6360  6766 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-16 18:15:27.377  1014  3070 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:27.377  1014  3070 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:27.377  1014  3070 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 18:15:27.377  6360  6766 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-16 18:15:27.377  6360  6766 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-16 18:15:27.377  6360  6766 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-16 18:15:27.377  1014  1555 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:27.377  1014  1555 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:27.377  1014  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 18:15:27.377  6360  6766 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-16 18:15:27.377  6360  6766 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-16 18:15:27.377  6360  6766 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-16 18:15:27.387  1014  1483 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:27.387  1014  1359 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:27.387  1014  1483 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-16 18:15:27.387  1014  1359 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:27.387  1014  1359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 18:15:27.387  6360  6766 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-16 18:15:27.387  6360  6766 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-16 18:15:27.387  6360  6766 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-16 18:15:27.387  1014  1483 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:27.387  1014  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:27.387  1014  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 18:15:27.387  6360  6766 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-16 18:15:27.387  6360  6766 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-16 18:15:27.387  6360  6766 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-16 18:15:27.387  1014  1345 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:27.387  1014  1345 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-16 18:15:27.387  1014  1345 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:27.387  1014  1345 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 18:15:27.387  1014  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:27.397  6360  6766 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-16 18:15:27.397  6360  6766 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-16 18:15:27.397  6360  6766 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-16 18:15:27.397  1014  1558 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:27.397  1014  1558 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-16 18:15:27.397  1014  1558 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:27.397  1014  1558 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 18:15:27.397  1014  1558 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:27.397  6360  6766 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-16 18:15:27.397  6360  6766 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-16 18:15:27.397  6360  6766 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-16 18:15:27.397  6360  6766 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-16 18:15:27.397  6360  6766 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-16 18:15:27.397  6360  6766 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-16 18:15:27.397  6360  6766 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-16 18:15:27.397  6360  6766 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-16 18:15:27.397  6360  6766 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-16 18:15:27.397  6360  6766 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-16 18:15:27.397  6360  6766 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-16 18:15:27.397  6360  6766 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-16 18:15:27.397  6360  6360 E BluetoothAdapterService(503402198): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-16 18:15:27.397  6360  6766 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-16 18:15:27.397  6360  6360 D HeadsetService: Received stop request...Stopping profile...
08-16 18:15:27.397  6360  6360 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e014ed6
,08-16 18:15:27.407  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-16 18:15:27.407  1322  1322 D HeadsetProfile: Bluetooth service disconnected
,08-16 18:15:27.407  6360  6360 D A2dpService: Received stop request...Stopping profile...
,08-16 18:15:27.407  6360  6780 D A2dpStateMachine: Exit Disconnected: -1
,08-16 18:15:27.407  6360  6360 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e014ed6
,08-16 18:15:27.407  1014  1014 D BluetoothA2dp: Proxy object disconnected,
08-16 18:15:27.407  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-16 18:15:27.417  6360  6360 D HidService: Received stop request...Stopping profile...
08-16 18:15:27.417  6360  6360 D HidService: Stopping Bluetooth HidService
08-16 18:15:27.417  6360  6360 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 18:15:27.417  6360  6360 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-16 18:15:27.417  6360  6360 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 18:15:27.417  6360  6360 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e014ed6
,08-16 18:15:27.417  1322  1322 D BluetoothA2dp: Proxy object disconnected
08-16 18:15:27.417  1322  1322 D A2dpProfile: Bluetooth service disconnected
08-16 18:15:27.417  2864  2864 D BluetoothA2dp: Proxy object disconnected
,08-16 18:15:27.417  1322  1322 D BluetoothInputDevice: Proxy object disconnected
08-16 18:15:27.417  1322  1322 D HidProfile: Bluetooth service disconnected
08-16 18:15:27.417  6360  6360 D HealthService: Received stop request...Stopping profile...
08-16 18:15:27.417  6360  6360 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e014ed6
,08-16 18:15:27.417  6360  6360 D PanService: Received stop request...Stopping profile...
,08-16 18:15:27.417  6360  6360 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e014ed6
,08-16 18:15:27.417  1014  1014 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-16 18:15:27.427  6360  6360 D BluetoothMapService: Received stop request...Stopping profile...
08-16 18:15:27.427  1322  1322 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 18:15:27.427  1322  1322 D PanProfile: Bluetooth service disconnected
,08-16 18:15:27.427  6360  6360 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e014ed6
,08-16 18:15:27.427  6360  6360 D SapService: Received stop request...Stopping profile...
08-16 18:15:27.427  6360  6360 D SapService: Stopping Bluetooth SapService
08-16 18:15:27.427  6360  6360 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e014ed6
08-16 18:15:27.427  1322  1322 D BluetoothMap: Proxy object disconnected
08-16 18:15:27.427  1322  1322 D MapProfile: Bluetooth service disconnected
08-16 18:15:27.427  1322  1322 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-16 18:15:27.427  1322  1322 D SapProfile: Bluetooth service disconnected
,08-16 18:15:27.427  6360  6360 E BluetoothAdapterService(503402198): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-16 18:15:27.427  6360  6360 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 18:15:27.427  6360  6360 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-16 18:15:27.427  6360  6360 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-16 18:15:27.427  6360  6360 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-16 18:15:27.437  6360  6360 E BluetoothAdapterService(503402198): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-16 18:15:27.437  6360  6360 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 18:15:27.437  6360  6360 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-16 18:15:27.437  6360  6781 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-16 18:15:27.437  6360  6360 I GKI_LINUX: GKI_exit_task 2 done
08-16 18:15:27.437  6360  6360 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-16 18:15:27.437  6360  6360 D BluetoothA2dp: Proxy object disconnected
08-16 18:15:27.437  6360  6360 D BluetoothAdapterService: Bluetooth A2dp source service disconnected,
08-16 18:15:27.437  6360  6360 E BluetoothAdapterService(503402198): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-16 18:15:27.437  6360  6360 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 18:15:27.437  6360  6360 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-16 18:15:27.437  6360  6360 E BluetoothAdapterService(503402198): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
,08-16 18:15:27.437  6360  6360 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 18:15:27.437  6360  6360 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-16 18:15:27.437  6360  6360 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-16 18:15:27.437  6360  6360 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 18:15:27.437  6360  6360 E BluetoothAdapterService(503402198): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-16 18:15:27.437  6360  6360 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-16 18:15:27.437  6360  6360 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-16 18:15:27.437  6360  6360 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 18:15:27.437  6360  6360 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-16 18:15:27.437  6360  6360 E BluetoothAdapterService(503402198): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-16 18:15:27.437  6360  6360 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-16 18:15:27.437  6360  6360 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-16 18:15:27.437  6360  6360 E BluetoothAdapterService(503402198): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-16 18:15:27.437  6360  6360 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-16 18:15:27.437  6360  6360 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-16 18:15:27.437  6360  6766 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,08-16 18:15:27.437  6360  6766 D BluetoothAdapterProperties: Setting state to 10
08-16 18:15:27.437  6360  6766 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-16 18:15:27.437  6360  6766 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 18:15:27.437  6360  6766 D BluetoothAdapterService: updateAdapterState state is 10
,08-16 18:15:27.447  1322  1333 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 18:15:27.447  6360  6766 D BluetoothAdapterService: Autoconnection is available 
08-16 18:15:27.447  6360  6766 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-16 18:15:27.447  6360  6766 I BluetoothAdapterState: Entering OffState
,08-16 18:15:27.447  6360  6814 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 18:15:27.447  6360  6814 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-16 18:15:27.447  1014  1044 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 18:15:27.447  1322  1331 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-16 18:15:27.447  1322  6625 D BluetoothMap: onBluetoothStateChange: up=false
,08-16 18:15:27.447  1322  1333 D Bluetoothsap: onBluetoothStateChange: up=false
,08-16 18:15:27.447  1322  1333 D Bluetoothsap: Unbinding service...
,08-16 18:15:27.447  1014  1044 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 18:15:27.447  1014  1044 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 18:15:27.457  1439  1453 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 18:15:27.457  1439  1453 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 18:15:27.457  6168  6178 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 18:15:27.457  6168  6178 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-16 18:15:27.457  6168  6178 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,08-16 18:15:27.457  6168  6178 D BluetoothLeAdvertiser: Exit stop advertising
08-16 18:15:27.457  6168  6178 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-16 18:15:27.457  6168  6178 D BluetoothLeScanner: Exiting stopAllScan
,08-16 18:15:27.457  2864  2882 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 18:15:27.457  2864  2882 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 18:15:27.457  1322  6625 D BluetoothPbap: onBluetoothStateChange: up=false
,08-16 18:15:27.457  6329  6338 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 18:15:27.457  6329  6338 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 18:15:27.457  1454  1635 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 18:15:27.457  1454  1635 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 18:15:27.467  2864  2873 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 18:15:27.467  1931  1940 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 18:15:27.467  1931  1940 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 18:15:27.467  6360  6770 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 18:15:27.467  1430  1443 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 18:15:27.467  1430  1443 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 18:15:27.467  1322  1331 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 18:15:27.467  1322  1331 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 18:15:27.467  1171  1202 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 18:15:27.467  1171  1202 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 18:15:27.467  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 11 receivers.
,08-16 18:15:27.477  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-16 18:15:27.477  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-16 18:15:27.477  1014  1014 I InputMethodManagerService: [BT Setting State] State =10
08-16 18:15:27.477  1014  1014 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-16 18:15:27.477  6360  6769 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-16 18:15:27.487  6360  6360 I GKI_LINUX: GKI_exit_task 1 done
08-16 18:15:27.487  6360  6360 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-16 18:15:27.487  6360  6360 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-16 18:15:27.487  1171  1171 D BluetoothAdapter: 224888337: getState() :  mService = null. Returning STATE_OFF
08-16 18:15:27.487  1171  1171 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-16 18:15:27.487  1171  1720 D BluetoothAdapter: 224888337: getState() :  mService = null. Returning STATE_OFF
,08-16 18:15:27.487  1171  1171 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 18:15:27.487  1171  1171 D BluetoothTile:  getBluetoothState : 10
08-16 18:15:27.487  1171  1720 D BluetoothAdapter: 224888337: getState() :  mService = null. Returning STATE_OFF
,08-16 18:15:27.487  1171  1171 D BluetoothAdapter: 224888337: getState() :  mService = null. Returning STATE_OFF
,08-16 18:15:27.487  1171  1171 D BluetoothAdapter: 224888337: getState() :  mService = null. Returning STATE_OFF
,08-16 18:15:27.487  6360  6360 I art     : System.exit called, status: 0
08-16 18:15:27.487  6360  6360 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-16 18:15:27.487  1014  1215 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 18:15:27.487  1014  1491 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-16 18:15:27.487  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 18:15:27.497  1773  1773 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 18:15:27.497  1322  1322 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 18:15:27.497  1931  2109 D BluetoothAdapter: 107551660: getState() :  mService = null. Returning STATE_OFF
08-16 18:15:27.497  1931  2109 D BluetoothAdapter: 107551660: getState() :  mService = null. Returning STATE_OFF
,08-16 18:15:27.497  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:27.497  1014  3070 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 18:15:27.497  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:27.497  1014  3070 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-16 18:15:27.497  1014  3070 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:27.497  1014  3070 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:27.497  1322  1322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 18:15:27.497  1014  3070 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:27.507  1014  1345 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-16 18:15:27.507  1014  1345 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-16 18:15:27.507  1014  1345 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:27.507  1014  1345 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:27.507  1014  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-16 18:15:27.507  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-16 18:15:27.517  1322  1322 D DockEventReceiver: finishStartingService: stopping service
,08-16 18:15:27.517  1322  1322 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 18:15:27.527  1171  1171 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:27.527  1171  1171 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-16 18:15:27.607  1014  1483 I ActivityManager: Process com.android.bluetooth (pid 6360)(adj 0) has died(64,1077)
,08-16 18:15:27.617  1931  1931 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-16 18:15:27.617  1014  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 18:15:27.617  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-16 18:15:27.617  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:27.617  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 18:15:27.617  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:27.637  1931  6843 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-16 18:15:27.637  1931  1931 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-16 18:15:27.727  1931  2094 I art     : Explicit concurrent mark sweep GC freed 62263(3MB) AllocSpace objects, 65(3MB) LOS objects, 40% free, 14MB/24MB, paused 1.466ms total 86.713ms
,08-16 18:15:27.727  1014  1345 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 18:15:27.727  1014  1345 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:27.727  1014  1345 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:27.727  1014  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:27.737  1931  6843 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-16 18:15:27.787  1014  1330 E Watchdog: !@Sync 4
,08-16 18:15:28.437   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-16 18:15:29.437   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-16 18:15:29.467   286   286 E SMD     : DCD OFF,
,08-16 18:15:29.767  6168  6220 D io.jxcore.node.ConnectivityMonitor: stop,
08-16 18:15:29.767  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:30.437   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-16 18:15:31.437   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-16 18:15:32.047  1014  1969 V SAMP_SPCM_test: CSC File load.. 
,08-16 18:15:32.057  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,08-16 18:15:32.057  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
08-16 18:15:32.057  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
,08-16 18:15:32.057  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
08-16 18:15:32.057  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
08-16 18:15:32.057  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming,
08-16 18:15:32.057  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
08-16 18:15:32.057  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
08-16 18:15:32.057  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
,08-16 18:15:32.057  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
08-16 18:15:32.057  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
08-16 18:15:32.057  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
,08-16 18:15:32.057  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
08-16 18:15:32.057  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
08-16 18:15:32.057  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
,08-16 18:15:32.057  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
08-16 18:15:32.057  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
08-16 18:15:32.057  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
,08-16 18:15:32.057  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
08-16 18:15:32.057  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
08-16 18:15:32.057  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time,
,08-16 18:15:32.087  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,08-16 18:15:32.087  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
,08-16 18:15:32.087  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
,08-16 18:15:32.087  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
08-16 18:15:32.097  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
08-16 18:15:32.097  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
,08-16 18:15:32.097  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
08-16 18:15:32.097  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
,08-16 18:15:32.097  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
08-16 18:15:32.097  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
,08-16 18:15:32.097  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
08-16 18:15:32.097  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
,08-16 18:15:32.097  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
,08-16 18:15:32.097  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
08-16 18:15:32.097  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
,08-16 18:15:32.097  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
08-16 18:15:32.097  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings,
,08-16 18:15:32.097  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
08-16 18:15:32.097  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
08-16 18:15:32.097  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-16 18:15:32.097  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-16 18:15:32.107  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
08-16 18:15:32.107  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
08-16 18:15:32.107  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
08-16 18:15:32.107  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
08-16 18:15:32.107  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
08-16 18:15:32.107  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
08-16 18:15:32.107  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
08-16 18:15:32.107  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
08-16 18:15:32.107  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
08-16 18:15:32.107  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
08-16 18:15:32.107  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
08-16 18:15:32.107  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
08-16 18:15:32.107  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
08-16 18:15:32.107  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
08-16 18:15:32.107  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
08-16 18:15:32.107  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
08-16 18:15:32.107  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
08-16 18:15:32.107  1014  1969 W DeviceAdminInfo: Unknown tag under, uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
08-16 18:15:32.107  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
08-16 18:15:32.107  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
08-16 18:15:32.107  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
08-16 18:15:32.107  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
08-16 18:15:32.107  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
08-16 18:15:32.107  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
08-16 18:15:32.107  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
08-16 18:15:32.107  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
08-16 18:15:32.107  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
08-16 18:15:32.107  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
08-16 18:15:32.107  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
08-16 18:15:32.107  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
08-16 18:15:32.107  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-16 18:15:32.107  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
08-16 18:15:32.107  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
08-16 18:15:32.107  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
,08-16 18:15:32.107  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
08-16 18:15:32.107  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
08-16 18:15:32.107  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-16 18:15:32.107  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
,08-16 18:15:32.107  1014  1969 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,08-16 18:15:32.117  1014  1969 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm,
,08-16 18:15:32.117  1014  1969 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:32.117  1014  1969 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:32.117  1014  1969 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:32.117  1014  1969 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:32.127  1014  1969 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=6847 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,08-16 18:15:32.137  6847  6847 E Zygote  : MountEmulatedStorage(),
08-16 18:15:32.137  6847  6847 E Zygote  : v2
08-16 18:15:32.137  6847  6847 I libpersona: KNOX_SDCARD checking this for 1000,
08-16 18:15:32.137  6847  6847 I libpersona: KNOX_SDCARD not a persona
,08-16 18:15:32.137  6847  6847 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-16 18:15:32.147  6847  6847 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-16 18:15:32.147  6847  6847 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-16 18:15:32.167  6847  6847 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:32.167  6847  6847 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:32.187  6847  6847 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-16 18:15:32.227  1014  1969 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,08-16 18:15:32.437   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 18:15:32.467   286   286 E SMD     : DCD OFF
,08-16 18:15:32.767  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 18:15:32.767  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3ba94ad3 added. We now have 6 listener(s)
,08-16 18:15:32.767  6168  6220 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 18:15:32.777  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 18:15:32.777  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2e135610 added. We now have 7 listener(s)
08-16 18:15:32.777  6168  6220 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 18:15:32.777  6168  6220 I System.out: IsBluetoothEnabled
,08-16 18:15:32.777  6168  6220 D BluetoothAdapter: disable()
,08-16 18:15:32.777  1014  1555 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-16 18:15:32.787  6168  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:32.787  6168  6220 D BluetoothAdapter: enable()
,08-16 18:15:32.787  1014  1558 W ActivityManager: Permission Denial: getCurrentUser() from pid=6168, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,08-16 18:15:32.787  1014  1558 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-16 18:15:32.787  1014  1558 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6168, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-16 18:15:32.787  1014  1558 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-16 18:15:32.787  1014  1558 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
08-16 18:15:32.787  1014  1558 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
08-16 18:15:32.787  1014  1558 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
08-16 18:15:32.787  1014  1558 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-16 18:15:32.787  1014  1558 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 18:15:32.787  1014  1558 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 18:15:32.787  1014  1558 D SettingsProvider: name = bluetooth_on
,08-16 18:15:32.797  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-16 18:15:32.797  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 18:15:32.797  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
08-16 18:15:32.797  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-16 18:15:32.807  1014  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:32.807  1014  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:32.807  1014  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:32.807  1014  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:32.817  6866  6866 E Zygote  : MountEmulatedStorage(),
08-16 18:15:32.817  6866  6866 E Zygote  : v2,
,08-16 18:15:32.827  6866  6866 I libpersona: KNOX_SDCARD checking this for 1002
08-16 18:15:32.827  6866  6866 I libpersona: KNOX_SDCARD not a persona
,08-16 18:15:32.827  6866  6866 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
08-16 18:15:32.827  1014  1044 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6866 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-16 18:15:32.827  6866  6866 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-16 18:15:32.837  6866  6866 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-16 18:15:32.857  6866  6866 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:32.867  6866  6866 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:32.907  6866  6866 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-16 18:15:32.907  6866  6866 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-16 18:15:32.937  6866  6866 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-16 18:15:32.967  6866  6866 D BtSettings.ProfileConfig: Adding GattService
,08-16 18:15:32.967  6866  6866 D BtSettings.ProfileConfig: Adding HeadsetService
,08-16 18:15:32.967  6866  6866 D BtSettings.ProfileConfig: Adding A2dpService
,08-16 18:15:32.977  6866  6866 D BtSettings.ProfileConfig: Adding HidService
,08-16 18:15:32.977  6866  6866 D BtSettings.ProfileConfig: Adding HealthService
,08-16 18:15:32.977  6866  6866 D BtSettings.ProfileConfig: Adding PanService
,08-16 18:15:32.977  6866  6866 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-16 18:15:32.977  6866  6866 D BtSettings.ProfileConfig: Adding SapService
,08-16 18:15:32.977  6866  6866 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-16 18:15:32.977  6866  6866 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-16 18:15:32.977  6866  6866 D BtSettings.ProfileConfig: Adding SapClientService
,08-16 18:15:32.977  6866  6866 D BtSettings.ProfileConfig: Adding HidDevService
,08-16 18:15:32.977  6866  6866 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-16 18:15:32.977  1014  1026 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-16 18:15:32.987  1014  1026 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-16 18:15:32.987  1014  1026 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 18:15:32.987  1014  1026 D SettingsProvider: selectionArgs: false
08-16 18:15:32.987  1014  1026 D SettingsProvider: selectionArgs: 1002
,08-16 18:15:32.987  1014  1026 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-16 18:15:32.987  1014  1026 D SettingsProvider: ret = -1
,08-16 18:15:32.987  1014  1215 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,08-16 18:15:32.987  1014  1215 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 18:15:32.987  1014  1215 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 18:15:32.987  1014  1215 D SettingsProvider: selectionArgs: false
08-16 18:15:32.987  1014  1215 D SettingsProvider: selectionArgs: 1002
,08-16 18:15:32.987  1014  1215 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 18:15:32.987  1014  1215 D SettingsProvider: ret = -1
08-16 18:15:32.987  1014  1491 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-16 18:15:32.987  1014  1491 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 18:15:32.987  1014  1491 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-16 18:15:32.987  1014  1491 D SettingsProvider: selectionArgs: false
08-16 18:15:32.987  1014  1491 D SettingsProvider: selectionArgs: 1002
08-16 18:15:32.987  1014  1491 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 18:15:32.987  1014  1491 D SettingsProvider: ret = -1
08-16 18:15:32.987  1014  1483 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-16 18:15:32.987  1014  1483 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 18:15:32.987  1014  1483 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-16 18:15:32.987  1014  1483 D SettingsProvider: selectionArgs: false
08-16 18:15:32.987  1014  1483 D SettingsProvider: selectionArgs: 1002
08-16 18:15:32.987  1014  1483 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-16 18:15:32.987  1014  1483 D SettingsProvider: ret = -1,
,08-16 18:15:32.987  1014  1359 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
,08-16 18:15:32.987  1014  1359 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 18:15:32.987  1014  1359 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 18:15:32.987  1014  1359 D SettingsProvider: selectionArgs: false
08-16 18:15:32.987  1014  1359 D SettingsProvider: selectionArgs: 1002
08-16 18:15:32.987  1014  1359 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 18:15:32.987  1014  1359 D SettingsProvider: ret = -1
08-16 18:15:32.987  1014  1555 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-16 18:15:32.987  1014  1555 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 18:15:32.987  1014  1555 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 18:15:32.987  1014  1555 D SettingsProvider: selectionArgs: false
08-16 18:15:32.987  1014  1555 D SettingsProvider: selectionArgs: 1002
08-16 18:15:32.987  1014  1555 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 18:15:32.987  1014  1555 D SettingsProvider: ret = -1
08-16 18:15:32.987  1014  1345 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-16 18:15:32.987  1014  1345 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 18:15:32.987  1014  1345 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 18:15:32.987  1014  1345 D SettingsProvider: selectionArgs: false
08-16 18:15:32.987  1014  1345 D SettingsProvider: selectionArgs: 1002
08-16 18:15:32.987  1014  1345 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 18:15:32.987  1014  1345 D SettingsProvider: ret = -1
08-16 18:15:32.987  1014  1719 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-16 18:15:32.987  1014  1719 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 18:15:32.987  1014  1719 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 18:15:32.987  1014  1719 D SettingsProvider: selectionArgs: false
08-16 18:15:32.987  1014  1719 D SettingsProvider: selectionArgs: 1002
08-16 18:15:32.987  1014  1719 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 18:15:32.987  1014  1719 D SettingsProvider: ret = -1
08-16 18:15:32.987  1014  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-16 18:15:32.987  1014  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 18:15:32.987  1014  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 18:15:32.987  1014  1027 D SettingsProvider: selectionArgs: false
08-16 18:15:32.987  1014  1027 D SettingsProvider: selectionArgs: 1002
08-16 18:15:32.997  1014  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 18:15:32.997  1014  1027 D SettingsProvider: ret = -1
,08-16 18:15:32.997  1014  1558 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-16 18:15:32.997  1014  1558 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 18:15:32.997  1014  1558 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 18:15:32.997  1014  1558 D SettingsProvider: selectionArgs: false
,08-16 18:15:32.997  1014  1558 D SettingsProvider: selectionArgs: 1002
08-16 18:15:32.997  1014  1558 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 18:15:32.997  1014  1558 D SettingsProvider: ret = -1
08-16 18:15:32.997  1014  1557 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-16 18:15:32.997  1014  1557 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-16 18:15:32.997  1014  1557 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 18:15:32.997  1014  1557 D SettingsProvider: selectionArgs: false
08-16 18:15:32.997  1014  1557 D SettingsProvider: selectionArgs: 1002
08-16 18:15:32.997  1014  1557 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 18:15:32.997  1014  1557 D SettingsProvider: ret = -1
,08-16 18:15:32.997  1014  3070 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-16 18:15:32.997  1014  3070 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 18:15:32.997  1014  3070 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 18:15:32.997  1014  3070 D SettingsProvider: selectionArgs: false,
08-16 18:15:32.997  1014  3070 D SettingsProvider: selectionArgs: 1002
08-16 18:15:32.997  1014  3070 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 18:15:32.997  1014  3070 D SettingsProvider: ret = -1,
,08-16 18:15:33.017  6866  6866 D BluetoothAdapterState: make
,08-16 18:15:33.017  6866  6866 I bluedroid: init,
,08-16 18:15:33.017  6866  6881 I BluetoothAdapterState: Entering OffState
,08-16 18:15:33.027  6866  6866 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf,
08-16 18:15:33.027  6866  6866 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-16 18:15:33.027  6866  6866 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-16 18:15:33.027  6866  6866 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 18:15:33.027  6866  6866 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-16 18:15:33.027  6866  6866 I bluedroid: get_profile_interface socket,
08-16 18:15:33.027  6866  6866 I bluedroid: get_profile_interface map_client
08-16 18:15:33.027  6866  6884 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-16 18:15:33.027  6866  6866 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-16 18:15:33.027  6866  6884 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,08-16 18:15:33.027  6866  6884 E BluetoothServiceJni: populateRssiValuesNative
08-16 18:15:33.027  6866  6884 I bluedroid: getModelRssiValues
08-16 18:15:33.027  6866  6884 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-16 18:15:33.027  6866  6884 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-16 18:15:33.037  1014  1014 D SettingsProvider: name = bluetooth_name
,08-16 18:15:33.037  6866  6884 D BluetoothAdapterProperties: Name is: A5-1
,08-16 18:15:33.037  6866  6866 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-16 18:15:33.037  1014  1133 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-16 18:15:33.037  1014  1133 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 18:15:33.037  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:33.037  1014  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:33.037  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:33.047  6866  6877 I bluedroid: config_hci_snoop_log
,08-16 18:15:33.047  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,08-16 18:15:33.047  1014  1044 D BluetoothManagerService: Ble is always on enable gatt
,08-16 18:15:33.047  1014  1044 I BluetoothManagerService: enableGattForLeMode, doBind called
08-16 18:15:33.047  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-16 18:15:33.047  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-16 18:15:33.047  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 18:15:33.057  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-16 18:15:33.057  6866  6866 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-16 18:15:33.057  1014  1044 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-16 18:15:33.057  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-16 18:15:33.057  6866  6881 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-16 18:15:33.057  6866  6881 D BluetoothAdapterProperties: Setting state to 11
,08-16 18:15:33.057  6866  6881 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-16 18:15:33.057  6866  6881 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 18:15:33.067  6866  6881 D BluetoothAdapterService: updateAdapterState state is 11
,08-16 18:15:33.067  6866  6881 D BluetoothAdapterService: Autoconnection is available 
,08-16 18:15:33.067  6866  6881 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-16 18:15:33.067  6866  6881 D BluetoothSecureManager: getInstant: null
,08-16 18:15:33.067  6866  6881 D BluetoothSecureManager: calling getMethod for getService
08-16 18:15:33.067  6866  6881 D BluetoothSecureManager: calling getService
,08-16 18:15:33.067  6866  6881 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@25914f29
,08-16 18:15:33.067  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:33.067  1014  1014 I InputMethodManagerService: [BT Setting State] State =11
,08-16 18:15:33.067  1014  1719 D BluetoothSecureManagerService: isSecureModeEnabled
08-16 18:15:33.067  1014  1719 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-16 18:15:33.077  6866  6881 D BtConfig.SecureMode: isSecureModeOn:false
08-16 18:15:33.077  6866  6881 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-16 18:15:33.077  6866  6881 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-16 18:15:33.077  6866  6881 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-16 18:15:33.077  6866  6881 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-16 18:15:33.077  6866  6881 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-16 18:15:33.077  6866  6881 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-16 18:15:33.077  6866  6881 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-16 18:15:33.077  6866  6881 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-16 18:15:33.077  6866  6881 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-16 18:15:33.077  1171  1171 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-16 18:15:33.077  1171  1171 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 18:15:33.087  1171  1171 D BluetoothTile:  getBluetoothState : 11
,08-16 18:15:33.087  6866  6881 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-16 18:15:33.087  6866  6881 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-16 18:15:33.087  6866  6881 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-16 18:15:33.087  6866  6881 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-16 18:15:33.087  1773  1773 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 18:15:33.087  6866  6881 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-16 18:15:33.087  6866  6881 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-16 18:15:33.087  1014  1558 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 18:15:33.087  6866  6881 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
,08-16 18:15:33.087  6866  6881 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-16 18:15:33.087  1014  1026 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-16 18:15:33.087  6866  6881 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-16 18:15:33.087  6866  6881 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-16 18:15:33.087  1171  1720 D BluetoothTile:  handleUpdatestate:false name:null
08-16 18:15:33.087  1171  1720 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-16 18:15:33.087  6866  6881 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-16 18:15:33.087  6866  6881 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-16 18:15:33.087  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-16 18:15:33.087  6866  6881 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-16 18:15:33.087  6866  6881 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-16 18:15:33.097  1322  1322 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 18:15:33.097  6866  6881 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService,
,08-16 18:15:33.097  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:33.097  1014  1491 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 18:15:33.097  1014  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-16 18:15:33.097  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:33.097  1014  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 18:15:33.107  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:33.107  6866  6881 D BluetoothBondStateMachine: make
,08-16 18:15:33.107  1322  1322 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 18:15:33.117  6866  6886 I BluetoothBondStateMachine: StableState(): Entering Off State
08-16 18:15:33.117  6866  6881 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-16 18:15:33.117  6866  6881 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-16 18:15:33.117  6866  6881 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-16 18:15:33.117  1171  1171 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:33.117  1171  1171 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
08-16 18:15:33.117  1014  1557 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:33.117  1014  1557 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-16 18:15:33.117  1014  1557 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:33.117  1014  1557 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:33.117  1014  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:33.117  6866  6881 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-16 18:15:33.117  6866  6881 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-16 18:15:33.117  6866  6881 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-16 18:15:33.117  6866  6866 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 18:15:33.117  6866  6866 D BtGatt.GattService: Received start request. Starting profile...
08-16 18:15:33.117  6866  6866 D BtGatt.GattService: start()
08-16 18:15:33.117  6866  6866 D BtGatt.GattService: start()
08-16 18:15:33.117  6866  6866 I bluedroid: get_profile_interface gatt
,08-16 18:15:33.117  6866  6866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2877fa98
08-16 18:15:33.117  6866  6866 D BtGatt.AdvertiseManager: advertise manager created
,08-16 18:15:33.127  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 18:15:33.127  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-16 18:15:33.127  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:33.127  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:33.127  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:33.137  6866  6881 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,08-16 18:15:33.137  6866  6881 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-16 18:15:33.137  6866  6881 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-16 18:15:33.137  6866  6866 D BtGatt.GattService: mStartError = false
08-16 18:15:33.137  6866  6866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2877fa98
,08-16 18:15:33.137  1014  1719 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:33.137  1014  1719 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 18:15:33.137  1014  1719 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:33.137  1014  1719 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:33.137  1014  1719 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:33.137  6866  6866 D HeadsetService: Received start request. Starting profile...
,08-16 18:15:33.137  6866  6881 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-16 18:15:33.137  6866  6866 D HeadsetService: start()
08-16 18:15:33.137  6866  6881 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 18:15:33.137  6866  6881 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-16 18:15:33.147  6866  6866 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 18:15:33.147  6866  6866 D HeadsetStateMachine: make
08-16 18:15:33.147  1014  1215 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:33.147  1014  1215 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-16 18:15:33.147  1014  1215 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:33.147  6866  6866 E HeadsetStateMachine: # of Max HF connection is 2
,08-16 18:15:33.147  1014  1215 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-16 18:15:33.147  1014  1215 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:33.147  6866  6881 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-16 18:15:33.147  6866  6881 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-16 18:15:33.147  6866  6881 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-16 18:15:33.147  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 18:15:33.147  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-16 18:15:33.157  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:33.157  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:33.157  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:33.157  6866  6881 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,08-16 18:15:33.157  6866  6881 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-16 18:15:33.157  6866  6881 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-16 18:15:33.157  1014  3070 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-16 18:15:33.157  1014  3070 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-16 18:15:33.157  1014  3070 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:33.157  1014  3070 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:33.157  1014  3070 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-16 18:15:33.157  1014  1359 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 18:15:33.157  1014  1359 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 18:15:33.167  1014  1359 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:33.167  1014  1359 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:33.167  1014  1359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:33.167  1014  1557 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-16 18:15:33.167  1014  1557 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-16 18:15:33.167  6866  6881 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-16 18:15:33.167  6866  6881 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 18:15:33.167  6866  6881 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-16 18:15:33.167  1014  1557 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:33.167  1014  1557 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:33.167  1014  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-16 18:15:33.167  6866  6866 I bluedroid: get_profile_interface handsfree
,08-16 18:15:33.167  1014  1133 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 18:15:33.167  1014  1133 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-16 18:15:33.167  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:33.167  1014  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 18:15:33.167  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:33.177  6866  6881 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-16 18:15:33.177  6866  6881 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-16 18:15:33.177  6866  6881 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-16 18:15:33.177  1014  1215 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:33.177  1014  1215 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-16 18:15:33.177  1014  1215 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:33.177  1014  1215 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:33.177  1014  1215 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:33.187  6866  6881 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-16 18:15:33.187  6866  6881 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-16 18:15:33.187  6866  6881 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-16 18:15:33.187  6866  6881 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-16 18:15:33.187  6866  6881 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-16 18:15:33.187  6866  6881 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-16 18:15:33.187  6866  6881 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-16 18:15:33.187  6866  6881 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-16 18:15:33.187  6866  6881 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-16 18:15:33.187  6866  6881 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-16 18:15:33.187  6866  6881 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-16 18:15:33.187  6866  6881 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,08-16 18:15:33.187  6866  6866 I DualScoManager: Instantiating Dual Sco Manager
,08-16 18:15:33.187  6866  6866 I DualScoManager: Set HeadsetServiceHelper
08-16 18:15:33.197  6866  6881 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-16 18:15:33.197  6866  6866 D BluetoothAtMessage: createCMTIContentObservers
,08-16 18:15:33.197  1014  3070 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-16 18:15:33.197  1014  3070 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 18:15:33.197  1014  3070 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 18:15:33.197  1014  3070 D SettingsProvider: selectionArgs: false
08-16 18:15:33.197  1014  3070 D SettingsProvider: selectionArgs: 1002
,08-16 18:15:33.197  1014  3070 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 18:15:33.197  1014  3070 D SettingsProvider: ret = -1
,08-16 18:15:33.197  6866  6890 D HeadsetStateMachine: Enter Disconnected: -2
,08-16 18:15:33.197  6866  6866 D HeadsetService: mStartError = false
08-16 18:15:33.197  6866  6866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2877fa98
08-16 18:15:33.197  6866  6866 E BluetoothAdapterService(678951576): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-16 18:15:33.207  6866  6866 D A2dpService: Received start request. Starting profile...
08-16 18:15:33.207  6866  6866 D A2dpService: start()
,08-16 18:15:33.207  6866  6866 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-16 18:15:33.207  6866  6890 D HeadsetStateMachine: Clear mHeadsetBrsf
08-16 18:15:33.207  6866  6890 D HeadsetStateMachine: map size, before remove : 0
08-16 18:15:33.207  6866  6890 D HeadsetStateMachine: map size, after remove: 0
,08-16 18:15:33.207  6866  6866 I bluedroid: get_profile_interface avrcp
,08-16 18:15:33.217  1931  1931 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-16 18:15:33.217  6866  6866 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 18:15:33.217  1931  1931 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-16 18:15:33.237  6866  6866 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-16 18:15:33.237  6866  6894 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
08-16 18:15:33.237  6866  6866 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 18:15:33.237  6866  6866 D A2dpStateMachine: make
,08-16 18:15:33.237  6866  6866 I bluedroid: get_profile_interface a2dp
08-16 18:15:33.237  6866  6896 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-16 18:15:33.237  6866  6866 E bt-btif : warning : media task started media_task_refcnt 1 
,08-16 18:15:33.247  6866  6866 D A2dpService: mStartError = false
08-16 18:15:33.247  6866  6866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2877fa98
,08-16 18:15:33.247  6866  6866 I BluetoothHidServiceJni: classInitNative: succeeds
,08-16 18:15:33.247  6866  6895 D A2dpStateMachine: Enter Disconnected: -2
,08-16 18:15:33.247  6866  6866 D HidService: Received start request. Starting profile...
,08-16 18:15:33.247  6866  6866 D HidService: start()
08-16 18:15:33.247  6866  6866 I bluedroid: get_profile_interface hidhost
,08-16 18:15:33.247  6866  6866 D HidService: setHidService(): set to: null
08-16 18:15:33.247  6866  6866 D HidService: mStartError = false
,08-16 18:15:33.247  6866  6866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2877fa98
,08-16 18:15:33.247  6866  6866 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-16 18:15:33.247  6866  6866 D HealthService: Received start request. Starting profile...
08-16 18:15:33.247  6866  6866 D HealthService: start()
,08-16 18:15:33.257  6866  6866 I bluedroid: get_profile_interface health
08-16 18:15:33.257  6866  6866 D HealthService: mStartError = false
08-16 18:15:33.257  6866  6866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2877fa98
,08-16 18:15:33.257  6866  6866 D HeadsetStateMachine: Try to query the phonestate on bind
,08-16 18:15:33.257  1430  1438 I Telecom : BluetoothPhoneService: queryPhoneState
,08-16 18:15:33.257  1430  1430 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-16 18:15:33.257  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-16 18:15:33.257  6866  6894 D BluetoothMediaBrowser: no now playing list
08-16 18:15:33.257  1430  1438 I Telecom : BluetoothPhoneService: Result of Message : true
08-16 18:15:33.257  6866  6894 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-16 18:15:33.257  6866  6866 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-16 18:15:33.257  6866  6866 D PanService: Received start request. Starting profile...
08-16 18:15:33.257  6866  6866 D PanService: start()
08-16 18:15:33.257  6866  6866 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 18:15:33.257  6866  6866 I bluedroid: get_profile_interface pan
,08-16 18:15:33.257  6866  6866 D PanService: mStartError = false
,08-16 18:15:33.257  6866  6866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2877fa98
,08-16 18:15:33.267  6866  6866 D HeadsetStateMachine: Proxy object connected
08-16 18:15:33.267  6866  6866 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-16 18:15:33.267  6866  6890 D HeadsetStateMachine: Disconnected process message: 11,
,08-16 18:15:33.267  6866  6866 D BluetoothMapService: Received start request. Starting profile...
,08-16 18:15:33.267  6866  6866 D BluetoothMapService: start()
,08-16 18:15:33.267  6866  6866 D BluetoothMapService: mStartError = false
,08-16 18:15:33.267  6866  6866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2877fa98
,08-16 18:15:33.267  6866  6866 D HeadsetPhoneState: sendDeviceDataStateChanged
08-16 18:15:33.267  6866  6890 D HeadsetStateMachine: Disconnected process message: 18
08-16 18:15:33.267  6866  6866 D HeadsetPhoneState: Signal level : previous=0 curr=0
,08-16 18:15:33.267  6866  6866 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-16 18:15:33.277  6866  6866 D SapService: Received start request. Starting profile...
08-16 18:15:33.277  6866  6866 D SapService: start()
08-16 18:15:33.277  6866  6866 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-16 18:15:33.277  6866  6866 I bluedroid: get_profile_interface sap
08-16 18:15:33.277  6866  6866 D SapService: mStartError = false
08-16 18:15:33.277  6866  6866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2877fa98
08-16 18:15:33.277  6866  6866 E BluetoothAdapterService(678951576): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,08-16 18:15:33.277  6866  6866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-16 18:15:33.277  6866  6866 D BluetoothA2dp: Proxy object connected
08-16 18:15:33.277  6866  6866 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-16 18:15:33.277  6866  6866 E BluetoothAdapterService(678951576): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-16 18:15:33.277  6866  6866 E BluetoothAdapterService(678951576): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-16 18:15:33.277  6866  6866 E BluetoothAdapterService(678951576): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,08-16 18:15:33.277  6866  6890 D HeadsetStateMachine: Disconnected process message: 10
,08-16 18:15:33.277  6866  6890 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 18:15:33.277  6866  6890 D HeadsetStateMachine: Disconnected process message: 11
,08-16 18:15:33.277  6866  6866 E BluetoothAdapterService(678951576): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-16 18:15:33.297  6866  6866 E BluetoothAdapterService(678951576): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-16 18:15:33.297  6866  6866 E BluetoothAdapterService(678951576): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-16 18:15:33.297  6866  6881 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-16 18:15:33.297  6866  6881 I bluedroid: enable
,08-16 18:15:33.297  6866  6881 I bt_hci_bdroid: init
,08-16 18:15:33.297  6866  6900 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-16 18:15:33.297  6866  6881 I bt_vendor: bt-vendor : init
08-16 18:15:33.297  6866  6881 I bt_vendor: bt-vendor : get_bt_soc_type
,08-16 18:15:33.297  6866  6881 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-16 18:15:33.297  6866  6881 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
08-16 18:15:33.297  6866  6881 D bt_userial_mct: userial_init
,08-16 18:15:33.297  6866  6881 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-16 18:15:33.297  6866  6881 I bt_vendor: Starting hciattach daemon
08-16 18:15:33.297  6866  6881 I bt_vendor: try to set false
,08-16 18:15:33.307  6866  6881 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,08-16 18:15:33.307  6866  6881 I bt_vendor: Starting hciattach daemon
08-16 18:15:33.307  6866  6881 I bt_vendor: try to set true
,08-16 18:15:33.317  6904  6904 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-16 18:15:33.367  6910  6910 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-16 18:15:33.377  6911  6911 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 18:15:33.397  6913  6913 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-16 18:15:33.407  6914  6914 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-16 18:15:33.417  6915  6915 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-16 18:15:33.427  6916  6916 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-16 18:15:33.437   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-16 18:15:33.657  6919  6919 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,08-16 18:15:33.667  6920  6920 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-16 18:15:33.717  6866  6881 I bt_vendor: bluetooth satus is on,
08-16 18:15:33.717  6866  6902 D bt_userial_mct: userial_open(port:0)
08-16 18:15:33.717  6866  6902 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-16 18:15:33.717  6866  6902 I bt_vendor: Done intiailizing UART,
,08-16 18:15:33.717  6866  6902 I bt_vendor: Done intiailizing UART,
08-16 18:15:33.717  6866  6902 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66,
08-16 18:15:33.717  6866  6902 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-16 18:15:33.727  6866  6922 D bt_userial_mct: Entering userial_read_thread(),
,08-16 18:15:33.727  6866  6900 I         : BTE_InitTraceLevels -- TRC_HCI
,08-16 18:15:33.727  6866  6900 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 18:15:33.727  6866  6900 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-16 18:15:33.727  6866  6900 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 18:15:33.727  6866  6900 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-16 18:15:33.727  6866  6900 I         : BTE_InitTraceLevels -- TRC_A2D
,08-16 18:15:33.737  6866  6900 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 18:15:33.737  6866  6900 I         : BTE_InitTraceLevels -- TRC_BTM
,08-16 18:15:33.737  6866  6900 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 18:15:33.737  6866  6900 I         : BTE_InitTraceLevels -- TRC_PAN
,08-16 18:15:33.737  6866  6900 I         : BTE_InitTraceLevels -- TRC_SAP
08-16 18:15:33.737  6866  6900 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 18:15:33.737  6866  6900 I         : BTE_InitTraceLevels -- TRC_GATT
,08-16 18:15:33.737  6866  6900 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 18:15:33.737  6866  6900 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-16 18:15:33.737  6866  6900 I         : BTE_InitTraceLevels -- TRC_BTIF
08-16 18:15:33.737  6866  6900 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-16 18:15:33.837  6866  6900 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-16 18:15:33.847  6866  6900 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa3fde6e9 
,08-16 18:15:33.847  6866  6900 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3fde6e9 
,08-16 18:15:33.857  6866  6884 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-16 18:15:33.867  6866  6884 E bt-btif : Calling BTA_HhEnable
,08-16 18:15:33.867  6866  6884 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-16 18:15:33.867  6866  6884 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,08-16 18:15:33.867  6866  6884 E BluetoothServiceJni: populateRssiValuesNative
,08-16 18:15:33.867  6866  6884 I bluedroid: getModelRssiValues
08-16 18:15:33.867  6866  6884 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-16 18:15:33.867  6866  6884 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-16 18:15:33.877  6866  6884 D BluetoothAdapterProperties: Name is: A5-1,
08-16 18:15:33.877  1014  1014 D SettingsProvider: name = bluetooth_name
,08-16 18:15:33.877  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:33.877  6866  6884 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-16 18:15:33.877  6866  6884 D BluetoothAdapterProperties: Scan Mode:20
,08-16 18:15:33.877  6866  6884 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 18:15:33.887  6866  6884 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
08-16 18:15:33.887  6866  6884 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-16 18:15:33.887  6866  6884 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,08-16 18:15:33.887  6866  6884 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-16 18:15:33.887  6866  6884 E bt-btif : btif_sock_init: !vhci_init
,08-16 18:15:33.887  6866  6884 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
08-16 18:15:33.887  6866  6884 D IOP_DB_BT: db_open: db_open : handle 3025907728l, read 13894 bytes onto local cache
08-16 18:15:33.887  6866  6884 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
08-16 18:15:33.887  6866  6884 D IOP_DB_BT: db_query: result 1
08-16 18:15:33.887  6866  6884 I         : iop_db_open: iop_db_open status 0
,08-16 18:15:33.887  6866  6884 D bte_conf: Device ID record 1 : primary
08-16 18:15:33.887  6866  6884 D bte_conf:   vendorId            = 0075
,08-16 18:15:33.887  6866  6884 D bte_conf:   vendorIdSource      = 0001
08-16 18:15:33.887  6866  6884 D bte_conf:   product             = 0100
08-16 18:15:33.887  6866  6884 D bte_conf:   version             = 0200
08-16 18:15:33.887  6866  6884 D bte_conf:   clientExecutableURL = 
08-16 18:15:33.887  6866  6884 D bte_conf:   serviceDescription  = 
08-16 18:15:33.887  6866  6884 D bte_conf:   documentationURL    = 
08-16 18:15:33.887  6866  6884 D bte_conf: bte_load_did_conf no section named DID2.
,08-16 18:15:33.887  6866  6881 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-16 18:15:33.887  6866  6884 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-16 18:15:33.887  6866  6881 D BluetoothAdapterProperties: ScanMode =  20
08-16 18:15:33.887  6866  6881 D BluetoothAdapterProperties: State =  11
08-16 18:15:33.887  1014  1555 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-16 18:15:33.887  6866  6881 D BluetoothAdapterProperties: Setting state to 12
08-16 18:15:33.887  6866  6881 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-16 18:15:33.897  6866  6922 E bt_mct  : hci lib postload completed
,08-16 18:15:33.897  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:33.897  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:33.897  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:33.897  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:15:33.897  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:33.897  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:33.897  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:33.897  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:15:33.897  6866  6884 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-16 18:15:33.897  6866  6884 D BluetoothAdapterProperties: Scan Mode:21
,08-16 18:15:33.907  6866  6884 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 18:15:33.907  1014  1215 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-16 18:15:33.907  1014  1215 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 18:15:33.907  1014  1215 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 18:15:33.907  1014  1215 D SettingsProvider: selectionArgs: false
08-16 18:15:33.907  1014  1215 D SettingsProvider: selectionArgs: 1002
08-16 18:15:33.907  1014  1215 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 18:15:33.907  1014  1215 D SettingsProvider: ret = -1
,08-16 18:15:33.907  6866  6881 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-16 18:15:33.907  6866  6881 D BluetoothAdapterService: updateAdapterState state is 12
,08-16 18:15:33.907  1014  1359 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 18:15:33.907  1014  1359 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-16 18:15:33.907  1014  1359 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:33.907  1014  1359 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 18:15:33.917  1014  1359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:33.917  6866  6881 D BluetoothAdapterService: Autoconnection is available 
08-16 18:15:33.917  6866  6881 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-16 18:15:33.917  6866  6881 D BluetoothAdapterService: starting service from this receiver
,08-16 18:15:33.917  1322  1333 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 18:15:33.917  1014  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 18:15:33.917  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-16 18:15:33.917  1322  1333 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-16 18:15:33.927  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:33.927  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:33.927  6168  6168 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 18:15:33.927  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:33.927  6866  6881 I BluetoothAdapterState: Entering On State from state = 11
,08-16 18:15:33.927  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-16 18:15:33.927  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 18:15:33.937  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:33.937  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:33.937  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:33.937  1322  1322 D BluetoothA2dp: Proxy object connected
08-16 18:15:33.937  1322  1322 D A2dpProfile: Bluetooth service connected
,08-16 18:15:33.937  1430  2739 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 18:15:33.947  1014  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 18:15:33.947  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 18:15:33.947  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:33.947  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 18:15:33.947  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:33.947  1430  2739 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 18:15:33.947  1014  1044 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 18:15:33.947  1014  1044 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-16 18:15:33.947  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-16 18:15:33.947  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0,
08-16 18:15:33.947  1014  1014 D BluetoothA2dp: Proxy object connected
,08-16 18:15:33.947  1322  1331 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 18:15:33.957  6866  6866 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-16 18:15:33.957  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-16 18:15:33.957  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-16 18:15:33.957  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:33.957  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:33.957  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:33.957  1014  1044 D BluetoothPan: Binding service...
,08-16 18:15:33.957  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-16 18:15:33.957  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 18:15:33.957  6866  6874 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 18:15:33.967  1322  6625 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 18:15:33.967  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-16 18:15:33.967  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-16 18:15:33.967  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:33.967  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:33.967  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:33.967  1322  1333 D Bluetoothsap: onBluetoothStateChange: up=true
,08-16 18:15:33.967  1322  1333 D Bluetoothsap: Binding service...
,08-16 18:15:33.967  6866  6866 I BluetoothPbapService: Handler(): got msg=1
,08-16 18:15:33.967  1322  1333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
08-16 18:15:33.977  1014  1557 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-16 18:15:33.977  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-16 18:15:33.977  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-16 18:15:33.977  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:33.977  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:33.977  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:33.977  1322  1333 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-16 18:15:33.977  1014  1044 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 18:15:33.977  1014  1044 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 18:15:33.977  1322  1322 D BluetoothInputDevice: Proxy object connected
08-16 18:15:33.977  1322  1322 D HidProfile: Bluetooth service connected
08-16 18:15:33.977  1430  1438 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 18:15:33.977  1014  1014 D BluetoothPan: BluetoothPAN Proxy object connected
,08-16 18:15:33.977  1014  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 18:15:33.977  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-16 18:15:33.977  6866  6926 V BluetoothPbapService: PBAP Service initSocket try: 0
08-16 18:15:33.977  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:33.977  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:33.977  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:33.977  1430  1438 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 18:15:33.987  1454  1635 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 18:15:33.987  1014  1044 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 18:15:33.987  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 18:15:33.987  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:33.987  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:33.987  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:33.987  1454  1635 E BluetoothHeadset: BluetoothHeadset service is binded
08-16 18:15:33.987  6866  6926 D BluetoothSocket: bindListen(): myUserId = 0
08-16 18:15:33.987  6866  6926 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 18:15:33.987  1322  1322 D BluetoothMap: Proxy object connected
08-16 18:15:33.987  1322  1322 D MapProfile: Bluetooth service connected
08-16 18:15:33.987  1322  1322 D BluetoothMap: getConnectedDevices()
,08-16 18:15:33.987  2864  2873 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 18:15:33.987  1014  1044 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 18:15:33.987  6866  6926 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
08-16 18:15:33.987  6866  6926 D BluetoothSocket: bindListen(), new LocalSocket 
08-16 18:15:33.987  6866  6926 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-16 18:15:33.987  6866  6926 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@37d72c7d
08-16 18:15:33.987  1322  1322 D Bluetoothsap: BluetoothSAP Proxy object connected
08-16 18:15:33.987  1322  1322 D SapProfile: Bluetooth service connected
08-16 18:15:33.987  1322  1322 D Bluetoothsap: getConnectedDevices()
,08-16 18:15:33.987  6866  6926 D BluetoothSocket: channel: 19
08-16 18:15:33.987  6866  6926 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-16 18:15:33.987  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 18:15:33.997  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:33.997  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 18:15:33.997  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:33.997  2864  2873 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 18:15:33.997  1322  1331 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 18:15:33.997  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-16 18:15:33.997  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 18:15:33.997  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:33.997  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 18:15:33.997  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:33.997  1322  1331 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 18:15:33.997  6866  6874 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-16 18:15:33.997  6866  6874 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 18:15:33.997  1439  1453 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 18:15:33.997  1439  1453 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 18:15:34.007  6168  6182 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 18:15:34.007  6168  6182 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 18:15:34.007  1322  1322 D HeadsetProfile: Bluetooth service connected
,08-16 18:15:34.007  2864  2882 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 18:15:34.007  2864  2882 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 18:15:34.007  1322  1333 D BluetoothPbap: onBluetoothStateChange: up=true
,08-16 18:15:34.007  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-16 18:15:34.007  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-16 18:15:34.007  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:34.007  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:34.007  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:34.007  1322  6625 D BluetoothPan: Binding service...
,08-16 18:15:34.007  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-16 18:15:34.007  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 18:15:34.007  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:34.007  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:34.007  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:34.007  6329  6338 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 18:15:34.007  6329  6338 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 18:15:34.007  1322  1322 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 18:15:34.007  1322  1322 D PanProfile: Bluetooth service connected
,08-16 18:15:34.007  1014  1044 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 18:15:34.007  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 18:15:34.007  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 18:15:34.017  1014  1044 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 18:15:34.017  1454  1890 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 18:15:34.017  1454  1890 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 18:15:34.017  2864  6812 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 18:15:34.017  2864  6812 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-16 18:15:34.017  1322  1322 D BluetoothPbap: Proxy object connected
08-16 18:15:34.017  1014  1044 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-16 18:15:34.017  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 18:15:34.017  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:34.017  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:34.017  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
08-16 18:15:34.017  1322  1322 D PbapServerProfile: Bluetooth service connected
,08-16 18:15:34.017  1931  6756 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-16 18:15:34.017  1931  6756 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 18:15:34.017  2864  2864 D BluetoothA2dp: Proxy object connected
,08-16 18:15:34.027  1430  1443 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 18:15:34.027  1014  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 18:15:34.027  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 18:15:34.027  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:34.027  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:34.027  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:34.027  1430  1443 E BluetoothHeadset: BluetoothHeadset service is binded
08-16 18:15:34.027  1430  1438 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 18:15:34.027  1430  1438 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 18:15:34.027  1322  1333 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-16 18:15:34.027  1322  1333 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 18:15:34.027  1171  3478 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-16 18:15:34.027  1171  3478 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 18:15:34.027  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-16 18:15:34.027  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-16 18:15:34.037  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:34.037  1014  1014 I InputMethodManagerService: [BT Setting State] State =12
08-16 18:15:34.037  1014  1014 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-16 18:15:34.037  1430  1430 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@36e60a2f, true
,08-16 18:15:34.037  1430  1430 D BluetoothHeadset: registerMessageListener
,08-16 18:15:34.037  1171  1171 D BluetoothTile:  onBluetoothStateChange:
,08-16 18:15:34.037  1171  1171 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-16 18:15:34.047  1171  1720 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 18:15:34.047  1171  1171 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:34.047  1171  1171 D BluetoothTile:  getBluetoothState : 12
,08-16 18:15:34.047  1171  1720 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 18:15:34.047  1773  1773 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 18:15:34.047  1322  1322 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 18:15:34.047  1171  1720 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 18:15:34.057  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:34.057  1014  1133 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 18:15:34.057  1014  1215 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 18:15:34.057  6866  6874 D HeadsetService: registerMessageListener
08-16 18:15:34.057  1014  1215 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-16 18:15:34.057  6866  6874 D HeadsetService: registerMessageListener
,08-16 18:15:34.057  6866  6890 D HeadsetStateMachine: Disconnected process message: 70
,08-16 18:15:34.057  1430  1430 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-16 18:15:34.057  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-16 18:15:34.057  6866  6890 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@3bda3772
,08-16 18:15:34.067  1014  1215 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:34.067  1014  1359 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
08-16 18:15:34.067  1014  1215 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:34.067  1430  1430 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-16 18:15:34.067  1014  1215 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-16 18:15:34.067  1430  1430 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-16 18:15:34.067  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-16 18:15:34.067  6866  6928 D BluetoothMapMasInstance: set MAP SDP message type : 1
08-16 18:15:34.067  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 18:15:34.067  1322  1322 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,08-16 18:15:34.067  1322  1322 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-16 18:15:34.067  1322  1322 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-16 18:15:34.067  1322  1322 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-16 18:15:34.077  6866  6890 D HeadsetStateMachine: Disconnected process message: 9
,08-16 18:15:34.077  6866  6890 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-16 18:15:34.077  6866  6928 D BluetoothSocket: bindListen(): myUserId = 0
08-16 18:15:34.077  6866  6928 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 18:15:34.077  6866  6928 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
08-16 18:15:34.077  6866  6928 D BluetoothSocket: bindListen(), new LocalSocket 
08-16 18:15:34.077  6866  6928 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-16 18:15:34.077  6866  6928 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@cfa87c3
,08-16 18:15:34.087   281   281 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-16 18:15:34.087   281   281 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-16 18:15:34.087   281   281 V voice   : voice_set_parameters: exit with code(-2)
08-16 18:15:34.087   281   281 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-16 18:15:34.087   281   281 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-16 18:15:34.087   281   281 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-16 18:15:34.087   281   281 V audio_hw_primary: adev_set_parameters: exit
08-16 18:15:34.087  6866  6928 D BluetoothSocket: channel: 5
08-16 18:15:34.087  6866  6890 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-16 18:15:34.087  1322  1322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 18:15:34.087  1014  1133 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-16 18:15:34.087  1014  1133 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-16 18:15:34.087  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:34.087  1014  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:34.087  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-16 18:15:34.107  1322  1322 D DockEventReceiver: finishStartingService: stopping service
,08-16 18:15:34.107  1322  1322 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 18:15:34.107  1171  1171 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:15:34.107  1171  1171 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-16 18:15:34.117  6866  6866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2877fa98
,08-16 18:15:34.117  6866  6866 D BtConfig.SecureMode: isSecureModeOn:false
,08-16 18:15:34.127  1014  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 18:15:34.127  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-16 18:15:34.127  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:34.127  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:34.127  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 18:15:34.137  1931  1931 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-16 18:15:34.137  1014  1215 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 18:15:34.137  1014  1215 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-16 18:15:34.147  1014  1215 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:34.147  1014  1215 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:34.147  1014  1215 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:34.157  1014  1557 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-16 18:15:34.167  1931  6935 D EasyUnlockInitService: Handling intent for initializer IntentService.,
08-16 18:15:34.167  1931  1931 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-16 18:15:34.167  1014  1557 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 18:15:34.177  1014  1557 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:34.177  1014  1557 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:34.177  1014  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:34.187  6866  6938 D BluetoothSocket: bindListen(): myUserId = 0
08-16 18:15:34.187  6866  6938 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 18:15:34.187  6866  6938 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
08-16 18:15:34.187  6866  6938 D BluetoothSocket: bindListen(), new LocalSocket 
08-16 18:15:34.187  6866  6938 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-16 18:15:34.187  6866  6938 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2a846e35
,08-16 18:15:34.187  6866  6938 D BluetoothSocket: channel: 12
08-16 18:15:34.187  6866  6938 I BtOppRfcommListener: Accept thread started.
,08-16 18:15:34.187  1014  1491 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 18:15:34.197  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:34.197  1014  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:34.197  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:34.207  1931  6935 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-16 18:15:34.807  6168  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:34.807  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:34.807  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:34.807  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:15:34.807  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:34.807  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:34.807  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:34.807  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:15:34.817  6168  6220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null,
,08-16 18:15:34.817  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 18:15:34.817  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@22d4b509 added. We now have 8 listener(s)
,08-16 18:15:34.817  6168  6220 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 18:15:34.817  1014  1345 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-16 18:15:34.827  1014  1345 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-16 18:15:34.827  1014  1345 D SecContentProvider2: mCursor = null
,08-16 18:15:34.827  1014  1345 D WifiService: setWifiEnabled: false pid=6168, uid=10155
,08-16 18:15:34.827  1014  1345 D SettingsProvider: name = wifi_on
,08-16 18:15:34.827  6168  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:34.837  1014  1026 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-16 18:15:34.837  1014  1026 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-16 18:15:34.837  1014  1026 D SecContentProvider2: mCursor = null
,08-16 18:15:34.837  1014  1026 D WifiService: setWifiEnabled: true pid=6168, uid=10155
,08-16 18:15:34.837  1014  1026 W ActivityManager: Permission Denial: getCurrentUser() from pid=6168, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,08-16 18:15:34.837  1014  1026 W WifiService: Failed getting userId using ActivityManagerNative
08-16 18:15:34.837  1014  1026 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6168, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-16 18:15:34.837  1014  1026 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-16 18:15:34.837  1014  1026 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-16 18:15:34.837  1014  1026 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-16 18:15:34.837  1014  1026 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-16 18:15:34.837  1014  1026 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-16 18:15:34.837  1014  1026 D SettingsProvider: name = wifi_on
,08-16 18:15:34.847  1014  1123 E WifiHW  : ##################### set firmware type 0 #####################
,08-16 18:15:35.217  1014  1042 D Tethering: interfaceAdded wlan0
,08-16 18:15:35.217  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
08-16 18:15:35.217  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-16 18:15:35.217  1014  1128 E Tethering: No numeric data
08-16 18:15:35.227  1014  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 18:15:35.227  1014  1128 D Tethering: clearTetheredNotification()
,08-16 18:15:35.227  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-16 18:15:35.227  1014  1128 D Tethering: InitialState.processMessage what=4
,08-16 18:15:35.227  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit,
08-16 18:15:35.227  1014  1120 V NetworkStats: performPollLocked(flags=0x1)
,08-16 18:15:35.227  1014  1120 D NetworkStatsFactory: UpdateStatsForKnox updated,
08-16 18:15:35.227  1014  1120 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-16 18:15:35.227  1014  1042 D Tethering: interfaceAdded p2p0,
,08-16 18:15:35.227  1014  1042 D Tethering: p2p0 is not a tetherable iface, ignoring,
08-16 18:15:35.237  1171  1171 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-16 18:15:35.237  1171  1171 D HotspotTile: updateTetherState():false, false
08-16 18:15:35.237  1014  1128 E Tethering: No numeric data
,08-16 18:15:35.237  1014  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-16 18:15:35.237  1014  1120 V NetworkStats: performPollLocked() took 13ms
08-16 18:15:35.237  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:35.237  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 18:15:35.237  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
08-16 18:15:35.237  1014  1128 D Tethering: clearTetheredNotification()
08-16 18:15:35.237  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-16 18:15:35.247   276   978 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-16 18:15:35.247   276   978 D SoftapController: Softap fwReload - Ok
,08-16 18:15:35.247   276   978 D CommandListener: Setting iface cfg
08-16 18:15:35.247   276   978 D CommandListener: Trying to bring down wlan0
,08-16 18:15:35.257  1171  1171 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-16 18:15:35.257  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:35.257  1014  1120 V NetworkStats: performPollLocked(flags=0x1)
08-16 18:15:35.257  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:35.257  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:35.257   276   978 D CommandListener: Clearing all IP addresses on wlan0
08-16 18:15:35.257  1171  1171 D HotspotTile: updateTetherState():false, false
08-16 18:15:35.257  1014  1120 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 18:15:35.257  1014  1120 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 18:15:35.257  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:35.257  1014  1120 V NetworkStats: performPollLocked() took 3ms
,08-16 18:15:35.257  1014  1123 E WifiHW  : supplicant_name : p2p_supplicant
08-16 18:15:35.257  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:35.257  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:35.297  6950  6950 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-16 18:15:35.297  6950  6950 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-16 18:15:35.297  6950  6950 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-16 18:15:35.317  6950  6950 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
08-16 18:15:35.317   374   374 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6950
08-16 18:15:35.317   374   374 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-16 18:15:35.317  6950  6950 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-16 18:15:35.317  6950  6950 I wpa_supplicant: ssSupport state is = 1
08-16 18:15:35.317  6950  6950 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
,08-16 18:15:35.317  6950  6950 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-16 18:15:35.317   374   374 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6950
08-16 18:15:35.317   374   374 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,08-16 18:15:35.357  1014  1123 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
,08-16 18:15:35.367  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 18:15:35.367  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-16 18:15:35.367  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:35.367  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:35.367  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:35.367  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:35.367  1171  1171 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 18:15:35.367  1171  1171 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-16 18:15:35.367  1171  1720 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-16 18:15:35.367  1171  1171 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-16 18:15:35.367  1171  1171 D HotspotTile: onReceive : 2, 0
,08-16 18:15:35.377  1322  1322 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-16 18:15:35.377  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:35.377  1014  1557 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 18:15:35.377  1014  1557 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 18:15:35.377  1014  1557 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:35.377  1014  1557 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:35.377  1014  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 18:15:35.387  3616  3616 I Hs20UtilService: Starting #17
,08-16 18:15:35.387  3616  3649 I Hs20UtilService: Message received 5011
08-16 18:15:35.387  6443  6443 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-16 18:15:35.387  6443  6443 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 18:15:35.387  6443  6443 D SecurityLogAgent: StateMachine : Current State = 1
08-16 18:15:35.387  6443  6443 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 18:15:35.467   286   286 E SMD     : DCD OFF,
,08-16 18:15:35.477   374   374 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0,
,08-16 18:15:35.487  6950  6950 I SecureStorage: [INFO]: SPID(0x00000004)Processing data has been completed,
,08-16 18:15:35.547  6950  6950 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-16 18:15:35.547  6950  6950 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,08-16 18:15:35.557  6950  6950 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
,08-16 18:15:35.557   374   374 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6950,
08-16 18:15:35.557   374   374 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
08-16 18:15:35.557  6950  6950 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
08-16 18:15:35.557  6950  6950 I wpa_supplicant: ssSupport state is = 1
08-16 18:15:35.557  6950  6950 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-16 18:15:35.567  6950  6950 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 18:15:35.567  6950  6950 E wpa_supplicant: SIM READ ERROR
08-16 18:15:35.567  6950  6950 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 18:15:35.567  6950  6950 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 18:15:35.567  6950  6950 E wpa_supplicant: SIM READ ERROR
08-16 18:15:35.567  6950  6950 I wpa_supplicant: Blacklist: Clear (all) 
,08-16 18:15:35.567  6950  6950 I wpa_supplicant: wpa_default_ap_write_once
08-16 18:15:35.567  6950  6950 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-16 18:15:35.567  6950  6950 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 18:15:35.567  6950  6950 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-16 18:15:35.567  6950  6950 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-16 18:15:35.567  6950  6950 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 18:15:35.567  6950  6950 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-16 18:15:35.567  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 18:15:35.567  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 18:15:35.567  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-16 18:15:35.627  6950  6950 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-16 18:15:35.907  6950  6950 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-16 18:15:35.907  6950  6950 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,08-16 18:15:35.917  6950  6950 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
08-16 18:15:35.927   374   374 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6950
08-16 18:15:35.927   374   374 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
08-16 18:15:35.927  6950  6950 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
08-16 18:15:35.927  6950  6950 I wpa_supplicant: ssSupport state is = 1
08-16 18:15:35.927  6950  6950 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-16 18:15:35.927  6950  6950 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
08-16 18:15:35.937  6950  6950 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
08-16 18:15:35.937   374   374 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6950
08-16 18:15:35.937   374   374 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
08-16 18:15:35.937  6950  6950 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
08-16 18:15:35.937  6950  6950 I wpa_supplicant: ssSupport state is = 1
08-16 18:15:35.937  6950  6950 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 18:15:35.937  6950  6950 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 18:15:35.937  6950  6950 E wpa_supplicant: SIM READ ERROR
08-16 18:15:35.937  6950  6950 I wpa_supplicant: wpa_default_ap_write_once
08-16 18:15:35.937  6950  6950 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-16 18:15:35.937  6950  6950 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-16 18:15:35.947  1014  1215 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-16 18:15:35.947  1014  1215 D BatteryService: level:91, scale:100, status:2, health:2, present:true, voltage: 4175, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-16 18:15:35.947  1014  1215 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-16 18:15:35.947  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 18:15:35.947  1014  1215 D BatteryService: stay LED for charging
08-16 18:15:35.947  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
08-16 18:15:35.947  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-16 18:15:35.947  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-16 18:15:35.947  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 18:15:35.947  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
08-16 18:15:35.947  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-16 18:15:35.947  1014  1014 I MotionRecognitionService: Plugged
08-16 18:15:35.957  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
08-16 18:15:35.957  1171  1171 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-16 18:15:35.957  1171  1171 D KeyguardUpdateMonitor: handleBatteryUpdate
08-16 18:15:35.957  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-16 18:15:35.957  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 91
08-16 18:15:35.977  6866  6866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-16 18:15:35.977  6866  6890 D HeadsetStateMachine: Disconnected process message: 10
,08-16 18:15:35.987  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:91 status:2 health:2
,08-16 18:15:35.987  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:91 status:2 health:2
08-16 18:15:35.987  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:91 status:2 health:2
,08-16 18:15:36.007  6950  6950 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-16 18:15:36.007  6950  6950 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-16 18:15:36.067  6950  6950 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-16 18:15:36.067  6950  6950 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=,
08-16 18:15:36.067  6950  6950 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-16 18:15:36.077  1014  1123 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
08-16 18:15:36.077  1014  1123 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-16 18:15:36.087  6950  6950 I wpa_supplicant: HOTSPOT20_ENABLE called,
08-16 18:15:36.087  6950  6950 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-16 18:15:36.087  6950  6950 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-16 18:15:36.087  6950  6950 E wpa_supplicant: SIM READ ERROR
,08-16 18:15:36.087  6950  6950 I wpa_supplicant: Blacklist: Clear (all) ,
,08-16 18:15:36.107  6950  6950 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-16 18:15:36.117  1014  1123 D WifiNative-wlan0: callSECApiInt - ID [210]
08-16 18:15:36.117  6950  6950 I wpa_supplicant: Skip scan - bUseNetwork false
,08-16 18:15:36.117  1014  1123 D WifiConfigStore: Loading config and enabling all networks ,
08-16 18:15:36.117  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-16 18:15:36.117  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
08-16 18:15:36.117  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:36.117  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-16 18:15:36.117  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:36.117  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:36.117  1171  1171 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 18:15:36.117  1171  1171 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-16 18:15:36.127  1171  1720 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-16 18:15:36.127  1171  1171 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-16 18:15:36.127  1171  1171 D HotspotTile: onReceive : 3, 0
,08-16 18:15:36.127  1322  1322 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-16 18:15:36.137  1014  1027 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 18:15:36.137  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 18:15:36.137  1014  1027 W ActivityManager: userId = 0, bbcId = -10000,
,08-16 18:15:36.137  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:36.137  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 18:15:36.137  3616  3616 I Hs20UtilService: Starting #18
,08-16 18:15:36.137  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:36.137  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:36.137  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:36.137  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:36.137  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:36.137  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:36.137  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:36.137  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:15:36.147  3616  3649 I Hs20UtilService: Message received 5011,
,08-16 18:15:36.147  1014  1123 E WifiConfigStore: Not a HS20
08-16 18:15:36.147  6168  6168 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
08-16 18:15:36.147  6443  6443 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-16 18:15:36.147  6443  6443 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 18:15:36.147  6443  6443 D SecurityLogAgent: StateMachine : Current State = 1
,08-16 18:15:36.147  6443  6443 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-16 18:15:36.147  1014  1123 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-16 18:15:36.157  1014  1123 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-16 18:15:36.157  1014  1123 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-16 18:15:36.157  6950  6950 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-16 18:15:36.157  6950  6950 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-16 18:15:36.157  6950  6950 I wpa_supplicant: reset timer : RESET_TIMER 0
08-16 18:15:36.157  6950  6950 I wpa_supplicant: P2P: Current p2p state = IDLE
08-16 18:15:36.157  6950  6950 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-16 18:15:36.157  6950  6950 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-16 18:15:36.157  6950  6950 I wpa_supplicant: First Scan Start
,08-16 18:15:36.167  6950  6950 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-16 18:15:36.167  1014  1123 D WifiNative-wlan0: Setting external_sim to 1
,08-16 18:15:36.167  1014  1123 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 18:15:36.167  1014  1123 I WifiNative-HAL: startHal
08-16 18:15:36.167  1014  1123 E wifi    : getStaticLongField sWifiHalHandle 0x9cac988c
08-16 18:15:36.167  1014  1123 I WifiNative-HAL: Could not start hal
,08-16 18:15:36.167  6413  6413 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 18:15:36.167  1014  1123 E WifiNative-wlan0: do suspend true
,08-16 18:15:36.167  1014  1123 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-16 18:15:36.167  1014  1122 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-16 18:15:36.167  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 3
,08-16 18:15:36.167  1014  1148 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:36.167  1014  1148 I WifiNative-HAL: startHal
,08-16 18:15:36.167  1014  1148 E wifi    : getStaticLongField sWifiHalHandle 0x9dc7b9bc
08-16 18:15:36.167  1014  1148 I WifiNative-HAL: Could not start hal
08-16 18:15:36.167  1014  1148 E WifiScanningService: could not start HAL
08-16 18:15:36.167  1014  1014 D RttService: SCAN_AVAILABLE : 3
,08-16 18:15:36.167  1014  1149 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 18:15:36.177   276   978 D CommandListener: Setting iface cfg
08-16 18:15:36.177   276   978 D CommandListener: Trying to bring up p2p0
,08-16 18:15:36.177  1014  1122 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-16 18:15:36.177  1014  1122 D WifiP2pService: P2pEnablingState
,08-16 18:15:36.177  1014  1122 D WifiP2pService: P2pEnablingState{ what=147457 }
,08-16 18:15:36.177  1014  1123 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,08-16 18:15:36.177  1014  1123 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-16 18:15:36.177  1014  1123 E WifiNative-wlan0: invaild command id : 215
,08-16 18:15:36.177  1014  1123 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-16 18:15:36.177  1014  1123 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-16 18:15:36.177  1014  1122 D WifiP2pService: P2p socket connection successful
08-16 18:15:36.177  1014  1123 E WifiNative-wlan0: invaild command id : 215
08-16 18:15:36.177  1014  1122 D WifiP2pService: P2pEnabledState
,08-16 18:15:36.177  1014  1122 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-16 18:15:36.177  1014  1125 E ConnectivityService: updateNetworkInfo()
,08-16 18:15:36.177  6950  6950 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-16 18:15:36.187  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-16 18:15:36.187  1014  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-16 18:15:36.187  6950  6950 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-16 18:15:36.187  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 18:15:36.187  1014  1045 D WifiDisplayController: disconnect
08-16 18:15:36.187  1014  1045 D WifiDisplayController: updateConnection
,08-16 18:15:36.187  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 18:15:36.187  1014  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-16 18:15:36.187  6950  6950 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,08-16 18:15:36.187  1014  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 18:15:36.187  1014  1045 D WifiDisplayAdapter: onP2pDisconnected
,08-16 18:15:36.187  1014  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-16 18:15:36.187  1014  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-16 18:15:36.187  1171  1171 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED,
,08-16 18:15:36.187  1014  1123 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 18:15:36.187  1014  1555 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-16 18:15:36.187  1014  1123 D SecContentProvider2: mCursor = null
08-16 18:15:36.187  1171  1171 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-16 18:15:36.197  1014  1122 D WifiNative-p2p0: p2pGetDeviceAddress
,08-16 18:15:36.197  1014  1122 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
,08-16 18:15:36.197  1322  1322 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-16 18:15:36.197  1322  1322 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-16 18:15:36.197  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-16 18:15:36.197  1014  1123 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 18:15:36.197  1014  1123 D SecContentProvider2: mCursor = null
,08-16 18:15:36.197  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-16 18:15:36.197  1014  1122 D WifiP2pService: DeviceAddress: 7e:96:ac
,08-16 18:15:36.197  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 18:15:36.197  1014  1045 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
08-16 18:15:36.197  1014  1045 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
08-16 18:15:36.197  1014  1045 D WifiDisplayController:  primary type: 10-0050F204-5
08-16 18:15:36.197  1014  1045 D WifiDisplayController:  secondary type: null
08-16 18:15:36.197  1014  1045 D WifiDisplayController:  wps: 0
08-16 18:15:36.197  1014  1045 D WifiDisplayController:  grpcapab: 0
08-16 18:15:36.197  1014  1045 D WifiDisplayController:  devcapab: 0
08-16 18:15:36.197  1014  1045 D WifiDisplayController:  status: 3
08-16 18:15:36.197  1014  1045 D WifiDisplayController:  wfdInfo: null
08-16 18:15:36.197  1014  1045 D WifiDisplayController:  groupownerAddress: null
08-16 18:15:36.197  1014  1045 D WifiDisplayController:  GOdeviceName: null
08-16 18:15:36.197  1014  1045 D WifiDisplayController:  interfaceAddress: 
08-16 18:15:36.197  1014  1045 D WifiDisplayController:  SConnectInfo : null
,08-16 18:15:36.197  1322  1322 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-16 18:15:36.197  1322  3077 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-16 18:15:36.207  6381  6381 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-16 18:15:36.207  6381  6381 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-16 18:15:36.207  6381  6381 D FileShare-Client: Outbound.stopDelayTimer - 
08-16 18:15:36.207  6398  6398 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-16 18:15:36.217  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 18:15:36.217  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
08-16 18:15:36.217  1014  1122 D WifiP2pService: sending p2p persistent groups changed broadcast
08-16 18:15:36.217  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-16 18:15:36.217  1014  1122 D WifiP2pService: InactiveState
08-16 18:15:36.217  1014  1122 D WifiP2pService: InactiveState{ what=143376 }
08-16 18:15:36.217  1014  1122 D WifiP2pService: P2pEnabledState{ what=143376 }
08-16 18:15:36.217  6950  6950 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-16 18:15:36.217  1014  1122 D WifiP2pService: InactiveState{ what=143376 }
08-16 18:15:36.217  1014  1122 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-16 18:15:36.867  6168  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:36.867  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:36.867  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:36.867  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:36.867  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:36.867  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:36.867  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:36.867  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:15:36.867  6168  6220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:15:36.867  6168  6220 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-16 18:15:36.877  6168  6220 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-16 18:15:36.877  6168  6220 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@dab39c8 Bundle[{}]
,08-16 18:15:36.877  6168  6220 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-16 18:15:36.877  6168  6220 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-16 18:15:36.877  6168  6220 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-16 18:15:36.877  6168  6220 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-16 18:15:36.877  6168  6220 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-16 18:15:36.877  6168  6220 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-16 18:15:36.887  6168  6220 I System.out: Running OutgoingSocketThread
,08-16 18:15:36.887  6168  6959 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1162)
,08-16 18:15:36.897  6168  6959 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 40837
,08-16 18:15:36.897  6168  6959 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-16 18:15:36.987  1014  2723 D SSRM:n  : SIOP:: AP = 320
,08-16 18:15:37.337  6950  6950 I wpa_supplicant: nl80211: Received scan results (32 BSSes),
08-16 18:15:37.337  6950  6950 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
08-16 18:15:37.337  6950  6950 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,08-16 18:15:37.337  6950  6950 I wpa_supplicant: Trying to associate with  'G700'
08-16 18:15:37.337  6950  6950 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,08-16 18:15:37.337  6950  6950 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-16 18:15:37.337  1014  6955 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-16 18:15:37.357  1014  1123 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-16 18:15:37.357  1014  1123 D SecContentProvider2: mCursor = null
,08-16 18:15:37.447  6950  6950 E wpa_supplicant: Cmd 35605 not handled
,08-16 18:15:37.447  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 18:15:37.447  6950  6950 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-16 18:15:37.447  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
08-16 18:15:37.447  6950  6950 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
08-16 18:15:37.447  6950  6950 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-16 18:15:37.447  6950  6950 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,08-16 18:15:37.447  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 18:15:37.447  6950  6950 I wpa_supplicant: Associated with F4.99.3E
08-16 18:15:37.447  6950  6950 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-16 18:15:37.447  6950  6950 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-16 18:15:37.447  6950  6950 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-16 18:15:37.457  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 18:15:37.457  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
08-16 18:15:37.457  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 18:15:37.457  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, true
08-16 18:15:37.457  1014  1042 D Tethering: interfaceStatusChanged wlan0, true
,08-16 18:15:37.457  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true,
,08-16 18:15:37.457  1014  1123 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 18:15:37.457  1014  1123 D SecContentProvider2: mCursor = null
,08-16 18:15:37.457  6950  6950 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-16 18:15:37.457  6950  6950 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-16 18:15:37.457  1014  1128 E Tethering: No numeric data
08-16 18:15:37.457  6950  6950 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-16 18:15:37.457  1014  1123 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 18:15:37.457  1014  1123 D SecContentProvider2: mCursor = null
08-16 18:15:37.467  6950  6950 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-16 18:15:37.467  6950  6950 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 18:15:37.467  6950  6950 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,08-16 18:15:37.467  6950  6950 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,08-16 18:15:37.467  1014  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0,
,08-16 18:15:37.467  1014  1128 D Tethering: clearTetheredNotification()
08-16 18:15:37.467  1014  1120 V NetworkStats: performPollLocked(flags=0x1)
08-16 18:15:37.467  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:37.467  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-16 18:15:37.467  6950  6950 I wpa_supplicant: Blacklist: Clear (temp) 
08-16 18:15:37.467  6950  6950 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-16 18:15:37.467  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, true
08-16 18:15:37.467  1014  1042 D Tethering: interfaceStatusChanged wlan0, true
,08-16 18:15:37.467  1014  1120 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-16 18:15:37.467  1014  1120 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-16 18:15:37.467  1014  1123 D WifiNative-wlan0: callSECApiVoid - ID [50]
08-16 18:15:37.467  1171  1171 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-16 18:15:37.467  1171  1171 D HotspotTile: updateTetherState():false, false
08-16 18:15:37.477  1014  1123 E WifiConfigStore: setLastSelectedConfiguration -1
08-16 18:15:37.477  1014  1120 V NetworkStats: performPollLocked() took 7ms
08-16 18:15:37.477  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:37.477  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 18:15:37.477  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 18:15:37.477  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:37.477  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-16 18:15:37.477  1014  1123 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-16 18:15:37.477  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:37.487  1014  1125 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 18:15:37.477  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:37.477  1014  1125 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-16 18:15:37.487  1014  1125 E ConnectivityService: updateNetworkInfo()
,08-16 18:15:37.487  1014  1123 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 18:15:37.487  1014  1215 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 18:15:37.487  1014  1215 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 18:15:37.487  1014  1215 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:37.487  1014  1215 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:37.487  1014  1215 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-16 18:15:37.487  3616  3616 I Hs20UtilService: Starting #19
08-16 18:15:37.487  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:37.487  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:37.487  3616  3649 I Hs20UtilService: Message received 5007
,08-16 18:15:37.497  1322  1322 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-16 18:15:37.497  1322  1322 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 18:15:37.497  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 18:15:37.497  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-16 18:15:37.497  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 18:15:37.497  1322  1322 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-16 18:15:37.497  1322  3077 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 18:15:37.507  1014  1123 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 18:15:37.517   276   978 D CommandListener: Setting iface cfg
,08-16 18:15:37.517  1014  1123 E WifiStateMachine: Start Dhcp Watchdog 2
,08-16 18:15:37.517  1014  1123 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-16 18:15:37.527  1014  1123 D SecContentProvider2: mCursor = null
,08-16 18:15:37.527  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 18:15:37.527  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-16 18:15:37.527  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:37.537  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:37.537  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:37.537  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:37.537  1014  1123 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-16 18:15:37.537  1014  1123 D SecContentProvider2: mCursor = null
,08-16 18:15:37.547  1014  1123 E WifiNative-wlan0: do suspend false
,08-16 18:15:37.547  1014  1122 D WifiP2pService: InactiveState{ what=143375 }
,08-16 18:15:37.547  1014  1122 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-16 18:15:37.767  6962  6962 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-16 18:15:37.767  6962  6962 I dhcpcd  : version 5.5.6 starting,
,08-16 18:15:37.767  6962  6962 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-16 18:15:37.827  6962  6962 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-16 18:15:37.827  6962  6962 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-16 18:15:37.827  6962  6962 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-16 18:15:37.827  6962  6962 I dhcpcd  : bssid match,
08-16 18:15:37.827  6962  6962 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111
,08-16 18:15:37.887  6962  6962 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1,
,08-16 18:15:37.887  6168  6220 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1163),
08-16 18:15:37.887  6168  6220 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1163)
,08-16 18:15:37.897  6168  6220 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1168)
08-16 18:15:37.897  6168  6220 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-16 18:15:37.897  6168  6220 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1169),
08-16 18:15:37.897  6168  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:15:37.897  6168  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31b0030e added. We now have 2 listener(s),
,08-16 18:15:37.907  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-16 18:15:37.907  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 18:15:37.907  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 18:15:37.907  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 18:15:37.907  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b3c12f added. We now have 9 listener(s)
,08-16 18:15:37.907  6168  6220 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 18:15:37.907  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 18:15:37.917  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 18:15:37.917  6168  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:15:37.917  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:37.917  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:37.917  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:37.917  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:37.917  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:37.917  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:37.917  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:15:37.917  6168  6220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 18:15:37.917  6168  6220 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 18:15:37.927  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:37.927  6168  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:15:37.927  6168  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88a98c5 added. We now have 3 listener(s)
,08-16 18:15:37.927  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-16 18:15:37.927  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-16 18:15:37.927  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:15:37.927  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:15:37.927  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:15:37.927  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aed421a added. We now have 10 listener(s)
08-16 18:15:37.927  6168  6220 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:15:37.927  6168  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:37.927  6168  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:37.927  6168  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:37.927  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:37.927  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:37.927  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:15:37.927  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:15:37.927  6168  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31b0030e removed from the list
08-16 18:15:37.927  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:37.927  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b3c12f removed from the list
08-16 18:15:37.927  6168  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:37.927  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:37.927  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:37.927  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:37.927  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:37.927  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:37.927  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:37.927  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b3c12f not in the list
08-16 18:15:37.927  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:37.927  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:37.927  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:37.937  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:37.937  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:37.937  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aed421a removed from the list
08-16 18:15:37.937  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:37.937  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:37.937  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:37.937  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:15:37.937  6168  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88a98c5 removed from the list
08-16 18:15:37.937  6168  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:15:37.937  6168  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b45414b added. We now have 2 listener(s)
08-16 18:15:37.937  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-16 18:15:37.937  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:15:37.937  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:15:37.937  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:15:37.937  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1163d728 added. We now have 9 listener(s)
08-16 18:15:37.937  6168  6220 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:15:37.937  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 18:15:37.947  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:15:37.947  6168  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:15:37.947  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:37.947  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:37.947  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:37.947  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:37.947  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:37.947  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:37.947  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 18:15:37.957  6168  6220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:15:37.957  6168  6220 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 18:15:37.957  6168  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:15:37.957  6168  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c8d65e6 added. We now have 3 listener(s)
08-16 18:15:37.957  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:37.957  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:37.957  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-16 18:15:37.957  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 18:15:37.967  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:15:37.967  6962  6962 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds
08-16 18:15:37.967  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:15:37.967  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1324a727 added. We now have 10 listener(s)
08-16 18:15:37.967  6168  6220 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:15:37.967  6168  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 18:15:37.967  6168  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 18:15:37.967  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 18:15:37.967  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:15:37.967  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 18:15:37.967  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 18:15:37.977  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 18:15:37.977  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 18:15:37.987  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 18:15:37.987  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 18:15:37.987  6168  6220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 18:15:37.997  6866  6927 D BtGatt.GattService: registerClient() - UUID=747f422d-ce68-4510-8601-eb869f8ee530
,08-16 18:15:38.037  6866  6884 D BtGatt.GattService: onClientRegistered() - UUID=747f422d-ce68-4510-8601-eb869f8ee530, clientIf=6
,08-16 18:15:38.037  6168  6182 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6,
08-16 18:15:38.037  6866  6885 D BtGatt.GattService: start scan with filters
,08-16 18:15:38.047  6866  6889 D BtGatt.ScanManager: handling starting scan
,08-16 18:15:38.047  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 18:15:38.047  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 18:15:38.047  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-16 18:15:38.047  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
,08-16 18:15:38.047  6866  6889 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2877fa98
08-16 18:15:38.047  6168  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 18:15:38.057  6168  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 18:15:38.057  6168  6168 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
08-16 18:15:38.057  6866  6884 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-16 18:15:38.057  6866  6884 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:38.057  6866  6889 D BtGatt.ScanManager: allow scan with filters
08-16 18:15:38.057  6866  6889 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-16 18:15:38.057  6866  6889 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-16 18:15:38.057  6866  6884 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-16 18:15:38.057  6866  6884 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 18:15:38.057  6866  6889 D BtGatt.ScanManager: Starting BLE batch scan
08-16 18:15:38.057  6866  6889 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-16 18:15:38.057  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 18:15:38.057  6866  6884 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-16 18:15:38.057  6866  6884 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:38.067  6168  6220 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-16 18:15:38.067  6168  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:38.067  6168  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 18:15:38.067  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:38.067  6866  6884 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-16 18:15:38.067  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 18:15:38.067  6866  6884 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:38.067  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-16 18:15:38.067  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 18:15:38.067  6168  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 18:15:38.067  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 18:15:38.067  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 18:15:38.067  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 18:15:38.067  6866  6927 D BtGatt.GattService: stopScan() - queue size =1,
08-16 18:15:38.067  6866  6885 D BtGatt.GattService: unregisterClient() - clientIf=6,
,08-16 18:15:38.077  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 18:15:38.077  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 18:15:38.077  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 18:15:38.077  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 18:15:38.077  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 18:15:38.077  6168  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 18:15:38.077  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 18:15:38.077  6168  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 18:15:38.077  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 18:15:38.077  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 18:15:38.087  6168  6168 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 18:15:38.087  6168  6168 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 18:15:38.087  6168  6168 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 18:15:38.087  6168  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 18:15:38.087  6168  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:38.087  6168  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:38.087  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:38.087  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:38.087  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 18:15:38.087  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:15:38.087  6168  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b45414b removed from the list
,08-16 18:15:38.087  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:38.087  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1163d728 removed from the list
08-16 18:15:38.087  6168  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:38.087  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:38.097  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:38.097  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:38.097  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:38.097  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:38.097  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:38.097  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1163d728 not in the list
08-16 18:15:38.097  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:38.097  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:38.107  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:38.107  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:38.107  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:38.107  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1324a727 removed from the list
08-16 18:15:38.107  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:38.107  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:38.107  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:38.107  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:15:38.107  6168  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c8d65e6 removed from the list
,08-16 18:15:38.107  6168  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:15:38.107  6168  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37aa8ec3 added. We now have 2 listener(s)
08-16 18:15:38.107  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-16 18:15:38.107  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:15:38.107  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:15:38.107  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:15:38.107  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18f06340 added. We now have 9 listener(s)
08-16 18:15:38.107  6168  6220 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:15:38.107  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 18:15:38.117  6866  6889 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 33
08-16 18:15:38.117  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 18:15:38.117  6168  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:15:38.117  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:38.117  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:38.117  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:38.117  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:38.117  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:38.117  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:38.117  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 18:15:38.117  6866  6889 D BtGatt.ScanManager: filter size is 1
08-16 18:15:38.117  6866  6889 D BtGatt.ScanManager: delete FilterIndex - 3
,08-16 18:15:38.117  6866  6884 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
08-16 18:15:38.117  6866  6884 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:38.117  6866  6889 D BtGatt.ScanManager: stopping BLe Batch
,08-16 18:15:38.127  6168  6220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:15:38.127  6168  6220 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 18:15:38.127  6168  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:15:38.127  6168  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38a94bbe added. We now have 3 listener(s)
,08-16 18:15:38.127  6866  6884 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-16 18:15:38.127  6866  6884 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:38.127  6866  6889 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-16 18:15:38.127  6866  6884 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-16 18:15:38.127  6866  6884 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:38.127  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-16 18:15:38.127  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:15:38.127  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:15:38.127  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 18:15:38.127  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81d541f added. We now have 10 listener(s)
,08-16 18:15:38.137  6168  6220 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:15:38.137  6168  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 18:15:38.137  6168  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 18:15:38.137  6168  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only,
08-16 18:15:38.137  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 18:15:38.137  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:15:38.137  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 18:15:38.147  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,08-16 18:15:38.147  1014  1040 W ProcessCpuTracker: Skipping unknown process pid 6983
,08-16 18:15:38.157  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
08-16 18:15:38.157  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
,08-16 18:15:38.167  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:38.167  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:38.167  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 18:15:38.167  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 18:15:38.167  6168  6220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 18:15:38.177  6866  6874 D BtGatt.GattService: registerClient() - UUID=d640b9e5-fa0e-400f-8e1c-1639799a88ca
,08-16 18:15:38.217  6866  6884 D BtGatt.GattService: onClientRegistered() - UUID=d640b9e5-fa0e-400f-8e1c-1639799a88ca, clientIf=6
08-16 18:15:38.217  6168  6178 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-16 18:15:38.217  6866  6927 D BtGatt.GattService: start scan with filters
08-16 18:15:38.217  6866  6889 D BtGatt.ScanManager: handling starting scan,
08-16 18:15:38.217  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 18:15:38.217  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 18:15:38.217  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-16 18:15:38.217  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-16 18:15:38.217  6866  6884 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-16 18:15:38.217  6866  6884 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 18:15:38.217  6866  6889 D BtGatt.ScanManager: allow scan with filters
,08-16 18:15:38.217  6866  6889 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-16 18:15:38.217  6866  6889 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-16 18:15:38.227  6866  6884 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-16 18:15:38.227  6866  6884 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 18:15:38.227  6866  6889 D BtGatt.ScanManager: Starting BLE batch scan
,08-16 18:15:38.227  6866  6889 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-16 18:15:38.227  6866  6884 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-16 18:15:38.227  6866  6884 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:38.227  6168  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 18:15:38.227  6168  6168 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 18:15:38.227  6866  6884 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-16 18:15:38.227  6866  6884 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:38.237  6168  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 18:15:38.237  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 18:15:38.247  6866  6889 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 34
,08-16 18:15:38.247  6168  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 18:15:38.247  6168  6220 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 18:15:38.247  6168  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:38.247  6168  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 18:15:38.247  6168  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:38.247  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 18:15:38.247  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:38.247  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 18:15:38.247  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:15:38.247  6168  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37aa8ec3 removed from the list
08-16 18:15:38.247  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:38.247  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18f06340 removed from the list
,08-16 18:15:38.247  6168  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:38.247  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 18:15:38.247  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:38.247  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-16 18:15:38.247  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 18:15:38.247  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 18:15:38.247  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 18:15:38.247  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:38.247  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:38.247  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18f06340 not in the list
,08-16 18:15:38.247  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 18:15:38.247  6168  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 18:15:38.247  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 18:15:38.247  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 18:15:38.247  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 18:15:38.257  6866  6927 D BtGatt.GattService: stopScan() - queue size =1
,08-16 18:15:38.257  6866  6889 D BtGatt.ScanManager: filter size is 1
08-16 18:15:38.257  6866  6889 D BtGatt.ScanManager: delete FilterIndex - 4
,08-16 18:15:38.257  6866  6877 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-16 18:15:38.257  6866  6884 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-16 18:15:38.257  6866  6884 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:38.257  6866  6889 D BtGatt.ScanManager: stopping BLe Batch
,08-16 18:15:38.257  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 18:15:38.257  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 18:15:38.257  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 18:15:38.257  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 18:15:38.257  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 18:15:38.257  6168  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 18:15:38.257  6866  6884 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-16 18:15:38.257  6866  6884 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 18:15:38.257  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 18:15:38.257  6168  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 18:15:38.257  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 18:15:38.267  6866  6889 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-16 18:15:38.267  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:38.267  6866  6884 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-16 18:15:38.267  6866  6884 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:38.267  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:38.267  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:38.267  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:38.267  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81d541f removed from the list
08-16 18:15:38.267  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:38.267  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:38.267  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:38.267  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:15:38.267  6168  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38a94bbe removed from the list
,08-16 18:15:38.267  6168  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:15:38.267  6168  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37cd133b added. We now have 2 listener(s)
08-16 18:15:38.267  6168  6168 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 18:15:38.267  6168  6168 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 18:15:38.267  6168  6168 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 18:15:38.267  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-16 18:15:38.267  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 18:15:38.267  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 18:15:38.267  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:15:38.267  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cf5a58 added. We now have 9 listener(s)
,08-16 18:15:38.267  6168  6220 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:15:38.277  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 18:15:38.277  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 18:15:38.277  6168  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:15:38.277  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:38.277  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:38.277  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:38.277  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:38.277  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:15:38.277  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:15:38.277  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:15:38.287  6168  6220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 18:15:38.287  6168  6220 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 18:15:38.287  6168  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 18:15:38.287  6168  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18f11496 added. We now have 3 listener(s)
,08-16 18:15:38.287  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:38.287  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-16 18:15:38.287  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:15:38.287  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:15:38.287  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:15:38.287  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14efa817 added. We now have 10 listener(s)
08-16 18:15:38.287  6168  6220 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:15:38.287  6168  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 18:15:38.287  6168  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 18:15:38.287  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 18:15:38.287  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:15:38.287  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 18:15:38.297  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:38.297  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 18:15:38.297  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 18:15:38.307  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 18:15:38.307  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 18:15:38.307  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 18:15:38.307  6168  6220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 18:15:38.317  6866  6877 D BtGatt.GattService: registerClient() - UUID=b2e12679-b70e-4195-bd2a-f48e334e0761
,08-16 18:15:38.357  6866  6884 D BtGatt.GattService: onClientRegistered() - UUID=b2e12679-b70e-4195-bd2a-f48e334e0761, clientIf=6
08-16 18:15:38.357  1014  1123 E WifiNative-wlan0: do suspend true
,08-16 18:15:38.357  6168  6178 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-16 18:15:38.357  6866  6885 D BtGatt.GattService: start scan with filters
,08-16 18:15:38.357  6866  6889 D BtGatt.ScanManager: handling starting scan
,08-16 18:15:38.367  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 18:15:38.367  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 18:15:38.367  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-16 18:15:38.367  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 18:15:38.367  6866  6884 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-16 18:15:38.367  6866  6884 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:38.367  6866  6889 D BtGatt.ScanManager: allow scan with filters
,08-16 18:15:38.367  6866  6889 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-16 18:15:38.367  6866  6889 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-16 18:15:38.377  6168  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 18:15:38.377  6168  6168 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 18:15:38.377  6866  6884 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-16 18:15:38.377  6866  6884 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:38.377  6866  6889 D BtGatt.ScanManager: Starting BLE batch scan
,08-16 18:15:38.377  6866  6889 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-16 18:15:38.377  6168  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 18:15:38.377  6866  6884 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-16 18:15:38.377  6866  6884 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:38.387  6866  6884 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-16 18:15:38.387  6866  6884 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:38.397  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-16 18:15:38.397  1014  1122 D WifiP2pService: InactiveState{ what=143375 }
08-16 18:15:38.397  1014  1122 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-16 18:15:38.397  1014  1123 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-16 18:15:38.397  1014  1123 E WifiStateMachine: VerifyingLinkState enter
,08-16 18:15:38.397  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 18:15:38.397  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-16 18:15:38.407  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:38.407  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:38.407  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:38.407  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:38.407  1014  1123 D WifiNative-wlan0: callSECApiInt - ID [210]
,08-16 18:15:38.407  1014  1125 E ConnectivityService: updateNetworkInfo()
,08-16 18:15:38.407  1014  1125 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null,
08-16 18:15:38.407  1014  1125 D ConnectivityService: Adding iface wlan0 to network 503
,08-16 18:15:38.417  6866  6889 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 35
08-16 18:15:38.417  1014  1142 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
08-16 18:15:38.417  1014  1142 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-16 18:15:38.417  1014  1142 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-16 18:15:38.417  1014  1142 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-16 18:15:38.417  1014  1142 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-16 18:15:38.417  6168  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 18:15:38.417  6168  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:38.417  6168  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:38.417  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:38.417  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:38.417  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 18:15:38.417  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:15:38.417  6168  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37cd133b removed from the list
08-16 18:15:38.417  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:38.417  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cf5a58 removed from the list
08-16 18:15:38.417  6168  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:38.417  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 18:15:38.427  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 18:15:38.427  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 18:15:38.427  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:38.427  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:38.427  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:38.427  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:38.427  1014  1123 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
08-16 18:15:38.437  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:38.437  1014  1345 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 18:15:38.437  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-16 18:15:38.437  1014  1345 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-16 18:15:38.437  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:38.437  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:15:38.437  1014  1345 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:38.437  1014  1345 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:38.437  1014  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-16 18:15:38.437  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:38.437  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:38.437  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:38.437  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cf5a58 not in the list
08-16 18:15:38.437  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 18:15:38.437  6168  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 18:15:38.437  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 18:15:38.437  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 18:15:38.437  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 18:15:38.437  6866  6877 D BtGatt.GattService: stopScan() - queue size =1
08-16 18:15:38.437  6866  6885 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-16 18:15:38.437  6866  6889 D BtGatt.ScanManager: filter size is 1
08-16 18:15:38.437  6866  6889 D BtGatt.ScanManager: delete FilterIndex - 5
08-16 18:15:38.437  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 18:15:38.437  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 18:15:38.437  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 18:15:38.437  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 18:15:38.437  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 18:15:38.447  6866  6884 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-16 18:15:38.447  6866  6884 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 18:15:38.447  6866  6889 D BtGatt.ScanManager: stopping BLe Batch
08-16 18:15:38.447  1014  1125 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 503
08-16 18:15:38.447  3616  3616 I Hs20UtilService: Starting #20
,08-16 18:15:38.447  6168  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 18:15:38.447  1322  1322 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-16 18:15:38.447  1322  1322 I NearbySettings: MountReceiver.onReceive - Keep current state
08-16 18:15:38.447  1014  1125 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
08-16 18:15:38.447  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 18:15:38.447  6168  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 18:15:38.447  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 18:15:38.447  6866  6884 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-16 18:15:38.447  6866  6884 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 18:15:38.447  6866  6889 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-16 18:15:38.457  1014  1125 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,08-16 18:15:38.457  3616  3649 I Hs20UtilService: Message received 5007
08-16 18:15:38.457  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-16 18:15:38.457  1014  1125 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-16 18:15:38.457  6866  6884 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-16 18:15:38.457  6866  6884 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 18:15:38.457  1014  1125 D ConnectivityService: Setting Dns servers for network 503 to [/192.168.1.1]
08-16 18:15:38.457  1014  1125 D ConnectivityService: LTETest block dns file not exists
,08-16 18:15:38.457  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 18:15:38.457  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 18:15:38.457  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:38.457  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:38.457  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:38.457  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:38.467  1014  1125 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,08-16 18:15:38.467  1014  1125 E ConnectivityService: updateNetworkInfo()
08-16 18:15:38.467  1014  1125 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 18:15:38.467  1014  1125 E ConnectivityService: updateNetworkInfo()
08-16 18:15:38.467  1014  1125 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
08-16 18:15:38.467  1014  1123 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-16 18:15:38.467  1014  1125 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
,08-16 18:15:38.467  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:38.467   286   286 E SMD     : DCD OFF
,08-16 18:15:38.467  1014  1123 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-16 18:15:38.477  1014  6960 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-16 18:15:38.477  1014  6960 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected,
08-16 18:15:38.477  1014  6960 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 18:15:38.477  1014  6960 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700",
08-16 18:15:38.477  1014  6960 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-16 18:15:38.477  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-16 18:15:38.477  1014  1014 I WifiTrafficPoller: mBoosterFLAG : 0
,08-16 18:15:38.477  1014  1014 I WifiTrafficPoller: current booster mode : FullMode
08-16 18:15:38.477   276   974 D EnterpriseController: uids 1000
08-16 18:15:38.477   276   974 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-16 18:15:38.477   276   974 D Netd    : getNetworkForDns: using netid 503 for uid 1000
,08-16 18:15:38.477  1014  1125 D ConnectivityService:    accepting network in place of null
08-16 18:15:38.477  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:15:38.477  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:38.477  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:38.477  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14efa817 removed from the list
08-16 18:15:38.477  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:38.477  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:38.477  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:38.477  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:15:38.477  6168  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18f11496 removed from the list
,08-16 18:15:38.477  6168  6168 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 18:15:38.477  6168  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:15:38.477  6168  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@313caeb3 added. We now have 2 listener(s)
08-16 18:15:38.477  6168  6168 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 18:15:38.477  6168  6168 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 18:15:38.477  1454  1454 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-16 18:15:38.477  1454  1454 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-16 18:15:38.477  1014  1014 D WifiNative-wlan0: callSECApiVoid - ID [212]
08-16 18:15:38.477  1014  1123 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-16 18:15:38.477  1014  1122 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-16 18:15:38.477  1014  1125 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-16 18:15:38.477  1014  1125 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
08-16 18:15:38.477  1014  1125 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-16 18:15:38.487  1171  1171 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 18:15:38.487  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-16 18:15:38.487  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:38.487  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:38.487  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:38.487  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:38.487  1014  1125 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,08-16 18:15:38.487  1014  1014 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,08-16 18:15:38.487  1014  1128 D Tethering: MasterInitialState.processMessage what=3
08-16 18:15:38.487  1014  1120 V NetworkStats: updateIfacesLocked()
08-16 18:15:38.487  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:38.487  1014  1120 V NetworkStats: performPollLocked(flags=0x1)
,08-16 18:15:38.497  1014  1120 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-16 18:15:38.497  1014  1120 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-16 18:15:38.497  1014  1125 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,08-16 18:15:38.497  1014  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-16 18:15:38.497  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-16 18:15:38.497  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:15:38.497  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:15:38.497  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:15:38.497  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5831c70 added. We now have 9 listener(s)
08-16 18:15:38.497  6168  6220 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 18:15:38.497  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 18:15:38.497  1171  1712 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-16 18:15:38.497  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:38.497  1014  1120 V NetworkStats: performPollLocked() took 9ms
08-16 18:15:38.497  3812  6230 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-16 18:15:38.507  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:38.507  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:38.507  1014  1121 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,08-16 18:15:38.507  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit,
08-16 18:15:38.507  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:38.507  1171  1171 D StatusBar.NetworkController: EthernetConnected: false,
08-16 18:15:38.507  1014  1027 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 18:15:38.507  1171  1171 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-16 18:15:38.507  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 18:15:38.507  1171  1171 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-16 18:15:38.507  1171  1171 D StatusBar.NetworkController: updateDataNetType()
08-16 18:15:38.507  1171  1171 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-16 18:15:38.507  1171  1171 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-16 18:15:38.517  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:38.517  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:38.517  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings,
,08-16 18:15:38.517  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 18:15:38.517  1171  1171 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,08-16 18:15:38.517  1171  1171 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-16 18:15:38.517  1171  1171 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-16 18:15:38.517  1171  1171 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 18:15:38.517  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-16 18:15:38.517  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:38.517  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-16 18:15:38.517  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:38.517  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:38.517  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:38.517  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:38.517  3616  3616 I Hs20UtilService: Starting #21
,08-16 18:15:38.517  3616  3649 I Hs20UtilService: Message received 5007
,08-16 18:15:38.527  6168  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:15:38.527  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:38.527  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:38.527  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:38.527  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:38.527  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:38.527  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:15:38.527  6168  6220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 18:15:38.527  1322  1322 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-16 18:15:38.527  6168  6220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:38.527  6168  6220 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 18:15:38.527  6168  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:15:38.527  6168  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@149e206e added. We now have 3 listener(s)
,08-16 18:15:38.527  1322  1322 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 18:15:38.527  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:15:38.527  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,08-16 18:15:38.527  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-16 18:15:38.527  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
08-16 18:15:38.527  1322  1322 I NearbySettings: MountReceiver.onReceive - Keep current state
08-16 18:15:38.527  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-16 18:15:38.527  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:15:38.527  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:15:38.527  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:15:38.527  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3849830f added. We now have 10 listener(s)
08-16 18:15:38.527  6168  6220 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:15:38.527  6168  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:15:38.527  6168  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:15:38.527  6168  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:15:38.527  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:38.527  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:38.527  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:15:38.527  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:15:38.527  6168  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@313caeb3 removed from the list
08-16 18:15:38.527  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:38.527  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5831c70 removed from the list
,08-16 18:15:38.527  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:15:38.537  6168  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:15:38.537  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:38.537  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:38.537  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:38.537  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 18:15:38.537  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 18:15:38.537  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 18:15:38.537  6168  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5831c70 not in the list
08-16 18:15:38.537  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:38.537  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:15:38.547  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 18:15:38.547  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:15:38.547  1014  1359 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 18:15:38.547  6168  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:15:38.547  1014  1359 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 18:15:38.547  1014  1359 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:38.547  1014  1359 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:38.547  1014  1359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 18:15:38.547  6168  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3849830f removed from the list
08-16 18:15:38.547  6168  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:15:38.547  6168  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:15:38.547  6168  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:15:38.547  6168  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:15:38.547  6168  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@149e206e removed from the list
,08-16 18:15:38.547  3616  3616 I Hs20UtilService: Starting #22
,08-16 18:15:38.547  6168  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-16 18:15:38.547  6168  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-16 18:15:38.547  6168  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-16 18:15:38.547  6168  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 18:15:38.547  6168  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-16 18:15:38.547  6168  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 18:15:38.547  1322  1322 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-16 18:15:38.547  1322  1322 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-16 18:15:38.547  3616  3649 I Hs20UtilService: Message received 5007
,08-16 18:15:38.557  6168  7000 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1176, name: My test thread name)
,08-16 18:15:38.557  6168  7000 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1176, thread name: My test thread name)
08-16 18:15:38.557  6168  7000 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1176, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-16 18:15:38.557  1014  3070 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-16 18:15:38.557  1014  1491 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
08-16 18:15:38.557  1014  1491 D SecContentProvider2: mCursor = null
,08-16 18:15:38.557  6168  7001 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1178, name: My test thread name)
08-16 18:15:38.557  6168  7001 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1178, thread name: My test thread name)
08-16 18:15:38.557  6168  7001 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1178, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-16 18:15:38.557  1014  1555 D SecContentProvider2: uri = 15 selection = getToastGravity
08-16 18:15:38.557  1014  1555 D SecContentProvider2: mCursor = null
,08-16 18:15:38.567  6168  6220 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-16 18:15:38.567  6168  6220 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-16 18:15:38.567  6168  6220 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-16 18:15:38.567  6168  6220 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-16 18:15:38.567  6168  6220 D com.test.thalitest.ThaliTestRunner: Total duration: 24465 ms
08-16 18:15:38.567  6168  6220 I jxcore-log: Total number of executed tests:  80
08-16 18:15:38.567  6168  6220 I jxcore-log: 
08-16 18:15:38.567  6168  6220 I jxcore-log: Number of passed tests:  80
08-16 18:15:38.567  6168  6220 I jxcore-log: 
08-16 18:15:38.567  1014  1719 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-16 18:15:38.567  1014  1719 D SecContentProvider2: mCursor = null
08-16 18:15:38.567  6168  6220 I jxcore-log: Number of failed tests:  0
08-16 18:15:38.567  6168  6220 I jxcore-log: 
08-16 18:15:38.567  6168  6220 I jxcore-log: Number of ignored tests:  0
08-16 18:15:38.567  6168  6220 I jxcore-log: 
08-16 18:15:38.567  6168  6220 I jxcore-log: Total duration:  24465
08-16 18:15:38.567  6168  6220 I jxcore-log: 
08-16 18:15:38.567  6168  6220 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-16 18:15:38.567  6168  6220 I jxcore-log: 
08-16 18:15:38.567  1014  1359 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
08-16 18:15:38.567  6168  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:15:38.567  6168  6220 I jxcore-log: 
08-16 18:15:38.567  1014  1359 D SecContentProvider2: mCursor = null
,08-16 18:15:38.577  1014  1027 D SecContentProvider2: uri = 15 selection = getToastEnabledState
08-16 18:15:38.577  1014  1027 D SecContentProvider2: mCursor = null
08-16 18:15:38.577  6168  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:15:38.577  6168  6220 I jxcore-log: 
08-16 18:15:38.577  1014  1558 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
08-16 18:15:38.577  1014  1558 D SecContentProvider2: mCursor = null
08-16 18:15:38.577  6168  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:15:38.577  6168  6220 I jxcore-log: 
08-16 18:15:38.577  6168  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:15:38.577  6168  6220 I jxcore-log: 
08-16 18:15:38.577  6168  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:15:38.577  6168  6220 I jxcore-log: 
08-16 18:15:38.577  6168  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:15:38.577  6168  6220 I jxcore-log: 
08-16 18:15:38.577  6168  6168 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-16 18:15:38.577  6168  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:15:38.577  6168  6220 I jxcore-log: 
08-16 18:15:38.587  6168  6168 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-16 18:15:38.587  1014  6960 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-16 18:15:38.587  6168  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 18:15:38.587  6168  6220 I jxcore-log: 
08-16 18:15:38.587  6168  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 18:15:38.587  6168  6220 I jxcore-log: 
08-16 18:15:38.587  6168  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 18:15:38.587  6168  6220 I jxcore-log: 
08-16 18:15:38.587  6168  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 18:15:38.587  6168  6220 I jxcore-log: 
08-16 18:15:38.587  6168  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 18:15:38.587  6168  6220 I jxcore-log: 
08-16 18:15:38.587  6168  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 18:15:38.587  6168  6220 I jxcore-log: 
08-16 18:15:38.587  6168  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 18:15:38.587  6168  6220 I jxcore-log: 
,08-16 18:15:38.587  6168  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 18:15:38.587  6168  6220 I jxcore-log: 
08-16 18:15:38.597  6168  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 18:15:38.597  6168  6220 I jxcore-log: 
08-16 18:15:38.597  6168  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 18:15:38.597  6168  6220 I jxcore-log: 
08-16 18:15:38.597  6168  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 18:15:38.597  6168  6220 I jxcore-log: 
08-16 18:15:38.597  6168  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 18:15:38.597  6168  6220 I jxcore-log: 
,08-16 18:15:38.597  6168  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 18:15:38.597  6168  6220 I jxcore-log: 
08-16 18:15:38.597  6168  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 18:15:38.597  6168  6220 I jxcore-log: 
08-16 18:15:38.597  6168  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 18:15:38.597  6168  6220 I jxcore-log: 
08-16 18:15:38.597  6168  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 18:15:38.597  6168  6220 I jxcore-log: 
,08-16 18:15:38.597  6168  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 18:15:38.597  6168  6220 I jxcore-log: 
08-16 18:15:38.597  6168  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 18:15:38.597  6168  6220 I jxcore-log: 
,08-16 18:15:38.597  6168  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 18:15:38.597  6168  6220 I jxcore-log: 
08-16 18:15:38.597  6168  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:15:38.597  6168  6220 I jxcore-log: 
08-16 18:15:38.597  6168  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 18:15:38.597  6168  6220 I jxcore-log: 
08-16 18:15:38.607   256   256 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=4, Uoast
,08-16 18:15:38.617  1014  1491 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1014
,08-16 18:15:38.627  1171  1171 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! ,
,08-16 18:15:38.647  1014  6960 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 16:15:38 GMT], X-Android-Received-Millis=[1471364138655], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471364138622]}
,08-16 18:15:38.647  1014  6960 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-16 18:15:38.647  1014  6960 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-16 18:15:38.647  1014  1125 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 503]
08-16 18:15:38.647  1171  1712 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 18:15:38.647  1014  1125 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
08-16 18:15:38.647  3812  6230 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 18:15:38.647  1014  1125 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
08-16 18:15:38.647  1014  1125 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
08-16 18:15:38.647  1014  1125 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-16 18:15:38.667  1171  1171 D StatusBar.NetworkController: EthernetConnected: false
,08-16 18:15:38.667  1171  1171 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-16 18:15:38.667  1171  1171 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-16 18:15:38.667  1171  1171 D StatusBar.NetworkController: updateDataNetType()
,08-16 18:15:38.667  1171  1171 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-16 18:15:38.667  1171  1171 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-16 18:15:38.667  1171  1171 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,08-16 18:15:38.667  1171  1171 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-16 18:15:38.667  1171  1171 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-16 18:15:38.667  1171  1171 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 18:15:38.667  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-16 18:15:38.667  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:38.667  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:38.667  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 18:15:38.667  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 18:15:38.767  6168  6168 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
,08-16 18:15:38.767  6168  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 18:15:38.767  6168  6220 I jxcore-log: 
,08-16 18:15:38.847  7003  7003 D AndroidRuntime: 
08-16 18:15:38.847  7003  7003 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-16 18:15:38.847  7003  7003 D AndroidRuntime: CheckJNI is OFF
,08-16 18:15:38.847  7003  7003 D AndroidRuntime: readGMSProperty: start
08-16 18:15:38.847  7003  7003 D AndroidRuntime: readGMSProperty: already setted!!
,08-16 18:15:38.847  7003  7003 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-16 18:15:38.847  7003  7003 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-16 18:15:38.847  7003  7003 D AndroidRuntime: readGMSProperty: end
,08-16 18:15:38.847  7003  7003 D AndroidRuntime: addProductProperty: start
,08-16 18:15:38.977  6168  6168 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-16 18:15:38.977  6168  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 18:15:38.977  6168  6220 I jxcore-log: 
,08-16 18:15:38.987  1014  1125 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:15:39.007  1014  1039 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:15:39.017  3119  3119 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,08-16 18:15:39.017  7003  7003 E AffinityControl: AffinityControl: registerfunction enter,
,08-16 18:15:39.027  6492  6492 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-16 18:15:39.027  6168  6168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:15:39.027  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:15:39.027  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:15:39.027  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:15:39.027  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:15:39.027  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:15:39.027  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:15:39.027  6168  6168 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 18:15:39.037  6168  6168 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 18:15:39.037  6475  6475 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-16 18:15:39.037  6168  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:15:39.037  6168  6220 I jxcore-log: 
,08-16 18:15:39.037  6475  6475 I PCWCLIENTTRACE_PushUtil: sales region : global
08-16 18:15:39.037  6475  6475 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-16 18:15:39.037  6475  6475 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:15:39.047  1014  1359 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
08-16 18:15:39.047  1014  1359 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-16 18:15:39.047  7003  7003 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-16 18:15:39.057  6492  6492 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,08-16 18:15:39.057  1729  1729 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-16 18:15:39.077  1729  1729 D accuweather: [KK AccuPhone]>>> U:4106 [0:0] getPWC : surface = 0, remote = 1
,08-16 18:15:39.077  1729  1729 D accuweather: [KK AccuPhone]>>> U:4284 [0:0] Store PWC = 1
08-16 18:15:39.077  1729  1729 D accuweather: [KK AccuPhone]>>> U:4158 [0:0] addPWC = 1
08-16 18:15:39.077  1729  1729 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-16 18:15:39.077  6507  6507 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,08-16 18:15:39.077  1014  1558 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 18:15:39.087  1014  1491 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 18:15:39.227  1014  1719 I art     : Explicit concurrent mark sweep GC freed 71453(3MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 27MB/41MB, paused 2.617ms total 159.497ms
,08-16 18:15:39.227  1014  1719 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-16 18:15:39.227  1014  1719 D SecContentProvider2: mCursor = null
,08-16 18:15:39.227  1014  1027 D PackageManager: START PACKAGE DELETE: observer{772639456}
08-16 18:15:39.227  1014  1027 D PackageManager: pkg{<packageName>}
08-16 18:15:39.227  1014  1027 D PackageManager: user{0}
08-16 18:15:39.227  1014  1027 D PackageManager: caller{2000}
08-16 18:15:39.227  1014  1027 D PackageManager: flags{2}
08-16 18:15:39.227  1014  1027 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-16 18:15:39.227  1014  1027 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-16 18:15:39.227  1014  1027 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-16 18:15:39.227  1014  1027 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-16 18:15:39.227  1014  1027 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-16 18:15:39.237  1014  1055 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-16 18:15:39.237  1014  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-16 18:15:39.237  1014  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-16 18:15:39.237  1014  1055 D ApplicationPolicy: getApplicationUninstallationEnabled
08-16 18:15:39.237  1014  1055 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-16 18:15:39.237  1014  1055 D PackageManager: !@killApplicatoin: 10155, uninstall pkg
,08-16 18:15:39.247  1014  1040 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
,08-16 18:15:39.247  1014  1040 I ActivityManager: Killing 6168:com.test.thalitest/u0a155 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-16 18:15:39.347  1014  1040 I ActivityManager:   Force finishing activity ActivityRecord{2f69af33 u0 com.test.thalitest/.MainActivity t128}
,08-16 18:15:39.347  1014  1040 W ActivityManager: mDVFSHelper.acquire()
,08-16 18:15:39.367  1729  1729 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-16 18:15:39.367  1014  1040 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-16 18:15:39.367  1729  1729 D accuweather: [KK AccuPhone]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,08-16 18:15:39.377  1292  2722 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 11
,08-16 18:15:39.377  1014  1040 D InputDispatcher: Focus left window: 6168
,08-16 18:15:39.377  1014  1040 D InputDispatcher: Focused application released
,08-16 18:15:39.387  1014  1045 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-16 18:15:39.387  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-16 18:15:39.387  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-16 18:15:39.387  6507  6507 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,08-16 18:15:39.387  1014  1719 E WindowState: getStack: Window{3646c313 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowState.isDefaultDisplay:1845 com.android.server.wm.WindowState.getMultiWindowStyleLw:2377 com.android.internal.policy.impl.multiwindow.MultiPhoneWindowManager.applyPostLayoutPolicyLw:712 
,08-16 18:15:39.397  6507  6507 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,08-16 18:15:39.397  1014  1719 E WindowState: getStack: Window{3646c313 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowManagerService.performLayoutAndPlaceSurfacesLockedInner:12706 com.android.server.wm.WindowManagerService.performLayoutAndPlaceSurfacesLockedLoop:11498 com.android.server.wm.WindowManagerService.performLayoutAndPlaceSurfacesLocked:11440 com.android.server.wm.WindowManagerService.relayoutWindow:4398 
08-16 18:15:39.397  6507  6507 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
08-16 18:15:39.397  1014  1055 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,08-16 18:15:39.397  1014  1719 E WindowState: getStack: Window{3646c313 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowState.isDefaultDisplay:1845 com.android.server.wm.WindowState.getMultiWindowStyleLw:2377 com.android.server.wm.WindowManagerService.performLayoutAndPlaceSurfacesLockedInner:12748 
,08-16 18:15:39.397  6443  6443 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-16 18:15:39.397  1014  1719 E WindowState: getStack: Window{3646c313 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowState.isDefaultDisplay:1845 com.android.server.wm.WindowState.getMultiWindowStyleLw:2377 com.android.server.wm.WindowManagerService.performLayoutAndPlaceSurfacesLockedInner:12748 
08-16 18:15:39.397  6443  6443 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 18:15:39.397  1014  1719 E WindowState: getStack: Window{3646c313 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowState.isDefaultDisplay:1845 com.android.server.wm.WindowState.getMultiWindowStyleLw:2377 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:1933 
08-16 18:15:39.397  6443  6443 D SecurityLogAgent: StateMachine : Current State = 1
08-16 18:15:39.397  1014  1719 E WindowState: getStack: Window{3646c313 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowStateAnimator.updateSurfaceWindowCrop:1663 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:2032 com.android.server.wm.WindowManagerService.performLayoutAndPlaceSurfacesLockedInner:12811 
,08-16 18:15:39.397  1014  1719 E WindowState: getStack: Window{3646c313 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowState.isDefaultDisplay:1845 com.android.server.wm.WindowStateAnimator.updateSurfaceWindowCrop:1673 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:2032 
08-16 18:15:39.397  1014  1719 E WindowState: getStack: Window{3646c313 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowState.isDefaultDisplay:1845 com.android.server.wm.WindowState.getMultiWindowStyleLw:2377 com.android.server.wm.WindowStateAnimator.updateSurfaceWindowCrop:1705 
,08-16 18:15:39.397  1014  1719 E WindowState: getStack: Window{3646c313 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowStateAnimator.updateSurfaceWindowCrop:1707 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:2032 com.android.server.wm.WindowManagerService.performLayoutAndPlaceSurfacesLockedInner:12811 com.android.server.wm.WindowManagerService.performLayoutAndPlaceSurfacesLockedLoop:11498 
,08-16 18:15:39.397  1014  1719 E WindowState: getStack: Window{3646c313 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowStateAnimator.updateSurfaceWindowCrop:1707 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:2032 com.android.server.wm.WindowManagerService.performLayoutAndPlaceSurfacesLockedInner:12811 com.android.server.wm.WindowManagerService.performLayoutAndPlaceSurfacesLockedLoop:11498 
,08-16 18:15:39.397  1014  1719 E WindowState: getStack: Window{3646c313 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowState.isDefaultDisplay:1845 com.android.server.wm.WindowState.getMultiWindowStyleLw:2377 com.android.server.wm.WindowStateAnimator.updateSurfaceWindowCrop:1723 
08-16 18:15:39.397  1014  1719 E WindowState: getStack: Window{3646c313 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowState.isDefaultDisplay:1845 com.android.server.wm.WindowState.getMultiWindowStyleLw:2377 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:1933 
,08-16 18:15:39.397  1014  1719 E WindowState: getStack: Window{3646c313 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowStateAnimator.updateSurfaceWindowCrop:1663 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:2032 com.android.server.wm.WindowManagerService.performLayoutAndPlaceSurfacesLockedInner:12812 
08-16 18:15:39.397  1014  1719 E WindowState: getStack: Window{3646c313 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowState.isDefaultDisplay:1845 com.android.server.wm.WindowStateAnimator.updateSurfaceWindowCrop:1673 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:2032 
,08-16 18:15:39.407  1014  1719 E WindowState: getStack: Window{3646c313 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowState.isDefaultDisplay:1845 com.android.server.wm.WindowState.getMultiWindowStyleLw:2377 com.android.server.wm.WindowStateAnimator.updateSurfaceWindowCrop:1705 
08-16 18:15:39.407  1014  1719 E WindowState: getStack: Window{3646c313 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowStateAnimator.updateSurfaceWindowCrop:1707 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:2032 com.android.server.wm.WindowManagerService.performLayoutAndPlaceSurfacesLockedInner:12812 com.android.server.wm.WindowManagerService.performLayoutAndPlaceSurfacesLockedLoop:11498 
,08-16 18:15:39.407  1014  1719 E WindowState: getStack: Window{3646c313 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowStateAnimator.updateSurfaceWindowCrop:1707 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:2032 com.android.server.wm.WindowManagerService.performLayoutAndPlaceSurfacesLockedInner:12812 com.android.server.wm.WindowManagerService.performLayoutAndPlaceSurfacesLockedLoop:11498 
08-16 18:15:39.407  1014  1719 E WindowState: getStack: Window{3646c313 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowState.isDefaultDisplay:1845 com.android.server.wm.WindowState.getMultiWindowStyleLw:2377 com.android.server.wm.WindowStateAnimator.updateSurfaceWindowCrop:1723 
,08-16 18:15:39.407  1014  1719 E WindowState: getStack: Window{3646c313 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowState.isDefaultDisplay:1845 com.android.server.wm.WindowState.getMultiWindowStyleLw:2377 com.android.server.wm.InputMonitor.updateInputWindowsLw:459 
08-16 18:15:39.407  1014  1719 E WindowState: getStack: Window{3646c313 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowState.getDisplayId:1229 com.android.server.wm.InputMonitor.updateInputWindowsLw:464 com.android.server.wm.WindowManagerService.performLayoutAndPlaceSurfacesLockedInner:13131 
08-16 18:15:39.407  1014  1719 E WindowState: getStack: Window{3646c313 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowState.isDefaultDisplay:1845 com.android.server.wm.WindowState.getMultiWindowStyleLw:2377 com.android.server.wm.InputMonitor.addInputWindowHandleLw:200 
08-16 18:15:39.407  1014  1719 E WindowState: getStack: Window{3646c313 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getStackBounds:1265 com.android.server.wm.InputMonitor.addInputWindowHandleLw:312 com.android.server.wm.InputMonitor.updateInputWindowsLw:484 com.android.server.wm.WindowManagerService.performLayoutAndPlaceSurfacesLockedInner:13131 
08-16 18:15:39.407  1014  1719 E WindowState: getStack: Window{3646c313 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowState.isDefaultDisplay:1845 com.android.server.wm.WindowState.getMultiWindowStyleLw:2377 com.android.server.wm.WindowState.getStackBounds:1272 
08-16 18:15:39.407  1014  1719 E WindowState: getStack: Window{3646c313 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowState.isDefaultDisplay:1845 com.android.server.wm.WindowState.getMultiWindowStyleLw:2377 com.android.server.wm.WindowState.canReceiveKeys:1675 
08-16 18:15:39.407  6443  6443 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-16 18:15:39.407  1014  1719 E WindowState: getStack: Window{3646c313 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowState.isDefaultDisplay:1845 com.android.server.wm.WindowState.getMultiWindowStyleLw:2377 com.android.server.wm.InputMonitor.updateInputWindowsLw:459 
08-16 18:15:39.407  1014  1719 E WindowState: getStack: Window{3646c313 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowState.getDisplayId:1229 com.android.server.wm.InputMonitor.updateInputWindowsLw:464 com.android.server.wm.WindowManagerService.relayoutWindow:4435 
08-16 18:15:39.407  1014  1719 E WindowState: getStack: Window{3646c313 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowState.isDefaultDisplay:1845 com.android.server.wm.WindowState.getMultiWindowStyleLw:2377 com.android.server.wm.InputMonitor.addInputWindowHandleLw:200 
08-16 18:15:39.407  1014  1719 E WindowState: getStack: Window{3646c313 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getStackBounds:1265 com.android.server.wm.InputMonitor.addInputWindowHandleLw:312 com.android.server.wm.InputMonitor.updateInputWindowsLw:484 com.android.server.wm.WindowManagerService.relayoutWindow:4435 
08-16 18:15:39.407  1014  1719 E WindowState: getStack: Window{3646c313 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowState.isDefaultDisplay:1845 com.android.server.wm.WindowState.getMultiWindowStyleLw:2377 com.android.server.wm.WindowState.getStackBounds:1272 
08-16 18:15:39.417  1014  1719 E WindowState: getStack: Window{3646c313 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowState.isDefaultDisplay:1845 com.android.server.wm.WindowState.getMultiWindowStyleLw:2377 com.android.server.wm.WindowState.canReceiveKeys:1675 
08-16 18:15:39.417  1014  1055 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
08-16 18:15:39.427  1729  1729 D accuweather: [KK AccuPhone]>>> U:4250 [0:0] Store PWC succeed
08-16 18:15:39.437  1014  1045 E WindowState: getStack: Window{3646c313 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowStateAnimator.stepAnimationLocked:341 com.android.server.wm.WindowAnimator.updateWindowsLocked:292 com.android.server.wm.WindowAnimator.animateLocked:806 
08-16 18:15:39.437  1014  1045 E WindowState: getStack: Window{3646c313 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowState.isDefaultDisplay:1845 com.android.server.wm.WindowState.getMultiWindowStyleLw:2377 com.android.server.wm.WindowAnimator.updateWindowsLocked:451 
08-16 18:15:39.437  1014  1045 E WindowState: getStack: Window{3646c313 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowState.getDisplayId:1229 com.android.server.wm.WindowStateAnimator.computeShownFrameLocked:1319 com.android.server.wm.WindowStateAnimator.prepareSurfaceLocked:2059 
08-16 18:15:39.437  1014  1045 E WindowState: getStack: Window{3646c313 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowState.getDisplayId:1229 com.android.server.wm.WindowStateAnimator.computeShownFrameLocked:1555 com.android.server.wm.WindowStateAnimator.prepareSurfaceLocked:2059 
08-16 18:15:39.437  1014  1045 E WindowState: getStack: Window{3646c313 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowState.isDefaultDisplay:1845 com.android.server.wm.WindowState.getMultiWindowStyleLw:2377 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:1933 
08-16 18:15:39.437  1014  1045 E WindowState: getStack: Window{3646c313 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowStateAnimator.updateSurfaceWindowCrop:1663 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:2032 com.android.server.wm.WindowStateAnimator.prepareSurfaceLocked:2061 
08-16 18:15:39.437  3927  3927 I art     : Explicit concurrent mark sweep GC freed 2686(164KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 6MB/11MB, paused 699us total 24.692ms
08-16 18:15:39.437  1014  1045 E WindowState: getStack: Window{3646c313 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowState.isDefaultDisplay:1845 com.android.server.wm.WindowStateAnimator.updateSurfaceWindowCrop:1673 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:2032 
08-16 18:15:39.437  1014  1045 E WindowState: getStack: Window{3646c313 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowState.isDefaultDisplay:1845 com.android.server.wm.WindowState.getMultiWindowStyleLw:2377 com.android.server.wm.WindowStateAnimator.updateSurfaceWindowCrop:1705 
08-16 18:15:39.437  1014  1045 E WindowState: getStack: Window{3646c313 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowStateAnimator.updateSurfaceWindowCrop:1707 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:2032 com.android.server.wm.WindowStateAnimator.prepareSurfaceLocked:2061 com.android.server.wm.WindowAnimator.animateLocked:812 
08-16 18:15:39.437  1014  1045 E WindowState: getStack: Window{3646c313 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowStateAnimator.updateSurfaceWindowCrop:1707 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:2032 com.android.server.wm.WindowStateAnimator.prepareSurfaceLocked:2061 com.android.server.wm.WindowAnimator.animateLocked:812 
08-16 18:15:39.437  1014  1045 E WindowState: getStack: Window{3646c313 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowState.isDefaultDisplay:1845 com.android.server.wm.WindowState.getMultiWindowStyleLw:2377 com.android.server.wm.WindowStateAnimator.updateSurfaceWindowCrop:1723 
,08-16 18:15:39.447  1014  1557 I WindowState: WIN DEATH: Window{3646c313 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-16 18:15:39.447   256   451 I SurfaceFlinger: id=14 Removed NainActivit (6/9)
08-16 18:15:39.447   256   445 I SurfaceFlinger: id=14 Removed NainActivit (-2/9)
08-16 18:15:39.447  1014  1557 E WindowState: getStack: Window{3646c313 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowState.getWindowList:1991 com.android.server.wm.WindowManagerService.removeWindowInnerLocked:3693 com.android.server.wm.WindowManagerService.removeWindowLocked:3559 
08-16 18:15:39.447  1014  1557 E WindowState: getStack: Window{3646c313 u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowManagerService.removeWindowInnerLocked:3698 com.android.server.wm.WindowManagerService.removeWindowLocked:3559 com.android.server.wm.WindowState$DeathRecipient.binderDied:1650 
08-16 18:15:39.457  5475  5475 I art     : Explicit concurrent mark sweep GC freed 386(27KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/11MB, paused 766us total 40.057ms
08-16 18:15:39.457  1014  1039 E libprocessgroup: failed to kill 1 processes for processgroup 6168
08-16 18:15:39.457  1014  1096 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-16 18:15:39.457  1773  1773 E SamsungIME: mOCRHelper is null
08-16 18:15:39.467  1931  2101 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-16 18:15:39.477  3119  3119 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,08-16 18:15:39.487  3119  3119 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 3
,08-16 18:15:39.487  3812  3812 I art     : Explicit concurrent mark sweep GC freed 22959(1390KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 15MB/21MB, paused 1.856ms total 85.052ms
,08-16 18:15:39.497  1014  1125 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-16 18:15:39.497  3119  3119 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,08-16 18:15:39.507  1439  1439 D PersonaManager: isKioskContainerExistOnDevice
,08-16 18:15:39.507  3119  3119 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,08-16 18:15:39.507  3119  3119 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 3
,08-16 18:15:39.517  3119  3119 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,08-16 18:15:39.517  3652  3652 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 16 18:15:39 GMT+02:00 2016
,08-16 18:15:39.527  1014  3070 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-16 18:15:39.527  1014  3070 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-16 18:15:39.527  3119  3119 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,08-16 18:15:39.527  1014  3070 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:39.527  1014  3070 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:39.527  1014  3070 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-16 18:15:39.537  3119  3119 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,08-16 18:15:39.547  3652  3652 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,08-16 18:15:39.547  1014  1120 V NetworkStats: removeUidsLocked() for UIDs [10155]
08-16 18:15:39.547  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:39.547  1014  1120 V NetworkStats: performPollLocked(flags=0x3)
,08-16 18:15:39.547  1014  1120 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 18:15:39.547  1014  1120 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 18:15:39.557  1014  1120 V NetworkStats: performPollLocked() took 6ms
08-16 18:15:39.557  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:39.557  1439  1439 D RegisteredServicesCache: empty dynamic service
,08-16 18:15:39.577  3652  3652 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,08-16 18:15:39.577  3119  3119 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,08-16 18:15:39.577  1014  1039 D EnterpriseDeviceManagerService: Package has changed for user 0
08-16 18:15:39.577  1014  1039 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-16 18:15:39.577  1014  1039 W TextServicesManagerService: no available spell checker services found
,08-16 18:15:39.577  3652  3652 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-16 18:15:39.587  1014  1027 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,08-16 18:15:39.597  1014  1027 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,08-16 18:15:39.597  3119  3119 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 3
,08-16 18:15:39.607  3119  3119 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,08-16 18:15:39.617  3652  3652 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-16 18:15:39.617  3119  3119 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,08-16 18:15:39.617  3119  3119 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,08-16 18:15:39.617  3119  3119 I DBG_DM  : [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,08-16 18:15:39.617  3119  3119 I DBG_DM  : [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,08-16 18:15:39.627  3652  7017 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-16 18:15:39.627  3652  7017 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-16 18:15:39.627  1014  1558 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-16 18:15:39.627  1014  1558 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-16 18:15:39.627  1014  1558 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-16 18:15:39.627  3119  3119 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,08-16 18:15:39.637  6668  6668 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:15:39.637  6668  6668 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-16 18:15:39.637  6668  6668 I DIAGMON_AGENT: ./extraInfo: "NG700"
,08-16 18:15:39.637   256   256 I SurfaceFlinger: id=16 createSurf (720x1280),1 flag=404, YUIInstallC
,08-16 18:15:39.637  6668  6668 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,08-16 18:15:39.647  1014  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-16 18:15:39.647  1014  1483 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
08-16 18:15:39.647  1014  1483 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,08-16 18:15:39.647  1014  1483 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:39.647  1014  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:39.647  1014  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,08-16 18:15:39.647  1014  1491 D InputDispatcher: Focus entered window: 3119
,08-16 18:15:39.657  3119  3119 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-16 18:15:39.657  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-16 18:15:39.657  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-16 18:15:39.657  1014  1133 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 18:15:39.657  1014  1133 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-16 18:15:39.657  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:39.657  1014  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 18:15:39.657  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 18:15:39.667  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 18:15:39.667  3652  7017 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,08-16 18:15:39.677   276   974 D EnterpriseController: uids 10012
08-16 18:15:39.677   276   974 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-16 18:15:39.677   276   974 D Netd    : getNetworkForDns: using netid 503 for uid 10012
08-16 18:15:39.677  3652  7017 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().START
,08-16 18:15:39.687  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 18:15:39.687  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 18:15:39.687  3652  7017 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().START 
,08-16 18:15:39.687  1014  1345 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-16 18:15:39.707  1014  1345 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6168 uid 10155
,08-16 18:15:39.707  1014  7026 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-16 18:15:39.717  1014  3070 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-16 18:15:39.717  1014  3070 D SecContentProvider2: mCursor = null
,08-16 18:15:39.717  3119  3119 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@70f23a3 time:150043
,08-16 18:15:39.717  1773  1773 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-16 18:15:39.717  3652  7017 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().END 
,08-16 18:15:39.717  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 18:15:39.727  3119  3119 V ActivityThread: updateVisibility : ActivityRecord{2255361c token=android.os.BinderProxy@70f23a3 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,08-16 18:15:39.727  1014  1014 D RCPManagerService: PackageReceiver onReceive()
,08-16 18:15:39.727  1014  1014 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-16 18:15:39.727  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 18:15:39.737  1014  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{17fe95cb u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t127} time:150060
08-16 18:15:39.737  1014  1045 W ActivityManager: mDVFSHelper.release()
,08-16 18:15:39.737  3652  7017 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,08-16 18:15:39.737  1014  1014 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-16 18:15:39.737  1014  1014 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,08-16 18:15:39.737  1439  1439 D RegisteredComponentCache: Collect Tech packages for Knox
,08-16 18:15:39.737  1439  1439 D PersonaManager: isKioskContainerExistOnDevice
,08-16 18:15:39.737  1014  1014 D OTPFW   : OtpDbHelper::getInstance New instance created
,08-16 18:15:39.737  1014  1014 D OTPFW   : DBIntegrity::getInstance - New instance created
,08-16 18:15:39.737  3812  3812 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-16 18:15:39.747  1014  1014 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
,08-16 18:15:39.747  1014  1014 I OTPFW   : ProvisionData::getAllEntries Enter
,08-16 18:15:39.747  1014  1014 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-16 18:15:39.747  1014  1014 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-16 18:15:39.747  1014  1014 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-16 18:15:39.747  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-16 18:15:39.747  1014  1014 V EnterpriseBillingPolicy: uID is 10155
08-16 18:15:39.747  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
08-16 18:15:39.747  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-16 18:15:39.747  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-16 18:15:39.747  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-16 18:15:39.747  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-16 18:15:39.747  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-16 18:15:39.747  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-16 18:15:39.747  1014  1014 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-16 18:15:39.747  1014  2723 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,08-16 18:15:39.747  3812  4527 I iu.UploadsManager: num queued entries: 0
08-16 18:15:39.747  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-16 18:15:39.747  1014  1014 V EnterpriseBillingPolicy: uID is 10155
08-16 18:15:39.747  3812  4527 I iu.UploadsManager: num updated entries: 0
08-16 18:15:39.747  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
08-16 18:15:39.747  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-16 18:15:39.757  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-16 18:15:39.757  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-16 18:15:39.757  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-16 18:15:39.757  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-16 18:15:39.757  3652  3652 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,08-16 18:15:39.767  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-16 18:15:39.767  1014  1159 D TaskPersister: removeObsoleteFile: deleting file=128_task.xml
,08-16 18:15:39.767  1014  1159 D TaskPersister: removeObsoleteFile: deleting file=127_task.xml
,08-16 18:15:39.767  1014  1014 V AlarmManagerEXT: com.test.thalitest(10155) is removed.
,08-16 18:15:39.767  1014  1014 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
08-16 18:15:39.767  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-16 18:15:39.767  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
,08-16 18:15:39.767  1171  1171 D PanelView: There is/are notification(s) 
,08-16 18:15:39.787  3812  4527 I iu.SyncManager: NEXT; no task
,08-16 18:15:39.797  6722  6722 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:15:39.807  1931  7019 I qtaguid : Tagging socket 49 with tag 1000040700000000{268436487,0} for uid -1, pid: 1931, getuid(): 10012
,08-16 18:15:39.807  6722  6722 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
08-16 18:15:39.807  6722  6722 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-16 18:15:39.807  1014  1055 W art     : Suspending all threads took: 11.741ms
,08-16 18:15:39.827  3177  7030 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-16 18:15:39.827  3177  7030 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,08-16 18:15:39.827  3177  7030 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-16 18:15:39.837  5884  5884 D WaitQueueForNetworkActivate: notifyNetworkActivated
,08-16 18:15:39.847  5794  5794 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,08-16 18:15:39.857  5993  5993 I SA      : [OR] onReceive log=[SA = 2.1.0240 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOJ6 PSS = 4.978878039476607  ]
,08-16 18:15:39.857  5993  5993 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
08-16 18:15:39.857  5993  5993 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-16 18:15:39.867  1014  1039 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-16 18:15:39.867  5993  5993 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-16 18:15:39.867  5993  5993 I SA      : [OR] == isSIMCardReady false ==
,08-16 18:15:39.867  1171  1171 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,08-16 18:15:39.867  5993  5993 I SA      : [SCU] == networkStateCheck == true
,08-16 18:15:39.867  5993  5993 I SA      : [DM] getCountryCodeFromCSC : PL
08-16 18:15:39.867  5993  5993 I SA      : isChinaCountryCode : false
08-16 18:15:39.867  5993  5993 I SA      : [SCU] is ChinestModel Data Restricted   : false
08-16 18:15:39.867  5993  5993 I SA      : [OR] == networkStateCheck true ==
,08-16 18:15:39.877  1171  1171 D PersonaManager: isKioskContainerExistOnDevice
08-16 18:15:39.877  1171  1171 D PersonaManager: isKioskContainerExistOnDevice
,08-16 18:15:39.877  1171  1171 D PanelView: There is/are notification(s) 
08-16 18:15:39.877  1171  1171 D PanelView: kidsfalse mQsExpansionEnabled:true
,08-16 18:15:39.877  5993  5993 I SA      : [OR] GetMyCountryZoneTask
,08-16 18:15:39.877  5993  5993 I SA      : [OR] onReceive END
08-16 18:15:39.877  1171  1171 D PersonaManager: isKioskContainerExistOnDevice
08-16 18:15:39.877  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-16 18:15:39.877  1171  1171 D PanelView: There is/are notification(s) 
08-16 18:15:39.877  1171  1171 D PanelView: kidsfalse mQsExpansionEnabled:true
,08-16 18:15:39.887  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 18:15:39.887  1226  1226 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:15:39.897  6866  6882 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-16 18:15:39.897  1014  1719 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,08-16 18:15:39.897  1014  1719 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
08-16 18:15:39.897  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 18:15:39.897  1014  1719 W ActivityManager: userId = 0, bbcId = -10000
,08-16 18:15:39.897  1014  1719 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:39.897  1014  1719 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,08-16 18:15:39.897  1014  1055 I art     : Explicit concurrent mark sweep GC freed 42432(3MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 28MB/42MB, paused 24.405ms total 374.935ms
,08-16 18:15:39.917  3177  7030 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,08-16 18:15:39.917  3177  7030 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,08-16 18:15:39.917  1014  1055 D PackageManager: delete codoeFile: 
,08-16 18:15:39.917  1014  1039 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.,
08-16 18:15:39.917  1014  1039 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 18:15:39.917  1014  1039 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-16 18:15:39.917  3177  7030 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,08-16 18:15:39.927  3177  7030 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
08-16 18:15:39.927  3177  7030 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
08-16 18:15:39.927  5993  7035 I SA      : [SRS] prepareGetMyCountryZone
,08-16 18:15:39.927  3177  7030 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
08-16 18:15:39.927  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 18:15:39.927  3177  7030 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,08-16 18:15:39.927  1014  1055 D AASAuninstall: userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
,08-16 18:15:39.927  1014  1055 I AASA_removePackage: UID=10155 Target=com.test.thalitest
,08-16 18:15:39.927  3177  7030 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,08-16 18:15:39.937  1014  1055 D PackageManager: result of delete: 1{772639456}
,08-16 18:15:39.937  5993  7035 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-16 18:15:39.937  5993  7035 I SA      : [SSP] query invoked
,08-16 18:15:39.937  3177  7030 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,08-16 18:15:39.937  1014  1558 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
08-16 18:15:39.937  1014  1558 D SecContentProvider2: mCursor = null
,08-16 18:15:39.947  1171  1171 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,08-16 18:15:39.947  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 18:15:39.947  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 18:15:39.957  3177  7030 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-16 18:15:39.957  7003  7003 D AndroidRuntime: Shutting down VM
08-16 18:15:39.957  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-16 18:15:39.957  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-16 18:15:39.957  5993  7035 I SA      : [TPMU] GetMccFromDB : null
,08-16 18:15:39.957  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 18:15:39.957  5993  7035 I SA      : [SCU] getMccFromPreferece mcc = 260
,08-16 18:15:39.957  5993  7035 I SA      : [LBE] isSupportCheckDomainRegion : false
08-16 18:15:39.957  5993  7035 I SA      : [TPM] isNoProxy(default) : true
,08-16 18:15:39.957  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-16 18:15:39.957  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-16 18:15:39.967  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-16 18:15:39.967  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-16 18:15:39.967  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 18:15:39.967  1014  1039 D UsbSettingsManager: clearDefaults: com.test.thalitest
08-16 18:15:39.967  1014  1039 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-16 18:15:39.967  5993  7035 E File    : fail readDirectory() errno=2
,08-16 18:15:39.977  1014  1055 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-16 18:15:39.977  1014  1055 D PackageManager: userId{-1}
08-16 18:15:39.977  1014  1055 D PackageManager: andCode{true}
,08-16 18:15:39.997  1014  1055 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-16 18:15:40.087  1014  3070 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,08-16 18:15:40.087  1014  3070 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,08-16 18:15:40.087  1014  3070 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:40.087  1014  3070 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-16 18:15:40.087  1014  3070 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,08-16 18:15:40.087  1014  1040 I splitIntent: Queue : backgroundsplit_2 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-16 18:15:40.097  5884  5884 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,08-16 18:15:40.097  5884  5884 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,08-16 18:15:40.097  5884  5884 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,08-16 18:15:40.097  5884  5884 D InitializeManagerStateMachine: exit::IDLE
08-16 18:15:40.097  5884  5884 D InitializeManagerStateMachine: entry::NETWORK_CHECK
08-16 18:15:40.097  3652  3652 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 16 18:15:40 GMT+02:00 2016
,08-16 18:15:40.097  1014  1026 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-16 18:15:40.097  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-16 18:15:40.107  5884  5884 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
08-16 18:15:40.107  5884  5884 D InitializeManagerStateMachine: exit::NETWORK_CHECK
08-16 18:15:40.107  5884  5884 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
08-16 18:15:40.107  5884  5884 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
08-16 18:15:40.107  5884  5884 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
08-16 18:15:40.107  5884  5884 D InitializeManagerStateMachine: entry::SUCCESS
08-16 18:15:40.107  5884  5884 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,08-16 18:15:40.107  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:40.107  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:40.107  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-16 18:15:40.107  3652  3652 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
08-16 18:15:40.107  5884  5884 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
08-16 18:15:40.107  5884  5884 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,08-16 18:15:40.107  1014  1026 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
08-16 18:15:40.107  5884  5884 D InitializeManagerStateMachine: exit::SUCCESS
08-16 18:15:40.107  1014  1026 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
08-16 18:15:40.107  5884  5884 D InitializeManagerStateMachine: entry::IDLE
,08-16 18:15:40.107  1014  1026 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-16 18:15:40.107  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:40.107  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:40.107  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:40.107  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:40.117  3652  3652 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
08-16 18:15:40.117  3652  3652 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-16 18:15:40.127  3652  3652 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-16 18:15:40.127  3652  7042 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) },
,08-16 18:15:40.127  7043  7043 E Zygote  : MountEmulatedStorage()
08-16 18:15:40.127  7043  7043 E Zygote  : v2
08-16 18:15:40.127  7043  7043 I libpersona: KNOX_SDCARD checking this for 10094
08-16 18:15:40.127  7043  7043 I libpersona: KNOX_SDCARD not a persona
,08-16 18:15:40.137  3652  7042 I KLMS-2.5.183: : KLMSIntentService(): PACKAGE_REMOVED
,08-16 18:15:40.137  7043  7043 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 18:15:40.137  7043  7043 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 18:15:40.137  7043  7043 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 18:15:40.137  3652  7042 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().START
,08-16 18:15:40.147  1014  1026 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7043 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a,
08-16 18:15:40.147  3652  7042 I KLMS-2.5.183: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,08-16 18:15:40.147  1014  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,08-16 18:15:40.157  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:40.157  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:40.157  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:40.157  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:40.167  7003  7003 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
,08-16 18:15:40.167   308   308 I art     : Explicit concurrent mark sweep GC freed 8717(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 2.510ms total 27.774ms
,08-16 18:15:40.187   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 608us total 17.197ms
,08-16 18:15:40.197  7043  7043 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:40.197  7043  7043 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:40.207   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 609us total 17.428ms
,08-16 18:15:40.207  3652  7042 I KLMS-2.5.183: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-16 18:15:40.217  3652  7042 I KLMS-2.5.183: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-16 18:15:40.217  3652  7042 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().END
,08-16 18:15:40.217  7058  7058 E Zygote  : MountEmulatedStorage(),
,08-16 18:15:40.217  7058  7058 E Zygote  : v2
,08-16 18:15:40.227  7058  7058 I libpersona: KNOX_SDCARD checking this for 10044
08-16 18:15:40.227  7058  7058 I libpersona: KNOX_SDCARD not a persona
,08-16 18:15:40.227  7058  7058 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 18:15:40.227  1014  1040 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7058 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,08-16 18:15:40.227  7058  7058 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
08-16 18:15:40.227  7058  7058 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-16 18:15:40.237  3652  3652 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,08-16 18:15:40.247  1014  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,08-16 18:15:40.247  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:40.247  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:40.247  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:40.247  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:40.257  7058  7058 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 18:15:40.257  7058  7058 D ActivityThread: Added TimaKeyStore provider
08-16 18:15:40.257  7075  7075 E Zygote  : MountEmulatedStorage(),
08-16 18:15:40.257  7075  7075 E Zygote  : v2
08-16 18:15:40.257  7075  7075 I libpersona: KNOX_SDCARD checking this for 10149
08-16 18:15:40.257  7075  7075 I libpersona: KNOX_SDCARD not a persona
08-16 18:15:40.267  7075  7075 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 18:15:40.267  7075  7075 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 18:15:40.267  1014  1040 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7075 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 18:15:40.267  7075  7075 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-16 18:15:40.267  7043  7043 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
08-16 18:15:40.267  7043  7043 D elm:15183: ELMEngine.ELMEngine( context ).
,08-16 18:15:40.267  7043  7043 D elm:15183: MDMBridge.setEnterpriseBridge()
,08-16 18:15:40.277  1014  1491 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-16 18:15:40.277  1014  1491 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-16 18:15:40.277  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
08-16 18:15:40.277  1014  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 18:15:40.277  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-16 18:15:40.287  7043  7043 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-16 18:15:40.287  7043  7043 D elm:15183: ElmAgentService : onCreate()
,08-16 18:15:40.287  7043  7087 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
08-16 18:15:40.287  7043  7087 D elm:15183: MainReceiver.listeningToPackageRemoved()
,08-16 18:15:40.287  7043  7087 D elm:15183: MDMBridge.getInstance()
08-16 18:15:40.287  7043  7087 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,08-16 18:15:40.287  3347  3347 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
08-16 18:15:40.287  3347  3347 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-16 18:15:40.297  3347  3347 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
08-16 18:15:40.297  3347  3347 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
08-16 18:15:40.297  3347  3347 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
08-16 18:15:40.297  3347  3347 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
08-16 18:15:40.297  3347  3347 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
08-16 18:15:40.297  3347  3347 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:15:40.297  3347  3347 W System.err: 	at android.os.Looper.loop(Looper.java:145)
08-16 18:15:40.297  3347  3347 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 18:15:40.297  3347  3347 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:15:40.297  3347  3347 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 18:15:40.297  3347  3347 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 18:15:40.297  3347  3347 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-16 18:15:40.297  7075  7075 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 18:15:40.297  7075  7075 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:40.307  7043  7087 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,08-16 18:15:40.307  6475  6475 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true,
08-16 18:15:40.307  6475  6475 I PCWCLIENTTRACE_PushUtil: sales region : global
08-16 18:15:40.307  6475  6475 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-16 18:15:40.307  6475  6475 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,08-16 18:15:40.317  6847  7069 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,08-16 18:15:40.317  1014  1555 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,08-16 18:15:40.317  1014  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:40.317  1014  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:40.317  1014  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:40.317  1014  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:40.317  7058  7058 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-16 18:15:40.317  7058  7058 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 18:15:40.317  7058  7058 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-16 18:15:40.317  7058  7058 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-16 18:15:40.317  7058  7058 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,08-16 18:15:40.317  7058  7058 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-16 18:15:40.317  7058  7058 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-16 18:15:40.317  7058  7058 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-16 18:15:40.327  7092  7092 E Zygote  : MountEmulatedStorage()
08-16 18:15:40.327  7092  7092 E Zygote  : v2
08-16 18:15:40.327  7092  7092 I libpersona: KNOX_SDCARD checking this for 10032
08-16 18:15:40.327  7092  7092 I libpersona: KNOX_SDCARD not a persona
,08-16 18:15:40.337  1014  1555 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7092 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,08-16 18:15:40.337  7043  7043 D elm:15183: ElmAgentService : onDestroy().
,08-16 18:15:40.347  7075  7075 D ThemeInfoUtil: getCurrentFestivalName is [null]
08-16 18:15:40.347  7075  7075 D ThemeInfoUtil: isCurrentFestival = false
,08-16 18:15:40.347  1014  1215 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,08-16 18:15:40.347  1014  1215 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:40.357  7092  7092 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
08-16 18:15:40.357  1014  1215 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:40.357  7092  7092 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
08-16 18:15:40.357  1014  1215 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:40.357  7092  7092 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-16 18:15:40.357  1014  1215 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:40.367  6847  6847 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-16 18:15:40.367  6847  6847 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM app_history WHERE package_name=?] disk I/O error
08-16 18:15:40.367  6847  6847 D AndroidRuntime: Shutting down VM
08-16 18:15:40.367  6847  6847 E AndroidRuntime: FATAL EXCEPTION: main
08-16 18:15:40.367  6847  6847 E AndroidRuntime: Process: com.samsung.android.sm, PID: 6847
08-16 18:15:40.367  6847  6847 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.samsung.android.sm.ui.security.MonitorReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 18:15:40.367  6847  6847 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3132)
08-16 18:15:40.367  6847  6847 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
08-16 18:15:40.367  6847  6847 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
08-16 18:15:40.367  6847  6847 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:15:40.367  6847  6847 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-16 18:15:40.367  6847  6847 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 18:15:40.367  6847  6847 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:15:40.367  6847  6847 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 18:15:40.367  6847  6847 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 18:15:40.367  6847  6847 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 18:15:40.367  6847  6847 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 18:15:40.367  6847  6847 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-16 18:15:40.367  6847  6847 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
08-16 18:15:40.367  6847  6847 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-16 18:15:40.367  6847  6847 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-16 18:15:40.367  6847  6847 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1637)
08-16 18:15:40.367  6847  6847 E AndroidRuntime: 	at com.samsung.android.sm.common.security.m.b(ScanHistoryHelper.java:222)
08-16 18:15:40.367  6847  6847 E AndroidRuntime: 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:175)
08-16 18:15:40.367  6847  6847 E AndroidRuntime: 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:67)
08-16 18:15:40.367  6847  6847 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
08-16 18:15:40.367  6847  6847 E AndroidRuntime: 	... 9 more
,08-16 18:15:40.387  1014  1215 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7107 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a,
08-16 18:15:40.387  1014  1215 I ActivityManager: Killing 5475:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,08-16 18:15:40.387  7092  7092 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 18:15:40.387  7092  7092 D ActivityThread: Added TimaKeyStore provider
,08-16 18:15:40.397  7107  7107 E Zygote  : MountEmulatedStorage()
08-16 18:15:40.397  7107  7107 I libpersona: KNOX_SDCARD checking this for 10152
08-16 18:15:40.397  7107  7107 E Zygote  : v2
08-16 18:15:40.397  7107  7107 I libpersona: KNOX_SDCARD not a persona
08-16 18:15:40.397  1014  1359 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.sm
,08-16 18:15:40.417  6847  7069 I art     : Explicit concurrent mark sweep GC freed 1013(101KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 661us total 50.437ms
,08-16 18:15:40.427  7107  7107 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 18:15:40.427  7058  7058 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.gallery3d/databases/picasa.db" with flag (131138) and mode_t (0) due to error (30)
,08-16 18:15:40.427  7107  7107 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 18:15:40.427  7107  7107 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 18:15:40.437  7058  7058 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.gallery3d/databases/picasa.db'.
08-16 18:15:40.437  7058  7058 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 18:15:40.437  7058  7058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 18:15:40.437  7058  7058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-16 18:15:40.437  7058  7058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-16 18:15:40.437  7058  7058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-16 18:15:40.437  7058  7058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-16 18:15:40.437  7058  7058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-16 18:15:40.437  7058  7058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-16 18:15:40.437  7058  7058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-16 18:15:40.437  7058  7058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-16 18:15:40.437  7058  7058 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-16 18:15:40.437  7058  7058 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-16 18:15:40.437  7058  7058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 18:15:40.437  7058  7058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 18:15:40.437  7058  7058 E SQLiteDatabase: 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider$SyncContext.<init>(PicasaContentProvider.java:911)
08-16 18:15:40.437  7058  7058 E SQLiteDatabase: 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider.attachInfo(PicasaContentProvider.java:103)
08-16 18:15:40.437  7058  7058 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
08-16 18:15:40.437  7058  7058 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
08-16 18:15:40.437  7058  7058 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
08-16 18:15:40.437  7058  7058 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 18:15:40.437  7058  7058 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 18:15:40.437  7058  7058 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:15:40.437  7058  7058 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-16 18:15:40.437  7058  7058 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 18:15:40.437  7058  7058 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:15:40.437  7058  7058 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 18:15:40.437  7058  7058 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 18:15:40.437  7058  7058 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-16 18:15:40.447  1014  7114 E DropBoxManagerService: Can't write: system_app_crash
08-16 18:15:40.447  1014  7114 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop197.tmp: open failed: EROFS (Read-only file system)
08-16 18:15:40.447  1014  7114 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-16 18:15:40.447  1014  7114 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 18:15:40.447  1014  7114 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 18:15:40.447  1014  7114 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 18:15:40.447  1014  7114 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-16 18:15:40.447  1014  7114 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15777)
08-16 18:15:40.447  1014  7114 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 18:15:40.447  1014  7114 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 18:15:40.447  1014  7114 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 18:15:40.447  1014  7114 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-16 18:15:40.447  1014  7114 E DropBoxManagerService: 	... 5 more
08-16 18:15:40.447  5905  5935 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-16 18:15:40.447  5905  5935 E SQLiteLog: (3850) statement aborts at 28: [UPDATE apps SET badgecount=? WHERE package=? AND class=?] disk I/O error
08-16 18:15:40.447  5905  5935 E DatabaseUtils: Writing exception to parcel
08-16 18:15:40.447  5905  5935 E DatabaseUtils: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 18:15:40.447  5905  5935 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-16 18:15:40.447  5905  5935 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
08-16 18:15:40.447  5905  5935 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-16 18:15:40.447  5905  5935 E DatabaseUtils: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-16 18:15:40.447  5905  5935 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1714)
08-16 18:15:40.447  5905  5935 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1660)
08-16 18:15:40.447  5905  5935 E DatabaseUtils: 	at com.sec.android.provider.badge.BadgeProvider.update(BadgeProvider.java:170)
08-16 18:15:40.447  5905  5935 E DatabaseUtils: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:340)
08-16 18:15:40.447  5905  5935 E DatabaseUtils: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:222)
08-16 18:15:40.447  5905  5935 E DatabaseUtils: 	at android.os.Binder.execTransact(Binder.java:446)
08-16 18:15:40.447  1014  1040 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,08-16 18:15:40.447  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:40.447  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:40.447  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 18:15:40.447  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 18:15:40.467  7125  7125 E Zygote  : MountEmulatedStorage()
08-16 18:15:40.467  7125  7125 E Zygote  : v2
08-16 18:15:40.467  7125  7125 I libpersona: KNOX_SDCARD checking this for 1000
08-16 18:15:40.467  7125  7125 I libpersona: KNOX_SDCARD not a persona
08-16 18:15:40.467  7125  7125 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 18:15:40.467  1014  1040 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7125 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,08-16 18:15:40.467  7125  7125 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-16 18:15:40.467  7125  7125 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 18:15:40.477  1014  1557 D PersonaManager: isKioskContainerExistOnDevice
,08-16 18:15:40.477  7107  7107 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 18:15:40.477  1014  1557 I ActivityManager: Killing 6104:com.google.android.gms:car/u0a12 (adj 15): empty #31
08-16 18:15:40.477  7107  7107 D ActivityThread: Added TimaKeyStore provider

```
