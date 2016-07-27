#### Test 78968685da35147_thali09_samsung-SM-A300FU Logs


```
--------- beginning of main
07-27 08:54:03.725   290   290 E SMD     : DCD OFF
,--------- beginning of system
07-27 08:54:04.485  1017  2650 D SSRM:n  : SIOP:: AP = 290
07-27 08:54:04.635  5794  5794 D AndroidRuntime: 
07-27 08:54:04.635  5794  5794 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-27 08:54:04.645  5794  5794 D AndroidRuntime: CheckJNI is OFF
07-27 08:54:04.645  5794  5794 D AndroidRuntime: readGMSProperty: start
07-27 08:54:04.645  5794  5794 D AndroidRuntime: readGMSProperty: already setted!!
07-27 08:54:04.645  5794  5794 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-27 08:54:04.645  5794  5794 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-27 08:54:04.645  5794  5794 D AndroidRuntime: readGMSProperty: end
07-27 08:54:04.645  5794  5794 D AndroidRuntime: addProductProperty: start
07-27 08:54:04.785  5794  5794 E AffinityControl: AffinityControl: registerfunction enter
07-27 08:54:04.815  5794  5794 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-27 08:54:04.825  1017  3011 E PersonaManagerService: inState():  stateMachine is null !!
07-27 08:54:04.825  1017  3011 I PersonaManagerService: PersonaId don't exist
07-27 08:54:04.825  1017  3011 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
07-27 08:54:04.825  1017  3011 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-27 08:54:04.835  1017  3011 W ActivityManager: mDVFSHelper.acquire()
07-27 08:54:04.845  1017  3011 D FocusedStackFrame: Set to : 0
07-27 08:54:04.845  1017  1048 D PhoneWindow: *FMB* installDecor mIsFloating : false
07-27 08:54:04.845  1017  1048 D PhoneWindow: *FMB* installDecor flags : -2122120936
07-27 08:54:04.845  1017  3011 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:04.845  1017  3011 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:04.845  1017  3011 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:04.845  1017  3011 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:04.865  5805  5805 E Zygote  : MountEmulatedStorage()
07-27 08:54:04.865  5805  5805 E Zygote  : v2
07-27 08:54:04.865  1017  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
07-27 08:54:04.865  1017  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
07-27 08:54:04.865  5805  5805 I libpersona: KNOX_SDCARD checking this for 10170
07-27 08:54:04.865   257   257 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, uhalitest
07-27 08:54:04.865  5805  5805 I libpersona: KNOX_SDCARD not a persona
07-27 08:54:04.865  5805  5805 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-27 08:54:04.865  1017  3011 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5805 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-27 08:54:04.865  1017  3011 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
07-27 08:54:04.865  1017  3011 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-27 08:54:04.865  5805  5805 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-27 08:54:04.875  5805  5805 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
07-27 08:54:04.885  5805  5805 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:54:04.885  5805  5805 D ActivityThread: Added TimaKeyStore provider
07-27 08:54:04.895  1017  3011 D InputDispatcher: Focused application set to: xxxx
07-27 08:54:04.895  1017  3011 D InputDispatcher: Focus left window: 1478
07-27 08:54:04.895  5794  5794 D AndroidRuntime: Shutting down VM
07-27 08:54:04.895  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-27 08:54:04.895  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
07-27 08:54:04.895  1017  1523 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
07-27 08:54:04.905  1017  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-27 08:54:04.915  1017  1523 D PersonaManager: isKioskContainerExistOnDevice
07-27 08:54:04.925  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
07-27 08:54:04.945   257   453 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
07-27 08:54:04.945   257   450 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
07-27 08:54:04.955  1478  1478 V ActivityThread: updateVisibility : ActivityRecord{24a3bd39 token=android.os.BinderProxy@c79e05b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-27 08:54:04.955  1478  1478 D Launcher: onTrimMemory. Level: 20
07-27 08:54:05.015  5805  5805 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
07-27 08:54:05.025  5805  5805 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 3107-3109)
07-27 08:54:05.025  5805  5805 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 08:54:05.045  5805  5805 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {32087434}
07-27 08:54:05.045  5805  5805 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 08:54:05.045  5805  5805 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
07-27 08:54:05.085  5805  5805 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-27 08:54:05.085  5805  5805 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-27 08:54:05.085  5805  5805 E SysUtils: ApplicationContext is null in ApplicationStatus
07-27 08:54:05.095  5805  5822 W chromium: [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
07-27 08:54:05.105  5794  5794 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
07-27 08:54:05.105  5805  5805 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
07-27 08:54:05.105  5805  5805 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
07-27 08:54:05.105  5805  5805 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
07-27 08:54:05.115  5805  5805 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
07-27 08:54:05.115  5805  5805 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
07-27 08:54:05.115  5805  5805 I Adreno-EGL: Build Date: 04/06/15 Mon
07-27 08:54:05.115  5805  5805 I Adreno-EGL: Local Branch: 
07-27 08:54:05.115  5805  5805 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
07-27 08:54:05.115  5805  5805 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
07-27 08:54:05.115  5805  5805 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
07-27 08:54:05.175  5805  5833 D BluetoothAdapter: 722528089: getState() :  mService = null. Returning STATE_OFF
07-27 08:54:05.245  5805  5831 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
07-27 08:54:05.295  5805  5805 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-27 08:54:05.305  5805  5805 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-27 08:54:05.315  5805  5805 D PhoneWindow: *FMB* installDecor mIsFloating : false
07-27 08:54:05.315  5805  5805 D PhoneWindow: *FMB* installDecor flags : -2139027200
07-27 08:54:05.315  5805  5805 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
07-27 08:54:05.325  5805  5805 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-27 08:54:05.325  5805  5805 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-27 08:54:05.365  5805  5844 D OpenGLRenderer: Render dirty regions requested: true
07-27 08:54:05.375  1017  1523 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-27 08:54:05.375  1017  1523 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-27 08:54:05.375  1017  1523 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
07-27 08:54:05.375  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-27 08:54:05.375  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
07-27 08:54:05.385  5805  5805 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
07-27 08:54:05.385  5805  5805 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
07-27 08:54:05.395   257   257 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, NainActivit
07-27 08:54:05.405  1017  1522 D InputDispatcher: Focus entered window: 5805
07-27 08:54:05.405  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-27 08:54:05.405  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
07-27 08:54:05.405  5805  5805 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
07-27 08:54:05.405  5805  5844 I OpenGLRenderer: Initialized EGL, version 1.4
07-27 08:54:05.415  5805  5844 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
07-27 08:54:05.415  5805  5844 D OpenGLRenderer: Enabling debug mode 0
07-27 08:54:05.425  5805  5805 V ActivityThread: updateVisibility : ActivityRecord{376c89fc token=android.os.BinderProxy@39d23bce {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
07-27 08:54:05.465  1017  3010 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
07-27 08:54:05.475  5805  5805 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@39d23bce time:123552
07-27 08:54:05.475  1180  1180 I StatusBar: Icon Only
07-27 08:54:05.475  1180  1180 D PanelView: There is/are notification(s) 
07-27 08:54:05.475  1017  5847 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
07-27 08:54:05.485  5805  5805 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
07-27 08:54:05.485  1017  1048 I ActivityManager: Displayed Component not be shown by security: +570ms (total +15s955ms)
07-27 08:54:05.485  1017  1048 W ActivityManager: mDVFSHelper.release()
07-27 08:54:05.485  1017  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{24d4640 u0 com.test.thalitest/.MainActivity t9} time:123567
07-27 08:54:05.525   257  1155 I SurfaceFlinger: id=11 Removed uhalitest (7/9)
07-27 08:54:05.525   257   450 I SurfaceFlinger: id=11 Removed uhalitest (-2/9)
07-27 08:54:05.555  1796  1796 I SamsungIME: getCurrentCandidateView
07-27 08:54:05.565  5805  5805 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5805
07-27 08:54:05.655  1796  1796 D SamsungIME: Dismiss ExpandCandiate
07-27 08:54:05.695  5805  5805 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
07-27 08:54:05.735   322   322 I ServiceManager: Waiting for service AtCmdFwd...
07-27 08:54:05.825  5805  5849 D jxcore_app_log: JniHelper::setJavaVM(0xb86382f0), pthread_self() = -1195786304
07-27 08:54:05.825  5805  5849 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-27 08:54:05.825  5805  5849 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-27 08:54:05.825  5805  5849 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-27 08:54:05.825  5805  5849 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-27 08:54:05.825  5805  5849 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-27 08:54:05.825  5805  5849 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fe46a2c added. We now have 1 listener(s)
07-27 08:54:05.835  1796  1796 I SamsungIME: getDebugLevel  : 0x4f4c
07-27 08:54:05.835  5805  5849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
07-27 08:54:05.835  5805  5849 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
07-27 08:54:05.835  5805  5849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 08:54:05.835  5805  5849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 08:54:05.845  5805  5849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-27 08:54:05.845  5805  5849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-27 08:54:05.845  5805  5849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-27 08:54:05.845  5805  5849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
07-27 08:54:05.845  5805  5849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-27 08:54:05.845  5805  5849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-27 08:54:05.845  5805  5849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-27 08:54:05.845  5805  5849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-27 08:54:05.845  5805  5849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-27 08:54:05.845  5805  5849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-27 08:54:05.845  5805  5849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-27 08:54:05.845  5805  5849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f788fb added. We now have 1 listener(s)
07-27 08:54:05.845  5805  5849 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 08:54:05.845  5805  5849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-27 08:54:05.845  5805  5849 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
07-27 08:54:05.855  5805  5849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-27 08:54:05.855  5805  5849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-27 08:54:05.855  5805  5849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-27 08:54:05.855  5805  5849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-27 08:54:05.855  5805  5849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 08:54:05.855  5805  5849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
07-27 08:54:05.855  5805  5849 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-27 08:54:05.855  5805  5849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 08:54:05.855  5805  5849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:54:05.855  5805  5849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-27 08:54:05.855  5805  5849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 08:54:05.855  5805  5849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 08:54:05.855  5805  5849 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 08:54:05.855  5805  5849 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 08:54:05.855  5805  5849 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 08:54:05.855  5805  5849 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-27 08:54:05.855  5805  5849 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 08:54:05.855  5805  5849 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-27 08:54:05.885  1796  1796 I SamsungIME: getDebugLevel  : 0x4f4c
,07-27 08:54:05.895  5805  5805 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-27 08:54:05.895  1796  1796 I SamsungIME: KeybaordView init() : load resources
,07-27 08:54:05.935  1796  1796 I SamsungIME: getCurrentKeyboard
07-27 08:54:05.935  1796  1796 I SamsungIME: getTextKeyboard
,07-27 08:54:05.945  1796  1796 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,07-27 08:54:06.355  5805  5854 W jxcore-log: Initializing JXcore engine,
07-27 08:54:06.355  5805  5854 W jxcore-log: JXcore engine is ready
,07-27 08:54:06.405  1893  1893 E audit   : type=1400 msg=audit(1469602446.405:203): avc:  denied  { ioctl } for  pid=5854 comm="Thread-1038" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0,
07-27 08:54:06.405  1893  1893 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
07-27 08:54:06.405  1893  1893 E audit   : type=1300 msg=audit(1469602446.405:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9e9048f8 items=0 ppid=311 ppcomm=main pid=5854 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1038" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
07-27 08:54:06.405  1893  1893 E audit   : type=1320 msg=audit(1469602446.405:203): 
,07-27 08:54:06.415  5805  5854 W jxcore-log: Starting JXcore engine
,07-27 08:54:06.515  5805  5854 W jxcore-log: Platform android
07-27 08:54:06.515  5805  5854 W jxcore-log: 
07-27 08:54:06.515  5805  5854 W jxcore-log: Process ARCH arm
07-27 08:54:06.515  5805  5854 W jxcore-log: 
,07-27 08:54:06.695  5805  5854 I jxcore-log: JXcore Cordova bridge is ready!
07-27 08:54:06.695  5805  5854 I jxcore-log: 
,07-27 08:54:06.695  5805  5854 W jxcore-log: JXcore engine is started
,07-27 08:54:06.695  5805  5849 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-27 08:54:06.705  5805  5805 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41),
,07-27 08:54:06.705  5805  5854 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
07-27 08:54:06.705  5805  5854 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-27 08:54:06.715  5805  5805 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
07-27 08:54:06.715  5805  5805 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
07-27 08:54:06.715  1017  1248 D FocusedStackFrame: Set to : 0
07-27 08:54:06.715  1017  1248 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-27 08:54:06.715  1017  1248 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
07-27 08:54:06.715  1017  1248 D InputDispatcher: Focused application set to: xxxx
07-27 08:54:06.725  1017  1248 D InputDispatcher: Focus left window: 5805
07-27 08:54:06.725   290   290 E SMD     : DCD OFF
,07-27 08:54:06.725  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-27 08:54:06.725  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
07-27 08:54:06.725  1017  1248 I ActivityManager: Killing 5430:com.sec.spp.push/u0a32 (adj 15): empty #21
07-27 08:54:06.735  5805  5805 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-27 08:54:06.735  5805  5805 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
07-27 08:54:06.735   322   322 I ServiceManager: Waiting for service AtCmdFwd...
07-27 08:54:06.735  5805  5805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 08:54:06.735  5805  5805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 08:54:06.735  5805  5805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 08:54:06.735  5805  5805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 08:54:06.735  5805  5805 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fe46a2c removed from the list
07-27 08:54:06.735  5805  5805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 08:54:06.735  5805  5805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f788fb removed from the list
07-27 08:54:06.735  5805  5805 D io.jxcore.node.ConnectivityMonitor: stop
07-27 08:54:06.735  5805  5805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
07-27 08:54:06.735  5805  5805 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-27 08:54:06.755   257   450 I SurfaceFlinger: id=12 Removed NainActivit (6/8)
,07-27 08:54:06.755   257   453 I SurfaceFlinger: id=12 Removed NainActivit (-2/8)
,07-27 08:54:06.765  1017  1477 W ActivityManager: mDVFSHelper.acquire(),
,07-27 08:54:06.765  1017  1477 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,07-27 08:54:06.785  1478  1478 D Launcher: onRestart, Launcher: 735223712
,07-27 08:54:06.785  1478  1478 D Launcher: onStart, Launcher: 735223712
07-27 08:54:06.785  1478  1478 D Launcher.HomeView: onStart
,07-27 08:54:06.785  1478  1478 D Launcher: onResume, Launcher: 735223712
07-27 08:54:06.795  1017  1030 D SettingsProvider: name = kids_home_mode
07-27 08:54:06.795  1017  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 08:54:06.795  1017  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 08:54:06.795  1017  1030 D SettingsProvider: selectionArgs: false
07-27 08:54:06.795  1017  1030 D SettingsProvider: selectionArgs: 10006
07-27 08:54:06.795  1017  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 08:54:06.795  1017  1030 D SettingsProvider: ret = -1
07-27 08:54:06.795  1478  1478 D Launcher.HomeView: onResume
,07-27 08:54:06.805  1478  1478 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,07-27 08:54:06.805  1478  1478 D MenuAppsGridFragment: onResume
,07-27 08:54:06.805  1478  1478 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
07-27 08:54:06.805  1478  1478 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,07-27 08:54:06.805  1017  1043 W ActivityManager: userId = 0, bbcId = -10000
07-27 08:54:06.805  1017  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,07-27 08:54:06.805  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,07-27 08:54:06.815  1017  1522 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=7, mSplitNum[2]=9, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=11
,07-27 08:54:06.815  1017  1522 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,07-27 08:54:06.815  1017  1522 W ActivityManager: userId = 0, bbcId = -10000
,07-27 08:54:06.815  1017  1522 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-27 08:54:06.815  1017  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,07-27 08:54:06.815  1017  1522 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,07-27 08:54:06.815  1017  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:54:06.815  1017  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:06.815  1017  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:06.815  1017  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:54:06.835  5858  5858 E Zygote  : MountEmulatedStorage()
,07-27 08:54:06.835  5858  5858 E Zygote  : v2
07-27 08:54:06.835  5858  5858 I libpersona: KNOX_SDCARD checking this for 10039
07-27 08:54:06.835  5858  5858 I libpersona: KNOX_SDCARD not a persona
,07-27 08:54:06.835  5858  5858 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-27 08:54:06.835  1017  1522 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=5858 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,07-27 08:54:06.835  1017  1477 D ActivityManager: handle home activity for 0
07-27 08:54:06.835  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
07-27 08:54:06.835  1017  1477 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
07-27 08:54:06.835  1017  1477 D KnoxTimeoutHandler: post home show event for user 0
07-27 08:54:06.835  1017  1017 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
07-27 08:54:06.835  1017  1477 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-27 08:54:06.835  1017  1477 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-27 08:54:06.835  1017  1017 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
07-27 08:54:06.835  1017  1477 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
07-27 08:54:06.835  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-27 08:54:06.835  1478  1478 D Launcher.HomeView: onPause
07-27 08:54:06.835  1017  1043 W ActivityManager: userId = 0, bbcId = -10000
07-27 08:54:06.835  1017  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-27 08:54:06.835  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,07-27 08:54:06.835  1478  1478 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,07-27 08:54:06.845  1017  1043 W ActivityManager: userId = 0, bbcId = -10000,
07-27 08:54:06.845  1017  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-27 08:54:06.845  1017  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.dualclockdigital, hostingType: broadcast
07-27 08:54:06.845  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.dualclockdigital
,07-27 08:54:06.845  5858  5858 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-27 08:54:06.845  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:06.845  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:06.845  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:06.845  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:06.845  5858  5858 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 08:54:06.865  5870  5870 E Zygote  : MountEmulatedStorage(),
,07-27 08:54:06.865  5870  5870 E Zygote  : v2
07-27 08:54:06.865  5870  5870 I libpersona: KNOX_SDCARD checking this for 10089
07-27 08:54:06.865  5870  5870 I libpersona: KNOX_SDCARD not a persona
,07-27 08:54:06.865  1017  1043 I ActivityManager: Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=5870 uid=10089 gids={50089, 9997, 3003} abi=armeabi-v7a
,07-27 08:54:06.865  5870  5870 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-27 08:54:06.865  1017  1043 W ActivityManager: userId = 0, bbcId = -10000
07-27 08:54:06.865  1017  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
07-27 08:54:06.865  1017  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-27 08:54:06.865  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
07-27 08:54:06.865  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:06.865  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:54:06.865  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:06.865  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:54:06.875  5858  5858 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:54:06.875  5858  5858 D ActivityThread: Added TimaKeyStore provider
,07-27 08:54:06.875  5870  5870 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-27 08:54:06.875  5870  5870 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL,
,07-27 08:54:06.885  5885  5885 E Zygote  : MountEmulatedStorage()
07-27 08:54:06.885  5885  5885 E Zygote  : v2
07-27 08:54:06.885  5885  5885 I libpersona: KNOX_SDCARD checking this for 10139
07-27 08:54:06.895  5885  5885 I libpersona: KNOX_SDCARD not a persona
07-27 08:54:06.895  5885  5885 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-27 08:54:06.895  5885  5885 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-27 08:54:06.895  5885  5885 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 08:54:06.895  5870  5870 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:54:06.895  5870  5870 D ActivityThread: Added TimaKeyStore provider
,07-27 08:54:06.905  1017  1043 I ActivityManager: Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=5885 uid=10139 gids={50139, 9997, 1028, 1015} abi=armeabi-v7a,
,07-27 08:54:06.925  5885  5885 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:54:06.925  5885  5885 D ActivityThread: Added TimaKeyStore provider
,07-27 08:54:06.925  5870  5870 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-27 08:54:06.925  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
07-27 08:54:06.925  5870  5870 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
07-27 08:54:06.925  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-27 08:54:06.925  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
07-27 08:54:06.925  1017  1029 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1478, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
,07-27 08:54:06.935   257   257 I SurfaceFlinger: id=13 createSurf (540x960),1 flag=4, Mauncher
,07-27 08:54:06.935  5858  5858 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,07-27 08:54:06.935  5858  5858 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-27 08:54:06.935  5858  5858 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-27 08:54:06.935  5858  5858 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
07-27 08:54:06.935  1017  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-27 08:54:06.935  5858  5858 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-27 08:54:06.935  5858  5858 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
07-27 08:54:06.935  5858  5858 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-27 08:54:06.945  1017  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-27 08:54:06.945  1017  1464 D InputDispatcher: Focus entered window: 1478
,07-27 08:54:06.945  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-27 08:54:06.945  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
07-27 08:54:06.945  1478  1478 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,07-27 08:54:06.965  1478  1478 D Launcher.HomeView: onStop
07-27 08:54:06.965  1478  1478 V ActivityThread: updateVisibility : ActivityRecord{24a3bd39 token=android.os.BinderProxy@c79e05b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,07-27 08:54:06.965  1017  3008 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-27 08:54:06.975  1017  5905 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,07-27 08:54:06.975  5805  5805 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,07-27 08:54:06.975  1180  1180 I StatusBar: Icon Only
07-27 08:54:06.975  1180  1180 D PanelView: There is/are notification(s) 
07-27 08:54:06.975  1796  1796 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,07-27 08:54:06.995  1478  1478 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@c79e05b time:125075
,07-27 08:54:07.015  1017  1043 W ActivityManager: userId = 0, bbcId = -10000
07-27 08:54:07.015  1017  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-27 08:54:07.015  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,07-27 08:54:07.015  5885  5885 V TaskCloserActivity: TaskCloserActivity enter()
07-27 08:54:07.015  2460  2460 D Recents_RecreateReceiver: onReceive by home
07-27 08:54:07.015  5856  5856 D AndroidRuntime: 
07-27 08:54:07.015  5856  5856 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,07-27 08:54:07.015  1017  1529 W ActivityManager: userId = 0, bbcId = -10000
07-27 08:54:07.015  1017  1529 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
07-27 08:54:07.015  1017  1529 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-27 08:54:07.025  1017  1529 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:07.015  1017  1529 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
07-27 08:54:07.025  1017  1529 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:07.015  5856  5856 D AndroidRuntime: CheckJNI is OFF
07-27 08:54:07.025  1017  1529 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:07.015  5856  5856 D AndroidRuntime: readGMSProperty: start
07-27 08:54:07.025  1017  1529 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:07.025  5856  5856 D AndroidRuntime: readGMSProperty: already setted!!
07-27 08:54:07.025  5856  5856 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-27 08:54:07.025  5856  5856 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-27 08:54:07.025  5856  5856 D AndroidRuntime: readGMSProperty: end
07-27 08:54:07.025  5856  5856 D AndroidRuntime: addProductProperty: start
07-27 08:54:07.025  5885  5885 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,07-27 08:54:07.045  5909  5909 E Zygote  : MountEmulatedStorage(),
07-27 08:54:07.045  5909  5909 E Zygote  : v2
07-27 08:54:07.045  5909  5909 I libpersona: KNOX_SDCARD checking this for 10084
07-27 08:54:07.045  5909  5909 I libpersona: KNOX_SDCARD not a persona
,07-27 08:54:07.045  5909  5909 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-27 08:54:07.045  1017  1529 I ActivityManager: Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=5909 uid=10084 gids={50084, 9997} abi=armeabi-v7a
,07-27 08:54:07.055  5909  5909 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-27 08:54:07.055  5909  5909 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
07-27 08:54:07.055  1017  1529 I ActivityManager: Killing 5445:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
07-27 08:54:07.055  1017  1529 W ActivityManager: userId = 0, bbcId = -10000
07-27 08:54:07.055  1017  1529 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-27 08:54:07.055  1017  1529 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,07-27 08:54:07.065  1017  1048 W ActivityManager: mDVFSHelper.release()
,07-27 08:54:07.065  1017  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{265b59ec u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t7} time:125140
,07-27 08:54:07.075  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200,
,07-27 08:54:07.085  1017  3011 W ActivityManager: userId = 0, bbcId = -10000
07-27 08:54:07.085  1017  3011 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
07-27 08:54:07.085  1017  3011 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-27 08:54:07.085  1017  3011 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,07-27 08:54:07.085  1017  3011 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:07.085  1017  3011 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:07.085  1017  3011 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:07.085  1017  3011 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:54:07.095  5931  5931 E Zygote  : MountEmulatedStorage(),
07-27 08:54:07.095  5931  5931 E Zygote  : v2
07-27 08:54:07.095  5931  5931 I libpersona: KNOX_SDCARD checking this for 10135
07-27 08:54:07.095  5931  5931 I libpersona: KNOX_SDCARD not a persona
,07-27 08:54:07.105  5931  5931 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
07-27 08:54:07.105  1017  3011 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=5931 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
07-27 08:54:07.105  1017  3011 I ActivityManager: Killing 5501:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
07-27 08:54:07.105  5931  5931 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-27 08:54:07.105  5931  5931 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,07-27 08:54:07.115  5909  5909 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:54:07.115  5909  5909 D ActivityThread: Added TimaKeyStore provider
,07-27 08:54:07.125  5931  5931 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:54:07.125  5931  5931 D ActivityThread: Added TimaKeyStore provider
,07-27 08:54:07.135  5858  5858 D NearbySource: Nearby Source Create!
,07-27 08:54:07.135  5858  5858 D NearbyContext: Nearby Context Create!
,07-27 08:54:07.145  1017  1523 D PersonaManager: isKioskContainerExistOnDevice
,07-27 08:54:07.145  5909  5909 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-27 08:54:07.155  5931  5931 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
07-27 08:54:07.155  5931  5931 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-27 08:54:07.155  5931  5931 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
07-27 08:54:07.155  5931  5931 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
07-27 08:54:07.155  5931  5931 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-27 08:54:07.165  1017  1476 I ActivityManager: Killing 5526:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,07-27 08:54:07.175  5856  5856 E AffinityControl: AffinityControl: registerfunction enter
,07-27 08:54:07.185  1017  1529 I ActivityManager: Killing 5462:com.osp.app.signin/u0a36 (adj 15): empty #21
,07-27 08:54:07.185  5858  5858 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
07-27 08:54:07.185   256   546 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
07-27 08:54:07.185  5858  5858 D SLinkSource: Samsung link source created
07-27 08:54:07.185   256   546 W Vold    : Returning OperationFailed - no handler for errno 0
,07-27 08:54:07.205  5856  5856 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,07-27 08:54:07.215  1017  1523 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
07-27 08:54:07.215  1017  1523 D PackageManager: START PACKAGE DELETE: observer{103502227}
07-27 08:54:07.215  1017  1523 D PackageManager: pkg{<packageName>}
07-27 08:54:07.215  1017  1523 D PackageManager: user{0}
07-27 08:54:07.215  1017  1523 D PackageManager: caller{2000}
07-27 08:54:07.215  1017  1523 D PackageManager: flags{2}
07-27 08:54:07.215  1017  1523 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
07-27 08:54:07.215  1017  1523 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
07-27 08:54:07.215  1017  1523 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-27 08:54:07.215  1017  1523 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-27 08:54:07.215  1017  1058 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,07-27 08:54:07.215  1017  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,07-27 08:54:07.215  1017  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
07-27 08:54:07.215  1017  1058 D ApplicationPolicy: getApplicationUninstallationEnabled
07-27 08:54:07.215  1017  1058 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,07-27 08:54:07.215  1017  1058 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
,07-27 08:54:07.215  1017  1043 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
07-27 08:54:07.225  1017  1043 I ActivityManager: Killing 5805:com.test.thalitest/u0a170 (adj 15): stop com.test.thalitest cause uninstall pkg
,07-27 08:54:07.305  1017  1058 W PackageSettings: Skipping PackageSetting{9329c06 com.example.hello/10168} due to missing metadata
,07-27 08:54:07.335  1017  1523 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-27 08:54:07.335  5858  5949 D ContactProvider: getAllContactInfoList Start
,07-27 08:54:07.345  1017  3011 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-27 08:54:07.345  5858  5858 D GalleryCacheReady: Receive : home resume
,07-27 08:54:07.345  1017  1248 W ActivityManager: userId = 0, bbcId = -10000
07-27 08:54:07.345  1017  1248 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,07-27 08:54:07.345  1017  1248 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,07-27 08:54:07.355  1017  1058 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,07-27 08:54:07.355  5344  5344 D Mms/UIEventReceiver: ui event
,07-27 08:54:07.375  1017  1058 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,07-27 08:54:07.425  5468  5468 I art     : Explicit concurrent mark sweep GC freed 15754(888KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 964us total 48.449ms
,07-27 08:54:07.425  1017  1099 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-27 08:54:07.445  1796  1796 E SamsungIME: mOCRHelper is null
,07-27 08:54:07.455  1438  1438 D PersonaManager: isKioskContainerExistOnDevice
,07-27 08:54:07.465  1438  1438 D RegisteredServicesCache: empty dynamic service
,07-27 08:54:07.475  1438  1438 D RegisteredComponentCache: Collect Tech packages for Knox
,07-27 08:54:07.475  1438  1438 D PersonaManager: isKioskContainerExistOnDevice
,07-27 08:54:07.485  5630  5630 I art     : Explicit concurrent mark sweep GC freed 588(34KB) AllocSpace objects, 0(0B) LOS objects, 26% free, 5MB/7MB, paused 762us total 117.553ms
,07-27 08:54:07.515  1017  1123 V NetworkStats: removeUidsLocked() for UIDs [10170]
07-27 08:54:07.515  1017  1123 V NetworkStats: performPollLocked(flags=0x3)
,07-27 08:54:07.515  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,07-27 08:54:07.515  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,07-27 08:54:07.525  3843  3843 I art     : Explicit concurrent mark sweep GC freed 9524(601KB) AllocSpace objects, 4(64KB) LOS objects, 24% free, 12MB/16MB, paused 1.323ms total 153.697ms
,07-27 08:54:07.535  1017  1123 V NetworkStats: performPollLocked() took 13ms
,07-27 08:54:07.575  1017  3008 I art     : Explicit concurrent mark sweep GC freed 47130(3MB) AllocSpace objects, 20(320KB) LOS objects, 33% free, 24MB/36MB, paused 4.900ms total 228.498ms
,07-27 08:54:07.575  1017  1017 I art     : WaitForGcToComplete blocked for 208.837ms for cause Explicit
07-27 08:54:07.575  1017  1477 I splitIntent: Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
,07-27 08:54:07.585  1017  1476 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,07-27 08:54:07.585  1927  2102 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-27 08:54:07.585  1017  1477 W ActivityManager: userId = 0, bbcId = -10000
07-27 08:54:07.585  1017  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-27 08:54:07.585  1017  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,07-27 08:54:07.585  1017  1476 D SecContentProvider2: mCursor = null
,07-27 08:54:07.595  1017  1042 D EnterpriseDeviceManagerService: Package has changed for user 0
07-27 08:54:07.595  1017  1042 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
07-27 08:54:07.595  5885  5885 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
07-27 08:54:07.595  1017  1042 W TextServicesManagerService: no available spell checker services found
,07-27 08:54:07.605  1017  1124 D NtpTrustedTime: forceRefresh() from cache miss
,07-27 08:54:07.605   277   973 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
07-27 08:54:07.605   277   973 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,07-27 08:54:07.605   277   973 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
07-27 08:54:07.605   277   973 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,07-27 08:54:07.615  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-27 08:54:07.615  1017  1124 D NtpTrustedTime: forceRefresh Fail.
,07-27 08:54:07.615  3554  3554 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Jul 27 08:54:07 GMT+02:00 2016
,07-27 08:54:07.615  1017  1464 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
07-27 08:54:07.615  1017  1464 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,07-27 08:54:07.615  1017  1464 W ActivityManager: userId = 0, bbcId = -10000
,07-27 08:54:07.615  1017  1464 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-27 08:54:07.615  1017  1464 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,07-27 08:54:07.625  3554  3554 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,07-27 08:54:07.635  1017  3008 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=23, mSplitNum[2]=33, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=43
07-27 08:54:07.635  1017  3008 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,07-27 08:54:07.635  1017  3008 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,07-27 08:54:07.635  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-27 08:54:07.635  1017  3008 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:54:07.635  1017  3008 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:54:07.635  1017  3008 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:07.635  1017  3008 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:54:07.645  3554  3554 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,07-27 08:54:07.645  3554  3554 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,07-27 08:54:07.645  5954  5954 E Zygote  : MountEmulatedStorage()
,07-27 08:54:07.645  5954  5954 E Zygote  : v2
,07-27 08:54:07.645  5954  5954 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-27 08:54:07.645  5954  5954 I libpersona: KNOX_SDCARD checking this for 10090
07-27 08:54:07.645  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-27 08:54:07.645  5954  5954 I libpersona: KNOX_SDCARD not a persona
,07-27 08:54:07.655  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-27 08:54:07.655  5954  5954 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-27 08:54:07.655  1017  3008 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5954 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a,
,07-27 08:54:07.655  5954  5954 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 08:54:07.665  3554  3554 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,07-27 08:54:07.675  1017  1043 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,07-27 08:54:07.675  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:54:07.675  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:07.675  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:07.675  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:54:07.675  3554  5953 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,07-27 08:54:07.685  5967  5967 E Zygote  : MountEmulatedStorage()
,07-27 08:54:07.685  5967  5967 E Zygote  : v2
07-27 08:54:07.685  5967  5967 I libpersona: KNOX_SDCARD checking this for 1000
07-27 08:54:07.685  5967  5967 I libpersona: KNOX_SDCARD not a persona
,07-27 08:54:07.685  5967  5967 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-27 08:54:07.685  1017  1043 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=5967 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,07-27 08:54:07.695  5967  5967 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-27 08:54:07.695  5967  5967 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-27 08:54:07.695  1017  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
,07-27 08:54:07.705  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:07.705  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0,
07-27 08:54:07.705  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:07.705  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:54:07.705  3554  5953 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
07-27 08:54:07.705  5954  5954 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:54:07.705  5954  5954 D ActivityThread: Added TimaKeyStore provider
,07-27 08:54:07.715  3554  5953 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,07-27 08:54:07.715  3554  5953 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
07-27 08:54:07.725   311   311 I art     : Explicit concurrent mark sweep GC freed 8708(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 616us total 33.771ms
,07-27 08:54:07.725  5344  5344 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
07-27 08:54:07.735   322   322 I ServiceManager: Waiting for service AtCmdFwd...
07-27 08:54:07.745   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 869us total 17.296ms
07-27 08:54:07.755  1017  1017 I art     : Explicit concurrent mark sweep GC freed 15240(1186KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 5.069ms total 172.785ms
07-27 08:54:07.755  1017  1058 I art     : WaitForGcToComplete blocked for 253.908ms for cause Explicit
07-27 08:54:07.755  5967  5967 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:54:07.755  5967  5967 D ActivityThread: Added TimaKeyStore provider
07-27 08:54:07.755   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 569us total 16.720ms
,07-27 08:54:07.765  1017  1042 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,07-27 08:54:07.765  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-27 08:54:07.775  5984  5984 E Zygote  : MountEmulatedStorage()
,07-27 08:54:07.775  5984  5984 E Zygote  : v2
07-27 08:54:07.775  5984  5984 I libpersona: KNOX_SDCARD checking this for 1000
07-27 08:54:07.775  5984  5984 I libpersona: KNOX_SDCARD not a persona
07-27 08:54:07.775  5984  5984 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-27 08:54:07.775  5984  5984 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-27 08:54:07.775  5984  5984 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 08:54:07.775  1017  1043 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=5984 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,07-27 08:54:07.785  1017  1522 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms,
07-27 08:54:07.785  1017  1522 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
,07-27 08:54:07.785  1017  1522 W ActivityManager: userId = 0, bbcId = -10000
07-27 08:54:07.785  1017  1522 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-27 08:54:07.785  1017  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,07-27 08:54:07.805  5858  5949 D ContactProvider: getAllContactInfoList End
07-27 08:54:07.805  5858  5949 I syncContacts: thread: 1023, sync time = 584
,07-27 08:54:07.815  5984  5984 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:54:07.815  5984  5984 D ActivityThread: Added TimaKeyStore provider
,07-27 08:54:07.825  5344  5993 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
,07-27 08:54:07.825  5344  5993 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
07-27 08:54:07.825  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-27 08:54:07.835  1017  1464 I TactileAssist: enable value -1
,07-27 08:54:07.835  1017  1464 I TactileAssist: internal enable value -1
07-27 08:54:07.835  1017  1464 I TactileAssist: intensity value -1
07-27 08:54:07.835  1017  1464 I TactileAssist: saveAppList value true
,07-27 08:54:07.835  1017  1017 D RCPManagerService: PackageReceiver onReceive()
,07-27 08:54:07.845  1017  1017 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,07-27 08:54:07.845  1017  1464 I TactileAssist: List of disabled apps :
,07-27 08:54:07.845  3554  5953 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,07-27 08:54:07.845  1017  1017 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
07-27 08:54:07.845  1017  1017 I OTPFW   : PackageRemovalReceiver::onReceive Enter
07-27 08:54:07.845  1017  1017 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,07-27 08:54:07.845  1017  1017 I OTPFW   : ProvisionData::getAllEntries Enter
,07-27 08:54:07.855  1017  1017 E OTPFW   : ProvisionData::getAllEntries Table is empty
,07-27 08:54:07.855  5954  5954 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,07-27 08:54:07.855  5954  5954 D elm:15121: ELMEngine.ELMEngine( context ).
,07-27 08:54:07.865  5954  5954 D elm:15121: MDMBridge.setEnterpriseBridge()
,07-27 08:54:07.875  1017  1464 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,07-27 08:54:07.875  1017  1464 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,07-27 08:54:07.875  1017  1464 W ActivityManager: userId = 0, bbcId = -10000
,07-27 08:54:07.875  1017  1464 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,07-27 08:54:07.875  1017  1464 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,07-27 08:54:07.875  5984  5984 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
,07-27 08:54:07.885  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-27 08:54:07.885  5954  5954 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
07-27 08:54:07.885  3554  5953 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,07-27 08:54:07.895  3554  5953 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,07-27 08:54:07.895  3172  3172 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,07-27 08:54:07.895  5967  5967 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,07-27 08:54:07.895  3172  3172 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,07-27 08:54:07.895  5954  5954 D elm:15121: ElmAgentService : onCreate()
07-27 08:54:07.895  5954  6002 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
07-27 08:54:07.895  3172  3172 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
07-27 08:54:07.895  3172  3172 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
07-27 08:54:07.895  3172  3172 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
07-27 08:54:07.895  3172  3172 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
07-27 08:54:07.895  3172  3172 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
07-27 08:54:07.895  3172  3172 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:54:07.895  3172  3172 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-27 08:54:07.895  3172  3172 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-27 08:54:07.895  3172  3172 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:54:07.895  3172  3172 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 08:54:07.895  3172  3172 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-27 08:54:07.895  3172  3172 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,07-27 08:54:07.905  5954  6002 D elm:15121: MainReceiver.listeningToPackageRemoved()
07-27 08:54:07.905  5954  6002 D elm:15121: MDMBridge.getInstance()
07-27 08:54:07.905  5954  6002 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,07-27 08:54:07.905  5954  6002 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,07-27 08:54:07.905  3554  3554 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,07-27 08:54:07.905  1017  1476 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
,07-27 08:54:07.905  1017  1476 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,07-27 08:54:07.905  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
07-27 08:54:07.905  1017  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-27 08:54:07.905  1017  1523 D SecContentProvider2: uri = -1 selection = getSealedState
07-27 08:54:07.905  1017  1523 D SecContentProvider2: mCursor = null
,07-27 08:54:07.905  5984  5984 I PopupuiReceiver_KNOX: getSealedState : true
,07-27 08:54:07.905  1017  3011 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
07-27 08:54:07.915  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,07-27 08:54:07.915  1017  3011 D SecContentProvider2: mCursor = null
,07-27 08:54:07.915  5984  5984 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
,07-27 08:54:07.915  1017  1477 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
07-27 08:54:07.915  1017  1477 D SecContentProvider2: mCursor = null
,07-27 08:54:07.915  5984  5984 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
07-27 08:54:07.915  5984  5984 D PopupuiReceiver: Action package removed
,07-27 08:54:07.925  5612  5612 D Compatibility: onReceive() it will make start service
,07-27 08:54:07.935  1017  1030 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
07-27 08:54:07.935  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,07-27 08:54:07.945  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
07-27 08:54:07.945  1017  1042 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-27 08:54:07.945  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-27 08:54:07.945  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,07-27 08:54:07.945  1017  1042 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-27 08:54:07.945  1017  1042 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-27 08:54:07.945  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-27 08:54:07.955  5612  6005 D Compatibility: onHandleIntent()
,07-27 08:54:07.955  5612  6005 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10170, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,07-27 08:54:07.965  5612  6005 D Compatibility: found: 2
07-27 08:54:07.965  1017  1523 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,07-27 08:54:07.965  1017  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:07.965  1017  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:07.965  5612  6005 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
07-27 08:54:07.965  1017  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:07.965  5612  6005 D Compatibility: skipping ResolveInfo{39b880a3 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
07-27 08:54:07.965  1017  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:07.965  5612  6005 D Compatibility: considering ResolveInfo{2bd29fa0 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
07-27 08:54:07.965  5612  6005 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,07-27 08:54:07.965  1017  1017 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,07-27 08:54:07.965  1017  1017 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-27 08:54:07.965  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
07-27 08:54:07.965  1017  1017 V EnterpriseBillingPolicy: uID is 10170
07-27 08:54:07.965  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
07-27 08:54:07.965  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
07-27 08:54:07.965  5612  6005 D Compatibility: enabling receiver ResolveInfo{2b10e759 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,07-27 08:54:07.965  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
07-27 08:54:07.965  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-27 08:54:07.965  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-27 08:54:07.965  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,07-27 08:54:07.975  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,07-27 08:54:07.975  1017  1058 I art     : Explicit concurrent mark sweep GC freed 9303(526KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 3.949ms total 216.658ms
,07-27 08:54:07.975  6006  6006 E Zygote  : MountEmulatedStorage()
07-27 08:54:07.975  6006  6006 E Zygote  : v2
,07-27 08:54:07.975  6006  6006 I libpersona: KNOX_SDCARD checking this for 1000
07-27 08:54:07.975  6006  6006 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-27 08:54:07.975  6006  6006 I libpersona: KNOX_SDCARD not a persona
,07-27 08:54:07.985  6006  6006 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-27 08:54:07.985  1017  1523 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6006 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,07-27 08:54:07.985  6006  6006 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 08:54:07.985  5612  6005 D Compatibility: enabling receiver ResolveInfo{485cf1e com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,07-27 08:54:07.995  5612  6005 D Compatibility: enabling receiver ResolveInfo{14883ff com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,07-27 08:54:08.005  5612  6005 D Compatibility: enabling receiver ResolveInfo{3a5215cc com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,07-27 08:54:08.005  1017  1248 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,07-27 08:54:08.005  1017  1248 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:08.005  1017  1248 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:08.005  1017  1248 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:08.005  1017  1248 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:54:08.015  5612  6005 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,07-27 08:54:08.015  6021  6021 E Zygote  : MountEmulatedStorage()
07-27 08:54:08.015  6021  6021 E Zygote  : v2
07-27 08:54:08.015  6021  6021 I libpersona: KNOX_SDCARD checking this for 10145
07-27 08:54:08.015  6021  6021 I libpersona: KNOX_SDCARD not a persona
,07-27 08:54:08.025  6021  6021 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-27 08:54:08.025  6006  6006 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:54:08.025  1017  1248 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=6021 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-27 08:54:08.025  6021  6021 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-27 08:54:08.025  6006  6006 D ActivityThread: Added TimaKeyStore provider
07-27 08:54:08.025  6021  6021 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 08:54:08.025  1017  1017 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,07-27 08:54:08.025  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
07-27 08:54:08.025  1017  1017 V EnterpriseBillingPolicy: uID is 10170
07-27 08:54:08.025  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
07-27 08:54:08.025  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
07-27 08:54:08.025  1017  2650 D SSRM:bc : MSG_TYPE_APP_REMOVED::
07-27 08:54:08.025  1017  1058 D PackageManager: delete codoeFile: 
07-27 08:54:08.035  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
,07-27 08:54:08.035  1017  1058 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
07-27 08:54:08.035  1017  1058 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,07-27 08:54:08.035  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-27 08:54:08.035  1017  1162 D TaskPersister: removeObsoleteFile: deleting file=9_task.xml
07-27 08:54:08.035  1017  1058 D PackageManager: result of delete: 1{103502227}
,07-27 08:54:08.035  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-27 08:54:08.035  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,07-27 08:54:08.035  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,07-27 08:54:08.035  1017  1017 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
,07-27 08:54:08.045  5954  5954 D elm:15121: ElmAgentService : onDestroy().
,07-27 08:54:08.045  5856  5856 D AndroidRuntime: Shutting down VM
,07-27 08:54:08.045  1017  1476 I ActivityManager: Killing 5556:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,07-27 08:54:08.045  1017  1476 I ActivityManager: Killing 5573:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,07-27 08:54:08.045  1017  3007 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,07-27 08:54:08.055  1017  3007 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,07-27 08:54:08.055  1017  3007 W ActivityManager: userId = 0, bbcId = -10000
07-27 08:54:08.055  1017  3007 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-27 08:54:08.055  1017  3007 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,07-27 08:54:08.055  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,07-27 08:54:08.055  6021  6021 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:54:08.065  6021  6021 D ActivityThread: Added TimaKeyStore provider
,07-27 08:54:08.065  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-27 08:54:08.065  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-27 08:54:08.065  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-27 08:54:08.075  1017  1058 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
07-27 08:54:08.075  1017  1058 D PackageManager: userId{-1}
07-27 08:54:08.075  1017  1058 D PackageManager: andCode{true}
,07-27 08:54:08.075  1017  1058 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,07-27 08:54:08.075  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-27 08:54:08.075  6006  6006 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-27 08:54:08.075  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-27 08:54:08.075  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-27 08:54:08.075  5630  6036 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,07-27 08:54:08.075  1017  1477 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,07-27 08:54:08.075  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-27 08:54:08.075  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-27 08:54:08.085  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-27 08:54:08.085  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:08.085  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:54:08.085  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:08.085  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:54:08.095  6006  6006 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,07-27 08:54:08.105  1017  1029 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
,07-27 08:54:08.105  1017  1029 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,07-27 08:54:08.115  6040  6040 E Zygote  : MountEmulatedStorage()
07-27 08:54:08.115  6040  6040 E Zygote  : v2
07-27 08:54:08.115  6040  6040 I libpersona: KNOX_SDCARD checking this for 10055
07-27 08:54:08.115  6040  6040 I libpersona: KNOX_SDCARD not a persona
,07-27 08:54:08.115  6040  6040 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-27 08:54:08.115  1017  1477 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6040 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
07-27 08:54:08.115  6040  6040 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-27 08:54:08.125  6040  6040 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-27 08:54:08.125  1017  1042 D UsbSettingsManager: clearDefaults: com.test.thalitest
07-27 08:54:08.125  1017  1042 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,07-27 08:54:08.135  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,07-27 08:54:08.135  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:08.135  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:08.135  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:08.135  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:54:08.155  6040  6040 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:54:08.155  6040  6040 D ActivityThread: Added TimaKeyStore provider
,07-27 08:54:08.165  6055  6055 E Zygote  : MountEmulatedStorage(),
07-27 08:54:08.165  6055  6055 E Zygote  : v2
07-27 08:54:08.165  6055  6055 I libpersona: KNOX_SDCARD checking this for 1000
07-27 08:54:08.165  6055  6055 I libpersona: KNOX_SDCARD not a persona
07-27 08:54:08.165  6055  6055 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-27 08:54:08.165  1017  1017 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6055 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-27 08:54:08.165  6055  6055 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-27 08:54:08.165  6055  6055 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 08:54:08.175  6021  6021 D ThemeInfoUtil: getCurrentFestivalName is [null]
07-27 08:54:08.175  6021  6021 D ThemeInfoUtil: isCurrentFestival = false
,07-27 08:54:08.175  1017  3011 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,07-27 08:54:08.175  5672  5672 D FilterInstaller: onReceive:android.intent.action.PACKAGE_REMOVED, package:com.test.thalitest
,07-27 08:54:08.175  5672  5672 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,07-27 08:54:08.185  1017  3011 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:08.185  1017  3011 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:08.185  1017  3011 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:08.185  1017  3011 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:54:08.195  6068  6068 E Zygote  : MountEmulatedStorage()
07-27 08:54:08.195  6068  6068 E Zygote  : v2
07-27 08:54:08.195  6068  6068 I libpersona: KNOX_SDCARD checking this for 10148
07-27 08:54:08.195  6068  6068 I libpersona: KNOX_SDCARD not a persona
,07-27 08:54:08.195  6068  6068 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-27 08:54:08.195  6055  6055 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:54:08.195  6055  6055 D ActivityThread: Added TimaKeyStore provider
,07-27 08:54:08.195  6068  6068 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-27 08:54:08.195  6068  6068 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 08:54:08.205  1017  3011 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=6068 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
,07-27 08:54:08.205  1017  1476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
07-27 08:54:08.205  1017  1476 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4312, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-27 08:54:08.205  1017  1476 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-27 08:54:08.205  1017  1476 D BatteryService: stay LED for fully charged
07-27 08:54:08.205  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:54:08.205  1017  3008 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
07-27 08:54:08.205  1017  3008 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
,07-27 08:54:08.205  1017  3008 W ActivityManager: userId = 0, bbcId = -10000
,07-27 08:54:08.205  1017  3008 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-27 08:54:08.205  1017  3008 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,07-27 08:54:08.215  1017  1248 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-27 08:54:08.215  1017  1248 W ActivityManager: userId = 0, bbcId = -10000
07-27 08:54:08.215  1017  1248 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-27 08:54:08.215  1017  1248 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,07-27 08:54:08.225  5672  5672 I FilterInstaller: FilterPackageService : ACTION_PACKAGE_REMOVED
,07-27 08:54:08.225  5672  6083 I FilterInstaller: FilterPackageService : ACTION_REMOVED
07-27 08:54:08.225  5672  6083 D FilterUnInstaller: before removeFromFS
,07-27 08:54:08.225  1017  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-27 08:54:08.225  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,07-27 08:54:08.225  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,07-27 08:54:08.225  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-27 08:54:08.225  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-27 08:54:08.225  6068  6068 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:54:08.235  6068  6068 D ActivityThread: Added TimaKeyStore provider
,07-27 08:54:08.235  1017  1017 I MotionRecognitionService: Plugged
07-27 08:54:08.235  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,07-27 08:54:08.235  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:54:08.235  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:54:08.245  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-27 08:54:08.245  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-27 08:54:08.245  6040  6040 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,07-27 08:54:08.255  5856  5856 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,07-27 08:54:08.265  6055  6055 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
07-27 08:54:08.265  1017  1464 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-27 08:54:08.265  6055  6055 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
07-27 08:54:08.265  1017  1464 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
07-27 08:54:08.265  6055  6055 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,07-27 08:54:08.265  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 08:54:08.265  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 08:54:08.265  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 08:54:08.265  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-27 08:54:08.265  1180  1180 D SViewCoverView: level :100 plugged : 2
,07-27 08:54:08.265  1017  1464 W ActivityManager: userId = 0, bbcId = -10000
07-27 08:54:08.265  1017  1464 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-27 08:54:08.265  1017  1464 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-27 08:54:08.265  1017  1029 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.provider.filterprovider,
07-27 08:54:08.275  6040  6040 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
07-27 08:54:08.275  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:08.275  6040  6040 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
,07-27 08:54:08.275  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:08.275  6040  6040 D UserAnalysis: Create SecureDbHelper
07-27 08:54:08.275  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:08.275  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:54:08.285  6086  6086 E Zygote  : MountEmulatedStorage()
,07-27 08:54:08.285  6086  6086 E Zygote  : v2
07-27 08:54:08.285  6086  6086 I libpersona: KNOX_SDCARD checking this for 10095
07-27 08:54:08.285  6086  6086 I libpersona: KNOX_SDCARD not a persona
,07-27 08:54:08.285  6086  6086 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-27 08:54:08.285  1017  1029 I ActivityManager: Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=6086 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
,07-27 08:54:08.285  6086  6086 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-27 08:54:08.285  6086  6086 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 08:54:08.295  1017  1522 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,07-27 08:54:08.295  1017  1522 W ActivityManager: userId = 0, bbcId = -10000
07-27 08:54:08.295  1017  1522 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-27 08:54:08.295  1017  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-27 08:54:08.295  6040  6040 D IntelligenceServiceApplication: onCreate()
,07-27 08:54:08.295  6040  6040 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,07-27 08:54:08.305  1017  3008 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-27 08:54:08.305  1017  3008 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,07-27 08:54:08.305  1017  3008 W ActivityManager: userId = 0, bbcId = -10000
07-27 08:54:08.305  1017  3008 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-27 08:54:08.305  1017  3008 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-27 08:54:08.315  6040  6040 D IntelligenceServiceApplication: no applications having user consent for prediction
,07-27 08:54:08.315  6086  6086 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:54:08.315  6086  6086 D ActivityThread: Added TimaKeyStore provider
,07-27 08:54:08.315  1017  1477 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
,07-27 08:54:08.325  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:08.325  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:08.325  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:08.325  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:54:08.325  6055  6055 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
07-27 08:54:08.325  6055  6055 I PCWCLIENTTRACE_PushUtil: sales region : global
,07-27 08:54:08.325  6055  6055 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,07-27 08:54:08.325  6055  6055 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,07-27 08:54:08.335  6104  6104 E Zygote  : MountEmulatedStorage()
07-27 08:54:08.335  6104  6104 E Zygote  : v2
07-27 08:54:08.335  6104  6104 I libpersona: KNOX_SDCARD checking this for 1000
07-27 08:54:08.335  6104  6104 I libpersona: KNOX_SDCARD not a persona
07-27 08:54:08.335  6104  6104 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,07-27 08:54:08.335  6104  6104 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-27 08:54:08.335  6104  6104 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 08:54:08.345  1017  1477 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6104 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,07-27 08:54:08.345  1017  1523 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-27 08:54:08.345  1017  1523 W ActivityManager: userId = 0, bbcId = -10000
07-27 08:54:08.355  1017  1523 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-27 08:54:08.355  1017  1523 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-27 08:54:08.355  6068  6068 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,07-27 08:54:08.355  1017  3010 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,07-27 08:54:08.365  1017  3010 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
07-27 08:54:08.365  1017  3010 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,07-27 08:54:08.365  5753  6102 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
07-27 08:54:08.365  1017  3010 W ActivityManager: userId = 0, bbcId = -10000
07-27 08:54:08.365  1017  3010 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-27 08:54:08.365  1017  3010 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,07-27 08:54:08.365  6040  6040 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,07-27 08:54:08.365  1017  1464 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,07-27 08:54:08.375  1017  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:08.375  1017  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:08.375  1017  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:08.375  1017  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:54:08.375  6104  6104 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:54:08.375  6104  6104 D ActivityThread: Added TimaKeyStore provider
,07-27 08:54:08.385  6121  6121 E Zygote  : MountEmulatedStorage()
07-27 08:54:08.385  6121  6121 I libpersona: KNOX_SDCARD checking this for 10029
07-27 08:54:08.385  6121  6121 E Zygote  : v2
07-27 08:54:08.385  6121  6121 I libpersona: KNOX_SDCARD not a persona
,07-27 08:54:08.385  6121  6121 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-27 08:54:08.395  6121  6121 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
07-27 08:54:08.395  1017  1464 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6121 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,07-27 08:54:08.395  6121  6121 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 08:54:08.395  6086  6086 D PreloadFilterInstaller: uses FILTER_DB_VER_1
,07-27 08:54:08.395  6086  6086 E SQLiteLog: (28) failed to open "/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db" with flag (131138) and mode_t (0) due to error (30)
07-27 08:54:08.395  1017  1464 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,07-27 08:54:08.395  1017  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:08.395  1017  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:08.395  1017  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:08.395  1017  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:54:08.405  6040  6040 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
07-27 08:54:08.405  6040  6040 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
,07-27 08:54:08.415  6121  6121 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:54:08.415  6121  6121 D ActivityThread: Added TimaKeyStore provider
,07-27 08:54:08.415  5753  6102 W FileUtils: Failed to chmod(/data/data/com.samsung.android.sm/databases/seatbelt.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,07-27 08:54:08.415  6040  6040 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
07-27 08:54:08.415  6040  6040 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 08:54:08.415  6040  6040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 08:54:08.415  6040  6040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-27 08:54:08.415  6040  6040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-27 08:54:08.415  6040  6040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-27 08:54:08.415  6040  6040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-27 08:54:08.415  6040  6040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-27 08:54:08.415  6040  6040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-27 08:54:08.415  6040  6040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-27 08:54:08.415  6040  6040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-27 08:54:08.415  6040  6040 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-27 08:54:08.415  6040  6040 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-27 08:54:08.415  6040  6040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 08:54:08.415  6040  6040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-27 08:54:08.415  6040  6040 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:204)
07-27 08:54:08.415  6040  6040 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:78)
07-27 08:54:08.415  6040  6040 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
07-27 08:54:08.415  6040  6040 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-27 08:54:08.415  6040  6040 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-27 08:54:08.415  6040  6040 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-27 08:54:08.415  6040  6040 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:54:08.415  6040  6040 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 08:54:08.415  6040  6040 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-27 08:54:08.415  6040  6040 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-27 08:54:08.415  6040  6040 D AndroidRuntime: Shutting down VM
07-27 08:54:08.415  6040  6040 E AndroidRuntime: FATAL EXCEPTION: main
07-27 08:54:08.415  6040  6040 E AndroidRuntime: Process: com.samsung.android.intelligenceservice, PID: 6040
07-27 08:54:08.415  6040  6040 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 08:54:08.415  6040  6040 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 08:54:08.415  6040  6040 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-27 08:54:08.415  6040  6040 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-27 08:54:08.415  6040  6040 E AndroidRuntime: 	at android.d,atabase.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-27 08:54:08.415  6040  6040 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-27 08:54:08.415  6040  6040 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-27 08:54:08.415  6040  6040 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-27 08:54:08.415  6040  6040 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-27 08:54:08.415  6040  6040 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-27 08:54:08.415  6040  6040 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-27 08:54:08.415  6040  6040 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-27 08:54:08.415  6040  6040 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 08:54:08.415  6040  6040 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-27 08:54:08.415  6040  6040 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:204)
07-27 08:54:08.415  6040  6040 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:78)
07-27 08:54:08.415  6040  6040 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
07-27 08:54:08.415  6040  6040 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-27 08:54:08.415  6040  6040 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
07-27 08:54:08.415  6040  6040 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-27 08:54:08.415  6040  6040 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:54:08.415  6040  6040 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 08:54:08.415  6040  6040 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-27 08:54:08.415  6040  6040 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-27 08:54:08.415  6133  6133 E Zygote  : MountEmulatedStorage()
07-27 08:54:08.415  6133  6133 I libpersona: KNOX_SDCARD checking this for 10152
07-27 08:54:08.415  6133  6133 E Zygote  : v2
07-27 08:54:08.415  6133  6133 I libpersona: KNOX_SDCARD not a persona
07-27 08:54:08.415  6086  6086 E SQLiteDatabase: Failed to open database '/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db'.
07-27 08:54:08.415  6086  6086 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 08:54:08.415  6086  6086 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 08:54:08.415  6086  6086 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-27 08:54:08.415  6086  6086 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-27 08:54:08.415  6086  6086 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-27 08:54:08.415  6086  6086 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-27 08:54:08.415  6086  6086 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-27 08:54:08.415  6086  6086 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-27 08:54:08.415  6086  6086 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-27 08:54:08.415  6086  6086 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-27 08:54:08.415  6086  6086 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-27 08:54:08.415  6086  6086 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-27 08:54:08.415  6086  6086 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 08:54:08.415  6086  6086 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-27 08:54:08.415  6086  6086 E SQLiteDatabase: 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:423)
07-27 08:54:08.415  6086  6086 E SQLiteDatabase: 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.loadExternalFilters(PreloadFilterInstaller.java:122)
07-27 08:54:08.415  6086  6086 E SQLiteDatabase: 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.installFilters(PreloadFilterInstaller.java:100)
07-27 08:54:08.415  6086  6086 E SQLiteDatabase: 	at com.samsung.android.provider.filterprovider.FilterProvider.onCreate(FilterProvider.java:179)
07-27 08:54:08.415  6086  6086 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
07-27 08:54:08.415  6086  6086 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
07-27 08:54:08.415  6086  6086 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
07-27 08:54:08.415  6086  6086 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
07-27 08:54:08.415  6086  6086 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
07-27 08:54:08.415  6086  6086 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
07-27 08:54:08.415  6086  6086 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
07-27 08:54:08.415  6086  6086 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:54:08.415  6086  6086 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-27 08:54:08.415  6086  6086 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-27 08:54:08.415  6086  6086 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:54:08.415  6086  6086 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 08:54:08.415  6086  6086 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-27 08:54:08.415  6086  6086 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-27 08:54:08.415  6086  6086 E SQLiteOpenHelper: Couldn't open filter.db for writing (will try read-only):
07-27 08:54:08.415  6086  6086 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 08:54:08.415  6086  6086 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 08:54:08.415  6086  6086 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-27 08:54:08.415  6086  6086 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-27 08:54:08.415  6086  6086 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-27 08:54:08.415  6086  6086 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-27 08:54:08.415  6086  6086 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-27 08:54:08.415  6086  6086 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-27 08:54:08.415  6086  6086 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-27 08:54:08.415  6086  6086 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-27 08:54:08.415  6086  6086 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-27 08:54:08.415  6086  6086 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-27 08:54:08.415  6086  6086 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 08:54:08.415  6086  6086 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-27 08:54:08.415  6086  6086 E SQLiteOpenHelper: 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:423)
07-27 08:54:08.415  6086  6086 E SQLiteOpenHelper: 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.loadExternalFilters(PreloadFilterInstaller.java:122)
07-27 08:54:08.415  6086  6086 E SQLiteOpenHelper: 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.installFilters(PreloadFilterInstaller.java:100)
07-27 08:54:08.415  6086  6086 E SQLiteOpenHelper: 	at com.samsung.android.provider.filterprovider.FilterProvider.onCreate(FilterProvider.java:179)
07-27 08:54:08.415  6086  6086 E SQLiteOpenHelper: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
07-27 08:54:08.415  6086  6086 E SQLiteOpenHelper: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
07-27 08:54:08.415  6086  6086 E SQLiteOpenHelper: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
07-27 08:54:08.415  6086  6086 E SQLiteOpenHelper: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
07-27 08:54:08.415  6086  6086 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
07-27 08:54:08.415  6086  6086 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
07-27 08:54:08.415  6086  6086 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
07-27 08:54:08.415  6086  6086 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:54:08.415  6086  6086 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
07-27 08:54:08.415  6086  6086 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-27 08:54:08.415  6086  6086 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:54:08.415  6086  6086 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 08:54:08.415  6086  6086 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-27 08:54:08.415  6086  6086 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-27 08:54:08.415  6133  6133 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-27 08:54:08.425  6086  6086 W SQLiteOpenHelper: Opened filter.db in read-only mode
07-27 08:54:08.425  1017  1464 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=6133 uid=10152 gids={50152, 9997} abi=armeabi-v7a
07-27 08:54:08.425  6133  6133 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-27 08:54:08.425  6086  6086 E SQLiteLog: (284) automatic index on titles(filter_id)
07-27 08:54:08.425  6133  6133 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-27 08:54:08.435  1017  1477 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.intelligenceservice
07-27 08:54:08.445  5753  5753 W FileUtils: Failed to chmod(/data/data/com.samsung.android.sm/databases/history.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
07-27 08:54:08.445  5753  5753 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
07-27 08:54:08.445  5753  5753 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM app_history WHERE package_name=?] disk I/O error
,07-27 08:54:08.445  6040  6040 I Process : Sending signal. PID: 6040 SIG: 9
07-27 08:54:08.455  5753  5753 D AndroidRuntime: Shutting down VM
07-27 08:54:08.455  1017  1464 I ActivityManager: Killing 5597:com.wsomacp/u0a23 (adj 15): empty #21
07-27 08:54:08.455  5753  5753 E AndroidRuntime: FATAL EXCEPTION: main
07-27 08:54:08.455  5753  5753 E AndroidRuntime: Process: com.samsung.android.sm, PID: 5753
07-27 08:54:08.455  5753  5753 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.samsung.android.sm.ui.security.MonitorReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-27 08:54:08.455  5753  5753 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3132)
07-27 08:54:08.455  5753  5753 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
07-27 08:54:08.455  5753  5753 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
07-27 08:54:08.455  5753  5753 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:54:08.455  5753  5753 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
07-27 08:54:08.455  5753  5753 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-27 08:54:08.455  5753  5753 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:54:08.455  5753  5753 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 08:54:08.455  5753  5753 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-27 08:54:08.455  5753  5753 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-27 08:54:08.455  5753  5753 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-27 08:54:08.455  5753  5753 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-27 08:54:08.455  5753  5753 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
07-27 08:54:08.455  5753  5753 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-27 08:54:08.455  5753  5753 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-27 08:54:08.455  5753  5753 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1637)
07-27 08:54:08.455  5753  5753 E AndroidRuntime: 	at com.samsung.android.sm.common.security.m.b(ScanHistoryHelper.java:222)
07-27 08:54:08.455  5753  5753 E AndroidRuntime: 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:175)
07-27 08:54:08.455  5753  5753 E AndroidRuntime: 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:67)
07-27 08:54:08.455  5753  5753 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
07-27 08:54:08.455  5753  5753 E AndroidRuntime: 	... 9 more
07-27 08:54:08.465  6133  6133 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:54:08.465  6133  6133 D ActivityThread: Added TimaKeyStore provider
07-27 08:54:08.465  1017  3008 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.sm
07-27 08:54:08.465  1017  3011 I ActivityManager: Killing 5178:com.android.vending/u0a26 (adj 15): empty #21
07-27 08:54:08.465  5753  6102 I art     : Explicit concurrent mark sweep GC freed 894(97KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 4MB/6MB, paused 1.047ms total 52.148ms
07-27 08:54:08.465  1017  1477 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-27 08:54:08.465  1017  1477 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.LightweightIndexService$LightweightWorkerService; callingUser = 0; userId(target) = 0
07-27 08:54:08.475  1017  1477 W ActivityManager: userId = 0, bbcId = -10000
07-27 08:54:08.475  1017  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-27 08:54:08.475  1017  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-27 08:54:08.485  1017  1476 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.sm, calleePkgName: com.sec.android.provider.badge
07-27 08:54:08.485  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:08.485  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:08.485  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:08.485  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:08.485  1017  6152 E DropBoxManagerService: Can't write: system_app_crash
07-27 08:54:08.485  1017  6152 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop169.tmp: open failed: EROFS (Read-only file system)
07-27 08:54:08.485  1017  6152 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-27 08:54:08.485  1017  6152 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-27 08:54:08.485  1017  6152 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-27 08:54:08.485  1017  6152 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-27 08:54:08.485  1017  6152 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-27 08:54:08.485  1017  6152 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15777)
07-27 08:54:08.485  1017  6152 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-27 08:54:08.485  1017  6152 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-27 08:54:08.485  1017  6152 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-27 08:54:08.485  1017  6152 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-27 08:54:08.485  1017  6152 E DropBoxManagerService: 	... 5 more
07-27 08:54:08.485  1017  6149 E DropBoxManagerService: Can't write: system_app_crash
07-27 08:54:08.485  1017  6149 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop168.tmp: open failed: EROFS (Read-only file system)
07-27 08:54:08.485  1017  6149 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-27 08:54:08.485  1017  6149 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-27 08:54:08.485  1017  6149 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-27 08:54:08.485  1017  6149 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-27 08:54:08.485  1017  6149 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-27 08:54:08.485  1017  6149 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15777)
07-27 08:54:08.485  1017  6149 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-27 08:54:08.485  1017  6149 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-27 08:54:08.485  1017  6149 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-27 08:54:08.485  1017  6149 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-27 08:54:08.485  1017  6149 E DropBoxManagerService: 	... 5 more

```
