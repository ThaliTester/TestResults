#### Test 62754403d2f0346_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main
,03-17 13:28:54.722   288   288 E SMD     : DCD OFF
03-17 13:28:54.992  6100  6100 D AndroidRuntime: 
03-17 13:28:54.992  6100  6100 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-17 13:28:54.992  6100  6100 D AndroidRuntime: CheckJNI is OFF
03-17 13:28:55.002  6100  6100 D AndroidRuntime: readGMSProperty: start
03-17 13:28:55.002  6100  6100 D AndroidRuntime: readGMSProperty: already setted!!
03-17 13:28:55.002  6100  6100 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-17 13:28:55.002  6100  6100 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-17 13:28:55.002  6100  6100 D AndroidRuntime: readGMSProperty: end
03-17 13:28:55.002  6100  6100 D AndroidRuntime: addProductProperty: start
03-17 13:28:55.132  6100  6100 E AffinityControl: AffinityControl: registerfunction enter
03-17 13:28:55.162  6100  6100 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-17 13:28:55.172  1018  1384 E PersonaManagerService: inState():  stateMachine is null !!
03-17 13:28:55.172  1018  1384 I PersonaManagerService: PersonaId don't exist
03-17 13:28:55.172  1018  1384 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-17 13:28:55.172  1018  1384 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
03-17 13:28:55.192  1018  1384 W ActivityManager: mDVFSHelper.acquire()
03-17 13:28:55.192  1018  1384 D FocusedStackFrame: Set to : 0
03-17 13:28:55.202  1018  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:28:55.202  1018  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:28:55.202  1018  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:28:55.202  1018  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:28:55.202  1018  1048 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-17 13:28:55.202  1018  1048 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-17 13:28:55.212  6112  6112 E Zygote  : MountEmulatedStorage()
03-17 13:28:55.212  6112  6112 E Zygote  : v2
03-17 13:28:55.212  6112  6112 I libpersona: KNOX_SDCARD checking this for 10167
03-17 13:28:55.222  1018  1384 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6112 uid=10167 gids={50167, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-17 13:28:55.222  6112  6112 I libpersona: KNOX_SDCARD not a persona
03-17 13:28:55.222  1018  1384 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-17 13:28:55.222  1018  1384 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 13:28:55.222  1018  1384 D InputDispatcher: Focused application set to: xxxx
03-17 13:28:55.222  1018  1384 D InputDispatcher: Focus left window: 1496
03-17 13:28:55.222  6100  6100 D AndroidRuntime: Shutting down VM
03-17 13:28:55.222  6112  6112 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 13:28:55.222  1018  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-17 13:28:55.222  1018  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-17 13:28:55.222  6112  6112 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 13:28:55.222   257   257 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
03-17 13:28:55.232  6112  6112 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-17 13:28:55.242  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 13:28:55.242  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 13:28:55.252  6112  6112 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:28:55.252  6112  6112 D ActivityThread: Added TimaKeyStore provider
03-17 13:28:55.252  1018  1501 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-17 13:28:55.262  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-17 13:28:55.272  1018  1501 D PersonaManager: isKioskContainerExistOnDevice
03-17 13:28:55.282  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
03-17 13:28:55.302   257  1113 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
03-17 13:28:55.302  1496  1496 V ActivityThread: updateVisibility : ActivityRecord{22006235 token=android.os.BinderProxy@3f63cb95 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-17 13:28:55.302   257   444 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
03-17 13:28:55.302  1496  1496 D Launcher: onTrimMemory. Level: 20
03-17 13:28:55.372  6112  6112 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
03-17 13:28:55.392  6112  6112 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 6042-6043)
03-17 13:28:55.392  6112  6112 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-17 13:28:55.432  6112  6112 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {17d250e3}
03-17 13:28:55.432  6112  6112 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-17 13:28:55.432  6112  6112 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
03-17 13:28:55.442  6100  6100 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,03-17 13:28:55.462  6112  6112 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-17 13:28:55.462  6112  6112 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,03-17 13:28:55.462  6112  6112 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-17 13:28:55.482  6112  6112 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-17 13:28:55.482  6112  6112 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-17 13:28:55.482  6112  6112 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-17 13:28:55.482  6112  6112 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 13:28:55.482  6112  6112 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 13:28:55.482  6112  6112 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 13:28:55.482  6112  6112 I Adreno-EGL: Local Branch: 
03-17 13:28:55.482  6112  6112 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 13:28:55.482  6112  6112 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 13:28:55.482  6112  6112 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 13:28:55.702  6112  6112 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 13:28:55.712  6112  6112 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-17 13:28:55.722  6112  6112 D PhoneWindow: *FMB* installDecor mIsFloating : false
,03-17 13:28:55.722  6112  6112 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-17 13:28:55.722  6112  6112 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-17 13:28:55.732  6112  6112 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 13:28:55.732  6112  6112 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 13:28:55.772  1018  1043 W ActivityManager: Activity pause timeout for ActivityRecord{1ba78ede u0 com.test.thalitest/.MainActivity t23}
,03-17 13:28:55.792  6112  6152 D OpenGLRenderer: Render dirty regions requested: true
,03-17 13:28:55.792  1018  1384 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,03-17 13:28:55.792  1018  1384 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-17 13:28:55.792  1018  1384 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-17 13:28:55.792  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-17 13:28:55.792  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,03-17 13:28:55.802  6112  6139 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-17 13:28:55.802  6112  6112 V ActivityThread: updateVisibility : ActivityRecord{1054ef4b token=android.os.BinderProxy@3b1b16c5 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,03-17 13:28:55.802  6112  6112 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-17 13:28:55.802  6112  6112 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-17 13:28:55.812   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,03-17 13:28:55.822  1018  1512 D InputDispatcher: Focus entered window: 6112
,03-17 13:28:55.822  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,03-17 13:28:55.822  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 13:28:55.832  6112  6112 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-17 13:28:55.832  6112  6152 I OpenGLRenderer: Initialized EGL, version 1.4
,03-17 13:28:55.832  6112  6152 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,03-17 13:28:55.832  6112  6152 D OpenGLRenderer: Enabling debug mode 0
,03-17 13:28:55.882  1018  1739 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-17 13:28:55.892  1172  1172 I StatusBar: Icon Only
,03-17 13:28:55.892  1172  1172 D PanelView: There is/are notification(s) 
,03-17 13:28:55.892  1018  6154 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:28:55.902  6112  6112 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection,
03-17 13:28:55.902  6112  6112 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3b1b16c5 time:206555
,03-17 13:28:55.902  1018  1048 I ActivityManager: Displayed Component not be shown by security: +630ms (total +1m29s773ms)
03-17 13:28:55.902  1018  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1ba78ede u0 com.test.thalitest/.MainActivity t23} time:206558
03-17 13:28:55.902  1018  1048 W ActivityManager: mDVFSHelper.release()
,03-17 13:28:55.912   257  1113 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,03-17 13:28:55.912   257   444 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,03-17 13:28:55.932  1892  1892 I SamsungIME: getCurrentCandidateView
,03-17 13:28:55.962  1892  1892 D SamsungIME: Dismiss ExpandCandiate
,03-17 13:28:55.992  1892  1892 I SamsungIME: getDebugLevel  : 0x4f4c
,03-17 13:28:56.032  1892  1892 I SamsungIME: getDebugLevel  : 0x4f4c
,03-17 13:28:56.052  1892  1892 I SamsungIME: KeybaordView init() : load resources
,03-17 13:28:56.072  1892  1892 I SamsungIME: getCurrentKeyboard
,03-17 13:28:56.072  1892  1892 I SamsungIME: getTextKeyboard
,03-17 13:28:56.102  1892  1892 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-17 13:28:56.152  6112  6112 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6112
,03-17 13:28:56.172  1018  1739 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:28:56.182  1018  1739 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:28:56.182  1018  1739 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:28:56.182  1018  1739 D BatteryService: stay LED for fully charged
03-17 13:28:56.182  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:28:56.182  1018  1018 I MotionRecognitionService: Plugged
,03-17 13:28:56.182  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:28:56.182  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 13:28:56.182  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:28:56.192  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 13:28:56.192  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:28:56.202  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:28:56.202  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:28:56.212  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:28:56.212  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:28:56.212  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:28:56.212  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-17 13:28:56.212  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:28:56.272  6112  6112 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-17 13:28:56.472  6112  6157 D jxcore_app_log: JniHelper::setJavaVM(0xb7085448), pthread_self() = -1218541400
,03-17 13:28:56.482  6112  6157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-17 13:28:56.482  6112  6157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-17 13:28:56.482  6112  6157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-17 13:28:56.482  6112  6157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-17 13:28:56.482  6112  6157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,03-17 13:28:56.482  6112  6157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cf1f058 added. We now have 1 listener(s)
,03-17 13:28:56.482  6112  6157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,03-17 13:28:56.482  6112  6157 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:EC:A9:50:75:41"}
,03-17 13:28:56.482  6112  6157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"08:EC:A9:50:75:41"}
03-17 13:28:56.482  6112  6157 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-17 13:28:56.482  6112  6157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-17 13:28:56.492  6112  6157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-17 13:28:56.492  6112  6157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-17 13:28:56.492  6112  6157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-17 13:28:56.492  6112  6157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
03-17 13:28:56.492  6112  6157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-17 13:28:56.492  6112  6157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-17 13:28:56.492  6112  6157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-17 13:28:56.492  6112  6157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-17 13:28:56.492  6112  6157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-17 13:28:56.492  6112  6157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,03-17 13:28:56.492  6112  6157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@158bb617 added. We now have 1 listener(s)
,03-17 13:28:56.492  6112  6157 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-17 13:28:56.502  6112  6157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-17 13:28:56.502  6112  6157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-17 13:28:56.502  6112  6157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-17 13:28:56.502  6112  6157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-17 13:28:56.502  6112  6157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-17 13:28:56.502  6112  6157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-17 13:28:56.502  6112  6157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
,03-17 13:28:56.512  6112  6157 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-17 13:28:56.512  6112  6157 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-17 13:28:56.512  6112  6157 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-17 13:28:56.512  6112  6157 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-17 13:28:56.512  6112  6157 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-17 13:28:56.512  6112  6157 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-17 13:28:56.512  6112  6157 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-17 13:28:56.512  6112  6157 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-17 13:28:56.512  6112  6157 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-17 13:28:56.512  6112  6157 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-17 13:28:56.512  6112  6112 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 13:28:56.522  6112  6112 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 13:28:56.552  6112  6112 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-17 13:28:57.042  6112  6164 W jxcore-log: Initializing JXcore engine
03-17 13:28:57.042  6112  6164 W jxcore-log: JXcore engine is ready
,03-17 13:28:57.092  1839  1839 E audit   : type=1400 msg=audit(1458217737.092:205): avc:  denied  { ioctl } for  pid=6164 comm="Thread-1060" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-17 13:28:57.092  1839  1839 E audit   :  SEPF_SM-A300FU_5.0.2_0027
03-17 13:28:57.092  1839  1839 E audit   : type=1300 msg=audit(1458217737.092:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=9d4d48f8 items=0 ppid=306 ppcomm=main pid=6164 auid=4294967295 uid=10167 gid=10167 euid=10167 suid=10167 fsuid=10167 egid=10167 sgid=10167 fsgid=10167 ses=4294967295 tty=(none) comm="Thread-1060" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-17 13:28:57.092  1839  1839 E audit   : type=1320 msg=audit(1458217737.092:205): 
,03-17 13:28:57.102  6112  6164 W jxcore-log: Starting JXcore engine
,03-17 13:28:57.202  6112  6164 W jxcore-log: Platform android
03-17 13:28:57.202  6112  6164 W jxcore-log: 
03-17 13:28:57.202  6112  6164 W jxcore-log: Process ARCH arm
03-17 13:28:57.202  6112  6164 W jxcore-log: 
,03-17 13:28:57.412  6112  6164 I jxcore-log: JXcore Cordova bridge is ready!
03-17 13:28:57.412  6112  6164 I jxcore-log: 
,03-17 13:28:57.412  6112  6164 W jxcore-log: JXcore engine is started
,03-17 13:28:57.422  6112  6157 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-17 13:28:57.432  6112  6164 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-17 13:28:57.432  6112  6164 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-17 13:28:57.442  6112  6112 I chromium: [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,03-17 13:28:57.442  1018  1739 D FocusedStackFrame: Set to : 0
,03-17 13:28:57.442  1018  1739 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,03-17 13:28:57.442  1018  1739 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,03-17 13:28:57.442  1018  1739 D InputDispatcher: Focused application set to: xxxx
,03-17 13:28:57.452  1018  1739 D InputDispatcher: Focus left window: 6112
,03-17 13:28:57.452  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,03-17 13:28:57.452  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 13:28:57.452  1018  1739 I ActivityManager: Killing 5195:com.google.android.gm/u0a99 (adj 15): empty #31
,03-17 13:28:57.462  6112  6157 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 17ms. Plugin should use CordovaInterface.getThreadPool().
,03-17 13:28:57.482   257   444 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
,03-17 13:28:57.482   257  1113 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,03-17 13:28:57.492  1018  1384 W ActivityManager: mDVFSHelper.acquire()
,03-17 13:28:57.502  1018  1384 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,03-17 13:28:57.502  6112  6112 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@1e419bed that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 13:28:57.502  6112  6112 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@1e419bed that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 13:28:57.502  6112  6112 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-17 13:28:57.502  6112  6112 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-17 13:28:57.502  6112  6112 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-17 13:28:57.502  6112  6112 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-17 13:28:57.502  6112  6112 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-17 13:28:57.502  6112  6112 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.initialize(BluetoothManager.java:275)
03-17 13:28:57.502  6112  6112 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.bind(BluetoothManager.java:103)
03-17 13:28:57.502  6112  6112 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:75)
03-17 13:28:57.502  6112  6112 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-17 13:28:57.502  6112  6112 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-17 13:28:57.502  6112  6112 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-17 13:28:57.502  6112  6112 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-17 13:28:57.502  6112  6112 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-17 13:28:57.502  6112  6112 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-17 13:28:57.502  6112  6112 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-17 13:28:57.502  6112  6112 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-17 13:28:57.502  6112  6112 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-17 13:28:57.502  6112  6112 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-17 13:28:57.502  6112  6112 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 13:28:57.502  6112  6112 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-17 13:28:57.502  6112  6112 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 13:28:57.502  6112  6112 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@2ac1ba04 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 13:28:57.502  6112  6112 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@2ac1ba04 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 13:28:57.502  6112  6112 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-17 13:28:57.502  6112  6112 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-17 13:28:57.502  6112  6112 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-17 13:28:57.502  6112  6112 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-17 13:28:57.502  6112  6112 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-17 13:28:57.502  6112  6112 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:503)
03-17 13:28:57.502  6112  6112 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:67)
03-17 13:28:57.502  6112  6112 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-17 13:28:57.502  6112  6112 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-17 13:28:57.502  6112  6112 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-17 13:28:57.502  6112  6112 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-17 13:28:57.502  6112  6112 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-17 13:28:57.502  6112  6112 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-17 13:28:57.502  6112  6112 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-17 13:28:57.502  6112  6112 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-17 13:28:57.502  6112  6112 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-17 13:28:57.502  6112  6112 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-17 13:28:57.502  6112  6112 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 13:28:57.502  6112  6112 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-17 13:28:57.502  6112  6112 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 13:28:57.522  1496  1496 D Launcher: onRestart, Launcher: 821365854
,03-17 13:28:57.522  1496  1496 D Launcher: onStart, Launcher: 821365854
,03-17 13:28:57.522  1496  1496 D Launcher.HomeView: onStart
,03-17 13:28:57.522  1496  1496 D Launcher: onResume, Launcher: 821365854
,03-17 13:28:57.522  1018  1031 D SettingsProvider: name = kids_home_mode
,03-17 13:28:57.522  1018  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 13:28:57.522  1018  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 13:28:57.522  1018  1031 D SettingsProvider: selectionArgs: false
03-17 13:28:57.522  1018  1031 D SettingsProvider: selectionArgs: 10006
,03-17 13:28:57.522  1018  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 13:28:57.522  1018  1031 D SettingsProvider: ret = -1
03-17 13:28:57.522  1496  1496 D Launcher.HomeView: onResume
03-17 13:28:57.532  1496  1496 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-17 13:28:57.532  1496  1496 D MenuAppsGridFragment: onResume
03-17 13:28:57.532  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:28:57.532  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:28:57.532  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,03-17 13:28:57.542  1018  1384 D ActivityManager: handle home activity for 0
03-17 13:28:57.542  1018  1384 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
03-17 13:28:57.542  1018  1384 D KnoxTimeoutHandler: post home show event for user 0
03-17 13:28:57.542  1018  1384 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-17 13:28:57.542  1018  1384 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-17 13:28:57.542  1018  1384 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-17 13:28:57.542  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
03-17 13:28:57.542  1018  1018 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
03-17 13:28:57.542  1018  1018 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
03-17 13:28:57.542  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-17 13:28:57.542  1496  1496 D Launcher.HomeView: onPause
,03-17 13:28:57.542  1018  1512 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
03-17 13:28:57.542  1018  1512 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,03-17 13:28:57.542  1496  1496 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-17 13:28:57.542  1018  1512 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:28:57.542  1018  1512 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:28:57.542  1018  1512 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,03-17 13:28:57.542  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:28:57.542  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 13:28:57.542  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,03-17 13:28:57.552  4998  4998 D GalleryCacheReady: Receive : home resume
03-17 13:28:57.552  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:28:57.552  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:28:57.552  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
03-17 13:28:57.552  2538  2538 D Recents_RecreateReceiver: onReceive by home
03-17 13:28:57.552  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:28:57.552  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:28:57.552  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,03-17 13:28:57.562  1018  1512 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:28:57.562  1018  1512 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 13:28:57.562  1018  1512 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,03-17 13:28:57.562  5603  5603 D Mms/UIEventReceiver: ui event
,03-17 13:28:57.562  5978  5978 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,03-17 13:28:57.572   257   257 I SurfaceFlinger: id=14 createSurf (540x960),1 flag=4, Mauncher
,03-17 13:28:57.572  1018  1512 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:28:57.572  1018  1512 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:28:57.572  1018  1512 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,03-17 13:28:57.572  1018  1512 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:28:57.572  1018  1512 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:28:57.572  1018  1512 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:28:57.572  1018  1512 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:28:57.572  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-17 13:28:57.572  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-17 13:28:57.582  1018  1737 D InputDispatcher: Focus entered window: 1496
,03-17 13:28:57.582  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,03-17 13:28:57.582  6167  6167 I libpersona: KNOX_SDCARD checking this for 10135
03-17 13:28:57.582  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 13:28:57.582  6167  6167 I libpersona: KNOX_SDCARD not a persona
03-17 13:28:57.582  6167  6167 E Zygote  : MountEmulatedStorage()
03-17 13:28:57.582  6167  6167 E Zygote  : v2
03-17 13:28:57.582  1496  1496 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-17 13:28:57.582  6167  6167 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 13:28:57.582  6167  6167 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:28:57.592  6167  6167 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:28:57.592  1018  1512 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=6167 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
03-17 13:28:57.592  1496  1496 V ActivityThread: updateVisibility : ActivityRecord{22006235 token=android.os.BinderProxy@3f63cb95 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true,
03-17 13:28:57.592  1496  1496 D Launcher.HomeView: onStop
,03-17 13:28:57.592  1018  1030 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-17 13:28:57.592  1018  1512 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:28:57.592  1018  6176 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
03-17 13:28:57.592  1018  1512 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:28:57.592  1018  1512 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,03-17 13:28:57.602  1892  1892 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,03-17 13:28:57.602  1018  1512 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:28:57.602  1018  1512 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:28:57.602  1018  1512 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1496, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
03-17 13:28:57.602  1018  1512 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,03-17 13:28:57.602  6112  6112 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-17 13:28:57.602  1172  1172 I StatusBar: Icon Only
03-17 13:28:57.602  1172  1172 D PanelView: There is/are notification(s) 
,03-17 13:28:57.622  1018  3818 D PersonaManager: isKioskContainerExistOnDevice
,03-17 13:28:57.622  6167  6167 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:28:57.622  6167  6167 D ActivityThread: Added TimaKeyStore provider
,03-17 13:28:57.632  1496  1496 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3f63cb95 time:208285
,03-17 13:28:57.642  1018  1048 W ActivityManager: mDVFSHelper.release()
,03-17 13:28:57.642  6167  6167 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-17 13:28:57.642  6167  6167 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 13:28:57.642  6167  6167 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-17 13:28:57.642  6167  6167 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-17 13:28:57.642  6167  6167 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 13:28:57.642  1018  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{30b80c99 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t21} time:208294
,03-17 13:28:57.672  1018  1384 I splitIntent: Queue : backgroundsplit_1 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,03-17 13:28:57.672  1018  1384 I ActivityManager: Killing 4188:com.sec.spp.push/u0a32 (adj 15): empty #31
,03-17 13:28:57.682  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:28:57.682  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:28:57.682  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,03-17 13:28:57.682  1018  1042 W libprocessgroup: failed to open /acct/uid_10099/pid_5195/cgroup.procs: No such file or directory
,03-17 13:28:57.682  5978  5978 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,03-17 13:28:57.722   288   288 E SMD     : DCD OFF
,03-17 13:28:57.732  1018  2774 D SSRM:n  : SIOP:: AP = 290
,03-17 13:28:57.742  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,03-17 13:28:57.882  1018  1042 W libprocessgroup: failed to open /acct/uid_10032/pid_4188/cgroup.procs: No such file or directory
,03-17 13:28:59.992  1018  1096 V AlarmManager: waitForAlarm result :8
,03-17 13:29:00.732   288   288 E SMD     : DCD OFF
,03-17 13:29:02.692   315   315 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
03-17 13:29:02.692   315   315 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,03-17 13:29:03.732   288   288 E SMD     : DCD OFF
,03-17 13:29:05.252  1018  1056 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,03-17 13:29:05.782  1018  2818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:29:06.242  1018  1384 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-17 13:29:06.242  1018  1384 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
03-17 13:29:06.242  1018  1384 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
03-17 13:29:06.242  1018  1384 D BatteryService: stay LED for fully charged,
03-17 13:29:06.242  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-17 13:29:06.252  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 13:29:06.252  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
03-17 13:29:06.252  1018  1018 I MotionRecognitionService: Plugged
,03-17 13:29:06.252  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:29:06.252  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-17 13:29:06.252  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:29:06.262  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-17 13:29:06.262  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:29:06.272  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-17 13:29:06.272  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:29:06.272  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:29:06.272  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:29:06.272  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:29:06.732   288   288 E SMD     : DCD OFF,
,03-17 13:29:07.472  1018  1050 I PowerManagerService: [PWL] Off : 140s ago,
,03-17 13:29:07.762  1018  2774 D SSRM:n  : SIOP:: AP = 290
,03-17 13:29:09.732   288   288 E SMD     : DCD OFF
,03-17 13:29:12.692   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 13:29:12.732   288   288 E SMD     : DCD OFF,
,03-17 13:29:13.702   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 13:29:14.692   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 13:29:15.692   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 13:29:15.742   288   288 E SMD     : DCD OFF
,03-17 13:29:16.302  1018  1512 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:29:16.692   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:29:17.552  1018  1329 E Watchdog: !@Sync 7
,03-17 13:29:17.692   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,03-17 13:29:17.772  1018  2774 D SSRM:n  : SIOP:: AP = 290
,03-17 13:29:18.732   288   288 E SMD     : DCD OFF
,03-17 13:29:21.742   288   288 E SMD     : DCD OFF
,03-17 13:29:22.692   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 13:29:23.702   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:29:24.692   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:29:24.742   288   288 E SMD     : DCD OFF
,03-17 13:29:25.702   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 13:29:25.782  1018  2818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-17 13:29:26.362  1018  3818 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:29:26.702   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:29:27.702   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,03-17 13:29:27.742   288   288 E SMD     : DCD OFF
,03-17 13:29:27.812  1018  2774 D SSRM:n  : SIOP:: AP = 280
,03-17 13:29:30.742   288   288 E SMD     : DCD OFF
,03-17 13:29:33.752   288   288 E SMD     : DCD OFF
,03-17 13:29:36.422  1018  1305 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:29:36.422  1018  1305 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:29:36.422  1018  1305 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:29:36.422  1018  1305 D BatteryService: stay LED for fully charged
03-17 13:29:36.422  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:29:36.432  1018  1018 I MotionRecognitionService: Plugged
,03-17 13:29:36.432  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
03-17 13:29:36.432  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-17 13:29:36.432  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
03-17 13:29:36.432  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 13:29:36.432  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:29:36.442  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:29:36.442  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:29:36.452  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:29:36.452  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:29:36.452  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:29:36.452  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-17 13:29:36.452  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:29:36.742   288   288 E SMD     : DCD OFF
,03-17 13:29:37.702   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 13:29:37.832  1018  2774 D SSRM:n  : SIOP:: AP = 270
,03-17 13:29:38.712   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 13:29:39.702   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:29:39.742   288   288 E SMD     : DCD OFF
,03-17 13:29:40.702   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:29:41.702   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:29:42.702   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-17 13:29:42.742   288   288 E SMD     : DCD OFF
,03-17 13:29:45.742   288   288 E SMD     : DCD OFF,
,03-17 13:29:45.772  1018  2818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:29:46.482  1018  1737 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:29:47.482  1018  1050 I PowerManagerService: [PWL] Off : 180s ago
,03-17 13:29:47.542  1018  1329 E Watchdog: !@Sync 8
,03-17 13:29:47.882  1018  2774 D SSRM:n  : SIOP:: AP = 270
,03-17 13:29:48.742   288   288 E SMD     : DCD OFF,
,03-17 13:29:51.752   288   288 E SMD     : DCD OFF
,03-17 13:29:54.762   288   288 E SMD     : DCD OFF
,03-17 13:29:56.542  1018  3817 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:29:57.702   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:29:57.752   288   288 E SMD     : DCD OFF
,03-17 13:29:57.912  1018  2774 D SSRM:n  : SIOP:: AP = 270
,03-17 13:29:58.702   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:29:59.702   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:30:00.702   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:30:00.752   288   288 E SMD     : DCD OFF
,03-17 13:30:01.702   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 13:30:02.702   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,03-17 13:30:03.752   288   288 E SMD     : DCD OFF
,03-17 13:30:04.172  1018  1096 V AlarmManager: waitForAlarm result :4
,03-17 13:30:04.172  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-17 13:30:04.172  1172  1172 D KeyguardUpdateMonitor: handleTimeUpdate
,03-17 13:30:04.172  1172  1172 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-17 13:30:04.172  1172  1172 D SecKeyguardClockView: HomeTimezone(): 1
,03-17 13:30:04.182  1172  1172 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:30:04.182  1172  1172 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
03-17 13:30:04.182  1172  1172 I KeyguardEffectViewController: *** don't update sliding image ***
,03-17 13:30:04.202  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:30:04.202  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:30:04.212  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:30:04.242  1172  1172 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,03-17 13:30:04.252  1172  1172 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:30:04.372  6006  6213 I BooksSync: Starting books sync for 61035162, extras: ade
,03-17 13:30:04.382  6006  6214 I BooksConfig: GmsCore Version = 7.8.99 (2134222-434)
,03-17 13:30:04.392  1018  1541 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:30:04.392  1018  1541 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:30:04.392  1018  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,03-17 13:30:04.412  1018  3843 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:30:04.412  1018  3843 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:30:04.412  1018  3843 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:30:04.422  1719  1729 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-17 13:30:04.422  1719  1729 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-17 13:30:04.422  1719  1729 I GLSUser : [GLSUser] Extracting token using key: Auth
03-17 13:30:04.422  1719  1729 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-17 13:30:04.422  1719  1729 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 13:30:04.432  1018  1737 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:30:04.432  1018  1737 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:30:04.432  1018  1737 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:30:04.442  1018  3819 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,03-17 13:30:04.442  1018  3819 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,03-17 13:30:04.442  1018  1018 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,03-17 13:30:04.452  1172  1172 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,03-17 13:30:04.452  1172  1172 D PersonaManager: isKioskContainerExistOnDevice
03-17 13:30:04.452  1172  1172 D PersonaManager: isKioskContainerExistOnDevice
03-17 13:30:04.452  1172  1172 I PhoneStatusBar: Icon Only
03-17 13:30:04.452  1172  1172 I StatusBar: Icon Only
03-17 13:30:04.452  1172  1172 D PanelView: There is/are notification(s) 
03-17 13:30:04.452  1172  1172 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-17 13:30:04.452  1172  1172 D PersonaManager: isKioskContainerExistOnDevice
03-17 13:30:04.452  1172  1172 I PhoneStatusBar: Icon Only
03-17 13:30:04.452  1172  1172 I StatusBar: Icon Only
03-17 13:30:04.452  1172  1172 D PanelView: There is/are notification(s) 
03-17 13:30:04.452  1172  1172 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-17 13:30:04.462  1018  3819 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:30:04.462  1018  3819 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:30:04.462  1018  3819 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,03-17 13:30:04.472  1018  1737 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:30:04.472  1018  1737 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:30:04.472  1018  1737 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:30:04.482  1719  1730 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-17 13:30:04.482  1719  1730 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-17 13:30:04.482  1719  1730 I GLSUser : [GLSUser] Extracting token using key: Auth
03-17 13:30:04.482  1719  1730 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-17 13:30:04.482  1719  1730 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 13:30:04.492  1018  3817 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:30:04.492  1018  3817 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:30:04.492  1018  3817 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:30:04.502  6006  6214 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-17 13:30:04.502  6006  6213 E BooksSync: Soft error
03-17 13:30:04.502  6006  6213 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-17 13:30:04.502  6006  6213 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-17 13:30:04.502  6006  6213 E BooksSync: Sync error
03-17 13:30:04.502  6006  6213 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-17 13:30:04.502  6006  6213 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-17 13:30:04.502  6006  6213 I BooksSync: Finished books sync
,03-17 13:30:04.502  1018  1042 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 274813, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-17 13:30:04.522  1172  1172 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,03-17 13:30:04.552  1018  1501 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,03-17 13:30:04.552  1018  1501 D SecContentProvider2: mCursor = null
,03-17 13:30:05.782  1018  2818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:30:06.612  1018  3817 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:30:06.762   288   288 E SMD     : DCD OFF
,03-17 13:30:07.952  1018  2774 D SSRM:n  : SIOP:: AP = 270
,03-17 13:30:09.762   288   288 E SMD     : DCD OFF
,03-17 13:30:12.762   288   288 E SMD     : DCD OFF
,03-17 13:30:15.772   288   288 E SMD     : DCD OFF
,03-17 13:30:16.672  1018  3819 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:30:17.552  1018  1329 E Watchdog: !@Sync 9
,03-17 13:30:17.972  1018  2774 D SSRM:n  : SIOP:: AP = 290
,03-17 13:30:18.772   288   288 E SMD     : DCD OFF
,03-17 13:30:21.772   288   288 E SMD     : DCD OFF
,03-17 13:30:22.702   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:30:23.712   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:30:24.712   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:30:24.772   288   288 E SMD     : DCD OFF
,03-17 13:30:25.722   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:30:25.782  1018  2818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:30:26.712   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:30:26.722  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:30:27.722   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,03-17 13:30:27.772   288   288 E SMD     : DCD OFF
,03-17 13:30:27.992  1018  2774 D SSRM:n  : SIOP:: AP = 270
,03-17 13:30:30.772   288   288 E SMD     : DCD OFF
,03-17 13:30:32.502  1018  1050 I PowerManagerService: [PWL] Off : 225s ago
,03-17 13:30:33.772   288   288 E SMD     : DCD OFF
,03-17 13:30:34.372  1018  1096 V AlarmManager: waitForAlarm result :4
,03-17 13:30:36.772   288   288 E SMD     : DCD OFF
,03-17 13:30:36.792  1018  1138 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-17 13:30:38.042  1018  2774 D SSRM:n  : SIOP:: AP = 270
,03-17 13:30:39.782   288   288 E SMD     : DCD OFF
,03-17 13:30:42.782   288   288 E SMD     : DCD OFF
,03-17 13:30:44.562  1018  1087 D TimaService: TIMA: TimaService scheduler is intialized. 
,03-17 13:30:44.562  1018  1086 D TimaService: TimaServiceHandler.handleMessage what =1
,03-17 13:30:44.562  1018  1087 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,03-17 13:30:44.562  1018  1087 I TLC_TIMA_PKM_initialize: initializing...
,03-17 13:30:44.562  1018  1087 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
03-17 13:30:44.562  1018  1087 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
,03-17 13:30:44.562  1018  1087 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
03-17 13:30:44.562  1018  1087 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
03-17 13:30:44.562  1018  1087 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
03-17 13:30:44.562  1018  1087 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
,03-17 13:30:44.562  1018  1087 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080,
03-17 13:30:44.562  1018  1087 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
,03-17 13:30:44.572  1018  1087 D QSEECOMAPI: : App is not loaded in QSEE
,03-17 13:30:44.592  1018  1087 D QSEECOMAPI: : Loaded image: APP id = 11
,03-17 13:30:44.612  1018  1087 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded,
,03-17 13:30:44.622  1018  1087 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,03-17 13:30:45.772   288   288 E SMD     : DCD OFF
,03-17 13:30:45.782  1018  2818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:30:46.572  1018  1087 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,03-17 13:30:46.572  1018  1087 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-17 13:30:46.572  1018  1087 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-17 13:30:46.572  1018  1087 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-17 13:30:46.852  1018  3843 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:30:46.852  1018  3843 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:30:46.852  1018  3843 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:30:46.852  1018  3843 D BatteryService: stay LED for fully charged
03-17 13:30:46.852  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:30:46.852  1018  1018 I MotionRecognitionService: Plugged
03-17 13:30:46.852  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:30:46.852  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 13:30:46.852  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate,
03-17 13:30:46.862  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 13:30:46.862  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,03-17 13:30:46.872  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:30:46.872  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:30:46.882  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:30:46.882  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:30:46.882  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:30:46.882  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-17 13:30:46.882  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:30:47.552  1018  1329 E Watchdog: !@Sync 10
,03-17 13:30:48.052  1018  2774 D SSRM:n  : SIOP:: AP = 270
,03-17 13:30:48.782   288   288 E SMD     : DCD OFF
,03-17 13:30:51.772   288   288 E SMD     : DCD OFF
,03-17 13:30:52.722   315   315 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
03-17 13:30:52.722   315   315 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,03-17 13:30:54.792   288   288 E SMD     : DCD OFF
,03-17 13:30:56.912  1018  1501 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:30:56.912  1018  1501 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:30:56.912  1018  1501 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:30:56.912  1018  1501 D BatteryService: stay LED for fully charged
03-17 13:30:56.912  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:30:56.912  1018  1018 I MotionRecognitionService: Plugged
03-17 13:30:56.912  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:30:56.922  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-17 13:30:56.922  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 13:30:56.922  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
03-17 13:30:56.922  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:30:56.932  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-17 13:30:56.932  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:30:56.942  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:30:56.942  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:30:56.942  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:30:56.942  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:30:56.942  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:30:57.792   288   288 E SMD     : DCD OFF
,03-17 13:30:58.072  1018  2774 D SSRM:n  : SIOP:: AP = 270
,03-17 13:30:59.992  1018  1096 V AlarmManager: waitForAlarm result :8
,03-17 13:31:00.782   288   288 E SMD     : DCD OFF
,03-17 13:31:03.782   288   288 E SMD     : DCD OFF
,03-17 13:31:05.782  1018  2818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:31:06.782   288   288 E SMD     : DCD OFF
,03-17 13:31:06.982  1018  1388 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:31:06.982  1018  1388 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:31:06.982  1018  1388 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:31:06.982  1018  1388 D BatteryService: stay LED for fully charged
,03-17 13:31:06.982  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:31:06.982  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-17 13:31:06.982  1018  1018 I MotionRecognitionService: Plugged
03-17 13:31:06.982  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
03-17 13:31:06.982  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:31:06.992  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 13:31:06.992  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:31:07.002  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:31:07.002  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:31:07.022  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:31:07.022  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:31:07.022  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:31:07.022  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:31:07.022  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:31:07.722   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:31:08.082  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:31:08.722   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:31:09.712   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:31:09.792   288   288 E SMD     : DCD OFF
,03-17 13:31:10.722   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:31:11.712   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:31:12.712   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,03-17 13:31:12.792   288   288 E SMD     : DCD OFF
,03-17 13:31:15.802   288   288 E SMD     : DCD OFF
,03-17 13:31:17.042  1018  1138 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:31:17.042  1018  1138 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:31:17.042  1018  1138 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:31:17.042  1018  1138 D BatteryService: stay LED for fully charged
,03-17 13:31:17.042  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:31:17.042  1018  1018 I MotionRecognitionService: Plugged
,03-17 13:31:17.042  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:31:17.052  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 13:31:17.052  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:31:17.052  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-17 13:31:17.052  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:31:17.062  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:31:17.062  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:31:17.072  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:31:17.082  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:31:17.082  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:31:17.082  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:31:17.082  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:31:17.552  1018  1329 E Watchdog: !@Sync 11
,03-17 13:31:17.712   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:31:18.112  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:31:18.712   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:31:18.802   288   288 E SMD     : DCD OFF
,03-17 13:31:19.722   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:31:20.722   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:31:21.722   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:31:21.802   288   288 E SMD     : DCD OFF
,03-17 13:31:22.522  1018  1050 I PowerManagerService: [PWL] Off : 275s ago
,03-17 13:31:22.732   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,03-17 13:31:24.792   288   288 E SMD     : DCD OFF
,03-17 13:31:24.922  1719  1719 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 13:31:24.922  1018  1737 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:31:24.922  1018  1737 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:31:24.922  1018  1737 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:31:24.942  1018  1501 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:31:24.942  1018  1501 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:31:24.942  1018  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:31:24.972  1719  2108 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-17 13:31:24.972  1719  2108 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-17 13:31:24.972  1719  2108 I GLSUser : [GLSUser] Extracting token using key: Auth
03-17 13:31:24.972  1719  2108 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-17 13:31:24.982  1719  2108 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 13:31:24.982  1018  1388 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:31:24.982  1018  1388 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:31:24.982  1018  1388 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:31:25.012  1018  1737 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,03-17 13:31:25.012  1018  1737 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,03-17 13:31:25.022  1018  1018 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,03-17 13:31:25.022  1172  1172 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,03-17 13:31:25.032  1719  2108 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-17 13:31:25.032  1719  2108 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-17 13:31:25.032  1719  2108 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-17 13:31:25.032  1719  2108 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-17 13:31:25.032  1719  2108 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-17 13:31:25.032  1719  2108 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-17 13:31:25.032  1719  2108 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:461)
,03-17 13:31:25.032  1172  1172 D PersonaManager: isKioskContainerExistOnDevice
03-17 13:31:25.032  1172  1172 D PersonaManager: isKioskContainerExistOnDevice
,03-17 13:31:25.032  1172  1172 I PhoneStatusBar: Icon Only
03-17 13:31:25.032  1172  1172 I StatusBar: Icon Only
03-17 13:31:25.032  1172  1172 D PanelView: There is/are notification(s) 
03-17 13:31:25.032  1172  1172 D PanelView: kidsfalse mQsExpansionEnabled:true
03-17 13:31:25.032  5349  5383 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
03-17 13:31:25.032  5349  5383 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-17 13:31:25.032  5349  5383 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
03-17 13:31:25.032  5349  5383 E PlayEventLogger: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-17 13:31:25.032  5349  5383 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
03-17 13:31:25.032  5349  5383 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-17 13:31:25.032  5349  5383 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:461)
,03-17 13:31:25.032  1172  1172 D PersonaManager: isKioskContainerExistOnDevice,
03-17 13:31:25.032  1172  1172 I PhoneStatusBar: Icon Only
03-17 13:31:25.032  1172  1172 I StatusBar: Icon Only
03-17 13:31:25.032  1172  1172 D PanelView: There is/are notification(s) 
03-17 13:31:25.032  1172  1172 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-17 13:31:25.102  1172  1172 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true,
,03-17 13:31:25.192  1018  3817 I art     : Explicit concurrent mark sweep GC freed 56955(4MB) AllocSpace objects, 111(1790KB) LOS objects, 33% free, 23MB/35MB, paused 2.349ms total 154.846ms,
,03-17 13:31:25.222  5349  5383 W System  : Ignoring header User-Agent because its value was null.
,03-17 13:31:25.222  5349  5383 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,03-17 13:31:25.222  5349  5383 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
03-17 13:31:25.222  5349  5383 I System.out: (HTTPLog)-Static: isShipBuild true
03-17 13:31:25.222  5349  5383 I System.out: (HTTPLog)-Thread-908-646556724: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
03-17 13:31:25.222  5349  5383 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,03-17 13:31:25.222   278  1003 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-17 13:31:25.222   278  1003 D Netd    : getNetworkForDns: using netid 502 for uid 10026
,03-17 13:31:25.342  5349  5383 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,03-17 13:31:25.792  1018  2818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:31:27.102  1018  1737 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-17 13:31:27.102  1018  1737 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:31:27.102  1018  1737 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:31:27.102  1018  1737 D BatteryService: stay LED for fully charged
03-17 13:31:27.102  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:31:27.112  1018  1018 I MotionRecognitionService: Plugged
03-17 13:31:27.112  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:31:27.112  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 13:31:27.112  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:31:27.112  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-17 13:31:27.122  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:31:27.132  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:31:27.132  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:31:27.142  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:31:27.142  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:31:27.142  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:31:27.142  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:31:27.142  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:31:27.802   288   288 E SMD     : DCD OFF
,03-17 13:31:28.132  1018  2774 D SSRM:n  : SIOP:: AP = 270
,03-17 13:31:30.792   288   288 E SMD     : DCD OFF,
,03-17 13:31:32.722   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 13:31:33.722   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 13:31:33.802   288   288 E SMD     : DCD OFF,
,03-17 13:31:34.722   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 13:31:35.722   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:31:36.722   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:31:36.812   288   288 E SMD     : DCD OFF
,03-17 13:31:37.172  1018  1388 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:31:37.732   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-17 13:31:38.172  1018  2774 D SSRM:n  : SIOP:: AP = 270
,03-17 13:31:39.802   288   288 E SMD     : DCD OFF
,03-17 13:31:42.802   288   288 E SMD     : DCD OFF
,03-17 13:31:45.792  1018  2818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:31:45.812   288   288 E SMD     : DCD OFF
,03-17 13:31:47.232  1018  1541 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:31:47.232  1018  1541 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:31:47.232  1018  1541 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:31:47.232  1018  1541 D BatteryService: stay LED for fully charged
,03-17 13:31:47.232  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:31:47.242  1018  1018 I MotionRecognitionService: Plugged
,03-17 13:31:47.242  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:31:47.242  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-17 13:31:47.242  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate,
03-17 13:31:47.242  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 13:31:47.242  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:31:47.252  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:31:47.262  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:31:47.272  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:31:47.272  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:31:47.272  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:31:47.272  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:31:47.272  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:31:47.552  1018  1329 E Watchdog: !@Sync 12
,03-17 13:31:48.182  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:31:48.812   288   288 E SMD     : DCD OFF
,03-17 13:31:51.812   288   288 E SMD     : DCD OFF
,03-17 13:31:52.732   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:31:53.722   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:31:54.722   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:31:54.822   288   288 E SMD     : DCD OFF
,03-17 13:31:55.732   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:31:56.722   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:31:57.292  1018  3817 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-17 13:31:57.732   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,03-17 13:31:57.822   288   288 E SMD     : DCD OFF
,03-17 13:31:58.192  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:32:00.822   288   288 E SMD     : DCD OFF
,03-17 13:32:03.822   288   288 E SMD     : DCD OFF
,03-17 13:32:05.792  1018  2818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-17 13:32:06.812   288   288 E SMD     : DCD OFF
,03-17 13:32:07.362  1018  1501 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:32:07.362  1018  1501 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:32:07.362  1018  1501 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,03-17 13:32:07.362  1018  1501 D BatteryService: stay LED for fully charged
03-17 13:32:07.362  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:32:07.362  1018  1018 I MotionRecognitionService: Plugged
03-17 13:32:07.362  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:32:07.372  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 13:32:07.372  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:32:07.372  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-17 13:32:07.372  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:32:07.382  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-17 13:32:07.382  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:32:07.392  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:32:07.392  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:32:07.392  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:32:07.392  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-17 13:32:07.392  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:32:08.212  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:32:09.832   288   288 E SMD     : DCD OFF
,03-17 13:32:12.832   288   288 E SMD     : DCD OFF
,03-17 13:32:15.832   288   288 E SMD     : DCD OFF
,03-17 13:32:17.422  1018  1512 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:32:17.522  1018  1050 I PowerManagerService: [PWL] Off : 330s ago
,03-17 13:32:17.552  1018  1329 E Watchdog: !@Sync 13
,03-17 13:32:17.732   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:32:18.232  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:32:18.722   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:32:18.832   288   288 E SMD     : DCD OFF
,03-17 13:32:19.732   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:32:20.732   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:32:21.732   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:32:21.832   288   288 E SMD     : DCD OFF
,03-17 13:32:22.742   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,03-17 13:32:24.822   288   288 E SMD     : DCD OFF
,03-17 13:32:25.782  1018  2818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:32:27.482  1018  1740 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:32:27.832   288   288 E SMD     : DCD OFF
,03-17 13:32:28.242  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:32:30.842   288   288 E SMD     : DCD OFF
,03-17 13:32:33.832   288   288 E SMD     : DCD OFF
,03-17 13:32:36.832   288   288 E SMD     : DCD OFF
,03-17 13:32:37.552  1018  3843 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:32:37.552  1018  3843 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:32:37.552  1018  3843 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:32:37.552  1018  3843 D BatteryService: stay LED for fully charged
03-17 13:32:37.552  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:32:37.552  1018  1018 I MotionRecognitionService: Plugged
03-17 13:32:37.552  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:32:37.552  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-17 13:32:37.562  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:32:37.562  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-17 13:32:37.562  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:32:37.572  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:32:37.572  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:32:37.592  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:32:37.592  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:32:37.592  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:32:37.592  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:32:37.592  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:32:38.262  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:32:39.842   288   288 E SMD     : DCD OFF
,03-17 13:32:42.842   288   288 E SMD     : DCD OFF
,03-17 13:32:45.782  1018  2818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:32:45.832   288   288 E SMD     : DCD OFF
,03-17 13:32:47.552  1018  1329 E Watchdog: !@Sync 14
,03-17 13:32:47.612  1018  1138 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:32:47.612  1018  1138 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,03-17 13:32:47.612  1018  1138 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:32:47.612  1018  1138 D BatteryService: stay LED for fully charged
,03-17 13:32:47.612  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:32:47.622  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 13:32:47.622  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:32:47.622  1018  1018 I MotionRecognitionService: Plugged
,03-17 13:32:47.622  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 13:32:47.622  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:32:47.622  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:32:47.632  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:32:47.632  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:32:47.632  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:32:47.642  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:32:47.652  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:32:47.652  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:32:47.652  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:32:47.742   315   315 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
03-17 13:32:47.742   315   315 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,03-17 13:32:48.292  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:32:48.842   288   288 E SMD     : DCD OFF
,03-17 13:32:51.852   288   288 E SMD     : DCD OFF
,03-17 13:32:54.842   288   288 E SMD     : DCD OFF
,03-17 13:32:57.682  1018  1739 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-17 13:32:57.852   288   288 E SMD     : DCD OFF,
,03-17 13:32:58.302  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:33:00.842   288   288 E SMD     : DCD OFF
,03-17 13:33:03.842   288   288 E SMD     : DCD OFF
,03-17 13:33:05.792  1018  2818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-17 13:33:06.842   288   288 E SMD     : DCD OFF
,03-17 13:33:07.732   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:33:07.742  1018  1388 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-17 13:33:07.742  1018  1388 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,03-17 13:33:07.742  1018  1388 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:33:07.742  1018  1388 D BatteryService: stay LED for fully charged
03-17 13:33:07.742  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:33:07.742  1018  1018 I MotionRecognitionService: Plugged
03-17 13:33:07.742  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
03-17 13:33:07.752  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-17 13:33:07.752  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
03-17 13:33:07.752  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 13:33:07.752  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:33:07.762  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-17 13:33:07.762  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:33:07.782  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-17 13:33:07.782  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:33:07.782  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:33:07.782  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:33:07.782  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:33:08.312  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:33:08.732   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:33:09.732   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:33:09.852   288   288 E SMD     : DCD OFF
,03-17 13:33:10.742   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:33:11.732   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:33:12.732   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,03-17 13:33:12.862   288   288 E SMD     : DCD OFF
,03-17 13:33:15.862   288   288 E SMD     : DCD OFF
,03-17 13:33:17.542  1018  1050 I PowerManagerService: [PWL] Off : 390s ago,
,03-17 13:33:17.562  1018  1329 E Watchdog: !@Sync 15
,03-17 13:33:17.742   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:33:17.802  1018  3843 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:33:18.342  1018  2774 D SSRM:n  : SIOP:: AP = 290
,03-17 13:33:18.742   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:33:18.862   288   288 E SMD     : DCD OFF
,03-17 13:33:19.742   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:33:20.732   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:33:21.742   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:33:21.862   288   288 E SMD     : DCD OFF
,03-17 13:33:22.742   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,03-17 13:33:24.852   288   288 E SMD     : DCD OFF
,03-17 13:33:25.792  1018  2818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-17 13:33:27.852   288   288 E SMD     : DCD OFF
,03-17 13:33:27.872  1018  3817 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-17 13:33:28.382  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:33:30.862   288   288 E SMD     : DCD OFF
,03-17 13:33:32.742   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:33:33.742   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:33:33.872   288   288 E SMD     : DCD OFF
,03-17 13:33:34.742   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 13:33:35.742   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 13:33:35.762   312   312 I bootchecker: bootchecker wake up!!
,03-17 13:33:36.742   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 13:33:36.872   288   288 E SMD     : DCD OFF,
,03-17 13:33:37.742   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,03-17 13:33:37.922  1018  1501 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:33:38.422  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:33:39.872   288   288 E SMD     : DCD OFF
,03-17 13:33:42.872   288   288 E SMD     : DCD OFF
,03-17 13:33:45.802  1018  2818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-17 13:33:45.862   288   288 E SMD     : DCD OFF,
,03-17 13:33:47.562  1018  1329 E Watchdog: !@Sync 16
,03-17 13:33:47.992  1018  1739 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:33:47.992  1018  1739 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:33:47.992  1018  1739 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:33:47.992  1018  1739 D BatteryService: stay LED for fully charged
,03-17 13:33:47.992  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-17 13:33:47.992  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-17 13:33:47.992  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
03-17 13:33:47.992  1018  1018 I MotionRecognitionService: Plugged,
03-17 13:33:47.992  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
03-17 13:33:48.002  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-17 13:33:48.002  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:33:48.012  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:33:48.012  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:33:48.032  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:33:48.032  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:33:48.032  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:33:48.032  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:33:48.032  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:33:48.432  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:33:48.872   288   288 E SMD     : DCD OFF
,03-17 13:33:51.882   288   288 E SMD     : DCD OFF
,03-17 13:33:52.742   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:33:53.742   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:33:54.742   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 13:33:54.872   288   288 E SMD     : DCD OFF,
,03-17 13:33:55.752   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 13:33:56.742   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:33:57.742   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,03-17 13:33:57.882   288   288 E SMD     : DCD OFF
,03-17 13:33:58.052  1018  1740 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:33:58.052  1018  1740 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:33:58.052  1018  1740 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,03-17 13:33:58.052  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:33:58.052  1018  1740 D BatteryService: stay LED for fully charged
,03-17 13:33:58.052  1018  1018 I MotionRecognitionService: Plugged
03-17 13:33:58.062  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:33:58.062  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-17 13:33:58.062  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
03-17 13:33:58.062  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
03-17 13:33:58.062  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:33:58.072  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:33:58.072  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:33:58.082  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:33:58.082  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:33:58.082  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:33:58.082  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:33:58.082  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:33:58.452  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:33:59.992  1018  1096 V AlarmManager: waitForAlarm result :8
,03-17 13:33:59.992  1018  1096 V AlarmManager: No more alarm at this time.nowELAPSED=510639 batch.start=519621
,03-17 13:34:00.872   288   288 E SMD     : DCD OFF,
,03-17 13:34:03.882   288   288 E SMD     : DCD OFF
,03-17 13:34:05.802  1018  2818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:34:06.882   288   288 E SMD     : DCD OFF
,03-17 13:34:08.112  1018  1384 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:34:08.112  1018  1384 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:34:08.122  1018  1384 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:34:08.122  1018  1384 D BatteryService: stay LED for fully charged
03-17 13:34:08.122  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:34:08.122  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-17 13:34:08.122  1018  1018 I MotionRecognitionService: Plugged
03-17 13:34:08.122  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate,
03-17 13:34:08.122  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
03-17 13:34:08.122  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 13:34:08.122  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,03-17 13:34:08.132  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:34:08.132  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-17 13:34:08.132  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:34:08.152  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:34:08.152  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:34:08.152  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:34:08.152  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:34:08.472  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:34:08.982  1018  1096 V AlarmManager: waitForAlarm result :4
,03-17 13:34:08.982  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-17 13:34:08.982  1172  1172 D KeyguardUpdateMonitor: handleTimeUpdate
,03-17 13:34:08.982  1172  1172 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-17 13:34:08.982  1172  1172 D SecKeyguardClockView: HomeTimezone(): 1
,03-17 13:34:08.992  1172  1172 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:34:08.992  1172  1172 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
03-17 13:34:08.992  1172  1172 I KeyguardEffectViewController: *** don't update sliding image ***
,03-17 13:34:09.022  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:34:09.022  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:34:09.032  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:34:09.042  1172  1172 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,03-17 13:34:09.052  1172  1172 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:34:09.072  6006  6318 I BooksSync: Starting books sync for 61035162, extras: ade
,03-17 13:34:09.092  6006  6319 I BooksConfig: GmsCore Version = 7.8.99 (2134222-434)
,03-17 13:34:09.092  1018  1740 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:34:09.092  1018  1740 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:34:09.092  1018  1740 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,03-17 13:34:09.112  1018  3817 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:34:09.112  1018  3817 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:34:09.112  1018  3817 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:34:09.122  1719  2116 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-17 13:34:09.132  1719  2116 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-17 13:34:09.132  1719  2116 I GLSUser : [GLSUser] Extracting token using key: Auth
03-17 13:34:09.132  1719  2116 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-17 13:34:09.132  1719  2116 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 13:34:09.132  1018  3819 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:34:09.142  1018  3819 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:34:09.142  1018  3819 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:34:09.162  1018  1030 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,03-17 13:34:09.162  1018  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,03-17 13:34:09.162  1018  1018 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,03-17 13:34:09.172  1172  1172 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,03-17 13:34:09.172  1172  1172 D PersonaManager: isKioskContainerExistOnDevice
,03-17 13:34:09.172  1172  1172 D PersonaManager: isKioskContainerExistOnDevice
03-17 13:34:09.172  1172  1172 I PhoneStatusBar: Icon Only
03-17 13:34:09.172  1172  1172 I StatusBar: Icon Only
03-17 13:34:09.172  1172  1172 D PanelView: There is/are notification(s) 
03-17 13:34:09.172  1172  1172 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-17 13:34:09.172  1172  1172 D PersonaManager: isKioskContainerExistOnDevice
03-17 13:34:09.172  1172  1172 I PhoneStatusBar: Icon Only
,03-17 13:34:09.172  1172  1172 I StatusBar: Icon Only
03-17 13:34:09.172  1172  1172 D PanelView: There is/are notification(s) 
03-17 13:34:09.172  1172  1172 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-17 13:34:09.182  1018  3843 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:34:09.182  1018  3843 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:34:09.182  1018  3843 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,03-17 13:34:09.192  1018  1737 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:34:09.192  1018  1737 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:34:09.192  1018  1737 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:34:09.202  1719  1730 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-17 13:34:09.202  1719  1730 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-17 13:34:09.202  1719  1730 I GLSUser : [GLSUser] Extracting token using key: Auth
03-17 13:34:09.202  1719  1730 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-17 13:34:09.212  1719  1730 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 13:34:09.212  1018  1305 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:34:09.212  1018  1305 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:34:09.212  1018  1305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:34:09.222  6006  6319 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-17 13:34:09.222  6006  6318 E BooksSync: Soft error
03-17 13:34:09.222  6006  6318 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-17 13:34:09.222  6006  6318 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-17 13:34:09.222  6006  6318 E BooksSync: Sync error
03-17 13:34:09.222  6006  6318 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-17 13:34:09.222  6006  6318 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-17 13:34:09.222  6006  6318 I BooksSync: Finished books sync
,03-17 13:34:09.232  1018  1042 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 519621, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-17 13:34:09.242  1172  1172 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,03-17 13:34:09.272  1018  1512 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,03-17 13:34:09.272  1018  1512 D SecContentProvider2: mCursor = null
,03-17 13:34:09.882   288   288 E SMD     : DCD OFF
,03-17 13:34:12.892   288   288 E SMD     : DCD OFF
,03-17 13:34:15.892   288   288 E SMD     : DCD OFF,
,03-17 13:34:17.562  1018  1329 E Watchdog: !@Sync 17
,03-17 13:34:17.752   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:34:18.182  1018  1501 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-17 13:34:18.482  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:34:18.742   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:34:18.892   288   288 E SMD     : DCD OFF,
,03-17 13:34:19.742   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 13:34:20.752   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 13:34:21.752   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:34:21.892   288   288 E SMD     : DCD OFF
,03-17 13:34:22.542  1018  1050 I PowerManagerService: [PWL] Off : 455s ago
,03-17 13:34:22.762   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,03-17 13:34:24.892   288   288 E SMD     : DCD OFF
,03-17 13:34:25.792  1018  2818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:34:27.892   288   288 E SMD     : DCD OFF
,03-17 13:34:28.242  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:34:28.502  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:34:30.892   288   288 E SMD     : DCD OFF,
,03-17 13:34:33.892   288   288 E SMD     : DCD OFF
,03-17 13:34:36.892   288   288 E SMD     : DCD OFF
,03-17 13:34:38.312  1018  1739 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-17 13:34:38.522  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:34:39.062  1018  1096 V AlarmManager: waitForAlarm result :4
,03-17 13:34:39.902   288   288 E SMD     : DCD OFF
,03-17 13:34:42.902   288   288 E SMD     : DCD OFF
,03-17 13:34:45.802  1018  2818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:34:45.892   288   288 E SMD     : DCD OFF,
,03-17 13:34:47.562  1018  1329 E Watchdog: !@Sync 18
,03-17 13:34:47.752   315   315 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
03-17 13:34:47.752   315   315 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,03-17 13:34:48.372  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:34:48.372  1018  1031 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:34:48.372  1018  1031 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:34:48.372  1018  1031 D BatteryService: stay LED for fully charged
03-17 13:34:48.372  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:34:48.372  1018  1018 I MotionRecognitionService: Plugged
03-17 13:34:48.372  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:34:48.382  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-17 13:34:48.382  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:34:48.382  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
03-17 13:34:48.382  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:34:48.392  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-17 13:34:48.392  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:34:48.402  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:34:48.402  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:34:48.402  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:34:48.402  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-17 13:34:48.402  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:34:48.532  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:34:48.902   288   288 E SMD     : DCD OFF,
,03-17 13:34:51.912   288   288 E SMD     : DCD OFF
,03-17 13:34:54.902   288   288 E SMD     : DCD OFF,
,03-17 13:34:57.912   288   288 E SMD     : DCD OFF
,03-17 13:34:58.432  1018  1305 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:34:58.572  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:34:59.992  1018  1096 V AlarmManager: waitForAlarm result :8
,03-17 13:35:00.912   288   288 E SMD     : DCD OFF,
,03-17 13:35:03.912   288   288 E SMD     : DCD OFF
,03-17 13:35:05.802  1018  2818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:35:06.902   288   288 E SMD     : DCD OFF
,03-17 13:35:08.492  1018  1501 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:35:08.622  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:35:09.912   288   288 E SMD     : DCD OFF,
,03-17 13:35:12.762   315   315 I Atfwd_Daemon: Stop the daemon....,
,03-17 13:35:12.922   288   288 E SMD     : DCD OFF,
,03-17 13:35:15.922   288   288 E SMD     : DCD OFF,
,03-17 13:35:17.562  1018  1329 E Watchdog: !@Sync 19
,03-17 13:35:18.562  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-17 13:35:18.562  1018  1030 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:35:18.562  1018  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:35:18.562  1018  1030 D BatteryService: stay LED for fully charged
03-17 13:35:18.562  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:35:18.562  1018  1018 I MotionRecognitionService: Plugged
,03-17 13:35:18.562  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:35:18.562  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 13:35:18.562  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:35:18.572  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-17 13:35:18.572  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:35:18.582  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:35:18.582  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:35:18.592  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:35:18.592  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:35:18.592  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:35:18.592  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:35:18.592  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:35:18.632  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:35:18.922   288   288 E SMD     : DCD OFF
,03-17 13:35:21.922   288   288 E SMD     : DCD OFF
,03-17 13:35:24.912   288   288 E SMD     : DCD OFF,
,03-17 13:35:25.802  1018  2818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:35:27.912   288   288 E SMD     : DCD OFF
,03-17 13:35:28.622  1018  1388 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-17 13:35:28.622  1018  1388 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:35:28.622  1018  1388 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:35:28.622  1018  1388 D BatteryService: stay LED for fully charged
03-17 13:35:28.622  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
03-17 13:35:28.622  1018  1018 I MotionRecognitionService: Plugged
03-17 13:35:28.622  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
03-17 13:35:28.622  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-17 13:35:28.632  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:35:28.632  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 13:35:28.632  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:35:28.642  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-17 13:35:28.642  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:35:28.652  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:35:28.652  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:35:28.652  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:35:28.652  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:35:28.652  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:35:28.662  1018  2774 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:35:30.922   288   288 E SMD     : DCD OFF,
,03-17 13:35:32.532  1018  1050 I PowerManagerService: [PWL] Off : 525s ago
,03-17 13:35:33.932   288   288 E SMD     : DCD OFF
,03-17 13:35:36.922   288   288 E SMD     : DCD OFF
,03-17 13:35:38.682  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-17 13:35:38.682  1018  1030 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:35:38.682  1018  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:35:38.682  1018  1030 D BatteryService: stay LED for fully charged
03-17 13:35:38.682  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:35:38.692  1018  1018 I MotionRecognitionService: Plugged
,03-17 13:35:38.692  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:35:38.692  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 13:35:38.692  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:35:38.702  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 13:35:38.702  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:35:38.702  1018  2774 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:35:38.712  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:35:38.712  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:35:38.732  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:35:38.732  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:35:38.732  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:35:38.732  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-17 13:35:38.732  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:35:39.932   288   288 E SMD     : DCD OFF
,03-17 13:35:42.932   288   288 E SMD     : DCD OFF
,03-17 13:35:44.552  1018  1087 D TimaService: TIMA: TimaService scheduler is intialized. 
,03-17 13:35:44.552  1018  1087 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,03-17 13:35:44.552  1018  1086 D TimaService: TimaServiceHandler.handleMessage what =1
,03-17 13:35:45.412  1018  1087 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,03-17 13:35:45.412  1018  1087 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-17 13:35:45.422  1018  1087 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-17 13:35:45.422  1018  1087 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-17 13:35:45.792  1018  2818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:35:45.932   288   288 E SMD     : DCD OFF,
,03-17 13:35:47.562  1018  1329 E Watchdog: !@Sync 20
,03-17 13:35:48.742  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:35:48.752  1018  1388 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-17 13:35:48.752  1018  1388 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:35:48.752  1018  1388 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:35:48.752  1018  1388 D BatteryService: stay LED for fully charged
03-17 13:35:48.752  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:35:48.752  1018  1018 I MotionRecognitionService: Plugged
,03-17 13:35:48.752  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:35:48.752  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 13:35:48.762  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:35:48.762  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-17 13:35:48.762  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:35:48.772  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:35:48.772  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:35:48.782  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-17 13:35:48.782  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:35:48.782  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:35:48.782  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:35:48.782  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:35:48.932   288   288 E SMD     : DCD OFF
,03-17 13:35:51.932   288   288 E SMD     : DCD OFF
,03-17 13:35:54.942   288   288 E SMD     : DCD OFF
,03-17 13:35:57.942   288   288 E SMD     : DCD OFF
,03-17 13:35:58.782  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:35:58.832  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:36:00.942   288   288 E SMD     : DCD OFF,
,03-17 13:36:03.942   288   288 E SMD     : DCD OFF
,03-17 13:36:05.802  1018  2818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:36:06.942   288   288 E SMD     : DCD OFF
,03-17 13:36:08.802  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:36:08.892  1018  1739 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:36:08.892  1018  1739 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:36:08.892  1018  1739 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:36:08.892  1018  1739 D BatteryService: stay LED for fully charged
,03-17 13:36:08.892  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:36:08.902  1018  1018 I MotionRecognitionService: Plugged
,03-17 13:36:08.902  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:36:08.902  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 13:36:08.902  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:36:08.902  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-17 13:36:08.912  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:36:08.922  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:36:08.922  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:36:08.942  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:36:08.942  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:36:08.942  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:36:08.942  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:36:08.942  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:36:09.942   288   288 E SMD     : DCD OFF,
,03-17 13:36:12.942   288   288 E SMD     : DCD OFF
,03-17 13:36:15.942   288   288 E SMD     : DCD OFF
,03-17 13:36:17.552  1018  1329 E Watchdog: !@Sync 21
,03-17 13:36:18.842  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:36:18.942   288   288 E SMD     : DCD OFF
,03-17 13:36:18.962  1018  3843 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:36:18.962  1018  3843 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:36:18.962  1018  3843 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:36:18.962  1018  3843 D BatteryService: stay LED for fully charged
,03-17 13:36:18.962  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:36:18.962  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 13:36:18.972  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 13:36:18.962  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
03-17 13:36:18.972  1018  1018 I MotionRecognitionService: Plugged
03-17 13:36:18.972  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
03-17 13:36:18.972  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:36:18.982  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:36:18.982  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:36:18.992  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:36:18.992  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:36:18.992  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:36:18.992  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:36:18.992  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:36:21.942   288   288 E SMD     : DCD OFF
,03-17 13:36:24.942   288   288 E SMD     : DCD OFF,
,03-17 13:36:27.952   288   288 E SMD     : DCD OFF
,03-17 13:36:28.882  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:36:29.022  1018  3818 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:36:30.952   288   288 E SMD     : DCD OFF,
,03-17 13:36:33.962   288   288 E SMD     : DCD OFF
,03-17 13:36:36.952   288   288 E SMD     : DCD OFF
,03-17 13:36:38.902  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:36:39.082  1018  1740 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:36:39.952   288   288 E SMD     : DCD OFF,
,03-17 13:36:42.962   288   288 E SMD     : DCD OFF
,03-17 13:36:45.952   288   288 E SMD     : DCD OFF,
,03-17 13:36:47.552  1018  1329 E Watchdog: !@Sync 22
,03-17 13:36:47.562  1018  1050 I PowerManagerService: [PWL] Off : 600s ago
,03-17 13:36:48.942  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:36:48.952   288   288 E SMD     : DCD OFF
,03-17 13:36:49.152  1018  1384 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:36:49.152  1018  1384 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:36:49.152  1018  1384 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:36:49.152  1018  1384 D BatteryService: stay LED for fully charged
03-17 13:36:49.152  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:36:49.152  1018  1018 I MotionRecognitionService: Plugged
,03-17 13:36:49.152  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:36:49.152  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 13:36:49.152  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:36:49.162  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-17 13:36:49.162  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:36:49.162  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-17 13:36:49.162  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:36:49.172  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:36:49.172  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:36:49.182  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:36:49.182  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:36:49.182  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:36:51.962   288   288 E SMD     : DCD OFF
,03-17 13:36:54.962   288   288 E SMD     : DCD OFF
,03-17 13:36:57.962   288   288 E SMD     : DCD OFF
,03-17 13:36:58.982  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:36:59.212  1018  1541 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:36:59.212  1018  1541 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:36:59.212  1018  1541 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,03-17 13:36:59.212  1018  1541 D BatteryService: stay LED for fully charged
03-17 13:36:59.212  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:36:59.212  1018  1018 I MotionRecognitionService: Plugged
,03-17 13:36:59.212  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:36:59.222  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 13:36:59.222  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:36:59.222  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-17 13:36:59.222  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:36:59.232  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:36:59.232  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:36:59.242  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:36:59.242  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:36:59.242  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:36:59.242  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:36:59.242  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:37:00.972   288   288 E SMD     : DCD OFF,
,03-17 13:37:03.962   288   288 E SMD     : DCD OFF,
,03-17 13:37:06.972   288   288 E SMD     : DCD OFF,
,03-17 13:37:09.002  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:37:09.272  1018  1388 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:37:09.982   288   288 E SMD     : DCD OFF
,03-17 13:37:12.972   288   288 E SMD     : DCD OFF
,03-17 13:37:15.982   288   288 E SMD     : DCD OFF
,03-17 13:37:17.562  1018  1329 E Watchdog: !@Sync 23
,03-17 13:37:18.982   288   288 E SMD     : DCD OFF
,03-17 13:37:19.012  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:37:19.342  1018  3819 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:37:19.342  1018  3819 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:37:19.342  1018  3819 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:37:19.342  1018  3819 D BatteryService: stay LED for fully charged
,03-17 13:37:19.342  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-17 13:37:19.342  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-17 13:37:19.342  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
03-17 13:37:19.352  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-17 13:37:19.352  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-17 13:37:19.352  1018  1018 I MotionRecognitionService: Plugged
03-17 13:37:19.352  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:37:19.362  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:37:19.362  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:37:19.382  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:37:19.382  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:37:19.382  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:37:19.382  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:37:19.382  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:37:21.972   288   288 E SMD     : DCD OFF
,03-17 13:37:24.982   288   288 E SMD     : DCD OFF
,03-17 13:37:27.982   288   288 E SMD     : DCD OFF
,03-17 13:37:29.032  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:37:29.402  1018  1739 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:37:29.402  1018  1739 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:37:29.402  1018  1739 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:37:29.402  1018  1739 D BatteryService: stay LED for fully charged
03-17 13:37:29.402  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:37:29.402  1018  1018 I MotionRecognitionService: Plugged
03-17 13:37:29.402  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:37:29.412  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-17 13:37:29.412  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
03-17 13:37:29.412  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 13:37:29.412  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:37:29.422  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:37:29.422  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:37:29.432  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:37:29.432  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:37:29.432  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:37:29.432  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:37:29.432  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:37:30.992   288   288 E SMD     : DCD OFF
,03-17 13:37:33.992   288   288 E SMD     : DCD OFF
,03-17 13:37:36.982   288   288 E SMD     : DCD OFF
,03-17 13:37:39.072  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:37:39.462  1018  3843 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:37:39.472  1018  3843 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:37:39.472  1018  3843 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:37:39.472  1018  3843 D BatteryService: stay LED for fully charged
03-17 13:37:39.472  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:37:39.472  1018  1018 I MotionRecognitionService: Plugged
,03-17 13:37:39.472  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:37:39.472  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-17 13:37:39.472  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:37:39.472  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-17 13:37:39.472  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:37:39.492  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-17 13:37:39.492  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:37:39.502  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:37:39.502  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:37:39.502  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:37:39.502  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-17 13:37:39.502  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:37:39.982   288   288 E SMD     : DCD OFF
,03-17 13:37:42.992   288   288 E SMD     : DCD OFF
,03-17 13:37:45.982   288   288 E SMD     : DCD OFF
,03-17 13:37:47.572  1018  1329 E Watchdog: !@Sync 24
,03-17 13:37:48.992   288   288 E SMD     : DCD OFF
,03-17 13:37:49.082  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:37:49.532  1018  3818 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:37:52.002   288   288 E SMD     : DCD OFF,
,03-17 13:37:54.992   288   288 E SMD     : DCD OFF
,03-17 13:37:58.002   288   288 E SMD     : DCD OFF
,03-17 13:37:59.102  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:37:59.592  1018  1740 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:37:59.592  1018  1740 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:37:59.592  1018  1740 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:37:59.592  1018  1740 D BatteryService: stay LED for fully charged
03-17 13:37:59.592  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:37:59.592  1018  1018 I MotionRecognitionService: Plugged
03-17 13:37:59.592  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:37:59.602  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 13:37:59.602  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:37:59.602  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 13:37:59.602  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:37:59.612  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:37:59.612  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:37:59.622  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:37:59.622  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:37:59.622  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:37:59.622  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-17 13:37:59.622  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:38:00.992   288   288 E SMD     : DCD OFF
,03-17 13:38:04.002   288   288 E SMD     : DCD OFF
,03-17 13:38:07.002   288   288 E SMD     : DCD OFF
,03-17 13:38:07.572  1018  1050 I PowerManagerService: [PWL] Off : 680s ago
,03-17 13:38:09.152  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:38:09.652  1018  1739 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-17 13:38:10.012   288   288 E SMD     : DCD OFF
,03-17 13:38:13.012   288   288 E SMD     : DCD OFF
,03-17 13:38:16.012   288   288 E SMD     : DCD OFF
,03-17 13:38:17.572  1018  1329 E Watchdog: !@Sync 25
,03-17 13:38:19.012   288   288 E SMD     : DCD OFF
,03-17 13:38:19.162  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:38:19.722  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-17 13:38:22.012   288   288 E SMD     : DCD OFF
,03-17 13:38:25.012   288   288 E SMD     : DCD OFF
,03-17 13:38:28.022   288   288 E SMD     : DCD OFF
,03-17 13:38:29.172  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:38:29.782  1018  1737 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:38:31.022   288   288 E SMD     : DCD OFF
,03-17 13:38:34.022   288   288 E SMD     : DCD OFF
,03-17 13:38:37.012   288   288 E SMD     : DCD OFF
,03-17 13:38:39.222  1018  2774 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:38:39.852  1018  1388 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:38:39.852  1018  1388 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:38:39.852  1018  1388 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:38:39.852  1018  1388 D BatteryService: stay LED for fully charged
,03-17 13:38:39.852  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:38:39.852  1018  1018 I MotionRecognitionService: Plugged
,03-17 13:38:39.852  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:38:39.852  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 13:38:39.852  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:38:39.862  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 13:38:39.862  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:38:39.872  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:38:39.872  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:38:39.882  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:38:39.882  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:38:39.882  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:38:39.882  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:38:39.882  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:38:40.022   288   288 E SMD     : DCD OFF
,03-17 13:38:43.012   288   288 E SMD     : DCD OFF
,03-17 13:38:46.022   288   288 E SMD     : DCD OFF
,03-17 13:38:47.562  1018  1329 E Watchdog: !@Sync 26
,03-17 13:38:49.022   288   288 E SMD     : DCD OFF
,03-17 13:38:49.262  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:38:49.912  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:38:52.032   288   288 E SMD     : DCD OFF
,03-17 13:38:55.022   288   288 E SMD     : DCD OFF
,03-17 13:38:58.032   288   288 E SMD     : DCD OFF
,03-17 13:38:59.312  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:38:59.972  1018  1739 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:39:01.022   288   288 E SMD     : DCD OFF
,03-17 13:39:04.032   288   288 E SMD     : DCD OFF
,03-17 13:39:07.042   288   288 E SMD     : DCD OFF
,03-17 13:39:09.352  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:39:10.032   288   288 E SMD     : DCD OFF
,03-17 13:39:10.032  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:39:13.042   288   288 E SMD     : DCD OFF
,03-17 13:39:16.042   288   288 E SMD     : DCD OFF
,03-17 13:39:17.572  1018  1329 E Watchdog: !@Sync 27
,03-17 13:39:19.042   288   288 E SMD     : DCD OFF,
,03-17 13:39:19.382  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:39:20.092  1018  1737 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:39:22.032   288   288 E SMD     : DCD OFF
,03-17 13:39:25.042   288   288 E SMD     : DCD OFF
,03-17 13:39:28.052   288   288 E SMD     : DCD OFF
,03-17 13:39:29.422  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:39:30.152  1018  1388 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-17 13:39:30.162  1018  1388 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:39:30.162  1018  1388 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:39:30.162  1018  1388 D BatteryService: stay LED for fully charged
03-17 13:39:30.162  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:39:30.162  1018  1018 I MotionRecognitionService: Plugged
03-17 13:39:30.162  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:39:30.162  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 13:39:30.162  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
03-17 13:39:30.162  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 13:39:30.162  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:39:30.172  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:39:30.182  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-17 13:39:30.182  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:39:30.192  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:39:30.192  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:39:30.192  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-17 13:39:30.192  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:39:31.052   288   288 E SMD     : DCD OFF
,03-17 13:39:32.572  1018  1050 I PowerManagerService: [PWL] Off : 765s ago
,03-17 13:39:34.042   288   288 E SMD     : DCD OFF
,03-17 13:39:37.052   288   288 E SMD     : DCD OFF
,03-17 13:39:39.452  1018  2774 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:39:40.052   288   288 E SMD     : DCD OFF
,03-17 13:39:40.222  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-17 13:39:43.052   288   288 E SMD     : DCD OFF
,03-17 13:39:46.062   288   288 E SMD     : DCD OFF
,03-17 13:39:47.562  1018  1329 E Watchdog: !@Sync 28
,03-17 13:39:49.062   288   288 E SMD     : DCD OFF
,03-17 13:39:49.472  1018  2774 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:39:50.272  1018  1739 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:39:52.062   288   288 E SMD     : DCD OFF
,03-17 13:39:55.062   288   288 E SMD     : DCD OFF
,03-17 13:39:58.052   288   288 E SMD     : DCD OFF
,03-17 13:39:59.492  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:40:00.342  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:40:01.052   288   288 E SMD     : DCD OFF
,03-17 13:40:04.052   288   288 E SMD     : DCD OFF
,03-17 13:40:07.072   288   288 E SMD     : DCD OFF
,03-17 13:40:09.532  1018  2774 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:40:10.072   288   288 E SMD     : DCD OFF
,03-17 13:40:10.402  1018  1737 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:40:13.072   288   288 E SMD     : DCD OFF
,03-17 13:40:16.072   288   288 E SMD     : DCD OFF
,03-17 13:40:17.572  1018  1329 E Watchdog: !@Sync 29
,03-17 13:40:19.072   288   288 E SMD     : DCD OFF
,03-17 13:40:19.582  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:40:20.472  1018  1388 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-17 13:40:22.062   288   288 E SMD     : DCD OFF
,03-17 13:40:25.072   288   288 E SMD     : DCD OFF
,03-17 13:40:28.082   288   288 E SMD     : DCD OFF
,03-17 13:40:29.602  1018  2774 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:40:30.522  1018  3819 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-17 13:40:31.072   288   288 E SMD     : DCD OFF
,03-17 13:40:34.072   288   288 E SMD     : DCD OFF
,03-17 13:40:37.082   288   288 E SMD     : DCD OFF
,03-17 13:40:39.642  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:40:40.082   288   288 E SMD     : DCD OFF
,03-17 13:40:40.592  1018  1305 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:40:40.592  1018  1305 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:40:40.592  1018  1305 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:40:40.592  1018  1305 D BatteryService: stay LED for fully charged
,03-17 13:40:40.592  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:40:40.592  1018  1018 I MotionRecognitionService: Plugged
,03-17 13:40:40.602  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:40:40.602  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 13:40:40.602  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:40:40.602  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-17 13:40:40.602  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:40:40.612  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:40:40.612  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:40:40.632  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:40:40.632  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:40:40.632  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:40:40.632  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:40:40.632  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:40:43.082   288   288 E SMD     : DCD OFF
,03-17 13:40:44.562  1018  1087 D TimaService: TIMA: TimaService scheduler is intialized. 
03-17 13:40:44.562  1018  1087 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,03-17 13:40:44.562  1018  1086 D TimaService: TimaServiceHandler.handleMessage what =1
,03-17 13:40:46.092   288   288 E SMD     : DCD OFF
,03-17 13:40:46.522  1018  1087 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,03-17 13:40:46.522  1018  1087 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-17 13:40:46.522  1018  1087 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-17 13:40:46.522  1018  1087 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-17 13:40:47.572  1018  1329 E Watchdog: !@Sync 30
,03-17 13:40:49.092   288   288 E SMD     : DCD OFF
,03-17 13:40:49.692  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:40:50.652  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-17 13:40:50.652  1018  1031 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:40:50.652  1018  1031 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:40:50.652  1018  1031 D BatteryService: stay LED for fully charged
03-17 13:40:50.652  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:40:50.662  1018  1018 I MotionRecognitionService: Plugged
,03-17 13:40:50.662  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:40:50.662  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 13:40:50.662  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:40:50.662  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-17 13:40:50.662  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:40:50.672  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:40:50.672  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:40:50.692  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:40:50.692  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:40:50.692  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:40:50.692  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-17 13:40:50.692  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:40:52.092   288   288 E SMD     : DCD OFF
,03-17 13:40:55.082   288   288 E SMD     : DCD OFF
,03-17 13:40:58.012  1018  1096 V AlarmManager: waitForAlarm result :4
,03-17 13:40:58.022  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-17 13:40:58.022  1172  1172 D KeyguardUpdateMonitor: handleTimeUpdate
,03-17 13:40:58.022  1172  1172 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-17 13:40:58.032  1172  1172 D SecKeyguardClockView: HomeTimezone(): 1
,03-17 13:40:58.042  1172  1172 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:40:58.042  1172  1172 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
03-17 13:40:58.042  1172  1172 I KeyguardEffectViewController: *** don't update sliding image ***
,03-17 13:40:58.082   288   288 E SMD     : DCD OFF
,03-17 13:40:58.092  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:40:58.092  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:40:58.102  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:40:58.102  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:40:58.102  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:40:58.102  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:40:58.112  1172  1172 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,03-17 13:40:58.132  1719  2611 D GCM     : Message class com.google.f.a.a.i
,03-17 13:40:58.132  1018  1305 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:40:58.132  1018  1305 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:40:58.132  1018  1305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:40:58.142  1172  1172 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:40:58.152  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:40:58.152  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:40:58.152  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
03-17 13:40:58.152  1719  1719 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-17 13:40:58.182  1018  1541 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:40:58.182  1018  1541 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:40:58.182  1018  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:40:58.222  1018  1138 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:40:58.222  1018  1138 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:40:58.222  1018  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:40:58.252  1018  3817 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:40:58.252  1018  3817 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:40:58.252  1018  3817 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:40:58.262  1719  6487 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,03-17 13:40:58.262   278  1003 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-17 13:40:58.262   278  1003 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,03-17 13:40:58.362  1719  6487 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,03-17 13:40:58.362  1719  6487 I qtaguid : Tagging socket 56 with tag 120300000000{4611,0} for uid -1, pid: 1719, getuid(): 10011
,03-17 13:40:58.462  1719  6487 I qtaguid : Tagging socket 63 with tag 120300000000{4611,0} for uid -1, pid: 1719, getuid(): 10011
,03-17 13:40:58.692  1719  6487 I qtaguid : Untagging socket 56
,03-17 13:40:58.712  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:40:58.712  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:40:58.712  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:40:58.722  1018  3817 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:40:58.722  1018  3817 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:40:58.722  1018  3817 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:40:58.742  1018  1388 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:40:58.742  1018  1388 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:40:58.742  1018  1388 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:40:58.752  1018  1384 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:40:58.752  1018  1384 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:40:58.752  1018  1384 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:40:58.772  1719  6487 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,03-17 13:40:58.782  1018  1740 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:40:58.782  1018  1740 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:40:58.782  1018  1740 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:40:58.792  1018  3819 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:40:58.792  1018  3819 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 13:40:58.792  1018  3819 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:40:58.802  1018  1737 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:40:58.802  1018  1737 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:40:58.802  1018  1737 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:40:58.812  1018  1305 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:40:58.812  1018  1305 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:40:58.812  1018  1305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:40:59.312  1018  1740 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:40:59.312  1018  1740 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:40:59.312  1018  1740 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:40:59.712  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:40:59.822  1719  1719 E SQLiteLog: (10) POSIX Error : 11 SQLite Error : 3850
,03-17 13:40:59.982  1018  1096 V AlarmManager: waitForAlarm result :8
,03-17 13:41:00.732  1018  1740 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-17 13:41:00.732  1018  1740 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:41:00.732  1018  1740 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:41:00.732  1018  1740 D BatteryService: stay LED for fully charged,
03-17 13:41:00.732  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-17 13:41:00.732  1018  1018 I MotionRecognitionService: Plugged,
03-17 13:41:00.732  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-17 13:41:00.732  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
03-17 13:41:00.732  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:41:00.742  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 13:41:00.742  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:41:00.752  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:41:00.752  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:41:00.762  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:41:00.762  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:41:00.762  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:41:00.762  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:41:00.762  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:41:01.082   288   288 E SMD     : DCD OFF,
,03-17 13:41:02.562  1018  1050 I PowerManagerService: [PWL] Off : 855s ago
,03-17 13:41:04.082   288   288 E SMD     : DCD OFF
,03-17 13:41:07.102   288   288 E SMD     : DCD OFF
,03-17 13:41:09.762  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:41:10.092   288   288 E SMD     : DCD OFF
,03-17 13:41:10.792  1018  1739 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:41:10.792  1018  1739 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:41:10.792  1018  1739 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:41:10.792  1018  1739 D BatteryService: stay LED for fully charged
03-17 13:41:10.792  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:41:10.792  1018  1018 I MotionRecognitionService: Plugged
03-17 13:41:10.792  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:41:10.802  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 13:41:10.802  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
03-17 13:41:10.802  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 13:41:10.802  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:41:10.812  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:41:10.812  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:41:10.832  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:41:10.832  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:41:10.832  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:41:10.832  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:41:10.832  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:41:13.092   288   288 E SMD     : DCD OFF
,03-17 13:41:16.092   288   288 E SMD     : DCD OFF
,03-17 13:41:17.572  1018  1329 E Watchdog: !@Sync 31
,03-17 13:41:19.102   288   288 E SMD     : DCD OFF
,03-17 13:41:19.812  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:41:20.852  1018  1740 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:41:22.102   288   288 E SMD     : DCD OFF
,03-17 13:41:25.102   288   288 E SMD     : DCD OFF
,03-17 13:41:28.112   288   288 E SMD     : DCD OFF
,03-17 13:41:29.832  1018  2774 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:41:30.912  1018  1305 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-17 13:41:31.102   288   288 E SMD     : DCD OFF
,03-17 13:41:34.112   288   288 E SMD     : DCD OFF
,03-17 13:41:37.112   288   288 E SMD     : DCD OFF
,03-17 13:41:39.882  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:41:40.102   288   288 E SMD     : DCD OFF
,03-17 13:41:40.972  1018  1541 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-17 13:41:43.112   288   288 E SMD     : DCD OFF
,03-17 13:41:46.122   288   288 E SMD     : DCD OFF
,03-17 13:41:47.572  1018  1329 E Watchdog: !@Sync 32
,03-17 13:41:49.112   288   288 E SMD     : DCD OFF
,03-17 13:41:49.922  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:41:51.032  1018  1501 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-17 13:41:52.122   288   288 E SMD     : DCD OFF
,03-17 13:41:55.122   288   288 E SMD     : DCD OFF
,03-17 13:41:58.122   288   288 E SMD     : DCD OFF
,03-17 13:41:59.972  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:42:01.092  1018  1739 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:42:01.102  1018  1739 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:42:01.102  1018  1739 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:42:01.102  1018  1739 D BatteryService: stay LED for fully charged
,03-17 13:42:01.102  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:42:01.102  1018  1018 I MotionRecognitionService: Plugged
,03-17 13:42:01.102  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:42:01.102  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 13:42:01.112  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:42:01.112  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-17 13:42:01.112  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:42:01.122   288   288 E SMD     : DCD OFF
,03-17 13:42:01.122  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-17 13:42:01.122  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:42:01.142  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:42:01.142  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:42:01.142  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:42:01.142  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:42:01.142  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:42:04.132   288   288 E SMD     : DCD OFF
,03-17 13:42:07.122   288   288 E SMD     : DCD OFF
,03-17 13:42:09.992  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:42:10.122   288   288 E SMD     : DCD OFF
,03-17 13:42:11.162  1018  3843 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:42:13.132   288   288 E SMD     : DCD OFF
,03-17 13:42:16.132   288   288 E SMD     : DCD OFF
,03-17 13:42:17.572  1018  1329 E Watchdog: !@Sync 33
,03-17 13:42:18.152  1018  1096 V AlarmManager: waitForAlarm result :4
,03-17 13:42:18.162  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-17 13:42:18.162  1172  1172 D KeyguardUpdateMonitor: handleTimeUpdate
,03-17 13:42:18.172  1172  1172 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-17 13:42:18.172  1172  1172 D SecKeyguardClockView: HomeTimezone(): 1
,03-17 13:42:18.182  1172  1172 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:42:18.182  1172  1172 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
03-17 13:42:18.182  1172  1172 I KeyguardEffectViewController: *** don't update sliding image ***
,03-17 13:42:18.212  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:42:18.212  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:42:18.212  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:42:18.222  1172  1172 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,03-17 13:42:18.242  1172  1172 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:42:18.452  6006  6527 I BooksSync: Starting books sync for 61035162, extras: ade
,03-17 13:42:18.462  6006  6528 I BooksConfig: GmsCore Version = 7.8.99 (2134222-434)
,03-17 13:42:18.472  1018  1384 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:42:18.472  1018  1384 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:42:18.472  1018  1384 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,03-17 13:42:18.482  1018  1737 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:42:18.482  1018  1737 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:42:18.482  1018  1737 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:42:18.492  1719  1730 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-17 13:42:18.492  1719  1730 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-17 13:42:18.492  1719  1730 I GLSUser : [GLSUser] Extracting token using key: Auth
03-17 13:42:18.492  1719  1730 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-17 13:42:18.502  1719  1730 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 13:42:18.502  1018  3818 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:42:18.502  1018  3818 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:42:18.502  1018  3818 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:42:18.512  1018  1739 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,03-17 13:42:18.522  1018  1739 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,03-17 13:42:18.522  1018  1018 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,03-17 13:42:18.522  1172  1172 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,03-17 13:42:18.522  1172  1172 D PersonaManager: isKioskContainerExistOnDevice
03-17 13:42:18.522  1172  1172 D PersonaManager: isKioskContainerExistOnDevice
,03-17 13:42:18.522  1172  1172 I PhoneStatusBar: Icon Only
03-17 13:42:18.522  1172  1172 I StatusBar: Icon Only
03-17 13:42:18.522  1172  1172 D PanelView: There is/are notification(s) 
03-17 13:42:18.522  1172  1172 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-17 13:42:18.532  1018  3817 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:42:18.532  1018  3817 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:42:18.532  1018  3817 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,03-17 13:42:18.532  1172  1172 D PersonaManager: isKioskContainerExistOnDevice
03-17 13:42:18.532  1172  1172 I PhoneStatusBar: Icon Only
03-17 13:42:18.532  1172  1172 I StatusBar: Icon Only
03-17 13:42:18.532  1172  1172 D PanelView: There is/are notification(s) 
03-17 13:42:18.532  1172  1172 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-17 13:42:18.542  1018  3818 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:42:18.542  1018  3818 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:42:18.542  1018  3818 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:42:18.552  1719  2116 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-17 13:42:18.552  1719  2116 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-17 13:42:18.552  1719  2116 I GLSUser : [GLSUser] Extracting token using key: Auth
03-17 13:42:18.552  1719  2116 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-17 13:42:18.562  1719  2116 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 13:42:18.562  1018  1501 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:42:18.562  1018  1501 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:42:18.562  1018  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:42:18.572  6006  6528 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-17 13:42:18.572  6006  6527 E BooksSync: Soft error
03-17 13:42:18.572  6006  6527 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-17 13:42:18.572  6006  6527 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-17 13:42:18.572  6006  6527 E BooksSync: Sync error
03-17 13:42:18.572  6006  6527 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-17 13:42:18.572  6006  6527 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-17 13:42:18.572  6006  6527 I BooksSync: Finished books sync
,03-17 13:42:18.572  1018  1042 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1008808, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-17 13:42:18.602  1172  1172 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,03-17 13:42:18.612  1018  1388 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,03-17 13:42:18.612  1018  1388 D SecContentProvider2: mCursor = null
,03-17 13:42:19.142   288   288 E SMD     : DCD OFF
,03-17 13:42:20.012  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:42:21.222  1018  1737 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:42:21.222  1018  1737 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:42:21.222  1018  1737 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:42:21.222  1018  1737 D BatteryService: stay LED for fully charged
03-17 13:42:21.222  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:42:21.232  1018  1018 I MotionRecognitionService: Plugged
03-17 13:42:21.232  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-17 13:42:21.232  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:42:21.232  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
03-17 13:42:21.232  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 13:42:21.232  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:42:21.242  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-17 13:42:21.242  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:42:21.252  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:42:21.252  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:42:21.252  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:42:21.252  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:42:21.252  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:42:22.142   288   288 E SMD     : DCD OFF,
,03-17 13:42:25.142   288   288 E SMD     : DCD OFF
,03-17 13:42:28.142   288   288 E SMD     : DCD OFF
,03-17 13:42:30.062  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:42:31.142   288   288 E SMD     : DCD OFF
,03-17 13:42:31.282  1018  1541 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:42:34.142   288   288 E SMD     : DCD OFF
,03-17 13:42:37.142   288   288 E SMD     : DCD OFF
,03-17 13:42:37.572  1018  1050 I PowerManagerService: [PWL] Off : 950s ago
,03-17 13:42:40.082  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:42:40.142   288   288 E SMD     : DCD OFF
,03-17 13:42:41.352  1018  1740 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:42:41.352  1018  1740 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:42:41.352  1018  1740 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:42:41.352  1018  1740 D BatteryService: stay LED for fully charged
03-17 13:42:41.352  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:42:41.352  1018  1018 I MotionRecognitionService: Plugged
,03-17 13:42:41.352  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
03-17 13:42:41.362  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-17 13:42:41.362  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:42:41.362  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 13:42:41.362  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:42:41.372  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:42:41.372  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:42:41.382  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:42:41.382  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:42:41.382  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:42:41.392  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:42:41.392  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:42:43.152   288   288 E SMD     : DCD OFF
,03-17 13:42:46.142   288   288 E SMD     : DCD OFF
,03-17 13:42:47.572  1018  1329 E Watchdog: !@Sync 34
,03-17 13:42:48.452  1018  1096 V AlarmManager: waitForAlarm result :4
,03-17 13:42:49.152   288   288 E SMD     : DCD OFF
,03-17 13:42:50.132  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:42:51.412  1018  1512 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:42:52.152   288   288 E SMD     : DCD OFF
,03-17 13:42:55.152   288   288 E SMD     : DCD OFF
,03-17 13:42:58.162   288   288 E SMD     : DCD OFF
,03-17 13:42:59.982  1018  1096 V AlarmManager: waitForAlarm result :8
,03-17 13:43:00.152  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:43:01.152   288   288 E SMD     : DCD OFF
,03-17 13:43:01.472  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:43:04.152   288   288 E SMD     : DCD OFF,
,03-17 13:43:07.162   288   288 E SMD     : DCD OFF,
,03-17 13:43:10.162   288   288 E SMD     : DCD OFF,
,03-17 13:43:10.172  1018  2774 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:43:11.532  1018  1501 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:43:13.162   288   288 E SMD     : DCD OFF
,03-17 13:43:16.172   288   288 E SMD     : DCD OFF
,03-17 13:43:17.582  1018  1329 E Watchdog: !@Sync 35
,03-17 13:43:19.172   288   288 E SMD     : DCD OFF
,03-17 13:43:20.222  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:43:21.602  1018  1541 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:43:22.172   288   288 E SMD     : DCD OFF
,03-17 13:43:25.162   288   288 E SMD     : DCD OFF
,03-17 13:43:28.162   288   288 E SMD     : DCD OFF
,03-17 13:43:30.272  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:43:31.172   288   288 E SMD     : DCD OFF
,03-17 13:43:31.662  1018  1740 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:43:34.182   288   288 E SMD     : DCD OFF
,03-17 13:43:37.182   288   288 E SMD     : DCD OFF,
,03-17 13:43:40.182   288   288 E SMD     : DCD OFF
,03-17 13:43:40.322  1018  2774 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:43:41.722  1018  1739 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:43:41.722  1018  1739 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:43:41.722  1018  1739 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:43:41.722  1018  1739 D BatteryService: stay LED for fully charged
03-17 13:43:41.722  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:43:41.722  1018  1018 I MotionRecognitionService: Plugged
,03-17 13:43:41.732  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:43:41.732  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-17 13:43:41.732  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate,
03-17 13:43:41.732  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 13:43:41.732  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:43:41.742  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-17 13:43:41.742  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:43:41.752  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:43:41.752  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:43:41.752  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:43:41.752  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:43:41.752  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:43:43.182   288   288 E SMD     : DCD OFF
,03-17 13:43:46.182   288   288 E SMD     : DCD OFF
,03-17 13:43:47.582  1018  1329 E Watchdog: !@Sync 36
,03-17 13:43:49.172   288   288 E SMD     : DCD OFF
,03-17 13:43:50.362  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:43:51.782  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-17 13:43:52.192   288   288 E SMD     : DCD OFF
,03-17 13:43:55.182   288   288 E SMD     : DCD OFF
,03-17 13:43:58.192   288   288 E SMD     : DCD OFF
,03-17 13:44:00.412  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:44:01.192   288   288 E SMD     : DCD OFF
,03-17 13:44:01.842  1018  1501 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:44:01.842  1018  1501 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:44:01.842  1018  1501 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:44:01.842  1018  1501 D BatteryService: stay LED for fully charged
03-17 13:44:01.842  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-17 13:44:01.852  1018  1018 I MotionRecognitionService: Plugged
,03-17 13:44:01.852  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:44:01.852  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-17 13:44:01.852  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
03-17 13:44:01.852  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 13:44:01.852  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:44:01.862  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:44:01.862  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:44:01.872  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:44:01.872  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:44:01.872  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:44:01.872  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:44:01.872  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:44:04.192   288   288 E SMD     : DCD OFF,
,03-17 13:44:07.202   288   288 E SMD     : DCD OFF
,03-17 13:44:10.192   288   288 E SMD     : DCD OFF
,03-17 13:44:10.472  1018  2774 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:44:11.912  1018  3819 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:44:13.192   288   288 E SMD     : DCD OFF
,03-17 13:44:16.192   288   288 E SMD     : DCD OFF,
,03-17 13:44:17.582  1018  1329 E Watchdog: !@Sync 37
,03-17 13:44:17.592  1018  1050 I PowerManagerService: [PWL] Off : 1050s ago,
,03-17 13:44:19.192   288   288 E SMD     : DCD OFF,
,03-17 13:44:20.512  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:44:21.972  1018  1737 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:44:22.202   288   288 E SMD     : DCD OFF
,03-17 13:44:25.202   288   288 E SMD     : DCD OFF
,03-17 13:44:28.212   288   288 E SMD     : DCD OFF
,03-17 13:44:30.542  1018  2774 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:44:31.202   288   288 E SMD     : DCD OFF,
,03-17 13:44:32.032  1018  1512 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:44:34.202   288   288 E SMD     : DCD OFF
,03-17 13:44:37.202   288   288 E SMD     : DCD OFF,
,03-17 13:44:40.212   288   288 E SMD     : DCD OFF,
,03-17 13:44:40.592  1018  2774 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:44:42.092  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:44:43.212   288   288 E SMD     : DCD OFF
,03-17 13:44:46.222   288   288 E SMD     : DCD OFF
,03-17 13:44:47.582  1018  1329 E Watchdog: !@Sync 38
,03-17 13:44:49.222   288   288 E SMD     : DCD OFF
,03-17 13:44:50.612  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:44:52.162  1018  1501 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-17 13:44:52.222   288   288 E SMD     : DCD OFF
,03-17 13:44:55.222   288   288 E SMD     : DCD OFF
,03-17 13:44:58.222   288   288 E SMD     : DCD OFF
,03-17 13:45:00.632  1018  2774 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:45:01.212   288   288 E SMD     : DCD OFF
,03-17 13:45:02.222  1018  1541 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:45:04.232   288   288 E SMD     : DCD OFF
,03-17 13:45:07.222   288   288 E SMD     : DCD OFF
,03-17 13:45:10.232   288   288 E SMD     : DCD OFF
,03-17 13:45:10.672  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:45:12.282  1018  1740 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:45:13.232   288   288 E SMD     : DCD OFF
,03-17 13:45:16.232   288   288 E SMD     : DCD OFF
,03-17 13:45:17.582  1018  1329 E Watchdog: !@Sync 39
,03-17 13:45:19.222   288   288 E SMD     : DCD OFF,
,03-17 13:45:20.712  1018  2774 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:45:22.232   288   288 E SMD     : DCD OFF
,03-17 13:45:22.342  1018  1739 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:45:25.242   288   288 E SMD     : DCD OFF
,03-17 13:45:28.232   288   288 E SMD     : DCD OFF
,03-17 13:45:30.722  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:45:31.232   288   288 E SMD     : DCD OFF,
,03-17 13:45:32.402  1018  3819 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:45:32.402  1018  3819 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:45:32.402  1018  3819 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,03-17 13:45:32.402  1018  3819 D BatteryService: stay LED for fully charged
03-17 13:45:32.402  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:45:32.412  1018  1018 I MotionRecognitionService: Plugged
03-17 13:45:32.412  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:45:32.412  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-17 13:45:32.412  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:45:32.412  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
03-17 13:45:32.412  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:45:32.422  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:45:32.432  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:45:32.432  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:45:32.442  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:45:32.442  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-17 13:45:32.442  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:45:32.442  1172  1172 D SViewCoverView: level :100 plugged : 2,
,03-17 13:45:34.242   288   288 E SMD     : DCD OFF
,03-17 13:45:37.232   288   288 E SMD     : DCD OFF,
,03-17 13:45:40.242   288   288 E SMD     : DCD OFF
,03-17 13:45:40.782  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:45:42.462  1018  1501 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:45:43.252   288   288 E SMD     : DCD OFF
,03-17 13:45:44.562  1018  1087 D TimaService: TIMA: TimaService scheduler is intialized. 
,03-17 13:45:44.562  1018  1087 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
03-17 13:45:44.562  1018  1086 D TimaService: TimaServiceHandler.handleMessage what =1
,03-17 13:45:45.192  1018  1042 I UsageStatsService: User[0] Flushing usage stats to disk
,03-17 13:45:45.222  1018  1102 I ApplicationUsage: handleMessage : MSG_UPDATE_USAGE_DB
,03-17 13:45:45.222  1018  1102 I ApplicationUsage: Updating Usage Statistics in DB @ 1458218745240
,03-17 13:45:45.232  1018  1102 I ApplicationPolicy: updateDataUsageMap
,03-17 13:45:45.392  1018  1087 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,03-17 13:45:45.392  1018  1087 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-17 13:45:45.402  1018  1087 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-17 13:45:45.402  1018  1087 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-17 13:45:45.552  1018  1102 I NetworkDataUsageDb: ::getAppControlDB: DB is Created 
,03-17 13:45:45.552  1018  1102 I NetworkDataUsageDb: ::isTableExists: Table exists 
,03-17 13:45:45.572  1018  1102 I ApplicationUsage: Done Updating Usage Statistics in DB @ 1458218745587
,03-17 13:45:46.252   288   288 E SMD     : DCD OFF
,03-17 13:45:47.582  1018  1329 E Watchdog: !@Sync 40
,03-17 13:45:49.252   288   288 E SMD     : DCD OFF
,03-17 13:45:50.802  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:45:52.252   288   288 E SMD     : DCD OFF
,03-17 13:45:52.522  1018  1541 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:45:55.252   288   288 E SMD     : DCD OFF
,03-17 13:45:58.252   288   288 E SMD     : DCD OFF
,03-17 13:46:00.822  1018  2774 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:46:01.262   288   288 E SMD     : DCD OFF
,03-17 13:46:02.582  1018  1740 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:46:02.592  1018  1050 I PowerManagerService: [PWL] Off : 1155s ago
,03-17 13:46:04.262   288   288 E SMD     : DCD OFF
,03-17 13:46:07.262   288   288 E SMD     : DCD OFF
,03-17 13:46:10.262   288   288 E SMD     : DCD OFF
,03-17 13:46:10.862  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:46:12.642  1018  1739 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:46:13.262   288   288 E SMD     : DCD OFF
,03-17 13:46:16.262   288   288 E SMD     : DCD OFF
,03-17 13:46:17.592  1018  1329 E Watchdog: !@Sync 41
,03-17 13:46:19.272   288   288 E SMD     : DCD OFF
,03-17 13:46:20.892  1018  2774 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:46:22.272   288   288 E SMD     : DCD OFF
,03-17 13:46:22.712  1018  3819 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-17 13:46:25.262   288   288 E SMD     : DCD OFF
,03-17 13:46:28.272   288   288 E SMD     : DCD OFF
,03-17 13:46:30.902  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:46:31.272   288   288 E SMD     : DCD OFF,
,03-17 13:46:32.772  1018  1737 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:46:34.272   288   288 E SMD     : DCD OFF
,03-17 13:46:37.272   288   288 E SMD     : DCD OFF
,03-17 13:46:40.282   288   288 E SMD     : DCD OFF
,03-17 13:46:40.952  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:46:42.832  1018  1512 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:46:43.282   288   288 E SMD     : DCD OFF
,03-17 13:46:46.282   288   288 E SMD     : DCD OFF
,03-17 13:46:47.592  1018  1329 E Watchdog: !@Sync 42
,03-17 13:46:49.282   288   288 E SMD     : DCD OFF
,03-17 13:46:51.002  1018  2774 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:46:52.282   288   288 E SMD     : DCD OFF
,03-17 13:46:52.892  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:46:55.282   288   288 E SMD     : DCD OFF
,03-17 13:46:58.292   288   288 E SMD     : DCD OFF
,03-17 13:47:01.022  1018  2774 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:47:01.292   288   288 E SMD     : DCD OFF
,03-17 13:47:02.952  1018  1501 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-17 13:47:04.292   288   288 E SMD     : DCD OFF
,03-17 13:47:07.292   288   288 E SMD     : DCD OFF
,03-17 13:47:10.292   288   288 E SMD     : DCD OFF
,03-17 13:47:11.072  1018  2774 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:47:13.012  1018  1541 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:47:13.292   288   288 E SMD     : DCD OFF
,03-17 13:47:16.292   288   288 E SMD     : DCD OFF,
,03-17 13:47:17.582  1018  1329 E Watchdog: !@Sync 43
,03-17 13:47:19.302   288   288 E SMD     : DCD OFF
,03-17 13:47:21.122  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:47:22.302   288   288 E SMD     : DCD OFF
,03-17 13:47:23.082  1018  1740 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:47:25.302   288   288 E SMD     : DCD OFF,
,03-17 13:47:28.302   288   288 E SMD     : DCD OFF
,03-17 13:47:31.142  1018  2774 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:47:31.302   288   288 E SMD     : DCD OFF,
,03-17 13:47:33.132  1018  1739 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:47:34.312   288   288 E SMD     : DCD OFF
,03-17 13:47:37.312   288   288 E SMD     : DCD OFF
,03-17 13:47:40.302   288   288 E SMD     : DCD OFF
,03-17 13:47:41.172  1018  2774 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:47:43.202  1018  3819 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-17 13:47:43.312   288   288 E SMD     : DCD OFF,
,03-17 13:47:46.312   288   288 E SMD     : DCD OFF,
,03-17 13:47:47.592  1018  1329 E Watchdog: !@Sync 44
,03-17 13:47:49.312   288   288 E SMD     : DCD OFF
,03-17 13:47:51.202  1018  2774 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:47:52.312   288   288 E SMD     : DCD OFF
,03-17 13:47:52.692  1018  1050 I PowerManagerService: [PWL] Off : 1265s ago
,03-17 13:47:53.272  1018  1737 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:47:55.312   288   288 E SMD     : DCD OFF,
,03-17 13:47:58.322   288   288 E SMD     : DCD OFF,
,03-17 13:48:01.222  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:48:01.322   288   288 E SMD     : DCD OFF,
,03-17 13:48:03.332  1018  3817 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:48:04.322   288   288 E SMD     : DCD OFF
,03-17 13:48:07.332   288   288 E SMD     : DCD OFF
,03-17 13:48:10.322   288   288 E SMD     : DCD OFF
,03-17 13:48:11.282  1018  2774 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:48:13.332   288   288 E SMD     : DCD OFF
,03-17 13:48:13.392  1018  3843 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:48:16.322   288   288 E SMD     : DCD OFF
,03-17 13:48:17.592  1018  1329 E Watchdog: !@Sync 45
,03-17 13:48:19.332   288   288 E SMD     : DCD OFF
,03-17 13:48:21.312  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:48:22.332   288   288 E SMD     : DCD OFF
,03-17 13:48:23.452  1018  1305 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-17 13:48:25.332   288   288 E SMD     : DCD OFF,
,03-17 13:48:28.332   288   288 E SMD     : DCD OFF
,03-17 13:48:31.322  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:48:31.342   288   288 E SMD     : DCD OFF
,03-17 13:48:33.522  1018  1388 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:48:34.342   288   288 E SMD     : DCD OFF
,03-17 13:48:37.332   288   288 E SMD     : DCD OFF
,03-17 13:48:40.342   288   288 E SMD     : DCD OFF
,03-17 13:48:41.372  1018  2774 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:48:43.342   288   288 E SMD     : DCD OFF,
,03-17 13:48:43.582  1018  1384 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:48:46.352   288   288 E SMD     : DCD OFF
,03-17 13:48:47.582  1018  1329 E Watchdog: !@Sync 46,
,03-17 13:48:49.352   288   288 E SMD     : DCD OFF
,03-17 13:48:51.392  1018  2774 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:48:52.342   288   288 E SMD     : DCD OFF
,03-17 13:48:53.642  1018  1138 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:48:55.342   288   288 E SMD     : DCD OFF
,03-17 13:48:58.352   288   288 E SMD     : DCD OFF
,03-17 13:49:01.362   288   288 E SMD     : DCD OFF
,03-17 13:49:01.412  1018  2774 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:49:03.702  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:49:04.362   288   288 E SMD     : DCD OFF
,03-17 13:49:07.352   288   288 E SMD     : DCD OFF,
,03-17 13:49:10.352   288   288 E SMD     : DCD OFF
,03-17 13:49:11.462  1018  2774 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:49:13.352   288   288 E SMD     : DCD OFF
,03-17 13:49:13.762  1018  3818 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:49:16.352   288   288 E SMD     : DCD OFF
,03-17 13:49:17.592  1018  1329 E Watchdog: !@Sync 47
,03-17 13:49:19.362   288   288 E SMD     : DCD OFF
,03-17 13:49:21.502  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:49:22.372   288   288 E SMD     : DCD OFF
,03-17 13:49:23.822  1018  3817 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:49:25.362   288   288 E SMD     : DCD OFF
,03-17 13:49:28.362   288   288 E SMD     : DCD OFF
,03-17 13:49:31.362   288   288 E SMD     : DCD OFF
,03-17 13:49:31.532  1018  2774 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:49:33.882  1018  3843 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-17 13:49:34.372   288   288 E SMD     : DCD OFF
,03-17 13:49:37.362   288   288 E SMD     : DCD OFF
,03-17 13:49:40.372   288   288 E SMD     : DCD OFF
,03-17 13:49:41.582  1018  2774 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:49:43.382   288   288 E SMD     : DCD OFF
,03-17 13:49:43.942  1018  1305 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:49:43.942  1018  1305 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:49:43.942  1018  1305 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:49:43.942  1018  1305 D BatteryService: stay LED for fully charged
03-17 13:49:43.942  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:49:43.952  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 13:49:43.952  1018  1018 I MotionRecognitionService: Plugged
03-17 13:49:43.952  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
03-17 13:49:43.952  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false,
03-17 13:49:43.952  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 13:49:43.952  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:49:43.972  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-17 13:49:43.972  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:49:43.982  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-17 13:49:43.982  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:49:43.982  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:49:43.982  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:49:43.982  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:49:46.372   288   288 E SMD     : DCD OFF
,03-17 13:49:47.592  1018  1329 E Watchdog: !@Sync 48
,03-17 13:49:47.702  1018  1050 I PowerManagerService: [PWL] Off : 1380s ago
,03-17 13:49:49.372   288   288 E SMD     : DCD OFF
,03-17 13:49:51.622  1018  2774 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:49:52.382   288   288 E SMD     : DCD OFF,
,03-17 13:49:54.012  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:49:55.372   288   288 E SMD     : DCD OFF,
,03-17 13:49:58.382   288   288 E SMD     : DCD OFF
,03-17 13:50:01.382   288   288 E SMD     : DCD OFF
,03-17 13:50:01.652  1018  2774 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:50:04.072  1018  3818 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:50:04.392   288   288 E SMD     : DCD OFF
,03-17 13:50:07.382   288   288 E SMD     : DCD OFF
,03-17 13:50:10.392   288   288 E SMD     : DCD OFF
,03-17 13:50:11.702  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:50:13.392   288   288 E SMD     : DCD OFF
,03-17 13:50:14.142  1018  3817 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-17 13:50:16.392   288   288 E SMD     : DCD OFF
,03-17 13:50:17.582  1018  1329 E Watchdog: !@Sync 49
,03-17 13:50:19.392   288   288 E SMD     : DCD OFF
,03-17 13:50:21.752  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:50:22.392   288   288 E SMD     : DCD OFF,
,03-17 13:50:24.202  1018  3843 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:50:25.392   288   288 E SMD     : DCD OFF
,03-17 13:50:28.402   288   288 E SMD     : DCD OFF
,03-17 13:50:31.402   288   288 E SMD     : DCD OFF
,03-17 13:50:31.772  1018  2774 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:50:34.262  1018  1305 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:50:34.402   288   288 E SMD     : DCD OFF,
,03-17 13:50:37.402   288   288 E SMD     : DCD OFF
,03-17 13:50:40.412   288   288 E SMD     : DCD OFF
,03-17 13:50:41.822  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:50:43.412   288   288 E SMD     : DCD OFF
,03-17 13:50:44.322  1018  1388 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:50:44.562  1018  1087 D TimaService: TIMA: TimaService scheduler is intialized. 
,03-17 13:50:44.562  1018  1087 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
03-17 13:50:44.562  1018  1086 D TimaService: TimaServiceHandler.handleMessage what =1
,03-17 13:50:46.412   288   288 E SMD     : DCD OFF
,03-17 13:50:46.502  1018  1087 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,03-17 13:50:46.502  1018  1087 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-17 13:50:46.522  1018  1087 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-17 13:50:46.522  1018  1087 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-17 13:50:47.592  1018  1329 E Watchdog: !@Sync 50
,03-17 13:50:49.412   288   288 E SMD     : DCD OFF
,03-17 13:50:51.862  1018  2774 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:50:52.412   288   288 E SMD     : DCD OFF
,03-17 13:50:54.382  1018  1384 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:50:55.402   288   288 E SMD     : DCD OFF
,03-17 13:50:58.412   288   288 E SMD     : DCD OFF
,03-17 13:51:01.422   288   288 E SMD     : DCD OFF
,03-17 13:51:01.882  1018  2774 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:51:04.422   288   288 E SMD     : DCD OFF
,03-17 13:51:04.452  1018  1138 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:51:07.422   288   288 E SMD     : DCD OFF
,03-17 13:51:10.412   288   288 E SMD     : DCD OFF
,03-17 13:51:11.942  1018  2774 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:51:13.422   288   288 E SMD     : DCD OFF
,03-17 13:51:14.512  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:51:16.422   288   288 E SMD     : DCD OFF
,03-17 13:51:17.602  1018  1329 E Watchdog: !@Sync 51
,03-17 13:51:19.432   288   288 E SMD     : DCD OFF
,03-17 13:51:21.992  1018  2774 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:51:22.432   288   288 E SMD     : DCD OFF
,03-17 13:51:24.572  1018  3818 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:51:25.422   288   288 E SMD     : DCD OFF
,03-17 13:51:28.422   288   288 E SMD     : DCD OFF,
,03-17 13:51:31.432   288   288 E SMD     : DCD OFF
,03-17 13:51:32.022  1018  2774 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:51:32.992  1018  1096 V AlarmManager: waitForAlarm result :4
,03-17 13:51:32.992  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-17 13:51:32.992  1172  1172 D KeyguardUpdateMonitor: handleTimeUpdate
,03-17 13:51:33.002  1172  1172 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
03-17 13:51:33.002  1172  1172 D SecKeyguardClockView: HomeTimezone(): 1
,03-17 13:51:33.012  1172  1172 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
03-17 13:51:33.012  1172  1172 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
03-17 13:51:33.012  1172  1172 I KeyguardEffectViewController: *** don't update sliding image ***
,03-17 13:51:33.042  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:51:33.042  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:51:33.052  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:51:33.062  1172  1172 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,03-17 13:51:33.072  1172  1172 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:51:34.422   288   288 E SMD     : DCD OFF
,03-17 13:51:34.632  1018  1541 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:51:34.642  1018  1541 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:51:34.642  1018  1541 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,03-17 13:51:34.642  1018  1541 D BatteryService: stay LED for fully charged
03-17 13:51:34.642  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:51:34.642  1018  1018 I MotionRecognitionService: Plugged
,03-17 13:51:34.642  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:51:34.642  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 13:51:34.642  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:51:34.652  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-17 13:51:34.652  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:51:34.662  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:51:34.662  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:51:34.672  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:51:34.672  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:51:34.672  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:51:34.672  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-17 13:51:34.672  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:51:37.432   288   288 E SMD     : DCD OFF,
,03-17 13:51:40.442   288   288 E SMD     : DCD OFF,
,03-17 13:51:42.042  1018  2774 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:51:43.442   288   288 E SMD     : DCD OFF
,03-17 13:51:44.702  1018  1737 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-17 13:51:44.702  1018  1737 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:51:44.702  1018  1737 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:51:44.702  1018  1737 D BatteryService: stay LED for fully charged
03-17 13:51:44.702  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:51:44.702  1018  1018 I MotionRecognitionService: Plugged
03-17 13:51:44.702  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-17 13:51:44.702  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
03-17 13:51:44.702  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:51:44.702  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 13:51:44.702  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:51:44.712  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-17 13:51:44.712  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:51:44.732  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:51:44.732  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:51:44.732  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:51:44.732  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:51:44.732  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:51:46.442   288   288 E SMD     : DCD OFF
,03-17 13:51:47.602  1018  1329 E Watchdog: !@Sync 52
,03-17 13:51:47.712  1018  1050 I PowerManagerService: [PWL] Off : 1500s ago,
,03-17 13:51:49.442   288   288 E SMD     : DCD OFF
,03-17 13:51:52.092  1018  2774 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:51:52.442   288   288 E SMD     : DCD OFF,
,03-17 13:51:54.762  1018  3819 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:51:55.452   288   288 E SMD     : DCD OFF
,03-17 13:51:58.442   288   288 E SMD     : DCD OFF
,03-17 13:51:59.992  1018  1096 V AlarmManager: waitForAlarm result :8,
,03-17 13:52:01.452   288   288 E SMD     : DCD OFF
,03-17 13:52:02.112  1018  2774 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:52:03.512  1018  1096 V AlarmManager: waitForAlarm result :4
,03-17 13:52:03.522  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-17 13:52:03.522  1172  1172 D KeyguardUpdateMonitor: handleTimeUpdate
,03-17 13:52:03.532  1172  1172 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-17 13:52:03.532  1172  1172 D SecKeyguardClockView: HomeTimezone(): 1
,03-17 13:52:03.542  1172  1172 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:52:03.542  1172  1172 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
03-17 13:52:03.542  1172  1172 I KeyguardEffectViewController: *** don't update sliding image ***
,03-17 13:52:03.562  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:52:03.562  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:52:03.572  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:52:03.592  1172  1172 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,03-17 13:52:03.602  1172  1172 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:52:04.452   288   288 E SMD     : DCD OFF
,03-17 13:52:04.822  1018  1541 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:52:07.442   288   288 E SMD     : DCD OFF,
,03-17 13:52:10.442   288   288 E SMD     : DCD OFF
,03-17 13:52:12.162  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:52:13.452   288   288 E SMD     : DCD OFF
,03-17 13:52:14.882  1018  1740 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:52:16.462   288   288 E SMD     : DCD OFF
,03-17 13:52:17.602  1018  1329 E Watchdog: !@Sync 53
,03-17 13:52:19.462   288   288 E SMD     : DCD OFF
,03-17 13:52:22.212  1018  2774 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:52:22.462   288   288 E SMD     : DCD OFF,
,03-17 13:52:24.942  1018  3818 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:52:25.462   288   288 E SMD     : DCD OFF,
,03-17 13:52:28.462   288   288 E SMD     : DCD OFF
,03-17 13:52:31.472   288   288 E SMD     : DCD OFF
,03-17 13:52:32.242  1018  2774 D SSRM:n  : SIOP:: AP = 260
,03-17 13:52:34.472   288   288 E SMD     : DCD OFF
,TIME-OUT KILL (timeout was 1400000ms),03-17 13:52:34.942  6780  6780 D AndroidRuntime: 
03-17 13:52:34.942  6780  6780 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-17 13:52:34.942  6780  6780 D AndroidRuntime: CheckJNI is OFF
03-17 13:52:34.942  6780  6780 D AndroidRuntime: readGMSProperty: start
03-17 13:52:34.942  6780  6780 D AndroidRuntime: readGMSProperty: already setted!!
03-17 13:52:34.942  6780  6780 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-17 13:52:34.942  6780  6780 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-17 13:52:34.942  6780  6780 D AndroidRuntime: readGMSProperty: end
03-17 13:52:34.942  6780  6780 D AndroidRuntime: addProductProperty: start
03-17 13:52:35.002  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-17 13:52:35.002  1018  1030 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:52:35.002  1018  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:52:35.002  1018  1030 D BatteryService: stay LED for fully charged
03-17 13:52:35.002  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-17 13:52:35.012  1018  1018 I MotionRecognitionService: Plugged
03-17 13:52:35.012  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
03-17 13:52:35.012  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-17 13:52:35.012  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
03-17 13:52:35.012  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 13:52:35.012  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-17 13:52:35.022  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-17 13:52:35.022  2663  2768 D HeadsetStateMachine: Disconnected process message: 10
03-17 13:52:35.032  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:52:35.032  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:52:35.032  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:52:35.032  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:52:35.032  1172  1172 D SViewCoverView: level :100 plugged : 2
03-17 13:52:35.072  6780  6780 E AffinityControl: AffinityControl: registerfunction enter
03-17 13:52:35.102  6780  6780 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
03-17 13:52:35.112  1018  1740 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
03-17 13:52:35.112  1018  1740 D PackageManager: START PACKAGE DELETE: observer{830395587}
03-17 13:52:35.112  1018  1740 D PackageManager: pkg{<packageName>}
03-17 13:52:35.112  1018  1740 D PackageManager: user{0}
03-17 13:52:35.112  1018  1740 D PackageManager: caller{2000}
03-17 13:52:35.112  1018  1740 D PackageManager: flags{2}
03-17 13:52:35.112  1018  1740 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
03-17 13:52:35.122  1018  1056 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
03-17 13:52:35.112  1018  1740 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
03-17 13:52:35.112  1018  1740 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-17 13:52:35.112  1018  1740 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-17 13:52:35.122  1018  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
03-17 13:52:35.122  1018  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
03-17 13:52:35.122  1018  1056 D ApplicationPolicy: getApplicationUninstallationEnabled
03-17 13:52:35.122  1018  1056 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
03-17 13:52:35.122  1018  1056 D PackageManager: !@killApplicatoin: 10167, uninstall pkg
03-17 13:52:35.122  1018  1043 I ActivityManager: Force stopping com.test.thalitest appid=10167 user=-1: uninstall pkg
03-17 13:52:35.122  1018  1043 I ActivityManager: Killing 6112:com.test.thalitest/u0a167 (adj 15): stop com.test.thalitest cause uninstall pkg
03-17 13:52:35.212  1018  1056 W PackageSettings: Skipping PackageSetting{3f6a3540 com.example.hello/10346} due to missing metadata
03-17 13:52:35.262  1018  1056 I ActivityManager: Force stopping com.test.thalitest appid=10167 user=0: pkg removed
03-17 13:52:35.272  1018  1056 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
03-17 13:52:35.322  4011  4011 I art     : Explicit concurrent mark sweep GC freed 2537(152KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 1.061ms total 47.642ms
03-17 13:52:35.332  5933  5933 I art     : Explicit concurrent mark sweep GC freed 400(27KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/8MB, paused 883us total 57.320ms
03-17 13:52:35.352  1018  1099 I InputReader: Reconfiguring input devices.  changes=0x00000010
03-17 13:52:35.372  1680  2012 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
03-17 13:52:35.372  1473  1473 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-17 13:52:35.382  1892  1892 E SamsungIME: mOCRHelper is null
03-17 13:52:35.402  3695  3695 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Mar 17 13:52:35 GMT+01:00 2016
03-17 13:52:35.412  1018  1740 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:52:35.412  1018  1740 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:52:35.412  1018  1740 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
03-17 13:52:35.422  1018  1123 V NetworkStats: removeUidsLocked() for UIDs [10167]
03-17 13:52:35.422  1018  1123 D NtpTrustedTime: currentTimeMillis() cache hit
03-17 13:52:35.422  1018  1123 V NetworkStats: performPollLocked(flags=0x3)
03-17 13:52:35.422  1018  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
03-17 13:52:35.432  1018  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
03-17 13:52:35.432  3695  3695 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
03-17 13:52:35.432  1018  1042 D EnterpriseDeviceManagerService: Package has changed for user 0
03-17 13:52:35.432  1018  1042 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
03-17 13:52:35.432  1018  1042 W TextServicesManagerService: no available spell checker services found
03-17 13:52:35.442  1018  1123 V NetworkStats: performPollLocked() took 15ms
03-17 13:52:35.442  1018  1123 D NtpTrustedTime: currentTimeMillis() cache hit
03-17 13:52:35.442  1018  3819 I splitIntent: intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
03-17 13:52:35.442  1018  3819 I splitIntent: base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
03-17 13:52:35.442  1018  3819 I splitIntent: other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
03-17 13:52:35.442  1018  3819 I splitIntent: arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
03-17 13:52:35.442  1018  3819 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:52:35.442  1018  3819 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:52:35.442  1018  3819 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:52:35.442  1018  3819 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:52:35.452  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 13:52:35.462  6793  6793 E Zygote  : MountEmulatedStorage()
03-17 13:52:35.462  6793  6793 E Zygote  : v2
03-17 13:52:35.462  6793  6793 I libpersona: KNOX_SDCARD checking this for 10090
03-17 13:52:35.462  6793  6793 I libpersona: KNOX_SDCARD not a persona
03-17 13:52:35.462  6793  6793 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 13:52:35.462  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 13:52:35.462  6793  6793 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 13:52:35.462  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 13:52:35.472  6793  6793 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:52:35.472  1018  1128 D NtpTrustedTime: currentTimeMillis() cache hit
03-17 13:52:35.472  1018  3819 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6793 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
03-17 13:52:35.472  1018  1128 D NtpTrustedTime: currentTimeMillis() cache hit
03-17 13:52:35.472  3695  3695 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
03-17 13:52:35.482  3695  3695 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
03-17 13:52:35.492  3695  3695 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
03-17 13:52:35.492  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 13:52:35.502  3695  6792 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
03-17 13:52:35.502  3695  6792 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
03-17 13:52:35.502  1018  3818 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
03-17 13:52:35.502  1018  3818 D SecContentProvider2: mCursor = null
03-17 13:52:35.512  6793  6793 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:52:35.512  6793  6793 D ActivityThread: Added TimaKeyStore provider
03-17 13:52:35.512  3695  6792 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
03-17 13:52:35.522  3695  6792 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
03-17 13:52:35.552  1457  1457 D RegisteredServicesCache: empty dynamic service
03-17 13:52:35.572  6793  6793 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
03-17 13:52:35.582  6793  6793 D elm:15121: ELMEngine.ELMEngine( context ).
03-17 13:52:35.582  6793  6793 D elm:15121: MDMBridge.setEnterpriseBridge()
03-17 13:52:35.582  1018  1138 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:52:35.582  1018  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:52:35.582  1018  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
03-17 13:52:35.582  1018  1018 I art     : Explicit concurrent mark sweep GC freed 48479(5MB) AllocSpace objects, 206(3MB) LOS objects, 33% free, 24MB/36MB, paused 5.484ms total 306.408ms
03-17 13:52:35.582  6793  6793 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
03-17 13:52:35.592  6793  6793 D elm:15121: ElmAgentService : onCreate()
03-17 13:52:35.592  1018  1056 I art     : WaitForGcToComplete blocked for 179.003ms for cause Explicit
03-17 13:52:35.592  6793  6808 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
03-17 13:52:35.592  6793  6808 D elm:15121: MainReceiver.listeningToPackageRemoved()
03-17 13:52:35.592  6793  6808 D elm:15121: MDMBridge.getInstance()
03-17 13:52:35.592  6793  6808 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
03-17 13:52:35.592  6793  6808 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
03-17 13:52:35.642  6793  6793 D elm:15121: ElmAgentService : onDestroy().
03-17 13:52:35.642  3695  6792 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
03-17 13:52:35.662  3695  6792 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
03-17 13:52:35.662  3695  6792 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
03-17 13:52:35.662  3695  3695 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
03-17 13:52:35.722  1018  1042 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
03-17 13:52:35.732  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 13:52:35.732  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 13:52:35.742  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 13:52:35.752  1018  1042 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 13:52:35.752  1018  1042 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 13:52:35.752  1018  1042 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 13:52:35.752  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 13:52:35.762  1018  1018 D RCPManagerService: PackageReceiver onReceive()
03-17 13:52:35.772  1018  1018 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
03-17 13:52:35.772  1018  1018 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
03-17 13:52:35.772  1018  1056 I art     : Explicit concurrent mark sweep GC freed 10978(509KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 3.055ms total 182.441ms
03-17 13:52:35.812  1018  1056 D PackageManager: delete codoeFile: 
03-17 13:52:35.812  1018  1056 D AASAuninstall: userId = 0, info.removedAppID = 10167, info.uid = 10167, packageName = com.test.thalitest
03-17 13:52:35.812  1018  1056 I AASA_removePackage: UID=10167 Target=com.test.thalitest
03-17 13:52:35.812  1018  1056 D PackageManager: result of delete: 1{830395587}
03-17 13:52:35.822  6780  6780 D AndroidRuntime: Shutting down VM
03-17 13:52:35.822  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 13:52:35.822  1018  1056 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
03-17 13:52:35.822  1018  1056 D PackageManager: userId{-1}
03-17 13:52:35.822  1018  1056 D PackageManager: andCode{true}
03-17 13:52:35.822  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 13:52:35.832  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 13:52:35.832  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
03-17 13:52:35.832  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 13:52:35.842  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 13:52:35.842  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
03-17 13:52:35.842  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 13:52:35.842  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
03-17 13:52:35.842  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 13:52:35.852  1018  1042 D UsbSettingsManager: clearDefaults: com.test.thalitest
03-17 13:52:35.852  1018  1042 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
03-17 13:52:35.872  1018  1018 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-17 13:52:35.872  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
03-17 13:52:35.872  1018  1018 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-17 13:52:35.872  1018  1018 V EnterpriseBillingPolicy: uID is 10167
03-17 13:52:35.872  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
03-17 13:52:35.872  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
03-17 13:52:35.872  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-17 13:52:35.872  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-17 13:52:35.872  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-17 13:52:35.872  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
03-17 13:52:35.872  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
03-17 13:52:35.872  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 13:52:35.882  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
03-17 13:52:35.882  1018  1018 V EnterpriseBillingPolicy: uID is 10167
03-17 13:52:35.882  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
03-17 13:52:35.882  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
03-17 13:52:35.882  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-17 13:52:35.882  1018  2774 D SSRM:aZ : MSG_TYPE_APP_REMOVED::
03-17 13:52:35.882  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-17 13:52:35.882  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-17 13:52:35.882  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
03-17 13:52:35.882  1018  1160 D TaskPersister: removeObsoleteFile: deleting file=23_task.xml
03-17 13:52:35.882  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
03-17 13:52:35.892  5634  5634 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-17 13:52:35.892  5634  5634 I PCWCLIENTTRACE_PushUtil: sales region : global
03-17 13:52:35.892  5634  5634 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-17 13:52:35.892  5634  5634 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
03-17 13:52:35.912  5731  5731 I SA      : [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
03-17 13:52:35.912  5731  5731 I SA      : [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10167 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
03-17 13:52:35.912  1018  1138 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:52:35.912  1018  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:52:35.912  1018  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
03-17 13:52:35.932  4998  4998 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
03-17 13:52:35.952  5603  5603 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
03-17 13:52:35.962  1018  3843 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:52:35.962  1018  3843 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:52:35.962  1018  3843 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
03-17 13:52:35.962  1018  1737 I TactileAssist: enable value -1
03-17 13:52:35.972  1018  1737 I TactileAssist: internal enable value -1
03-17 13:52:35.972  1018  1737 I TactileAssist: intensity value -1
03-17 13:52:35.972  1018  1737 I TactileAssist: saveAppList value true
03-17 13:52:35.972  1018  1737 I TactileAssist: List of disabled apps :
03-17 13:52:35.982  5603  6812 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
03-17 13:52:35.982  5603  6812 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
03-17 13:52:36.002  5825  5825 D Compatibility: onReceive() it will make start service
03-17 13:52:36.002  1018  1512 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:52:36.002  1018  1512 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:52:36.012  1018  1512 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
03-17 13:52:36.012  1018  3843 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:52:36.012  1018  3843 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:52:36.012  1018  3843 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:52:36.012  1018  3843 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:52:36.012  5825  6813 D Compatibility: onHandleIntent()
03-17 13:52:36.012  5825  6813 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10167, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
03-17 13:52:36.022  5825  6813 D Compatibility: found: 2
03-17 13:52:36.022  5825  6813 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
03-17 13:52:36.022  5825  6813 D Compatibility: skipping ResolveInfo{2bc3cae0 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
03-17 13:52:36.022  5825  6813 D Compatibility: considering ResolveInfo{136dd199 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
03-17 13:52:36.022  5825  6813 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
03-17 13:52:36.022  5825  6813 D Compatibility: enabling receiver ResolveInfo{30f50c5e com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
03-17 13:52:36.022  5825  6813 D Compatibility: enabling receiver ResolveInfo{30cf183f com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
03-17 13:52:36.022  6814  6814 E Zygote  : MountEmulatedStorage()
03-17 13:52:36.022  6814  6814 E Zygote  : v2
03-17 13:52:36.022  6814  6814 I libpersona: KNOX_SDCARD checking this for 10055
03-17 13:52:36.022  6814  6814 I libpersona: KNOX_SDCARD not a persona
03-17 13:52:36.022  6814  6814 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 13:52:36.022  1018  3843 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6814 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
03-17 13:52:36.032  6814  6814 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 13:52:36.032  6780  6780 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
03-17 13:52:36.032  6814  6814 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:52:36.032  1018  1138 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:52:36.032  1018  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:52:36.032  1018  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
03-17 13:52:36.042  5825  6813 D Compatibility: enabling receiver ResolveInfo{214ab50c com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
03-17 13:52:36.042  5825  6813 D Compatibility: enabling receiver ResolveInfo{340ee55 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
03-17 13:52:36.052  5825  6813 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
03-17 13:52:36.052   306   306 I art     : Explicit concurrent mark sweep GC freed 8698(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 683us total 26.835ms
03-17 13:52:36.062  6814  6814 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:52:36.062  6814  6814 D ActivityThread: Added TimaKeyStore provider
03-17 13:52:36.072   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 16.758ms
03-17 13:52:36.092  6814  6814 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
03-17 13:52:36.092   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 568us total 18.380ms
03-17 13:52:36.122  6814  6814 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
03-17 13:52:36.122  6814  6814 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
03-17 13:52:36.122  6814  6814 D UserAnalysis: Create SecureDbHelper
03-17 13:52:36.122  6814  6814 D IntelligenceServiceApplication: onCreate()
03-17 13:52:36.122  6814  6814 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
03-17 13:52:36.132  6814  6814 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
03-17 13:52:36.132  5846  5846 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
03-17 13:52:36.132  6814  6814 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
03-17 13:52:36.132  6814  6814 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 13:52:36.132  6814  6814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 13:52:36.132  6814  6814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 13:52:36.132  6814  6814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 13:52:36.132  6814  6814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 13:52:36.132  6814  6814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 13:52:36.132  6814  6814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 13:52:36.132  6814  6814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 13:52:36.132  6814  6814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 13:52:36.132  6814  6814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 13:52:36.132  6814  6814 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 13:52:36.132  6814  6814 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 13:52:36.132  6814  6814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 13:52:36.132  6814  6814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-17 13:52:36.132  6814  6814 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:69)
03-17 13:52:36.132  6814  6814 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.IntelligenceServiceApplication$1.run(IntelligenceServiceApplication.java:46)
03-17 13:52:36.132  6814  6814 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-17 13:52:36.132  6814  6814 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-17 13:52:36.132  6814  6814 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-17 13:52:36.132  6814  6814 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 13:52:36.132  6814  6814 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 13:52:36.132  6814  6814 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 13:52:36.132  6814  6814 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 13:52:36.132  6814  6814 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 13:52:36.132  6814  6814 E SQLiteOpenHelper: Couldn't open privacy for writing (will try read-only):
03-17 13:52:36.132  6814  6814 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 13:52:36.132  6814  6814 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 13:52:36.132  6814  6814 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 13:52:36.132  6814  6814 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 13:52:36.132  6814  6814 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 13:52:36.132  6814  6814 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 13:52:36.132  6814  6814 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 13:52:36.132  6814  6814 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 13:52:36.132  6814  6814 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 13:52:36.132  6814  6814 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 13:52:36.132  6814  6814 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 13:52:36.132  6814  6814 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 13:52:36.132  6814  6814 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 13:52:36.132  6814  6814 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-17 13:52:36.132  6814  6814 E SQLiteOpenHelper: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:69)
03-17 13:52:36.132  6814  6814 E SQLiteOpenHelper: 	at com.samsung.android.intelligenceservice.IntelligenceServiceApplication$1.run(IntelligenceServiceApplication.java:46)
03-17 13:52:36.132  6814  6814 E SQLiteOpenHelper: 	at android.os.Handler.handleCallback(Handler.java:739)
03-17 13:52:36.132  6814  6814 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-17 13:52:36.132  6814  6814 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
03-17 13:52:36.132  6814  6814 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 13:52:36.132  6814  6814 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 13:52:36.132  6814  6814 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 13:52:36.132  6814  6814 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 13:52:36.132  6814  6814 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 13:52:36.142  6814  6814 W SQLiteOpenHelper: Opened privacy in read-only mode
03-17 13:52:36.142  6814  6814 D IntelligenceServiceApplication: no applications having user consent for prediction
03-17 13:52:36.142  1018  3843 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:52:36.142  1018  3843 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:52:36.142  1018  3843 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
03-17 13:52:36.142  6814  6814 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
03-17 13:52:36.152  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:52:36.152  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:52:36.152  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:52:36.152  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:52:36.152  6814  6814 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
03-17 13:52:36.152  6814  6814 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
03-17 13:52:36.152  5846  6832 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
03-17 13:52:36.162  6833  6833 E Zygote  : MountEmulatedStorage()
03-17 13:52:36.162  6833  6833 E Zygote  : v2
03-17 13:52:36.162  6833  6833 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:52:36.162  6833  6833 I libpersona: KNOX_SDCARD not a persona
03-17 13:52:36.162  5846  6832 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
03-17 13:52:36.162  5846  6832 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 13:52:36.162  5846  6832 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 13:52:36.162  5846  6832 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 13:52:36.162  5846  6832 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 13:52:36.162  5846  6832 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 13:52:36.162  5846  6832 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 13:52:36.162  5846  6832 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 13:52:36.162  5846  6832 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 13:52:36.162  5846  6832 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 13:52:36.162  5846  6832 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 13:52:36.162  5846  6832 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 13:52:36.162  5846  6832 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 13:52:36.162  5846  6832 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 13:52:36.162  5846  6832 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 13:52:36.162  5846  6832 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
03-17 13:52:36.162  5846  6832 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
03-17 13:52:36.162  5846  6832 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 13:52:36.162  5846  6832 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 13:52:36.162  5846  6832 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-17 13:52:36.162  5846  6832 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-17 13:52:36.162  1018  1031 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6833 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 13:52:36.162  5846  6832 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 13:52:36.172  1018  1512 I ActivityManager: Killing 5266:com.google.android.partnersetup/u0a14 (adj 15): empty #31
03-17 13:52:36.162  5846  6832 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 13:52:36.162  5846  6832 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 13:52:36.162  5846  6832 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 13:52:36.162  5846  6832 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 13:52:36.162  5846  6832 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 13:52:36.162  5846  6832 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 13:52:36.162  5846  6832 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 13:52:36.162  5846  6832 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 13:52:36.162  5846  6832 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 13:52:36.162  5846  6832 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 13:52:36.162  5846  6832 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 13:52:36.162  5846  6832 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 13:52:36.162  5846  6832 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 13:52:36.162  5846  6832 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
03-17 13:52:36.162  5846  6832 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
03-17 13:52:36.162  5846  6832 W System.err: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 13:52:36.162  5846  6832 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 13:52:36.162  5846  6832 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-17 13:52:36.162  5846  6832 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-17 13:52:36.172  6833  6833 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 13:52:36.172  6833  6833 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 13:52:36.172  6833  6833 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:52:36.182  6814  6814 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
03-17 13:52:36.182  6814  6814 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 13:52:36.182  6814  6814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 13:52:36.182  6814  6814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 13:52:36.182  6814  6814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 13:52:36.182  6814  6814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 13:52:36.182  6814  6814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 13:52:36.182  6814  6814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 13:52:36.182  6814  6814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 13:52:36.182  6814  6814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 13:52:36.182  6814  6814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 13:52:36.182  6814  6814 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 13:52:36.182  6814  6814 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 13:52:36.182  6814  6814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 13:52:36.182  6814  6814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 13:52:36.182  6814  6814 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:204)
03-17 13:52:36.182  6814  6814 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:78)
03-17 13:52:36.182  6814  6814 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-17 13:52:36.182  6814  6814 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-17 13:52:36.182  6814  6814 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-17 13:52:36.182  6814  6814 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 13:52:36.182  6814  6814 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 13:52:36.182  6814  6814 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 13:52:36.182  6814  6814 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 13:52:36.182  6814  6814 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 13:52:36.182  6814  6814 D AndroidRuntime: Shutting down VM
03-17 13:52:36.182  6814  6814 E AndroidRuntime: FATAL EXCEPTION: main
03-17 13:52:36.182  6814  6814 E AndroidRuntime: Process: com.samsung.android.intelligenceservice, PID: 6814
03-17 13:52:36.182  6814  6814 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 13:52:36.182  6814  6814 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 13:52:36.182  6814  6814 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 13:52:36.182  6814  6814 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 13:52:36.182  6814  6814 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 13:52:36.182  6814  6814 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 13:52:36.182  6814  6814 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 13:52:36.182  6814  6814 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 13:52:36.182  6814  6814 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 13:52:36.182  6814  6814 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 13:52:36.182  6814  6814 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 13:52:36.182  6814  6814 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 13:52:36.182  6814  6814 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 13:52:36.182  6814  6814 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 13:52:36.182  6814  6814 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:204)
03-17 13:52:36.182  6814  6814 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:78)
03-17 13:52:36.182  6814  6814 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
03-17 13:52:36.182  6814  6814 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-17 13:52:36.182  6814  6814 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
03-17 13:52:36.182  6814  6814 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 13:52:36.182  6814  6814 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 13:52:36.182  6814  6814 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 13:52:36.182  6814  6814 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 13:52:36.182  6814  6814 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 13:52:36.192  1018  1384 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.intelligenceservice
03-17 13:52:36.192  6833  6833 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:52:36.192  6833  6833 D ActivityThread: Added TimaKeyStore provider
03-17 13:52:36.202  1018  6847 E DropBoxManagerService: Can't write: system_app_crash
03-17 13:52:36.202  1018  6847 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop174.tmp: open failed: EROFS (Read-only file system)
03-17 13:52:36.202  1018  6847 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-17 13:52:36.202  1018  6847 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-17 13:52:36.202  1018  6847 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-17 13:52:36.202  1018  6847 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-17 13:52:36.202  1018  6847 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-17 13:52:36.202  1018  6847 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:15884)
03-17 13:52:36.202  1018  6847 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-17 13:52:36.202  1018  6847 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-17 13:52:36.202  1018  6847 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-17 13:52:36.202  1018  6847 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-17 13:52:36.202  1018  6847 E DropBoxManagerService: 	... 5 more

```
