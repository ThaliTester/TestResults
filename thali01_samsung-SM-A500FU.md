#### Test 7214543196063dc_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
,07-05 14:04:32.513   290   290 E SMD     : DCD OFF
07-05 14:04:32.793  6246  6246 D AndroidRuntime: 
07-05 14:04:32.793  6246  6246 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-05 14:04:32.793  6246  6246 D AndroidRuntime: CheckJNI is OFF
07-05 14:04:32.793  6246  6246 D AndroidRuntime: readGMSProperty: start
07-05 14:04:32.793  6246  6246 D AndroidRuntime: readGMSProperty: already setted!!
07-05 14:04:32.793  6246  6246 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-05 14:04:32.793  6246  6246 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-05 14:04:32.793  6246  6246 D AndroidRuntime: readGMSProperty: end
07-05 14:04:32.793  6246  6246 D AndroidRuntime: addProductProperty: start
07-05 14:04:32.953  6246  6246 E AffinityControl: AffinityControl: registerfunction enter
07-05 14:04:32.983  6246  6246 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-05 14:04:32.993  1012  1711 E PersonaManagerService: inState():  stateMachine is null !!
07-05 14:04:32.993  1012  1711 I PersonaManagerService: PersonaId don't exist
07-05 14:04:32.993  1012  1711 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
07-05 14:04:32.993  1012  1711 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
07-05 14:04:33.003  1012  1711 W ActivityManager: mDVFSHelper.acquire()
07-05 14:04:33.013  1012  1711 D FocusedStackFrame: Set to : 0
07-05 14:04:33.013  1012  1044 D PhoneWindow: *FMB* installDecor mIsFloating : false
07-05 14:04:33.013  1012  1044 D PhoneWindow: *FMB* installDecor flags : -2122120936
07-05 14:04:33.023  1012  1711 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:33.023  1012  1711 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:33.023  1012  1711 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:33.023  1012  1711 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:33.033  1012  1711 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6257 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-05 14:04:33.033  1012  1711 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
07-05 14:04:33.033  1012  1711 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-05 14:04:33.033  1012  1711 D InputDispatcher: Focused application set to: xxxx
07-05 14:04:33.033  1012  1711 D InputDispatcher: Focus left window: 1476
07-05 14:04:33.033  6257  6257 E Zygote  : MountEmulatedStorage()
07-05 14:04:33.033  6257  6257 E Zygote  : v2
07-05 14:04:33.033  6257  6257 I libpersona: KNOX_SDCARD checking this for 10155
07-05 14:04:33.033  6257  6257 I libpersona: KNOX_SDCARD not a persona
07-05 14:04:33.033  6246  6246 D AndroidRuntime: Shutting down VM
07-05 14:04:33.033  1012  1044 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
07-05 14:04:33.033  1012  1044 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
07-05 14:04:33.033   257   257 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
07-05 14:04:33.033  6257  6257 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
07-05 14:04:33.043  6257  6257 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
07-05 14:04:33.043  6257  6257 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
07-05 14:04:33.053  1012  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-05 14:04:33.053  1012  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
07-05 14:04:33.063  6257  6257 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 14:04:33.063  6257  6257 D ActivityThread: Added TimaKeyStore provider
07-05 14:04:33.063  1012  3185 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
07-05 14:04:33.073  1012  1042 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-05 14:04:33.083  1012  3185 D PersonaManager: isKioskContainerExistOnDevice
07-05 14:04:33.093  1012  1012 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
07-05 14:04:33.123   257   442 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
07-05 14:04:33.123   257  1900 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
07-05 14:04:33.133  1476  1476 V ActivityThread: updateVisibility : ActivityRecord{25ecee33 token=android.os.BinderProxy@2ab6212a {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-05 14:04:33.133  1476  1476 D Launcher: onTrimMemory. Level: 20
07-05 14:04:33.183  6257  6257 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
07-05 14:04:33.203  6257  6257 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 4630-4632)
07-05 14:04:33.203  6257  6257 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 14:04:33.223  6257  6257 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2ac12065}
07-05 14:04:33.223  6257  6257 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 14:04:33.223  6257  6257 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
07-05 14:04:33.243  6246  6246 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,07-05 14:04:33.253  6257  6257 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-05 14:04:33.253  6257  6257 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 14:04:33.263  6257  6257 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-05 14:04:33.283  6257  6257 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,07-05 14:04:33.283  6257  6257 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,07-05 14:04:33.283  6257  6257 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,07-05 14:04:33.283  6257  6257 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
07-05 14:04:33.283  6257  6257 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
07-05 14:04:33.283  6257  6257 I Adreno-EGL: Build Date: 04/06/15 Mon
07-05 14:04:33.283  6257  6257 I Adreno-EGL: Local Branch: 
07-05 14:04:33.283  6257  6257 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
07-05 14:04:33.283  6257  6257 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
07-05 14:04:33.283  6257  6257 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,07-05 14:04:33.403  6257  6283 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,07-05 14:04:33.443  6257  6257 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-05 14:04:33.463  6257  6257 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-05 14:04:33.463  6257  6257 D PhoneWindow: *FMB* installDecor mIsFloating : false
,07-05 14:04:33.473  6257  6257 D PhoneWindow: *FMB* installDecor flags : -2139027200
,07-05 14:04:33.473  6257  6257 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-05 14:04:33.483  6257  6257 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-05 14:04:33.483  6257  6257 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-05 14:04:33.533  6257  6296 D OpenGLRenderer: Render dirty regions requested: true
,07-05 14:04:33.533  1012  3157 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,07-05 14:04:33.533  1012  3157 D KnoxTimeoutHandler: postActiveUserChange for user 0
,07-05 14:04:33.533  1012  3157 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,07-05 14:04:33.533  1012  1012 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-05 14:04:33.533  1012  1012 D PersonaManagerService: getPersonasForUser(): returning null!
,07-05 14:04:33.543  6257  6257 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,07-05 14:04:33.543  6257  6257 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,07-05 14:04:33.553   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,07-05 14:04:33.563  1012  1487 D InputDispatcher: Focus entered window: 6257
,07-05 14:04:33.563  1012  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,07-05 14:04:33.573  1012  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,07-05 14:04:33.573  6257  6257 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,07-05 14:04:33.573  6257  6296 I OpenGLRenderer: Initialized EGL, version 1.4
,07-05 14:04:33.573  6257  6296 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,07-05 14:04:33.573  6257  6296 D OpenGLRenderer: Enabling debug mode 0
,07-05 14:04:33.613  6257  6257 V ActivityThread: updateVisibility : ActivityRecord{1c331224 token=android.os.BinderProxy@43aedb6 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,07-05 14:04:33.643  1012  1217 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-05 14:04:33.643  1169  1169 I StatusBar: Icon Only
,07-05 14:04:33.643  1169  1169 D PanelView: There is/are notification(s) 
,07-05 14:04:33.653  1012  6299 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:04:33.663  1012  1044 I ActivityManager: Displayed Component not be shown by security: +574ms (total +21s157ms)
,07-05 14:04:33.663  1012  1044 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1c9f5cef u0 com.test.thalitest/.MainActivity t24} time:135091
07-05 14:04:33.663  1012  1044 W ActivityManager: mDVFSHelper.release()
,07-05 14:04:33.663   257  1900 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,07-05 14:04:33.663   257   440 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,07-05 14:04:33.673  1805  1805 I SamsungIME: getCurrentCandidateView
,07-05 14:04:33.673  6257  6257 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,07-05 14:04:33.673  6257  6257 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@43aedb6 time:135105
,07-05 14:04:33.733  6257  6257 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6257
,07-05 14:04:33.743  1805  1805 D SamsungIME: Dismiss ExpandCandiate
,07-05 14:04:33.853  6257  6257 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-05 14:04:33.873  1805  1805 I SamsungIME: getDebugLevel  : 0x4f4c
,07-05 14:04:33.913  1805  1805 I SamsungIME: getDebugLevel  : 0x4f4c
,07-05 14:04:33.923  1805  1805 I SamsungIME: KeybaordView init() : load resources
,07-05 14:04:33.953  1805  1805 I SamsungIME: getCurrentKeyboard
07-05 14:04:33.953  1805  1805 I SamsungIME: getTextKeyboard
,07-05 14:04:33.963  6257  6300 D jxcore_app_log: JniHelper::setJavaVM(0xb7cd7328), pthread_self() = -1205623000
,07-05 14:04:33.963  1805  1805 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,07-05 14:04:33.973  6257  6300 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-05 14:04:33.973  6257  6300 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-05 14:04:33.973  6257  6300 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-05 14:04:33.973  6257  6300 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
,07-05 14:04:33.973  6257  6300 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-05 14:04:33.973  6257  6300 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11914c54 added. We now have 1 listener(s)
07-05 14:04:33.973  6257  6300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,07-05 14:04:33.973  6257  6300 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,07-05 14:04:33.983  6257  6300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-05 14:04:33.983  6257  6300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-05 14:04:33.983  6257  6300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-05 14:04:33.983  6257  6300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-05 14:04:33.983  6257  6300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-05 14:04:33.983  6257  6300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
07-05 14:04:33.983  6257  6300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-05 14:04:33.983  6257  6300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-05 14:04:33.983  6257  6300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-05 14:04:33.983  6257  6300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-05 14:04:33.983  6257  6300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-05 14:04:33.983  6257  6300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-05 14:04:33.983  6257  6300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-05 14:04:33.983  6257  6300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd0cf43 added. We now have 1 listener(s)
,07-05 14:04:33.983  6257  6300 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-05 14:04:33.993  6257  6300 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,07-05 14:04:33.993  6257  6300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-05 14:04:33.993  6257  6300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,07-05 14:04:33.993  6257  6300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-05 14:04:33.993  6257  6300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-05 14:04:33.993  6257  6300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-05 14:04:33.993  6257  6300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,07-05 14:04:34.003  6257  6300 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 14:04:34.003  6257  6300 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 14:04:34.003  6257  6300 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-05 14:04:34.003  6257  6300 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 14:04:34.003  6257  6300 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 14:04:34.003  6257  6300 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-05 14:04:34.003  6257  6300 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-05 14:04:34.003  6257  6300 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-05 14:04:34.003  6257  6300 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-05 14:04:34.003  6257  6300 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-05 14:04:34.003  6257  6300 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-05 14:04:34.003  6257  6257 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-05 14:04:34.013  6257  6257 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-05 14:04:34.043  6257  6257 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-05 14:04:34.483  1805  6305 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,07-05 14:04:34.533  6257  6310 W jxcore-log: Initializing JXcore engine
07-05 14:04:34.533  6257  6310 W jxcore-log: JXcore engine is ready
,07-05 14:04:34.583  1909  1909 E audit   : type=1400 msg=audit(1467720274.583:205): avc:  denied  { ioctl } for  pid=6310 comm="Thread-1089" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-05 14:04:34.583  1909  1909 E audit   :  SEPF_SM-A500FU_5.0.2-1_0051
07-05 14:04:34.583  1909  1909 E audit   : type=1300 msg=audit(1467720274.583:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=2 a3=9e5c08f8 items=0 ppid=305 ppcomm=main pid=6310 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-1089" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
07-05 14:04:34.583  1909  1909 E audit   : type=1320 msg=audit(1467720274.583:205): 
,07-05 14:04:34.593  6257  6310 W jxcore-log: Starting JXcore engine
,07-05 14:04:34.713  6257  6310 W jxcore-log: Platform android
07-05 14:04:34.713  6257  6310 W jxcore-log: 
07-05 14:04:34.713  6257  6310 W jxcore-log: Process ARCH arm
07-05 14:04:34.713  6257  6310 W jxcore-log: 
,07-05 14:04:34.923  6257  6310 I jxcore-log: JXcore Cordova bridge is ready!
07-05 14:04:34.923  6257  6310 I jxcore-log: 
,07-05 14:04:34.923  6257  6310 W jxcore-log: JXcore engine is started
,07-05 14:04:34.933  6257  6300 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
07-05 14:04:34.933  6257  6257 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-05 14:04:34.943  6257  6310 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
07-05 14:04:34.943  6257  6310 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-05 14:04:34.953  6257  6257 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,07-05 14:04:34.953  6257  6257 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-05 14:04:34.953  1012  1306 D FocusedStackFrame: Set to : 0
07-05 14:04:34.953  1012  1306 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-05 14:04:34.953  1012  1306 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
07-05 14:04:34.953  1012  1306 D InputDispatcher: Focused application set to: xxxx
07-05 14:04:34.963  1012  1306 D InputDispatcher: Focus left window: 6257
07-05 14:04:34.963  1012  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-05 14:04:34.963  1012  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,07-05 14:04:34.973  1012  1306 I ActivityManager: Killing 5727:com.google.android.gms:car/u0a12 (adj 15): empty #31
,07-05 14:04:34.973  6257  6300 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 17ms. Plugin should use CordovaInterface.getThreadPool().
07-05 14:04:34.973  6257  6257 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,07-05 14:04:34.973  6257  6257 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
07-05 14:04:34.973  6257  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-05 14:04:34.973  6257  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-05 14:04:34.973  6257  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-05 14:04:34.973  6257  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-05 14:04:34.973  6257  6257 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11914c54 removed from the list
07-05 14:04:34.973  6257  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-05 14:04:34.973  6257  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd0cf43 removed from the list
07-05 14:04:34.973  6257  6257 D io.jxcore.node.ConnectivityMonitor: stop
07-05 14:04:34.973  6257  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,07-05 14:04:34.973  6257  6257 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-05 14:04:34.993  1012  1025 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:04:34.993  1012  1025 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
07-05 14:04:34.993  1012  1025 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
07-05 14:04:34.993  1012  1025 D BatteryService: stay LED for fully charged
07-05 14:04:34.993  1012  1012 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:04:34.993  1012  1012 I MotionRecognitionService: Plugged
,07-05 14:04:34.993  1012  1012 I MotionRecognitionService: mGripSensorEnabled= false
,07-05 14:04:35.003  1169  1169 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:04:35.003  1169  1169 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:04:35.003  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,07-05 14:04:35.003  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 14:04:35.013   257  1092 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
,07-05 14:04:35.013   257   440 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,07-05 14:04:35.023  2645  2645 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:04:35.023  2645  2737 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:04:35.033  1012  1492 W ActivityManager: mDVFSHelper.acquire(),
,07-05 14:04:35.043  1012  1492 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,07-05 14:04:35.053  1169  1169 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:04:35.063  1169  1169 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:04:35.063  1169  1169 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:04:35.063  1476  1476 D Launcher: onRestart, Launcher: 615013857
,07-05 14:04:35.063  1476  1476 D Launcher: onStart, Launcher: 615013857
,07-05 14:04:35.063  1476  1476 D Launcher.HomeView: onStart
07-05 14:04:35.063  1476  1476 D Launcher: onResume, Launcher: 615013857
,07-05 14:04:35.073  1012  1025 D SettingsProvider: name = kids_home_mode
,07-05 14:04:35.073  1012  1025 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-05 14:04:35.073  1012  1025 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-05 14:04:35.073  1012  1025 D SettingsProvider: selectionArgs: false
07-05 14:04:35.073  1012  1025 D SettingsProvider: selectionArgs: 10007
,07-05 14:04:35.073  1012  1025 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-05 14:04:35.073  1012  1025 D SettingsProvider: ret = -1
,07-05 14:04:35.073  1476  1476 D Launcher.HomeView: onResume
,07-05 14:04:35.073  1476  1476 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,07-05 14:04:35.083  1476  1476 D MenuAppsGridFragment: onResume
,07-05 14:04:35.083  1012  1039 W ActivityManager: userId = 0, bbcId = -10000
,07-05 14:04:35.083  1476  1476 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,07-05 14:04:35.083  1012  1039 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 14:04:35.083  1012  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,07-05 14:04:35.093  1476  1476 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,07-05 14:04:35.093  1476  1476 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
07-05 14:04:35.093  1012  1487 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=6, mSplitNum[2]=8, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=10
07-05 14:04:35.093  1012  1487 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
07-05 14:04:35.093  1012  1487 W ActivityManager: userId = 0, bbcId = -10000
07-05 14:04:35.093  1012  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 14:04:35.093  1012  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,07-05 14:04:35.103  1012  1039 W ActivityManager: userId = 0, bbcId = -10000
,07-05 14:04:35.103  1012  1039 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 14:04:35.103  1012  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,07-05 14:04:35.103  1012  1039 W ActivityManager: userId = 0, bbcId = -10000
,07-05 14:04:35.103  1012  1039 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 14:04:35.103  1012  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
,07-05 14:04:35.103  1012  1039 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
,07-05 14:04:35.113  1012  1039 D ActivityManager: com.sec.android.widgetapp.digitalclock, Starting
,07-05 14:04:35.113  1012  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 14:04:35.113  1012  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 14:04:35.113  1012  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:35.113  1012  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 14:04:35.113  4982  4982 D GalleryCacheReady: Receive : home resume,
,07-05 14:04:35.123  1012  1039 I ActivityManager: Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=6317 uid=10088 gids={50088, 9997} abi=armeabi-v7a
,07-05 14:04:35.133  6317  6317 E Zygote  : MountEmulatedStorage()
,07-05 14:04:35.133  6317  6317 E Zygote  : v2
07-05 14:04:35.133  6317  6317 I libpersona: KNOX_SDCARD checking this for 10088
07-05 14:04:35.133  6317  6317 I libpersona: KNOX_SDCARD not a persona,
07-05 14:04:35.133  1012  1039 W ActivityManager: userId = 0, bbcId = -10000
07-05 14:04:35.133  1012  1039 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 14:04:35.133  1012  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
07-05 14:04:35.133  1012  1039 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast,
07-05 14:04:35.133  1012  1039 D ActivityManager: com.sec.android.widgetapp.activeapplicationwidget, Starting
,07-05 14:04:35.133  6317  6317 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,07-05 14:04:35.133  6317  6317 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,07-05 14:04:35.133  6317  6317 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,07-05 14:04:35.143  1012  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 14:04:35.143  1012  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:35.143  1012  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:35.143  1012  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 14:04:35.153  6326  6326 E Zygote  : MountEmulatedStorage()
,07-05 14:04:35.153  6326  6326 E Zygote  : v2
07-05 14:04:35.153  6326  6326 I libpersona: KNOX_SDCARD checking this for 10142
07-05 14:04:35.153  6326  6326 I libpersona: KNOX_SDCARD not a persona
,07-05 14:04:35.153  6326  6326 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,07-05 14:04:35.153  1012  1039 I ActivityManager: Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=6326 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a,
07-05 14:04:35.153  1012  3207 D ActivityManager: handle home activity for 0
07-05 14:04:35.153  1012  1012 D PersonaManagerService: getPersonasForUser(): returning null!
07-05 14:04:35.153  1012  3207 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
07-05 14:04:35.153  1012  3207 D KnoxTimeoutHandler: post home show event for user 0
07-05 14:04:35.153  1012  3207 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-05 14:04:35.153  1012  3207 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-05 14:04:35.153  1012  3207 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false,
07-05 14:04:35.153  1012  1012 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
07-05 14:04:35.153  1012  1012 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
07-05 14:04:35.153  1012  1012 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-05 14:04:35.153  6326  6326 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
07-05 14:04:35.153  1476  1476 D Launcher.HomeView: onPause
07-05 14:04:35.153  6326  6326 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-05 14:04:35.153  1476  1476 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
07-05 14:04:35.163  1012  1487 W ActivityManager: userId = 0, bbcId = -10000
07-05 14:04:35.163  1012  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 14:04:35.163  1012  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,07-05 14:04:35.173  6317  6317 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 14:04:35.173  6317  6317 D ActivityThread: Added TimaKeyStore provider
,07-05 14:04:35.183  1012  1475 W ActivityManager: userId = 0, bbcId = -10000
07-05 14:04:35.183   257   257 I SurfaceFlinger: id=14 createSurf (720x1280),1 flag=4, Mauncher
07-05 14:04:35.183  1012  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 14:04:35.183  1012  1475 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1476, uid=10007) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
07-05 14:04:35.183  1012  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,07-05 14:04:35.183  1012  1042 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-05 14:04:35.183  5811  5811 D Mms/UIEventReceiver: ui event
07-05 14:04:35.183  1012  1039 W ActivityManager: userId = 0, bbcId = -10000
07-05 14:04:35.183  1012  1039 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 14:04:35.183  1012  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,07-05 14:04:35.183  2516  2516 D Recents_RecreateReceiver: onReceive by home
,07-05 14:04:35.193  1012  1042 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-05 14:04:35.203  1012  1306 D InputDispatcher: Focus entered window: 1476
07-05 14:04:35.203  1012  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-05 14:04:35.203  1012  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,07-05 14:04:35.203  1476  1476 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
07-05 14:04:35.203  6326  6326 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 14:04:35.203  6326  6326 D ActivityThread: Added TimaKeyStore provider
,07-05 14:04:35.213  1476  1476 V ActivityThread: updateVisibility : ActivityRecord{25ecee33 token=android.os.BinderProxy@2ab6212a {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
07-05 14:04:35.213  1476  1476 D Launcher.HomeView: onStop
,07-05 14:04:35.213  1012  3166 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-05 14:04:35.213  1012  6348 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
07-05 14:04:35.213  6317  6317 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-05 14:04:35.223  6257  6257 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,07-05 14:04:35.223  1805  1805 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,07-05 14:04:35.223  1012  2742 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:04:35.233  1169  1169 I StatusBar: Icon Only
07-05 14:04:35.233  1169  1169 D PanelView: There is/are notification(s) 
,07-05 14:04:35.233  6326  6326 V TaskCloserActivity: TaskCloserActivity enter()
,07-05 14:04:35.233  6313  6313 D AndroidRuntime: 
07-05 14:04:35.233  6313  6313 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,07-05 14:04:35.243  6313  6313 D AndroidRuntime: CheckJNI is OFF
07-05 14:04:35.243  6326  6326 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,07-05 14:04:35.243  6313  6313 D AndroidRuntime: readGMSProperty: start
07-05 14:04:35.243  6313  6313 D AndroidRuntime: readGMSProperty: already setted!!
07-05 14:04:35.243  6313  6313 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-05 14:04:35.243  6313  6313 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
,07-05 14:04:35.243  6313  6313 D AndroidRuntime: readGMSProperty: end
07-05 14:04:35.243  6313  6313 D AndroidRuntime: addProductProperty: start
,07-05 14:04:35.243  1012  1025 W ActivityManager: userId = 0, bbcId = -10000
07-05 14:04:35.243  1012  1025 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 14:04:35.243  1012  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,07-05 14:04:35.253  1012  1025 I ActivityManager: Killing 5703:com.samsung.android.sm/1000 (adj 15): empty #31
07-05 14:04:35.253  1476  1476 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2ab6212a time:136681
,07-05 14:04:35.253  1012  1025 W ActivityManager: userId = 0, bbcId = -10000
07-05 14:04:35.253  1012  1025 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
07-05 14:04:35.253  1012  1025 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 14:04:35.253  1012  1025 D ActivityManager: com.sec.android.app.camera, Starting
07-05 14:04:35.253  1012  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,07-05 14:04:35.263  1012  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0,
07-05 14:04:35.263  1012  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:35.263  1012  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:35.263  1012  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 14:04:35.273  6351  6351 E Zygote  : MountEmulatedStorage()
,07-05 14:04:35.273  6351  6351 E Zygote  : v2
07-05 14:04:35.273  6351  6351 I libpersona: KNOX_SDCARD checking this for 10139
07-05 14:04:35.273  6351  6351 I libpersona: KNOX_SDCARD not a persona,
,07-05 14:04:35.273  6351  6351 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
07-05 14:04:35.273  1012  1025 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=6351 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
07-05 14:04:35.273  1012  1025 I ActivityManager: Killing 5519:com.google.android.apps.plus/u0a120 (adj 15): empty #31
,07-05 14:04:35.283  6351  6351 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,07-05 14:04:35.283  6351  6351 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-05 14:04:35.283  1012  1044 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2800b8a u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t22} time:136716
07-05 14:04:35.283  1012  1044 W ActivityManager: mDVFSHelper.release()
,07-05 14:04:35.293  1012  1012 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,07-05 14:04:35.313  6351  6351 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 14:04:35.313  6351  6351 D ActivityThread: Added TimaKeyStore provider
,07-05 14:04:35.323  6351  6351 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
07-05 14:04:35.323  6351  6351 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-05 14:04:35.323  6351  6351 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
07-05 14:04:35.323  6351  6351 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
07-05 14:04:35.323  6351  6351 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-05 14:04:35.333  1012  3157 D PersonaManager: isKioskContainerExistOnDevice
,07-05 14:04:35.373  1012  1487 I splitIntent: Queue : backgroundsplit_1 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,07-05 14:04:35.373  1012  1487 I ActivityManager: Killing 5050:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,07-05 14:04:35.373  1012  1039 W ActivityManager: userId = 0, bbcId = -10000
07-05 14:04:35.373  1012  1039 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 14:04:35.373  1012  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,07-05 14:04:35.373  6326  6326 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,07-05 14:04:35.393  6313  6313 E AffinityControl: AffinityControl: registerfunction enter
,07-05 14:04:35.413  6313  6313 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,07-05 14:04:35.433  1012  3185 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
07-05 14:04:35.433  1012  3185 D PackageManager: START PACKAGE DELETE: observer{821975651}
07-05 14:04:35.433  1012  3185 D PackageManager: pkg{<packageName>}
07-05 14:04:35.433  1012  3185 D PackageManager: user{0}
07-05 14:04:35.433  1012  3185 D PackageManager: caller{2000}
07-05 14:04:35.433  1012  3185 D PackageManager: flags{2}
07-05 14:04:35.433  1012  3185 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
07-05 14:04:35.433  1012  1053 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
07-05 14:04:35.433  1012  3185 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,07-05 14:04:35.433  1012  3185 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-05 14:04:35.433  1012  3185 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-05 14:04:35.433  1012  1053 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
07-05 14:04:35.433  1012  1053 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
07-05 14:04:35.433  1012  1053 D ApplicationPolicy: getApplicationUninstallationEnabled
07-05 14:04:35.433  1012  1053 D PackageManager: !@killApplicatoin: 10155, uninstall pkg
07-05 14:04:35.433  1012  1053 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
07-05 14:04:35.433  1012  1039 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
,07-05 14:04:35.433  1012  1039 I ActivityManager: Killing 6257:com.test.thalitest/u0a155 (adj 15): stop com.test.thalitest cause uninstall pkg
,07-05 14:04:35.513   290   290 E SMD     : DCD OFF,
,07-05 14:04:35.553  1012  1053 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,07-05 14:04:35.563  1012  1053 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,07-05 14:04:35.593  1012  1094 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-05 14:04:35.603  1805  1805 E SamsungIME: mOCRHelper is null
,07-05 14:04:35.603  1937  2119 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-05 14:04:35.623  5616  5616 I art     : Explicit concurrent mark sweep GC freed 1981(113KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 699us total 52.796ms
,07-05 14:04:35.633  1444  1444 D PersonaManager: isKioskContainerExistOnDevice
,07-05 14:04:35.643  1012  1120 V NetworkStats: removeUidsLocked() for UIDs [10155]
07-05 14:04:35.643  1012  1120 D NtpTrustedTime: currentTimeMillis() cache hit
07-05 14:04:35.643  1012  1120 V NetworkStats: performPollLocked(flags=0x3)
,07-05 14:04:35.643  3613  3613 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jul 05 14:04:35 GMT+02:00 2016
07-05 14:04:35.643  5409  5409 I art     : Explicit concurrent mark sweep GC freed 11702(778KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/11MB, paused 789us total 54.894ms
,07-05 14:04:35.643  1012  1120 D NetworkStatsFactory: UpdateStatsForKnox updated
07-05 14:04:35.643  1012  1120 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,07-05 14:04:35.643  1012  1120 V NetworkStats: performPollLocked() took 7ms
07-05 14:04:35.643  1012  1120 D NtpTrustedTime: currentTimeMillis() cache hit
,07-05 14:04:35.653  1012  1487 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,07-05 14:04:35.653  1012  1487 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,07-05 14:04:35.653  1444  1444 D RegisteredServicesCache: empty dynamic service
,07-05 14:04:35.653  1012  1487 W ActivityManager: userId = 0, bbcId = -10000
07-05 14:04:35.653  1012  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 14:04:35.653  1012  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,07-05 14:04:35.663  3613  3613 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,07-05 14:04:35.673  1012  3207 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
,07-05 14:04:35.673  1012  3207 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,07-05 14:04:35.673  1012  3207 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
07-05 14:04:35.673  1012  3207 D ActivityManager: com.sec.esdk.elm, Starting
,07-05 14:04:35.673  1012  3207 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:35.673  1012  3207 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:35.673  1012  3207 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:35.673  1012  3207 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 14:04:35.683  3613  3613 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,07-05 14:04:35.683  3613  3613 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,07-05 14:04:35.693  6376  6376 I libpersona: KNOX_SDCARD checking this for 10094
07-05 14:04:35.683  3613  3613 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
07-05 14:04:35.693  6376  6376 I libpersona: KNOX_SDCARD not a persona
07-05 14:04:35.693  6376  6376 E Zygote  : MountEmulatedStorage()
07-05 14:04:35.693  6376  6376 E Zygote  : v2
07-05 14:04:35.693  1012  1038 W TextServicesManagerService: no available spell checker services found,
07-05 14:04:35.693  3613  6375 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
07-05 14:04:35.693  6376  6376 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
07-05 14:04:35.693  1012  1038 D EnterpriseDeviceManagerService: Package has changed for user 0
07-05 14:04:35.693  1012  1038 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,07-05 14:04:35.693  6376  6376 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,07-05 14:04:35.693  6376  6376 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-05 14:04:35.693  1012  3207 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6376 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,07-05 14:04:35.713  1444  1444 D RegisteredComponentCache: Collect Tech packages for Knox
,07-05 14:04:35.713  1444  1444 D PersonaManager: isKioskContainerExistOnDevice
,07-05 14:04:35.723  3613  6375 I KLMS-2.5.183: : KLMSIntentService(): PACKAGE_REMOVED
,07-05 14:04:35.743  6376  6376 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 14:04:35.743  6376  6376 D ActivityThread: Added TimaKeyStore provider
,07-05 14:04:35.753  1012  1306 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
07-05 14:04:35.753  1012  1306 D SecContentProvider2: mCursor = null
,07-05 14:04:35.763  1012  1012 I art     : Explicit concurrent mark sweep GC freed 39957(3MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 28MB/42MB, paused 3.758ms total 197.648ms
,07-05 14:04:35.763  1012  1053 I art     : WaitForGcToComplete blocked for 131.938ms for cause Explicit
,07-05 14:04:35.763  3613  6375 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().START
07-05 14:04:35.773  3823  3823 I art     : Explicit concurrent mark sweep GC freed 21170(1319KB) AllocSpace objects, 5(80KB) LOS objects, 24% free, 15MB/20MB, paused 1.331ms total 208.855ms
,07-05 14:04:35.783  1012  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 14:04:35.783  3613  6375 I KLMS-2.5.183: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,07-05 14:04:35.803  1012  1121 D NtpTrustedTime: currentTimeMillis() cache hit
07-05 14:04:35.803  1012  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,07-05 14:04:35.813  1012  1039 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
07-05 14:04:35.813  1012  1039 D ActivityManager: com.samsung.android.sm, Starting
,07-05 14:04:35.813  4982  4982 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
,07-05 14:04:35.813  1012  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:35.813  1012  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:35.813  1012  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:35.813  1012  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 14:04:35.823  1012  1039 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=6391 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,07-05 14:04:35.833  6391  6391 E Zygote  : MountEmulatedStorage()
07-05 14:04:35.833  6391  6391 I libpersona: KNOX_SDCARD checking this for 1000
07-05 14:04:35.833  6391  6391 E Zygote  : v2,
07-05 14:04:35.833  6391  6391 I libpersona: KNOX_SDCARD not a persona
07-05 14:04:35.833  6391  6391 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,07-05 14:04:35.833  6391  6391 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
07-05 14:04:35.843  6391  6391 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-05 14:04:35.843  5811  5811 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
,07-05 14:04:35.843  6376  6376 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,07-05 14:04:35.853  1012  1135 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
07-05 14:04:35.853  1012  1135 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
07-05 14:04:35.853  1012  1135 W ActivityManager: userId = 0, bbcId = -10000
07-05 14:04:35.853  1012  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 14:04:35.853  1012  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,07-05 14:04:35.853  6376  6376 D elm:15183: ELMEngine.ELMEngine( context ).
,07-05 14:04:35.853  6376  6376 D elm:15183: MDMBridge.setEnterpriseBridge()
,07-05 14:04:35.853  1012  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 14:04:35.863  1012  1039 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,07-05 14:04:35.863  1012  1039 D ActivityManager: com.sec.android.app.themechooser, Starting
,07-05 14:04:35.863  1012  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 14:04:35.863  1012  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 14:04:35.863  1012  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 14:04:35.863  1012  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 14:04:35.873  1012  3207 I TactileAssist: enable value -1
07-05 14:04:35.873  1012  3207 I TactileAssist: internal enable value -1
07-05 14:04:35.873  1012  3207 I TactileAssist: intensity value -1
07-05 14:04:35.873  1012  3207 I TactileAssist: saveAppList value true
,07-05 14:04:35.873  5811  6401 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
,07-05 14:04:35.873  5811  6401 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
,07-05 14:04:35.883  6407  6407 E Zygote  : MountEmulatedStorage()
07-05 14:04:35.883  6407  6407 E Zygote  : v2
07-05 14:04:35.883  6407  6407 I libpersona: KNOX_SDCARD checking this for 10149
07-05 14:04:35.883  6407  6407 I libpersona: KNOX_SDCARD not a persona
,07-05 14:04:35.883  1012  3207 I TactileAssist: List of disabled apps :,
07-05 14:04:35.883  1012  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 14:04:35.883  1012  1039 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=6407 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-05 14:04:35.893  3613  6375 I KLMS-2.5.183: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,07-05 14:04:35.893  6391  6391 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 14:04:35.893  1012  3157 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
07-05 14:04:35.893  6391  6391 D ActivityThread: Added TimaKeyStore provider
07-05 14:04:35.893  1012  3157 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,07-05 14:04:35.893  6407  6407 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,07-05 14:04:35.893  6407  6407 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
07-05 14:04:35.893  1012  3157 W ActivityManager: userId = 0, bbcId = -10000
07-05 14:04:35.893  1012  3157 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 14:04:35.893  1012  3157 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm,
07-05 14:04:35.903  6407  6407 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-05 14:04:35.903  3613  6375 I KLMS-2.5.183: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,07-05 14:04:35.913  6376  6376 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,07-05 14:04:35.913  3613  6375 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().END
,07-05 14:04:35.913  6376  6376 D elm:15183: ElmAgentService : onCreate()
,07-05 14:04:35.923  6376  6416 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,07-05 14:04:35.923  6376  6416 D elm:15183: MainReceiver.listeningToPackageRemoved()
07-05 14:04:35.923  6376  6416 D elm:15183: MDMBridge.getInstance()
07-05 14:04:35.923  6376  6416 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,07-05 14:04:35.923  6407  6407 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 14:04:35.923  6376  6416 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,07-05 14:04:35.923  6407  6407 D ActivityThread: Added TimaKeyStore provider
,07-05 14:04:35.933  3613  3613 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,07-05 14:04:35.943  3373  3373 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,07-05 14:04:35.943  3373  3373 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,07-05 14:04:35.943  3373  3373 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
,07-05 14:04:35.943  6391  6391 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-05 14:04:35.953  3373  3373 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
07-05 14:04:35.953  3373  3373 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
07-05 14:04:35.953  3373  3373 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
07-05 14:04:35.953  3373  3373 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
07-05 14:04:35.953  3373  3373 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:04:35.953  3373  3373 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:04:35.953  3373  3373 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-05 14:04:35.953  3373  3373 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 14:04:35.953  3373  3373 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 14:04:35.953  3373  3373 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-05 14:04:35.953  3373  3373 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,07-05 14:04:35.963  6376  6376 D elm:15183: ElmAgentService : onDestroy().
,07-05 14:04:35.963  1012  1053 I art     : Explicit concurrent mark sweep GC freed 10574(1126KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 28MB/42MB, paused 3.473ms total 192.479ms
,07-05 14:04:35.983  6049  6049 D Compatibility: onReceive() it will make start service
,07-05 14:04:35.983  1012  1217 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
07-05 14:04:35.983  1012  1217 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,07-05 14:04:35.983  1012  1217 W ActivityManager: userId = 0, bbcId = -10000
,07-05 14:04:35.983  1012  1217 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 14:04:35.983  1012  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,07-05 14:04:35.993  6049  6424 D Compatibility: onHandleIntent()
,07-05 14:04:35.993  6049  6424 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10155, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,07-05 14:04:36.003  6407  6407 D ThemeInfoUtil: getCurrentFestivalName is [null]
07-05 14:04:36.003  6407  6407 D ThemeInfoUtil: isCurrentFestival = false
,07-05 14:04:36.003  1012  1492 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
07-05 14:04:36.003  1012  1492 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,07-05 14:04:36.003  1012  1492 W ActivityManager: userId = 0, bbcId = -10000
07-05 14:04:36.003  1012  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 14:04:36.003  1012  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,07-05 14:04:36.003  6049  6424 D Compatibility: found: 2
07-05 14:04:36.003  6049  6424 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
07-05 14:04:36.003  6049  6424 D Compatibility: skipping ResolveInfo{6ab3b48 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
07-05 14:04:36.003  6049  6424 D Compatibility: considering ResolveInfo{24a85de1 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
07-05 14:04:36.003  6049  6424 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,07-05 14:04:36.003  6049  6424 D Compatibility: enabling receiver ResolveInfo{2550b706 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,07-05 14:04:36.013  6049  6424 D Compatibility: enabling receiver ResolveInfo{fc5f1c7 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,07-05 14:04:36.013  5409  6425 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,07-05 14:04:36.013  1012  1492 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
,07-05 14:04:36.013  1012  1492 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,07-05 14:04:36.013  1012  1492 W ActivityManager: userId = 0, bbcId = -10000
,07-05 14:04:36.013  1012  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 14:04:36.013  1012  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,07-05 14:04:36.023  1012  1038 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,07-05 14:04:36.033  6049  6424 D Compatibility: enabling receiver ResolveInfo{ddcc3f4 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,07-05 14:04:36.033  5892  5892 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
,07-05 14:04:36.033  5892  5892 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
07-05 14:04:36.033  5892  5892 I TapandpayWidget:Utils: Clear T&P info.
,07-05 14:04:36.043  5892  5892 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
,07-05 14:04:36.043  1012  1025 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
07-05 14:04:36.043  1012  1025 D ActivityManager: com.samsung.android.intelligenceservice, Starting
,07-05 14:04:36.043  1012  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 14:04:36.043  1012  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:36.043  1012  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:36.043  1012  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:36.043  1012  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:36.043  1012  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 14:04:36.043  6049  6424 D Compatibility: enabling receiver ResolveInfo{2d6bf71d com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,07-05 14:04:36.063  6428  6428 E Zygote  : MountEmulatedStorage(),
07-05 14:04:36.063  6428  6428 I libpersona: KNOX_SDCARD checking this for 10003,
07-05 14:04:36.063  6428  6428 E Zygote  : v2
07-05 14:04:36.063  6428  6428 I libpersona: KNOX_SDCARD not a persona
,07-05 14:04:36.063  6428  6428 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,07-05 14:04:36.063  6428  6428 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
07-05 14:04:36.063  1012  1025 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6428 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
07-05 14:04:36.063  6428  6428 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-05 14:04:36.063  1012  1053 D PackageManager: delete codoeFile: 
,07-05 14:04:36.073  1012  1053 D AASAuninstall: userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
,07-05 14:04:36.073  1012  1053 I AASA_removePackage: UID=10155 Target=com.test.thalitest
,07-05 14:04:36.073  1012  1025 D ActivityManager: startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
07-05 14:04:36.073  1012  1025 D ActivityManager: com.sec.enterprise.knox.cloudmdm.smdms, Starting
07-05 14:04:36.073  1012  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:36.073  1012  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:36.073  1012  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:36.073  1012  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 14:04:36.083  1012  1053 D PackageManager: result of delete: 1{821975651}
,07-05 14:04:36.083  6313  6313 D AndroidRuntime: Shutting down VM
07-05 14:04:36.083  6049  6424 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,07-05 14:04:36.093  1012  1053 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
07-05 14:04:36.093  1012  1053 D PackageManager: userId{-1}
07-05 14:04:36.093  1012  1053 D PackageManager: andCode{true}
,07-05 14:04:36.093  6428  6428 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 14:04:36.103  6428  6428 D ActivityThread: Added TimaKeyStore provider,
,07-05 14:04:36.103  6443  6443 E Zygote  : MountEmulatedStorage(),
07-05 14:04:36.103  6443  6443 E Zygote  : v2
07-05 14:04:36.103  6443  6443 I libpersona: KNOX_SDCARD checking this for 10160
07-05 14:04:36.103  6443  6443 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
07-05 14:04:36.103  6443  6443 I libpersona: KNOX_SDCARD not a persona
,07-05 14:04:36.103  6443  6443 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
07-05 14:04:36.103  6443  6443 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-05 14:04:36.103  1012  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 14:04:36.113  1012  1025 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=6443 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,07-05 14:04:36.113  6391  6426 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,07-05 14:04:36.133  6391  6391 I art     : Explicit concurrent mark sweep GC freed 8061(387KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 771us total 49.576ms
,07-05 14:04:36.133   305   305 I art     : Explicit concurrent mark sweep GC freed 8727(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 653us total 22.365ms
,07-05 14:04:36.133  6443  6443 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 14:04:36.133  6443  6443 D ActivityThread: Added TimaKeyStore provider
,07-05 14:04:36.153   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 632us total 17.391ms
,07-05 14:04:36.153  1012  1053 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,07-05 14:04:36.163  6443  6443 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,07-05 14:04:36.173   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 636us total 19.947ms
,07-05 14:04:36.183  1012  1038 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-05 14:04:36.183  1012  1038 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-05 14:04:36.183  1012  1038 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-05 14:04:36.183  6443  6443 D [0]UMC:UMCContentProvider: @onCreate
,07-05 14:04:36.183  6443  6443 D [0]UMC:Core: onCreate(): 
07-05 14:04:36.183  6443  6443 D [0]UMC:Core: @isManagedProfileUser
07-05 14:04:36.183  6443  6443 D [0]UMC:Core: userId: 0
,07-05 14:04:36.183  6443  6443 D [0]UMC:Core: userInfo: UserInfo{0:Thali Test:13}
07-05 14:04:36.183  6443  6443 D [0]UMC:Core: userInfo.isManagedProfile() : false
,07-05 14:04:36.193  1012  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 14:04:36.193  1012  1711 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-05 14:04:36.193  5991  6004 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
,07-05 14:04:36.193  5991  6004 D BadgeProvider: sendNotify, [notify] : null
07-05 14:04:36.193  5991  6004 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
07-05 14:04:36.193  5991  6004 D BadgeProvider: update, [BadgeCount] : badgecount=0
07-05 14:04:36.193  5991  6004 D BadgeProvider: update, [UpdateCount] : 1
,07-05 14:04:36.193  6428  6428 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,07-05 14:04:36.203  1012  1711 W ActivityManager: userId = 0, bbcId = -10000
,07-05 14:04:36.203  1012  1711 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 14:04:36.203  1012  1711 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,07-05 14:04:36.203  1012  1012 D RCPManagerService: PackageReceiver onReceive()
07-05 14:04:36.203  1012  1012 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,07-05 14:04:36.203  1012  1475 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
07-05 14:04:36.203  1012  1475 D ActivityManager: com.samsung.android.app.assistantmenu, Starting
,07-05 14:04:36.203  1012  1012 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
07-05 14:04:36.203  1012  1012 I OTPFW   : PackageRemovalReceiver::onReceive Enter
07-05 14:04:36.203  1012  1012 D OTPFW   : OtpDbHelper::getInstance New instance created
,07-05 14:04:36.203  1012  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:36.203  1012  1012 D OTPFW   : DBIntegrity::getInstance - New instance created
07-05 14:04:36.203  1012  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:36.203  1012  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:36.203  1012  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 14:04:36.213  1012  1012 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
,07-05 14:04:36.213  1012  1012 I OTPFW   : ProvisionData::getAllEntries Enter
,07-05 14:04:36.213  1012  1012 E OTPFW   : ProvisionData::getAllEntries Table is empty
,07-05 14:04:36.213  1012  1012 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-05 14:04:36.213  1012  1012 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-05 14:04:36.213  1012  1012 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
07-05 14:04:36.213  1012  1012 V EnterpriseBillingPolicy: uID is 10155
07-05 14:04:36.213  1012  1012 V EnterpriseBillingPolicy: Removed Packageuid is0
07-05 14:04:36.213  1012  1012 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,07-05 14:04:36.223  1012  1012 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
07-05 14:04:36.223  1012  1012 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-05 14:04:36.223  1012  1012 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-05 14:04:36.223  1012  1012 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,07-05 14:04:36.223  1012  1012 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,07-05 14:04:36.223  6461  6461 E Zygote  : MountEmulatedStorage(),
07-05 14:04:36.223  6461  6461 I libpersona: KNOX_SDCARD checking this for 1000
07-05 14:04:36.223  6461  6461 E Zygote  : v2
07-05 14:04:36.223  6461  6461 I libpersona: KNOX_SDCARD not a persona
07-05 14:04:36.223  6461  6461 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
07-05 14:04:36.223  1012  1475 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6461 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,07-05 14:04:36.223  6443  6443 D [0]UMC:DeviceInfo: USA==US==
,07-05 14:04:36.233  6461  6461 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,07-05 14:04:36.233  6461  6461 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,07-05 14:04:36.243  1012  1711 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-05 14:04:36.243  1012  1711 W ActivityManager: userId = 0, bbcId = -10000
07-05 14:04:36.243  1012  1711 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
07-05 14:04:36.243  1012  1711 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 14:04:36.243  1012  1711 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-05 14:04:36.253  1012  1012 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-05 14:04:36.253  1012  1012 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
07-05 14:04:36.253  1012  2721 D SSRM:bc : MSG_TYPE_APP_REMOVED::
07-05 14:04:36.253  1012  1012 V EnterpriseBillingPolicy: uID is 10155
07-05 14:04:36.253  1012  1012 V EnterpriseBillingPolicy: Removed Packageuid is0
07-05 14:04:36.253  1012  1158 D TaskPersister: removeObsoleteFile: deleting file=24_task.xml
07-05 14:04:36.253  1012  1012 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,07-05 14:04:36.253  1012  1012 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
07-05 14:04:36.253  1012  1012 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-05 14:04:36.253  1012  1012 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-05 14:04:36.253  1012  1012 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,07-05 14:04:36.253  6461  6461 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 14:04:36.253  1012  1012 V AlarmManagerEXT: com.test.thalitest(10155) is removed.
07-05 14:04:36.253  1012  1012 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
07-05 14:04:36.253  6461  6461 D ActivityThread: Added TimaKeyStore provider
,07-05 14:04:36.263  1012  1475 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-05 14:04:36.263  1012  1475 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,07-05 14:04:36.263  6428  6428 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
07-05 14:04:36.263  1012  1475 W ActivityManager: userId = 0, bbcId = -10000
07-05 14:04:36.263  1012  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 14:04:36.263  1012  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-05 14:04:36.263  6428  6428 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
07-05 14:04:36.263  6428  6428 D UserAnalysis: Create SecureDbHelper
,07-05 14:04:36.273  5845  5845 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
07-05 14:04:36.273  5845  5845 I PCWCLIENTTRACE_PushUtil: sales region : global
07-05 14:04:36.273  5845  5845 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
07-05 14:04:36.273  5845  5845 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,07-05 14:04:36.283  1012  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 14:04:36.293  6428  6428 D IntelligenceServiceApplication: onCreate()
,07-05 14:04:36.293  6428  6428 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,07-05 14:04:36.293  1012  1475 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
07-05 14:04:36.293  1012  1475 D ActivityManager: com.sec.spp.push, Starting
,07-05 14:04:36.303  6313  6313 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
07-05 14:04:36.303  1012  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:36.303  1012  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:36.303  1012  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:36.303  1012  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:36.313  1012  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 14:04:36.313  1012  2721 D SSRM:n  : SIOP:: AP = 340
,07-05 14:04:36.313  6428  6428 D IntelligenceServiceApplication: no applications having user consent for prediction
,07-05 14:04:36.323  6476  6476 E Zygote  : MountEmulatedStorage()
07-05 14:04:36.323  6476  6476 I libpersona: KNOX_SDCARD checking this for 10035
07-05 14:04:36.323  6476  6476 E Zygote  : v2
07-05 14:04:36.323  6476  6476 I libpersona: KNOX_SDCARD not a persona
07-05 14:04:36.323  6476  6476 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,07-05 14:04:36.323  6476  6476 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
07-05 14:04:36.323  6476  6476 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
07-05 14:04:36.333  1012  1475 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6476 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-05 14:04:36.333  1012  1475 I ActivityManager: Killing 5429:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,07-05 14:04:36.343  1476  1476 D Launcher.Model: reloadBadges entered.
07-05 14:04:36.343  1012  1024 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,07-05 14:04:36.343  6428  6428 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,07-05 14:04:36.343  6461  6461 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,07-05 14:04:36.343  1012  1024 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
07-05 14:04:36.343  1012  1024 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,07-05 14:04:36.353  1012  1024 W ActivityManager: userId = 0, bbcId = -10000
07-05 14:04:36.353  1012  1024 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 14:04:36.353  1012  1024 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
07-05 14:04:36.353  6428  6428 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,07-05 14:04:36.363  6476  6476 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 14:04:36.363  6476  6476 D ActivityThread: Added TimaKeyStore provider
,07-05 14:04:36.373  1012  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 14:04:36.373  1012  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-05 14:04:36.383  5487  5487 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,07-05 14:04:36.383  6443  6443 D USER_AGENT: UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US,
,07-05 14:04:36.393  6428  6428 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
,07-05 14:04:36.393  6428  6428 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
,07-05 14:04:36.393  6428  6428 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
07-05 14:04:36.393  6443  6443 D [0]UMC:AdminManager: init - start
,07-05 14:04:36.393  6428  6428 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
07-05 14:04:36.393  6428  6428 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
07-05 14:04:36.393  6428  6428 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,07-05 14:04:36.393  6428  6428 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
07-05 14:04:36.393  6428  6428 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
07-05 14:04:36.393  6428  6428 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
,07-05 14:04:36.393  6428  6428 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
07-05 14:04:36.393  6428  6428 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,07-05 14:04:36.393  6428  6428 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
07-05 14:04:36.393  6428  6428 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,07-05 14:04:36.393  6428  6428 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
07-05 14:04:36.393  6428  6428 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
07-05 14:04:36.393  6428  6428 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
,07-05 14:04:36.393  6428  6428 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
07-05 14:04:36.393  6428  6428 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,07-05 14:04:36.393  6428  6428 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
07-05 14:04:36.403  6428  6428 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,07-05 14:04:36.403  6428  6428 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
,07-05 14:04:36.403  1012  1025 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
07-05 14:04:36.403  1012  1025 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,07-05 14:04:36.403  6428  6428 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
07-05 14:04:36.403  6428  6428 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
07-05 14:04:36.403  6428  6428 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
,07-05 14:04:36.403  1012  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 14:04:36.413  6443  6443 D [0]UMC:AdminManager: loadAdmins
,07-05 14:04:36.413  1012  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 14:04:36.413  1012  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-05 14:04:36.423  6428  6428 D BluetoothAdapter: cancelDiscovery
,07-05 14:04:36.423  1012  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 14:04:36.423  1012  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-05 14:04:36.423  1012  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 14:04:36.423  1012  1487 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-05 14:04:36.433  6391  6459 E SQLiteLog: (10) unixWrite() File Descriptor : 36 gets errno : 9
07-05 14:04:36.433  1012  1487 W ActivityManager: userId = 0, bbcId = -10000
07-05 14:04:36.433  1012  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 14:04:36.433  1012  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-05 14:04:36.433  6391  6459 E SQLiteDatabase: Error inserting name=this value=SmartManager LowpowerContextEngine
07-05 14:04:36.433  6391  6459 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
07-05 14:04:36.433  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
07-05 14:04:36.433  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
07-05 14:04:36.433  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
07-05 14:04:36.433  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
07-05 14:04:36.433  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
07-05 14:04:36.433  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
07-05 14:04:36.433  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2487)
07-05 14:04:36.433  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1740)
07-05 14:04:36.433  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.g(LowpowerContextEngine.java:204)
07-05 14:04:36.433  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.e(LowpowerContextEngine.java:150)
07-05 14:04:36.433  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:100)
07-05 14:04:36.433  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:106)
07-05 14:04:36.433  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:100)
07-05 14:04:36.433  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:41)
07-05 14:04:36.433  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.n.run(LowpowerContextReceiver.java:51)
07-05 14:04:36.433  6391  6459 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
07-05 14:04:36.433  6391  6459 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-05 14:04:36.433  6391  6459 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:04:36.433  6391  6459 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:04:36.443  6443  6443 D [0]UMC:AdminManager: init - end
07-05 14:04:36.443  6443  6443 D GSLBManager: migrateStoredUrlFromOldPref
07-05 14:04:36.443  6391  6459 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
07-05 14:04:36.443  6391  6459 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: Error inserting name=now value=Tue Jul 05 14:04:36 GMT+02:00 2016
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2487)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1740)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.g(LowpowerContextEngine.java:205)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.e(LowpowerContextEngine.java:150)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:100)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:106)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:100)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:41)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.n.run(LowpowerContextReceiver.java:51)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:04:36.443  6391  6459 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
07-05 14:04:36.443  6391  6459 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: Error inserting name=isSystemBuild value=false
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2487)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1740)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.g(LowpowerContextEngine.java:206)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.e(LowpowerContextEngine.java:150)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:100)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:106)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:100)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:41)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.n.run(LowpowerContextReceiver.java:51)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:04:36.443  6391  6459 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
07-05 14:04:36.443  6391  6459 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: Error inserting name=isDevelopVersion value=false
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2487)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1740)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.g(LowpowerContextEngine.java:207)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.e(LowpowerContextEngine.java:150)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:100)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:106)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:100)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:41)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.n.run(LowpowerContextReceiver.java:51)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:04:36.443  6391  6459 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:04:36.443  6391  6459 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
07-05 14:04:36.453  6391  6459 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
07-05 14:04:36.453  6391  6459 E SQLiteDatabase: Error inserting name=DBVersion value=2003
07-05 14:04:36.453  6391  6459 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-05 14:04:36.453  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
07-05 14:04:36.453  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
07-05 14:04:36.453  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
07-05 14:04:36.453  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
07-05 14:04:36.453  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
07-05 14:04:36.453  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
07-05 14:04:36.453  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2487)
07-05 14:04:36.453  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1740)
07-05 14:04:36.453  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.g(LowpowerContextEngine.java:208)
07-05 14:04:36.453  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.e(LowpowerContextEngine.java:150)
07-05 14:04:36.453  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:100)
07-05 14:04:36.453  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:106)
07-05 14:04:36.453  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:100)
07-05 14:04:36.453  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:41)
07-05 14:04:36.453  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.n.run(LowpowerContextReceiver.java:51)
07-05 14:04:36.453  6391  6459 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
07-05 14:04:36.453  6391  6459 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-05 14:04:36.453  6391  6459 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:04:36.453  6391  6459 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:04:36.453  1012  1038 D UsbSettingsManager: clearDefaults: com.test.thalitest
07-05 14:04:36.453  1012  1038 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
07-05 14:04:36.453  6391  6459 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
07-05 14:04:36.453  6391  6459 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
07-05 14:04:36.453  6391  6459 E SQLiteDatabase: Error inserting name=LPCSystemVersion value=1.0.0
07-05 14:04:36.453  6391  6459 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-05 14:04:36.453  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
07-05 14:04:36.453  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
07-05 14:04:36.453  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
07-05 14:04:36.453  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
07-05 14:04:36.453  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
07-05 14:04:36.453  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
07-05 14:04:36.453  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2487)
07-05 14:04:36.453  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1740)
07-05 14:04:36.453  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.g(LowpowerContextEngine.java:209)
07-05 14:04:36.453  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.e(LowpowerContextEngine.java:150)
07-05 14:04:36.453  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:100)
07-05 14:04:36.453  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:106)
07-05 14:04:36.453  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:100)
07-05 14:04:36.453  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:41)
07-05 14:04:36.453  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.n.run(LowpowerContextReceiver.java:51)
07-05 14:04:36.453  6391  6459 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
07-05 14:04:36.453  6391  6459 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-05 14:04:36.453  6391  6459 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:04:36.453  6391  6459 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:04:36.453  6443  6443 D GSLBManager: migrateStoredUrlFromOldPref : Migration Not Needed
07-05 14:04:36.453  6391  6459 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
07-05 14:04:36.453  6391  6459 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
07-05 14:04:36.453  6443  6443 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: Error inserting name=UT enabled value=false
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2487)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1740)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.g(LowpowerContextEngine.java:210)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.e(LowpowerContextEngine.java:150)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:100)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:106)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:100)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:41)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.n.run(LowpowerContextReceiver.java:51)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:04:36.463  6391  6459 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
07-05 14:04:36.463  6391  6459 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
07-05 14:04:36.463  6443  6443 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
07-05 14:04:36.463  6443  6443 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: Error inserting name=AFP Enabled value=true
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2487)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1740)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.g(LowpowerContextEngine.java:211)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.e(LowpowerContextEngine.java:150)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:100)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:106)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:100)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:41)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.n.run(LowpowerContextReceiver.java:51)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:04:36.463  6443  6443 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
07-05 14:04:36.463  6443  6443 D [0]UMC:UMCAdmin: isContainer : 0
07-05 14:04:36.463  6391  6459 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
07-05 14:04:36.463  6391  6459 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: Error inserting name=SleepDetection Enabled value=false
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2487)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1740)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.g(LowpowerContextEngine.java:212)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.e(LowpowerContextEngine.java:150)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:100)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:106)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:100)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:41)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.n.run(LowpowerContextReceiver.java:51)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:04:36.463  6391  6459 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
07-05 14:04:36.463  6391  6459 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: Error inserting name=System Build Version Release value=5.0.2
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2487)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1740)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.g(LowpowerContextEngine.java:213)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.e(LowpowerContextEngine.java:150)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:100)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:106)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:100)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:41)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.n.run(LowpowerContextReceiver.java:51)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:04:36.463  6391  6459 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:04:36.473  2645  2656 D BluetoothAdapterProperties: mDiscovering is false
,07-05 14:04:36.473  2645  2656 E BluetoothAdapterService: This is not a scanning status. cancelDiscovery() will be not called.
07-05 14:04:36.473  6428  6428 D BluetoothAdapter: cancelDiscovery = true
07-05 14:04:36.473  6428  6428 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
07-05 14:04:36.473  6391  6459 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
07-05 14:04:36.473  1012  1487 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
07-05 14:04:36.473  6391  6459 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
07-05 14:04:36.473  6428  6428 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
07-05 14:04:36.473  6391  6459 E SQLiteDatabase: Error inserting name=status value=successfully initialized
07-05 14:04:36.473  6391  6459 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-05 14:04:36.473  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
07-05 14:04:36.473  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
07-05 14:04:36.473  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
07-05 14:04:36.473  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
07-05 14:04:36.473  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
07-05 14:04:36.473  6391  6459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
07-05 14:04:36.473  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2487)
07-05 14:04:36.473  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1740)
07-05 14:04:36.473  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.g(LowpowerContextEngine.java:214)
07-05 14:04:36.473  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.e(LowpowerContextEngine.java:150)
07-05 14:04:36.473  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:100)
07-05 14:04:36.473  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:106)
07-05 14:04:36.473  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:100)
07-05 14:04:36.473  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:41)
07-05 14:04:36.473  6391  6459 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.n.run(LowpowerContextReceiver.java:51)
07-05 14:04:36.473  6391  6459 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
07-05 14:04:36.473  6391  6459 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-05 14:04:36.473  6391  6459 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:04:36.473  6391  6459 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:04:36.473  1012  1024 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
07-05 14:04:36.473  1012  1024 D ActivityManager: com.android.keychain, Starting
07-05 14:04:36.483  1012  1217 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
07-05 14:04:36.483  6443  6443 E [0]UMC:UMCAdmin: No active admin owned by uid 10160
07-05 14:04:36.483  6443  6443 D [0]UMC:UMCAdmin: isContainer : 0
07-05 14:04:36.483  1012  1024 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:36.483  1012  1024 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:36.483  1012  1024 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:36.483  1012  1024 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:36.483  6443  6443 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
07-05 14:04:36.483  6428  6428 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
07-05 14:04:36.493  6428  6428 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/dump.db" with flag (131138) and mode_t (0) due to error (30)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/dump.db'.
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:106)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-05 14:04:36.493  6499  6499 I libpersona: KNOX_SDCARD checking this for 1000
07-05 14:04:36.493  6428  6428 E UserAnalysis: It failed to get the database for dump_log
07-05 14:04:36.493  6499  6499 I libpersona: KNOX_SDCARD not a persona
07-05 14:04:36.493  6499  6499 E Zygote  : MountEmulatedStorage()
07-05 14:04:36.493  1012  1024 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6499 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
07-05 14:04:36.493  6499  6499 E Zygote  : v2
07-05 14:04:36.493  6428  6428 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/dump.db" with flag (131138) and mode_t (0) due to error (30)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/dump.db'.
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:106)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-05 14:04:36.493  6428  6428 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-05 14:04:36.493  6428  6428 E UserAnalysis: It failed to get the database for dump_log
07-05 14:04:36.493  6476  6498 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
07-05 14:04:36.493  6476  6498 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
07-05 14:04:36.503  6476  6476 E SQLiteLog: (28) failed to open "/data/data/com.sec.spp.push/databases/push_noti_db" with flag (131138) and mode_t (0) due to error (30)
07-05 14:04:36.503  6499  6499 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
07-05 14:04:36.503  6499  6499 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
07-05 14:04:36.503  6499  6499 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-05 14:04:36.503  1012  3207 D ActivityManager: startService callerProcessName:com.sec.enterprise.knox.cloudmdm.smdms, calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms
07-05 14:04:36.503  1012  3207 D ActivityManager: retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
07-05 14:04:36.503  1012  3207 W ActivityManager: userId = 0, bbcId = -10000
07-05 14:04:36.503  1012  3207 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,07-05 14:04:36.503  1012  3207 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
07-05 14:04:36.513  6476  6476 E SQLiteDatabase: Failed to open database '/data/data/com.sec.spp.push/databases/push_noti_db'.
07-05 14:04:36.513  6476  6476 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-05 14:04:36.513  6476  6476 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-05 14:04:36.513  6476  6476 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-05 14:04:36.513  6476  6476 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-05 14:04:36.513  6476  6476 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-05 14:04:36.513  6476  6476 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-05 14:04:36.513  6476  6476 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-05 14:04:36.513  6476  6476 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-05 14:04:36.513  6476  6476 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-05 14:04:36.513  6476  6476 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-05 14:04:36.513  6476  6476 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-05 14:04:36.513  6476  6476 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-05 14:04:36.513  6476  6476 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-05 14:04:36.513  6476  6476 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-05 14:04:36.513  6476  6476 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.a.b.<init>(Unknown Source)
07-05 14:04:36.513  6476  6476 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.a.b.a(Unknown Source)
07-05 14:04:36.513  6476  6476 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.registration.n.b(Unknown Source)
07-05 14:04:36.513  6476  6476 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.registration.n.a(Unknown Source)
07-05 14:04:36.513  6476  6476 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.a(Unknown Source)
07-05 14:04:36.513  6476  6476 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.a(Unknown Source)
07-05 14:04:36.513  6476  6476 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.registration.i.handleMessage(Unknown Source)
07-05 14:04:36.513  6476  6476 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:04:36.513  6476  6476 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:04:36.513  6476  6476 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-05 14:04:36.513  6476  6476 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 14:04:36.513  6476  6476 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 14:04:36.513  6476  6476 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-05 14:04:36.513  6476  6476 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-05 14:04:36.513  6476  6476 E LNoti   : [b] open fail. SQLException occured
,07-05 14:04:36.513  6443  6443 D [0]UMC:GuardService: @GuardService - startService Result = ComponentInfo{com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService}
07-05 14:04:36.513  6443  6443 D [0]UMC:CoreReceiver: Intent : android.intent.action.PACKAGE_REMOVED
07-05 14:04:36.513  6443  6443 D [0]UMC:CoreReceiver: PackageName : com.test.thalitest
07-05 14:04:36.513  6476  6498 D SPPClientService: PushLog.txt file is not deleted.
07-05 14:04:36.513  6443  6443 D [0]UMC:CoreReceiver: Intent Replacing : false
07-05 14:04:36.513  6476  6498 D SPPClientService: PushLog.txt file is not deleted.
07-05 14:04:36.513  6476  6498 D SPPClientService: ============PushLog. stop!
,07-05 14:04:36.513  6073  6073 I SA      : [SUR] onReceive called
,07-05 14:04:36.523  1012  1711 I ActivityManager: Killing 5830:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,07-05 14:04:36.523  6073  6073 I SA      : [SUR] Not SA Package.. finish

```
