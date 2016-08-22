#### Test 79763830f325397_thali03_samsung-SM-A500FU Logs


```
--------- beginning of main,
08-22 12:03:13.073   288   288 E SMD     : DCD OFF
08-22 12:03:13.353  5467  5467 D AndroidRuntime: 
08-22 12:03:13.353  5467  5467 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-22 12:03:13.353  5467  5467 D AndroidRuntime: CheckJNI is OFF
08-22 12:03:13.353  5467  5467 D AndroidRuntime: readGMSProperty: start
08-22 12:03:13.353  5467  5467 D AndroidRuntime: readGMSProperty: already setted!!
08-22 12:03:13.353  5467  5467 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-22 12:03:13.353  5467  5467 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-22 12:03:13.353  5467  5467 D AndroidRuntime: readGMSProperty: end
08-22 12:03:13.353  5467  5467 D AndroidRuntime: addProductProperty: start
08-22 12:03:13.503  5467  5467 E AffinityControl: AffinityControl: registerfunction enter
08-22 12:03:13.533  5467  5467 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-22 12:03:13.543  1014  3001 E PersonaManagerService: inState():  stateMachine is null !!
08-22 12:03:13.543  1014  3001 I PersonaManagerService: PersonaId don't exist
08-22 12:03:13.543  1014  3001 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-22 12:03:13.543  1014  3001 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
08-22 12:03:13.553  1014  3001 W ActivityManager: mDVFSHelper.acquire()
08-22 12:03:13.563  1014  3001 D FocusedStackFrame: Set to : 0
08-22 12:03:13.563  1014  1044 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-22 12:03:13.563  1014  1044 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-22 12:03:13.573  1014  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:13.573  1014  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:13.573  1014  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:13.573  1014  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:13.583  5478  5478 E Zygote  : MountEmulatedStorage()
08-22 12:03:13.583  1014  3001 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5478 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-22 12:03:13.583  5478  5478 E Zygote  : v2
08-22 12:03:13.583  5478  5478 I libpersona: KNOX_SDCARD checking this for 10155
08-22 12:03:13.583  1014  3001 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-22 12:03:13.583  5478  5478 I libpersona: KNOX_SDCARD not a persona
08-22 12:03:13.583  1014  3001 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-22 12:03:13.583  1014  3001 D InputDispatcher: Focused application set to: xxxx
08-22 12:03:13.583  1014  3001 D InputDispatcher: Focus left window: 1467
08-22 12:03:13.583  5467  5467 D AndroidRuntime: Shutting down VM
08-22 12:03:13.583  1014  1044 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-22 12:03:13.583  1014  1044 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-22 12:03:13.583  5478  5478 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-22 12:03:13.583   258   258 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, uhalitest
08-22 12:03:13.593  5478  5478 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-22 12:03:13.593  5478  5478 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-22 12:03:13.613  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-22 12:03:13.613  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
08-22 12:03:13.613  5478  5478 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 12:03:13.613  5478  5478 D ActivityThread: Added TimaKeyStore provider
08-22 12:03:13.613  1014  1533 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-22 12:03:13.613  1014  1014 V ActivityManager: Display changed displayId=0
08-22 12:03:13.623  1014  1042 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-22 12:03:13.633  1014  1533 D PersonaManager: isKioskContainerExistOnDevice
08-22 12:03:13.643  1014  1014 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-22 12:03:13.693   258   442 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
08-22 12:03:13.693  1467  1467 V ActivityThread: updateVisibility : ActivityRecord{38a188da token=android.os.BinderProxy@7fc16dc {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-22 12:03:13.693   258  1095 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
08-22 12:03:13.693  1467  1467 D Launcher: onTrimMemory. Level: 20
08-22 12:03:13.753  5478  5478 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
08-22 12:03:13.763  5478  5478 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 8734-8735)
08-22 12:03:13.763  5478  5478 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-22 12:03:13.783  5478  5478 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {170ceb79}
08-22 12:03:13.783  5478  5478 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-22 12:03:13.783  5478  5478 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
08-22 12:03:13.793  5467  5467 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-22 12:03:13.823  5478  5478 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-22 12:03:13.823  5478  5478 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-22 12:03:13.823  5478  5478 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-22 12:03:13.833  5478  5495 W chromium: [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,08-22 12:03:13.843  5478  5478 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,08-22 12:03:13.843  5478  5478 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,08-22 12:03:13.843  5478  5478 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,08-22 12:03:13.853  5478  5478 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-22 12:03:13.853  5478  5478 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-22 12:03:13.853  5478  5478 I Adreno-EGL: Build Date: 04/06/15 Mon
08-22 12:03:13.853  5478  5478 I Adreno-EGL: Local Branch: 
08-22 12:03:13.853  5478  5478 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-22 12:03:13.853  5478  5478 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-22 12:03:13.853  5478  5478 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-22 12:03:13.913  5478  5506 D BluetoothAdapter: 403815114: getState() :  mService = null. Returning STATE_OFF
,08-22 12:03:13.963  5478  5504 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,08-22 12:03:14.003  5478  5478 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-22 12:03:14.023  5478  5478 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-22 12:03:14.033  5478  5478 D PhoneWindow: *FMB* installDecor mIsFloating : false
,08-22 12:03:14.033  5478  5478 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-22 12:03:14.033  5478  5478 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-22 12:03:14.043  5478  5478 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-22 12:03:14.043  5478  5478 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-22 12:03:14.083  5478  5517 D OpenGLRenderer: Render dirty regions requested: true
,08-22 12:03:14.093  1014  1488 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-22 12:03:14.093  1014  1488 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-22 12:03:14.093  1014  1488 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-22 12:03:14.093  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-22 12:03:14.093  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
,08-22 12:03:14.103  5478  5478 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,08-22 12:03:14.103  5478  5478 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-22 12:03:14.113   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, NainActivit
,08-22 12:03:14.123  1014  3002 D InputDispatcher: Focus entered window: 5478
,08-22 12:03:14.123  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-22 12:03:14.123  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-22 12:03:14.123  5478  5478 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-22 12:03:14.123  5478  5517 I OpenGLRenderer: Initialized EGL, version 1.4
08-22 12:03:14.133  5478  5517 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-22 12:03:14.133  5478  5517 D OpenGLRenderer: Enabling debug mode 0
,08-22 12:03:14.173  5478  5478 V ActivityThread: updateVisibility : ActivityRecord{20010821 token=android.os.BinderProxy@10b8b22b {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-22 12:03:14.193  1014  1251 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-22 12:03:14.193  1014  5520 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-22 12:03:14.193  1176  1176 D PanelView: There is/are notification(s) 
,08-22 12:03:14.203  1014  1044 I ActivityManager: Displayed Component not be shown by security: +564ms (total +638ms)
,08-22 12:03:14.203  1014  1044 W ActivityManager: mDVFSHelper.release()
08-22 12:03:14.203  1014  1044 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{212f219a u0 com.test.thalitest/.MainActivity t127} time:99179
,08-22 12:03:14.213  1794  1794 I SamsungIME: getCurrentCandidateView
,08-22 12:03:14.223   258  1095 I SurfaceFlinger: id=11 Removed uhalitest (7/9)
,08-22 12:03:14.223   258   455 I SurfaceFlinger: id=11 Removed uhalitest (-2/9)
,08-22 12:03:14.233  5478  5478 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-22 12:03:14.233  5478  5478 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@10b8b22b time:99202
,08-22 12:03:14.273  5478  5478 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5478,
,08-22 12:03:14.303  1794  1794 D SamsungIME: Dismiss ExpandCandiate
,08-22 12:03:14.393  5478  5478 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-22 12:03:14.433  1794  1794 I SamsungIME: getDebugLevel  : 0x4f4c
,08-22 12:03:14.473  1794  1794 I SamsungIME: getDebugLevel  : 0x4f4c
,08-22 12:03:14.483  1794  1794 I SamsungIME: KeybaordView init() : load resources
,08-22 12:03:14.493  5478  5522 D jxcore_app_log: JniHelper::setJavaVM(0xb720c328), pthread_self() = -1216924848
,08-22 12:03:14.513  1794  1794 I SamsungIME: getCurrentKeyboard
08-22 12:03:14.513  1794  1794 I SamsungIME: getTextKeyboard
,08-22 12:03:14.513  5478  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-22 12:03:14.513  5478  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-22 12:03:14.513  5478  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-22 12:03:14.513  5478  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-22 12:03:14.513  5478  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-22 12:03:14.513  5478  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@396b3b91 added. We now have 1 listener(s)
,08-22 12:03:14.523  5478  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,08-22 12:03:14.523  5478  5522 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-22 12:03:14.523  1794  1794 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-22 12:03:14.523  5478  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-22 12:03:14.523  5478  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-22 12:03:14.533  5478  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-22 12:03:14.533  5478  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-22 12:03:14.533  5478  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-22 12:03:14.533  5478  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
08-22 12:03:14.533  5478  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-22 12:03:14.533  5478  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-22 12:03:14.533  5478  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-22 12:03:14.533  5478  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-22 12:03:14.533  5478  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-22 12:03:14.533  5478  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-22 12:03:14.533  5478  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-22 12:03:14.533  5478  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-22 12:03:14.533  5478  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-22 12:03:14.533  5478  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-22 12:03:14.533  5478  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1560c164 added. We now have 1 listener(s)
,08-22 12:03:14.533  5478  5522 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 12:03:14.533  5478  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-22 12:03:14.533  5478  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-22 12:03:14.533  5478  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-22 12:03:14.533  5478  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-22 12:03:14.533  5478  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-22 12:03:14.543  5478  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 12:03:14.543  5478  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,08-22 12:03:14.543  5478  5522 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 12:03:14.543  5478  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 12:03:14.543  5478  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 12:03:14.543  5478  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-22 12:03:14.543  5478  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 12:03:14.543  5478  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 12:03:14.543  5478  5522 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 12:03:14.543  5478  5522 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 12:03:14.543  5478  5522 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 12:03:14.543  5478  5522 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-22 12:03:14.543  5478  5522 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 12:03:14.543  5478  5522 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-22 12:03:14.583  5478  5478 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-22 12:03:15.033  1794  5526 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-22 12:03:15.103  5478  5530 W jxcore-log: Initializing JXcore engine
08-22 12:03:15.103  5478  5530 W jxcore-log: JXcore engine is ready
,08-22 12:03:15.163  1915  1915 E audit   : type=1400 msg=audit(1471860195.153:203): avc:  denied  { ioctl } for  pid=5530 comm="Thread-943" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-22 12:03:15.163  1915  1915 E audit   :  SEPF_SM-A500FU_5.0.2-1_0051
08-22 12:03:15.163  1915  1915 E audit   : type=1300 msg=audit(1471860195.153:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9ea028f8 items=0 ppid=308 ppcomm=main pid=5530 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-943" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-22 12:03:15.163  1915  1915 E audit   : type=1320 msg=audit(1471860195.153:203): 
,08-22 12:03:15.173  5478  5530 W jxcore-log: Starting JXcore engine
,08-22 12:03:15.273  5478  5530 W jxcore-log: Platform android
08-22 12:03:15.273  5478  5530 W jxcore-log: 
08-22 12:03:15.273  5478  5530 W jxcore-log: Process ARCH arm
08-22 12:03:15.273  5478  5530 W jxcore-log: 
,08-22 12:03:15.473  5478  5530 I jxcore-log: JXcore Cordova bridge is ready!
08-22 12:03:15.473  5478  5530 I jxcore-log: 
,08-22 12:03:15.473  5478  5530 W jxcore-log: JXcore engine is started
,08-22 12:03:15.483  5478  5522 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-22 12:03:15.483  5478  5478 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-22 12:03:16.073   288   288 E SMD     : DCD OFF,
,08-22 12:03:16.963  1014  1026 I art     : Explicit concurrent mark sweep GC freed 34714(2MB) AllocSpace objects, 14(224KB) LOS objects, 33% free, 27MB/41MB, paused 2.445ms total 144.150ms
,08-22 12:03:18.173  1014  1046 I PowerManagerService: [PWL] Off : 50s ago,
,08-22 12:03:18.243  1014  2625 D SSRM:n  : SIOP:: AP = 340,
,08-22 12:03:19.073   288   288 E SMD     : DCD OFF
,08-22 12:03:21.023  1014  1488 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-22 12:03:21.023  1014  1488 D BatteryService: level:97, scale:100, status:2, health:2, present:true, voltage: 4211, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,08-22 12:03:21.023  1014  1488 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-22 12:03:21.023  1014  1488 D BatteryService: stay LED for charging
,08-22 12:03:21.023  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-22 12:03:21.023  1014  1014 I MotionRecognitionService: Plugged
,08-22 12:03:21.023  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,08-22 12:03:21.033  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-22 12:03:21.033  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-22 12:03:21.033  1405  1405 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-22 12:03:21.033  1405  1405 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 97
,08-22 12:03:21.053  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:97 status:2 health:2
,08-22 12:03:21.063  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:97 status:2 health:2
08-22 12:03:21.063  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:97 status:2 health:2
,08-22 12:03:21.543  4665  4665 D FactoryTest: Not factory mode
,08-22 12:03:21.553  4665  4665 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-22 12:03:21.553  4665  4665 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-22 12:03:21.553  4665  4665 D MTPRx   : still no open session command from host, so toast
,08-22 12:03:21.553  4665  4665 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
08-22 12:03:21.553  4665  4665 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:106522,
,08-22 12:03:21.553  4665  4665 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-22 12:03:21.553  1014  3003 E PersonaManagerService: inState():  stateMachine is null !!
08-22 12:03:21.553  1014  3003 I PersonaManagerService: PersonaId don't exist
08-22 12:03:21.553  1014  3003 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-22 12:03:21.553  1014  3003 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
,08-22 12:03:21.553  1014  3003 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:21.553  1014  3003 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 12:03:21.553  1014  3003 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-22 12:03:21.563  1014  3003 W ActivityManager: mDVFSHelper.acquire(),
,08-22 12:03:21.573  1014  3003 D PersonaManager: isKioskContainerExistOnDevice
,08-22 12:03:21.583  1014  3003 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-22 12:03:21.583  1014  3003 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-22 12:03:21.583  1014  3003 D InputDispatcher: Focused application set to: xxxx
,08-22 12:03:21.583  1014  3003 D InputDispatcher: Focus left window: 5478
,08-22 12:03:21.583  4665  4665 E MTPRx   : started activity for popup
,08-22 12:03:21.583  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-22 12:03:21.583  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-22 12:03:21.623  4665  4665 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-22 12:03:21.623  4665  4665 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,08-22 12:03:21.623  4665  4665 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-22 12:03:21.623  4665  4665 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-22 12:03:21.623  4665  4665 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-22 12:03:21.623  4665  4665 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-22 12:03:21.643  4665  4665 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-22 12:03:21.643  1014  1026 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-22 12:03:21.643  1014  1026 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-22 12:03:21.643  1014  1026 D InputDispatcher: Focused application set to: xxxx
,08-22 12:03:21.643  1014  1026 D InputDispatcher: Focus entered window: 5478
,08-22 12:03:21.643  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-22 12:03:21.643  1014  1531 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-22 12:03:21.653  1014  1531 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@2774795 attribute=null, token = android.os.BinderProxy@e644b25
,08-22 12:03:21.653  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-22 12:03:21.683  4665  4665 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-22 12:03:21.693  4665  4665 D PhoneWindow: *FMB* installDecor mIsFloating : true,
08-22 12:03:21.693  4665  4665 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-22 12:03:21.713  5478  5478 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-22 12:03:21.713  5478  5478 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-22 12:03:21.713  5478  5478 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-22 12:03:21.713  5478  5478 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-22 12:03:21.713  1014  1533 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-22 12:03:21.713  1014  1533 D KnoxTimeoutHandler: postActiveUserChange for user 0
,08-22 12:03:21.713  1014  1533 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-22 12:03:21.713  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
08-22 12:03:21.713  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0,
,08-22 12:03:21.723  5478  5478 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-22 12:03:21.723  5478  5478 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-22 12:03:21.733  5478  5478 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1e55656e Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@1b6f4b58, 16908290=android.view.AbsSavedState$1@1b6f4b58}, android:focusedViewId=100}]}]
08-22 12:03:21.733  5478  5478 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-22 12:03:21.733  5478  5478 V ActivityThread: updateVisibility : ActivityRecord{20010821 token=android.os.BinderProxy@10b8b22b {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-22 12:03:21.733  5478  5478 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-22 12:03:21.733  5478  5478 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-22 12:03:21.733  5478  5478 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@10b8b22b time:106703
,08-22 12:03:21.733  1014  1466 D PersonaManager: isKioskContainerExistOnDevice
,08-22 12:03:22.073   288   288 E SMD     : DCD OFF
,08-22 12:03:23.423  1014  1332 E Watchdog: !@Sync 3,
,08-22 12:03:23.623  1014  1053 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS,
,08-22 12:03:24.563  1014  1039 W ActivityManager: mDVFSHelper.release(),
,08-22 12:03:24.763   330   330 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-22 12:03:24.763   330   330 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-22 12:03:25.083   288   288 E SMD     : DCD OFF,
,08-22 12:03:27.823  5478  5530 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
08-22 12:03:27.823  5478  5530 I jxcore-log: 
,08-22 12:03:27.823  5478  5530 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-22 12:03:27.823  5478  5530 I jxcore-log: 
,08-22 12:03:27.833  5478  5530 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-22 12:03:27.833  5478  5530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 12:03:27.833  5478  5530 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 12:03:27.833  5478  5530 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED,
08-22 12:03:27.833  5478  5530 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 12:03:27.833  5478  5530 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 12:03:27.833  5478  5530 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 12:03:27.833  5478  5530 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 12:03:27.833  5478  5530 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 12:03:27.833  5478  5530 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 12:03:27.833  5478  5530 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 12:03:27.833  5478  5530 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-22 12:03:27.833  5478  5530 I jxcore-log: 
,08-22 12:03:27.833  5478  5530 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
08-22 12:03:27.833  5478  5530 I jxcore-log: 
,08-22 12:03:28.083   288   288 E SMD     : DCD OFF,
,08-22 12:03:28.253  1014  2625 D SSRM:n  : SIOP:: AP = 340
,08-22 12:03:28.473  5478  5530 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests,
08-22 12:03:28.473  5478  5530 I jxcore-log: Failed to execute UT.
08-22 12:03:28.473  5478  5530 I jxcore-log: 
08-22 12:03:28.473  5478  5530 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-22 12:03:28.473  5478  5530 I jxcore-log: 
,08-22 12:03:28.483  5478  5530 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 12:03:28.483  5478  5530 I jxcore-log: 
08-22 12:03:28.483  5478  5478 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-22 12:03:28.783  5539  5539 D AndroidRuntime: 
08-22 12:03:28.783  5539  5539 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-22 12:03:28.783  5539  5539 D AndroidRuntime: CheckJNI is OFF,
,08-22 12:03:28.783  5539  5539 D AndroidRuntime: readGMSProperty: start,
08-22 12:03:28.783  5539  5539 D AndroidRuntime: readGMSProperty: already setted!!
08-22 12:03:28.783  5539  5539 D AndroidRuntime: propertySet: couldn't set property (it is from app)
,08-22 12:03:28.783  5539  5539 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-22 12:03:28.783  5539  5539 D AndroidRuntime: readGMSProperty: end
08-22 12:03:28.783  5539  5539 D AndroidRuntime: addProductProperty: start
,08-22 12:03:28.943  5539  5539 E AffinityControl: AffinityControl: registerfunction enter,
,08-22 12:03:28.963  5539  5539 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,08-22 12:03:28.973  1014  3003 D PackageManager: START PACKAGE DELETE: observer{237114523},
08-22 12:03:28.973  1014  3003 D PackageManager: pkg{<packageName>}
08-22 12:03:28.973  1014  3003 D PackageManager: user{0}
08-22 12:03:28.973  1014  3003 D PackageManager: caller{2000}
08-22 12:03:28.973  1014  3003 D PackageManager: flags{2}
08-22 12:03:28.973  1014  3003 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-22 12:03:28.973  1014  3003 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-22 12:03:28.973  1014  3003 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true,
08-22 12:03:28.973  1014  3003 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-22 12:03:28.973  1014  3003 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-22 12:03:28.983  1014  1053 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-22 12:03:28.983  1014  1053 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-22 12:03:28.983  1014  1053 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,08-22 12:03:28.983  1014  1053 D ApplicationPolicy: getApplicationUninstallationEnabled
08-22 12:03:28.983  1014  1053 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-22 12:03:28.983  1014  1053 D PackageManager: !@killApplicatoin: 10155, uninstall pkg
08-22 12:03:28.983  1014  1039 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
,08-22 12:03:28.983  1014  1039 I ActivityManager: Killing 5478:com.test.thalitest/u0a155 (adj 0): stop com.test.thalitest cause uninstall pkg
08-22 12:03:28.983  1014  1039 I ActivityManager:   Force finishing activity ActivityRecord{212f219a u0 com.test.thalitest/.MainActivity t127}
,08-22 12:03:28.983  1014  1039 D InputDispatcher: Focus left window: 5478
,08-22 12:03:28.993   258  1095 I SurfaceFlinger: id=12 Removed NainActivit (6/8)
08-22 12:03:28.993   258   455 I SurfaceFlinger: id=12 Removed NainActivit (-2/8)
,08-22 12:03:28.993  1014  1039 D InputDispatcher: Focused application released
08-22 12:03:28.993  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-22 12:03:28.993  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-22 12:03:29.093  1014  1053 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,08-22 12:03:29.123  1014  1053 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-22 12:03:29.143  3666  3666 I art     : Explicit concurrent mark sweep GC freed 2521(155KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 6MB/11MB, paused 721us total 26.414ms
,08-22 12:03:29.153  4803  4803 I art     : Explicit concurrent mark sweep GC freed 403(27KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 8MB/11MB, paused 818us total 39.222ms
,08-22 12:03:29.163  1014  1097 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-22 12:03:29.173  4148  4148 I art     : Explicit concurrent mark sweep GC freed 13121(721KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/9MB, paused 668us total 29.819ms
,08-22 12:03:29.173  1794  1794 E SamsungIME: mOCRHelper is null
,08-22 12:03:29.173  3743  3743 I art     : Explicit concurrent mark sweep GC freed 2183(89KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 14MB/19MB, paused 1.157ms total 77.309ms
,08-22 12:03:29.183  1937  2092 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-22 12:03:29.203  1433  1433 D PersonaManager: isKioskContainerExistOnDevice
,08-22 12:03:29.203  3526  3526 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Aug 22 12:03:29 GMT+02:00 2016
,08-22 12:03:29.203  1014  1122 V NetworkStats: removeUidsLocked() for UIDs [10155]
08-22 12:03:29.203  1014  1122 V NetworkStats: performPollLocked(flags=0x3)
,08-22 12:03:29.213  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 12:03:29.213  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-22 12:03:29.213  1014  1122 V NetworkStats: performPollLocked() took 7ms
08-22 12:03:29.213  1014  3001 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-22 12:03:29.213  1014  3001 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
08-22 12:03:29.213  1014  3001 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:29.213  1014  3001 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 12:03:29.213  1014  3001 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
08-22 12:03:29.223  1433  1433 D RegisteredServicesCache: empty dynamic service
,08-22 12:03:29.223  3526  3526 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,08-22 12:03:29.223  1014  1026 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
,08-22 12:03:29.233  1014  1026 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-22 12:03:29.233  1014  1026 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-22 12:03:29.233  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:29.233  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:29.233  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:29.233  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:29.243  5552  5552 E Zygote  : MountEmulatedStorage()
08-22 12:03:29.243  5552  5552 E Zygote  : v2
08-22 12:03:29.243  5552  5552 I libpersona: KNOX_SDCARD checking this for 10094
08-22 12:03:29.243  5552  5552 I libpersona: KNOX_SDCARD not a persona
,08-22 12:03:29.243  5552  5552 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-22 12:03:29.253  1014  1026 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5552 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,08-22 12:03:29.253  1433  1433 D RegisteredComponentCache: Collect Tech packages for Knox
08-22 12:03:29.253  1433  1433 D PersonaManager: isKioskContainerExistOnDevice
08-22 12:03:29.253  5552  5552 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-22 12:03:29.253  5552  5552 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 12:03:29.263  3526  3526 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,08-22 12:03:29.283  3526  3526 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-22 12:03:29.293  3526  3526 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-22 12:03:29.293  5552  5552 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 12:03:29.293  5552  5552 D ActivityThread: Added TimaKeyStore provider
,08-22 12:03:29.303  1014  3010 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-22 12:03:29.303  1014  3010 D SecContentProvider2: mCursor = null
,08-22 12:03:29.303  3526  5551 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-22 12:03:29.303  1014  1123 D NtpTrustedTime: forceRefresh() from cache miss
,08-22 12:03:29.303  3526  5551 I KLMS-2.5.183: : KLMSIntentService(): PACKAGE_REMOVED
,08-22 12:03:29.303   278  1008 D EnterpriseController: uids 1000
08-22 12:03:29.303   278  1008 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-22 12:03:29.303   278  1008 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,08-22 12:03:29.313  3526  5551 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().START
,08-22 12:03:29.313  4409  4409 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
,08-22 12:03:29.313   278  1008 D EnterpriseController: uids 1000
08-22 12:03:29.313   278  1008 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-22 12:03:29.313   278  1008 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,08-22 12:03:29.313  1014  1123 D NtpTrustedTime: forceRefresh Fail.
,08-22 12:03:29.323  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,08-22 12:03:29.323  3526  5551 I KLMS-2.5.183: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
08-22 12:03:29.323  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:29.323  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:29.323  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:29.323  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:29.333  5569  5569 E Zygote  : MountEmulatedStorage()
08-22 12:03:29.333  5569  5569 E Zygote  : v2
08-22 12:03:29.333  5569  5569 I libpersona: KNOX_SDCARD checking this for 10149
08-22 12:03:29.333  5569  5569 I libpersona: KNOX_SDCARD not a persona
08-22 12:03:29.333  5569  5569 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-22 12:03:29.343  5569  5569 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-22 12:03:29.343  5569  5569 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 12:03:29.343  1014  1039 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=5569 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-22 12:03:29.343  1014  1014 I art     : Explicit concurrent mark sweep GC freed 30940(2MB) AllocSpace objects, 15(240KB) LOS objects, 33% free, 27MB/41MB, paused 5.427ms total 218.162ms
,08-22 12:03:29.343  1014  1053 I art     : WaitForGcToComplete blocked for 149.459ms for cause Explicit
,08-22 12:03:29.363  5073  5073 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
,08-22 12:03:29.363  1014  3002 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
08-22 12:03:29.363  1014  3002 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
,08-22 12:03:29.373  1014  3002 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:29.373  1014  3002 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 12:03:29.373  1014  3002 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,08-22 12:03:29.373  5569  5569 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 12:03:29.383  5569  5569 D ActivityThread: Added TimaKeyStore provider
,08-22 12:03:29.393  5073  5585 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
,08-22 12:03:29.393  1014  1298 I TactileAssist: enable value -1
08-22 12:03:29.393  1014  1298 I TactileAssist: internal enable value -1
08-22 12:03:29.393  1014  1298 I TactileAssist: intensity value -1
08-22 12:03:29.393  1014  1298 I TactileAssist: saveAppList value true
,08-22 12:03:29.403  5073  5585 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
,08-22 12:03:29.403  1014  1298 I TactileAssist: List of disabled apps :
,08-22 12:03:29.403  5552  5552 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-22 12:03:29.413  5552  5552 D elm:15183: ELMEngine.ELMEngine( context ).
,08-22 12:03:29.413  4148  4148 I art     : Explicit concurrent mark sweep GC freed 922(41KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 985us total 49.756ms
,08-22 12:03:29.413  5552  5552 D elm:15183: MDMBridge.setEnterpriseBridge()
,08-22 12:03:29.423  1014  3002 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,08-22 12:03:29.423  1014  3002 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-22 12:03:29.423  1014  3002 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:29.423  4148  5572 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,08-22 12:03:29.423  1014  3002 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 12:03:29.423  1014  3002 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-22 12:03:29.423  5552  5552 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-22 12:03:29.433  3079  3079 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,08-22 12:03:29.443  3079  3079 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-22 12:03:29.443  5552  5552 D elm:15183: ElmAgentService : onCreate()
,08-22 12:03:29.443  5552  5586 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
08-22 12:03:29.443  5552  5586 D elm:15183: MainReceiver.listeningToPackageRemoved()
08-22 12:03:29.443  5552  5586 D elm:15183: MDMBridge.getInstance()
08-22 12:03:29.443  5552  5586 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,08-22 12:03:29.443  5552  5586 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,08-22 12:03:29.443  5311  5311 D Compatibility: onReceive() it will make start service
08-22 12:03:29.443  3079  3079 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
08-22 12:03:29.443  3079  3079 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
08-22 12:03:29.443  3079  3079 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
08-22 12:03:29.443  3079  3079 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
08-22 12:03:29.443  3079  3079 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
08-22 12:03:29.443  3079  3079 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 12:03:29.443  3079  3079 W System.err: 	at android.os.Looper.loop(Looper.java:145)
08-22 12:03:29.443  3079  3079 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 12:03:29.443  3079  3079 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 12:03:29.443  3079  3079 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 12:03:29.443  3079  3079 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 12:03:29.443  3079  3079 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-22 12:03:29.453  3526  5551 I KLMS-2.5.183: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-22 12:03:29.453  5569  5569 D ThemeInfoUtil: getCurrentFestivalName is [null]
08-22 12:03:29.453  5569  5569 D ThemeInfoUtil: isCurrentFestival = false
,08-22 12:03:29.463  3526  5551 I KLMS-2.5.183: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
08-22 12:03:29.463  1014  3003 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
08-22 12:03:29.463  1014  3003 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,08-22 12:03:29.463  1014  3003 W ActivityManager: userId = 0, bbcId = -10000
,08-22 12:03:29.463  1014  3003 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 12:03:29.463  1014  3003 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,08-22 12:03:29.473  3526  5551 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().END
,08-22 12:03:29.483  1014  1297 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
08-22 12:03:29.483  1014  1297 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,08-22 12:03:29.483  1014  1297 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:29.483  1014  1297 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 12:03:29.483  1014  1297 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,08-22 12:03:29.483  3526  3526 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,08-22 12:03:29.493  5552  5552 D elm:15183: ElmAgentService : onDestroy().
,08-22 12:03:29.493  5311  5588 D Compatibility: onHandleIntent()
,08-22 12:03:29.503  1014  1038 D EnterpriseDeviceManagerService: Package has changed for user 0
08-22 12:03:29.503  1014  1038 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-22 12:03:29.503  4458  4458 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
08-22 12:03:29.503  5311  5588 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10155, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,08-22 12:03:29.503  5255  5264 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
,08-22 12:03:29.503  5255  5264 D BadgeProvider: sendNotify, [notify] : null
08-22 12:03:29.503  5255  5264 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
08-22 12:03:29.503  5255  5264 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-22 12:03:29.503  1014  1038 W TextServicesManagerService: no available spell checker services found
08-22 12:03:29.503  5255  5264 D BadgeProvider: update, [UpdateCount] : 1
,08-22 12:03:29.513  1014  1026 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-22 12:03:29.513  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-22 12:03:29.513  5311  5588 D Compatibility: found: 2
08-22 12:03:29.513  5311  5588 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
08-22 12:03:29.513  5311  5588 D Compatibility: skipping ResolveInfo{2a28806c com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
08-22 12:03:29.513  5311  5588 D Compatibility: considering ResolveInfo{9e7c635 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
08-22 12:03:29.513  5311  5588 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,08-22 12:03:29.513  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:29.513  5311  5588 D Compatibility: enabling receiver ResolveInfo{1811baca com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
08-22 12:03:29.513  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 12:03:29.513  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-22 12:03:29.513  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 12:03:29.523  1014  3002 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
,08-22 12:03:29.523  1014  3002 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,08-22 12:03:29.523  1014  3002 W ActivityManager: userId = 0, bbcId = -10000
,08-22 12:03:29.523  1014  3002 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 12:03:29.523  1014  3002 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,08-22 12:03:29.533  5311  5588 D Compatibility: enabling receiver ResolveInfo{28b2443b com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,08-22 12:03:29.533  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 12:03:29.543  5311  5588 D Compatibility: enabling receiver ResolveInfo{25533758 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,08-22 12:03:29.543  5155  5155 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
08-22 12:03:29.543  5155  5155 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
08-22 12:03:29.543  5155  5155 I TapandpayWidget:Utils: Clear T&P info.
,08-22 12:03:29.543  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 12:03:29.543  5155  5155 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
,08-22 12:03:29.543  5311  5588 D Compatibility: enabling receiver ResolveInfo{255b90b1 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,08-22 12:03:29.553  4803  5590 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-22 12:03:29.553  5311  5588 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,08-22 12:03:29.563  1014  3010 D ActivityManager: startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
08-22 12:03:29.563  1014  3010 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:29.563  1014  3010 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:29.563  1014  3010 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:29.563  1014  3010 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:29.563  4883  4883 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,08-22 12:03:29.573  1014  1297 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
,08-22 12:03:29.573  1014  1297 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,08-22 12:03:29.583  5592  5592 E Zygote  : MountEmulatedStorage(),
08-22 12:03:29.583  5592  5592 E Zygote  : v2
08-22 12:03:29.583  5592  5592 I libpersona: KNOX_SDCARD checking this for 10160
,08-22 12:03:29.583  5592  5592 I libpersona: KNOX_SDCARD not a persona
,08-22 12:03:29.583  5592  5592 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-22 12:03:29.583  5592  5592 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-22 12:03:29.593  5592  5592 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 12:03:29.603  1014  3010 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=5592 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
08-22 12:03:29.603  1014  1466 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
08-22 12:03:29.603  1014  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:29.603  1014  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:29.603  1014  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:29.603  1014  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:29.603  1014  1053 I art     : Explicit concurrent mark sweep GC freed 11307(617KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 4.312ms total 256.311ms
,08-22 12:03:29.613  5604  5604 E Zygote  : MountEmulatedStorage()
08-22 12:03:29.613  5604  5604 E Zygote  : v2
08-22 12:03:29.613  5604  5604 I libpersona: KNOX_SDCARD checking this for 10003
08-22 12:03:29.613  5604  5604 I libpersona: KNOX_SDCARD not a persona
08-22 12:03:29.613  5604  5604 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-22 12:03:29.623  5604  5604 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-22 12:03:29.623  5604  5604 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-22 12:03:29.623  1014  1466 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=5604 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,08-22 12:03:29.643  5592  5592 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 12:03:29.643  5592  5592 D ActivityThread: Added TimaKeyStore provider
,08-22 12:03:29.643   308   308 I art     : Explicit concurrent mark sweep GC freed 8726(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 716us total 26.624ms
,08-22 12:03:29.643  5604  5604 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 12:03:29.653  5604  5604 D ActivityThread: Added TimaKeyStore provider
,08-22 12:03:29.673   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.164ms total 19.948ms
,08-22 12:03:29.673  5592  5592 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-22 12:03:29.673  1014  3001 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
,08-22 12:03:29.673  1014  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:29.673  1014  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:29.673  1014  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:29.673  1014  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:29.693   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 617us total 18.488ms
,08-22 12:03:29.703  1014  1038 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-22 12:03:29.703  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,08-22 12:03:29.703  5622  5622 E Zygote  : MountEmulatedStorage()
08-22 12:03:29.703  5622  5622 I libpersona: KNOX_SDCARD checking this for 1000
08-22 12:03:29.703  5622  5622 E Zygote  : v2
08-22 12:03:29.703  5622  5622 I libpersona: KNOX_SDCARD not a persona
08-22 12:03:29.703  5622  5622 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-22 12:03:29.703  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 12:03:29.703  5622  5622 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-22 12:03:29.713  5622  5622 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 12:03:29.713  1014  1014 D RCPManagerService: PackageReceiver onReceive()
08-22 12:03:29.713  1014  1014 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
08-22 12:03:29.713  5592  5592 D [0]UMC:UMCContentProvider: @onCreate
,08-22 12:03:29.713  1014  3001 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5622 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,08-22 12:03:29.713  5604  5604 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-22 12:03:29.733  1014  1014 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-22 12:03:29.733  1014  3001 I ActivityManager: Killing 4823:com.google.android.partnersetup/u0a15 (adj 15): empty #31
08-22 12:03:29.733  1014  1014 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-22 12:03:29.733  1014  1014 D OTPFW   : OtpDbHelper::getInstance New instance created
08-22 12:03:29.733  1014  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-22 12:03:29.733  1014  1014 D OTPFW   : DBIntegrity::getInstance - New instance created
08-22 12:03:29.733  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:29.733  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 12:03:29.733  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,08-22 12:03:29.743  5622  5622 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 12:03:29.743  1014  1014 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
,08-22 12:03:29.743  5622  5622 D ActivityThread: Added TimaKeyStore provider
,08-22 12:03:29.743  5592  5592 D [0]UMC:Core: onCreate(): 
08-22 12:03:29.743  5592  5592 D [0]UMC:Core: @isManagedProfileUser
08-22 12:03:29.743  5592  5592 D [0]UMC:Core: userId: 0
,08-22 12:03:29.743  5592  5592 D [0]UMC:Core: userInfo: UserInfo{0:Thali Test:13}
08-22 12:03:29.743  5592  5592 D [0]UMC:Core: userInfo.isManagedProfile() : false
,08-22 12:03:29.753  1014  1014 I OTPFW   : ProvisionData::getAllEntries Enter
,08-22 12:03:29.753  1014  1133 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 12:03:29.753  1014  1133 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-22 12:03:29.753  1014  1014 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-22 12:03:29.753  1014  1014 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-22 12:03:29.753  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:29.753  1014  1014 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-22 12:03:29.753  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-22 12:03:29.753  1014  1014 V EnterpriseBillingPolicy: uID is 10155
08-22 12:03:29.753  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
08-22 12:03:29.753  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-22 12:03:29.753  1014  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 12:03:29.753  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-22 12:03:29.753  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-22 12:03:29.753  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-22 12:03:29.753  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
,08-22 12:03:29.753  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-22 12:03:29.753  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 12:03:29.753  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-22 12:03:29.753  1014  1014 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-22 12:03:29.753  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-22 12:03:29.753  1014  1014 V EnterpriseBillingPolicy: uID is 10155
08-22 12:03:29.753  1014  2625 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-22 12:03:29.753  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
08-22 12:03:29.753  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-22 12:03:29.753  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-22 12:03:29.753  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-22 12:03:29.753  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-22 12:03:29.753  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-22 12:03:29.753  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-22 12:03:29.763  1014  1160 D TaskPersister: removeObsoleteFile: deleting file=127_task.xml
,08-22 12:03:29.763  1014  1014 V AlarmManagerEXT: com.test.thalitest(10155) is removed.
,08-22 12:03:29.763  5088  5088 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-22 12:03:29.763  5088  5088 I PCWCLIENTTRACE_PushUtil: sales region : global
08-22 12:03:29.763  5088  5088 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-22 12:03:29.763  1014  1038 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-22 12:03:29.763  5088  5088 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
08-22 12:03:29.763  1014  1038 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-22 12:03:29.763  1014  1038 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-22 12:03:29.763  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 12:03:29.773   330   330 I ServiceManager: Waiting for service AtCmdFwd...,
,08-22 12:03:29.793  1014  1466 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-22 12:03:29.793  5604  5604 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-22 12:03:29.793  5604  5604 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-22 12:03:29.793  5604  5604 D UserAnalysis: Create SecureDbHelper
08-22 12:03:29.793  1014  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:29.793  1014  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:29.793  1014  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:29.793  1014  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:29.803  5592  5592 D [0]UMC:DeviceInfo: USA==US==,
,08-22 12:03:29.813  1014  1466 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=5637 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-22 12:03:29.813  5637  5637 E Zygote  : MountEmulatedStorage()
08-22 12:03:29.813  5637  5637 I libpersona: KNOX_SDCARD checking this for 10035
08-22 12:03:29.813  5637  5637 E Zygote  : v2
08-22 12:03:29.813  5637  5637 I libpersona: KNOX_SDCARD not a persona
08-22 12:03:29.813  1014  1053 D PackageManager: delete codoeFile: 
08-22 12:03:29.813  5637  5637 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-22 12:03:29.813  5637  5637 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-22 12:03:29.813  5637  5637 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-22 12:03:29.823  1014  1533 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 12:03:29.823  1014  1533 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-22 12:03:29.823  1014  1533 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:29.823  1014  1053 D AASAuninstall: userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
08-22 12:03:29.823  1014  1053 I AASA_removePackage: UID=10155 Target=com.test.thalitest
08-22 12:03:29.823  1014  1533 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 12:03:29.823  1014  1053 D PackageManager: result of delete: 1{237114523}
08-22 12:03:29.823  1014  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-22 12:03:29.823  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 12:03:29.823  5622  5622 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
,08-22 12:03:29.823  5539  5539 D AndroidRuntime: Shutting down VM
,08-22 12:03:29.833  1014  3303 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,08-22 12:03:29.833  5604  5604 D IntelligenceServiceApplication: onCreate()
,08-22 12:03:29.833  5604  5604 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,08-22 12:03:29.843  1014  3303 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:29.843  1014  3303 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 12:03:29.843  1014  3303 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-22 12:03:29.843  5604  5604 D IntelligenceServiceApplication: no applications having user consent for prediction
08-22 12:03:29.843  1014  1488 D ActivityManager: startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
08-22 12:03:29.843  1014  1488 D ActivityManager: retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,08-22 12:03:29.853  1014  1488 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:29.853  1014  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 12:03:29.853  1014  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,08-22 12:03:29.853  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 12:03:29.853  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
08-22 12:03:29.853  1014  1053 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-22 12:03:29.853  1014  1053 D PackageManager: userId{-1}
08-22 12:03:29.853  1014  1053 D PackageManager: andCode{true}
,08-22 12:03:29.853  5604  5604 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-22 12:03:29.853  5637  5637 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 12:03:29.863  5637  5637 D ActivityThread: Added TimaKeyStore provider
08-22 12:03:29.863  5604  5604 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
08-22 12:03:29.863  1014  1531 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
08-22 12:03:29.863  1014  1531 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:29.863  1014  1531 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:29.863  1014  1531 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:29.863  1014  1531 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:29.873  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 12:03:29.873  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-22 12:03:29.873  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,08-22 12:03:29.883  5655  5655 E Zygote  : MountEmulatedStorage()
08-22 12:03:29.883  5655  5655 E Zygote  : v2
08-22 12:03:29.883  5655  5655 I libpersona: KNOX_SDCARD checking this for 1000
,08-22 12:03:29.883  5655  5655 I libpersona: KNOX_SDCARD not a persona
,08-22 12:03:29.883  5655  5655 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-22 12:03:29.883  5655  5655 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-22 12:03:29.883  5655  5655 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 12:03:29.893  5604  5604 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
,08-22 12:03:29.893  5604  5604 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
08-22 12:03:29.893  5604  5604 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
,08-22 12:03:29.893  5604  5604 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
08-22 12:03:29.893  5604  5604 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
08-22 12:03:29.893  5604  5604 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
08-22 12:03:29.893  5604  5604 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
08-22 12:03:29.893  5604  5604 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
08-22 12:03:29.893  5604  5604 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
08-22 12:03:29.893  5604  5604 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
08-22 12:03:29.893  5592  5592 D USER_AGENT: UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
08-22 12:03:29.893  5604  5604 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
08-22 12:03:29.893  5604  5604 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
08-22 12:03:29.893  5604  5604 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
08-22 12:03:29.893  5604  5604 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
,08-22 12:03:29.893  5604  5604 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
08-22 12:03:29.893  5604  5604 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
08-22 12:03:29.893  5604  5604 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
,08-22 12:03:29.893  5604  5604 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
08-22 12:03:29.893  5604  5604 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
08-22 12:03:29.893  5604  5604 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
08-22 12:03:29.893  5604  5604 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
,08-22 12:03:29.893  5604  5604 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
08-22 12:03:29.893  5604  5604 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
,08-22 12:03:29.903  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 12:03:29.903  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-22 12:03:29.903  5592  5592 D [0]UMC:AdminManager: init - start
,08-22 12:03:29.903  5604  5604 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
,08-22 12:03:29.903  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 12:03:29.903  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-22 12:03:29.903  5604  5604 D BluetoothAdapter: 896561412: getState() :  mService = null. Returning STATE_OFF
08-22 12:03:29.913  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 12:03:29.913  5604  5604 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
,08-22 12:03:29.913  1014  1531 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=5655 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,08-22 12:03:29.913  1014  1053 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-22 12:03:29.913  1014  1026 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 12:03:29.913  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,08-22 12:03:29.923  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:29.923  5655  5655 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 12:03:29.923  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 12:03:29.923  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-22 12:03:29.923  5655  5655 D ActivityThread: Added TimaKeyStore provider
,08-22 12:03:29.923  5592  5592 D [0]UMC:AdminManager: loadAdmins
,08-22 12:03:29.923  1014  2979 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-22 12:03:29.923  5604  5604 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-22 12:03:29.933  1014  1038 D UsbSettingsManager: clearDefaults: com.test.thalitest
08-22 12:03:29.933  1014  1038 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
08-22 12:03:29.933  5604  5604 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-22 12:03:29.953  5592  5592 D [0]UMC:AdminManager: init - end
,08-22 12:03:29.953  1014  3010 I ActivityManager: Killing 4921:com.google.android.apps.plus/u0a120 (adj 15): empty #31
,08-22 12:03:29.953  5592  5592 D GSLBManager: migrateStoredUrlFromOldPref
,08-22 12:03:29.963  5592  5592 D GSLBManager: migrateStoredUrlFromOldPref : Migration Not Needed
,08-22 12:03:29.963  5592  5592 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
,08-22 12:03:29.963  5592  5592 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
,08-22 12:03:29.973  5592  5592 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
,08-22 12:03:29.973  5592  5592 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
,08-22 12:03:29.973  1014  1466 I ActivityManager: Killing 5112:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,08-22 12:03:29.973  5592  5592 D [0]UMC:UMCAdmin: isContainer : 0
,08-22 12:03:29.973  5655  5672 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_REMOVED
,08-22 12:03:29.983  3743  5654 W IcingInternalCorpora: getNumBytesRead when not calculated.
,08-22 12:03:29.983  1014  1466 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
,08-22 12:03:29.983  5592  5592 E [0]UMC:UMCAdmin: No active admin owned by uid 10160
08-22 12:03:29.983  5592  5592 D [0]UMC:UMCAdmin: isContainer : 0
,08-22 12:03:29.983  4148  4148 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,08-22 12:03:29.993  5655  5672 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,08-22 12:03:29.993  5592  5592 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
,08-22 12:03:29.993  1014  2979 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
08-22 12:03:29.993  1014  2979 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,08-22 12:03:30.003  1014  2979 W ActivityManager: userId = 0, bbcId = -10000
,08-22 12:03:30.003  1014  2979 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 12:03:30.003  1014  2979 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,08-22 12:03:30.003  4803  5590 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 449 ms] updated apps [took 449 ms] 
08-22 12:03:30.003  5255  5267 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
08-22 12:03:30.003  5255  5267 D BadgeProvider: sendNotify, [notify] : null
08-22 12:03:30.003  5255  5267 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
08-22 12:03:30.003  5255  5267 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-22 12:03:30.003  5255  5267 D BadgeProvider: update, [UpdateCount] : 1
,08-22 12:03:30.003  5655  5655 D AcmsService: Enter Oncreate
,08-22 12:03:30.003  1014  1133 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 12:03:30.013  5655  5655 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-22 12:03:30.013  5655  5655 D AcmsService: creating AcmsCore
,08-22 12:03:30.013  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:30.013  1014  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 12:03:30.013  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 12:03:30.013  5655  5655 D AcmsCore: AcmsCore.getAcmsCore() - Enter
08-22 12:03:30.013  5655  5655 D AcmsCore: AcmsCore
,08-22 12:03:30.013  5655  5655 D AcmsCore: init
08-22 12:03:30.013  5655  5655 D AcmsCore: Looper handler is not null
08-22 12:03:30.013  5655  5655 D AcmsCore: Post to AcmsCoreHandler
08-22 12:03:30.013  5655  5655 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-22 12:03:30.013  5655  5655 D AcmsServiceMonitor: Incrementing - Counter value: 1
08-22 12:03:30.013  5655  5655 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>1
,08-22 12:03:30.013  5655  5655 D AcmsService: onStartCommand
08-22 12:03:30.013  5655  5655 D AcmsService: Action: android.intent.action.PACKAGE_REMOVED
08-22 12:03:30.013  5655  5655 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 1
08-22 12:03:30.013  5655  5655 D AcmsServiceMonitor: Incrementing - Counter value: 2
08-22 12:03:30.013  5655  5655 D AcmsService: Incremented Counter Value : onStartCommand
,08-22 12:03:30.013  1014  3010 D ActivityManager: startService callerProcessName:com.sec.enterprise.knox.cloudmdm.smdms, calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms
08-22 12:03:30.013  1014  3010 D ActivityManager: retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,08-22 12:03:30.023  1014  3010 W ActivityManager: userId = 0, bbcId = -10000
,08-22 12:03:30.023  1014  3010 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 12:03:30.023  1014  3010 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,08-22 12:03:30.023  5655  5674 D AcmsCertificateMngr: AcmsCertificateMngr
,08-22 12:03:30.023  5655  5674 D AcmsRevocationMngr: AcmsRevocationMngr
,08-22 12:03:30.023  1014  1466 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,08-22 12:03:30.023  5592  5592 D [0]UMC:GuardService: @GuardService - startService Result = ComponentInfo{com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService}
,08-22 12:03:30.023  5592  5592 D [0]UMC:CoreReceiver: Intent : android.intent.action.PACKAGE_REMOVED
08-22 12:03:30.023  5592  5592 D [0]UMC:CoreReceiver: PackageName : com.test.thalitest
,08-22 12:03:30.023  5592  5592 D [0]UMC:CoreReceiver: Intent Replacing : false
,08-22 12:03:30.033  5655  5655 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,08-22 12:03:30.033  5637  5675 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
08-22 12:03:30.033  5637  5675 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-22 12:03:30.033  5539  5539 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-22 12:03:30.043  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-22 12:03:30.043  5637  5675 D SPPClientService: PushLog.txt file is not deleted.
08-22 12:03:30.043  5637  5675 D SPPClientService: PushLog.txt file is not deleted.
08-22 12:03:30.053  5637  5675 D SPPClientService: ============PushLog. stop!
,08-22 12:03:30.053  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:30.053  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:30.053  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:30.053  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:30.053  5592  5592 D [0]UMC:CoreReceiver: bulk enrolled package: null
08-22 12:03:30.053  5592  5592 V [0]UMC:ProfileStorage: Enter loadList
,08-22 12:03:30.053  5592  5592 D [0]UMC:CoreReceiver: handleAutoEnrollmentAndUMCAdminDeactivation
08-22 12:03:30.053  5592  5592 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
,08-22 12:03:30.053  5592  5592 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
,08-22 12:03:30.063  5592  5592 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
08-22 12:03:30.063  5592  5592 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1,
08-22 12:03:30.063  5592  5592 D [0]UMC:UMCAdmin: isContainer : 0
,08-22 12:03:30.063  5678  5678 E Zygote  : MountEmulatedStorage(),
08-22 12:03:30.063  5678  5678 I libpersona: KNOX_SDCARD checking this for 10120
08-22 12:03:30.063  5678  5678 E Zygote  : v2
08-22 12:03:30.063  5678  5678 I libpersona: KNOX_SDCARD not a persona
08-22 12:03:30.063  1014  2979 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
08-22 12:03:30.063  5592  5592 E [0]UMC:UMCAdmin: No active admin owned by uid 10160
08-22 12:03:30.063  5592  5592 D [0]UMC:UMCAdmin: isContainer : 0
08-22 12:03:30.073  1014  1039 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PhotosAppTransitionMonitor: pid=5678 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-22 12:03:30.063  5678  5678 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-22 12:03:30.073  1014  1251 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-22 12:03:30.073  5678  5678 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-22 12:03:30.073  5678  5678 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-22 12:03:30.073  1014  1251 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:30.073  1014  1251 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 12:03:30.073  1014  1251 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 12:03:30.073  5592  5592 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
08-22 12:03:30.073  5592  5592 D [0]UMC:GuardService: @GuardService oncreate()
08-22 12:03:30.073  5592  5592 D [0]UMC:GuardService: @GuardService onStartCommand()
,08-22 12:03:30.083  5655  5655 D AcmsService: Inside handle Intent
08-22 12:03:30.083  5655  5655 D AcmsService: App removed - package name: com.test.thalitest
08-22 12:03:30.083  5655  5655 D AcmsCore: Post to AcmsCoreHandler
08-22 12:03:30.083  5655  5655 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-22 12:03:30.083  5655  5655 D AcmsServiceMonitor: Incrementing - Counter value: 3
08-22 12:03:30.083  5655  5655 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>5
08-22 12:03:30.083  5655  5655 D AcmsService: Decremented Counter Value : handleStartIntent
08-22 12:03:30.083  5655  5655 D AcmsServiceMonitor: Decrementing - Counter value: 2
,08-22 12:03:30.083  5338  5338 I SA      : [SUR] onReceive called
08-22 12:03:30.083  5338  5338 I SA      : [SUR] Not SA Package.. finish
,08-22 12:03:30.083  1014  3010 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 12:03:30.083  1014  3010 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.LightweightIndexService$LightweightWorkerService; callingUser = 0; userId(target) = 0
,08-22 12:03:30.093  1014  3010 W ActivityManager: userId = 0, bbcId = -10000,
,08-22 12:03:30.093  1014  3010 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 12:03:30.093  1014  3010 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 12:03:30.103  4943  4943 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(304): Wear auto uninstall disabled for package com.test.thalitest
,08-22 12:03:30.103  1014  1531 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
08-22 12:03:30.103  1014  1531 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.wear.WearSupportService; callingUser = 0; userId(target) = 0
,08-22 12:03:30.103  5678  5678 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 12:03:30.103  5678  5678 D ActivityThread: Added TimaKeyStore provider
,08-22 12:03:30.113  1014  1531 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:30.113  1014  1531 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 12:03:30.113  1014  1531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,08-22 12:03:30.133  1014  3303 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,08-22 12:03:30.133  1014  3303 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,08-22 12:03:30.133  1014  3303 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:30.133  1014  3303 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 12:03:30.133  1014  3303 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,08-22 12:03:30.133  1014  3003 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
08-22 12:03:30.133  1014  3003 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
,08-22 12:03:30.143  1014  3003 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:30.143  1014  3003 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 12:03:30.143  1014  3003 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,08-22 12:03:30.153  5678  5678 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-22 12:03:30.163  1014  1466 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 12:03:30.163  1014  1466 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chimera.GmsIntentOperationService; callingUser = 0; userId(target) = 0
08-22 12:03:30.163  1014  1466 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:30.163  1014  1466 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 12:03:30.163  1014  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-22 12:03:30.163  1014  1298 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-22 12:03:30.173  1014  1298 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:30.173  1014  1298 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 12:03:30.173  1014  1298 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,08-22 12:03:30.183  3743  5696 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-22 12:03:30.183  3743  5696 D AccountUtils: Clearing selected account for com.test.thalitest
,08-22 12:03:30.183  1937  1937 D WearableService: callingUid 10012, callindPid: 1937
,08-22 12:03:30.193  1467  1467 D Launcher.Model: reloadBadges entered.
,08-22 12:03:30.193  3743  5696 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,08-22 12:03:30.193  1467  1467 D Launcher.Model: reloadBadges entered.
,08-22 12:03:30.193  1014  1027 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: com.google.android.location.util.PreferenceService
,08-22 12:03:30.193  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.util.PreferenceService; callingUser = 0; userId(target) = 0
,08-22 12:03:30.193  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:30.193  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 12:03:30.193  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 12:03:30.203  1937  1937 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-22 12:03:30.203  1937  1937 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-22 12:03:30.203  1937  1937 D AndroidRuntime: Shutting down VM
,08-22 12:03:30.203  1014  3001 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 12:03:30.203  1014  3001 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:30.203  4943  4943 E Finsky  : [1] com.google.android.finsky.wear.bo.a(838): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-22 12:03:30.203  4943  4943 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6396): Dropping command=send_installed_apps due to Gms not connected
,08-22 12:03:30.203  1014  3001 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 12:03:30.203  1014  3001 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 12:03:30.213  3743  5696 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-22 12:03:30.223  1014  1533 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-22 12:03:30.223  1014  1533 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.config.ConfigService; callingUser = 0; userId(target) = 0
,08-22 12:03:30.223  1014  1533 W ActivityManager: userId = 0, bbcId = -10000
,08-22 12:03:30.223  1014  1533 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 12:03:30.223  1014  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 12:03:30.233  1014  1488 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 12:03:30.243  1014  1488 W ActivityManager: userId = 0, bbcId = -10000
,08-22 12:03:30.243  1014  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 12:03:30.243  1014  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms

```
