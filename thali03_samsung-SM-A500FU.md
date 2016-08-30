#### Test 7976383051d2164_thali03_samsung-SM-A500FU Logs


```
--------- beginning of main
08-30 11:36:35.294   290   290 E SMD     : DCD OFF
,08-30 11:36:35.894  6301  6301 D AndroidRuntime: 
08-30 11:36:35.894  6301  6301 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-30 11:36:35.894  6301  6301 D AndroidRuntime: CheckJNI is OFF
08-30 11:36:35.894  6301  6301 D AndroidRuntime: readGMSProperty: start
08-30 11:36:35.894  6301  6301 D AndroidRuntime: readGMSProperty: already setted!!
08-30 11:36:35.894  6301  6301 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-30 11:36:35.894  6301  6301 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-30 11:36:35.894  6301  6301 D AndroidRuntime: readGMSProperty: end
08-30 11:36:35.894  6301  6301 D AndroidRuntime: addProductProperty: start
08-30 11:36:36.034  6301  6301 E AffinityControl: AffinityControl: registerfunction enter
08-30 11:36:36.064  6301  6301 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-30 11:36:36.074  1017  1497 E PersonaManagerService: inState():  stateMachine is null !!
08-30 11:36:36.074  1017  1497 I PersonaManagerService: PersonaId don't exist
08-30 11:36:36.074  1017  1497 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-30 11:36:36.074  1017  1497 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
08-30 11:36:36.084  1017  1497 W ActivityManager: mDVFSHelper.acquire()
08-30 11:36:36.094  1017  1048 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-30 11:36:36.094  1017  1048 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-30 11:36:36.104  1017  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:36.104  1017  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:36.104  1017  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:36.104  1017  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:36.114  6312  6312 E Zygote  : MountEmulatedStorage()
08-30 11:36:36.114  6312  6312 E Zygote  : v2
08-30 11:36:36.114  6312  6312 I libpersona: KNOX_SDCARD checking this for 10155
08-30 11:36:36.114  6312  6312 I libpersona: KNOX_SDCARD not a persona
08-30 11:36:36.114  1017  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-30 11:36:36.114  1017  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-30 11:36:36.114   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
08-30 11:36:36.124  1017  1497 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
08-30 11:36:36.124  1017  1497 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6312 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-30 11:36:36.124  1017  1497 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-30 11:36:36.124  6312  6312 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-30 11:36:36.124  1017  1497 D InputDispatcher: Focused application set to: xxxx
08-30 11:36:36.124  1017  1497 D InputDispatcher: Focus left window: 3173
08-30 11:36:36.124  6301  6301 D AndroidRuntime: Shutting down VM
08-30 11:36:36.134  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-30 11:36:36.134  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-30 11:36:36.134  6312  6312 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-30 11:36:36.134  6312  6312 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-30 11:36:36.154  6312  6312 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 11:36:36.164  6312  6312 D ActivityThread: Added TimaKeyStore provider
08-30 11:36:36.164  1017  1017 V ActivityManager: Display changed displayId=0
08-30 11:36:36.174  1017  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-30 11:36:36.184  1017  1560 D PersonaManager: isKioskContainerExistOnDevice
08-30 11:36:36.214   257   439 I SurfaceFlinger: id=11 Removed YUIInstallC (5/9)
08-30 11:36:36.214   257   431 I SurfaceFlinger: id=11 Removed YUIInstallC (-2/9)
08-30 11:36:36.224  3173  3173 V ActivityThread: updateVisibility : ActivityRecord{28da4f18 token=android.os.BinderProxy@384f5f4f {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
08-30 11:36:36.274   319   319 I ServiceManager: Waiting for service AtCmdFwd...
08-30 11:36:36.304  6312  6312 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
08-30 11:36:36.314  6312  6312 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 3925-3927)
08-30 11:36:36.314  6312  6312 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 11:36:36.334  6301  6301 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-30 11:36:36.344  6312  6312 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2a6a6c54}
,08-30 11:36:36.344  6312  6312 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 11:36:36.344  6312  6312 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,08-30 11:36:36.384  6312  6312 I BrowserStartupController: Initializing chromium process, singleProcess=true,
,08-30 11:36:36.384  6312  6312 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,08-30 11:36:36.384  6312  6312 E SysUtils: ApplicationContext is null in ApplicationStatus,
,08-30 11:36:36.404  6312  6312 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,08-30 11:36:36.404  6312  6312 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,08-30 11:36:36.404  6312  6312 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,08-30 11:36:36.404  6312  6312 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-30 11:36:36.404  6312  6312 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-30 11:36:36.404  6312  6312 I Adreno-EGL: Build Date: 04/06/15 Mon
08-30 11:36:36.404  6312  6312 I Adreno-EGL: Local Branch: 
08-30 11:36:36.404  6312  6312 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-30 11:36:36.404  6312  6312 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-30 11:36:36.404  6312  6312 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-30 11:36:36.524  6312  6338 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,08-30 11:36:36.574  6312  6312 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 11:36:36.584  6312  6312 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-30 11:36:36.594  6312  6312 D PhoneWindow: *FMB* installDecor mIsFloating : false
,08-30 11:36:36.594  6312  6312 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-30 11:36:36.604  6312  6312 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-30 11:36:36.604  6312  6312 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 11:36:36.604  6312  6312 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 11:36:36.644  6312  6351 D OpenGLRenderer: Render dirty regions requested: true
,08-30 11:36:36.654  1017  1501 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-30 11:36:36.654  1017  1501 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-30 11:36:36.654  1017  1501 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-30 11:36:36.654  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-30 11:36:36.654  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,08-30 11:36:36.664  6312  6312 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-30 11:36:36.664  6312  6312 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-30 11:36:36.674   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
,08-30 11:36:36.684  1017  3289 D InputDispatcher: Focus entered window: 6312
,08-30 11:36:36.694  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-30 11:36:36.694  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-30 11:36:36.694  6312  6312 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-30 11:36:36.694  6312  6351 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 11:36:36.694  6312  6351 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,08-30 11:36:36.694  6312  6351 D OpenGLRenderer: Enabling debug mode 0
,08-30 11:36:36.724  6312  6312 V ActivityThread: updateVisibility : ActivityRecord{345c0b8f token=android.os.BinderProxy@545a069 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-30 11:36:36.764  1017  1477 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-30 11:36:36.764  1177  1177 D PanelView: There is/are notification(s) 
,08-30 11:36:36.774  1017  6354 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-30 11:36:36.774  1770  1770 I SamsungIME: getCurrentCandidateView
,08-30 11:36:36.784  1017  1048 I ActivityManager: Displayed Component not be shown by security: +589ms (total +682ms)
,08-30 11:36:36.784  1017  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{272c9f86 u0 com.test.thalitest/.MainActivity t128} time:114392
08-30 11:36:36.784  1017  1048 W ActivityManager: mDVFSHelper.release()
,08-30 11:36:36.784   257   431 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
,08-30 11:36:36.784   257  1039 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
,08-30 11:36:36.794  6312  6312 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection,
08-30 11:36:36.794  6312  6312 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@545a069 time:114402
,08-30 11:36:36.834  6312  6312 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6312
,08-30 11:36:36.864  1770  1770 D SamsungIME: Dismiss ExpandCandiate
,08-30 11:36:36.964  6312  6312 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 11:36:37.014  1770  1770 I SamsungIME: getDebugLevel  : 0x4f4c
,08-30 11:36:37.054  1770  1770 I SamsungIME: getDebugLevel  : 0x4f4c
,08-30 11:36:37.064  1770  1770 I SamsungIME: KeybaordView init() : load resources
,08-30 11:36:37.084  6312  6355 D jxcore_app_log: JniHelper::setJavaVM(0xb8e4e328), pthread_self() = -1187306560
,08-30 11:36:37.084  6312  6355 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 11:36:37.084  6312  6355 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 11:36:37.084  6312  6355 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 11:36:37.084  6312  6355 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 11:36:37.084  6312  6355 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-30 11:36:37.084  6312  6355 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c1cf67f added. We now have 1 listener(s)
,08-30 11:36:37.094  1770  1770 I SamsungIME: getCurrentKeyboard
08-30 11:36:37.094  1770  1770 I SamsungIME: getTextKeyboard
,08-30 11:36:37.094  6312  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,08-30 11:36:37.094  6312  6355 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-30 11:36:37.094  6312  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 11:36:37.094  6312  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 11:36:37.104  6312  6355 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 11:36:37.104  6312  6355 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 11:36:37.104  6312  6355 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 11:36:37.104  6312  6355 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
08-30 11:36:37.104  6312  6355 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 11:36:37.104  6312  6355 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 11:36:37.104  6312  6355 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 11:36:37.104  6312  6355 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 11:36:37.104  6312  6355 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 11:36:37.104  6312  6355 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 11:36:37.104  6312  6355 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 11:36:37.104  6312  6355 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 11:36:37.104  6312  6355 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 11:36:37.104  6312  6355 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 11:36:37.104  6312  6355 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@886b3aa added. We now have 1 listener(s)
08-30 11:36:37.104  6312  6355 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 11:36:37.104  6312  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 11:36:37.104  6312  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-30 11:36:37.104  6312  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 11:36:37.104  6312  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 11:36:37.114  6312  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-30 11:36:37.114  1770  1770 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-30 11:36:37.114  6312  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 11:36:37.114  6312  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,08-30 11:36:37.124  6312  6355 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-30 11:36:37.124  6312  6355 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 11:36:37.124  6312  6355 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:36:37.124  6312  6355 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:36:37.124  6312  6355 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:36:37.124  6312  6355 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:36:37.124  6312  6355 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 11:36:37.124  6312  6355 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 11:36:37.124  6312  6355 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 11:36:37.124  6312  6355 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 11:36:37.124  6312  6355 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 11:36:37.124  6312  6355 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-30 11:36:37.124  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:36:37.134  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:36:37.164  6312  6312 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 11:36:37.284   319   319 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 11:36:37.644  1770  6361 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-30 11:36:37.684  6312  6364 W jxcore-log: Initializing JXcore engine
08-30 11:36:37.684  6312  6364 W jxcore-log: JXcore engine is ready
,08-30 11:36:37.744  1906  1906 E audit   : type=1400 msg=audit(1472549797.744:205): avc:  denied  { ioctl } for  pid=6364 comm="Thread-1083" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-30 11:36:37.744  1906  1906 E audit   :  SEPF_SM-A500FU_5.0.2-1_0051
08-30 11:36:37.744  1906  1906 E audit   : type=1300 msg=audit(1472549797.744:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9e6008f8 items=0 ppid=309 ppcomm=main pid=6364 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-1083" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-30 11:36:37.744  1906  1906 E audit   : type=1320 msg=audit(1472549797.744:205): 
,08-30 11:36:37.754  6312  6364 W jxcore-log: Starting JXcore engine
,08-30 11:36:37.864  6312  6364 W jxcore-log: Platform android,
08-30 11:36:37.864  6312  6364 W jxcore-log: 
08-30 11:36:37.864  6312  6364 W jxcore-log: Process ARCH arm
08-30 11:36:37.864  6312  6364 W jxcore-log: 
,08-30 11:36:38.064  6312  6364 I jxcore-log: JXcore Cordova bridge is ready!
08-30 11:36:38.064  6312  6364 I jxcore-log: 
,08-30 11:36:38.064  6312  6364 W jxcore-log: JXcore engine is started
,08-30 11:36:38.064  6312  6355 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 11:36:38.064  6312  6312 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 11:36:38.284   319   319 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 11:36:38.294   290   290 E SMD     : DCD OFF,
,08-30 11:36:38.424  1017  3091 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-30 11:36:38.424  1017  3091 D BatteryService: level:86, scale:100, status:2, health:2, present:true, voltage: 4105, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,08-30 11:36:38.424  1017  3091 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-30 11:36:38.424  1017  3091 D BatteryService: stay LED for charging
08-30 11:36:38.424  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-30 11:36:38.424  1017  1017 I MotionRecognitionService: Plugged
,08-30 11:36:38.424  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-30 11:36:38.424  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-30 11:36:38.424  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-30 11:36:38.434  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-30 11:36:38.434  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 86
,08-30 11:36:38.444  2649  2649 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-30 11:36:38.444  2649  2780 D HeadsetStateMachine: Disconnected process message: 10
,08-30 11:36:38.454  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:86 status:2 health:2
,08-30 11:36:38.454  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:86 status:2 health:2
,08-30 11:36:38.454  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:86 status:2 health:2
,08-30 11:36:38.814  1017  2784 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-30 11:36:39.004  5573  5573 D FactoryTest: Not factory mode
,08-30 11:36:39.004  5573  5573 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-30 11:36:39.004  5573  5573 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-30 11:36:39.004  5573  5573 D MTPRx   : still no open session command from host, so toast
,08-30 11:36:39.014  5573  5573 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,08-30 11:36:39.014  5573  5573 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-30 11:36:39.014  5573  5573 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:116622
,08-30 11:36:39.014  1017  1497 E PersonaManagerService: inState():  stateMachine is null !!
,08-30 11:36:39.014  1017  1497 I PersonaManagerService: PersonaId don't exist
08-30 11:36:39.014  1017  1497 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-30 11:36:39.014  1017  1497 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-30 11:36:39.014  1017  1497 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:39.014  1017  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:36:39.014  1017  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-30 11:36:39.024  1017  1497 W ActivityManager: mDVFSHelper.acquire()
,08-30 11:36:39.034  1017  1497 D PersonaManager: isKioskContainerExistOnDevice
,08-30 11:36:39.034  1017  1497 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-30 11:36:39.034  1017  1497 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-30 11:36:39.034  1017  1497 D InputDispatcher: Focused application set to: xxxx
08-30 11:36:39.034  1017  1497 D InputDispatcher: Focus left window: 6312
,08-30 11:36:39.044  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-30 11:36:39.044  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-30 11:36:39.044  5573  5573 E MTPRx   : started activity for popup
,08-30 11:36:39.074  5573  5573 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-30 11:36:39.074  5573  5573 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-30 11:36:39.074  5573  5573 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-30 11:36:39.074  5573  5573 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 11:36:39.074  5573  5573 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 11:36:39.074  5573  5573 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 11:36:39.094  5573  5573 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-30 11:36:39.094  1017  1217 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-30 11:36:39.094  1017  1217 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-30 11:36:39.094  1017  1217 D InputDispatcher: Focused application set to: xxxx
08-30 11:36:39.094  1017  1217 D InputDispatcher: Focus entered window: 6312
,08-30 11:36:39.104  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-30 11:36:39.104  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101,
08-30 11:36:39.104  1017  1497 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@2c7b16b1 attribute=null, token = android.os.BinderProxy@c25db41
08-30 11:36:39.104  1017  1497 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-30 11:36:39.144  5573  5573 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-30 11:36:39.154  5573  5573 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-30 11:36:39.154  5573  5573 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-30 11:36:39.174  6312  6312 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-30 11:36:39.174  6312  6312 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
08-30 11:36:39.174  6312  6312 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-30 11:36:39.174  6312  6312 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
08-30 11:36:39.174  1017  3091 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-30 11:36:39.174  1017  3091 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-30 11:36:39.174  1017  3091 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-30 11:36:39.174  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-30 11:36:39.174  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,08-30 11:36:39.184  6312  6312 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-30 11:36:39.184  6312  6312 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-30 11:36:39.184  6312  6312 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@545a069 time:116799
,08-30 11:36:39.194  6312  6312 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@372b9284 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@3e61c5ec, 16908290=android.view.AbsSavedState$1@3e61c5ec}, android:focusedViewId=100}]}]
,08-30 11:36:39.194  6312  6312 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-30 11:36:39.194  6312  6312 V ActivityThread: updateVisibility : ActivityRecord{345c0b8f token=android.os.BinderProxy@545a069 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-30 11:36:39.194  6312  6312 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 11:36:39.194  6312  6312 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-30 11:36:39.194  1017  1140 D PersonaManager: isKioskContainerExistOnDevice
,08-30 11:36:39.284   319   319 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 11:36:40.284   319   319 I ServiceManager: Waiting for service AtCmdFwd...,
,08-30 11:36:41.284   319   319 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-30 11:36:41.294   290   290 E SMD     : DCD OFF,
,08-30 11:36:41.974  1017  2734 D SSRM:n  : SIOP:: AP = 330
,08-30 11:36:42.024  1017  1043 W ActivityManager: mDVFSHelper.release()
,08-30 11:36:42.394  1017  1096 V AlarmManager: waitForAlarm result :4
,08-30 11:36:42.404  1017  1096 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,08-30 11:36:42.414  1929  1929 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-30 11:36:42.454  1017  1560 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 11:36:42.454  1017  1560 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,08-30 11:36:42.454  1017  1560 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:42.454  1017  1560 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:42.454  1017  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:36:42.524  1017  1029 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 11:36:42.524  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.phenotype.service.sync.PhenotypeConfigurator; callingUser = 0; userId(target) = 0
,08-30 11:36:42.524  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:42.524  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 11:36:42.524  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:36:42.554  1017  3289 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 11:36:42.554  1017  3289 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-30 11:36:42.554  1017  3289 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:42.554  1017  3289 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:42.554  1017  3289 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:36:42.574  1017  1140 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,08-30 11:36:42.574  1017  1140 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-30 11:36:42.604  1017  1560 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 11:36:42.604  1017  1560 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:42.604  1017  1560 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 11:36:42.604  1017  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:36:42.604  1017  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 11:36:42.614  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:42.614  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 11:36:42.614  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:36:42.624  1929  1929 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-30 11:36:42.624  1929  1929 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-30 11:36:42.654  1017  1043 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:42.654  1017  1043 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:42.654  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:36:42.754  1017  1029 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-30 11:36:42.754  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-30 11:36:42.754  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:42.754  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:42.754  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:36:42.764  1929  1929 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-30 11:36:42.764  1929  1929 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-30 11:36:42.784  1017  1497 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 11:36:42.784  1017  1497 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:42.784  1017  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:42.784  1017  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:36:42.814  1017  3440 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-30 11:36:42.814  1017  3440 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-30 11:36:42.814  1017  3440 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:42.814  1017  3440 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:42.814  1017  3440 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:36:42.824  1929  6372 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 11:36:42.824   280   985 D EnterpriseController: uids 10012
08-30 11:36:42.824   280   985 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-30 11:36:42.824   280   985 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-30 11:36:42.834  1929  6372 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-30 11:36:42.834  1929  6372 I qtaguid : Tagging socket 62 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1929, getuid(): 10012
,08-30 11:36:42.874  1929  6372 I qtaguid : Tagging socket 73 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1929, getuid(): 10012
,08-30 11:36:43.064  1017  1497 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 11:36:43.064  1017  1497 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-30 11:36:43.064  1017  1497 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:43.064  1017  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:43.064  1017  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:36:43.084  1929  6372 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 11:36:43.084   280   985 D EnterpriseController: uids 10012
08-30 11:36:43.084   280   985 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-30 11:36:43.084   280   985 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-30 11:36:43.094  1929  6372 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-30 11:36:43.094  1929  6372 I qtaguid : Tagging socket 74 with tag 1000120300000000{268440067,0} for uid -1, pid: 1929, getuid(): 10012
,08-30 11:36:43.094  3808  6375 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
08-30 11:36:43.094  3808  6375 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-30 11:36:43.114  1929  6372 I qtaguid : Tagging socket 78 with tag 1000120300000000{268440067,0} for uid -1, pid: 1929, getuid(): 10012
,08-30 11:36:43.334  1017  1560 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 11:36:43.334  1017  1560 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-30 11:36:43.334  1017  1560 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:43.334  1017  1560 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:43.334  1017  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:36:43.344  1929  6372 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 11:36:43.344  1929  6372 I qtaguid : Tagging socket 74 with tag 1000120300000000{268440067,0} for uid -1, pid: 1929, getuid(): 10012
,08-30 11:36:43.364  1017  1560 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 11:36:43.364  1017  1560 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:43.364  1017  1560 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:43.364  1017  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:36:43.394  1017  1478 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 11:36:43.404  1017  1478 W ActivityManager: userId = 0, bbcId = -10000,
08-30 11:36:43.404  1017  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:43.404  1017  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:36:43.404  1017  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:36:43.404  1017  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:43.404  1017  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:36:43.404  1017  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:36:43.414  6379  6379 E Zygote  : MountEmulatedStorage()
08-30 11:36:43.414  6379  6379 E Zygote  : v2
08-30 11:36:43.414  6379  6379 I libpersona: KNOX_SDCARD checking this for 10012
08-30 11:36:43.414  6379  6379 I libpersona: KNOX_SDCARD not a persona
,08-30 11:36:43.424  1017  1478 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6379 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,08-30 11:36:43.424  6379  6379 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-30 11:36:43.424  6379  6379 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 11:36:43.424  6379  6379 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-30 11:36:43.444  1017  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 11:36:43.454  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:43.454  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:43.454  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:36:43.464  6379  6379 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 11:36:43.464  6379  6379 D ActivityThread: Added TimaKeyStore provider
,08-30 11:36:43.484  6379  6379 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-30 11:36:43.484  6379  6379 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-30 11:36:43.504  1017  1501 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 11:36:43.504  1017  1501 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:43.504  1017  1501 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:43.504  1017  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:36:43.524  6379  6379 I MultiDex: VM with version 2.1.0 has multidex support
,08-30 11:36:43.524  6379  6379 I MultiDex: install
08-30 11:36:43.524  6379  6379 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-30 11:36:43.524  1929  6372 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,08-30 11:36:43.534  1017  3289 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 11:36:43.534  1017  3289 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:43.534  1017  3289 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 11:36:43.534  1017  3289 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:36:43.544  1929  6372 I PhenotypeSyncScheduler: Cancel all previously scheduled adaptive polling
,08-30 11:36:43.554  6379  6379 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-30 11:36:43.554  1017  1043 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:43.554  1017  1043 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:43.554  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:36:43.614  6379  6379 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-30 11:36:43.624  6379  6379 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12a78749: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-30 11:36:43.624  6379  6379 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-30 11:36:43.644  6379  6379 D ChimeraCfgMgr: Reading stored module config
,08-30 11:36:43.724  6379  6397 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-30 11:36:43.724  6379  6379 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-30 11:36:43.724  6379  6379 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-30 11:36:43.814   285  1014 D WVCdm   : Instantiating CDM.
,08-30 11:36:43.814   285   285 I WVCdm   : CdmEngine::OpenSession
,08-30 11:36:43.814   285   285 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-30 11:36:43.834   285   285 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-30 11:36:43.854   285   285 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
08-30 11:36:43.854   285   285 D DrmWidevineDash: Service_Initialize: starts!
08-30 11:36:43.854   285   285 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,08-30 11:36:43.864   285   285 D QSEECOMAPI: : App is not loaded in QSEE
,08-30 11:36:43.864   285   285 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
08-30 11:36:43.864   285   285 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-30 11:36:43.864   285   285 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-30 11:36:43.864   285   285 D QSEECOMAPI: : App is not loaded in QSEE
,08-30 11:36:43.864   285   285 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
08-30 11:36:43.864   285   285 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-30 11:36:43.864   285   285 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-30 11:36:43.864   285   285 D QSEECOMAPI: : App is not loaded in QSEE
,08-30 11:36:43.884   285   285 D QSEECOMAPI: : Loaded image: APP id = 12
,08-30 11:36:43.884   285   285 D DrmWidevineDash: Service_Initialize: ends! returns 0
,08-30 11:36:43.894   285   285 D QSAPPSVER: qsapps_get_capabilities: Capability from secure side: 0x0
08-30 11:36:43.894   285   285 D QSAPPSVER: qsapps_get_capabilities: returns 0
08-30 11:36:43.894   285   285 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb16c0000
08-30 11:36:43.894   285   285 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb16c0000
08-30 11:36:43.894   285   285 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-30 11:36:43.894   421   428 D DrmLibTime: got the req here! ret=0
08-30 11:36:43.894   421   428 D DrmLibTime: command id, time_cmd_id = 770
08-30 11:36:43.894   421   428 D DrmLibTime: time_getutcsec starts!
08-30 11:36:43.894   421   428 D DrmLibTime: QSEE Time Listener: time_getutcsec
08-30 11:36:43.894   421   428 D DrmLibTime: QSEE Time Listener: get_utc_seconds
08-30 11:36:43.894   421   428 D DrmLibTime: QSEE Time Listener: time_get_modem_time
08-30 11:36:43.894   421   428 D DrmLibTime: QSEE Time Listener: Checking if ATS_MODEM is set or not.
,08-30 11:36:43.894   421   428 D QC-time-services: Lib:time_genoff_operation: pargs->base = 13
08-30 11:36:43.894   421   428 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 2
08-30 11:36:43.894   421   428 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 0
08-30 11:36:43.894   421   428 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
08-30 11:36:43.894   323   415 D QC-time-services: Daemon: Connection accepted:time_genoff
,08-30 11:36:43.894   323  6402 D QC-time-services: Daemon:Received base = 13, unit = 1, operation = 2,value = 0
08-30 11:36:43.894   323  6402 D QC-time-services: Daemon:genoff_opr: Base = 13, val = 0, operation = 2
08-30 11:36:43.894   323  6402 D QC-time-services: offset is: 0 for base: 0
08-30 11:36:43.894   421   428 E QC-time-services: Receive Passed == base = 13, unit = 1, operation = 2, result = 0
08-30 11:36:43.894   421   428 D DrmLibTime: QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
08-30 11:36:43.894   421   428 D DrmLibTime: QSEE Time Listener: Retrieved Android system time: 1472549803
08-30 11:36:43.894   421   428 D DrmLibTime: time_getutcsec returns 0, sec = 1472549803; nsec = 0
08-30 11:36:43.894   421   428 D DrmLibTime: time_getutcsec finished! 
08-30 11:36:43.904   421   428 D DrmLibTime: iotcl_continue_command finished! and return 0 
08-30 11:36:43.904   421   428 D DrmLibTime: before calling ioctl to read the next time_cmd
08-30 11:36:43.904   323   415 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,08-30 11:36:43.904   285   285 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,08-30 11:36:43.904  6379  6390 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-30 11:36:43.904   285   285 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
08-30 11:36:43.904   285   285 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
08-30 11:36:43.904   285   285 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-30 11:36:43.904  6379  6390 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 11:36:43.904  6379  6390 I System.out: (HTTPLog)-Static: isShipBuild true
08-30 11:36:43.904  6379  6390 I System.out: (HTTPLog)-Thread-1064-995752882: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-30 11:36:43.904  6379  6390 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 11:36:43.904   285   285 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-30 11:36:43.904   285   285 D DrmWidevineDash: hlos api version =  9
08-30 11:36:43.904   285   285 D DrmWidevineDash: tz api version =  9
08-30 11:36:43.904   285   285 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
08-30 11:36:43.904   285   285 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
08-30 11:36:43.904   285   285 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-30 11:36:43.914   280   985 D EnterpriseController: uids 10012
08-30 11:36:43.914   280   985 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-30 11:36:43.914   280   985 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-30 11:36:43.914  6379  6390 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-30 11:36:43.914  6379  6390 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6379, getuid(): 10012
,08-30 11:36:43.924   285   285 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,08-30 11:36:43.924   285   285 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
08-30 11:36:43.924   285   285 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
,08-30 11:36:43.924   285   285 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xbeca61b0
08-30 11:36:43.924   285   285 D DrmWidevineDash: OEMCrypto_OpenSession Session ID = 0
08-30 11:36:43.924   285   285 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-30 11:36:43.924   285   285 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,08-30 11:36:43.924   285   285 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
08-30 11:36:43.924   285   285 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
08-30 11:36:43.934   285   285 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb721c968, dataLength=8
,08-30 11:36:43.934   285   285 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-30 11:36:43.934   285   285 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-30 11:36:43.934   285   285 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,08-30 11:36:43.934   285   285 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xb71d3f48, wrapped_rsa_key_length=1280
,08-30 11:36:43.934   285   285 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-30 11:36:43.934   285   285 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,08-30 11:36:43.934   285   285 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
08-30 11:36:43.934   285   285 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-30 11:36:43.944   285   684 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,08-30 11:36:43.944   285   684 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-30 11:36:43.944   285   684 I WVCdm   : CdmEngine::GenerateKeyRequest
,08-30 11:36:43.944   285   684 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb71d2c68, idLength=0xb18e2730
08-30 11:36:43.944   285   684 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-30 11:36:43.954   285   684 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,08-30 11:36:43.954   285   684 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
08-30 11:36:43.954   285   684 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
08-30 11:36:43.954   285   684 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-30 11:36:43.954   285   684 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-30 11:36:43.954   285   684 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
08-30 11:36:43.954   285   684 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 24
08-30 11:36:43.954   285   684 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0
08-30 11:36:43.954   285   684 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!, current = 0xb18e2746, maximum = 0xb18e2747
08-30 11:36:43.954   285   684 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-30 11:36:43.954   285   684 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-30 11:36:43.954   285   684 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0
08-30 11:36:43.954   285   684 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
08-30 11:36:43.954   285   684 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-30 11:36:43.954   285   684 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-30 11:36:43.954   285   684 D DrmWidevineDash: hlos api version =  9
08-30 11:36:43.954   285   684 D DrmWidevineDash: tz api version =  9
08-30 11:36:43.954   285   684 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
08-30 11:36:43.954   285   684 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xb18e27b4
08-30 11:36:43.954   285   684 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-30 11:36:43.954   285   684 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,08-30 11:36:43.954   285   684 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
08-30 11:36:43.954   285   684 D WVCdm   : PrepareKeyRequest: nonce=458354840
08-30 11:36:43.954   285   684 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb71f7d38
08-30 11:36:43.954   285   684 D DrmWidevineDash: message_length=1599, signature=0xb71f89c8, signature_length=0xb18e2714
,08-30 11:36:43.954   285   684 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-30 11:36:44.104   285   684 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-30 11:36:44.104   285   684 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,08-30 11:36:44.104   285  1014 I WVCdm   : CdmEngine::CloseSession
08-30 11:36:44.104   285  1014 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
08-30 11:36:44.104   285  1014 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-30 11:36:44.114   285  1014 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-30 11:36:44.114   285  1014 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
08-30 11:36:44.114   285  1014 I WVCdm   : L3 Terminate.
08-30 11:36:44.114   285  1014 D DrmWidevineDash: OEMCrypto_Terminate: starts!
08-30 11:36:44.114   285  1014 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-30 11:36:44.114   285  1014 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-30 11:36:44.114   285  1014 D DrmWidevineDash: Service_Uninitialize: starts!
08-30 11:36:44.114   285  1014 D QSEECOMAPI: : QSEECom_dealloc_memory 
08-30 11:36:44.114   285  1014 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 12
08-30 11:36:44.114   285  1014 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
08-30 11:36:44.114   285  1014 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,08-30 11:36:44.194  6379  6390 I qtaguid : Untagging socket 30
,08-30 11:36:44.294   290   290 E SMD     : DCD OFF
,08-30 11:36:44.764  6408  6408 I dex2oat : ----------------------------------------------------
08-30 11:36:44.764  6408  6408 I dex2oat : <SS>: S T A R T I N G . . .
08-30 11:36:44.764  6408  6408 I dex2oat : <SS>: Zip is absent. Canceled.
,08-30 11:36:44.764  6408  6408 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-30 11:36:44.794  6408  6408 I dex2oat : dex2oat took 28.088ms (threads: 4)
,08-30 11:36:44.804  6379  6390 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-30 11:36:44.804  6379  6390 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-30 11:36:44.804  6379  6390 I Adreno-EGL: Build Date: 04/06/15 Mon
08-30 11:36:44.804  6379  6390 I Adreno-EGL: Local Branch: 
08-30 11:36:44.804  6379  6390 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-30 11:36:44.804  6379  6390 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-30 11:36:44.804  6379  6390 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-30 11:36:44.884  6379  6390 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-30 11:36:44.884  6379  6390 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-30 11:36:44.884  6379  6390 I Adreno-EGL: Build Date: 04/06/15 Mon
08-30 11:36:44.884  6379  6390 I Adreno-EGL: Local Branch: 
08-30 11:36:44.884  6379  6390 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-30 11:36:44.884  6379  6390 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-30 11:36:44.884  6379  6390 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-30 11:36:45.094  6379  6390 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-30 11:36:45.094  6379  6390 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-30 11:36:45.094  6379  6390 I Adreno-EGL: Build Date: 04/06/15 Mon
08-30 11:36:45.094  6379  6390 I Adreno-EGL: Local Branch: 
08-30 11:36:45.094  6379  6390 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-30 11:36:45.094  6379  6390 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-30 11:36:45.094  6379  6390 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-30 11:36:45.174  1929  6378 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 11:36:45.174   280   985 D EnterpriseController: uids 10012
08-30 11:36:45.174   280   985 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-30 11:36:45.174   280   985 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-30 11:36:45.184  1929  6378 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-30 11:36:45.184  1929  6378 I qtaguid : Tagging socket 56 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1929, getuid(): 10012,
,08-30 11:36:45.224  1929  6378 I qtaguid : Tagging socket 81 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1929, getuid(): 10012
,08-30 11:36:45.354  1017  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 11:36:45.354  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,08-30 11:36:45.364  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:45.364  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:45.364  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:36:45.424  1017  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 11:36:45.424  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:45.424  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:45.424  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:36:45.774  1929  2094 I art     : Explicit concurrent mark sweep GC freed 72748(4MB) AllocSpace objects, 24(1150KB) LOS objects, 39% free, 14MB/23MB, paused 1.470ms total 73.196ms
,08-30 11:36:45.804  1017  3091 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,08-30 11:36:45.814  1017  1501 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 11:36:45.814  1017  1501 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:45.814  1017  1501 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:45.814  1017  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:36:45.824  1017  1478 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 11:36:45.824  1017  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:45.824  1017  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:45.824  1017  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:36:45.854  1929  1929 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=b74f7982-d5fc-4f03-a64a-acb3c096928c
,08-30 11:36:45.864  1017  1560 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-30 11:36:45.864  1017  1560 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-30 11:36:45.864  1017  1560 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:45.864  1017  1560 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:45.864  1017  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:36:46.004  1929  2093 W GCoreFlp: No location to return for getLastLocation()
,08-30 11:36:46.034  1017  1217 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 11:36:46.034  1017  1217 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:46.034  1017  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:46.034  1017  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:36:46.044  1017  1560 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 11:36:46.044  1017  1560 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:46.044  1017  1560 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:46.044  1017  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:36:46.044  1017  1478 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
08-30 11:36:46.054  1017  1478 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:46.054  1017  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:46.054  1017  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:36:46.064  3808  6416 D UdcContextInitService: registered all accounts: true
,08-30 11:36:46.144  1017  1058 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-30 11:36:46.214  1017  3440 I art     : Explicit concurrent mark sweep GC freed 34624(1884KB) AllocSpace objects, 16(256KB) LOS objects, 33% free, 27MB/41MB, paused 2.493ms total 147.120ms
,08-30 11:36:46.214  1929  2098 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-30 11:36:46.234  1929  2109 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-30 11:36:46.284   319   319 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 11:36:46.344  1017  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 11:36:46.344  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,08-30 11:36:46.344  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:46.344  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:46.344  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:36:46.364  1644  1723 I art     : Explicit concurrent mark sweep GC freed 1386(47KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 730us total 35.216ms
,08-30 11:36:46.454  1017  1560 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 11:36:46.454  1017  1560 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:46.454  1017  1560 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:46.454  1017  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:36:46.474  1929  2109 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 11:36:46.474  1929  2109 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-30 11:36:46.474  1929  2109 I qtaguid : Tagging socket 87 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1929, getuid(): 10012
,08-30 11:36:46.494  1017  1501 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 11:36:46.494  1017  1501 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:46.494  1017  1501 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:46.494  1017  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:36:46.494  1929  6424 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-30 11:36:46.494  1929  6422 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-30 11:36:46.494  1017  3091 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 11:36:46.494  1017  3091 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:46.494  1017  3091 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:46.494  1017  3091 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:36:46.514  1929  2109 I qtaguid : Tagging socket 91 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1929, getuid(): 10012
,08-30 11:36:46.524  1017  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 11:36:46.524  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:46.524  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:46.524  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:36:46.524  1929  6424 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-30 11:36:46.524  1929  6422 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-30 11:36:46.524  1017  1217 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 11:36:46.524  1017  1217 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:46.524  1017  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:46.524  1017  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:36:46.554  1017  1140 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 11:36:46.554  1017  1140 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:46.554  1017  1140 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:46.554  1017  1140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:36:46.554  1929  6424 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-30 11:36:46.554  1929  6422 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
08-30 11:36:46.554  1929  6422 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,08-30 11:36:46.564  1929  6422 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-30 11:36:46.624  1017  3440 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 11:36:46.654  1929  6422 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 11:36:46.654   280   985 D EnterpriseController: uids 10012
08-30 11:36:46.654   280   985 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-30 11:36:46.654   280   985 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-30 11:36:46.654  1929  6422 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-30 11:36:46.654  1929  6422 I qtaguid : Tagging socket 93 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1929, getuid(): 10012
,08-30 11:36:46.684  1929  6422 I qtaguid : Tagging socket 53 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1929, getuid(): 10012
,08-30 11:36:46.734  1929  3028 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 11:36:46.734   280   985 D EnterpriseController: uids 10012
08-30 11:36:46.734   280   985 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-30 11:36:46.734   280   985 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-30 11:36:46.744  1929  3028 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false,
08-30 11:36:46.744  1929  3028 I qtaguid : Tagging socket 95 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1929, getuid(): 10012
,08-30 11:36:46.764  1017  1350 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-30 11:36:46.774  1929  3028 I qtaguid : Tagging socket 97 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1929, getuid(): 10012
,08-30 11:36:46.944  1017  1497 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 11:36:46.954  1929  6422 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 11:36:46.954  1929  6422 I qtaguid : Tagging socket 93 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1929, getuid(): 10012
,08-30 11:36:47.034  1929  3028 I qtaguid : Untagging socket 95
,08-30 11:36:47.044  1929  2109 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-30 11:36:47.084  1017  3091 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 11:36:47.094  1929  6422 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 11:36:47.094  1929  6422 I qtaguid : Tagging socket 93 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 1929, getuid(): 10012
,08-30 11:36:47.234  1017  1501 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 11:36:47.244  1929  6422 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 11:36:47.244  1929  6422 I qtaguid : Tagging socket 93 with tag 1106541400000000{285627412,0} for uid -1, pid: 1929, getuid(): 10012
,08-30 11:36:47.284   319   319 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 11:36:47.294   290   290 E SMD     : DCD OFF,
,08-30 11:36:47.384  1017  1497 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 11:36:47.384  1929  6422 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 11:36:47.384  1929  6422 I qtaguid : Tagging socket 93 with tag fffffca200000000{4294966434,0} for uid -1, pid: 1929, getuid(): 10012
,08-30 11:36:48.284   319   319 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 11:36:48.484  1017  1140 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-30 11:36:48.484  1017  1140 D BatteryService: level:86, scale:100, status:2, health:2, present:true, voltage: 4116, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-30 11:36:48.484  1017  1140 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-30 11:36:48.484  1017  1140 D BatteryService: stay LED for charging
08-30 11:36:48.484  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-30 11:36:48.484  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-30 11:36:48.484  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
08-30 11:36:48.494  1017  1017 I MotionRecognitionService: Plugged
08-30 11:36:48.494  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-30 11:36:48.494  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-30 11:36:48.494  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 86
,08-30 11:36:48.504  2649  2649 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-30 11:36:48.504  2649  2780 D HeadsetStateMachine: Disconnected process message: 10
,08-30 11:36:48.514  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:86 status:2 health:2
,08-30 11:36:48.514  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:86 status:2 health:2
08-30 11:36:48.514  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:86 status:2 health:2
,08-30 11:36:48.834  1929  3027 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 11:36:48.834  1929  3027 I qtaguid : Tagging socket 95 with tag 1000310200000000{268448002,0} for uid 10012, pid: 1929, getuid(): 10012
,08-30 11:36:49.064  1929  3027 I qtaguid : Untagging socket 95
,08-30 11:36:49.074  1929  2109 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0,
,08-30 11:36:49.094  1017  1140 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-30 11:36:49.284   319   319 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 11:36:50.164  1017  3440 I ActivityManager: Killing 5443:com.google.android.talk/u0a104 (adj 15): empty #31
,08-30 11:36:50.284   319   319 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 11:36:50.294   290   290 E SMD     : DCD OFF
,08-30 11:36:50.734  6312  6364 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 11:36:50.734  6312  6364 I jxcore-log: 
,08-30 11:36:50.734  6312  6364 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 11:36:50.734  6312  6364 I jxcore-log: 
,08-30 11:36:50.744  6312  6364 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 11:36:50.744  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:36:50.744  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:36:50.744  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:36:50.744  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:36:50.744  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 11:36:50.744  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 11:36:50.744  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 11:36:50.744  6312  6364 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 11:36:50.744  6312  6364 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 11:36:50.744  6312  6364 I jxcore-log: 
,08-30 11:36:50.744  6312  6364 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 11:36:50.744  6312  6364 I jxcore-log: 
,08-30 11:36:51.284  1017  1050 I PowerManagerService: [PWL] Off : 51s ago
,08-30 11:36:51.284   319   319 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-30 11:36:51.374  6312  6364 D executeNativeTests: Running unit tests
,08-30 11:36:51.454  6312  6364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 11:36:51.454  6312  6364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bfc1e25 added. We now have 2 listener(s)
,08-30 11:36:51.454  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-30 11:36:51.454  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 11:36:51.454  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 11:36:51.454  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 11:36:51.454  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31264bfa added. We now have 2 listener(s)
08-30 11:36:51.454  6312  6364 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 11:36:51.454  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 11:36:51.454  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 11:36:51.464  6312  6364 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 11:36:51.464  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:36:51.464  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:36:51.464  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:36:51.464  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:36:51.464  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 11:36:51.464  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 11:36:51.464  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 11:36:51.464  6312  6364 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 11:36:51.464  6312  6364 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 11:36:51.464  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:36:51.464  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 11:36:51.464  6312  6364 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 11:36:51.464  6312  6364 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 11:36:51.464  6312  6364 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-30 11:36:51.464  6312  6364 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 11:36:51.464  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 11:36:51.464  6312  6364 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 11:36:51.464  6312  6364 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-30 11:36:51.464  6312  6364 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:51.464  6312  6364 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:51.464  6312  6364 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 11:36:51.464  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:51.464  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.464  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 11:36:51.464  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 11:36:51.464  6312  6364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bfc1e25 removed from the list
08-30 11:36:51.464  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:51.464  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31264bfa removed from the list
,08-30 11:36:51.474  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:36:51.474  6312  6364 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:51.474  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:36:51.474  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.474  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:36:51.474  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:51.474  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:51.474  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:51.474  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31264bfa not in the list
,08-30 11:36:51.474  6312  6364 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported,
08-30 11:36:51.474  6312  6364 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:51.474  6312  6364 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:51.474  6312  6364 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:51.474  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:51.474  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.474  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:36:51.474  6312  6364 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bfc1e25 not in the list
08-30 11:36:51.474  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:51.474  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31264bfa not in the list
08-30 11:36:51.474  6312  6364 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:51.474  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.474  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:51.474  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-30 11:36:51.474  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:36:51.484  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:51.484  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:51.484  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:51.484  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31264bfa not in the list
,08-30 11:36:51.484  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-30 11:36:51.484  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 11:36:51.484  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 11:36:51.484  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 11:36:51.484  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 11:36:51.484  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 11:36:51.484  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 11:36:51.484  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 11:36:51.484  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 11:36:51.484  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 11:36:51.484  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 11:36:51.484  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 11:36:51.484  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 11:36:51.484  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 11:36:51.484  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 11:36:51.484  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 11:36:51.484  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 11:36:51.484  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 11:36:51.484  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 11:36:51.484  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 11:36:51.484  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 11:36:51.484  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 11:36:51.484  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 11:36:51.484  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 11:36:51.484  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 11:36:51.484  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 11:36:51.484  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 11:36:51.484  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no pe,er name> 36:2610:2610:2610:2610:2610]
08-30 11:36:51.484  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 11:36:51.484  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 11:36:51.484  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 11:36:51.484  6312  6364 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:51.484  6312  6364 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:51.484  6312  6364 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:51.484  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:51.484  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.484  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:51.484  6312  6364 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bfc1e25 not in the list
08-30 11:36:51.484  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:51.484  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31264bfa not in the list
08-30 11:36:51.484  6312  6364 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:51.484  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.484  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:51.484  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.484  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:51.484  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:51.484  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:51.484  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:51.484  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31264bfa not in the list
08-30 11:36:51.484  6312  6364 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 11:36:51.494  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 11:36:51.494  6312  6364 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 11:36:51.494  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:36:51.494  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:36:51.494  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:36:51.494  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:36:51.494  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 11:36:51.494  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 11:36:51.494  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 11:36:51.494  6312  6364 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 11:36:51.494  6312  6364 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 11:36:51.494  6312  6364 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 11:36:51.494  6312  6364 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 11:36:51.494  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 11:36:51.494  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 11:36:51.494  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 11:36:51.504  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:36:51.504  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 11:36:51.504  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:36:51.514  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 11:36:51.514  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 11:36:51.514  6312  6364 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-30 11:36:51.524  6312  6364 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-30 11:36:51.524  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 11:36:51.524  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-30 11:36:51.534  6312  6364 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 11:36:51.544  2649  2659 D BtGatt.GattService: registerClient() - UUID=e205dc37-12ff-44b0-86e4-597a310c9286
,08-30 11:36:51.594  2649  2733 D BtGatt.GattService: onClientRegistered() - UUID=e205dc37-12ff-44b0-86e4-597a310c9286, clientIf=6
,08-30 11:36:51.594  6312  6320 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-30 11:36:51.594  2649  3003 D BtGatt.GattService: start scan with filters
,08-30 11:36:51.604  2649  2764 D BtGatt.ScanManager: handling starting scan
,08-30 11:36:51.604  2649  2764 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a6a6c54
,08-30 11:36:51.604  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 11:36:51.604  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-30 11:36:51.614  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-30 11:36:51.614  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 11:36:51.614  2649  2733 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-30 11:36:51.614  2649  2733 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 11:36:51.614  2649  2764 D BtGatt.ScanManager: allow scan with filters
08-30 11:36:51.614  2649  2764 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-30 11:36:51.614  2649  2764 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-30 11:36:51.624  6312  6364 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 11:36:51.624  6312  6312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 11:36:51.624  6312  6364 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 11:36:51.624  2649  2733 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-30 11:36:51.624  2649  2733 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 11:36:51.624  2649  2764 D BtGatt.ScanManager: Starting BLE batch scan
,08-30 11:36:51.624  2649  2764 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-30 11:36:51.634  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 11:36:51.634  6312  6364 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 11:36:51.644  2649  2733 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-30 11:36:51.644  2649  2733 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 11:36:51.644  6312  6364 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 11:36:51.644  6312  6364 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-30 11:36:51.644  6312  6364 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 11:36:51.644  6312  6364 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-30 11:36:51.644  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.644  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 11:36:51.644  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-30 11:36:51.644  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 11:36:51.644  6312  6364 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 11:36:51.644  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 11:36:51.654  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 11:36:51.654  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 11:36:51.654  2649  2733 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-30 11:36:51.654  2649  2733 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 11:36:51.654  2649  2660 D BtGatt.GattService: stopScan() - queue size =1
,08-30 11:36:51.664  2649  3003 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-30 11:36:51.664  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 11:36:51.664  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 11:36:51.664  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 11:36:51.664  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 11:36:51.664  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 11:36:51.664  6312  6364 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 11:36:51.664  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 11:36:51.664  6312  6364 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 11:36:51.664  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 11:36:51.664  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 11:36:51.664  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:51.664  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.664  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 11:36:51.664  6312  6364 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bfc1e25 not in the list
08-30 11:36:51.664  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:51.664  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31264bfa not in the list
08-30 11:36:51.664  6312  6364 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 11:36:51.664  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:51.664  6312  6364 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 11:36:51.674  6312  6312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 11:36:51.674  6312  6312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 11:36:51.674  6312  6312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 11:36:51.674  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 11:36:51.684  6312  6364 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 11:36:51.684  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:36:51.684  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:36:51.684  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:36:51.684  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:36:51.684  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 11:36:51.684  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 11:36:51.684  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 11:36:51.684  2649  2764 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 6
,08-30 11:36:51.684  6312  6364 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 11:36:51.684  6312  6364 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 11:36:51.684  6312  6364 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 11:36:51.684  6312  6364 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 11:36:51.684  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 11:36:51.684  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 11:36:51.684  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 11:36:51.684  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 11:36:51.694  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:36:51.694  2649  2764 D BtGatt.ScanManager: filter size is 1
,08-30 11:36:51.694  2649  2764 D BtGatt.ScanManager: delete FilterIndex - 3
,08-30 11:36:51.694  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:36:51.694  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 11:36:51.694  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 11:36:51.694  2649  2733 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-30 11:36:51.704  2649  2733 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 11:36:51.704  2649  2764 D BtGatt.ScanManager: stopping BLe Batch
,08-30 11:36:51.704  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 11:36:51.704  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-30 11:36:51.704  6312  6364 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 11:36:51.704  2649  2659 D BtGatt.GattService: registerClient() - UUID=7bd29690-c4a3-4730-b5e1-2337869c19d2
,08-30 11:36:51.704  2649  2733 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-30 11:36:51.704  2649  2733 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 11:36:51.704  2649  2764 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-30 11:36:51.714  2649  2733 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-30 11:36:51.714  2649  2733 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 11:36:51.744  2649  2733 D BtGatt.GattService: onClientRegistered() - UUID=7bd29690-c4a3-4730-b5e1-2337869c19d2, clientIf=6
,08-30 11:36:51.744  6312  6326 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-30 11:36:51.744  2649  2660 D BtGatt.GattService: start scan with filters
,08-30 11:36:51.754  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 11:36:51.754  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 11:36:51.754  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 11:36:51.754  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 11:36:51.754  6312  6364 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 11:36:51.754  2649  2764 D BtGatt.ScanManager: handling starting scan
,08-30 11:36:51.754  6312  6312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 11:36:51.754  6312  6364 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 11:36:51.764  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 11:36:51.764  2649  2733 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-30 11:36:51.764  6312  6364 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 11:36:51.764  2649  2733 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 11:36:51.764  2649  2764 D BtGatt.ScanManager: allow scan with filters
08-30 11:36:51.764  2649  2764 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-30 11:36:51.764  2649  2764 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-30 11:36:51.764  2649  2733 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-30 11:36:51.764  2649  2733 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 11:36:51.764  2649  2764 D BtGatt.ScanManager: Starting BLE batch scan
08-30 11:36:51.764  2649  2764 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-30 11:36:51.774  6312  6364 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 11:36:51.774  6312  6364 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-30 11:36:51.774  6312  6364 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 11:36:51.774  2649  2733 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-30 11:36:51.774  2649  2733 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 11:36:51.774  6312  6364 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-30 11:36:51.774  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.774  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 11:36:51.774  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-30 11:36:51.774  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 11:36:51.774  6312  6364 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 11:36:51.774  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 11:36:51.774  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-30 11:36:51.774  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 11:36:51.784  2649  3003 D BtGatt.GattService: stopScan() - queue size =1
,08-30 11:36:51.784  2649  2733 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-30 11:36:51.784  2649  2733 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 11:36:51.794  2649  2659 D BtGatt.GattService: unregisterClient() - clientIf=6,
,08-30 11:36:51.794  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 11:36:51.794  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 11:36:51.794  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 11:36:51.794  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 11:36:51.794  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 11:36:51.794  6312  6364 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 11:36:51.794  2649  2764 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 7
,08-30 11:36:51.794  2649  2764 D BtGatt.ScanManager: filter size is 1
,08-30 11:36:51.804  2649  2764 D BtGatt.ScanManager: delete FilterIndex - 4
,08-30 11:36:51.804  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 11:36:51.804  6312  6364 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 11:36:51.804  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 11:36:51.804  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 11:36:51.804  6312  6312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 11:36:51.804  6312  6312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 11:36:51.804  6312  6312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 11:36:51.804  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 11:36:51.804  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 11:36:51.804  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 11:36:51.804  6312  6364 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bfc1e25 not in the list
08-30 11:36:51.804  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 11:36:51.804  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31264bfa not in the list
,08-30 11:36:51.804  2649  2733 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-30 11:36:51.814  6312  6364 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:51.814  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:36:51.814  2649  2733 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 11:36:51.814  2649  2764 D BtGatt.ScanManager: stopping BLe Batch
,08-30 11:36:51.814  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.814  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:36:51.814  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 11:36:51.814  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 11:36:51.814  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:51.814  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31264bfa not in the list
,08-30 11:36:51.814  6312  6364 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-30 11:36:51.824  2649  2733 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-30 11:36:51.824  2649  2733 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 11:36:51.824  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 11:36:51.824  2649  2764 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-30 11:36:51.824  6312  6364 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 11:36:51.824  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:36:51.824  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:36:51.824  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:36:51.824  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:36:51.824  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 11:36:51.824  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 11:36:51.824  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 11:36:51.824  6312  6364 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 11:36:51.824  6312  6364 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 11:36:51.824  2649  2733 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-30 11:36:51.834  2649  2733 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 11:36:51.834  6312  6364 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 11:36:51.834  6312  6364 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 11:36:51.834  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 11:36:51.834  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 11:36:51.834  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 11:36:51.834  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 11:36:51.834  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:36:51.834  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:36:51.844  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 11:36:51.844  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 11:36:51.844  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 11:36:51.844  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-30 11:36:51.844  6312  6364 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 11:36:51.844  2649  3003 D BtGatt.GattService: registerClient() - UUID=3fb78381-8a63-4509-87fa-f0fc6da273ff
,08-30 11:36:51.894  2649  2733 D BtGatt.GattService: onClientRegistered() - UUID=3fb78381-8a63-4509-87fa-f0fc6da273ff, clientIf=6
,08-30 11:36:51.894  6312  6320 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-30 11:36:51.894  2649  2659 D BtGatt.GattService: start scan with filters
,08-30 11:36:51.894  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 11:36:51.894  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 11:36:51.894  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 11:36:51.894  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 11:36:51.894  6312  6364 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 11:36:51.904  6312  6364 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 11:36:51.904  6312  6312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 11:36:51.904  2649  2764 D BtGatt.ScanManager: handling starting scan
,08-30 11:36:51.904  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 11:36:51.914  6312  6364 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 11:36:51.914  2649  2733 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-30 11:36:51.914  2649  2733 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 11:36:51.914  2649  2764 D BtGatt.ScanManager: allow scan with filters
08-30 11:36:51.914  2649  2764 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-30 11:36:51.914  2649  2764 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-30 11:36:51.914  6312  6364 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 11:36:51.914  6312  6364 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 11:36:51.914  6312  6364 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 11:36:51.914  6312  6364 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 11:36:51.914  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.914  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 11:36:51.914  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 11:36:51.914  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 11:36:51.914  6312  6364 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 11:36:51.914  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 11:36:51.914  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 11:36:51.914  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 11:36:51.924  2649  2733 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-30 11:36:51.924  2649  2733 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 11:36:51.924  2649  2764 D BtGatt.ScanManager: Starting BLE batch scan
,08-30 11:36:51.924  2649  2764 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-30 11:36:51.924  2649  2660 D BtGatt.GattService: stopScan() - queue size =1
,08-30 11:36:51.924  2649  3003 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-30 11:36:51.924  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 11:36:51.924  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 11:36:51.924  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 11:36:51.924  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 11:36:51.924  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 11:36:51.934  6312  6364 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 11:36:51.934  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 11:36:51.934  6312  6364 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 11:36:51.934  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 11:36:51.934  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 11:36:51.934  2649  2733 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-30 11:36:51.934  2649  2733 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 11:36:51.934  6312  6312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 11:36:51.934  6312  6312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 11:36:51.934  6312  6312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 11:36:51.934  6312  6364 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 11:36:51.934  6312  6364 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-30 11:36:51.934  6312  6364 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:51.934  6312  6364 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 11:36:51.944  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:51.944  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.944  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 11:36:51.944  6312  6364 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bfc1e25 not in the list
08-30 11:36:51.944  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:51.944  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31264bfa not in the list
08-30 11:36:51.944  6312  6364 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:51.944  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:51.944  2649  2733 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-30 11:36:51.944  2649  2733 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 11:36:51.944  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.944  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:36:51.944  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:51.944  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:51.944  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:51.944  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31264bfa not in the list
,08-30 11:36:51.944  6312  6364 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-30 11:36:51.944  6312  6364 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:51.944  6312  6364 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:51.944  6312  6364 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:51.944  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:51.944  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.944  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:51.944  6312  6364 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bfc1e25 not in the list
08-30 11:36:51.944  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:51.944  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31264bfa not in the list
08-30 11:36:51.944  6312  6364 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:51.944  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.944  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:51.944  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.944  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:36:51.944  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:51.944  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:51.944  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:51.944  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31264bfa not in the list
,08-30 11:36:51.944  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 11:36:51.944  6312  6364 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:51.944  6312  6364 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:51.944  6312  6364 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:51.944  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:51.944  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.944  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:51.944  6312  6364 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bfc1e25 not in the list
08-30 11:36:51.944  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:51.944  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31264bfa not in the list
08-30 11:36:51.944  6312  6364 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:51.944  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.944  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:51.944  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.944  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:36:51.944  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:51.944  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:51.944  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:51.944  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31264bfa not in the list
,08-30 11:36:51.944  6312  6364 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-30 11:36:51.944  6312  6364 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:51.944  6312  6364 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:51.944  6312  6364 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:51.944  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:51.944  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.944  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:51.944  6312  6364 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bfc1e25 not in the list
08-30 11:36:51.944  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:51.944  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31264bfa not in the list
08-30 11:36:51.944  6312  6364 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:51.944  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.944  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:51.954  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.954  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:36:51.954  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:51.954  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:51.954  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:51.954  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31264bfa not in the list
,08-30 11:36:51.954  6312  6364 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-30 11:36:51.954  6312  6364 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:51.954  6312  6364 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:51.954  6312  6364 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:51.954  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:51.954  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.954  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:51.954  6312  6364 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bfc1e25 not in the list
08-30 11:36:51.954  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:51.954  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31264bfa not in the list
08-30 11:36:51.954  6312  6364 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:51.954  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.954  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:51.954  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.954  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:36:51.954  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:51.954  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 11:36:51.954  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:51.954  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31264bfa not in the list
08-30 11:36:51.954  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 11:36:51.954  6312  6364 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 11:36:51.954  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 11:36:51.954  6312  6364 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 11:36:51.954  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-30 11:36:51.954  6312  6364 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 11:36:51.954  6312  6364 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-30 11:36:51.954  6312  6364 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:51.954  6312  6364 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 11:36:51.954  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:51.954  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.954  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:51.954  6312  6364 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bfc1e25 not in the list
08-30 11:36:51.954  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 11:36:51.954  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31264bfa not in the list
08-30 11:36:51.954  6312  6364 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:51.954  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.954  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:51.954  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.954  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:51.954  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:51.954  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:51.954  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 11:36:51.954  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31264bfa not in the list
08-30 11:36:51.954  6312  6364 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 11:36:51.954  6312  6364 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,08-30 11:36:51.954  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55],
,08-30 11:36:51.964  6312  6364 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55,
,08-30 11:36:51.964  6312  6364 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,08-30 11:36:51.964  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-30 11:36:51.964  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-30 11:36:51.964  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-30 11:36:51.964  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 11:36:51.964  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410],
,08-30 11:36:51.964  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 11:36:51.964  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 11:36:51.964  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 11:36:51.964  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 11:36:51.964  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 11:36:51.964  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 11:36:51.964  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 11:36:51.964  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 11:36:51.964  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 11:36:51.964  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 11:36:51.964  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 11:36:51.964  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 11:36:51.964  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 11:36:51.964  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 11:36:51.964  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 11:36:51.964  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 11:36:51.964  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 11:36:51.964  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 11:36:51.964  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 11:36:51.964  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 11:36:51.964  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 11:36:51.964  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 11:36:51.964  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 11:36:51.964  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 11:36:51.964  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 11:36:51.964  6312  6364 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-30 11:36:51.964  6312  6364 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered pee,rs, but trying anyway...
08-30 11:36:51.964  6312  6364 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-30 11:36:51.964  6312  6364 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 11:36:51.964  6312  6364 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 11:36:51.964  6312  6364 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-30 11:36:51.964  6312  6364 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 11:36:51.964  6312  6364 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 11:36:51.964  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-30 11:36:51.964  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-30 11:36:51.964  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-30 11:36:51.964  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-30 11:36:51.964  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-30 11:36:51.964  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-30 11:36:51.964  6312  6364 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-30 11:36:51.964  6312  6364 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 11:36:51.964  6312  6364 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-30 11:36:51.964  6312  6364 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:51.964  6312  6364 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:51.964  6312  6364 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:51.964  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:51.964  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.964  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:51.964  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-30 11:36:51.964  6312  6364 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bfc1e25 not in the list
08-30 11:36:51.964  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:51.964  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31264bfa not in the list
08-30 11:36:51.964  6312  6364 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:51.964  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.964  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:51.964  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-30 11:36:51.964  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:51.974  6312  6437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1147
08-30 11:36:51.974  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:51.974  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:51.974  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:51.974  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31264bfa not in the list
08-30 11:36:51.974  2649  2764 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 8
08-30 11:36:51.974  6312  6364 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-30 11:36:51.974  2649  2764 D BtGatt.ScanManager: filter size is 1
08-30 11:36:51.974  2649  2764 D BtGatt.ScanManager: delete FilterIndex - 5
08-30 11:36:51.974  6312  6364 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:51.974  6312  6364 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:51.974  6312  6364 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:51.974  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:51.974  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.974  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:51.974  6312  6364 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bfc1e25 not in the list
,08-30 11:36:51.974  6312  6436 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1147)
08-30 11:36:51.974  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:51.974  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31264bfa not in the list
08-30 11:36:51.974  6312  6364 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:51.974  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.974  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:51.974  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.974  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-30 11:36:51.974  6312  6436 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1147)
08-30 11:36:51.974  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:51.974  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:51.974  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:51.974  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31264bfa not in the list
08-30 11:36:51.974  6312  6364 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,08-30 11:36:51.974  6312  6364 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:51.974  6312  6364 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:51.974  6312  6364 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:51.974  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:51.974  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.974  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:51.974  6312  6364 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bfc1e25 not in the list
08-30 11:36:51.974  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 11:36:51.974  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31264bfa not in the list
08-30 11:36:51.974  6312  6364 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:51.974  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.974  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:51.974  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.974  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:51.974  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:51.974  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:51.974  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 11:36:51.974  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31264bfa not in the list
08-30 11:36:51.974  6312  6364 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-30 11:36:51.974  6312  6364 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-30 11:36:51.974  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 11:36:51.974  6312  6364 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-30 11:36:51.974  6312  6364 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 11:36:51.974  6312  6364 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-30 11:36:51.974  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 11:36:51.974  6312  6364 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-30 11:36:51.974  6312  6364 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,08-30 11:36:51.974  6312  6364 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 11:36:51.974  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 11:36:51.974  6312  6364 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-30 11:36:51.974  6312  6364 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:51.974  6312  6364 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:51.974  6312  6364 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:51.974  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 11:36:51.974  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.974  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:51.974  6312  6364 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bfc1e25 not in the list
08-30 11:36:51.974  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:51.974  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31264bfa not in the list
08-30 11:36:51.974  6312  6364 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:51.974  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.974  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:51.974  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.974  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:51.974  2649  2733 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-30 11:36:51.974  2649  2733 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 11:36:51.974  2649  2764 D BtGatt.ScanManager: stopping BLe Batch
08-30 11:36:51.984  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:51.984  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:51.984  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:51.984  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31264bfa not in the list
08-30 11:36:51.984  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:51.984  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.984  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:51.984  6312  6364 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bfc1e25 not in the list
08-30 11:36:51.984  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:51.984  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31264bfa not in the list
08-30 11:36:51.984  6312  6364 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:51.984  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.984  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:51.984  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 11:36:51.984  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31264bfa not in the list
08-30 11:36:51.984  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:51.984  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.984  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:51.984  6312  6364 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bfc1e25 not in the list
08-30 11:36:51.984  6312  6364 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:51.984  6312  6364 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:51.984  6312  6364 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:51.984  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:51.984  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.984  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:51.984  6312  6364 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bfc1e25 not in the list
,08-30 11:36:51.984  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:51.984  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31264bfa not in the list
08-30 11:36:51.984  6312  6364 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:51.984  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.984  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:51.984  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.984  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:51.984  2649  2733 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-30 11:36:51.984  2649  2733 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 11:36:51.984  2649  2764 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-30 11:36:51.984  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:51.984  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:51.984  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:51.984  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31264bfa not in the list
08-30 11:36:51.984  6312  6364 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-30 11:36:51.984  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 11:36:51.984  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-30 11:36:51.984  6312  6364 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 11:36:51.984  6312  6364 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 11:36:51.984  6312  6312 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 11:36:51.984  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 11:36:51.984  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 11:36:51.984  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:51.984  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 11:36:51.994  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 11:36:51.994  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 11:36:51.994  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:51.994  6312  6364 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 11:36:51.994  6312  6364 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bfc1e25 not in the list
08-30 11:36:51.994  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:51.994  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 11:36:51.994  6312  6364 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 11:36:51.994  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 11:36:51.994  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.994  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:36:51.994  6312  6312 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 11:36:51.994  2649  2733 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-30 11:36:51.994  2649  2733 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 11:36:51.994  6312  6364 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 11:36:51.994  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31264bfa not in the list
,08-30 11:36:51.994  6312  6364 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:51.994  6312  6364 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:51.994  6312  6364 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:51.994  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:51.994  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.994  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:51.994  6312  6312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 11:36:51.994  6312  6364 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bfc1e25 not in the list
08-30 11:36:51.994  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:51.994  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31264bfa not in the list
08-30 11:36:51.994  6312  6364 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:51.994  6312  6312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 11:36:51.994  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.994  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:51.994  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 11:36:51.994  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:51.994  6312  6312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 11:36:51.994  6312  6438 D BluetoothSocket: bindListen(): myUserId = 0
08-30 11:36:51.994  6312  6438 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 11:36:51.994  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:51.994  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:51.994  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:51.994  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31264bfa not in the list
08-30 11:36:51.994  6312  6364 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-30 11:36:51.994  6312  6364 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 11:36:51.994  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 11:36:51.994  6312  6364 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-30 11:36:51.994  6312  6364 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:51.994  6312  6364 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:51.994  6312  6364 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:51.994  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:51.994  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.994  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:51.994  6312  6364 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bfc1e25 not in the list
08-30 11:36:51.994  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:51.994  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31264bfa not in the list
08-30 11:36:51.994  6312  6364 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:51.994  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.994  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:51.994  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:51.994  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:51.994  6312  6438 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[109]}
08-30 11:36:51.994  6312  6438 D BluetoothSocket: bindListen(), new LocalSocket 
08-30 11:36:51.994  6312  6438 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-30 11:36:51.994  6312  6438 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2b4eaa4c
08-30 11:36:51.994  6312  6438 D BluetoothSocket: channel: 6
08-30 11:36:51.994  6312  6438 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2b29da95, channel: 6, state: LISTENING
08-30 11:36:51.994  6312  6438 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2b29da95, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2b4eaa4c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@5a9a7aamSocket: android.net.LocalSocket@31ce5f9b impl:android.net.LocalSocketImpl@22e21f38 fd:FileDescriptor[109]
08-30 11:36:51.994  6312  6438 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@31ce5f9b impl:android.net.LocalSocketImpl@22e21f38 fd:FileDescriptor[109]
,08-30 11:36:52.004  6312  6438 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-30 11:36:52.004  6312  6438 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 11:36:52.004  6312  6438 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-30 11:36:52.004  6312  6312 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-30 11:36:52.004  1017  2734 D SSRM:n  : SIOP:: AP = 340
08-30 11:36:52.004  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:52.004  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:52.004  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:52.004  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31264bfa not in the list
,08-30 11:36:52.004  6312  6364 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:52.004  6312  6364 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:52.004  6312  6364 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:52.004  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:52.004  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:52.004  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:52.004  6312  6364 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bfc1e25 not in the list
08-30 11:36:52.004  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:52.004  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31264bfa not in the list
08-30 11:36:52.004  6312  6364 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:52.004  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:52.004  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:52.004  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:52.004  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:36:52.004  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:52.004  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:52.004  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:52.004  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31264bfa not in the list
,08-30 11:36:52.004  6312  6364 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:52.004  6312  6364 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:52.004  6312  6364 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:52.004  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 11:36:52.004  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:52.004  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:52.004  6312  6364 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bfc1e25 not in the list
08-30 11:36:52.004  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:52.004  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31264bfa not in the list
08-30 11:36:52.004  6312  6364 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 11:36:52.004  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:52.004  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:52.004  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:52.004  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:52.004  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:52.004  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:52.004  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:52.004  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31264bfa not in the list
,08-30 11:36:52.014  6312  6364 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-30 11:36:52.014  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 11:36:52.014  6312  6364 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-30 11:36:52.014  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 11:36:52.014  6312  6364 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-30 11:36:52.014  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-30 11:36:52.014  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 11:36:52.014  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-30 11:36:52.014  6312  6364 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-30 11:36:52.014  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 11:36:52.014  6312  6364 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-30 11:36:52.014  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 11:36:52.014  6312  6364 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-30 11:36:52.014  6312  6364 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-30 11:36:52.014  6312  6364 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-30 11:36:52.014  6312  6364 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-30 11:36:52.014  6312  6364 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-30 11:36:52.014  6312  6364 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-30 11:36:52.014  6312  6364 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-30 11:36:52.014  6312  6364 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-30 11:36:52.014  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 11:36:52.014  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1d1a8b11 added. We now have 2 listener(s)
08-30 11:36:52.014  6312  6364 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 11:36:52.014  6312  6364 D BluetoothAdapter: enable(),
,08-30 11:36:52.014  6312  6364 D BluetoothAdapter: enable(): BT is already enabled..!
,08-30 11:36:52.024  1017  1478 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-30 11:36:52.024  1017  1478 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-30 11:36:52.024  1017  1478 D SecContentProvider2: mCursor = null
,08-30 11:36:52.024  1017  1478 D WifiService: setWifiEnabled: true pid=6312, uid=10155,
08-30 11:36:52.024  1017  1478 W ActivityManager: Permission Denial: getCurrentUser() from pid=6312, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,08-30 11:36:52.024  1017  1478 W WifiService: Failed getting userId using ActivityManagerNative
08-30 11:36:52.024  1017  1478 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6312, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-30 11:36:52.024  1017  1478 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-30 11:36:52.024  1017  1478 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-30 11:36:52.024  1017  1478 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-30 11:36:52.024  1017  1478 W WifiService: ,	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-30 11:36:52.024  1017  1478 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-30 11:36:52.024  1017  1478 D SettingsProvider: name = wifi_on
08-30 11:36:52.024  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 11:36:52.024  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1ad29476 added. We now have 3 listener(s)
08-30 11:36:52.024  6312  6364 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 11:36:52.024  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 11:36:52.024  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1e295a77 added. We now have 4 listener(s)
08-30 11:36:52.024  6312  6364 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 11:36:52.024  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 11:36:52.024  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2035f6e4 added. We now have 5 listener(s)
08-30 11:36:52.024  6312  6364 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 11:36:52.034  1017  3091 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-30 11:36:52.034  1017  3091 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-30 11:36:52.034  1017  3091 D SecContentProvider2: mCursor = null
,08-30 11:36:52.034  1017  3091 D WifiService: setWifiEnabled: false pid=6312, uid=10155
08-30 11:36:52.034  1017  3091 D SettingsProvider: name = wifi_on
,08-30 11:36:52.034  1017  1128 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-30 11:36:52.044  6312  6364 D BluetoothAdapter: disable()
08-30 11:36:52.044  2141  2141 I wpa_supplicant: reset timer : RESET_TIMER 0
08-30 11:36:52.044  2141  2141 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-30 11:36:52.044  2141  2141 I wpa_supplicant: P2P: Current p2p state = IDLE
08-30 11:36:52.044  1017  3289 D SettingsProvider: name = bluetooth_on
08-30 11:36:52.044  2141  2141 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-30 11:36:52.044  1017  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 11:36:52.044  2649  2728 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-30 11:36:52.044  1017  1497 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 11:36:52.044  2649  2728 D BluetoothAdapterProperties: Setting state to 13
08-30 11:36:52.044  1017  1497 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-30 11:36:52.044  2649  2728 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-30 11:36:52.044  2649  2728 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-30 11:36:52.044  2649  2728 D BluetoothAdapterService: updateAdapterState state is 13
08-30 11:36:52.054  1017  1497 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:52.054  1017  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:36:52.054  1017  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 11:36:52.054  2649  2649 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-30 11:36:52.054  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 11:36:52.054  2649  2649 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1713d326, channel: 19, state: LISTENING
08-30 11:36:52.054  2649  2649 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1713d326, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2803084e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@132aab67mSocket: android.net.LocalSocket@220e8d14 impl:android.net.LocalSocketImpl@20a659bd fd:FileDescriptor[74]
08-30 11:36:52.054  2649  2649 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@220e8d14 impl:android.net.LocalSocketImpl@20a659bd fd:FileDescriptor[74]
08-30 11:36:52.054  2649  2728 D BluetoothAdapterService: Autoconnection is available 
,08-30 11:36:52.054  2649  2728 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-30 11:36:52.054  2649  2728 D BluetoothAdapterService: terminating service from this receiver
,08-30 11:36:52.054  1017  1128 E WifiNative-wlan0: do suspend true
,08-30 11:36:52.054  1017  3091 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-30 11:36:52.054  1017  3091 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:52.054  1017  3091 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:36:52.054  1017  3091 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 11:36:52.064  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:36:52.064  6312  6364 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 11:36:52.064  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:36:52.064  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:36:52.064  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:36:52.064  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 11:36:52.064  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 11:36:52.064  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 11:36:52.064  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 11:36:52.064  1319  1319 D BluetoothPbap: Proxy object disconnected
08-30 11:36:52.064  1319  1319 D PbapServerProfile: Bluetooth service disconnected
08-30 11:36:52.064  2649  2728 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 11:36:52.064  2649  2728 D BluetoothAdapterProperties: mDiscovering is false
,08-30 11:36:52.064  1017  1477 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-30 11:36:52.064  2649  2728 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-30 11:36:52.064  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-30 11:36:52.064  1017  1017 I InputMethodManagerService: [BT Setting State] State =13
,08-30 11:36:52.074  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 11:36:52.074  6312  6364 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 11:36:52.074  6312  6364 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 11:36:52.074  2649  2733 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-30 11:36:52.074  2649  2733 D BluetoothAdapterProperties: Scan Mode:20
,08-30 11:36:52.074  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-30 11:36:52.074  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:36:52.074  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-30 11:36:52.074  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:36:52.074  1177  1177 D BluetoothTile:  getBluetoothState : 13
,08-30 11:36:52.074  1177  1717 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 11:36:52.074  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:36:52.084  1177  1717 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 11:36:52.084  1770  1770 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 11:36:52.084  1319  1319 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 11:36:52.084  1017  1477 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 11:36:52.084  1017  1350 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-30 11:36:52.084  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-30 11:36:52.084  1177  1717 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-30 11:36:52.094  1017  1478 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 11:36:52.094  1017  1478 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-30 11:36:52.094  2649  2728 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-30 11:36:52.094  2649  2728 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
08-30 11:36:52.094  2649  2728 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-30 11:36:52.094  2649  2728 E bt-btif : cmd socket is not created
08-30 11:36:52.094  2649  2728 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-30 11:36:52.094  2649  2841 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-30 11:36:52.094  2649  2841 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-30 11:36:52.094  1017  1478 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:52.094  1017  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:52.094  1017  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:36:52.094  2649  5123 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-30 11:36:52.094  6312  6312 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:36:52.094  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:36:52.094  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:36:52.094  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:36:52.094  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:36:52.094  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 11:36:52.094  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 11:36:52.094  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 11:36:52.094  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 11:36:52.094  6312  6312 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:36:52.094  6312  6312 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 11:36:52.094  1319  1319 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 11:36:52.094  2649  2841 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 11:36:52.094  2649  2841 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 11:36:52.094  2649  2841 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-30 11:36:52.104  1017  1350 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-30 11:36:52.104  1017  1350 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-30 11:36:52.104  1017  1350 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:52.104  1017  1350 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:36:52.104  1017  1350 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-30 11:36:52.104  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:36:52.104  2649  2649 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@dac9703, channel: 5, state: LISTENING
,08-30 11:36:52.104  2649  2649 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@dac9703, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@30267d6f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@37d16680mSocket: android.net.LocalSocket@1863d4b9 impl:android.net.LocalSocketImpl@d6820fe fd:FileDescriptor[76]
08-30 11:36:52.104  2649  2649 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1863d4b9 impl:android.net.LocalSocketImpl@d6820fe fd:FileDescriptor[76]
08-30 11:36:52.104  2649  2649 I BtOppRfcommListener: stopping Accept Thread
08-30 11:36:52.104  2649  2649 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@31d7a05f, channel: 12, state: LISTENING
08-30 11:36:52.104  2649  2649 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@31d7a05f, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3493d681, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@14266aacmSocket: android.net.LocalSocket@35e40375 impl:android.net.LocalSocketImpl@ca14f0a fd:FileDescriptor[80]
08-30 11:36:52.104  2649  2649 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@35e40375 impl:android.net.LocalSocketImpl@ca14f0a fd:FileDescriptor[80]
,08-30 11:36:52.114  2649  5123 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-30 11:36:52.114  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:36:52.114  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:36:52.114  2649  2649 V BluetoothOppManager: cleanUp...
,08-30 11:36:52.124  1319  1319 D DockEventReceiver: finishStartingService: stopping service
,08-30 11:36:52.124  1319  1319 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 11:36:52.124  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:36:52.124  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-30 11:36:52.134  1017  1477 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-30 11:36:52.134  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:36:52.134  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:36:52.134  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:52.134  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:36:52.144  1017  1477 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6444 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,08-30 11:36:52.144  6444  6444 E Zygote  : MountEmulatedStorage()
08-30 11:36:52.144  6444  6444 E Zygote  : v2
08-30 11:36:52.144  6444  6444 I libpersona: KNOX_SDCARD checking this for 10003
08-30 11:36:52.144  6444  6444 I libpersona: KNOX_SDCARD not a persona
,08-30 11:36:52.154  6444  6444 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 11:36:52.154  6444  6444 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 11:36:52.154  6444  6444 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 11:36:52.184  6444  6444 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 11:36:52.184  6444  6444 D ActivityThread: Added TimaKeyStore provider
,08-30 11:36:52.214  6444  6444 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-30 11:36:52.214  1017  1127 D WifiP2pService: InactiveState{ what=143375 }
08-30 11:36:52.214  1017  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-30 11:36:52.214   280   989 D CommandListener: Clearing all IP addresses on wlan0
,08-30 11:36:52.214  1929  4673 V NativeCrypto: Read error: ssl=0xb930d488: I/O error during system call, Connection timed out
,08-30 11:36:52.214  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020543/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 11:36:52.214  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-30 11:36:52.214  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:52.214  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:52.214  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:52.214  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 11:36:52.214  1929  4673 V NativeCrypto: SSL shutdown failed: ssl=0xb930d488: I/O error during system call, Broken pipe
08-30 11:36:52.224  1929  4673 E GCM     : Wifi connection closed with errorCode 20
,08-30 11:36:52.224  1017  1130 E ConnectivityService: updateNetworkInfo()
08-30 11:36:52.224  1017  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 11:36:52.224  1017  1130 E ConnectivityService: updateNetworkInfo()
08-30 11:36:52.224  1017  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,08-30 11:36:52.224  1017  1127 D WifiP2pService: InactiveState{ what=131204 }
,08-30 11:36:52.224  1017  1127 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-30 11:36:52.224  1017  1128 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-30 11:36:52.224  1017  1127 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-30 11:36:52.224  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-30 11:36:52.224  1017  1501 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,08-30 11:36:52.224  1017  2260 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:36:52.224  1017  2260 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:36:52.224  1017  2260 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-30 11:36:52.224  1017  2260 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:36:52.224  1017  2260 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,08-30 11:36:52.224  1017  2260 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 11:36:52.224  1017  2260 I qtaguid : Tagging socket 355 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1017, getuid(): 1000
,08-30 11:36:52.234  1017  2260 I qtaguid : Untagging socket 355
,08-30 11:36:52.234  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 1
08-30 11:36:52.234  1017  1017 D RttService: SCAN_AVAILABLE : 1
08-30 11:36:52.234  1017  2260 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 11:36:52.234  1017  1151 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:36:52.234  1017  1152 D RttService: EnabledState got{ when=-2ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 11:36:52.234  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020543/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 11:36:52.234  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 11:36:52.234  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 11:36:52.244  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 11:36:52.244  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:52.244  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:52.244  1017  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 11:36:52.244  1017  1048 D WifiDisplayAdapter: onP2pDisconnected
08-30 11:36:52.244  1017  1127 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-30 11:36:52.244  1017  1127 D WifiP2pService: P2pDisablingState
08-30 11:36:52.244  1017  1127 D WifiP2pService: P2pDisablingState{ what=147458 }
08-30 11:36:52.244  1017  1127 D WifiP2pService: p2p socket connection lost
,08-30 11:36:52.244  1017  1127 D WifiP2pService: P2pDisabledState
08-30 11:36:52.244  1017  1128 E WifiNative-wlan0: do suspend true
,08-30 11:36:52.254  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-30 11:36:52.254  1017  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-30 11:36:52.254  1017  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
08-30 11:36:52.254  1017  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-30 11:36:52.254  1017  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 11:36:52.254  1017  1048 D WifiDisplayController: disconnect
08-30 11:36:52.254  1017  1048 D WifiDisplayController: updateConnection
08-30 11:36:52.254  1017  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 11:36:52.254  1017  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-30 11:36:52.254  1017  1127 D WifiP2pService: P2pDisabledState{ what=143375 }
08-30 11:36:52.254  1017  1127 D WifiP2pService: DefaultState{ what=143375 }
,08-30 11:36:52.254  1017  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-30 11:36:52.254  1017  1048 D WifiDisplayAdapter: onP2pDisconnected
08-30 11:36:52.254  1017  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-30 11:36:52.254  1017  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-30 11:36:52.254  6444  6444 D UserAnalysis.SecureDbManager: Key for secure DB is newly created,
,08-30 11:36:52.254  6444  6444 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-30 11:36:52.254  6444  6444 D UserAnalysis: Create SecureDbHelper
,08-30 11:36:52.264  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED,
,08-30 11:36:52.264  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020543/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-30 11:36:52.264  1017  1501 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-30 11:36:52.264  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 11:36:52.264  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-30 11:36:52.264  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:52.264  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:52.264  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-30 11:36:52.264  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:52.264  6444  6444 D IntelligenceServiceApplication: onCreate()
,08-30 11:36:52.274  1017  3091 I ActivityManager: Killing 4928:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,08-30 11:36:52.274  6444  6444 D IntelligenceServiceApplication: no applications having user consent for prediction
08-30 11:36:52.284   280   985 D EnterpriseController: uids 1000
08-30 11:36:52.284   280   985 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-30 11:36:52.284   280   985 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-30 11:36:52.284   280   989 D CommandListener: Clearing all IP addresses on wlan0
08-30 11:36:52.284  1017  1130 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,08-30 11:36:52.284  1017  1130 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
08-30 11:36:52.284  1017  1477 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
08-30 11:36:52.284  1017  1130 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 11:36:52.284  1177  1690 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-30 11:36:52.284  1017  3091 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
08-30 11:36:52.284  1017  1130 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-30 11:36:52.284  1017  1130 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-30 11:36:52.284  1017  1127 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-30 11:36:52.284  1017  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 11:36:52.284  1453  1453 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-30 11:36:52.284  1453  1453 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 11:36:52.284  1017  3091 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:52.284  1017  3091 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:52.284  1017  3091 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:52.284  1017  3091 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:52.284  3808  4216 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-30 11:36:52.284  1017  2260 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-30 11:36:52.284  1017  2260 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-30 11:36:52.284  1017  2260 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:36:52.284  1017  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-30 11:36:52.294  2649  2936 I bt_userial_mct: exiting userial_read_thread
08-30 11:36:52.294  2649  2936 D bt_userial_mct: Leaving userial_evt_read_thread()
08-30 11:36:52.294  6444  6444 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
08-30 11:36:52.294  2649  2841 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 11:36:52.294  2649  2841 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 11:36:52.294  2649  2841 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 11:36:52.294  2649  2841 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 11:36:52.294  2649  2841 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 11:36:52.294  2649  2841 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 11:36:52.294  2649  2841 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 11:36:52.294  2649  2841 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 11:36:52.294  2649  2841 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 11:36:52.294  2649  2841 W bt-btif : ag scb idx 1 not allocated
08-30 11:36:52.294  2649  2841 W bt-btif : ag scb idx 2 not allocated
08-30 11:36:52.294  2649  2841 E bt-btif : BTA AG is already disabled, ignoring ...
08-30 11:36:52.294  2649  2733 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-30 11:36:52.294  2649  2844 I bt_vendor: hw_epilog_process
08-30 11:36:52.294  2649  2733 D bt_userial_mct: userial_close
08-30 11:36:52.294  2649  2733 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-30 11:36:52.304  6444  6444 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-30 11:36:52.304  6470  6470 E Zygote  : MountEmulatedStorage()
08-30 11:36:52.304  6470  6470 E Zygote  : v2
08-30 11:36:52.304  6470  6470 I libpersona: KNOX_SDCARD checking this for 10107
08-30 11:36:52.304  6470  6470 I libpersona: KNOX_SDCARD not a persona
08-30 11:36:52.304  6470  6470 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 11:36:52.304  6470  6470 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 11:36:52.304  6470  6470 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-30 11:36:52.314  1017  3091 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6470 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-30 11:36:52.314  1017  1130 D ConnectivityService: nai.networkMonitor.doQuit()
08-30 11:36:52.314  1017  1130 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 11:36:52.314  1017  1130 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-30 11:36:52.314  1017  1130 E ConnectivityService: updateNetworkInfo()
08-30 11:36:52.314  1017  1130 E ConnectivityService: updateNetworkInfo(),
08-30 11:36:52.314  1017  1017 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-30 11:36:52.314  1017  1125 V NetworkStats: updateIfacesLocked()
08-30 11:36:52.314  1017  1131 D Tethering: MasterInitialState.processMessage what=3
08-30 11:36:52.314  1017  1125 V NetworkStats: performPollLocked(flags=0x1)
08-30 11:36:52.314  1017  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-30 11:36:52.314  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 11:36:52.314  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 11:36:52.314  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-30 11:36:52.314  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
08-30 11:36:52.314  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-30 11:36:52.314  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-30 11:36:52.314  1177  1177 D StatusBar.NetworkController: updateDataNetType()
08-30 11:36:52.314  1177  1177 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-30 11:36:52.314  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-30 11:36:52.324  2141  2141 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
08-30 11:36:52.324  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 11:36:52.324  1017  1125 V NetworkStats: performPollLocked() took 7ms
08-30 11:36:52.324  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-30 11:36:52.324  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-30 11:36:52.324  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,08-30 11:36:52.324  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-30 11:36:52.324  1017  1126 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-30 11:36:52.324  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 11:36:52.324  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020543/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 11:36:52.324  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 11:36:52.324  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:52.324  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:52.324  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:52.324  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:52.324  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 11:36:52.324  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 11:36:52.324  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 11:36:52.334  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020543/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 11:36:52.334  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 11:36:52.334  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:52.334  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:52.334  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:52.334  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 11:36:52.334  1017  1128 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-30 11:36:52.334  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 11:36:52.334  1017  1128 D SecContentProvider2: mCursor = null
,08-30 11:36:52.334  6470  6470 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 11:36:52.334  6470  6470 D ActivityThread: Added TimaKeyStore provider
,08-30 11:36:52.344  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020543/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 11:36:52.344  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-30 11:36:52.344  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:52.344  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:52.344  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:52.344  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 11:36:52.344  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 11:36:52.344  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0),
08-30 11:36:52.344  1177  1717 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-30 11:36:52.344  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 11:36:52.344  1177  1177 D HotspotTile: onReceive : 0, 0
,08-30 11:36:52.344  1319  1319 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-30 11:36:52.344  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 11:36:52.344  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 11:36:52.344  6312  6312 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:36:52.344  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:36:52.344  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:36:52.344  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:36:52.344  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 11:36:52.344  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 11:36:52.344  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:36:52.344  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:36:52.344  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 11:36:52.354  6312  6312 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 11:36:52.354  6312  6312 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 11:36:52.354  6312  6312 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 11:36:52.354  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:36:52.354  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:36:52.354  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:36:52.354  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 11:36:52.354  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 11:36:52.354  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:36:52.354  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:36:52.354  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 11:36:52.354  6312  6312 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:36:52.354  6312  6312 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 11:36:52.414  2141  2141 I wpa_supplicant: Blacklist: Clear (all) 
,08-30 11:36:52.414  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 11:36:52.414  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 11:36:52.414  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 11:36:52.424  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 11:36:52.424  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-30 11:36:52.424  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 11:36:52.424  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 11:36:52.424  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 11:36:52.424  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 11:36:52.424  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 11:36:52.424  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 11:36:52.424  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 11:36:52.434  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 11:36:52.434  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 11:36:52.434  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 11:36:52.434  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-30 11:36:52.434  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 11:36:52.434  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 11:36:52.434  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 11:36:52.434  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 11:36:52.434  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
,08-30 11:36:52.444  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 11:36:52.444  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
,08-30 11:36:52.444  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 11:36:52.444  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 11:36:52.444  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 11:36:52.444  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 11:36:52.444  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 11:36:52.444  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 11:36:52.454  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
,08-30 11:36:52.474  2141  2141 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-30 11:36:52.474  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-30 11:36:52.474  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 11:36:52.474  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-30 11:36:52.494  6312  6312 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 11:36:52.504  2141  2141 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-30 11:36:52.504  2141  2141 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-30 11:36:52.504  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 11:36:52.504  2141  2141 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-30 11:36:52.504  2141  2141 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-30 11:36:52.504  2141  2141 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-30 11:36:52.504  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 11:36:52.504  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
08-30 11:36:52.504  1017  1131 D Tethering: InitialState.processMessage what=4
08-30 11:36:52.504  1017  1128 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
,08-30 11:36:52.514  1017  1131 E Tethering: No numeric data
08-30 11:36:52.514  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 11:36:52.514  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 11:36:52.514  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
08-30 11:36:52.514  1017  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 11:36:52.514  1017  1131 D Tethering: clearTetheredNotification()
,08-30 11:36:52.514  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 11:36:52.514  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,08-30 11:36:52.514  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
08-30 11:36:52.514  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 11:36:52.514  1017  1125 V NetworkStats: performPollLocked(flags=0x1)
,08-30 11:36:52.514  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 11:36:52.514  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 11:36:52.514  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-30 11:36:52.514  1177  1177 D HotspotTile: updateTetherState():false, false
,08-30 11:36:52.524  1017  1125 V NetworkStats: performPollLocked() took 6ms
08-30 11:36:52.524  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 11:36:52.524  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 11:36:52.524  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 11:36:52.564   271   271 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb760f7c8
08-30 11:36:52.564   271   271 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
08-30 11:36:52.564   271   271 I rmt_storage: wakelock acquired: 1, error no: 42
08-30 11:36:52.564   271   302 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1218382536)
,08-30 11:36:52.574  2649  2733 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-30 11:36:52.574  2649  2733 I bt_vendor: bluetooth satus is on
08-30 11:36:52.574  2649  2733 I bt_vendor: bt-vendor : resetting BT status
08-30 11:36:52.574  2649  2733 I bt_vendor: Starting hciattach daemon
08-30 11:36:52.574  2649  2733 I bt_vendor: try to set false
,08-30 11:36:52.574  2649  2733 I bt_vendor: Starting hciattach daemon
08-30 11:36:52.574  2649  2733 I bt_vendor: try to set false
,08-30 11:36:52.574  2649  2733 I bt_vendor: cleanup
,08-30 11:36:52.574  2649  2841 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-30 11:36:52.574  2649  2733 I GKI_LINUX: GKI_exit_task 0 done
08-30 11:36:52.574  2649  2733 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-30 11:36:52.574  2649  2728 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-30 11:36:52.574  2649  2728 D BtConfig.SecureMode: isSecureModeOn:false
,08-30 11:36:52.574  2649  2728 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,08-30 11:36:52.584  2649  2728 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,08-30 11:36:52.584  2649  2728 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-30 11:36:52.584  2649  2728 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-30 11:36:52.584  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 11:36:52.584  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-30 11:36:52.594  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:52.594  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:36:52.594  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 11:36:52.594  2649  2649 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 11:36:52.594  2649  2728 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-30 11:36:52.594  2649  2728 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-30 11:36:52.594  2649  2728 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-30 11:36:52.594  1017  3289 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 11:36:52.594  1017  3289 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-30 11:36:52.594  2649  2649 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 11:36:52.594  2649  2649 D BtGatt.GattService: stop()
08-30 11:36:52.594  2649  2649 D BtGatt.AdvertiseManager: advertise clients cleared
,08-30 11:36:52.604  1017  3289 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:52.604  1017  3289 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:36:52.604  1017  3289 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 11:36:52.604  2649  2728 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,08-30 11:36:52.604  2649  2649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a6a6c54
08-30 11:36:52.604  2649  2728 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-30 11:36:52.604  2649  2728 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-30 11:36:52.604  1017  1478 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 11:36:52.604  1017  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 11:36:52.604  2649  2649 D HeadsetService: Received stop request...Stopping profile...
08-30 11:36:52.604  1017  1478 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:52.604  1017  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:36:52.604  1017  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 11:36:52.604  2649  2728 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-30 11:36:52.604  2649  2728 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-30 11:36:52.604  2649  2728 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-30 11:36:52.604  2649  2649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a6a6c54
,08-30 11:36:52.614  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-30 11:36:52.614  1017  1217 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 11:36:52.614  1017  1217 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-30 11:36:52.614  1017  1217 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:52.614  1017  1217 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:36:52.614  1017  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 11:36:52.624  2649  2728 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-30 11:36:52.624  2649  2728 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-30 11:36:52.624  2649  2728 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-30 11:36:52.624  1017  3091 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 11:36:52.624  1017  3091 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-30 11:36:52.624  1319  1319 D HeadsetProfile: Bluetooth service disconnected
,08-30 11:36:52.624  1017  3091 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:52.624  1017  3091 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:36:52.624  1017  3091 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 11:36:52.624  2649  2728 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-30 11:36:52.624  2649  2728 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-30 11:36:52.624   271   302 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
08-30 11:36:52.624   271   302 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
08-30 11:36:52.624   271   302 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1218382536) wakelock released: 1, error no: 0
08-30 11:36:52.624   271   302 I rmt_storage: 
,08-30 11:36:52.624  2649  2728 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-30 11:36:52.624   271   271 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb760f7c8
,08-30 11:36:52.634  1017  1478 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 11:36:52.634  1017  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-30 11:36:52.634  1017  1478 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:52.634  1017  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:36:52.634  1017  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 11:36:52.634  2649  2728 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-30 11:36:52.634  2649  2728 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-30 11:36:52.634  2649  2728 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-30 11:36:52.634  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 11:36:52.634  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0,
08-30 11:36:52.634  1017  1030 W ActivityManager: userId = 0, bbcId = -10000,
08-30 11:36:52.634  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:36:52.634  1017  1030 D ActivityManager: bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
08-30 11:36:52.634  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 11:36:52.634  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
08-30 11:36:52.634  2649  2728 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-30 11:36:52.644  1017  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 11:36:52.634  2649  2728 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-30 11:36:52.644  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-30 11:36:52.634  2649  2728 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-30 11:36:52.644  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:52.644  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
08-30 11:36:52.644  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
08-30 11:36:52.644  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:52.644  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:36:52.644  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 11:36:52.644  2649  2728 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-30 11:36:52.644  2649  2728 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-30 11:36:52.644  2649  2728 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-30 11:36:52.644  2649  2728 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-30 11:36:52.644  2649  2728 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-30 11:36:52.644  2649  2728 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,08-30 11:36:52.644  2649  2728 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-30 11:36:52.644  2649  2728 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-30 11:36:52.644  2649  2728 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-30 11:36:52.644  2649  2728 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-30 11:36:52.644  2649  2728 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-30 11:36:52.644  2649  2728 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-30 11:36:52.644  2649  2728 D BluetoothAdapterState: Stopping profile services that were post enabled
08-30 11:36:52.644  2649  2649 E BluetoothAdapterService(711617620): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,08-30 11:36:52.644  2649  2649 D A2dpService: Received stop request...Stopping profile...
,08-30 11:36:52.644  2649  2791 D A2dpStateMachine: Exit Disconnected: -1
,08-30 11:36:52.654  2649  2649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a6a6c54
,08-30 11:36:52.654  1017  1017 D BluetoothA2dp: Proxy object disconnected
08-30 11:36:52.654  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-30 11:36:52.654  2892  2892 D BluetoothA2dp: Proxy object disconnected
08-30 11:36:52.654  2649  2649 E BluetoothAdapterService(711617620): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-30 11:36:52.654  2649  2649 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 11:36:52.654  2649  2649 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-30 11:36:52.654  1319  1319 D BluetoothA2dp: Proxy object disconnected
08-30 11:36:52.654  1319  1319 D A2dpProfile: Bluetooth service disconnected
,08-30 11:36:52.654  2649  2649 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 11:36:52.654  2649  2649 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-30 11:36:52.654  2649  2649 D HidService: Received stop request...Stopping profile...
08-30 11:36:52.654  2649  2649 D HidService: Stopping Bluetooth HidService
08-30 11:36:52.654  2649  2649 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-30 11:36:52.654  2649  2649 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-30 11:36:52.654  2649  2649 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-30 11:36:52.654  2649  2649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a6a6c54
,08-30 11:36:52.664  2649  2649 D HealthService: Received stop request...Stopping profile...
,08-30 11:36:52.664  2649  2649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a6a6c54
08-30 11:36:52.664  1319  1319 D BluetoothInputDevice: Proxy object disconnected
08-30 11:36:52.664  1319  1319 D HidProfile: Bluetooth service disconnected
,08-30 11:36:52.664  2649  2649 D PanService: Received stop request...Stopping profile...
08-30 11:36:52.664  2649  2649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a6a6c54
,08-30 11:36:52.664  1017  1017 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-30 11:36:52.664  1319  1319 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 11:36:52.664  1319  1319 D PanProfile: Bluetooth service disconnected
08-30 11:36:52.664  2649  2649 D BluetoothMapService: Received stop request...Stopping profile...
,08-30 11:36:52.664  2649  2649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a6a6c54
,08-30 11:36:52.674  2649  2649 D SapService: Received stop request...Stopping profile...
08-30 11:36:52.674  1319  1319 D BluetoothMap: Proxy object disconnected
08-30 11:36:52.674  1319  1319 D MapProfile: Bluetooth service disconnected
,08-30 11:36:52.674  2649  2649 D SapService: Stopping Bluetooth SapService
,08-30 11:36:52.674  2649  2649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a6a6c54
08-30 11:36:52.674  2649  2649 E BluetoothAdapterService(711617620): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-30 11:36:52.674  2649  2649 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 11:36:52.674  2649  2649 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-30 11:36:52.674  2649  2649 D BluetoothA2dp: Proxy object disconnected
08-30 11:36:52.674  2649  2649 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-30 11:36:52.674  2649  2792 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-30 11:36:52.674  2649  2649 I GKI_LINUX: GKI_exit_task 2 done
08-30 11:36:52.674  2649  2649 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-30 11:36:52.674  1319  1319 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-30 11:36:52.674  1319  1319 D SapProfile: Bluetooth service disconnected
08-30 11:36:52.674  2649  2649 E BluetoothAdapterService(711617620): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-30 11:36:52.674  2649  2649 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 11:36:52.674  2649  2649 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-30 11:36:52.674  2649  2649 E BluetoothAdapterService(711617620): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-30 11:36:52.674  2649  2649 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 11:36:52.674  2649  2649 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-30 11:36:52.674  2649  2649 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 11:36:52.674  2649  2649 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 11:36:52.674  2649  2649 E BluetoothAdapterService(711617620): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-30 11:36:52.674  2649  2649 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 11:36:52.674  2649  2649 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-30 11:36:52.674  2649  2649 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 11:36:52.674  2649  2649 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-30 11:36:52.674  2649  2649 E BluetoothAdapterService(711617620): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-30 11:36:52.674  2649  2649 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-30 11:36:52.674  2649  2649 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-30 11:36:52.674  2649  2649 E BluetoothAdapterService(711617620): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-30 11:36:52.674  2649  2649 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-30 11:36:52.674  2649  2649 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-30 11:36:52.684  2649  2728 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-30 11:36:52.684  2649  2728 D BluetoothAdapterProperties: Setting state to 10
08-30 11:36:52.684  2649  2728 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-30 11:36:52.684  2649  2728 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-30 11:36:52.684  2649  2728 D BluetoothAdapterService: updateAdapterState state is 10
,08-30 11:36:52.684  2649  2728 D BluetoothAdapterService: Autoconnection is available 
08-30 11:36:52.684  2649  2728 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-30 11:36:52.684  2649  2728 I BluetoothAdapterState: Entering OffState
,08-30 11:36:52.684  6312  6326 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 11:36:52.684  6312  6326 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 11:36:52.684  6312  6326 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-30 11:36:52.684  6312  6326 D BluetoothLeAdvertiser: Exit stop advertising
,08-30 11:36:52.684  6312  6326 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-30 11:36:52.684  6312  6326 D BluetoothLeScanner: Exiting stopAllScan
,08-30 11:36:52.684  2892  2901 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 11:36:52.684  1177  1188 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 11:36:52.684  1177  1188 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 11:36:52.684  1017  1047 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 11:36:52.684  1017  1047 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 11:36:52.684  1453  1468 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 11:36:52.684  1453  1468 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 11:36:52.684  1319  1339 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 11:36:52.694  1319  1332 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-30 11:36:52.694  2892  2900 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 11:36:52.694  2892  2900 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 11:36:52.694  1929  2099 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 11:36:52.694  1929  2099 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 11:36:52.694  6470  6470 D StrictMode: StrictMode policy violation; ~duration=276 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 11:36:52.694  6470  6470 D StrictMode: StrictMode policy violation; ~duration=267 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.g,mm.base.app.a.a(PG:1211)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 11:36:52.694  6470  6470 D StrictMode: StrictMode policy violation; ~duration=213 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at java.io.File.exists(File.java:363)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.ActivityTh,read.main(ActivityThread.java:6145)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 11:36:52.694  6470  6470 D StrictMode: StrictMode policy violation; ~duration=212 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 11:36:52.694  6470  6470 D StrictMode: StrictMode policy violation; ~duration=211 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 11:36:52.694  1017  1029 I ActivityManager: Killing 5636:com.google.android.partnersetup/u0a15 (adj 15): empty #31
08-30 11:36:52.694  6470  6470 D StrictMode: StrictMode policy violation; ~duration=208 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.r.k.c(PG:1187)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.r.v.a(PG:1206)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.r.y.a(PG:2233)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.r.e.b(PG:170)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.r.e.b(PG:13188)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 11:36:52.694  6470  6470 D StrictMode: StrictMode policy violation; ~duration=207 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.r.k.c(PG:1187)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.r.k.b(PG:14147)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.r.k.c(PG:583)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.r.v.a(PG:1206)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.r.y.a(PG:2233)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.r.e.b(PG:170)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.r.e.b(PG:13188)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 11:36:52.694  6470  6470 D StrictMode: StrictMode policy violation; ~duration=181 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at java.io.File.exists(File.java:363)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 11:36:52.694  6470  6470 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 11:36:52.704  2141  2141 I wpa_supplicant: Blacklist: Clear (all) 
08-30 11:36:52.704  2649  3003 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 11:36:52.704  2649  3003 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 11:36:52.704  1929  1929 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-30 11:36:52.704  1429  1440 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 11:36:52.704  1429  1440 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 11:36:52.704  1319  1332 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 11:36:52.704  1319  1332 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 11:36:52.714  1017  1047 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 11:36:52.714  1441  1465 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 11:36:52.714  1441  1465 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 11:36:52.714  2649  2660 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 11:36:52.714  1929  1929 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-30 11:36:52.714  1319  1339 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 11:36:52.714  1319  1332 D BluetoothMap: onBluetoothStateChange: up=false
08-30 11:36:52.714  1319  1339 D Bluetoothsap: onBluetoothStateChange: up=false
08-30 11:36:52.714  1319  1339 D Bluetoothsap: Unbinding service...
08-30 11:36:52.714  1017  1140 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 11:36:52.714  1017  1140 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-30 11:36:52.724  1017  1140 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:52.724  1017  1140 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:36:52.724  1017  1140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-30 11:36:52.724  3682  3682 I Hs20UtilService: Starting #8
08-30 11:36:52.724  1017  1047 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
08-30 11:36:52.724  1319  1319 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-30 11:36:52.724  1319  1319 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-30 11:36:52.724  3682  3722 I Hs20UtilService: Message received 5007
08-30 11:36:52.724  1319  1319 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-30 11:36:52.724  1319  1319 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-30 11:36:52.724  1319  1319 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 11:36:52.724  1319  1319 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-30 11:36:52.724  1319  3112 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-30 11:36:52.724  1017  1047 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-30 11:36:52.734  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-30 11:36:52.734  1017  1017 I InputMethodManagerService: [BT Setting State] State =10
08-30 11:36:52.734  1017  1017 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
08-30 11:36:52.744  1177  1177 D BluetoothAdapter: 690758941: getState() :  mService = null. Returning STATE_OFF
08-30 11:36:52.744  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-30 11:36:52.744  1177  1717 D BluetoothAdapter: 690758941: getState() :  mService = null. Returning STATE_OFF
08-30 11:36:52.744  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:36:52.744  1177  1177 D BluetoothTile:  getBluetoothState : 10
08-30 11:36:52.744  1177  1177 D BluetoothAdapter: 690758941: getState() :  mService = null. Returning STATE_OFF
08-30 11:36:52.744  1177  1177 D BluetoothAdapter: 690758941: getState() :  mService = null. Returning STATE_OFF
08-30 11:36:52.744  1017  1560 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-30 11:36:52.744  1177  1717 D BluetoothAdapter: 690758941: getState() :  mService = null. Returning STATE_OFF
08-30 11:36:52.744  1770  1770 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
08-30 11:36:52.744  1017  1497 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-30 11:36:52.744  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-30 11:36:52.744  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-30 11:36:52.744  1929  2106 D BluetoothAdapter: 997781882: getState() :  mService = null. Returning STATE_OFF
08-30 11:36:52.744  1929  2106 D BluetoothAdapter: 997781882: getState() :  mService = null. Returning STATE_OFF
08-30 11:36:52.744  1319  1319 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:36:52.754  2141  2141 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-30 11:36:52.754  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 11:36:52.754  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 11:36:52.754  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
08-30 11:36:52.754  1017  1217 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:52.754  1017  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:52.754  1017  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
08-30 11:36:52.754  1017  1217 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
08-30 11:36:52.764  6470  6505 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-30 11:36:52.764  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:36:52.764  1017  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:52.764  1017  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:52.764  1017  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:52.764  1017  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:52.764  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:36:52.774  6509  6509 E Zygote  : MountEmulatedStorage()
,08-30 11:36:52.774  6509  6509 E Zygote  : v2
08-30 11:36:52.774  6509  6509 I libpersona: KNOX_SDCARD checking this for 10104
08-30 11:36:52.774  6509  6509 I libpersona: KNOX_SDCARD not a persona
08-30 11:36:52.774  6509  6509 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 11:36:52.784  6509  6509 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-30 11:36:52.784  6509  6509 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-30 11:36:52.784  1017  1217 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6509 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-30 11:36:52.794  1017  3091 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 11:36:52.794  1017  3091 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-30 11:36:52.794  1017  3091 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:52.794  1017  3091 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:52.794  1017  3091 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:36:52.794  1017  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-30 11:36:52.794  1017  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-30 11:36:52.794  1017  1128 E WifiConfigStore: setLastSelectedConfiguration -1
,08-30 11:36:52.794  2649  2733 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-30 11:36:52.794  2649  2649 I GKI_LINUX: GKI_exit_task 1 done
08-30 11:36:52.794  2649  2649 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-30 11:36:52.794  2649  2649 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-30 11:36:52.794  1017  1350 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 11:36:52.794  1017  1350 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:52.794  1017  1350 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:52.794  1017  1350 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-30 11:36:52.804  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020543/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 11:36:52.804  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-30 11:36:52.804  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:52.804  2649  2649 I art     : System.exit called, status: 0
08-30 11:36:52.804  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:52.804  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:52.804  2649  2649 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-30 11:36:52.804  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:52.804  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 11:36:52.804  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-30 11:36:52.804  1177  1717 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-30 11:36:52.804  6509  6509 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 11:36:52.804  6509  6509 D ActivityThread: Added TimaKeyStore provider
08-30 11:36:52.804  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-30 11:36:52.804  1177  1177 D HotspotTile: onReceive : 1, 0
,08-30 11:36:52.814  1319  1319 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-30 11:36:52.814  1929  2106 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:36:52.814  1017  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 11:36:52.814  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:36:52.814  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:36:52.824  1017  1017 I ApplicationPolicy: updateDataUsageMap
,08-30 11:36:52.834  1017  1042 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 11:36:52.844  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:36:52.844  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:36:52.844  3173  3173 I DBG_DM  : [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,08-30 11:36:52.854  6509  6509 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-30 11:36:52.854  3173  3173 I DBG_DM  : [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,08-30 11:36:52.874  1017  1497 I ActivityManager: Process com.android.bluetooth (pid 2649)(adj 0) has died(36,1097)
,08-30 11:36:53.024  6509  6537 I Babel   : MmsConfig: mnc/mcc: 0/0
,08-30 11:36:53.024  6509  6537 I Babel   : MmsConfig.loadMmsSettings
08-30 11:36:53.024  6509  6537 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
08-30 11:36:53.024  6509  6537 I Babel   : MmsConfig.loadFromDatabase
,08-30 11:36:53.034  6509  6537 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-30 11:36:53.034  6509  6537 I Babel   : MmsConfig.loadFromResources
,08-30 11:36:53.034  6509  6537 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-30 11:36:53.034  1017  1497 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
08-30 11:36:53.034  1017  1497 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-30 11:36:53.044  1017  1497 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:53.044  6509  6537 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,08-30 11:36:53.044  1017  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:53.044  1017  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-30 11:36:53.044  6509  6509 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 11:36:53.084  6509  6509 I Babel_StickerModule: App launched.
,08-30 11:36:53.094  1319  1319 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-30 11:36:53.094  1319  1319 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 11:36:53.094  1319  1319 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 11:36:53.094  1319  1319 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-30 11:36:53.094  1319  1319 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 11:36:53.094  1319  1319 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-30 11:36:53.094  1319  3112 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 11:36:53.094  1017  1350 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-30 11:36:53.094  1017  1350 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:36:53.094  1017  1350 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:53.094  1017  1350 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:36:53.094  1017  1350 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:36:53.104  6539  6539 E Zygote  : MountEmulatedStorage()
,08-30 11:36:53.114  6539  6539 E Zygote  : v2
,08-30 11:36:53.114  6539  6539 I libpersona: KNOX_SDCARD checking this for 10068
08-30 11:36:53.114  6539  6539 I libpersona: KNOX_SDCARD not a persona
08-30 11:36:53.114  6539  6539 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 11:36:53.114   285  1014 W QCamera2Factory: getCameraInfo: E, camera_id = 0
08-30 11:36:53.114  1017  1350 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6539 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 11:36:53.114   285  1014 W QCamera2Factory: getCameraInfo: X
,08-30 11:36:53.114  6539  6539 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 11:36:53.114  6539  6539 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 11:36:53.114   285   695 W QCamera2Factory: getCameraInfo: E, camera_id = 1
08-30 11:36:53.114   285   695 W QCamera2Factory: getCameraInfo: X
,08-30 11:36:53.134  6539  6539 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 11:36:53.134  6539  6539 D ActivityThread: Added TimaKeyStore provider
,08-30 11:36:53.144  6539  6539 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-30 11:36:53.144  6509  6509 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 11:36:53.154  6509  6509 W AudioCapabilities: Unsupported mime audio/evrc
,08-30 11:36:53.154  6509  6509 W AudioCapabilities: Unsupported mime audio/qcelp
,08-30 11:36:53.164  6509  6509 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-30 11:36:53.164  6509  6509 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-30 11:36:53.164  6539  6539 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 11:36:53.164  6509  6509 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-30 11:36:53.164  6509  6509 W AudioCapabilities: Unsupported mime audio/x-ima
,08-30 11:36:53.174  6509  6509 W AudioCapabilities: Unsupported mime audio/qcelp
,08-30 11:36:53.174  6539  6539 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-30 11:36:53.174  6509  6509 W AudioCapabilities: Unsupported mime audio/evrc
,08-30 11:36:53.194  6509  6509 W VideoCapabilities: Unsupported mime video/wvc1
,08-30 11:36:53.194  6509  6509 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-30 11:36:53.204  6509  6509 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-30 11:36:53.204  6539  6539 D FileShare-Client: Outbound.stopDelayTimer - 
,08-30 11:36:53.204  1017  3289 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-30 11:36:53.204  6509  6509 W VideoCapabilities: Unsupported mime video/wvc1
,08-30 11:36:53.204  1017  3289 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:53.204  6509  6509 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-30 11:36:53.204  1017  3289 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:36:53.204  1017  3289 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:53.204  1017  3289 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:36:53.224  6554  6554 E Zygote  : MountEmulatedStorage(),
,08-30 11:36:53.224  6554  6554 E Zygote  : v2,
,08-30 11:36:53.224  6554  6554 I libpersona: KNOX_SDCARD checking this for 10069
,08-30 11:36:53.224  6554  6554 I libpersona: KNOX_SDCARD not a persona
,08-30 11:36:53.224  6554  6554 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
08-30 11:36:53.224  6509  6509 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
08-30 11:36:53.224  1017  3289 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6554 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 11:36:53.224  1017  3289 I ActivityManager: Killing 5881:com.sec.pcw.device/1000 (adj 15): empty #31
,08-30 11:36:53.234  6509  6509 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-30 11:36:53.234  6509  6509 W VideoCapabilities: Unsupported mime video/mp43
,08-30 11:36:53.234  6509  6509 W VideoCapabilities: Unsupported mime video/sorenson
,08-30 11:36:53.244  6554  6554 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 11:36:53.244  6554  6554 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 11:36:53.244  6509  6509 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-30 11:36:53.264  6554  6554 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 11:36:53.264  6554  6554 D ActivityThread: Added TimaKeyStore provider
,08-30 11:36:53.264  6509  6509 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-30 11:36:53.294  6554  6554 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 11:36:53.294   290   290 E SMD     : DCD OFF
,08-30 11:36:53.294  1017  1030 I ActivityManager: Killing 5208:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,08-30 11:36:53.304  1017  1477 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,08-30 11:36:53.304  1017  1477 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,08-30 11:36:53.304  1017  1477 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:53.304  1017  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:53.304  1017  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
08-30 11:36:53.304  1017  1501 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-30 11:36:53.304  1017  1501 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 11:36:53.304  1017  1501 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:53.304  1017  1501 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:36:53.304  1017  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 11:36:53.314  1017  1045 D Tethering: interfaceRemoved wlan0
08-30 11:36:53.314  1017  1045 E Tethering: attempting to remove unknown iface (wlan0), ignoring
08-30 11:36:53.314  1319  1319 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-30 11:36:53.314  1319  1319 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 11:36:53.314  3682  3682 I Hs20UtilService: Starting #9
08-30 11:36:53.314  3682  3722 I Hs20UtilService: Message received 5007
,08-30 11:36:53.314  1319  1319 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 11:36:53.314  1319  1319 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-30 11:36:53.314  1319  1319 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 11:36:53.314  1319  1319 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-30 11:36:53.314  1319  3112 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 11:36:53.324  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:53.324  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:36:53.324  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 11:36:53.324  1017  1477 I ActivityManager: Killing 5725:com.google.android.apps.plus/u0a120 (adj 15): empty #31
,08-30 11:36:53.394  1017  1045 D Tethering: interfaceRemoved p2p0
,08-30 11:36:53.394  1017  1045 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-30 11:36:53.644  1017  1350 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-30 11:36:53.644  1017  1350 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 11:36:53.654  1017  1350 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:53.654  1017  1350 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:36:53.654  1017  1350 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 11:36:53.654  1017  1560 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,08-30 11:36:53.654  1017  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:36:53.654  1017  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:53.654  1017  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:36:53.654  1017  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:36:53.654  3682  3682 I Hs20UtilService: Starting #10,
,08-30 11:36:53.654  3682  3722 I Hs20UtilService: Message received 5011
,08-30 11:36:53.664  6571  6571 E Zygote  : MountEmulatedStorage()
,08-30 11:36:53.664  6571  6571 E Zygote  : v2
08-30 11:36:53.664  6571  6571 I libpersona: KNOX_SDCARD checking this for 1000
08-30 11:36:53.664  6571  6571 I libpersona: KNOX_SDCARD not a persona
,08-30 11:36:53.664  6571  6571 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 11:36:53.664  1017  1560 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6571 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,08-30 11:36:53.674  6571  6571 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-30 11:36:53.674  6571  6571 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 11:36:53.694  6571  6571 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 11:36:53.694  6571  6571 D ActivityThread: Added TimaKeyStore provider
,08-30 11:36:53.724  6571  6571 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-30 11:36:53.724  6571  6571 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-30 11:36:53.724  6571  6571 D SecurityLogAgent: StateMachine : Current State = 1
,08-30 11:36:53.724  6571  6571 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 11:36:53.724  1017  1140 I ActivityManager: Killing 5917:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,08-30 11:36:53.734  1017  1497 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:53.734  1017  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:36:53.734  1017  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 11:36:53.734  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:53.734  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:36:53.734  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 11:36:53.744  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:53.744  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:36:53.744  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 11:36:53.744  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:53.744  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:36:53.744  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 11:36:53.744  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:53.744  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 11:36:53.744  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 11:36:53.754  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:53.754  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:36:53.754  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 11:36:53.754  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:53.754  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:36:53.754  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 11:36:53.754  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:53.754  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:36:53.754  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 11:36:53.764  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:53.764  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:36:53.764  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 11:36:53.764  1017  1017 W ActivityManager: userId = 0, bbcId = -10000,
08-30 11:36:53.764  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:36:53.764  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 11:36:53.764  1017  1017 W ActivityManager: userId = 0, bbcId = -10000,
08-30 11:36:53.764  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:36:53.764  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 11:36:53.774  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:53.774  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:36:53.774  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 11:36:53.774  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:53.774  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-30 11:36:53.774  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 11:36:53.774  1017  1017 W ActivityManager: userId = 0, bbcId = -10000,
08-30 11:36:53.774  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:36:53.774  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 11:36:53.784  1319  1319 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 11:36:53.784  1017  1477 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-30 11:36:53.784  1017  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-30 11:36:53.794  1017  1477 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:53.794  1017  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:36:53.794  1017  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-30 11:36:53.794  1319  1319 D DockEventReceiver: finishStartingService: stopping service
,08-30 11:36:53.794  1319  1319 D BluetoothNotiBroadcastReceiver: onReceive
08-30 11:36:53.804  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 11:36:53.804  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-30 11:36:53.804  1017  1477 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-30 11:36:53.804  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-30 11:36:53.804  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:53.804  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:53.804  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:36:53.814  6590  6590 E Zygote  : MountEmulatedStorage(),
,08-30 11:36:53.814  6590  6590 E Zygote  : v2
08-30 11:36:53.814  6590  6590 I libpersona: KNOX_SDCARD checking this for 1002,
,08-30 11:36:53.814  6590  6590 I libpersona: KNOX_SDCARD not a persona
,08-30 11:36:53.824  1017  1477 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6590 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-30 11:36:53.824  6590  6590 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 11:36:53.824  6590  6590 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-30 11:36:53.824  6590  6590 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 11:36:53.844  6590  6590 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 11:36:53.844  6590  6590 D ActivityThread: Added TimaKeyStore provider
,08-30 11:36:53.864  6590  6590 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-30 11:36:53.864  6590  6590 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 11:36:53.884  6590  6590 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-30 11:36:53.914  6590  6590 D BtSettings.ProfileConfig: Adding GattService
,08-30 11:36:53.914  6590  6590 D BtSettings.ProfileConfig: Adding HeadsetService
08-30 11:36:53.914  6590  6590 D BtSettings.ProfileConfig: Adding A2dpService
,08-30 11:36:53.914  6590  6590 D BtSettings.ProfileConfig: Adding HidService
08-30 11:36:53.914  6590  6590 D BtSettings.ProfileConfig: Adding HealthService
08-30 11:36:53.914  6590  6590 D BtSettings.ProfileConfig: Adding PanService
,08-30 11:36:53.914  6590  6590 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-30 11:36:53.914  6590  6590 D BtSettings.ProfileConfig: Adding SapService
08-30 11:36:53.914  6590  6590 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-30 11:36:53.914  6590  6590 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-30 11:36:53.914  6590  6590 D BtSettings.ProfileConfig: Adding SapClientService
08-30 11:36:53.914  6590  6590 D BtSettings.ProfileConfig: Adding HidDevService
,08-30 11:36:53.914  6590  6590 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-30 11:36:53.924  1017  1030 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-30 11:36:53.924  1017  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 11:36:53.924  1017  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 11:36:53.924  1017  1030 D SettingsProvider: selectionArgs: false
,08-30 11:36:53.924  1017  1030 D SettingsProvider: selectionArgs: 1002
08-30 11:36:53.924  1017  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-30 11:36:53.924  1017  1030 D SettingsProvider: ret = -1
,08-30 11:36:53.924  1017  1501 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-30 11:36:53.924  1017  1501 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 11:36:53.924  1017  1501 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 11:36:53.924  1017  1501 D SettingsProvider: selectionArgs: false
08-30 11:36:53.924  1017  1501 D SettingsProvider: selectionArgs: 1002
08-30 11:36:53.924  1017  1501 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 11:36:53.924  1017  1501 D SettingsProvider: ret = -1
,08-30 11:36:53.924  1017  1497 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-30 11:36:53.924  1017  1497 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 11:36:53.924  1017  1497 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-30 11:36:53.924  1017  1497 D SettingsProvider: selectionArgs: false
08-30 11:36:53.924  1017  1497 D SettingsProvider: selectionArgs: 1002
08-30 11:36:53.924  1017  1497 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 11:36:53.924  1017  1497 D SettingsProvider: ret = -1
,08-30 11:36:53.924  1017  1477 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-30 11:36:53.924  1017  1477 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 11:36:53.924  1017  1477 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 11:36:53.924  1017  1477 D SettingsProvider: selectionArgs: false
08-30 11:36:53.924  1017  1477 D SettingsProvider: selectionArgs: 1002
08-30 11:36:53.924  1017  1477 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 11:36:53.924  1017  1477 D SettingsProvider: ret = -1
,08-30 11:36:53.924  1017  1029 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
,08-30 11:36:53.924  1017  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 11:36:53.924  1017  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 11:36:53.924  1017  1029 D SettingsProvider: selectionArgs: false
08-30 11:36:53.924  1017  1029 D SettingsProvider: selectionArgs: 1002
,08-30 11:36:53.924  1017  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 11:36:53.924  1017  1029 D SettingsProvider: ret = -1
,08-30 11:36:53.924  1017  1350 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-30 11:36:53.924  1017  1350 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 11:36:53.924  1017  1350 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-30 11:36:53.924  1017  1350 D SettingsProvider: selectionArgs: false
08-30 11:36:53.924  1017  1350 D SettingsProvider: selectionArgs: 1002
08-30 11:36:53.924  1017  1350 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 11:36:53.924  1017  1350 D SettingsProvider: ret = -1
08-30 11:36:53.924  1017  1217 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,08-30 11:36:53.924  1017  1217 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 11:36:53.924  1017  1217 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 11:36:53.924  1017  1217 D SettingsProvider: selectionArgs: false
08-30 11:36:53.924  1017  1217 D SettingsProvider: selectionArgs: 1002
08-30 11:36:53.924  1017  1217 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 11:36:53.924  1017  1217 D SettingsProvider: ret = -1
,08-30 11:36:53.934  1017  3091 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-30 11:36:53.934  1017  3091 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 11:36:53.934  1017  3091 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 11:36:53.934  1017  3091 D SettingsProvider: selectionArgs: false
,08-30 11:36:53.934  1017  3091 D SettingsProvider: selectionArgs: 1002
08-30 11:36:53.934  1017  3091 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 11:36:53.934  1017  3091 D SettingsProvider: ret = -1
08-30 11:36:53.934  1017  1560 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-30 11:36:53.934  1017  1560 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
08-30 11:36:53.934  1017  1560 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 11:36:53.934  1017  1560 D SettingsProvider: selectionArgs: false
08-30 11:36:53.934  1017  1560 D SettingsProvider: selectionArgs: 1002
08-30 11:36:53.934  1017  1560 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 11:36:53.934  1017  1560 D SettingsProvider: ret = -1
,08-30 11:36:53.934  1017  1478 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-30 11:36:53.934  1017  1478 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 11:36:53.934  1017  1478 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 11:36:53.934  1017  1478 D SettingsProvider: selectionArgs: false
08-30 11:36:53.934  1017  1478 D SettingsProvider: selectionArgs: 1002
,08-30 11:36:53.934  1017  1478 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 11:36:53.934  1017  1478 D SettingsProvider: ret = -1
08-30 11:36:53.934  1017  3289 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-30 11:36:53.934  1017  3289 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 11:36:53.934  1017  3289 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 11:36:53.934  1017  3289 D SettingsProvider: selectionArgs: false
08-30 11:36:53.934  1017  3289 D SettingsProvider: selectionArgs: 1002
,08-30 11:36:53.934  1017  3289 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 11:36:53.934  1017  3289 D SettingsProvider: ret = -1
,08-30 11:36:53.934  1017  1140 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-30 11:36:53.934  1017  1140 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 11:36:53.934  1017  1140 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-30 11:36:53.934  1017  1140 D SettingsProvider: selectionArgs: false
08-30 11:36:53.934  1017  1140 D SettingsProvider: selectionArgs: 1002
08-30 11:36:53.934  1017  1140 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 11:36:53.934  1017  1140 D SettingsProvider: ret = -1
,08-30 11:36:53.944  1017  3440 I ActivityManager: Killing 5660:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,08-30 11:36:53.944  1929  1929 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-30 11:36:53.944  1017  1029 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 11:36:53.944  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-30 11:36:53.944  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:53.944  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:53.944  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:36:53.954  1929  1929 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-30 11:36:53.964  1929  6607 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-30 11:36:53.964  1017  1350 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-30 11:36:53.964  1017  1350 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 11:36:53.964  1017  1350 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:53.964  1017  1350 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:36:53.964  1017  1350 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 11:36:53.964  3682  3682 I Hs20UtilService: Starting #11
,08-30 11:36:53.964  3682  3722 I Hs20UtilService: Message received 5011
,08-30 11:36:53.964  6571  6571 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-30 11:36:53.964  6571  6571 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-30 11:36:53.964  6571  6571 D SecurityLogAgent: StateMachine : Current State = 1
08-30 11:36:53.964  6571  6571 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 11:36:53.974  1017  1350 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-30 11:36:53.974  1017  1350 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-30 11:36:53.974  1017  1350 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:53.974  1017  1350 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:36:53.974  1017  1350 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:36:53.994  6608  6608 E Zygote  : MountEmulatedStorage(),
08-30 11:36:53.994  6608  6608 E Zygote  : v2
08-30 11:36:53.994  6608  6608 I libpersona: KNOX_SDCARD checking this for 1000
08-30 11:36:53.994  6608  6608 I libpersona: KNOX_SDCARD not a persona
,08-30 11:36:53.994  6608  6608 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 11:36:53.994  1017  1350 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6608 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
08-30 11:36:53.994  6608  6608 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 11:36:53.994  6608  6608 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-30 11:36:54.014   309   309 I art     : Explicit concurrent mark sweep GC freed 8732(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 626us total 21.772ms,
,08-30 11:36:54.024  6608  6608 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 11:36:54.024  6608  6608 D ActivityThread: Added TimaKeyStore provider
,08-30 11:36:54.044   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 634us total 23.058ms
,08-30 11:36:54.054  6608  6608 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-30 11:36:54.054  6608  6608 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-30 11:36:54.054  6608  6608 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-30 11:36:54.054  1929  2091 I art     : Explicit concurrent mark sweep GC freed 50089(2MB) AllocSpace objects, 52(2MB) LOS objects, 40% free, 14MB/24MB, paused 1.703ms total 95.539ms
,08-30 11:36:54.054  1017  1477 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-30 11:36:54.054   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 620us total 17.062ms
,08-30 11:36:54.064  1017  1477 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:54.064  1017  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:54.064  1017  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:36:54.074  6608  6608 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-30 11:36:54.074  6608  6608 I PCWCLIENTTRACE_PushUtil: sales region : global
,08-30 11:36:54.074  6608  6608 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-30 11:36:54.074  6608  6608 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-30 11:36:54.074  1017  3091 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
08-30 11:36:54.074  1017  3091 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
08-30 11:36:54.074  6608  6623 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-30 11:36:54.074  1017  3091 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,08-30 11:36:54.084  1017  3091 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:54.084  1017  3091 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:54.084  1017  3091 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:54.084  1017  3091 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:36:54.094  6625  6625 E Zygote  : MountEmulatedStorage(),
08-30 11:36:54.094  6625  6625 E Zygote  : v2
08-30 11:36:54.094  6625  6625 I libpersona: KNOX_SDCARD checking this for 10111
08-30 11:36:54.094  6625  6625 I libpersona: KNOX_SDCARD not a persona,
08-30 11:36:54.094  6625  6625 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 11:36:54.094  1017  3091 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6625 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-30 11:36:54.094  1017  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
08-30 11:36:54.094  6625  6625 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 11:36:54.094  6625  6625 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
08-30 11:36:54.094  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-30 11:36:54.094  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:54.094  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-30 11:36:54.094  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:36:54.114  6636  6636 E Zygote  : MountEmulatedStorage()
08-30 11:36:54.114  6636  6636 E Zygote  : v2
08-30 11:36:54.114  6636  6636 I libpersona: KNOX_SDCARD checking this for 10009
,08-30 11:36:54.114  6636  6636 I libpersona: KNOX_SDCARD not a persona
08-30 11:36:54.114  1017  1043 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6636 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 11:36:54.114  6636  6636 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 11:36:54.114  6636  6636 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-30 11:36:54.114  1017  1043 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
08-30 11:36:54.114  1728  1728 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
08-30 11:36:54.114  6625  6625 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 11:36:54.124  6636  6636 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-30 11:36:54.124  6625  6625 D ActivityThread: Added TimaKeyStore provider
08-30 11:36:54.124  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:54.124  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:54.124  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:54.124  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:36:54.134  6655  6655 E Zygote  : MountEmulatedStorage()
08-30 11:36:54.134  6655  6655 I libpersona: KNOX_SDCARD checking this for 10145
08-30 11:36:54.134  6655  6655 E Zygote  : v2
08-30 11:36:54.134  6655  6655 I libpersona: KNOX_SDCARD not a persona
,08-30 11:36:54.134  6655  6655 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-30 11:36:54.134  6636  6636 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 11:36:54.134  6636  6636 D ActivityThread: Added TimaKeyStore provider
08-30 11:36:54.144  1017  1043 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6655 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
08-30 11:36:54.144  6655  6655 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
08-30 11:36:54.144  1017  1217 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-30 11:36:54.144  6655  6655 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 11:36:54.144  1017  1217 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:54.144  1017  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:54.144  1017  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,08-30 11:36:54.154  1929  6607 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-30 11:36:54.154  1728  1728 D accuweather: [KK AccuPhone]>>> U:4106 [0:0] getPWC : surface = 0, remote = 1
,08-30 11:36:54.154  1728  1728 D accuweather: [KK AccuPhone]>>> U:4284 [0:0] Store PWC = 1
08-30 11:36:54.154  1728  1728 D accuweather: [KK AccuPhone]>>> U:4158 [0:0] addPWC = 1
08-30 11:36:54.154  1728  1728 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-30 11:36:54.164  1728  1728 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-30 11:36:54.174  1297  1308 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,08-30 11:36:54.174  1728  1728 D accuweather: [KK AccuPhone]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,08-30 11:36:54.174  1017  1560 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-30 11:36:54.174  1017  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:54.174  1017  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:54.174  1017  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:54.174  1017  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:36:54.184  6655  6655 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 11:36:54.184  6655  6655 D ActivityThread: Added TimaKeyStore provider,
,08-30 11:36:54.194  1017  1560 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6670 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 11:36:54.194  6670  6670 E Zygote  : MountEmulatedStorage()
08-30 11:36:54.194  6670  6670 E Zygote  : v2
08-30 11:36:54.194  6670  6670 I libpersona: KNOX_SDCARD checking this for 10081
,08-30 11:36:54.194  6670  6670 I libpersona: KNOX_SDCARD not a persona
08-30 11:36:54.194  6670  6670 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
08-30 11:36:54.204  6670  6670 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-30 11:36:54.204  6670  6670 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
08-30 11:36:54.204  1728  1728 D accuweather: [KK AccuPhone]>>> U:4250 [0:0] Store PWC succeed
,08-30 11:36:54.224  6670  6670 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 11:36:54.224  6670  6670 D ActivityThread: Added TimaKeyStore provider
,08-30 11:36:54.224  6655  6655 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-30 11:36:54.234  6655  6655 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 11:36:54.234  6655  6655 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-30 11:36:54.234  6655  6655 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-30 11:36:54.234  6655  6655 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-30 11:36:54.244  1017  1350 I ActivityManager: Killing 5935:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,08-30 11:36:54.254  3730  3730 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 30 11:36:54 GMT+02:00 2016
,08-30 11:36:54.254  1017  1029 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-30 11:36:54.254  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-30 11:36:54.254  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:54.254  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:36:54.254  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-30 11:36:54.254  6625  6625 I MusicStore: Database version: 108
,08-30 11:36:54.264  3730  3730 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,08-30 11:36:54.264  1017  1217 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-30 11:36:54.264  1017  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:54.264  1017  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:54.264  1017  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:54.264  1017  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:36:54.264  1017  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-30 11:36:54.284  6691  6691 E Zygote  : MountEmulatedStorage()
08-30 11:36:54.284  6691  6691 I libpersona: KNOX_SDCARD checking this for 10034
08-30 11:36:54.284  6691  6691 E Zygote  : v2
08-30 11:36:54.284  6691  6691 I libpersona: KNOX_SDCARD not a persona
08-30 11:36:54.284  6691  6691 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-30 11:36:54.284  1017  1217 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6691 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,08-30 11:36:54.284  6691  6691 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 11:36:54.284  6691  6691 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 11:36:54.284  3730  3730 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,08-30 11:36:54.284  3730  3730 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-30 11:36:54.294  3730  3730 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
08-30 11:36:54.294  1017  1477 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-30 11:36:54.294  1017  1030 D RCPManagerService: exchangeData() failure , invalid userId
08-30 11:36:54.294  1017  1477 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
08-30 11:36:54.294  1017  1477 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:54.294  1017  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:54.294  1017  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 11:36:54.304  3730  6689 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-30 11:36:54.304  3730  6689 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-30 11:36:54.304  6691  6691 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 11:36:54.304  6691  6691 D ActivityThread: Added TimaKeyStore provider
,08-30 11:36:54.314  3730  6689 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-30 11:36:54.314  3730  6689 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,08-30 11:36:54.324  3730  3730 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,08-30 11:36:54.324  1017  1560 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 11:36:54.354  6691  6691 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-30 11:36:54.354  1017  1140 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-30 11:36:54.354  1017  1140 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:54.354  1017  1140 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:54.354  1017  1140 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:54.354  1017  1140 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:36:54.374  6712  6712 E Zygote  : MountEmulatedStorage()
08-30 11:36:54.374  6712  6712 E Zygote  : v2
,08-30 11:36:54.374  6712  6712 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-30 11:36:54.374  6712  6712 I libpersona: KNOX_SDCARD checking this for 10113
08-30 11:36:54.374  6712  6712 I libpersona: KNOX_SDCARD not a persona
08-30 11:36:54.374  1017  1140 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6712 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 11:36:54.374  1017  1140 I ActivityManager: Killing 5693:com.sec.knox.bridge/1000 (adj 15): empty #31
,08-30 11:36:54.374  6712  6712 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 11:36:54.374  6712  6712 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-30 11:36:54.384  3239  6719 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-30 11:36:54.394  3239  6719 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-30 11:36:54.394  6625  6625 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-30 11:36:54.394  6625  6625 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-30 11:36:54.394  1017  1029 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 11:36:54.394  3239  6719 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-30 11:36:54.394  3239  6719 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,08-30 11:36:54.404  5968  5968 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
08-30 11:36:54.404  6712  6712 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 11:36:54.404  6712  6712 D ActivityThread: Added TimaKeyStore provider
,08-30 11:36:54.404  3239  6719 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-30 11:36:54.404  6155  6155 I SA      : [DM] init START
,08-30 11:36:54.414  1017  1217 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,08-30 11:36:54.414  1017  1217 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,08-30 11:36:54.414  6155  6155 I SA      : [DM] This device is not a Vodafone
08-30 11:36:54.414  1017  1030 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 11:36:54.414  1017  1217 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:54.414  1017  1217 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-30 11:36:54.414  1017  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-30 11:36:54.424  6155  6155 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,08-30 11:36:54.424  6155  6155 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,08-30 11:36:54.424  6155  6155 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
08-30 11:36:54.424  6155  6155 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,08-30 11:36:54.424  6155  6155 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
08-30 11:36:54.424  6155  6155 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
08-30 11:36:54.424  6155  6155 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,08-30 11:36:54.434  6155  6155 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-30 11:36:54.434  6155  6155 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,08-30 11:36:54.434  6155  6155 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-30 11:36:54.434  6155  6155 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,08-30 11:36:54.434  6155  6155 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-30 11:36:54.444  5968  6730 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-30 11:36:54.444  6155  6155 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
08-30 11:36:54.444  6155  6155 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
08-30 11:36:54.444  6155  6155 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-30 11:36:54.444  6155  6155 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-30 11:36:54.444  6155  6155 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
08-30 11:36:54.444  6155  6155 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
08-30 11:36:54.444  6155  6155 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
08-30 11:36:54.444  6155  6155 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
08-30 11:36:54.444  6155  6155 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
08-30 11:36:54.444  6155  6155 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
08-30 11:36:54.444  6155  6155 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
08-30 11:36:54.444  6155  6155 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
08-30 11:36:54.444  6155  6155 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,08-30 11:36:54.444  6155  6155 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75),
,08-30 11:36:54.454  6625  6625 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...,
,08-30 11:36:54.464  6155  6155 I SA      : [SCU] isHaveSA() - false
,08-30 11:36:54.464  6155  6155 I SA      : support phone number id : false
08-30 11:36:54.464  6155  6155 I SA      : [DM] Supports Ref Jpn : true
,08-30 11:36:54.464  6155  6155 I SA      : [DM] init END
08-30 11:36:54.464  6155  6155 I SA      : [OR] onReceive log=[SA = 2.1.0240 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOJ6 PSS = 4.978878039476607  ]
,08-30 11:36:54.474  6155  6155 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,08-30 11:36:54.474  6155  6155 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-30 11:36:54.474  6155  6155 I SA      : [SLFUCHKMGR] constructor called
,08-30 11:36:54.484  6155  6155 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-30 11:36:54.484  6155  6155 I SA      : [OR] == isSIMCardReady false ==
,08-30 11:36:54.484  6155  6155 I SA      : [SCU] == networkStateCheck == false
,08-30 11:36:54.484  6155  6155 I SA      : [OR] onReceive END
,08-30 11:36:54.494  1227  1227 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-30 11:36:54.504  6053  6062 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-30 11:36:54.504  6625  6625 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-30 11:36:54.514  6625  6625 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@21ecb268: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-30 11:36:54.514  6625  6625 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-30 11:36:54.514  6625  6625 D AndroidMusic: GMSCore installation verified
,08-30 11:36:54.514  6053  6062 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
,08-30 11:36:54.514  6053  6062 D BadgeProvider: sendNotify, [notify] : null
08-30 11:36:54.514  6053  6062 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-30 11:36:54.514  6053  6062 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-30 11:36:54.514  6053  6062 D BadgeProvider: update, [UpdateCount] : 1
08-30 11:36:54.514  1479  1479 D Launcher.Model: reloadBadges entered.
,08-30 11:36:54.534  1017  1497 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-30 11:36:54.534  1017  1497 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,08-30 11:36:54.534  1017  1497 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:54.534  1017  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:54.534  1017  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 11:36:54.534  1017  1140 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 11:36:54.534  1017  1350 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 11:36:54.544  6625  6625 I ConfigStore: Config Database version: 1
,08-30 11:36:54.574  1017  1217 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 11:36:54.584  1017  1029 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 11:36:54.584  6571  6571 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-30 11:36:54.584  6571  6571 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-30 11:36:54.584  6571  6571 D SecurityLogAgent: StateMachine : Current State = 1
08-30 11:36:54.584  6571  6571 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 11:36:54.584  1017  1478 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,08-30 11:36:54.594  1017  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:36:54.594  1017  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:54.594  1017  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:54.594  1017  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:36:54.614  6740  6740 E Zygote  : MountEmulatedStorage(),
08-30 11:36:54.614  6740  6740 E Zygote  : v2
08-30 11:36:54.614  6740  6740 I libpersona: KNOX_SDCARD checking this for 10159
08-30 11:36:54.614  6740  6740 I libpersona: KNOX_SDCARD not a persona
,08-30 11:36:54.614  6740  6740 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 11:36:54.614  6740  6740 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 11:36:54.614  6740  6740 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
08-30 11:36:54.624  1017  1478 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6740 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 11:36:54.644  6740  6740 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 11:36:54.644  6740  6740 D ActivityThread: Added TimaKeyStore provider
,08-30 11:36:54.664   256   539 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-30 11:36:54.664   256   539 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 11:36:54.664  6625  6625 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-30 11:36:54.664   256   539 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-30 11:36:54.674   256   539 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 11:36:54.674  6625  6625 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-30 11:36:54.674   256   539 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-30 11:36:54.674   256   539 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 11:36:54.674  6625  6625 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-30 11:36:54.684  1017  1497 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,08-30 11:36:54.684  1017  1497 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,08-30 11:36:54.684  1017  1497 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:54.684  1017  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:54.684  1017  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 11:36:54.694  1017  3440 I art     : Explicit concurrent mark sweep GC freed 54082(2MB) AllocSpace objects, 4(112KB) LOS objects, 33% free, 27MB/41MB, paused 2.849ms total 168.398ms
,08-30 11:36:54.704  1017  1497 I ActivityManager: Killing 5986:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,08-30 11:36:54.714  1017  1217 I ActivityManager: Killing 4864:com.samsung.android.sm/1000 (adj 15): empty #31
,08-30 11:36:54.714  1017  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 11:36:54.714  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-30 11:36:54.714  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:54.714  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:54.714  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:36:54.724  3808  3808 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-30 11:36:54.734  3808  4685 I iu.UploadsManager: num queued entries: 0
,08-30 11:36:54.734  3808  4685 I iu.UploadsManager: num updated entries: 0
,08-30 11:36:54.734  3808  4685 I iu.SyncManager: NEXT; no task
,08-30 11:36:54.734  1017  1140 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-30 11:36:54.734  1017  1140 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,08-30 11:36:54.734  1017  1140 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:54.734  1017  1140 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:54.744  1017  1140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 11:36:54.764  1017  1560 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-30 11:36:54.764  1017  1501 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-30 11:36:54.774  1017  1478 I AudioService: getStreamVolume 3 index 0
,08-30 11:36:54.774  6625  6625 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,08-30 11:36:54.784  6625  6625 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,08-30 11:36:54.794   256   539 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-30 11:36:54.794   256   539 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 11:36:54.804  6712  6760 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-30 11:36:54.804   256   539 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-30 11:36:54.804   256   539 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 11:36:54.804  1017  1030 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-30 11:36:54.804  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-30 11:36:54.804  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:54.804  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:54.804  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 11:36:54.804  6712  6760 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-30 11:36:54.804  1017  3440 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-30 11:36:54.804  1017  3440 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,08-30 11:36:54.804  1017  3440 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:54.814  1017  3440 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:54.814  1017  3440 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 11:36:54.814  1017  1560 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-30 11:36:54.814  1017  1560 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,08-30 11:36:54.814  1017  1560 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:54.814  1017  1560 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 11:36:54.814  1017  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 11:36:54.824  1017  1501 I ActivityManager: Killing 5897:com.android.mms/u0a46 (adj 15): empty #31
,08-30 11:36:54.824  1017  3289 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-30 11:36:54.824   256   539 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-30 11:36:54.824   256   539 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 11:36:54.824  6712  6767 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-30 11:36:54.834   256   539 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-30 11:36:54.834   256   539 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 11:36:54.834  6712  6767 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-30 11:36:54.834  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-30 11:36:54.844  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:36:54.844  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:36:54.844  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:54.844  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:36:54.854  6769  6769 E Zygote  : MountEmulatedStorage(),
08-30 11:36:54.854  6769  6769 I libpersona: KNOX_SDCARD checking this for 10002
08-30 11:36:54.854  6769  6769 E Zygote  : v2
08-30 11:36:54.854  6769  6769 I libpersona: KNOX_SDCARD not a persona
08-30 11:36:54.854  6769  6769 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-30 11:36:54.854  1017  1017 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6769 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 11:36:54.854  6769  6769 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 11:36:54.864  6769  6769 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 11:36:54.864  1017  1560 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,08-30 11:36:54.864  1017  1560 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-30 11:36:54.864  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-30 11:36:54.874  1017  3440 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-30 11:36:54.884  1017  1140 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,08-30 11:36:54.884  1017  1140 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-30 11:36:54.884  1017  1140 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:54.884  1017  1140 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:54.884  1017  1140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,08-30 11:36:54.884  6769  6769 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 11:36:54.884  6769  6769 D ActivityThread: Added TimaKeyStore provider
,08-30 11:36:54.894  6625  6625 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,08-30 11:36:54.904  1017  1501 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-30 11:36:54.904  1017  1501 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-30 11:36:54.904  1017  1501 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:54.904  1017  1501 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:54.904  1017  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 11:36:54.914  1017  1029 D CountryDetector: No listener is left
,08-30 11:36:54.924  1017  1501 I ActivityManager: Killing 6070:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,08-30 11:36:54.944  1017  3091 I ActivityManager: Killing 6088:com.wsomacp/u0a25 (adj 15): empty #31
,08-30 11:36:54.954  1017  3440 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-30 11:36:54.954  1017  3440 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:36:54.954  1017  3440 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:54.954  1017  3440 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:54.954  1017  3440 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:36:54.964  6800  6800 E Zygote  : MountEmulatedStorage()
08-30 11:36:54.964  1017  3440 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6800 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
08-30 11:36:54.964  6800  6800 E Zygote  : v2
08-30 11:36:54.964  6800  6800 I libpersona: KNOX_SDCARD checking this for 1000
08-30 11:36:54.964  6800  6800 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-30 11:36:54.964  6800  6800 I libpersona: KNOX_SDCARD not a persona
,08-30 11:36:54.974  6800  6800 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-30 11:36:54.974  6800  6800 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 11:36:54.984  1017  1478 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 11:36:54.984  1017  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:54.984  1017  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:54.984  1017  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-30 11:36:54.994  6800  6800 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 11:36:55.004  6800  6800 D ActivityThread: Added TimaKeyStore provider
,08-30 11:36:55.014  6712  6712 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,08-30 11:36:55.024  6712  6712 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 2632-2633)
08-30 11:36:55.024  6712  6712 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 11:36:55.024  6712  6712 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1863d4b9}
,08-30 11:36:55.024  6712  6712 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 11:36:55.034  6712  6712 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,08-30 11:36:55.034  6800  6800 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-30 11:36:55.044  6712  6712 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-30 11:36:55.054  6712  6712 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 11:36:55.054  6712  6712 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-30 11:36:55.074  1017  1140 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-30 11:36:55.074  1017  1140 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-30 11:36:55.074  1017  1140 D SecContentProvider2: mCursor = null
,08-30 11:36:55.074  6712  6712 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,08-30 11:36:55.074  6712  6712 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
08-30 11:36:55.074  6712  6712 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,08-30 11:36:55.074  1017  1140 D WifiService: setWifiEnabled: true pid=6312, uid=10155
,08-30 11:36:55.074  1017  1140 W ActivityManager: Permission Denial: getCurrentUser() from pid=6312, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,08-30 11:36:55.074  1017  1140 W WifiService: Failed getting userId using ActivityManagerNative
08-30 11:36:55.074  1017  1140 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6312, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-30 11:36:55.074  1017  1140 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-30 11:36:55.074  1017  1140 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-30 11:36:55.074  1017  1140 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-30 11:36:55.074  1017  1140 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-30 11:36:55.074  1017  1140 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-30 11:36:55.074  1017  1140 D SettingsProvider: name = wifi_on
,08-30 11:36:55.084  6712  6712 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-30 11:36:55.084  6712  6712 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-30 11:36:55.084  6712  6712 I Adreno-EGL: Build Date: 04/06/15 Mon
08-30 11:36:55.084  6712  6712 I Adreno-EGL: Local Branch: 
08-30 11:36:55.084  6712  6712 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-30 11:36:55.084  6712  6712 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-30 11:36:55.084  6712  6712 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-30 11:36:55.084  1017  1128 E WifiHW  : ##################### set firmware type 0 #####################
,08-30 11:36:55.154  6800  6800 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-30 11:36:55.164  6800  6800 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-30 11:36:55.164  6800  6800 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-30 11:36:55.174  6800  6800 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-30 11:36:55.174  6800  6800 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-30 11:36:55.174  6800  6800 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-30 11:36:55.294  6712  6830 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-30 11:36:55.294  6712  6712 I NSApplication: Starting up...
,08-30 11:36:55.314  1017  1560 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-30 11:36:55.314  1017  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:36:55.314  1017  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:55.314  1017  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:55.314  1017  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:36:55.324  1017  1560 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6840 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-30 11:36:55.324  1017  1560 I ActivityManager: Killing 6015:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #31
,08-30 11:36:55.334  1017  1560 I ActivityManager: Killing 6123:com.sec.android.app.soundalive/u0a53 (adj 15): empty #32
,08-30 11:36:55.334  6840  6840 E Zygote  : MountEmulatedStorage()
08-30 11:36:55.334  6840  6840 E Zygote  : v2
08-30 11:36:55.334  6840  6840 I libpersona: KNOX_SDCARD checking this for 10120
08-30 11:36:55.334  6840  6840 I libpersona: KNOX_SDCARD not a persona
,08-30 11:36:55.334  6840  6840 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 11:36:55.334  6840  6840 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 11:36:55.334  6840  6840 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-30 11:36:55.354  6840  6840 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 11:36:55.354  6840  6840 D ActivityThread: Added TimaKeyStore provider
,08-30 11:36:55.374  6840  6840 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 11:36:55.434  1017  1045 D Tethering: interfaceAdded wlan0
,08-30 11:36:55.444  1017  1131 E Tethering: No numeric data
,08-30 11:36:55.444  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 11:36:55.444  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 11:36:55.444  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-30 11:36:55.444  1017  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-30 11:36:55.444  1017  1131 D Tethering: clearTetheredNotification()
08-30 11:36:55.444  1017  1131 D Tethering: InitialState.processMessage what=4
,08-30 11:36:55.444  1017  1131 E Tethering: No numeric data
,08-30 11:36:55.454  1017  1125 V NetworkStats: performPollLocked(flags=0x1)
08-30 11:36:55.454  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 11:36:55.454  1017  1045 D Tethering: interfaceAdded p2p0
,08-30 11:36:55.454  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-30 11:36:55.454  1177  1177 D HotspotTile: updateTetherState():false, false
,08-30 11:36:55.454  1017  1045 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-30 11:36:55.454  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 11:36:55.454  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 11:36:55.454  1017  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 11:36:55.454  1017  1131 D Tethering: clearTetheredNotification()
,08-30 11:36:55.454  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-30 11:36:55.454  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 11:36:55.454  1017  1125 V NetworkStats: performPollLocked() took 9ms
,08-30 11:36:55.464  1177  1177 D HotspotTile: updateTetherState():false, false
,08-30 11:36:55.464  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 11:36:55.464  1017  1125 V NetworkStats: performPollLocked(flags=0x1)
08-30 11:36:55.464  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 11:36:55.464  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-30 11:36:55.464  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
08-30 11:36:55.464  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 11:36:55.464  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 11:36:55.464  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 11:36:55.464  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 11:36:55.464   280   989 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,08-30 11:36:55.464   280   989 D SoftapController: Softap fwReload - Ok
,08-30 11:36:55.464  1017  1125 V NetworkStats: performPollLocked() took 6ms
08-30 11:36:55.464  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 11:36:55.464  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 11:36:55.464  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 11:36:55.464   280   989 D CommandListener: Setting iface cfg
08-30 11:36:55.464   280   989 D CommandListener: Trying to bring down wlan0
,08-30 11:36:55.474   280   989 D CommandListener: Clearing all IP addresses on wlan0
,08-30 11:36:55.474  1017  1128 E WifiHW  : supplicant_name : p2p_supplicant
,08-30 11:36:55.514  6858  6858 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL,
08-30 11:36:55.514  6858  6858 I wpa_supplicant: Successfully initialized wpa_supplicant
08-30 11:36:55.514  6858  6858 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-30 11:36:55.524  6858  6858 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
08-30 11:36:55.534   337   337 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6858,
08-30 11:36:55.534   337   337 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-30 11:36:55.534  6858  6858 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-30 11:36:55.534  6858  6858 I wpa_supplicant: ssSupport state is = 1
08-30 11:36:55.534  6858  6858 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-30 11:36:55.534  6858  6858 I SecureStorage: [INFO]: SPID(0x00000000)Processing data,
08-30 11:36:55.534   337   337 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6858
08-30 11:36:55.534   337   337 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-30 11:36:55.574  1017  1128 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-30 11:36:55.584  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020543/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 11:36:55.584  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-30 11:36:55.584  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-30 11:36:55.584  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:55.584  1177  1717 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi,
08-30 11:36:55.584  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 11:36:55.584  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 11:36:55.584  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:55.584  1177  1177 D HotspotTile: onReceive : 2, 0,
08-30 11:36:55.584  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-30 11:36:55.584  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-30 11:36:55.584  1319  1319 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-30 11:36:55.594  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:36:55.594  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-30 11:36:55.684  1017  1497 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-30 11:36:55.684  1017  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:55.684  1017  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:55.684  1017  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:36:55.684  1017  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:36:55.704   337   337 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,08-30 11:36:55.704  6864  6864 E Zygote  : MountEmulatedStorage()
,08-30 11:36:55.704  6864  6864 E Zygote  : v2
08-30 11:36:55.704  6864  6864 I libpersona: KNOX_SDCARD checking this for 10125
08-30 11:36:55.704  1017  1497 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6864 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
08-30 11:36:55.704  6864  6864 I libpersona: KNOX_SDCARD not a persona
08-30 11:36:55.704  1017  1497 I ActivityManager: Killing 5955:com.google.android.apps.docs/u0a91 (adj 15): empty #31
08-30 11:36:55.714  6864  6864 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 11:36:55.714  6858  6858 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,08-30 11:36:55.714  6864  6864 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-30 11:36:55.714  6864  6864 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 11:36:55.734   309   309 I art     : Explicit concurrent mark sweep GC freed 8716(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 623us total 24.606ms
,08-30 11:36:55.734  6864  6864 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 11:36:55.734  6864  6864 D ActivityThread: Added TimaKeyStore provider
,08-30 11:36:55.744  6864  6864 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 11:36:55.744  6864  6864 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-30 11:36:55.744  6864  6864 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 11:36:55.754   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 602us total 17.125ms,
,08-30 11:36:55.764  6864  6864 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-30 11:36:55.764  6864  6864 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-30 11:36:55.764  6864  6864 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
08-30 11:36:55.764   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 611us total 16.792ms
,08-30 11:36:55.764  1017  1477 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
08-30 11:36:55.764  1017  1477 I ActivityManager: Killing 6188:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,08-30 11:36:55.774  1017  3440 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 11:36:55.774  1017  3440 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 11:36:55.774  1017  3440 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:55.774  1017  3440 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 11:36:55.774  1017  3440 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-30 11:36:55.784  3682  3682 I Hs20UtilService: Starting #12
08-30 11:36:55.784  3682  3722 I Hs20UtilService: Message received 5011
08-30 11:36:55.784  6858  6858 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-30 11:36:55.784  6858  6858 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-30 11:36:55.784  6571  6571 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-30 11:36:55.784  6571  6571 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-30 11:36:55.784  6571  6571 D SecurityLogAgent: StateMachine : Current State = 1
08-30 11:36:55.784  6571  6571 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 11:36:55.804  6858  6858 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,08-30 11:36:55.804   337   337 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6858
08-30 11:36:55.804   337   337 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-30 11:36:55.804  6858  6858 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-30 11:36:55.804  6858  6858 I wpa_supplicant: ssSupport state is = 1
08-30 11:36:55.804  6858  6858 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-30 11:36:55.804  6858  6858 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 11:36:55.804  6858  6858 E wpa_supplicant: SIM READ ERROR
08-30 11:36:55.804  6858  6858 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 11:36:55.804  6858  6858 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 11:36:55.804  6858  6858 E wpa_supplicant: SIM READ ERROR
08-30 11:36:55.804  6858  6858 I wpa_supplicant: Blacklist: Clear (all) 
,08-30 11:36:55.804  6858  6858 I wpa_supplicant: wpa_default_ap_write_once
08-30 11:36:55.804  6858  6858 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-30 11:36:55.804  6858  6858 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 11:36:55.804  6858  6858 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-30 11:36:55.804  6858  6858 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 11:36:55.804  6858  6858 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-30 11:36:55.804  6858  6858 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 11:36:55.804  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 11:36:55.804  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 11:36:55.804  1017  1045 D Tethering: interfaceStatusChanged wlan0, false,
,08-30 11:36:55.854  6858  6858 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-30 11:36:56.034  6858  6858 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-30 11:36:56.034  6858  6858 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-30 11:36:56.044  6858  6858 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-30 11:36:56.044   337   337 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6858
08-30 11:36:56.044   337   337 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-30 11:36:56.054  6858  6858 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
08-30 11:36:56.054  6858  6858 I wpa_supplicant: ssSupport state is = 1
08-30 11:36:56.054  6858  6858 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-30 11:36:56.054  6858  6858 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-30 11:36:56.064  6858  6858 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-30 11:36:56.064   337   337 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6858
08-30 11:36:56.064   337   337 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-30 11:36:56.064  6858  6858 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-30 11:36:56.064  6858  6858 I wpa_supplicant: ssSupport state is = 1,
08-30 11:36:56.064  6858  6858 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 11:36:56.064  6858  6858 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 11:36:56.064  6858  6858 E wpa_supplicant: SIM READ ERROR
08-30 11:36:56.064  6858  6858 I wpa_supplicant: wpa_default_ap_write_once
,08-30 11:36:56.064  6858  6858 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-30 11:36:56.064  6858  6858 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 11:36:56.064  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false,
08-30 11:36:56.064  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-30 11:36:56.064  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-30 11:36:56.074  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false,
08-30 11:36:56.074  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-30 11:36:56.074  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-30 11:36:56.224  6858  6858 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-30 11:36:56.224  6858  6858 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-30 11:36:56.304   290   290 E SMD     : DCD OFF,
,08-30 11:36:56.344  6858  6858 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,08-30 11:36:56.344  6858  6858 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-30 11:36:56.344  6858  6858 I wpa_supplicant: Skip scan - bUseNetwork false
,08-30 11:36:56.354  1017  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-30 11:36:56.354  1017  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-30 11:36:56.354  6858  6858 I wpa_supplicant: HOTSPOT20_ENABLE called
08-30 11:36:56.354  6858  6858 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 11:36:56.354  6858  6858 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 11:36:56.354  6858  6858 E wpa_supplicant: SIM READ ERROR
08-30 11:36:56.354  6858  6858 I wpa_supplicant: Blacklist: Clear (all) 
,08-30 11:36:56.384  6858  6858 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-30 11:36:56.394  1017  1128 D WifiNative-wlan0: callSECApiInt - ID [210]
08-30 11:36:56.394  6858  6858 I wpa_supplicant: Skip scan - bUseNetwork false
08-30 11:36:56.394  1017  1128 D WifiConfigStore: Loading config and enabling all networks ,
08-30 11:36:56.394  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020543/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 11:36:56.394  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 11:36:56.394  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:56.394  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:56.394  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:56.394  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:56.404  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 11:36:56.404  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-30 11:36:56.404  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-30 11:36:56.404  1177  1717 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-30 11:36:56.404  1177  1177 D HotspotTile: onReceive : 3, 0
,08-30 11:36:56.404  1319  1319 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-30 11:36:56.414  6312  6312 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 11:36:56.414  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:36:56.414  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:36:56.414  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:36:56.414  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,08-30 11:36:56.414  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 11:36:56.414  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:36:56.414  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:36:56.414  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 11:36:56.414  6312  6312 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:36:56.414  6312  6312 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 11:36:56.414  1017  1128 E WifiConfigStore: Not a HS20
08-30 11:36:56.414  1017  1128 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-30 11:36:56.414  1017  1029 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 11:36:56.414  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 11:36:56.414  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:56.414  6312  6312 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:36:56.414  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:36:56.414  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-30 11:36:56.414  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:36:56.414  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:36:56.414  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:36:56.414  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:36:56.414  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 11:36:56.414  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:36:56.414  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:36:56.414  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 11:36:56.414  6312  6312 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:36:56.414  6312  6312 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 11:36:56.424  3682  3682 I Hs20UtilService: Starting #13
08-30 11:36:56.424  3682  3722 I Hs20UtilService: Message received 5011
,08-30 11:36:56.424  1017  1128 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-30 11:36:56.424  6571  6571 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-30 11:36:56.424  6571  6571 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-30 11:36:56.424  6571  6571 D SecurityLogAgent: StateMachine : Current State = 1
08-30 11:36:56.424  1017  1128 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-30 11:36:56.424  6858  6858 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-30 11:36:56.424  6858  6858 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-30 11:36:56.424  6858  6858 I wpa_supplicant: reset timer : RESET_TIMER 0
08-30 11:36:56.424  6858  6858 I wpa_supplicant: P2P: Current p2p state = IDLE
08-30 11:36:56.424  6858  6858 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-30 11:36:56.424  6858  6858 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-30 11:36:56.424  6858  6858 I wpa_supplicant: First Scan Start
,08-30 11:36:56.434  6858  6858 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-30 11:36:56.434  6571  6571 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 11:36:56.434  1017  1128 D WifiNative-wlan0: Setting external_sim to 1
,08-30 11:36:56.434  1017  1128 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 11:36:56.434  1017  1128 I WifiNative-HAL: startHal
08-30 11:36:56.434  1017  1128 E wifi    : getStaticLongField sWifiHalHandle 0x9cb6588c
08-30 11:36:56.434  1017  1128 I WifiNative-HAL: Could not start hal
,08-30 11:36:56.434  6509  6509 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 11:36:56.434  1017  1128 E WifiNative-wlan0: do suspend true
,08-30 11:36:56.434  1017  1127 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-30 11:36:56.434   280   989 D CommandListener: Setting iface cfg
08-30 11:36:56.434   280   989 D CommandListener: Trying to bring up p2p0
,08-30 11:36:56.444  1017  1127 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-30 11:36:56.444  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-30 11:36:56.444  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 11:36:56.444  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-30 11:36:56.444  1017  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-30 11:36:56.444  1017  1127 D WifiP2pService: P2pEnablingState
08-30 11:36:56.444  1017  1127 D WifiP2pService: P2pEnablingState{ what=147457 }
,08-30 11:36:56.444  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 3
,08-30 11:36:56.444  1017  1151 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 11:36:56.444  1017  1151 I WifiNative-HAL: startHal
08-30 11:36:56.444  1017  1151 E wifi    : getStaticLongField sWifiHalHandle 0x9dd179bc
08-30 11:36:56.444  1017  1151 I WifiNative-HAL: Could not start hal
08-30 11:36:56.444  1017  1151 E WifiScanningService: could not start HAL
08-30 11:36:56.444  1017  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-30 11:36:56.444  1017  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-30 11:36:56.444  1017  1128 E WifiNative-wlan0: invaild command id : 215
,08-30 11:36:56.444  1017  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-30 11:36:56.444  1017  1017 D RttService: SCAN_AVAILABLE : 3
08-30 11:36:56.444  1017  1152 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:36:56.444  1017  1127 D WifiP2pService: P2p socket connection successful
,08-30 11:36:56.444  1017  1127 D WifiP2pService: P2pEnabledState
,08-30 11:36:56.444  1017  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-30 11:36:56.444  1017  1128 E WifiNative-wlan0: invaild command id : 215
,08-30 11:36:56.454  1017  1127 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-30 11:36:56.454  1017  1130 E ConnectivityService: updateNetworkInfo()
08-30 11:36:56.454  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-30 11:36:56.454  6858  6858 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-30 11:36:56.454  1017  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-30 11:36:56.454  1017  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 11:36:56.454  1017  1048 D WifiDisplayController: disconnect
08-30 11:36:56.454  1017  1048 D WifiDisplayController: updateConnection
08-30 11:36:56.454  1017  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 11:36:56.454  1017  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-30 11:36:56.454  6858  6858 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,08-30 11:36:56.464  1017  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 11:36:56.464  1017  1048 D WifiDisplayAdapter: onP2pDisconnected
08-30 11:36:56.464  1017  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-30 11:36:56.464  6858  6858 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
08-30 11:36:56.464  1017  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-30 11:36:56.464  1319  1319 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-30 11:36:56.464  1319  1319 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 11:36:56.464  1319  1319 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 11:36:56.464  1319  1319 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-30 11:36:56.464  1319  1319 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 11:36:56.464  1319  1319 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-30 11:36:56.464  1319  3112 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 11:36:56.464  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 11:36:56.464  1017  1128 D SecContentProvider2: mCursor = null
,08-30 11:36:56.464  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-30 11:36:56.464  1017  1477 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-30 11:36:56.464  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-30 11:36:56.464  1017  1127 D WifiNative-p2p0: p2pGetDeviceAddress
08-30 11:36:56.464  1017  1127 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
,08-30 11:36:56.474  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
,08-30 11:36:56.474  1017  1128 D SecContentProvider2: mCursor = null
,08-30 11:36:56.474  6539  6539 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-30 11:36:56.474  6539  6539 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-30 11:36:56.474  6539  6539 D FileShare-Client: Outbound.stopDelayTimer - 
,08-30 11:36:56.484  1017  1127 D WifiP2pService: DeviceAddress: 7e:96:ac
,08-30 11:36:56.484  1017  1048 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
08-30 11:36:56.484  1017  1048 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
08-30 11:36:56.484  1017  1048 D WifiDisplayController:  primary type: 10-0050F204-5
08-30 11:36:56.484  1017  1048 D WifiDisplayController:  secondary type: null
08-30 11:36:56.484  1017  1048 D WifiDisplayController:  wps: 0
08-30 11:36:56.484  1017  1048 D WifiDisplayController:  grpcapab: 0
08-30 11:36:56.484  1017  1048 D WifiDisplayController:  devcapab: 0
08-30 11:36:56.484  1017  1048 D WifiDisplayController:  status: 3
08-30 11:36:56.484  1017  1048 D WifiDisplayController:  wfdInfo: null
08-30 11:36:56.484  1017  1048 D WifiDisplayController:  groupownerAddress: null
08-30 11:36:56.484  1017  1048 D WifiDisplayController:  GOdeviceName: null
08-30 11:36:56.484  1017  1048 D WifiDisplayController:  interfaceAddress: 
08-30 11:36:56.484  1017  1048 D WifiDisplayController:  SConnectInfo : null
,08-30 11:36:56.484  6554  6554 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 11:36:56.504  1017  1127 D WifiP2pService: sending p2p persistent groups changed broadcast,
08-30 11:36:56.504  1017  1127 D WifiP2pService: InactiveState
08-30 11:36:56.504  1017  1127 D WifiP2pService: InactiveState{ what=143376 }
,08-30 11:36:56.504  1017  1127 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-30 11:36:56.504  6858  6858 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,08-30 11:36:56.504  1017  1127 D WifiP2pService: InactiveState{ what=143376 },
08-30 11:36:56.504  1017  1127 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-30 11:36:57.694  6858  6858 I wpa_supplicant: nl80211: Received scan results (24 BSSes),
,08-30 11:36:57.694  6858  6858 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
08-30 11:36:57.694  6858  6858 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,08-30 11:36:57.704  1017  6882 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
08-30 11:36:57.704  6858  6858 I wpa_supplicant: Trying to associate with  'G700'
08-30 11:36:57.704  6858  6858 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-30 11:36:57.704  6858  6858 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-30 11:36:57.714  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-30 11:36:57.714  1017  1128 D SecContentProvider2: mCursor = null
,08-30 11:36:57.814  6858  6858 E wpa_supplicant: Cmd 35605 not handled
08-30 11:36:57.814  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 11:36:57.814  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 11:36:57.814  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
08-30 11:36:57.814  6858  6858 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,08-30 11:36:57.814  6858  6858 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-30 11:36:57.814  6858  6858 I wpa_supplicant: Associated with F4.99.3E
,08-30 11:36:57.814  6858  6858 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-30 11:36:57.814  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 11:36:57.814  6858  6858 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-30 11:36:57.814  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 11:36:57.814  6858  6858 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-30 11:36:57.814  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 11:36:57.814  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
08-30 11:36:57.814  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,08-30 11:36:57.814  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
08-30 11:36:57.814  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, true
08-30 11:36:57.814  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-30 11:36:57.814  1017  1045 D Tethering: interfaceStatusChanged wlan0, true
,08-30 11:36:57.824  1017  1131 E Tethering: No numeric data
,08-30 11:36:57.824  1017  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-30 11:36:57.824  1017  1131 D Tethering: clearTetheredNotification()
,08-30 11:36:57.824  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-30 11:36:57.824  1017  1128 D SecContentProvider2: mCursor = null
08-30 11:36:57.824  6858  6858 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-30 11:36:57.824  6858  6858 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-30 11:36:57.824  6858  6858 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-30 11:36:57.824  6858  6858 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-30 11:36:57.824  6858  6858 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 11:36:57.824  6858  6858 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-30 11:36:57.824  6858  6858 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,08-30 11:36:57.834  6858  6858 I wpa_supplicant: Blacklist: Clear (temp) 
08-30 11:36:57.834  6858  6858 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-30 11:36:57.834  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, true
,08-30 11:36:57.834  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-30 11:36:57.834  1017  1045 D Tethering: interfaceStatusChanged wlan0, true
08-30 11:36:57.834  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 11:36:57.834  1017  1128 D SecContentProvider2: mCursor = null
,08-30 11:36:57.834  1017  1128 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-30 11:36:57.844  1017  1125 V NetworkStats: performPollLocked(flags=0x1)
08-30 11:36:57.844  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 11:36:57.844  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-30 11:36:57.844  1017  1128 E WifiConfigStore: setLastSelectedConfiguration -1
08-30 11:36:57.844  1177  1177 D HotspotTile: updateTetherState():false, false
,08-30 11:36:57.844  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 11:36:57.844  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 11:36:57.844  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020543/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 11:36:57.854  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 11:36:57.854  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:57.854  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:57.854  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:57.854  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 11:36:57.854  1017  1043 I ActivityManager: Killing 6211:com.samsung.helphub/1000 (adj 15): empty #31
,08-30 11:36:57.854  1017  1128 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-30 11:36:57.854  1017  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 11:36:57.854  1017  1125 V NetworkStats: performPollLocked() took 15ms
08-30 11:36:57.854  1017  1130 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-30 11:36:57.854  1017  1130 E ConnectivityService: updateNetworkInfo()
08-30 11:36:57.854  1017  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 11:36:57.854  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 11:36:57.854  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 11:36:57.854  1017  1217 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 11:36:57.854  1017  1217 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 11:36:57.854  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 11:36:57.864  1017  1217 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:57.864  1017  1217 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-30 11:36:57.864  1017  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-30 11:36:57.864  3682  3682 I Hs20UtilService: Starting #14
,08-30 11:36:57.864  1017  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 11:36:57.864  3682  3722 I Hs20UtilService: Message received 5007
08-30 11:36:57.874  1319  1319 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-30 11:36:57.874  1319  1319 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 11:36:57.874  1319  1319 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 11:36:57.874  1319  1319 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-30 11:36:57.874  1319  1319 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 11:36:57.874  1319  1319 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-30 11:36:57.874  1319  3112 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 11:36:57.884   280   989 D CommandListener: Setting iface cfg
,08-30 11:36:57.884  1017  1128 E WifiStateMachine: Start Dhcp Watchdog 2
,08-30 11:36:57.894  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 11:36:57.894  1017  1128 D SecContentProvider2: mCursor = null
,08-30 11:36:57.904  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020543/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 11:36:57.904  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 11:36:57.904  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:57.904  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:57.904  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:57.904  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 11:36:57.904  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-30 11:36:57.904  1017  1128 D SecContentProvider2: mCursor = null
,08-30 11:36:57.904  1017  1128 E WifiNative-wlan0: do suspend false
,08-30 11:36:57.904  1017  1127 D WifiP2pService: InactiveState{ what=143375 }
,08-30 11:36:57.904  1017  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-30 11:36:58.084  1017  1217 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-30 11:36:58.084  1017  1217 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-30 11:36:58.084  1017  1217 D SecContentProvider2: mCursor = null,
,08-30 11:36:58.084  1017  1217 D SettingsProvider: name = wifi_on
08-30 11:36:58.084  1017  1217 D WifiService: setWifiEnabled: false pid=6312, uid=10155
,08-30 11:36:58.104  1017  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 11:36:58.114  1017  1128 E WifiNative-wlan0: do suspend true,
,08-30 11:36:58.124  6889  6889 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-30 11:36:58.124  6889  6889 I dhcpcd  : version 5.5.6 starting,
,08-30 11:36:58.134  1017  1127 D WifiP2pService: InactiveState{ what=143375 },
08-30 11:36:58.134  1017  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-30 11:36:58.134  6889  6889 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
08-30 11:36:58.134  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020543/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 11:36:58.134  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 11:36:58.134  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:58.134  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:58.134  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:58.134  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 11:36:58.144   280   989 D CommandListener: Clearing all IP addresses on wlan0
,08-30 11:36:58.154  1017  1130 E ConnectivityService: updateNetworkInfo()
,08-30 11:36:58.154  1017  1130 E ConnectivityService: updateNetworkInfo()
08-30 11:36:58.154  1017  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 11:36:58.154   280   989 E Netd    : no such netId 503,
08-30 11:36:58.154  1017  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
08-30 11:36:58.154  1017  1130 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '75 network destroy 503' failed with '400 75 destroyNetwork() failed (Machine is not on the network)'
08-30 11:36:58.154  1017  1130 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-30 11:36:58.154  1017  1130 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
,08-30 11:36:58.154  1017  1130 D ConnectivityService: nai.networkMonitor.doQuit()
08-30 11:36:58.154  1017  1130 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-30 11:36:58.154  1017  1130 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-30 11:36:58.154  1017  6886 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:36:58.154  1017  6886 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-30 11:36:58.164  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-30 11:36:58.174  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020543/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 11:36:58.174  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 11:36:58.174  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:58.174  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:58.174  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:58.174  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 11:36:58.174  1017  1127 D WifiP2pService: InactiveState{ what=131204 },
08-30 11:36:58.184  1017  1128 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 11:36:58.184  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 1
08-30 11:36:58.184  1017  1127 D WifiP2pService: P2pEnabledState{ what=131204 }
08-30 11:36:58.184  1017  1151 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:36:58.184  1017  1127 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-30 11:36:58.184  1017  1130 E ConnectivityService: updateNetworkInfo()
08-30 11:36:58.184  1017  1017 D RttService: SCAN_AVAILABLE : 1
,08-30 11:36:58.184  1017  1152 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:36:58.184  1017  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 11:36:58.184  1017  1048 D WifiDisplayAdapter: onP2pDisconnected
08-30 11:36:58.184  1017  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-30 11:36:58.184  1017  1350 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:58.184  1017  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
08-30 11:36:58.184  1017  1350 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:36:58.184  1017  1350 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 11:36:58.184  1017  1350 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-30 11:36:58.184  1017  1350 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 11:36:58.184  1017  1127 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-30 11:36:58.184  1017  1130 E ConnectivityService: updateNetworkInfo()
,08-30 11:36:58.194  3682  3682 I Hs20UtilService: Starting #15
,08-30 11:36:58.194  3682  3722 I Hs20UtilService: Message received 5007
,08-30 11:36:58.194  1017  1127 D WifiP2pService: P2pDisablingState
08-30 11:36:58.194  1017  1127 D WifiP2pService: P2pDisablingState{ what=147458 }
08-30 11:36:58.194  1017  1127 D WifiP2pService: p2p socket connection lost
08-30 11:36:58.194  1017  1127 D WifiP2pService: P2pDisabledState
,08-30 11:36:58.194  1017  1128 E WifiNative-wlan0: do suspend true
08-30 11:36:58.194  1017  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,08-30 11:36:58.194  1017  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 11:36:58.194  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-30 11:36:58.194  1017  1048 D WifiDisplayController: disconnect
08-30 11:36:58.194  1017  1048 D WifiDisplayController: updateConnection
,08-30 11:36:58.194  1017  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 11:36:58.194  1017  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-30 11:36:58.204  1017  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-30 11:36:58.204  1017  1048 D WifiDisplayAdapter: onP2pDisconnected
08-30 11:36:58.204  1319  1319 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-30 11:36:58.204  1017  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer,
08-30 11:36:58.204  1319  1319 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-30 11:36:58.204  1017  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
08-30 11:36:58.204  1319  1319 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 11:36:58.204  1319  1319 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-30 11:36:58.204  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-30 11:36:58.204  1319  1319 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 11:36:58.204  1017  3289 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-30 11:36:58.204  1319  1319 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-30 11:36:58.204  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-30 11:36:58.204  1319  3112 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 11:36:58.214  1319  1319 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE,
08-30 11:36:58.214  1319  1319 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-30 11:36:58.214  1319  1319 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 11:36:58.224  1319  1319 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-30 11:36:58.224  1319  1319 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 11:36:58.224  1319  1319 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-30 11:36:58.224  1017  1127 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-30 11:36:58.224  1017  1127 D WifiP2pService: DefaultState{ what=143375 }
,08-30 11:36:58.224  1319  3112 V NearbySettings: MountReceiver.mPrefHandler - 7002,
,08-30 11:36:58.224   280   989 D CommandListener: Clearing all IP addresses on wlan0
,08-30 11:36:58.234  6539  6539 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 11:36:58.234  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020543/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 11:36:58.234  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 11:36:58.234  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:58.234  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:58.234  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:58.234  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:58.234  6889  6889 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-30 11:36:58.234  6889  6889 E dhcpcd  : wlan0: sendmsg: Network is unreachable
08-30 11:36:58.234  6889  6889 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-30 11:36:58.234  6889  6889 I dhcpcd  : bssid match
08-30 11:36:58.234  6889  6889 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111
08-30 11:36:58.234  6858  6858 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-30 11:36:58.234  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-30 11:36:58.234  6539  6539 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-30 11:36:58.234  6539  6539 D FileShare-Client: Outbound.stopDelayTimer - 
,08-30 11:36:58.244  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020543/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 11:36:58.244  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 11:36:58.244  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:58.244  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:58.244  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:58.244  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 11:36:58.244  6554  6554 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 11:36:58.254  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020543/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 11:36:58.254  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 11:36:58.254  1017  1128 D SecContentProvider2: mCursor = null
,08-30 11:36:58.254  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-30 11:36:58.254  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:58.254  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:58.254  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:58.254  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 11:36:58.254  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 11:36:58.254  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-30 11:36:58.254  1177  1717 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-30 11:36:58.254  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
08-30 11:36:58.254  1177  1177 D HotspotTile: onReceive : 0, 0
,08-30 11:36:58.264  1319  1319 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-30 11:36:58.264  6312  6312 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:36:58.264  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:36:58.264  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:36:58.264  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:36:58.264  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 11:36:58.264  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 11:36:58.264  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:36:58.264  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:36:58.264  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 11:36:58.264  6312  6312 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:36:58.264  6312  6312 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 11:36:58.264  6312  6312 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 11:36:58.264  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:36:58.264  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:36:58.264  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:36:58.264  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 11:36:58.264  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 11:36:58.264  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:36:58.264  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:36:58.264  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 11:36:58.264  6312  6312 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:36:58.264  6312  6312 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 11:36:58.264  1017  3440 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-30 11:36:58.264  1017  3440 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 11:36:58.264  1017  3440 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:58.264  1017  3440 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 11:36:58.274  1017  3440 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 11:36:58.274  3682  3682 I Hs20UtilService: Starting #16
08-30 11:36:58.274  3682  3722 I Hs20UtilService: Message received 5007
,08-30 11:36:58.274  1319  1319 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-30 11:36:58.274  1319  1319 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 11:36:58.274  1319  1319 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 11:36:58.274  1319  1319 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-30 11:36:58.274  1319  1319 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 11:36:58.274  1319  1319 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-30 11:36:58.274  1319  3112 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 11:36:58.284  1017  1350 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-30 11:36:58.284  1017  1350 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 11:36:58.284  1017  1350 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:58.284  1017  1350 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:36:58.284  1017  1350 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 11:36:58.294  6571  6571 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-30 11:36:58.294  6571  6571 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-30 11:36:58.294  6571  6571 D SecurityLogAgent: StateMachine : Current State = 1
,08-30 11:36:58.294  6571  6571 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 11:36:58.294  3682  3682 I Hs20UtilService: Starting #17
,08-30 11:36:58.294  3682  3722 I Hs20UtilService: Message received 5011
,08-30 11:36:58.364  6889  6889 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1
,08-30 11:36:58.464  6858  6858 I wpa_supplicant: Blacklist: Clear (all) ,
,08-30 11:36:58.534  6889  6889 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds
,08-30 11:36:58.554  1017  3091 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-30 11:36:58.554  1017  3091 D BatteryService: level:86, scale:100, status:2, health:2, present:true, voltage: 4141, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,08-30 11:36:58.554  1017  3091 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-30 11:36:58.564  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-30 11:36:58.554  1017  3091 D BatteryService: stay LED for charging
08-30 11:36:58.564  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate,
08-30 11:36:58.554  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-30 11:36:58.564  1017  1017 I MotionRecognitionService: Plugged
08-30 11:36:58.564  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-30 11:36:58.564  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-30 11:36:58.564  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 86
,08-30 11:36:58.594  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:86 status:2 health:2,
08-30 11:36:58.594  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:86 status:2 health:2
08-30 11:36:58.594  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:86 status:2 health:2
,08-30 11:36:58.614  6858  6858 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING ,
,08-30 11:36:58.614  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-30 11:36:58.614  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 11:36:58.614  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-30 11:36:58.634  6858  6858 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-30 11:36:58.634  6858  6858 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
,08-30 11:36:58.634  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 11:36:58.634  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 11:36:58.644  1017  1128 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
08-30 11:36:58.634  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
08-30 11:36:58.644  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 11:36:58.634  6858  6858 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-30 11:36:58.634  6858  6858 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030,
,08-30 11:36:58.634  6858  6858 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-30 11:36:58.644  1017  1131 D Tethering: InitialState.processMessage what=4
08-30 11:36:58.644  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 11:36:58.644  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-30 11:36:58.644  1017  1131 E Tethering: No numeric data
08-30 11:36:58.644  1017  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 11:36:58.644  1017  1131 D Tethering: clearTetheredNotification()
08-30 11:36:58.654  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
08-30 11:36:58.654  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-30 11:36:58.654  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-30 11:36:58.654  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 11:36:58.654  1017  1125 V NetworkStats: performPollLocked(flags=0x1)
08-30 11:36:58.654  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-30 11:36:58.654  1177  1177 D HotspotTile: updateTetherState():false, false
,08-30 11:36:58.654  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 11:36:58.654  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 11:36:58.664  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
08-30 11:36:58.664  1017  1125 V NetworkStats: performPollLocked() took 8ms
,08-30 11:36:58.664  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 11:36:58.664  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 11:36:58.814  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 11:36:58.814  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 11:36:58.814  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-30 11:36:58.814  1017  2784 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-30 11:36:59.024  6858  6858 I wpa_supplicant: Blacklist: Clear (all) ,
,08-30 11:36:59.194  6858  6858 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-30 11:36:59.194  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 11:36:59.194  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 11:36:59.194  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-30 11:36:59.204  1017  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-30 11:36:59.204  1017  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-30 11:36:59.204  1017  1128 E WifiConfigStore: setLastSelectedConfiguration -1
,08-30 11:36:59.214  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020543/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 11:36:59.214  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-30 11:36:59.214  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:59.214  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:59.214  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:36:59.214  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 11:36:59.214  6509  6509 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 11:36:59.214  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 11:36:59.214  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-30 11:36:59.214  1177  1717 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-30 11:36:59.214  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-30 11:36:59.214  1177  1177 D HotspotTile: onReceive : 1, 0
,08-30 11:36:59.224  1929  2106 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 11:36:59.224  1319  1319 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-30 11:36:59.224  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:36:59.224  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:36:59.234  1017  1029 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 11:36:59.234  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 11:36:59.234  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:59.234  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:36:59.234  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 11:36:59.234  3682  3682 I Hs20UtilService: Starting #18
,08-30 11:36:59.234  3682  3722 I Hs20UtilService: Message received 5011
,08-30 11:36:59.234  6571  6571 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-30 11:36:59.234  6571  6571 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-30 11:36:59.234  6571  6571 D SecurityLogAgent: StateMachine : Current State = 1
08-30 11:36:59.234  6571  6571 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 11:36:59.304   290   290 E SMD     : DCD OFF,
,08-30 11:36:59.774  1017  1043 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:59.774  1017  1043 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:59.774  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 11:36:59.784  1017  1350 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,08-30 11:36:59.784  1017  1350 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,08-30 11:36:59.784  1017  1350 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:59.784  1017  1350 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 11:36:59.784  1017  1350 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 11:36:59.794  1017  1497 D ActivityManager: bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,08-30 11:36:59.794  1017  1497 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,08-30 11:36:59.794  1017  1497 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:59.794  1017  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 11:36:59.804  1017  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-30 11:36:59.804  1017  1140 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:59.804  1017  1140 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:59.804  1017  1140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 11:36:59.814  1017  1217 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-30 11:36:59.814  1017  1217 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,08-30 11:36:59.814  1017  1217 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:59.814  1017  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:59.814  1017  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 11:36:59.814  6712  6761 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-30 11:36:59.824   280   983 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,08-30 11:36:59.824  1017  1045 D Tethering: interfaceRemoved wlan0
08-30 11:36:59.824  1017  1045 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-30 11:36:59.824  1017  1560 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-30 11:36:59.824  1017  1560 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,08-30 11:36:59.824  1017  1560 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:59.824  1017  1560 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:59.824  1017  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 11:36:59.834  1017  1477 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-30 11:36:59.834  1017  1477 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-30 11:36:59.834  1017  1477 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:59.834  1017  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:59.834  1017  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 11:36:59.844  1017  3289 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,08-30 11:36:59.844  1017  3289 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,08-30 11:36:59.854  1017  3289 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:59.854  1017  3289 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:59.854  1017  3289 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 11:36:59.874  1017  1478 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 11:36:59.874  1017  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:36:59.874  1017  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:59.874  1017  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,08-30 11:36:59.884  1929  1929 D WearableService: callingUid 10012, callindPid: 1929
,08-30 11:36:59.904  1017  1501 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-30 11:36:59.904  1017  1501 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-30 11:36:59.904  1017  1501 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:36:59.904  1017  1501 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:36:59.904  1017  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 11:36:59.924  6625  6920 I MusicLeanback: Conditions not met for autocaching.
,08-30 11:36:59.924  6625  6920 I MusicLeanback: Stop autocaching.
,08-30 11:36:59.944  6625  6625 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,08-30 11:36:59.944  6625  6926 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,08-30 11:36:59.984  1017  1096 V AlarmManager: waitForAlarm result :8
,08-30 11:37:00.024  1017  1045 D Tethering: interfaceRemoved p2p0
08-30 11:37:00.024  1017  1045 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-30 11:37:00.774  1017  1338 E Watchdog: !@Sync 4
,08-30 11:37:00.814  1017  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-30 11:37:01.104  6312  6364 D BluetoothAdapter: enable()
,08-30 11:37:01.104  1017  1497 W ActivityManager: Permission Denial: getCurrentUser() from pid=6312, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,08-30 11:37:01.104  1017  1497 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-30 11:37:01.104  1017  1497 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6312, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-30 11:37:01.104  1017  1497 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-30 11:37:01.104  1017  1497 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
08-30 11:37:01.104  1017  1497 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
08-30 11:37:01.104  1017  1497 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
08-30 11:37:01.104  1017  1497 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-30 11:37:01.104  1017  1497 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-30 11:37:01.104  1017  1497 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 11:37:01.104  1017  1497 D SettingsProvider: name = bluetooth_on,
,08-30 11:37:01.114  1017  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
08-30 11:37:01.114  1017  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 11:37:01.114  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth,
,08-30 11:37:01.114  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-30 11:37:01.154  6590  6590 D BluetoothAdapterState: make
,08-30 11:37:01.164  6590  6590 I bluedroid: init
,08-30 11:37:01.164  6590  6928 I BluetoothAdapterState: Entering OffState
,08-30 11:37:01.164  6590  6590 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-30 11:37:01.174  6590  6590 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-30 11:37:01.174  6590  6590 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 11:37:01.174  6590  6590 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-30 11:37:01.174  6590  6590 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-30 11:37:01.174  6590  6590 I bluedroid: get_profile_interface socket
08-30 11:37:01.174  6590  6590 I bluedroid: get_profile_interface map_client
,08-30 11:37:01.174  6590  6931 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-30 11:37:01.174  6590  6590 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-30 11:37:01.174  6590  6931 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,08-30 11:37:01.184  6590  6931 E BluetoothServiceJni: populateRssiValuesNative
08-30 11:37:01.184  6590  6931 I bluedroid: getModelRssiValues
08-30 11:37:01.184  6590  6931 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-30 11:37:01.184  6590  6931 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-30 11:37:01.184  6590  6931 D BluetoothAdapterProperties: Name is: A5-1
,08-30 11:37:01.184  1017  1017 D SettingsProvider: name = bluetooth_name
,08-30 11:37:01.184  6590  6590 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-30 11:37:01.184  1017  3440 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-30 11:37:01.184  1017  3440 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 11:37:01.194  1017  3440 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:37:01.194  1017  3440 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:01.194  1017  3440 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:01.194  6590  6758 I bluedroid: config_hci_snoop_log
,08-30 11:37:01.194  1017  1047 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,08-30 11:37:01.194  1017  1047 D BluetoothManagerService: Ble is always on enable gatt
,08-30 11:37:01.194  1017  1047 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-30 11:37:01.204  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-30 11:37:01.204  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-30 11:37:01.204  1017  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-30 11:37:01.204  1017  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 11:37:01.204  6590  6590 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-30 11:37:01.204  1017  1047 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-30 11:37:01.214  6590  6928 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-30 11:37:01.214  6590  6928 D BluetoothAdapterProperties: Setting state to 11
,08-30 11:37:01.214  6590  6928 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-30 11:37:01.214  6590  6928 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-30 11:37:01.214  6590  6928 D BluetoothAdapterService: updateAdapterState state is 11
,08-30 11:37:01.214  6590  6928 D BluetoothAdapterService: Autoconnection is available 
08-30 11:37:01.214  6590  6928 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-30 11:37:01.214  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-30 11:37:01.214  1017  1017 I InputMethodManagerService: [BT Setting State] State =11
,08-30 11:37:01.224  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-30 11:37:01.224  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:37:01.224  1177  1177 D BluetoothTile:  getBluetoothState : 11
,08-30 11:37:01.224  1770  1770 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 11:37:01.224  1177  1717 D BluetoothTile:  handleUpdatestate:false name:null
08-30 11:37:01.224  1177  1717 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-30 11:37:01.234  1017  1478 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 11:37:01.234  1017  1140 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-30 11:37:01.234  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-30 11:37:01.234  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:01.234  1017  3440 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 11:37:01.234  1017  3440 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-30 11:37:01.234  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:01.234  6590  6928 D BluetoothSecureManager: getInstant: null
,08-30 11:37:01.234  6590  6928 D BluetoothSecureManager: calling getMethod for getService
08-30 11:37:01.234  6590  6928 D BluetoothSecureManager: calling getService
08-30 11:37:01.234  1319  1319 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 11:37:01.234  6590  6928 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@311740d8
08-30 11:37:01.234  1017  1030 D BluetoothSecureManagerService: isSecureModeEnabled
08-30 11:37:01.234  1017  1030 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
08-30 11:37:01.234  1017  3440 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:01.234  1017  3440 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:37:01.234  1017  3440 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-30 11:37:01.234  6590  6928 D BtConfig.SecureMode: isSecureModeOn:false
,08-30 11:37:01.234  6590  6928 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-30 11:37:01.234  6590  6928 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-30 11:37:01.234  6590  6928 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-30 11:37:01.244  6590  6928 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-30 11:37:01.244  6590  6928 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-30 11:37:01.244  1017  1047 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-30 11:37:01.244  6590  6928 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-30 11:37:01.244  6590  6928 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-30 11:37:01.244  6590  6928 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-30 11:37:01.244  6590  6928 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-30 11:37:01.244  6590  6928 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-30 11:37:01.244  6590  6928 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-30 11:37:01.244  6590  6928 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-30 11:37:01.244  6590  6928 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 11:37:01.244  6590  6928 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-30 11:37:01.244  6590  6928 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-30 11:37:01.244  6590  6928 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-30 11:37:01.244  6590  6928 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-30 11:37:01.244  6590  6928 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-30 11:37:01.244  6590  6928 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-30 11:37:01.244  6590  6928 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-30 11:37:01.244  6590  6928 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-30 11:37:01.244  6590  6928 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-30 11:37:01.244  6590  6928 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-30 11:37:01.254  6590  6928 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-30 11:37:01.254  6590  6928 D BluetoothBondStateMachine: make
,08-30 11:37:01.254  6590  6928 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,08-30 11:37:01.254  6590  6928 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-30 11:37:01.254  6590  6928 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-30 11:37:01.254  6590  6933 I BluetoothBondStateMachine: StableState(): Entering Off State
08-30 11:37:01.254  1319  1319 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 11:37:01.264  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 11:37:01.264  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11,
08-30 11:37:01.264  1017  1140 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 11:37:01.264  1017  1140 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:01.264  1017  1140 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-30 11:37:01.264  1017  1140 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:01.264  1017  1140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:01.264  6590  6928 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-30 11:37:01.264  6590  6928 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-30 11:37:01.264  6590  6928 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-30 11:37:01.264  6590  6590 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 11:37:01.264  6590  6590 D BtGatt.GattService: Received start request. Starting profile...
08-30 11:37:01.264  6590  6590 D BtGatt.GattService: start()
08-30 11:37:01.264  6590  6590 D BtGatt.GattService: start()
08-30 11:37:01.264  6590  6590 I bluedroid: get_profile_interface gatt
,08-30 11:37:01.264  6590  6590 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d50cf2
08-30 11:37:01.264  6590  6590 D BtGatt.AdvertiseManager: advertise manager created
,08-30 11:37:01.264  1017  1560 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 11:37:01.274  1017  1560 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-30 11:37:01.274  1017  1560 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:37:01.274  1017  1560 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:01.274  1017  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:01.284  6590  6928 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-30 11:37:01.284  6590  6928 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-30 11:37:01.284  6590  6928 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-30 11:37:01.284  1017  3440 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 11:37:01.284  1017  3440 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 11:37:01.284  1017  3440 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:01.284  1017  3440 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:01.284  1017  3440 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:01.284  6590  6928 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-30 11:37:01.284  6590  6928 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 11:37:01.284  6590  6928 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-30 11:37:01.284  1017  1350 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 11:37:01.284   319   319 I ServiceManager: Waiting for service AtCmdFwd...
08-30 11:37:01.284  1017  1350 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-30 11:37:01.284  1017  1350 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:01.284  1017  1350 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:01.284  1017  1350 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:01.284  6590  6590 D BtGatt.GattService: mStartError = false
08-30 11:37:01.284  6590  6590 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d50cf2
,08-30 11:37:01.294  6590  6590 D HeadsetService: Received start request. Starting profile...
,08-30 11:37:01.294  6590  6590 D HeadsetService: start()
,08-30 11:37:01.294  6590  6590 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-30 11:37:01.294  6590  6590 D HeadsetStateMachine: make
08-30 11:37:01.294  6590  6928 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-30 11:37:01.294  6590  6928 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-30 11:37:01.294  6590  6928 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-30 11:37:01.294  6590  6590 E HeadsetStateMachine: # of Max HF connection is 2
,08-30 11:37:01.304  1017  1560 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 11:37:01.304  1017  1560 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-30 11:37:01.304  1017  1560 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:01.304  1017  1560 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:01.304  1017  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:01.314  1017  3289 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-30 11:37:01.314  1017  3289 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-30 11:37:01.314  1017  3289 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:01.314  1017  3289 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:01.314  1017  3289 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-30 11:37:01.314  6590  6928 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,08-30 11:37:01.314  6590  6928 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-30 11:37:01.314  6590  6928 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-30 11:37:01.314  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 11:37:01.314  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-30 11:37:01.314  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:37:01.314  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:01.314  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:01.314  1017  1477 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-30 11:37:01.314  1017  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-30 11:37:01.314  1017  1477 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:01.314  1017  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:01.314  1017  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-30 11:37:01.314  6590  6590 I bluedroid: get_profile_interface handsfree
,08-30 11:37:01.314  6590  6928 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-30 11:37:01.314  6590  6928 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 11:37:01.324  6590  6928 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-30 11:37:01.324  1017  1140 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 11:37:01.324  1017  1140 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-30 11:37:01.324  1017  1140 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:37:01.324  1017  1140 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:01.324  1017  1140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:01.334  6590  6928 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-30 11:37:01.334  6590  6928 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-30 11:37:01.334  6590  6928 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-30 11:37:01.334  1017  1501 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 11:37:01.334  1017  1501 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-30 11:37:01.334  6590  6590 I DualScoManager: Instantiating Dual Sco Manager
08-30 11:37:01.334  6590  6590 I DualScoManager: Set HeadsetServiceHelper
,08-30 11:37:01.334  1017  1501 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:01.334  1017  1501 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:01.334  1017  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:01.334  6590  6590 D BluetoothAtMessage: createCMTIContentObservers
,08-30 11:37:01.334  1017  3289 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-30 11:37:01.334  1017  3289 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 11:37:01.334  1017  3289 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-30 11:37:01.334  1017  3289 D SettingsProvider: selectionArgs: false
08-30 11:37:01.334  1017  3289 D SettingsProvider: selectionArgs: 1002
08-30 11:37:01.334  1017  3289 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 11:37:01.334  1017  3289 D SettingsProvider: ret = -1
,08-30 11:37:01.334  6590  6928 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-30 11:37:01.334  6590  6937 D HeadsetStateMachine: Enter Disconnected: -2
08-30 11:37:01.334  6590  6928 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-30 11:37:01.334  6590  6928 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-30 11:37:01.334  6590  6928 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-30 11:37:01.334  6590  6928 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-30 11:37:01.334  6590  6928 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-30 11:37:01.334  6590  6928 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-30 11:37:01.334  6590  6928 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-30 11:37:01.334  6590  6928 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-30 11:37:01.334  6590  6928 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-30 11:37:01.334  6590  6928 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-30 11:37:01.334  6590  6928 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-30 11:37:01.334  6590  6928 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-30 11:37:01.344  6590  6590 D HeadsetService: mStartError = false
08-30 11:37:01.344  6590  6590 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d50cf2
,08-30 11:37:01.344  6590  6937 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-30 11:37:01.344  6590  6937 D HeadsetStateMachine: map size, before remove : 0
,08-30 11:37:01.344  6590  6937 D HeadsetStateMachine: map size, after remove: 0
,08-30 11:37:01.344  6590  6590 D A2dpService: Received start request. Starting profile...
08-30 11:37:01.344  6590  6590 D A2dpService: start()
,08-30 11:37:01.344  6590  6590 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-30 11:37:01.354  6590  6590 I bluedroid: get_profile_interface avrcp
,08-30 11:37:01.354  1929  1929 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-30 11:37:01.354  1929  1929 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-30 11:37:01.364  6590  6590 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-30 11:37:01.374  6590  6590 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-30 11:37:01.384  6590  6940 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
08-30 11:37:01.384  6590  6590 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 11:37:01.384  6590  6590 D A2dpStateMachine: make
,08-30 11:37:01.384  6590  6590 I bluedroid: get_profile_interface a2dp
,08-30 11:37:01.384  6590  6942 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-30 11:37:01.384  6590  6590 E bt-btif : warning : media task started media_task_refcnt 1 
,08-30 11:37:01.384  6590  6590 D A2dpService: mStartError = false
08-30 11:37:01.384  6590  6590 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d50cf2
,08-30 11:37:01.394  6590  6941 D A2dpStateMachine: Enter Disconnected: -2
08-30 11:37:01.394  6590  6590 E BluetoothAdapterService(869600498): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-30 11:37:01.394  6590  6590 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 11:37:01.394  6590  6590 D HidService: Received start request. Starting profile...
08-30 11:37:01.394  6590  6590 D HidService: start()
08-30 11:37:01.394  6590  6590 I bluedroid: get_profile_interface hidhost
08-30 11:37:01.394  6590  6590 D HidService: setHidService(): set to: null
08-30 11:37:01.394  6590  6590 D HidService: mStartError = false
08-30 11:37:01.394  6590  6590 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d50cf2
,08-30 11:37:01.394  6590  6590 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-30 11:37:01.394  6590  6590 D HealthService: Received start request. Starting profile...
08-30 11:37:01.394  6590  6590 D HealthService: start()
,08-30 11:37:01.404  6590  6940 D BluetoothMediaBrowser: no now playing list
08-30 11:37:01.404  6590  6940 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-30 11:37:01.404  6590  6590 I bluedroid: get_profile_interface health
,08-30 11:37:01.404  6590  6590 D HealthService: mStartError = false
08-30 11:37:01.404  6590  6590 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d50cf2
08-30 11:37:01.404  6590  6590 D HeadsetStateMachine: Try to query the phonestate on bind
,08-30 11:37:01.404  1429  2777 I Telecom : BluetoothPhoneService: queryPhoneState
,08-30 11:37:01.404  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-30 11:37:01.404  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-30 11:37:01.404  1429  2777 I Telecom : BluetoothPhoneService: Result of Message : true
,08-30 11:37:01.404  6590  6590 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-30 11:37:01.404  6590  6590 D PanService: Received start request. Starting profile...
08-30 11:37:01.404  6590  6590 D PanService: start()
08-30 11:37:01.404  6590  6590 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 11:37:01.404  6590  6590 I bluedroid: get_profile_interface pan
08-30 11:37:01.414  6590  6590 D PanService: mStartError = false
08-30 11:37:01.414  6590  6590 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d50cf2
08-30 11:37:01.414  6590  6590 D HeadsetStateMachine: Proxy object connected
,08-30 11:37:01.414  6590  6590 D BluetoothMapService: Received start request. Starting profile...
,08-30 11:37:01.414  6590  6590 D BluetoothMapService: start()
,08-30 11:37:01.414  6590  6590 D BluetoothMapService: mStartError = false
,08-30 11:37:01.414  6590  6590 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d50cf2
08-30 11:37:01.414  6590  6590 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-30 11:37:01.414  6590  6590 D HeadsetPhoneState: sendDeviceDataStateChanged
08-30 11:37:01.414  6590  6590 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-30 11:37:01.414  6590  6937 D HeadsetStateMachine: Disconnected process message: 11
,08-30 11:37:01.414  6590  6590 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
08-30 11:37:01.414  6590  6937 D HeadsetStateMachine: Disconnected process message: 18
,08-30 11:37:01.424  6590  6590 D SapService: Received start request. Starting profile...
,08-30 11:37:01.424  6590  6590 D SapService: start()
08-30 11:37:01.424  6590  6590 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-30 11:37:01.424  6590  6590 I bluedroid: get_profile_interface sap
08-30 11:37:01.424  6590  6590 D SapService: mStartError = false
08-30 11:37:01.424  6590  6590 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d50cf2
08-30 11:37:01.424  6590  6590 E BluetoothAdapterService(869600498): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,08-30 11:37:01.424  6590  6590 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-30 11:37:01.424  6590  6590 D BluetoothA2dp: Proxy object connected
08-30 11:37:01.424  6590  6590 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-30 11:37:01.424  6590  6590 E BluetoothAdapterService(869600498): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-30 11:37:01.424  6590  6590 E BluetoothAdapterService(869600498): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-30 11:37:01.424  6590  6937 D HeadsetStateMachine: Disconnected process message: 10
,08-30 11:37:01.424  6590  6937 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
08-30 11:37:01.424  6590  6937 D HeadsetStateMachine: Disconnected process message: 11
,08-30 11:37:01.424  6590  6590 E BluetoothAdapterService(869600498): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,08-30 11:37:01.424  6590  6590 E BluetoothAdapterService(869600498): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-30 11:37:01.454  6590  6590 E BluetoothAdapterService(869600498): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-30 11:37:01.454  6590  6590 E BluetoothAdapterService(869600498): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-30 11:37:01.454  6590  6928 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-30 11:37:01.454  6590  6928 I bluedroid: enable
,08-30 11:37:01.454  6590  6928 I bt_hci_bdroid: init
,08-30 11:37:01.454  6590  6946 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-30 11:37:01.464  6590  6928 I bt_vendor: bt-vendor : init
,08-30 11:37:01.464  6590  6928 I bt_vendor: bt-vendor : get_bt_soc_type
,08-30 11:37:01.464  6590  6928 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-30 11:37:01.464  6590  6928 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
,08-30 11:37:01.464  6590  6928 D bt_userial_mct: userial_init
,08-30 11:37:01.464  6590  6928 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-30 11:37:01.464  6590  6928 I bt_vendor: Starting hciattach daemon
08-30 11:37:01.464  6590  6928 I bt_vendor: try to set false
,08-30 11:37:01.464  6590  6928 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,08-30 11:37:01.464  6590  6928 I bt_vendor: Starting hciattach daemon
08-30 11:37:01.464  6590  6928 I bt_vendor: try to set true
,08-30 11:37:01.484  6950  6950 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-30 11:37:01.544  6956  6956 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-30 11:37:01.554  6957  6957 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-30 11:37:01.574  6959  6959 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-30 11:37:01.574  6960  6960 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-30 11:37:01.584  6961  6961 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-30 11:37:01.594  6962  6962 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-30 11:37:01.834  6965  6965 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,08-30 11:37:01.844  6966  6966 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-30 11:37:01.874  6590  6928 I bt_vendor: bluetooth satus is on,
08-30 11:37:01.874  6590  6948 D bt_userial_mct: userial_open(port:0)
08-30 11:37:01.874  6590  6948 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-30 11:37:01.874  6590  6948 I bt_vendor: Done intiailizing UART,
,08-30 11:37:01.874  6590  6948 I bt_vendor: Done intiailizing UART,
08-30 11:37:01.874  6590  6948 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-30 11:37:01.874  6590  6948 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-30 11:37:01.884  6590  6968 D bt_userial_mct: Entering userial_read_thread()
,08-30 11:37:01.884  6590  6946 I         : BTE_InitTraceLevels -- TRC_HCI
,08-30 11:37:01.884  6590  6946 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 11:37:01.884  6590  6946 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 11:37:01.884  6590  6946 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-30 11:37:01.884  6590  6946 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 11:37:01.884  6590  6946 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 11:37:01.884  6590  6946 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-30 11:37:01.884  6590  6946 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 11:37:01.884  6590  6946 I         : BTE_InitTraceLevels -- TRC_GAP
,08-30 11:37:01.884  6590  6946 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 11:37:01.884  6590  6946 I         : BTE_InitTraceLevels -- TRC_SAP
08-30 11:37:01.884  6590  6946 I         : BTE_InitTraceLevels -- TRC_SDP
,08-30 11:37:01.884  6590  6946 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 11:37:01.894  6590  6946 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 11:37:01.894  6590  6946 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-30 11:37:01.894  6590  6946 I         : BTE_InitTraceLevels -- TRC_BTIF
08-30 11:37:01.894  6590  6946 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-30 11:37:01.994  6590  6946 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-30 11:37:01.994  6590  6946 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa3d816e9 
,08-30 11:37:01.994  6590  6946 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3d816e9 
,08-30 11:37:02.014  6590  6931 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-30 11:37:02.014  6590  6931 E bt-btif : Calling BTA_HhEnable
,08-30 11:37:02.024  6590  6931 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-30 11:37:02.024  6590  6931 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,08-30 11:37:02.024  6590  6931 E BluetoothServiceJni: populateRssiValuesNative
08-30 11:37:02.024  6590  6931 I bluedroid: getModelRssiValues
08-30 11:37:02.024  6590  6931 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-30 11:37:02.024  6590  6931 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-30 11:37:02.024  6590  6931 D BluetoothAdapterProperties: Name is: A5-1
,08-30 11:37:02.024  1017  1017 D SettingsProvider: name = bluetooth_name
,08-30 11:37:02.024  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:37:02.034  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:37:02.034  6590  6931 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-30 11:37:02.034  6590  6931 D BluetoothAdapterProperties: Scan Mode:20
,08-30 11:37:02.034  6590  6931 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 11:37:02.034  6590  6931 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
,08-30 11:37:02.034  6590  6931 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-30 11:37:02.034  6590  6931 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,08-30 11:37:02.034  6590  6931 E bt-btif : btif_sock_init: !radio_req && !rfc_init,
08-30 11:37:02.034  6590  6931 E bt-btif : btif_sock_init: !vhci_init
08-30 11:37:02.034  6590  6931 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-30 11:37:02.034  6590  6931 D IOP_DB_BT: db_open: db_open : handle 2968887312l, read 13894 bytes onto local cache
08-30 11:37:02.034  6590  6931 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
08-30 11:37:02.034  6590  6931 D IOP_DB_BT: db_query: result 1
08-30 11:37:02.034  6590  6931 I         : iop_db_open: iop_db_open status 0
,08-30 11:37:02.044  6590  6931 D bte_conf: Device ID record 1 : primary
,08-30 11:37:02.044  6590  6931 D bte_conf:   vendorId            = 0075
08-30 11:37:02.044  6590  6931 D bte_conf:   vendorIdSource      = 0001
08-30 11:37:02.044  6590  6931 D bte_conf:   product             = 0100
08-30 11:37:02.044  1017  2734 D SSRM:n  : SIOP:: AP = 340
,08-30 11:37:02.044  6590  6931 D bte_conf:   version             = 0200
08-30 11:37:02.044  6590  6931 D bte_conf:   clientExecutableURL = 
08-30 11:37:02.044  6590  6931 D bte_conf:   serviceDescription  = 
08-30 11:37:02.044  6590  6931 D bte_conf:   documentationURL    = 
08-30 11:37:02.044  6590  6931 D bte_conf: bte_load_did_conf no section named DID2.
,08-30 11:37:02.044  6590  6931 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-30 11:37:02.044  6590  6928 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-30 11:37:02.044  6590  6928 D BluetoothAdapterProperties: ScanMode =  20
08-30 11:37:02.044  6590  6968 E bt_mct  : hci lib postload completed
08-30 11:37:02.044  6590  6928 D BluetoothAdapterProperties: State =  11
,08-30 11:37:02.044  1017  3289 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-30 11:37:02.044  6590  6928 D BluetoothAdapterProperties: Setting state to 12
,08-30 11:37:02.044  6590  6928 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-30 11:37:02.054  6590  6931 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-30 11:37:02.054  6590  6931 D BluetoothAdapterProperties: Scan Mode:21
,08-30 11:37:02.054  6590  6931 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 11:37:02.054  1017  1217 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-30 11:37:02.054  1017  1217 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 11:37:02.054  1017  1217 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 11:37:02.054  1017  1217 D SettingsProvider: selectionArgs: false
08-30 11:37:02.054  1017  1217 D SettingsProvider: selectionArgs: 1002
08-30 11:37:02.054  1017  1217 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-30 11:37:02.054  1017  1217 D SettingsProvider: ret = -1
08-30 11:37:02.054  6590  6928 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-30 11:37:02.054  6590  6928 D BluetoothAdapterService: updateAdapterState state is 12
,08-30 11:37:02.054  1017  1140 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 11:37:02.054  1017  1140 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-30 11:37:02.054  1017  1140 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:02.054  1017  1140 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:02.054  1017  1140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:02.074  2892  2901 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 11:37:02.074  1017  1047 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-30 11:37:02.074  6590  6928 D BluetoothAdapterService: Autoconnection is available 
08-30 11:37:02.074  6590  6928 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-30 11:37:02.074  6590  6928 D BluetoothAdapterService: starting service from this receiver
,08-30 11:37:02.074  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 11:37:02.074  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:37:02.074  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 11:37:02.074  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:37:02.074  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:02.074  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:37:02.074  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 11:37:02.074  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:37:02.074  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:37:02.074  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:37:02.074  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 11:37:02.074  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:02.074  1017  3289 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 11:37:02.084  1017  3289 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-30 11:37:02.084  2892  2901 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 11:37:02.084  6590  6590 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
08-30 11:37:02.084  1017  3289 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:37:02.084  6312  6326 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 11:37:02.084  1017  3289 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:02.084  1017  3289 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:02.084  6312  6326 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 11:37:02.084  6470  6481 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 11:37:02.084  6470  6481 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 11:37:02.084  1319  1332 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 11:37:02.084  6590  6928 I BluetoothAdapterState: Entering On State from state = 11
08-30 11:37:02.084  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 11:37:02.084  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 11:37:02.084  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:02.084  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:02.084  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-30 11:37:02.084  1319  1332 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 11:37:02.084  6590  6590 I BluetoothPbapService: Handler(): got msg=1
,08-30 11:37:02.094  2892  2900 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 11:37:02.094  6312  6312 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 11:37:02.094  1017  1029 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
08-30 11:37:02.094  1319  1319 D HeadsetProfile: Bluetooth service connected
,08-30 11:37:02.094  2892  2900 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-30 11:37:02.094  1017  1047 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-30 11:37:02.094  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 11:37:02.094  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:37:02.094  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:02.094  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:02.104  2892  2892 D BluetoothA2dp: Proxy object connected
,08-30 11:37:02.104  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:37:02.104  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:02.104  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:37:02.104  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 11:37:02.104  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:37:02.104  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:37:02.104  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:37:02.104  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 11:37:02.104  1177  1890 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 11:37:02.104  1177  1890 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 11:37:02.104  1017  1047 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 11:37:02.104  1017  1047 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 11:37:02.104  6590  6972 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-30 11:37:02.104  1429  2779 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 11:37:02.104  1017  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 11:37:02.104  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 11:37:02.104  6312  6312 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 11:37:02.114  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:02.114  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:02.114  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:02.114  1429  2779 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 11:37:02.114  6590  6972 D BluetoothSocket: bindListen(): myUserId = 0
,08-30 11:37:02.114  6590  6972 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 11:37:02.114  1453  1468 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 11:37:02.114  1453  1468 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 11:37:02.114  6590  6972 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
08-30 11:37:02.114  6590  6972 D BluetoothSocket: bindListen(), new LocalSocket 
,08-30 11:37:02.114  1319  1332 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 11:37:02.114  6590  6972 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-30 11:37:02.114  6590  6972 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@12a78749
08-30 11:37:02.114  6590  6972 D BluetoothSocket: channel: 19
08-30 11:37:02.114  6590  6972 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-30 11:37:02.114  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-30 11:37:02.114  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-30 11:37:02.124  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:37:02.124  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:02.124  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:02.124  1319  1339 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-30 11:37:02.124  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-30 11:37:02.124  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-30 11:37:02.124  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:02.124  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:02.124  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:02.124  1319  1319 D BluetoothPbap: Proxy object connected
08-30 11:37:02.124  1319  1319 D PbapServerProfile: Bluetooth service connected
,08-30 11:37:02.124  2892  6971 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 11:37:02.134  2892  6971 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 11:37:02.134  1319  1319 D BluetoothInputDevice: Proxy object connected
,08-30 11:37:02.134  1319  1339 D BluetoothPan: Binding service...
08-30 11:37:02.134  1319  1319 D HidProfile: Bluetooth service connected
,08-30 11:37:02.134  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-30 11:37:02.134  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-30 11:37:02.134  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:02.134  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:02.134  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:02.134  1929  2094 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 11:37:02.134  1929  2094 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 11:37:02.134  6590  6605 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 11:37:02.134  1319  1319 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 11:37:02.134  1319  1319 D PanProfile: Bluetooth service connected
,08-30 11:37:02.134  1453  1718 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 11:37:02.134  1017  1047 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 11:37:02.134  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 11:37:02.134  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:02.134  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 11:37:02.134  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:02.134  1453  1718 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 11:37:02.144  1429  1440 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 11:37:02.144  1017  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-30 11:37:02.144  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 11:37:02.144  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:37:02.144  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:02.144  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:02.144  1429  1440 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 11:37:02.144  1429  2777 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 11:37:02.144  1017  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-30 11:37:02.144  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 11:37:02.144  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:37:02.144  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:02.144  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:02.154  1429  2777 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 11:37:02.154  1429  2779 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 11:37:02.154  1429  2779 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 11:37:02.154  6590  6602 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 11:37:02.154  6590  6602 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 11:37:02.154  1319  1339 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 11:37:02.154  1319  1339 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 11:37:02.154  1017  1047 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 11:37:02.154  1017  1047 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-30 11:37:02.154  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-30 11:37:02.154  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 11:37:02.154  1017  1017 D BluetoothA2dp: Proxy object connected
08-30 11:37:02.154  1441  1465 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 11:37:02.154  1441  1465 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 11:37:02.154  1017  1047 D BluetoothPan: Binding service...
08-30 11:37:02.154  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-30 11:37:02.154  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-30 11:37:02.154  1017  1047 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-30 11:37:02.154  1017  1047 E BluetoothHeadset: BluetoothHeadset service is binded
08-30 11:37:02.154  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 11:37:02.154  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 11:37:02.154  1017  1017 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 11:37:02.154  1319  6974 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 11:37:02.154  1319  6974 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0,
,08-30 11:37:02.154  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-30 11:37:02.154  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-30 11:37:02.154  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:02.154  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:02.154  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-30 11:37:02.154  1319  1319 D BluetoothA2dp: Proxy object connected
08-30 11:37:02.154  1319  1319 D A2dpProfile: Bluetooth service connected
,08-30 11:37:02.154  1319  1339 D BluetoothMap: onBluetoothStateChange: up=true
,08-30 11:37:02.164  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-30 11:37:02.164  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-30 11:37:02.164  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:02.164  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:02.164  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:02.164  1319  1332 D Bluetoothsap: onBluetoothStateChange: up=true
08-30 11:37:02.164  1319  1332 D Bluetoothsap: Binding service...
,08-30 11:37:02.164  1319  1332 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 ,
08-30 11:37:02.164  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-30 11:37:02.164  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-30 11:37:02.164  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:02.164  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:02.164  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:02.164  1319  1319 D BluetoothMap: Proxy object connected
08-30 11:37:02.164  1319  1332 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-30 11:37:02.164  1319  1319 D MapProfile: Bluetooth service connected
08-30 11:37:02.164  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-30 11:37:02.164  1319  1319 D BluetoothMap: getConnectedDevices()
08-30 11:37:02.164  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-30 11:37:02.164  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-30 11:37:02.164  1017  1017 I InputMethodManagerService: [BT Setting State] State =12
08-30 11:37:02.174  1017  1017 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-30 11:37:02.174  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-30 11:37:02.174  1429  1429 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@886b3aa, true
,08-30 11:37:02.174  1429  1429 D BluetoothHeadset: registerMessageListener
,08-30 11:37:02.174  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-30 11:37:02.174  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:37:02.174  1177  1177 D BluetoothTile:  getBluetoothState : 12
,08-30 11:37:02.174  1177  1717 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 11:37:02.184  1177  1717 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 11:37:02.184  1017  3440 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 11:37:02.184  1017  1029 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-30 11:37:02.184  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 11:37:02.184  1177  1717 D BluetoothTile:  handleUpdatestate:false name:null
08-30 11:37:02.184  1770  1770 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 11:37:02.194  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:37:02.194  6590  6758 D HeadsetService: registerMessageListener
,08-30 11:37:02.194  1017  1477 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 11:37:02.194  1017  1477 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-30 11:37:02.194  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:37:02.194  1319  1319 D Bluetoothsap: BluetoothSAP Proxy object connected
08-30 11:37:02.194  1319  1319 D SapProfile: Bluetooth service connected
08-30 11:37:02.194  1319  1319 D Bluetoothsap: getConnectedDevices()
08-30 11:37:02.194  6590  6758 D HeadsetService: registerMessageListener
,08-30 11:37:02.194  6590  6937 D HeadsetStateMachine: Disconnected process message: 70
08-30 11:37:02.194  6590  6937 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@2d756a7c
08-30 11:37:02.194  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,08-30 11:37:02.194  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-30 11:37:02.194  1017  1477 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:02.194  1017  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:37:02.194  1017  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:37:02.204  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,08-30 11:37:02.204  6590  6977 D BluetoothMapMasInstance: set MAP SDP message type : 1
08-30 11:37:02.204  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-30 11:37:02.204  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-30 11:37:02.204  1319  1319 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 11:37:02.204  6590  6937 D HeadsetStateMachine: Disconnected process message: 9
08-30 11:37:02.214  6590  6937 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
08-30 11:37:02.214  6590  6977 D BluetoothSocket: bindListen(): myUserId = 0
08-30 11:37:02.214  6590  6977 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 11:37:02.214  6590  6977 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
08-30 11:37:02.214  6590  6977 D BluetoothSocket: bindListen(), new LocalSocket 
08-30 11:37:02.214  6590  6977 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-30 11:37:02.214  6590  6977 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@39584f05
08-30 11:37:02.214  6590  6977 D BluetoothSocket: channel: 5
,08-30 11:37:02.214   285  1014 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-30 11:37:02.214   285  1014 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-30 11:37:02.214   285  1014 V voice   : voice_set_parameters: exit with code(-2)
08-30 11:37:02.214   285  1014 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-30 11:37:02.214   285  1014 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-30 11:37:02.214   285  1014 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-30 11:37:02.214   285  1014 V audio_hw_primary: adev_set_parameters: exit
08-30 11:37:02.214  6590  6937 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
08-30 11:37:02.214  1319  1319 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-30 11:37:02.214  1319  1319 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-30 11:37:02.214  1319  1319 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-30 11:37:02.214  1319  1319 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-30 11:37:02.234  1319  1319 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 11:37:02.234  1017  3289 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-30 11:37:02.234  1017  3289 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-30 11:37:02.234  1017  3289 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:02.234  1017  3289 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:02.234  1017  3289 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-30 11:37:02.234  1319  1319 D DockEventReceiver: finishStartingService: stopping service
,08-30 11:37:02.234  1319  1319 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 11:37:02.244  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:37:02.244  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-30 11:37:02.254  6590  6590 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d50cf2
,08-30 11:37:02.254  6590  6590 D BtConfig.SecureMode: isSecureModeOn:false
,08-30 11:37:02.254  1017  3091 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 11:37:02.254  1017  3091 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-30 11:37:02.254  1017  3091 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:37:02.254  1017  3091 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:02.254  1017  3091 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:02.274  1929  1929 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-30 11:37:02.274  1017  1497 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 11:37:02.274  1017  1497 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-30 11:37:02.274  1017  1497 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:02.274  1017  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:37:02.274  1017  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:37:02.284  1017  1501 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-30 11:37:02.284  1929  6985 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-30 11:37:02.284  1929  1929 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-30 11:37:02.284   319   319 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 11:37:02.294  6590  6987 D BluetoothSocket: bindListen(): myUserId = 0
,08-30 11:37:02.294  6590  6987 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 11:37:02.294  6590  6987 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[81]}
,08-30 11:37:02.294  6590  6987 D BluetoothSocket: bindListen(), new LocalSocket 
08-30 11:37:02.294  6590  6987 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,08-30 11:37:02.294  6590  6987 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3493d681
08-30 11:37:02.294  6590  6987 D BluetoothSocket: channel: 12
,08-30 11:37:02.294  6590  6987 I BtOppRfcommListener: Accept thread started.
,08-30 11:37:02.304   290   290 E SMD     : DCD OFF
,08-30 11:37:02.434  1017  1497 I art     : Explicit concurrent mark sweep GC freed 66528(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 27MB/41MB, paused 2.430ms total 145.735ms
,08-30 11:37:02.434  1017  1497 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 11:37:02.434  1017  1497 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:02.434  1017  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:37:02.434  1017  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:37:02.444  1017  3091 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 11:37:02.454  1017  3091 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:37:02.454  1017  3091 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:37:02.454  1017  3091 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:37:02.454  1929  6985 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-30 11:37:03.294   319   319 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 11:37:04.124  6312  6364 D BluetoothAdapter: disable()
,08-30 11:37:04.124  1017  1501 D SettingsProvider: name = bluetooth_on
,08-30 11:37:04.134  6590  6928 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-30 11:37:04.134  6590  6928 D BluetoothAdapterProperties: Setting state to 13
08-30 11:37:04.134  6590  6928 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 11:37:04.134  6590  6928 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-30 11:37:04.134  6590  6928 D BluetoothAdapterService: updateAdapterState state is 13
08-30 11:37:04.134  1017  1477 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 11:37:04.134  1017  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-30 11:37:04.144  1017  1477 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:37:04.144  1017  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:04.144  1017  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:04.144  6590  6590 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-30 11:37:04.144  6590  6590 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1713d326, channel: 19, state: LISTENING
08-30 11:37:04.144  6590  6590 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1713d326, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@12a78749, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@132aab67mSocket: android.net.LocalSocket@220e8d14 impl:android.net.LocalSocketImpl@20a659bd fd:FileDescriptor[75]
08-30 11:37:04.144  6590  6590 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@220e8d14 impl:android.net.LocalSocketImpl@20a659bd fd:FileDescriptor[75]
,08-30 11:37:04.144  6590  6928 D BluetoothAdapterService: Autoconnection is available 
08-30 11:37:04.144  6590  6928 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-30 11:37:04.144  6590  6928 D BluetoothAdapterService: terminating service from this receiver
,08-30 11:37:04.144  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-30 11:37:04.144  1017  1017 I InputMethodManagerService: [BT Setting State] State =13
,08-30 11:37:04.154  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-30 11:37:04.164  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-30 11:37:04.164  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:37:04.164  1177  1177 D BluetoothTile:  getBluetoothState : 13
,08-30 11:37:04.164  1177  1717 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 11:37:04.164  1177  1717 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 11:37:04.164  1017  1140 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 11:37:04.164  1177  1717 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-30 11:37:04.164  1017  3440 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-30 11:37:04.174  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-30 11:37:04.174  1770  1770 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 11:37:04.184  1319  1319 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 11:37:04.184  6312  6312 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:37:04.184  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:37:04.184  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:04.184  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:37:04.184  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 11:37:04.184  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 11:37:04.184  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:37:04.184  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:37:04.184  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 11:37:04.184  6312  6312 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 11:37:04.184  6312  6312 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 11:37:04.184  1017  3091 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-30 11:37:04.194  1017  3091 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:04.194  1017  3091 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:04.194  1017  3091 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:04.194  6590  6928 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 11:37:04.194  6590  6928 D BluetoothAdapterProperties: mDiscovering is false
,08-30 11:37:04.194  1017  1560 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-30 11:37:04.194  1017  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 11:37:04.194  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-30 11:37:04.194  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:04.194  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:37:04.194  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:37:04.194  6590  6928 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-30 11:37:04.204  1319  1319 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 11:37:04.204  6312  6312 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 11:37:04.204  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:37:04.204  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:04.204  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:37:04.204  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 11:37:04.204  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 11:37:04.204  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:37:04.204  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:37:04.204  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 11:37:04.204  6312  6312 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:37:04.204  6312  6312 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 11:37:04.204  1017  1029 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings,
08-30 11:37:04.204  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-30 11:37:04.214  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:37:04.214  6590  6931 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-30 11:37:04.214  6590  6931 D BluetoothAdapterProperties: Scan Mode:20
,08-30 11:37:04.214  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:04.214  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-30 11:37:04.224  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:37:04.224  6590  6928 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-30 11:37:04.224  6590  6928 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-30 11:37:04.224  6590  6928 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-30 11:37:04.224  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:04.224  6590  6987 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 11:37:04.224  6590  6928 E bt-btif : cmd socket is not created
,08-30 11:37:04.224  6590  6928 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 11:37:04.224  6590  6946 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-30 11:37:04.224  6590  6946 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-30 11:37:04.224  6590  6946 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 11:37:04.224  6590  6946 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 11:37:04.224  6590  6946 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-30 11:37:04.234  1319  1319 D BluetoothPbap: Proxy object disconnected
08-30 11:37:04.234  1319  1319 D PbapServerProfile: Bluetooth service disconnected
,08-30 11:37:04.234  1319  1319 D DockEventReceiver: finishStartingService: stopping service
,08-30 11:37:04.244  6590  6590 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3b59fbb2, channel: 5, state: LISTENING
08-30 11:37:04.244  6590  6590 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3b59fbb2, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@39584f05, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@dac9703mSocket: android.net.LocalSocket@37d16680 impl:android.net.LocalSocketImpl@1863d4b9 fd:FileDescriptor[77]
08-30 11:37:04.244  6590  6590 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@37d16680 impl:android.net.LocalSocketImpl@1863d4b9 fd:FileDescriptor[77]
,08-30 11:37:04.244  6590  6590 I BtOppRfcommListener: stopping Accept Thread
08-30 11:37:04.244  6590  6590 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@d6820fe, channel: 12, state: LISTENING
08-30 11:37:04.244  6590  6590 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@d6820fe, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3493d681, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@31d7a05fmSocket: android.net.LocalSocket@14266aac impl:android.net.LocalSocketImpl@35e40375 fd:FileDescriptor[81]
08-30 11:37:04.244  6590  6590 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@14266aac impl:android.net.LocalSocketImpl@35e40375 fd:FileDescriptor[81]
,08-30 11:37:04.244  6590  6987 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-30 11:37:04.244  1319  1319 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 11:37:04.244  6590  6590 V BluetoothOppManager: cleanUp...
,08-30 11:37:04.264  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 11:37:04.264  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-30 11:37:04.274  1929  1929 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-30 11:37:04.284  1929  1929 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-30 11:37:04.294   319   319 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 11:37:04.434  6590  6946 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-30 11:37:04.434  6590  6946 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 11:37:04.434  6590  6946 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-30 11:37:04.434  6590  6946 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 11:37:04.434  6590  6946 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 11:37:04.434  6590  6946 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-30 11:37:04.434  6590  6946 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 11:37:04.434  6590  6946 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 11:37:04.434  6590  6946 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-30 11:37:04.434  6590  6946 W bt-btif : ag scb idx 1 not allocated
08-30 11:37:04.434  6590  6946 W bt-btif : ag scb idx 2 not allocated
08-30 11:37:04.434  6590  6946 E bt-btif : BTA AG is already disabled, ignoring ...
,08-30 11:37:04.434  6590  6968 I bt_userial_mct: exiting userial_read_thread
08-30 11:37:04.434  6590  6968 D bt_userial_mct: Leaving userial_evt_read_thread()
,08-30 11:37:04.434  6590  6931 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
,08-30 11:37:04.434  6590  6948 I bt_vendor: hw_epilog_process
,08-30 11:37:04.434  6590  6931 D bt_userial_mct: userial_close
08-30 11:37:04.434  6590  6931 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-30 11:37:04.904  1017  1968 V SAMP_SPCM_test: CSC File load.. 
,08-30 11:37:04.914  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,08-30 11:37:04.914  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
08-30 11:37:04.914  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
,08-30 11:37:04.914  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
08-30 11:37:04.914  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
08-30 11:37:04.914  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
08-30 11:37:04.914  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
,08-30 11:37:04.914  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
08-30 11:37:04.914  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
08-30 11:37:04.914  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
08-30 11:37:04.914  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
,08-30 11:37:04.914  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
08-30 11:37:04.914  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
08-30 11:37:04.914  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
,08-30 11:37:04.914  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
08-30 11:37:04.914  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
08-30 11:37:04.914  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
,08-30 11:37:04.914  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
08-30 11:37:04.914  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
08-30 11:37:04.914  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
,08-30 11:37:04.914  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,08-30 11:37:04.964  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,08-30 11:37:04.964  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
08-30 11:37:04.964  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
08-30 11:37:04.964  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
,08-30 11:37:04.964  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
08-30 11:37:04.964  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
08-30 11:37:04.964  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
,08-30 11:37:04.964  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
08-30 11:37:04.964  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
08-30 11:37:04.964  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
08-30 11:37:04.964  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
,08-30 11:37:04.964  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
08-30 11:37:04.974  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
,08-30 11:37:04.974  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
08-30 11:37:04.974  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
08-30 11:37:04.974  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
08-30 11:37:04.974  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
,08-30 11:37:04.974  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
08-30 11:37:04.974  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
08-30 11:37:04.974  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-30 11:37:04.974  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-30 11:37:04.984  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
,08-30 11:37:04.984  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
08-30 11:37:04.984  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
08-30 11:37:04.984  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
,08-30 11:37:04.984  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
08-30 11:37:04.984  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
08-30 11:37:04.984  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
08-30 11:37:04.984  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
08-30 11:37:04.984  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
,08-30 11:37:04.984  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
08-30 11:37:04.984  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
08-30 11:37:04.984  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
08-30 11:37:04.984  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
08-30 11:37:04.984  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
08-30 11:37:04.984  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
08-30 11:37:04.984  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
08-30 11:37:04.984  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
08-30 11:37:04.984  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
08-30 11:37:04.984  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
08-30 11:37:04.984  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
08-30 11:37:04.984  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
08-30 11:37:04.984  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
08-30 11:37:04.984  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
08-30 11:37:04.984  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
08-30 11:37:04.984  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
08-30 11:37:04.984  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
08-30 11:37:04.984  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies o,f ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
08-30 11:37:04.984  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
08-30 11:37:04.984  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
08-30 11:37:04.984  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
08-30 11:37:04.984  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-30 11:37:04.984  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
08-30 11:37:04.984  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
08-30 11:37:04.984  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
08-30 11:37:04.984  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
08-30 11:37:04.984  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
08-30 11:37:04.984  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-30 11:37:04.984  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
08-30 11:37:04.984  1017  1968 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,08-30 11:37:04.994  1017  1968 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
,08-30 11:37:04.994  1017  1968 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:37:04.994  1017  1968 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:37:04.994  1017  1968 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:37:04.994  1017  1968 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:37:05.014  6999  6999 E Zygote  : MountEmulatedStorage()
08-30 11:37:05.014  6999  6999 E Zygote  : v2
08-30 11:37:05.014  6999  6999 I libpersona: KNOX_SDCARD checking this for 1000
08-30 11:37:05.014  6999  6999 I libpersona: KNOX_SDCARD not a persona
,08-30 11:37:05.014  1017  1968 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=6999 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,08-30 11:37:05.014  6999  6999 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 11:37:05.024  6999  6999 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-30 11:37:05.024  6999  6999 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-30 11:37:05.044  6999  6999 D TimaKeyStoreProvider: TimaSignature is unavailable,
,08-30 11:37:05.044  6999  6999 D ActivityThread: Added TimaKeyStore provider
,08-30 11:37:05.054  6999  6999 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-30 11:37:05.094  1017  1968 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,08-30 11:37:05.124  6590  6931 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-30 11:37:05.124  6590  6931 I bt_vendor: bluetooth satus is on
08-30 11:37:05.124  6590  6931 I bt_vendor: bt-vendor : resetting BT status
08-30 11:37:05.124  6590  6931 I bt_vendor: Starting hciattach daemon
08-30 11:37:05.124  6590  6931 I bt_vendor: try to set false
,08-30 11:37:05.124  6590  6931 I bt_vendor: Starting hciattach daemon
08-30 11:37:05.124  6590  6931 I bt_vendor: try to set false
,08-30 11:37:05.124  6590  6931 I bt_vendor: cleanup
,08-30 11:37:05.124  6590  6946 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-30 11:37:05.124  6590  6931 I GKI_LINUX: GKI_exit_task 0 done
08-30 11:37:05.124  6590  6931 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-30 11:37:05.124  6590  6928 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-30 11:37:05.124  6590  6928 D BtConfig.SecureMode: isSecureModeOn:false
08-30 11:37:05.124  6590  6928 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,08-30 11:37:05.124  6590  6928 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-30 11:37:05.124  6590  6928 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-30 11:37:05.124  6590  6928 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-30 11:37:05.124  1017  1478 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 11:37:05.134  1017  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-30 11:37:05.134  1017  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:37:05.134  1017  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:05.134  1017  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:05.134  6590  6928 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,08-30 11:37:05.134  6590  6928 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-30 11:37:05.134  6590  6928 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-30 11:37:05.134  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 11:37:05.134  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-30 11:37:05.134  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:37:05.134  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:05.134  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:05.134  6590  6928 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,08-30 11:37:05.134  6590  6928 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-30 11:37:05.134  6590  6928 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-30 11:37:05.144  6590  6590 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 11:37:05.144  1017  1501 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 11:37:05.144  1017  1501 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 11:37:05.144  6590  6590 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 11:37:05.144  6590  6590 D BtGatt.GattService: stop()
08-30 11:37:05.144  6590  6590 D BtGatt.AdvertiseManager: advertise clients cleared
,08-30 11:37:05.144  1017  1501 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:05.144  1017  1501 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:05.144  1017  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:05.144  6590  6590 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d50cf2
08-30 11:37:05.144  6590  6928 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-30 11:37:05.144  6590  6928 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 11:37:05.144  6590  6928 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-30 11:37:05.144  1017  3440 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 11:37:05.144  1017  3440 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-30 11:37:05.144  1017  3440 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:37:05.144  1017  3440 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:05.144  1017  3440 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:05.144  6590  6928 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-30 11:37:05.144  6590  6928 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-30 11:37:05.144  6590  6928 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-30 11:37:05.144  6590  6590 D HeadsetService: Received stop request...Stopping profile...
,08-30 11:37:05.144  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 11:37:05.144  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-30 11:37:05.144  6590  6590 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d50cf2
08-30 11:37:05.144  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:05.144  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:05.144  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:05.154  6590  6928 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-30 11:37:05.154  6590  6928 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-30 11:37:05.154  6590  6928 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-30 11:37:05.154  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-30 11:37:05.154  1017  1140 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 11:37:05.154  1017  1140 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-30 11:37:05.154  1017  1140 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:05.154  1017  1140 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:05.154  1017  1140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:05.154  6590  6590 D A2dpService: Received stop request...Stopping profile...
,08-30 11:37:05.154  6590  6941 D A2dpStateMachine: Exit Disconnected: -1
,08-30 11:37:05.154  1319  1319 D HeadsetProfile: Bluetooth service disconnected
,08-30 11:37:05.164  6590  6928 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-30 11:37:05.164  6590  6928 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 11:37:05.164  6590  6928 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-30 11:37:05.164  6590  6590 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d50cf2
,08-30 11:37:05.164  1017  1017 D BluetoothA2dp: Proxy object disconnected
08-30 11:37:05.164  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-30 11:37:05.164  1017  1478 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 11:37:05.164  1017  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-30 11:37:05.164  1017  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:37:05.164  1017  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:05.164  1017  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:05.164  6590  6928 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-30 11:37:05.164  6590  6928 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-30 11:37:05.164  6590  6928 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-30 11:37:05.164  2892  2892 D BluetoothA2dp: Proxy object disconnected
08-30 11:37:05.164  1017  3091 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 11:37:05.164  1017  3091 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-30 11:37:05.164  1319  1319 D BluetoothA2dp: Proxy object disconnected
08-30 11:37:05.164  1319  1319 D A2dpProfile: Bluetooth service disconnected
,08-30 11:37:05.164  1017  3091 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:37:05.164  1017  3091 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:05.164  1017  3091 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:05.164  6590  6928 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-30 11:37:05.164  6590  6928 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-30 11:37:05.164  6590  6928 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-30 11:37:05.174  6590  6928 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,08-30 11:37:05.174  6590  6928 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-30 11:37:05.174  6590  6928 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,08-30 11:37:05.174  6590  6928 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-30 11:37:05.174  6590  6928 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-30 11:37:05.174  6590  6928 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,08-30 11:37:05.174  6590  6928 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-30 11:37:05.174  6590  6928 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-30 11:37:05.174  6590  6928 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,08-30 11:37:05.174  6590  6928 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-30 11:37:05.174  6590  6590 E BluetoothAdapterService(869600498): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,08-30 11:37:05.174  6590  6590 D HidService: Received stop request...Stopping profile...
,08-30 11:37:05.174  6590  6590 D HidService: Stopping Bluetooth HidService
,08-30 11:37:05.174  6590  6590 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 11:37:05.174  6590  6590 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-30 11:37:05.174  6590  6590 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object,
08-30 11:37:05.174  6590  6590 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d50cf2
,08-30 11:37:05.174  6590  6590 E BluetoothAdapterService(869600498): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-30 11:37:05.174  6590  6590 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 11:37:05.174  6590  6590 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-30 11:37:05.174  6590  6590 D HealthService: Received stop request...Stopping profile...
,08-30 11:37:05.184  6590  6590 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d50cf2
08-30 11:37:05.184  1319  1319 D BluetoothInputDevice: Proxy object disconnected
,08-30 11:37:05.184  1319  1319 D HidProfile: Bluetooth service disconnected
,08-30 11:37:05.184  6590  6590 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-30 11:37:05.184  6590  6590 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-30 11:37:05.184  6590  6590 D PanService: Received stop request...Stopping profile...
08-30 11:37:05.184  6590  6590 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d50cf2
,08-30 11:37:05.184  1017  1017 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-30 11:37:05.184  6590  6590 E BluetoothAdapterService(869600498): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,08-30 11:37:05.184  6590  6590 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 11:37:05.184  1319  1319 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-30 11:37:05.184  1319  1319 D PanProfile: Bluetooth service disconnected
08-30 11:37:05.184  6590  6590 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-30 11:37:05.184  6590  6590 D BluetoothA2dp: Proxy object disconnected
,08-30 11:37:05.184  6590  6590 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-30 11:37:05.184  6590  6942 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-30 11:37:05.194  6590  6590 I GKI_LINUX: GKI_exit_task 2 done
08-30 11:37:05.194  6590  6590 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-30 11:37:05.194  6590  6590 D BluetoothMapService: Received stop request...Stopping profile...
,08-30 11:37:05.194  6590  6590 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d50cf2
,08-30 11:37:05.194  1319  1319 D BluetoothMap: Proxy object disconnected
,08-30 11:37:05.194  1319  1319 D MapProfile: Bluetooth service disconnected
08-30 11:37:05.194  6590  6590 D SapService: Received stop request...Stopping profile...
08-30 11:37:05.194  6590  6590 D SapService: Stopping Bluetooth SapService
08-30 11:37:05.194  6590  6590 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d50cf2
,08-30 11:37:05.194  1319  1319 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-30 11:37:05.194  6590  6590 E BluetoothAdapterService(869600498): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-30 11:37:05.194  6590  6590 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 11:37:05.194  6590  6590 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-30 11:37:05.194  6590  6590 E BluetoothAdapterService(869600498): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-30 11:37:05.194  6590  6590 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 11:37:05.194  6590  6590 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-30 11:37:05.194  6590  6590 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-30 11:37:05.194  6590  6590 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 11:37:05.194  6590  6590 E BluetoothAdapterService(869600498): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
,08-30 11:37:05.194  6590  6590 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 11:37:05.194  6590  6590 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-30 11:37:05.194  1319  1319 D SapProfile: Bluetooth service disconnected
08-30 11:37:05.194  6590  6590 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 11:37:05.194  6590  6590 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-30 11:37:05.204  6590  6590 E BluetoothAdapterService(869600498): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,08-30 11:37:05.204  6590  6590 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-30 11:37:05.204  6590  6590 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-30 11:37:05.204  6590  6590 E BluetoothAdapterService(869600498): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-30 11:37:05.204  6590  6928 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-30 11:37:05.204  6590  6590 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-30 11:37:05.204  6590  6590 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-30 11:37:05.204  6590  6928 D BluetoothAdapterProperties: Setting state to 10
08-30 11:37:05.204  6590  6928 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-30 11:37:05.204  6590  6928 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-30 11:37:05.204  6590  6928 D BluetoothAdapterService: updateAdapterState state is 10
,08-30 11:37:05.204  6590  6928 D BluetoothAdapterService: Autoconnection is available 
08-30 11:37:05.204  6590  6928 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-30 11:37:05.204  6590  6928 I BluetoothAdapterState: Entering OffState
,08-30 11:37:05.204  6312  6326 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 11:37:05.204  6312  6326 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 11:37:05.204  6312  6326 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,08-30 11:37:05.204  6312  6326 D BluetoothLeAdvertiser: Exit stop advertising
08-30 11:37:05.204  6312  6326 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
,08-30 11:37:05.204  6312  6326 D BluetoothLeScanner: Exiting stopAllScan
,08-30 11:37:05.204  6470  6481 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 11:37:05.204  6470  6481 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 11:37:05.214  2892  6971 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 11:37:05.214  1177  1188 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 11:37:05.214  1177  1188 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 11:37:05.214  1017  1047 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 11:37:05.214  1017  1047 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 11:37:05.214  1453  1468 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 11:37:05.214  1453  1468 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 11:37:05.214  1319  1339 D BluetoothPbap: onBluetoothStateChange: up=false
,08-30 11:37:05.214  1319  1332 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-30 11:37:05.214  2892  2901 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 11:37:05.214  2892  2901 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 11:37:05.214  1929  1942 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 11:37:05.224  1929  1942 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 11:37:05.224  6590  6976 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 11:37:05.224  1429  2778 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 11:37:05.224  1429  2778 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 11:37:05.224  6590  6758 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 11:37:05.224  6590  6758 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 11:37:05.224  1319  6974 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 11:37:05.224  1319  6974 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 11:37:05.224  1017  1047 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 11:37:05.224  1441  1462 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 11:37:05.224  1441  1462 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 11:37:05.224  1319  1339 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 11:37:05.224  1319  1332 D BluetoothMap: onBluetoothStateChange: up=false
,08-30 11:37:05.224  1319  6975 D Bluetoothsap: onBluetoothStateChange: up=false
,08-30 11:37:05.224  1319  6975 D Bluetoothsap: Unbinding service...
,08-30 11:37:05.234  1017  1047 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 11 receivers.
,08-30 11:37:05.234  1017  1047 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-30 11:37:05.244  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-30 11:37:05.244  1017  1017 I InputMethodManagerService: [BT Setting State] State =10
08-30 11:37:05.244  6590  6931 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-30 11:37:05.244  1017  1017 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-30 11:37:05.244  6590  6590 I GKI_LINUX: GKI_exit_task 1 done
08-30 11:37:05.244  6590  6590 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-30 11:37:05.244  6590  6590 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-30 11:37:05.244  1177  1177 D BluetoothAdapter: 690758941: getState() :  mService = null. Returning STATE_OFF
,08-30 11:37:05.244  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-30 11:37:05.244  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:37:05.244  1177  1177 D BluetoothTile:  getBluetoothState : 10
08-30 11:37:05.244  1177  1717 D BluetoothAdapter: 690758941: getState() :  mService = null. Returning STATE_OFF
,08-30 11:37:05.244  1177  1717 D BluetoothAdapter: 690758941: getState() :  mService = null. Returning STATE_OFF
08-30 11:37:05.244  1177  1177 D BluetoothAdapter: 690758941: getState() :  mService = null. Returning STATE_OFF
08-30 11:37:05.244  1177  1177 D BluetoothAdapter: 690758941: getState() :  mService = null. Returning STATE_OFF
,08-30 11:37:05.244  1017  1217 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-30 11:37:05.244  1017  1497 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-30 11:37:05.244  6590  6590 I art     : System.exit called, status: 0
08-30 11:37:05.244  6590  6590 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 11:37:05.244  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-30 11:37:05.244  1770  1770 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 11:37:05.244  1929  2106 D BluetoothAdapter: 997781882: getState() :  mService = null. Returning STATE_OFF
08-30 11:37:05.244  1929  2106 D BluetoothAdapter: 997781882: getState() :  mService = null. Returning STATE_OFF
08-30 11:37:05.254  1319  1319 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 11:37:05.254  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:05.254  1017  3289 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 11:37:05.254  1017  3289 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-30 11:37:05.264  1017  3289 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:37:05.264  1017  3289 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:37:05.264  1017  3289 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:37:05.264  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:37:05.264  1319  1319 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 11:37:05.264  1017  1029 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-30 11:37:05.264  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-30 11:37:05.264  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:37:05.264  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:05.264  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-30 11:37:05.284  1319  1319 D DockEventReceiver: finishStartingService: stopping service
,08-30 11:37:05.284  1319  1319 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 11:37:05.284  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:37:05.284  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-30 11:37:05.294   319   319 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 11:37:05.294  1017  1497 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-30 11:37:05.294  1017  1497 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-30 11:37:05.294  1017  1497 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
08-30 11:37:05.294  1017  1497 W BroadcastQueue: android.os.TransactionTooLargeException
08-30 11:37:05.294  1017  1497 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 11:37:05.294  1017  1497 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 11:37:05.294  1017  1497 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-30 11:37:05.294  1017  1497 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-30 11:37:05.294  1017  1497 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-30 11:37:05.294  1017  1497 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20437)
08-30 11:37:05.294  1017  1497 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-30 11:37:05.294  1017  1497 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3278)
08-30 11:37:05.294  1017  1497 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,08-30 11:37:05.294  1017  1497 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-30 11:37:05.294  1017  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:37:05.294  1017  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:37:05.294  1017  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:37:05.294  1017  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:37:05.304   290   290 E SMD     : DCD OFF
,08-30 11:37:05.314  7020  7020 E Zygote  : MountEmulatedStorage(),
08-30 11:37:05.314  7020  7020 E Zygote  : v2
,08-30 11:37:05.314  7020  7020 I libpersona: KNOX_SDCARD checking this for 1002
08-30 11:37:05.314  7020  7020 I libpersona: KNOX_SDCARD not a persona
,08-30 11:37:05.314  7020  7020 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-30 11:37:05.314  7020  7020 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 11:37:05.314  1017  1497 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7020 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-30 11:37:05.314  7020  7020 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 11:37:05.334  7020  7020 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 11:37:05.334  7020  7020 D ActivityThread: Added TimaKeyStore provider
,08-30 11:37:05.344  7020  7020 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-30 11:37:05.344  7020  7020 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 11:37:05.364  7020  7020 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-30 11:37:05.404  7020  7020 D BtSettings.ProfileConfig: Adding GattService
,08-30 11:37:05.404  7020  7020 D BtSettings.ProfileConfig: Adding HeadsetService
08-30 11:37:05.404  7020  7020 D BtSettings.ProfileConfig: Adding A2dpService
,08-30 11:37:05.404  7020  7020 D BtSettings.ProfileConfig: Adding HidService
08-30 11:37:05.404  7020  7020 D BtSettings.ProfileConfig: Adding HealthService
,08-30 11:37:05.404  7020  7020 D BtSettings.ProfileConfig: Adding PanService
08-30 11:37:05.404  7020  7020 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-30 11:37:05.404  7020  7020 D BtSettings.ProfileConfig: Adding SapService
08-30 11:37:05.404  7020  7020 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-30 11:37:05.404  7020  7020 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-30 11:37:05.404  7020  7020 D BtSettings.ProfileConfig: Adding SapClientService
,08-30 11:37:05.404  7020  7020 D BtSettings.ProfileConfig: Adding HidDevService
08-30 11:37:05.404  7020  7020 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-30 11:37:05.404  1017  1350 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-30 11:37:05.404  1017  1350 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-30 11:37:05.404  1017  1350 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 11:37:05.404  1017  1350 D SettingsProvider: selectionArgs: false
,08-30 11:37:05.404  1017  1350 D SettingsProvider: selectionArgs: 1002
,08-30 11:37:05.404  1017  1350 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-30 11:37:05.404  1017  1350 D SettingsProvider: ret = -1
,08-30 11:37:05.404  1017  3289 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-30 11:37:05.404  1017  3289 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 11:37:05.404  1017  3289 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 11:37:05.404  1017  3289 D SettingsProvider: selectionArgs: false
08-30 11:37:05.404  1017  3289 D SettingsProvider: selectionArgs: 1002
08-30 11:37:05.404  1017  3289 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 11:37:05.404  1017  3289 D SettingsProvider: ret = -1
,08-30 11:37:05.404  1017  1030 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-30 11:37:05.404  1017  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 11:37:05.404  1017  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 11:37:05.404  1017  1030 D SettingsProvider: selectionArgs: false
08-30 11:37:05.404  1017  1030 D SettingsProvider: selectionArgs: 1002
08-30 11:37:05.414  1017  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 11:37:05.414  1017  1030 D SettingsProvider: ret = -1
,08-30 11:37:05.414  1017  3440 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-30 11:37:05.414  1017  3440 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 11:37:05.414  1017  3440 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 11:37:05.414  1017  3440 D SettingsProvider: selectionArgs: false
08-30 11:37:05.414  1017  3440 D SettingsProvider: selectionArgs: 1002
08-30 11:37:05.414  1017  3440 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 11:37:05.414  1017  3440 D SettingsProvider: ret = -1
,08-30 11:37:05.414  1017  1497 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-30 11:37:05.414  1017  1497 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 11:37:05.414  1017  1497 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 11:37:05.414  1017  1497 D SettingsProvider: selectionArgs: false
08-30 11:37:05.414  1017  1497 D SettingsProvider: selectionArgs: 1002
08-30 11:37:05.414  1017  1497 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 11:37:05.414  1017  1497 D SettingsProvider: ret = -1
,08-30 11:37:05.414  1017  1478 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
,08-30 11:37:05.414  1017  1478 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 11:37:05.414  1017  1478 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 11:37:05.414  1017  1478 D SettingsProvider: selectionArgs: false
08-30 11:37:05.414  1017  1478 D SettingsProvider: selectionArgs: 1002
08-30 11:37:05.414  1017  1478 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 11:37:05.414  1017  1478 D SettingsProvider: ret = -1
,08-30 11:37:05.414  1017  1029 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,08-30 11:37:05.414  1017  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 11:37:05.414  1017  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-30 11:37:05.414  1017  1029 D SettingsProvider: selectionArgs: false
08-30 11:37:05.414  1017  1029 D SettingsProvider: selectionArgs: 1002
,08-30 11:37:05.414  1017  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-30 11:37:05.414  1017  1029 D SettingsProvider: ret = -1
,08-30 11:37:05.414  1017  1477 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
,08-30 11:37:05.414  1017  1477 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-30 11:37:05.414  1017  1477 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 11:37:05.414  1017  1477 D SettingsProvider: selectionArgs: false
,08-30 11:37:05.414  1017  1477 D SettingsProvider: selectionArgs: 1002
,08-30 11:37:05.414  1017  1477 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-30 11:37:05.414  1017  1477 D SettingsProvider: ret = -1
,08-30 11:37:05.414  1017  1501 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,08-30 11:37:05.414  1017  1501 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 11:37:05.414  1017  1501 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-30 11:37:05.424  1017  1501 D SettingsProvider: selectionArgs: false
08-30 11:37:05.424  1017  1501 D SettingsProvider: selectionArgs: 1002
,08-30 11:37:05.424  1017  1501 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-30 11:37:05.424  1017  1501 D SettingsProvider: ret = -1
,08-30 11:37:05.424  1017  1217 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,08-30 11:37:05.424  1017  1217 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 11:37:05.424  1017  1217 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-30 11:37:05.424  1017  1217 D SettingsProvider: selectionArgs: false
08-30 11:37:05.424  1017  1217 D SettingsProvider: selectionArgs: 1002
,08-30 11:37:05.424  1017  1217 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-30 11:37:05.424  1017  1217 D SettingsProvider: ret = -1
,08-30 11:37:05.424  1017  3091 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService,
08-30 11:37:05.424  1017  3091 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 11:37:05.424  1017  3091 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 11:37:05.424  1017  3091 D SettingsProvider: selectionArgs: false
,08-30 11:37:05.424  1017  3091 D SettingsProvider: selectionArgs: 1002,
08-30 11:37:05.424  1017  3091 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 11:37:05.424  1017  3091 D SettingsProvider: ret = -1
08-30 11:37:05.424  1017  1560 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
,08-30 11:37:05.424  1017  1560 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 11:37:05.424  1017  1560 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 11:37:05.424  1017  1560 D SettingsProvider: selectionArgs: false
08-30 11:37:05.424  1017  1560 D SettingsProvider: selectionArgs: 1002,
08-30 11:37:05.424  1017  1560 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 11:37:05.424  1017  1560 D SettingsProvider: ret = -1
,08-30 11:37:05.434  1929  1929 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-30 11:37:05.444  1017  1497 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 11:37:05.444  1017  1497 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-30 11:37:05.444  1017  1497 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:37:05.444  1017  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 11:37:05.444  1017  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:37:05.454  1929  7036 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-30 11:37:05.454  1929  1929 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-30 11:37:05.454  1017  1497 I ActivityManager: Killing 5617:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,08-30 11:37:05.464  1017  1350 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 11:37:05.474  1017  1350 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:37:05.474  1017  1350 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:37:05.474  1017  1350 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:37:05.484  1929  7036 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-30 11:37:06.304   319   319 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-30 11:37:07.144  6312  6364 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 11:37:07.144  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:37:08.304   290   290 E SMD     : DCD OFF
,08-30 11:37:08.614  1017  1560 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-30 11:37:08.614  1017  1560 D BatteryService: level:86, scale:100, status:2, health:2, present:true, voltage: 4152, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,08-30 11:37:08.614  1017  1560 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,08-30 11:37:08.624  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-30 11:37:08.614  1017  1560 D BatteryService: stay LED for charging
,08-30 11:37:08.624  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate,
08-30 11:37:08.614  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-30 11:37:08.624  1017  1017 I MotionRecognitionService: Plugged,
08-30 11:37:08.624  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
08-30 11:37:08.624  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-30 11:37:08.624  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 86
,08-30 11:37:08.654  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:86 status:2 health:2
,08-30 11:37:08.654  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:86 status:2 health:2
,08-30 11:37:08.654  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:86 status:2 health:2
,08-30 11:37:10.134  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 11:37:10.134  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4cb8202 added. We now have 6 listener(s)
08-30 11:37:10.134  6312  6364 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 11:37:10.144  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 11:37:10.144  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1bcf2713 added. We now have 7 listener(s)
08-30 11:37:10.144  6312  6364 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 11:37:10.144  6312  6364 I System.out: IsBluetoothEnabled
08-30 11:37:10.144  6312  6364 D BluetoothAdapter: disable()
,08-30 11:37:10.144  1017  1497 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-30 11:37:10.144  6312  6364 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:37:10.144  6312  6364 D BluetoothAdapter: enable()
,08-30 11:37:10.154  1017  3440 W ActivityManager: Permission Denial: getCurrentUser() from pid=6312, uid=10155 requires android.permission.INTERACT_ACROSS_USERS,
,08-30 11:37:10.154  1017  3440 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
08-30 11:37:10.154  1017  3440 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6312, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-30 11:37:10.154  1017  3440 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-30 11:37:10.154  1017  3440 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
08-30 11:37:10.154  1017  3440 W BluetoothManagerService: 	,at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
08-30 11:37:10.154  1017  3440 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
08-30 11:37:10.154  1017  3440 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-30 11:37:10.154  1017  3440 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-30 11:37:10.154  1017  3440 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 11:37:10.154  1017  3440 D SettingsProvider: name = bluetooth_on,
,08-30 11:37:10.164  1017  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-30 11:37:10.164  1017  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 11:37:10.164  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth,
08-30 11:37:10.164  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2,
,08-30 11:37:10.184  7020  7020 D BluetoothAdapterState: make
,08-30 11:37:10.194  7020  7020 I bluedroid: init
,08-30 11:37:10.194  7020  7042 I BluetoothAdapterState: Entering OffState
,08-30 11:37:10.194  7020  7020 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-30 11:37:10.194  7020  7020 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-30 11:37:10.194  7020  7020 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 11:37:10.194  7020  7020 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-30 11:37:10.194  7020  7020 E bt-btif : btif_fetch_local_ble_random_bdaddr
08-30 11:37:10.194  7020  7020 I bluedroid: get_profile_interface socket
,08-30 11:37:10.194  7020  7020 I bluedroid: get_profile_interface map_client
,08-30 11:37:10.204  7020  7045 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-30 11:37:10.204  7020  7020 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-30 11:37:10.204  7020  7045 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,08-30 11:37:10.204  7020  7045 E BluetoothServiceJni: populateRssiValuesNative
,08-30 11:37:10.204  7020  7045 I bluedroid: getModelRssiValues
08-30 11:37:10.204  7020  7045 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-30 11:37:10.204  7020  7045 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-30 11:37:10.204  1017  1017 D SettingsProvider: name = bluetooth_name
,08-30 11:37:10.204  7020  7045 D BluetoothAdapterProperties: Name is: A5-1
,08-30 11:37:10.214  7020  7020 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-30 11:37:10.214  1017  1478 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp,
08-30 11:37:10.214  1017  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0,
,08-30 11:37:10.214  1017  1478 W ActivityManager: userId = 0, bbcId = -10000,
08-30 11:37:10.214  1017  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:10.214  1017  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:10.214  7020  7028 I bluedroid: config_hci_snoop_log
,08-30 11:37:10.214  1017  1047 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,08-30 11:37:10.224  1017  1047 D BluetoothManagerService: Ble is always on enable gatt
,08-30 11:37:10.224  1017  1047 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-30 11:37:10.224  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-30 11:37:10.224  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-30 11:37:10.224  7020  7020 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-30 11:37:10.224  1017  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 11:37:10.234  1017  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 11:37:10.234  1017  1047 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-30 11:37:10.234  7020  7042 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-30 11:37:10.234  7020  7042 D BluetoothAdapterProperties: Setting state to 11
08-30 11:37:10.234  7020  7042 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-30 11:37:10.234  7020  7042 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-30 11:37:10.234  7020  7042 D BluetoothAdapterService: updateAdapterState state is 11
,08-30 11:37:10.244  7020  7042 D BluetoothAdapterService: Autoconnection is available 
08-30 11:37:10.244  7020  7042 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-30 11:37:10.244  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-30 11:37:10.244  1017  1017 I InputMethodManagerService: [BT Setting State] State =11
,08-30 11:37:10.254  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-30 11:37:10.254  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 11:37:10.254  1177  1177 D BluetoothTile:  getBluetoothState : 11
,08-30 11:37:10.254  1770  1770 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 11:37:10.264  1177  1717 D BluetoothTile:  handleUpdatestate:false name:null
08-30 11:37:10.264  1177  1717 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-30 11:37:10.264  1017  1029 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 11:37:10.264  7020  7042 D BluetoothSecureManager: getInstant: null
08-30 11:37:10.264  1319  1319 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 11:37:10.264  7020  7042 D BluetoothSecureManager: calling getMethod for getService
08-30 11:37:10.264  7020  7042 D BluetoothSecureManager: calling getService
,08-30 11:37:10.264  7020  7042 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@311740d8
,08-30 11:37:10.274  1017  1030 D BluetoothSecureManagerService: isSecureModeEnabled
08-30 11:37:10.274  1017  1030 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-30 11:37:10.274  7020  7042 D BtConfig.SecureMode: isSecureModeOn:false
08-30 11:37:10.274  7020  7042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-30 11:37:10.274  7020  7042 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-30 11:37:10.274  7020  7042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-30 11:37:10.274  1017  1350 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-30 11:37:10.274  7020  7042 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-30 11:37:10.274  7020  7042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-30 11:37:10.274  7020  7042 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-30 11:37:10.274  7020  7042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 11:37:10.274  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-30 11:37:10.274  7020  7042 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
,08-30 11:37:10.274  7020  7042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-30 11:37:10.274  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:37:10.274  7020  7042 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-30 11:37:10.274  7020  7042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-30 11:37:10.274  1017  1477 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 11:37:10.274  7020  7042 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-30 11:37:10.274  1017  1477 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-30 11:37:10.274  7020  7042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-30 11:37:10.284  1017  1477 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:10.284  7020  7042 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-30 11:37:10.284  7020  7042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-30 11:37:10.284  1017  1047 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-30 11:37:10.284  1017  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:37:10.284  1017  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:37:10.284  7020  7042 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
,08-30 11:37:10.284  7020  7042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-30 11:37:10.284  7020  7042 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
,08-30 11:37:10.284  7020  7042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-30 11:37:10.284  7020  7042 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
,08-30 11:37:10.284  7020  7042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-30 11:37:10.284  7020  7042 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-30 11:37:10.284  7020  7042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-30 11:37:10.284  7020  7042 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-30 11:37:10.294  7020  7042 D BluetoothBondStateMachine: make
,08-30 11:37:10.294  7020  7042 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-30 11:37:10.294  7020  7042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-30 11:37:10.294  7020  7042 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-30 11:37:10.294  1319  1319 D BluetoothNotiBroadcastReceiver: onReceive
08-30 11:37:10.294  1017  3440 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 11:37:10.294  1017  3440 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-30 11:37:10.294  1017  3440 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:10.294  1017  3440 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:10.294  1017  3440 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:10.294  7020  7042 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-30 11:37:10.294  7020  7042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-30 11:37:10.294  7020  7042 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-30 11:37:10.304  7020  7046 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 11:37:10.304  7020  7020 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 11:37:10.304  7020  7020 D BtGatt.GattService: Received start request. Starting profile...
08-30 11:37:10.304  7020  7020 D BtGatt.GattService: start()
08-30 11:37:10.304  7020  7020 D BtGatt.GattService: start()
08-30 11:37:10.304  7020  7020 I bluedroid: get_profile_interface gatt
,08-30 11:37:10.304  7020  7020 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d50cf2
08-30 11:37:10.304  7020  7020 D BtGatt.AdvertiseManager: advertise manager created
,08-30 11:37:10.304  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 11:37:10.304  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-30 11:37:10.314  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 11:37:10.314  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-30 11:37:10.314  1017  1030 W ActivityManager: userId = 0, bbcId = -10000,
,08-30 11:37:10.314  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:10.314  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:10.324  7020  7042 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-30 11:37:10.324  7020  7042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-30 11:37:10.324  7020  7042 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-30 11:37:10.324  1017  1497 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 11:37:10.324  1017  1497 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 11:37:10.334  7020  7020 D BtGatt.GattService: mStartError = false
,08-30 11:37:10.334  7020  7020 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d50cf2
08-30 11:37:10.334  1017  1497 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:37:10.334  1017  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:10.334  1017  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:10.334  7020  7020 D HeadsetService: Received start request. Starting profile...
,08-30 11:37:10.334  7020  7042 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-30 11:37:10.334  7020  7020 D HeadsetService: start()
,08-30 11:37:10.334  7020  7042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 11:37:10.334  7020  7042 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-30 11:37:10.334  1017  1477 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 11:37:10.334  1017  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-30 11:37:10.334  1017  1477 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:10.334  1017  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:10.334  1017  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:10.344  7020  7020 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-30 11:37:10.344  7020  7020 D HeadsetStateMachine: make
08-30 11:37:10.344  7020  7042 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-30 11:37:10.344  7020  7042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-30 11:37:10.344  7020  7042 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-30 11:37:10.344  1017  3440 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 11:37:10.344  1017  3440 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-30 11:37:10.344  1017  3440 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:10.344  1017  3440 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:10.344  1017  3440 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:10.354  7020  7042 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-30 11:37:10.354  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 11:37:10.354  7020  7042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-30 11:37:10.354  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-30 11:37:10.354  7020  7042 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-30 11:37:10.354  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:10.354  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:10.354  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:10.354  7020  7020 E HeadsetStateMachine: # of Max HF connection is 2
08-30 11:37:10.354  7020  7042 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-30 11:37:10.354  7020  7042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-30 11:37:10.354  7020  7042 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-30 11:37:10.354  1017  1497 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 11:37:10.354  1017  1497 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-30 11:37:10.354  1017  1497 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:10.354  1017  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:10.354  1017  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:10.364  7020  7042 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-30 11:37:10.364  7020  7042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-30 11:37:10.364  7020  7042 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-30 11:37:10.364  1017  1350 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:10.364  1017  1350 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-30 11:37:10.364  1017  1350 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:10.364  1017  1350 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
08-30 11:37:10.364  1017  1350 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-30 11:37:10.364  1017  3289 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 11:37:10.364  1017  3289 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-30 11:37:10.364  1017  3289 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:10.364  1017  3289 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:10.364  1017  3289 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 11:37:10.364  1017  1217 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-30 11:37:10.364  1017  1217 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-30 11:37:10.374  7020  7042 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-30 11:37:10.374  7020  7042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-30 11:37:10.374  7020  7042 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-30 11:37:10.374  7020  7042 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-30 11:37:10.374  7020  7042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-30 11:37:10.374  7020  7042 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-30 11:37:10.374  7020  7042 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-30 11:37:10.374  7020  7042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-30 11:37:10.374  1017  1217 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:10.374  1017  1217 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:10.374  7020  7042 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-30 11:37:10.374  1017  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-30 11:37:10.374  7020  7042 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-30 11:37:10.374  7020  7042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-30 11:37:10.374  7020  7042 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-30 11:37:10.374  7020  7042 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-30 11:37:10.374  7020  7020 I bluedroid: get_profile_interface handsfree
,08-30 11:37:10.384  7020  7020 I DualScoManager: Instantiating Dual Sco Manager
,08-30 11:37:10.384  7020  7020 I DualScoManager: Set HeadsetServiceHelper
,08-30 11:37:10.384  7020  7020 D BluetoothAtMessage: createCMTIContentObservers
,08-30 11:37:10.384  1017  1497 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-30 11:37:10.384  1017  1497 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 11:37:10.384  1017  1497 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 11:37:10.384  1017  1497 D SettingsProvider: selectionArgs: false
08-30 11:37:10.384  1017  1497 D SettingsProvider: selectionArgs: 1002
08-30 11:37:10.384  1017  1497 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 11:37:10.384  1017  1497 D SettingsProvider: ret = -1
,08-30 11:37:10.394  7020  7050 D HeadsetStateMachine: Enter Disconnected: -2
,08-30 11:37:10.394  7020  7020 D HeadsetService: mStartError = false
08-30 11:37:10.394  7020  7020 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d50cf2
08-30 11:37:10.394  7020  7020 E BluetoothAdapterService(869600498): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-30 11:37:10.394  7020  7050 D HeadsetStateMachine: Clear mHeadsetBrsf
08-30 11:37:10.394  7020  7050 D HeadsetStateMachine: map size, before remove : 0
08-30 11:37:10.394  7020  7050 D HeadsetStateMachine: map size, after remove: 0
,08-30 11:37:10.394  7020  7020 D A2dpService: Received start request. Starting profile...
08-30 11:37:10.394  7020  7020 D A2dpService: start()
,08-30 11:37:10.394  7020  7020 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-30 11:37:10.394  7020  7020 I bluedroid: get_profile_interface avrcp
,08-30 11:37:10.404  7020  7020 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-30 11:37:10.414  7020  7020 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-30 11:37:10.414  7020  7055 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-30 11:37:10.424  7020  7020 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 11:37:10.424  7020  7020 D A2dpStateMachine: make
,08-30 11:37:10.424  7020  7020 I bluedroid: get_profile_interface a2dp
,08-30 11:37:10.424  7020  7057 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-30 11:37:10.424  7020  7020 E bt-btif : warning : media task started media_task_refcnt 1 
,08-30 11:37:10.424  7020  7020 D A2dpService: mStartError = false
08-30 11:37:10.424  7020  7020 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d50cf2
,08-30 11:37:10.434  7020  7056 D A2dpStateMachine: Enter Disconnected: -2
,08-30 11:37:10.434  7020  7020 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 11:37:10.434  7020  7020 D HidService: Received start request. Starting profile...
08-30 11:37:10.434  7020  7020 D HidService: start()
08-30 11:37:10.434  7020  7020 I bluedroid: get_profile_interface hidhost
08-30 11:37:10.434  7020  7020 D HidService: setHidService(): set to: null
08-30 11:37:10.434  7020  7020 D HidService: mStartError = false
08-30 11:37:10.434  7020  7020 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d50cf2
,08-30 11:37:10.434  7020  7020 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-30 11:37:10.434  7020  7020 D HealthService: Received start request. Starting profile...
08-30 11:37:10.434  7020  7020 D HealthService: start()
,08-30 11:37:10.434  7020  7020 I bluedroid: get_profile_interface health
,08-30 11:37:10.444  7020  7020 D HealthService: mStartError = false
08-30 11:37:10.444  7020  7020 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d50cf2
,08-30 11:37:10.444  7020  7020 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-30 11:37:10.444  7020  7055 D BluetoothMediaBrowser: no now playing list
08-30 11:37:10.444  7020  7055 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-30 11:37:10.444  7020  7020 D PanService: Received start request. Starting profile...
08-30 11:37:10.444  7020  7020 D PanService: start()
08-30 11:37:10.444  7020  7020 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 11:37:10.444  7020  7020 I bluedroid: get_profile_interface pan
,08-30 11:37:10.444  7020  7020 D PanService: mStartError = false
08-30 11:37:10.444  7020  7020 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d50cf2
,08-30 11:37:10.444  7020  7020 D BluetoothMapService: Received start request. Starting profile...
08-30 11:37:10.444  7020  7020 D BluetoothMapService: start()
,08-30 11:37:10.444  1929  1929 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-30 11:37:10.454  7020  7020 D BluetoothMapService: mStartError = false
08-30 11:37:10.454  7020  7020 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d50cf2
,08-30 11:37:10.454  7020  7020 D HeadsetStateMachine: Try to query the phonestate on bind
,08-30 11:37:10.454  1429  2779 I Telecom : BluetoothPhoneService: queryPhoneState
,08-30 11:37:10.454  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-30 11:37:10.454  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-30 11:37:10.454  1429  2779 I Telecom : BluetoothPhoneService: Result of Message : true
,08-30 11:37:10.454  7020  7020 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-30 11:37:10.454  7020  7020 D HeadsetStateMachine: Proxy object connected
,08-30 11:37:10.454  7020  7020 D SapService: Received start request. Starting profile...
08-30 11:37:10.454  7020  7020 D SapService: start()
08-30 11:37:10.454  7020  7020 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-30 11:37:10.454  7020  7020 I bluedroid: get_profile_interface sap
08-30 11:37:10.454  7020  7020 D SapService: mStartError = false
08-30 11:37:10.454  7020  7020 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d50cf2
08-30 11:37:10.454  7020  7020 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-30 11:37:10.464  7020  7020 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-30 11:37:10.464  7020  7050 D HeadsetStateMachine: Disconnected process message: 11
,08-30 11:37:10.464  7020  7020 D HeadsetPhoneState: Signal level : previous=0 curr=0
,08-30 11:37:10.464  7020  7020 E BluetoothAdapterService(869600498): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-30 11:37:10.464  7020  7050 D HeadsetStateMachine: Disconnected process message: 18
,08-30 11:37:10.464  7020  7020 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-30 11:37:10.464  7020  7020 D BluetoothA2dp: Proxy object connected
08-30 11:37:10.464  7020  7020 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-30 11:37:10.464  7020  7020 E BluetoothAdapterService(869600498): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-30 11:37:10.464  7020  7050 D HeadsetStateMachine: Disconnected process message: 10
08-30 11:37:10.464  7020  7050 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
08-30 11:37:10.464  7020  7020 E BluetoothAdapterService(869600498): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-30 11:37:10.464  7020  7020 E BluetoothAdapterService(869600498): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,08-30 11:37:10.464  7020  7050 D HeadsetStateMachine: Disconnected process message: 11
,08-30 11:37:10.464  7020  7020 E BluetoothAdapterService(869600498): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
08-30 11:37:10.464  1929  1929 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-30 11:37:10.494  7020  7020 E BluetoothAdapterService(869600498): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
08-30 11:37:10.494  7020  7020 E BluetoothAdapterService(869600498): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-30 11:37:10.494  7020  7042 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-30 11:37:10.494  7020  7042 I bluedroid: enable
,08-30 11:37:10.494  7020  7042 I bt_hci_bdroid: init
08-30 11:37:10.494  7020  7061 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-30 11:37:10.494  7020  7042 I bt_vendor: bt-vendor : init
,08-30 11:37:10.494  7020  7042 I bt_vendor: bt-vendor : get_bt_soc_type
08-30 11:37:10.494  7020  7042 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-30 11:37:10.494  7020  7042 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
08-30 11:37:10.494  7020  7042 D bt_userial_mct: userial_init
,08-30 11:37:10.504  7020  7042 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-30 11:37:10.504  7020  7042 I bt_vendor: Starting hciattach daemon
08-30 11:37:10.504  7020  7042 I bt_vendor: try to set false
,08-30 11:37:10.504  7020  7042 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-30 11:37:10.504  7020  7042 I bt_vendor: Starting hciattach daemon
08-30 11:37:10.504  7020  7042 I bt_vendor: try to set true
,08-30 11:37:10.514  7065  7065 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-30 11:37:10.564  7071  7071 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-30 11:37:10.564  7072  7072 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-30 11:37:10.584  7074  7074 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-30 11:37:10.594  7075  7075 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-30 11:37:10.604  7076  7076 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-30 11:37:10.614  7077  7077 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-30 11:37:10.834  7080  7080 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,08-30 11:37:10.844  7081  7081 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-30 11:37:10.904  7020  7042 I bt_vendor: bluetooth satus is on,
08-30 11:37:10.904  7020  7063 D bt_userial_mct: userial_open(port:0)
08-30 11:37:10.904  7020  7063 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-30 11:37:10.904  7020  7063 I bt_vendor: Done intiailizing UART,
,08-30 11:37:10.914  7020  7063 I bt_vendor: Done intiailizing UART
,08-30 11:37:10.914  7020  7063 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-30 11:37:10.914  7020  7063 I bt_vendor: Bluetooth Firmware and transport layer are initialized,
,08-30 11:37:10.914  7020  7083 D bt_userial_mct: Entering userial_read_thread()
,08-30 11:37:10.914  7020  7061 I         : BTE_InitTraceLevels -- TRC_HCI
08-30 11:37:10.914  7020  7061 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 11:37:10.914  7020  7061 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-30 11:37:10.914  7020  7061 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 11:37:10.914  7020  7061 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 11:37:10.914  7020  7061 I         : BTE_InitTraceLevels -- TRC_A2D
,08-30 11:37:10.924  7020  7061 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 11:37:10.924  7020  7061 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 11:37:10.924  7020  7061 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 11:37:10.924  7020  7061 I         : BTE_InitTraceLevels -- TRC_PAN
,08-30 11:37:10.924  7020  7061 I         : BTE_InitTraceLevels -- TRC_SAP
08-30 11:37:10.924  7020  7061 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 11:37:10.924  7020  7061 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 11:37:10.924  7020  7061 I         : BTE_InitTraceLevels -- TRC_SMP
,08-30 11:37:10.924  7020  7061 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 11:37:10.924  7020  7061 I         : BTE_InitTraceLevels -- TRC_BTIF
08-30 11:37:10.924  7020  7061 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-30 11:37:11.024  7020  7061 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-30 11:37:11.024  7020  7061 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa3f7d6e9 
,08-30 11:37:11.024  7020  7061 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3f7d6e9 
,08-30 11:37:11.044  7020  7045 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-30 11:37:11.044  7020  7045 E bt-btif : Calling BTA_HhEnable
,08-30 11:37:11.044  7020  7045 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-30 11:37:11.044  7020  7045 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,08-30 11:37:11.044  7020  7045 E BluetoothServiceJni: populateRssiValuesNative
08-30 11:37:11.044  7020  7045 I bluedroid: getModelRssiValues
08-30 11:37:11.044  7020  7045 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-30 11:37:11.054  7020  7045 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-30 11:37:11.054  1017  1017 D SettingsProvider: name = bluetooth_name
,08-30 11:37:11.054  7020  7045 D BluetoothAdapterProperties: Name is: A5-1
,08-30 11:37:11.054  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:37:11.064  7020  7045 D BluetoothUtils: getBtEnabledContainers(): btContainers = [],
08-30 11:37:11.064  7020  7045 D BluetoothAdapterProperties: Scan Mode:20
08-30 11:37:11.064  7020  7045 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 11:37:11.064  7020  7045 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
08-30 11:37:11.064  7020  7045 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-30 11:37:11.064  7020  7045 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-30 11:37:11.064  7020  7045 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,08-30 11:37:11.064  7020  7045 E bt-btif : btif_sock_init: !vhci_init
08-30 11:37:11.064  7020  7045 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
08-30 11:37:11.064  7020  7045 D IOP_DB_BT: db_open: db_open : handle 3026124816l, read 13894 bytes onto local cache
,08-30 11:37:11.064  7020  7045 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
08-30 11:37:11.064  7020  7045 D IOP_DB_BT: db_query: result 1,
08-30 11:37:11.064  7020  7045 I         : iop_db_open: iop_db_open status 0
08-30 11:37:11.064  7020  7045 D bte_conf: Device ID record 1 : primary
08-30 11:37:11.064  7020  7045 D bte_conf:   vendorId            = 0075
08-30 11:37:11.064  7020  7045 D bte_conf:   vendorIdSource      = 0001
08-30 11:37:11.064  7020  7045 D bte_conf:   product             = 0100
08-30 11:37:11.064  7020  7045 D bte_conf:   version             = 0200
08-30 11:37:11.064  7020  7045 D bte_conf:   clientExecutableURL = 
08-30 11:37:11.064  7020  7045 D bte_conf:   serviceDescription  = 
08-30 11:37:11.064  7020  7045 D bte_conf:   documentationURL    = 
08-30 11:37:11.064  7020  7045 D bte_conf: bte_load_did_conf no section named DID2.
08-30 11:37:11.064  7020  7045 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-30 11:37:11.064  7020  7042 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-30 11:37:11.064  7020  7042 D BluetoothAdapterProperties: ScanMode =  20
08-30 11:37:11.064  7020  7042 D BluetoothAdapterProperties: State =  11
08-30 11:37:11.064  1017  3091 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-30 11:37:11.064  7020  7042 D BluetoothAdapterProperties: Setting state to 12
08-30 11:37:11.064  7020  7042 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-30 11:37:11.064  7020  7083 E bt_mct  : hci lib postload completed,
,08-30 11:37:11.074  7020  7045 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-30 11:37:11.074  7020  7045 D BluetoothAdapterProperties: Scan Mode:21
,08-30 11:37:11.074  7020  7045 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 11:37:11.074  1017  1560 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-30 11:37:11.074  1017  1560 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 11:37:11.074  1017  1560 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 11:37:11.074  1017  1560 D SettingsProvider: selectionArgs: false
08-30 11:37:11.074  1017  1560 D SettingsProvider: selectionArgs: 1002
08-30 11:37:11.074  1017  1560 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 11:37:11.074  1017  1560 D SettingsProvider: ret = -1
08-30 11:37:11.074  7020  7042 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-30 11:37:11.074  7020  7042 D BluetoothAdapterService: updateAdapterState state is 12
,08-30 11:37:11.074  1017  1350 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 11:37:11.074  1017  1350 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-30 11:37:11.074  1017  1350 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:37:11.074  1017  1350 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:11.074  1017  1350 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:11.084  7020  7042 D BluetoothAdapterService: Autoconnection is available 
08-30 11:37:11.084  7020  7042 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-30 11:37:11.084  7020  7042 D BluetoothAdapterService: starting service from this receiver
,08-30 11:37:11.084  1017  1497 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 11:37:11.084  1017  1497 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-30 11:37:11.084  1017  1497 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:11.084  1017  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:11.084  1017  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:11.094  2892  2901 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 11:37:11.094  7020  7042 I BluetoothAdapterState: Entering On State from state = 11
,08-30 11:37:11.094  1017  1047 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-30 11:37:11.094  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 11:37:11.094  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:37:11.094  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:11.094  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:11.094  2892  2901 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 11:37:11.104  6312  6320 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 11:37:11.104  6312  6320 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 11:37:11.104  6470  6478 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 11:37:11.104  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:37:11.104  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:11.104  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:37:11.104  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 11:37:11.104  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:37:11.104  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:37:11.104  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:37:11.104  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 11:37:11.104  6470  6478 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 11:37:11.104  6312  6312 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 11:37:11.104  1319  1339 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 11:37:11.114  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-30 11:37:11.114  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 11:37:11.114  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:37:11.114  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:11.114  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:11.114  1319  1339 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 11:37:11.114  2892  2900 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 11:37:11.114  2892  2900 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-30 11:37:11.124  7020  7020 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
08-30 11:37:11.124  1017  1047 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-30 11:37:11.124  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 11:37:11.124  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:37:11.124  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:11.124  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:11.124  1177  2709 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 11:37:11.124  1177  2709 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 11:37:11.124  1017  1047 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 11:37:11.124  1017  1047 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 11:37:11.124  2892  2892 D BluetoothA2dp: Proxy object connected
,08-30 11:37:11.124  1429  2778 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 11:37:11.134  1017  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-30 11:37:11.134  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 11:37:11.134  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:37:11.134  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 11:37:11.134  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:11.134  1429  2778 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 11:37:11.134  7020  7020 I BluetoothPbapService: Handler(): got msg=1
,08-30 11:37:11.144  1017  1217 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-30 11:37:11.144  1453  1789 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 11:37:11.144  1453  1789 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 11:37:11.144  1319  1319 D HeadsetProfile: Bluetooth service connected
,08-30 11:37:11.144  1319  6975 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 11:37:11.144  7020  7087 V BluetoothPbapService: PBAP Service initSocket try: 0
08-30 11:37:11.144  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-30 11:37:11.144  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-30 11:37:11.144  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:11.144  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:11.144  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:11.144  1319  6974 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-30 11:37:11.154  1319  1319 D BluetoothPbap: Proxy object connected
08-30 11:37:11.154  1319  1319 D PbapServerProfile: Bluetooth service connected
,08-30 11:37:11.154  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-30 11:37:11.154  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-30 11:37:11.154  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:37:11.154  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:11.154  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:11.154  7020  7087 D BluetoothSocket: bindListen(): myUserId = 0
,08-30 11:37:11.154  7020  7087 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 11:37:11.154  2892  6971 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 11:37:11.154  2892  6971 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 11:37:11.154  1319  1332 D BluetoothPan: Binding service...
,08-30 11:37:11.164  1319  1319 D BluetoothInputDevice: Proxy object connected
,08-30 11:37:11.164  1319  1319 D HidProfile: Bluetooth service connected
08-30 11:37:11.164  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-30 11:37:11.164  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-30 11:37:11.164  7020  7087 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
08-30 11:37:11.164  7020  7087 D BluetoothSocket: bindListen(), new LocalSocket 
08-30 11:37:11.164  7020  7087 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-30 11:37:11.164  7020  7087 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@30267d6f
08-30 11:37:11.164  7020  7087 D BluetoothSocket: channel: 19
08-30 11:37:11.164  7020  7087 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-30 11:37:11.164  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:37:11.164  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:11.164  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:11.164  7020  7029 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 11:37:11.164  7020  7029 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 11:37:11.164  1929  1942 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 11:37:11.164  1929  1942 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 11:37:11.174  1453  1468 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 11:37:11.174  1017  1047 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset,
08-30 11:37:11.174  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-30 11:37:11.174  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:11.174  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:11.174  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:11.174  1453  1468 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 11:37:11.174  1319  1319 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 11:37:11.174  1319  1319 D PanProfile: Bluetooth service connected
,08-30 11:37:11.174  6312  6364 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:37:11.174  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:11.174  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:37:11.174  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 11:37:11.174  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:37:11.174  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:37:11.174  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:37:11.174  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 11:37:11.174  1429  2777 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 11:37:11.184  1017  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 11:37:11.184  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 11:37:11.184  6312  6364 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 11:37:11.184  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 11:37:11.184  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cd9d50 added. We now have 8 listener(s)
08-30 11:37:11.184  6312  6364 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 11:37:11.184  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:11.184  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:11.184  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:11.184  1429  2777 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 11:37:11.184  1429  2778 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 11:37:11.184  1017  1217 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-30 11:37:11.184  1017  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 11:37:11.184  1017  1217 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-30 11:37:11.184  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-30 11:37:11.184  1017  1217 D SecContentProvider2: mCursor = null
08-30 11:37:11.194  1017  1217 D WifiService: setWifiEnabled: false pid=6312, uid=10155
08-30 11:37:11.184  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:11.184  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:11.184  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-30 11:37:11.194  1429  2778 E BluetoothHeadset: BluetoothHeadset service is binded
08-30 11:37:11.194  1017  1217 D SettingsProvider: name = wifi_on
08-30 11:37:11.194  1429  1440 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 11:37:11.194  1429  1440 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 11:37:11.194  1319  1332 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 11:37:11.194  1319  1332 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 11:37:11.194  1017  1047 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 11:37:11.194  1017  1047 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-30 11:37:11.194  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-30 11:37:11.194  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 11:37:11.194  7020  7088 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 11:37:11.194  1017  1017 D BluetoothA2dp: Proxy object connected
,08-30 11:37:11.194  1441  1462 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 11:37:11.194  1441  1462 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 11:37:11.194  1017  1047 D BluetoothPan: Binding service...
08-30 11:37:11.194  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-30 11:37:11.194  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-30 11:37:11.194  1017  1017 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 11:37:11.194  1017  1047 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-30 11:37:11.194  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 11:37:11.194  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-30 11:37:11.194  1017  1047 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 11:37:11.194  1319  1339 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 11:37:11.194  1319  1339 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-30 11:37:11.204  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-30 11:37:11.204  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 11:37:11.204  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:11.204  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:11.204  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:11.204  1319  1319 D BluetoothA2dp: Proxy object connected
08-30 11:37:11.204  1319  1319 D A2dpProfile: Bluetooth service connected
,08-30 11:37:11.204  1319  6974 D BluetoothMap: onBluetoothStateChange: up=true
,08-30 11:37:11.204  6312  6364 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:37:11.204  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-30 11:37:11.204  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-30 11:37:11.204  1017  3091 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-30 11:37:11.204  1017  3091 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-30 11:37:11.204  1017  3091 D SecContentProvider2: mCursor = null
,08-30 11:37:11.204  1017  3091 D WifiService: setWifiEnabled: true pid=6312, uid=10155
08-30 11:37:11.204  1017  3091 W ActivityManager: Permission Denial: getCurrentUser() from pid=6312, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,08-30 11:37:11.204  1017  3091 W WifiService: Failed getting userId using ActivityManagerNative
08-30 11:37:11.204  1017  3091 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6312, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-30 11:37:11.204  1017  3091 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916),
08-30 11:37:11.204  1017  3091 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-30 11:37:11.204  1017  3091 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-30 11:37:11.204  1017  3091 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-30 11:37:11.204  1017  3091 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-30 11:37:11.204  1017  3091 D SettingsProvider: name = wifi_on
08-30 11:37:11.204  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:11.204  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 11:37:11.204  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-30 11:37:11.214  1319  1332 D Bluetoothsap: onBluetoothStateChange: up=true
08-30 11:37:11.214  1319  1332 D Bluetoothsap: Binding service...,
,08-30 11:37:11.214  1319  1332 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 ,
08-30 11:37:11.214  1319  1319 D BluetoothMap: Proxy object connected
,08-30 11:37:11.214  1319  1319 D MapProfile: Bluetooth service connected
08-30 11:37:11.214  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-30 11:37:11.214  1319  1319 D BluetoothMap: getConnectedDevices()
08-30 11:37:11.214  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-30 11:37:11.214  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:11.214  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:11.214  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:11.214  1319  1332 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-30 11:37:11.214  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-30 11:37:11.214  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
08-30 11:37:11.214  1319  1319 D Bluetoothsap: BluetoothSAP Proxy object connected
08-30 11:37:11.214  1319  1319 D SapProfile: Bluetooth service connected
08-30 11:37:11.214  1319  1319 D Bluetoothsap: getConnectedDevices()
,08-30 11:37:11.224  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-30 11:37:11.224  1017  1017 I InputMethodManagerService: [BT Setting State] State =12
08-30 11:37:11.224  1017  1017 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
08-30 11:37:11.224  1017  1128 E WifiHW  : ##################### set firmware type 0 #####################
,08-30 11:37:11.224  1429  1429 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@b947b9b, true
,08-30 11:37:11.224  1429  1429 D BluetoothHeadset: registerMessageListener
,08-30 11:37:11.234  1177  1177 D BluetoothTile:  onBluetoothStateChange:
08-30 11:37:11.234  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-30 11:37:11.234  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:37:11.234  1177  1177 D BluetoothTile:  getBluetoothState : 12
,08-30 11:37:11.234  1177  1717 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 11:37:11.244  1177  1717 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 11:37:11.244  1770  1770 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 11:37:11.244  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:37:11.244  1177  1717 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 11:37:11.244  1319  1319 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 11:37:11.244  7020  7029 D HeadsetService: registerMessageListener
,08-30 11:37:11.244  1017  3440 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 11:37:11.244  1017  3440 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-30 11:37:11.254  7020  7029 D HeadsetService: registerMessageListener
,08-30 11:37:11.254  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-30 11:37:11.254  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-30 11:37:11.254  7020  7050 D HeadsetStateMachine: Disconnected process message: 70
08-30 11:37:11.254  7020  7050 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@2d756a7c
,08-30 11:37:11.254  1017  3440 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:11.254  1017  3440 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 11:37:11.254  1017  3440 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:37:11.254  1017  1350 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 11:37:11.254  1017  1478 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-30 11:37:11.254  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 11:37:11.254  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,08-30 11:37:11.254  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-30 11:37:11.254  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-30 11:37:11.264  7020  7092 D BluetoothMapMasInstance: set MAP SDP message type : 1
08-30 11:37:11.264  1319  1319 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-30 11:37:11.264  1319  1319 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-30 11:37:11.264  1319  1319 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-30 11:37:11.264  1319  1319 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-30 11:37:11.264  7020  7050 D HeadsetStateMachine: Disconnected process message: 9
,08-30 11:37:11.264  7020  7050 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-30 11:37:11.264  7020  7092 D BluetoothSocket: bindListen(): myUserId = 0
,08-30 11:37:11.264  7020  7092 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 11:37:11.274  1319  1319 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 11:37:11.274  1017  3091 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-30 11:37:11.274  1017  3091 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-30 11:37:11.274  7020  7092 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
,08-30 11:37:11.274  7020  7092 D BluetoothSocket: bindListen(), new LocalSocket 
08-30 11:37:11.274  7020  7092 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-30 11:37:11.274  7020  7092 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@39584f05
08-30 11:37:11.274  7020  7092 D BluetoothSocket: channel: 5
,08-30 11:37:11.274  1017  3091 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:11.274  1017  3091 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:11.274  1017  3091 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-30 11:37:11.284   285   684 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-30 11:37:11.284   285   684 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-30 11:37:11.284   285   684 V voice   : voice_set_parameters: exit with code(-2)
08-30 11:37:11.284   285   684 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-30 11:37:11.284   285   684 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-30 11:37:11.284   285   684 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-30 11:37:11.284   285   684 V audio_hw_primary: adev_set_parameters: exit
08-30 11:37:11.284  7020  7050 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-30 11:37:11.294  1319  1319 D DockEventReceiver: finishStartingService: stopping service
,08-30 11:37:11.294  1319  1319 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 11:37:11.294  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:37:11.294  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-30 11:37:11.304   290   290 E SMD     : DCD OFF
,08-30 11:37:11.304  7020  7020 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d50cf2
08-30 11:37:11.304  7020  7020 D BtConfig.SecureMode: isSecureModeOn:false
,08-30 11:37:11.314  1017  1350 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 11:37:11.314  1017  1350 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-30 11:37:11.314  1017  1350 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:11.314  1017  1350 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:11.314  1017  1350 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 11:37:11.334  1929  1929 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-30 11:37:11.334  1017  3289 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 11:37:11.334  1017  3289 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
08-30 11:37:11.334  1017  3289 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:11.334  1017  3289 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:37:11.334  1017  3289 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:37:11.334  1017  1217 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-30 11:37:11.344  1929  7101 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-30 11:37:11.344  1929  1929 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-30 11:37:11.354  1017  3289 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 11:37:11.354  1017  3289 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:37:11.354  1017  3289 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:37:11.354  1017  3289 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:37:11.364  7020  7102 D BluetoothSocket: bindListen(): myUserId = 0
,08-30 11:37:11.364  7020  7102 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 11:37:11.364  7020  7102 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-30 11:37:11.364  7020  7102 D BluetoothSocket: bindListen(), new LocalSocket 
08-30 11:37:11.364  7020  7102 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-30 11:37:11.364  7020  7102 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3493d681
,08-30 11:37:11.364  7020  7102 D BluetoothSocket: channel: 12
08-30 11:37:11.364  7020  7102 I BtOppRfcommListener: Accept thread started.
,08-30 11:37:11.364  1017  3440 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 11:37:11.374  1017  3440 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:37:11.374  1017  3440 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 11:37:11.374  1017  3440 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 11:37:11.384  1929  7101 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-30 11:37:11.584  1017  1045 D Tethering: interfaceAdded wlan0
,08-30 11:37:11.584  1017  1131 E Tethering: No numeric data
,08-30 11:37:11.594  1017  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-30 11:37:11.594  1017  1125 V NetworkStats: performPollLocked(flags=0x1)
08-30 11:37:11.594  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 11:37:11.594  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-30 11:37:11.594  1177  1177 D HotspotTile: updateTetherState():false, false
08-30 11:37:11.594  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 11:37:11.594  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-30 11:37:11.594  1017  1131 D Tethering: clearTetheredNotification(),
,08-30 11:37:11.604  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 11:37:11.604  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 11:37:11.604  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-30 11:37:11.604  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 11:37:11.604  1017  1125 V NetworkStats: performPollLocked() took 11ms
08-30 11:37:11.604  1017  1131 D Tethering: InitialState.processMessage what=4
,08-30 11:37:11.604  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 11:37:11.604  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 11:37:11.614  1017  1131 E Tethering: No numeric data
08-30 11:37:11.614  1017  1045 D Tethering: interfaceAdded p2p0
08-30 11:37:11.614  1017  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 11:37:11.614  1017  1131 D Tethering: clearTetheredNotification()
,08-30 11:37:11.614  1017  1045 D Tethering: p2p0 is not a tetherable iface, ignoring,
08-30 11:37:11.614  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-30 11:37:11.614  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 11:37:11.614  1177  1177 D HotspotTile: updateTetherState():false, false
08-30 11:37:11.614  1017  1125 V NetworkStats: performPollLocked(flags=0x1),
,08-30 11:37:11.624  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-30 11:37:11.624  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
,08-30 11:37:11.624   280   989 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-30 11:37:11.624  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
08-30 11:37:11.624  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 11:37:11.624  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-30 11:37:11.624   280   989 D SoftapController: Softap fwReload - Ok
,08-30 11:37:11.624   280   989 D CommandListener: Setting iface cfg
08-30 11:37:11.624   280   989 D CommandListener: Trying to bring down wlan0
,08-30 11:37:11.624   280   989 D CommandListener: Clearing all IP addresses on wlan0
08-30 11:37:11.624  1017  1125 V NetworkStats: performPollLocked() took 9ms
08-30 11:37:11.624  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 11:37:11.624  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit,
08-30 11:37:11.624  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 11:37:11.634  1017  1128 E WifiHW  : supplicant_name : p2p_supplicant
,08-30 11:37:11.634  1017  1128 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-30 11:37:11.634  1017  1128 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,08-30 11:37:11.634  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020543/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 11:37:11.634  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-30 11:37:11.634  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 11:37:11.634  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:37:11.634  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:37:11.634  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:37:11.644  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 11:37:11.644  1177  1717 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-30 11:37:11.644  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-30 11:37:11.644  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 11:37:11.644  1177  1177 D HotspotTile: onReceive : 2, 0
,08-30 11:37:11.644  1319  1319 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
,08-30 11:37:11.654  1017  1477 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 11:37:11.654  1017  1477 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 11:37:11.654  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:37:11.654  1017  1477 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:11.654  1017  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:11.654  1017  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-30 11:37:11.654  3682  3682 I Hs20UtilService: Starting #19
,08-30 11:37:11.654  6571  6571 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-30 11:37:11.654  6571  6571 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-30 11:37:11.654  6571  6571 D SecurityLogAgent: StateMachine : Current State = 1
08-30 11:37:11.654  6571  6571 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-30 11:37:11.654  3682  3722 I Hs20UtilService: Message received 5011
,08-30 11:37:11.674  7110  7110 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-30 11:37:11.674  7110  7110 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-30 11:37:11.674  7110  7110 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-30 11:37:11.684  7110  7110 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-30 11:37:11.694   337   337 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7110,
08-30 11:37:11.694   337   337 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-30 11:37:11.694  7110  7110 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-30 11:37:11.694  7110  7110 I wpa_supplicant: ssSupport state is = 1
08-30 11:37:11.694  7110  7110 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-30 11:37:11.694  7110  7110 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-30 11:37:11.694   337   337 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7110
08-30 11:37:11.694   337   337 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106,
,08-30 11:37:11.854   337   337 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0,
,08-30 11:37:11.864  7110  7110 I SecureStorage: [INFO]: SPID(0x00000004)Processing data has been completed,
,08-30 11:37:11.924  7110  7110 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-30 11:37:11.924  7110  7110 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,08-30 11:37:11.934  7110  7110 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
08-30 11:37:11.934   337   337 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7110
,08-30 11:37:11.934   337   337 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
08-30 11:37:11.944  7110  7110 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
08-30 11:37:11.944  7110  7110 I wpa_supplicant: ssSupport state is = 1,
08-30 11:37:11.944  7110  7110 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 11:37:11.944  7110  7110 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 11:37:11.944  7110  7110 E wpa_supplicant: SIM READ ERROR
08-30 11:37:11.944  7110  7110 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-30 11:37:11.944  7110  7110 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 11:37:11.944  7110  7110 E wpa_supplicant: SIM READ ERROR
08-30 11:37:11.944  7110  7110 I wpa_supplicant: Blacklist: Clear (all) 
08-30 11:37:11.944  7110  7110 I wpa_supplicant: wpa_default_ap_write_once
08-30 11:37:11.944  7110  7110 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
08-30 11:37:11.944  7110  7110 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 11:37:11.944  7110  7110 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-30 11:37:11.944  7110  7110 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 11:37:11.944  7110  7110 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-30 11:37:11.944  7110  7110 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-30 11:37:11.944  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
08-30 11:37:11.944  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 11:37:11.944  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-30 11:37:12.014  7110  7110 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-30 11:37:12.054  1017  2734 D SSRM:n  : SIOP:: AP = 330,
,08-30 11:37:12.124  7110  7110 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-30 11:37:12.124  7110  7110 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,08-30 11:37:12.134  7110  7110 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
08-30 11:37:12.134   337   337 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7110
08-30 11:37:12.134   337   337 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
08-30 11:37:12.144  7110  7110 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
08-30 11:37:12.144  7110  7110 I wpa_supplicant: ssSupport state is = 1,
08-30 11:37:12.144  7110  7110 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-30 11:37:12.144  7110  7110 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,08-30 11:37:12.154  7110  7110 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
08-30 11:37:12.154   337   337 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7110
08-30 11:37:12.154   337   337 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
08-30 11:37:12.154  7110  7110 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
08-30 11:37:12.154  7110  7110 I wpa_supplicant: ssSupport state is = 1
08-30 11:37:12.154  7110  7110 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 11:37:12.154  7110  7110 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-30 11:37:12.154  7110  7110 E wpa_supplicant: SIM READ ERROR
08-30 11:37:12.154  7110  7110 I wpa_supplicant: wpa_default_ap_write_once
08-30 11:37:12.154  7110  7110 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-30 11:37:12.154  7110  7110 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 11:37:12.154  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 11:37:12.154  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-30 11:37:12.154  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-30 11:37:12.164  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 11:37:12.164  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-30 11:37:12.164  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-30 11:37:12.204  7110  7110 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-30 11:37:12.204  7110  7110 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-30 11:37:12.264  7110  7110 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-30 11:37:12.264  7110  7110 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-30 11:37:12.264  7110  7110 I wpa_supplicant: Skip scan - bUseNetwork false
,08-30 11:37:12.594  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-30 11:37:12.594  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 11:37:12.594  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-30 11:37:12.634  1017  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
,08-30 11:37:12.644  1017  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-30 11:37:12.644  7110  7110 I wpa_supplicant: HOTSPOT20_ENABLE called
08-30 11:37:12.644  7110  7110 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 11:37:12.644  7110  7110 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-30 11:37:12.644  7110  7110 E wpa_supplicant: SIM READ ERROR
,08-30 11:37:12.644  7110  7110 I wpa_supplicant: Blacklist: Clear (all) 
,08-30 11:37:12.654  7110  7110 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-30 11:37:12.664  7110  7110 I wpa_supplicant: Skip scan - bUseNetwork false
,08-30 11:37:12.664  1017  1128 D WifiNative-wlan0: callSECApiInt - ID [210]
,08-30 11:37:12.664  1017  1128 D WifiConfigStore: Loading config and enabling all networks 
,08-30 11:37:12.664  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020543/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 11:37:12.674  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 11:37:12.674  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:37:12.674  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:37:12.674  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:37:12.674  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:37:12.674  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 11:37:12.674  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-30 11:37:12.674  1177  1717 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-30 11:37:12.674  1319  1319 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-30 11:37:12.674  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-30 11:37:12.674  1177  1177 D HotspotTile: onReceive : 3, 0
,08-30 11:37:12.684  1017  1128 E WifiConfigStore: Not a HS20
08-30 11:37:12.684  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:37:12.684  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:12.684  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:37:12.684  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:37:12.684  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:37:12.684  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:37:12.684  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:37:12.684  6312  6312 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 11:37:12.684  1017  1128 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-30 11:37:12.684  1017  1497 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-30 11:37:12.684  1017  1128 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-30 11:37:12.694  1017  1497 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-30 11:37:12.694  1017  1497 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:12.694  1017  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:12.694  1017  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 11:37:12.694  6312  6312 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 11:37:12.694  1017  1128 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-30 11:37:12.694  7110  7110 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-30 11:37:12.694  7110  7110 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-30 11:37:12.694  7110  7110 I wpa_supplicant: reset timer : RESET_TIMER 0
08-30 11:37:12.694  7110  7110 I wpa_supplicant: P2P: Current p2p state = IDLE
08-30 11:37:12.694  7110  7110 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-30 11:37:12.694  7110  7110 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-30 11:37:12.694  7110  7110 I wpa_supplicant: First Scan Start
,08-30 11:37:12.694  7110  7110 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-30 11:37:12.694  3682  3682 I Hs20UtilService: Starting #20
,08-30 11:37:12.704  3682  3722 I Hs20UtilService: Message received 5011
,08-30 11:37:12.704  6571  6571 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-30 11:37:12.704  6571  6571 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-30 11:37:12.704  6571  6571 D SecurityLogAgent: StateMachine : Current State = 1
,08-30 11:37:12.704  1017  1128 D WifiNative-wlan0: Setting external_sim to 1
,08-30 11:37:12.704  1017  1128 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 11:37:12.704  1017  1128 I WifiNative-HAL: startHal
08-30 11:37:12.704  1017  1128 E wifi    : getStaticLongField sWifiHalHandle 0x9cb6588c
08-30 11:37:12.704  1017  1128 I WifiNative-HAL: Could not start hal
,08-30 11:37:12.704  6509  6509 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 11:37:12.704  6571  6571 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 11:37:12.714  1017  1128 E WifiNative-wlan0: do suspend true
,08-30 11:37:12.714  1017  1127 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-30 11:37:12.714   280   989 D CommandListener: Setting iface cfg
08-30 11:37:12.724   280   989 D CommandListener: Trying to bring up p2p0
,08-30 11:37:12.724  1017  1127 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-30 11:37:12.724  1017  1127 D WifiP2pService: P2pEnablingState
08-30 11:37:12.724  1017  1127 D WifiP2pService: P2pEnablingState{ what=147457 }
,08-30 11:37:12.724  1017  1127 D WifiP2pService: P2p socket connection successful
08-30 11:37:12.724  1017  1127 D WifiP2pService: P2pEnabledState
,08-30 11:37:12.724  1017  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-30 11:37:12.724  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 3
,08-30 11:37:12.724  1017  1017 D RttService: SCAN_AVAILABLE : 3
,08-30 11:37:12.724  1017  1151 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 11:37:12.724  1017  1151 I WifiNative-HAL: startHal
08-30 11:37:12.724  1017  1151 E wifi    : getStaticLongField sWifiHalHandle 0x9dd179bc
,08-30 11:37:12.724  1017  1151 I WifiNative-HAL: Could not start hal
08-30 11:37:12.724  1017  1151 E WifiScanningService: could not start HAL
,08-30 11:37:12.724  1017  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,08-30 11:37:12.724  1017  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-30 11:37:12.724  1017  1128 E WifiNative-wlan0: invaild command id : 215
,08-30 11:37:12.734  1017  1152 D RttService: DefaultState got{ when=-4ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 11:37:12.734  1017  1127 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-30 11:37:12.734  1017  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-30 11:37:12.734  1017  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-30 11:37:12.734  1017  1128 E WifiNative-wlan0: invaild command id : 215
08-30 11:37:12.734  1017  1130 E ConnectivityService: updateNetworkInfo()
,08-30 11:37:12.734  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-30 11:37:12.734  7110  7110 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-30 11:37:12.734  1017  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,08-30 11:37:12.734  1017  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 11:37:12.734  1017  1048 D WifiDisplayController: disconnect
,08-30 11:37:12.734  1017  1048 D WifiDisplayController: updateConnection
08-30 11:37:12.734  7110  7110 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-30 11:37:12.734  1017  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-30 11:37:12.734  1017  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-30 11:37:12.734  7110  7110 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN,
,08-30 11:37:12.744  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-30 11:37:12.744  1017  3440 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-30 11:37:12.744  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-30 11:37:12.744  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-30 11:37:12.744  1017  1128 D SecContentProvider2: mCursor = null
,08-30 11:37:12.744  1017  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 11:37:12.744  1017  1048 D WifiDisplayAdapter: onP2pDisconnected
08-30 11:37:12.744  1017  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-30 11:37:12.744  1017  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-30 11:37:12.744  1017  1127 D WifiNative-p2p0: p2pGetDeviceAddress
,08-30 11:37:12.744  1017  1127 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
,08-30 11:37:12.754  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 11:37:12.754  1017  1128 D SecContentProvider2: mCursor = null
08-30 11:37:12.754  1017  1127 D WifiP2pService: DeviceAddress: 7e:96:ac
08-30 11:37:12.754  1319  1319 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-30 11:37:12.754  1319  1319 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 11:37:12.754  1319  1319 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 11:37:12.754  1017  1048 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
08-30 11:37:12.754  1017  1048 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
08-30 11:37:12.754  1017  1048 D WifiDisplayController:  primary type: 10-0050F204-5
08-30 11:37:12.754  1017  1048 D WifiDisplayController:  secondary type: null
08-30 11:37:12.754  1017  1048 D WifiDisplayController:  wps: 0
08-30 11:37:12.754  1017  1048 D WifiDisplayController:  grpcapab: 0
08-30 11:37:12.754  1017  1048 D WifiDisplayController:  devcapab: 0
08-30 11:37:12.754  1017  1048 D WifiDisplayController:  status: 3
08-30 11:37:12.754  1017  1048 D WifiDisplayController:  wfdInfo: null
08-30 11:37:12.754  1017  1048 D WifiDisplayController:  groupownerAddress: null
08-30 11:37:12.754  1017  1048 D WifiDisplayController:  GOdeviceName: null
08-30 11:37:12.754  1017  1048 D WifiDisplayController:  interfaceAddress: 
08-30 11:37:12.754  1017  1048 D WifiDisplayController:  SConnectInfo : null
,08-30 11:37:12.754  1319  1319 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-30 11:37:12.754  1319  1319 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 11:37:12.754  1319  1319 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-30 11:37:12.754  1319  3112 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 11:37:12.764  6539  6539 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 11:37:12.764  6539  6539 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-30 11:37:12.764  6539  6539 D FileShare-Client: Outbound.stopDelayTimer - 
,08-30 11:37:12.774  6554  6554 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 11:37:12.774  1017  1127 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-30 11:37:12.774  1017  1127 D WifiP2pService: InactiveState
,08-30 11:37:12.774  1017  1127 D WifiP2pService: InactiveState{ what=143376 }
,08-30 11:37:12.774  1017  1127 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-30 11:37:12.774  7110  7110 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-30 11:37:12.774  1017  1127 D WifiP2pService: InactiveState{ what=143376 }
08-30 11:37:12.774  1017  1127 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-30 11:37:13.244  6312  6364 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:37:13.244  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:13.244  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:37:13.244  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:37:13.244  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:37:13.244  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:37:13.244  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:37:13.244  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 11:37:13.244  6312  6364 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 11:37:13.254  6312  6364 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-30 11:37:13.254  6312  6364 D io.jxcore.node.LifeCycleMonitor: onActivityResumed,
,08-30 11:37:13.254  6312  6364 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@372b9284 Bundle[{}],
08-30 11:37:13.254  6312  6364 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-30 11:37:13.254  6312  6364 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-30 11:37:13.254  6312  6364 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-30 11:37:13.254  6312  6364 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 11:37:13.254  6312  6364 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-30 11:37:13.264  6312  6364 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-30 11:37:13.264  6312  6364 I System.out: Running OutgoingSocketThread
,08-30 11:37:13.264  6312  7118 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1177),
,08-30 11:37:13.274  6312  7118 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 38979,
08-30 11:37:13.274  6312  7118 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-30 11:37:13.984  7110  7110 I wpa_supplicant: nl80211: Received scan results (19 BSSes),
08-30 11:37:13.984  7110  7110 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-30 11:37:13.984  7110  7110 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-30 11:37:13.984  7110  7110 I wpa_supplicant: Trying to associate with  'G700'
,08-30 11:37:13.984  7110  7110 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-30 11:37:13.984  7110  7110 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-30 11:37:13.984  1017  7116 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-30 11:37:14.004  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 11:37:14.004  1017  1128 D SecContentProvider2: mCursor = null
,08-30 11:37:14.104  7110  7110 E wpa_supplicant: Cmd 35605 not handled
,08-30 11:37:14.104  7110  7110 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,08-30 11:37:14.104  7110  7110 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-30 11:37:14.104  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 11:37:14.104  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 11:37:14.104  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-30 11:37:14.104  7110  7110 I wpa_supplicant: Associated with F4.99.3E,
,08-30 11:37:14.104  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
08-30 11:37:14.104  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-30 11:37:14.104  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
08-30 11:37:14.104  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 11:37:14.104  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,08-30 11:37:14.104  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
08-30 11:37:14.104  7110  7110 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e,
08-30 11:37:14.104  7110  7110 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-30 11:37:14.104  7110  7110 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-30 11:37:14.114  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, true
08-30 11:37:14.114  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-30 11:37:14.114  1017  1045 D Tethering: interfaceStatusChanged wlan0, true
,08-30 11:37:14.114  1017  1131 E Tethering: No numeric data
08-30 11:37:14.114  1017  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-30 11:37:14.114  1017  1131 D Tethering: clearTetheredNotification()
,08-30 11:37:14.114  1017  1125 V NetworkStats: performPollLocked(flags=0x1)
08-30 11:37:14.114  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 11:37:14.114  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-30 11:37:14.114  1177  1177 D HotspotTile: updateTetherState():false, false
08-30 11:37:14.114  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 11:37:14.114  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-30 11:37:14.124  7110  7110 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-30 11:37:14.124  7110  7110 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-30 11:37:14.124  7110  7110 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-30 11:37:14.124  7110  7110 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-30 11:37:14.124  7110  7110 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 11:37:14.124  7110  7110 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-30 11:37:14.124  7110  7110 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-30 11:37:14.124  7110  7110 I wpa_supplicant: Blacklist: Clear (temp) 
08-30 11:37:14.124  7110  7110 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-30 11:37:14.124  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, true
08-30 11:37:14.124  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-30 11:37:14.124  1017  1045 D Tethering: interfaceStatusChanged wlan0, true
08-30 11:37:14.124  1017  1125 V NetworkStats: performPollLocked() took 11ms
,08-30 11:37:14.124  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 11:37:14.134  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 11:37:14.134  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 11:37:14.134  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 11:37:14.134  1017  1128 D SecContentProvider2: mCursor = null
,08-30 11:37:14.134  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-30 11:37:14.134  1017  1128 D SecContentProvider2: mCursor = null,
,08-30 11:37:14.134  1017  1128 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-30 11:37:14.144  1017  1128 E WifiConfigStore: setLastSelectedConfiguration -1
,08-30 11:37:14.154  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020543/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 11:37:14.154  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 11:37:14.154  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:37:14.154  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:37:14.154  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 11:37:14.154  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 11:37:14.154  1017  1128 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-30 11:37:14.154  1017  1130 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-30 11:37:14.154  1017  1130 E ConnectivityService: updateNetworkInfo()
08-30 11:37:14.154  1017  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-30 11:37:14.154  1017  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 11:37:14.164  1017  3289 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
,08-30 11:37:14.164  1017  3289 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 11:37:14.164  1017  3289 W ActivityManager: userId = 0, bbcId = -10000,
,08-30 11:37:14.164  1017  3289 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-30 11:37:14.164  1017  3289 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings,
,08-30 11:37:14.174  3682  3682 I Hs20UtilService: Starting #21
,08-30 11:37:14.174  3682  3722 I Hs20UtilService: Message received 5007
,08-30 11:37:14.174  1017  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 11:37:14.174  1319  1319 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
,08-30 11:37:14.174  1319  1319 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 11:37:14.184   280   989 D CommandListener: Setting iface cfg
,08-30 11:37:14.184  1319  1319 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 11:37:14.184  1319  1319 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-30 11:37:14.184  1017  1128 E WifiStateMachine: Start Dhcp Watchdog 3
,08-30 11:37:14.194  1319  1319 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 11:37:14.194  1319  1319 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-30 11:37:14.194  1319  3112 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 11:37:14.194  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-30 11:37:14.194  1017  1128 D SecContentProvider2: mCursor = null
,08-30 11:37:14.204  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020543/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 11:37:14.204  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-30 11:37:14.204  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 11:37:14.204  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 11:37:14.204  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 11:37:14.214  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 11:37:14.214  1017  1128 E WifiNative-wlan0: do suspend false
,08-30 11:37:14.224  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 11:37:14.224  1017  1127 D WifiP2pService: InactiveState{ what=143375 }
,08-30 11:37:14.224  1017  1128 D SecContentProvider2: mCursor = null
08-30 11:37:14.224  1017  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-30 11:37:14.264  6312  6364 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1178)
,08-30 11:37:14.264  6312  6364 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1178)
,08-30 11:37:14.264  6312  6364 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1183)
,08-30 11:37:14.274  6312  6364 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...,
,08-30 11:37:14.274  6312  6364 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1184)
,08-30 11:37:14.274  6312  6364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 11:37:14.274  6312  6364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@395a8b49 added. We now have 2 listener(s),
08-30 11:37:14.274  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB",
08-30 11:37:14.274  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
08-30 11:37:14.274  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 11:37:14.274  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 11:37:14.274  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@573bc4e added. We now have 9 listener(s)
08-30 11:37:14.274  6312  6364 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 11:37:14.284  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 11:37:14.284  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 11:37:14.294  6312  6364 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 11:37:14.294  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:14.294  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:37:14.294  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:37:14.294  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:37:14.294  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:37:14.294  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:37:14.294  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 11:37:14.294  6312  6364 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 11:37:14.294  6312  6364 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 11:37:14.294  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:37:14.304  6312  6364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 11:37:14.304  6312  6364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34f73e7c added. We now have 3 listener(s)
,08-30 11:37:14.304  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:37:14.304  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-30 11:37:14.304  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 11:37:14.304  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 11:37:14.304  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 11:37:14.304  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32379305 added. We now have 10 listener(s)
,08-30 11:37:14.304  6312  6364 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 11:37:14.304   290   290 E SMD     : DCD OFF
,08-30 11:37:14.304  6312  6364 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:37:14.304  6312  6364 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:37:14.304  6312  6364 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:37:14.304  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:37:14.304  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:14.304  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 11:37:14.304  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 11:37:14.304  6312  6364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@395a8b49 removed from the list
08-30 11:37:14.304  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:37:14.304  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@573bc4e removed from the list
08-30 11:37:14.304  6312  6364 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:37:14.304  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:37:14.304  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:14.304  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:37:14.314  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:37:14.314  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:37:14.314  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:37:14.314  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@573bc4e not in the list
08-30 11:37:14.314  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 11:37:14.314  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:37:14.314  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 11:37:14.314  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 11:37:14.314  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 11:37:14.314  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32379305 removed from the list
,08-30 11:37:14.314  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 11:37:14.314  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 11:37:14.314  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:37:14.314  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 11:37:14.314  6312  6364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34f73e7c removed from the list
,08-30 11:37:14.314  6312  6364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 11:37:14.314  6312  6364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b534f5a added. We now have 2 listener(s)
,08-30 11:37:14.324  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-30 11:37:14.324  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 11:37:14.324  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 11:37:14.324  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 11:37:14.324  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e42658b added. We now have 9 listener(s)
,08-30 11:37:14.324  6312  6364 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 11:37:14.324  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 11:37:14.334  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 11:37:14.334  6312  6364 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 11:37:14.334  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:14.334  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:37:14.334  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:37:14.334  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:37:14.334  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:37:14.334  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:37:14.334  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 11:37:14.334  6312  6364 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 11:37:14.334  6312  6364 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 11:37:14.334  6312  6364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 11:37:14.334  6312  6364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16235a81 added. We now have 3 listener(s)
,08-30 11:37:14.334  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:37:14.344  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-30 11:37:14.344  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB",
08-30 11:37:14.344  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 11:37:14.344  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 11:37:14.344  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 11:37:14.344  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33670726 added. We now have 10 listener(s),
08-30 11:37:14.344  6312  6364 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 11:37:14.344  6312  6364 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 11:37:14.344  6312  6364 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 11:37:14.344  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-30 11:37:14.344  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 11:37:14.344  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 11:37:14.344  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 11:37:14.354  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 11:37:14.354  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 11:37:14.354  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 11:37:14.354  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-30 11:37:14.354  6312  6364 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 11:37:14.354  7020  7051 D BtGatt.GattService: registerClient() - UUID=ef75a6ca-a294-4a59-9d61-b9eca3743624
,08-30 11:37:14.404  7020  7045 D BtGatt.GattService: onClientRegistered() - UUID=ef75a6ca-a294-4a59-9d61-b9eca3743624, clientIf=6
,08-30 11:37:14.404  6312  6320 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-30 11:37:14.404  7020  7029 D BtGatt.GattService: start scan with filters
,08-30 11:37:14.404  7020  7049 D BtGatt.ScanManager: handling starting scan
,08-30 11:37:14.404  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 11:37:14.404  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 11:37:14.404  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 11:37:14.404  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 11:37:14.414  7020  7049 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33d50cf2
,08-30 11:37:14.414  6312  6364 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 11:37:14.414  6312  6364 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 11:37:14.414  6312  6312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 11:37:14.414  7020  7045 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-30 11:37:14.414  7020  7045 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 11:37:14.414  7020  7049 D BtGatt.ScanManager: allow scan with filters
,08-30 11:37:14.414  7020  7049 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-30 11:37:14.424  7020  7049 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-30 11:37:14.424  7020  7045 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-30 11:37:14.424  7020  7045 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 11:37:14.424  7020  7049 D BtGatt.ScanManager: Starting BLE batch scan
08-30 11:37:14.424  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 11:37:14.424  7020  7049 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-30 11:37:14.434  7020  7045 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
08-30 11:37:14.434  7020  7045 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 11:37:14.434  7020  7045 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-30 11:37:14.434  7020  7045 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 11:37:14.434  7124  7124 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-30 11:37:14.444  7124  7124 I dhcpcd  : version 5.5.6 starting
,08-30 11:37:14.444  6312  6364 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 11:37:14.444  6312  6364 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 11:37:14.444  6312  6364 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 11:37:14.444  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:14.444  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 11:37:14.444  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 11:37:14.444  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 11:37:14.444  6312  6364 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 11:37:14.444  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 11:37:14.444  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 11:37:14.444  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 11:37:14.444  7020  7029 D BtGatt.GattService: stopScan() - queue size =1
,08-30 11:37:14.444  7124  7124 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-30 11:37:14.444  7020  7028 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-30 11:37:14.444  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
08-30 11:37:14.444  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 11:37:14.444  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-30 11:37:14.444  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 11:37:14.444  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 11:37:14.454  6312  6364 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 11:37:14.454  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 11:37:14.454  6312  6364 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 11:37:14.454  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 11:37:14.464  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 11:37:14.464  6312  6312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 11:37:14.464  6312  6312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 11:37:14.464  6312  6312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 11:37:14.474  6312  6364 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 11:37:14.474  6312  6364 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:37:14.474  6312  6364 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:37:14.474  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:37:14.474  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:14.474  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 11:37:14.474  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 11:37:14.474  6312  6364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b534f5a removed from the list
08-30 11:37:14.474  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:37:14.474  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e42658b removed from the list
08-30 11:37:14.474  6312  6364 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:37:14.474  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:37:14.474  7020  7049 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 9
,08-30 11:37:14.474  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 11:37:14.474  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:37:14.474  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 11:37:14.474  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:37:14.474  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 11:37:14.474  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e42658b not in the list
08-30 11:37:14.474  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:14.474  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:37:14.474  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 11:37:14.474  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:37:14.474  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 11:37:14.484  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33670726 removed from the list
08-30 11:37:14.484  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:37:14.484  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:14.484  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:37:14.484  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 11:37:14.484  6312  6364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16235a81 removed from the list
,08-30 11:37:14.484  6312  6364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 11:37:14.484  6312  6364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bac6fb2 added. We now have 2 listener(s)
,08-30 11:37:14.484  7020  7049 D BtGatt.ScanManager: filter size is 1
,08-30 11:37:14.484  7020  7049 D BtGatt.ScanManager: delete FilterIndex - 3
08-30 11:37:14.484  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-30 11:37:14.484  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 11:37:14.484  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 11:37:14.484  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 11:37:14.484  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281ffb03 added. We now have 9 listener(s)
08-30 11:37:14.484  6312  6364 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 11:37:14.484  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 11:37:14.484  7020  7045 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-30 11:37:14.484  7020  7045 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 11:37:14.494  7020  7049 D BtGatt.ScanManager: stopping BLe Batch
,08-30 11:37:14.494  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-30 11:37:14.494  7020  7045 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-30 11:37:14.494  7020  7045 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 11:37:14.494  7020  7049 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-30 11:37:14.494  7020  7045 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
08-30 11:37:14.494  7020  7045 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 11:37:14.504  6312  6364 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 11:37:14.504  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:14.504  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:37:14.504  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:37:14.504  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:37:14.504  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:37:14.504  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:37:14.504  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 11:37:14.514  6312  6364 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 11:37:14.514  6312  6364 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 11:37:14.514  6312  6364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 11:37:14.514  6312  6364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23dfd8b9 added. We now have 3 listener(s),
08-30 11:37:14.514  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:37:14.514  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:37:14.524  7124  7124 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-30 11:37:14.524  7124  7124 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-30 11:37:14.524  7124  7124 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-30 11:37:14.524  7124  7124 I dhcpcd  : bssid match
08-30 11:37:14.524  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-30 11:37:14.524  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 11:37:14.524  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 11:37:14.524  7124  7124 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111
08-30 11:37:14.524  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 11:37:14.524  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@126dd4fe added. We now have 10 listener(s)
08-30 11:37:14.524  6312  6364 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 11:37:14.524  6312  6364 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 11:37:14.524  6312  6364 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 11:37:14.524  6312  6364 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 11:37:14.524  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 11:37:14.524  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 11:37:14.524  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 11:37:14.524  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 11:37:14.534  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 11:37:14.534  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 11:37:14.534  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 11:37:14.534  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-30 11:37:14.534  6312  6364 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 11:37:14.544  7020  7029 D BtGatt.GattService: registerClient() - UUID=c2ee992a-071e-4a7b-883e-c8eaf4c56215
,08-30 11:37:14.584  7020  7045 D BtGatt.GattService: onClientRegistered() - UUID=c2ee992a-071e-4a7b-883e-c8eaf4c56215, clientIf=6
,08-30 11:37:14.584  6312  6326 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-30 11:37:14.584  7020  7088 D BtGatt.GattService: start scan with filters
,08-30 11:37:14.584  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 11:37:14.584  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-30 11:37:14.584  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-30 11:37:14.584  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 11:37:14.594  6312  6364 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 11:37:14.594  6312  6364 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 11:37:14.594  6312  6312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 11:37:14.594  7020  7049 D BtGatt.ScanManager: handling starting scan
,08-30 11:37:14.594  7020  7045 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-30 11:37:14.594  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 11:37:14.594  7020  7045 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 11:37:14.594  7020  7049 D BtGatt.ScanManager: allow scan with filters
,08-30 11:37:14.594  7020  7049 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-30 11:37:14.594  7020  7049 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-30 11:37:14.604  7020  7045 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-30 11:37:14.604  7020  7045 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 11:37:14.604  7020  7049 D BtGatt.ScanManager: Starting BLE batch scan
,08-30 11:37:14.604  7020  7049 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-30 11:37:14.604  7020  7045 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-30 11:37:14.604  7020  7045 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 11:37:14.604  6312  6364 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 11:37:14.614  6312  6364 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-30 11:37:14.614  6312  6364 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:37:14.614  6312  6364 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:37:14.614  6312  6364 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:37:14.614  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:37:14.614  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:14.614  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 11:37:14.614  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 11:37:14.614  7020  7045 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-30 11:37:14.614  6312  6364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bac6fb2 removed from the list
08-30 11:37:14.614  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:37:14.614  7020  7045 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 11:37:14.614  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281ffb03 removed from the list
,08-30 11:37:14.614  6312  6364 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:37:14.614  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 11:37:14.614  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:14.614  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-30 11:37:14.614  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:14.614  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 11:37:14.614  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:37:14.614  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:37:14.614  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 11:37:14.614  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281ffb03 not in the list
08-30 11:37:14.614  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 11:37:14.614  6312  6364 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 11:37:14.614  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 11:37:14.614  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-30 11:37:14.614  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 11:37:14.614  7020  7088 D BtGatt.GattService: stopScan() - queue size =1
,08-30 11:37:14.624  7020  7028 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-30 11:37:14.624  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 11:37:14.624  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 11:37:14.624  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 11:37:14.624  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 11:37:14.624  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 11:37:14.624  6312  6364 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 11:37:14.624  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 11:37:14.624  6312  6364 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 11:37:14.624  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 11:37:14.624  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:37:14.624  6312  6312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-30 11:37:14.624  6312  6312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 11:37:14.624  6312  6312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 11:37:14.624  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:37:14.624  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:37:14.624  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:37:14.624  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@126dd4fe removed from the list
08-30 11:37:14.624  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:37:14.624  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:14.624  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:37:14.624  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 11:37:14.624  6312  6364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23dfd8b9 removed from the list
08-30 11:37:14.624  6312  6364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 11:37:14.624  6312  6364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e4e430a added. We now have 2 listener(s)
,08-30 11:37:14.634  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-30 11:37:14.634  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 11:37:14.634  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 11:37:14.634  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 11:37:14.634  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@337bc77b added. We now have 9 listener(s)
08-30 11:37:14.634  6312  6364 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 11:37:14.634  7020  7049 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 10
08-30 11:37:14.634  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 11:37:14.634  7020  7049 D BtGatt.ScanManager: filter size is 1
08-30 11:37:14.634  7020  7049 D BtGatt.ScanManager: delete FilterIndex - 4,
,08-30 11:37:14.634  7020  7045 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-30 11:37:14.634  7020  7045 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 11:37:14.644  7020  7049 D BtGatt.ScanManager: stopping BLe Batch
,08-30 11:37:14.644  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 11:37:14.644  6312  6364 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 11:37:14.644  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:14.644  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:37:14.644  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:37:14.644  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:37:14.644  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:37:14.644  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:37:14.644  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 11:37:14.644  7020  7045 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-30 11:37:14.644  7020  7045 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 11:37:14.644  7020  7049 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-30 11:37:14.644  7124  7124 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1
,08-30 11:37:14.644  7020  7045 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-30 11:37:14.644  7020  7045 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 11:37:14.654  6312  6364 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 11:37:14.654  6312  6364 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 11:37:14.654  6312  6364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 11:37:14.654  6312  6364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1976e5f1 added. We now have 3 listener(s)
,08-30 11:37:14.654  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:37:14.654  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:14.654  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-30 11:37:14.654  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 11:37:14.654  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 11:37:14.654  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 11:37:14.654  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1585d6 added. We now have 10 listener(s)
08-30 11:37:14.654  6312  6364 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 11:37:14.654  6312  6364 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 11:37:14.654  6312  6364 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 11:37:14.654  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 11:37:14.654  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 11:37:14.654  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 11:37:14.654  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 11:37:14.664  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 11:37:14.664  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 11:37:14.664  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 11:37:14.664  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-30 11:37:14.664  6312  6364 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 11:37:14.674  7020  7088 D BtGatt.GattService: registerClient() - UUID=d10dbee0-0998-4b16-baac-1807e44eb19a
,08-30 11:37:14.724  7020  7045 D BtGatt.GattService: onClientRegistered() - UUID=d10dbee0-0998-4b16-baac-1807e44eb19a, clientIf=6
08-30 11:37:14.724  6312  6326 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-30 11:37:14.724  7020  7028 D BtGatt.GattService: start scan with filters
,08-30 11:37:14.724  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 11:37:14.724  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 11:37:14.724  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-30 11:37:14.724  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 11:37:14.724  7020  7049 D BtGatt.ScanManager: handling starting scan
,08-30 11:37:14.724  6312  6364 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 11:37:14.724  6312  6364 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 11:37:14.724  6312  6312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 11:37:14.724  7020  7045 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-30 11:37:14.724  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-30 11:37:14.724  7020  7045 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 11:37:14.724  7020  7049 D BtGatt.ScanManager: allow scan with filters
,08-30 11:37:14.724  7020  7049 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-30 11:37:14.724  7020  7049 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-30 11:37:14.724  7020  7045 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-30 11:37:14.724  7020  7045 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 11:37:14.734  7020  7049 D BtGatt.ScanManager: Starting BLE batch scan
08-30 11:37:14.734  7020  7049 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-30 11:37:14.734  7020  7045 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-30 11:37:14.734  7020  7045 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 11:37:14.734  6312  6364 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 11:37:14.734  6312  6364 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:37:14.734  6312  6364 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:37:14.734  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:37:14.734  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:14.734  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 11:37:14.734  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 11:37:14.734  6312  6364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e4e430a removed from the list
08-30 11:37:14.734  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:37:14.734  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@337bc77b removed from the list
08-30 11:37:14.734  6312  6364 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:37:14.734  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 11:37:14.734  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:14.734  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-30 11:37:14.734  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:14.734  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 11:37:14.734  7020  7045 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-30 11:37:14.734  7020  7045 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 11:37:14.744  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:37:14.744  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 11:37:14.744  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:37:14.744  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@337bc77b not in the list
08-30 11:37:14.744  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 11:37:14.744  6312  6364 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 11:37:14.744  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 11:37:14.744  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 11:37:14.744  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 11:37:14.754  7020  7088 D BtGatt.GattService: stopScan() - queue size =1
,08-30 11:37:14.754  7020  7028 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-30 11:37:14.754  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 11:37:14.754  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 11:37:14.754  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 11:37:14.754  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 11:37:14.754  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 11:37:14.754  6312  6364 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
08-30 11:37:14.754  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 11:37:14.754  6312  6364 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-30 11:37:14.754  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 11:37:14.754  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:37:14.764  6312  6312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-30 11:37:14.764  6312  6312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 11:37:14.764  6312  6312 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 11:37:14.764  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:37:14.764  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 11:37:14.764  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:37:14.764  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1585d6 removed from the list
08-30 11:37:14.764  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 11:37:14.764  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-30 11:37:14.764  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,08-30 11:37:14.764  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 11:37:14.764  6312  6364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1976e5f1 removed from the list
08-30 11:37:14.764  6312  6364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 11:37:14.764  6312  6364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@273c2962 added. We now have 2 listener(s)
,08-30 11:37:14.764  7020  7049 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 11
08-30 11:37:14.764  7020  7049 D BtGatt.ScanManager: filter size is 1
08-30 11:37:14.764  7020  7049 D BtGatt.ScanManager: delete FilterIndex - 5
08-30 11:37:14.764  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-30 11:37:14.764  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 11:37:14.764  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 11:37:14.764  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 11:37:14.764  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d05aaf3 added. We now have 9 listener(s)
08-30 11:37:14.764  6312  6364 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-30 11:37:14.764  7020  7045 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-30 11:37:14.764  7020  7045 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 11:37:14.764  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 11:37:14.764  7020  7049 D BtGatt.ScanManager: stopping BLe Batch
,08-30 11:37:14.774  7020  7045 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-30 11:37:14.774  7020  7045 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 11:37:14.774  7020  7049 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-30 11:37:14.774  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 11:37:14.774  7020  7045 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-30 11:37:14.774  7020  7045 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 11:37:14.784  7124  7124 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds
,08-30 11:37:14.794  6312  6364 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 11:37:14.794  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,08-30 11:37:14.794  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 11:37:14.794  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:37:14.794  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:37:14.794  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:37:14.794  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:37:14.794  6312  6364 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 11:37:14.794  6312  6364 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 11:37:14.794  6312  6364 D io.jxcore.node.ConnectivityMonitor: start: OK,
08-30 11:37:14.794  6312  6364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 11:37:14.794  6312  6364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7cb6229 added. We now have 3 listener(s)
08-30 11:37:14.794  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:37:14.804  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-30 11:37:14.804  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 11:37:14.804  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 11:37:14.804  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 11:37:14.804  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e3779ae added. We now have 10 listener(s)
08-30 11:37:14.804  6312  6364 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 11:37:14.804  6312  6364 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:37:14.804  6312  6364 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:37:14.804  6312  6364 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:37:14.804  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:37:14.804  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:14.804  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 11:37:14.804  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 11:37:14.804  6312  6364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@273c2962 removed from the list
,08-30 11:37:14.804  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:37:14.804  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d05aaf3 removed from the list
08-30 11:37:14.804  6312  6312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:14.804  6312  6364 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:37:14.804  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:37:14.804  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:14.804  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:37:14.804  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:37:14.804  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:37:14.804  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-30 11:37:14.804  6312  6364 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d05aaf3 not in the list
08-30 11:37:14.804  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:14.804  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:37:14.804  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:37:14.804  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:37:14.804  6312  6364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:37:14.804  6312  6364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e3779ae removed from the list
08-30 11:37:14.804  6312  6364 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:37:14.804  6312  6364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:14.804  6312  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:37:14.804  6312  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 11:37:14.804  6312  6364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7cb6229 removed from the list
08-30 11:37:14.804  6312  6364 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-30 11:37:14.804  6312  6364 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 11:37:14.804  6312  6364 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-30 11:37:14.804  6312  6364 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 11:37:14.804  6312  6364 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-30 11:37:14.804  6312  6364 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 11:37:14.824  6312  7139 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1191, name: My test thread name)
,08-30 11:37:14.824  6312  7139 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1191, thread name: My test thread name)
08-30 11:37:14.824  6312  7139 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1191, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-30 11:37:14.824  6312  7141 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1193, name: My test thread name)
,08-30 11:37:14.824  6312  7141 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1193, thread name: My test thread name)
08-30 11:37:14.824  6312  7141 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1193, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-30 11:37:14.824  6312  6364 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-30 11:37:14.824  6312  6364 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,08-30 11:37:14.824  6312  6364 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-30 11:37:14.824  6312  6364 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-30 11:37:14.824  6312  6364 D com.test.thalitest.ThaliTestRunner: Total duration: 23377 ms,
08-30 11:37:14.824  6312  6364 I jxcore-log: *Native tests were executed*
08-30 11:37:14.824  6312  6364 I jxcore-log: 
08-30 11:37:14.824  6312  6364 I jxcore-log: Total number of executed tests:  80,
08-30 11:37:14.824  6312  6364 I jxcore-log: 
08-30 11:37:14.824  6312  6364 I jxcore-log: Number of passed tests:  80
08-30 11:37:14.824  6312  6364 I jxcore-log: ,
08-30 11:37:14.824  6312  6364 I jxcore-log: Number of failed tests:  0
08-30 11:37:14.824  6312  6364 I jxcore-log: 
,08-30 11:37:14.824  6312  6364 I jxcore-log: Number of ignored tests:  0
08-30 11:37:14.824  6312  6364 I jxcore-log: 
08-30 11:37:14.824  6312  6364 I jxcore-log: Total duration:  23377
08-30 11:37:14.824  6312  6364 I jxcore-log: 
08-30 11:37:14.824  6312  6364 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****,
08-30 11:37:14.824  6312  6364 I jxcore-log: 
08-30 11:37:14.834  6312  6364 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 11:37:14.834  6312  6364 I jxcore-log: 
08-30 11:37:14.844  6312  6364 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 11:37:14.844  6312  6364 I jxcore-log: 
,08-30 11:37:14.844  6312  6364 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
08-30 11:37:14.844  6312  6364 I jxcore-log: 
08-30 11:37:14.844  6312  6364 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 11:37:14.844  6312  6364 I jxcore-log: 
08-30 11:37:14.844  6312  6312 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-30 11:37:14.844  6312  6364 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 11:37:14.844  6312  6364 I jxcore-log: 
,08-30 11:37:14.844  6312  6364 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 11:37:14.844  6312  6364 I jxcore-log: 
,08-30 11:37:14.844  6312  6364 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
08-30 11:37:14.844  6312  6364 I jxcore-log: 
,08-30 11:37:14.854  6312  6364 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 11:37:14.854  6312  6364 I jxcore-log: 
,08-30 11:37:14.854  6312  6364 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"},
08-30 11:37:14.854  6312  6364 I jxcore-log: 
,08-30 11:37:14.854  6312  6364 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 11:37:14.854  6312  6364 I jxcore-log: 
,08-30 11:37:14.854  6312  6364 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"},
08-30 11:37:14.854  6312  6364 I jxcore-log: 
,08-30 11:37:14.854  6312  6364 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"},
08-30 11:37:14.854  6312  6364 I jxcore-log: 
,08-30 11:37:14.854  6312  6364 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"},
08-30 11:37:14.854  6312  6364 I jxcore-log: 
,08-30 11:37:14.854  6312  6364 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"},
08-30 11:37:14.854  6312  6364 I jxcore-log: 
,08-30 11:37:14.864  6312  6364 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 11:37:14.864  6312  6364 I jxcore-log: 
,08-30 11:37:14.864  6312  6364 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"},
08-30 11:37:14.864  6312  6364 I jxcore-log: 
,08-30 11:37:14.864  6312  6364 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"},
08-30 11:37:14.864  6312  6364 I jxcore-log: 
,08-30 11:37:14.864  6312  6364 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"},
08-30 11:37:14.864  6312  6364 I jxcore-log: 
,08-30 11:37:14.864  6312  6364 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"},
08-30 11:37:14.864  6312  6364 I jxcore-log: 
,08-30 11:37:14.864  6312  6364 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"},
08-30 11:37:14.864  6312  6364 I jxcore-log: 
,08-30 11:37:14.864  6312  6364 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-30 11:37:14.864  6312  6364 I jxcore-log: 
,08-30 11:37:14.864  6312  6364 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-30 11:37:14.864  6312  6364 I jxcore-log: 
,08-30 11:37:14.864  6312  6364 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-30 11:37:14.864  6312  6364 I jxcore-log: 
,08-30 11:37:14.874  6312  6364 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-30 11:37:14.874  6312  6364 I jxcore-log: 
,08-30 11:37:14.874  6312  6364 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-30 11:37:14.874  6312  6364 I jxcore-log: 
,08-30 11:37:14.874  6312  6364 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-30 11:37:14.874  6312  6364 I jxcore-log: 
,08-30 11:37:14.874  6312  6364 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-30 11:37:14.874  6312  6364 I jxcore-log: 
,08-30 11:37:14.964  6312  6312 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 11:37:14.964  6312  6364 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 11:37:14.964  6312  6364 I jxcore-log: 
,08-30 11:37:15.024  1017  1128 E WifiNative-wlan0: do suspend true
,08-30 11:37:15.054  1017  1127 D WifiP2pService: InactiveState{ what=143375 }
08-30 11:37:15.054  1017  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-30 11:37:15.064  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020543/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 11:37:15.064  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 11:37:15.064  1017  1128 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-30 11:37:15.064  1017  1128 E WifiStateMachine: VerifyingLinkState enter
,08-30 11:37:15.064  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:37:15.064  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-30 11:37:15.064  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:37:15.064  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 11:37:15.094  7147  7147 D AndroidRuntime: 
08-30 11:37:15.094  7147  7147 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-30 11:37:15.094  7147  7147 D AndroidRuntime: CheckJNI is OFF,
08-30 11:37:15.094  7147  7147 D AndroidRuntime: readGMSProperty: start,
08-30 11:37:15.094  7147  7147 D AndroidRuntime: readGMSProperty: already setted!!
08-30 11:37:15.094  7147  7147 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-30 11:37:15.094  7147  7147 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
,08-30 11:37:15.094  7147  7147 D AndroidRuntime: readGMSProperty: end
08-30 11:37:15.094  7147  7147 D AndroidRuntime: addProductProperty: start
,08-30 11:37:15.124  6312  6312 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-30 11:37:15.134  6312  6364 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 11:37:15.134  6312  6364 I jxcore-log: 
,08-30 11:37:15.134  1017  1501 I art     : Explicit concurrent mark sweep GC freed 57563(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 28MB/42MB, paused 2.588ms total 147.780ms
,08-30 11:37:15.134  1017  1128 D WifiNative-wlan0: callSECApiInt - ID [210]
,08-30 11:37:15.134  1017  1130 E ConnectivityService: updateNetworkInfo()
,08-30 11:37:15.134  1017  1130 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
08-30 11:37:15.134  1017  1130 D ConnectivityService: Adding iface wlan0 to network 504
,08-30 11:37:15.144  1017  1145 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
08-30 11:37:15.144  1017  1145 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
08-30 11:37:15.144  1017  1145 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-30 11:37:15.144  1017  1145 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-30 11:37:15.144  1017  1145 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-30 11:37:15.154  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020543/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 11:37:15.154  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 11:37:15.154  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:37:15.154  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:37:15.154  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:37:15.154  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 11:37:15.154  1017  1128 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
08-30 11:37:15.154  1017  1477 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 11:37:15.154  1017  1477 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-30 11:37:15.154  1017  1477 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:15.154  1017  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:15.154  1017  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-30 11:37:15.154  3682  3682 I Hs20UtilService: Starting #22
08-30 11:37:15.154  3682  3722 I Hs20UtilService: Message received 5007
,08-30 11:37:15.164  1319  1319 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-30 11:37:15.164  1319  1319 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-30 11:37:15.164  1017  1130 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,08-30 11:37:15.164  1017  1130 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
08-30 11:37:15.164  1017  1130 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
08-30 11:37:15.164  1017  1130 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-30 11:37:15.164  1017  1130 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
08-30 11:37:15.164  1017  1130 D ConnectivityService: LTETest block dns file not exists
,08-30 11:37:15.174  1017  1130 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504],
,08-30 11:37:15.184  1017  1130 E ConnectivityService: updateNetworkInfo()
,08-30 11:37:15.194  1017  1130 E ConnectivityService: updateNetworkInfo()
08-30 11:37:15.194  1017  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 11:37:15.194  1017  1130 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-30 11:37:15.194  1017  1130 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
,08-30 11:37:15.194  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-30 11:37:15.194  1017  7121 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:15.194  1017  7121 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-30 11:37:15.194  1017  7121 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:15.194  1017  7121 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,08-30 11:37:15.194  1017  7121 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 11:37:15.194   280   985 D EnterpriseController: uids 1000,
08-30 11:37:15.194   280   985 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-30 11:37:15.194   280   985 D Netd    : getNetworkForDns: using netid 504 for uid 1000
,08-30 11:37:15.194  1017  1127 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false,
08-30 11:37:15.194  1017  1130 D ConnectivityService:    accepting network in place of null
08-30 11:37:15.194  1453  1453 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-30 11:37:15.194  1017  1130 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-30 11:37:15.194  1453  1453 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 11:37:15.194  1017  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE,
08-30 11:37:15.194  1017  1130 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-30 11:37:15.204  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020543/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 11:37:15.204  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 11:37:15.204  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:37:15.204  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 11:37:15.204  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:37:15.204  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:37:15.204  1017  1128 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-30 11:37:15.204  1017  1130 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
08-30 11:37:15.204  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-30 11:37:15.204  1017  1017 I WifiTrafficPoller: mBoosterFLAG : 0
,08-30 11:37:15.204  1017  1017 I WifiTrafficPoller: current booster mode : FullMode
08-30 11:37:15.204  1017  1017 D WifiNative-wlan0: callSECApiVoid - ID [212]
,08-30 11:37:15.204  1017  1130 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,08-30 11:37:15.204  1177  1690 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 11:37:15.204  3808  4216 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-30 11:37:15.214  1017  1017 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-30 11:37:15.214  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020543/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 11:37:15.214  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-30 11:37:15.214  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:37:15.214  1017  1131 D Tethering: MasterInitialState.processMessage what=3
08-30 11:37:15.214  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:37:15.214  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:37:15.214  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 11:37:15.214  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 11:37:15.214  1017  1125 V NetworkStats: updateIfacesLocked()
08-30 11:37:15.214  1017  1125 V NetworkStats: performPollLocked(flags=0x1)
,08-30 11:37:15.214  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated,
08-30 11:37:15.214  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 11:37:15.224  1017  3440 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 11:37:15.224  1017  3440 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-30 11:37:15.224  1017  3440 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:15.224  1017  3440 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:15.224  1017  3440 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 11:37:15.224  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 11:37:15.224  1017  1125 V NetworkStats: performPollLocked() took 6ms
08-30 11:37:15.224  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 11:37:15.224  1017  1126 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-30 11:37:15.224  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 11:37:15.224  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 11:37:15.224  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 11:37:15.224  3682  3682 I Hs20UtilService: Starting #23
08-30 11:37:15.224  3682  3722 I Hs20UtilService: Message received 5007
,08-30 11:37:15.224  1319  1319 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-30 11:37:15.224  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 11:37:15.224  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 11:37:15.224  1319  1319 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 11:37:15.224  1319  1319 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,08-30 11:37:15.234  1319  1319 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-30 11:37:15.234  1319  1319 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
08-30 11:37:15.234  1319  1319 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-30 11:37:15.234  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
08-30 11:37:15.234  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-30 11:37:15.234  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-30 11:37:15.234  1177  1177 D StatusBar.NetworkController: updateDataNetType()
08-30 11:37:15.234  1177  1177 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-30 11:37:15.234  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-30 11:37:15.244  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false,
08-30 11:37:15.244  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-30 11:37:15.244  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal,
08-30 11:37:15.244  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020543/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 11:37:15.244  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-30 11:37:15.244  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:37:15.244  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:37:15.244  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 11:37:15.244  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 11:37:15.244  1017  1030 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-30 11:37:15.254  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 11:37:15.254  7147  7147 E AffinityControl: AffinityControl: registerfunction enter
,08-30 11:37:15.254  1017  1030 W ActivityManager: userId = 0, bbcId = -10000,
08-30 11:37:15.254  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 11:37:15.254  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-30 11:37:15.254  3682  3682 I Hs20UtilService: Starting #24
,08-30 11:37:15.254  3682  3722 I Hs20UtilService: Message received 5007
,08-30 11:37:15.254  1319  1319 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-30 11:37:15.254  1319  1319 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-30 11:37:15.264  6312  6312 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 11:37:15.264  6312  6364 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 11:37:15.264  6312  6364 I jxcore-log: 
,08-30 11:37:15.274  1017  3289 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0,
08-30 11:37:15.274  1017  3091 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
08-30 11:37:15.274  1017  3091 D SecContentProvider2: mCursor = null
08-30 11:37:15.274  1017  1560 D SecContentProvider2: uri = 15 selection = getToastGravity
08-30 11:37:15.274  1017  1560 D SecContentProvider2: mCursor = null
08-30 11:37:15.274  1017  1030 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-30 11:37:15.274  1017  1030 D SecContentProvider2: mCursor = null
08-30 11:37:15.274  1017  1029 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
08-30 11:37:15.274  1017  1029 D SecContentProvider2: mCursor = null
08-30 11:37:15.274  7147  7147 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 11:37:15.284  1017  1497 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,08-30 11:37:15.284  1017  1497 D SecContentProvider2: mCursor = null
,08-30 11:37:15.284  1017  3440 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
08-30 11:37:15.284  1017  3440 D SecContentProvider2: mCursor = null
,08-30 11:37:15.294  1017  3289 D PackageManager: START PACKAGE DELETE: observer{993497174}
08-30 11:37:15.294  1017  3289 D PackageManager: pkg{<packageName>}
08-30 11:37:15.294  1017  3289 D PackageManager: user{0}
08-30 11:37:15.294  1017  3289 D PackageManager: caller{2000}
08-30 11:37:15.294  1017  3289 D PackageManager: flags{2}
,08-30 11:37:15.294  1017  3289 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-30 11:37:15.294  1017  3289 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-30 11:37:15.294  1017  3289 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-30 11:37:15.294  1017  3289 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-30 11:37:15.294  1017  3289 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-30 11:37:15.294  1017  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-30 11:37:15.294  1017  1058 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-30 11:37:15.294  1017  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-30 11:37:15.294  1017  1058 D ApplicationPolicy: getApplicationUninstallationEnabled
08-30 11:37:15.294  1017  1058 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-30 11:37:15.294  1017  1058 D PackageManager: !@killApplicatoin: 10155, uninstall pkg
,08-30 11:37:15.324  1017  1043 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
,08-30 11:37:15.324  1017  1043 I ActivityManager: Killing 6312:com.test.thalitest/u0a155 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-30 11:37:15.404   257   257 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=4, Uoast
,08-30 11:37:15.404  1017  1043 I ActivityManager:   Force finishing activity ActivityRecord{272c9f86 u0 com.test.thalitest/.MainActivity t128}
,08-30 11:37:15.424  1017  1098 W InputDispatcher: channel ~ Consumer closed input channel or an error occurred.  events=0x9
08-30 11:37:15.424  1017  1217 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017
08-30 11:37:15.424  1017  1098 E InputDispatcher: channel ~ Channel is unrecoverably broken and will be disposed!
,08-30 11:37:15.424  1017  1560 W InputDispatcher: Attempted to unregister already unregistered input channel
08-30 11:37:15.424  1017  1560 I WindowState: WIN DEATH: Window{a3258e6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-30 11:37:15.424   257  7175 I SurfaceFlinger: id=14 Removed NainActivit (6/9)
08-30 11:37:15.424  1177  1177 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-30 11:37:15.424   257   439 I SurfaceFlinger: id=14 Removed NainActivit (-2/9)
08-30 11:37:15.424   257  7175 I SurfaceFlinger: id=14 Removed NainActivit (-2/9)
,08-30 11:37:15.434  1017  1043 W ActivityManager: mDVFSHelper.acquire()
,08-30 11:37:15.434  1017  1560 D InputDispatcher: Focus left window: 6312
,08-30 11:37:15.434  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-30 11:37:15.434  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-30 11:37:15.454  1017  1058 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,08-30 11:37:15.454  1017  1058 I ActivityManager:   Force finishing activity ActivityRecord{272c9f86 u0 com.test.thalitest/.MainActivity t128 f}
,08-30 11:37:15.454  1017  1058 W ActivityManager: Duplicate finish request for ActivityRecord{272c9f86 u0 com.test.thalitest/.MainActivity t128 f}
,08-30 11:37:15.464  1017  1058 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-30 11:37:15.504  3173  3173 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,08-30 11:37:15.504  5779  5779 I art     : Explicit concurrent mark sweep GC freed 2068(118KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 820us total 31.302ms
,08-30 11:37:15.504  1017  1043 D InputDispatcher: Focused application released
,08-30 11:37:15.514  3173  3173 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 6
,08-30 11:37:15.524  3173  3173 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,08-30 11:37:15.544  3173  3173 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,08-30 11:37:15.544  3173  3173 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 6
,08-30 11:37:15.544  1017  1099 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 11:37:15.554  3173  3173 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,08-30 11:37:15.554  3808  3808 I art     : Explicit concurrent mark sweep GC freed 18905(1159KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 15MB/26MB, paused 1.362ms total 91.175ms
,08-30 11:37:15.554  1770  1770 E SamsungIME: mOCRHelper is null
,08-30 11:37:15.564  1929  2098 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-30 11:37:15.584  1017  1125 V NetworkStats: removeUidsLocked() for UIDs [10155]
08-30 11:37:15.584  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 11:37:15.584  1017  1125 V NetworkStats: performPollLocked(flags=0x3)
,08-30 11:37:15.584  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 11:37:15.584  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 11:37:15.594  1017  1125 V NetworkStats: performPollLocked() took 10ms
,08-30 11:37:15.594  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 11:37:15.594  3173  3173 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,08-30 11:37:15.604  3173  3173 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,08-30 11:37:15.604  1441  1441 D PersonaManager: isKioskContainerExistOnDevice
,08-30 11:37:15.614  1441  1441 D RegisteredServicesCache: empty dynamic service
,08-30 11:37:15.624  3173  3173 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,08-30 11:37:15.624  3730  3730 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 30 11:37:15 GMT+02:00 2016
,08-30 11:37:15.624  1017  1030 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-30 11:37:15.624  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-30 11:37:15.624  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-30 11:37:15.624  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:15.624  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-30 11:37:15.634  1441  1441 D RegisteredComponentCache: Collect Tech packages for Knox
,08-30 11:37:15.634  3730  3730 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,08-30 11:37:15.644  3730  3730 I KLMS-2.5.183: : KLMSIntentService(): onCreate(),
,08-30 11:37:15.644  1017  1029 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
08-30 11:37:15.644  1017  1029 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-30 11:37:15.644  3730  3730 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-30 11:37:15.654  1441  1441 D PersonaManager: isKioskContainerExistOnDevice
08-30 11:37:15.654  1017  1477 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-30 11:37:15.654  1017  1477 D SecContentProvider2: mCursor = null
,08-30 11:37:15.654  1017  1350 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,08-30 11:37:15.654  1017  1350 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,08-30 11:37:15.664  3173  3173 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 6
,08-30 11:37:15.664  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-30 11:37:15.664  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:37:15.664  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:37:15.664  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:37:15.664  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:37:15.674  3730  3730 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-30 11:37:15.684  7179  7179 E Zygote  : MountEmulatedStorage()
08-30 11:37:15.684  7179  7179 E Zygote  : v2
08-30 11:37:15.684  7179  7179 I libpersona: KNOX_SDCARD checking this for 10094
08-30 11:37:15.684  7179  7179 I libpersona: KNOX_SDCARD not a persona
,08-30 11:37:15.684  3730  7178 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-30 11:37:15.684  7179  7179 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 11:37:15.684  3173  3173 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,08-30 11:37:15.684  7179  7179 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 11:37:15.694  7179  7179 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 11:37:15.694  3173  3173 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
08-30 11:37:15.694  3173  3173 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
08-30 11:37:15.694  1017  1029 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7179 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,08-30 11:37:15.694  3173  3173 I DBG_DM  : [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,08-30 11:37:15.704  3730  7178 I KLMS-2.5.183: : KLMSIntentService(): PACKAGE_REMOVED
,08-30 11:37:15.704  3730  7178 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().START
,08-30 11:37:15.704  3173  3173 I DBG_DM  : [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
08-30 11:37:15.704  1017  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 11:37:15.704  3730  7178 I KLMS-2.5.183: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,08-30 11:37:15.714  1017  1042 D EnterpriseDeviceManagerService: Package has changed for user 0
,08-30 11:37:15.714  1017  1042 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-30 11:37:15.714  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 11:37:15.714  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 11:37:15.724  1017  1017 D RCPManagerService: PackageReceiver onReceive()
,08-30 11:37:15.734  7179  7179 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 11:37:15.734  1017  1030 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-30 11:37:15.734  1017  1030 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-30 11:37:15.734  1017  1030 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-30 11:37:15.734  7179  7179 D ActivityThread: Added TimaKeyStore provider
,08-30 11:37:15.734  1017  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,08-30 11:37:15.734  3173  3173 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,08-30 11:37:15.734  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:37:15.734  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:37:15.734  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:37:15.734  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:37:15.744  1017  1017 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
08-30 11:37:15.744  1017  1042 W TextServicesManagerService: no available spell checker services found
,08-30 11:37:15.754  1017  1017 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,08-30 11:37:15.754  1017  1017 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,08-30 11:37:15.754  7194  7194 E Zygote  : MountEmulatedStorage()
,08-30 11:37:15.754  7194  7194 E Zygote  : v2
08-30 11:37:15.754  7194  7194 I libpersona: KNOX_SDCARD checking this for 10044
,08-30 11:37:15.754  7194  7194 I libpersona: KNOX_SDCARD not a persona
,08-30 11:37:15.754  7194  7194 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
08-30 11:37:15.754  1017  1043 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7194 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a,
,08-30 11:37:15.754  7194  7194 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 11:37:15.754  7194  7194 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-30 11:37:15.764  1017  1017 D OTPFW   : OtpDbHelper::getInstance New instance created
,08-30 11:37:15.774  1017  1017 D OTPFW   : DBIntegrity::getInstance - New instance created
,08-30 11:37:15.774  3730  7178 I KLMS-2.5.183: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-30 11:37:15.784  1017  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
08-30 11:37:15.784  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 11:37:15.784  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:37:15.784  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:37:15.784  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:37:15.784  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:37:15.794  1017  1017 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
,08-30 11:37:15.794  1017  1017 I OTPFW   : ProvisionData::getAllEntries Enter
08-30 11:37:15.794  1017  1017 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-30 11:37:15.794  1017  1017 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-30 11:37:15.794  7194  7194 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 11:37:15.804  1017  1017 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED,
08-30 11:37:15.804  7194  7194 D ActivityThread: Added TimaKeyStore provider
08-30 11:37:15.804  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-30 11:37:15.804  1017  1017 V EnterpriseBillingPolicy: uID is 10155
08-30 11:37:15.804  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
08-30 11:37:15.804  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-30 11:37:15.804  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-30 11:37:15.804  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-30 11:37:15.804  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-30 11:37:15.804  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-30 11:37:15.804  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-30 11:37:15.804  3730  7178 I KLMS-2.5.183: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-30 11:37:15.814  7210  7210 E Zygote  : MountEmulatedStorage()
08-30 11:37:15.814  7210  7210 I libpersona: KNOX_SDCARD checking this for 10149
08-30 11:37:15.814  7210  7210 E Zygote  : v2
08-30 11:37:15.814  7210  7210 I libpersona: KNOX_SDCARD not a persona
,08-30 11:37:15.814  3730  7178 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().END
08-30 11:37:15.814  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-30 11:37:15.814  7210  7210 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 11:37:15.824  7210  7210 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
08-30 11:37:15.824  1017  1043 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7210 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 11:37:15.824  7210  7210 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 11:37:15.824  1017  1058 I art     : Explicit concurrent mark sweep GC freed 37431(3MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 28MB/42MB, paused 3.621ms total 329.924ms
08-30 11:37:15.824  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 11:37:15.844  6625  6625 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-30 11:37:15.854  6999  7209 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,08-30 11:37:15.854  1017  1017 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-30 11:37:15.864  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
,08-30 11:37:15.864  1017  2734 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,08-30 11:37:15.864  1017  1017 V EnterpriseBillingPolicy: uID is 10155
08-30 11:37:15.864  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
08-30 11:37:15.864  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-30 11:37:15.864  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-30 11:37:15.864  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-30 11:37:15.864  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-30 11:37:15.864  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-30 11:37:15.864  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-30 11:37:15.864  1017  1017 V AlarmManagerEXT: com.test.thalitest(10155) is removed.
08-30 11:37:15.864  7210  7210 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 11:37:15.874  7210  7210 D ActivityThread: Added TimaKeyStore provider
,08-30 11:37:15.874  3730  3730 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,08-30 11:37:15.874  1017  1017 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
08-30 11:37:15.874  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-30 11:37:15.874  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,08-30 11:37:15.874   257   257 I SurfaceFlinger: id=16 createSurf (720x1280),1 flag=404, YUIInstallC,
,08-30 11:37:15.884  1017  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-30 11:37:15.884  1017  3440 D InputDispatcher: Focus entered window: 3173
,08-30 11:37:15.884  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-30 11:37:15.884  3173  3173 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-30 11:37:15.884  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-30 11:37:15.894  3173  3173 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,08-30 11:37:15.904  7194  7194 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-30 11:37:15.904  7194  7194 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 11:37:15.904  1017  1030 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-30 11:37:15.904  7194  7194 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-30 11:37:15.904  7194  7194 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 11:37:15.904  7194  7194 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,08-30 11:37:15.904  7194  7194 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 11:37:15.904  7194  7194 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-30 11:37:15.904  7194  7194 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-30 11:37:15.914  7179  7179 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-30 11:37:15.914  7179  7179 D elm:15183: ELMEngine.ELMEngine( context ).
,08-30 11:37:15.914  1017  7226 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-30 11:37:15.914  7179  7179 D elm:15183: MDMBridge.setEnterpriseBridge()
,08-30 11:37:15.914  1017  1030 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6312 uid 10155
,08-30 11:37:15.924  1017  1162 D TaskPersister: removeObsoleteFile: deleting file=128_task.xml
,08-30 11:37:15.924  1017  1162 D TaskPersister: removeObsoleteFile: deleting file=127_task.xml
,08-30 11:37:15.924  6999  7209 I art     : Explicit concurrent mark sweep GC freed 741(53KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/9MB, paused 669us total 37.314ms
,08-30 11:37:15.934  1770  1770 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-30 11:37:15.944  1177  1177 D PanelView: There is/are notification(s) 
,08-30 11:37:15.954  1017  1217 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-30 11:37:15.954  1017  1217 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-30 11:37:15.954  1017  1217 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:15.954  1017  1217 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:15.954  1017  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-30 11:37:15.954  1177  1177 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,08-30 11:37:15.954  1177  1177 D PersonaManager: isKioskContainerExistOnDevice
08-30 11:37:15.954  1177  1177 D PersonaManager: isKioskContainerExistOnDevice
,08-30 11:37:15.954  1177  1177 D PanelView: There is/are notification(s) 
08-30 11:37:15.954  1177  1177 D PanelView: kidsfalse mQsExpansionEnabled:true
,08-30 11:37:15.954  3173  3173 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@384f5f4f time:153569
,08-30 11:37:15.964  7179  7179 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-30 11:37:15.964  1177  1177 D PersonaManager: isKioskContainerExistOnDevice
,08-30 11:37:15.964  1177  1177 D PanelView: There is/are notification(s) 
08-30 11:37:15.964  1177  1177 D PanelView: kidsfalse mQsExpansionEnabled:true
,08-30 11:37:15.964  3173  3173 V ActivityThread: updateVisibility : ActivityRecord{28da4f18 token=android.os.BinderProxy@384f5f4f {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,08-30 11:37:15.974  1017  1058 D PackageManager: delete codoeFile: 
,08-30 11:37:15.984  7179  7179 D elm:15183: ElmAgentService : onCreate()
,08-30 11:37:15.984  7179  7229 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
08-30 11:37:15.984  7179  7229 D elm:15183: MainReceiver.listeningToPackageRemoved()
08-30 11:37:15.984  7179  7229 D elm:15183: MDMBridge.getInstance()
08-30 11:37:15.984  7179  7229 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,08-30 11:37:15.984  1017  1058 D AASAuninstall: userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
08-30 11:37:15.984  1017  1058 I AASA_removePackage: UID=10155 Target=com.test.thalitest
,08-30 11:37:15.984  3413  3413 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,08-30 11:37:15.984  6053  6061 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
08-30 11:37:15.984  6053  6061 D BadgeProvider: sendNotify, [notify] : null
08-30 11:37:15.984  6053  6061 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
08-30 11:37:15.984  6053  6061 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-30 11:37:15.984  6053  6061 D BadgeProvider: update, [UpdateCount] : 1
,08-30 11:37:15.994  7179  7229 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,08-30 11:37:15.994  3413  3413 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-30 11:37:15.994  3413  3413 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
08-30 11:37:15.994  3413  3413 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
08-30 11:37:15.994  3413  3413 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
08-30 11:37:15.994  3413  3413 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
08-30 11:37:15.994  3413  3413 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
08-30 11:37:15.994  3413  3413 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 11:37:15.994  3413  3413 W System.err: 	at android.os.Looper.loop(Looper.java:145)
08-30 11:37:15.994  3413  3413 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 11:37:15.994  3413  3413 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 11:37:15.994  3413  3413 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 11:37:15.994  3413  3413 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 11:37:15.994  3413  3413 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 11:37:15.994  7210  7210 D ThemeInfoUtil: getCurrentFestivalName is [null]
08-30 11:37:15.994  7210  7210 D ThemeInfoUtil: isCurrentFestival = false
,08-30 11:37:15.994  1017  1477 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,08-30 11:37:15.994  1017  1058 D PackageManager: result of delete: 1{993497174}
,08-30 11:37:15.994  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:37:15.994  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:37:15.994  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:37:15.994  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:37:16.014  7231  7231 E Zygote  : MountEmulatedStorage()
08-30 11:37:16.014  7231  7231 E Zygote  : v2
08-30 11:37:16.014  7231  7231 I libpersona: KNOX_SDCARD checking this for 1000
08-30 11:37:16.014  7231  7231 I libpersona: KNOX_SDCARD not a persona
,08-30 11:37:16.014  7231  7231 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 11:37:16.014  7231  7231 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-30 11:37:16.014  1017  1477 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7231 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
08-30 11:37:16.014  7231  7231 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 11:37:16.024  7147  7147 D AndroidRuntime: Shutting down VM
,08-30 11:37:16.024  7179  7179 D elm:15183: ElmAgentService : onDestroy().
,08-30 11:37:16.034  1017  1048 W ActivityManager: mDVFSHelper.release()
,08-30 11:37:16.034  1017  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2b397cae u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t127} time:153643
,08-30 11:37:16.034  1177  1177 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,08-30 11:37:16.044  7231  7231 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 11:37:16.054  7231  7231 D ActivityThread: Added TimaKeyStore provider
,08-30 11:37:16.074  1017  1058 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-30 11:37:16.074  1017  1058 D PackageManager: userId{-1}
08-30 11:37:16.074  1017  1058 D PackageManager: andCode{true}
,08-30 11:37:16.074  1017  1497 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-30 11:37:16.074  1017  1497 D SecContentProvider2: mCursor = null
,08-30 11:37:16.074  1017  1501 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,08-30 11:37:16.084  6608  6608 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-30 11:37:16.084  6608  6608 I PCWCLIENTTRACE_PushUtil: sales region : global
08-30 11:37:16.084  6608  6608 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-30 11:37:16.084  6608  6608 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,08-30 11:37:16.084  1017  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:37:16.084  1017  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:37:16.084  1017  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:37:16.084  1017  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:37:16.084  1017  1042 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-30 11:37:16.094  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
08-30 11:37:16.094  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 11:37:16.094  7249  7249 E Zygote  : MountEmulatedStorage()
08-30 11:37:16.094  7249  7249 E Zygote  : v2
08-30 11:37:16.094  7249  7249 I libpersona: KNOX_SDCARD checking this for 10152
08-30 11:37:16.094  7249  7249 I libpersona: KNOX_SDCARD not a persona
,08-30 11:37:16.104  7249  7249 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-30 11:37:16.104  1017  1501 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7249 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
,08-30 11:37:16.104  7249  7249 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 11:37:16.104  7249  7249 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 11:37:16.104  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 11:37:16.114  1017  1042 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-30 11:37:16.114  1017  1042 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 11:37:16.114  1017  1042 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-30 11:37:16.114  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 11:37:16.114  1017  1501 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,08-30 11:37:16.124  1017  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:37:16.124  1017  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:37:16.124  1017  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:37:16.124  1017  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:37:16.124  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 11:37:16.134  7249  7249 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 11:37:16.134  7249  7249 D ActivityThread: Added TimaKeyStore provider
,08-30 11:37:16.134  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 11:37:16.134  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-30 11:37:16.134  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-30 11:37:16.134  7264  7264 E Zygote  : MountEmulatedStorage(),
,08-30 11:37:16.134  1017  1501 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7264 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a,
,08-30 11:37:16.144  7264  7264 E Zygote  : v2
,08-30 11:37:16.144  7264  7264 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-30 11:37:16.144  7264  7264 I libpersona: KNOX_SDCARD checking this for 10032
08-30 11:37:16.144  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-30 11:37:16.144  7264  7264 I libpersona: KNOX_SDCARD not a persona
08-30 11:37:16.144  7264  7264 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-30 11:37:16.144  7264  7264 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 11:37:16.144  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-30 11:37:16.144  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-30 11:37:16.164  7264  7264 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 11:37:16.164  7231  7231 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,08-30 11:37:16.164  7264  7264 D ActivityThread: Added TimaKeyStore provider
,08-30 11:37:16.174  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-30 11:37:16.174  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-30 11:37:16.174  7194  7194 D NearbySource: Nearby Source Create!
,08-30 11:37:16.174  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 11:37:16.174  7194  7194 D NearbyContext: Nearby Context Create!
,08-30 11:37:16.184  1017  1058 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-30 11:37:16.184  1017  1350 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
08-30 11:37:16.184  1017  1350 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,08-30 11:37:16.184  1017  1350 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:16.184  1017  1350 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:16.184  1017  1350 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,08-30 11:37:16.194  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,08-30 11:37:16.204  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:37:16.204  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:37:16.204  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:37:16.204  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:37:16.204  1017  1130 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-30 11:37:16.214  7281  7281 E Zygote  : MountEmulatedStorage(),
08-30 11:37:16.214  7281  7281 E Zygote  : v2
08-30 11:37:16.214  7281  7281 I libpersona: KNOX_SDCARD checking this for 1000,
08-30 11:37:16.214  1017  1030 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7281 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
08-30 11:37:16.214  7281  7281 I libpersona: KNOX_SDCARD not a persona
,08-30 11:37:16.224  7281  7281 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 11:37:16.224  7281  7281 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-30 11:37:16.224  7281  7281 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 11:37:16.234  7147  7147 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-30 11:37:16.234  1017  1042 D UsbSettingsManager: clearDefaults: com.test.thalitest
08-30 11:37:16.234  1017  1042 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-30 11:37:16.244  1017  1501 I ActivityManager: Killing 6247:com.google.android.gms:car/u0a12 (adj 15): empty #31
,08-30 11:37:16.244  7249  7249 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
08-30 11:37:16.244  1017  1042 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-30 11:37:16.244   256   539 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
08-30 11:37:16.244   256   539 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 11:37:16.244  7194  7194 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,08-30 11:37:16.244  7194  7194 D SLinkSource: Samsung link source created
,08-30 11:37:16.254  1017  1497 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
,08-30 11:37:16.254  1017  1497 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,08-30 11:37:16.254  1017  1497 W ActivityManager: userId = 0, bbcId = -10000
08-30 11:37:16.254  1017  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 11:37:16.254  1017  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,08-30 11:37:16.254  7281  7281 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 11:37:16.254  7281  7281 D ActivityThread: Added TimaKeyStore provider
08-30 11:37:16.254  1017  1140 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,08-30 11:37:16.254  1017  1140 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:37:16.254  1017  1140 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:37:16.254  1017  1140 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:37:16.254  1017  1140 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:37:16.274  7298  7298 E Zygote  : MountEmulatedStorage()
08-30 11:37:16.274  7298  7298 E Zygote  : v2
08-30 11:37:16.274  7298  7298 I libpersona: KNOX_SDCARD checking this for 10156
08-30 11:37:16.274  7298  7298 I libpersona: KNOX_SDCARD not a persona
,08-30 11:37:16.274  7298  7298 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 11:37:16.274  1017  1140 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7298 uid=10156 gids={50156, 9997} abi=armeabi-v7a
,08-30 11:37:16.274  7298  7298 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 11:37:16.284  7264  7297 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,08-30 11:37:16.284  7298  7298 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 11:37:16.284  1017  1050 I PowerManagerService: [PWL] Off : 76s ago
08-30 11:37:16.284  1017  1050 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-30 11:37:16.284  1017  1050 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
08-30 11:37:16.284  1017  1050 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'GpsLocationProvider' (uid=1000, pid=1017, ws=null) (elapsedTime=41)
,08-30 11:37:16.294  1017  1477 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-30 11:37:16.304  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:37:16.304  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:37:16.304  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:37:16.304  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:37:16.304  7264  7297 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
08-30 11:37:16.304  7264  7297 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 11:37:16.304  7264  7297 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,08-30 11:37:16.314  7264  7297 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 11:37:16.314  7264  7297 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-30 11:37:16.314  7264  7297 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,08-30 11:37:16.314  7281  7281 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-30 11:37:16.324  1017  1477 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7314 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 11:37:16.324  7314  7314 E Zygote  : MountEmulatedStorage()
08-30 11:37:16.324  1017  1477 I ActivityManager: Killing 5532:com.android.vending/u0a28 (adj 15): empty #31
08-30 11:37:16.324  7314  7314 E Zygote  : v2
08-30 11:37:16.324  7314  7314 I libpersona: KNOX_SDCARD checking this for 10035
08-30 11:37:16.324  7314  7314 I libpersona: KNOX_SDCARD not a persona
08-30 11:37:16.324  7314  7314 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 11:37:16.324  7264  7297 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-30 11:37:16.324  7264  7297 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-30 11:37:16.324  7264  7297 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-30 11:37:16.324  7264  7297 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 11:37:16.324  7264  7297 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-30 11:37:16.324  7264  7297 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 11:37:16.334  7314  7314 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 11:37:16.334  1017  3440 D PersonaManager: isKioskContainerExistOnDevice
,08-30 11:37:16.334  7314  7314 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-30 11:37:16.354   309   309 I art     : Explicit concurrent mark sweep GC freed 8731(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 635us total 35.999ms
,08-30 11:37:16.354  7281  7281 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,08-30 11:37:16.364  1017  1350 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
08-30 11:37:16.364  1017  1350 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,08-30 11:37:16.364  7298  7298 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 11:37:16.364  7298  7298 D ActivityThread: Added TimaKeyStore provider
,08-30 11:37:16.364  1017  1497 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,08-30 11:37:16.374  1017  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 11:37:16.374  1017  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:37:16.374  1017  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:37:16.374  1017  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 11:37:16.374   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 601us total 17.320ms
08-30 11:37:16.374  7264  7297 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-30 11:37:16.374  7264  7297 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 11:37:16.374  7264  7297 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 11:37:16.374  7314  7314 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 11:37:16.374  7314  7314 D ActivityThread: Added TimaKeyStore provider
,08-30 11:37:16.384  6999  7228 E SQLiteLog: (10) unixWrite() File Descriptor : 36 gets errno : 9
08-30 11:37:16.384  7264  7297 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-30 11:37:16.384  6999  7228 E SQLiteLog: (778) statement aborts at 21: [INSERT INTO system_env_info(name,value) VALUES (?,?)] 
08-30 11:37:16.384  7264  7297 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 11:37:16.384  7264  7297 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,08-30 11:37:16.384  6999  7228 E SQLiteLog: (10) unixWrite() File Descriptor : 36 gets errno : 9
,08-30 11:37:16.384  6999  7228 E SQLiteDatabase: Error inserting name=AFP Enabled value=true
08-30 11:37:16.384  6999  7228 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
08-30 11:37:16.384  6999  7228 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-30 11:37:16.384  6999  7228 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
08-30 11:37:16.384  6999  7228 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
08-30 11:37:16.384  6999  7228 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-30 11:37:16.384  6999  7228 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
08-30 11:37:16.384  6999  7228 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
08-30 11:37:16.384  6999  7228 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2487)
08-30 11:37:16.384  6999  7228 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1740)
08-30 11:37:16.384  6999  7228 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.g(LowpowerContextEngine.java:211)
08-30 11:37:16.384  6999  7228 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.e(LowpowerContextEngine.java:150)
08-30 11:37:16.384  6999  7228 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:100)
08-30 11:37:16.384  6999  7228 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:106)
08-30 11:37:16.384  6999  7228 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:100)
08-30 11:37:16.384  6999  7228 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:41)
08-30 11:37:16.384  6999  7228 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.n.run(LowpowerContextReceiver.java:51)
08-30 11:37:16.384  6999  7228 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 11:37:16.384  6999  7228 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 11:37:16.384  6999  7228 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-30 11:37:16.384  6999  7228 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 11:37:16.394  6999  7228 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
,08-30 11:37:16.394  6999  7228 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: Error inserting name=SleepDetection Enabled value=false
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
,08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609),
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2487)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1740)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.g(LowpowerContextEngine.java:212)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.e(LowpowerContextEngine.java:150)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:100)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: ,	,at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:106)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:100)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:41)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.n.run(LowpowerContextReceiver.java:51)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 11:37:16.394  6999  7228 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
,08-30 11:37:16.394  7264  7297 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-30 11:37:16.394  6999  7228 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
08-30 11:37:16.394  7264  7297 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 11:37:16.394   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 621us total 17.850ms
08-30 11:37:16.394  7264  7297 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,08-30 11:37:16.394  6999  7228 E SQLiteDatabase: Error inserting name=System Build Version Release value=5.0.2
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2487)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1740)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.g(LowpowerContextEngine.java:213)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.e(LowpowerContextEngine.java:150)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:100)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:106)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:100)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:41)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.n.run(LowpowerContextReceiver.java:51)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 11:37:16.394  7264  7297 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 11:37:16.394  6999  7228 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-30 11:37:16.394  7264  7297 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,08-30 11:37:16.394  6999  7228 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
08-30 11:37:16.394  7264  7297 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: Error inserting name=status value=successfully initialized
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2487)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1740)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.g(LowpowerContextEngine.java:214)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.e(LowpowerContextEngine.java:150)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:100)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:106)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:100)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:41)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.n.run(LowpowerContextReceiver.java:51)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-30 11:37:16.394  6999  7228 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 11:37:16.394  7264  7297 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-30 11:37:16.394  7264  7297 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-30 11:37:16.404  7332  7332 E Zygote  : MountEmulatedStorage()
,08-30 11:37:16.404  7332  7332 E Zygote  : v2
08-30 11:37:16.404  7332  7332 I libpersona: KNOX_SDCARD checking this for 10091
08-30 11:37:16.404  7332  7332 I libpersona: KNOX_SDCARD not a persona
,08-30 11:37:16.414  7332  7332 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-30 11:37:16.414  7194  7194 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.gallery3d/databases/local.db" with flag (131138) and mode_t (0) due to error (30)
,08-30 11:37:16.414  1017  1497 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7332 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-30 11:37:16.414  1017  1497 I ActivityManager: Killing 6379:com.google.android.gms.unstable/u0a12 (adj 15): empty #31
08-30 11:37:16.414  7264  7297 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 11:37:16.414  7264  7297 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-30 11:37:16.414  7264  7297 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-30 11:37:16.424  7332  7332 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-30 11:37:16.424  7332  7332 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-30 11:37:16.424  7264  7297 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
08-30 11:37:16.424  7264  7297 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-30 11:37:16.424  7264  7297 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-30 11:37:16.424  7264  7297 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 11:37:16.424  7264  7297 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-30 11:37:16.434  7194  7194 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.gallery3d/databases/local.db'.
08-30 11:37:16.434  7194  7194 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 11:37:16.434  7194  7194 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 11:37:16.434  7194  7194 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-30 11:37:16.434  7194  7194 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-30 11:37:16.434  7194  7194 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-30 11:37:16.434  7194  7194 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-30 11:37:16.434  7194  7194 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-30 11:37:16.434  7194  7194 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-30 11:37:16.434  7194  7194 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-30 11:37:16.434  7194  7194 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-30 11:37:16.434  7194  7194 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-30 11:37:16.434  7194  7194 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-30 11:37:16.434  7194  7194 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 11:37:16.434  7194  7194 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 11:37:16.434  7194  7194 E SQLiteDatabase: 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
08-30 11:37:16.434  7194  7194 E SQLiteDatabase: 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
08-30 11:37:16.434  7194  7194 E SQLiteDatabase: 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
08-30 11:37:16.434  7194  7194 E SQLiteDatabase: 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:211)
08-30 11:37:16.434  7194  7194 E SQLiteDatabase: 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:203)
08-30 11:37:16.434  7194  7194 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 11:37:16.434  7194  7194 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 11:37:16.434  7194  7194 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 11:37:16.434  7194  7194 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 11:37:16.434  7194  7194 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 11:37:16.434  7194  7194 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-30 11:37:16.434  7194  7194 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 11:37:16.434  7194  7194 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 11:37:16.434  7194  7194 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 11:37:16.434  7194  7194 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 11:37:16.434  7194  7194 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 11:37:16.434  7194  7194 E SQLiteOpenHelper: Couldn't open local.db for writing (will try re,ad-only):
08-30 11:37:16.434  7194  7194 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 11:37:16.434  7194  7194 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 11:37:16.434  7194  7194 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-30 11:37:16.434  7194  7194 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-30 11:37:16.434  7194  7194 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-30 11:37:16.434  7194  7194 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-30 11:37:16.434  7194  7194 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-30 11:37:16.434  7194  7194 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-30 11:37:16.434  7194  7194 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-30 11:37:16.434  7194  7194 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-30 11:37:16.434  7194  7194 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-30 11:37:16.434  7194  7194 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-30 11:37:16.434  7194  7194 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 11:37:16.434  7194  7194 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 11:37:16.434  7194  7194 E SQLiteOpenHelper: 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
08-30 11:37:16.434  7194  7194 E SQLiteOpenHelper: 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
08-30 11:37:16.434  7194  7194 E SQLiteOpenHelper: 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
08-30 11:37:16.434  7194  7194 E SQLiteOpenHelper: 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:211)
08-30 11:37:16.434  7194  7194 E SQLiteOpenHelper: 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:203)
08-30 11:37:16.434  7194  7194 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 11:37:16.434  7194  7194 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 11:37:16.434  7194  7194 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 11:37:16.434  7194  7194 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 11:37:16.434  7194  7194 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 11:37:16.434  7194  7194 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
08-30 11:37:16.434  7194  7194 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 11:37:16.434  7194  7194 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 11:37:16.434  7194  7194 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 11:37:16.434  7194  7194 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 11:37:16.434  7194  7194 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 11:37:16.434  1017  1140 I ActivityManager: Killing 6670:com.android.chrome/u0a81 (adj 15): empty #31
,08-30 11:37:16.444  1017  1140 I ActivityManager: Killing 6636:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
,08-30 11:37:16.444  7194  7194 W SQLiteOpenHelper: Opened local.db in read-only mode
,08-30 11:37:16.454  6999  6999 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,08-30 11:37:16.454  7264  7297 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
08-30 11:37:16.454  7264  7297 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 11:37:16.454  7264  7297 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-30 11:37:16.454  7264  7297 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-30 11:37:16.464  7194  7331 D ContactProvider: getAllContactInfoList Start
,08-30 11:37:16.464  1017  1350 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-30 11:37:16.464  7332  7332 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 11:37:16.464  7332  7332 D ActivityThread: Added TimaKeyStore provider
,08-30 11:37:16.484  1017  1477 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-30 11:37:16.484  7264  7297 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
08-30 11:37:16.484  7264  7297 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 11:37:16.484  7264  7297 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-30 11:37:16.484  7264  7297 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 11:37:16.484  7264  7297 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.

```
