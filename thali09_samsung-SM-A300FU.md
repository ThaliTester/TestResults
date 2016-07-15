#### Test 75789268514fc25_thali09_samsung-SM-A300FU Logs


```
--------- beginning of main,
07-15 15:21:45.987   294   294 E SMD     : DCD OFF
07-15 15:21:46.247  6672  6672 D AndroidRuntime: 
07-15 15:21:46.247  6672  6672 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-15 15:21:46.247  6672  6672 D AndroidRuntime: CheckJNI is OFF
07-15 15:21:46.247  6672  6672 D AndroidRuntime: readGMSProperty: start
07-15 15:21:46.247  6672  6672 D AndroidRuntime: readGMSProperty: already setted!!
07-15 15:21:46.247  6672  6672 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-15 15:21:46.247  6672  6672 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-15 15:21:46.247  6672  6672 D AndroidRuntime: readGMSProperty: end
07-15 15:21:46.247  6672  6672 D AndroidRuntime: addProductProperty: start
07-15 15:21:46.387  6672  6672 E AffinityControl: AffinityControl: registerfunction enter
07-15 15:21:46.407  6672  6672 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-15 15:21:46.417  1017  1530 E PersonaManagerService: inState():  stateMachine is null !!
07-15 15:21:46.417  1017  1530 I PersonaManagerService: PersonaId don't exist
07-15 15:21:46.417  1017  1530 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
07-15 15:21:46.427  1017  1530 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
07-15 15:21:46.437  1017  1530 W ActivityManager: mDVFSHelper.acquire()
07-15 15:21:46.437  1017  1530 D FocusedStackFrame: Set to : 0
07-15 15:21:46.447  1017  1047 D PhoneWindow: *FMB* installDecor mIsFloating : false
07-15 15:21:46.447  1017  1047 D PhoneWindow: *FMB* installDecor flags : -2122120936
07-15 15:21:46.447  1017  1530 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:46.447  1017  1530 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:46.447  1017  1530 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:46.447  1017  1530 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:46.467  1017  1530 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6683 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-15 15:21:46.467  6683  6683 E Zygote  : MountEmulatedStorage()
07-15 15:21:46.467  6683  6683 I libpersona: KNOX_SDCARD checking this for 10170
07-15 15:21:46.467  6683  6683 E Zygote  : v2
07-15 15:21:46.467  6683  6683 I libpersona: KNOX_SDCARD not a persona
07-15 15:21:46.467  1017  1530 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
07-15 15:21:46.467  1017  1530 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-15 15:21:46.467  1017  1530 D InputDispatcher: Focused application set to: xxxx
07-15 15:21:46.467  1017  1530 D InputDispatcher: Focus left window: 1495
07-15 15:21:46.467  6672  6672 D AndroidRuntime: Shutting down VM
07-15 15:21:46.467  6683  6683 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-15 15:21:46.467  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
07-15 15:21:46.467  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
07-15 15:21:46.467   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
07-15 15:21:46.467  6683  6683 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-15 15:21:46.477  6683  6683 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
07-15 15:21:46.487  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-15 15:21:46.487  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
07-15 15:21:46.497  6683  6683 D TimaKeyStoreProvider: TimaSignature is unavailable
07-15 15:21:46.497  6683  6683 D ActivityThread: Added TimaKeyStore provider
07-15 15:21:46.497  1017  1030 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
07-15 15:21:46.497  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-15 15:21:46.507  1017  1030 D PersonaManager: isKioskContainerExistOnDevice
07-15 15:21:46.527  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
07-15 15:21:46.547   258  1160 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
07-15 15:21:46.547   258   446 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
07-15 15:21:46.557  1495  1495 V ActivityThread: updateVisibility : ActivityRecord{3a46e938 token=android.os.BinderProxy@182d9430 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-15 15:21:46.557  1495  1495 D Launcher: onTrimMemory. Level: 20
07-15 15:21:46.627  6683  6683 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
07-15 15:21:46.637  6683  6683 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 9401-9403)
07-15 15:21:46.637  6683  6683 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-15 15:21:46.657  6683  6683 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3b6de39f}
07-15 15:21:46.657  6683  6683 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-15 15:21:46.667  6672  6672 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
07-15 15:21:46.677  6683  6683 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,07-15 15:21:46.707  6683  6683 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-15 15:21:46.707  6683  6683 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-15 15:21:46.707  6683  6683 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-15 15:21:46.737  6683  6683 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,07-15 15:21:46.737  6683  6683 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,07-15 15:21:46.737  6683  6683 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,07-15 15:21:46.747  6683  6683 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
07-15 15:21:46.747  6683  6683 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
07-15 15:21:46.747  6683  6683 I Adreno-EGL: Build Date: 04/06/15 Mon
07-15 15:21:46.747  6683  6683 I Adreno-EGL: Local Branch: 
07-15 15:21:46.747  6683  6683 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
07-15 15:21:46.747  6683  6683 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
07-15 15:21:46.747  6683  6683 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,07-15 15:21:46.947  6683  6709 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,07-15 15:21:46.997  6683  6683 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-15 15:21:47.007  6683  6683 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-15 15:21:47.017  1017  1042 W ActivityManager: Activity pause timeout for ActivityRecord{e2d6e36 u0 com.test.thalitest/.MainActivity t9}
,07-15 15:21:47.017  6683  6683 D PhoneWindow: *FMB* installDecor mIsFloating : false
07-15 15:21:47.017  6683  6683 D PhoneWindow: *FMB* installDecor flags : -2139027200
,07-15 15:21:47.027  6683  6683 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-15 15:21:47.037  6683  6683 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-15 15:21:47.037  6683  6683 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-15 15:21:47.097  6683  6722 D OpenGLRenderer: Render dirty regions requested: true
,07-15 15:21:47.107  1017  1530 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,07-15 15:21:47.107  1017  1530 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-15 15:21:47.107  1017  1530 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,07-15 15:21:47.107  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-15 15:21:47.107  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,07-15 15:21:47.167  6683  6683 V ActivityThread: updateVisibility : ActivityRecord{16fd7cc6 token=android.os.BinderProxy@1e379b08 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,07-15 15:21:47.167  6683  6683 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
07-15 15:21:47.167  6683  6683 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,07-15 15:21:47.167   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,07-15 15:21:47.177  1017  1535 D InputDispatcher: Focus entered window: 6683
,07-15 15:21:47.177  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,07-15 15:21:47.177  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,07-15 15:21:47.177  6683  6683 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
07-15 15:21:47.187  6683  6722 I OpenGLRenderer: Initialized EGL, version 1.4
07-15 15:21:47.187  6683  6722 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
07-15 15:21:47.187  6683  6722 D OpenGLRenderer: Enabling debug mode 0
,07-15 15:21:47.207  1017  1501 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-15 15:21:47.207  1017  6725 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-15 15:21:47.207  1174  1174 I StatusBar: Icon Only
07-15 15:21:47.207  1174  1174 D PanelView: There is/are notification(s) 
,07-15 15:21:47.207  6683  6683 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,07-15 15:21:47.207  6683  6683 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1e379b08 time:149979
,07-15 15:21:47.237  1017  1047 I ActivityManager: Displayed Component not be shown by security: +717ms (total +35s362ms)
,07-15 15:21:47.237  1017  1047 W ActivityManager: mDVFSHelper.release()
07-15 15:21:47.237  1017  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{e2d6e36 u0 com.test.thalitest/.MainActivity t9} time:150001
,07-15 15:21:47.237   258   446 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,07-15 15:21:47.237   258   449 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,07-15 15:21:47.257  1869  1869 I SamsungIME: getCurrentCandidateView
,07-15 15:21:47.307  6683  6683 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6683
,07-15 15:21:47.347  1869  1869 D SamsungIME: Dismiss ExpandCandiate
,07-15 15:21:47.437  6683  6683 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-15 15:21:47.567  1869  1869 I SamsungIME: getDebugLevel  : 0x4f4c
,07-15 15:21:47.607  1869  1869 I SamsungIME: getDebugLevel  : 0x4f4c
,07-15 15:21:47.617  1869  1869 I SamsungIME: KeybaordView init() : load resources
,07-15 15:21:47.637  6683  6727 D jxcore_app_log: JniHelper::setJavaVM(0xb70492f0), pthread_self() = -1218817824
,07-15 15:21:47.647  1869  1869 I SamsungIME: getCurrentKeyboard
07-15 15:21:47.647  1869  1869 I SamsungIME: getTextKeyboard
,07-15 15:21:47.647  6683  6727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-15 15:21:47.647  6683  6727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-15 15:21:47.647  6683  6727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-15 15:21:47.647  6683  6727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-15 15:21:47.647  6683  6727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-15 15:21:47.647  6683  6727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3884a376 added. We now have 1 listener(s)
07-15 15:21:47.657  6683  6727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
07-15 15:21:47.657  6683  6727 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
07-15 15:21:47.657  6683  6727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-15 15:21:47.657  6683  6727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-15 15:21:47.667  6683  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-15 15:21:47.667  6683  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-15 15:21:47.667  6683  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-15 15:21:47.667  6683  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
07-15 15:21:47.667  6683  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-15 15:21:47.667  6683  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-15 15:21:47.667  6683  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-15 15:21:47.667  6683  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-15 15:21:47.667  6683  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-15 15:21:47.667  6683  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-15 15:21:47.667  6683  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,07-15 15:21:47.667  6683  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1574624d added. We now have 1 listener(s)
07-15 15:21:47.667  6683  6727 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-15 15:21:47.677  6683  6727 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,07-15 15:21:47.677  6683  6727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-15 15:21:47.677  6683  6727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-15 15:21:47.677  6683  6727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-15 15:21:47.677  6683  6727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-15 15:21:47.677  1869  1869 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
07-15 15:21:47.677  6683  6727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-15 15:21:47.677  6683  6727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,07-15 15:21:47.687  6683  6727 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-15 15:21:47.687  6683  6727 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:21:47.687  6683  6727 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-15 15:21:47.687  6683  6727 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:21:47.687  6683  6727 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:21:47.687  6683  6727 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-15 15:21:47.687  6683  6727 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-15 15:21:47.687  6683  6727 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-15 15:21:47.687  6683  6727 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-15 15:21:47.687  6683  6727 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-15 15:21:47.687  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:21:47.687  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:21:47.687  6683  6727 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-15 15:21:47.697  6683  6727 D io.jxcore.node.JXcoreExtension: Unit Tests on
,07-15 15:21:47.727  6683  6683 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-15 15:21:48.257  6683  6732 W jxcore-log: Initializing JXcore engine
07-15 15:21:48.257  6683  6732 W jxcore-log: JXcore engine is ready
,07-15 15:21:48.307  2008  2008 E audit   : type=1400 msg=audit(1468588908.307:205): avc:  denied  { ioctl } for  pid=6732 comm="Thread-1198" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-15 15:21:48.307  2008  2008 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
07-15 15:21:48.307  2008  2008 E audit   : type=1300 msg=audit(1468588908.307:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=9efc08f8 items=0 ppid=314 ppcomm=main pid=6732 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1198" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
07-15 15:21:48.307  2008  2008 E audit   : type=1320 msg=audit(1468588908.307:205): 
,07-15 15:21:48.317  6683  6732 W jxcore-log: Starting JXcore engine
,07-15 15:21:48.417  6683  6732 W jxcore-log: Platform android
07-15 15:21:48.417  6683  6732 W jxcore-log: 
07-15 15:21:48.417  6683  6732 W jxcore-log: Process ARCH arm
07-15 15:21:48.417  6683  6732 W jxcore-log: 
,07-15 15:21:48.627  6683  6732 I jxcore-log: JXcore Cordova bridge is ready!
07-15 15:21:48.627  6683  6732 I jxcore-log: 
,07-15 15:21:48.627  6683  6732 W jxcore-log: JXcore engine is started
,07-15 15:21:48.637  6683  6727 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-15 15:21:48.637  6683  6683 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-15 15:21:48.647  6683  6732 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
07-15 15:21:48.647  6683  6732 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-15 15:21:48.647  6683  6683 I chromium: [INFO:CONSOLE(57)] "app.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,07-15 15:21:48.647  6683  6683 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-15 15:21:48.647  1017  3545 D FocusedStackFrame: Set to : 0
07-15 15:21:48.657  1017  3545 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-15 15:21:48.657  1017  3545 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
07-15 15:21:48.657  1017  3545 D InputDispatcher: Focused application set to: xxxx
07-15 15:21:48.657  1017  3545 D InputDispatcher: Focus left window: 6683
07-15 15:21:48.657  1017  3545 I ActivityManager: Killing 6286:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
07-15 15:21:48.667  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-15 15:21:48.667  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
07-15 15:21:48.667  6683  6683 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,07-15 15:21:48.667  6683  6683 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
,07-15 15:21:48.667  6683  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-15 15:21:48.667  6683  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-15 15:21:48.667  6683  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:48.667  6683  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-15 15:21:48.667  6683  6683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3884a376 removed from the list
,07-15 15:21:48.667  6683  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:48.667  6683  6727 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 21ms. Plugin should use CordovaInterface.getThreadPool().
07-15 15:21:48.677  6683  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1574624d removed from the list
07-15 15:21:48.677  6683  6683 D io.jxcore.node.ConnectivityMonitor: stop
,07-15 15:21:48.677  6683  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,07-15 15:21:48.677  6683  6683 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-15 15:21:48.687   258   446 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
,07-15 15:21:48.687   258  1160 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,07-15 15:21:48.687  1017  1135 W ActivityManager: mDVFSHelper.acquire()
,07-15 15:21:48.697  1017  1135 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,07-15 15:21:48.717  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,07-15 15:21:48.717  1495  1495 D Launcher: onRestart, Launcher: 878123707
,07-15 15:21:48.717  1495  1495 D Launcher: onStart, Launcher: 878123707
,07-15 15:21:48.717  1495  1495 D Launcher.HomeView: onStart
,07-15 15:21:48.727  1495  1495 D Launcher: onResume, Launcher: 878123707
,07-15 15:21:48.727  1017  1030 D SettingsProvider: name = kids_home_mode
07-15 15:21:48.727  1017  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-15 15:21:48.727  1017  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-15 15:21:48.727  1017  1030 D SettingsProvider: selectionArgs: false
07-15 15:21:48.727  1017  1030 D SettingsProvider: selectionArgs: 10006
07-15 15:21:48.727  1017  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-15 15:21:48.727  1017  1030 D SettingsProvider: ret = -1
,07-15 15:21:48.727  1495  1495 D Launcher.HomeView: onResume
,07-15 15:21:48.737  1495  1495 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,07-15 15:21:48.737  1495  1495 D MenuAppsGridFragment: onResume
,07-15 15:21:48.737  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
07-15 15:21:48.737  1017  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-15 15:21:48.737  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,07-15 15:21:48.737  1495  1495 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,07-15 15:21:48.737  1495  1495 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,07-15 15:21:48.747  1017  4003 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=7, mSplitNum[2]=9, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=11
,07-15 15:21:48.747  1017  4003 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,07-15 15:21:48.747  1017  4003 W ActivityManager: userId = 0, bbcId = -10000
,07-15 15:21:48.747  1017  4003 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-15 15:21:48.747  1017  4003 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,07-15 15:21:48.747  1017  4003 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,07-15 15:21:48.747  1017  4003 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-15 15:21:48.747  1017  4003 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:48.747  1017  4003 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:48.747  1017  4003 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-15 15:21:48.757  6738  6738 E Zygote  : MountEmulatedStorage()
,07-15 15:21:48.757  6738  6738 I libpersona: KNOX_SDCARD checking this for 10039
07-15 15:21:48.757  6738  6738 E Zygote  : v2
07-15 15:21:48.757  6738  6738 I libpersona: KNOX_SDCARD not a persona
,07-15 15:21:48.767  6738  6738 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,07-15 15:21:48.767  1017  4003 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=6738 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
07-15 15:21:48.767  6738  6738 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-15 15:21:48.767  6738  6738 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-15 15:21:48.777  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
07-15 15:21:48.777  1017  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-15 15:21:48.777  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,07-15 15:21:48.777  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
07-15 15:21:48.777  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.dualclockdigital, hostingType: broadcast
07-15 15:21:48.777  1017  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-15 15:21:48.777  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:48.777  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.dualclockdigital
07-15 15:21:48.777  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:48.777  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:48.777  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-15 15:21:48.797  6752  6752 E Zygote  : MountEmulatedStorage(),
07-15 15:21:48.797  6752  6752 E Zygote  : v2
07-15 15:21:48.797  6752  6752 I libpersona: KNOX_SDCARD checking this for 10089
07-15 15:21:48.797  6752  6752 I libpersona: KNOX_SDCARD not a persona
07-15 15:21:48.797  6752  6752 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-15 15:21:48.797  1017  1042 I ActivityManager: Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=6752 uid=10089 gids={50089, 9997, 3003} abi=armeabi-v7a
,07-15 15:21:48.797  6752  6752 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-15 15:21:48.807  6752  6752 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
07-15 15:21:48.807  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
07-15 15:21:48.807  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
07-15 15:21:48.807  1017  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-15 15:21:48.807  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,07-15 15:21:48.807  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:48.807  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-15 15:21:48.807  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:48.807  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-15 15:21:48.827  6738  6738 D TimaKeyStoreProvider: TimaSignature is unavailable,
07-15 15:21:48.827  6738  6738 D ActivityThread: Added TimaKeyStore provider
,07-15 15:21:48.827  6752  6752 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-15 15:21:48.827  6752  6752 D ActivityThread: Added TimaKeyStore provider
,07-15 15:21:48.827  6768  6768 E Zygote  : MountEmulatedStorage(),
07-15 15:21:48.827  6768  6768 I libpersona: KNOX_SDCARD checking this for 10139
07-15 15:21:48.827  6768  6768 E Zygote  : v2
07-15 15:21:48.827  6768  6768 I libpersona: KNOX_SDCARD not a persona
07-15 15:21:48.827  6768  6768 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-15 15:21:48.837  1017  1042 I ActivityManager: Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=6768 uid=10139 gids={50139, 9997, 1028, 1015} abi=armeabi-v7a,
07-15 15:21:48.837  1017  1317 D ActivityManager: handle home activity for 0
07-15 15:21:48.837  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
07-15 15:21:48.837  1017  1317 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
07-15 15:21:48.837  1017  1317 D KnoxTimeoutHandler: post home show event for user 0
07-15 15:21:48.837  1017  1317 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-15 15:21:48.837  1017  1317 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-15 15:21:48.837  1017  1317 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,07-15 15:21:48.837  1017  1017 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
07-15 15:21:48.837  1017  1017 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
07-15 15:21:48.837  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-15 15:21:48.837  1495  1495 D Launcher.HomeView: onPause
07-15 15:21:48.837  1495  1495 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,07-15 15:21:48.837  6768  6768 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-15 15:21:48.837  6768  6768 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-15 15:21:48.857  6768  6768 D TimaKeyStoreProvider: TimaSignature is unavailable
07-15 15:21:48.857  6768  6768 D ActivityThread: Added TimaKeyStore provider
,07-15 15:21:48.857   258   258 I SurfaceFlinger: id=14 createSurf (540x960),1 flag=4, Mauncher
,07-15 15:21:48.867  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-15 15:21:48.867  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-15 15:21:48.867  6752  6752 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-15 15:21:48.867  6752  6752 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,07-15 15:21:48.877  1017  1318 D InputDispatcher: Focus entered window: 1495
,07-15 15:21:48.877  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-15 15:21:48.877  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
07-15 15:21:48.877  1495  1495 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,07-15 15:21:48.877  1017  4003 W ActivityManager: userId = 0, bbcId = -10000
07-15 15:21:48.877  1017  4003 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1495, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
07-15 15:21:48.877  1017  4003 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-15 15:21:48.877  1017  4003 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,07-15 15:21:48.877  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
07-15 15:21:48.877  1017  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-15 15:21:48.877  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,07-15 15:21:48.887  2631  2631 D Recents_RecreateReceiver: onReceive by home
,07-15 15:21:48.887  6738  6738 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,07-15 15:21:48.887  6738  6738 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-15 15:21:48.887  6738  6738 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-15 15:21:48.887  6738  6738 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
07-15 15:21:48.887  6738  6738 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-15 15:21:48.887  6738  6738 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
07-15 15:21:48.887  6738  6738 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-15 15:21:48.887  1017  1535 W ActivityManager: userId = 0, bbcId = -10000
07-15 15:21:48.887  1017  1535 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
07-15 15:21:48.887  1017  1535 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-15 15:21:48.887  1017  1535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
07-15 15:21:48.897  1017  1535 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:48.897  1017  1535 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:48.897  1017  1535 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:48.897  1017  1535 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-15 15:21:48.897  1495  1495 D Launcher.HomeView: onStop
07-15 15:21:48.897  1495  1495 V ActivityThread: updateVisibility : ActivityRecord{3a46e938 token=android.os.BinderProxy@182d9430 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,07-15 15:21:48.897  1017  1029 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-15 15:21:48.907  1174  1174 I StatusBar: Icon Only
07-15 15:21:48.907  1174  1174 D PanelView: There is/are notification(s) 
,07-15 15:21:48.907  1017  6784 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-15 15:21:48.917  1869  1869 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
07-15 15:21:48.917  6785  6785 I libpersona: KNOX_SDCARD checking this for 10084
07-15 15:21:48.917  6785  6785 E Zygote  : MountEmulatedStorage()
07-15 15:21:48.917  6785  6785 I libpersona: KNOX_SDCARD not a persona
07-15 15:21:48.917  6785  6785 E Zygote  : v2
07-15 15:21:48.917  1017  1535 I ActivityManager: Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=6785 uid=10084 gids={50084, 9997} abi=armeabi-v7a
07-15 15:21:48.917  6768  6768 V TaskCloserActivity: TaskCloserActivity enter()
07-15 15:21:48.917  6785  6785 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-15 15:21:48.917  6785  6785 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-15 15:21:48.917  6785  6785 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,07-15 15:21:48.937  6734  6734 D AndroidRuntime: 
07-15 15:21:48.937  6734  6734 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,07-15 15:21:48.937  6768  6768 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,07-15 15:21:48.937  1017  4003 W ActivityManager: userId = 0, bbcId = -10000
,07-15 15:21:48.937  1017  4003 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-15 15:21:48.937  1017  4003 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,07-15 15:21:48.937  6734  6734 D AndroidRuntime: CheckJNI is OFF
07-15 15:21:48.937  6734  6734 D AndroidRuntime: readGMSProperty: start
07-15 15:21:48.937  6734  6734 D AndroidRuntime: readGMSProperty: already setted!!
07-15 15:21:48.937  6734  6734 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-15 15:21:48.937  6734  6734 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-15 15:21:48.937  6734  6734 D AndroidRuntime: readGMSProperty: end
07-15 15:21:48.937  1017  4003 I ActivityManager: Killing 6271:com.osp.app.signin/u0a36 (adj 15): empty #21
07-15 15:21:48.937  6734  6734 D AndroidRuntime: addProductProperty: start
,07-15 15:21:48.947  6683  6683 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,07-15 15:21:48.947  6785  6785 D TimaKeyStoreProvider: TimaSignature is unavailable
07-15 15:21:48.957  6785  6785 D ActivityThread: Added TimaKeyStore provider
,07-15 15:21:48.967  1495  1495 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@182d9430 time:151739
,07-15 15:21:48.977  6785  6785 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-15 15:21:48.987   294   294 E SMD     : DCD OFF
,07-15 15:21:48.987  1017  4005 W ActivityManager: userId = 0, bbcId = -10000
07-15 15:21:48.987  1017  4005 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-15 15:21:48.987  1017  4005 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
07-15 15:21:48.987  1017  4005 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
,07-15 15:21:48.997  1017  4005 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-15 15:21:48.997  1017  4005 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:48.997  1017  4005 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:48.997  1017  4005 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-15 15:21:49.017  6811  6811 E Zygote  : MountEmulatedStorage(),
07-15 15:21:49.017  6811  6811 E Zygote  : v2,
07-15 15:21:49.017  6811  6811 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-15 15:21:49.017  6811  6811 I libpersona: KNOX_SDCARD checking this for 10135
07-15 15:21:49.017  6811  6811 I libpersona: KNOX_SDCARD not a persona
07-15 15:21:49.027  6811  6811 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-15 15:21:49.017  1017  4005 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=6811 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
07-15 15:21:49.017  1017  4005 I ActivityManager: Killing 6308:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21,
07-15 15:21:49.027  6811  6811 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-15 15:21:49.027  1017  1030 D PersonaManager: isKioskContainerExistOnDevice
,07-15 15:21:49.037  1017  1501 I ActivityManager: Killing 6338:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,07-15 15:21:49.037  1017  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1c45f2c5 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t7} time:151806
07-15 15:21:49.037  1017  1047 W ActivityManager: mDVFSHelper.release()
,07-15 15:21:49.057  6811  6811 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-15 15:21:49.057  6811  6811 D ActivityThread: Added TimaKeyStore provider
,07-15 15:21:49.067  6811  6811 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
07-15 15:21:49.067  6811  6811 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-15 15:21:49.067  6811  6811 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
07-15 15:21:49.067  6811  6811 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
07-15 15:21:49.067  6811  6811 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-15 15:21:49.077  6734  6734 E AffinityControl: AffinityControl: registerfunction enter
,07-15 15:21:49.107  6738  6738 D NearbySource: Nearby Source Create!
,07-15 15:21:49.107  6738  6738 D NearbyContext: Nearby Context Create!
,07-15 15:21:49.107  1017  1029 I ActivityManager: Killing 6167:com.android.mms/u0a41 (adj 15): empty #21
07-15 15:21:49.107  6734  6734 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,07-15 15:21:49.137  1017  1501 D PackageManager: START PACKAGE DELETE: observer{793745716}
07-15 15:21:49.137  1017  1501 D PackageManager: pkg{<packageName>}
07-15 15:21:49.137  1017  1501 D PackageManager: user{0}
07-15 15:21:49.137  1017  1501 D PackageManager: caller{2000}
07-15 15:21:49.137  1017  1501 D PackageManager: flags{2}
,07-15 15:21:49.137  1017  1501 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
07-15 15:21:49.137  1017  1501 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
,07-15 15:21:49.137  1017  1501 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
07-15 15:21:49.137  1017  1501 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,07-15 15:21:49.137  1017  1501 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,07-15 15:21:49.137  1017  1055 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,07-15 15:21:49.137  1017  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,07-15 15:21:49.137  1017  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
07-15 15:21:49.137  1017  1055 D ApplicationPolicy: getApplicationUninstallationEnabled
,07-15 15:21:49.137  1017  1055 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,07-15 15:21:49.147   257   533 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
07-15 15:21:49.147   257   533 W Vold    : Returning OperationFailed - no handler for errno 0
,07-15 15:21:49.147  6738  6738 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,07-15 15:21:49.147  6738  6738 D SLinkSource: Samsung link source created
07-15 15:21:49.147  1017  1055 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
,07-15 15:21:49.157  1017  1042 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
,07-15 15:21:49.157  1017  1042 I ActivityManager: Killing 6683:com.test.thalitest/u0a170 (adj 15): stop com.test.thalitest cause uninstall pkg
,07-15 15:21:49.177  1017  1030 D CountryDetector: No listener is left
,07-15 15:21:49.227  1017  1055 W PackageSettings: Skipping PackageSetting{2352dffe com.example.hello/10168} due to missing metadata
,07-15 15:21:49.267  1017  4005 W ActivityManager: Spurious death for ProcessRecord{17ca435d 6683:com.test.thalitest/u0a170}, curProc for 6683: null
,07-15 15:21:49.277  1017  1055 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,07-15 15:21:49.287  1017  1055 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,07-15 15:21:49.347  6438  6438 I art     : Explicit concurrent mark sweep GC freed 591(34KB) AllocSpace objects, 0(0B) LOS objects, 26% free, 5MB/7MB, paused 1ms total 43.043ms
,07-15 15:21:49.347  2764  2764 I art     : Explicit concurrent mark sweep GC freed 23433(1279KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 1.076ms total 49.964ms
,07-15 15:21:49.357  6473  6473 I art     : Explicit concurrent mark sweep GC freed 7698(364KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 3MB/5MB, paused 871us total 64.512ms
,07-15 15:21:49.377  1017  1320 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-15 15:21:49.387  1017  1098 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-15 15:21:49.407  1869  1869 E SamsungIME: mOCRHelper is null
,07-15 15:21:49.417  2040  2209 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-15 15:21:49.417  4697  4697 I art     : Explicit concurrent mark sweep GC freed 24120(1508KB) AllocSpace objects, 9(144KB) LOS objects, 24% free, 12MB/17MB, paused 1.277ms total 135.739ms
,07-15 15:21:49.427  1017  1041 D EnterpriseDeviceManagerService: Package has changed for user 0
,07-15 15:21:49.427  1017  1041 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,07-15 15:21:49.427  1017  1041 W TextServicesManagerService: no available spell checker services found
,07-15 15:21:49.427  1474  1474 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-15 15:21:49.437  1017  1122 V NetworkStats: removeUidsLocked() for UIDs [10170]
07-15 15:21:49.437  1017  1122 D NtpTrustedTime: currentTimeMillis() cache hit
07-15 15:21:49.437  1017  1122 V NetworkStats: performPollLocked(flags=0x3)
,07-15 15:21:49.437  1017  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
,07-15 15:21:49.437  1017  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,07-15 15:21:49.447  1017  1122 V NetworkStats: performPollLocked() took 9ms
,07-15 15:21:49.447  1017  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,07-15 15:21:49.457  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,07-15 15:21:49.457  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,07-15 15:21:49.457  1459  1459 D PersonaManager: isKioskContainerExistOnDevice
,07-15 15:21:49.467  1459  1459 D RegisteredServicesCache: empty dynamic service
,07-15 15:21:49.467  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-15 15:21:49.477  6738  6829 D ContactProvider: getAllContactInfoList Start
07-15 15:21:49.477  1017  3545 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-15 15:21:49.487  6738  6738 D GalleryCacheReady: Receive : home resume
,07-15 15:21:49.487  1017  1320 W ActivityManager: userId = 0, bbcId = -10000
07-15 15:21:49.487  1017  1320 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-15 15:21:49.487  1017  1320 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
07-15 15:21:49.487  1017  1320 D ActivityManager: startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,07-15 15:21:49.487  1017  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:49.487  1017  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:49.487  1017  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:49.487  1017  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-15 15:21:49.497  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-15 15:21:49.507  6831  6831 E Zygote  : MountEmulatedStorage()
07-15 15:21:49.507  6831  6831 E Zygote  : v2
07-15 15:21:49.507  6831  6831 I libpersona: KNOX_SDCARD checking this for 10041
07-15 15:21:49.507  6831  6831 I libpersona: KNOX_SDCARD not a persona,
07-15 15:21:49.507  6831  6831 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-15 15:21:49.507  6831  6831 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,07-15 15:21:49.507  6831  6831 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
07-15 15:21:49.507  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-15 15:21:49.507  1017  1320 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.UIEventReceiver: pid=6831 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,07-15 15:21:49.517  1459  1459 D RegisteredComponentCache: Collect Tech packages for Knox
,07-15 15:21:49.527  1459  1459 D PersonaManager: isKioskContainerExistOnDevice
,07-15 15:21:49.537  6831  6831 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-15 15:21:49.537  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-15 15:21:49.537  6831  6831 D ActivityThread: Added TimaKeyStore provider
,07-15 15:21:49.547  1017  1017 I art     : Explicit concurrent mark sweep GC freed 56556(3MB) AllocSpace objects, 15(240KB) LOS objects, 33% free, 23MB/35MB, paused 3.911ms total 254.532ms
,07-15 15:21:49.547  1017  1055 I art     : WaitForGcToComplete blocked for 130.872ms for cause Explicit
,07-15 15:21:49.657  1017  1041 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,07-15 15:21:49.657  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-15 15:21:49.657  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-15 15:21:49.677  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-15 15:21:49.677  1017  1041 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-15 15:21:49.677  1017  1041 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-15 15:21:49.677  1017  1041 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-15 15:21:49.687  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-15 15:21:49.687  1017  1017 D RCPManagerService: PackageReceiver onReceive()
,07-15 15:21:49.687  1017  1017 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,07-15 15:21:49.687  1017  1017 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
07-15 15:21:49.697  1017  1017 I OTPFW   : PackageRemovalReceiver::onReceive Enter
07-15 15:21:49.697  1017  1017 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,07-15 15:21:49.697  1017  1017 I OTPFW   : ProvisionData::getAllEntries Enter
,07-15 15:21:49.707  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-15 15:21:49.717  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
07-15 15:21:49.717  1017  1017 E OTPFW   : ProvisionData::getAllEntries Table is empty
,07-15 15:21:49.717  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-15 15:21:49.717  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-15 15:21:49.717  1017  1055 I art     : Explicit concurrent mark sweep GC freed 9382(430KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 11.711ms total 175.317ms
,07-15 15:21:49.717  1017  1135 I art     : WaitForGcToComplete blocked for 196.704ms for cause Explicit
,07-15 15:21:49.757  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-15 15:21:49.767  1017  1055 D PackageManager: delete codoeFile: 
,07-15 15:21:49.777  1017  1055 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
,07-15 15:21:49.777  1017  1055 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,07-15 15:21:49.777  1017  1055 D PackageManager: result of delete: 1{793745716}
,07-15 15:21:49.777  6734  6734 D AndroidRuntime: Shutting down VM
,07-15 15:21:49.787  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-15 15:21:49.787  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-15 15:21:49.787  1017  1055 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
07-15 15:21:49.787  1017  1055 D PackageManager: userId{-1}
07-15 15:21:49.787  1017  1055 D PackageManager: andCode{true}
,07-15 15:21:49.787  1017  1055 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,07-15 15:21:49.787  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-15 15:21:49.787  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-15 15:21:49.797  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-15 15:21:49.797  1017  1041 D UsbSettingsManager: clearDefaults: com.test.thalitest
,07-15 15:21:49.797  1017  1041 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,07-15 15:21:49.827  1017  1017 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,07-15 15:21:49.827  1017  1017 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,07-15 15:21:49.837  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
07-15 15:21:49.837  1017  1017 V EnterpriseBillingPolicy: uID is 10170
07-15 15:21:49.837  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
07-15 15:21:49.837  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,07-15 15:21:49.837  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
07-15 15:21:49.837  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-15 15:21:49.837  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-15 15:21:49.837  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,07-15 15:21:49.837  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,07-15 15:21:49.837  1017  1017 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,07-15 15:21:49.837  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
07-15 15:21:49.837  1017  1017 V EnterpriseBillingPolicy: uID is 10170
07-15 15:21:49.837  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
07-15 15:21:49.837  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,07-15 15:21:49.837  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
07-15 15:21:49.837  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-15 15:21:49.837  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-15 15:21:49.837  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,07-15 15:21:49.837  1017  1161 D TaskPersister: removeObsoleteFile: deleting file=9_task.xml
07-15 15:21:49.837  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,07-15 15:21:49.837  1017  3467 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,07-15 15:21:49.837  1017  1017 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
,07-15 15:21:49.887  1017  1135 I art     : Explicit concurrent mark sweep GC freed 9925(481KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 3.464ms total 166.337ms
07-15 15:21:49.887  1017  3545 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
07-15 15:21:49.887  1017  3545 D SecContentProvider2: mCursor = null
,07-15 15:21:49.917  6831  6831 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,07-15 15:21:49.917  6831  6831 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-15 15:21:49.927  6831  6831 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-15 15:21:49.927  6831  6831 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
07-15 15:21:49.927  6831  6831 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,07-15 15:21:49.937  6738  6829 D ContactProvider: getAllContactInfoList End
,07-15 15:21:49.937  6738  6829 I syncContacts: thread: 1183, sync time = 603
,07-15 15:21:49.947  6831  6831 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,07-15 15:21:49.987  6734  6734 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,07-15 15:21:50.037  1017  3467 D SSRM:n  : SIOP:: AP = 310,
,07-15 15:21:50.147  6831  6850 D Mms/ArtClassLoader: init before art
,07-15 15:21:50.147  6831  6831 D Mms/TelephonyPermission: start operation mode monitor

```
