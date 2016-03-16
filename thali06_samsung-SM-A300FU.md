#### Test 62509094c147163_thali06_samsung-SM-A300FU Logs


```
--------- beginning of system,
03-16 08:37:10.202  1019  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-16 08:37:10.202  1019  1479 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
--------- beginning of main
03-16 08:37:10.212  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-16 08:37:10.202  1019  1479 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 08:37:10.212  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
03-16 08:37:10.202  1019  1479 D BatteryService: stay LED for fully charged
03-16 08:37:10.202  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-16 08:37:10.212  1019  1019 I MotionRecognitionService: Plugged
03-16 08:37:10.212  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
03-16 08:37:10.212  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 08:37:10.212  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-16 08:37:10.222  2637  2637 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-16 08:37:10.232  2637  2731 D HeadsetStateMachine: Disconnected process message: 10
03-16 08:37:10.242  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 08:37:10.242  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 08:37:10.242  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 08:37:10.242  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 08:37:10.242  1180  1180 D SViewCoverView: level :100 plugged : 2
03-16 08:37:10.302  1019  2762 D SSRM:n  : SIOP:: AP = 260
03-16 08:37:10.482  6170  6170 D AndroidRuntime: 
03-16 08:37:10.482  6170  6170 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-16 08:37:10.482  6170  6170 D AndroidRuntime: CheckJNI is OFF
03-16 08:37:10.482  6170  6170 D AndroidRuntime: readGMSProperty: start
03-16 08:37:10.482  6170  6170 D AndroidRuntime: readGMSProperty: already setted!!
03-16 08:37:10.482  6170  6170 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-16 08:37:10.482  6170  6170 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-16 08:37:10.482  6170  6170 D AndroidRuntime: readGMSProperty: end
03-16 08:37:10.482  6170  6170 D AndroidRuntime: addProductProperty: start
03-16 08:37:10.642  6170  6170 E AffinityControl: AffinityControl: registerfunction enter
03-16 08:37:10.662  6170  6170 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-16 08:37:10.682  1019  1514 E PersonaManagerService: inState():  stateMachine is null !!
03-16 08:37:10.682  1019  1514 I PersonaManagerService: PersonaId don't exist
03-16 08:37:10.682  1019  1514 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-16 08:37:10.682  1019  1514 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-16 08:37:10.712  1019  1514 W ActivityManager: mDVFSHelper.acquire()
03-16 08:37:10.712  1019  1514 D FocusedStackFrame: Set to : 0
03-16 08:37:10.722  1019  1049 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-16 08:37:10.722  1019  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 08:37:10.722  1019  1049 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-16 08:37:10.722  1019  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 08:37:10.722  1019  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 08:37:10.722  1019  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 08:37:10.742  1019  1514 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6183 uid=10167 gids={50167, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-16 08:37:10.742  1019  1514 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-16 08:37:10.742  1019  1514 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-16 08:37:10.742  1019  1514 D InputDispatcher: Focused application set to: xxxx
03-16 08:37:10.742  1019  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-16 08:37:10.742  1019  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-16 08:37:10.742  1019  1514 D InputDispatcher: Focus left window: 1481
03-16 08:37:10.742   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
03-16 08:37:10.742  6170  6170 D AndroidRuntime: Shutting down VM
03-16 08:37:10.742  6183  6183 E Zygote  : MountEmulatedStorage()
03-16 08:37:10.742  6183  6183 I libpersona: KNOX_SDCARD checking this for 10167
03-16 08:37:10.742  6183  6183 E Zygote  : v2
03-16 08:37:10.742  6183  6183 I libpersona: KNOX_SDCARD not a persona
03-16 08:37:10.742  6183  6183 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 08:37:10.742  6183  6183 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 08:37:10.752  6183  6183 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-16 08:37:10.762  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-16 08:37:10.762  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
03-16 08:37:10.762  6183  6183 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 08:37:10.762  6183  6183 D ActivityThread: Added TimaKeyStore provider
03-16 08:37:10.772  1019  1496 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-16 08:37:10.772  1019  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-16 08:37:10.782   293   293 E SMD     : DCD OFF
03-16 08:37:10.782  1019  1496 D PersonaManager: isKioskContainerExistOnDevice
03-16 08:37:10.792  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
03-16 08:37:10.822   257  1866 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
03-16 08:37:10.822   257   445 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
03-16 08:37:10.822  1481  1481 V ActivityThread: updateVisibility : ActivityRecord{3465e6c2 token=android.os.BinderProxy@a057d8f {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-16 08:37:10.832  1481  1481 D Launcher: onTrimMemory. Level: 20
03-16 08:37:10.922  6183  6183 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
03-16 08:37:10.932  6183  6183 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 7512-7513)
03-16 08:37:10.932  6183  6183 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-16 08:37:10.952  6170  6170 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,03-16 08:37:10.962  6183  6183 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {30a7f57}
,03-16 08:37:10.962  6183  6183 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-16 08:37:10.962  6183  6183 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-16 08:37:10.992  6183  6183 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-16 08:37:10.992  6183  6183 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 08:37:10.992  6183  6183 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-16 08:37:11.012  6183  6183 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-16 08:37:11.012  6183  6183 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-16 08:37:11.012  6183  6183 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-16 08:37:11.012  6183  6183 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-16 08:37:11.012  6183  6183 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-16 08:37:11.012  6183  6183 I Adreno-EGL: Build Date: 04/06/15 Mon
03-16 08:37:11.012  6183  6183 I Adreno-EGL: Local Branch: 
03-16 08:37:11.012  6183  6183 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-16 08:37:11.012  6183  6183 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-16 08:37:11.012  6183  6183 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-16 08:37:11.242  6183  6183 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 08:37:11.252  6183  6183 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-16 08:37:11.262  6183  6183 D PhoneWindow: *FMB* installDecor mIsFloating : false
,03-16 08:37:11.262  6183  6183 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-16 08:37:11.262  6183  6183 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-16 08:37:11.272  6183  6183 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 08:37:11.272  6183  6183 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 08:37:11.282  1019  1044 W ActivityManager: Activity pause timeout for ActivityRecord{2ea7bd5e u0 com.test.thalitest/.MainActivity t23}
,03-16 08:37:11.332  6183  6224 D OpenGLRenderer: Render dirty regions requested: true
,03-16 08:37:11.332  1019  1496 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,03-16 08:37:11.332  1019  1496 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-16 08:37:11.332  1019  1496 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-16 08:37:11.342  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-16 08:37:11.342  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
,03-16 08:37:11.342  6183  6211 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-16 08:37:11.342  6183  6183 V ActivityThread: updateVisibility : ActivityRecord{8c1d3f token=android.os.BinderProxy@a900e99 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,03-16 08:37:11.352  6183  6183 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-16 08:37:11.352  6183  6183 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-16 08:37:11.362   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
,03-16 08:37:11.372  1019  1728 D InputDispatcher: Focus entered window: 6183
,03-16 08:37:11.372  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,03-16 08:37:11.372  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-16 08:37:11.372  6183  6183 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-16 08:37:11.372  6183  6224 I OpenGLRenderer: Initialized EGL, version 1.4
,03-16 08:37:11.382  6183  6224 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,03-16 08:37:11.382  6183  6224 D OpenGLRenderer: Enabling debug mode 0
,03-16 08:37:11.422  1019  3294 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-16 08:37:11.432  1019  6226 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 08:37:11.432  1180  1180 I StatusBar: Icon Only
,03-16 08:37:11.432  1180  1180 D PanelView: There is/are notification(s) 
,03-16 08:37:11.442  1019  1049 I ActivityManager: Displayed Component not be shown by security: +657ms (total +1m39s827ms)
,03-16 08:37:11.442  1019  1049 W ActivityManager: mDVFSHelper.release()
03-16 08:37:11.442  1019  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2ea7bd5e u0 com.test.thalitest/.MainActivity t23} time:218027
,03-16 08:37:11.452  6183  6183 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-16 08:37:11.452   257  1104 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
,03-16 08:37:11.452  6183  6183 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@a900e99 time:218033
03-16 08:37:11.452   257   452 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
03-16 08:37:11.472  1840  1840 I SamsungIME: getCurrentCandidateView
,03-16 08:37:11.502  1840  1840 D SamsungIME: Dismiss ExpandCandiate
,03-16 08:37:11.532  1840  1840 I SamsungIME: getDebugLevel  : 0x4f4c
,03-16 08:37:11.572  1840  1840 I SamsungIME: getDebugLevel  : 0x4f4c
,03-16 08:37:11.582  1840  1840 I SamsungIME: KeybaordView init() : load resources
,03-16 08:37:11.602  1840  1840 I SamsungIME: getCurrentKeyboard
03-16 08:37:11.602  1840  1840 I SamsungIME: getTextKeyboard
,03-16 08:37:11.622  1840  1840 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-16 08:37:11.662  6183  6183 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6183
,03-16 08:37:11.792  6183  6183 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-16 08:37:11.982  6183  6228 D jxcore_app_log: JniHelper::setJavaVM(0xb79ce448), pthread_self() = -1208801784
,03-16 08:37:11.992  6183  6228 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-16 08:37:11.992  6183  6228 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-16 08:37:11.992  6183  6228 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-16 08:37:11.992  6183  6228 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-16 08:37:11.992  6183  6228 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,03-16 08:37:11.992  6183  6228 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3676da3c added. We now have 1 listener(s)
,03-16 08:37:11.992  6183  6228 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,03-16 08:37:12.002  6183  6228 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:EC:A9:50:75:41"}
,03-16 08:37:12.002  6183  6228 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"08:EC:A9:50:75:41"}
03-16 08:37:12.002  6183  6228 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-16 08:37:12.002  6183  6228 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-16 08:37:12.002  6183  6228 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-16 08:37:12.002  6183  6228 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-16 08:37:12.002  6183  6228 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-16 08:37:12.002  6183  6228 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
03-16 08:37:12.002  6183  6228 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-16 08:37:12.002  6183  6228 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-16 08:37:12.002  6183  6228 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-16 08:37:12.002  6183  6228 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-16 08:37:12.002  6183  6228 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-16 08:37:12.002  6183  6228 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-16 08:37:12.002  6183  6228 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c844b added. We now have 1 listener(s)
,03-16 08:37:12.002  6183  6228 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-16 08:37:12.012  6183  6228 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-16 08:37:12.012  6183  6228 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-16 08:37:12.012  6183  6228 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-16 08:37:12.012  6183  6228 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-16 08:37:12.012  6183  6228 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-16 08:37:12.012  6183  6228 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-16 08:37:12.022  6183  6228 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
,03-16 08:37:12.022  6183  6228 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-16 08:37:12.022  6183  6228 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-16 08:37:12.022  6183  6228 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-16 08:37:12.022  6183  6228 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-16 08:37:12.022  6183  6228 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-16 08:37:12.022  6183  6228 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-16 08:37:12.022  6183  6228 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-16 08:37:12.022  6183  6228 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-16 08:37:12.022  6183  6228 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-16 08:37:12.022  6183  6228 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-16 08:37:12.022  6183  6183 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-16 08:37:12.032  6183  6183 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-16 08:37:12.062  6183  6183 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-16 08:37:13.052  6183  6234 W jxcore-log: Initializing JXcore engine
03-16 08:37:13.052  6183  6234 W jxcore-log: JXcore engine is ready
,03-16 08:37:13.112  1871  1871 E audit   : type=1400 msg=audit(1458113833.112:205): avc:  denied  { ioctl } for  pid=6234 comm="Thread-1065" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-16 08:37:13.112  1871  1871 E audit   :  SEPF_SM-A300FU_5.0.2_0027
03-16 08:37:13.112  1871  1871 E audit   : type=1300 msg=audit(1458113833.112:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=2 a3=9dbe88b8 items=0 ppid=313 ppcomm=main pid=6234 auid=4294967295 uid=10167 gid=10167 euid=10167 suid=10167 fsuid=10167 egid=10167 sgid=10167 fsgid=10167 ses=4294967295 tty=(none) comm="Thread-1065" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-16 08:37:13.112  1871  1871 E audit   : type=1320 msg=audit(1458113833.112:205): 
,03-16 08:37:13.122  6183  6234 W jxcore-log: Starting JXcore engine
,03-16 08:37:13.222  6183  6234 W jxcore-log: Platform android
03-16 08:37:13.222  6183  6234 W jxcore-log: 
03-16 08:37:13.222  6183  6234 W jxcore-log: Process ARCH arm
03-16 08:37:13.222  6183  6234 W jxcore-log: 
,03-16 08:37:13.672  6183  6234 I jxcore-log: JXcore Cordova bridge is ready!
03-16 08:37:13.672  6183  6234 I jxcore-log: 
,03-16 08:37:13.672  6183  6234 W jxcore-log: JXcore engine is started
,03-16 08:37:13.672  6183  6228 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-16 08:37:13.672  6183  6183 I chromium: [INFO:CONSOLE(47)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (47)
,03-16 08:37:13.682  6183  6234 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-16 08:37:13.682  6183  6234 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-16 08:37:13.692  6183  6183 I chromium: [INFO:CONSOLE(62)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (62)
,03-16 08:37:13.692  6183  6183 I chromium: [INFO:CONSOLE(33)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (33)
,03-16 08:37:13.692  1019  3272 D FocusedStackFrame: Set to : 0
03-16 08:37:13.692  1019  3272 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-16 08:37:13.692  1019  3272 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-16 08:37:13.692  1019  3272 D InputDispatcher: Focused application set to: xxxx
03-16 08:37:13.702  1019  3272 D InputDispatcher: Focus left window: 6183
03-16 08:37:13.702  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-16 08:37:13.702  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
03-16 08:37:13.712  1019  3272 I ActivityManager: Killing 4189:com.sec.spp.push/u0a32 (adj 15): empty #31
,03-16 08:37:13.712  6183  6228 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 20ms. Plugin should use CordovaInterface.getThreadPool().
,03-16 08:37:13.742   257   452 I SurfaceFlinger: id=14 Removed NainActivit (6/8)
,03-16 08:37:13.742   257  1866 I SurfaceFlinger: id=14 Removed NainActivit (-2/8)
,03-16 08:37:13.762  1019  1496 W ActivityManager: mDVFSHelper.acquire()
,03-16 08:37:13.762  1019  1496 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,03-16 08:37:13.772  6183  6183 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@9197741 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-16 08:37:13.772  6183  6183 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@9197741 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-16 08:37:13.772  6183  6183 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-16 08:37:13.772  6183  6183 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-16 08:37:13.772  6183  6183 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-16 08:37:13.772  6183  6183 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-16 08:37:13.772  6183  6183 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-16 08:37:13.772  6183  6183 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.initialize(BluetoothManager.java:275)
03-16 08:37:13.772  6183  6183 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.bind(BluetoothManager.java:103)
03-16 08:37:13.772  6183  6183 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:75)
03-16 08:37:13.772  6183  6183 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-16 08:37:13.772  6183  6183 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-16 08:37:13.772  6183  6183 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-16 08:37:13.772  6183  6183 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-16 08:37:13.772  6183  6183 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-16 08:37:13.772  6183  6183 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-16 08:37:13.772  6183  6183 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-16 08:37:13.772  6183  6183 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-16 08:37:13.772  6183  6183 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-16 08:37:13.772  6183  6183 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-16 08:37:13.772  6183  6183 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 08:37:13.772  6183  6183 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-16 08:37:13.772  6183  6183 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-16 08:37:13.772  6183  6183 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@ff55e28 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-16 08:37:13.772  6183  6183 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@ff55e28 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-16 08:37:13.772  6183  6183 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-16 08:37:13.772  6183  6183 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-16 08:37:13.772  6183  6183 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-16 08:37:13.772  6183  6183 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-16 08:37:13.772  6183  6183 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-16 08:37:13.772  6183  6183 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:503)
03-16 08:37:13.772  6183  6183 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:67)
03-16 08:37:13.772  6183  6183 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-16 08:37:13.772  6183  6183 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-16 08:37:13.772  6183  6183 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-16 08:37:13.772  6183  6183 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-16 08:37:13.772  6183  6183 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-16 08:37:13.772  6183  6183 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-16 08:37:13.772  6183  6183 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-16 08:37:13.772  6183  6183 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-16 08:37:13.772  6183  6183 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-16 08:37:13.772  6183  6183 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-16 08:37:13.772  6183  6183 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 08:37:13.772  6183  6183 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-16 08:37:13.772  6183  6183 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-16 08:37:13.782   293   293 E SMD     : DCD OFF
,03-16 08:37:13.792  1481  1481 D Launcher: onRestart, Launcher: 812586082
,03-16 08:37:13.792  1481  1481 D Launcher: onStart, Launcher: 812586082
,03-16 08:37:13.792  1481  1481 D Launcher.HomeView: onStart
03-16 08:37:13.792  1481  1481 D Launcher: onResume, Launcher: 812586082
,03-16 08:37:13.802  1019  1385 D SettingsProvider: name = kids_home_mode
03-16 08:37:13.802  1019  1385 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-16 08:37:13.802  1019  1385 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-16 08:37:13.802  1019  1385 D SettingsProvider: selectionArgs: false
03-16 08:37:13.802  1019  1385 D SettingsProvider: selectionArgs: 10006
03-16 08:37:13.802  1019  1385 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-16 08:37:13.802  1019  1385 D SettingsProvider: ret = -1
03-16 08:37:13.802  1481  1481 D Launcher.HomeView: onResume
,03-16 08:37:13.802  1481  1481 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-16 08:37:13.812  1481  1481 D MenuAppsGridFragment: onResume
,03-16 08:37:13.812  1019  1044 W ActivityManager: userId = 0, bbcId = -10000
03-16 08:37:13.812  1019  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 08:37:13.812  1019  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,03-16 08:37:13.812  1019  1032 D ActivityManager: handle home activity for 0
03-16 08:37:13.812  1019  1032 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
03-16 08:37:13.812  1019  1032 D KnoxTimeoutHandler: post home show event for user 0
03-16 08:37:13.812  1019  1032 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false,
03-16 08:37:13.812  1019  1032 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-16 08:37:13.812  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
03-16 08:37:13.812  1019  1032 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-16 08:37:13.812  1019  1019 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
03-16 08:37:13.812  1019  1019 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
03-16 08:37:13.812  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-16 08:37:13.812  1481  1481 D Launcher.HomeView: onPause
03-16 08:37:13.822  1481  1481 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-16 08:37:13.822  1019  1385 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
03-16 08:37:13.822  1019  1385 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,03-16 08:37:13.822  1019  1385 W ActivityManager: userId = 0, bbcId = -10000
,03-16 08:37:13.822  1019  1385 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 08:37:13.822  1019  1385 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,03-16 08:37:13.832  4977  4977 D GalleryCacheReady: Receive : home resume
,03-16 08:37:13.832  1019  1044 W ActivityManager: userId = 0, bbcId = -10000
03-16 08:37:13.832  1019  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-16 08:37:13.832  1019  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,03-16 08:37:13.832  1019  1044 W ActivityManager: userId = 0, bbcId = -10000
,03-16 08:37:13.832  1019  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 08:37:13.832  1019  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,03-16 08:37:13.842  2415  2415 D Recents_RecreateReceiver: onReceive by home
03-16 08:37:13.842  1019  1044 W ActivityManager: userId = 0, bbcId = -10000
03-16 08:37:13.842  1019  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 08:37:13.842  1019  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,03-16 08:37:13.842   257   257 I SurfaceFlinger: id=15 createSurf (540x960),1 flag=4, Mauncher
,03-16 08:37:13.852  5637  5637 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
03-16 08:37:13.852  1019  1385 W ActivityManager: userId = 0, bbcId = -10000
,03-16 08:37:13.852  1019  1385 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 08:37:13.852  1019  1385 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
03-16 08:37:13.852  1019  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-16 08:37:13.852  1019  1043 W libprocessgroup: failed to open /acct/uid_10032/pid_4189/cgroup.procs: No such file or directory
,03-16 08:37:13.852  1019  1385 W ActivityManager: userId = 0, bbcId = -10000
03-16 08:37:13.852  1019  1385 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 08:37:13.852  1019  1385 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,03-16 08:37:13.862  5659  5659 D Mms/UIEventReceiver: ui event,
03-16 08:37:13.862  1019  1378 D InputDispatcher: Focus entered window: 1481
03-16 08:37:13.862  1019  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-16 08:37:13.862  1481  1481 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-16 08:37:13.862  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-16 08:37:13.862  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
03-16 08:37:13.862  1019  1385 W ActivityManager: userId = 0, bbcId = -10000
03-16 08:37:13.862  1019  1385 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 08:37:13.862  1019  1385 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
03-16 08:37:13.872  1481  1481 D Launcher.HomeView: onStop
03-16 08:37:13.872  1481  1481 V ActivityThread: updateVisibility : ActivityRecord{3465e6c2 token=android.os.BinderProxy@a057d8f {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,03-16 08:37:13.872  1019  3294 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-16 08:37:13.872  1019  6241 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 08:37:13.872  1840  1840 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
03-16 08:37:13.882  1019  1385 W ActivityManager: userId = 0, bbcId = -10000
03-16 08:37:13.882  1019  1385 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 08:37:13.882  1019  1385 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1481, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
03-16 08:37:13.882  1019  1385 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,03-16 08:37:13.882  1019  1385 I splitIntent: Queue : backgroundsplit_2 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,03-16 08:37:13.882  1019  1044 W ActivityManager: userId = 0, bbcId = -10000
03-16 08:37:13.882  1019  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 08:37:13.882  1019  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,03-16 08:37:13.882  6183  6183 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-16 08:37:13.892  1180  1180 I StatusBar: Icon Only
,03-16 08:37:13.892  1180  1180 D PanelView: There is/are notification(s) 
03-16 08:37:13.892  5637  5637 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,03-16 08:37:13.902  1481  1481 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@a057d8f time:220487
,03-16 08:37:13.922  1019  1049 W ActivityManager: mDVFSHelper.release()
03-16 08:37:13.922  1019  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{221a8362 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t21} time:220509
,03-16 08:37:13.992  6236  6236 D AndroidRuntime: ,
03-16 08:37:13.992  6236  6236 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,03-16 08:37:14.002  6236  6236 D AndroidRuntime: CheckJNI is OFF,
,03-16 08:37:14.002  6236  6236 D AndroidRuntime: readGMSProperty: start
03-16 08:37:14.002  6236  6236 D AndroidRuntime: readGMSProperty: already setted!!,
03-16 08:37:14.002  6236  6236 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-16 08:37:14.002  6236  6236 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-16 08:37:14.002  6236  6236 D AndroidRuntime: readGMSProperty: end,
03-16 08:37:14.002  6236  6236 D AndroidRuntime: addProductProperty: start
,03-16 08:37:14.022  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,03-16 08:37:14.162  6236  6236 E AffinityControl: AffinityControl: registerfunction enter,
,03-16 08:37:14.192  6236  6236 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-16 08:37:14.202  1019  1496 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
03-16 08:37:14.202  1019  1496 D PackageManager: START PACKAGE DELETE: observer{648555298}
03-16 08:37:14.202  1019  1496 D PackageManager: pkg{<packageName>}
03-16 08:37:14.202  1019  1496 D PackageManager: user{0}
03-16 08:37:14.202  1019  1496 D PackageManager: caller{2000}
03-16 08:37:14.202  1019  1496 D PackageManager: flags{2}
03-16 08:37:14.202  1019  1496 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
,03-16 08:37:14.202  1019  1057 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
03-16 08:37:14.202  1019  1496 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
03-16 08:37:14.202  1019  1496 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-16 08:37:14.202  1019  1496 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-16 08:37:14.202  1019  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
03-16 08:37:14.202  1019  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
03-16 08:37:14.202  1019  1057 D ApplicationPolicy: getApplicationUninstallationEnabled
03-16 08:37:14.202  1019  1057 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,03-16 08:37:14.212  1019  1057 D PackageManager: !@killApplicatoin: 10167, uninstall pkg,
,03-16 08:37:14.212  1019  1044 I ActivityManager: Force stopping com.test.thalitest appid=10167 user=-1: uninstall pkg,
03-16 08:37:14.212  1019  1044 I ActivityManager: Killing 6183:com.test.thalitest/u0a167 (adj 13): stop com.test.thalitest cause uninstall pkg
,03-16 08:37:14.222  1019  1044 D PersonaManager: isKioskContainerExistOnDevice
,03-16 08:37:14.302  1019  1057 W PackageSettings: Skipping PackageSetting{1a3216a4 com.example.hello/10346} due to missing metadata,
,03-16 08:37:14.342  1019  1057 I ActivityManager: Force stopping com.test.thalitest appid=10167 user=0: pkg removed
,03-16 08:37:14.352  1019  1057 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,03-16 08:37:14.382  4023  4023 I art     : Explicit concurrent mark sweep GC freed 2537(152KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 820us total 27.333ms
,03-16 08:37:14.392  1019  1101 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-16 08:37:14.402  1840  1840 E SamsungIME: mOCRHelper is null
,03-16 08:37:14.412  1809  2132 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-16 08:37:14.432  3691  3691 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Mar 16 08:37:14 GMT+01:00 2016
,03-16 08:37:14.432  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
03-16 08:37:14.432  1019  1125 V NetworkStats: removeUidsLocked() for UIDs [10167]
03-16 08:37:14.432  1019  1125 V NetworkStats: performPollLocked(flags=0x3)
,03-16 08:37:14.442  1019  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
03-16 08:37:14.442  1019  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,03-16 08:37:14.452  1019  1125 V NetworkStats: performPollLocked() took 13ms
03-16 08:37:14.452  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,03-16 08:37:14.452  1019  3272 W ActivityManager: userId = 0, bbcId = -10000
,03-16 08:37:14.452  1019  3272 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 08:37:14.452  1019  3272 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-16 08:37:14.472  5997  5997 I art     : Explicit concurrent mark sweep GC freed 405(27KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/8MB, paused 738us total 122.213ms
,03-16 08:37:14.482  3691  3691 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,03-16 08:37:14.482  1019  1326 I splitIntent: intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
03-16 08:37:14.482  1019  1326 I splitIntent: base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
03-16 08:37:14.482  1019  1326 I splitIntent: other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
03-16 08:37:14.482  1019  1326 I splitIntent: arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,03-16 08:37:14.482  1019  1326 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 08:37:14.482  1019  1326 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 08:37:14.482  1019  1326 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 08:37:14.482  1019  1326 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 08:37:14.492  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,03-16 08:37:14.492  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,03-16 08:37:14.492  3691  3691 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,03-16 08:37:14.502  6254  6254 E Zygote  : MountEmulatedStorage(),
03-16 08:37:14.502  6254  6254 E Zygote  : v2
03-16 08:37:14.502  6254  6254 I libpersona: KNOX_SDCARD checking this for 10090
03-16 08:37:14.502  6254  6254 I libpersona: KNOX_SDCARD not a persona
,03-16 08:37:14.512  6254  6254 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 08:37:14.512  6254  6254 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 08:37:14.512  6254  6254 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 08:37:14.522  3691  3691 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-16 08:37:14.522  1019  1326 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6254 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,03-16 08:37:14.522  3691  3691 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-16 08:37:14.552  3691  6253 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,03-16 08:37:14.552  6254  6254 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 08:37:14.552  6254  6254 D ActivityThread: Added TimaKeyStore provider
,03-16 08:37:14.572  1019  1019 I art     : Explicit concurrent mark sweep GC freed 30137(2MB) AllocSpace objects, 15(244KB) LOS objects, 33% free, 23MB/35MB, paused 2.640ms total 218.431ms
,03-16 08:37:14.572  3691  6253 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,03-16 08:37:14.572  1019  1057 I art     : WaitForGcToComplete blocked for 143.490ms for cause Explicit
,03-16 08:37:14.582  1019  3867 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
03-16 08:37:14.582  1019  3867 D SecContentProvider2: mCursor = null
,03-16 08:37:14.582  3691  6253 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,03-16 08:37:14.592  3691  6253 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,03-16 08:37:14.592  1443  1443 D RegisteredServicesCache: empty dynamic service
,03-16 08:37:14.612  1019  1019 D RCPManagerService: PackageReceiver onReceive()
,03-16 08:37:14.612  1019  1019 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,03-16 08:37:14.612  1019  1019 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,03-16 08:37:14.632  6254  6254 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,03-16 08:37:14.632  6254  6254 D elm:15121: ELMEngine.ELMEngine( context ).
,03-16 08:37:14.632  6254  6254 D elm:15121: MDMBridge.setEnterpriseBridge()
,03-16 08:37:14.632  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-16 08:37:14.632  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-16 08:37:14.632  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,03-16 08:37:14.642  6254  6254 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,03-16 08:37:14.652  1019  1043 D EnterpriseDeviceManagerService: Package has changed for user 0
03-16 08:37:14.652  1019  1043 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,03-16 08:37:14.652  1019  1043 W TextServicesManagerService: no available spell checker services found
,03-16 08:37:14.652  6254  6254 D elm:15121: ElmAgentService : onCreate()
,03-16 08:37:14.652  6254  6269 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
03-16 08:37:14.652  6254  6269 D elm:15121: MainReceiver.listeningToPackageRemoved()
03-16 08:37:14.652  6254  6269 D elm:15121: MDMBridge.getInstance()
03-16 08:37:14.652  6254  6269 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,03-16 08:37:14.662  6254  6269 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,03-16 08:37:14.662  3691  6253 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,03-16 08:37:14.672  3691  6253 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,03-16 08:37:14.672  3691  6253 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,03-16 08:37:14.682  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 08:37:14.682  3691  3691 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,03-16 08:37:14.682  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 08:37:14.682  6254  6254 D elm:15121: ElmAgentService : onDestroy().
,03-16 08:37:14.692  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 08:37:14.702  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 08:37:14.702  1019  1019 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-16 08:37:14.702  1019  1019 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-16 08:37:14.702  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
03-16 08:37:14.702  1019  1019 V EnterpriseBillingPolicy: uID is 10167
03-16 08:37:14.702  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
03-16 08:37:14.702  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-16 08:37:14.702  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-16 08:37:14.702  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-16 08:37:14.702  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-16 08:37:14.702  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-16 08:37:14.702  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-16 08:37:14.712  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,03-16 08:37:14.712  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
03-16 08:37:14.712  1019  1162 D TaskPersister: removeObsoleteFile: deleting file=23_task.xml
,03-16 08:37:14.712  1019  1019 V EnterpriseBillingPolicy: uID is 10167
03-16 08:37:14.712  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
03-16 08:37:14.712  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
03-16 08:37:14.712  1019  2762 D SSRM:aZ : MSG_TYPE_APP_REMOVED::
,03-16 08:37:14.712  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-16 08:37:14.712  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-16 08:37:14.712  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-16 08:37:14.712  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-16 08:37:14.712  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-16 08:37:14.742  1019  1057 I art     : Explicit concurrent mark sweep GC freed 12256(657KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 3.291ms total 175.422ms
,03-16 08:37:14.762  5705  5705 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-16 08:37:14.762  5705  5705 I PCWCLIENTTRACE_PushUtil: sales region : global
03-16 08:37:14.762  5705  5705 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-16 08:37:14.762  5705  5705 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,03-16 08:37:14.772  5798  5798 I SA      : [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,03-16 08:37:14.772  5798  5798 I SA      : [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10167 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,03-16 08:37:14.782  1019  1496 W ActivityManager: userId = 0, bbcId = -10000
,03-16 08:37:14.782  1019  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 08:37:14.782  1019  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,03-16 08:37:14.792  4977  4977 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
,03-16 08:37:14.802  1019  1043 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,03-16 08:37:14.812  5659  5659 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
,03-16 08:37:14.812  1019  1514 W ActivityManager: userId = 0, bbcId = -10000
03-16 08:37:14.812  1019  1514 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 08:37:14.812  1019  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,03-16 08:37:14.822  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 08:37:14.822  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 08:37:14.822  5659  6272 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
,03-16 08:37:14.822  5659  6272 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
,03-16 08:37:14.832  1019  1742 I TactileAssist: enable value -1
03-16 08:37:14.832  1019  1742 I TactileAssist: internal enable value -1
03-16 08:37:14.832  1019  1742 I TactileAssist: intensity value -1
03-16 08:37:14.832  1019  1742 I TactileAssist: saveAppList value true
03-16 08:37:14.832  1019  1057 D PackageManager: delete codoeFile: 
,03-16 08:37:14.832  1019  1057 D AASAuninstall: userId = 0, info.removedAppID = 10167, info.uid = 10167, packageName = com.test.thalitest
03-16 08:37:14.832  1019  1057 I AASA_removePackage: UID=10167 Target=com.test.thalitest
,03-16 08:37:14.832  1019  1057 D PackageManager: result of delete: 1{648555298}
,03-16 08:37:14.832  1019  1742 I TactileAssist: List of disabled apps :
,03-16 08:37:14.832  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 08:37:14.842  6236  6236 D AndroidRuntime: Shutting down VM
,03-16 08:37:14.842  1019  1043 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-16 08:37:14.842  1019  1043 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 08:37:14.842  1019  1043 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-16 08:37:14.842  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 08:37:14.862  5885  5885 D Compatibility: onReceive() it will make start service
,03-16 08:37:14.862  1019  3295 W ActivityManager: userId = 0, bbcId = -10000
,03-16 08:37:14.862  1019  3295 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 08:37:14.862  1019  3295 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,03-16 08:37:14.872  1019  1728 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 08:37:14.872  1019  1728 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 08:37:14.872  1019  1728 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 08:37:14.872  1019  1728 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 08:37:14.872  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 08:37:14.872  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
03-16 08:37:14.872  5885  6273 D Compatibility: onHandleIntent()
03-16 08:37:14.872  5885  6273 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10167, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
03-16 08:37:14.872  5885  6273 D Compatibility: found: 2
,03-16 08:37:14.872  5885  6273 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
03-16 08:37:14.872  5885  6273 D Compatibility: skipping ResolveInfo{128eea44 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
03-16 08:37:14.872  5885  6273 D Compatibility: considering ResolveInfo{26d2a72d com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
03-16 08:37:14.872  5885  6273 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
03-16 08:37:14.882  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 08:37:14.882  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1},
03-16 08:37:14.882  5885  6273 D Compatibility: enabling receiver ResolveInfo{306f1462 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,03-16 08:37:14.882  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 08:37:14.882  6274  6274 E Zygote  : MountEmulatedStorage()
03-16 08:37:14.882  6274  6274 E Zygote  : v2
03-16 08:37:14.882  6274  6274 I libpersona: KNOX_SDCARD checking this for 10055
03-16 08:37:14.882  6274  6274 I libpersona: KNOX_SDCARD not a persona
03-16 08:37:14.882  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 08:37:14.882  6274  6274 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 08:37:14.882  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
03-16 08:37:14.882  1019  1728 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6274 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
03-16 08:37:14.882  6274  6274 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 08:37:14.882  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 08:37:14.882  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
03-16 08:37:14.892  6274  6274 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 08:37:14.892  5885  6273 D Compatibility: enabling receiver ResolveInfo{1d4db9f3 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,03-16 08:37:14.892  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 08:37:14.902  5885  6273 D Compatibility: enabling receiver ResolveInfo{2db266b0 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,03-16 08:37:14.902  1019  1043 D UsbSettingsManager: clearDefaults: com.test.thalitest
,03-16 08:37:14.902  5885  6273 D Compatibility: enabling receiver ResolveInfo{2c5f8929 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
03-16 08:37:14.902  1019  1043 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,03-16 08:37:14.902   313   313 I art     : Explicit concurrent mark sweep GC freed 8692(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 615us total 20.715ms,
03-16 08:37:14.912  5885  6273 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,03-16 08:37:14.912  6274  6274 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 08:37:14.912  6274  6274 D ActivityThread: Added TimaKeyStore provider
,03-16 08:37:14.922   313   313 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 583us total 16.694ms
,03-16 08:37:14.942   313   313 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 577us total 16.524ms
,03-16 08:37:14.952  6274  6274 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,03-16 08:37:14.972  1019  1378 W ActivityManager: userId = 0, bbcId = -10000
,03-16 08:37:14.972  1019  1378 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 08:37:14.972  1019  1378 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,03-16 08:37:14.982  1019  1051 I PowerManagerService: [PWL] Off : 105s ago
,03-16 08:37:14.982  6274  6274 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,03-16 08:37:14.982  6274  6274 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
03-16 08:37:14.982  6274  6274 D UserAnalysis: Create SecureDbHelper
,03-16 08:37:14.982  6274  6274 D IntelligenceServiceApplication: onCreate()
,03-16 08:37:14.982  6274  6274 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,03-16 08:37:14.992  5904  5904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,03-16 08:37:14.992  1019  3867 W ActivityManager: userId = 0, bbcId = -10000
,03-16 08:37:14.992  1019  3867 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 08:37:14.992  1019  3867 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,03-16 08:37:14.992  6274  6274 D IntelligenceServiceApplication: no applications having user consent for prediction
,03-16 08:37:14.992  6274  6274 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
03-16 08:37:14.992  1019  3867 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 08:37:14.992  1019  3867 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 08:37:14.992  1019  3867 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 08:37:14.992  1019  3867 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 08:37:15.012  6274  6274 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,03-16 08:37:15.012  6291  6291 E Zygote  : MountEmulatedStorage()
03-16 08:37:15.012  1019  3867 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6291 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-16 08:37:15.012  6291  6291 E Zygote  : v2
03-16 08:37:15.012  6291  6291 I libpersona: KNOX_SDCARD checking this for 1000
03-16 08:37:15.012  6291  6291 I libpersona: KNOX_SDCARD not a persona
,03-16 08:37:15.012  6291  6291 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 08:37:15.022  6291  6291 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 08:37:15.022  6291  6291 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 08:37:15.022  1019  1385 I ActivityManager: Killing 5198:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
,03-16 08:37:15.052  6236  6236 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
,03-16 08:37:15.062  1019  1057 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
03-16 08:37:15.062  1019  1057 D PackageManager: userId{-1}
03-16 08:37:15.062  1019  1057 D PackageManager: andCode{true}
,03-16 08:37:15.062  6274  6274 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
,03-16 08:37:15.062  6274  6274 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
,03-16 08:37:15.072  6291  6291 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 08:37:15.072  6291  6291 D ActivityThread: Added TimaKeyStore provider
03-16 08:37:15.072  6274  6274 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
03-16 08:37:15.072  6274  6274 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
03-16 08:37:15.072  6274  6274 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
03-16 08:37:15.072  6274  6274 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
03-16 08:37:15.072  6274  6274 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
03-16 08:37:15.072  6274  6274 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
03-16 08:37:15.072  6274  6274 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
03-16 08:37:15.072  6274  6274 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
03-16 08:37:15.072  6274  6274 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
03-16 08:37:15.072  6274  6274 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
03-16 08:37:15.072  6274  6274 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
03-16 08:37:15.072  6274  6274 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
03-16 08:37:15.072  6274  6274 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
03-16 08:37:15.072  6274  6274 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
03-16 08:37:15.072  6274  6274 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
03-16 08:37:15.072  6274  6274 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
03-16 08:37:15.072  6274  6274 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,03-16 08:37:15.072  6274  6274 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
03-16 08:37:15.072  6274  6274 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
03-16 08:37:15.072  6274  6274 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
03-16 08:37:15.072  6274  6274 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
,03-16 08:37:15.082  6274  6274 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
,03-16 08:37:15.082  6274  6274 D BluetoothAdapter: cancelDiscovery
,03-16 08:37:15.082  2637  2645 D BluetoothAdapterProperties: mDiscovering is false
,03-16 08:37:15.082  2637  2645 E BluetoothAdapterService: This is not a scanning status. cancelDiscovery() will be not called.
03-16 08:37:15.082  6274  6274 D BluetoothAdapter: cancelDiscovery = true
,03-16 08:37:15.082  6274  6274 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
,03-16 08:37:15.092  6274  6274 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,03-16 08:37:15.092  6274  6274 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,03-16 08:37:15.092  6291  6291 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-16 08:37:15.122  6291  6291 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,03-16 08:37:15.122  1019  1031 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
,03-16 08:37:15.122  1019  1031 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,03-16 08:37:15.132  5923  5923 D FilterInstaller: onReceive:android.intent.action.PACKAGE_REMOVED, package:com.test.thalitest
,03-16 08:37:15.132  5923  5923 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,03-16 08:37:15.132  1019  1326 W ActivityManager: userId = 0, bbcId = -10000
,03-16 08:37:15.142  1019  1326 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 08:37:15.142  1019  1326 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,03-16 08:37:15.152  5923  5923 I FilterInstaller: FilterPackageService : ACTION_PACKAGE_REMOVED
,03-16 08:37:15.152  6274  6274 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
,03-16 08:37:15.152  6274  6274 E SQLiteLog: (3850) statement aborts at 17: [INSERT INTO dump_log(timestamp,message) VALUES (?,?)] disk I/O error
03-16 08:37:15.152  1019  1043 W libprocessgroup: failed to open /acct/uid_10032/pid_5198/cgroup.procs: No such file or directory
03-16 08:37:15.152  5923  6309 I FilterInstaller: FilterPackageService : ACTION_REMOVED
,03-16 08:37:15.152  5923  6309 D FilterUnInstaller: before removeFromFS
,03-16 08:37:15.152  1019  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 08:37:15.152  1019  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 08:37:15.152  1019  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 08:37:15.152  1019  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 08:37:15.162  6274  6274 E SQLiteDatabase: Error inserting timestamp=1458113835094 message=Predictor: service stopped by removePlaceCategories()
03-16 08:37:15.162  6274  6274 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-16 08:37:15.162  6274  6274 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-16 08:37:15.162  6274  6274 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-16 08:37:15.162  6274  6274 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-16 08:37:15.162  6274  6274 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-16 08:37:15.162  6274  6274 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-16 08:37:15.162  6274  6274 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-16 08:37:15.162  6274  6274 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:110)
03-16 08:37:15.162  6274  6274 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
03-16 08:37:15.162  6274  6274 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-16 08:37:15.162  6274  6274 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-16 08:37:15.162  6274  6274 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-16 08:37:15.162  6274  6274 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-16 08:37:15.162  6274  6274 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-16 08:37:15.162  6274  6274 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-16 08:37:15.162  6274  6274 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-16 08:37:15.162  6274  6274 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,03-16 08:37:15.162  6274  6274 E UserAnalysis: It failed to insert to dump_log table
,03-16 08:37:15.172  6311  6311 E Zygote  : MountEmulatedStorage()
,03-16 08:37:15.172  6311  6311 E Zygote  : v2
03-16 08:37:15.172  6311  6311 I libpersona: KNOX_SDCARD checking this for 1000
03-16 08:37:15.172  6311  6311 I libpersona: KNOX_SDCARD not a persona
,03-16 08:37:15.172  1019  1479 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6311 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-16 08:37:15.172  6311  6311 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 08:37:15.172  1019  1742 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-16 08:37:15.172  1019  1742 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 08:37:15.172  1019  1742 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 08:37:15.172  1019  1742 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 08:37:15.182  6311  6311 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 08:37:15.182  6311  6311 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-16 08:37:15.192  6324  6324 E Zygote  : MountEmulatedStorage()
,03-16 08:37:15.192  6324  6324 I libpersona: KNOX_SDCARD checking this for 10095
03-16 08:37:15.192  6324  6324 E Zygote  : v2
03-16 08:37:15.192  6324  6324 I libpersona: KNOX_SDCARD not a persona
03-16 08:37:15.192  6324  6324 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
03-16 08:37:15.192  1019  1742 I ActivityManager: Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=6324 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
,03-16 08:37:15.202  6324  6324 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-16 08:37:15.202  6324  6324 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 08:37:15.202  6311  6311 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 08:37:15.202  6311  6311 D ActivityThread: Added TimaKeyStore provider
,03-16 08:37:15.232  6324  6324 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 08:37:15.232  6324  6324 D ActivityThread: Added TimaKeyStore provider

```
