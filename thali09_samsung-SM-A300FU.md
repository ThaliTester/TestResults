#### Test 7214543121d4f5c_thali09_samsung-SM-A300FU Logs


```
--------- beginning of main
07-06 13:55:45.765   337   337 I ServiceManager: Waiting for service AtCmdFwd...
07-06 13:55:46.225   293   293 E SMD     : DCD OFF
,07-06 13:55:46.505  6692  6692 D AndroidRuntime: 
07-06 13:55:46.505  6692  6692 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-06 13:55:46.515  6692  6692 D AndroidRuntime: CheckJNI is OFF
07-06 13:55:46.515  6692  6692 D AndroidRuntime: readGMSProperty: start
07-06 13:55:46.515  6692  6692 D AndroidRuntime: readGMSProperty: already setted!!
07-06 13:55:46.515  6692  6692 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-06 13:55:46.515  6692  6692 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-06 13:55:46.515  6692  6692 D AndroidRuntime: readGMSProperty: end
07-06 13:55:46.515  6692  6692 D AndroidRuntime: addProductProperty: start
07-06 13:55:46.665  6692  6692 E AffinityControl: AffinityControl: registerfunction enter
07-06 13:55:46.685  6692  6692 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-06 13:55:46.705  1014  1302 E PersonaManagerService: inState():  stateMachine is null !!
07-06 13:55:46.705  1014  1302 I PersonaManagerService: PersonaId don't exist
07-06 13:55:46.705  1014  1302 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
07-06 13:55:46.705  1014  1302 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
07-06 13:55:46.715  1014  1302 W ActivityManager: mDVFSHelper.acquire()
07-06 13:55:46.725  1014  1302 D FocusedStackFrame: Set to : 0
07-06 13:55:46.725  1014  1044 D PhoneWindow: *FMB* installDecor mIsFloating : false
07-06 13:55:46.725  1014  1044 D PhoneWindow: *FMB* installDecor flags : -2122120936
07-06 13:55:46.735  1014  1302 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 13:55:46.735  1014  1302 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 13:55:46.735  1014  1302 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 13:55:46.735  1014  1302 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 13:55:46.745  6705  6705 E Zygote  : MountEmulatedStorage()
07-06 13:55:46.745  1014  1302 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6705 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-06 13:55:46.745  6705  6705 E Zygote  : v2
07-06 13:55:46.745  1014  1302 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
07-06 13:55:46.745  1014  1302 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-06 13:55:46.745  1014  1044 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
07-06 13:55:46.745  1014  1044 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
07-06 13:55:46.745  1014  1302 D InputDispatcher: Focused application set to: xxxx
07-06 13:55:46.745  1014  1302 D InputDispatcher: Focus left window: 1500
07-06 13:55:46.745  6705  6705 I libpersona: KNOX_SDCARD checking this for 10170
07-06 13:55:46.745  6705  6705 I libpersona: KNOX_SDCARD not a persona
07-06 13:55:46.745  6705  6705 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-06 13:55:46.745  6692  6692 D AndroidRuntime: Shutting down VM
07-06 13:55:46.745   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
07-06 13:55:46.755  6705  6705 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-06 13:55:46.755  6705  6705 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
07-06 13:55:46.765  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-06 13:55:46.765  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
07-06 13:55:46.765   337   337 I ServiceManager: Waiting for service AtCmdFwd...
07-06 13:55:46.775  6705  6705 D TimaKeyStoreProvider: TimaSignature is unavailable
07-06 13:55:46.775  6705  6705 D ActivityThread: Added TimaKeyStore provider
07-06 13:55:46.775  1014  1495 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
07-06 13:55:46.785  1014  1042 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-06 13:55:46.795  1014  1495 D PersonaManager: isKioskContainerExistOnDevice
07-06 13:55:46.805  1014  1014 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
07-06 13:55:46.835   258  6022 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
07-06 13:55:46.835   258   447 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
07-06 13:55:46.845  1500  1500 V ActivityThread: updateVisibility : ActivityRecord{23cf4227 token=android.os.BinderProxy@3644817f {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-06 13:55:46.845  1500  1500 D Launcher: onTrimMemory. Level: 20
07-06 13:55:46.915  6705  6705 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
07-06 13:55:46.925  6705  6705 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 1593-1594)
07-06 13:55:46.925  6705  6705 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-06 13:55:46.945  6705  6705 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1bfbaba}
07-06 13:55:46.945  6705  6705 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-06 13:55:46.955  6692  6692 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
07-06 13:55:46.955  6705  6705 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,07-06 13:55:46.995  6705  6705 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-06 13:55:46.995  6705  6705 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-06 13:55:46.995  6705  6705 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-06 13:55:47.025  6705  6705 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,07-06 13:55:47.025  6705  6705 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,07-06 13:55:47.025  6705  6705 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,07-06 13:55:47.025  6705  6705 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
07-06 13:55:47.025  6705  6705 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
07-06 13:55:47.025  6705  6705 I Adreno-EGL: Build Date: 04/06/15 Mon
07-06 13:55:47.025  6705  6705 I Adreno-EGL: Local Branch: 
07-06 13:55:47.025  6705  6705 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
07-06 13:55:47.025  6705  6705 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
07-06 13:55:47.025  6705  6705 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,07-06 13:55:47.235  6705  6731 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,07-06 13:55:47.285  6705  6705 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-06 13:55:47.295  1014  1039 W ActivityManager: Activity pause timeout for ActivityRecord{22373a83 u0 com.test.thalitest/.MainActivity t44}
,07-06 13:55:47.305  6705  6705 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-06 13:55:47.305  6705  6705 D PhoneWindow: *FMB* installDecor mIsFloating : false
,07-06 13:55:47.305  6705  6705 D PhoneWindow: *FMB* installDecor flags : -2139027200
,07-06 13:55:47.315  6705  6705 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-06 13:55:47.325  6705  6705 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-06 13:55:47.325  6705  6705 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-06 13:55:47.395  6705  6744 D OpenGLRenderer: Render dirty regions requested: true
,07-06 13:55:47.395  1014  1348 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,07-06 13:55:47.405  1014  1348 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-06 13:55:47.405  1014  1348 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,07-06 13:55:47.405  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,07-06 13:55:47.405  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
,07-06 13:55:47.435  6705  6705 V ActivityThread: updateVisibility : ActivityRecord{18c1210d token=android.os.BinderProxy@d9f2e37 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true,
07-06 13:55:47.435  6705  6705 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
07-06 13:55:47.435  6705  6705 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,07-06 13:55:47.445   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,07-06 13:55:47.465  1014  1499 D InputDispatcher: Focus entered window: 6705
,07-06 13:55:47.465  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-06 13:55:47.465  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,07-06 13:55:47.465  6705  6705 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,07-06 13:55:47.465  6705  6744 I OpenGLRenderer: Initialized EGL, version 1.4
,07-06 13:55:47.475  6705  6744 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,07-06 13:55:47.475  6705  6744 D OpenGLRenderer: Enabling debug mode 0
,07-06 13:55:47.505  1014  1027 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-06 13:55:47.515  1172  1172 I StatusBar: Icon Only
07-06 13:55:47.515  1172  1172 D PanelView: There is/are notification(s) 
,07-06 13:55:47.525  1014  6747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,07-06 13:55:47.525  1014  1044 I ActivityManager: Displayed Component not be shown by security: +728ms (total +2m17s747ms)
,07-06 13:55:47.525  1014  1044 W ActivityManager: mDVFSHelper.release()
,07-06 13:55:47.525  1014  1044 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{22373a83 u0 com.test.thalitest/.MainActivity t44} time:252198
,07-06 13:55:47.535  6705  6705 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,07-06 13:55:47.535  6705  6705 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@d9f2e37 time:252203
07-06 13:55:47.535   258   447 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
07-06 13:55:47.535   258   447 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,07-06 13:55:47.565  1872  1872 I SamsungIME: getCurrentCandidateView
,07-06 13:55:47.625  6705  6705 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6705
,07-06 13:55:47.695  1872  1872 D SamsungIME: Dismiss ExpandCandiate
,07-06 13:55:47.745  6705  6705 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-06 13:55:47.765   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 13:55:47.855  1872  1872 I SamsungIME: getDebugLevel  : 0x4f4c
,07-06 13:55:47.915  1872  1872 I SamsungIME: getDebugLevel  : 0x4f4c
,07-06 13:55:47.935  1872  1872 I SamsungIME: KeybaordView init() : load resources
,07-06 13:55:47.955  6705  6748 D jxcore_app_log: JniHelper::setJavaVM(0xb7b372f0), pthread_self() = -1207291552
,07-06 13:55:47.955  1872  1872 I SamsungIME: getCurrentKeyboard
07-06 13:55:47.955  1872  1872 I SamsungIME: getTextKeyboard
,07-06 13:55:47.965  6705  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-06 13:55:47.965  6705  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-06 13:55:47.965  6705  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-06 13:55:47.965  6705  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-06 13:55:47.965  6705  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-06 13:55:47.965  6705  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc9677d added. We now have 1 listener(s)
,07-06 13:55:47.965  6705  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,07-06 13:55:47.965  6705  6748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
07-06 13:55:47.975  6705  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-06 13:55:47.975  6705  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-06 13:55:47.975  6705  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-06 13:55:47.975  6705  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-06 13:55:47.975  6705  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-06 13:55:47.975  6705  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
07-06 13:55:47.975  6705  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-06 13:55:47.975  6705  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-06 13:55:47.975  6705  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-06 13:55:47.975  6705  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-06 13:55:47.975  6705  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-06 13:55:47.975  6705  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-06 13:55:47.975  6705  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-06 13:55:47.975  6705  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16731f40 added. We now have 1 listener(s)
07-06 13:55:47.975  6705  6748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-06 13:55:47.985  1872  1872 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,07-06 13:55:47.995  6705  6748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,07-06 13:55:47.995  6705  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-06 13:55:47.995  6705  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-06 13:55:47.995  6705  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-06 13:55:47.995  6705  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-06 13:55:48.005  6705  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-06 13:55:48.005  6705  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,07-06 13:55:48.015  6705  6748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-06 13:55:48.015  6705  6748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-06 13:55:48.015  6705  6748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-06 13:55:48.015  6705  6748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-06 13:55:48.015  6705  6748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-06 13:55:48.015  6705  6748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-06 13:55:48.015  6705  6748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-06 13:55:48.015  6705  6748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-06 13:55:48.015  6705  6748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-06 13:55:48.015  6705  6748 D io.jxcore.node.ConnectivityMonitor: start: OK
07-06 13:55:48.015  6705  6748 I io.jxcore.node.LifeCycleMonitor: start: OK
07-06 13:55:48.015  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-06 13:55:48.015  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-06 13:55:48.055  6705  6705 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-06 13:55:48.465  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 13:55:48.525  6705  6755 W jxcore-log: Initializing JXcore engine
07-06 13:55:48.525  6705  6755 W jxcore-log: JXcore engine is ready
,07-06 13:55:48.575  2020  2020 E audit   : type=1400 msg=audit(1467806148.575:205): avc:  denied  { ioctl } for  pid=6755 comm="Thread-1199" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-06 13:55:48.575  2020  2020 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
07-06 13:55:48.575  2020  2020 E audit   : type=1300 msg=audit(1467806148.575:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=9f5008f8 items=0 ppid=311 ppcomm=main pid=6755 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1199" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
07-06 13:55:48.575  2020  2020 E audit   : type=1320 msg=audit(1467806148.575:205): 
,07-06 13:55:48.595  6705  6755 W jxcore-log: Starting JXcore engine
,07-06 13:55:48.695  6705  6755 W jxcore-log: Platform android,
07-06 13:55:48.695  6705  6755 W jxcore-log: 
07-06 13:55:48.695  6705  6755 W jxcore-log: Process ARCH arm
07-06 13:55:48.695  6705  6755 W jxcore-log: 
,07-06 13:55:48.775   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 13:55:48.905  6705  6755 I jxcore-log: JXcore Cordova bridge is ready!
07-06 13:55:48.905  6705  6755 I jxcore-log: 
,07-06 13:55:48.905  6705  6755 W jxcore-log: JXcore engine is started
,07-06 13:55:48.905  6705  6748 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-06 13:55:48.905  6705  6705 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-06 13:55:49.225   293   293 E SMD     : DCD OFF,
,07-06 13:55:49.775   337   337 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,07-06 13:55:52.225   293   293 E SMD     : DCD OFF
,07-06 13:55:52.385  1014  1514 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 13:55:52.385  1014  1514 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,07-06 13:55:52.385  1014  1514 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-06 13:55:52.385  1014  1514 D BatteryService: stay LED for fully charged
07-06 13:55:52.385  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 13:55:52.395  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 13:55:52.395  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 13:55:52.395  1014  1014 I MotionRecognitionService: Plugged
,07-06 13:55:52.395  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,07-06 13:55:52.395  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,07-06 13:55:52.395  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-06 13:55:52.405  3340  3340 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 13:55:52.405  3340  3435 D HeadsetStateMachine: Disconnected process message: 10
,07-06 13:55:52.415  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,07-06 13:55:52.415  1172  1172 D SViewCoverView: level :100 plugged : 2
,07-06 13:55:52.425  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 13:55:52.425  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 13:55:52.425  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 13:55:53.125  1014  1301 E Watchdog: !@Sync 8,
,07-06 13:55:55.225   293   293 E SMD     : DCD OFF
,07-06 13:55:56.785  1014  1054 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,07-06 13:55:57.915  1014  3534 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 13:55:58.225   293   293 E SMD     : DCD OFF
,07-06 13:55:58.495  1014  3464 D SSRM:n  : SIOP:: AP = 300
,07-06 13:55:59.995  1014  1092 V AlarmManager: waitForAlarm result :8
,07-06 13:56:01.225   293   293 E SMD     : DCD OFF
,07-06 13:56:01.805  6705  6755 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
07-06 13:56:01.805  6705  6755 I jxcore-log: 
,07-06 13:56:01.805  6705  6755 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
07-06 13:56:01.805  6705  6755 I jxcore-log: 
,07-06 13:56:01.815  6705  6755 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-06 13:56:01.815  6705  6755 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-06 13:56:01.815  6705  6755 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-06 13:56:01.815  6705  6755 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-06 13:56:01.815  6705  6755 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-06 13:56:01.815  6705  6755 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-06 13:56:01.815  6705  6755 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-06 13:56:01.815  6705  6755 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-06 13:56:01.815  6705  6755 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-06 13:56:01.815  6705  6755 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-06 13:56:01.815  6705  6755 I jxcore-log: 
,07-06 13:56:01.825  6705  6755 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-06 13:56:01.825  6705  6755 I jxcore-log: 
,07-06 13:56:02.265  6705  6755 I jxcore-log: Unit Test app is loaded,
07-06 13:56:02.265  6705  6755 I jxcore-log: 
,07-06 13:56:02.275  6705  6755 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
07-06 13:56:02.275  6705  6755 I jxcore-log: 
,07-06 13:56:02.275  6705  6755 I jxcore-log: My device name is: samsung-SM-A300FU
07-06 13:56:02.275  6705  6755 I jxcore-log: 
,07-06 13:56:02.275  6705  6705 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-06 13:56:02.275  6705  6755 I jxcore-log: WARN testUtils: myNameCallback not set!
07-06 13:56:02.275  6705  6755 I jxcore-log: 
,07-06 13:56:02.445  1014  3882 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 13:56:04.225   293   293 E SMD     : DCD OFF
,07-06 13:56:04.775   337   337 I ServiceManager: Waiting for service AtCmdFwd...,
,07-06 13:56:05.775   337   337 I ServiceManager: Waiting for service AtCmdFwd...,
,07-06 13:56:06.775   337   337 I ServiceManager: Waiting for service AtCmdFwd...,
,07-06 13:56:07.225   293   293 E SMD     : DCD OFF,
,07-06 13:56:07.445  6705  6755 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js,
07-06 13:56:07.445  6705  6755 I jxcore-log: 
,07-06 13:56:07.775   337   337 I ServiceManager: Waiting for service AtCmdFwd...,
,07-06 13:56:07.945  6705  6755 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js,
07-06 13:56:07.945  6705  6755 I jxcore-log: 
,07-06 13:56:07.975  6705  6755 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js,
07-06 13:56:07.975  6705  6755 I jxcore-log: 
,07-06 13:56:07.985  6705  6755 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js,
07-06 13:56:07.985  6705  6755 I jxcore-log: 
,07-06 13:56:08.005  6705  6755 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js,
07-06 13:56:08.005  6705  6755 I jxcore-log: 
,07-06 13:56:08.005  6705  6755 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js,
07-06 13:56:08.005  6705  6755 I jxcore-log: 
,07-06 13:56:08.525  1014  3464 D SSRM:n  : SIOP:: AP = 310
,07-06 13:56:08.775   337   337 I ServiceManager: Waiting for service AtCmdFwd...,
,07-06 13:56:09.775   337   337 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,07-06 13:56:10.235   293   293 E SMD     : DCD OFF
,07-06 13:56:10.605  6705  6755 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js,
07-06 13:56:10.605  6705  6755 I jxcore-log: 
,07-06 13:56:10.615  6705  6755 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js,
07-06 13:56:10.615  6705  6755 I jxcore-log: 
,07-06 13:56:10.625  6705  6755 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js,
07-06 13:56:10.625  6705  6755 I jxcore-log: 
,07-06 13:56:10.835  6705  6755 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js,
07-06 13:56:10.835  6705  6755 I jxcore-log: 
,07-06 13:56:10.945  6705  6755 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js,
07-06 13:56:10.945  6705  6755 I jxcore-log: 
,07-06 13:56:11.015  6705  6755 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js,
07-06 13:56:11.015  6705  6755 I jxcore-log: 
,07-06 13:56:11.025  6705  6755 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js,
07-06 13:56:11.025  6705  6755 I jxcore-log: 
,07-06 13:56:11.275  6705  6755 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js,
07-06 13:56:11.275  6705  6755 I jxcore-log: 
,07-06 13:56:11.305  6705  6755 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js,
07-06 13:56:11.305  6705  6755 I jxcore-log: 
,07-06 13:56:11.305  6705  6755 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js,
07-06 13:56:11.305  6705  6755 I jxcore-log: 
,07-06 13:56:11.315  6705  6755 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js,
07-06 13:56:11.315  6705  6755 I jxcore-log: 
,07-06 13:56:11.335  6705  6755 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js,
07-06 13:56:11.335  6705  6755 I jxcore-log: 
,07-06 13:56:11.355  6705  6755 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js,
07-06 13:56:11.355  6705  6755 I jxcore-log: 
,07-06 13:56:11.465  6705  6755 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js,
07-06 13:56:11.465  6705  6755 I jxcore-log: 
,07-06 13:56:11.475  6705  6755 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js,
07-06 13:56:11.475  6705  6755 I jxcore-log: 
,07-06 13:56:11.505  6705  6755 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js,
07-06 13:56:11.505  6705  6755 I jxcore-log: 
,07-06 13:56:11.515  6705  6755 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,07-06 13:56:11.515  6705  6755 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
07-06 13:56:11.515  6705  6755 I jxcore-log: 
,07-06 13:56:12.515  1014  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 13:56:12.515  1014  1348 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-06 13:56:12.515  1014  1348 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-06 13:56:12.515  1014  1348 D BatteryService: stay LED for fully charged
,07-06 13:56:12.515  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 13:56:12.525  1014  1014 I MotionRecognitionService: Plugged
,07-06 13:56:12.525  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
07-06 13:56:12.525  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-06 13:56:12.525  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 13:56:12.535  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,07-06 13:56:12.535  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-06 13:56:12.535  3340  3340 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 13:56:12.535  3340  3435 D HeadsetStateMachine: Disconnected process message: 10
,07-06 13:56:12.555  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,07-06 13:56:12.555  1172  1172 D SViewCoverView: level :100 plugged : 2
07-06 13:56:12.555  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 13:56:12.555  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 13:56:12.555  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 13:56:13.235   293   293 E SMD     : DCD OFF
,07-06 13:56:16.235   293   293 E SMD     : DCD OFF
,07-06 13:56:17.915  1014  3534 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 13:56:18.555  1014  3464 D SSRM:n  : SIOP:: AP = 300
,07-06 13:56:19.235   293   293 E SMD     : DCD OFF
,07-06 13:56:22.235   293   293 E SMD     : DCD OFF
,07-06 13:56:22.585  1014  1133 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-06 13:56:23.035  1014  1046 I PowerManagerService: [PWL] Off : 225s ago,
,07-06 13:56:23.125  1014  1301 E Watchdog: !@Sync 9,
,07-06 13:56:25.235   293   293 E SMD     : DCD OFF,
,07-06 13:56:28.235   293   293 E SMD     : DCD OFF,
,07-06 13:56:28.565  1014  3464 D SSRM:n  : SIOP:: AP = 290
,07-06 13:56:29.775   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 13:56:30.775   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 13:56:31.245   293   293 E SMD     : DCD OFF
,07-06 13:56:31.775   337   337 I ServiceManager: Waiting for service AtCmdFwd...,
,07-06 13:56:32.645  1014  1535 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 13:56:32.775   337   337 I ServiceManager: Waiting for service AtCmdFwd...,
,07-06 13:56:33.775   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 13:56:34.245   293   293 E SMD     : DCD OFF,
,07-06 13:56:34.775   337   337 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-06 13:56:37.245   293   293 E SMD     : DCD OFF,
,07-06 13:56:37.915  1014  3534 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 13:56:38.585  1014  3464 D SSRM:n  : SIOP:: AP = 290
,07-06 13:56:40.245   293   293 E SMD     : DCD OFF
,07-06 13:56:42.705  1014  1536 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-06 13:56:43.245   293   293 E SMD     : DCD OFF
,07-06 13:56:46.245   293   293 E SMD     : DCD OFF
,07-06 13:56:48.595  1014  3464 D SSRM:n  : SIOP:: AP = 290
,07-06 13:56:49.245   293   293 E SMD     : DCD OFF
,07-06 13:56:50.845  1014  1083 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-06 13:56:50.845  1014  1083 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-06 13:56:50.845  1014  1082 D TimaService: TimaServiceHandler.handleMessage what =1
,07-06 13:56:50.855  1014  1083 I TLC_TIMA_PKM_initialize: initializing...
,07-06 13:56:50.855  1014  1083 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
07-06 13:56:50.855  1014  1083 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
,07-06 13:56:50.855  1014  1083 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
07-06 13:56:50.855  1014  1083 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
07-06 13:56:50.855  1014  1083 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
,07-06 13:56:50.855  1014  1083 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
07-06 13:56:50.855  1014  1083 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
07-06 13:56:50.855  1014  1083 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
,07-06 13:56:50.855  1014  1083 D QSEECOMAPI: : App is not loaded in QSEE
,07-06 13:56:50.885  1014  1083 D QSEECOMAPI: : Loaded image: APP id = 11
,07-06 13:56:50.885  1014  1083 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,07-06 13:56:50.895  1014  1083 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,07-06 13:56:52.255   293   293 E SMD     : DCD OFF
,07-06 13:56:52.775  1014  3881 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-06 13:56:52.805  1014  1083 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-06 13:56:52.805  1014  1083 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-06 13:56:52.805  1014  1083 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-06 13:56:52.815  1014  1083 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-06 13:56:53.125  1014  1301 E Watchdog: !@Sync 10,
,07-06 13:56:55.255   293   293 E SMD     : DCD OFF
,07-06 13:56:57.915  1014  3534 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 13:56:58.255   293   293 E SMD     : DCD OFF
,07-06 13:56:58.605  1014  3464 D SSRM:n  : SIOP:: AP = 290
,07-06 13:56:59.775   337   337 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-06 13:56:59.775   337   337 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-06 13:57:01.255   293   293 E SMD     : DCD OFF
,07-06 13:57:02.835  1014  1514 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 13:57:02.835  1014  1514 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,07-06 13:57:02.835  1014  1514 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-06 13:57:02.845  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-06 13:57:02.845  1014  1514 D BatteryService: stay LED for fully charged
07-06 13:57:02.845  1014  1014 I MotionRecognitionService: Plugged
07-06 13:57:02.845  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,07-06 13:57:02.845  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-06 13:57:02.845  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 13:57:02.845  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-06 13:57:02.845  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-06 13:57:02.855  3340  3340 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-06 13:57:02.865  3340  3435 D HeadsetStateMachine: Disconnected process message: 10
,07-06 13:57:02.875  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,07-06 13:57:02.875  1172  1172 D SViewCoverView: level :100 plugged : 2
,07-06 13:57:02.875  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 13:57:02.875  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 13:57:02.875  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 13:57:04.255   293   293 E SMD     : DCD OFF
,07-06 13:57:07.255   293   293 E SMD     : DCD OFF
,07-06 13:57:08.635  1014  3464 D SSRM:n  : SIOP:: AP = 290
,07-06 13:57:10.255   293   293 E SMD     : DCD OFF
,07-06 13:57:12.905  1014  4014 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 13:57:12.905  1014  4014 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-06 13:57:12.905  1014  4014 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-06 13:57:12.905  1014  4014 D BatteryService: stay LED for fully charged
07-06 13:57:12.905  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 13:57:12.915  1014  1014 I MotionRecognitionService: Plugged
07-06 13:57:12.915  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,07-06 13:57:12.915  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 13:57:12.915  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 13:57:12.915  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,07-06 13:57:12.915  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-06 13:57:12.925  3340  3340 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 13:57:12.925  3340  3435 D HeadsetStateMachine: Disconnected process message: 10
,07-06 13:57:12.945  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,07-06 13:57:12.945  1172  1172 D SViewCoverView: level :100 plugged : 2
,07-06 13:57:12.945  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 13:57:12.945  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 13:57:12.945  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 13:57:13.035  1014  1046 I PowerManagerService: [PWL] Off : 275s ago
,07-06 13:57:13.265   293   293 E SMD     : DCD OFF
,07-06 13:57:14.775   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 13:57:15.775   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 13:57:16.265   293   293 E SMD     : DCD OFF
,07-06 13:57:16.775   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 13:57:17.775   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 13:57:17.915  1014  3534 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 13:57:18.655  1014  3464 D SSRM:n  : SIOP:: AP = 290
,07-06 13:57:18.775   337   337 I ServiceManager: Waiting for service AtCmdFwd...,
,07-06 13:57:19.265   293   293 E SMD     : DCD OFF
,07-06 13:57:19.775   337   337 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,07-06 13:57:22.265   293   293 E SMD     : DCD OFF
,07-06 13:57:22.975  1014  3881 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 13:57:22.975  1014  3881 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-06 13:57:22.975  1014  3881 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-06 13:57:22.975  1014  3881 D BatteryService: stay LED for fully charged
,07-06 13:57:22.975  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 13:57:22.975  1014  1014 I MotionRecognitionService: Plugged,
07-06 13:57:22.975  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
07-06 13:57:22.985  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 13:57:22.985  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
07-06 13:57:22.985  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-06 13:57:22.985  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-06 13:57:22.995  3340  3340 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-06 13:57:22.995  3340  3435 D HeadsetStateMachine: Disconnected process message: 10
,07-06 13:57:23.005  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,07-06 13:57:23.005  1172  1172 D SViewCoverView: level :100 plugged : 2
,07-06 13:57:23.005  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 13:57:23.005  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 13:57:23.005  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 13:57:23.125  1014  1301 E Watchdog: !@Sync 11,
,07-06 13:57:24.775   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 13:57:25.265   293   293 E SMD     : DCD OFF
,07-06 13:57:25.785   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 13:57:26.785   337   337 I ServiceManager: Waiting for service AtCmdFwd...,
,07-06 13:57:27.785   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 13:57:28.265   293   293 E SMD     : DCD OFF
,07-06 13:57:28.685  1014  3464 D SSRM:n  : SIOP:: AP = 290
,07-06 13:57:28.785   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 13:57:29.785   337   337 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,07-06 13:57:31.265   293   293 E SMD     : DCD OFF
,07-06 13:57:33.035  1014  1302 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 13:57:34.265   293   293 E SMD     : DCD OFF
,07-06 13:57:35.305  1014  3882 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
07-06 13:57:35.305  1014  3882 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,07-06 13:57:35.315  2030  2030 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-06 13:57:35.315  1014  1499 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,07-06 13:57:35.315  1014  1499 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,07-06 13:57:35.325  1014  1499 W ActivityManager: userId = 0, bbcId = -10000
,07-06 13:57:35.325  1014  1499 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-06 13:57:35.325  1014  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-06 13:57:35.325  2030  2030 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-06 13:57:35.325  2030  2030 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-06 13:57:35.355  1014  1348 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-06 13:57:35.355  1014  1348 W ActivityManager: userId = 0, bbcId = -10000
,07-06 13:57:35.355  1014  1348 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-06 13:57:35.355  1014  1348 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-06 13:57:35.365  5947  5981 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-06 13:57:35.375   278   972 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
07-06 13:57:35.375   278   972 D Netd    : getNetworkForDns: using netid 502 for uid 10026
,07-06 13:57:35.415  5947  5981 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,07-06 13:57:37.275   293   293 E SMD     : DCD OFF
,07-06 13:57:37.925  1014  3534 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 13:57:38.715  1014  3464 D SSRM:n  : SIOP:: AP = 290
,07-06 13:57:39.785   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 13:57:40.275   293   293 E SMD     : DCD OFF
,07-06 13:57:40.785   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 13:57:41.785   337   337 I ServiceManager: Waiting for service AtCmdFwd...,
,07-06 13:57:42.785   337   337 I ServiceManager: Waiting for service AtCmdFwd...,
,07-06 13:57:43.105  1014  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 13:57:43.275   293   293 E SMD     : DCD OFF
,07-06 13:57:43.785   337   337 I ServiceManager: Waiting for service AtCmdFwd...,
,07-06 13:57:44.785   337   337 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,07-06 13:57:46.275   293   293 E SMD     : DCD OFF
,07-06 13:57:48.725  1014  3464 D SSRM:n  : SIOP:: AP = 290
,07-06 13:57:49.275   293   293 E SMD     : DCD OFF
,07-06 13:57:52.275   293   293 E SMD     : DCD OFF
,07-06 13:57:53.125  1014  1301 E Watchdog: !@Sync 12
,07-06 13:57:53.175  1014  3882 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 13:57:55.275   293   293 E SMD     : DCD OFF
,07-06 13:57:57.925  1014  3534 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,07-06 13:57:58.275   293   293 E SMD     : DCD OFF,
,07-06 13:57:58.745  1014  3464 D SSRM:n  : SIOP:: AP = 290
,07-06 13:57:59.785   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 13:58:00.785   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 13:58:01.285   293   293 E SMD     : DCD OFF
,07-06 13:58:01.785   337   337 I ServiceManager: Waiting for service AtCmdFwd...,
,07-06 13:58:02.785   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 13:58:03.235  1014  1535 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 13:58:03.235  1014  1535 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,07-06 13:58:03.235  1014  1535 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-06 13:58:03.235  1014  1535 D BatteryService: stay LED for fully charged
07-06 13:58:03.235  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-06 13:58:03.245  1014  1014 I MotionRecognitionService: Plugged
07-06 13:58:03.245  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
07-06 13:58:03.245  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-06 13:58:03.245  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
07-06 13:58:03.245  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-06 13:58:03.245  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
07-06 13:58:03.255  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-06 13:58:03.255  1172  1172 D SViewCoverView: level :100 plugged : 2
07-06 13:58:03.255  3340  3340 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-06 13:58:03.255  3340  3435 D HeadsetStateMachine: Disconnected process message: 10
,07-06 13:58:03.275  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 13:58:03.275  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 13:58:03.275  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 13:58:03.785   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 13:58:04.285   293   293 E SMD     : DCD OFF
,07-06 13:58:04.785   337   337 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-06 13:58:07.285   293   293 E SMD     : DCD OFF
,07-06 13:58:08.035  1014  1046 I PowerManagerService: [PWL] Off : 330s ago
,07-06 13:58:08.755  1014  3464 D SSRM:n  : SIOP:: AP = 290
,07-06 13:58:10.285   293   293 E SMD     : DCD OFF
,07-06 13:58:13.285   293   293 E SMD     : DCD OFF
,07-06 13:58:13.305  1014  1026 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 13:58:13.305  1014  1026 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,07-06 13:58:13.305  1014  1026 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-06 13:58:13.305  1014  1026 D BatteryService: stay LED for fully charged
07-06 13:58:13.305  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
07-06 13:58:13.305  1014  1014 I MotionRecognitionService: Plugged
07-06 13:58:13.305  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
07-06 13:58:13.315  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 13:58:13.315  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
07-06 13:58:13.315  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-06 13:58:13.315  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-06 13:58:13.315  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
07-06 13:58:13.315  3340  3340 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-06 13:58:13.315  1172  1172 D SViewCoverView: level :100 plugged : 2
,07-06 13:58:13.315  3340  3435 D HeadsetStateMachine: Disconnected process message: 10
,07-06 13:58:13.335  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 13:58:13.335  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 13:58:13.335  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 13:58:16.285   293   293 E SMD     : DCD OFF
,07-06 13:58:17.925  1014  3534 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 13:58:18.765  1014  3464 D SSRM:n  : SIOP:: AP = 290
,07-06 13:58:19.285   293   293 E SMD     : DCD OFF
,07-06 13:58:22.295   293   293 E SMD     : DCD OFF
,07-06 13:58:23.125  1014  1301 E Watchdog: !@Sync 13
,07-06 13:58:23.365  1014  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 13:58:24.785   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 13:58:25.295   293   293 E SMD     : DCD OFF
,07-06 13:58:25.785   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 13:58:26.785   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 13:58:27.785   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 13:58:28.295   293   293 E SMD     : DCD OFF
,07-06 13:58:28.785  1014  3464 D SSRM:n  : SIOP:: AP = 290
,07-06 13:58:28.785   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 13:58:29.785   337   337 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-06 13:58:31.295   293   293 E SMD     : DCD OFF
,07-06 13:58:33.435  1014  1514 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 13:58:33.435  1014  1514 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-06 13:58:33.435  1014  1514 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-06 13:58:33.435  1014  1514 D BatteryService: stay LED for fully charged
07-06 13:58:33.435  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 13:58:33.435  1014  1014 I MotionRecognitionService: Plugged
,07-06 13:58:33.435  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,07-06 13:58:33.435  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-06 13:58:33.445  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-06 13:58:33.435  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
07-06 13:58:33.445  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-06 13:58:33.455  3340  3340 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-06 13:58:33.455  3340  3435 D HeadsetStateMachine: Disconnected process message: 10
,07-06 13:58:33.465  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
07-06 13:58:33.465  1172  1172 D SViewCoverView: level :100 plugged : 2
07-06 13:58:33.465  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 13:58:33.465  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 13:58:33.465  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 13:58:34.295   293   293 E SMD     : DCD OFF
,07-06 13:58:37.295   293   293 E SMD     : DCD OFF
,07-06 13:58:37.925  1014  3534 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 13:58:38.795  1014  3464 D SSRM:n  : SIOP:: AP = 290
,07-06 13:58:40.295   293   293 E SMD     : DCD OFF
,07-06 13:58:43.295   293   293 E SMD     : DCD OFF
,07-06 13:58:43.495  1014  4014 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 13:58:43.495  1014  4014 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,07-06 13:58:43.495  1014  4014 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-06 13:58:43.495  1014  4014 D BatteryService: stay LED for fully charged
,07-06 13:58:43.495  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 13:58:43.505  1014  1014 I MotionRecognitionService: Plugged
,07-06 13:58:43.505  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
07-06 13:58:43.505  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-06 13:58:43.505  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 13:58:43.505  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
07-06 13:58:43.505  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,07-06 13:58:43.515  3340  3340 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 13:58:43.515  3340  3435 D HeadsetStateMachine: Disconnected process message: 10
,07-06 13:58:43.525  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,07-06 13:58:43.525  1172  1172 D SViewCoverView: level :100 plugged : 2
,07-06 13:58:43.525  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 13:58:43.525  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 13:58:43.535  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 13:58:46.305   293   293 E SMD     : DCD OFF
,07-06 13:58:48.805  1014  3464 D SSRM:n  : SIOP:: AP = 290
,07-06 13:58:49.305   293   293 E SMD     : DCD OFF
,07-06 13:58:52.305   293   293 E SMD     : DCD OFF
,07-06 13:58:53.125  1014  1301 E Watchdog: !@Sync 14
,07-06 13:58:53.565  1014  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 13:58:54.785   337   337 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-06 13:58:54.785   337   337 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-06 13:58:55.305   293   293 E SMD     : DCD OFF
,07-06 13:58:57.925  1014  3534 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 13:58:58.305   293   293 E SMD     : DCD OFF
,07-06 13:58:58.825  1014  3464 D SSRM:n  : SIOP:: AP = 290
,07-06 13:58:59.995  1014  1092 V AlarmManager: waitForAlarm result :8
07-06 13:58:59.995  1014  1092 V AlarmManager: No more alarm at this time.nowELAPSED=444661 batch.start=797650
,07-06 13:58:59.995  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK,
07-06 13:58:59.995  1172  1172 D KeyguardUpdateMonitor: handleTimeUpdate
,07-06 13:59:00.015  1172  1172 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-06 13:59:00.015  1172  1172 D SecKeyguardClockView: HomeTimezone(): 1
,07-06 13:59:00.015  1172  1172 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-06 13:59:00.015  1172  1172 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
07-06 13:59:00.015  1172  1172 I KeyguardEffectViewController: *** don't update sliding image ***
,07-06 13:59:00.025  1172  1172 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,07-06 13:59:00.065  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-06 13:59:00.065  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-06 13:59:00.065  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-06 13:59:00.085  1172  1172 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-06 13:59:01.305   293   293 E SMD     : DCD OFF
,07-06 13:59:03.625  1014  1514 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 13:59:04.305   293   293 E SMD     : DCD OFF
,07-06 13:59:07.315   293   293 E SMD     : DCD OFF
,07-06 13:59:08.045  1014  1046 I PowerManagerService: [PWL] Off : 390s ago
,07-06 13:59:08.835  1014  3464 D SSRM:n  : SIOP:: AP = 290
,07-06 13:59:10.315   293   293 E SMD     : DCD OFF
,07-06 13:59:13.315   293   293 E SMD     : DCD OFF
,07-06 13:59:13.695  1014  3882 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-06 13:59:13.695  1014  3882 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-06 13:59:13.695  1014  3882 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-06 13:59:13.695  1014  3882 D BatteryService: stay LED for fully charged
07-06 13:59:13.695  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 13:59:13.695  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-06 13:59:13.695  1014  1014 I MotionRecognitionService: Plugged
07-06 13:59:13.695  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
07-06 13:59:13.695  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,07-06 13:59:13.705  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
,07-06 13:59:13.705  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-06 13:59:13.715  3340  3340 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-06 13:59:13.715  3340  3435 D HeadsetStateMachine: Disconnected process message: 10
,07-06 13:59:13.725  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,07-06 13:59:13.725  1172  1172 D SViewCoverView: level :100 plugged : 2
,07-06 13:59:13.725  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 13:59:13.725  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 13:59:13.725  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 13:59:14.795   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 13:59:15.795   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 13:59:16.315   293   293 E SMD     : DCD OFF
,07-06 13:59:16.795   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 13:59:17.795   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 13:59:17.925  1014  3534 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 13:59:18.795   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 13:59:18.845  1014  3464 D SSRM:n  : SIOP:: AP = 290
,07-06 13:59:19.315   293   293 E SMD     : DCD OFF
,07-06 13:59:19.795   337   337 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,07-06 13:59:22.315   293   293 E SMD     : DCD OFF
,07-06 13:59:23.125  1014  1301 E Watchdog: !@Sync 15
,07-06 13:59:23.755  1014  1302 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 13:59:24.795   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 13:59:25.315   293   293 E SMD     : DCD OFF
,07-06 13:59:25.795   337   337 I ServiceManager: Waiting for service AtCmdFwd...,
,07-06 13:59:26.795   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 13:59:27.795   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 13:59:28.315   293   293 E SMD     : DCD OFF
,07-06 13:59:28.795   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 13:59:28.865  1014  3464 D SSRM:n  : SIOP:: AP = 290
,07-06 13:59:29.795   337   337 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,07-06 13:59:31.325   293   293 E SMD     : DCD OFF
,07-06 13:59:33.815  1014  4014 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-06 13:59:34.325   293   293 E SMD     : DCD OFF
,07-06 13:59:37.325   293   293 E SMD     : DCD OFF
,07-06 13:59:37.925  1014  3534 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 13:59:38.875  1014  3464 D SSRM:n  : SIOP:: AP = 290
,07-06 13:59:39.795   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 13:59:40.325   293   293 E SMD     : DCD OFF
,07-06 13:59:40.795   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 13:59:41.795   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 13:59:42.335   332   332 I bootchecker: bootchecker wake up!!,
,07-06 13:59:42.795   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 13:59:43.325   293   293 E SMD     : DCD OFF
,07-06 13:59:43.795   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 13:59:43.885  1014  1133 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 13:59:44.795   337   337 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,07-06 13:59:46.325   293   293 E SMD     : DCD OFF
,07-06 13:59:48.885  1014  3464 D SSRM:n  : SIOP:: AP = 290
,07-06 13:59:49.325   293   293 E SMD     : DCD OFF
,07-06 13:59:52.325   293   293 E SMD     : DCD OFF
,07-06 13:59:53.125  1014  1301 E Watchdog: !@Sync 16
,07-06 13:59:53.945  1014  3881 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-06 13:59:55.335   293   293 E SMD     : DCD OFF
,07-06 13:59:57.925  1014  3534 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 13:59:58.335   293   293 E SMD     : DCD OFF
,07-06 13:59:58.905  1014  3464 D SSRM:n  : SIOP:: AP = 290
,07-06 13:59:59.795   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 13:59:59.995  1014  1092 V AlarmManager: waitForAlarm result :8
,07-06 14:00:00.795   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 14:00:01.335   293   293 E SMD     : DCD OFF
,07-06 14:00:01.795   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 14:00:02.795   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 14:00:03.795   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 14:00:04.015  1014  1498 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:00:04.335   293   293 E SMD     : DCD OFF
,07-06 14:00:04.795   337   337 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-06 14:00:07.335   293   293 E SMD     : DCD OFF
,07-06 14:00:08.935  1014  3464 D SSRM:n  : SIOP:: AP = 290
,07-06 14:00:10.335   293   293 E SMD     : DCD OFF
,07-06 14:00:13.045  1014  1046 I PowerManagerService: [PWL] Off : 455s ago
,07-06 14:00:13.335   293   293 E SMD     : DCD OFF
,07-06 14:00:14.075  1014  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:00:16.345   293   293 E SMD     : DCD OFF
,07-06 14:00:17.925  1014  3534 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 14:00:18.965  1014  3464 D SSRM:n  : SIOP:: AP = 290
,07-06 14:00:19.345   293   293 E SMD     : DCD OFF
,07-06 14:00:22.345   293   293 E SMD     : DCD OFF
,07-06 14:00:23.125  1014  1301 E Watchdog: !@Sync 17
,07-06 14:00:24.145  1014  1535 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:00:24.805   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 14:00:25.345   293   293 E SMD     : DCD OFF
,07-06 14:00:25.805   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 14:00:26.805   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 14:00:27.805   337   337 I ServiceManager: Waiting for service AtCmdFwd...,
,07-06 14:00:28.345   293   293 E SMD     : DCD OFF
,07-06 14:00:28.805   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 14:00:28.985  1014  3464 D SSRM:n  : SIOP:: AP = 280
,07-06 14:00:29.805   337   337 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-06 14:00:31.345   293   293 E SMD     : DCD OFF
,07-06 14:00:34.205  1014  1302 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:00:34.345   293   293 E SMD     : DCD OFF
,07-06 14:00:37.345   293   293 E SMD     : DCD OFF
,07-06 14:00:37.935  1014  3534 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,07-06 14:00:38.995  1014  3464 D SSRM:n  : SIOP:: AP = 290
,07-06 14:00:40.355   293   293 E SMD     : DCD OFF
,07-06 14:00:43.355   293   293 E SMD     : DCD OFF
,07-06 14:00:44.275  1014  4014 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:00:46.355   293   293 E SMD     : DCD OFF
,07-06 14:00:49.025  1014  3464 D SSRM:n  : SIOP:: AP = 280
,07-06 14:00:49.355   293   293 E SMD     : DCD OFF
,07-06 14:00:52.355   293   293 E SMD     : DCD OFF
,07-06 14:00:53.125  1014  1301 E Watchdog: !@Sync 18
,07-06 14:00:54.335  1014  1133 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:00:54.805   337   337 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-06 14:00:54.805   337   337 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-06 14:00:55.355   293   293 E SMD     : DCD OFF
,07-06 14:00:57.935  1014  3534 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 14:00:58.355   293   293 E SMD     : DCD OFF
,07-06 14:00:59.055  1014  3464 D SSRM:n  : SIOP:: AP = 280
,07-06 14:01:01.355   293   293 E SMD     : DCD OFF
,07-06 14:01:04.365   293   293 E SMD     : DCD OFF
,07-06 14:01:04.405  1014  3881 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:01:07.365   293   293 E SMD     : DCD OFF
,07-06 14:01:09.075  1014  3464 D SSRM:n  : SIOP:: AP = 280
,07-06 14:01:10.365   293   293 E SMD     : DCD OFF
,07-06 14:01:13.365   293   293 E SMD     : DCD OFF
,07-06 14:01:14.475  1014  1498 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:01:16.365   293   293 E SMD     : DCD OFF
,07-06 14:01:17.935  1014  3534 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 14:01:19.085  1014  3464 D SSRM:n  : SIOP:: AP = 290
,07-06 14:01:19.365   293   293 E SMD     : DCD OFF
,07-06 14:01:19.805   337   337 I Atfwd_Daemon: Stop the daemon....,
,07-06 14:01:22.365   293   293 E SMD     : DCD OFF
,07-06 14:01:23.045  1014  1046 I PowerManagerService: [PWL] Off : 525s ago
,07-06 14:01:23.125  1014  1301 E Watchdog: !@Sync 19
,07-06 14:01:24.545  1014  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:01:25.375   293   293 E SMD     : DCD OFF
,07-06 14:01:28.375   293   293 E SMD     : DCD OFF
,07-06 14:01:29.095  1014  3464 D SSRM:n  : SIOP:: AP = 280
,07-06 14:01:31.375   293   293 E SMD     : DCD OFF
,07-06 14:01:34.375   293   293 E SMD     : DCD OFF
,07-06 14:01:34.605  1014  1535 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:01:37.375   293   293 E SMD     : DCD OFF
,07-06 14:01:37.935  1014  3534 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 14:01:39.115  1014  3464 D SSRM:n  : SIOP:: AP = 290
,07-06 14:01:40.375   293   293 E SMD     : DCD OFF
,07-06 14:01:43.375   293   293 E SMD     : DCD OFF
,07-06 14:01:44.675  1014  1302 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:01:46.375   293   293 E SMD     : DCD OFF
,07-06 14:01:49.125  1014  3464 D SSRM:n  : SIOP:: AP = 280
,07-06 14:01:49.385   293   293 E SMD     : DCD OFF
,07-06 14:01:50.845  1014  1083 D TimaService: TIMA: TimaService scheduler is intialized. 
07-06 14:01:50.845  1014  1083 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
07-06 14:01:50.845  1014  1082 D TimaService: TimaServiceHandler.handleMessage what =1
,07-06 14:01:51.655  1014  1083 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-06 14:01:51.655  1014  1083 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-06 14:01:51.665  1014  1083 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-06 14:01:51.665  1014  1083 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-06 14:01:52.385   293   293 E SMD     : DCD OFF
,07-06 14:01:53.125  1014  1301 E Watchdog: !@Sync 20
,07-06 14:01:54.735  1014  4014 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:01:55.385   293   293 E SMD     : DCD OFF
,07-06 14:01:57.935  1014  3534 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,07-06 14:01:58.385   293   293 E SMD     : DCD OFF
,07-06 14:01:59.145  1014  3464 D SSRM:n  : SIOP:: AP = 290
,07-06 14:02:01.385   293   293 E SMD     : DCD OFF
,07-06 14:02:04.385   293   293 E SMD     : DCD OFF
,07-06 14:02:04.805  1014  1133 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-06 14:02:07.385   293   293 E SMD     : DCD OFF
,07-06 14:02:09.155  1014  3464 D SSRM:n  : SIOP:: AP = 290
,07-06 14:02:10.395   293   293 E SMD     : DCD OFF
,07-06 14:02:13.395   293   293 E SMD     : DCD OFF
,07-06 14:02:14.865  1014  3881 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-06 14:02:14.865  1014  3881 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-06 14:02:14.865  1014  3881 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-06 14:02:14.865  1014  3881 D BatteryService: stay LED for fully charged
07-06 14:02:14.865  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 14:02:14.875  1014  1014 I MotionRecognitionService: Plugged
,07-06 14:02:14.875  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,07-06 14:02:14.875  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,07-06 14:02:14.875  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
07-06 14:02:14.875  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,07-06 14:02:14.875  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-06 14:02:14.885  3340  3340 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 14:02:14.885  3340  3435 D HeadsetStateMachine: Disconnected process message: 10
,07-06 14:02:14.895  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,07-06 14:02:14.895  1172  1172 D SViewCoverView: level :100 plugged : 2
,07-06 14:02:14.905  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 14:02:14.905  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:02:14.905  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:02:16.395   293   293 E SMD     : DCD OFF
,07-06 14:02:17.935  1014  3534 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,07-06 14:02:19.185  1014  3464 D SSRM:n  : SIOP:: AP = 290
,07-06 14:02:19.395   293   293 E SMD     : DCD OFF
,07-06 14:02:22.395   293   293 E SMD     : DCD OFF
,07-06 14:02:23.125  1014  1301 E Watchdog: !@Sync 21
,07-06 14:02:24.935  1014  1536 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:02:24.935  1014  1536 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,07-06 14:02:24.935  1014  1536 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-06 14:02:24.935  1014  1536 D BatteryService: stay LED for fully charged
07-06 14:02:24.935  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 14:02:24.935  1014  1014 I MotionRecognitionService: Plugged
,07-06 14:02:24.935  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,07-06 14:02:24.945  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-06 14:02:24.945  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate,
,07-06 14:02:24.945  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-06 14:02:24.945  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,07-06 14:02:24.955  3340  3340 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-06 14:02:24.955  3340  3435 D HeadsetStateMachine: Disconnected process message: 10
,07-06 14:02:24.965  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,07-06 14:02:24.965  1172  1172 D SViewCoverView: level :100 plugged : 2
,07-06 14:02:24.965  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:02:24.965  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 14:02:24.965  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,07-06 14:02:25.395   293   293 E SMD     : DCD OFF
,07-06 14:02:28.395   293   293 E SMD     : DCD OFF
,07-06 14:02:29.215  1014  3464 D SSRM:n  : SIOP:: AP = 290,
,07-06 14:02:31.395   293   293 E SMD     : DCD OFF
,07-06 14:02:34.405   293   293 E SMD     : DCD OFF
,07-06 14:02:34.995  1014  1133 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-06 14:02:37.405   293   293 E SMD     : DCD OFF,
,07-06 14:02:38.045  1014  1046 I PowerManagerService: [PWL] Off : 600s ago
,07-06 14:02:39.235  1014  3464 D SSRM:n  : SIOP:: AP = 290
,07-06 14:02:40.405   293   293 E SMD     : DCD OFF
,07-06 14:02:43.405   293   293 E SMD     : DCD OFF
,07-06 14:02:45.065  1014  3881 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:02:46.405   293   293 E SMD     : DCD OFF
,07-06 14:02:49.245  1014  3464 D SSRM:n  : SIOP:: AP = 290
,07-06 14:02:49.405   293   293 E SMD     : DCD OFF
,07-06 14:02:52.405   293   293 E SMD     : DCD OFF,
,07-06 14:02:53.125  1014  1301 E Watchdog: !@Sync 22
,07-06 14:02:55.135  1014  1498 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:02:55.415   293   293 E SMD     : DCD OFF
,07-06 14:02:58.415   293   293 E SMD     : DCD OFF
,07-06 14:02:59.255  1014  3464 D SSRM:n  : SIOP:: AP = 290
,07-06 14:03:01.415   293   293 E SMD     : DCD OFF
,07-06 14:03:04.415   293   293 E SMD     : DCD OFF
,07-06 14:03:05.195  1014  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:03:07.415   293   293 E SMD     : DCD OFF
,07-06 14:03:09.275  1014  3464 D SSRM:n  : SIOP:: AP = 290
,07-06 14:03:10.415   293   293 E SMD     : DCD OFF
,07-06 14:03:13.415   293   293 E SMD     : DCD OFF
,07-06 14:03:15.265  1014  1535 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:03:15.265  1014  1535 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,07-06 14:03:15.265  1014  1535 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-06 14:03:15.265  1014  1535 D BatteryService: stay LED for fully charged
07-06 14:03:15.265  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 14:03:15.275  1014  1014 I MotionRecognitionService: Plugged
,07-06 14:03:15.275  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,07-06 14:03:15.275  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-06 14:03:15.275  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 14:03:15.275  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-06 14:03:15.275  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-06 14:03:15.285  3340  3340 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-06 14:03:15.285  3340  3435 D HeadsetStateMachine: Disconnected process message: 10
,07-06 14:03:15.295  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,07-06 14:03:15.295  1172  1172 D SViewCoverView: level :100 plugged : 2
,07-06 14:03:15.295  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:03:15.305  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:03:15.305  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:03:16.415   293   293 E SMD     : DCD OFF
,07-06 14:03:19.285  1014  3464 D SSRM:n  : SIOP:: AP = 290
,07-06 14:03:19.425   293   293 E SMD     : DCD OFF
,07-06 14:03:22.425   293   293 E SMD     : DCD OFF
,07-06 14:03:23.135  1014  1301 E Watchdog: !@Sync 23
,07-06 14:03:25.335  1014  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:03:25.425   293   293 E SMD     : DCD OFF
,07-06 14:03:28.425   293   293 E SMD     : DCD OFF
,07-06 14:03:29.295  1014  3464 D SSRM:n  : SIOP:: AP = 290
,07-06 14:03:31.425   293   293 E SMD     : DCD OFF
,07-06 14:03:34.425   293   293 E SMD     : DCD OFF
,07-06 14:03:35.395  1014  1536 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-06 14:03:35.395  1014  1536 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-06 14:03:35.395  1014  1536 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-06 14:03:35.395  1014  1536 D BatteryService: stay LED for fully charged
07-06 14:03:35.395  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-06 14:03:35.395  1014  1014 I MotionRecognitionService: Plugged
07-06 14:03:35.395  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,07-06 14:03:35.405  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 14:03:35.405  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-06 14:03:35.405  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
07-06 14:03:35.405  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-06 14:03:35.415  3340  3340 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-06 14:03:35.415  3340  3435 D HeadsetStateMachine: Disconnected process message: 10
,07-06 14:03:35.425  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,07-06 14:03:35.425  1172  1172 D SViewCoverView: level :100 plugged : 2
,07-06 14:03:35.425  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 14:03:35.425  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 14:03:35.425  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:03:37.425   293   293 E SMD     : DCD OFF,
,07-06 14:03:39.315  1014  3464 D SSRM:n  : SIOP:: AP = 290
,07-06 14:03:40.425   293   293 E SMD     : DCD OFF
,07-06 14:03:43.435   293   293 E SMD     : DCD OFF
,07-06 14:03:45.455  1014  1499 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:03:45.455  1014  1499 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-06 14:03:45.455  1014  1499 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-06 14:03:45.455  1014  1499 D BatteryService: stay LED for fully charged
07-06 14:03:45.455  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 14:03:45.465  1014  1014 I MotionRecognitionService: Plugged
07-06 14:03:45.465  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,07-06 14:03:45.465  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 14:03:45.465  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 14:03:45.465  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,07-06 14:03:45.465  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
07-06 14:03:45.475  3340  3340 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-06 14:03:45.475  3340  3435 D HeadsetStateMachine: Disconnected process message: 10
,07-06 14:03:45.485  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,07-06 14:03:45.485  1172  1172 D SViewCoverView: level :100 plugged : 2
,07-06 14:03:45.485  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 14:03:45.485  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 14:03:45.495  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:03:46.435   293   293 E SMD     : DCD OFF
,07-06 14:03:49.325  1014  3464 D SSRM:n  : SIOP:: AP = 280
,07-06 14:03:49.435   293   293 E SMD     : DCD OFF
,07-06 14:03:52.435   293   293 E SMD     : DCD OFF
,07-06 14:03:53.135  1014  1301 E Watchdog: !@Sync 24
,07-06 14:03:55.435   293   293 E SMD     : DCD OFF
,07-06 14:03:55.525  1014  1498 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:03:55.525  1014  1498 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-06 14:03:55.525  1014  1498 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-06 14:03:55.525  1014  1498 D BatteryService: stay LED for fully charged
07-06 14:03:55.525  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 14:03:55.525  1014  1014 I MotionRecognitionService: Plugged
,07-06 14:03:55.525  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,07-06 14:03:55.525  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 14:03:55.525  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 14:03:55.525  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,07-06 14:03:55.525  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-06 14:03:55.535  3340  3340 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 14:03:55.535  3340  3435 D HeadsetStateMachine: Disconnected process message: 10
,07-06 14:03:55.545  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,07-06 14:03:55.545  1172  1172 D SViewCoverView: level :100 plugged : 2
,07-06 14:03:55.555  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:03:55.555  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:03:55.555  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:03:58.055  1014  1046 I PowerManagerService: [PWL] Off : 680s ago
,07-06 14:03:58.435   293   293 E SMD     : DCD OFF
,07-06 14:03:59.355  1014  3464 D SSRM:n  : SIOP:: AP = 280
,07-06 14:04:01.435   293   293 E SMD     : DCD OFF
,07-06 14:04:04.445   293   293 E SMD     : DCD OFF
,07-06 14:04:05.585  1014  1535 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:04:07.445   293   293 E SMD     : DCD OFF,
,07-06 14:04:09.385  1014  3464 D SSRM:n  : SIOP:: AP = 280
,07-06 14:04:10.445   293   293 E SMD     : DCD OFF
,07-06 14:04:13.445   293   293 E SMD     : DCD OFF
,07-06 14:04:15.655  1014  1302 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
07-06 14:04:15.655  1014  1302 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,07-06 14:04:15.655  1014  1302 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,07-06 14:04:15.655  1014  1302 D BatteryService: stay LED for fully charged
07-06 14:04:15.655  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 14:04:15.655  1014  1014 I MotionRecognitionService: Plugged
07-06 14:04:15.655  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false,
07-06 14:04:15.665  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-06 14:04:15.665  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate,
,07-06 14:04:15.665  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
07-06 14:04:15.665  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,07-06 14:04:15.675  3340  3340 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 14:04:15.675  3340  3435 D HeadsetStateMachine: Disconnected process message: 10
,07-06 14:04:15.685  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,07-06 14:04:15.685  1172  1172 D SViewCoverView: level :100 plugged : 2
,07-06 14:04:15.685  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:04:15.685  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:04:15.685  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:04:16.445   293   293 E SMD     : DCD OFF
,07-06 14:04:19.405  1014  3464 D SSRM:n  : SIOP:: AP = 280
,07-06 14:04:19.445   293   293 E SMD     : DCD OFF
,07-06 14:04:22.445   293   293 E SMD     : DCD OFF,
,07-06 14:04:23.135  1014  1301 E Watchdog: !@Sync 25
,07-06 14:04:25.455   293   293 E SMD     : DCD OFF
,07-06 14:04:25.715  1014  1133 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:04:28.455   293   293 E SMD     : DCD OFF
,07-06 14:04:29.415  1014  3464 D SSRM:n  : SIOP:: AP = 280
,07-06 14:04:31.455   293   293 E SMD     : DCD OFF
,07-06 14:04:34.455   293   293 E SMD     : DCD OFF
,07-06 14:04:35.775  1014  3881 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:04:35.775  1014  3881 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,07-06 14:04:35.775  1014  3881 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-06 14:04:35.775  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-06 14:04:35.775  1014  3881 D BatteryService: stay LED for fully charged
,07-06 14:04:35.775  1014  1014 I MotionRecognitionService: Plugged
,07-06 14:04:35.785  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,07-06 14:04:35.785  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,07-06 14:04:35.785  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-06 14:04:35.785  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
07-06 14:04:35.785  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-06 14:04:35.795  3340  3340 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 14:04:35.795  3340  3435 D HeadsetStateMachine: Disconnected process message: 10
,07-06 14:04:35.805  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,07-06 14:04:35.805  1172  1172 D SViewCoverView: level :100 plugged : 2
,07-06 14:04:35.805  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:04:35.805  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:04:35.805  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:04:37.455   293   293 E SMD     : DCD OFF,
,07-06 14:04:39.445  1014  3464 D SSRM:n  : SIOP:: AP = 280
,07-06 14:04:40.455   293   293 E SMD     : DCD OFF
,07-06 14:04:43.465   293   293 E SMD     : DCD OFF
,07-06 14:04:45.845  1014  1302 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:04:45.845  1014  1302 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,07-06 14:04:45.845  1014  1302 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-06 14:04:45.845  1014  1302 D BatteryService: stay LED for fully charged
07-06 14:04:45.845  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 14:04:45.845  1014  1014 I MotionRecognitionService: Plugged,
07-06 14:04:45.845  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false,
07-06 14:04:45.845  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-06 14:04:45.845  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 14:04:45.855  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-06 14:04:45.855  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-06 14:04:45.855  3340  3340 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 14:04:45.855  3340  3435 D HeadsetStateMachine: Disconnected process message: 10
,07-06 14:04:45.875  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,07-06 14:04:45.875  1172  1172 D SViewCoverView: level :100 plugged : 2
,07-06 14:04:45.875  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:04:45.875  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:04:45.875  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:04:46.465   293   293 E SMD     : DCD OFF
,07-06 14:04:49.455  1014  3464 D SSRM:n  : SIOP:: AP = 280
,07-06 14:04:49.465   293   293 E SMD     : DCD OFF
,07-06 14:04:52.465   293   293 E SMD     : DCD OFF
,07-06 14:04:52.985  1014  1092 V AlarmManager: waitForAlarm result :4
,07-06 14:04:52.985  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-06 14:04:52.995  1172  1172 D KeyguardUpdateMonitor: handleTimeUpdate
,07-06 14:04:52.995  1172  1172 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-06 14:04:52.995  1172  1172 D SecKeyguardClockView: HomeTimezone(): 1
,07-06 14:04:53.015  1172  1172 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
07-06 14:04:53.015  1172  1172 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
07-06 14:04:53.015  1172  1172 I KeyguardEffectViewController: *** don't update sliding image ***
,07-06 14:04:53.015  1172  1172 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,07-06 14:04:53.045  1014  1498 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-06 14:04:53.045  1014  1498 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.EventLogService; callingUser = 0; userId(target) = 0
,07-06 14:04:53.045  1014  1498 W ActivityManager: userId = 0, bbcId = -10000
07-06 14:04:53.045  1014  1498 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-06 14:04:53.045  1014  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,07-06 14:04:53.055  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-06 14:04:53.065  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-06 14:04:53.065  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-06 14:04:53.085  1172  1172 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-06 14:04:53.095  1014  1026 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-06 14:04:53.095  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,07-06 14:04:53.095  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-06 14:04:53.095  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-06 14:04:53.135  1014  1301 E Watchdog: !@Sync 26
,07-06 14:04:53.135  4560  6981 I EventLogChimeraService: Aggregate from 1467804577778 (log), 1467804577778 (data)
,07-06 14:04:53.235  1014  1026 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-06 14:04:53.235  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,07-06 14:04:53.235  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-06 14:04:53.235  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-06 14:04:53.255  1014  1348 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-06 14:04:53.255  1014  1348 W ActivityManager: userId = 0, bbcId = -10000
,07-06 14:04:53.255  1014  1348 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-06 14:04:53.255  1014  1348 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-06 14:04:53.305  1014  1495 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-06 14:04:53.305  1014  1495 W ActivityManager: userId = 0, bbcId = -10000
,07-06 14:04:53.305  1014  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-06 14:04:53.305  1014  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-06 14:04:53.315  1014  1026 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-06 14:04:53.315  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,07-06 14:04:53.315  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-06 14:04:53.315  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-06 14:04:53.355  4560  6982 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-06 14:04:53.375  4560  6982 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-06 14:04:55.465   293   293 E SMD     : DCD OFF
,07-06 14:04:55.905  1014  1499 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:04:58.465   293   293 E SMD     : DCD OFF
,07-06 14:04:59.485  1014  3464 D SSRM:n  : SIOP:: AP = 290
,07-06 14:04:59.995  1014  1092 V AlarmManager: waitForAlarm result :8
,07-06 14:05:01.465   293   293 E SMD     : DCD OFF
,07-06 14:05:04.475   293   293 E SMD     : DCD OFF
,07-06 14:05:05.975  1014  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:05:07.475   293   293 E SMD     : DCD OFF
,07-06 14:05:09.505  1014  3464 D SSRM:n  : SIOP:: AP = 290
,07-06 14:05:10.475   293   293 E SMD     : DCD OFF,
,07-06 14:05:13.475   293   293 E SMD     : DCD OFF
,07-06 14:05:16.035  1014  1514 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-06 14:05:16.475   293   293 E SMD     : DCD OFF,
,07-06 14:05:19.475   293   293 E SMD     : DCD OFF,
,07-06 14:05:19.545  1014  3464 D SSRM:n  : SIOP:: AP = 290
,07-06 14:05:22.485   293   293 E SMD     : DCD OFF
,07-06 14:05:23.085  1014  1046 I PowerManagerService: [PWL] Off : 765s ago,
,07-06 14:05:23.135  1014  1301 E Watchdog: !@Sync 27
,07-06 14:05:25.485   293   293 E SMD     : DCD OFF,
,07-06 14:05:26.105  1014  1499 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:05:26.105  1014  1499 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-06 14:05:26.105  1014  1499 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-06 14:05:26.105  1014  1499 D BatteryService: stay LED for fully charged
,07-06 14:05:26.105  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 14:05:26.115  1014  1014 I MotionRecognitionService: Plugged
,07-06 14:05:26.115  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,07-06 14:05:26.115  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 14:05:26.115  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 14:05:26.115  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,07-06 14:05:26.115  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-06 14:05:26.125  3340  3340 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 14:05:26.125  3340  3435 D HeadsetStateMachine: Disconnected process message: 10
,07-06 14:05:26.145  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,07-06 14:05:26.145  1172  1172 D SViewCoverView: level :100 plugged : 2
,07-06 14:05:26.145  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 14:05:26.145  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 14:05:26.145  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:05:28.485   293   293 E SMD     : DCD OFF,
,07-06 14:05:29.555  1014  3464 D SSRM:n  : SIOP:: AP = 280
,07-06 14:05:31.485   293   293 E SMD     : DCD OFF
,07-06 14:05:34.485   293   293 E SMD     : DCD OFF
,07-06 14:05:36.175  1014  1498 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:05:37.485   293   293 E SMD     : DCD OFF
,07-06 14:05:39.585  1014  3464 D SSRM:n  : SIOP:: AP = 280
,07-06 14:05:40.495   293   293 E SMD     : DCD OFF
,07-06 14:05:43.495   293   293 E SMD     : DCD OFF
,07-06 14:05:46.235  1014  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:05:46.235  1014  1348 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,07-06 14:05:46.235  1014  1348 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-06 14:05:46.235  1014  1348 D BatteryService: stay LED for fully charged
07-06 14:05:46.235  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-06 14:05:46.245  1014  1014 I MotionRecognitionService: Plugged
07-06 14:05:46.245  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,07-06 14:05:46.245  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-06 14:05:46.245  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-06 14:05:46.245  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
07-06 14:05:46.245  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-06 14:05:46.255  3340  3340 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 14:05:46.255  3340  3435 D HeadsetStateMachine: Disconnected process message: 10
,07-06 14:05:46.265  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,07-06 14:05:46.265  1172  1172 D SViewCoverView: level :100 plugged : 2
,07-06 14:05:46.275  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 14:05:46.275  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 14:05:46.275  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:05:46.495   293   293 E SMD     : DCD OFF
,07-06 14:05:49.495   293   293 E SMD     : DCD OFF
,07-06 14:05:49.595  1014  3464 D SSRM:n  : SIOP:: AP = 280
,07-06 14:05:52.495   293   293 E SMD     : DCD OFF
,07-06 14:05:53.135  1014  1301 E Watchdog: !@Sync 28
,07-06 14:05:55.495   293   293 E SMD     : DCD OFF,
,07-06 14:05:56.305  1014  1499 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-06 14:05:58.495   293   293 E SMD     : DCD OFF,
,07-06 14:05:59.605  1014  3464 D SSRM:n  : SIOP:: AP = 280
,07-06 14:06:01.505   293   293 E SMD     : DCD OFF
,07-06 14:06:04.505   293   293 E SMD     : DCD OFF,
,07-06 14:06:06.365  1014  3882 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-06 14:06:06.365  1014  3882 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-06 14:06:06.365  1014  3882 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-06 14:06:06.365  1014  3882 D BatteryService: stay LED for fully charged
07-06 14:06:06.365  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 14:06:06.365  1014  1014 I MotionRecognitionService: Plugged
07-06 14:06:06.365  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,07-06 14:06:06.365  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 14:06:06.365  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 14:06:06.375  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-06 14:06:06.375  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-06 14:06:06.385  3340  3340 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 14:06:06.385  3340  3435 D HeadsetStateMachine: Disconnected process message: 10
,07-06 14:06:06.395  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,07-06 14:06:06.395  1172  1172 D SViewCoverView: level :100 plugged : 2
,07-06 14:06:06.395  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 14:06:06.395  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 14:06:06.395  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:06:07.505   293   293 E SMD     : DCD OFF,
,07-06 14:06:09.625  1014  3464 D SSRM:n  : SIOP:: AP = 280
,07-06 14:06:10.505   293   293 E SMD     : DCD OFF,
,07-06 14:06:13.505   293   293 E SMD     : DCD OFF
,07-06 14:06:16.425  1014  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:06:16.425  1014  1348 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
07-06 14:06:16.425  1014  1348 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
07-06 14:06:16.435  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-06 14:06:16.425  1014  1348 D BatteryService: stay LED for fully charged
07-06 14:06:16.435  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
07-06 14:06:16.425  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
07-06 14:06:16.435  1014  1014 I MotionRecognitionService: Plugged,
07-06 14:06:16.435  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
07-06 14:06:16.435  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,07-06 14:06:16.435  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-06 14:06:16.445  3340  3340 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 14:06:16.445  3340  3435 D HeadsetStateMachine: Disconnected process message: 10
,07-06 14:06:16.465  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,07-06 14:06:16.465  1172  1172 D SViewCoverView: level :100 plugged : 2
,07-06 14:06:16.465  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 14:06:16.465  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 14:06:16.465  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:06:16.505   293   293 E SMD     : DCD OFF
,07-06 14:06:19.505   293   293 E SMD     : DCD OFF,
,07-06 14:06:19.635  1014  3464 D SSRM:n  : SIOP:: AP = 280
,07-06 14:06:22.515   293   293 E SMD     : DCD OFF
,07-06 14:06:23.135  1014  1301 E Watchdog: !@Sync 29
,07-06 14:06:25.515   293   293 E SMD     : DCD OFF,
,07-06 14:06:26.495  1014  1499 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:06:26.495  1014  1499 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-06 14:06:26.495  1014  1499 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-06 14:06:26.495  1014  1499 D BatteryService: stay LED for fully charged
,07-06 14:06:26.495  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 14:06:26.495  1014  1014 I MotionRecognitionService: Plugged
,07-06 14:06:26.495  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,07-06 14:06:26.505  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 14:06:26.505  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 14:06:26.505  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,07-06 14:06:26.505  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-06 14:06:26.515  3340  3340 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 14:06:26.515  3340  3435 D HeadsetStateMachine: Disconnected process message: 10
,07-06 14:06:26.525  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,07-06 14:06:26.535  1172  1172 D SViewCoverView: level :100 plugged : 2
,07-06 14:06:26.535  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 14:06:26.535  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 14:06:26.535  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:06:28.515   293   293 E SMD     : DCD OFF,
,07-06 14:06:29.665  1014  3464 D SSRM:n  : SIOP:: AP = 280
,07-06 14:06:31.515   293   293 E SMD     : DCD OFF
,07-06 14:06:34.515   293   293 E SMD     : DCD OFF
,07-06 14:06:36.555  1014  1498 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:06:36.555  1014  1498 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-06 14:06:36.555  1014  1498 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-06 14:06:36.555  1014  1498 D BatteryService: stay LED for fully charged
07-06 14:06:36.555  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 14:06:36.555  1014  1014 I MotionRecognitionService: Plugged
,07-06 14:06:36.555  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,07-06 14:06:36.565  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 14:06:36.565  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 14:06:36.565  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,07-06 14:06:36.565  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-06 14:06:36.575  3340  3340 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-06 14:06:36.575  3340  3435 D HeadsetStateMachine: Disconnected process message: 10
,07-06 14:06:36.585  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-06 14:06:36.585  1172  1172 D SViewCoverView: level :100 plugged : 2
,07-06 14:06:36.585  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 14:06:36.585  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 14:06:36.585  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:06:37.515   293   293 E SMD     : DCD OFF
,07-06 14:06:39.675  1014  3464 D SSRM:n  : SIOP:: AP = 280
,07-06 14:06:40.525   293   293 E SMD     : DCD OFF
,07-06 14:06:43.525   293   293 E SMD     : DCD OFF,
,07-06 14:06:46.525   293   293 E SMD     : DCD OFF
,07-06 14:06:46.615  1014  1514 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:06:46.615  1014  1514 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
07-06 14:06:46.625  1014  1514 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-06 14:06:46.625  1014  1514 D BatteryService: stay LED for fully charged
07-06 14:06:46.625  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-06 14:06:46.625  1014  1014 I MotionRecognitionService: Plugged
07-06 14:06:46.625  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false,
07-06 14:06:46.625  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-06 14:06:46.625  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,07-06 14:06:46.635  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-06 14:06:46.635  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 14:06:46.635  3340  3340 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 14:06:46.635  3340  3435 D HeadsetStateMachine: Disconnected process message: 10
,07-06 14:06:46.655  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,07-06 14:06:46.655  1172  1172 D SViewCoverView: level :100 plugged : 2
,07-06 14:06:46.655  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 14:06:46.655  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 14:06:46.655  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:06:49.525   293   293 E SMD     : DCD OFF
,07-06 14:06:49.685  1014  3464 D SSRM:n  : SIOP:: AP = 280
,07-06 14:06:50.845  1014  1083 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-06 14:06:50.845  1014  1083 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-06 14:06:50.845  1014  1082 D TimaService: TimaServiceHandler.handleMessage what =1
,07-06 14:06:52.525   293   293 E SMD     : DCD OFF
,07-06 14:06:52.755  1014  1083 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-06 14:06:52.755  1014  1083 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-06 14:06:52.755  1014  1083 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-06 14:06:52.755  1014  1083 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-06 14:06:53.085  1014  1046 I PowerManagerService: [PWL] Off : 855s ago
,07-06 14:06:53.135  1014  1301 E Watchdog: !@Sync 30
,07-06 14:06:55.525   293   293 E SMD     : DCD OFF
,07-06 14:06:56.685  1014  1535 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:06:58.525   293   293 E SMD     : DCD OFF
,07-06 14:06:59.705  1014  3464 D SSRM:n  : SIOP:: AP = 290
,07-06 14:07:01.535   293   293 E SMD     : DCD OFF
,07-06 14:07:04.535   293   293 E SMD     : DCD OFF,
,07-06 14:07:06.755  1014  1498 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-06 14:07:07.535   293   293 E SMD     : DCD OFF
,07-06 14:07:09.715  1014  3464 D SSRM:n  : SIOP:: AP = 290
,07-06 14:07:10.535   293   293 E SMD     : DCD OFF
,07-06 14:07:13.535   293   293 E SMD     : DCD OFF
,07-06 14:07:16.535   293   293 E SMD     : DCD OFF
,07-06 14:07:16.815  1014  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:07:19.535   293   293 E SMD     : DCD OFF,
,07-06 14:07:19.745  1014  3464 D SSRM:n  : SIOP:: AP = 290
,07-06 14:07:22.545   293   293 E SMD     : DCD OFF
,07-06 14:07:23.135  1014  1301 E Watchdog: !@Sync 31
,07-06 14:07:25.545   293   293 E SMD     : DCD OFF,
,07-06 14:07:26.885  1014  1302 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:07:28.545   293   293 E SMD     : DCD OFF
,07-06 14:07:29.785  1014  3464 D SSRM:n  : SIOP:: AP = 280
,07-06 14:07:31.545   293   293 E SMD     : DCD OFF
,07-06 14:07:34.545   293   293 E SMD     : DCD OFF
,07-06 14:07:36.945  1014  1536 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:07:37.545   293   293 E SMD     : DCD OFF,
,07-06 14:07:39.795  1014  3464 D SSRM:n  : SIOP:: AP = 280
,07-06 14:07:40.555   293   293 E SMD     : DCD OFF
,07-06 14:07:43.555   293   293 E SMD     : DCD OFF
,07-06 14:07:46.555   293   293 E SMD     : DCD OFF
,07-06 14:07:47.005  1014  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:07:49.555   293   293 E SMD     : DCD OFF,
,07-06 14:07:49.815  1014  3464 D SSRM:n  : SIOP:: AP = 280
,07-06 14:07:52.555   293   293 E SMD     : DCD OFF
,07-06 14:07:53.135  1014  1301 E Watchdog: !@Sync 32,
,07-06 14:07:55.555   293   293 E SMD     : DCD OFF
,07-06 14:07:57.075  1014  4014 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:07:58.565   293   293 E SMD     : DCD OFF,
,07-06 14:07:59.825  1014  3464 D SSRM:n  : SIOP:: AP = 280
,07-06 14:08:01.565   293   293 E SMD     : DCD OFF
,07-06 14:08:04.565   293   293 E SMD     : DCD OFF,
,07-06 14:08:07.135  1014  1535 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:08:07.565   293   293 E SMD     : DCD OFF
,07-06 14:08:09.835  1014  3464 D SSRM:n  : SIOP:: AP = 280
,07-06 14:08:10.565   293   293 E SMD     : DCD OFF,
,07-06 14:08:13.565   293   293 E SMD     : DCD OFF,
,07-06 14:08:16.575   293   293 E SMD     : DCD OFF
,07-06 14:08:17.205  1014  1498 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:08:19.575   293   293 E SMD     : DCD OFF,
,07-06 14:08:19.855  1014  3464 D SSRM:n  : SIOP:: AP = 280
,07-06 14:08:22.575   293   293 E SMD     : DCD OFF
,07-06 14:08:23.135  1014  1301 E Watchdog: !@Sync 33,
,07-06 14:08:25.575   293   293 E SMD     : DCD OFF
,07-06 14:08:27.275  1014  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:08:28.155  1014  1046 I PowerManagerService: [PWL] Off : 950s ago
,07-06 14:08:28.575   293   293 E SMD     : DCD OFF,
,07-06 14:08:29.865  1014  3464 D SSRM:n  : SIOP:: AP = 280
,07-06 14:08:31.575   293   293 E SMD     : DCD OFF
,07-06 14:08:34.575   293   293 E SMD     : DCD OFF
,07-06 14:08:37.335  1014  1302 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:08:37.585   293   293 E SMD     : DCD OFF,
,07-06 14:08:39.905  1014  3464 D SSRM:n  : SIOP:: AP = 280
,07-06 14:08:40.585   293   293 E SMD     : DCD OFF
,07-06 14:08:43.585   293   293 E SMD     : DCD OFF
,07-06 14:08:46.585   293   293 E SMD     : DCD OFF
,07-06 14:08:47.405  1014  1536 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-06 14:08:49.585   293   293 E SMD     : DCD OFF
,07-06 14:08:49.915  1014  3464 D SSRM:n  : SIOP:: AP = 280
,07-06 14:08:52.585   293   293 E SMD     : DCD OFF
,07-06 14:08:53.135  1014  1301 E Watchdog: !@Sync 34,
,07-06 14:08:55.595   293   293 E SMD     : DCD OFF
,07-06 14:08:57.465  1014  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-06 14:08:58.595   293   293 E SMD     : DCD OFF,
,07-06 14:08:59.945  1014  3464 D SSRM:n  : SIOP:: AP = 280
,07-06 14:09:01.595   293   293 E SMD     : DCD OFF
,07-06 14:09:04.595   293   293 E SMD     : DCD OFF,
,07-06 14:09:07.525  1014  4014 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:09:07.595   293   293 E SMD     : DCD OFF
,07-06 14:09:09.955  1014  3464 D SSRM:n  : SIOP:: AP = 280
,07-06 14:09:10.595   293   293 E SMD     : DCD OFF,
,07-06 14:09:13.595   293   293 E SMD     : DCD OFF
,07-06 14:09:16.605   293   293 E SMD     : DCD OFF
,07-06 14:09:17.595  1014  1535 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:09:19.605   293   293 E SMD     : DCD OFF
,07-06 14:09:19.975  1014  3464 D SSRM:n  : SIOP:: AP = 280
,07-06 14:09:22.605   293   293 E SMD     : DCD OFF
,07-06 14:09:23.135  1014  1301 E Watchdog: !@Sync 35,
,07-06 14:09:25.605   293   293 E SMD     : DCD OFF
,07-06 14:09:27.665  1014  1026 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-06 14:09:28.605   293   293 E SMD     : DCD OFF
,07-06 14:09:29.985  1014  3464 D SSRM:n  : SIOP:: AP = 280
,07-06 14:09:31.605   293   293 E SMD     : DCD OFF
,07-06 14:09:34.605   293   293 E SMD     : DCD OFF
,07-06 14:09:37.615   293   293 E SMD     : DCD OFF
,07-06 14:09:37.725  1014  3881 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-06 14:09:40.015  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:09:40.615   293   293 E SMD     : DCD OFF
,07-06 14:09:43.615   293   293 E SMD     : DCD OFF
,07-06 14:09:46.615   293   293 E SMD     : DCD OFF
,07-06 14:09:47.805  1014  1133 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:09:49.615   293   293 E SMD     : DCD OFF
,07-06 14:09:50.035  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:09:52.615   293   293 E SMD     : DCD OFF
,07-06 14:09:53.135  1014  1301 E Watchdog: !@Sync 36
,07-06 14:09:55.615   293   293 E SMD     : DCD OFF
,07-06 14:09:57.865  1014  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:09:58.615   293   293 E SMD     : DCD OFF
,07-06 14:10:00.045  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:10:01.625   293   293 E SMD     : DCD OFF
,07-06 14:10:04.625   293   293 E SMD     : DCD OFF
,07-06 14:10:07.625   293   293 E SMD     : DCD OFF
,07-06 14:10:07.935  1014  1514 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:10:08.255  1014  1046 I PowerManagerService: [PWL] Off : 1051s ago,
,07-06 14:10:10.055  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:10:10.625   293   293 E SMD     : DCD OFF
,07-06 14:10:13.625   293   293 E SMD     : DCD OFF
,07-06 14:10:16.625   293   293 E SMD     : DCD OFF
,07-06 14:10:18.005  1014  1499 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:10:19.625   293   293 E SMD     : DCD OFF
,07-06 14:10:20.075  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:10:22.625   293   293 E SMD     : DCD OFF
,07-06 14:10:23.135  1014  1301 E Watchdog: !@Sync 37,
,07-06 14:10:25.635   293   293 E SMD     : DCD OFF
,07-06 14:10:28.075  1014  3882 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:10:28.635   293   293 E SMD     : DCD OFF
,07-06 14:10:30.085  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:10:31.635   293   293 E SMD     : DCD OFF
,07-06 14:10:34.635   293   293 E SMD     : DCD OFF
,07-06 14:10:37.635   293   293 E SMD     : DCD OFF
,07-06 14:10:38.145  1014  1026 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:10:40.125  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:10:40.635   293   293 E SMD     : DCD OFF
,07-06 14:10:43.635   293   293 E SMD     : DCD OFF
,07-06 14:10:46.645   293   293 E SMD     : DCD OFF
,07-06 14:10:48.225  1014  3881 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-06 14:10:49.645   293   293 E SMD     : DCD OFF
,07-06 14:10:50.155  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:10:52.645   293   293 E SMD     : DCD OFF
,07-06 14:10:53.135  1014  1301 E Watchdog: !@Sync 38
,07-06 14:10:55.645   293   293 E SMD     : DCD OFF
,07-06 14:10:58.285  1014  1133 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:10:58.645   293   293 E SMD     : DCD OFF
,07-06 14:11:00.165  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:11:01.645   293   293 E SMD     : DCD OFF
,07-06 14:11:04.645   293   293 E SMD     : DCD OFF,
,07-06 14:11:07.645   293   293 E SMD     : DCD OFF
,07-06 14:11:08.355  1014  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:11:10.205  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:11:10.655   293   293 E SMD     : DCD OFF
,07-06 14:11:13.655   293   293 E SMD     : DCD OFF
,07-06 14:11:16.655   293   293 E SMD     : DCD OFF
,07-06 14:11:18.415  1014  1514 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:11:19.655   293   293 E SMD     : DCD OFF
,07-06 14:11:20.215  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:11:22.655   293   293 E SMD     : DCD OFF
,07-06 14:11:23.135  1014  1301 E Watchdog: !@Sync 39
,07-06 14:11:25.655   293   293 E SMD     : DCD OFF
,07-06 14:11:28.485  1014  1499 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:11:28.655   293   293 E SMD     : DCD OFF
,07-06 14:11:30.235  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:11:31.665   293   293 E SMD     : DCD OFF
,07-06 14:11:34.665   293   293 E SMD     : DCD OFF
,07-06 14:11:37.665   293   293 E SMD     : DCD OFF
,07-06 14:11:38.545  1014  3882 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:11:40.245  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:11:40.665   293   293 E SMD     : DCD OFF
,07-06 14:11:43.665   293   293 E SMD     : DCD OFF
,07-06 14:11:46.665   293   293 E SMD     : DCD OFF
,07-06 14:11:48.615  1014  1026 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:11:49.665   293   293 E SMD     : DCD OFF
,07-06 14:11:50.255  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:11:50.765  1014  1038 I UsageStatsService: User[0] Flushing usage stats to disk
,07-06 14:11:50.805  1014  1099 I ApplicationUsage: handleMessage : MSG_UPDATE_USAGE_DB
,07-06 14:11:50.805  1014  1099 I ApplicationUsage: Updating Usage Statistics in DB @ 1467807110812
,07-06 14:11:50.815  1014  1099 I ApplicationPolicy: updateDataUsageMap
,07-06 14:11:50.845  1014  1083 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-06 14:11:50.845  1014  1083 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
07-06 14:11:50.845  1014  1082 D TimaService: TimaServiceHandler.handleMessage what =1
,07-06 14:11:51.315  1014  1099 I NetworkDataUsageDb: ::getAppControlDB: DB is Created 
,07-06 14:11:51.315  1014  1099 I NetworkDataUsageDb: ::isTableExists: Table exists 
,07-06 14:11:51.345  1014  1099 I ApplicationUsage: Done Updating Usage Statistics in DB @ 1467807111349
,07-06 14:11:51.645  1014  1083 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-06 14:11:51.655  1014  1083 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-06 14:11:51.655  1014  1083 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-06 14:11:51.655  1014  1083 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-06 14:11:52.665   293   293 E SMD     : DCD OFF
,07-06 14:11:53.145  1014  1301 E Watchdog: !@Sync 40
,07-06 14:11:53.255  1014  1046 I PowerManagerService: [PWL] Off : 1156s ago
,07-06 14:11:55.675   293   293 E SMD     : DCD OFF
,07-06 14:11:58.675   293   293 E SMD     : DCD OFF
07-06 14:11:58.675  1014  3881 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:12:00.275  1014  3464 D SSRM:n  : SIOP:: AP = 290
,07-06 14:12:01.675   293   293 E SMD     : DCD OFF
,07-06 14:12:04.675   293   293 E SMD     : DCD OFF
,07-06 14:12:07.675   293   293 E SMD     : DCD OFF
,07-06 14:12:08.735  1014  1133 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:12:08.735  1014  1133 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
07-06 14:12:08.735  1014  1133 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-06 14:12:08.735  1014  1133 D BatteryService: stay LED for fully charged
07-06 14:12:08.735  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
,07-06 14:12:08.745  1014  1014 I MotionRecognitionService: Plugged
07-06 14:12:08.745  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false,
,07-06 14:12:08.745  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 14:12:08.745  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 14:12:08.745  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-06 14:12:08.745  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,07-06 14:12:08.755  3340  3340 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-06 14:12:08.755  3340  3435 D HeadsetStateMachine: Disconnected process message: 10
,07-06 14:12:08.765  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,07-06 14:12:08.765  1172  1172 D SViewCoverView: level :100 plugged : 2
,07-06 14:12:08.765  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 14:12:08.765  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 14:12:08.765  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:12:10.295  1014  3464 D SSRM:n  : SIOP:: AP = 280
,07-06 14:12:10.675   293   293 E SMD     : DCD OFF
,07-06 14:12:13.675   293   293 E SMD     : DCD OFF
,07-06 14:12:16.675   293   293 E SMD     : DCD OFF
,07-06 14:12:18.805  1014  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:12:18.805  1014  1495 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,07-06 14:12:18.805  1014  1495 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-06 14:12:18.805  1014  1495 D BatteryService: stay LED for fully charged
,07-06 14:12:18.805  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 14:12:18.815  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 14:12:18.815  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 14:12:18.815  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,07-06 14:12:18.815  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-06 14:12:18.825  1014  1014 I MotionRecognitionService: Plugged
07-06 14:12:18.825  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,07-06 14:12:18.825  3340  3340 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 14:12:18.825  3340  3435 D HeadsetStateMachine: Disconnected process message: 10
,07-06 14:12:18.835  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-06 14:12:18.835  1172  1172 D SViewCoverView: level :100 plugged : 2
07-06 14:12:18.835  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 14:12:18.835  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 14:12:18.835  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:12:19.685   293   293 E SMD     : DCD OFF
,07-06 14:12:20.305  1014  3464 D SSRM:n  : SIOP:: AP = 280
,07-06 14:12:22.685   293   293 E SMD     : DCD OFF
,07-06 14:12:23.145  1014  1301 E Watchdog: !@Sync 41
,07-06 14:12:25.685   293   293 E SMD     : DCD OFF
,07-06 14:12:28.685   293   293 E SMD     : DCD OFF
,07-06 14:12:28.865  1014  1535 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:12:30.345  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:12:31.685   293   293 E SMD     : DCD OFF
,07-06 14:12:34.685   293   293 E SMD     : DCD OFF
,07-06 14:12:37.685   293   293 E SMD     : DCD OFF
,07-06 14:12:38.935  1014  1498 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:12:40.375  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:12:40.695   293   293 E SMD     : DCD OFF
,07-06 14:12:43.695   293   293 E SMD     : DCD OFF
,07-06 14:12:46.695   293   293 E SMD     : DCD OFF
,07-06 14:12:49.005  1014  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:12:49.695   293   293 E SMD     : DCD OFF
,07-06 14:12:50.395  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:12:52.695   293   293 E SMD     : DCD OFF
,07-06 14:12:53.145  1014  1301 E Watchdog: !@Sync 42,
,07-06 14:12:55.695   293   293 E SMD     : DCD OFF
,07-06 14:12:58.695   293   293 E SMD     : DCD OFF
,07-06 14:12:59.065  1014  1514 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:13:00.405  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:13:01.695   293   293 E SMD     : DCD OFF
,07-06 14:13:04.705   293   293 E SMD     : DCD OFF
,07-06 14:13:07.705   293   293 E SMD     : DCD OFF
,07-06 14:13:09.135  1014  1536 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:13:10.415  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:13:10.705   293   293 E SMD     : DCD OFF
,07-06 14:13:13.705   293   293 E SMD     : DCD OFF
,07-06 14:13:16.705   293   293 E SMD     : DCD OFF
,07-06 14:13:19.195  1014  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-06 14:13:19.705   293   293 E SMD     : DCD OFF
,07-06 14:13:20.435  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:13:22.705   293   293 E SMD     : DCD OFF
,07-06 14:13:23.145  1014  1301 E Watchdog: !@Sync 43
,07-06 14:13:25.705   293   293 E SMD     : DCD OFF
,07-06 14:13:28.715   293   293 E SMD     : DCD OFF
,07-06 14:13:29.265  1014  4014 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:13:30.445  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:13:31.715   293   293 E SMD     : DCD OFF
,07-06 14:13:34.715   293   293 E SMD     : DCD OFF
,07-06 14:13:37.715   293   293 E SMD     : DCD OFF
,07-06 14:13:39.325  1014  1535 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:13:40.455  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:13:40.715   293   293 E SMD     : DCD OFF
,07-06 14:13:43.255  1014  1046 I PowerManagerService: [PWL] Off : 1266s ago
,07-06 14:13:43.715   293   293 E SMD     : DCD OFF
,07-06 14:13:46.715   293   293 E SMD     : DCD OFF
,07-06 14:13:49.395  1014  1498 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-06 14:13:49.725   293   293 E SMD     : DCD OFF
,07-06 14:13:50.475  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:13:52.725   293   293 E SMD     : DCD OFF
,07-06 14:13:53.145  1014  1301 E Watchdog: !@Sync 44
,07-06 14:13:55.725   293   293 E SMD     : DCD OFF
,07-06 14:13:58.725   293   293 E SMD     : DCD OFF
,07-06 14:13:59.455  1014  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:14:00.485  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:14:01.725   293   293 E SMD     : DCD OFF
,07-06 14:14:04.725   293   293 E SMD     : DCD OFF
,07-06 14:14:07.725   293   293 E SMD     : DCD OFF
,07-06 14:14:09.515  1014  1514 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:14:10.495  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:14:10.725   293   293 E SMD     : DCD OFF
,07-06 14:14:13.735   293   293 E SMD     : DCD OFF
,07-06 14:14:16.735   293   293 E SMD     : DCD OFF
,07-06 14:14:19.585  1014  1536 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:14:19.735   293   293 E SMD     : DCD OFF
,07-06 14:14:20.505  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:14:22.735   293   293 E SMD     : DCD OFF,
,07-06 14:14:23.145  1014  1301 E Watchdog: !@Sync 45,
,07-06 14:14:25.735   293   293 E SMD     : DCD OFF
,07-06 14:14:28.735   293   293 E SMD     : DCD OFF
,07-06 14:14:29.655  1014  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-06 14:14:30.525  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:14:31.735   293   293 E SMD     : DCD OFF
,07-06 14:14:34.735   293   293 E SMD     : DCD OFF
,07-06 14:14:37.745   293   293 E SMD     : DCD OFF
,07-06 14:14:39.715  1014  4014 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:14:40.555  1014  3464 D SSRM:n  : SIOP:: AP = 270,
,07-06 14:14:40.745   293   293 E SMD     : DCD OFF
,07-06 14:14:43.745   293   293 E SMD     : DCD OFF
,07-06 14:14:46.745   293   293 E SMD     : DCD OFF
,07-06 14:14:49.745   293   293 E SMD     : DCD OFF
,07-06 14:14:49.785  1014  3882 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:14:50.575  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:14:52.745   293   293 E SMD     : DCD OFF,
,07-06 14:14:53.145  1014  1301 E Watchdog: !@Sync 46
,07-06 14:14:55.745   293   293 E SMD     : DCD OFF
,07-06 14:14:58.755   293   293 E SMD     : DCD OFF
,07-06 14:14:59.845  1014  1026 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:15:00.585  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:15:01.755   293   293 E SMD     : DCD OFF
,07-06 14:15:04.755   293   293 E SMD     : DCD OFF
,07-06 14:15:07.755   293   293 E SMD     : DCD OFF,
,07-06 14:15:09.915  1014  3881 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-06 14:15:10.595  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:15:10.755   293   293 E SMD     : DCD OFF
,07-06 14:15:13.755   293   293 E SMD     : DCD OFF
,07-06 14:15:16.755   293   293 E SMD     : DCD OFF
,07-06 14:15:19.755   293   293 E SMD     : DCD OFF
,07-06 14:15:19.975  1014  1133 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:15:20.615  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:15:22.765   293   293 E SMD     : DCD OFF,
,07-06 14:15:23.145  1014  1301 E Watchdog: !@Sync 47,
,07-06 14:15:25.765   293   293 E SMD     : DCD OFF
,07-06 14:15:28.765   293   293 E SMD     : DCD OFF
,07-06 14:15:30.045  1014  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:15:30.625  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:15:31.765   293   293 E SMD     : DCD OFF
,07-06 14:15:34.765   293   293 E SMD     : DCD OFF
,07-06 14:15:37.765   293   293 E SMD     : DCD OFF
,07-06 14:15:38.355  1014  1046 I PowerManagerService: [PWL] Off : 1381s ago
,07-06 14:15:40.105  1014  1302 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:15:40.635  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:15:40.765   293   293 E SMD     : DCD OFF
,07-06 14:15:43.765   293   293 E SMD     : DCD OFF
,07-06 14:15:46.775   293   293 E SMD     : DCD OFF
,07-06 14:15:49.775   293   293 E SMD     : DCD OFF
,07-06 14:15:50.165  1014  1499 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:15:50.165  1014  1499 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-06 14:15:50.165  1014  1499 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,07-06 14:15:50.165  1014  1499 D BatteryService: stay LED for fully charged
,07-06 14:15:50.165  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
07-06 14:15:50.175  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-06 14:15:50.175  1014  1014 I MotionRecognitionService: Plugged
,07-06 14:15:50.175  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
07-06 14:15:50.175  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,07-06 14:15:50.175  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-06 14:15:50.175  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,07-06 14:15:50.185  3340  3340 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 14:15:50.185  3340  3435 D HeadsetStateMachine: Disconnected process message: 10
,07-06 14:15:50.195  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,07-06 14:15:50.195  1172  1172 D SViewCoverView: level :100 plugged : 2
,07-06 14:15:50.195  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:15:50.195  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:15:50.195  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:15:50.655  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:15:52.775   293   293 E SMD     : DCD OFF,
,07-06 14:15:53.145  1014  1301 E Watchdog: !@Sync 48
,07-06 14:15:55.775   293   293 E SMD     : DCD OFF
,07-06 14:15:58.775   293   293 E SMD     : DCD OFF
,07-06 14:16:00.235  1014  1026 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:16:00.235  1014  1026 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
07-06 14:16:00.235  1014  1026 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-06 14:16:00.235  1014  1026 D BatteryService: stay LED for fully charged,
07-06 14:16:00.235  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 14:16:00.235  1014  1014 I MotionRecognitionService: Plugged
07-06 14:16:00.245  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-06 14:16:00.235  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false,
07-06 14:16:00.245  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
07-06 14:16:00.245  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
07-06 14:16:00.245  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-06 14:16:00.255  3340  3340 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-06 14:16:00.255  3340  3435 D HeadsetStateMachine: Disconnected process message: 10
,07-06 14:16:00.265  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,07-06 14:16:00.265  1172  1172 D SViewCoverView: level :100 plugged : 2
,07-06 14:16:00.265  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:16:00.265  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 14:16:00.265  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:16:00.665  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:16:01.775   293   293 E SMD     : DCD OFF
,07-06 14:16:04.775   293   293 E SMD     : DCD OFF
,07-06 14:16:07.785   293   293 E SMD     : DCD OFF
,07-06 14:16:10.295  1014  1514 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:16:10.295  1014  1514 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-06 14:16:10.295  1014  1514 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-06 14:16:10.295  1014  1514 D BatteryService: stay LED for fully charged
07-06 14:16:10.295  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 14:16:10.305  1014  1014 I MotionRecognitionService: Plugged
,07-06 14:16:10.305  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,07-06 14:16:10.305  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 14:16:10.305  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 14:16:10.315  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
07-06 14:16:10.315  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,07-06 14:16:10.325  3340  3340 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 14:16:10.325  3340  3435 D HeadsetStateMachine: Disconnected process message: 10
,07-06 14:16:10.335  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,07-06 14:16:10.335  1172  1172 D SViewCoverView: level :100 plugged : 2
,07-06 14:16:10.335  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 14:16:10.335  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:16:10.335  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:16:10.685  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:16:10.785   293   293 E SMD     : DCD OFF
,07-06 14:16:13.785   293   293 E SMD     : DCD OFF
,07-06 14:16:16.785   293   293 E SMD     : DCD OFF
,07-06 14:16:19.785   293   293 E SMD     : DCD OFF
,07-06 14:16:20.365  1014  3882 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-06 14:16:20.695  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:16:22.785   293   293 E SMD     : DCD OFF,
,07-06 14:16:23.145  1014  1301 E Watchdog: !@Sync 49,
,07-06 14:16:25.785   293   293 E SMD     : DCD OFF
,07-06 14:16:28.785   293   293 E SMD     : DCD OFF
,07-06 14:16:30.435  1014  1026 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:16:30.435  1014  1026 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-06 14:16:30.435  1014  1026 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-06 14:16:30.435  1014  1026 D BatteryService: stay LED for fully charged
,07-06 14:16:30.435  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 14:16:30.435  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-06 14:16:30.435  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-06 14:16:30.435  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
07-06 14:16:30.435  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-06 14:16:30.445  1014  1014 I MotionRecognitionService: Plugged
07-06 14:16:30.445  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,07-06 14:16:30.445  3340  3340 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-06 14:16:30.445  3340  3435 D HeadsetStateMachine: Disconnected process message: 10
,07-06 14:16:30.465  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-06 14:16:30.465  1172  1172 D SViewCoverView: level :100 plugged : 2
,07-06 14:16:30.465  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:16:30.465  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:16:30.465  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:16:30.705  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:16:31.795   293   293 E SMD     : DCD OFF
,07-06 14:16:34.795   293   293 E SMD     : DCD OFF
,07-06 14:16:37.795   293   293 E SMD     : DCD OFF
,07-06 14:16:40.495  1014  1514 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:16:40.495  1014  1514 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-06 14:16:40.495  1014  1514 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-06 14:16:40.495  1014  1514 D BatteryService: stay LED for fully charged
07-06 14:16:40.495  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 14:16:40.495  1014  1014 I MotionRecognitionService: Plugged
,07-06 14:16:40.495  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,07-06 14:16:40.505  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 14:16:40.505  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 14:16:40.505  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-06 14:16:40.505  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-06 14:16:40.515  3340  3340 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-06 14:16:40.515  3340  3435 D HeadsetStateMachine: Disconnected process message: 10
,07-06 14:16:40.525  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,07-06 14:16:40.525  1172  1172 D SViewCoverView: level :100 plugged : 2
,07-06 14:16:40.525  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:16:40.525  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:16:40.525  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:16:40.715  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:16:40.795   293   293 E SMD     : DCD OFF
,07-06 14:16:43.795   293   293 E SMD     : DCD OFF
,07-06 14:16:46.795   293   293 E SMD     : DCD OFF
,07-06 14:16:49.795   293   293 E SMD     : DCD OFF
,07-06 14:16:50.555  1014  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:16:50.735  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:16:50.845  1014  1083 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-06 14:16:50.845  1014  1083 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
07-06 14:16:50.845  1014  1082 D TimaService: TimaServiceHandler.handleMessage what =1
,07-06 14:16:52.735  1014  1083 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-06 14:16:52.735  1014  1083 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-06 14:16:52.745  1014  1083 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-06 14:16:52.755  1014  1083 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-06 14:16:52.805   293   293 E SMD     : DCD OFF,
,07-06 14:16:53.145  1014  1301 E Watchdog: !@Sync 50,
,07-06 14:16:55.805   293   293 E SMD     : DCD OFF
,07-06 14:16:58.805   293   293 E SMD     : DCD OFF
,07-06 14:17:00.625  1014  4014 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-06 14:17:00.765  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:17:01.805   293   293 E SMD     : DCD OFF
,07-06 14:17:04.805   293   293 E SMD     : DCD OFF
,07-06 14:17:07.805   293   293 E SMD     : DCD OFF
,07-06 14:17:10.685  1014  1535 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:17:10.785  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:17:10.805   293   293 E SMD     : DCD OFF
,07-06 14:17:13.805   293   293 E SMD     : DCD OFF
,07-06 14:17:16.815   293   293 E SMD     : DCD OFF
,07-06 14:17:19.815   293   293 E SMD     : DCD OFF
,07-06 14:17:20.755  1014  1498 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-06 14:17:20.815  1014  3464 D SSRM:n  : SIOP:: AP = 270,
,07-06 14:17:22.815   293   293 E SMD     : DCD OFF,
,07-06 14:17:23.145  1014  1301 E Watchdog: !@Sync 51
,07-06 14:17:25.815   293   293 E SMD     : DCD OFF
,07-06 14:17:28.815   293   293 E SMD     : DCD OFF
,07-06 14:17:30.815  1014  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-06 14:17:30.825  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:17:31.815   293   293 E SMD     : DCD OFF
,07-06 14:17:34.815   293   293 E SMD     : DCD OFF
,07-06 14:17:37.825   293   293 E SMD     : DCD OFF
,07-06 14:17:38.405  1014  1046 I PowerManagerService: [PWL] Off : 1501s ago,
,07-06 14:17:40.825   293   293 E SMD     : DCD OFF
,07-06 14:17:40.855  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:17:40.895  1014  1514 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-06 14:17:43.825   293   293 E SMD     : DCD OFF
,07-06 14:17:46.825   293   293 E SMD     : DCD OFF
,07-06 14:17:49.825   293   293 E SMD     : DCD OFF
,07-06 14:17:50.875  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:17:50.955  1014  1536 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:17:52.825   293   293 E SMD     : DCD OFF
,07-06 14:17:53.145  1014  1301 E Watchdog: !@Sync 52,
,07-06 14:17:55.825   293   293 E SMD     : DCD OFF
,07-06 14:17:58.825   293   293 E SMD     : DCD OFF
,07-06 14:18:00.895  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:18:01.025  1014  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-06 14:18:01.835   293   293 E SMD     : DCD OFF
,07-06 14:18:04.835   293   293 E SMD     : DCD OFF
,07-06 14:18:07.835   293   293 E SMD     : DCD OFF
,07-06 14:18:10.835   293   293 E SMD     : DCD OFF
,07-06 14:18:10.915  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:18:11.095  1014  4014 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-06 14:18:13.835   293   293 E SMD     : DCD OFF
,07-06 14:18:16.835   293   293 E SMD     : DCD OFF
,07-06 14:18:19.835   293   293 E SMD     : DCD OFF
,07-06 14:18:20.945  1014  3464 D SSRM:n  : SIOP:: AP = 270,
,07-06 14:18:21.155  1014  1535 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-06 14:18:22.835   293   293 E SMD     : DCD OFF
,07-06 14:18:23.145  1014  1301 E Watchdog: !@Sync 53
,07-06 14:18:25.845   293   293 E SMD     : DCD OFF
,07-06 14:18:28.845   293   293 E SMD     : DCD OFF
,07-06 14:18:30.985  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:18:31.225  1014  1498 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:18:31.845   293   293 E SMD     : DCD OFF
,07-06 14:18:34.845   293   293 E SMD     : DCD OFF
,07-06 14:18:37.845   293   293 E SMD     : DCD OFF
,07-06 14:18:40.845   293   293 E SMD     : DCD OFF
,07-06 14:18:41.025  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:18:41.285  1014  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:18:43.845   293   293 E SMD     : DCD OFF
,07-06 14:18:46.855   293   293 E SMD     : DCD OFF
,07-06 14:18:49.855   293   293 E SMD     : DCD OFF
,07-06 14:18:51.055  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:18:51.355  1014  1514 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-06 14:18:52.855   293   293 E SMD     : DCD OFF
,07-06 14:18:53.145  1014  1301 E Watchdog: !@Sync 54
,07-06 14:18:55.855   293   293 E SMD     : DCD OFF
,07-06 14:18:58.855   293   293 E SMD     : DCD OFF
,07-06 14:19:01.095  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:19:01.415  1014  1536 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:19:01.855   293   293 E SMD     : DCD OFF
,07-06 14:19:04.855   293   293 E SMD     : DCD OFF
,07-06 14:19:07.855   293   293 E SMD     : DCD OFF
,07-06 14:19:10.865   293   293 E SMD     : DCD OFF
,07-06 14:19:11.105  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:19:11.485  1014  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-06 14:19:11.485  1014  1495 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-06 14:19:11.485  1014  1495 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-06 14:19:11.485  1014  1495 D BatteryService: stay LED for fully charged
07-06 14:19:11.485  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 14:19:11.485  1014  1014 I MotionRecognitionService: Plugged,
07-06 14:19:11.485  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,07-06 14:19:11.495  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 14:19:11.495  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 14:19:11.495  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
07-06 14:19:11.495  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-06 14:19:11.505  3340  3340 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 14:19:11.505  3340  3435 D HeadsetStateMachine: Disconnected process message: 10
,07-06 14:19:11.515  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,07-06 14:19:11.515  1172  1172 D SViewCoverView: level :100 plugged : 2
,07-06 14:19:11.515  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:19:11.515  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:19:11.515  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:19:13.865   293   293 E SMD     : DCD OFF
,07-06 14:19:16.865   293   293 E SMD     : DCD OFF
,07-06 14:19:19.865   293   293 E SMD     : DCD OFF
,07-06 14:19:21.125  1014  3464 D SSRM:n  : SIOP:: AP = 270
,07-06 14:19:21.555  1014  3881 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:19:21.555  1014  3881 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-06 14:19:21.555  1014  3881 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,07-06 14:19:21.555  1014  3881 D BatteryService: stay LED for fully charged
07-06 14:19:21.555  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 14:19:21.565  1014  1014 I MotionRecognitionService: Plugged
,07-06 14:19:21.565  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,07-06 14:19:21.565  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-06 14:19:21.565  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate,
07-06 14:19:21.565  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,07-06 14:19:21.565  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-06 14:19:21.575  3340  3340 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-06 14:19:21.575  3340  3435 D HeadsetStateMachine: Disconnected process message: 10
,07-06 14:19:21.585  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,07-06 14:19:21.585  1172  1172 D SViewCoverView: level :100 plugged : 2
,07-06 14:19:21.585  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 14:19:21.585  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 14:19:21.585  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,TIME-OUT KILL (timeout was 1400000ms),07-06 14:19:22.475  7334  7334 D AndroidRuntime: 
07-06 14:19:22.475  7334  7334 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-06 14:19:22.475  7334  7334 D AndroidRuntime: CheckJNI is OFF
07-06 14:19:22.475  7334  7334 D AndroidRuntime: readGMSProperty: start
07-06 14:19:22.475  7334  7334 D AndroidRuntime: readGMSProperty: already setted!!
07-06 14:19:22.475  7334  7334 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-06 14:19:22.475  7334  7334 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-06 14:19:22.475  7334  7334 D AndroidRuntime: readGMSProperty: end
07-06 14:19:22.475  7334  7334 D AndroidRuntime: addProductProperty: start
07-06 14:19:22.595  7334  7334 E AffinityControl: AffinityControl: registerfunction enter
07-06 14:19:22.615  7334  7334 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-06 14:19:22.635  1014  1026 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
07-06 14:19:22.635  1014  1026 D PackageManager: START PACKAGE DELETE: observer{910640970}
07-06 14:19:22.635  1014  1026 D PackageManager: pkg{<packageName>}
07-06 14:19:22.635  1014  1026 D PackageManager: user{0}
07-06 14:19:22.635  1014  1026 D PackageManager: caller{2000}
07-06 14:19:22.635  1014  1026 D PackageManager: flags{2}
07-06 14:19:22.635  1014  1026 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
07-06 14:19:22.635  1014  1026 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
07-06 14:19:22.635  1014  1026 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-06 14:19:22.635  1014  1026 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-06 14:19:22.635  1014  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
07-06 14:19:22.635  1014  1054 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
07-06 14:19:22.635  1014  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
07-06 14:19:22.635  1014  1054 D ApplicationPolicy: getApplicationUninstallationEnabled
07-06 14:19:22.635  1014  1054 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
07-06 14:19:22.635  1014  1054 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
07-06 14:19:22.635  1014  1039 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
07-06 14:19:22.635  1014  1039 I ActivityManager: Killing 6705:com.test.thalitest/u0a170 (adj 0): stop com.test.thalitest cause uninstall pkg
07-06 14:19:22.655  1014  1039 I ActivityManager:   Force finishing activity ActivityRecord{22373a83 u0 com.test.thalitest/.MainActivity t44}
07-06 14:19:22.655  1014  1039 D InputDispatcher: Focus left window: 6705
07-06 14:19:22.655   258   439 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
07-06 14:19:22.655   258  6020 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
07-06 14:19:22.665  1014  1039 D InputDispatcher: Focused application released
07-06 14:19:22.665  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-06 14:19:22.665  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
07-06 14:19:22.735  1014  1054 W PackageSettings: Skipping PackageSetting{23c7c3e9 com.example.hello/10168} due to missing metadata
07-06 14:19:22.765  1014  1054 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
07-06 14:19:22.775  1014  1054 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
07-06 14:19:22.825  1872  1872 E SamsungIME: mOCRHelper is null
07-06 14:19:22.825  2030  2199 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-06 14:19:22.835  1014  1096 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-06 14:19:22.835  6425  6425 I art     : Explicit concurrent mark sweep GC freed 602(35KB) AllocSpace objects, 0(0B) LOS objects, 26% free, 5MB/7MB, paused 774us total 51.911ms
07-06 14:19:22.835  2736  2736 I art     : Explicit concurrent mark sweep GC freed 23430(1279KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 852us total 44.717ms
07-06 14:19:22.865  1014  1014 D RCPManagerService: PackageReceiver onReceive()
07-06 14:19:22.865   293   293 E SMD     : DCD OFF
07-06 14:19:22.875  1014  1014 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
07-06 14:19:22.875  4560  4560 I art     : Explicit concurrent mark sweep GC freed 24050(1489KB) AllocSpace objects, 5(80KB) LOS objects, 24% free, 13MB/17MB, paused 1.340ms total 103.585ms
07-06 14:19:22.885  1014  1014 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
07-06 14:19:22.885  1014  1014 I OTPFW   : PackageRemovalReceiver::onReceive Enter
07-06 14:19:22.885  1014  1014 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
07-06 14:19:22.885  1014  1120 V NetworkStats: removeUidsLocked() for UIDs [10170]
07-06 14:19:22.885  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
07-06 14:19:22.885  1014  1120 V NetworkStats: performPollLocked(flags=0x3)
07-06 14:19:22.885  1014  1120 D NetworkStatsFactory: UpdateStatsForKnox updated
07-06 14:19:22.885  1014  1120 D NetworkStatsFactory: UpdateStatsForKnox main else ---
07-06 14:19:22.895  1457  1457 D PersonaManager: isKioskContainerExistOnDevice
07-06 14:19:22.895  1457  1457 D RegisteredServicesCache: empty dynamic service
07-06 14:19:22.895  2689  2689 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Jul 06 14:19:22 GMT+02:00 2016
07-06 14:19:22.895  1014  1027 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
07-06 14:19:22.895  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
07-06 14:19:22.895  1014  1014 I OTPFW   : ProvisionData::getAllEntries Enter
07-06 14:19:22.905  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
07-06 14:19:22.905  1014  1120 V NetworkStats: performPollLocked() took 18ms
07-06 14:19:22.905  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
07-06 14:19:22.905  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-06 14:19:22.905  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
07-06 14:19:22.915  1014  1014 E OTPFW   : ProvisionData::getAllEntries Table is empty
07-06 14:19:22.915  2689  2689 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
07-06 14:19:22.925  1014  1499 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=23, mSplitNum[2]=33, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=43
07-06 14:19:22.925  1014  1499 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
07-06 14:19:22.925  1014  1499 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
07-06 14:19:22.935  2689  2689 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
07-06 14:19:22.935  1014  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 14:19:22.935  1014  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 14:19:22.935  1014  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 14:19:22.935  2689  2689 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
07-06 14:19:22.935  1014  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 14:19:22.945  2689  2689 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
07-06 14:19:22.945  2689  7345 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
07-06 14:19:22.945  2689  7345 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
07-06 14:19:22.945  2689  7345 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
07-06 14:19:22.955  7346  7346 E Zygote  : MountEmulatedStorage()
07-06 14:19:22.955  7346  7346 E Zygote  : v2
07-06 14:19:22.955  7346  7346 I libpersona: KNOX_SDCARD checking this for 10090
07-06 14:19:22.955  7346  7346 I libpersona: KNOX_SDCARD not a persona
07-06 14:19:22.955  7346  7346 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-06 14:19:22.955  1014  1499 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7346 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
07-06 14:19:22.955  7346  7346 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-06 14:19:22.965  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
07-06 14:19:22.965  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
07-06 14:19:22.965  7346  7346 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-06 14:19:22.965  2689  7345 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
07-06 14:19:22.985  6155  6155 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
07-06 14:19:22.985  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
07-06 14:19:22.985  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 14:19:22.985  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 14:19:22.985  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 14:19:22.985  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 14:19:22.995  7361  7361 E Zygote  : MountEmulatedStorage()
07-06 14:19:22.995  7361  7361 E Zygote  : v2
07-06 14:19:22.995  7361  7361 I libpersona: KNOX_SDCARD checking this for 1000
07-06 14:19:22.995  7361  7361 I libpersona: KNOX_SDCARD not a persona
07-06 14:19:23.005  7361  7361 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-06 14:19:23.005  7361  7361 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-06 14:19:23.005  7361  7361 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-06 14:19:23.005  7346  7346 D TimaKeyStoreProvider: TimaSignature is unavailable
07-06 14:19:23.005  1014  1039 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7361 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-06 14:19:23.005  7346  7346 D ActivityThread: Added TimaKeyStore provider
07-06 14:19:23.005  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
07-06 14:19:23.015  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 14:19:23.015  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 14:19:23.015  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 14:19:23.015  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 14:19:23.015  1014  1014 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-06 14:19:23.015  1014  1014 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-06 14:19:23.015  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
07-06 14:19:23.015  1014  1014 V EnterpriseBillingPolicy: uID is 10170
07-06 14:19:23.015  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
07-06 14:19:23.015  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
07-06 14:19:23.025  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
07-06 14:19:23.025  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-06 14:19:23.025  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-06 14:19:23.025  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
07-06 14:19:23.025  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
07-06 14:19:23.025  7374  7374 E Zygote  : MountEmulatedStorage()
07-06 14:19:23.035  7374  7374 E Zygote  : v2
07-06 14:19:23.035  7374  7374 I libpersona: KNOX_SDCARD checking this for 1000
07-06 14:19:23.035  1014  4014 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
07-06 14:19:23.035  1014  4014 D SecContentProvider2: mCursor = null
07-06 14:19:23.035  7361  7361 D TimaKeyStoreProvider: TimaSignature is unavailable
07-06 14:19:23.035  7374  7374 I libpersona: KNOX_SDCARD not a persona
07-06 14:19:23.035  7374  7374 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-06 14:19:23.035  7361  7361 D ActivityThread: Added TimaKeyStore provider
07-06 14:19:23.035  1014  1039 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=7374 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-06 14:19:23.035  1014  3881 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
07-06 14:19:23.035  1014  3881 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
07-06 14:19:23.035  1014  3881 W ActivityManager: userId = 0, bbcId = -10000
07-06 14:19:23.035  1014  3881 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-06 14:19:23.035  1014  3881 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
07-06 14:19:23.045  7374  7374 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-06 14:19:23.045  7374  7374 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-06 14:19:23.045  1457  1457 D RegisteredComponentCache: Collect Tech packages for Knox
07-06 14:19:23.055  6155  7384 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
07-06 14:19:23.055  6155  7384 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
07-06 14:19:23.055  1014  1014 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-06 14:19:23.055  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
07-06 14:19:23.055  1014  3464 D SSRM:bc : MSG_TYPE_APP_REMOVED::
07-06 14:19:23.055  1014  1014 V EnterpriseBillingPolicy: uID is 10170
07-06 14:19:23.055  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
07-06 14:19:23.055  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
07-06 14:19:23.055  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
07-06 14:19:23.055  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-06 14:19:23.055  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-06 14:19:23.055  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
07-06 14:19:23.065  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
07-06 14:19:23.065  1014  1014 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
07-06 14:19:23.065  1014  1158 D TaskPersister: removeObsoleteFile: deleting file=44_task.xml
07-06 14:19:23.065  1457  1457 D PersonaManager: isKioskContainerExistOnDevice
07-06 14:19:23.075  1014  3881 I TactileAssist: enable value -1
07-06 14:19:23.075  1014  3881 I TactileAssist: internal enable value -1
07-06 14:19:23.075  1014  3881 I TactileAssist: intensity value -1
07-06 14:19:23.075  1014  3881 I TactileAssist: saveAppList value true
07-06 14:19:23.085  7374  7374 D TimaKeyStoreProvider: TimaSignature is unavailable
07-06 14:19:23.085  7374  7374 D ActivityThread: Added TimaKeyStore provider
07-06 14:19:23.085  1014  3881 I TactileAssist: List of disabled apps :
07-06 14:19:23.105  2689  7345 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
07-06 14:19:23.125  6409  6409 D Compatibility: onReceive() it will make start service
07-06 14:19:23.125  1014  3882 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
07-06 14:19:23.125  1014  3882 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
07-06 14:19:23.125  1014  3882 W ActivityManager: userId = 0, bbcId = -10000
07-06 14:19:23.125  1014  3882 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-06 14:19:23.125  1014  3882 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
07-06 14:19:23.145  1014  1302 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
07-06 14:19:23.145  1014  1302 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
07-06 14:19:23.145  6409  7394 D Compatibility: onHandleIntent()
07-06 14:19:23.145  1014  1302 W ActivityManager: userId = 0, bbcId = -10000
07-06 14:19:23.145  1014  1301 E Watchdog: !@Sync 55
07-06 14:19:23.145  1014  1302 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-06 14:19:23.145  1014  1302 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
07-06 14:19:23.145  6409  7394 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10170, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
07-06 14:19:23.155  6409  7394 D Compatibility: found: 2
07-06 14:19:23.155  6409  7394 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
07-06 14:19:23.155  6409  7394 D Compatibility: skipping ResolveInfo{1d85c561 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
07-06 14:19:23.155  6409  7394 D Compatibility: considering ResolveInfo{1e1ec886 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
07-06 14:19:23.155  6409  7394 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
07-06 14:19:23.155  6425  7395 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
07-06 14:19:23.155  7361  7361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
07-06 14:19:23.165  2689  7345 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
07-06 14:19:23.165  6409  7394 D Compatibility: enabling receiver ResolveInfo{11d86547 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
07-06 14:19:23.165  1014  1348 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
07-06 14:19:23.165  1014  1348 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
07-06 14:19:23.165  1014  1348 W ActivityManager: userId = 0, bbcId = -10000
07-06 14:19:23.165  1014  1348 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-06 14:19:23.165  1014  1348 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
07-06 14:19:23.165  7374  7374 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
07-06 14:19:23.165  2689  7345 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
07-06 14:19:23.175  7346  7346 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
07-06 14:19:23.175  7346  7346 D elm:15121: ELMEngine.ELMEngine( context ).
07-06 14:19:23.175  7346  7346 D elm:15121: MDMBridge.setEnterpriseBridge()
07-06 14:19:23.185  1014  1133 D SecContentProvider2: uri = -1 selection = getSealedState
07-06 14:19:23.185  1014  1133 D SecContentProvider2: mCursor = null
07-06 14:19:23.185  7374  7374 I PopupuiReceiver_KNOX: getSealedState : true
07-06 14:19:23.185  6409  7394 D Compatibility: enabling receiver ResolveInfo{23e8f174 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
07-06 14:19:23.185  1014  1495 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
07-06 14:19:23.185  1014  1027 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
07-06 14:19:23.185  1014  1027 D SecContentProvider2: mCursor = null
07-06 14:19:23.185  7374  7374 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
07-06 14:19:23.185  1014  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 14:19:23.185  1014  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 14:19:23.185  1014  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 14:19:23.185  1014  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 14:19:23.195  1014  1514 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
07-06 14:19:23.195  1014  1514 D SecContentProvider2: mCursor = null
07-06 14:19:23.205  7397  7397 E Zygote  : MountEmulatedStorage()
07-06 14:19:23.205  7397  7397 I libpersona: KNOX_SDCARD checking this for 10055
07-06 14:19:23.205  7397  7397 E Zygote  : v2
07-06 14:19:23.205  7397  7397 I libpersona: KNOX_SDCARD not a persona
07-06 14:19:23.205  7374  7374 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
07-06 14:19:23.205  7374  7374 D PopupuiReceiver: Action package removed
07-06 14:19:23.205  7397  7397 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-06 14:19:23.205  2689  2689 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
07-06 14:19:23.205  6409  7394 D Compatibility: enabling receiver ResolveInfo{3778569d com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
07-06 14:19:23.205  7397  7397 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-06 14:19:23.205  1014  1054 I art     : Explicit concurrent mark sweep GC freed 28146(2MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 23MB/35MB, paused 8.916ms total 342.538ms
07-06 14:19:23.205  7397  7397 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-06 14:19:23.215  1014  1495 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=7397 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
07-06 14:19:23.225  6409  7394 D Compatibility: enabling receiver ResolveInfo{230ee712 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
07-06 14:19:23.225  1014  1495 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
07-06 14:19:23.225  1014  1054 D PackageManager: delete codoeFile: 
07-06 14:19:23.225  6409  7394 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
07-06 14:19:23.225  1014  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 14:19:23.225  1014  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 14:19:23.225  1014  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 14:19:23.225  1014  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 14:19:23.225  1014  1054 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
07-06 14:19:23.225  1014  1054 I AASA_removePackage: UID=10170 Target=com.test.thalitest
07-06 14:19:23.225  1014  1054 D PackageManager: result of delete: 1{910640970}
07-06 14:19:23.235  7334  7334 D AndroidRuntime: Shutting down VM
07-06 14:19:23.235  7410  7410 E Zygote  : MountEmulatedStorage()
07-06 14:19:23.235  7410  7410 I libpersona: KNOX_SDCARD checking this for 1000
07-06 14:19:23.235  7410  7410 E Zygote  : v2
07-06 14:19:23.235  7410  7410 I libpersona: KNOX_SDCARD not a persona
07-06 14:19:23.245  7410  7410 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-06 14:19:23.245  1014  1054 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
07-06 14:19:23.245  1014  1054 D PackageManager: userId{-1}
07-06 14:19:23.245  1014  1054 D PackageManager: andCode{true}
07-06 14:19:23.245  7410  7410 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-06 14:19:23.245  1014  1495 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7410 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-06 14:19:23.245  1014  1498 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
07-06 14:19:23.245  1014  1498 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
07-06 14:19:23.245  1014  1498 W ActivityManager: userId = 0, bbcId = -10000
07-06 14:19:23.245  1014  1498 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-06 14:19:23.245  1014  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
07-06 14:19:23.245  7410  7410 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-06 14:19:23.265  7346  7346 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
07-06 14:19:23.265  1014  1495 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
07-06 14:19:23.265  1014  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 14:19:23.265  1014  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 14:19:23.265  1014  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 14:19:23.265  1014  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 14:19:23.275  7397  7397 D TimaKeyStoreProvider: TimaSignature is unavailable
07-06 14:19:23.275  7346  7346 D elm:15121: ElmAgentService : onCreate()
07-06 14:19:23.275  7397  7397 D ActivityThread: Added TimaKeyStore provider
07-06 14:19:23.275  7346  7425 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
07-06 14:19:23.275  7346  7425 D elm:15121: MainReceiver.listeningToPackageRemoved()
07-06 14:19:23.275  7346  7425 D elm:15121: MDMBridge.getInstance()
07-06 14:19:23.275  7346  7425 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
07-06 14:19:23.275  7346  7425 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
07-06 14:19:23.285  7428  7428 E Zygote  : MountEmulatedStorage()
07-06 14:19:23.285  7428  7428 I libpersona: KNOX_SDCARD checking this for 10145
07-06 14:19:23.285  7428  7428 E Zygote  : v2
07-06 14:19:23.285  7428  7428 I libpersona: KNOX_SDCARD not a persona
07-06 14:19:23.285  7428  7428 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-06 14:19:23.285  1014  1495 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7428 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-06 14:19:23.285  7428  7428 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-06 14:19:23.285  7428  7428 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-06 14:19:23.285  7410  7410 D TimaKeyStoreProvider: TimaSignature is unavailable
07-06 14:19:23.285  7410  7410 D ActivityThread: Added TimaKeyStore provider
07-06 14:19:23.305  1014  1495 I ActivityManager: Killing 6246:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
07-06 14:19:23.305  1014  1054 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
07-06 14:19:23.315  7428  7428 D TimaKeyStoreProvider: TimaSignature is unavailable
07-06 14:19:23.315  7428  7428 D ActivityThread: Added TimaKeyStore provider
07-06 14:19:23.325  2852  2852 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
07-06 14:19:23.325  7346  7346 D elm:15121: ElmAgentService : onDestroy().
07-06 14:19:23.325  2852  2852 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-06 14:19:23.325  2852  2852 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
07-06 14:19:23.325  2852  2852 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
07-06 14:19:23.325  2852  2852 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
07-06 14:19:23.325  2852  2852 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
07-06 14:19:23.325  2852  2852 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
07-06 14:19:23.325  2852  2852 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-06 14:19:23.325  2852  2852 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-06 14:19:23.325  2852  2852 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-06 14:19:23.325  2852  2852 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-06 14:19:23.325  2852  2852 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-06 14:19:23.325  2852  2852 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-06 14:19:23.325  2852  2852 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-06 14:19:23.335  7397  7397 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
07-06 14:19:23.345  1014  1014 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
07-06 14:19:23.345  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 14:19:23.345  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 14:19:23.345  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 14:19:23.345  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 14:19:23.345  7410  7410 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-06 14:19:23.355  7445  7445 E Zygote  : MountEmulatedStorage()
07-06 14:19:23.355  7445  7445 E Zygote  : v2
07-06 14:19:23.355  7445  7445 I libpersona: KNOX_SDCARD checking this for 1000
07-06 14:19:23.355  7445  7445 I libpersona: KNOX_SDCARD not a persona
07-06 14:19:23.355  7445  7445 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-06 14:19:23.355  1014  1014 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7445 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-06 14:19:23.365  7445  7445 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-06 14:19:23.365  7445  7445 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-06 14:19:23.365  1014  1495 I ActivityManager: Killing 6289:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
07-06 14:19:23.375  1014  3881 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
07-06 14:19:23.375  1014  3881 W ActivityManager: userId = 0, bbcId = -10000
07-06 14:19:23.375  1014  3881 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-06 14:19:23.375  1014  3881 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
07-06 14:19:23.375  7397  7397 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
07-06 14:19:23.375  7397  7397 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
07-06 14:19:23.375  7397  7397 D UserAnalysis: Create SecureDbHelper
07-06 14:19:23.385  1014  1514 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-06 14:19:23.385  7445  7445 D TimaKeyStoreProvider: TimaSignature is unavailable
07-06 14:19:23.385  1014  1514 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
07-06 14:19:23.385  7445  7445 D ActivityThread: Added TimaKeyStore provider
07-06 14:19:23.385  7428  7428 D ThemeInfoUtil: getCurrentFestivalName is [null]
07-06 14:19:23.385  7428  7428 D ThemeInfoUtil: isCurrentFestival = false
07-06 14:19:23.385  1014  1514 W ActivityManager: userId = 0, bbcId = -10000
07-06 14:19:23.385  1014  1514 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-06 14:19:23.385  1014  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-06 14:19:23.395  1014  1026 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
07-06 14:19:23.395  7410  7410 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
07-06 14:19:23.395  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 14:19:23.395  1014  1514 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
07-06 14:19:23.395  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 14:19:23.395  1014  1514 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
07-06 14:19:23.395  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 14:19:23.395  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 14:19:23.415  7460  7460 E Zygote  : MountEmulatedStorage()
07-06 14:19:23.415  7460  7460 E Zygote  : v2
07-06 14:19:23.415  7460  7460 I libpersona: KNOX_SDCARD checking this for 10148
07-06 14:19:23.415  7460  7460 I libpersona: KNOX_SDCARD not a persona
07-06 14:19:23.415  7460  7460 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-06 14:19:23.425  7460  7460 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-06 14:19:23.425  1014  1026 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7460 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
07-06 14:19:23.425  7460  7460 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-06 14:19:23.425  1014  1302 I ActivityManager: Killing 6319:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
07-06 14:19:23.425  1014  3882 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
07-06 14:19:23.435  1014  3882 W ActivityManager: userId = 0, bbcId = -10000
07-06 14:19:23.435  1014  3882 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-06 14:19:23.435  1014  3882 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-06 14:19:23.445  7334  7334 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
07-06 14:19:23.455  1014  3881 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-06 14:19:23.455  1014  3881 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
07-06 14:19:23.455  1014  3881 W ActivityManager: userId = 0, bbcId = -10000
07-06 14:19:23.455  1014  3881 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-06 14:19:23.455  1014  3881 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-06 14:19:23.455   311   311 I art     : Explicit concurrent mark sweep GC freed 8739(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 871us total 36.175ms
07-06 14:19:23.465  7460  7460 D TimaKeyStoreProvider: TimaSignature is unavailable,
07-06 14:19:23.465  7460  7460 D ActivityThread: Added TimaKeyStore provider

```
