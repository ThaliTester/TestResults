#### Test 625090941eef958_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main
03-17 08:36:32.128   319   319 I ServiceManager: Waiting for service AtCmdFwd...
--------- beginning of system
03-17 08:36:32.378  1019  2802 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 08:36:33.098  5950  5950 D AndroidRuntime: 
03-17 08:36:33.098  5950  5950 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-17 08:36:33.098  5950  5950 D AndroidRuntime: CheckJNI is OFF
03-17 08:36:33.098  5950  5950 D AndroidRuntime: readGMSProperty: start
03-17 08:36:33.098  5950  5950 D AndroidRuntime: readGMSProperty: already setted!!
03-17 08:36:33.098  5950  5950 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-17 08:36:33.098  5950  5950 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-17 08:36:33.098  5950  5950 D AndroidRuntime: readGMSProperty: end
03-17 08:36:33.098  5950  5950 D AndroidRuntime: addProductProperty: start
03-17 08:36:33.108   290   290 E SMD     : DCD OFF
03-17 08:36:33.128   319   319 I ServiceManager: Waiting for service AtCmdFwd...
03-17 08:36:33.238  5950  5950 E AffinityControl: AffinityControl: registerfunction enter
03-17 08:36:33.258  5950  5950 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-17 08:36:33.278  1019  1331 E PersonaManagerService: inState():  stateMachine is null !!
03-17 08:36:33.278  1019  1331 I PersonaManagerService: PersonaId don't exist
03-17 08:36:33.278  1019  1331 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-17 08:36:33.278  1019  1331 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 08:36:33.298  1019  1331 W ActivityManager: mDVFSHelper.acquire()
03-17 08:36:33.298  1019  1331 D FocusedStackFrame: Set to : 0
03-17 08:36:33.308  1019  1331 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:36:33.308  1019  1331 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:36:33.308  1019  1331 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:36:33.308  1019  1331 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:36:33.308  1019  1049 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-17 08:36:33.308  1019  1049 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-17 08:36:33.318  5962  5962 E Zygote  : MountEmulatedStorage()
03-17 08:36:33.318  5962  5962 E Zygote  : v2
03-17 08:36:33.318  5962  5962 I libpersona: KNOX_SDCARD checking this for 10167
03-17 08:36:33.318  5962  5962 I libpersona: KNOX_SDCARD not a persona
03-17 08:36:33.318  1019  1331 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5962 uid=10167 gids={50167, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-17 08:36:33.318  1019  1331 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-17 08:36:33.318  1019  1331 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 08:36:33.318  5962  5962 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 08:36:33.328  1019  1331 D InputDispatcher: Focused application set to: xxxx
03-17 08:36:33.328  1019  1331 D InputDispatcher: Focus left window: 1488
03-17 08:36:33.328  5950  5950 D AndroidRuntime: Shutting down VM
03-17 08:36:33.328  5962  5962 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 08:36:33.328  5962  5962 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-17 08:36:33.328  1019  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-17 08:36:33.328  1019  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-17 08:36:33.328   259   259 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
03-17 08:36:33.348  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 08:36:33.348  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 08:36:33.358  5962  5962 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 08:36:33.358  5962  5962 D ActivityThread: Added TimaKeyStore provider
03-17 08:36:33.358  1019  1510 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-17 08:36:33.358  1019  1019 V ActivityManager: Display changed displayId=0
03-17 08:36:33.368  1019  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-17 08:36:33.378  1019  1510 D PersonaManager: isKioskContainerExistOnDevice
03-17 08:36:33.398  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
03-17 08:36:33.398   259   683 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
03-17 08:36:33.398   259   443 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
03-17 08:36:33.408  1488  1488 V ActivityThread: updateVisibility : ActivityRecord{d09a385 token=android.os.BinderProxy@24e83986 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-17 08:36:33.408  1488  1488 D Launcher: onTrimMemory. Level: 20
03-17 08:36:33.488  5962  5962 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
03-17 08:36:33.498  5962  5962 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 2794-2796)
03-17 08:36:33.498  5962  5962 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-17 08:36:33.518  5962  5962 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1d508e70}
03-17 08:36:33.528  5962  5962 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-17 08:36:33.528  5962  5962 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
03-17 08:36:33.548  5950  5950 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
03-17 08:36:33.558  5962  5962 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-17 08:36:33.558  5962  5962 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-17 08:36:33.558  5962  5962 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-17 08:36:33.568  5962  5962 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-17 08:36:33.578  5962  5962 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-17 08:36:33.578  5962  5962 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-17 08:36:33.578  5962  5962 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 08:36:33.578  5962  5962 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 08:36:33.578  5962  5962 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 08:36:33.578  5962  5962 I Adreno-EGL: Local Branch: 
03-17 08:36:33.578  5962  5962 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 08:36:33.578  5962  5962 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 08:36:33.578  5962  5962 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 08:36:33.788  5962  5962 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 08:36:33.798  5962  5962 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-17 08:36:33.808  5962  5962 D PhoneWindow: *FMB* installDecor mIsFloating : false
,03-17 08:36:33.808  5962  5962 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-17 08:36:33.818  5962  5962 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-17 08:36:33.818  5962  5962 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 08:36:33.818  5962  5962 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 08:36:33.888  1019  1044 W ActivityManager: Activity pause timeout for ActivityRecord{3986d3c7 u0 com.test.thalitest/.MainActivity t22}
,03-17 08:36:33.968  5962  6002 D OpenGLRenderer: Render dirty regions requested: true
,03-17 08:36:33.968  1019  1139 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,03-17 08:36:33.968  1019  1139 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-17 08:36:33.968  1019  1139 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-17 08:36:33.968  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-17 08:36:33.978  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
,03-17 08:36:33.978  5962  5989 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-17 08:36:33.988  5962  5962 V ActivityThread: updateVisibility : ActivityRecord{142116b8 token=android.os.BinderProxy@1416f32a {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,03-17 08:36:33.988  5962  5962 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,03-17 08:36:33.988  5962  5962 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-17 08:36:33.998   259   259 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,03-17 08:36:34.008  1019  1818 D InputDispatcher: Focus entered window: 5962
,03-17 08:36:34.018  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 08:36:34.018  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 08:36:34.018  5962  5962 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-17 08:36:34.018  5962  6002 I OpenGLRenderer: Initialized EGL, version 1.4
,03-17 08:36:34.028  5962  6002 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,03-17 08:36:34.028  5962  6002 D OpenGLRenderer: Enabling debug mode 0
,03-17 08:36:34.058  1019  3767 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-17 08:36:34.068  1177  1177 I StatusBar: Icon Only
,03-17 08:36:34.068  1177  1177 D PanelView: There is/are notification(s) 
,03-17 08:36:34.068  1019  6005 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 08:36:34.078  1019  1049 I ActivityManager: Displayed Component not be shown by security: +691ms (total +770ms)
,03-17 08:36:34.078  1019  1049 W ActivityManager: mDVFSHelper.release()
03-17 08:36:34.078  1019  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3986d3c7 u0 com.test.thalitest/.MainActivity t22} time:83374
,03-17 08:36:34.078  5962  5962 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-17 08:36:34.078  5962  5962 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1416f32a time:83379
03-17 08:36:34.088   259   443 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
03-17 08:36:34.088   259   683 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,03-17 08:36:34.088  1864  1864 I SamsungIME: getCurrentCandidateView
,03-17 08:36:34.128   319   319 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,03-17 08:36:34.128  5962  5962 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5962
,03-17 08:36:34.158  1019  1097 V AlarmManager: waitForAlarm result :4
,03-17 08:36:34.168  1177  1177 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,03-17 08:36:34.168  1177  1177 D KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
03-17 08:36:34.168  1177  1177 V KeyguardEffectViewController: *** Keyguard wallpaper service already unbounded
,03-17 08:36:34.178  1864  1864 D SamsungIME: Dismiss ExpandCandiate
,03-17 08:36:34.238  1864  1864 I SamsungIME: getDebugLevel  : 0x4f4c
,03-17 08:36:34.278  1864  1864 I SamsungIME: getDebugLevel  : 0x4f4c
,03-17 08:36:34.278  5962  5962 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-17 08:36:34.308  1864  1864 I SamsungIME: KeybaordView init() : load resources
,03-17 08:36:34.348  1864  1864 I SamsungIME: getCurrentKeyboard
,03-17 08:36:34.348  1864  1864 I SamsungIME: getTextKeyboard
,03-17 08:36:34.358  1864  1864 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-17 08:36:34.528  5962  6004 D jxcore_app_log: JniHelper::setJavaVM(0xb8114448), pthread_self() = -1201191648
,03-17 08:36:34.538  5962  6004 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-17 08:36:34.538  5962  6004 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-17 08:36:34.538  5962  6004 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-17 08:36:34.538  5962  6004 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-17 08:36:34.538  5962  6004 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,03-17 08:36:34.538  5962  6004 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f71c01 added. We now have 1 listener(s)
,03-17 08:36:34.548  5962  6004 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,03-17 08:36:34.548  5962  6004 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:EC:A9:50:75:41"}
,03-17 08:36:34.548  5962  6004 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"08:EC:A9:50:75:41"}
,03-17 08:36:34.548  5962  6004 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
,03-17 08:36:34.558  5962  6004 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-17 08:36:34.558  5962  6004 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-17 08:36:34.558  5962  6004 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-17 08:36:34.558  5962  6004 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-17 08:36:34.558  5962  6004 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
03-17 08:36:34.558  5962  6004 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-17 08:36:34.558  5962  6004 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-17 08:36:34.558  5962  6004 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-17 08:36:34.558  5962  6004 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-17 08:36:34.558  5962  6004 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-17 08:36:34.558  5962  6004 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,03-17 08:36:34.558  5962  6004 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dc8b094 added. We now have 1 listener(s)
,03-17 08:36:34.558  5962  6004 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-17 08:36:34.568  5962  6004 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-17 08:36:34.568  5962  6004 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
03-17 08:36:34.568  5962  6004 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-17 08:36:34.568  5962  6004 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-17 08:36:34.568  5962  6004 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-17 08:36:34.568  5962  6004 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-17 08:36:34.578  5962  6004 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
,03-17 08:36:34.578  5962  6004 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-17 08:36:34.578  5962  6004 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-17 08:36:34.578  5962  6004 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-17 08:36:34.578  5962  6004 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-17 08:36:34.578  5962  6004 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-17 08:36:34.578  5962  6004 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-17 08:36:34.578  5962  6004 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-17 08:36:34.578  5962  6004 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-17 08:36:34.578  5962  6004 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-17 08:36:34.578  5962  6004 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-17 08:36:34.588  5962  5962 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 08:36:34.588  5962  5962 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 08:36:34.608  5962  5962 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-17 08:36:34.868  1019  1051 I PowerManagerService: [PWL] Off : 5s ago
,03-17 08:36:34.868  1019  1051 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
03-17 08:36:34.868  1019  1051 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
03-17 08:36:34.868  1019  1051 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10011, pid=2029, ws=null) (elapsedTime=47291)
,03-17 08:36:35.178  5962  6012 W jxcore-log: Initializing JXcore engine
03-17 08:36:35.178  5962  6012 W jxcore-log: JXcore engine is ready
,03-17 08:36:35.228  1854  1854 E audit   : type=1400 msg=audit(1458200195.228:205): avc:  denied  { ioctl } for  pid=6012 comm="Thread-1029" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-17 08:36:35.228  1854  1854 E audit   :  SEPF_SM-A300FU_5.0.2_0027
03-17 08:36:35.228  1854  1854 E audit   : type=1300 msg=audit(1458200195.228:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=b a1=5451 a2=3 a3=9da008f8 items=0 ppid=311 ppcomm=main pid=6012 auid=4294967295 uid=10167 gid=10167 euid=10167 suid=10167 fsuid=10167 egid=10167 sgid=10167 fsgid=10167 ses=4294967295 tty=(none) comm="Thread-1029" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-17 08:36:35.228  1854  1854 E audit   : type=1320 msg=audit(1458200195.228:205): 
,03-17 08:36:35.238  5962  6012 W jxcore-log: Starting JXcore engine
,03-17 08:36:35.338  5962  6012 W jxcore-log: Platform android
03-17 08:36:35.338  5962  6012 W jxcore-log: 
03-17 08:36:35.338  5962  6012 W jxcore-log: Process ARCH arm
03-17 08:36:35.338  5962  6012 W jxcore-log: 
,03-17 08:36:35.548  5962  6012 I jxcore-log: JXcore Cordova bridge is ready!
03-17 08:36:35.548  5962  6012 I jxcore-log: 
,03-17 08:36:35.548  5962  6012 W jxcore-log: JXcore engine is started
,03-17 08:36:35.558  5962  6004 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-17 08:36:35.558  5962  5962 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41),
,03-17 08:36:35.568  5962  6012 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-17 08:36:35.568  5962  6012 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-17 08:36:35.568  5962  5962 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,03-17 08:36:35.578  5962  5962 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,03-17 08:36:35.578  1019  1502 D FocusedStackFrame: Set to : 0
03-17 08:36:35.578  1019  1502 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 08:36:35.578  1019  1502 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-17 08:36:35.578  1019  1502 D InputDispatcher: Focused application set to: xxxx
03-17 08:36:35.578  1019  1502 D InputDispatcher: Focus left window: 5962
03-17 08:36:35.588  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 08:36:35.588  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 08:36:35.588  1019  1502 I ActivityManager: Killing 4986:com.sec.android.app.music:service/u0a35 (adj 15): empty #31
03-17 08:36:35.598  5962  6004 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 19ms. Plugin should use CordovaInterface.getThreadPool().
,03-17 08:36:35.608   259   683 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
,03-17 08:36:35.608   259   450 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,03-17 08:36:35.628  1019  3946 W ActivityManager: mDVFSHelper.acquire()
,03-17 08:36:35.628  5962  5962 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@ab8773d that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 08:36:35.628  5962  5962 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@ab8773d that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 08:36:35.628  5962  5962 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-17 08:36:35.628  5962  5962 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-17 08:36:35.628  5962  5962 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-17 08:36:35.628  5962  5962 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-17 08:36:35.628  5962  5962 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-17 08:36:35.628  5962  5962 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:503)
03-17 08:36:35.628  5962  5962 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:67)
03-17 08:36:35.628  5962  5962 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-17 08:36:35.628  5962  5962 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-17 08:36:35.628  5962  5962 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-17 08:36:35.628  5962  5962 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-17 08:36:35.628  5962  5962 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-17 08:36:35.628  5962  5962 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-17 08:36:35.628  5962  5962 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-17 08:36:35.628  5962  5962 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-17 08:36:35.628  5962  5962 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-17 08:36:35.628  5962  5962 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-17 08:36:35.628  5962  5962 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 08:36:35.628  5962  5962 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-17 08:36:35.628  5962  5962 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 08:36:35.638  1019  3946 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,03-17 08:36:35.648  5962  5962 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@3b0d8b32 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 08:36:35.648  5962  5962 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@3b0d8b32 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 08:36:35.648  5962  5962 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-17 08:36:35.648  5962  5962 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-17 08:36:35.648  5962  5962 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-17 08:36:35.648  5962  5962 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-17 08:36:35.648  5962  5962 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-17 08:36:35.648  5962  5962 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.initialize(BluetoothManager.java:275)
03-17 08:36:35.648  5962  5962 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.bind(BluetoothManager.java:103)
03-17 08:36:35.648  5962  5962 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:75)
03-17 08:36:35.648  5962  5962 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-17 08:36:35.648  5962  5962 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-17 08:36:35.648  5962  5962 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-17 08:36:35.648  5962  5962 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-17 08:36:35.648  5962  5962 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-17 08:36:35.648  5962  5962 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-17 08:36:35.648  5962  5962 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-17 08:36:35.648  5962  5962 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-17 08:36:35.648  5962  5962 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-17 08:36:35.648  5962  5962 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-17 08:36:35.648  5962  5962 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 08:36:35.648  5962  5962 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-17 08:36:35.648  5962  5962 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 08:36:35.658  1488  1488 D Launcher: onRestart, Launcher: 373497103
,03-17 08:36:35.658  1488  1488 D Launcher: onStart, Launcher: 373497103
,03-17 08:36:35.668  1488  1488 D Launcher.HomeView: onStart
,03-17 08:36:35.668  1488  1488 D Launcher: onResume, Launcher: 373497103
,03-17 08:36:35.668  1019  3767 D SettingsProvider: name = kids_home_mode
03-17 08:36:35.668  1019  3767 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 08:36:35.668  1019  3767 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
03-17 08:36:35.668  1019  3767 D SettingsProvider: selectionArgs: false,
03-17 08:36:35.668  1019  3767 D SettingsProvider: selectionArgs: 10006
03-17 08:36:35.668  1019  3767 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 08:36:35.668  1019  3767 D SettingsProvider: ret = -1
03-17 08:36:35.668  1488  1488 D Launcher.HomeView: onResume
,03-17 08:36:35.678  1488  1488 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-17 08:36:35.678  1019  1044 W ActivityManager: userId = 0, bbcId = -10000
,03-17 08:36:35.678  1019  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 08:36:35.678  1019  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,03-17 08:36:35.688  1488  1488 D MenuAppsGridFragment: onResume
,03-17 08:36:35.688  1019  1032 D ActivityManager: handle home activity for 0
,03-17 08:36:35.688  1019  1032 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
03-17 08:36:35.688  1019  1032 D KnoxTimeoutHandler: post home show event for user 0
,03-17 08:36:35.688  1019  1019 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
03-17 08:36:35.688  1019  1032 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-17 08:36:35.688  1019  1019 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
03-17 08:36:35.688  1019  1032 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-17 08:36:35.688  1019  1032 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-17 08:36:35.688  1488  1488 D Launcher.HomeView: onPause
03-17 08:36:35.688  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-17 08:36:35.688  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
,03-17 08:36:35.688  1488  1488 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-17 08:36:35.688  1019  3946 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
,03-17 08:36:35.688  1019  3946 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,03-17 08:36:35.698  1019  3946 W ActivityManager: userId = 0, bbcId = -10000
,03-17 08:36:35.698  1019  3946 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:36:35.698  1019  3946 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,03-17 08:36:35.698  5002  5002 D GalleryCacheReady: Receive : home resume
,03-17 08:36:35.698  1019  1044 W ActivityManager: userId = 0, bbcId = -10000
,03-17 08:36:35.698  1019  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:36:35.698  1019  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,03-17 08:36:35.708  1019  1044 W ActivityManager: userId = 0, bbcId = -10000,
03-17 08:36:35.708  1019  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:36:35.708  1019  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,03-17 08:36:35.708  1019  1044 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:36:35.708  2531  2531 D Recents_RecreateReceiver: onReceive by home
,03-17 08:36:35.708  1019  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:36:35.708  1019  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,03-17 08:36:35.718  1019  3947 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:36:35.718  1019  3947 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:36:35.718  1019  3947 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,03-17 08:36:35.728  5921  5921 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,03-17 08:36:35.728  4735  4735 D Mms/UIEventReceiver: ui event
,03-17 08:36:35.728   259   259 I SurfaceFlinger: id=14 createSurf (540x960),1 flag=4, Mauncher
,03-17 08:36:35.738  1019  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-17 08:36:35.738  1019  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-17 08:36:35.738  1019  1031 D InputDispatcher: Focus entered window: 1488
,03-17 08:36:35.738  1488  1488 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-17 08:36:35.748  1019  1502 D PersonaManager: isKioskContainerExistOnDevice
,03-17 08:36:35.748  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 08:36:35.748  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 08:36:35.748  1488  1488 D Launcher.HomeView: onStop
03-17 08:36:35.748  1488  1488 V ActivityThread: updateVisibility : ActivityRecord{d09a385 token=android.os.BinderProxy@24e83986 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,03-17 08:36:35.748  1019  3947 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:36:35.748  1019  3947 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:36:35.748  1019  3947 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,03-17 08:36:35.758  1019  3947 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:36:35.758  1019  3947 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:36:35.758  1019  3947 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:36:35.758  1019  3947 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:36:35.768  6019  6019 E Zygote  : MountEmulatedStorage(),
03-17 08:36:35.768  6019  6019 E Zygote  : v2
,03-17 08:36:35.768  6019  6019 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 08:36:35.768  1019  3947 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=6019 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
03-17 08:36:35.768  6019  6019 I libpersona: KNOX_SDCARD checking this for 10135
03-17 08:36:35.768  6019  6019 I libpersona: KNOX_SDCARD not a persona
,03-17 08:36:35.778  6019  6019 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 08:36:35.778  1019  3947 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:36:35.778  1019  3947 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:36:35.778  1019  3947 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
03-17 08:36:35.778  6019  6019 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 08:36:35.778  1019  3947 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:36:35.778  1019  3947 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:36:35.778  1019  3947 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1488, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight,
03-17 08:36:35.778  1019  3947 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,03-17 08:36:35.788  1019  1431 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-17 08:36:35.798  6019  6019 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:36:35.798  6019  6019 D ActivityThread: Added TimaKeyStore provider
,03-17 08:36:35.798  1488  1488 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@24e83986 time:85099
,03-17 08:36:35.798  1019  6033 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 08:36:35.808  1177  1177 I StatusBar: Icon Only
03-17 08:36:35.808  1177  1177 D PanelView: There is/are notification(s) 
03-17 08:36:35.808  5962  5962 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-17 08:36:35.808  1864  1864 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,03-17 08:36:35.818  1019  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3edf2288 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t21} time:85110
03-17 08:36:35.818  1019  1049 W ActivityManager: mDVFSHelper.release()
,03-17 08:36:35.818  1019  1043 W libprocessgroup: failed to open /acct/uid_10035/pid_4986/cgroup.procs: No such file or directory
,03-17 08:36:35.818  6019  6019 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-17 08:36:35.818  6019  6019 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.,
03-17 08:36:35.818  6019  6019 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-17 08:36:35.818  6019  6019 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-17 08:36:35.818  6019  6019 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 08:36:35.848  1019  3730 I splitIntent: Queue : backgroundsplit_1 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,03-17 08:36:35.858  1019  3730 I ActivityManager: Killing 4461:com.google.android.music:main/u0a108 (adj 15): empty #31
,03-17 08:36:35.858  1019  1044 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:36:35.858  1019  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:36:35.858  1019  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,03-17 08:36:35.858  5921  5921 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,03-17 08:36:35.898  6013  6013 D AndroidRuntime: 
03-17 08:36:35.898  6013  6013 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,03-17 08:36:35.898  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,03-17 08:36:35.898  6013  6013 D AndroidRuntime: CheckJNI is OFF,
03-17 08:36:35.898  6013  6013 D AndroidRuntime: readGMSProperty: start
03-17 08:36:35.898  6013  6013 D AndroidRuntime: readGMSProperty: already setted!!
03-17 08:36:35.898  6013  6013 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-17 08:36:35.898  6013  6013 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-17 08:36:35.898  6013  6013 D AndroidRuntime: readGMSProperty: end
03-17 08:36:35.898  6013  6013 D AndroidRuntime: addProductProperty: start
,03-17 08:36:35.968  1019  1043 W libprocessgroup: failed to open /acct/uid_10108/pid_4461/cgroup.procs: No such file or directory
,03-17 08:36:36.068  6013  6013 E AffinityControl: AffinityControl: registerfunction enter,
,03-17 08:36:36.088  6013  6013 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-17 08:36:36.098  1019  1506 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
03-17 08:36:36.098  1019  1506 D PackageManager: START PACKAGE DELETE: observer{390347480}
03-17 08:36:36.098  1019  1506 D PackageManager: pkg{<packageName>}
03-17 08:36:36.098  1019  1506 D PackageManager: user{0}
03-17 08:36:36.098  1019  1506 D PackageManager: caller{2000}
03-17 08:36:36.098  1019  1506 D PackageManager: flags{2}
03-17 08:36:36.098  1019  1506 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
03-17 08:36:36.098  1019  1057 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
03-17 08:36:36.098  1019  1506 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
03-17 08:36:36.098  1019  1506 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-17 08:36:36.098  1019  1506 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-17 08:36:36.098  1019  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
03-17 08:36:36.098  1019  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
03-17 08:36:36.098  1019  1057 D ApplicationPolicy: getApplicationUninstallationEnabled
03-17 08:36:36.098  1019  1057 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,03-17 08:36:36.098  1019  1057 D PackageManager: !@killApplicatoin: 10167, uninstall pkg,
,03-17 08:36:36.108   290   290 E SMD     : DCD OFF
,03-17 08:36:36.108  1019  1044 I ActivityManager: Force stopping com.test.thalitest appid=10167 user=-1: uninstall pkg
,03-17 08:36:36.108  1019  1044 I ActivityManager: Killing 5962:com.test.thalitest/u0a167 (adj 13): stop com.test.thalitest cause uninstall pkg
,03-17 08:36:36.178  1019  1057 W PackageSettings: Skipping PackageSetting{37c64885 com.example.hello/10346} due to missing metadata
,03-17 08:36:36.198  1019  3730 W ActivityManager: Spurious death for ProcessRecord{d0b0e31 5962:com.test.thalitest/u0a167}, curProc for 5962: null
,03-17 08:36:36.208  1019  1057 I ActivityManager: Force stopping com.test.thalitest appid=10167 user=0: pkg removed
,03-17 08:36:36.218  1019  1057 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,03-17 08:36:36.248  4050  4050 I art     : Explicit concurrent mark sweep GC freed 2537(152KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 770us total 23.930ms
,03-17 08:36:36.258  1019  1100 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-17 08:36:36.268  1864  1864 E SamsungIME: mOCRHelper is null
,03-17 08:36:36.268  1798  2080 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-17 08:36:36.278  5284  5284 I art     : Explicit concurrent mark sweep GC freed 11566(829KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/8MB, paused 807us total 50.080ms
,03-17 08:36:36.298  1019  1128 V NetworkStats: removeUidsLocked() for UIDs [10167]
03-17 08:36:36.298  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
03-17 08:36:36.298  1019  1128 V NetworkStats: performPollLocked(flags=0x3)
,03-17 08:36:36.298  1019  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
03-17 08:36:36.298  1019  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,03-17 08:36:36.308  1019  1128 V NetworkStats: performPollLocked() took 7ms
03-17 08:36:36.308  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 08:36:36.318  1019  1043 D EnterpriseDeviceManagerService: Package has changed for user 0
,03-17 08:36:36.318  1019  1043 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,03-17 08:36:36.318  1019  1043 W TextServicesManagerService: no available spell checker services found
,03-17 08:36:36.338  3659  3659 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Mar 17 08:36:36 GMT+01:00 2016
,03-17 08:36:36.338  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 08:36:36.338  1019  3947 W ActivityManager: userId = 0, bbcId = -10000
,03-17 08:36:36.338  1019  3947 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:36:36.338  1019  3947 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-17 08:36:36.348  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
03-17 08:36:36.348  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 08:36:36.348  3659  3659 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,03-17 08:36:36.348  1019  1818 I splitIntent: intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
03-17 08:36:36.348  1019  1818 I splitIntent: base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
03-17 08:36:36.348  1019  1818 I splitIntent: other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
03-17 08:36:36.348  1019  1818 I splitIntent: arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,03-17 08:36:36.358  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 08:36:36.358  1019  1818 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:36:36.358  1019  1818 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:36:36.358  1019  1818 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:36:36.358  1019  1818 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:36:36.358  3659  3659 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,03-17 08:36:36.368  6047  6047 E Zygote  : MountEmulatedStorage(),
,03-17 08:36:36.368  6047  6047 I libpersona: KNOX_SDCARD checking this for 10090
03-17 08:36:36.368  6047  6047 E Zygote  : v2
03-17 08:36:36.368  6047  6047 I libpersona: KNOX_SDCARD not a persona
03-17 08:36:36.368  6047  6047 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 08:36:36.378  6047  6047 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 08:36:36.378  6047  6047 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 08:36:36.388  1019  1818 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6047 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
03-17 08:36:36.388  3659  3659 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
03-17 08:36:36.398  1019  1724 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
03-17 08:36:36.398  1019  1724 D SecContentProvider2: mCursor = null
03-17 08:36:36.398  3659  3659 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
03-17 08:36:36.398  6047  6047 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 08:36:36.408  6047  6047 D ActivityThread: Added TimaKeyStore provider
03-17 08:36:36.408  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 08:36:36.418  3659  6046 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
03-17 08:36:36.418  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 08:36:36.418  3659  6046 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,03-17 08:36:36.428  3659  6046 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,03-17 08:36:36.428  3659  6046 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
03-17 08:36:36.428  1019  1019 I art     : Explicit concurrent mark sweep GC freed 53850(3MB) AllocSpace objects, 21(340KB) LOS objects, 33% free, 24MB/36MB, paused 2.932ms total 215.303ms
03-17 08:36:36.438  1019  1057 I art     : WaitForGcToComplete blocked for 205.033ms for cause Explicit
,03-17 08:36:36.438  1455  1455 D RegisteredServicesCache: empty dynamic service
,03-17 08:36:36.488  6047  6047 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,03-17 08:36:36.498  6047  6047 D elm:15121: ELMEngine.ELMEngine( context ).
,03-17 08:36:36.498  6047  6047 D elm:15121: MDMBridge.setEnterpriseBridge()
,03-17 08:36:36.498  1019  1331 W ActivityManager: userId = 0, bbcId = -10000
,03-17 08:36:36.498  1019  1331 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:36:36.498  1019  1331 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,03-17 08:36:36.508  6047  6047 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,03-17 08:36:36.508  6047  6047 D elm:15121: ElmAgentService : onCreate()
,03-17 08:36:36.508  6047  6062 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,03-17 08:36:36.528  6047  6062 D elm:15121: MainReceiver.listeningToPackageRemoved(),
03-17 08:36:36.528  6047  6062 D elm:15121: MDMBridge.getInstance()
03-17 08:36:36.528  6047  6062 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,03-17 08:36:36.528  6047  6062 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,03-17 08:36:36.548  3659  6046 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,03-17 08:36:36.548  6047  6047 D elm:15121: ElmAgentService : onDestroy().
,03-17 08:36:36.558  3659  6046 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,03-17 08:36:36.568  3659  6046 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,03-17 08:36:36.568  3659  3659 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,03-17 08:36:36.578  1019  1043 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,03-17 08:36:36.578  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 08:36:36.588  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 08:36:36.588  1019  1019 D RCPManagerService: PackageReceiver onReceive()
,03-17 08:36:36.588  1019  1019 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,03-17 08:36:36.588  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 08:36:36.598  1019  1019 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,03-17 08:36:36.598  1019  1043 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 08:36:36.598  1019  1043 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 08:36:36.598  1019  1043 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 08:36:36.598  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 08:36:36.628  1019  1057 I art     : Explicit concurrent mark sweep GC freed 11806(561KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/36MB, paused 3.629ms total 198.951ms
,03-17 08:36:36.638  1019  1724 I art     : WaitForGcToComplete blocked for 218.104ms for cause Explicit
,03-17 08:36:36.678  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 08:36:36.678  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 08:36:36.678  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 08:36:36.678  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-17 08:36:36.688  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 08:36:36.688  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 08:36:36.688  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-17 08:36:36.688  1019  1057 D PackageManager: delete codoeFile: 
,03-17 08:36:36.688  1019  1057 D AASAuninstall: userId = 0, info.removedAppID = 10167, info.uid = 10167, packageName = com.test.thalitest
,03-17 08:36:36.688  1019  1057 I AASA_removePackage: UID=10167 Target=com.test.thalitest
,03-17 08:36:36.688  1019  1057 D PackageManager: result of delete: 1{390347480}
,03-17 08:36:36.698  6013  6013 D AndroidRuntime: Shutting down VM
03-17 08:36:36.698  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 08:36:36.698  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-17 08:36:36.698  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 08:36:36.698  1019  1043 D UsbSettingsManager: clearDefaults: com.test.thalitest
,03-17 08:36:36.698  1019  1057 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
03-17 08:36:36.698  1019  1057 D PackageManager: userId{-1}
03-17 08:36:36.698  1019  1057 D PackageManager: andCode{true}
,03-17 08:36:36.708  1019  1043 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,03-17 08:36:36.718  1019  1019 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-17 08:36:36.718  1019  1019 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-17 08:36:36.718  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
03-17 08:36:36.718  1019  1019 V EnterpriseBillingPolicy: uID is 10167
03-17 08:36:36.718  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
03-17 08:36:36.718  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
03-17 08:36:36.718  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-17 08:36:36.718  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-17 08:36:36.718  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-17 08:36:36.718  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-17 08:36:36.718  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-17 08:36:36.728  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,03-17 08:36:36.728  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
03-17 08:36:36.728  1019  1019 V EnterpriseBillingPolicy: uID is 10167
03-17 08:36:36.728  1019  1161 D TaskPersister: removeObsoleteFile: deleting file=22_task.xml
03-17 08:36:36.728  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
03-17 08:36:36.728  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-17 08:36:36.728  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0,
03-17 08:36:36.728  1019  2736 D SSRM:aZ : MSG_TYPE_APP_REMOVED::
03-17 08:36:36.728  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-17 08:36:36.728  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
,03-17 08:36:36.728  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
03-17 08:36:36.728  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-17 08:36:36.738  5665  5665 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,03-17 08:36:36.738  5665  5665 I PCWCLIENTTRACE_PushUtil: sales region : global
03-17 08:36:36.738  5665  5665 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-17 08:36:36.738  5665  5665 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,03-17 08:36:36.748  5784  5784 I SA      : [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,03-17 08:36:36.748  5784  5784 I SA      : [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10167 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,03-17 08:36:36.758  1019  1139 W ActivityManager: userId = 0, bbcId = -10000
,03-17 08:36:36.758  1019  1139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:36:36.758  1019  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,03-17 08:36:36.768  5002  5002 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
,03-17 08:36:36.778  1019  3946 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-17 08:36:36.778  1019  3946 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 08:36:36.778  1019  3946 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 08:36:36.778  1019  3946 D BatteryService: stay LED for fully charged
,03-17 08:36:36.798  1019  1724 I art     : Explicit concurrent mark sweep GC freed 8039(425KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 24MB/36MB, paused 2.766ms total 167.822ms
,03-17 08:36:36.838  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 08:36:36.838  1019  1431 W ActivityManager: userId = 0, bbcId = -10000
,03-17 08:36:36.838  1019  1431 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 08:36:36.838  1019  1431 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,03-17 08:36:36.838  4735  4735 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
,03-17 08:36:36.838  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-17 08:36:36.838  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:36:36.838  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,03-17 08:36:36.848  4735  6066 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
03-17 08:36:36.848  1019  1019 I MotionRecognitionService: Plugged
03-17 08:36:36.848  4735  6066 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
03-17 08:36:36.848  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 08:36:36.848  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 08:36:36.848  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 08:36:36.848  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 08:36:36.848  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 08:36:36.858  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 08:36:36.858  2629  2722 D HeadsetStateMachine: Disconnected process message: 10
,03-17 08:36:36.858  1019  1506 I TactileAssist: enable value -1
,03-17 08:36:36.858  1019  1506 I TactileAssist: internal enable value -1
03-17 08:36:36.858  1019  1506 I TactileAssist: intensity value -1
03-17 08:36:36.858  1019  1506 I TactileAssist: saveAppList value true
,03-17 08:36:36.868  1019  1506 I TactileAssist: List of disabled apps :,
,03-17 08:36:36.868  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 08:36:36.878  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 08:36:36.878  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 08:36:36.878  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 08:36:36.878  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-17 08:36:36.888  5743  5743 D Compatibility: onReceive() it will make start service
,03-17 08:36:36.888  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-17 08:36:36.888  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:36:36.888  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,03-17 08:36:36.888  1019  1818 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:36:36.888  1019  1818 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:36:36.888  1019  1818 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:36:36.888  1019  1818 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:36:36.888  5743  6067 D Compatibility: onHandleIntent()
,03-17 08:36:36.898  5743  6067 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10167, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,03-17 08:36:36.908  5743  6067 D Compatibility: found: 2
,03-17 08:36:36.908  5743  6067 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,03-17 08:36:36.908  1019  1818 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6068 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
03-17 08:36:36.908  5743  6067 D Compatibility: skipping ResolveInfo{2152f5e9 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
03-17 08:36:36.908  5743  6067 D Compatibility: considering ResolveInfo{1275e26e com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
03-17 08:36:36.908  5743  6067 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
03-17 08:36:36.908  6013  6013 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,03-17 08:36:36.908  5743  6067 D Compatibility: enabling receiver ResolveInfo{16431d0f com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,03-17 08:36:36.918  6068  6068 E Zygote  : MountEmulatedStorage()
03-17 08:36:36.918  6068  6068 I libpersona: KNOX_SDCARD checking this for 10055
03-17 08:36:36.918  6068  6068 E Zygote  : v2
03-17 08:36:36.918  6068  6068 I libpersona: KNOX_SDCARD not a persona
03-17 08:36:36.918  6068  6068 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 08:36:36.918  6068  6068 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 08:36:36.918  5743  6067 D Compatibility: enabling receiver ResolveInfo{3608219c com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,03-17 08:36:36.918  6068  6068 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 08:36:36.928  5743  6067 D Compatibility: enabling receiver ResolveInfo{165c07a5 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,03-17 08:36:36.938  5743  6067 D Compatibility: enabling receiver ResolveInfo{1e21b77a com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,03-17 08:36:36.938  5743  6067 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,03-17 08:36:36.948  6068  6068 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:36:36.948  6068  6068 D ActivityThread: Added TimaKeyStore provider
,03-17 08:36:36.978  6068  6068 D UserAnalysis.PlaceProvider: PlaceProvider onCreate(),
,03-17 08:36:37.008  6068  6068 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,03-17 08:36:37.008  6068  6068 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
03-17 08:36:37.008  6068  6068 D UserAnalysis: Create SecureDbHelper
,03-17 08:36:37.018  6068  6068 D IntelligenceServiceApplication: onCreate()
,03-17 08:36:37.018  6068  6068 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,03-17 08:36:37.018  6068  6068 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
,03-17 08:36:37.018  6068  6068 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
03-17 08:36:37.018  6068  6068 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 08:36:37.018  6068  6068 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 08:36:37.018  6068  6068 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 08:36:37.018  6068  6068 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 08:36:37.018  6068  6068 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 08:36:37.018  6068  6068 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 08:36:37.018  6068  6068 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 08:36:37.018  6068  6068 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 08:36:37.018  6068  6068 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 08:36:37.018  6068  6068 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 08:36:37.018  6068  6068 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 08:36:37.018  6068  6068 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 08:36:37.018  6068  6068 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 08:36:37.018  6068  6068 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-17 08:36:37.018  6068  6068 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:69)
03-17 08:36:37.018  6068  6068 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.IntelligenceServiceApplication$1.run(IntelligenceServiceApplication.java:46)
03-17 08:36:37.018  6068  6068 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-17 08:36:37.018  6068  6068 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-17 08:36:37.018  6068  6068 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-17 08:36:37.018  6068  6068 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 08:36:37.018  6068  6068 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 08:36:37.018  6068  6068 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 08:36:37.018  6068  6068 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 08:36:37.018  6068  6068 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,03-17 08:36:37.018  6068  6068 E SQLiteOpenHelper: Couldn't open privacy for writing (will try read-only):
03-17 08:36:37.018  6068  6068 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 08:36:37.018  6068  6068 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 08:36:37.018  6068  6068 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 08:36:37.018  6068  6068 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 08:36:37.018  6068  6068 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 08:36:37.018  6068  6068 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 08:36:37.018  6068  6068 E SQLiteOpenHelper: 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 08:36:37.018  6068  6068 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 08:36:37.018  6068  6068 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 08:36:37.018  6068  6068 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 08:36:37.018  6068  6068 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 08:36:37.018  6068  6068 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 08:36:37.018  6068  6068 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 08:36:37.018  6068  6068 E SQLiteOpenHelper: ,	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-17 08:36:37.018  6068  6068 E SQLiteOpenHelper: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:69)
03-17 08:36:37.018  6068  6068 E SQLiteOpenHelper: 	at com.samsung.android.intelligenceservice.IntelligenceServiceApplication$1.run(IntelligenceServiceApplication.java:46)
03-17 08:36:37.018  6068  6068 E SQLiteOpenHelper: 	at android.os.Handler.handleCallback(Handler.java:739)
03-17 08:36:37.018  6068  6068 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-17 08:36:37.018  6068  6068 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
03-17 08:36:37.018  6068  6068 E SQLiteOpenHelper: 	,at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 08:36:37.018  6068  6068 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 08:36:37.018  6068  6068 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 08:36:37.018  6068  6068 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 08:36:37.018  6068  6068 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 08:36:37.018  6068  6068 W SQLiteOpenHelper: Opened privacy in read-only mode
03-17 08:36:37.018  6068  6068 D IntelligenceServiceApplication: no applications having user consent for prediction
03-17 08:36:37.028  6068  6068 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,03-17 08:36:37.028  5111  5111 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,03-17 08:36:37.028  1019  3767 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:36:37.028  1019  3767 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:36:37.028  1019  3767 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,03-17 08:36:37.038  1019  3946 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:36:37.038  1019  3946 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:36:37.038  1019  3946 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:36:37.038  1019  3946 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:36:37.038  6068  6068 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,03-17 08:36:37.038  6068  6068 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
,03-17 08:36:37.048  5111  6087 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
,03-17 08:36:37.048  6088  6088 E Zygote  : MountEmulatedStorage()
03-17 08:36:37.048  6088  6088 I libpersona: KNOX_SDCARD checking this for 1000
03-17 08:36:37.048  6088  6088 E Zygote  : v2
03-17 08:36:37.048  6088  6088 I libpersona: KNOX_SDCARD not a persona
03-17 08:36:37.048  1019  3946 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6088 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 08:36:37.048  6088  6088 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 08:36:37.058  6068  6068 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.,
03-17 08:36:37.058  6068  6068 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 08:36:37.058  6068  6068 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 08:36:37.058  6068  6068 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 08:36:37.058  6068  6068 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 08:36:37.058  6068  6068 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 08:36:37.058  6068  6068 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 08:36:37.058  6068  6068 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 08:36:37.058  6068  6068 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 08:36:37.058  6068  6068 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 08:36:37.058  6068  6068 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 08:36:37.058  6068  6068 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 08:36:37.058  6068  6068 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 08:36:37.058  6068  6068 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 08:36:37.058  6068  6068 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 08:36:37.058  6068  6068 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:204)
03-17 08:36:37.058  6068  6068 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:78)
03-17 08:36:37.058  6068  6068 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-17 08:36:37.058  6068  6068 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-17 08:36:37.058  6068  6068 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-17 08:36:37.058  6068  6068 E SQLiteDatabase: 	,at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 08:36:37.058  6068  6068 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 08:36:37.058  6068  6068 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 08:36:37.058  6068  6068 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 08:36:37.058  6068  6068 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 08:36:37.058  6068  6068 D AndroidRuntime: Shutting down VM
03-17 08:36:37.058  6068  6068 E AndroidRuntime: FATAL EXCEPTION: main
03-17 08:36:37.058  6068  6068 E AndroidRuntime: Process: com.samsung.android.intelligenceservice, PID: 6068
03-17 08:36:37.058  6068  6068 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 08:36:37.058  6068  6068 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 08:36:37.058  6068  6068 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 08:36:37.058  6068  6068 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 08:36:37.058  6068  6068 E AndroidRuntime: 	,at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 08:36:37.058  6068  6068 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 08:36:37.058  6068  6068 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 08:36:37.058  6068  6068 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 08:36:37.058  6068  6068 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 08:36:37.058  6068  6068 E AndroidRuntime: ,	,at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 08:36:37.058  6068  6068 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 08:36:37.058  6068  6068 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 08:36:37.058  6068  6068 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 08:36:37.058  6068  6068 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 08:36:37.058  6068  6068 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:204)
03-17 08:36:37.058  6068  6068 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:78)
03-17 08:36:37.058  6068  6068 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
03-17 08:36:37.058  6068  6068 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-17 08:36:37.058  6068  6068 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
03-17 08:36:37.058  6068  6068 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 08:36:37.058  6068  6068 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 08:36:37.058  6068  6068 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 08:36:37.058  6068  6068 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 08:36:37.058  6068  6068 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 08:36:37.058  1019  1431 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.intelligenceservice
03-17 08:36:37.058  6088  6088 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 08:36:37.058  6088  6088 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 08:36:37.068  6068  6068 I Process : Sending signal. PID: 6068 SIG: 9
,03-17 08:36:37.078  5111  6087 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
03-17 08:36:37.078  5111  6087 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 08:36:37.078  5111  6087 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 08:36:37.078  5111  6087 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 08:36:37.078  5111  6087 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 08:36:37.078  5111  6087 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 08:36:37.078  5111  6087 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 08:36:37.078  5111  6087 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 08:36:37.078  5111  6087 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 08:36:37.078  5111  6087 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 08:36:37.078  5111  6087 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 08:36:37.078  5111  6087 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 08:36:37.078  5111  6087 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 08:36:37.078  5111  6087 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 08:36:37.078  5111  6087 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 08:36:37.078  5111  6087 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
03-17 08:36:37.078  5111  6087 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
03-17 08:36:37.078  5111  6087 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 08:36:37.078  5111  6087 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 08:36:37.078  5111  6087 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-17 08:36:37.078  5111  6087 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-17 08:36:37.078  5111  6087 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 08:36:37.078  5111  6087 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 08:36:37.078  5111  6087 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 08:36:37.078  5111  6087 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 08:36:37.078  5111  6087 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 08:36:37.078  5111  6087 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 08:36:37.078  5111  6087 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 08:36:37.078  5111  6087 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 08:36:37.078  5111  6087 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 08:36:37.078  5111  6087 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDataba,se.java:699)
03-17 08:36:37.078  5111  6087 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 08:36:37.078  5111  6087 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 08:36:37.078  5111  6087 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 08:36:37.078  5111  6087 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 08:36:37.078  5111  6087 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
03-17 08:36:37.078  5111  6087 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
03-17 08:36:37.078  5111  6087 W System.err: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 08:36:37.078  5111  6087 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 08:36:37.078  5111  6087 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-17 08:36:37.078  5111  6087 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
