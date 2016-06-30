#### Test 72145431fdae11f_thali01_samsung-SM-A300FU Logs


```
--------- beginning of main
06-30 10:35:32.795   287   287 E SMD     : DCD OFF
,06-30 10:35:34.605  5971  5971 D AndroidRuntime: 
06-30 10:35:34.605  5971  5971 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
06-30 10:35:34.605  5971  5971 D AndroidRuntime: CheckJNI is OFF
06-30 10:35:34.615  5971  5971 D AndroidRuntime: readGMSProperty: start
06-30 10:35:34.615  5971  5971 D AndroidRuntime: readGMSProperty: already setted!!
06-30 10:35:34.615  5971  5971 D AndroidRuntime: propertySet: couldn't set property (it is from app)
06-30 10:35:34.615  5971  5971 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
06-30 10:35:34.615  5971  5971 D AndroidRuntime: readGMSProperty: end
06-30 10:35:34.615  5971  5971 D AndroidRuntime: addProductProperty: start
06-30 10:35:34.755  5971  5971 E AffinityControl: AffinityControl: registerfunction enter
06-30 10:35:34.785  5971  5971 D AndroidRuntime: Calling main entry com.android.commands.am.Am
06-30 10:35:34.795  1014  1519 E PersonaManagerService: inState():  stateMachine is null !!
06-30 10:35:34.795  1014  1519 I PersonaManagerService: PersonaId don't exist
06-30 10:35:34.795  1014  1519 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
06-30 10:35:34.795  1014  1519 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
06-30 10:35:34.805  1014  1519 W ActivityManager: mDVFSHelper.acquire()
06-30 10:35:34.815  1014  1045 D PhoneWindow: *FMB* installDecor mIsFloating : false
06-30 10:35:34.815  1014  1045 D PhoneWindow: *FMB* installDecor flags : -2122120936
06-30 10:35:34.815  1014  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:34.825  1014  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:34.825  1014  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:34.825  1014  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:34.835  5984  5984 E Zygote  : MountEmulatedStorage()
06-30 10:35:34.835  5984  5984 E Zygote  : v2
06-30 10:35:34.835  5984  5984 I libpersona: KNOX_SDCARD checking this for 10151
06-30 10:35:34.835  5984  5984 I libpersona: KNOX_SDCARD not a persona
06-30 10:35:34.835  1014  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
06-30 10:35:34.835  1014  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
06-30 10:35:34.835   257   257 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
06-30 10:35:34.835  5984  5984 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-30 10:35:34.835  1014  1519 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5984 uid=10151 gids={50151, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
06-30 10:35:34.835  1014  1519 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
06-30 10:35:34.835  1014  1519 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
06-30 10:35:34.845  5984  5984 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-30 10:35:34.845  5984  5984 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
06-30 10:35:34.855  5984  5984 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 10:35:34.855  5984  5984 D ActivityThread: Added TimaKeyStore provider
06-30 10:35:34.855  1014  1519 D InputDispatcher: Focused application set to: xxxx
06-30 10:35:34.855  1014  1519 D InputDispatcher: Focus left window: 5200
06-30 10:35:34.855  5971  5971 D AndroidRuntime: Shutting down VM
06-30 10:35:34.855  1014  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
06-30 10:35:34.865  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
06-30 10:35:34.865  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 10:35:34.865  1014  1076 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
06-30 10:35:34.865  1014  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
06-30 10:35:34.885  1014  1076 D PersonaManager: isKioskContainerExistOnDevice
06-30 10:35:34.895  5200  5200 V ActivityThread: updateVisibility : ActivityRecord{2e91211d token=android.os.BinderProxy@6eee7e1 {com.android.settings/com.android.settings.SettingsReceiverActivity}} show : false
06-30 10:35:34.915   257   449 I SurfaceFlinger: id=8 Removed Mauncher (4/10)
06-30 10:35:34.915   257  1941 I SurfaceFlinger: id=8 Removed Mauncher (-2/10)
06-30 10:35:34.925  1479  1479 V ActivityThread: updateVisibility : ActivityRecord{1a8b74e2 token=android.os.BinderProxy@2d53610c {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
06-30 10:35:34.925  1479  1479 D Launcher: onTrimMemory. Level: 20
06-30 10:35:34.935   257  1941 I SurfaceFlinger: id=11 Removed TettingsRec (5/9)
06-30 10:35:34.935   257   449 I SurfaceFlinger: id=11 Removed TettingsRec (-2/9)
06-30 10:35:34.995  5984  5984 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
06-30 10:35:35.015  5984  5984 I LibraryLoader: Time to load native libraries: 8 ms (timestamps 1928-1936)
06-30 10:35:35.015  5984  5984 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 10:35:35.035  5984  5984 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1ec83888}
06-30 10:35:35.045  5984  5984 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 10:35:35.045  5984  5984 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
06-30 10:35:35.065  5971  5971 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
06-30 10:35:35.075  5984  5984 I BrowserStartupController: Initializing chromium process, singleProcess=true
06-30 10:35:35.075  5984  5984 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-30 10:35:35.085  5984  5984 E SysUtils: ApplicationContext is null in ApplicationStatus,
,06-30 10:35:35.095  5984  6001 W chromium: [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,06-30 10:35:35.105  5984  5984 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,06-30 10:35:35.105  5984  5984 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,06-30 10:35:35.105  5984  5984 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,06-30 10:35:35.105  5984  5984 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
06-30 10:35:35.105  5984  5984 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
06-30 10:35:35.105  5984  5984 I Adreno-EGL: Build Date: 04/06/15 Mon
06-30 10:35:35.105  5984  5984 I Adreno-EGL: Local Branch: 
06-30 10:35:35.105  5984  5984 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
06-30 10:35:35.105  5984  5984 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
06-30 10:35:35.105  5984  5984 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,06-30 10:35:35.245  5984  6010 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,06-30 10:35:35.305  5984  5984 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-30 10:35:35.315  5984  5984 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,06-30 10:35:35.325  5984  5984 D PhoneWindow: *FMB* installDecor mIsFloating : false
,06-30 10:35:35.325  5984  5984 D PhoneWindow: *FMB* installDecor flags : -2139027200
,06-30 10:35:35.325  5984  5984 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,06-30 10:35:35.335  5984  5984 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-30 10:35:35.335  5984  5984 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-30 10:35:35.385  5984  6023 D OpenGLRenderer: Render dirty regions requested: true,
,06-30 10:35:35.385  1014  1477 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,06-30 10:35:35.385  1014  1477 D KnoxTimeoutHandler: postActiveUserChange for user 0
06-30 10:35:35.385  1014  1477 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,06-30 10:35:35.385  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
06-30 10:35:35.385  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
,06-30 10:35:35.395  5984  5984 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,06-30 10:35:35.405  5984  5984 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,06-30 10:35:35.405   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,06-30 10:35:35.425  1014  1076 D InputDispatcher: Focus entered window: 5984,
,06-30 10:35:35.425  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,06-30 10:35:35.425  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 10:35:35.425  5984  5984 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
06-30 10:35:35.425  5984  6023 I OpenGLRenderer: Initialized EGL, version 1.4
06-30 10:35:35.435  5984  6023 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
06-30 10:35:35.435  5984  6023 D OpenGLRenderer: Enabling debug mode 0
,06-30 10:35:35.445  5984  5984 V ActivityThread: updateVisibility : ActivityRecord{33a42d93 token=android.os.BinderProxy@2ee6c9cd {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,06-30 10:35:35.465  1014  3864 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,06-30 10:35:35.475  1014  6026 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:35:35.475  1176  1176 I StatusBar: Icon Only
,06-30 10:35:35.475  1176  1176 D PanelView: There is/are notification(s) 
,06-30 10:35:35.485  1014  2732 D SSRM:n  : SIOP:: AP = 310
,06-30 10:35:35.495  1014  1045 I ActivityManager: Displayed Component not be shown by security: +599ms (total +671ms)
,06-30 10:35:35.495  1014  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1f0d1702 u0 com.test.thalitest/.MainActivity t81} time:112410
06-30 10:35:35.495  1014  1045 W ActivityManager: mDVFSHelper.release()
,06-30 10:35:35.495  5984  5984 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
06-30 10:35:35.495  5984  5984 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2ee6c9cd time:112416
,06-30 10:35:35.505  1796  1796 I SamsungIME: getCurrentCandidateView
,06-30 10:35:35.505   257  1036 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,06-30 10:35:35.505   257   449 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,06-30 10:35:35.585  5984  5984 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5984
,06-30 10:35:35.595  1796  1796 D SamsungIME: Dismiss ExpandCandiate
,06-30 10:35:35.705  5984  5984 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,06-30 10:35:35.745  1796  1796 I SamsungIME: getDebugLevel  : 0x4f4c
,06-30 10:35:35.775  1796  1796 I SamsungIME: getDebugLevel  : 0x4f4c
,06-30 10:35:35.785  1796  1796 I SamsungIME: KeybaordView init() : load resources
,06-30 10:35:35.785   287   287 E SMD     : DCD OFF
,06-30 10:35:35.815  1796  1796 I SamsungIME: getCurrentKeyboard
06-30 10:35:35.815  1796  1796 I SamsungIME: getTextKeyboard
,06-30 10:35:35.855  1796  1796 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,06-30 10:35:35.865  5984  6028 D jxcore_app_log: JniHelper::setJavaVM(0xb743d2f0), pthread_self() = -1214718472
,06-30 10:35:35.875  5984  6028 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-30 10:35:35.875  5984  6028 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-30 10:35:35.875  5984  6028 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-30 10:35:35.875  5984  6028 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-30 10:35:35.875  5984  6028 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
06-30 10:35:35.875  5984  6028 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1483a183 added. We now have 1 listener(s)
,06-30 10:35:35.875  5984  6028 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,06-30 10:35:35.875  5984  6028 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,06-30 10:35:35.875  5984  6028 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,06-30 10:35:35.875  5984  6028 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,06-30 10:35:35.885  5984  6028 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-30 10:35:35.885  5984  6028 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-30 10:35:35.885  5984  6028 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-30 10:35:35.885  5984  6028 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
06-30 10:35:35.885  5984  6028 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-30 10:35:35.885  5984  6028 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-30 10:35:35.885  5984  6028 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-30 10:35:35.885  5984  6028 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-30 10:35:35.885  5984  6028 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-30 10:35:35.885  5984  6028 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-30 10:35:35.885  5984  6028 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
06-30 10:35:35.885  5984  6028 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fa88d7e added. We now have 1 listener(s)
,06-30 10:35:35.885  5984  6028 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,06-30 10:35:35.885  5984  6028 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,06-30 10:35:35.895  5984  6028 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,06-30 10:35:35.895  5984  6028 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
06-30 10:35:35.895  5984  6028 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
06-30 10:35:35.895  5984  6028 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
06-30 10:35:35.895  5984  6028 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,06-30 10:35:35.895  5984  6028 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,06-30 10:35:35.895  5984  6028 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
,06-30 10:35:35.905  5984  6028 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 10:35:35.905  5984  6028 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 10:35:35.905  5984  6028 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 10:35:35.905  5984  6028 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-30 10:35:35.905  5984  6028 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 10:35:35.905  5984  6028 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 10:35:35.905  5984  6028 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 10:35:35.905  5984  6028 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 10:35:35.905  5984  6028 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 10:35:35.905  5984  6028 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-30 10:35:35.905  5984  6028 D io.jxcore.node.ConnectivityMonitor: start: OK
,06-30 10:35:35.905  5984  6028 I io.jxcore.node.LifeCycleMonitor: start: OK
,06-30 10:35:35.925  5984  5984 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,06-30 10:35:36.435  5984  6033 W jxcore-log: Initializing JXcore engine
06-30 10:35:36.435  5984  6033 W jxcore-log: JXcore engine is ready
,06-30 10:35:36.495  1943  1943 E audit   : type=1400 msg=audit(1467275736.485:203): avc:  denied  { ioctl } for  pid=6033 comm="Thread-1088" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
06-30 10:35:36.495  1943  1943 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
06-30 10:35:36.495  1943  1943 E audit   : type=1300 msg=audit(1467275736.485:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=3 a3=9ee008f8 items=0 ppid=304 ppcomm=main pid=6033 auid=4294967295 uid=10151 gid=10151 euid=10151 suid=10151 fsuid=10151 egid=10151 sgid=10151 fsgid=10151 ses=4294967295 tty=(none) comm="Thread-1088" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
06-30 10:35:36.495  1943  1943 E audit   : type=1320 msg=audit(1467275736.485:203): 
,06-30 10:35:36.505  5984  6033 W jxcore-log: Starting JXcore engine
,06-30 10:35:36.605  5984  6033 W jxcore-log: Platform android
06-30 10:35:36.605  5984  6033 W jxcore-log: 
06-30 10:35:36.605  5984  6033 W jxcore-log: Process ARCH arm
06-30 10:35:36.605  5984  6033 W jxcore-log: 
,06-30 10:35:36.785   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,06-30 10:35:36.805  5984  6033 I jxcore-log: JXcore Cordova bridge is ready!
06-30 10:35:36.805  5984  6033 I jxcore-log: 
,06-30 10:35:36.805  5984  6033 W jxcore-log: JXcore engine is started
,06-30 10:35:36.815  5984  6028 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,06-30 10:35:36.815  5984  5984 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,06-30 10:35:36.825  5984  6033 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
06-30 10:35:36.825  5984  6033 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,06-30 10:35:36.835  5984  5984 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,06-30 10:35:36.835  5984  5984 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,06-30 10:35:36.835  1014  1684 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
06-30 10:35:36.835  1014  1684 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
06-30 10:35:36.835  1014  1684 D InputDispatcher: Focused application set to: xxxx
06-30 10:35:36.845  1014  1684 I ActivityManager: Killing 5594:com.google.android.partnersetup/u0a14 (adj 15): empty #21
06-30 10:35:36.845  5984  5984 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
06-30 10:35:36.845  5984  5984 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
06-30 10:35:36.845  5984  5984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
06-30 10:35:36.845  5984  5984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
06-30 10:35:36.855  5984  5984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
06-30 10:35:36.855  5984  5984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
06-30 10:35:36.855  5984  5984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1483a183 removed from the list
06-30 10:35:36.855  5984  5984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
06-30 10:35:36.855  5984  5984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fa88d7e removed from the list
06-30 10:35:36.855  5984  5984 D io.jxcore.node.ConnectivityMonitor: stop
06-30 10:35:36.855  5984  5984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
06-30 10:35:36.855  5984  5984 I io.jxcore.node.LifeCycleMonitor: stop: OK
,06-30 10:35:36.865   257   451 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
06-30 10:35:36.865   257  1036 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,06-30 10:35:36.875  1014  1329 D InputDispatcher: Focus left window: 5984
,06-30 10:35:36.875  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
06-30 10:35:36.875  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 10:35:36.875  5984  5984 E ViewRootImpl: sendUserActionEvent() mView == null
,06-30 10:35:36.875  1014  1477 W ActivityManager: mDVFSHelper.acquire()
,06-30 10:35:36.905  1014  1309 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,06-30 10:35:36.935  1014  1685 D ActivityManager: post active user change for 0 fullscreen false record.isFloatingActivity() false
,06-30 10:35:36.935  1014  1685 D KnoxTimeoutHandler: postActiveUserChange for user 0
06-30 10:35:36.935  1014  1685 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,06-30 10:35:36.935  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,06-30 10:35:36.935  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
,06-30 10:35:36.935  1014  1014 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,06-30 10:35:36.935  1479  1479 D Launcher: onRestart, Launcher: 955012404
,06-30 10:35:36.935  1479  1479 D Launcher: onStart, Launcher: 955012404
,06-30 10:35:36.935  1479  1479 D Launcher.HomeView: onStart
,06-30 10:35:36.945  1479  1479 V ActivityThread: updateVisibility : ActivityRecord{1a8b74e2 token=android.os.BinderProxy@2d53610c {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,06-30 10:35:36.965   257   257 I SurfaceFlinger: id=14 createSurf (540x960),1 flag=4, Mauncher
,06-30 10:35:36.975  1014  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,06-30 10:35:36.985  1479  1479 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,06-30 10:35:36.995   257   257 I SurfaceFlinger: id=15 createSurf (585x883),1 flag=4, TettingsRec
,06-30 10:35:36.995  1014  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams,
,06-30 10:35:37.005  1014  1473 D InputDispatcher: Focus entered window: 5200
,06-30 10:35:37.005  5200  5200 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
06-30 10:35:37.005  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
06-30 10:35:37.005  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,06-30 10:35:37.025  5200  5200 V ActivityThread: updateVisibility : ActivityRecord{2e91211d token=android.os.BinderProxy@6eee7e1 {com.android.settings/com.android.settings.SettingsReceiverActivity}} show : true
,06-30 10:35:37.055  1479  1479 D Launcher.HomeView: onStop
,06-30 10:35:37.055  5200  5200 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@6eee7e1 time:113975
,06-30 10:35:37.065  1014  1045 W ActivityManager: mDVFSHelper.release()
,06-30 10:35:37.065  1014  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{5819caa u0 com.android.settings/.SettingsReceiverActivity t80} time:113983
06-30 10:35:37.065  1014  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{198d130d u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t79} time:113984
,06-30 10:35:37.145  6034  6034 D AndroidRuntime: 
06-30 10:35:37.145  6034  6034 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,06-30 10:35:37.145  6034  6034 D AndroidRuntime: CheckJNI is OFF
,06-30 10:35:37.145  6034  6034 D AndroidRuntime: readGMSProperty: start
06-30 10:35:37.145  6034  6034 D AndroidRuntime: readGMSProperty: already setted!!
06-30 10:35:37.145  6034  6034 D AndroidRuntime: propertySet: couldn't set property (it is from app)
06-30 10:35:37.145  6034  6034 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
06-30 10:35:37.145  6034  6034 D AndroidRuntime: readGMSProperty: end
06-30 10:35:37.145  6034  6034 D AndroidRuntime: addProductProperty: start
,06-30 10:35:37.285  6034  6034 E AffinityControl: AffinityControl: registerfunction enter,
,06-30 10:35:37.315  6034  6034 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,06-30 10:35:37.315  1014  1329 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
06-30 10:35:37.315  1014  1329 D PackageManager: START PACKAGE DELETE: observer{924652934}
06-30 10:35:37.315  1014  1329 D PackageManager: pkg{<packageName>}
06-30 10:35:37.315  1014  1329 D PackageManager: user{0}
06-30 10:35:37.315  1014  1329 D PackageManager: caller{2000}
06-30 10:35:37.315  1014  1329 D PackageManager: flags{2}
06-30 10:35:37.315  1014  1329 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
06-30 10:35:37.315  1014  1329 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
06-30 10:35:37.315  1014  1329 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
06-30 10:35:37.325  1014  1055 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
06-30 10:35:37.315  1014  1329 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
06-30 10:35:37.325  1014  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
06-30 10:35:37.325  1014  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
06-30 10:35:37.325  1014  1055 D ApplicationPolicy: getApplicationUninstallationEnabled
06-30 10:35:37.325  1014  1055 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,06-30 10:35:37.325  1014  1055 D PackageManager: !@killApplicatoin: 10151, uninstall pkg
,06-30 10:35:37.325  1014  1040 I ActivityManager: Force stopping com.test.thalitest appid=10151 user=-1: uninstall pkg
,06-30 10:35:37.325  1014  1040 I ActivityManager: Killing 5984:com.test.thalitest/u0a151 (adj 9): stop com.test.thalitest cause uninstall pkg
,06-30 10:35:37.325  1014  1040 D PersonaManager: isKioskContainerExistOnDevice
,06-30 10:35:37.445  1014  1055 I ActivityManager: Force stopping com.test.thalitest appid=10151 user=0: pkg removed
,06-30 10:35:37.465  1014  1055 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,06-30 10:35:37.505  5748  5748 I art     : Explicit concurrent mark sweep GC freed 17399(958KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 1.200ms total 52.325ms
,06-30 10:35:37.525  1595  1773 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,06-30 10:35:37.535  1796  1796 E SamsungIME: mOCRHelper is null
,06-30 10:35:37.535  1014  1097 I InputReader: Reconfiguring input devices.  changes=0x00000010
,06-30 10:35:37.575  1014  1121 V NetworkStats: removeUidsLocked() for UIDs [10151]
06-30 10:35:37.575  1014  1121 V NetworkStats: performPollLocked(flags=0x3)
,06-30 10:35:37.575  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
,06-30 10:35:37.575  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,06-30 10:35:37.575  1014  1121 V NetworkStats: performPollLocked() took 5ms
,06-30 10:35:37.595  1430  1430 D PersonaManager: isKioskContainerExistOnDevice
,06-30 10:35:37.595  1430  1430 D RegisteredServicesCache: empty dynamic service
,06-30 10:35:37.605  1430  1430 D RegisteredComponentCache: Collect Tech packages for Knox
,06-30 10:35:37.615  1430  1430 D PersonaManager: isKioskContainerExistOnDevice
,06-30 10:35:37.615  3958  3958 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Jun 30 10:35:37 GMT+02:00 2016
,06-30 10:35:37.615  1014  1684 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,06-30 10:35:37.615  1014  1684 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,06-30 10:35:37.615  1014  1684 W ActivityManager: userId = 0, bbcId = -10000,
06-30 10:35:37.615  1014  1684 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 10:35:37.615  1014  1684 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,06-30 10:35:37.625  1014  1039 D EnterpriseDeviceManagerService: Package has changed for user 0
,06-30 10:35:37.625  3958  3958 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,06-30 10:35:37.625  1014  1473 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=23, mSplitNum[2]=33, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=43
06-30 10:35:37.625  1014  1473 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,06-30 10:35:37.625  1014  1039 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
06-30 10:35:37.625  1014  1122 D NtpTrustedTime: forceRefresh() from cache miss
,06-30 10:35:37.625  1014  1039 W TextServicesManagerService: no available spell checker services found
,06-30 10:35:37.625   277   998 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
06-30 10:35:37.625   277   998 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,06-30 10:35:37.625   277   998 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
06-30 10:35:37.625   277   998 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,06-30 10:35:37.635  1014  1122 D NtpTrustedTime: forceRefresh Fail.
,06-30 10:35:37.635  1014  1473 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,06-30 10:35:37.635  1014  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:37.635  1014  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:37.635  1014  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:37.635  1014  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:37.635  3958  3958 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,06-30 10:35:37.655  6052  6052 E Zygote  : MountEmulatedStorage()
06-30 10:35:37.655  6052  6052 E Zygote  : v2
06-30 10:35:37.655  6052  6052 I libpersona: KNOX_SDCARD checking this for 10090
06-30 10:35:37.655  6052  6052 I libpersona: KNOX_SDCARD not a persona
,06-30 10:35:37.655  3958  3958 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,06-30 10:35:37.655  6052  6052 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 10:35:37.655  6052  6052 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-30 10:35:37.655  1014  1473 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6052 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,06-30 10:35:37.665  1014  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,06-30 10:35:37.665  6052  6052 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 10:35:37.665  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 10:35:37.665  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:37.665  3958  3958 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,06-30 10:35:37.665  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:37.665  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:37.665  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:37.675  6060  6060 E Zygote  : MountEmulatedStorage()
06-30 10:35:37.675  6060  6060 E Zygote  : v2
06-30 10:35:37.675  6060  6060 I libpersona: KNOX_SDCARD checking this for 10032
06-30 10:35:37.675  6060  6060 I libpersona: KNOX_SDCARD not a persona
,06-30 10:35:37.675  3958  6050 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
06-30 10:35:37.675  6060  6060 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 10:35:37.675  6060  6060 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-30 10:35:37.685  6060  6060 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,06-30 10:35:37.685  1014  1685 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin,
06-30 10:35:37.685  1014  1685 D SecContentProvider2: mCursor = null
,06-30 10:35:37.685  1014  1040 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=6060 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 10:35:37.685  1014  1040 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,06-30 10:35:37.685  3958  6050 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,06-30 10:35:37.685  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:37.695  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:37.695  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:37.695  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:37.695  3958  6050 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,06-30 10:35:37.695  3958  6050 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,06-30 10:35:37.705  6072  6072 E Zygote  : MountEmulatedStorage()
,06-30 10:35:37.705  6072  6072 I libpersona: KNOX_SDCARD checking this for 10052
06-30 10:35:37.705  6072  6072 E Zygote  : v2
06-30 10:35:37.705  6072  6072 I libpersona: KNOX_SDCARD not a persona
06-30 10:35:37.705  6072  6072 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 10:35:37.705  6072  6072 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-30 10:35:37.715  6072  6072 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,06-30 10:35:37.715  1014  1040 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6072 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a,
,06-30 10:35:37.725  1014  1040 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,06-30 10:35:37.725  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 10:35:37.725  6052  6052 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 10:35:37.725  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:37.725  6060  6060 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 10:35:37.725  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:37.725  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:37.725  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:37.725  6060  6060 D ActivityThread: Added TimaKeyStore provider
06-30 10:35:37.725  6052  6052 D ActivityThread: Added TimaKeyStore provider
,06-30 10:35:37.725  1014  1014 I art     : Explicit concurrent mark sweep GC freed 44195(3MB) AllocSpace objects, 17(272KB) LOS objects, 33% free, 22MB/34MB, paused 3.075ms total 259.248ms
,06-30 10:35:37.725  1014  1055 I art     : WaitForGcToComplete blocked for 252.048ms for cause Explicit
,06-30 10:35:37.725  1014  2750 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:35:37.735  6095  6095 E Zygote  : MountEmulatedStorage()
06-30 10:35:37.735  6095  6095 E Zygote  : v2
06-30 10:35:37.735  6095  6095 I libpersona: KNOX_SDCARD checking this for 10098
06-30 10:35:37.735  6095  6095 I libpersona: KNOX_SDCARD not a persona
,06-30 10:35:37.735  6095  6095 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 10:35:37.745  6095  6095 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-30 10:35:37.745  6095  6095 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 10:35:37.755  1014  1040 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=6095 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,06-30 10:35:37.755  6072  6072 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 10:35:37.755  6072  6072 D ActivityThread: Added TimaKeyStore provider
,06-30 10:35:37.785   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,06-30 10:35:37.785  6095  6095 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:35:37.785  6095  6095 D ActivityThread: Added TimaKeyStore provider
06-30 10:35:37.785  1014  1014 D RCPManagerService: PackageReceiver onReceive()
,06-30 10:35:37.785  1014  1014 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,06-30 10:35:37.795  1014  1014 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
06-30 10:35:37.795  1014  1014 I OTPFW   : PackageRemovalReceiver::onReceive Enter
06-30 10:35:37.795  1014  1014 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10151 container id = 0
,06-30 10:35:37.795  1014  1014 I OTPFW   : ProvisionData::getAllEntries Enter
,06-30 10:35:37.795  1014  1014 E OTPFW   : ProvisionData::getAllEntries Table is empty
,06-30 10:35:37.835  1014  1536 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,06-30 10:35:37.835  1014  1536 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:37.835  1014  1536 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:37.835  1014  1536 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:37.835  1014  1536 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:37.845  6052  6052 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,06-30 10:35:37.845  6052  6052 D elm:15121: ELMEngine.ELMEngine( context ).,
06-30 10:35:37.855  3958  6050 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.,
,06-30 10:35:37.855  6052  6052 D elm:15121: MDMBridge.setEnterpriseBridge(),
,06-30 10:35:37.855  1014  1536 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=6112 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,06-30 10:35:37.865  1014  1477 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
06-30 10:35:37.865  1014  1477 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,06-30 10:35:37.865  3958  6050 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,06-30 10:35:37.865  1014  1477 W ActivityManager: userId = 0, bbcId = -10000
06-30 10:35:37.865  1014  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 10:35:37.865  1014  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,06-30 10:35:37.865  6112  6112 E Zygote  : MountEmulatedStorage()
06-30 10:35:37.865  6112  6112 I libpersona: KNOX_SDCARD checking this for 1000
06-30 10:35:37.865  6112  6112 E Zygote  : v2
06-30 10:35:37.865  6112  6112 I libpersona: KNOX_SDCARD not a persona
,06-30 10:35:37.865  3958  6050 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
06-30 10:35:37.865  6112  6112 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 10:35:37.875  6112  6112 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-30 10:35:37.875  6112  6112 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 10:35:37.875  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 10:35:37.885  6052  6052 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,06-30 10:35:37.885  6052  6052 D elm:15121: ElmAgentService : onCreate()
,06-30 10:35:37.885  6052  6119 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,06-30 10:35:37.895  6052  6119 D elm:15121: MainReceiver.listeningToPackageRemoved()
,06-30 10:35:37.895  6052  6119 D elm:15121: MDMBridge.getInstance()
,06-30 10:35:37.895  1014  1486 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
06-30 10:35:37.895  1014  1486 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,06-30 10:35:37.895  3332  3332 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,06-30 10:35:37.905  1014  1486 W ActivityManager: userId = 0, bbcId = -10000
06-30 10:35:37.905  1014  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 10:35:37.905  1014  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,06-30 10:35:37.905  6052  6119 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
06-30 10:35:37.905  3332  3332 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,06-30 10:35:37.905  3332  3332 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
06-30 10:35:37.905  3332  3332 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
06-30 10:35:37.905  3332  3332 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
06-30 10:35:37.905  3332  3332 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
06-30 10:35:37.905  3332  3332 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
06-30 10:35:37.905  3332  3332 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:35:37.905  3332  3332 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:35:37.905  3332  3332 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
06-30 10:35:37.905  3332  3332 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 10:35:37.905  3332  3332 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 10:35:37.905  3332  3332 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
06-30 10:35:37.905  3332  3332 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,06-30 10:35:37.905  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 10:35:37.905  1014  1014 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,06-30 10:35:37.905  6052  6119 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,06-30 10:35:37.915  6060  6128 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,06-30 10:35:37.915  1014  1014 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,06-30 10:35:37.915  6112  6112 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:35:37.915  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
06-30 10:35:37.915  1014  1014 V EnterpriseBillingPolicy: uID is 10151
06-30 10:35:37.915  6112  6112 D ActivityThread: Added TimaKeyStore provider
06-30 10:35:37.915  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
06-30 10:35:37.915  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,06-30 10:35:37.915  6060  6128 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,06-30 10:35:37.915  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
06-30 10:35:37.915  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
06-30 10:35:37.915  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
06-30 10:35:37.915  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
06-30 10:35:37.915  3958  3958 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,06-30 10:35:37.915  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,06-30 10:35:37.935  1014  1014 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,06-30 10:35:37.935  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
06-30 10:35:37.935  1014  1014 V EnterpriseBillingPolicy: uID is 10151
06-30 10:35:37.935  1014  2732 D SSRM:bc : MSG_TYPE_APP_REMOVED::
06-30 10:35:37.935  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
06-30 10:35:37.935  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
06-30 10:35:37.935  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
06-30 10:35:37.935  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
06-30 10:35:37.935  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
06-30 10:35:37.935  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,06-30 10:35:37.935  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,06-30 10:35:37.935  1014  1014 V AlarmManagerEXT: com.test.thalitest(10151) is removed.
,06-30 10:35:37.935  6052  6052 D elm:15121: ElmAgentService : onDestroy().
,06-30 10:35:37.935  6060  6128 D SPPClientService: PushLog.txt file is not deleted.
06-30 10:35:37.935  6060  6128 D SPPClientService: PushLog.txt file is not deleted.
06-30 10:35:37.935  6060  6128 D SPPClientService: ============PushLog. stop!
,06-30 10:35:37.945  1014  1486 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,06-30 10:35:37.945  1014  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:37.945  1014  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:37.945  1014  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:37.945  1014  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:37.955  6132  6132 E Zygote  : MountEmulatedStorage(),
06-30 10:35:37.955  6132  6132 I libpersona: KNOX_SDCARD checking this for 10032
06-30 10:35:37.955  6132  6132 E Zygote  : v2
06-30 10:35:37.955  6132  6132 I libpersona: KNOX_SDCARD not a persona
,06-30 10:35:37.955  6132  6132 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 10:35:37.955  6132  6132 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,06-30 10:35:37.965  6132  6132 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,06-30 10:35:37.965  1014  1486 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6132 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 10:35:37.975  1014  1486 I ActivityManager: Killing 4963:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
,06-30 10:35:37.985  6132  6132 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:35:37.985  6132  6132 D ActivityThread: Added TimaKeyStore provider
,06-30 10:35:38.005  1014  1159 D TaskPersister: removeObsoleteFile: deleting file=81_task.xml
,06-30 10:35:38.005  1014  1159 D TaskPersister: removeObsoleteFile: deleting file=80_task.xml
,06-30 10:35:38.015  1014  1536 I ActivityManager: Killing 5631:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
,06-30 10:35:38.025  1014  1536 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,06-30 10:35:38.035  1014  1536 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:38.035  1014  1536 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:38.035  1014  1536 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:38.035  1014  1536 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:38.035  6072  6129 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,06-30 10:35:38.045  6148  6148 E Zygote  : MountEmulatedStorage(),
06-30 10:35:38.045  6148  6148 E Zygote  : v2
06-30 10:35:38.045  6148  6148 I libpersona: KNOX_SDCARD checking this for 10055
06-30 10:35:38.045  6148  6148 I libpersona: KNOX_SDCARD not a persona
06-30 10:35:38.045  6148  6148 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 10:35:38.045  6148  6148 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
06-30 10:35:38.045  1014  1536 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6148 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
06-30 10:35:38.055  6148  6148 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
06-30 10:35:38.055  1014  1039 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,06-30 10:35:38.055  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 10:35:38.055  1637  1637 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
06-30 10:35:38.055  1637  1637 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,06-30 10:35:38.065  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 10:35:38.075  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 10:35:38.075  1014  1477 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
,06-30 10:35:38.075  1014  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:38.075  1014  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:38.075  1014  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:38.075  1014  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:38.085  6148  6148 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:35:38.085  6148  6148 D ActivityThread: Added TimaKeyStore provider
,06-30 10:35:38.095  6164  6164 E Zygote  : MountEmulatedStorage()
,06-30 10:35:38.095  6164  6164 E Zygote  : v2
06-30 10:35:38.095  6164  6164 I libpersona: KNOX_SDCARD checking this for 1000
06-30 10:35:38.095  6164  6164 I libpersona: KNOX_SDCARD not a persona
06-30 10:35:38.095  6164  6164 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-30 10:35:38.095  1014  1477 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6164 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
06-30 10:35:38.105  1014  1477 I ActivityManager: Killing 5651:com.sec.pcw.device/1000 (adj 15): empty #21
06-30 10:35:38.105  6164  6164 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-30 10:35:38.105  6164  6164 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
06-30 10:35:38.105  1014  1026 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
06-30 10:35:38.105  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
06-30 10:35:38.105  6132  6167 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
06-30 10:35:38.105  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
06-30 10:35:38.105  6132  6167 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
06-30 10:35:38.105  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 10:35:38.105  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
06-30 10:35:38.115  6132  6167 D SPPClientService: PushLog.txt file is not deleted.
06-30 10:35:38.115  6132  6167 D SPPClientService: PushLog.txt file is not deleted.
06-30 10:35:38.115  6132  6167 D SPPClientService: ============PushLog. stop!
06-30 10:35:38.115  1014  1039 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
06-30 10:35:38.115  1014  1039 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 10:35:38.115  1014  1039 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
06-30 10:35:38.125  6164  6164 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 10:35:38.125  6164  6164 D ActivityThread: Added TimaKeyStore provider
06-30 10:35:38.125  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 10:35:38.135  1014  1309 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
06-30 10:35:38.135   304   304 I art     : Explicit concurrent mark sweep GC freed 8715(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 614us total 41.374ms
06-30 10:35:38.135  3374  6176 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,06-30 10:35:38.145  3374  6176 D AccountUtils: Clearing selected account for com.test.thalitest
,06-30 10:35:38.145  1014  1309 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:38.145  1014  1309 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:38.145  1014  1309 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:38.145  1014  1309 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:38.155   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 635us total 19.466ms
,06-30 10:35:38.165  6148  6148 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,06-30 10:35:38.165  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 10:35:38.175   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 578us total 18.198ms
,06-30 10:35:38.185  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,06-30 10:35:38.185  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 10:35:38.185  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,06-30 10:35:38.185  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,06-30 10:35:38.185  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 10:35:38.185  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,06-30 10:35:38.195  6185  6185 E Zygote  : MountEmulatedStorage(),
06-30 10:35:38.195  6185  6185 E Zygote  : v2
06-30 10:35:38.195  6185  6185 I libpersona: KNOX_SDCARD checking this for 10036,
06-30 10:35:38.195  6185  6185 I libpersona: KNOX_SDCARD not a persona
,06-30 10:35:38.195  6185  6185 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-30 10:35:38.195  1014  1309 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.msc.sa.selfupdate.SelfUpgradeReceiver: pid=6185 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 10:35:38.205  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 10:35:38.205  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,06-30 10:35:38.205  6185  6185 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-30 10:35:38.205  6185  6185 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
06-30 10:35:38.205  6148  6148 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,06-30 10:35:38.205  6148  6148 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
06-30 10:35:38.205  6148  6148 D UserAnalysis: Create SecureDbHelper
,06-30 10:35:38.205  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 10:35:38.215  1014  1076 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,06-30 10:35:38.215  1014  1076 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:38.215  1014  1076 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:38.215  1014  1076 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:38.215  1014  1076 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:38.215  3374  3374 D ChimeraRcvrProxy: Creating receiver proxy ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesSystemBroadcastReceiverProxy}
06-30 10:35:38.215  3374  3374 D ChimeraRcvrProxy: Proxying container receiver ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesSystemBroadcastReceiverProxy} to Chimera receiver impl com.google.android.gms.games.receiver.PlaySystemBroadcastReceiver
06-30 10:35:38.215  3374  3374 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
06-30 10:35:38.215  3374  3374 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,06-30 10:35:38.215  1014  1055 I art     : Explicit concurrent mark sweep GC freed 20912(1210KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 22MB/34MB, paused 3.176ms total 486.320ms
,06-30 10:35:38.225  6200  6200 E Zygote  : MountEmulatedStorage()
,06-30 10:35:38.225  6200  6200 E Zygote  : v2
06-30 10:35:38.225  6200  6200 I libpersona: KNOX_SDCARD checking this for 10014
06-30 10:35:38.225  6200  6200 I libpersona: KNOX_SDCARD not a persona
,06-30 10:35:38.225  6200  6200 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,06-30 10:35:38.235  1014  1076 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=6200 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
,06-30 10:35:38.235  6200  6200 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-30 10:35:38.235  6200  6200 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,06-30 10:35:38.235  6185  6185 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:35:38.235  6185  6185 D ActivityThread: Added TimaKeyStore provider
,06-30 10:35:38.245  1014  1473 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,06-30 10:35:38.245  1014  1473 W ActivityManager: userId = 0, bbcId = -10000
06-30 10:35:38.245  1014  1473 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,06-30 10:35:38.245  1014  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 10:35:38.245  1014  1519 D LocationManagerService: getProviders()=[passive, gps]
,06-30 10:35:38.265  6148  6148 D IntelligenceServiceApplication: onCreate()
06-30 10:35:38.265  1014  1329 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,06-30 10:35:38.265  6148  6148 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,06-30 10:35:38.265  1014  1329 W ActivityManager: userId = 0, bbcId = -10000
06-30 10:35:38.265  1014  1329 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 10:35:38.265  1014  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 10:35:38.265  6200  6200 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:35:38.265  6200  6200 D ActivityThread: Added TimaKeyStore provider
,06-30 10:35:38.275  6164  6164 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
,06-30 10:35:38.275  3374  3374 D ChimeraSrvcProxy: Creating service proxy ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesAsyncServiceProxy}
,06-30 10:35:38.275  3374  3374 D ChimeraSrvcProxy: Proxying container service ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesAsyncServiceProxy} to Chimera service impl com.google.android.gms.games.service.PlayGamesAsyncService
,06-30 10:35:38.275  1014  1473 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 10:35:38.275  1014  1473 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService; callingUser = 0; userId(target) = 0
,06-30 10:35:38.275  1014  1473 W ActivityManager: userId = 0, bbcId = -10000
06-30 10:35:38.275  1014  1473 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 10:35:38.275  1014  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 10:35:38.275  3374  3374 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
06-30 10:35:38.275  3374  3374 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,06-30 10:35:38.275  6148  6148 D IntelligenceServiceApplication: no applications having user consent for prediction
,06-30 10:35:38.285  3374  6176 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,06-30 10:35:38.285  1014  1039 D UsbSettingsManager: clearDefaults: com.test.thalitest
06-30 10:35:38.285  1014  1519 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,06-30 10:35:38.285  1014  1039 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,06-30 10:35:38.285  6148  6148 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,06-30 10:35:38.285  1014  1685 D ActivityManager: startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
06-30 10:35:38.285  1014  1685 D ActivityManager: retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,06-30 10:35:38.295  1014  1685 W ActivityManager: userId = 0, bbcId = -10000
,06-30 10:35:38.295  1014  1685 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,06-30 10:35:38.295  1014  1685 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,06-30 10:35:38.295  1014  1055 D PackageManager: delete codoeFile: 
,06-30 10:35:38.295  1014  1055 I AASA_removePackage: UID=10151 Target=com.test.thalitest
06-30 10:35:38.295  1014  1055 D AASAuninstall: userId = 0, info.removedAppID = 10151, info.uid = 10151, packageName = com.test.thalitest
06-30 10:35:38.295  1014  1055 D PackageManager: result of delete: 1{924652934}
,06-30 10:35:38.305  6148  6148 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,06-30 10:35:38.315  6034  6034 D AndroidRuntime: Shutting down VM
,06-30 10:35:38.315  1014  1309 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,06-30 10:35:38.315  1014  1309 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:38.315  1014  1309 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:38.315  1014  1309 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:38.315  1014  1309 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:38.335  6223  6223 E Zygote  : MountEmulatedStorage()
06-30 10:35:38.335  6223  6223 I libpersona: KNOX_SDCARD checking this for 1000
06-30 10:35:38.335  6223  6223 E Zygote  : v2
06-30 10:35:38.335  6223  6223 I libpersona: KNOX_SDCARD not a persona
06-30 10:35:38.335  6223  6223 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 10:35:38.335  1014  1309 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=6223 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,06-30 10:35:38.335  1014  1309 I ActivityManager: Killing 5714:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21,
06-30 10:35:38.335  6223  6223 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-30 10:35:38.335  1014  1055 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
06-30 10:35:38.335  1014  1055 D PackageManager: userId{-1}
06-30 10:35:38.335  1014  1055 D PackageManager: andCode{true}
,06-30 10:35:38.335  6223  6223 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,06-30 10:35:38.335  3374  6221 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
06-30 10:35:38.335  1014  1477 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
06-30 10:35:38.335  3374  6221 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
06-30 10:35:38.335  1014  1477 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.util.PreferenceService; callingUser = 0; userId(target) = 0
,06-30 10:35:38.345  3374  6221 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
06-30 10:35:38.345  3374  6221 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,06-30 10:35:38.345  1014  1477 W ActivityManager: userId = 0, bbcId = -10000
06-30 10:35:38.345  1014  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 10:35:38.345  1014  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 10:35:38.355  1014  1473 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,06-30 10:35:38.355  1014  1473 W ActivityManager: userId = 0, bbcId = -10000
,06-30 10:35:38.355  1014  1473 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 10:35:38.355  1014  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 10:35:38.355  6223  6223 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:35:38.355  1014  1536 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 10:35:38.355  1014  1536 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
06-30 10:35:38.365  6223  6223 D ActivityThread: Added TimaKeyStore provider
,06-30 10:35:38.365  1014  1536 W ActivityManager: userId = 0, bbcId = -10000
,06-30 10:35:38.365  1014  1536 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 10:35:38.365  1014  1536 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 10:35:38.365  1014  1536 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:38.365  1014  1536 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:38.365  1014  1536 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:38.365  1014  1536 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:38.365  3374  6221 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
06-30 10:35:38.365  3374  6221 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,06-30 10:35:38.365  3374  6221 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,06-30 10:35:38.385  6240  6240 E Zygote  : MountEmulatedStorage(),
06-30 10:35:38.385  6240  6240 E Zygote  : v2,
06-30 10:35:38.385  1014  1536 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=6240 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
06-30 10:35:38.385  6240  6240 I libpersona: KNOX_SDCARD checking this for 10011
06-30 10:35:38.385  6240  6240 I libpersona: KNOX_SDCARD not a persona
06-30 10:35:38.385  6240  6240 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 10:35:38.385  6240  6240 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-30 10:35:38.385  6185  6185 I SA      : [SSP] onCreated
,06-30 10:35:38.395  1014  1309 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,06-30 10:35:38.395  3374  6221 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
06-30 10:35:38.395  3374  6221 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,06-30 10:35:38.395  1014  1309 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:38.395  1014  1309 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:38.395  1014  1309 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:38.395  1014  1309 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:38.395  6240  6240 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,06-30 10:35:38.395  6148  6148 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
,06-30 10:35:38.395  6148  6148 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
,06-30 10:35:38.395  6148  6148 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
06-30 10:35:38.395  3374  6221 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
06-30 10:35:38.395  6148  6148 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
06-30 10:35:38.395  6148  6148 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,06-30 10:35:38.395  6148  6148 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,06-30 10:35:38.395  6148  6148 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
06-30 10:35:38.395  6148  6148 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
06-30 10:35:38.395  6148  6148 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
,06-30 10:35:38.395  6148  6148 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
06-30 10:35:38.405  6148  6148 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,06-30 10:35:38.415  6148  6148 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,06-30 10:35:38.415  6148  6148 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,06-30 10:35:38.415  6148  6148 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
06-30 10:35:38.415  6148  6148 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
06-30 10:35:38.415  6148  6148 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
,06-30 10:35:38.415  6148  6148 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false,
06-30 10:35:38.415  6148  6148 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
06-30 10:35:38.415  6148  6148 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
06-30 10:35:38.415  6148  6148 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
06-30 10:35:38.415  6148  6148 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
06-30 10:35:38.415  6148  6148 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
06-30 10:35:38.415  6148  6148 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
06-30 10:35:38.415  6148  6148 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
06-30 10:35:38.415  6240  6240 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 10:35:38.415  6240  6240 D ActivityThread: Added TimaKeyStore provider
06-30 10:35:38.425  6254  6254 E Zygote  : MountEmulatedStorage()
06-30 10:35:38.425  6254  6254 E Zygote  : v2
06-30 10:35:38.425  6254  6254 I libpersona: KNOX_SDCARD checking this for 1000
06-30 10:35:38.425  6254  6254 I libpersona: KNOX_SDCARD not a persona
06-30 10:35:38.425  6254  6254 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-30 10:35:38.425  6254  6254 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-30 10:35:38.425  1014  1309 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6254 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
06-30 10:35:38.425  1014  1026 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,06-30 10:35:38.425  6254  6254 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
06-30 10:35:38.425  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
06-30 10:35:38.425  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 10:35:38.425  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
06-30 10:35:38.445  1014  1477 I ActivityManager: Killing 5769:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
06-30 10:35:38.455  6148  6148 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
06-30 10:35:38.455  1014  1055 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
06-30 10:35:38.455  1014  1486 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,06-30 10:35:38.465  6148  6148 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,06-30 10:35:38.465  6148  6148 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,06-30 10:35:38.475  6185  6185 I SA      : [TPM] There is no property file
,06-30 10:35:38.475  1014  1684 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,06-30 10:35:38.475  1014  1684 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:38.475  1014  1684 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:38.475  1014  1684 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:38.475  6223  6223 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
06-30 10:35:38.475  1014  1684 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:38.475  6185  6185 I SA      : [SCU] isHaveSA() - false
,06-30 10:35:38.485  6185  6185 I SA      : [TPM] getModelProperty : null,
06-30 10:35:38.485  6185  6185 I SA      : [TPM] getCSCProperty : null
06-30 10:35:38.485  6240  6240 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
06-30 10:35:38.485  6240  6240 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,06-30 10:35:38.485  6185  6185 I SA      : [DM] FLOATING AMOLED FEATURE: true
06-30 10:35:38.485  6185  6185 I SA      : [DM] PRODUCT AMOLED FEATURE: false
06-30 10:35:38.485  6185  6185 I SA      : [DM] TFT FEATURE: false
,06-30 10:35:38.485  6254  6254 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:35:38.485  1637  1647 I art     : Explicit concurrent mark sweep GC freed 10642(592KB) AllocSpace objects, 2(32KB) LOS objects, 39% free, 7MB/11MB, paused 919us total 40.751ms
06-30 10:35:38.485  6254  6254 D ActivityThread: Added TimaKeyStore provider
,06-30 10:35:38.495  6185  6185 I SA      : [DM] init START
,06-30 10:35:38.495  6274  6274 E Zygote  : MountEmulatedStorage()
06-30 10:35:38.495  6274  6274 E Zygote  : v2
06-30 10:35:38.495  6274  6274 I libpersona: KNOX_SDCARD checking this for 1000
06-30 10:35:38.495  6274  6274 I libpersona: KNOX_SDCARD not a persona
,06-30 10:35:38.495  6274  6274 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 10:35:38.505  6185  6185 I SA      : [DM] This device is not a Vodafone
,06-30 10:35:38.505  6274  6274 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-30 10:35:38.505  1014  1684 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6274 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,06-30 10:35:38.505  6274  6274 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 10:35:38.525  6034  6034 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
,06-30 10:35:38.525  6240  6240 I MultiDex: VM with version 2.1.0 has multidex support
06-30 10:35:38.525  1014  1536 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 10:35:38.525  6240  6240 I MultiDex: install
06-30 10:35:38.525  1014  1536 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.config.ConfigFetchService; callingUser = 0; userId(target) = 0
06-30 10:35:38.525  6240  6240 I MultiDex: VM has multidex support, MultiDex support library is disabled.
06-30 10:35:38.525  1014  1536 W ActivityManager: userId = 0, bbcId = -10000
06-30 10:35:38.525  1014  1536 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 10:35:38.525  1014  1536 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 10:35:38.545  1014  1076 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,06-30 10:35:38.545  6185  6185 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
06-30 10:35:38.545  6185  6185 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,06-30 10:35:38.545  6185  6185 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
06-30 10:35:38.545  1014  1076 W ActivityManager: userId = 0, bbcId = -10000,
06-30 10:35:38.545  1014  1076 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 10:35:38.545  1014  1076 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
06-30 10:35:38.545  6185  6185 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
06-30 10:35:38.545  6185  6185 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
06-30 10:35:38.545  6185  6185 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
06-30 10:35:38.545  6185  6185 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,06-30 10:35:38.555  6274  6274 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:35:38.555  1637  1637 I ConfigService: onCreate
,06-30 10:35:38.555  6185  6185 W ResourceType: No package identifier when getting value for resource number 0x00000000
,06-30 10:35:38.555  6274  6274 D ActivityThread: Added TimaKeyStore provider
06-30 10:35:38.555  6185  6185 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,06-30 10:35:38.555  6185  6185 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,06-30 10:35:38.555  6185  6185 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
06-30 10:35:38.555  6185  6185 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,06-30 10:35:38.555  6185  6185 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
06-30 10:35:38.555  6185  6185 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
06-30 10:35:38.555  6185  6185 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
06-30 10:35:38.555  6185  6185 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,06-30 10:35:38.555  6185  6185 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,06-30 10:35:38.565  6185  6185 W ResourceType: Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
,06-30 10:35:38.565  6185  6185 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
06-30 10:35:38.565  6185  6185 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,06-30 10:35:38.565  6185  6185 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
06-30 10:35:38.565  1014  3864 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
06-30 10:35:38.565  6185  6185 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,06-30 10:35:38.565  6185  6185 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
06-30 10:35:38.565  6185  6185 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,06-30 10:35:38.565  6185  6185 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
06-30 10:35:38.565  6185  6185 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
06-30 10:35:38.565  1014  3864 W ActivityManager: userId = 0, bbcId = -10000
06-30 10:35:38.565  1014  3864 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 10:35:38.565  1014  3864 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
06-30 10:35:38.565  1014  1685 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 10:35:38.565  1014  1685 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
06-30 10:35:38.565  3374  3374 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,06-30 10:35:38.565  1637  1637 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
06-30 10:35:38.565  1637  1637 I ConfigService: onBind returning update interface
,06-30 10:35:38.565  1014  1685 W ActivityManager: userId = 0, bbcId = -10000
,06-30 10:35:38.575  1014  1685 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 10:35:38.575  1014  1685 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 10:35:38.575  6185  6185 I SA      : [SCU] isHaveSA() - false
06-30 10:35:38.575  6185  6185 I SA      : support phone number id : false
06-30 10:35:38.575  6185  6185 I SA      : [DM] Supports Ref Jpn : true
06-30 10:35:38.575  6185  6185 I SA      : [DM] init END
06-30 10:35:38.575  6185  6185 I SA      : [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOJ5 PSS = 4.497050696380942  ]
,06-30 10:35:38.575  1637  1637 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
06-30 10:35:38.575  1637  1637 I ConfigService: onBind returning service broker
,06-30 10:35:38.575  6185  6185 I SA      : [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10151 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,06-30 10:35:38.575  1014  1684 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 10:35:38.575  1014  1684 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,06-30 10:35:38.585  1014  1684 W ActivityManager: userId = 0, bbcId = -10000
06-30 10:35:38.585  1014  1684 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 10:35:38.585  1014  1684 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 10:35:38.585  1014  1477 I ActivityManager: Killing 5699:com.android.mms/u0a41 (adj 15): empty #21
,06-30 10:35:38.585  1014  1329 I ActivityManager: Killing 5785:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,06-30 10:35:38.595  1014  1309 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 10:35:38.595  1014  1309 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.disconnect.FitCleanupService; callingUser = 0; userId(target) = 0
06-30 10:35:38.595  1014  1309 W ActivityManager: userId = 0, bbcId = -10000
06-30 10:35:38.595  1014  1309 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 10:35:38.595  1014  1309 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 10:35:38.595  1014  1685 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,06-30 10:35:38.605  1014  1685 W ActivityManager: userId = 0, bbcId = -10000
06-30 10:35:38.605  6240  6240 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
06-30 10:35:38.605  1014  1685 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 10:35:38.605  1014  1685 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,06-30 10:35:38.615  1014  1027 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
06-30 10:35:38.615  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
,06-30 10:35:38.615  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
06-30 10:35:38.615  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 10:35:38.615  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,06-30 10:35:38.625  6254  6297 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_REMOVED
,06-30 10:35:38.625  3374  3374 I ConfigFetchService: service connected
,06-30 10:35:38.625  3374  6298 I PeopleContactsSync: CP2 sync disabled
,06-30 10:35:38.635  1014  1486 D CountryDetector: No listener is left
,06-30 10:35:38.635  1014  1685 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,06-30 10:35:38.635  1014  1685 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,06-30 10:35:38.635  6254  6297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,06-30 10:35:38.635  1014  1685 W ActivityManager: userId = 0, bbcId = -10000
06-30 10:35:38.635  1014  1685 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 10:35:38.635  1014  1685 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
06-30 10:35:38.635  6274  6274 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
06-30 10:35:38.635  6274  6274 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
06-30 10:35:38.635  6274  6274 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,06-30 10:35:38.645  3374  6296 W DatabaseHelper: Upgrading database /data/data/com.google.android.gms/databases/DocList.db from version 43 to 88 databaseName=DocList.db
,06-30 10:35:38.645  1014  1519 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,06-30 10:35:38.645  1014  1519 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,06-30 10:35:38.645  1014  1519 W ActivityManager: userId = 0, bbcId = -10000
06-30 10:35:38.645  1014  1519 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 10:35:38.645  1014  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,06-30 10:35:38.655  6254  6254 D AcmsService: Enter Oncreate
,06-30 10:35:38.655  6254  6254 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
06-30 10:35:38.655  6254  6254 D AcmsService: creating AcmsCore
06-30 10:35:38.655  1014  1309 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 10:35:38.655  6254  6254 D AcmsCore: AcmsCore.getAcmsCore() - Enter
06-30 10:35:38.655  1014  1309 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
06-30 10:35:38.655  6254  6254 D AcmsCore: AcmsCore
,06-30 10:35:38.655  1014  1309 W ActivityManager: userId = 0, bbcId = -10000
,06-30 10:35:38.655  1014  1309 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,06-30 10:35:38.655  3374  6296 E SQLiteLog: (10) unixWrite() File Descriptor : 101 gets errno : 9
06-30 10:35:38.655  3374  6296 E SQLiteLog: (778) statement aborts at 16: [DROP VIEW "InternalCachedContentSizeView"] 
06-30 10:35:38.655  3374  6296 E SQLiteLog: (10) unixWrite() File Descriptor : 101 gets errno : 9
,06-30 10:35:38.655  1014  1309 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 10:35:38.655  6254  6254 D AcmsCore: init
06-30 10:35:38.655  6254  6254 D AcmsCore: Looper handler is not null
06-30 10:35:38.655  6254  6254 D AcmsCore: Post to AcmsCoreHandler
06-30 10:35:38.655  6254  6254 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
06-30 10:35:38.655  6254  6254 D AcmsServiceMonitor: Incrementing - Counter value: 1
06-30 10:35:38.655  6254  6254 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>1
,06-30 10:35:38.665  6254  6254 D AcmsService: onStartCommand
06-30 10:35:38.665  6254  6254 D AcmsService: Action: android.intent.action.PACKAGE_REMOVED
06-30 10:35:38.665  6254  6254 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 1
06-30 10:35:38.665  6254  6254 D AcmsServiceMonitor: Incrementing - Counter value: 2
06-30 10:35:38.665  6254  6254 D AcmsService: Incremented Counter Value : onStartCommand
,06-30 10:35:38.665  1014  1536 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,06-30 10:35:38.665  1014  1536 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:38.665  1014  1536 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:38.665  6254  6302 D AcmsCertificateMngr: AcmsCertificateMngr
06-30 10:35:38.665  1014  1536 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:38.665  1014  1536 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:38.665  3374  6296 E DatabaseHelper: An exception occurred during database upgrade.
06-30 10:35:38.665  3374  6296 E DatabaseHelper: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
06-30 10:35:38.665  3374  6296 E DatabaseHelper: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
06-30 10:35:38.665  3374  6296 E DatabaseHelper: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
06-30 10:35:38.665  3374  6296 E DatabaseHelper: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
06-30 10:35:38.665  3374  6296 E DatabaseHelper: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
06-30 10:35:38.665  3374  6296 E DatabaseHelper: 	at android.database.sqlite.SQLiteDatabase.executeSql(SQLiteDatabase.java:1814)
06-30 10:35:38.665  3374  6296 E DatabaseHelper: 	at android.database.sqlite.SQLiteDatabase.execSQL(SQLiteDatabase.java:1743)
06-30 10:35:38.665  3374  6296 E DatabaseHelper: 	at com.google.android.gms.drive.database.a.b(SourceFile:340)
06-30 10:35:38.665  3374  6296 E DatabaseHelper: 	at com.google.android.gms.drive.database.a.a(SourceFile:191)
06-30 10:35:38.665  3374  6296 E DatabaseHelper: 	at com.google.android.gms.drive.database.a.onUpgrade(SourceFile:162)
06-30 10:35:38.665  3374  6296 E DatabaseHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:256)
06-30 10:35:38.665  3374  6296 E DatabaseHelper: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 10:35:38.665  3374  6296 E DatabaseHelper: 	at com.google.android.gms.drive.database.a.getWritableDatabase(SourceFile:226)
06-30 10:35:38.665  3374  6296 E DatabaseHelper: 	at com.google.android.gms.drive.database.k.b(SourceFile:610)
06-30 10:35:38.665  3374  6296 E DatabaseHelper: 	at com.google.android.gms.drive.database.k.a(SourceFile:604)
06-30 10:35:38.665  3374  6296 E DatabaseHelper: 	at com.google.android.gms.drive.database.m.run(SourceFile:625)
06-30 10:35:38.665  3374  6296 W DatabaseHelper: Database upgrade completed in 22 ms
06-30 10:35:38.665  3374  6296 E SQLiteLog: (1) statement aborts at 2: [ROLLBACK;] cannot rollback - no transaction is active
,06-30 10:35:38.665  3374  6296 E AndroidRuntime: FATAL EXCEPTION: Open database in background
06-30 10:35:38.665  3374  6296 E AndroidRuntime: Process: com.google.android.gms, PID: 3374
06-30 10:35:38.665  3374  6296 E AndroidRuntime: android.database.sqlite.SQLiteException: cannot rollback - no transaction is active (code 1)
06-30 10:35:38.665  3374  6296 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
06-30 10:35:38.665  3374  6296 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
06-30 10:35:38.665  3374  6296 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:439)
06-30 10:35:38.665  3374  6296 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
06-30 10:35:38.665  3374  6296 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:527)
06-30 10:35:38.665  3374  6296 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:262)
06-30 10:35:38.665  3374  6296 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 10:35:38.665  3374  6296 E AndroidRuntime: 	at com.google.android.gms.drive.database.a.getWritableDatabase(SourceFile:226)
06-30 10:35:38.665  3374  6296 E AndroidRuntime: 	at com.google.android.gms.drive.database.k.b(SourceFile:610)
06-30 10:35:38.665  3374  6296 E AndroidRuntime: 	at com.google.android.gms.drive.database.k.a(SourceFile:604)
06-30 10:35:38.665  3374  6296 E AndroidRuntime: 	at com.google.android.gms.drive.database.m.run(SourceFile:625)
06-30 10:35:38.665  6254  6302 D AcmsRevocationMngr: AcmsRevocationMngr
06-30 10:35:38.675  3374  3866 I Icing   : doRemovePackageData com.test.thalitest
06-30 10:35:38.675  6274  6274 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
06-30 10:35:38.675  6274  6274 I PCWCLIENTTRACE_PushUtil: sales region : global
06-30 10:35:38.675  6274  6274 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
06-30 10:35:38.675  6274  6274 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
06-30 10:35:38.675  6304  6304 E Zygote  : MountEmulatedStorage()
06-30 10:35:38.675  6304  6304 I libpersona: KNOX_SDCARD checking this for 10039
06-30 10:35:38.675  6304  6304 E Zygote  : v2
06-30 10:35:38.675  6304  6304 I libpersona: KNOX_SDCARD not a persona
06-30 10:35:38.675  6304  6304 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-30 10:35:38.685  1014  1536 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6304 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
06-30 10:35:38.685  1014  1684 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
06-30 10:35:38.685  6304  6304 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-30 10:35:38.685  1014  1685 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gms
06-30 10:35:38.685  6254  6254 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
06-30 10:35:38.685  6304  6304 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
06-30 10:35:38.685  1014  1477 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
06-30 10:35:38.685  1014  1477 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
06-30 10:35:38.695  1014  1477 W ActivityManager: userId = 0, bbcId = -10000
06-30 10:35:38.695  1014  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 10:35:38.695  1014  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
06-30 10:35:38.695  6223  6293 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,06-30 10:35:38.705  1014  1536 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
06-30 10:35:38.705  1014  1536 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:38.705  1014  1536 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:38.705  1014  1536 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:38.705  1014  1536 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:38.715  6304  6304 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 10:35:38.715  6304  6304 D ActivityThread: Added TimaKeyStore provider
06-30 10:35:38.725  6223  6223 I art     : Explicit concurrent mark sweep GC freed 4209(223KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 4MB/6MB, paused 1.143ms total 101.594ms
06-30 10:35:38.725  6321  6321 E Zygote  : MountEmulatedStorage()
06-30 10:35:38.725  6321  6321 I libpersona: KNOX_SDCARD checking this for 1000
06-30 10:35:38.725  6321  6321 E Zygote  : v2
06-30 10:35:38.725  6321  6321 I libpersona: KNOX_SDCARD not a persona
06-30 10:35:38.725  6321  6321 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-30 10:35:38.735  6321  6321 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-30 10:35:38.735  1014  1536 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=6321 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
06-30 10:35:38.735  6321  6321 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
06-30 10:35:38.735  3374  6286 W BaseAppContext: Using Auth Proxy for data requests.
,06-30 10:35:38.745  6072  6129 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
06-30 10:35:38.745  6072  6129 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,06-30 10:35:38.755  1014  1027 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.sm, calleePkgName: com.sec.android.provider.badge
,06-30 10:35:38.755  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:38.755  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:38.755  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:38.755  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:38.755  6072  6129 E AppDataSearchHelper: Exception thrown from onTableChanged
06-30 10:35:38.755  6072  6129 E AppDataSearchHelper: java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
06-30 10:35:38.755  6072  6129 E AppDataSearchHelper: 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:343)
06-30 10:35:38.755  6072  6129 E AppDataSearchHelper: 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:261)
06-30 10:35:38.755  6072  6129 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.w.j(InternalIcingCorporaProvider.java:661)
06-30 10:35:38.755  6072  6129 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.w.a(InternalIcingCorporaProvider.java:652)
06-30 10:35:38.755  6072  6129 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.w.g(InternalIcingCorporaProvider.java:590)
06-30 10:35:38.755  6072  6129 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:290)
06-30 10:35:38.755  6072  6129 E AppDataSearchHelper: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:340)
06-30 10:35:38.755  6072  6129 E AppDataSearchHelper: 	at android.content.ContentResolver.update(ContentResolver.java:1386)
06-30 10:35:38.755  6072  6129 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.z.amO(UpdateIcingCorporaService.java:358)
06-30 10:35:38.755  6072  6129 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.ab.amQ(UpdateIcingCorporaService.java:297)
06-30 10:35:38.755  6072  6129 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:270)
06-30 10:35:38.755  6072  6129 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.aF(UpdateIcingCorporaService.java:194)
06-30 10:35:38.755  6072  6129 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:182)
06-30 10:35:38.755  6072  6129 E AppDataSearchHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-30 10:35:38.755  6072  6129 E AppDataSearchHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:35:38.755  6072  6129 E AppDataSearchHelper: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:35:38.755  6072  6129 E AppDataSearchHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:35:38.755  6072  6129 E AppDataSearchHelper: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
06-30 10:35:38.755  6072  6129 E AppDataSearchHelper: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
06-30 10:35:38.755  6072  6129 E AppDataSearchHelper: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
06-30 10:35:38.755  6072  6129 E AppDataSearchHelper: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
06-30 10:35:38.755  6072  6129 E AppDataSearchHelper: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
06-30 10:35:38.755  6072  6129 E AppDataSearchHelper: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
06-30 10:35:38.755  6072  6129 E AppDataSearchHelper: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
06-30 10:35:38.755  6072  6129 E AppDataSearchHelper: 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:661)
06-30 10:35:38.755  6072  6129 E AppDataSearchHelper: 	at com.google.android.gms.appdatasearch.a.b.amO(AppDataSearchDbOpenHelperBase.java:246)
06-30 10:35:38.755  6072  6129 E AppDataSearchHelper: 	at com.google.android.gms.appdatasearch.a.b.call(AppDataSearchDbOpenHelperBase.java:227)
06-30 10:35:38.755  6072  6129 E AppDataSearchHelp,er: 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:341)
06-30 10:35:38.755  6072  6129 E AppDataSearchHelper: 	... 16 more
06-30 10:35:38.755  6072  6129 W AppDataSearchHelper: Table change notification failed for com.google.android.gms.appdatasearch.a.k@be7fd6a1
06-30 10:35:38.755  6072  6129 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 418 ms] updated apps [took 418 ms] 
,06-30 10:35:38.765  6321  6321 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:35:38.765  6321  6321 D ActivityThread: Added TimaKeyStore provider
,06-30 10:35:38.765  3374  6218 E SQLiteLog: (2570) os_unix.c:32652: (30) unlink(/data/data/com.google.android.gms/databases/DocList.db-journal) - 
06-30 10:35:38.765  3374  6218 E SQLiteLog: (10) os_unix.c:32667: (30) rename(/data/data/com.google.android.gms/databases/DocList.db-journal.bak) - 
06-30 10:35:38.765  3374  6218 E SQLiteLog: (539) recovered 5 pages from /data/data/com.google.android.gms/databases/DocList.db-journal
06-30 10:35:38.765  3374  6218 E SQLiteLog: (2570) disk I/O error
,06-30 10:35:38.765  6254  6254 D AcmsService: Inside handle Intent
06-30 10:35:38.765  6254  6254 D AcmsService: App removed - package name: com.test.thalitest
06-30 10:35:38.765  6254  6254 D AcmsCore: Post to AcmsCoreHandler
06-30 10:35:38.765  6254  6254 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
06-30 10:35:38.765  6254  6254 D AcmsServiceMonitor: Incrementing - Counter value: 3
06-30 10:35:38.765  6254  6254 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>5
06-30 10:35:38.765  6254  6254 D AcmsService: Decremented Counter Value : handleStartIntent
06-30 10:35:38.765  6254  6254 D AcmsServiceMonitor: Decrementing - Counter value: 2
,06-30 10:35:38.775  3374  6218 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
06-30 10:35:38.775  3374  6218 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570): , while compiling: PRAGMA journal_mode
06-30 10:35:38.775  3374  6218 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
06-30 10:35:38.775  3374  6218 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1093)
06-30 10:35:38.775  3374  6218 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:804)
06-30 10:35:38.775  3374  6218 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.setJournalMode(SQLiteConnection.java:490)
06-30 10:35:38.775  3374  6218 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.setWalModeFromConfiguration(SQLiteConnection.java:464)
06-30 10:35:38.775  3374  6218 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:363)
06-30 10:35:38.775  3374  6218 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
06-30 10:35:38.775  3374  6218 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
06-30 10:35:38.775  3374  6218 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
06-30 10:35:38.775  3374  6218 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
06-30 10:35:38.775  3374  6218 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
06-30 10:35:38.775  3374  6218 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
06-30 10:35:38.775  3374  6218 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
06-30 10:35:38.775  3374  6218 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
06-30 10:35:38.775  3374  6218 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
06-30 10:35:38.775  3374  6218 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 10:35:38.775  3374  6218 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 10:35:38.775  3374  6218 E SQLiteDatabase: 	at com.google.android.gms.drive.database.a.getWritableDatabase(SourceFile:226)
06-30 10:35:38.775  3374  6218 E SQLiteDatabase: 	at com.google.android.gms.drive.database.k.b(SourceFile:610)
06-30 10:35:38.775  3374  6218 E SQLiteDatabase: 	at com.google.android.gms.drive.database.k.a(SourceFile:604)
06-30 10:35:38.775  3374  6218 E SQLiteDatabase: 	at com.google.android.gms.drive.database.i.a(SourceFile:238)
06-30 10:35:38.775  3374  6218 E SQLiteDatabase: 	at com.google.android.gms.drive.database.i.a(SourceFile:417)
06-30 10:35:38.775  3374  6218 E SQLiteDatabase: 	at com.google.android.gms.drive.database.i.a(SourceFile:404)
06-30 10:35:38.775  3374  6218 E SQLiteDatabase: 	at com.google.android.gms.drive.database.d.a(SourceFile:2197)
06-30 10:35:38.775  3374  6218 E SQLiteDatabase: 	at com.google.android.gms.drive.events.ao.a(SourceFile:109)
06-30 10:35:38.775  3374  6218 E SQLiteDatabase: 	at com.google.android.gms.drive.events.ao.<init>(SourceFile:102)
06-30 10:35:38.775  3374  6218 E SQLiteDatabase: 	at com.google.android.gms.drive.g.aw.<init>(SourceFile:155)
06-30 10:35:38.775  3374  6218 E SQLiteDatabase: 	at com.google.android.gms.drive.g.aw.a(SourceFile:113)
06-30 10:35:38.775  3374  6218 E SQLiteDatabase: 	at com.google.android.gms.drive.q.<init>(SourceFile:46)
06-30 10:35:38.775  3374  6218 E SQLiteDatabase: 	at com.google.android.gms.drive.q.a(SourceFile:105)
06-30 10:35:38.775  3374  6218 E SQLiteDatab,ase: 	at com.google.android.gms.drive.q.b(SourceFile:119)
06-30 10:35:38.775  3374  6218 E SQLiteDatabase: 	at com.google.android.gms.drive.api.a.az.a(SourceFile:16)
06-30 10:35:38.775  3374  6218 E SQLiteDatabase: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
06-30 10:35:38.775  3374  6218 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
06-30 10:35:38.775  3374  6218 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
06-30 10:35:38.775  3374  6218 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
06-30 10:35:38.775  3374  6218 E DocListDatabase: Failed to query Subscription88 object
06-30 10:35:38.775  3374  6218 E DocListDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570): , while compiling: PRAGMA journal_mode
06-30 10:35:38.775  3374  6218 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
06-30 10:35:38.775  3374  6218 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1093)
06-30 10:35:38.775  3374  6218 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:804)
06-30 10:35:38.775  3374  6218 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.setJournalMode(SQLiteConnection.java:490)
06-30 10:35:38.775  3374  6218 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.setWalModeFromConfiguration(SQLiteConnection.java:464)
06-30 10:35:38.775  3374  6218 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:363)
06-30 10:35:38.775  3374  6218 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
06-30 10:35:38.775  3374  6218 E DocListDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
06-30 10:35:38.775  3374  6218 E DocListDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
06-30 10:35:38.775  3374  6218 E DocListDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
06-30 10:35:38.775  3374  6218 E DocListDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
06-30 10:35:38.775  3374  6218 E DocListDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
06-30 10:35:38.775  3374  6218 E DocListDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
06-30 10:35:38.775  3374  6218 E DocListDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
06-30 10:35:38.775  3374  6218 E DocListDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
06-30 10:35:38.775  3374  6218 E DocListDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 10:35:38.775  3374  6218 E DocListDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 10:35:38.775  3374  6218 E DocListDatabase: 	at com.google.android.gms.drive.database.a.getWritableDatabase(SourceFile:226)
06-30 10:35:38.775  3374  6218 E DocListDatabase: 	at com.google.android.gms.drive.database.k.b(SourceFile:610)
06-30 10:35:38.775  3374  6218 E DocListDatabase: 	at com.google.android.gms.drive.database.k.a(SourceFile:604)
06-30 10:35:38.775  3374  6218 E DocListDatabase: ,	at com.google.android.gms.drive.database.i.a(SourceFile:238)
06-30 10:35:38.775  3374  6218 E DocListDatabase: 	at com.google.android.gms.drive.database.i.a(SourceFile:417)
06-30 10:35:38.775  3374  6218 E DocListDatabase: ,	at com.google.android.gms.drive.database.i.a(SourceFile:404)
06-30 10:35:38.775  3374  6218 E DocListDatabase: 	at com.google.android.gms.drive.database.d.a(SourceFile:2197)
06-30 10:35:38.775  3374  6218 E DocListDatabase: 	at com.google.android.gms.drive.events.ao.a(SourceFile:109)
06-30 10:35:38.775  3374  6218 E DocListDatabase: 	at com.google.android.gms.drive.events.ao.<init>(SourceFile:102)
06-30 10:35:38.775  3374  6218 E DocListDatabase: 	at com.google.android.gms.drive.g.aw.<init>(SourceFile:155)
06-30 10:35:38.775  3374  6218 E DocListDatabase: 	at com.google.android.gms.drive.g.aw.a(SourceFile:113)
06-30 10:35:38.775  3374  6218 E DocListDatabase: 	at com.google.android.gms.drive.q.<init>(SourceFile:46)
06-30 10:35:38.775  3374  6218 E DocListDatabase: 	at com.google.android.gms.drive.q.a(SourceFile:105)
06-30 10:35:38.775  3374  6218 E DocListDatabase: 	at com.google.android.gms.drive.q.b(SourceFile:119),
06-30 10:35:38.775  3374  6218 E DocListDatabase: 	at com.google.android.gms.drive.api.a.az.a(SourceFile:16)
06-30 10:35:38.775  3374  6218 E DocListDatabase: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
06-30 10:35:38.775  3374  6218 E DocListDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
06-30 10:35:38.775  3374  6218 E DocListDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
06-30 10:35:38.775  3374  6218 E DocListDatabase: 	at java.lang.Thread.run(Thread.java:818)
06-30 10:35:38.775  3374  6218 E DriveAsyncService: disk I/O error (code 2570): , while compiling: PRAGMA journal_mode,
06-30 10:35:38.775  3374  6218 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570): , while compiling: PRAGMA journal_mode
06-30 10:35:38.775  3374  6218 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
06-30 10:35:38.775  3374  6218 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1093)
06-30 10:35:38.775  3374  6218 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:804)
06-30 10:35:38.775  3374  6218 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.setJournalMode(SQLiteConnection.java:490)
06-30 10:35:38.775  3374  6218 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.setWalModeFromConfiguration(SQLiteConnection.java:464)
06-30 10:35:38.775  3374  6218 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:363)
06-30 10:35:38.775  3374  6218 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
06-30 10:35:38.775  3374  6218 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
06-30 10:35:38.775  3374  6218 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
06-30 10:35:38.775  3374  6218 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
06-30 10:35:38.775  3374  6218 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
06-30 10:35:38.775  3374  6218 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
06-30 10:35:38.775  3374  6218 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
06-30 10:35:38.775  3374  6218 E DriveAsyncService: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
06-30 10:35:38.775  3374  6218 E DriveAsyncService: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
06-30 10:35:38.775  3374  6218 E DriveAsyncService: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 10:35:38.775  3374  6218 E DriveAsyncService: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 10:35:38.775  3374  6218 E DriveAsyncService: 	at com.google.android.gms.drive.database.a.getWritableDatabase(SourceFile:226)
06-30 10:35:38.775  3374  6218 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.b(SourceFile:610)
06-30 10:35:38.775  3374  6218 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.a(SourceFile:604)
06-30 10:35:38.775  3374  6218 E DriveAsyncService: 	at com.google.android.gms.drive.database.i.a(SourceFile:238)
06-30 10:35:38.775  3374  6218 E DriveAsyncService: 	at com.google.android.gms.drive.database.i.a(SourceFile:417)
06-30 10:35:38.775  3374  6218 E DriveAsyncService: 	at com.google.android.gms.drive.database.i.a(SourceFile:404)
06-30 10:35:38.775  3374  6218 E DriveAsyncService: 	,at com.google.android.gms.drive.database.d.a(SourceFile:2197)
06-30 10:35:38.775  3374  6218 E DriveAsyncService: 	at com.google.android.gms.drive.events.ao.a(SourceFile:109)
06-30 10:35:38.775  3374  6218 E DriveAsyncService: 	at com.google.android.gms.drive.events.ao.<init>(SourceFile:102)
06-30 10:35:38.775  3374  6218 E DriveAsyncService: 	at com.google.android.gms.drive.g.aw.<init>(SourceFile:155)
06-30 10:35:38.775  3374  6218 E DriveAsyncService: 	at com.google.android.gms.drive.g.aw.a(SourceFile:113)
06-30 10:35:38.775  3374  6218 E DriveAsyncService: 	at com.google.android.gms.drive.q.<init>(SourceFile:46)
06-30 10:35:38.775  3374  6218 E DriveAsyncService: 	at com.google.android.gms.drive.q.a(SourceFile:105)
06-30 10:35:38.775  3374  6218 E DriveAsyncService: 	at com.google.android.gms.drive.q.b(SourceFile:119)
06-30 10:35:38.775  3374  6218 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.az.a(SourceFile:16)
06-30 10:35:38.775  3374  6218 E DriveAsyncService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
06-30 10:35:38.775  3374  6218 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
06-30 10:35:38.775  3374  6218 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
06-30 10:35:38.775  3374  6218 E DriveAsyncService: 	at java.lang.Thread.run(Thread.java:818)
06-30 10:35:38.775  6304  6304 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
06-30 10:35:38.775  6304  6304 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 10:35:38.785  3374  6296 I Process : Sending signal. PID: 3374 SIG: 9
06-30 10:35:38.775  6304  6304 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
06-30 10:35:38.785  6336  6336 E Zygote  : MountEmulatedStorage()
06-30 10:35:38.775  6304  6304 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
06-30 10:35:38.785  6336  6336 E Zygote  : v2
06-30 10:35:38.775  6304  6304 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
06-30 10:35:38.785  6336  6336 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-30 10:35:38.775  6304  6304 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
06-30 10:35:38.775  6304  6304 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
06-30 10:35:38.775  1014  1027 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6336 uid=10068 gids={50068, 9997} abi=armeabi-v7a
06-30 10:35:38.785  6336  6336 I libpersona: KNOX_SDCARD checking this for 10068
06-30 10:35:38.785  6336  6336 I libpersona: KNOX_SDCARD not a persona
06-30 10:35:38.785  6336  6336 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-30 10:35:38.785   314   314 I ServiceManager: Waiting for service AtCmdFwd...
06-30 10:35:38.785  6336  6336 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
06-30 10:35:38.785   254   254 E lowmemorykiller: Error writing /proc/3374/oom_score_adj; errno=22
06-30 10:35:38.785   287   287 E SMD     : DCD OFF
,06-30 10:35:38.795  1014  1014 D CrashAnrDetector: processName: com.google.android.gms
06-30 10:35:38.795  1014  1014 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
06-30 10:35:38.795  1014  1014 D CrashAnrDetector: broadcastEvent : com.google.android.gms system_app_crash
,06-30 10:35:38.805  1014  1026 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,06-30 10:35:38.805  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:38.805  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:38.805  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:38.805  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:38.815  6336  6336 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 10:35:38.815  6336  6336 D ActivityThread: Added TimaKeyStore provider
,06-30 10:35:38.815  6352  6352 E Zygote  : MountEmulatedStorage()
06-30 10:35:38.815  6352  6352 I libpersona: KNOX_SDCARD checking this for 10029
06-30 10:35:38.815  6352  6352 E Zygote  : v2
06-30 10:35:38.815  6352  6352 I libpersona: KNOX_SDCARD not a persona
06-30 10:35:38.815  6352  6352 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 10:35:38.825  6352  6352 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
06-30 10:35:38.825  6352  6352 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
06-30 10:35:38.825  1014  1026 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6352 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
06-30 10:35:38.825   254   254 E lowmemorykiller: Error writing /proc/3374/oom_score_adj; errno=22
06-30 10:35:38.825  1014  1026 I ActivityManager: Killing 5814:com.wsomacp/u0a23 (adj 15): empty #21
06-30 10:35:38.825  1014  1026 I ActivityManager: Killing 5830:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,06-30 10:35:38.825  1014  1026 I ActivityManager: Killing 5846:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,06-30 10:35:38.835  1014  1026 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,06-30 10:35:38.835  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:38.835  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:38.845  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:38.845  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0

```
