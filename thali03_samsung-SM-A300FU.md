#### Test 84648740f6d448c_thali03_samsung-SM-A300FU Logs


```
--------- beginning of system
09-09 17:17:29.680  1015  3283 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
--------- beginning of main
09-09 17:17:29.690  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-09 17:17:29.690  1015  3283 D BatteryService: level:93, scale:100, status:2, health:2, present:true, voltage: 4227, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-09 17:17:29.690  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
09-09 17:17:29.690  1015  3283 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-09 17:17:29.690  1015  3283 D BatteryService: stay LED for charging
09-09 17:17:29.700  3225  3225 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-09 17:17:29.690  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-09 17:17:29.700  3225  3352 D HeadsetStateMachine: Disconnected process message: 10
09-09 17:17:29.690  1015  1015 I MotionRecognitionService: Plugged
09-09 17:17:29.690  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
09-09 17:17:29.690  1435  1435 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-09 17:17:29.690  1435  1435 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
09-09 17:17:29.720  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
09-09 17:17:29.720  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
09-09 17:17:29.720  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
09-09 17:17:29.720  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
09-09 17:17:29.720  1178  1178 D SViewCoverView: level :93 plugged : 2
09-09 17:17:29.720   287   287 E SMD     : DCD OFF
09-09 17:17:29.720   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 17:17:30.030  7306  7306 D AndroidRuntime: 
09-09 17:17:30.030  7306  7306 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-09 17:17:30.030  7306  7306 D AndroidRuntime: CheckJNI is OFF
09-09 17:17:30.030  7306  7306 D AndroidRuntime: readGMSProperty: start
09-09 17:17:30.030  7306  7306 D AndroidRuntime: readGMSProperty: already setted!!
09-09 17:17:30.030  7306  7306 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-09 17:17:30.030  7306  7306 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-09 17:17:30.030  7306  7306 D AndroidRuntime: readGMSProperty: end
09-09 17:17:30.030  7306  7306 D AndroidRuntime: addProductProperty: start
09-09 17:17:30.160  7306  7306 E AffinityControl: AffinityControl: registerfunction enter
09-09 17:17:30.190  7306  7306 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-09 17:17:30.200  1015  1027 E PersonaManagerService: inState():  stateMachine is null !!
09-09 17:17:30.200  1015  1027 I PersonaManagerService: PersonaId don't exist
09-09 17:17:30.200  1015  1027 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-09 17:17:30.210  1015  1027 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-09 17:17:30.220  1015  1027 W ActivityManager: mDVFSHelper.acquire()
09-09 17:17:30.230  1015  1027 D FocusedStackFrame: Set to : 0
09-09 17:17:30.240  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:30.240  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:30.240  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:30.240  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:30.250  1015  1047 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-09 17:17:30.250  1015  1047 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-09 17:17:30.250  7319  7319 E Zygote  : MountEmulatedStorage()
09-09 17:17:30.250  7319  7319 E Zygote  : v2
09-09 17:17:30.250  7319  7319 I libpersona: KNOX_SDCARD checking this for 10170
09-09 17:17:30.250  7319  7319 I libpersona: KNOX_SDCARD not a persona
09-09 17:17:30.250  7319  7319 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 17:17:30.250  1015  1027 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
09-09 17:17:30.250  1015  1027 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7319 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-09 17:17:30.250  1015  1027 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-09 17:17:30.250  1015  1027 D InputDispatcher: Focused application set to: xxxx
09-09 17:17:30.250  1015  1027 D InputDispatcher: Focus left window: 1506
09-09 17:17:30.260  7319  7319 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 17:17:30.260  7306  7306 D AndroidRuntime: Shutting down VM
09-09 17:17:30.260  7319  7319 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-09 17:17:30.260  1015  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-09 17:17:30.260  1015  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-09 17:17:30.270   257   257 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
09-09 17:17:30.280  7319  7319 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 17:17:30.280  7319  7319 D ActivityThread: Added TimaKeyStore provider
09-09 17:17:30.290  1015  3280 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
09-09 17:17:30.290  1015  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-09 17:17:30.300  1015  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-09 17:17:30.300  1015  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
09-09 17:17:30.300  1015  1015 V ActivityManager: Display changed displayId=0
09-09 17:17:30.310  1015  3280 D PersonaManager: isKioskContainerExistOnDevice
09-09 17:17:30.330  1015  1015 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
09-09 17:17:30.330   257  1038 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
09-09 17:17:30.340   257   441 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
09-09 17:17:30.340  1506  1506 V ActivityThread: updateVisibility : ActivityRecord{3c1fed89 token=android.os.BinderProxy@359b8c21 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
09-09 17:17:30.340  1506  1506 D Launcher: onTrimMemory. Level: 20
09-09 17:17:30.430  7319  7319 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
09-09 17:17:30.470  7306  7306 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
09-09 17:17:30.480  7319  7319 I cr.library_loader: Time to load native libraries: 12 ms (timestamps 6748-6760)
09-09 17:17:30.480  7319  7319 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-09 17:17:30.500  7319  7319 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {399cc371}
,09-09 17:17:30.500  7319  7319 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-09 17:17:30.500  7319  7319 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-09 17:17:30.540  7319  7319 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,09-09 17:17:30.540  7319  7319 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 17:17:30.550  7319  7319 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-09 17:17:30.600  7319  7319 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-09 17:17:30.600  7319  7319 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-09 17:17:30.600  7319  7319 I Adreno-EGL: Build Date: 04/06/15 Mon
09-09 17:17:30.600  7319  7319 I Adreno-EGL: Local Branch: 
09-09 17:17:30.600  7319  7319 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-09 17:17:30.600  7319  7319 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-09 17:17:30.600  7319  7319 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-09 17:17:30.660  7319  7319 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-09 17:17:30.680  7319  7319 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,09-09 17:17:30.680  7319  7319 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,09-09 17:17:30.690  7319  7319 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,09-09 17:17:30.690  7319  7319 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,09-09 17:17:30.720   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 17:17:30.800  7319  7319 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 17:17:30.810  7319  7319 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-09 17:17:30.820  7319  7319 D PhoneWindow: *FMB* installDecor mIsFloating : false
,09-09 17:17:30.820  7319  7319 D PhoneWindow: *FMB* installDecor flags : -2139027200
,09-09 17:17:30.820  1015  1042 W ActivityManager: Activity pause timeout for ActivityRecord{2bde6250 u0 com.test.thalitest/.MainActivity t163}
,09-09 17:17:30.820  7319  7319 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-09 17:17:30.830  7319  7319 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 17:17:30.830  7319  7319 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 17:17:30.960  7319  7359 D OpenGLRenderer: Render dirty regions requested: true
,09-09 17:17:30.960  1015  1244 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-09 17:17:30.960  1015  1244 D KnoxTimeoutHandler: postActiveUserChange for user 0
,09-09 17:17:30.960  1015  1244 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-09 17:17:30.960  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-09 17:17:30.960  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
,09-09 17:17:30.970  7319  7346 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,09-09 17:17:30.970  7319  7319 V ActivityThread: updateVisibility : ActivityRecord{24bcce51 token=android.os.BinderProxy@3af425ea {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-09 17:17:30.980  7319  7319 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,09-09 17:17:30.980  7319  7319 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,09-09 17:17:30.990   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,09-09 17:17:31.010  1015  1501 D InputDispatcher: Focus entered window: 7319
,09-09 17:17:31.020  1015  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-09 17:17:31.020  1015  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-09 17:17:31.020  7319  7319 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-09 17:17:31.020  7319  7359 I OpenGLRenderer: Initialized EGL, version 1.4
,09-09 17:17:31.020  7319  7359 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,09-09 17:17:31.030  7319  7359 D OpenGLRenderer: Enabling debug mode 0
,09-09 17:17:31.050  1015  1244 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-09 17:17:31.050  1178  1178 D PanelView: There is/are notification(s) ,
,09-09 17:17:31.060  1015  7364 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-09 17:17:31.070  1015  1047 I ActivityManager: Displayed Component not be shown by security: +749ms (total +833ms)
,09-09 17:17:31.070  1015  1047 W ActivityManager: mDVFSHelper.release()
,09-09 17:17:31.070  1015  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2bde6250 u0 com.test.thalitest/.MainActivity t163} time:117358
,09-09 17:17:31.080   257  1038 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,09-09 17:17:31.080   257  1037 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,09-09 17:17:31.080  7319  7319 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,09-09 17:17:31.090  7319  7319 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3af425ea time:117370
,09-09 17:17:31.090  2019  2019 I SamsungIME: getCurrentCandidateView
,09-09 17:17:31.110  7319  7319 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7319
,09-09 17:17:31.180  2019  2019 D SamsungIME: Dismiss ExpandCandiate
,09-09 17:17:31.310  7319  7319 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-09 17:17:31.320  1015  1057 D PackageManager: [MSG] MCS_UNBIND
,09-09 17:17:31.330  1015  1244 I ActivityManager: Killing 6942:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,09-09 17:17:31.340  2019  2019 I SamsungIME: getDebugLevel  : 0x4f4c
,09-09 17:17:31.380  2019  2019 I SamsungIME: getDebugLevel  : 0x4f4c
,09-09 17:17:31.390  2019  2019 I SamsungIME: KeybaordView init() : load resources
,09-09 17:17:31.390  7319  7363 D jxcore_app_log: JniHelper::setJavaVM(0xb834a2b0), pthread_self() = -1198662592
,09-09 17:17:31.400  7319  7363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-09 17:17:31.400  7319  7363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-09 17:17:31.400  7319  7363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-09 17:17:31.400  7319  7363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-09 17:17:31.400  7319  7363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-09 17:17:31.400  7319  7363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d829eaf added. We now have 1 listener(s)
,09-09 17:17:31.400  7319  7363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,09-09 17:17:31.410  7319  7363 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-09 17:17:31.410  7319  7363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 17:17:31.410  7319  7363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 17:17:31.410  7319  7363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-09 17:17:31.410  7319  7363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-09 17:17:31.410  7319  7363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-09 17:17:31.410  7319  7363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
09-09 17:17:31.410  7319  7363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-09 17:17:31.410  7319  7363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-09 17:17:31.410  7319  7363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-09 17:17:31.410  7319  7363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-09 17:17:31.410  7319  7363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-09 17:17:31.410  7319  7363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-09 17:17:31.410  7319  7363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-09 17:17:31.410  7319  7363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-09 17:17:31.410  7319  7363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-09 17:17:31.410  7319  7363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-09 17:17:31.410  7319  7363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c59dd9a added. We now have 1 listener(s)
,09-09 17:17:31.410  7319  7363 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 17:17:31.420  2019  2019 I SamsungIME: getCurrentKeyboard
09-09 17:17:31.420  2019  2019 I SamsungIME: getTextKeyboard
,09-09 17:17:31.420  7319  7363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 17:17:31.420  7319  7363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-09 17:17:31.420  7319  7363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-09 17:17:31.420  7319  7363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-09 17:17:31.420  7319  7363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-09 17:17:31.420  7319  7363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:17:31.430  7319  7363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
,09-09 17:17:31.430  7319  7363 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-09 17:17:31.430  7319  7363 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:17:31.430  7319  7363 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:31.430  7319  7363 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:17:31.430  7319  7363 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,09-09 17:17:31.430  7319  7363 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:17:31.430  7319  7363 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:17:31.430  7319  7363 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:17:31.430  7319  7363 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:17:31.430  7319  7363 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-09 17:17:31.430  7319  7363 D io.jxcore.node.ConnectivityMonitor: start: OK,
09-09 17:17:31.430  7319  7363 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-09 17:17:31.440  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-09 17:17:31.440  2019  2019 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
09-09 17:17:31.440  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:31.470  7319  7319 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-09 17:17:31.720   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 17:17:31.950  7319  7373 W jxcore-log: Initializing JXcore engine
09-09 17:17:31.950  7319  7373 W jxcore-log: JXcore engine is ready
,09-09 17:17:32.000  1997  1997 E audit   : type=1400 msg=audit(1473434252.000:205): avc:  denied  { ioctl } for  pid=7373 comm="Thread-1396" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-09 17:17:32.000  1997  1997 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
09-09 17:17:32.000  1997  1997 E audit   : type=1300 msg=audit(1473434252.000:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9f0998f8 items=0 ppid=303 ppcomm=main pid=7373 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1396" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-09 17:17:32.000  1997  1997 E audit   : type=1320 msg=audit(1473434252.000:205): 
,09-09 17:17:32.010  7319  7373 W jxcore-log: Starting JXcore engine
,09-09 17:17:32.120  7319  7373 W jxcore-log: Platform android
09-09 17:17:32.120  7319  7373 W jxcore-log: 
09-09 17:17:32.120  7319  7373 W jxcore-log: Process ARCH arm
09-09 17:17:32.120  7319  7373 W jxcore-log: 
,09-09 17:17:32.330  7319  7373 I jxcore-log: JXcore Cordova bridge is ready!
09-09 17:17:32.330  7319  7373 I jxcore-log: 
,09-09 17:17:32.330  7319  7373 W jxcore-log: JXcore engine is started
,09-09 17:17:32.330  7319  7363 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-09 17:17:32.330  7319  7319 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-09 17:17:32.720   287   287 E SMD     : DCD OFF,
,09-09 17:17:32.720   314   314 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-09 17:17:33.810  6016  6016 D FactoryTest: Not factory mode
,09-09 17:17:33.810  6016  6016 D FactoryTest: Not factory mode. isFactoryMode() returend false
,09-09 17:17:33.810  6016  6016 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,09-09 17:17:33.810  6016  6016 D MTPRx   : still no open session command from host, so toast
,09-09 17:17:33.820  6016  6016 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 ,
09-09 17:17:33.820  6016  6016 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,09-09 17:17:33.820  6016  6016 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:120105,
09-09 17:17:33.820  1015  1346 E PersonaManagerService: inState():  stateMachine is null !!
09-09 17:17:33.820  1015  1346 I PersonaManagerService: PersonaId don't exist
09-09 17:17:33.820  1015  1346 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,09-09 17:17:33.820  1015  1346 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
,09-09 17:17:33.830  1015  1346 W ActivityManager: userId = 0, bbcId = -10000,
09-09 17:17:33.830  1015  1346 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:33.830  1015  1346 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,09-09 17:17:33.830  1015  1346 W ActivityManager: mDVFSHelper.acquire(),
,09-09 17:17:33.840  1015  1346 D PersonaManager: isKioskContainerExistOnDevice
,09-09 17:17:33.850  1015  1346 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-09 17:17:33.850  1015  1346 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-09 17:17:33.850  1015  1346 D InputDispatcher: Focused application set to: xxxx
,09-09 17:17:33.850  1015  1346 D InputDispatcher: Focus left window: 7319
,09-09 17:17:33.860  6016  6016 E MTPRx   : started activity for popup
09-09 17:17:33.860  1015  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-09 17:17:33.860  1015  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-09 17:17:33.880  6016  6016 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,09-09 17:17:33.880  6016  6016 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,09-09 17:17:33.880  6016  6016 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-09 17:17:33.880  6016  6016 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 17:17:33.880  6016  6016 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 17:17:33.880  6016  6016 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-09 17:17:33.910  6016  6016 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,09-09 17:17:33.910  1015  1244 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-09 17:17:33.910  1015  1244 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-09 17:17:33.910  1015  1244 D InputDispatcher: Focused application set to: xxxx
,09-09 17:17:33.920  1015  1244 D InputDispatcher: Focus entered window: 7319
,09-09 17:17:33.920  1015  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-09 17:17:33.920  1015  1027 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-09 17:17:33.920  1015  1027 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@39f4afe3 attribute=null, token = android.os.BinderProxy@34ae3f3
,09-09 17:17:33.920  1015  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-09 17:17:33.960  6016  6016 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,09-09 17:17:33.970  6016  6016 D PhoneWindow: *FMB* installDecor mIsFloating : true
09-09 17:17:33.970  6016  6016 D PhoneWindow: *FMB* installDecor flags : 8388610
,09-09 17:17:33.990  7319  7319 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-09 17:17:33.990  7319  7319 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,09-09 17:17:33.990  7319  7319 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-09 17:17:33.990  7319  7319 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,09-09 17:17:33.990  1015  1501 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-09 17:17:33.990  1015  1501 D KnoxTimeoutHandler: postActiveUserChange for user 0
,09-09 17:17:33.990  1015  1501 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-09 17:17:33.990  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-09 17:17:33.990  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
,09-09 17:17:34.000  7319  7319 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-09 17:17:34.000  7319  7319 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-09 17:17:34.010  7319  7319 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3af425ea time:120290
,09-09 17:17:34.010  7319  7319 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1a884006 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@13f2ae3a, 16908290=android.view.AbsSavedState$1@13f2ae3a}, android:focusedViewId=100}]}]
,09-09 17:17:34.010  7319  7319 V ActivityThread: updateVisibility : ActivityRecord{24bcce51 token=android.os.BinderProxy@3af425ea {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-09 17:17:34.010  7319  7319 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-09 17:17:34.010  7319  7319 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-09 17:17:34.010  7319  7319 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-09 17:17:34.020  1015  1491 D PersonaManager: isKioskContainerExistOnDevice
,09-09 17:17:35.720   287   287 E SMD     : DCD OFF
,09-09 17:17:35.990  1015  3377 D SSRM:n  : SIOP:: AP = 360
,09-09 17:17:36.510  1015  3395 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-09 17:17:36.830  1015  1042 W ActivityManager: mDVFSHelper.release()
,09-09 17:17:37.720   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 17:17:38.720   287   287 E SMD     : DCD OFF
09-09 17:17:38.730   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 17:17:39.730   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 17:17:39.740  1015  1346 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-09 17:17:39.740  1015  1346 D BatteryService: level:93, scale:100, status:2, health:2, present:true, voltage: 4200, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-09 17:17:39.740  1015  1346 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-09 17:17:39.740  1015  1346 D BatteryService: stay LED for charging
,09-09 17:17:39.740  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-09 17:17:39.750  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-09 17:17:39.750  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
09-09 17:17:39.750  1015  1015 I MotionRecognitionService: Plugged
09-09 17:17:39.750  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,09-09 17:17:39.750  1435  1435 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-09 17:17:39.750  1435  1435 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93,
,09-09 17:17:39.760  3225  3225 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-09 17:17:39.760  3225  3352 D HeadsetStateMachine: Disconnected process message: 10
,09-09 17:17:39.770  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,09-09 17:17:39.770  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,09-09 17:17:39.770  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,09-09 17:17:39.770  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,09-09 17:17:39.770  1178  1178 D SViewCoverView: level :93 plugged : 2
,09-09 17:17:40.280  1015  1057 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-09 17:17:40.730   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 17:17:41.730   287   287 E SMD     : DCD OFF
09-09 17:17:41.730   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 17:17:42.730   314   314 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-09 17:17:44.630  7319  7373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-09 17:17:44.630  7319  7373 I jxcore-log: 
,09-09 17:17:44.630  7319  7373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-09 17:17:44.630  7319  7373 I jxcore-log: 
,09-09 17:17:44.640  7319  7373 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:17:44.640  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:44.640  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:17:44.640  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:17:44.640  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:17:44.640  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:17:44.640  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:17:44.640  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 17:17:44.640  7319  7373 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 17:17:44.640  7319  7373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-09 17:17:44.640  7319  7373 I jxcore-log: 
,09-09 17:17:44.640  7319  7373 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-09 17:17:44.640  7319  7373 I jxcore-log: 
,09-09 17:17:44.730   287   287 E SMD     : DCD OFF,
,09-09 17:17:45.300  7319  7373 D executeNativeTests: Running unit tests,
,09-09 17:17:45.390  7319  7373 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:17:45.390  7319  7373 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19e384db added. We now have 2 listener(s)
,09-09 17:17:45.390  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-09 17:17:45.390  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:17:45.390  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 17:17:45.400  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:17:45.400  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34bc7b78 added. We now have 2 listener(s)
09-09 17:17:45.400  7319  7373 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 17:17:45.400  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 17:17:45.400  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:17:45.400  7319  7373 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:17:45.400  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:45.400  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:17:45.400  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:17:45.400  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:17:45.400  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:17:45.400  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:17:45.400  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 17:17:45.410  7319  7373 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 17:17:45.410  7319  7373 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 17:17:45.410  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:45.410  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 17:17:45.410  7319  7373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 17:17:45.410  7319  7373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 17:17:45.410  7319  7373 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-09 17:17:45.410  7319  7373 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 17:17:45.410  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 17:17:45.410  7319  7373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 17:17:45.410  7319  7373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 17:17:45.410  7319  7373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 17:17:45.410  7319  7373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:45.410  7319  7373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 17:17:45.410  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:45.410  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.410  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:17:45.410  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:17:45.410  7319  7373 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19e384db removed from the list
09-09 17:17:45.410  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.410  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34bc7b78 removed from the list
,09-09 17:17:45.420  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:45.420  7319  7373 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:45.420  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:17:45.420  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.420  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:17:45.420  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 17:17:45.420  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:45.420  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.420  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34bc7b78 not in the list
,09-09 17:17:45.420  7319  7373 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-09 17:17:45.420  7319  7373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:45.420  7319  7373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:45.420  7319  7373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:45.420  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:45.420  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.420  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.420  7319  7373 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19e384db not in the list
09-09 17:17:45.420  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.420  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34bc7b78 not in the list
09-09 17:17:45.420  7319  7373 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:45.420  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.420  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.420  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.420  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:17:45.420  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:45.420  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:45.420  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.420  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34bc7b78 not in the list
,09-09 17:17:45.430  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-09 17:17:45.430  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 17:17:45.430  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 17:17:45.430  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 17:17:45.430  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 17:17:45.430  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 17:17:45.430  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 17:17:45.430  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 17:17:45.430  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 17:17:45.430  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 17:17:45.430  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 17:17:45.430  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 17:17:45.430  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 17:17:45.430  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 17:17:45.430  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 17:17:45.430  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 17:17:45.430  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 17:17:45.430  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 17:17:45.430  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 17:17:45.430  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 17:17:45.430  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 17:17:45.430  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 17:17:45.430  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 17:17:45.430  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 17:17:45.430  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 17:17:45.430  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 17:17:45.430  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 17:17:45.430  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no pe,er name> 36:2610:2610:2610:2610:2610]
09-09 17:17:45.430  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 17:17:45.430  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 17:17:45.430  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 17:17:45.430  7319  7373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:45.430  7319  7373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:45.430  7319  7373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:45.430  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:45.430  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.430  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.430  7319  7373 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19e384db not in the list
09-09 17:17:45.430  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.430  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34bc7b78 not in the list
09-09 17:17:45.430  7319  7373 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:45.430  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.430  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.430  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.430  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.430  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:45.430  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:45.430  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.430  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34bc7b78 not in the list
09-09 17:17:45.430  7319  7373 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 17:17:45.440  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:17:45.440  7319  7373 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:17:45.440  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:45.440  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:17:45.440  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:17:45.440  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:17:45.440  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:17:45.440  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:17:45.440  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:17:45.440  7319  7373 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 17:17:45.440  7319  7373 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 17:17:45.440  7319  7373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:17:45.450  7319  7373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 17:17:45.450  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 17:17:45.450  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:17:45.450  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 17:17:45.450  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:45.450  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 17:17:45.450  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:45.460  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 17:17:45.460  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 17:17:45.470  7319  7373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-09 17:17:45.470  7319  7373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-09 17:17:45.470  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-09 17:17:45.470  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 17:17:45.470  7319  7373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-09 17:17:45.480  3225  3237 D BtGatt.GattService: registerClient() - UUID=68dfa7d6-b0b6-4e16-b490-6eb46cb30df6
,09-09 17:17:45.530  3225  3304 D BtGatt.GattService: onClientRegistered() - UUID=68dfa7d6-b0b6-4e16-b490-6eb46cb30df6, clientIf=6
,09-09 17:17:45.530  7319  7328 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-09 17:17:45.530  3225  3240 D BtGatt.GattService: start scan with filters
,09-09 17:17:45.540  3225  3351 D BtGatt.ScanManager: handling starting scan
,09-09 17:17:45.540  3225  3351 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29627d18
,09-09 17:17:45.540  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 17:17:45.540  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-09 17:17:45.540  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-09 17:17:45.540  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 17:17:45.550  3225  3304 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-09 17:17:45.550  3225  3304 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:17:45.550  3225  3351 D BtGatt.ScanManager: allow scan with filters
,09-09 17:17:45.550  3225  3351 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-09 17:17:45.550  3225  3351 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-09 17:17:45.550  7319  7373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 17:17:45.560  7319  7319 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 17:17:45.560  3225  3304 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-09 17:17:45.560  3225  3304 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:17:45.560  3225  3351 D BtGatt.ScanManager: Starting BLE batch scan
,09-09 17:17:45.560  3225  3351 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-09 17:17:45.560  7319  7373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 17:17:45.560  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 17:17:45.570  3225  3304 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-09 17:17:45.570  3225  3304 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:17:45.570  3225  3304 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-09 17:17:45.570  3225  3304 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:17:45.570  7319  7373 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 17:17:45.580  7319  7373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 17:17:45.580  7319  7373 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 17:17:45.580  7319  7373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:45.580  7319  7373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 17:17:45.580  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.580  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 17:17:45.580  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 17:17:45.580  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 17:17:45.580  7319  7373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 17:17:45.580  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 17:17:45.580  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 17:17:45.580  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 17:17:45.580  3225  3380 D BtGatt.GattService: stopScan() - queue size =1
,09-09 17:17:45.590  3225  3351 D BtGatt.ScanManager: filter size is 1
09-09 17:17:45.590  3225  3240 D BtGatt.GattService: unregisterClient() - clientIf=6
09-09 17:17:45.590  3225  3351 D BtGatt.ScanManager: delete FilterIndex - 3
09-09 17:17:45.590  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:17:45.590  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 17:17:45.590  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 17:17:45.590  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 17:17:45.590  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 17:17:45.590  3225  3304 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
09-09 17:17:45.590  3225  3304 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 17:17:45.590  3225  3351 D BtGatt.ScanManager: stopping BLe Batch,
,09-09 17:17:45.590  7319  7373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 17:17:45.590  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
09-09 17:17:45.600  7319  7373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 17:17:45.600  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 17:17:45.600  3225  3304 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-09 17:17:45.600  3225  3304 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 17:17:45.600  3225  3351 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-09 17:17:45.600  3225  3304 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-09 17:17:45.600  3225  3304 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:17:45.600  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 17:17:45.600  7319  7319 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 17:17:45.600  7319  7319 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:17:45.600  7319  7319 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 17:17:45.600  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:45.600  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.600  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:17:45.600  7319  7373 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19e384db not in the list
09-09 17:17:45.600  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.600  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34bc7b78 not in the list
09-09 17:17:45.600  7319  7373 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:45.600  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:17:45.600  7319  7373 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-09 17:17:45.600  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:17:45.610  7319  7373 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:17:45.610  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:45.610  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:17:45.610  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:17:45.610  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:17:45.610  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:17:45.610  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:17:45.610  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 17:17:45.610  7319  7373 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 17:17:45.610  7319  7373 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 17:17:45.620  7319  7373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:17:45.620  7319  7373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 17:17:45.620  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 17:17:45.620  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:17:45.620  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 17:17:45.620  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:45.620  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:45.620  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 17:17:45.630  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 17:17:45.630  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 17:17:45.630  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 17:17:45.630  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-09 17:17:45.630  7319  7373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 17:17:45.640  3225  3240 D BtGatt.GattService: registerClient() - UUID=efc8b3aa-2740-4728-987e-b6d97e3ac519
,09-09 17:17:45.680  3225  3304 D BtGatt.GattService: onClientRegistered() - UUID=efc8b3aa-2740-4728-987e-b6d97e3ac519, clientIf=6,
09-09 17:17:45.680  7319  7366 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-09 17:17:45.680  3225  3366 D BtGatt.GattService: start scan with filters,
09-09 17:17:45.680  3225  3351 D BtGatt.ScanManager: handling starting scan
,09-09 17:17:45.680  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
09-09 17:17:45.680  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-09 17:17:45.680  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-09 17:17:45.680  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-09 17:17:45.680  7319  7373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 17:17:45.690  7319  7373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 17:17:45.690  7319  7319 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 17:17:45.690  3225  3304 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-09 17:17:45.690  3225  3304 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 17:17:45.690  3225  3351 D BtGatt.ScanManager: allow scan with filters
09-09 17:17:45.690  3225  3351 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-09 17:17:45.690  3225  3351 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,09-09 17:17:45.690  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 17:17:45.690  3225  3304 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-09 17:17:45.690  3225  3304 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:17:45.700  3225  3351 D BtGatt.ScanManager: Starting BLE batch scan
,09-09 17:17:45.700  3225  3351 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-09 17:17:45.700  7319  7373 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 17:17:45.700  7319  7373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 17:17:45.700  7319  7373 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-09 17:17:45.700  7319  7373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 17:17:45.700  7319  7373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-09 17:17:45.700  3225  3304 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-09 17:17:45.700  3225  3304 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:17:45.700  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:17:45.710  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 17:17:45.710  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 17:17:45.710  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 17:17:45.710  7319  7373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 17:17:45.710  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 17:17:45.710  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 17:17:45.710  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 17:17:45.710  3225  3237 D BtGatt.GattService: stopScan() - queue size =1
,09-09 17:17:45.710  3225  3240 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-09 17:17:45.710  3225  3304 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-09 17:17:45.710  3225  3304 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:17:45.720  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:17:45.720  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 17:17:45.720  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 17:17:45.720  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 17:17:45.720  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 17:17:45.720  3225  3351 D BtGatt.ScanManager: filter size is 1
,09-09 17:17:45.720  3225  3351 D BtGatt.ScanManager: delete FilterIndex - 4
09-09 17:17:45.720  7319  7373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 17:17:45.720  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 17:17:45.720  7319  7373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 17:17:45.720  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 17:17:45.720  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 17:17:45.720  7319  7319 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 17:17:45.720  7319  7319 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:17:45.720  7319  7319 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 17:17:45.720  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:45.720  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.720  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:17:45.720  7319  7373 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19e384db not in the list
09-09 17:17:45.720  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.720  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34bc7b78 not in the list
09-09 17:17:45.720  7319  7373 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:45.720  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.720  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.720  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:17:45.720  3225  3304 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-09 17:17:45.720  3225  3304 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 17:17:45.730  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 17:17:45.730  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:45.730  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.730  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34bc7b78 not in the list
,09-09 17:17:45.730  7319  7373 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-09 17:17:45.730  3225  3351 D BtGatt.ScanManager: stopping BLe Batch
,09-09 17:17:45.730  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:17:45.740  3225  3304 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-09 17:17:45.740  3225  3304 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 17:17:45.740  3225  3351 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-09 17:17:45.740  7319  7373 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:17:45.740  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:45.740  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:17:45.740  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:17:45.740  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:17:45.740  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:17:45.740  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:17:45.740  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 17:17:45.740  3225  3304 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-09 17:17:45.740  3225  3304 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:17:45.740  7319  7373 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 17:17:45.750  7319  7373 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 17:17:45.750  7319  7373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:17:45.750  7319  7373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 17:17:45.750  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 17:17:45.750  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:17:45.750  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 17:17:45.750  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:45.750  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:45.750  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 17:17:45.760  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 17:17:45.760  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 17:17:45.760  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 17:17:45.760  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-09 17:17:45.760  7319  7373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 17:17:45.770  3225  3366 D BtGatt.GattService: registerClient() - UUID=d9f3238a-c8ad-412e-88bc-de70d9d070e0
,09-09 17:17:45.820  3225  3304 D BtGatt.GattService: onClientRegistered() - UUID=d9f3238a-c8ad-412e-88bc-de70d9d070e0, clientIf=6
,09-09 17:17:45.820  7319  7327 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-09 17:17:45.820  3225  3380 D BtGatt.GattService: start scan with filters
,09-09 17:17:45.820  3225  3351 D BtGatt.ScanManager: handling starting scan
,09-09 17:17:45.820  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
09-09 17:17:45.820  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-09 17:17:45.820  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-09 17:17:45.820  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 17:17:45.820  3225  3304 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-09 17:17:45.820  3225  3304 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:17:45.820  3225  3351 D BtGatt.ScanManager: allow scan with filters
09-09 17:17:45.820  3225  3351 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-09 17:17:45.820  3225  3351 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-09 17:17:45.820  7319  7373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 17:17:45.820  7319  7319 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 17:17:45.820  7319  7373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 17:17:45.830  3225  3304 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-09 17:17:45.830  3225  3304 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:17:45.830  3225  3351 D BtGatt.ScanManager: Starting BLE batch scan
09-09 17:17:45.830  3225  3351 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-09 17:17:45.830  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 17:17:45.840  7319  7373 I io.jxcore.node.ConnectionHelper: start: OK
09-09 17:17:45.840  7319  7373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:45.840  7319  7373 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 17:17:45.840  7319  7373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:45.840  7319  7373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 17:17:45.840  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.840  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 17:17:45.840  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 17:17:45.840  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 17:17:45.840  7319  7373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 17:17:45.840  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 17:17:45.840  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 17:17:45.840  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 17:17:45.840  3225  3304 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-09 17:17:45.840  3225  3304 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:17:45.840  3225  3366 D BtGatt.GattService: stopScan() - queue size =1
,09-09 17:17:45.840  3225  3380 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-09 17:17:45.840  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 17:17:45.840  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 17:17:45.840  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-09 17:17:45.840  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-09 17:17:45.840  3225  3304 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-09 17:17:45.850  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 17:17:45.850  3225  3304 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:17:45.850  3225  3351 D BtGatt.ScanManager: filter size is 1
,09-09 17:17:45.850  3225  3351 D BtGatt.ScanManager: delete FilterIndex - 5
,09-09 17:17:45.850  7319  7373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 17:17:45.850  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 17:17:45.850  7319  7373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 17:17:45.850  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 17:17:45.850  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 17:17:45.860  7319  7319 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 17:17:45.860  3225  3304 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-09 17:17:45.860  7319  7373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:45.860  7319  7373 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 17:17:45.860  7319  7373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:45.860  7319  7373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:45.860  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:45.860  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.860  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:17:45.860  7319  7373 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19e384db not in the list
09-09 17:17:45.860  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.860  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34bc7b78 not in the list
09-09 17:17:45.860  7319  7373 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:45.860  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.860  3225  3304 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:17:45.860  3225  3351 D BtGatt.ScanManager: stopping BLe Batch
09-09 17:17:45.860  7319  7319 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:17:45.860  7319  7319 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 17:17:45.860  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.860  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:17:45.860  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 17:17:45.860  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:45.860  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.860  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34bc7b78 not in the list
,09-09 17:17:45.860  7319  7373 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-09 17:17:45.860  7319  7373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 17:17:45.860  7319  7373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:45.860  7319  7373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 17:17:45.870  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 17:17:45.870  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.870  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.870  7319  7373 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19e384db not in the list
,09-09 17:17:45.870  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 17:17:45.870  3225  3304 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-09 17:17:45.870  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34bc7b78 not in the list
09-09 17:17:45.870  7319  7373 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:45.870  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.870  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.870  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.870  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:17:45.870  3225  3304 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 17:17:45.870  3225  3351 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-09 17:17:45.870  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 17:17:45.870  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:45.870  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 17:17:45.870  3225  3304 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-09 17:17:45.870  3225  3304 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:17:45.870  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34bc7b78 not in the list
,09-09 17:17:45.870  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-09 17:17:45.870  7319  7373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 17:17:45.870  7319  7373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:45.870  7319  7373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 17:17:45.880  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:45.880  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.880  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:17:45.880  7319  7373 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19e384db not in the list
09-09 17:17:45.880  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.880  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34bc7b78 not in the list
,09-09 17:17:45.880  7319  7373 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:45.880  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.880  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.880  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:17:45.880  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:17:45.880  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 17:17:45.880  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:45.880  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.880  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34bc7b78 not in the list
,09-09 17:17:45.880  7319  7373 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-09 17:17:45.880  7319  7373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:45.880  7319  7373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:45.880  7319  7373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:45.880  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:45.880  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.880  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.880  7319  7373 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19e384db not in the list
09-09 17:17:45.880  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.880  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34bc7b78 not in the list
09-09 17:17:45.880  7319  7373 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:45.880  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.880  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.880  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.880  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:17:45.880  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:45.880  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:45.880  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.880  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34bc7b78 not in the list
,09-09 17:17:45.880  7319  7373 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-09 17:17:45.880  7319  7373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:45.880  7319  7373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:45.880  7319  7373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:45.880  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:45.880  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.880  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.880  7319  7373 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19e384db not in the list
09-09 17:17:45.880  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.880  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34bc7b78 not in the list
09-09 17:17:45.880  7319  7373 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:45.880  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.880  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.880  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.880  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:17:45.890  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:45.890  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:45.890  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 17:17:45.890  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34bc7b78 not in the list
09-09 17:17:45.890  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-09 17:17:45.890  7319  7373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 17:17:45.890  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 17:17:45.890  7319  7373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 17:17:45.890  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 17:17:45.890  7319  7373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 17:17:45.890  7319  7373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:45.890  7319  7373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:45.890  7319  7373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:45.890  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:45.890  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.890  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.890  7319  7373 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19e384db not in the list
09-09 17:17:45.890  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.890  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34bc7b78 not in the list
09-09 17:17:45.890  7319  7373 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:45.890  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.890  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.890  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.890  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.890  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:45.890  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:45.890  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.890  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34bc7b78 not in the list
09-09 17:17:45.890  7319  7373 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 17:17:45.890  7319  7373 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 17:17:45.890  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-09 17:17:45.890  7319  7373 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 17:17:45.890  7319  7373 E io.jxcore.node.ConnectionHelper: connect: Maximum number ,of peer connections (30) reached, please try again after disconnecting a peer
09-09 17:17:45.890  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 17:17:45.890  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 17:17:45.890  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 17:17:45.890  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 17:17:45.890  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 17:17:45.890  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 17:17:45.890  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 17:17:45.890  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 17:17:45.890  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 17:17:45.890  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 17:17:45.890  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 17:17:45.890  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 17:17:45.890  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 17:17:45.890  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 17:17:45.890  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 17:17:45.890  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-09 17:17:45.890  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 17:17:45.890  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 17:17:45.890  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-09 17:17:45.890  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 17:17:45.890  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 17:17:45.890  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 17:17:45.890  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 17:17:45.890  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-09 17:17:45.890  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 17:17:45.890  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 17:17:45.890  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 17:17:45.890  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 17:17:45.890  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 17:17:45.890  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-09 17:17:45.890  7319  7373 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-09 17:17:45.890  7319  7373 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 17:17:45.890  7319  7373 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd,
09-09 17:17:45.890  7319  7373 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 17:17:45.890  7319  7373 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 17:17:45.890  7319  7373 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-09 17:17:45.890  7319  7373 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 17:17:45.890  7319  7373 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-09 17:17:45.890  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-09 17:17:45.910  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-09 17:17:45.910  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-09 17:17:45.910  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-09 17:17:45.910  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,09-09 17:17:45.910  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-09 17:17:45.910  7319  7373 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-09 17:17:45.910  7319  7373 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 17:17:45.910  7319  7373 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-09 17:17:45.910  7319  7373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:45.910  7319  7373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:45.910  7319  7373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:45.910  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:45.910  7319  7385 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1460)
09-09 17:17:45.910  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.910  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:17:45.910  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-09 17:17:45.910  7319  7373 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19e384db not in the list
09-09 17:17:45.910  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.910  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34bc7b78 not in the list
09-09 17:17:45.910  7319  7373 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:45.910  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.910  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.910  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.910  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.910  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 17:17:45.910  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:45.910  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.910  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34bc7b78 not in the list
09-09 17:17:45.910  7319  7373 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-09 17:17:45.910  7319  7373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:45.910  7319  7373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:45.910  7319  7373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:45.910  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:45.910  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.910  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.910  7319  7373 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19e384db not in the list
,09-09 17:17:45.910  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.910  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34bc7b78 not in the list
09-09 17:17:45.910  7319  7373 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:45.910  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.910  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.910  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.910  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.910  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:45.910  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:45.910  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.910  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34bc7b78 not in the list
09-09 17:17:45.910  7319  7386 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1460
09-09 17:17:45.910  7319  7373 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-09 17:17:45.910  7319  7373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:45.910  7319  7373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:45.910  7319  7373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:45.910  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:45.910  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.910  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.910  7319  7373 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19e384db not in the list
09-09 17:17:45.910  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.910  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34bc7b78 not in the list
09-09 17:17:45.910  7319  7373 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:45.910  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.910  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:17:45.910  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.910  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:17:45.920  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:45.920  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:45.920  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.920  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34bc7b78 not in the list
,09-09 17:17:45.920  7319  7373 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-09 17:17:45.920  7319  7373 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-09 17:17:45.920  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 17:17:45.920  7319  7373 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-09 17:17:45.920  7319  7373 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 17:17:45.920  7319  7373 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-09 17:17:45.920  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 17:17:45.920  7319  7373 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-09 17:17:45.920  7319  7373 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 17:17:45.920  7319  7373 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 17:17:45.920  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 17:17:45.920  7319  7373 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,09-09 17:17:45.920  7319  7373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:45.920  7319  7373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:45.920  7319  7373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 17:17:45.920  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:45.920  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.920  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.920  7319  7373 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19e384db not in the list
09-09 17:17:45.920  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-09 17:17:45.920  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34bc7b78 not in the list
09-09 17:17:45.920  7319  7373 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:45.920  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.920  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.920  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.920  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.920  7319  7385 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
,09-09 17:17:45.920  7319  7385 D BluetoothSocket: connect(): myUserId = 0,
09-09 17:17:45.920  7319  7385 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 17:17:45.920  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:45.920  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:45.920  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.920  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34bc7b78 not in the list
,09-09 17:17:45.920  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:45.920  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.920  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.920  7319  7373 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19e384db not in the list
,09-09 17:17:45.920  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.920  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34bc7b78 not in the list
09-09 17:17:45.920  7319  7373 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:45.920  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:17:45.920  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.920  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.920  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34bc7b78 not in the list
09-09 17:17:45.920  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:45.920  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.920  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.920  7319  7373 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19e384db not in the list
09-09 17:17:45.920  7319  7373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:45.920  7319  7373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 17:17:45.920  7319  7373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:45.930  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:45.930  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.930  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.930  7319  7373 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19e384db not in the list
09-09 17:17:45.930  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.930  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34bc7b78 not in the list
09-09 17:17:45.930  7319  7373 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 17:17:45.930  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.930  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.930  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.930  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.930  3225  3240 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:17:45.930  7319  7385 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[105]}
09-09 17:17:45.930  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:45.930  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:45.930  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.930  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34bc7b78 not in the list
,09-09 17:17:45.930  7319  7373 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 17:17:45.930  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:17:45.930  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-09 17:17:45.930  7319  7373 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 17:17:45.930  7319  7373 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-09 17:17:45.930  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 17:17:45.930  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 17:17:45.930  7319  7319 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 17:17:45.930  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:45.930  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 17:17:45.930  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 17:17:45.930  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-09 17:17:45.930  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.930  7319  7373 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 17:17:45.930  7319  7373 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19e384db not in the list
09-09 17:17:45.930  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.930  7319  7319 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 17:17:45.930  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 17:17:45.930  7319  7373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 17:17:45.930  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 17:17:45.930  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:17:45.930  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.930  7319  7387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 17:17:45.930  7319  7387 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-09 17:17:45.930  7319  7373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 17:17:45.940  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34bc7b78 not in the list
09-09 17:17:45.940  7319  7373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:45.940  7319  7373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:45.940  7319  7373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:45.940  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:45.940  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.940  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.940  7319  7373 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19e384db not in the list
09-09 17:17:45.940  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.940  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34bc7b78 not in the list
09-09 17:17:45.940  7319  7373 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:45.940  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.940  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.940  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.940  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:17:45.940  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:45.940  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:45.940  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.940  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34bc7b78 not in the list
09-09 17:17:45.940  7319  7319 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:17:45.940  7319  7319 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:17:45.940  7319  7319 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-09 17:17:45.940  7319  7319 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 17:17:45.940  7319  7373 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-09 17:17:45.940  7319  7373 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 17:17:45.940  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 17:17:45.940  7319  7373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 17:17:45.940  7319  7373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:45.940  7319  7373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:45.940  7319  7373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 17:17:45.940  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:45.940  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.940  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.940  7319  7373 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19e384db not in the list
09-09 17:17:45.940  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.940  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34bc7b78 not in the list
09-09 17:17:45.940  7319  7373 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:45.940  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.940  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.940  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.940  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.940  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:45.940  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:45.940  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.940  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34bc7b78 not in the list
,09-09 17:17:45.940  7319  7373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:45.940  7319  7373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:45.940  7319  7373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:45.940  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
09-09 17:17:45.940  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.940  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.940  7319  7373 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19e384db not in the list
09-09 17:17:45.940  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.940  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34bc7b78 not in the list
09-09 17:17:45.940  7319  7373 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:45.940  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:17:45.940  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.940  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.940  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.940  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:45.940  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:45.940  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.940  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34bc7b78 not in the list,
09-09 17:17:45.940  7319  7373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:45.940  7319  7373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:45.940  7319  7373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:45.940  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:45.940  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:17:45.940  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.940  7319  7373 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19e384db not in the list
09-09 17:17:45.940  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.940  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34bc7b78 not in the list
09-09 17:17:45.940  7319  7373 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 17:17:45.940  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.940  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.940  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.940  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.950  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 17:17:45.950  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:45.950  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.950  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34bc7b78 not in the list
09-09 17:17:45.950  7319  7373 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-09 17:17:45.950  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 17:17:45.950  7319  7373 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,09-09 17:17:45.950  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 17:17:45.950  7319  7373 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-09 17:17:45.950  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 17:17:45.950  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 17:17:45.950  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-09 17:17:45.950  7319  7373 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-09 17:17:45.950  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 17:17:45.950  7319  7373 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-09 17:17:45.950  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 17:17:45.950  7319  7373 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,09-09 17:17:45.950  7319  7373 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-09 17:17:45.950  7319  7373 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-09 17:17:45.950  7319  7373 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-09 17:17:45.950  7319  7373 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-09 17:17:45.950  7319  7373 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,09-09 17:17:45.950  7319  7373 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-09 17:17:45.950  7319  7373 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-09 17:17:45.950  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 17:17:45.950  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@337dd19a added. We now have 2 listener(s)
09-09 17:17:45.950  7319  7373 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
09-09 17:17:45.950  7319  7373 D BluetoothAdapter: enable()
,09-09 17:17:45.950  7319  7373 D BluetoothAdapter: enable(): BT is already enabled..!
,09-09 17:17:45.960  1015  1466 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-09 17:17:45.960  1015  1466 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-09 17:17:45.960  1015  1466 D SecContentProvider2: mCursor = null
,09-09 17:17:45.960  1015  1466 D WifiService: setWifiEnabled: true pid=7319, uid=10170
09-09 17:17:45.960  1015  1466 W ActivityManager: Permission Denial: getCurrentUser() from pid=7319, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-09 17:17:45.960  1015  1466 W WifiService: Failed getting userId using ActivityManagerNative,
09-09 17:17:45.960  1015  1466 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7319, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-09 17:17:45.960  1015  1466 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-09 17:17:45.960  1015  1466 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-09 17:17:45.960  1015  1466 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-09 17:17:45.960  1015  1466 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-09 17:17:45.960  1015  1466 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-09 17:17:45.960  1015  1466 D SettingsProvider: name = wifi_on
,09-09 17:17:45.960  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:17:45.960  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@398b5acb added. We now have 3 listener(s)
09-09 17:17:45.960  7319  7373 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 17:17:45.970  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:17:45.970  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3a01b2a8 added. We now have 4 listener(s)
09-09 17:17:45.970  7319  7373 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 17:17:45.970  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:17:45.970  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d1871c1 added. We now have 5 listener(s)
09-09 17:17:45.970  7319  7373 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 17:17:45.970  1015  1505 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-09 17:17:45.970  1015  1505 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-09 17:17:45.970  1015  1505 D SecContentProvider2: mCursor = null
,09-09 17:17:45.970  1015  1505 D WifiService: setWifiEnabled: false pid=7319, uid=10170
,09-09 17:17:45.970  1015  1505 D SettingsProvider: name = wifi_on
,09-09 17:17:45.980  7319  7373 D BluetoothAdapter: disable()
,09-09 17:17:45.980  1015  1127 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-09 17:17:45.980  1015  1504 D SettingsProvider: name = bluetooth_on
09-09 17:17:45.980  1370  1370 I wpa_supplicant: reset timer : RESET_TIMER 0
09-09 17:17:45.980  1370  1370 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
09-09 17:17:45.980  1370  1370 I wpa_supplicant: P2P: Current p2p state = IDLE
09-09 17:17:45.980  1370  1370 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-09 17:17:45.990  1015  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,09-09 17:17:46.000  3225  3301 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF,
09-09 17:17:46.000  3225  3301 D BluetoothAdapterProperties: Setting state to 13
09-09 17:17:46.000  3225  3301 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-09 17:17:46.000  1015  1244 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:17:46.000  3225  3301 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-09 17:17:46.000  1015  1244 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
09-09 17:17:46.000  3225  3301 D BluetoothAdapterService: updateAdapterState state is 13
,09-09 17:17:46.000  1015  1244 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:46.000  1015  1244 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:46.000  1015  1244 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:46.010  3225  3225 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-09 17:17:46.010  1370  1370 I wpa_supplicant: Scan aborted because the firmware maybe busy.,
09-09 17:17:46.010  1370  1370 I wpa_supplicant: Therefore we will repeat the scan command after 1 seconds.
09-09 17:17:46.010  1370  1370 I wpa_supplicant: wlan0: Setting scan request: 1 sec 0 usec
09-09 17:17:46.010  1015  1127 E WifiNative-wlan0: do suspend true
,09-09 17:17:46.010  3225  3301 D BluetoothAdapterService: Autoconnection is available 
09-09 17:17:46.010  3225  3225 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@37e701d8, channel: 19, state: LISTENING
09-09 17:17:46.010  3225  3225 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@37e701d8, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@f289ac0, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@34fbc931mSocket: android.net.LocalSocket@1367c816 impl:android.net.LocalSocketImpl@392b1597 fd:FileDescriptor[80]
09-09 17:17:46.010  3225  3225 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1367c816 impl:android.net.LocalSocketImpl@392b1597 fd:FileDescriptor[80]
,09-09 17:17:46.010  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:17:46.010  3225  3301 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-09 17:17:46.010  3225  3301 D BluetoothAdapterService: terminating service from this receiver
,09-09 17:17:46.010  1015  3282 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-09 17:17:46.010  1015  3282 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:46.010  1015  3282 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:46.010  1015  3282 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 17:17:46.010  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:46.010  7319  7373 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:17:46.010  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:46.010  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:17:46.010  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:17:46.010  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
,09-09 17:17:46.010  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:17:46.010  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
,09-09 17:17:46.010  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:17:46.020  3225  3301 D BluetoothAdapterProperties: onBluetoothDisable()
09-09 17:17:46.020  3225  3301 D BluetoothAdapterProperties: mDiscovering is false
09-09 17:17:46.020  1015  1505 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-09 17:17:46.020  3225  3301 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-09 17:17:46.020  4743  4743 D BluetoothPbap: Proxy object disconnected
09-09 17:17:46.020  4743  4743 D PbapServerProfile: Bluetooth service disconnected
09-09 17:17:46.020  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:46.020  7319  7373 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 17:17:46.020  7319  7373 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 17:17:46.020  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:46.020  1015  1015 I InputMethodManagerService: [BT Setting State] State =13
,09-09 17:17:46.020  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:46.020  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:46.020  1015  3377 D SSRM:n  : SIOP:: AP = 370
,09-09 17:17:46.030  1178  1178 D BluetoothTile:  onBluetoothStateChange:
,09-09 17:17:46.030  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-09 17:17:46.030  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:46.030  1178  1178 D BluetoothTile:  getBluetoothState : 13
,09-09 17:17:46.030  2019  2019 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-09 17:17:46.030  1015  1505 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 17:17:46.030  1015  1491 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-09 17:17:46.030  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-09 17:17:46.040  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-09 17:17:46.040  1178  1704 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 17:17:46.040  4743  4743 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:17:46.040  7319  7319 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 17:17:46.040  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:17:46.040  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:46.040  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:17:46.040  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:17:46.040  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:17:46.040  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:17:46.040  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:17:46.040  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:17:46.040  7319  7319 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 17:17:46.040  7319  7319 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 17:17:46.050  3225  3304 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-09 17:17:46.050  3225  3304 D BluetoothAdapterProperties: Scan Mode:20
,09-09 17:17:46.050  1178  1704 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 17:17:46.050  3225  3301 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-09 17:17:46.050  3225  3301 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
09-09 17:17:46.050  3225  3301 E bt-btif : cmd socket is not created
09-09 17:17:46.050  3225  5310 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 17:17:46.050  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:46.050  7319  7385 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2572d8a7, channel: -1, state: INIT
09-09 17:17:46.050  7319  7385 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2572d8a7, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@28135154, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2df968fdmSocket: android.net.LocalSocket@1dcf9f2 impl:android.net.LocalSocketImpl@226a5843 fd:FileDescriptor[105]
09-09 17:17:46.050  7319  7385 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1dcf9f2 impl:android.net.LocalSocketImpl@226a5843 fd:FileDescriptor[105]
09-09 17:17:46.050  7319  7385 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1460)
,09-09 17:17:46.050  3225  3305 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,09-09 17:17:46.050  3225  3301 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-09 17:17:46.050  1178  1704 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-09 17:17:46.050  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:46.060  3225  3305 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-09 17:17:46.060  3225  3305 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 17:17:46.060  3225  3305 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 17:17:46.060  3225  3305 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 17:17:46.060  3225  3305 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-09 17:17:46.060  3225  3305 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 17:17:46.060  4743  4743 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 17:17:46.060  1015  3282 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-09 17:17:46.060  3225  3225 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@912c76d, channel: 5, state: LISTENING
09-09 17:17:46.060  3225  3225 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@912c76d, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3f093f9, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1104fa2mSocket: android.net.LocalSocket@25817433 impl:android.net.LocalSocketImpl@3bf833f0 fd:FileDescriptor[82]
09-09 17:17:46.060  3225  3225 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@25817433 impl:android.net.LocalSocketImpl@3bf833f0 fd:FileDescriptor[82]
,09-09 17:17:46.060  1015  3282 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-09 17:17:46.060  3225  3225 I BtOppRfcommListener: stopping Accept Thread
09-09 17:17:46.060  3225  3225 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@4216d69, channel: 12, state: LISTENING
09-09 17:17:46.060  3225  3225 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@4216d69, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3e64a8bb, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@39c7c3eemSocket: android.net.LocalSocket@2fd5208f impl:android.net.LocalSocketImpl@b449f1c fd:FileDescriptor[87]
09-09 17:17:46.060  3225  3225 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2fd5208f impl:android.net.LocalSocketImpl@b449f1c fd:FileDescriptor[87]
09-09 17:17:46.060  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:46.060  1015  3282 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:46.060  1015  3282 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:46.060  1015  3282 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-09 17:17:46.070  3225  5310 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-09 17:17:46.070  3225  3305 W bt-sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
,09-09 17:17:46.070  3225  3305 E bt-btif : DISCOVERY_COMP_EVT slot id:4, failed to find channle,                                       status:1, scn:0
09-09 17:17:46.070  3225  3305 W bt-btif : invalid rfc slot id: 4
,09-09 17:17:46.070  1698  1698 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 17:17:46.070  3225  3225 V BluetoothOppManager: cleanUp...
,09-09 17:17:46.080  4743  4743 D DockEventReceiver: finishStartingService: stopping service
,09-09 17:17:46.080  4743  4743 D BluetoothNotiBroadcastReceiver: onReceive
,09-09 17:17:46.080  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED,
09-09 17:17:46.080  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-09 17:17:46.090  1015  1346 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-09 17:17:46.090  1015  1126 D WifiP2pService: InactiveState{ what=143375 }
,09-09 17:17:46.090  1015  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:46.090  1015  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
09-09 17:17:46.090  1015  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:46.090  1015  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:46.090  1015  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:46.100  7392  7392 E Zygote  : MountEmulatedStorage()
,09-09 17:17:46.100  7392  7392 E Zygote  : v2
09-09 17:17:46.100  7392  7392 I libpersona: KNOX_SDCARD checking this for 10055
09-09 17:17:46.100  7392  7392 I libpersona: KNOX_SDCARD not a persona
,09-09 17:17:46.100  1015  1346 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7392 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,09-09 17:17:46.110  7392  7392 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 17:17:46.110   277   966 D CommandListener: Clearing all IP addresses on wlan0
,09-09 17:17:46.110  7392  7392 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 17:17:46.110  7392  7392 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 17:17:46.110  1698  2531 V NativeCrypto: Read error: ssl=0xb88a3b28: I/O error during system call, Connection timed out
,09-09 17:17:46.110  1698  2531 V NativeCrypto: SSL shutdown failed: ssl=0xb88a3b28: I/O error during system call, Broken pipe
,09-09 17:17:46.120  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-09 17:17:46.120  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-09 17:17:46.120  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:46.120  1015  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 17:17:46.120  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:46.120  1015  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
09-09 17:17:46.120  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:46.120  1015  1028 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,09-09 17:17:46.120  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:46.120  1015  1129 E ConnectivityService: updateNetworkInfo()
09-09 17:17:46.120  1015  1129 E ConnectivityService: updateNetworkInfo()
,09-09 17:17:46.120  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-09 17:17:46.120  1015  1751 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:46.120  1015  1751 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:46.120  1015  1751 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-09 17:17:46.120  1015  1751 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:46.120  1015  1751 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
09-09 17:17:46.120  1015  1751 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-09 17:17:46.120  1015  1751 I qtaguid : Tagging socket 347 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1015, getuid(): 1000
,09-09 17:17:46.130  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1
09-09 17:17:46.130  1015  1150 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 17:17:46.130  1015  1015 D RttService: SCAN_AVAILABLE : 1
09-09 17:17:46.130  1015  1151 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 17:17:46.130  1015  1127 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-09 17:17:46.130  1015  1751 I qtaguid : Untagging socket 347
09-09 17:17:46.130  1015  1751 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-09 17:17:46.140  1015  1126 D WifiP2pService: InactiveState{ what=131204 }
,09-09 17:17:46.140  1015  1126 D WifiP2pService: P2pEnabledState{ what=131204 }
,09-09 17:17:46.140  1015  1126 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-09 17:17:46.140  1015  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:17:46.140  1015  1047 D WifiDisplayAdapter: onP2pDisconnected
,09-09 17:17:46.140  1015  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-09 17:17:46.150  1015  1126 D WifiP2pService: P2pDisablingState
09-09 17:17:46.150  1015  1126 D WifiP2pService: P2pDisablingState{ what=147458 }
09-09 17:17:46.150  1015  1126 D WifiP2pService: p2p socket connection lost
09-09 17:17:46.150  1015  1126 D WifiP2pService: P2pDisabledState
09-09 17:17:46.150  1015  1127 E WifiNative-wlan0: do suspend true
09-09 17:17:46.150  1015  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 17:17:46.150  1015  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
09-09 17:17:46.150  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-09 17:17:46.150  1015  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-09 17:17:46.150  1015  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 17:17:46.150  1015  1047 D WifiDisplayController: disconnect
09-09 17:17:46.150  1015  1047 D WifiDisplayController: updateConnection
09-09 17:17:46.150  1015  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 17:17:46.150  1015  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-09 17:17:46.150  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-09 17:17:46.150  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 17:17:46.150  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 17:17:46.150  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:46.150  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:46.150  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:46.150  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:17:46.160  7392  7392 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 17:17:46.160  1015  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-09 17:17:46.160  1015  1047 D WifiDisplayAdapter: onP2pDisconnected
09-09 17:17:46.160  7392  7392 D ActivityThread: Added TimaKeyStore provider,
09-09 17:17:46.160  1015  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 17:17:46.160  1015  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-09 17:17:46.170  1178  1178 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-09 17:17:46.170  1015  3280 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-09 17:17:46.170  1178  1178 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-09 17:17:46.190  1015  1126 D WifiP2pService: P2pDisabledState{ what=143375 }
,09-09 17:17:46.190  1015  1126 D WifiP2pService: DefaultState{ what=143375 }
,09-09 17:17:46.190  7392  7392 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-09 17:17:46.190  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-09 17:17:46.190  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 17:17:46.190  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-09 17:17:46.200  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-09 17:17:46.200  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:46.200  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:46.200  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:17:46.230  7392  7392 D UserAnalysis.SecureDbManager: Key for secure DB is newly created,
,09-09 17:17:46.230  7392  7392 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-09 17:17:46.230  7392  7392 D UserAnalysis: Create SecureDbHelper
,09-09 17:17:46.230  7392  7392 D IntelligenceServiceApplication: onCreate(),
,09-09 17:17:46.240  1015  1346 I ActivityManager: Killing 6959:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,09-09 17:17:46.240   277   966 D CommandListener: Clearing all IP addresses on wlan0
09-09 17:17:46.240   277   962 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-09 17:17:46.240   277   962 D Netd    : getNetworkForDns: using netid 0 for uid 1000
09-09 17:17:46.240  1015  1129 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,09-09 17:17:46.240  1015  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:17:46.240  1015  1129 V NetworkStats: updateIfacesLocked()
09-09 17:17:46.240  1015  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 17:17:46.240  1015  1129 V NetworkStats: performPollLocked(flags=0x1)
09-09 17:17:46.240  1015  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 17:17:46.240  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-09 17:17:46.250  1015  1751 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
09-09 17:17:46.250  1015  1751 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-09 17:17:46.250  7392  7392 D IntelligenceServiceApplication: no applications having user consent for prediction
09-09 17:17:46.250  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:46.250  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-09 17:17:46.250  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:46.250  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:46.250  1015  1129 V NetworkStats: performPollLocked() took 7ms
09-09 17:17:46.250  1015  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:17:46.260  7413  7413 E Zygote  : MountEmulatedStorage()
,09-09 17:17:46.260  7413  7413 E Zygote  : v2
09-09 17:17:46.260  7413  7413 I libpersona: KNOX_SDCARD checking this for 10105
09-09 17:17:46.260  7413  7413 I libpersona: KNOX_SDCARD not a persona
,09-09 17:17:46.270  1015  1027 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7413 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,09-09 17:17:46.270  7413  7413 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 17:17:46.270  1015  3280 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-09 17:17:46.270  3225  3301 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-09 17:17:46.270  3225  3301 D BtConfig.SecureMode: isSecureModeOn:false
09-09 17:17:46.270  3225  3301 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-09 17:17:46.270  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
09-09 17:17:46.270  7392  7392 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
09-09 17:17:46.270  3225  3301 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
09-09 17:17:46.270  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-09 17:17:46.270  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-09 17:17:46.270  3225  3301 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-09 17:17:46.270  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-09 17:17:46.270  1370  1370 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
09-09 17:17:46.270  7413  7413 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 17:17:46.270  7413  7413 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-09 17:17:46.280  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:17:46.280  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-09 17:17:46.280  1015  1129 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
09-09 17:17:46.280  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:46.280  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:46.280  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 17:17:46.280  1015  1129 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-09 17:17:46.280  1015  1751 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:46.280  1015  1129 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
09-09 17:17:46.280  1015  1126 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-09 17:17:46.280  1015  1129 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
09-09 17:17:46.280  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
09-09 17:17:46.280  1015  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE,
09-09 17:17:46.280  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-09 17:17:46.280  1178  1677 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-09 17:17:46.280  1478  1478 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-09 17:17:46.280  1478  1478 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-09 17:17:46.280  3225  3301 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
09-09 17:17:46.280  3225  3225 D HeadsetService: Received stop request...Stopping profile...
,09-09 17:17:46.290  1015  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:17:46.290  1015  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:17:46.290   303   303 I art     : Explicit concurrent mark sweep GC freed 8725(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 677us total 24.218ms
,09-09 17:17:46.290  1015  1127 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-09 17:17:46.290  1015  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 17:17:46.290  1015  1127 D SecContentProvider2: mCursor = null
09-09 17:17:46.290  7392  7392 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
09-09 17:17:46.290  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-09 17:17:46.290  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 17:17:46.290  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 17:17:46.290  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:46.290  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:46.290  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:46.290  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:46.300  1015  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-09 17:17:46.300  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-09 17:17:46.300  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 17:17:46.300  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 17:17:46.300  1178  1704 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-09 17:17:46.300  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-09 17:17:46.300  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:46.300  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:46.300  1178  1178 D HotspotTile: onReceive : 0, 0
09-09 17:17:46.300  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:46.300  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:46.300  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 17:17:46.300  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,09-09 17:17:46.300  4743  4743 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-09 17:17:46.310   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 716us total 18.459ms
,09-09 17:17:46.310  1015  1129 D ConnectivityService: nai.networkMonitor.doQuit()
09-09 17:17:46.310  1015  1129 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-09 17:17:46.310  1015  1129 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 17:17:46.310  1015  1129 E ConnectivityService: updateNetworkInfo()
09-09 17:17:46.310  1015  1129 E ConnectivityService: updateNetworkInfo()
09-09 17:17:46.310  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,09-09 17:17:46.310  1015  1130 D Tethering: MasterInitialState.processMessage what=3
09-09 17:17:46.310  1015  1124 V NetworkStats: updateIfacesLocked()
09-09 17:17:46.310  1015  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-09 17:17:46.310  1015  1124 V NetworkStats: performPollLocked(flags=0x1)
09-09 17:17:46.310  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:17:46.320  1015  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 17:17:46.320  1015  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 17:17:46.320  3225  3225 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29627d18
,09-09 17:17:46.320  7319  7319 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:46.320  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:17:46.320  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:46.320  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:17:46.320  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:17:46.320  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:17:46.320  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:17:46.320  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:17:46.320  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:17:46.320  7319  7319 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:46.320  7319  7319 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 17:17:46.320  1015  1124 V NetworkStats: performPollLocked() took 10ms
09-09 17:17:46.320  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:17:46.330   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 685us total 18.031ms
09-09 17:17:46.330  1178  1178 D StatusBar.NetworkController: EthernetConnected: false
09-09 17:17:46.330  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-09 17:17:46.330  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-09 17:17:46.330  1178  1178 D StatusBar.NetworkController: updateDataNetType()
09-09 17:17:46.330  7319  7319 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:46.330  1015  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:17:46.330  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:17:46.330  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:46.330  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:17:46.330  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:17:46.330  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:17:46.330  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:17:46.330  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:17:46.330  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:17:46.330  7319  7319 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:46.330  7319  7319 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:17:46.330  1015  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:17:46.330  1015  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:17:46.330  1015  1125 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-09 17:17:46.330  1015  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:17:46.330  1015  3282 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:17:46.330  1015  3282 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 17:17:46.330  1015  3282 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:46.330  1015  3282 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:46.330  1015  3282 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:46.330  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-09 17:17:46.330  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-09 17:17:46.330  1178  1178 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-09 17:17:46.330  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
09-09 17:17:46.330  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-09 17:17:46.340  4743  4743 D HeadsetProfile: Bluetooth service disconnected
09-09 17:17:46.340  3225  3301 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-09 17:17:46.340  7413  7413 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 17:17:46.340  7413  7413 D ActivityThread: Added TimaKeyStore provider
,09-09 17:17:46.340  1015  1346 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:17:46.340  1015  1346 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-09 17:17:46.340  1015  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:17:46.340  1015  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:17:46.340  1015  1346 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:46.340  1015  1346 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:46.340  1015  1346 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:46.340  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
09-09 17:17:46.340  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-09 17:17:46.340  3225  3301 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-09 17:17:46.350  1178  1178 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-09 17:17:46.350  1015  1466 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:17:46.350  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 20 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
09-09 17:17:46.350  1015  1466 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
09-09 17:17:46.350  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
09-09 17:17:46.350  1015  1466 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:46.350  1015  1466 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:46.350  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
09-09 17:17:46.350  1015  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:46.350  1370  1370 I wpa_supplicant: Blacklist: Clear (all) 
09-09 17:17:46.350  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
09-09 17:17:46.350  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-09 17:17:46.350  3225  3301 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-09 17:17:46.350  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:17:46.350  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-09 17:17:46.350  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:46.350  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:46.350  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:46.350  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,09-09 17:17:46.350  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 17:17:46.350  3225  3301 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
09-09 17:17:46.350  1015  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:17:46.350  1015  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
09-09 17:17:46.350  1015  1491 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:46.350  1015  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:46.350  1015  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 17:17:46.360  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
09-09 17:17:46.360  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-09 17:17:46.360  3225  3301 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
09-09 17:17:46.360  1015  3283 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:17:46.360  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-09 17:17:46.360  1015  3283 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
09-09 17:17:46.360  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 17:17:46.360  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,09-09 17:17:46.360  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:46.360  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:46.360  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:46.360  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:46.360  1015  3283 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:46.360  1015  3283 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:46.360  1015  3283 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 17:17:46.360  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-09 17:17:46.360  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-09 17:17:46.360  3225  3301 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-09 17:17:46.360  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-09 17:17:46.360  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-09 17:17:46.360  3225  3301 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-09 17:17:46.360  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-09 17:17:46.360  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-09 17:17:46.360  3225  3301 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-09 17:17:46.360  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-09 17:17:46.360  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-09 17:17:46.360  3225  3301 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-09 17:17:46.360  3225  3301 D BluetoothAdapterState: Stopping profile services that were post enabled
09-09 17:17:46.360  3225  3225 E BluetoothAdapterService(694320408): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-09 17:17:46.360  3225  3225 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 17:17:46.360  3225  3225 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-09 17:17:46.360  3225  3225 D A2dpService: Received stop request...Stopping profile...
,09-09 17:17:46.360  3225  3370 D A2dpStateMachine: Exit Disconnected: -1
,09-09 17:17:46.370  3225  3225 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29627d18
09-09 17:17:46.370  1015  1015 D BluetoothA2dp: Proxy object disconnected
09-09 17:17:46.370  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-09 17:17:46.370  4743  4743 D BluetoothA2dp: Proxy object disconnected
09-09 17:17:46.370  4743  4743 D A2dpProfile: Bluetooth service disconnected
,09-09 17:17:46.380  3225  3225 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-09 17:17:46.380  3225  3225 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-09 17:17:46.380  3225  3225 D HidService: Received stop request...Stopping profile...
09-09 17:17:46.380  3225  3225 D HidService: Stopping Bluetooth HidService
09-09 17:17:46.380  3225  3225 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-09 17:17:46.380  3225  3225 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-09 17:17:46.380  3225  3225 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-09 17:17:46.380  3225  3225 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29627d18
,09-09 17:17:46.380  3225  3225 D HealthService: Received stop request...Stopping profile...
09-09 17:17:46.380  3225  3225 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29627d18
,09-09 17:17:46.380  3225  3225 D PanService: Received stop request...Stopping profile...
09-09 17:17:46.380  3225  3225 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29627d18
,09-09 17:17:46.380  1015  1015 D BluetoothPan: BluetoothPAN Proxy object disconnected,
09-09 17:17:46.380  3225  3225 D BluetoothMapService: Received stop request...Stopping profile...
,09-09 17:17:46.390  4743  4743 D BluetoothInputDevice: Proxy object disconnected
,09-09 17:17:46.390  4743  4743 D HidProfile: Bluetooth service disconnected
09-09 17:17:46.390  3225  3225 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29627d18
,09-09 17:17:46.390  4743  4743 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 17:17:46.390  4743  4743 D PanProfile: Bluetooth service disconnected
09-09 17:17:46.390  4743  4743 D BluetoothMap: Proxy object disconnected
09-09 17:17:46.390  4743  4743 D MapProfile: Bluetooth service disconnected
,09-09 17:17:46.390  3225  3225 D SapService: Received stop request...Stopping profile...
09-09 17:17:46.390  3225  3225 D SapService: Stopping Bluetooth SapService
09-09 17:17:46.390  3225  3225 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29627d18
,09-09 17:17:46.400  3225  3225 E BluetoothAdapterService(694320408): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-09 17:17:46.400  3225  3225 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 17:17:46.400  3225  3225 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-09 17:17:46.400  3225  3225 D BluetoothA2dp: Proxy object disconnected
09-09 17:17:46.400  3225  3225 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,09-09 17:17:46.400  3225  3371 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-09 17:17:46.400  3225  3225 I GKI_LINUX: GKI_exit_task 2 done
09-09 17:17:46.400  3225  3225 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-09 17:17:46.400  3225  3225 E BluetoothAdapterService(694320408): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-09 17:17:46.400  3225  3225 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,09-09 17:17:46.400  3225  3225 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 17:17:46.400  3225  3225 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-09 17:17:46.400  4743  4743 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-09 17:17:46.400  3225  3225 E BluetoothAdapterService(694320408): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-09 17:17:46.400  3225  3225 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-09 17:17:46.400  3225  3225 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-09 17:17:46.400  4743  4743 D SapProfile: Bluetooth service disconnected
09-09 17:17:46.400  3225  3225 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-09 17:17:46.400  3225  3225 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-09 17:17:46.400  3225  3225 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-09 17:17:46.400  3225  3225 E BluetoothAdapterService(694320408): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-09 17:17:46.400  3225  3225 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-09 17:17:46.400  3225  3225 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 17:17:46.400  3225  3225 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-09 17:17:46.400  3225  3225 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 17:17:46.400  3225  3225 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-09 17:17:46.400  3225  3225 E BluetoothAdapterService(694320408): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-09 17:17:46.400  3225  3225 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-09 17:17:46.400  3225  3225 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-09 17:17:46.400  3225  3225 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,09-09 17:17:46.400  3225  3225 E BluetoothAdapterService(694320408): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-09 17:17:46.400  3225  3225 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-09 17:17:46.400  3225  3225 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-09 17:17:46.400  3225  3225 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
09-09 17:17:46.400  3225  3301 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
09-09 17:17:46.400  3225  3301 D BluetoothAdapterProperties: Setting state to 10
09-09 17:17:46.400  3225  3301 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-09 17:17:46.400  3225  3301 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-09 17:17:46.400  3225  3301 D BluetoothAdapterService: updateAdapterState state is 10
,09-09 17:17:46.400  3225  3301 D BluetoothAdapterService: Autoconnection is available 
09-09 17:17:46.400  3225  3301 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-09 17:17:46.400  3225  3301 I BluetoothAdapterState: Entering OffState
,09-09 17:17:46.410  1681  2483 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 17:17:46.410  1681  2483 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 17:17:46.410  4743  4761 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-09 17:17:46.410  4743  7429 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-09 17:17:46.410  1452  3379 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 17:17:46.410  1452  3379 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 17:17:46.420  1370  1370 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-09 17:17:46.420  1015  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 17:17:46.420  1015  1044 D Tethering: interfaceLinkStateChanged p2p0, false
,09-09 17:17:46.420  1015  1044 D Tethering: interfaceStatusChanged p2p0, false
,09-09 17:17:46.420  1015  1046 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 17:17:46.420  1015  1046 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 17:17:46.430  3225  3380 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 17:17:46.430  3225  3380 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 17:17:46.430  1478  1676 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 17:17:46.430  1478  1676 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 17:17:46.430  4743  7429 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 17:17:46.430  4743  7429 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 17:17:46.430  1698  4217 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 17:17:46.440  1698  4217 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 17:17:46.440  1015  1046 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-09 17:17:46.440  7319  7366 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 17:17:46.440  7319  7366 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 17:17:46.440  7319  7366 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-09 17:17:46.440  7319  7366 D BluetoothLeAdvertiser: Exit stop advertising
09-09 17:17:46.440  7319  7366 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-09 17:17:46.440  7319  7366 D BluetoothLeScanner: Exiting stopAllScan
,09-09 17:17:46.440  1178  2402 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 17:17:46.440  1178  2402 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 17:17:46.440  4743  4755 D BluetoothPbap: onBluetoothStateChange: up=false
,09-09 17:17:46.440  7319  7319 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 17:17:46.440  1461  1476 D BluetoothAdapter: onBluetoothStateChange: up=false,
09-09 17:17:46.440  1461  1476 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 17:17:46.440  4743  4761 D BluetoothMap: onBluetoothStateChange: up=false
,09-09 17:17:46.440  1370  1370 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,09-09 17:17:46.440  1015  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 17:17:46.440  1370  1370 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-09 17:17:46.440  1370  1370 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-09 17:17:46.440  1015  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 17:17:46.440  1015  1044 D Tethering: interfaceStatusChanged wlan0, false
09-09 17:17:46.440  1370  1370 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-09 17:17:46.440  1370  1370 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-09 17:17:46.440  1015  1130 D Tethering: InitialState.processMessage what=4
09-09 17:17:46.440  1015  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 17:17:46.440  1015  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 17:17:46.440  1015  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-09 17:17:46.450  4743  7429 D Bluetoothsap: onBluetoothStateChange: up=false
09-09 17:17:46.450  4743  7429 D Bluetoothsap: Unbinding service...
,09-09 17:17:46.450  1015  1130 E Tethering: No numeric data
,09-09 17:17:46.450  3225  3240 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-09 17:17:46.450  1015  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-09 17:17:46.450  1015  1130 D Tethering: clearTetheredNotification()
,09-09 17:17:46.450  1015  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 17:17:46.450  1015  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 17:17:46.450  1015  1044 D Tethering: interfaceStatusChanged wlan0, false
09-09 17:17:46.450  1015  1124 V NetworkStats: performPollLocked(flags=0x1)
09-09 17:17:46.450  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:17:46.450  1015  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 17:17:46.450  1015  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-09 17:17:46.450  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 17:17:46.450  1178  1178 D HotspotTile: updateTetherState():false, false
,09-09 17:17:46.460  1015  1124 V NetworkStats: performPollLocked() took 3ms
09-09 17:17:46.460  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:17:46.460  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:46.460  1015  1015 I InputMethodManagerService: [BT Setting State] State =10
09-09 17:17:46.460  1015  1015 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-09 17:17:46.460  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-09 17:17:46.460  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:17:46.470  1178  1178 D BluetoothTile:  getBluetoothState : 10
,09-09 17:17:46.470  4743  4743 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:17:46.470  1015  3282 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 17:17:46.470  1015  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:17:46.470  1015  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:17:46.470  2019  2019 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-09 17:17:46.470  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 17:17:46.470  1015  1501 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-09 17:17:46.480  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 17:17:46.480  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-09 17:17:46.480  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:46.480  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:46.480  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 17:17:46.480  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 17:17:46.480  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 17:17:46.480  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 17:17:46.490  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 17:17:46.490  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 17:17:46.490  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 17:17:46.490  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 17:17:46.490  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 17:17:46.490  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 17:17:46.490  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 17:17:46.490  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 17:17:46.500  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-09 17:17:46.500  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 17:17:46.500  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 17:17:46.500  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 17:17:46.500  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 17:17:46.500  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 17:17:46.500   256   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-09 17:17:46.500   256   530 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 17:17:46.500  7413  7436 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
09-09 17:17:46.500  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 17:17:46.510  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 17:17:46.510  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 17:17:46.510  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 17:17:46.510  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 17:17:46.510  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 17:17:46.520  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 17:17:46.520  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 17:17:46.520  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 17:17:46.520  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 17:17:46.520  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 17:17:46.530   256   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-09 17:17:46.530   256   530 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 17:17:46.530  7413  7436 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-09 17:17:46.600  1370  1370 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 17:17:46.640  1370  1370 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
,09-09 17:17:46.640  1015  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 17:17:46.640  1015  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 17:17:46.640  1015  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-09 17:17:46.650  1015  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,09-09 17:17:46.650  1015  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-09 17:17:46.660  1681  2163 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 17:17:46.660  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-09 17:17:46.660  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 17:17:46.660  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-09 17:17:46.660  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:46.660  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:46.660  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:46.660  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 17:17:46.660  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:46.660  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 17:17:46.660  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,09-09 17:17:46.660  1178  1704 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-09 17:17:46.660  1178  1178 D HotspotTile: onReceive : 1, 0
,09-09 17:17:46.660  4743  4743 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-09 17:17:46.660  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:46.660  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:46.680  7413  7413 D StrictMode: StrictMode policy violation; ~duration=170 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at java.io.File.exists(File.java:363)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 17:17:46.680  7413  7413 D StrictMode: StrictMode policy violation; ~duration=169 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 17:17:46.680  7413  7413 D StrictMode: StrictMode policy violation; ~duration=168 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 17:17:46.680  7413  7413 D StrictMode: StrictMode policy violation; ~duration=167 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.q.e.b(PG:170)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 17:17:46.680  7413  7413 D StrictMode: StrictMode policy violation; ~duration=164 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.q.k.c(PG:18147)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.q.k.d(PG:583)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.q.e.b(PG:170)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 17:17:46.680  7413  7413 D StrictMode: StrictMode policy violation; ~duration=141 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at java.io.File.exists(File.java:363)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 17:17:46.680  1015  1346 I ActivityManager: Killing 6983:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
09-09 17:17:46.680  7413  7413 D StrictMode: StrictMode policy violation; ~duration=141 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at java.io.File.exists(File.java:363)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 17:17:46.680  7413  7413 D StrictMode: StrictMode policy violation; ~duration=140 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at java.io.File.lastModified(File.java:571)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 17:17:46.680  7413  7413 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 17:17:46.690  1015  1491 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 17:17:46.690  1015  1491 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-09 17:17:46.690  1015  1491 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:46.690  1015  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:46.690  1015  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-09 17:17:46.690  1605  1605 I Hs20UtilService: Starting #8
09-09 17:17:46.690  1605  1643 I Hs20UtilService: Message received 5007
09-09 17:17:46.700  4743  4743 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-09 17:17:46.710  4743  4743 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-09 17:17:46.710  4743  4743 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-09 17:17:46.710  4743  4743 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-09 17:17:46.710  4743  4743 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 17:17:46.710  4743  4743 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-09 17:17:46.710  4743  4825 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 17:17:46.720  4743  4743 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-09 17:17:46.720  4743  4743 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-09 17:17:46.720  4743  4743 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-09 17:17:46.730  4743  4743 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-09 17:17:46.730  4743  4743 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 17:17:46.730  4743  4743 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-09 17:17:46.730  4743  4825 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-09 17:17:46.730  1015  3283 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
09-09 17:17:46.730  1015  3283 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:46.730  1015  3283 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:46.730  1015  3283 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:46.730  1015  3283 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:46.750  7461  7461 E Zygote  : MountEmulatedStorage()
09-09 17:17:46.750  7461  7461 I libpersona: KNOX_SDCARD checking this for 10064
09-09 17:17:46.750  7461  7461 E Zygote  : v2
09-09 17:17:46.750  7461  7461 I libpersona: KNOX_SDCARD not a persona
09-09 17:17:46.750  7461  7461 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 17:17:46.750  1015  3283 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7461 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 17:17:46.750  7413  7459 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
09-09 17:17:46.750  7461  7461 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 17:17:46.750  7461  7461 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 17:17:46.770  7461  7461 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:17:46.770  7461  7461 D ActivityThread: Added TimaKeyStore provider
,09-09 17:17:46.770  1015  3283 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 17:17:46.770  1015  3283 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:46.770  1015  3283 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:46.770  1015  3283 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-09 17:17:46.780  7461  7461 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-09 17:17:46.800  7461  7461 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 17:17:46.800  7461  7461 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-09 17:17:46.810  1015  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 17:17:46.810  1015  1015 I ApplicationPolicy: updateDataUsageMap
,09-09 17:17:46.830  1015  1041 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-09 17:17:46.830  7461  7461 D FileShare-Client: Outbound.stopDelayTimer - 
,09-09 17:17:46.830  1015  1135 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,09-09 17:17:46.840  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-09 17:17:46.840  1015  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:46.840  1015  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:46.840  1015  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:46.840  1015  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:46.840  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-09 17:17:46.850  7478  7478 E Zygote  : MountEmulatedStorage()
,09-09 17:17:46.850  7478  7478 E Zygote  : v2
09-09 17:17:46.850  7478  7478 I libpersona: KNOX_SDCARD checking this for 10065
09-09 17:17:46.850  7478  7478 I libpersona: KNOX_SDCARD not a persona
,09-09 17:17:46.850  7478  7478 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 17:17:46.850  1015  1135 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7478 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 17:17:46.850  1015  1135 I ActivityManager: Killing 7006:com.sec.android.fotaclient/u0a8 (adj 15): empty #21,
09-09 17:17:46.860  7478  7478 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 17:17:46.860  7478  7478 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 17:17:46.880  7478  7478 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:17:46.880  7478  7478 D ActivityThread: Added TimaKeyStore provider
,09-09 17:17:46.900  7478  7478 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 17:17:46.900  1015  1346 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:46.900  1015  1346 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:46.900  1015  1346 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,09-09 17:17:46.910  1015  1346 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,09-09 17:17:46.910  1015  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:46.910  1015  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:46.910  1015  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:46.910  1015  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:46.920  7493  7493 E Zygote  : MountEmulatedStorage(),
09-09 17:17:46.920  7493  7493 E Zygote  : v2
09-09 17:17:46.920  7493  7493 I libpersona: KNOX_SDCARD checking this for 10102
09-09 17:17:46.920  7493  7493 I libpersona: KNOX_SDCARD not a persona
09-09 17:17:46.920  7493  7493 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 17:17:46.920  1015  1346 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7493 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-09 17:17:46.920  1015  1346 I ActivityManager: Killing 7026:com.osp.app.signin/u0a36 (adj 15): empty #21
,09-09 17:17:46.930  7493  7493 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 17:17:46.930  7493  7493 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-09 17:17:46.940  7493  7493 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:17:46.950  7493  7493 D ActivityThread: Added TimaKeyStore provider
,09-09 17:17:46.960  7493  7493 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-09 17:17:47.150  7493  7513 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
09-09 17:17:47.150  7493  7513 I Babel_SMS: MmsConfig.loadMmsSettings
09-09 17:17:47.150  7493  7513 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
09-09 17:17:47.150  7493  7513 I Babel_SMS: MmsConfig.loadFromDatabase
,09-09 17:17:47.180  7493  7513 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
09-09 17:17:47.180  7493  7513 I Babel_SMS: MmsConfig.loadFromResources
,09-09 17:17:47.190  7493  7513 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-09 17:17:47.190  7493  7513 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,09-09 17:17:47.200  1015  1491 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,09-09 17:17:47.200  1015  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,09-09 17:17:47.200  1015  1491 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:47.200  1015  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 17:17:47.200  1015  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-09 17:17:47.220  7493  7493 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 17:17:47.230  7493  7493 I Babel_Crash: startup - clean
,09-09 17:17:47.250  1015  1044 D Tethering: interfaceRemoved wlan0
,09-09 17:17:47.250  1015  1044 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-09 17:17:47.260  1015  1501 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 17:17:47.260  1015  1501 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 17:17:47.260  1015  1501 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:47.260  1015  1501 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 17:17:47.260  1015  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 17:17:47.270  1605  1605 I Hs20UtilService: Starting #9
09-09 17:17:47.270  4743  4743 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-09 17:17:47.270  4743  4743 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-09 17:17:47.270  4743  4743 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 17:17:47.270  1605  1643 I Hs20UtilService: Message received 5007
,09-09 17:17:47.270  4743  4743 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-09 17:17:47.270  4743  4743 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 17:17:47.270  4743  4743 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 17:17:47.270  4743  4825 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 17:17:47.280  1015  1244 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 17:17:47.280  1015  1244 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 17:17:47.280  1015  1244 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:47.280  1015  1244 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:47.280  1015  1244 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 17:17:47.280  1605  1605 I Hs20UtilService: Starting #10
,09-09 17:17:47.280  1605  1643 I Hs20UtilService: Message received 5011,
,09-09 17:17:47.290  7140  7140 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-09 17:17:47.290  7140  7140 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 17:17:47.290  7140  7140 D SecurityLogAgent: StateMachine : Current State = 1
,09-09 17:17:47.290  7140  7140 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 17:17:47.300  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:47.300  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:47.300  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 17:17:47.300  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:47.300  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:47.300  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
09-09 17:17:47.300  7493  7493 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 17:17:47.300  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:47.310  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:47.310  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
09-09 17:17:47.310  7493  7493 W AudioCapabilities: Unsupported mime audio/evrc
,09-09 17:17:47.310  7493  7493 W AudioCapabilities: Unsupported mime audio/qcelp
,09-09 17:17:47.310  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:47.310  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:47.310  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 17:17:47.310  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:47.310  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:47.310  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 17:17:47.310  7493  7493 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,09-09 17:17:47.320  7493  7493 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,09-09 17:17:47.320  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:47.320  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:47.320  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 17:17:47.320  7493  7493 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,09-09 17:17:47.320  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:47.320  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:47.320  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 17:17:47.320  7493  7493 W AudioCapabilities: Unsupported mime audio/x-ima
,09-09 17:17:47.330  7493  7493 W AudioCapabilities: Unsupported mime audio/qcelp
,09-09 17:17:47.330  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:47.330  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:47.330  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 17:17:47.330  7493  7493 W AudioCapabilities: Unsupported mime audio/evrc
,09-09 17:17:47.330  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:47.330  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:47.330  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 17:17:47.330  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:47.330  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:47.330  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 17:17:47.330  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:47.330  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:47.330  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 17:17:47.340  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:47.340  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:47.340  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
09-09 17:17:47.340  7493  7493 W VideoCapabilities: Unsupported mime video/wvc1
,09-09 17:17:47.340  7493  7493 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-09 17:17:47.340  1015  1015 W ActivityManager: userId = 0, bbcId = -10000,
09-09 17:17:47.340  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:47.340  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 17:17:47.340  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:47.340  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:47.340  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 17:17:47.350  4743  4743 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-09 17:17:47.350  1015  3280 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-09 17:17:47.350  1015  3280 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
09-09 17:17:47.350  1015  3280 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:47.350  1015  3280 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:47.350  1015  3280 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
09-09 17:17:47.350  7493  7493 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,09-09 17:17:47.360  1698  1698 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 17:17:47.360  7493  7493 W VideoCapabilities: Unsupported mime video/wvc1
,09-09 17:17:47.360  7493  7493 W VideoCapabilities: Unsupported mime video/x-ms-wmv
09-09 17:17:47.360  7493  7493 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,09-09 17:17:47.360  4743  4743 D DockEventReceiver: finishStartingService: stopping service
,09-09 17:17:47.360  4743  4743 D BluetoothNotiBroadcastReceiver: onReceive
09-09 17:17:47.360  7493  7493 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,09-09 17:17:47.370  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:47.370  7493  7493 W VideoCapabilities: Unsupported mime video/mp43
,09-09 17:17:47.370  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-09 17:17:47.380  7493  7493 W VideoCapabilities: Unsupported mime video/sorenson
,09-09 17:17:47.380  1015  1044 D Tethering: interfaceRemoved p2p0
09-09 17:17:47.380  1015  1044 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-09 17:17:47.380  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:47.380  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:47.380  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 17:17:47.380  7493  7493 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-09 17:17:47.390  1015  1346 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 17:17:47.390  1015  1346 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 17:17:47.390  1015  1346 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:47.390  1015  1346 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:47.390  1015  1346 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 17:17:47.390  1605  1605 I Hs20UtilService: Starting #11
,09-09 17:17:47.390  1605  1643 I Hs20UtilService: Message received 5011
,09-09 17:17:47.390  7140  7140 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-09 17:17:47.390  7140  7140 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 17:17:47.390  7140  7140 D SecurityLogAgent: StateMachine : Current State = 1
09-09 17:17:47.390  7140  7140 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 17:17:47.400  1015  3280 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-09 17:17:47.400  1015  3280 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:47.400  1015  3280 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:47.400  1015  3280 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:47.400  1015  3280 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:47.410  7493  7493 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es,
,09-09 17:17:47.410  7518  7518 E Zygote  : MountEmulatedStorage()
09-09 17:17:47.410  7518  7518 E Zygote  : v2
09-09 17:17:47.410  7518  7518 I libpersona: KNOX_SDCARD checking this for 1000
09-09 17:17:47.410  7518  7518 I libpersona: KNOX_SDCARD not a persona
,09-09 17:17:47.420  7518  7518 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 17:17:47.420  7518  7518 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 17:17:47.420  1015  3280 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7518 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,09-09 17:17:47.420  7518  7518 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 17:17:47.440  7518  7518 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:17:47.440  7518  7518 D ActivityThread: Added TimaKeyStore provider
,09-09 17:17:47.450  7493  7493 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 17:17:47.450  7493  7493 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 17:17:47.450  7493  7493 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 17:17:47.460  7493  7493 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 17:17:47.460  1015  1028 I ActivityManager: Killing 6694:com.android.mms/u0a41 (adj 15): empty #21
,09-09 17:17:47.460  7493  7493 I vclib   : onServiceConnected
,09-09 17:17:47.460  7518  7518 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
09-09 17:17:47.460  7518  7518 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-09 17:17:47.460  7518  7518 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-09 17:17:47.480  7518  7518 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-09 17:17:47.480  7518  7518 I PCWCLIENTTRACE_PushUtil: sales region : global
09-09 17:17:47.480  7518  7518 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-09 17:17:47.480  7518  7518 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-09 17:17:47.480  1015  3283 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
,09-09 17:17:47.480  1015  3283 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
09-09 17:17:47.480  1015  3283 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
09-09 17:17:47.480  7518  7533 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,09-09 17:17:47.480  1015  3283 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,09-09 17:17:47.480  1015  3283 I ActivityManager: Killing 7045:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,09-09 17:17:47.490  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-09 17:17:47.500  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:47.500  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:47.500  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:47.500  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:47.510  7535  7535 E Zygote  : MountEmulatedStorage()
,09-09 17:17:47.510  7535  7535 E Zygote  : v2
09-09 17:17:47.510  7535  7535 I libpersona: KNOX_SDCARD checking this for 10001
09-09 17:17:47.510  7535  7535 I libpersona: KNOX_SDCARD not a persona
,09-09 17:17:47.510  7535  7535 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 17:17:47.510  1015  1015 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7535 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 17:17:47.510  7535  7535 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 17:17:47.510  7535  7535 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-09 17:17:47.530  7535  7535 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 17:17:47.530  7535  7535 D ActivityThread: Added TimaKeyStore provider
,09-09 17:17:47.550  1015  1466 D CountryDetector: No listener is left
,09-09 17:17:47.600  1015  1501 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,09-09 17:17:47.600  1015  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:47.600  1015  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:47.600  1015  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:47.600  1015  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:47.610  1015  1501 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7552 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
09-09 17:17:47.610  1015  1501 I ActivityManager: Killing 6210:com.samsung.android.sm/1000 (adj 15): empty #21
,09-09 17:17:47.610  7552  7552 E Zygote  : MountEmulatedStorage()
09-09 17:17:47.610  7552  7552 I libpersona: KNOX_SDCARD checking this for 1000
09-09 17:17:47.610  7552  7552 E Zygote  : v2
09-09 17:17:47.610  7552  7552 I libpersona: KNOX_SDCARD not a persona
09-09 17:17:47.610  7552  7552 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 17:17:47.620  7552  7552 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 17:17:47.620  7552  7552 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 17:17:47.640  7552  7552 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:17:47.640  7552  7552 D ActivityThread: Added TimaKeyStore provider
,09-09 17:17:47.670  7552  7552 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-09 17:17:47.730   287   287 E SMD     : DCD OFF
,09-09 17:17:47.810  7552  7552 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,09-09 17:17:47.820  7552  7552 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,09-09 17:17:47.820  7552  7552 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-09 17:17:47.820  7552  7552 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-09 17:17:47.820  7552  7552 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,09-09 17:17:47.820  7552  7552 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-09 17:17:47.830  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast,
,09-09 17:17:47.830  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:47.830  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:47.830  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:47.830  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:47.850  7567  7567 E Zygote  : MountEmulatedStorage(),
09-09 17:17:47.850  7567  7567 E Zygote  : v2
09-09 17:17:47.850  7567  7567 I libpersona: KNOX_SDCARD checking this for 10008
09-09 17:17:47.850  7567  7567 I libpersona: KNOX_SDCARD not a persona
,09-09 17:17:47.850  7567  7567 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 17:17:47.850  1015  1027 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7567 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 17:17:47.850  7567  7567 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 17:17:47.850  1015  1027 I ActivityManager: Killing 7061:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,09-09 17:17:47.860  7567  7567 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-09 17:17:47.870  7567  7567 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:17:47.880  7567  7567 D ActivityThread: Added TimaKeyStore provider
,09-09 17:17:47.950  1015  1501 I ActivityManager: Killing 7076:com.sec.esdk.elm/u0a90 (adj 15): empty #21
,09-09 17:17:47.960  1015  3282 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
09-09 17:17:47.960  1015  3282 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-09 17:17:47.960  1015  3282 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:47.960  1015  3282 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:47.960  1015  3282 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,09-09 17:17:47.980  1871  1871 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-09 17:17:47.990  1871  2800 I iu.UploadsManager: num queued entries: 0
,09-09 17:17:47.990  1871  2800 I iu.UploadsManager: num updated entries: 0
,09-09 17:17:47.990  1871  2800 I iu.SyncManager: NEXT; no task
,09-09 17:17:47.990  1015  1491 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 17:17:47.990  1015  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,09-09 17:17:47.990  1015  1491 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:47.990  1015  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 17:17:47.990  1015  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:48.000  1015  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-09 17:17:48.000  1871  1871 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 17:17:48.010  1871  1871 I Kids    : [GCoreUtils] Current gmscore version, 8115234 is smaller than the required version 8400000
,09-09 17:17:48.020  2804  2804 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Sep 09 17:17:48 GMT+02:00 2016
,09-09 17:17:48.020  1015  1135 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-09 17:17:48.020  1015  1135 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-09 17:17:48.020  1015  1135 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:48.020  1015  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 17:17:48.020  1015  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-09 17:17:48.030  2804  2804 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-09 17:17:48.030  2804  2804 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-09 17:17:48.040  2804  2804 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-09 17:17:48.040  1015  3280 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,09-09 17:17:48.040  1015  3280 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:48.040  1015  3280 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:48.040  1015  3280 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:48.040  1015  3280 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:48.040  2804  2804 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-09 17:17:48.050  2804  7584 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-09 17:17:48.060  7585  7585 E Zygote  : MountEmulatedStorage()
,09-09 17:17:48.060  7585  7585 E Zygote  : v2
09-09 17:17:48.060  7585  7585 I libpersona: KNOX_SDCARD checking this for 10031
09-09 17:17:48.060  7585  7585 I libpersona: KNOX_SDCARD not a persona
,09-09 17:17:48.060  7585  7585 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-09 17:17:48.060  1015  3280 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7585 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a,
09-09 17:17:48.060  2804  7584 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-09 17:17:48.070  7585  7585 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 17:17:48.070  7585  7585 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 17:17:48.070  2804  7584 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,09-09 17:17:48.070  2804  7584 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,09-09 17:17:48.070  2804  2804 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-09 17:17:48.090  7585  7585 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:17:48.090  7585  7585 D ActivityThread: Added TimaKeyStore provider
,09-09 17:17:48.130  7585  7585 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,09-09 17:17:48.130  1015  1346 I ActivityManager: Killing 7160:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,09-09 17:17:48.150  1015  3283 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-09 17:17:48.150  1015  3283 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:48.150  1015  3283 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:48.150  1015  3283 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:48.150  1015  3283 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:48.160  2742  7600 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,09-09 17:17:48.160  2742  7600 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,09-09 17:17:48.160  7601  7601 E Zygote  : MountEmulatedStorage(),
09-09 17:17:48.160  7601  7601 E Zygote  : v2,
09-09 17:17:48.160  7601  7601 I libpersona: KNOX_SDCARD checking this for 10032
,09-09 17:17:48.160  7601  7601 I libpersona: KNOX_SDCARD not a persona
09-09 17:17:48.160  2742  7600 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,09-09 17:17:48.170  1015  3283 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7601 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,09-09 17:17:48.170  2742  7600 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,09-09 17:17:48.170  2742  7600 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... ,
,09-09 17:17:48.170  7601  7601 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 17:17:48.170  7601  7601 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-09 17:17:48.170  7601  7601 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-09 17:17:48.200  7601  7601 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:17:48.200  7601  7601 D ActivityThread: Added TimaKeyStore provider
,09-09 17:17:48.260  7601  7616 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,09-09 17:17:48.260  7601  7616 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-09 17:17:48.260  7601  7601 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,09-09 17:17:48.260  1015  3280 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,09-09 17:17:48.270  1015  3280 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:48.270  1015  3280 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:48.270  1015  3280 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:48.270  1015  3280 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:48.270  7601  7616 D SPPClientService: PushLog.txt file is not deleted.
,09-09 17:17:48.270  7601  7616 D SPPClientService: PushLog.txt file is not deleted.
,09-09 17:17:48.270  7601  7616 D SPPClientService: ============PushLog. stop!
,09-09 17:17:48.280  1015  3280 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7618 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 17:17:48.280  1015  1491 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
09-09 17:17:48.280  7618  7618 E Zygote  : MountEmulatedStorage()
09-09 17:17:48.280  1015  1491 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
09-09 17:17:48.280  7618  7618 E Zygote  : v2
09-09 17:17:48.280  7618  7618 I libpersona: KNOX_SDCARD checking this for 10036
09-09 17:17:48.280  7618  7618 I libpersona: KNOX_SDCARD not a persona
,09-09 17:17:48.280  7618  7618 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 17:17:48.280  1015  1491 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:48.280  1015  1491 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-09 17:17:48.280  1015  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,09-09 17:17:48.290  7618  7618 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 17:17:48.290  7618  7618 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,09-09 17:17:48.300  7601  7624 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,09-09 17:17:48.310  7618  7618 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:17:48.310  7618  7618 D ActivityThread: Added TimaKeyStore provider
,09-09 17:17:48.320  1015  1244 I ActivityManager: Killing 7176:com.qualcomm.timeservice/1000 (adj 15): empty #21
,09-09 17:17:48.350  7618  7618 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@38ad8639
,09-09 17:17:48.370  7618  7618 I SA      : [SSP] onCreated
,09-09 17:17:48.380  7618  7618 I SA      : [TPM] There is no property file
,09-09 17:17:48.380  7618  7618 I SA      : [SCU] isHaveSA() - false
,09-09 17:17:48.380  7618  7618 I SA      : [TPM] getModelProperty : null
,09-09 17:17:48.380  7618  7618 I SA      : [TPM] getCSCProperty : null
,09-09 17:17:48.390  7618  7618 I SA      : [DM] FLOATING AMOLED FEATURE: true
,09-09 17:17:48.390  7618  7618 I SA      : [DM] PRODUCT AMOLED FEATURE: false
,09-09 17:17:48.390  7618  7618 I SA      : [DM] TFT FEATURE: false
,09-09 17:17:48.390  7618  7618 I SA      : [DM] init START
,09-09 17:17:48.390  7618  7618 I SA      : [DM] This device is not a Vodafone
,09-09 17:17:48.400  7618  7618 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,09-09 17:17:48.400  7618  7618 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,09-09 17:17:48.400  7618  7618 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,09-09 17:17:48.400  7618  7618 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,09-09 17:17:48.400  7618  7618 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,09-09 17:17:48.400  7618  7618 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,09-09 17:17:48.410  7618  7618 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,09-09 17:17:48.410  7618  7618 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-09 17:17:48.410  7618  7618 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,09-09 17:17:48.410  7618  7618 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,09-09 17:17:48.410  7618  7618 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,09-09 17:17:48.410  7618  7618 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,09-09 17:17:48.410  7618  7618 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,09-09 17:17:48.410  7618  7618 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,09-09 17:17:48.420  7618  7618 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,09-09 17:17:48.420  7618  7618 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,09-09 17:17:48.420  7618  7618 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,09-09 17:17:48.420  7618  7618 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,09-09 17:17:48.420  7618  7618 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,09-09 17:17:48.420  7618  7618 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,09-09 17:17:48.420  7618  7618 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,09-09 17:17:48.420  7618  7618 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,09-09 17:17:48.420  7618  7618 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,09-09 17:17:48.420  7618  7618 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,09-09 17:17:48.420  7618  7618 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,09-09 17:17:48.420  7618  7618 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,09-09 17:17:48.430  7618  7618 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
,09-09 17:17:48.430  7618  7618 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,09-09 17:17:48.430  7618  7618 I SA      : [SCU] isHaveSA() - false
09-09 17:17:48.430  7618  7618 I SA      : support phone number id : false
09-09 17:17:48.430  7618  7618 I SA      : [DM] Supports Ref Jpn : true
,09-09 17:17:48.430  7618  7618 I SA      : [DM] init END
,09-09 17:17:48.430  7618  7618 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,09-09 17:17:48.440  7618  7618 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
09-09 17:17:48.440  7618  7618 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-09 17:17:48.440  7618  7618 I SA      : [SLFUCHKMGR] constructor called
,09-09 17:17:48.450  7618  7618 I SA      : [TPMU]  strSIMState ,	:SIM_STATE_ABSENT
09-09 17:17:48.450  7618  7618 I SA      : [OR] == isSIMCardReady false ==
09-09 17:17:48.450  7618  7618 I SA      : [SCU] == networkStateCheck == false
,09-09 17:17:48.450  7618  7618 I SA      : [OR] onReceive END
,09-09 17:17:48.450  1015  1491 I ActivityManager: Killing 7128:com.android.providers.calendar/u0a37 (adj 15): empty #21
,09-09 17:17:48.460  1225  1225 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-09 17:17:48.460  1823  1823 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-09 17:17:48.470  2673  2683 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,09-09 17:17:48.470  1823  1823 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,09-09 17:17:48.470  1823  1823 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
09-09 17:17:48.470  1823  1823 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1,
09-09 17:17:48.470  1823  1823 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-09 17:17:48.470  1823  1823 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-09 17:17:48.480  1823  1823 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,09-09 17:17:48.480  1015  1135 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,09-09 17:17:48.480  1015  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:48.480  1015  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:48.480  1015  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:48.480  1015  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:48.490  7640  7640 E Zygote  : MountEmulatedStorage()
,09-09 17:17:48.490  7640  7640 E Zygote  : v2
09-09 17:17:48.490  7640  7640 I libpersona: KNOX_SDCARD checking this for 10077
09-09 17:17:48.490  7640  7640 I libpersona: KNOX_SDCARD not a persona
,09-09 17:17:48.500  7640  7640 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 17:17:48.500  1015  1135 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7640 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 17:17:48.500  7640  7640 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 17:17:48.500  7640  7640 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,09-09 17:17:48.510  7640  7640 D TimaKeyStoreProvider: TimaSignature is unavailable,
09-09 17:17:48.510  7640  7640 D ActivityThread: Added TimaKeyStore provider
,09-09 17:17:48.520   303   303 I art     : Explicit concurrent mark sweep GC freed 8699(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 823us total 26.934ms
,09-09 17:17:48.540   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 636us total 17.038ms
,09-09 17:17:48.550   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 575us total 16.207ms
,09-09 17:17:48.670  1015  1135 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
09-09 17:17:48.670  1015  1135 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-09 17:17:48.670  1015  1135 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:48.670  1015  1135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 17:17:48.670  1015  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-09 17:17:48.670  1015  1501 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,09-09 17:17:48.680  1015  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:48.680  1015  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:48.680  1015  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:48.680  1015  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:48.690  1015  1501 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7658 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 17:17:48.690  1015  1244 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk,
09-09 17:17:48.690  7658  7658 E Zygote  : MountEmulatedStorage()
09-09 17:17:48.690  1015  1244 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
09-09 17:17:48.690  7658  7658 E Zygote  : v2
09-09 17:17:48.690  7658  7658 I libpersona: KNOX_SDCARD checking this for 10110
09-09 17:17:48.690  7658  7658 I libpersona: KNOX_SDCARD not a persona,
09-09 17:17:48.690  7658  7658 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 17:17:48.690  1015  1244 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:48.690  1015  1244 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:48.690  1015  1244 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-09 17:17:48.690  7658  7658 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 17:17:48.700  7658  7658 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-09 17:17:48.700  7493  7657 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-09 17:17:48.700  1015  3282 I ActivityManager: Killing 7092:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,09-09 17:17:48.710  7658  7658 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:17:48.710  7658  7658 D ActivityThread: Added TimaKeyStore provider
,09-09 17:17:48.800  1015  1466 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-09 17:17:48.900  7658  7658 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-09 17:17:48.900  7658  7658 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-09 17:17:48.900  7658  7658 I GAv4    :   adb logcat -s GAv4
,09-09 17:17:48.900   256   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-09 17:17:48.900   256   530 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 17:17:48.900  7658  7676 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-09 17:17:48.910  7658  7676 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-09 17:17:48.910   256   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-09 17:17:48.910   256   530 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 17:17:48.920  7658  7658 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
09-09 17:17:48.920  1015  3283 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-09 17:17:48.930  7658  7658 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,09-09 17:17:48.930   256   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-09 17:17:48.930   256   530 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 17:17:48.930  7658  7678 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-09 17:17:48.940   256   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-09 17:17:48.940   256   530 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 17:17:48.940  7658  7678 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-09 17:17:48.940  7658  7679 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-09 17:17:49.020  1015  1027 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-09 17:17:49.020  1015  1027 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-09 17:17:49.020  1015  1027 D SecContentProvider2: mCursor = null
,09-09 17:17:49.020  1015  1027 D WifiService: setWifiEnabled: true pid=7319, uid=10170
,09-09 17:17:49.020  1015  1027 W ActivityManager: Permission Denial: getCurrentUser() from pid=7319, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-09 17:17:49.020  1015  1027 W WifiService: Failed getting userId using ActivityManagerNative
09-09 17:17:49.020  1015  1027 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7319, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-09 17:17:49.020  1015  1027 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-09 17:17:49.020  1015  1027 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-09 17:17:49.020  1015  1027 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-09 17:17:49.020  1015  1027 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-09 17:17:49.020  1015  1027 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-09 17:17:49.020  1015  1027 D SettingsProvider: name = wifi_on
,09-09 17:17:49.030  1015  1127 E WifiHW  : ##################### set firmware type 0 #####################
,09-09 17:17:49.210  1015  1504 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 17:17:49.210  1015  1504 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:49.210  1015  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:49.210  1015  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-09 17:17:49.230  7658  7658 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,09-09 17:17:49.250  7658  7658 I cr.library_loader: Time to load native libraries: 3 ms (timestamps 5528-5531)
09-09 17:17:49.250  7658  7658 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-09 17:17:49.260  7658  7658 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {37e701d8}
,09-09 17:17:49.260  7658  7658 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-09 17:17:49.260  7658  7658 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-09 17:17:49.270  7658  7658 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,09-09 17:17:49.280  7658  7658 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 17:17:49.280  7658  7658 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-09 17:17:49.290  7658  7658 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-09 17:17:49.290  7658  7658 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-09 17:17:49.290  7658  7658 I Adreno-EGL: Build Date: 04/06/15 Mon
09-09 17:17:49.290  7658  7658 I Adreno-EGL: Local Branch: 
09-09 17:17:49.290  7658  7658 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-09 17:17:49.290  7658  7658 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-09 17:17:49.290  7658  7658 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-09 17:17:49.360  7658  7714 W cr.media: Requires BLUETOOTH permission
,09-09 17:17:49.360  7658  7658 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-09 17:17:49.370  7658  7658 I NSApplication: Starting up...
,09-09 17:17:49.370  1015  1135 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-09 17:17:49.370  1015  1028 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-09 17:17:49.380  1015  1504 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,09-09 17:17:49.380  1015  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:49.380  1015  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:49.380  1015  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:49.380  1015  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:49.390  7719  7719 E Zygote  : MountEmulatedStorage(),
,09-09 17:17:49.400  7719  7719 E Zygote  : v2
,09-09 17:17:49.400  7719  7719 I libpersona: KNOX_SDCARD checking this for 10117
09-09 17:17:49.400  7719  7719 I libpersona: KNOX_SDCARD not a persona
,09-09 17:17:49.400  7719  7719 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 17:17:49.400  1015  1504 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7719 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-09 17:17:49.400  1015  1044 D Tethering: interfaceAdded wlan0
,09-09 17:17:49.400  1015  1504 I ActivityManager: Killing 7108:com.android.calendar/u0a131 (adj 15): empty #21
09-09 17:17:49.400  1015  1044 D Tethering: interfaceLinkStateChanged wlan0, false
,09-09 17:17:49.400  1015  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 17:17:49.400  1015  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-09 17:17:49.410  1015  1044 D Tethering: interfaceAdded p2p0
,09-09 17:17:49.410  7719  7719 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 17:17:49.410  1015  1130 E Tethering: No numeric data
09-09 17:17:49.410  1015  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 17:17:49.410  1015  1130 D Tethering: clearTetheredNotification()
09-09 17:17:49.410  1015  1130 D Tethering: InitialState.processMessage what=4
09-09 17:17:49.410  7719  7719 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-09 17:17:49.410   277   966 I WifiHW  : wifi_change_fw_path(): fwpath = sta
09-09 17:17:49.410   277   966 D SoftapController: Softap fwReload - Ok
09-09 17:17:49.420   277   966 D CommandListener: Setting iface cfg
09-09 17:17:49.420   277   966 D CommandListener: Trying to bring down wlan0
,09-09 17:17:49.420  1015  1130 E Tethering: No numeric data
,09-09 17:17:49.420  1015  1044 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-09 17:17:49.420  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:17:49.420  1015  1124 V NetworkStats: performPollLocked(flags=0x1)
,09-09 17:17:49.420  1015  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 17:17:49.420  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 17:17:49.420  1015  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-09 17:17:49.420  1015  1044 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 17:17:49.420  1015  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 17:17:49.420  1015  1044 D Tethering: interfaceStatusChanged p2p0, false
09-09 17:17:49.420  1178  1178 D HotspotTile: updateTetherState():false, false
,09-09 17:17:49.420   277   966 D CommandListener: Clearing all IP addresses on wlan0
09-09 17:17:49.420  1015  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 17:17:49.420  1015  1130 D Tethering: clearTetheredNotification()
,09-09 17:17:49.420  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:17:49.420  1015  1124 V NetworkStats: performPollLocked() took 5ms
,09-09 17:17:49.430  1015  1127 E WifiHW  : supplicant_name : p2p_supplicant
09-09 17:17:49.430  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:17:49.430  1015  1124 V NetworkStats: performPollLocked(flags=0x1)
,09-09 17:17:49.430  1015  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 17:17:49.430  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 17:17:49.430  1015  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-09 17:17:49.430  1178  1178 D HotspotTile: updateTetherState():false, false
09-09 17:17:49.430  1015  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:17:49.430  1015  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:17:49.430  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:17:49.430  1015  1124 V NetworkStats: performPollLocked() took 3ms
,09-09 17:17:49.430  1015  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:17:49.430  1015  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:17:49.430  1015  1127 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-09 17:17:49.440  7719  7719 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:17:49.440  7719  7719 D ActivityThread: Added TimaKeyStore provider
,09-09 17:17:49.450  4743  4743 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-09 17:17:49.450  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-09 17:17:49.450  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 17:17:49.450  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 17:17:49.450  1178  1704 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-09 17:17:49.450  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-09 17:17:49.450  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:49.450  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:49.450  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:49.450  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:49.450  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 17:17:49.450  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,09-09 17:17:49.460  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:49.460  1178  1178 D HotspotTile: onReceive : 2, 0,
09-09 17:17:49.460  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:49.480  7719  7719 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 17:17:49.490  7732  7732 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-09 17:17:49.490  7732  7732 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-09 17:17:49.490  7732  7732 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-09 17:17:49.510  7732  7732 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
09-09 17:17:49.510   373   373 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7732
09-09 17:17:49.510   373   373 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
,09-09 17:17:49.510  7732  7732 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running,
09-09 17:17:49.510  7732  7732 I wpa_supplicant: ssSupport state is = 1
09-09 17:17:49.510  7732  7732 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-09 17:17:49.510  7732  7732 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-09 17:17:49.510   373   373 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7732,
09-09 17:17:49.510   373   373 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,09-09 17:17:49.690   373   373 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0,
,09-09 17:17:49.700  7732  7732 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,09-09 17:17:49.750  7732  7732 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-09 17:17:49.750  7732  7732 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-09 17:17:49.760  7732  7732 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,09-09 17:17:49.760   373   373 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7732
09-09 17:17:49.760   373   373 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-09 17:17:49.760  7732  7732 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-09 17:17:49.760  7732  7732 I wpa_supplicant: ssSupport state is = 1
,09-09 17:17:49.760  7732  7732 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-09 17:17:49.760  7732  7732 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 17:17:49.760  7732  7732 E wpa_supplicant: SIM READ ERROR
09-09 17:17:49.760  7732  7732 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 17:17:49.760  7732  7732 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 17:17:49.760  7732  7732 E wpa_supplicant: SIM READ ERROR
09-09 17:17:49.760  7732  7732 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 17:17:49.770  7732  7732 I wpa_supplicant: wpa_default_ap_write_once
09-09 17:17:49.770  7732  7732 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,09-09 17:17:49.770  7732  7732 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 17:17:49.770  7732  7732 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-09 17:17:49.770  7732  7732 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 17:17:49.770  7732  7732 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-09 17:17:49.770  7732  7732 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-09 17:17:49.770  1015  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-09 17:17:49.770  1015  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 17:17:49.770  1015  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-09 17:17:49.790  1015  3283 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-09 17:17:49.790  1015  3283 D BatteryService: level:93, scale:100, status:2, health:2, present:true, voltage: 4196, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-09 17:17:49.790  1015  3283 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-09 17:17:49.790  1015  3283 D BatteryService: stay LED for charging
09-09 17:17:49.790  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-09 17:17:49.790  1015  1015 I MotionRecognitionService: Plugged,
09-09 17:17:49.790  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,09-09 17:17:49.800  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-09 17:17:49.800  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-09 17:17:49.800  1435  1435 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-09 17:17:49.800  1435  1435 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,09-09 17:17:49.820  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,09-09 17:17:49.820  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,09-09 17:17:49.820  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
09-09 17:17:49.820  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,09-09 17:17:49.820  1178  1178 D SViewCoverView: level :93 plugged : 2
,09-09 17:17:49.870  7732  7732 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,09-09 17:17:49.870  1015  1466 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-09 17:17:49.870  1015  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:49.870  1015  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:49.870  1015  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:49.870  1015  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:49.880  1015  1466 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7744 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
09-09 17:17:49.890  7744  7744 E Zygote  : MountEmulatedStorage()
09-09 17:17:49.880  1015  1466 I ActivityManager: Killing 7200:com.google.android.gms:car/u0a11 (adj 15): empty #21
09-09 17:17:49.890  7744  7744 E Zygote  : v2
09-09 17:17:49.890  7744  7744 I libpersona: KNOX_SDCARD checking this for 10121
09-09 17:17:49.890  7744  7744 I libpersona: KNOX_SDCARD not a persona
,09-09 17:17:49.890  7744  7744 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 17:17:49.890  7744  7744 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 17:17:49.890  7744  7744 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 17:17:49.910  7744  7744 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 17:17:49.910  7744  7744 D ActivityThread: Added TimaKeyStore provider
,09-09 17:17:49.920  7744  7744 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 17:17:49.920  7744  7744 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-09 17:17:49.920  7744  7744 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-09 17:17:49.940  7744  7744 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-09 17:17:49.950  7744  7744 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,09-09 17:17:49.950  7744  7744 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-09 17:17:49.950  1015  1501 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,09-09 17:17:49.950  1015  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:49.950  1015  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:49.950  1015  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:49.950  1015  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:49.980  7762  7762 E Zygote  : MountEmulatedStorage(),
,09-09 17:17:49.980  7762  7762 E Zygote  : v2
09-09 17:17:49.980  7762  7762 I libpersona: KNOX_SDCARD checking this for 10141
,09-09 17:17:49.980  7762  7762 I libpersona: KNOX_SDCARD not a persona
,09-09 17:17:49.980  7762  7762 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-09 17:17:49.980  7762  7762 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 17:17:49.980  1015  1501 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7762 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
09-09 17:17:49.980  1015  1028 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.car.InCallServiceImpl in 1000ms
09-09 17:17:49.980  1015  1028 I ActivityManager: Killing 7219:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
,09-09 17:17:49.990  7762  7762 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 17:17:50.000  7762  7762 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:17:50.010  7762  7762 D ActivityThread: Added TimaKeyStore provider
,09-09 17:17:50.020  7762  7762 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,09-09 17:17:50.020  7762  7762 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 17:17:50.020  7762  7762 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 17:17:50.020  7762  7762 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-09 17:17:50.070  1015  1135 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 17:17:50.080  1015  1505 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 17:17:50.090  7732  7732 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,09-09 17:17:50.090  7732  7732 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-09 17:17:50.110  7732  7732 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,09-09 17:17:50.110   373   373 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7732
09-09 17:17:50.110   373   373 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-09 17:17:50.110  7732  7732 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-09 17:17:50.110  7732  7732 I wpa_supplicant: ssSupport state is = 1
,09-09 17:17:50.110  7732  7732 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-09 17:17:50.110  7732  7732 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-09 17:17:50.120  7732  7732 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
09-09 17:17:50.120   373   373 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7732
09-09 17:17:50.120   373   373 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,09-09 17:17:50.120  7732  7732 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-09 17:17:50.120  7732  7732 I wpa_supplicant: ssSupport state is = 1
09-09 17:17:50.120  7732  7732 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 17:17:50.120  7732  7732 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 17:17:50.120  7732  7732 E wpa_supplicant: SIM READ ERROR
09-09 17:17:50.120  7732  7732 I wpa_supplicant: wpa_default_ap_write_once
09-09 17:17:50.120  7732  7732 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-09 17:17:50.120  7732  7732 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-09 17:17:50.130  1015  1044 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 17:17:50.130  1015  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 17:17:50.130  1015  1044 D Tethering: interfaceStatusChanged p2p0, false
09-09 17:17:50.130  1015  1501 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 17:17:50.130  1015  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-09 17:17:50.130  1015  1044 D Tethering: interfaceLinkStateChanged p2p0, false
,09-09 17:17:50.130  1015  1044 D Tethering: interfaceStatusChanged p2p0, false
,09-09 17:17:50.140  1015  3283 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 17:17:50.180  7732  7732 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
09-09 17:17:50.180  7732  7732 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-09 17:17:50.180  1015  3282 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,09-09 17:17:50.180  1015  3282 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-09 17:17:50.180  1015  3282 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:50.180  1015  3282 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:50.180  1015  3282 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:50.190  1015  1466 D RCPManagerService: exchangeData() failure , invalid userId,
,09-09 17:17:50.200  1015  1505 D RCPManagerService: exchangeData() failure , invalid userId
09-09 17:17:50.200  7786  7786 E Zygote  : MountEmulatedStorage()
09-09 17:17:50.200  7786  7786 I libpersona: KNOX_SDCARD checking this for 10068
09-09 17:17:50.200  7786  7786 E Zygote  : v2
09-09 17:17:50.200  7786  7786 I libpersona: KNOX_SDCARD not a persona
,09-09 17:17:50.200  7786  7786 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 17:17:50.200  1015  3282 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7786 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,09-09 17:17:50.200  7786  7786 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 17:17:50.200  7786  7786 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-09 17:17:50.210  1015  1028 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 17:17:50.220  1015  1505 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,09-09 17:17:50.220  1015  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:50.220  1015  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:50.220  1015  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:50.220  1015  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:50.220  7786  7786 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:17:50.220  7786  7786 D ActivityThread: Added TimaKeyStore provider
,09-09 17:17:50.240  7802  7802 E Zygote  : MountEmulatedStorage()
09-09 17:17:50.240  7802  7802 E Zygote  : v2
09-09 17:17:50.240  7802  7802 I libpersona: KNOX_SDCARD checking this for 10009
09-09 17:17:50.240  7802  7802 I libpersona: KNOX_SDCARD not a persona
,09-09 17:17:50.240  7802  7802 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 17:17:50.240  1015  1505 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7802 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,09-09 17:17:50.240  7802  7802 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 17:17:50.240  1015  1505 I ActivityManager: Killing 7244:com.android.vending/u0a26 (adj 15): empty #21
09-09 17:17:50.240  7802  7802 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-09 17:17:50.250  1015  1491 I ActivityManager: Killing 7284:com.android.defcontainer/u0a3 (adj 15): empty #21
,09-09 17:17:50.260  7732  7732 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
09-09 17:17:50.260  7732  7732 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-09 17:17:50.260  7732  7732 I wpa_supplicant: Skip scan - bUseNetwork false
,09-09 17:17:50.260  1015  1049 I PowerManagerService: [PWL] Off : 75s ago
09-09 17:17:50.260  1015  1049 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
09-09 17:17:50.260  1015  1049 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
09-09 17:17:50.260  1015  1049 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1015, ws=null) (elapsedTime=3955)
,09-09 17:17:50.270  1015  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,09-09 17:17:50.270  1015  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
09-09 17:17:50.270  7732  7732 I wpa_supplicant: HOTSPOT20_ENABLE called
09-09 17:17:50.270  7732  7732 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 17:17:50.270  7732  7732 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 17:17:50.270  7732  7732 E wpa_supplicant: SIM READ ERROR
09-09 17:17:50.270  7732  7732 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 17:17:50.280  7802  7802 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:17:50.280  7802  7802 D ActivityThread: Added TimaKeyStore provider
,09-09 17:17:50.310  7732  7732 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-09 17:17:50.330  7732  7732 I wpa_supplicant: Skip scan - bUseNetwork false,
,09-09 17:17:50.330  1015  1127 D WifiConfigStore: Loading config and enabling all networks 
,09-09 17:17:50.330  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-09 17:17:50.340  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 17:17:50.340  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 17:17:50.340  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:17:50.340  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:17:50.340  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:17:50.340  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:50.340  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 17:17:50.340  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
09-09 17:17:50.340  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-09 17:17:50.340  1178  1704 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-09 17:17:50.340  1178  1178 D HotspotTile: onReceive : 3, 0
,09-09 17:17:50.340  7319  7319 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 17:17:50.340  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:17:50.340  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:50.340  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:17:50.340  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:17:50.340  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:17:50.340  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:17:50.340  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:17:50.340  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:17:50.350  7319  7319 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:50.350  7319  7319 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 17:17:50.350  7319  7319 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:50.350  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:17:50.350  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:50.350  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:17:50.350  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:17:50.350  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:17:50.350  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:17:50.350  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:17:50.350  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:17:50.350  7319  7319 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:50.350  7319  7319 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 17:17:50.350  1015  1127 E WifiConfigStore: Not a HS20
,09-09 17:17:50.350  4743  4743 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-09 17:17:50.360  1015  1127 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-09 17:17:50.360  1015  1127 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-09 17:17:50.360  7732  7732 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-09 17:17:50.360  7732  7732 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-09 17:17:50.360  7732  7732 I wpa_supplicant: reset timer : RESET_TIMER 0
09-09 17:17:50.360  7732  7732 I wpa_supplicant: P2P: Current p2p state = IDLE
09-09 17:17:50.360  7732  7732 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-09 17:17:50.360  7732  7732 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-09 17:17:50.360  7732  7732 I wpa_supplicant: First Scan Start
,09-09 17:17:50.360  7732  7732 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-09 17:17:50.360  1015  1127 D WifiNative-wlan0: Setting external_sim to 1
,09-09 17:17:50.360  1015  1127 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 17:17:50.360  1015  1127 I WifiNative-HAL: startHal
09-09 17:17:50.360  1015  1127 E wifi    : getStaticLongField sWifiHalHandle 0x9f6cc88c
09-09 17:17:50.360  1015  1127 I WifiNative-HAL: Could not start hal
,09-09 17:17:50.370  7493  7493 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 17:17:50.370  1015  1127 E WifiNative-wlan0: do suspend true
,09-09 17:17:50.370  1015  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-09 17:17:50.370  1015  1126 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-09 17:17:50.370   277   966 D CommandListener: Setting iface cfg
09-09 17:17:50.370   277   966 D CommandListener: Trying to bring up p2p0
,09-09 17:17:50.370  1015  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-09 17:17:50.370  1015  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-09 17:17:50.370  1015  1127 E WifiNative-wlan0: invaild command id : 215
,09-09 17:17:50.370  1015  1126 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-09 17:17:50.370  1015  1126 D WifiP2pService: P2pEnablingState
09-09 17:17:50.370  1015  1126 D WifiP2pService: P2pEnablingState{ what=147457 }
09-09 17:17:50.370  7732  7732 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-09 17:17:50.370  1015  1126 D WifiP2pService: P2p socket connection successful
09-09 17:17:50.370  1015  1126 D WifiP2pService: P2pEnabledState
,09-09 17:17:50.370  7732  7732 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-09 17:17:50.380  7732  7732 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
09-09 17:17:50.380  1015  1127 E WifiStateMachine: Failed to set frequency band 0
,09-09 17:17:50.380  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3
,09-09 17:17:50.380  1015  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 17:17:50.380  1015  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-09 17:17:50.380  1015  1127 D SecContentProvider2: mCursor = null
09-09 17:17:50.380  1015  1129 E ConnectivityService: updateNetworkInfo()
,09-09 17:17:50.380  1015  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 17:17:50.380  1015  1127 D SecContentProvider2: mCursor = null
09-09 17:17:50.380  1015  1015 D RttService: SCAN_AVAILABLE : 3
,09-09 17:17:50.380  1015  1150 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:50.380  1015  1150 I WifiNative-HAL: startHal
,09-09 17:17:50.380  1015  1151 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 17:17:50.380  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-09 17:17:50.380  1015  1150 E wifi    : getStaticLongField sWifiHalHandle 0x9e58e9bc
09-09 17:17:50.380  1015  1150 I WifiNative-HAL: Could not start hal
09-09 17:17:50.380  1015  1150 E WifiScanningService: could not start HAL
,09-09 17:17:50.380  1015  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-09 17:17:50.380  1015  1126 D WifiNative-p2p0: p2pGetDeviceAddress
09-09 17:17:50.380  1015  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 17:17:50.380  1015  1047 D WifiDisplayController: disconnect
09-09 17:17:50.380  1015  1047 D WifiDisplayController: updateConnection
09-09 17:17:50.380  1015  1126 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
09-09 17:17:50.380  1015  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 17:17:50.380  1015  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 17:17:50.390  1015  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-09 17:17:50.390  1015  1047 D WifiDisplayAdapter: onP2pDisconnected
09-09 17:17:50.390  1015  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
,09-09 17:17:50.390  1015  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
09-09 17:17:50.390  1015  1047 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
09-09 17:17:50.390  1015  1047 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
09-09 17:17:50.390  1015  1047 D WifiDisplayController:  primary type: 10-0050F204-5
09-09 17:17:50.390  1015  1047 D WifiDisplayController:  secondary type: null
09-09 17:17:50.390  1015  1047 D WifiDisplayController:  wps: 0
09-09 17:17:50.390  1015  1047 D WifiDisplayController:  grpcapab: 0
09-09 17:17:50.390  1015  1047 D WifiDisplayController:  devcapab: 0
09-09 17:17:50.390  1015  1047 D WifiDisplayController:  status: 3
09-09 17:17:50.390  1015  1047 D WifiDisplayController:  wfdInfo: null
09-09 17:17:50.390  1015  1047 D WifiDisplayController:  groupownerAddress: null
09-09 17:17:50.390  1015  1047 D WifiDisplayController:  GOdeviceName: null,
09-09 17:17:50.390  1015  1047 D WifiDisplayController:  interfaceAddress: 
09-09 17:17:50.390  1015  1047 D WifiDisplayController:  SConnectInfo : null
09-09 17:17:50.390  1015  1126 D WifiP2pService: DeviceAddress: 0a:75:42
09-09 17:17:50.390  1178  1178 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-09 17:17:50.390  1015  1466 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 17:17:50.390  1178  1178 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-09 17:17:50.400  1015  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-09 17:17:50.400  1015  1044 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 17:17:50.400  1015  1044 D Tethering: interfaceStatusChanged p2p0, false
,09-09 17:17:50.410  1015  1126 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-09 17:17:50.410  1015  1126 D WifiP2pService: InactiveState
09-09 17:17:50.410  1015  1126 D WifiP2pService: InactiveState{ what=143376 }
09-09 17:17:50.410  1015  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-09 17:17:50.410  7732  7732 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,09-09 17:17:50.410  1015  1126 D WifiP2pService: InactiveState{ what=143376 },
09-09 17:17:50.410  1015  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-09 17:17:50.440  1015  3283 I art     : Explicit concurrent mark sweep GC freed 81398(4MB) AllocSpace objects, 21(384KB) LOS objects, 33% free, 23MB/34MB, paused 2.547ms total 179.741ms
,09-09 17:17:50.460  7786  7786 D BadgeProvider: onCreate
,09-09 17:17:50.470  7786  7786 D BadgeProvider: DatabaseHelper
,09-09 17:17:50.480  1015  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,09-09 17:17:50.480  1015  1504 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,09-09 17:17:50.480  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,09-09 17:17:50.490  1015  3283 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,09-09 17:17:50.490  7786  7795 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,09-09 17:17:50.500  7786  7795 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
,09-09 17:17:50.500  7786  7795 D BadgeProvider: sendNotify, [notify] : null
09-09 17:17:50.500  7786  7795 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
09-09 17:17:50.500  7786  7795 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-09 17:17:50.500  7786  7795 D BadgeProvider: update, [UpdateCount] : 1
,09-09 17:17:50.510  1506  1506 D Launcher.Model: reloadBadges entered.
,09-09 17:17:50.520  1015  1501 I ActivityManager: Killing 7461:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,09-09 17:17:50.530  1015  1135 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 17:17:50.530  1015  1135 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-09 17:17:50.530  1015  1135 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:50.530  1015  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:50.530  1015  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 17:17:50.530  1605  1605 I Hs20UtilService: Starting #12
,09-09 17:17:50.530  1605  1643 I Hs20UtilService: Message received 5011
,09-09 17:17:50.530  7140  7140 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-09 17:17:50.530  7140  7140 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-09 17:17:50.530  7140  7140 D SecurityLogAgent: StateMachine : Current State = 1
,09-09 17:17:50.530  7140  7140 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 17:17:50.540  1015  1505 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 17:17:50.540  1015  1505 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 17:17:50.540  1015  1505 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:50.550  1015  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:50.550  1015  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 17:17:50.550  1605  1605 I Hs20UtilService: Starting #13
,09-09 17:17:50.550  7140  7140 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-09 17:17:50.550  7140  7140 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 17:17:50.550  7140  7140 D SecurityLogAgent: StateMachine : Current State = 1
,09-09 17:17:50.550  7140  7140 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 17:17:50.550  1605  1643 I Hs20UtilService: Message received 5011
,09-09 17:17:50.560  1015  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-09 17:17:50.560  1015  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-09 17:17:50.560  1015  1127 E WifiNative-wlan0: invaild command id : 215
,09-09 17:17:50.560  4743  4743 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-09 17:17:50.560  4743  4743 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 17:17:50.560  4743  4743 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 17:17:50.560  4743  4743 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-09 17:17:50.560  4743  4743 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 17:17:50.560  4743  4743 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 17:17:50.560  4743  4825 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 17:17:50.680  7478  7478 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 17:17:50.730   287   287 E SMD     : DCD OFF
,09-09 17:17:50.990  1015  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-09 17:17:50.990  1015  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:50.990  1015  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:50.990  1015  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:51.000  7825  7825 E Zygote  : MountEmulatedStorage()
,09-09 17:17:51.000  7825  7825 E Zygote  : v2
09-09 17:17:51.000  7825  7825 I libpersona: KNOX_SDCARD checking this for 10011
09-09 17:17:51.000  7825  7825 I libpersona: KNOX_SDCARD not a persona
,09-09 17:17:51.010  7825  7825 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 17:17:51.010  1015  1042 I ActivityManager: Start proc com.google.android.gms:car for service com.google.android.gms/.car.InCallServiceImpl: pid=7825 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,09-09 17:17:51.010  7825  7825 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 17:17:51.020  7825  7825 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-09 17:17:51.040  7825  7825 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:17:51.040  7825  7825 D ActivityThread: Added TimaKeyStore provider
,09-09 17:17:51.060  7825  7825 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-09 17:17:51.060  7825  7825 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-09 17:17:51.100  7825  7825 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,09-09 17:17:51.100  7825  7825 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,09-09 17:17:51.110  7825  7825 I MultiDex: VM with version 2.1.0 has multidex support
,09-09 17:17:51.110  7825  7825 I MultiDex: install
,09-09 17:17:51.110  7825  7825 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-09 17:17:51.130  7825  7825 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,09-09 17:17:51.220  7825  7825 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-09 17:17:51.220  7825  7825 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@e29a4fd: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
09-09 17:17:51.220  7825  7825 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-09 17:17:51.220  1015  1042 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:51.220  1015  1042 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:51.220  1015  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:51.230  1015  1135 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,09-09 17:17:51.230  1015  1135 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-09 17:17:51.230  1015  1135 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:51.230  1015  1135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 17:17:51.230  1015  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,09-09 17:17:51.230  1015  1504 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
09-09 17:17:51.230  1015  1504 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
09-09 17:17:51.230  1015  1504 I splitIntent: other index=5, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
09-09 17:17:51.230  1015  1504 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,09-09 17:17:51.230  1698  5077 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,09-09 17:17:51.230  1015  1504 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:51.230  1015  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 17:17:51.230  1015  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:51.240  1015  1504 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:51.240  1015  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:51.240  1015  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:51.240  1698  1698 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,09-09 17:17:51.250  1015  1135 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:51.250  1015  1135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:51.250  1015  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:51.250  1015  1491 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
09-09 17:17:51.250  1015  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,09-09 17:17:51.250  1015  1491 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:51.250  1015  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:51.250  1015  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,09-09 17:17:51.260  1015  1135 I ActivityManager: Killing 7392:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,09-09 17:17:51.260  1015  1135 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:51.260  1015  1135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:51.260  1015  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:51.260  1698  1698 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 17:17:51.270  1015  1135 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:51.270  1015  1135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 17:17:51.270  1015  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:51.270  1871  1871 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,09-09 17:17:51.270  1015  3280 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 17:17:51.270  1015  3280 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,09-09 17:17:51.270  1015  3280 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:51.270  1015  3280 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:51.270  1015  3280 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:51.280  1015  3283 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:51.280  1015  3283 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:51.280  1015  3283 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:51.280  7825  7842 D NativeLibraryUtils: Install completed successfully. count=0 extracted=0
,09-09 17:17:51.280  1015  1504 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:51.280  1015  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:51.280  1015  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:51.290  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:51.290  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 17:17:51.290  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:51.290  1015  1346 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 17:17:51.290  1015  1346 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:51.300  1015  1346 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:51.300  1015  1346 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:51.300  1015  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:51.300  1015  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:51.300  1015  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:51.300  1015  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:51.310  7844  7844 E Zygote  : MountEmulatedStorage(),
09-09 17:17:51.310  1015  1346 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=7844 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
09-09 17:17:51.310  7844  7844 E Zygote  : v2
09-09 17:17:51.310  7844  7844 I libpersona: KNOX_SDCARD checking this for 10011
09-09 17:17:51.310  7844  7844 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 17:17:51.310  7844  7844 I libpersona: KNOX_SDCARD not a persona
,09-09 17:17:51.320  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:51.320  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:51.320  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:51.320  1015  1491 W ActivityManager: userId = 0, bbcId = -10000,
09-09 17:17:51.320  1015  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:51.320  1015  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:51.320  7844  7844 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-09 17:17:51.330  7844  7844 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-09 17:17:51.340  1015  1244 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:51.340  1015  1244 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:51.340  1015  1244 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:51.340  1015  3283 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:51.340  1015  3283 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 17:17:51.340  1015  3283 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:51.340  1015  1504 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 17:17:51.350  1015  1504 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:51.350  1015  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:51.350  1015  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:51.350  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:51.350  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:51.350  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:51.360  1015  1505 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 17:17:51.360  1015  1505 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,09-09 17:17:51.360  1015  1505 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:51.360  1015  1505 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:51.360  1015  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:51.370  1871  7857 D LocationInitializer: Restart initialization of location
,09-09 17:17:51.370  1015  3282 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 17:17:51.370  1015  3282 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,09-09 17:17:51.370  7844  7844 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:17:51.370  1015  3282 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:51.370  1015  3282 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:51.370  1015  3282 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:51.370  7844  7844 D ActivityThread: Added TimaKeyStore provider
,09-09 17:17:51.380  1015  1244 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 17:17:51.390  1015  1244 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:51.390  1015  1244 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:51.390  1015  1244 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,09-09 17:17:51.400  7844  7844 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-09 17:17:51.400  7844  7844 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-09 17:17:51.420  7844  7844 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,09-09 17:17:51.430  7844  7844 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,09-09 17:17:51.430  7844  7844 I MultiDex: VM with version 2.1.0 has multidex support
09-09 17:17:51.430  7844  7844 I MultiDex: install
09-09 17:17:51.430  7844  7844 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-09 17:17:51.450  7844  7844 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,09-09 17:17:51.520  7844  7844 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-09 17:17:51.520  7844  7844 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@e29a4fd: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-09 17:17:51.520  7844  7844 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-09 17:17:51.520  1015  1042 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:51.520  1015  1042 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:51.520  1015  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:51.520  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,09-09 17:17:51.530  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-09 17:17:51.530  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:51.530  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:51.530  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,09-09 17:17:51.530  1015  1135 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,09-09 17:17:51.530  1698  2521 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
09-09 17:17:51.530  1015  1135 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
09-09 17:17:51.530  1015  1135 I splitIntent: other index=5, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
,09-09 17:17:51.530  1015  1135 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,09-09 17:17:51.530  1015  1135 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:51.530  1015  1135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:51.530  1015  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:51.540  1015  1466 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:51.540  1015  1466 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:51.540  1015  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:51.540  1698  1698 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,09-09 17:17:51.540  1015  1505 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:51.540  7844  7844 D WearableService: callingUid 10011, callindPid: 7844
09-09 17:17:51.540  1015  1505 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 17:17:51.540  1015  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:51.550  1015  1491 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,09-09 17:17:51.550  1015  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,09-09 17:17:51.550  1015  1491 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:51.550  1015  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 17:17:51.550  1015  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,09-09 17:17:51.560  1698  1698 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 17:17:51.560  1015  1501 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:51.560  1015  1501 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:51.560  1015  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:51.560  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:51.560  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:51.560  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:51.570  1871  1871 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,09-09 17:17:51.570  1015  1466 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 17:17:51.570  1015  1466 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,09-09 17:17:51.570  1015  1466 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:51.570  1015  1466 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:51.570  1015  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:51.570  7844  7863 D NativeLibraryUtils: Install completed successfully. count=0 extracted=0
,09-09 17:17:51.570  1015  1491 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:51.570  1015  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:51.570  1015  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:51.580  1015  3283 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:51.580  1015  3283 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:51.580  1015  3283 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:51.580  1015  1346 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:51.580  1015  1346 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:51.580  1015  1346 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:51.590  1015  1346 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:51.590  1015  1346 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:51.590  1015  1346 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,09-09 17:17:51.590  1015  1346 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:51.590  1015  1346 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:51.590  1015  1346 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:51.600  1681  3114 E MDM     : [166] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,09-09 17:17:51.610  1681  3114 E MDM     : [166] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,09-09 17:17:51.610  1015  1346 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:51.610  1015  1346 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:51.610  1015  1346 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:51.610  1015  1244 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:51.610  1015  1244 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:51.610  1015  1244 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:51.610  1015  1505 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 17:17:51.620  1015  1505 W ActivityManager: userId = 0, bbcId = -10000,
09-09 17:17:51.620  1015  1505 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:51.620  1015  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:51.620  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:51.620  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:51.620  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:51.630  1015  1028 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 17:17:51.630  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,09-09 17:17:51.630  1015  1028 W ActivityManager: userId = 0, bbcId = -10000,
09-09 17:17:51.630  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:51.630  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:51.630  1871  7865 D LocationInitializer: Restart initialization of location
09-09 17:17:51.630  1015  3282 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 17:17:51.630  1015  3282 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,09-09 17:17:51.630  1015  3282 W ActivityManager: userId = 0, bbcId = -10000,
09-09 17:17:51.630  1015  3282 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:51.630  1015  3282 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:51.670  7732  7732 I wpa_supplicant: nl80211: Received scan results (25 BSSes)
,09-09 17:17:51.670  7732  7732 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-09 17:17:51.670  7732  7732 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-09 17:17:51.670  7732  7732 I wpa_supplicant: Trying to associate with  'G700'
09-09 17:17:51.670  7732  7732 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
09-09 17:17:51.670  7732  7732 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
09-09 17:17:51.670  1015  7814 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-09 17:17:51.680  1015  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 17:17:51.680  1015  1127 D SecContentProvider2: mCursor = null
,09-09 17:17:51.790  7732  7732 E wpa_supplicant: Cmd 35605 not handled
,09-09 17:17:51.790  7732  7732 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,09-09 17:17:51.790  1015  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 17:17:51.790  1015  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 17:17:51.790  1015  1044 D Tethering: interfaceStatusChanged wlan0, false
09-09 17:17:51.790  7732  7732 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-09 17:17:51.790  7732  7732 I wpa_supplicant: Associated with F4.99.3E
09-09 17:17:51.790  7732  7732 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-09 17:17:51.790  7732  7732 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-09 17:17:51.790  7732  7732 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-09 17:17:51.800  1015  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 17:17:51.800  1015  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 17:17:51.800  1015  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-09 17:17:51.800  1015  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 17:17:51.800  1015  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 17:17:51.800  1015  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-09 17:17:51.800  1015  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
09-09 17:17:51.800  1015  1127 D SecContentProvider2: mCursor = null
,09-09 17:17:51.800  1015  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true,
09-09 17:17:51.800  1015  1044 D Tethering: interfaceLinkStateChanged wlan0, true
09-09 17:17:51.800  1015  1044 D Tethering: interfaceStatusChanged wlan0, true
,09-09 17:17:51.810  1015  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 17:17:51.810  1015  1127 D SecContentProvider2: mCursor = null
09-09 17:17:51.810  7732  7732 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-09 17:17:51.810  7732  7732 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
09-09 17:17:51.810  7732  7732 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-09 17:17:51.810  1015  1130 E Tethering: No numeric data
09-09 17:17:51.810  7732  7732 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,09-09 17:17:51.810  7732  7732 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 17:17:51.810  1015  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-09 17:17:51.810  1015  1130 D Tethering: clearTetheredNotification()
09-09 17:17:51.810  7732  7732 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,09-09 17:17:51.810  1015  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-09 17:17:51.810  7732  7732 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-09 17:17:51.810  7732  7732 I wpa_supplicant: Blacklist: Clear (temp) 
09-09 17:17:51.810  7732  7732 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-09 17:17:51.810  1015  1044 D Tethering: interfaceLinkStateChanged wlan0, true
,09-09 17:17:51.810  1015  1044 D Tethering: interfaceStatusChanged wlan0, true
,09-09 17:17:51.820  1015  1127 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-09 17:17:51.820  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:17:51.820  1015  1124 V NetworkStats: performPollLocked(flags=0x1)
,09-09 17:17:51.820  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-09 17:17:51.820  1178  1178 D HotspotTile: updateTetherState():false, false
,09-09 17:17:51.830  1015  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 17:17:51.830  1015  1127 E WifiConfigStore: setLastSelectedConfiguration -1
,09-09 17:17:51.830  1015  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 17:17:51.830  1015  1124 V NetworkStats: performPollLocked() took 10ms
09-09 17:17:51.830  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:17:51.830  1015  1127 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-09 17:17:51.840  1015  1129 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-09 17:17:51.840  1015  1129 E ConnectivityService: updateNetworkInfo()
09-09 17:17:51.840  1015  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-09 17:17:51.840  1015  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 17:17:51.840  1015  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:17:51.840  1015  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:17:51.850  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-09 17:17:51.850  1015  3280 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 17:17:51.850  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 17:17:51.850  1015  3280 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-09 17:17:51.850  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 17:17:51.850  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:17:51.850  1015  3280 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:51.850  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:51.850  1015  3280 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 17:17:51.850  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:51.850  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:51.850  1015  3280 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-09 17:17:51.850  1605  1605 I Hs20UtilService: Starting #14
09-09 17:17:51.850  1605  1643 I Hs20UtilService: Message received 5007
,09-09 17:17:51.860  4743  4743 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-09 17:17:51.860  4743  4743 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-09 17:17:51.860  1015  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 17:17:51.860  4743  4743 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 17:17:51.860  4743  4743 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-09 17:17:51.860  4743  4743 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 17:17:51.860  4743  4743 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-09 17:17:51.870  4743  4825 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 17:17:51.870   277   966 D CommandListener: Setting iface cfg
,09-09 17:17:51.880  1015  1127 E WifiStateMachine: Start Dhcp Watchdog 2
,09-09 17:17:51.880  1015  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 17:17:51.880  1015  1127 D SecContentProvider2: mCursor = null
,09-09 17:17:51.890  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-09 17:17:51.890  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 17:17:51.890  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 17:17:51.890  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:51.890  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:51.890  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:17:51.900  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:17:51.900  1015  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-09 17:17:51.900  1015  1127 D SecContentProvider2: mCursor = null
,09-09 17:17:51.910  1015  1127 E WifiNative-wlan0: do suspend false
,09-09 17:17:51.910  1015  1126 D WifiP2pService: InactiveState{ what=143375 }
,09-09 17:17:51.910  1015  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-09 17:17:51.960  1015  1326 E Watchdog: !@Sync 4
,09-09 17:17:52.030  1015  1028 D SecContentProvider: uri = 18 selection = isWifiEnabled,
09-09 17:17:52.030  1015  1028 D WifiService: setWifiEnabled: false pid=7319, uid=10170
09-09 17:17:52.030  1015  1028 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-09 17:17:52.030  1015  1028 D SecContentProvider2: mCursor = null
09-09 17:17:52.030  1015  1028 D SettingsProvider: name = wifi_on
,09-09 17:17:52.040  1015  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 17:17:52.060  1015  1127 E WifiNative-wlan0: do suspend true,
,09-09 17:17:52.080  1015  1126 D WifiP2pService: InactiveState{ what=143375 },
,09-09 17:17:52.080  1015  1126 D WifiP2pService: P2pEnabledState{ what=143375 },
,09-09 17:17:52.080   277   966 D CommandListener: Clearing all IP addresses on wlan0
,09-09 17:17:52.090  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-09 17:17:52.090  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 17:17:52.090  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-09 17:17:52.090  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:52.090  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:52.090  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:52.090  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:17:52.090  1015  1129 E ConnectivityService: updateNetworkInfo()
,09-09 17:17:52.090  1015  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-09 17:17:52.090  1015  1129 E ConnectivityService: updateNetworkInfo()
09-09 17:17:52.090  1015  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0,
09-09 17:17:52.090   277   966 E Netd    : no such netId 503
09-09 17:17:52.090  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-09 17:17:52.100  1015  1129 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '78 network destroy 503' failed with '400 78 destroyNetwork() failed (Machine is not on the network)'
09-09 17:17:52.100  1015  1129 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,09-09 17:17:52.100  1015  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:17:52.100  1015  1129 V NetworkStats: updateIfacesLocked()
09-09 17:17:52.100  1015  1129 V NetworkStats: performPollLocked(flags=0x1)
09-09 17:17:52.100  1015  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 17:17:52.100  1015  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 17:17:52.100  1015  1129 V NetworkStats: performPollLocked() took 5ms
09-09 17:17:52.100  1015  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:17:52.110  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-09 17:17:52.110  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 17:17:52.110  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-09 17:17:52.110  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:17:52.120  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:52.120  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:52.120  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:17:52.120  1015  1126 D WifiP2pService: InactiveState{ what=131204 }
09-09 17:17:52.120  1015  1127 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-09 17:17:52.120  1015  1126 D WifiP2pService: P2pEnabledState{ what=131204 }
,09-09 17:17:52.120  1015  1129 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503],
09-09 17:17:52.120  1015  7867 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:52.120  1015  1126 D WifiP2pService: sending p2p connection changed broadcast: FAILED
09-09 17:17:52.120  1015  7867 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
,09-09 17:17:52.130  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1
09-09 17:17:52.130  1015  1150 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 17:17:52.130  1015  1129 D ConnectivityService: nai.networkMonitor.doQuit()
09-09 17:17:52.130  1015  1129 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-09 17:17:52.130  1015  1129 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-09 17:17:52.130  1015  1129 E ConnectivityService: updateNetworkInfo()
,09-09 17:17:52.130  1015  1015 D RttService: SCAN_AVAILABLE : 1,
09-09 17:17:52.130  1015  1151 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:52.130  1015  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:17:52.130  1015  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:17:52.130  1015  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:17:52.130  1015  1047 D WifiDisplayAdapter: onP2pDisconnected
09-09 17:17:52.130  1015  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 17:17:52.130  1015  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
09-09 17:17:52.140  1015  3280 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 17:17:52.140  1015  3280 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 17:17:52.140  1015  3280 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:52.140  1015  3280 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:52.140  1015  3280 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 17:17:52.140  1605  1605 I Hs20UtilService: Starting #15
09-09 17:17:52.140  1015  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-09 17:17:52.140  1015  1129 E ConnectivityService: updateNetworkInfo()
09-09 17:17:52.140  1605  1643 I Hs20UtilService: Message received 5007
,09-09 17:17:52.140  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-09 17:17:52.140  1015  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-09 17:17:52.140  7870  7870 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
09-09 17:17:52.140  1015  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 17:17:52.140  1015  1047 D WifiDisplayController: disconnect
09-09 17:17:52.140  1015  1047 D WifiDisplayController: updateConnection
09-09 17:17:52.140  1015  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 17:17:52.140  1015  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 17:17:52.150  7870  7870 I dhcpcd  : version 5.5.6 starting
09-09 17:17:52.150  4743  4743 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-09 17:17:52.150  4743  4743 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-09 17:17:52.150  7870  7870 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-09 17:17:52.150  4743  4743 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 17:17:52.150  1178  1178 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-09 17:17:52.150  1015  1027 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-09 17:17:52.150  1178  1178 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-09 17:17:52.150  1015  1126 D WifiP2pService: P2pDisablingState
09-09 17:17:52.150  1015  1126 D WifiP2pService: P2pDisablingState{ what=147458 }
09-09 17:17:52.160  1015  1126 D WifiP2pService: p2p socket connection lost
,09-09 17:17:52.160  1015  1127 E WifiNative-wlan0: do suspend true
09-09 17:17:52.160  1015  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-09 17:17:52.160  1015  1047 D WifiDisplayAdapter: onP2pDisconnected
09-09 17:17:52.160  1015  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 17:17:52.160  1015  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
09-09 17:17:52.160  4743  4743 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-09 17:17:52.160  1015  1126 D WifiP2pService: P2pDisabledState
09-09 17:17:52.160  4743  4743 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 17:17:52.160  4743  4743 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 17:17:52.160  4743  4825 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 17:17:52.170  4743  4743 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-09 17:17:52.170  4743  4743 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 17:17:52.170  4743  4743 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-09 17:17:52.170  4743  4743 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-09 17:17:52.170  4743  4743 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 17:17:52.170  4743  4743 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 17:17:52.170  4743  4825 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 17:17:52.180  1015  1505 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,09-09 17:17:52.180  1015  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,09-09 17:17:52.180  1015  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:52.180  1015  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-09 17:17:52.180  1015  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:52.190  1015  1126 D WifiP2pService: P2pDisabledState{ what=143375 },
09-09 17:17:52.190  1015  1126 D WifiP2pService: DefaultState{ what=143375 }
,09-09 17:17:52.200  7875  7875 E Zygote  : MountEmulatedStorage()
,09-09 17:17:52.200  7875  7875 E Zygote  : v2
09-09 17:17:52.200  7875  7875 I libpersona: KNOX_SDCARD checking this for 10064
09-09 17:17:52.200  7875  7875 I libpersona: KNOX_SDCARD not a persona
09-09 17:17:52.200  7875  7875 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 17:17:52.200  1015  1505 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7875 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 17:17:52.200   277   966 D CommandListener: Clearing all IP addresses on wlan0,
,09-09 17:17:52.210  7875  7875 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 17:17:52.210  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-09 17:17:52.210  7732  7732 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
09-09 17:17:52.210  7875  7875 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 17:17:52.210  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-09 17:17:52.210  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 17:17:52.210  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 17:17:52.210  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:52.210  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:52.210  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:17:52.210  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:17:52.220  1015  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
09-09 17:17:52.220  1015  1127 D SecContentProvider2: mCursor = null
09-09 17:17:52.220  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-09 17:17:52.220  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 17:17:52.220  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 17:17:52.220  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:52.220  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:52.220  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:52.220  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:17:52.230  4743  4743 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-09 17:17:52.230  7319  7319 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:52.230  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:17:52.230  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:52.230  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:17:52.230  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:17:52.230  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:17:52.230  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:17:52.230  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:17:52.230  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:17:52.230  7319  7319 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:52.230  7319  7319 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:17:52.230  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-09 17:17:52.230  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 17:17:52.230  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-09 17:17:52.230  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:52.230  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:52.230  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:17:52.230  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:52.230  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 17:17:52.230  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 17:17:52.230  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
09-09 17:17:52.230  1178  1704 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-09 17:17:52.230  1178  1178 D HotspotTile: onReceive : 0, 0
09-09 17:17:52.230  7870  7870 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,09-09 17:17:52.230  7870  7870 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-09 17:17:52.230  7870  7870 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
09-09 17:17:52.230  7319  7319 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:52.230  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:17:52.230  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:52.230  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:17:52.230  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:17:52.230  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
,09-09 17:17:52.230  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:17:52.230  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:17:52.230  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:17:52.230  7870  7870 I dhcpcd  : bssid match
,09-09 17:17:52.240  7319  7319 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:52.240  7319  7319 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:17:52.240  7870  7870 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,09-09 17:17:52.240  7875  7875 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 17:17:52.240  7875  7875 D ActivityThread: Added TimaKeyStore provider
,09-09 17:17:52.250  7875  7875 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-09 17:17:52.260  7875  7875 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 17:17:52.270  7875  7875 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-09 17:17:52.290  7875  7875 D FileShare-Client: Outbound.stopDelayTimer - 
,09-09 17:17:52.300  7478  7478 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 17:17:52.300  1015  1027 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 17:17:52.300  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 17:17:52.310  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:52.310  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:52.310  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 17:17:52.310  1605  1605 I Hs20UtilService: Starting #16
,09-09 17:17:52.310  1605  1643 I Hs20UtilService: Message received 5007
,09-09 17:17:52.310  4743  4743 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-09 17:17:52.310  4743  4743 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 17:17:52.310  4743  4743 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 17:17:52.310  4743  4743 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-09 17:17:52.310  4743  4743 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 17:17:52.310  4743  4743 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 17:17:52.310  4743  4825 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 17:17:52.320  1015  1505 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
,09-09 17:17:52.320  1015  1505 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:52.320  1015  1505 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-09 17:17:52.320  1015  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:52.320  1015  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 17:17:52.320  7140  7140 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-09 17:17:52.320  7140  7140 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 17:17:52.320  7140  7140 D SecurityLogAgent: StateMachine : Current State = 1
,09-09 17:17:52.330  7140  7140 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 17:17:52.330  1605  1605 I Hs20UtilService: Starting #17
,09-09 17:17:52.330  7870  7870 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
09-09 17:17:52.330  1605  1643 I Hs20UtilService: Message received 5011
,09-09 17:17:52.340  7732  7732 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 17:17:52.400  7732  7732 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING ,
,09-09 17:17:52.400  1015  1044 D Tethering: interfaceLinkStateChanged p2p0, false
,09-09 17:17:52.400  1015  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 17:17:52.400  1015  1044 D Tethering: interfaceStatusChanged p2p0, false
,09-09 17:17:52.430  7732  7732 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1,
09-09 17:17:52.430  7732  7732 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-09 17:17:52.430  7732  7732 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-09 17:17:52.430  7732  7732 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-09 17:17:52.430  7732  7732 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
09-09 17:17:52.430  1015  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 17:17:52.430  1015  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 17:17:52.430  1015  1044 D Tethering: interfaceStatusChanged wlan0, false
09-09 17:17:52.430  1015  1130 D Tethering: InitialState.processMessage what=4
,09-09 17:17:52.430  1015  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 17:17:52.430  1015  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 17:17:52.430  1015  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-09 17:17:52.430  1015  1130 E Tethering: No numeric data
,09-09 17:17:52.440  1015  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-09 17:17:52.440  1015  1130 D Tethering: clearTetheredNotification()
09-09 17:17:52.440  1015  1124 V NetworkStats: performPollLocked(flags=0x1)
09-09 17:17:52.440  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:17:52.440  1015  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-09 17:17:52.440  1015  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-09 17:17:52.440  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 17:17:52.440  1178  1178 D HotspotTile: updateTetherState():false, false
,09-09 17:17:52.440  1015  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 17:17:52.440  1015  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 17:17:52.440  1015  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-09 17:17:52.440  1015  1124 V NetworkStats: performPollLocked() took 6ms
,09-09 17:17:52.440  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:17:52.440  1015  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:17:52.440  1015  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:17:52.500  7870  7870 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds,
,09-09 17:17:52.730  7732  7732 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 17:17:52.730   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 17:17:52.790  1015  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 17:17:52.790  1015  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 17:17:52.790  1015  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-09 17:17:52.870  1015  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 17:17:52.870  1015  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 17:17:52.870  1015  1044 D Tethering: interfaceStatusChanged wlan0, false
09-09 17:17:52.870  7732  7732 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-09 17:17:52.980  1015  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
09-09 17:17:52.980  1015  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-09 17:17:52.980  7493  7493 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,09-09 17:17:53.000  4743  4743 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-09 17:17:53.000  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:53.000  1681  2163 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 17:17:53.000  1015  1466 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 17:17:53.000  1015  1466 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 17:17:53.000  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-09 17:17:53.000  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 17:17:53.000  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-09 17:17:53.000  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:53.000  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:53.000  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:53.000  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:53.000  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 17:17:53.000  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
09-09 17:17:53.000  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 17:17:53.000  1178  1704 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-09 17:17:53.000  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:53.000  1178  1178 D HotspotTile: onReceive : 1, 0
09-09 17:17:53.000  1015  1466 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:53.000  1015  1466 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:53.000  1015  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 17:17:53.010  1605  1605 I Hs20UtilService: Starting #18
,09-09 17:17:53.010  1605  1643 I Hs20UtilService: Message received 5011
,09-09 17:17:53.010  7140  7140 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-09 17:17:53.010  7140  7140 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 17:17:53.010  7140  7140 D SecurityLogAgent: StateMachine : Current State = 1
,09-09 17:17:53.010  7140  7140 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 17:17:53.670   277   958 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,09-09 17:17:53.670  1015  1044 D Tethering: interfaceRemoved wlan0,
09-09 17:17:53.670  1015  1044 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-09 17:17:53.730   287   287 E SMD     : DCD OFF
,09-09 17:17:53.730   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 17:17:53.910  1015  1044 D Tethering: interfaceRemoved p2p0
,09-09 17:17:53.910  1015  1044 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-09 17:17:54.660  1015  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-09 17:17:54.740   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 17:17:55.040  7319  7373 D BluetoothAdapter: enable()
,09-09 17:17:55.050  1015  1244 W ActivityManager: Permission Denial: getCurrentUser() from pid=7319, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-09 17:17:55.050  1015  1244 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-09 17:17:55.050  1015  1244 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7319, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-09 17:17:55.050  1015  1244 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-09 17:17:55.050  1015  1244 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
09-09 17:17:55.050  1015  1244 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-09 17:17:55.050  1015  1244 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-09 17:17:55.050  1015  1244 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-09 17:17:55.050  1015  1244 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-09 17:17:55.050  1015  1244 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-09 17:17:55.070  1015  1244 D SettingsProvider: name = bluetooth_on,
,09-09 17:17:55.080  1015  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-09 17:17:55.080  1015  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-09 17:17:55.080  1015  1046 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-09 17:17:55.090  3225  3301 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-09 17:17:55.090  3225  3301 D BluetoothAdapterProperties: Setting state to 11
09-09 17:17:55.090  3225  3301 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,09-09 17:17:55.090  3225  3301 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-09 17:17:55.090  3225  3301 D BluetoothAdapterService: updateAdapterState state is 11
,09-09 17:17:55.090  3225  3301 D BluetoothAdapterService: Autoconnection is available 
,09-09 17:17:55.090  3225  3301 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-09 17:17:55.090  3225  3301 D BtConfig.SecureMode: isSecureModeOn:false
09-09 17:17:55.090  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-09 17:17:55.090  3225  3301 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
,09-09 17:17:55.090  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-09 17:17:55.090  3225  3301 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
,09-09 17:17:55.090  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-09 17:17:55.090  3225  3301 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10,
09-09 17:17:55.090  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 17:17:55.090  3225  3301 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
09-09 17:17:55.090  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-09 17:17:55.090  3225  3301 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
09-09 17:17:55.090  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-09 17:17:55.090  3225  3301 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
,09-09 17:17:55.090  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService,
09-09 17:17:55.090  3225  3301 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
09-09 17:17:55.100  1015  1504 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:17:55.090  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-09 17:17:55.100  1015  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-09 17:17:55.090  3225  3301 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
09-09 17:17:55.090  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-09 17:17:55.090  3225  3301 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-09 17:17:55.090  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-09 17:17:55.090  3225  3301 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-09 17:17:55.090  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-09 17:17:55.090  3225  3301 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-09 17:17:55.090  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-09 17:17:55.090  3225  3301 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
09-09 17:17:55.090  3225  3301 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
09-09 17:17:55.090  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-09 17:17:55.090  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-09 17:17:55.090  3225  3301 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-09 17:17:55.100  1015  1504 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:55.100  1015  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:55.100  1015  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:55.100  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
09-09 17:17:55.100  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-09 17:17:55.100  3225  3301 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-09 17:17:55.100  3225  3225 D HeadsetService: Received start request. Starting profile...
,09-09 17:17:55.100  3225  3225 D HeadsetService: start()
09-09 17:17:55.100  3225  3225 D HeadsetStateMachine: make
,09-09 17:17:55.110  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:17:55.110  1015  1015 I InputMethodManagerService: [BT Setting State] State =11,
,09-09 17:17:55.120  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-09 17:17:55.120  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:55.120  1178  1178 D BluetoothTile:  getBluetoothState : 11
,09-09 17:17:55.120  3225  3225 E HeadsetStateMachine: # of Max HF connection is 2
,09-09 17:17:55.120  2019  2019 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-09 17:17:55.120  1178  1704 D BluetoothTile:  handleUpdatestate:false name:null
09-09 17:17:55.120  1178  1704 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-09 17:17:55.130  4743  4743 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:17:55.130  1015  1466 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 17:17:55.130  1015  3280 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-09 17:17:55.130  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ),
,09-09 17:17:55.130  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:55.130  1015  1505 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 17:17:55.130  1015  1505 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 17:17:55.140  1015  1505 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:55.140  1015  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 17:17:55.140  1015  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:55.140  1015  1244 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
09-09 17:17:55.140  1015  1244 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-09 17:17:55.140  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
09-09 17:17:55.140  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 17:17:55.140  3225  3301 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-09 17:17:55.140  1015  1244 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:55.140  1015  1244 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:55.140  1015  1244 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-09 17:17:55.140  1015  3280 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:17:55.140  1015  3280 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-09 17:17:55.140  1015  3280 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:55.140  1015  3280 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:55.140  1015  3280 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:55.150  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:55.150  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
09-09 17:17:55.150  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-09 17:17:55.150  3225  3301 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-09 17:17:55.150  1015  3282 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:17:55.150  1015  3282 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-09 17:17:55.150  1015  3282 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:55.150  1015  3282 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:55.150  1015  3282 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:55.150  1015  1027 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,09-09 17:17:55.150  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
09-09 17:17:55.150  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-09 17:17:55.150  3225  3301 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-09 17:17:55.150  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-09 17:17:55.150  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:55.150  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:55.150  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-09 17:17:55.150  3225  3225 I bluedroid: get_profile_interface handsfree
,09-09 17:17:55.160  1015  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:17:55.160  1015  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-09 17:17:55.160  1015  1491 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:55.160  1015  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:55.160  1015  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:55.160  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
09-09 17:17:55.160  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 17:17:55.160  3225  3301 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-09 17:17:55.160  1698  1698 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 17:17:55.160  1015  1466 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 17:17:55.160  1015  1466 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-09 17:17:55.160  1015  1466 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:55.170  1015  1466 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 17:17:55.170  1015  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:55.170  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
09-09 17:17:55.170  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-09 17:17:55.170  3225  3301 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-09 17:17:55.170  1015  1244 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 17:17:55.180  1015  1244 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-09 17:17:55.180  3225  3225 E DualScoManager: Dual Sco Manager already instantiated
09-09 17:17:55.180  3225  3225 I DualScoManager: Set HeadsetServiceHelper
09-09 17:17:55.180  3225  3225 D BluetoothAtMessage: createCMTIContentObservers
09-09 17:17:55.180  1015  1504 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,09-09 17:17:55.180  1015  1504 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 17:17:55.180  1015  1504 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 17:17:55.180  1015  1504 D SettingsProvider: selectionArgs: false
09-09 17:17:55.180  1015  1504 D SettingsProvider: selectionArgs: 1002
09-09 17:17:55.180  1015  1504 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 17:17:55.180  1015  1504 D SettingsProvider: ret = -1
09-09 17:17:55.180  1015  1244 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:55.180  1015  1244 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
09-09 17:17:55.180  1015  1244 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 17:17:55.180  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-09 17:17:55.180  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-09 17:17:55.180  3225  3301 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-09 17:17:55.180  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-09 17:17:55.180  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-09 17:17:55.180  3225  3301 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-09 17:17:55.180  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-09 17:17:55.180  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-09 17:17:55.180  3225  3301 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-09 17:17:55.180  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-09 17:17:55.180  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-09 17:17:55.180  3225  3301 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-09 17:17:55.180  3225  3301 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-09 17:17:55.180  3225  7916 D HeadsetStateMachine: Enter Disconnected: -2
,09-09 17:17:55.180  3225  3225 D HeadsetService: mStartError = false
09-09 17:17:55.180  3225  3225 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29627d18
09-09 17:17:55.180  4743  4743 D BluetoothNotiBroadcastReceiver: onReceive
,09-09 17:17:55.180  3225  7916 D HeadsetStateMachine: Clear mHeadsetBrsf
09-09 17:17:55.180  3225  7916 D HeadsetStateMachine: map size, before remove : 0
09-09 17:17:55.180  3225  7916 D HeadsetStateMachine: map size, after remove: 0
,09-09 17:17:55.180  3225  3225 D HeadsetStateMachine: Try to query the phonestate on bind
,09-09 17:17:55.190  1452  1477 I Telecom : BluetoothPhoneService: queryPhoneState
,09-09 17:17:55.190  1452  1452 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,09-09 17:17:55.190  1452  1452 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-09 17:17:55.190  1452  1477 I Telecom : BluetoothPhoneService: Result of Message : true
,09-09 17:17:55.190  3225  3225 D A2dpService: Received start request. Starting profile...
09-09 17:17:55.190  3225  3225 D A2dpService: start()
09-09 17:17:55.190  3225  3225 I bluedroid: get_profile_interface avrcp
,09-09 17:17:55.190  3225  3225 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-09 17:17:55.190  3225  3225 D Avrcp   : Initialize Media Controller
09-09 17:17:55.190  3225  3225 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,09-09 17:17:55.190  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:55.200  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-09 17:17:55.200  3225  3225 E Avrcp   : getActiveSessions
09-09 17:17:55.200  1015  1504 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
09-09 17:17:55.200  3225  3225 D Avrcp   : pick active media Controller
09-09 17:17:55.200  3225  3225 D Avrcp   : Get the active Media Controller 
,09-09 17:17:55.200  1015  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:55.200  1015  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:55.200  1015  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:55.200  1015  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:55.210  7918  7918 E Zygote  : MountEmulatedStorage(),
09-09 17:17:55.210  7918  7918 E Zygote  : v2
09-09 17:17:55.210  7918  7918 I libpersona: KNOX_SDCARD checking this for 10055
09-09 17:17:55.210  7918  7918 I libpersona: KNOX_SDCARD not a persona
,09-09 17:17:55.210  7918  7918 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 17:17:55.210  1015  1504 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7918 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,09-09 17:17:55.220  7918  7918 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-09 17:17:55.220  7918  7918 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
09-09 17:17:55.220  3225  3225 I Avrcp   :  Updating now playing list upon AVRCP Start
09-09 17:17:55.220  3225  7917 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
09-09 17:17:55.220  3225  3225 D A2dpStateMachine: make
09-09 17:17:55.220  3225  3225 I bluedroid: get_profile_interface a2dp
09-09 17:17:55.220  3225  7926 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-09 17:17:55.220  3225  3225 E bt-btif : warning : media task started media_task_refcnt 1 
,09-09 17:17:55.230  3225  3225 D A2dpService: mStartError = false
09-09 17:17:55.230  3225  3225 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29627d18
,09-09 17:17:55.230  3225  3225 D HidService: Received start request. Starting profile...
09-09 17:17:55.230  3225  3225 D HidService: start()
09-09 17:17:55.230  3225  3225 I bluedroid: get_profile_interface hidhost
09-09 17:17:55.230  3225  3225 D HidService: setHidService(): set to: null
09-09 17:17:55.230  3225  3225 D HidService: mStartError = false
09-09 17:17:55.230  3225  3225 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29627d18
09-09 17:17:55.230  3225  7925 D A2dpStateMachine: Enter Disconnected: -2
09-09 17:17:55.230  3225  3225 D HeadsetStateMachine: Proxy object connected
,09-09 17:17:55.230  3225  3225 D HealthService: Received start request. Starting profile...
09-09 17:17:55.230  3225  3225 D HealthService: start()
,09-09 17:17:55.230  3225  3225 I bluedroid: get_profile_interface health
09-09 17:17:55.230  3225  3225 D HealthService: mStartError = false
09-09 17:17:55.230  3225  3225 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29627d18
,09-09 17:17:55.230  3225  3225 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
09-09 17:17:55.230  3225  7916 D HeadsetStateMachine: Disconnected process message: 11
,09-09 17:17:55.230  3225  3225 D PanService: Received start request. Starting profile...
09-09 17:17:55.230  3225  3225 D PanService: start()
09-09 17:17:55.230  3225  3225 D BluetoothPanServiceJni: initializeNative(L110): pan
09-09 17:17:55.230  3225  3225 I bluedroid: get_profile_interface pan
09-09 17:17:55.230  3225  3225 D PanService: mStartError = false
09-09 17:17:55.230  3225  3225 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29627d18
,09-09 17:17:55.230  3225  3225 D BluetoothMapService: Received start request. Starting profile...
09-09 17:17:55.230  3225  3225 D BluetoothMapService: start()
,09-09 17:17:55.240  3225  3225 D BluetoothMapService: mStartError = false
09-09 17:17:55.240  3225  3225 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29627d18
09-09 17:17:55.240  3225  3225 D HeadsetPhoneState: sendDeviceDataStateChanged
,09-09 17:17:55.240  3225  3225 D HeadsetPhoneState: Signal level : previous=0 curr=4
09-09 17:17:55.240  3225  7916 D HeadsetStateMachine: Disconnected process message: 18
,09-09 17:17:55.240  3225  3225 D SapService: Received start request. Starting profile...
09-09 17:17:55.240  3225  3225 D SapService: start()
09-09 17:17:55.240  3225  3225 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-09 17:17:55.240  3225  3225 I bluedroid: get_profile_interface sap
09-09 17:17:55.240  3225  3225 D SapService: mStartError = false
09-09 17:17:55.240  3225  3225 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29627d18
09-09 17:17:55.240  3225  7917 D BluetoothMediaBrowser: no now playing list
09-09 17:17:55.240  3225  7917 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
09-09 17:17:55.240  3225  3225 E BluetoothAdapterService(694320408): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-09 17:17:55.240  3225  3225 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-09 17:17:55.240  3225  3225 E BluetoothAdapterService(694320408): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-09 17:17:55.240  3225  3225 E BluetoothAdapterService(694320408): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-09 17:17:55.240  3225  3225 E BluetoothAdapterService(694320408): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-09 17:17:55.240  3225  3225 E BluetoothAdapterService(694320408): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-09 17:17:55.240  3225  7916 D HeadsetStateMachine: Disconnected process message: 10
09-09 17:17:55.240  3225  7916 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-09 17:17:55.240  3225  7916 D HeadsetStateMachine: Disconnected process message: 11
,09-09 17:17:55.250  3225  3225 E BluetoothAdapterService(694320408): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-09 17:17:55.250  3225  3225 E BluetoothAdapterService(694320408): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-09 17:17:55.260  7918  7918 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:17:55.260  3225  3301 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
09-09 17:17:55.260  3225  3301 I bluedroid: enable
,09-09 17:17:55.260  7918  7918 D ActivityThread: Added TimaKeyStore provider
,09-09 17:17:55.260  3225  3304 E bt-btif : Calling BTA_HhEnable
,09-09 17:17:55.260  3225  3304 E bt-btif :                : sec: 0x80orig 1, psname [19, proto_id 7, chan_id 2
09-09 17:17:55.260  3225  3304 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
09-09 17:17:55.260  3225  3304 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-09 17:17:55.260  3225  3304 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
09-09 17:17:55.260  3225  3304 E BluetoothServiceJni: populateRssiValuesNative
09-09 17:17:55.260  3225  3304 I bluedroid: getModelRssiValues
09-09 17:17:55.260  3225  3304 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-09 17:17:55.260  3225  3304 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-09 17:17:55.260  1015  1015 D SettingsProvider: name = bluetooth_name
,09-09 17:17:55.270  3225  3304 D BluetoothAdapterProperties: Name is: Galaxy A3
,09-09 17:17:55.280  3225  3304 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-09 17:17:55.280  3225  3304 D BluetoothAdapterProperties: Scan Mode:20
09-09 17:17:55.280  3225  3304 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 17:17:55.280  3225  3304 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
09-09 17:17:55.280  3225  3304 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
09-09 17:17:55.280  3225  3304 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,09-09 17:17:55.280  3225  3304 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-09 17:17:55.280  3225  3304 E bt-btif : JVenable fails
,09-09 17:17:55.280  3225  3304 D bte_conf: Device ID record 1 : primary
09-09 17:17:55.280  3225  3304 D bte_conf:   vendorId            = 0075
09-09 17:17:55.280  3225  3304 D bte_conf:   vendorIdSource      = 0001
09-09 17:17:55.280  3225  3304 D bte_conf:   product             = 0100
09-09 17:17:55.280  3225  3304 D bte_conf:   version             = 0200
09-09 17:17:55.280  3225  3304 D bte_conf:   clientExecutableURL = 
09-09 17:17:55.280  3225  3304 D bte_conf:   serviceDescription  = 
09-09 17:17:55.280  3225  3304 D bte_conf:   documentationURL    = 
,09-09 17:17:55.280  3225  3304 D bte_conf: bte_load_did_conf no section named DID2.
,09-09 17:17:55.280  3225  3304 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,09-09 17:17:55.280  3225  3301 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-09 17:17:55.280  3225  3301 D BluetoothAdapterProperties: ScanMode =  20
09-09 17:17:55.280  3225  3301 D BluetoothAdapterProperties: State =  11
,09-09 17:17:55.280  1015  3283 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-09 17:17:55.280  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:55.280  3225  3301 D BluetoothAdapterProperties: Setting state to 12
09-09 17:17:55.280  3225  3301 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-09 17:17:55.280  3225  3304 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-09 17:17:55.280  1015  1028 D SettingsProvider: name = bluetooth_a2dp_sink_mode
09-09 17:17:55.280  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 17:17:55.280  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 17:17:55.280  1015  1028 D SettingsProvider: selectionArgs: false
09-09 17:17:55.280  1015  1028 D SettingsProvider: selectionArgs: 1002
09-09 17:17:55.280  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 17:17:55.280  1015  1028 D SettingsProvider: ret = -1
,09-09 17:17:55.280  3225  3301 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-09 17:17:55.280  3225  3301 D BluetoothAdapterService: updateAdapterState state is 12
,09-09 17:17:55.280  1015  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:17:55.280  1015  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
09-09 17:17:55.290  1015  1491 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:55.290  1015  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:55.290  1015  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 17:17:55.290  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:17:55.290  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:55.290  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:17:55.290  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:17:55.290  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:17:55.290  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:17:55.290  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:17:55.290  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:17:55.290  7319  7319 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 17:17:55.290  3225  3301 D BluetoothAdapterService: Autoconnection is available 
09-09 17:17:55.290  3225  3301 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-09 17:17:55.290  3225  3301 D BluetoothAdapterService: starting service from this receiver
,09-09 17:17:55.300  1015  1504 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:17:55.300  1015  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-09 17:17:55.300  1452  3379 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-09 17:17:55.300  1015  1504 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:55.300  1015  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:55.300  1015  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:55.300  3225  3301 I BluetoothAdapterState: Entering On State from state = 11
,09-09 17:17:55.300  3225  3304 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-09 17:17:55.300  3225  3304 D BluetoothAdapterProperties: Scan Mode:21
09-09 17:17:55.300  3225  3304 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-09 17:17:55.300  1015  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 17:17:55.300  1015  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 17:17:55.300  1015  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:55.300  1015  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 17:17:55.300  3225  3225 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
09-09 17:17:55.300  1015  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:55.300  1452  3379 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 17:17:55.310  1681  1693 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 17:17:55.310  1681  1693 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 17:17:55.310  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:17:55.310  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:55.310  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:17:55.310  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:17:55.310  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:17:55.310  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:17:55.310  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:17:55.310  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:17:55.310  4743  4755 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-09 17:17:55.310  7319  7319 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 17:17:55.310  7918  7918 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-09 17:17:55.310  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:55.320  3225  3225 I BluetoothPbapService: Handler(): got msg=1
,09-09 17:17:55.320  1015  3280 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy,
,09-09 17:17:55.320  1015  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,09-09 17:17:55.320  1015  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-09 17:17:55.320  1015  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:55.320  1015  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:55.320  1015  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:55.320  4743  4743 D BluetoothInputDevice: Proxy object connected
09-09 17:17:55.320  1015  1046 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 17:17:55.320  1015  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 17:17:55.320  1015  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-09 17:17:55.320  1015  1046 E BluetoothHeadset: BluetoothHeadset service is binded
09-09 17:17:55.320  4743  4743 D HidProfile: Bluetooth service connected
09-09 17:17:55.330  4743  4761 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 17:17:55.330  4743  4761 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-09 17:17:55.330  1015  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-09 17:17:55.330  1015  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-09 17:17:55.330  3225  7939 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-09 17:17:55.330  1015  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:55.330  1015  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:55.330  1015  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:55.330  1452  1477 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-09 17:17:55.330  1452  1477 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 17:17:55.330  4743  7429 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 17:17:55.330  1015  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 17:17:55.330  1015  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 17:17:55.330  1015  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:55.330  1015  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:55.330  1015  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:55.330  4743  7429 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 17:17:55.330  3225  7939 D BluetoothSocket: bindListen(): myUserId = 0
09-09 17:17:55.330  3225  7939 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 17:17:55.330  4743  4743 D BluetoothA2dp: Proxy object connected
09-09 17:17:55.330  4743  4743 D A2dpProfile: Bluetooth service connected
,09-09 17:17:55.340  1452  3379 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-09 17:17:55.340  3225  7939 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
09-09 17:17:55.340  3225  7939 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 17:17:55.340  3225  7939 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,09-09 17:17:55.340  3225  7939 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1a0b16bd
09-09 17:17:55.340  3225  7939 D BluetoothSocket: channel: 19
09-09 17:17:55.340  3225  7939 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-09 17:17:55.340  1015  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 17:17:55.340  1015  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 17:17:55.340  1015  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:55.340  1015  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:55.340  1015  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:55.340  1452  3379 E BluetoothHeadset: BluetoothHeadset service is binded
09-09 17:17:55.340  1015  1046 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 17:17:55.340  1015  1046 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 17:17:55.340  1478  3344 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 17:17:55.340  4743  4743 D HeadsetProfile: Bluetooth service connected
09-09 17:17:55.340  1015  1046 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 17:17:55.340  1015  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 17:17:55.340  1015  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:55.340  1015  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:55.340  1015  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
09-09 17:17:55.340  1478  3344 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 17:17:55.340  7413  7422 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 17:17:55.340  7413  7422 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 17:17:55.340  4743  4761 D BluetoothPan: Binding service...
,09-09 17:17:55.340  1015  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,09-09 17:17:55.350  1015  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-09 17:17:55.350  1015  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:55.350  1015  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:55.350  1015  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:55.350  4743  4743 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 17:17:55.350  4743  4743 D PanProfile: Bluetooth service connected
,09-09 17:17:55.350  1452  1477 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 17:17:55.350  1015  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-09 17:17:55.350  1015  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 17:17:55.350  1015  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:55.350  1015  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 17:17:55.350  1015  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:55.350  7918  7918 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
09-09 17:17:55.350  1452  1477 E BluetoothHeadset: BluetoothHeadset service is binded
09-09 17:17:55.350  1015  1046 D BluetoothPan: Binding service...
,09-09 17:17:55.350  7918  7918 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-09 17:17:55.350  1015  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-09 17:17:55.350  7918  7918 D UserAnalysis: Create SecureDbHelper
,09-09 17:17:55.350  1015  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-09 17:17:55.360  1015  1015 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 17:17:55.360  3225  3237 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 17:17:55.360  3225  3237 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 17:17:55.360  1478  1843 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-09 17:17:55.360  1478  1843 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-09 17:17:55.360  4743  7429 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 17:17:55.360  4743  7429 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-09 17:17:55.360  1698  5685 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 17:17:55.360  1698  5685 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-09 17:17:55.360  1015  1095 V AlarmManager: waitForAlarm result :4
09-09 17:17:55.360  1015  1046 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 17:17:55.360  1015  1046 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-09 17:17:55.360  1015  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-09 17:17:55.360  1015  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 17:17:55.360  1015  1015 D BluetoothA2dp: Proxy object connected
,09-09 17:17:55.360  7319  7328 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 17:17:55.360  7319  7328 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-09 17:17:55.360  1178  1193 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 17:17:55.360  1178  1193 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-09 17:17:55.360  4743  4761 D BluetoothPbap: onBluetoothStateChange: up=true
,09-09 17:17:55.360  1015  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-09 17:17:55.360  1015  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-09 17:17:55.360  1015  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:55.360  1015  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:55.360  1015  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:55.360  7918  7918 D IntelligenceServiceApplication: onCreate()
,09-09 17:17:55.370  4743  4743 D BluetoothPbap: Proxy object connected
09-09 17:17:55.370  4743  4743 D PbapServerProfile: Bluetooth service connected
,09-09 17:17:55.370  1461  1486 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 17:17:55.370  1461  1486 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-09 17:17:55.370  4743  7429 D BluetoothMap: onBluetoothStateChange: up=true
,09-09 17:17:55.370  1015  1028 I ActivityManager: Killing 7413:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,09-09 17:17:55.370  7918  7918 D IntelligenceServiceApplication: no applications having user consent for prediction
,09-09 17:17:55.380  1015  1491 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-09 17:17:55.380  1015  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
09-09 17:17:55.380  1015  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
09-09 17:17:55.380  1015  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:55.380  1015  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:55.380  1015  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-09 17:17:55.380  7918  7918 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,09-09 17:17:55.380  4743  4761 D Bluetoothsap: onBluetoothStateChange: up=true
09-09 17:17:55.380  4743  4761 D Bluetoothsap: Binding service...
,09-09 17:17:55.380  4743  4743 D BluetoothMap: Proxy object connected
09-09 17:17:55.380  4743  4743 D MapProfile: Bluetooth service connected
09-09 17:17:55.380  4743  4743 D BluetoothMap: getConnectedDevices()
,09-09 17:17:55.380  4743  4761 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-09 17:17:55.380  1015  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-09 17:17:55.380  1015  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-09 17:17:55.380  1015  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:55.380  1015  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:55.380  1015  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:55.390  4743  4761 D Bluetoothsap: bindService called to Bluetooth SAP Service
09-09 17:17:55.390  3225  3240 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 17:17:55.390  3225  3240 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-09 17:17:55.390  4743  4743 D Bluetoothsap: BluetoothSAP Proxy object connected
09-09 17:17:55.390  1015  1046 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-09 17:17:55.390  1015  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 17:17:55.390  4743  4743 D SapProfile: Bluetooth service connected
09-09 17:17:55.390  7918  7918 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
09-09 17:17:55.390  1015  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:55.390  1015  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:55.390  1015  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 17:17:55.390  3225  3225 D BluetoothA2dp: Proxy object connected
,09-09 17:17:55.390  3225  3225 D BluetoothAdapterService: Bluetooth A2dp source service connected
09-09 17:17:55.390  1015  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-09 17:17:55.390  4743  4743 D Bluetoothsap: getConnectedDevices()
09-09 17:17:55.390  1015  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-09 17:17:55.390  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:17:55.390  1015  1015 I InputMethodManagerService: [BT Setting State] State =12
,09-09 17:17:55.390  1015  1015 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-09 17:17:55.400  1178  1178 D BluetoothTile:  onBluetoothStateChange:
,09-09 17:17:55.400  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-09 17:17:55.400  1178  1704 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 17:17:55.400  1452  1452 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@d829eaf, true
,09-09 17:17:55.400  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:55.400  1178  1178 D BluetoothTile:  getBluetoothState : 12
,09-09 17:17:55.410  1178  1704 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 17:17:55.410  1452  1452 D BluetoothHeadset: registerMessageListener
,09-09 17:17:55.410  2019  2019 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-09 17:17:55.410  4743  4743 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:17:55.410  1178  1704 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 17:17:55.410  3225  3380 D HeadsetService: registerMessageListener
,09-09 17:17:55.410  3225  3380 D HeadsetService: registerMessageListener
09-09 17:17:55.410  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:55.410  3225  7916 D HeadsetStateMachine: Disconnected process message: 70
09-09 17:17:55.410  3225  7916 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@ad474b2
,09-09 17:17:55.420  1452  1452 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-09 17:17:55.420  1452  1452 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-09 17:17:55.420  4743  4743 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-09 17:17:55.420  4743  4743 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-09 17:17:55.420  4743  4743 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-09 17:17:55.420  4743  4743 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
09-09 17:17:55.420  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:55.420  1015  1135 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 17:17:55.420  1015  1504 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-09 17:17:55.420  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 17:17:55.420  3225  7942 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-09 17:17:55.420  1452  1452 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-09 17:17:55.420  1452  1452 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,09-09 17:17:55.420  1452  1452 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-09 17:17:55.430  3225  7916 D HeadsetStateMachine: Disconnected process message: 9
09-09 17:17:55.430  3225  7916 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-09 17:17:55.430  3225  7942 D BluetoothSocket: bindListen(): myUserId = 0
09-09 17:17:55.430  3225  7942 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 17:17:55.430   282  1013 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
09-09 17:17:55.430   282  1013 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-09 17:17:55.430   282  1013 V voice   : voice_set_parameters: exit with code(-2)
09-09 17:17:55.430   282  1013 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-09 17:17:55.430   282  1013 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-09 17:17:55.430   282  1013 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-09 17:17:55.430   282  1013 V audio_hw_primary: adev_set_parameters: exit
09-09 17:17:55.430  3225  7916 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-09 17:17:55.430  3225  7942 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
09-09 17:17:55.430  3225  7942 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 17:17:55.430  3225  7942 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 17:17:55.430  3225  7942 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@bb01c03
,09-09 17:17:55.430  3225  7942 D BluetoothSocket: channel: 5
,09-09 17:17:55.480   277   962 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-09 17:17:55.480   277   962 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,09-09 17:17:55.480  4743  4743 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 17:17:55.480  1015  1244 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-09 17:17:55.480  1015  1244 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-09 17:17:55.490  1015  1244 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:55.490  1015  1244 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 17:17:55.490  1015  1244 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-09 17:17:55.500  1698  1698 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 17:17:55.500  4743  4743 D DockEventReceiver: finishStartingService: stopping service
,09-09 17:17:55.500  4743  4743 D BluetoothNotiBroadcastReceiver: onReceive
,09-09 17:17:55.510  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED,
09-09 17:17:55.510  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-09 17:17:55.510  3225  3225 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29627d18
,09-09 17:17:55.510  3225  3225 D BtConfig.SecureMode: isSecureModeOn:false
,09-09 17:17:55.510  1015  1505 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:17:55.520  1015  1505 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-09 17:17:55.520  1015  1505 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:55.520  1015  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:55.520  1015  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:55.520  1015  1135 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-09 17:17:55.520  1015  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:55.520  1015  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:55.520  1015  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:55.520  1015  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:55.530  7947  7947 E Zygote  : MountEmulatedStorage()
,09-09 17:17:55.530  7947  7947 E Zygote  : v2
,09-09 17:17:55.530  7947  7947 I libpersona: KNOX_SDCARD checking this for 10105
09-09 17:17:55.530  7947  7947 I libpersona: KNOX_SDCARD not a persona
,09-09 17:17:55.530  7947  7947 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-09 17:17:55.530  1015  1135 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7947 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,09-09 17:17:55.540  1015  1504 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-09 17:17:55.540  7947  7947 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-09 17:17:55.540  7947  7947 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-09 17:17:55.550  3225  7956 D BluetoothSocket: bindListen(): myUserId = 0
09-09 17:17:55.550  3225  7956 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 17:17:55.550  3225  7956 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[85]}
09-09 17:17:55.550  3225  7956 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 17:17:55.550  3225  7956 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 17:17:55.550  3225  7956 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2d0e755f
,09-09 17:17:55.550  3225  7956 D BluetoothSocket: channel: 12
09-09 17:17:55.550  3225  7956 I BtOppRfcommListener: Accept thread started.
,09-09 17:17:55.560   303   303 I art     : Explicit concurrent mark sweep GC freed 8680(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 610us total 21.889ms
,09-09 17:17:55.560  7947  7947 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:17:55.560  7947  7947 D ActivityThread: Added TimaKeyStore provider
,09-09 17:17:55.570   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 563us total 16.397ms
,09-09 17:17:55.590   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 574us total 16.566ms
,09-09 17:17:55.670   256   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-09 17:17:55.670   256   530 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 17:17:55.670  7947  7968 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-09 17:17:55.680   256   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-09 17:17:55.680   256   530 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 17:17:55.680  7947  7968 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-09 17:17:55.740   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 17:17:55.840  7947  7947 D StrictMode: StrictMode policy violation; ~duration=154 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at java.io.File.exists(File.java:363)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-09 17:17:55.840  7947  7947 D StrictMode: StrictMode policy violation; ~duration=153 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 17:17:55.840  7947  7947 D StrictMode: StrictMode policy violation; ~duration=151 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gm,m.map.m.e.a(PG:1515)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 17:17:55.840  7947  7947 D StrictMode: StrictMode policy violation; ~duration=149 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.q.e.b(PG:170)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09,-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 17:17:55.840  7947  7947 D StrictMode: StrictMode policy violation; ~duration=146 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.q.k.c(PG:18147)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.q.k.d(PG:583)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.q.e.b(PG:170)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 17:17:55.840  7947  7947 D StrictMode: StrictMode policy violation; ~duration=119 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at java.io.File.exists(File.java:363)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 17:17:55.840  7947  7947 D StrictMode: StrictMode policy violation; ~duration=119 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at java.io.File.exists(File.java:363)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 17:17:55.840  7947  7947 D StrictMode: StrictMode policy violation; ~duration=118 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at java.io.File.lastModified(File.java:571)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 17:17:55.840  7947  7947 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 17:17:55.850  1015  1505 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:55.850  1015  1505 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:55.850  1015  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
09-09 17:17:55.850  1015  1505 I ActivityManager: Killing 7518:com.sec.pcw.device/1000 (adj 15): empty #21
,09-09 17:17:55.900  7947  7975 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
09-09 17:17:55.910  1015  1501 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-09 17:17:55.910  1015  1501 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:55.910  1015  1501 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:55.910  1015  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-09 17:17:56.080  1015  3377 D SSRM:n  : SIOP:: AP = 370
,09-09 17:17:56.370  1015  2071 V SAMP_SPCM_test: CSC File load.. 
,09-09 17:17:56.380  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,09-09 17:17:56.380  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
,09-09 17:17:56.380  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
,09-09 17:17:56.380  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
09-09 17:17:56.380  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
,09-09 17:17:56.380  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
,09-09 17:17:56.380  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
09-09 17:17:56.380  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
,09-09 17:17:56.380  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
,09-09 17:17:56.380  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
,09-09 17:17:56.390  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
09-09 17:17:56.390  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
09-09 17:17:56.390  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
09-09 17:17:56.390  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
09-09 17:17:56.390  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
09-09 17:17:56.390  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
09-09 17:17:56.390  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
09-09 17:17:56.390  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
09-09 17:17:56.390  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
09-09 17:17:56.390  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
09-09 17:17:56.390  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,09-09 17:17:56.430  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,09-09 17:17:56.430  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
,09-09 17:17:56.430  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
,09-09 17:17:56.430  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
09-09 17:17:56.430  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
,09-09 17:17:56.430  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
09-09 17:17:56.430  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
09-09 17:17:56.430  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
,09-09 17:17:56.430  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
09-09 17:17:56.430  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control,
09-09 17:17:56.430  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
09-09 17:17:56.430  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
,09-09 17:17:56.430  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
09-09 17:17:56.430  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email,
09-09 17:17:56.430  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
09-09 17:17:56.430  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
09-09 17:17:56.430  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
09-09 17:17:56.430  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
09-09 17:17:56.430  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
09-09 17:17:56.430  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
09-09 17:17:56.430  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,09-09 17:17:56.440  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
,09-09 17:17:56.450  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
,09-09 17:17:56.450  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
,09-09 17:17:56.450  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
09-09 17:17:56.450  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
,09-09 17:17:56.450  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
09-09 17:17:56.450  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
09-09 17:17:56.450  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
,09-09 17:17:56.450  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
09-09 17:17:56.450  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
09-09 17:17:56.450  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize,
09-09 17:17:56.450  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
,09-09 17:17:56.450  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
,09-09 17:17:56.450  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
09-09 17:17:56.450  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
,09-09 17:17:56.450  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
09-09 17:17:56.450  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
09-09 17:17:56.450  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
,09-09 17:17:56.450  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
09-09 17:17:56.450  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
09-09 17:17:56.450  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
,09-09 17:17:56.450  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
09-09 17:17:56.450  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
,09-09 17:17:56.450  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
09-09 17:17:56.450  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
09-09 17:17:56.450  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
,09-09 17:17:56.450  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
09-09 17:17:56.450  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
09-09 17:17:56.450  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering,
09-09 17:17:56.450  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
09-09 17:17:56.450  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
,09-09 17:17:56.450  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
09-09 17:17:56.450  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
,09-09 17:17:56.450  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
09-09 17:17:56.450  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
09-09 17:17:56.450  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
,09-09 17:17:56.450  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
09-09 17:17:56.450  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
,09-09 17:17:56.450  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,09-09 17:17:56.460  1015  2071 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
,09-09 17:17:56.460  1015  2071 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-09 17:17:56.460  1015  2071 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:56.460  1015  2071 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:56.460  1015  2071 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:56.480  7981  7981 E Zygote  : MountEmulatedStorage()
,09-09 17:17:56.480  1015  2071 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=7981 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-09 17:17:56.480  7981  7981 E Zygote  : v2
09-09 17:17:56.480  7981  7981 I libpersona: KNOX_SDCARD checking this for 1000
09-09 17:17:56.480  7981  7981 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 17:17:56.480  7981  7981 I libpersona: KNOX_SDCARD not a persona
,09-09 17:17:56.480  7981  7981 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 17:17:56.490  7981  7981 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 17:17:56.510  7981  7981 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:17:56.510  7981  7981 D ActivityThread: Added TimaKeyStore provider
,09-09 17:17:56.520  1015  3395 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-09 17:17:56.520  7981  7981 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-09 17:17:56.570  1015  2071 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,09-09 17:17:56.580  1015  1015 I ActivityManager: Killing 7535:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,09-09 17:17:56.620  1015  1501 I ActivityManager: Killing 7552:com.sec.android.diagmonagent/1000 (adj 15): empty #21
,09-09 17:17:56.650  1015  3280 I ActivityManager: Killing 7567:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,09-09 17:17:56.730   287   287 E SMD     : DCD OFF
,09-09 17:17:56.740   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 17:17:57.740   314   314 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-09 17:17:58.080  7319  7373 D BluetoothAdapter: disable()
,09-09 17:17:58.080  1015  3282 D SettingsProvider: name = bluetooth_on
,09-09 17:17:58.090  3225  3301 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,09-09 17:17:58.090  3225  3301 D BluetoothAdapterProperties: Setting state to 13
,09-09 17:17:58.090  3225  3301 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-09 17:17:58.090  3225  3301 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-09 17:17:58.090  3225  3301 D BluetoothAdapterService: updateAdapterState state is 13
,09-09 17:17:58.090  1015  1505 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 17:17:58.090  1015  1505 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-09 17:17:58.100  1015  1505 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:58.100  1015  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 17:17:58.100  1015  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:58.100  3225  3225 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-09 17:17:58.100  3225  3225 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3d651bac, channel: 19, state: LISTENING
,09-09 17:17:58.100  3225  3225 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3d651bac, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1a0b16bd, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@5836075mSocket: android.net.LocalSocket@2fd1e80a impl:android.net.LocalSocketImpl@12cf087b fd:FileDescriptor[80]
09-09 17:17:58.100  3225  3225 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2fd1e80a impl:android.net.LocalSocketImpl@12cf087b fd:FileDescriptor[80]
,09-09 17:17:58.100  3225  3301 D BluetoothAdapterService: Autoconnection is available 
,09-09 17:17:58.100  3225  3301 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-09 17:17:58.100  3225  3301 D BluetoothAdapterService: terminating service from this receiver
,09-09 17:17:58.100  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:17:58.100  1015  1015 I InputMethodManagerService: [BT Setting State] State =13
,09-09 17:17:58.110  1178  1178 D BluetoothTile:  onBluetoothStateChange:
,09-09 17:17:58.110  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-09 17:17:58.110  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:58.110  1178  1178 D BluetoothTile:  getBluetoothState : 13
,09-09 17:17:58.110  2019  2019 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-09 17:17:58.110  1178  1704 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 17:17:58.110  4743  4743 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:17:58.120  1178  1704 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 17:17:58.120  7319  7319 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:58.120  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:17:58.120  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:58.120  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:17:58.120  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:17:58.120  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:17:58.120  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:17:58.120  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:17:58.120  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:17:58.120  1015  1504 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 17:17:58.120  7319  7319 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 17:17:58.120  7319  7319 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:17:58.120  1015  1491 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-09 17:17:58.130  1178  1704 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-09 17:17:58.130  1015  1346 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-09 17:17:58.130  3225  3225 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@20de4698, channel: 5, state: LISTENING
,09-09 17:17:58.130  3225  3225 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@20de4698, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@bb01c03, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@29b68ef1mSocket: android.net.LocalSocket@21ae7ad6 impl:android.net.LocalSocketImpl@183bb157 fd:FileDescriptor[82]
,09-09 17:17:58.130  3225  3225 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@21ae7ad6 impl:android.net.LocalSocketImpl@183bb157 fd:FileDescriptor[82]
,09-09 17:17:58.130  3225  3225 I BtOppRfcommListener: stopping Accept Thread
09-09 17:17:58.130  3225  3225 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1bd3444, channel: 12, state: LISTENING
09-09 17:17:58.130  3225  3225 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1bd3444, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2d0e755f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1414292dmSocket: android.net.LocalSocket@36ef6e62 impl:android.net.LocalSocketImpl@19600bf3 fd:FileDescriptor[85]
09-09 17:17:58.130  3225  3225 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@36ef6e62 impl:android.net.LocalSocketImpl@19600bf3 fd:FileDescriptor[85]
,09-09 17:17:58.130  3225  7956 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 17:17:58.130  3225  7956 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-09 17:17:58.140  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-09 17:17:58.140  1015  1346 W ActivityManager: userId = 0, bbcId = -10000,
09-09 17:17:58.140  1015  1346 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 17:17:58.140  1015  1346 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:58.140  7319  7319 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:58.140  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:17:58.140  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:58.140  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:17:58.140  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:17:58.140  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:17:58.140  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:17:58.140  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:17:58.140  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:17:58.140  3225  3301 D BluetoothAdapterProperties: onBluetoothDisable()
09-09 17:17:58.140  3225  3301 D BluetoothAdapterProperties: mDiscovering is false
,09-09 17:17:58.140  1015  1135 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-09 17:17:58.150  7319  7319 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:58.150  3225  3301 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-09 17:17:58.150  7319  7319 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 17:17:58.150  3225  3304 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-09 17:17:58.150  4743  4743 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-09 17:17:58.150  3225  3304 D BluetoothAdapterProperties: Scan Mode:20
,09-09 17:17:58.160  1015  1135 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-09 17:17:58.160  1015  1135 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-09 17:17:58.160  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:58.160  3225  3301 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,09-09 17:17:58.160  3225  3301 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,09-09 17:17:58.160  3225  3301 E bt-btif : cmd socket is not created
,09-09 17:17:58.160  3225  3305 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,09-09 17:17:58.160  3225  3301 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-09 17:17:58.170  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:58.170  1015  1135 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:58.170  1015  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:58.170  1015  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-09 17:17:58.170  3225  3225 V BluetoothOppManager: cleanUp...
,09-09 17:17:58.170  4743  4743 D BluetoothPbap: Proxy object disconnected
,09-09 17:17:58.170  4743  4743 D PbapServerProfile: Bluetooth service disconnected
,09-09 17:17:58.170  1698  1698 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 17:17:58.180  3225  3305 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 17:17:58.180  3225  3305 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 17:17:58.180  3225  3305 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 17:17:58.180  3225  3305 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 17:17:58.180  3225  3305 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 17:17:58.180  3225  3305 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-09 17:17:58.180  4743  4743 D DockEventReceiver: finishStartingService: stopping service
,09-09 17:17:58.180  4743  4743 D BluetoothNotiBroadcastReceiver: onReceive
,09-09 17:17:58.190  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:17:58.190  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-09 17:17:58.370  3225  3301 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,09-09 17:17:58.370  3225  3301 D BtConfig.SecureMode: isSecureModeOn:false
09-09 17:17:58.370  3225  3301 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-09 17:17:58.370  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
09-09 17:17:58.370  3225  3301 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
09-09 17:17:58.370  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-09 17:17:58.370  1015  1466 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:17:58.370  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-09 17:17:58.370  1015  1466 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-09 17:17:58.370  3225  3301 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-09 17:17:58.370  1015  1466 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:58.370  1015  1466 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 17:17:58.370  1015  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:58.370  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
09-09 17:17:58.370  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-09 17:17:58.370  3225  3301 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-09 17:17:58.370  1015  3282 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:17:58.370  1015  3282 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 17:17:58.370  3225  3225 D HeadsetService: Received stop request...Stopping profile...
09-09 17:17:58.370  1015  3282 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:58.370  1015  3282 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:58.370  1015  3282 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:58.370  3225  3225 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29627d18
,09-09 17:17:58.380  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-09 17:17:58.380  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,09-09 17:17:58.380  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 17:17:58.380  3225  3301 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-09 17:17:58.380  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:17:58.380  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-09 17:17:58.380  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:58.380  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:58.380  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:58.380  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
09-09 17:17:58.380  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-09 17:17:58.380  3225  3301 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-09 17:17:58.390  3225  3225 D A2dpService: Received stop request...Stopping profile...
,09-09 17:17:58.390  3225  7925 D A2dpStateMachine: Exit Disconnected: -1
,09-09 17:17:58.390  4743  4743 D HeadsetProfile: Bluetooth service disconnected
09-09 17:17:58.390  1015  1501 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:17:58.390  1015  1501 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-09 17:17:58.390  1015  1501 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:58.390  1015  1501 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:58.390  1015  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:58.390  3225  3225 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29627d18
,09-09 17:17:58.390  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
09-09 17:17:58.390  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-09 17:17:58.390  3225  3301 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-09 17:17:58.390  1015  3283 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 17:17:58.390  1015  3283 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-09 17:17:58.390  1015  3283 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:58.390  1015  3283 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:58.390  1015  3283 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
,09-09 17:17:58.390  1015  1015 D BluetoothA2dp: Proxy object disconnected
09-09 17:17:58.400  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-09 17:17:58.400  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
09-09 17:17:58.400  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 17:17:58.400  3225  3301 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
09-09 17:17:58.400  1015  3282 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:17:58.400  1015  3282 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-09 17:17:58.400  1015  3282 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:58.400  1015  3282 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:58.400  1015  3282 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:58.400  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
09-09 17:17:58.400  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-09 17:17:58.400  3225  3301 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-09 17:17:58.400  1015  3282 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 17:17:58.400  1015  3282 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
09-09 17:17:58.400  1015  3282 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:58.400  1015  3282 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:58.400  1015  3282 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:58.400  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-09 17:17:58.400  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-09 17:17:58.400  3225  3301 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-09 17:17:58.400  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-09 17:17:58.400  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-09 17:17:58.400  3225  3301 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-09 17:17:58.400  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-09 17:17:58.400  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-09 17:17:58.400  3225  3301 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-09 17:17:58.400  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-09 17:17:58.400  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-09 17:17:58.400  3225  3301 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-09 17:17:58.400  3225  3301 D BluetoothAdapterState: Stopping profile services that were post enabled
09-09 17:17:58.400  3225  3225 E BluetoothAdapterService(694320408): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-09 17:17:58.400  3225  3225 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 17:17:58.400  3225  3225 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-09 17:17:58.400  4743  4743 D BluetoothA2dp: Proxy object disconnected
,09-09 17:17:58.400  4743  4743 D A2dpProfile: Bluetooth service disconnected
09-09 17:17:58.400  3225  3225 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-09 17:17:58.400  3225  3225 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-09 17:17:58.400  3225  3225 D HidService: Received stop request...Stopping profile...
09-09 17:17:58.400  3225  3225 D HidService: Stopping Bluetooth HidService
,09-09 17:17:58.400  3225  3225 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-09 17:17:58.410  3225  3225 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-09 17:17:58.410  3225  3225 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-09 17:17:58.410  3225  3225 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29627d18
,09-09 17:17:58.410  3225  3225 D HealthService: Received stop request...Stopping profile...
,09-09 17:17:58.410  3225  3225 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29627d18
,09-09 17:17:58.410  4743  4743 D BluetoothInputDevice: Proxy object disconnected
,09-09 17:17:58.410  4743  4743 D HidProfile: Bluetooth service disconnected
09-09 17:17:58.410  3225  3225 E BluetoothAdapterService(694320408): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-09 17:17:58.410  3225  3225 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 17:17:58.410  3225  3225 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-09 17:17:58.410  3225  3225 D BluetoothA2dp: Proxy object disconnected
09-09 17:17:58.410  3225  3225 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,09-09 17:17:58.410  3225  3225 D PanService: Received stop request...Stopping profile...
,09-09 17:17:58.410  3225  3225 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29627d18
,09-09 17:17:58.410  1015  1015 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-09 17:17:58.410  3225  7926 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,09-09 17:17:58.420  3225  3225 I GKI_LINUX: GKI_exit_task 2 done
09-09 17:17:58.420  3225  3225 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,09-09 17:17:58.420  3225  3225 D BluetoothMapService: Received stop request...Stopping profile...
09-09 17:17:58.420  4743  4743 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 17:17:58.420  4743  4743 D PanProfile: Bluetooth service disconnected
,09-09 17:17:58.420  3225  3225 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29627d18
,09-09 17:17:58.420  3225  3225 D SapService: Received stop request...Stopping profile...
,09-09 17:17:58.420  3225  3225 D SapService: Stopping Bluetooth SapService
09-09 17:17:58.420  3225  3225 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29627d18
,09-09 17:17:58.420  4743  4743 D BluetoothMap: Proxy object disconnected
09-09 17:17:58.420  4743  4743 D MapProfile: Bluetooth service disconnected
,09-09 17:17:58.420  3225  3225 E BluetoothAdapterService(694320408): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
,09-09 17:17:58.420  3225  3225 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-09 17:17:58.420  3225  3225 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 17:17:58.420  3225  3225 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,09-09 17:17:58.420  4743  4743 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-09 17:17:58.420  4743  4743 D SapProfile: Bluetooth service disconnected
09-09 17:17:58.420  3225  3225 E BluetoothAdapterService(694320408): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-09 17:17:58.420  3225  3225 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,09-09 17:17:58.420  3225  3225 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-09 17:17:58.420  3225  3225 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-09 17:17:58.430  3225  3225 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-09 17:17:58.430  3225  3225 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-09 17:17:58.430  3225  3225 E BluetoothAdapterService(694320408): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
,09-09 17:17:58.430  3225  3225 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,09-09 17:17:58.430  3225  3225 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-09 17:17:58.430  3225  3225 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,09-09 17:17:58.430  3225  3225 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 17:17:58.430  3225  3225 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-09 17:17:58.430  3225  3225 E BluetoothAdapterService(694320408): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-09 17:17:58.430  3225  3225 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-09 17:17:58.430  3225  3225 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-09 17:17:58.430  3225  3225 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,09-09 17:17:58.430  3225  3225 E BluetoothAdapterService(694320408): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-09 17:17:58.430  3225  3225 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,09-09 17:17:58.430  3225  3225 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-09 17:17:58.430  3225  3225 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-09 17:17:58.430  3225  3301 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
09-09 17:17:58.430  3225  3301 D BluetoothAdapterProperties: Setting state to 10
09-09 17:17:58.430  3225  3301 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-09 17:17:58.430  3225  3301 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-09 17:17:58.430  3225  3301 D BluetoothAdapterService: updateAdapterState state is 10
,09-09 17:17:58.430  3225  3301 D BluetoothAdapterService: Autoconnection is available 
,09-09 17:17:58.430  3225  3301 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-09 17:17:58.430  3225  3301 I BluetoothAdapterState: Entering OffState
,09-09 17:17:58.430  1681  2483 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 17:17:58.430  1681  2483 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 17:17:58.440  4743  4755 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-09 17:17:58.440  4743  7429 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-09 17:17:58.440  1452  3379 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 17:17:58.440  1452  3379 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 17:17:58.440  1015  1046 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 17:17:58.440  1015  1046 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 17:17:58.440  3225  3237 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 17:17:58.440  3225  3237 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 17:17:58.440  1478  3343 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 17:17:58.440  1478  3343 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 17:17:58.450  7947  7958 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 17:17:58.450  7947  7958 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 17:17:58.450  4743  7429 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 17:17:58.450  4743  7429 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 17:17:58.450  1698  4217 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 17:17:58.450  1698  4217 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 17:17:58.450  1015  1046 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-09 17:17:58.450  7319  7366 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 17:17:58.450  7319  7366 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 17:17:58.450  7319  7366 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,09-09 17:17:58.450  7319  7366 D BluetoothLeAdvertiser: Exit stop advertising
09-09 17:17:58.450  7319  7366 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
,09-09 17:17:58.450  7319  7366 D BluetoothLeScanner: Exiting stopAllScan
,09-09 17:17:58.450  1178  3300 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 17:17:58.450  1178  3300 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 17:17:58.450  4743  4761 D BluetoothPbap: onBluetoothStateChange: up=false
,09-09 17:17:58.450  1461  1476 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 17:17:58.450  1461  1476 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 17:17:58.450  4743  4755 D BluetoothMap: onBluetoothStateChange: up=false
,09-09 17:17:58.450  4743  7429 D Bluetoothsap: onBluetoothStateChange: up=false
09-09 17:17:58.450  4743  7429 D Bluetoothsap: Unbinding service...
,09-09 17:17:58.460  3225  3366 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-09 17:17:58.460  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:17:58.460  1015  1015 I InputMethodManagerService: [BT Setting State] State =10
,09-09 17:17:58.460  1015  1015 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-09 17:17:58.470  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:17:58.470  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-09 17:17:58.470  1178  1178 D BluetoothTile:  getBluetoothState : 10
,09-09 17:17:58.470  2019  2019 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-09 17:17:58.470  4743  4743 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:17:58.470  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:58.480  1015  3282 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 17:17:58.480  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:58.480  4743  4743 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-09 17:17:58.480  1015  1504 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-09 17:17:58.480  1015  1135 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-09 17:17:58.480  1015  1135 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-09 17:17:58.480  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-09 17:17:58.480  1015  1135 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:58.480  1015  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 17:17:58.480  1015  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-09 17:17:58.490  1698  1698 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 17:17:58.490  4743  4743 D DockEventReceiver: finishStartingService: stopping service
,09-09 17:17:58.490  4743  4743 D BluetoothNotiBroadcastReceiver: onReceive
,09-09 17:17:58.490  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:17:58.500  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-09 17:17:59.740   287   287 E SMD     : DCD OFF,
,09-09 17:17:59.840  1015  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-09 17:17:59.840  1015  1028 D BatteryService: level:93, scale:100, status:2, health:2, present:true, voltage: 4225, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-09 17:17:59.840  1015  1028 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,09-09 17:17:59.850  1015  1028 D BatteryService: stay LED for charging
09-09 17:17:59.850  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-09 17:17:59.850  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-09 17:17:59.850  1015  1015 I MotionRecognitionService: Plugged
09-09 17:17:59.850  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
09-09 17:17:59.850  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,09-09 17:17:59.850  1435  1435 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-09 17:17:59.850  1435  1435 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,09-09 17:17:59.870  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,09-09 17:17:59.880  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,09-09 17:17:59.880  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,09-09 17:17:59.880  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,09-09 17:17:59.880  1178  1178 D SViewCoverView: level :93 plugged : 2
,09-09 17:17:59.990  1015  1095 V AlarmManager: waitForAlarm result :8
,09-09 17:18:01.110  7319  7373 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 17:18:01.110  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:18:02.740   287   287 E SMD     : DCD OFF
,09-09 17:18:04.110  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 17:18:04.110  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@14fe2ec0 added. We now have 6 listener(s)
09-09 17:18:04.110  7319  7373 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 17:18:04.110  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 17:18:04.110  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@af897f9 added. We now have 7 listener(s)
,09-09 17:18:04.110  7319  7373 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 17:18:04.110  7319  7373 I System.out: IsBluetoothEnabled
,09-09 17:18:04.120  7319  7373 D BluetoothAdapter: disable()
,09-09 17:18:04.120  1015  1491 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,09-09 17:18:04.130  7319  7373 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:18:04.130  7319  7373 D BluetoothAdapter: enable()
,09-09 17:18:04.130  1015  1505 W ActivityManager: Permission Denial: getCurrentUser() from pid=7319, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-09 17:18:04.130  1015  1505 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-09 17:18:04.130  1015  1505 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7319, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-09 17:18:04.130  1015  1505 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-09 17:18:04.130  1015  1505 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
09-09 17:18:04.130  1015  1505 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-09 17:18:04.130  1015  1505 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-09 17:18:04.130  1015  1505 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-09 17:18:04.130  1015  1505 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-09 17:18:04.130  1015  1505 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-09 17:18:04.130  1015  1505 D SettingsProvider: name = bluetooth_on
,09-09 17:18:04.140  1015  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-09 17:18:04.140  1015  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-09 17:18:04.150  1015  1046 D SecContentProvider: uri = 3 selection = isBluetoothEnabled,
09-09 17:18:04.150  3225  3301 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
09-09 17:18:04.150  1015  3283 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:18:04.150  3225  3301 D BluetoothAdapterProperties: Setting state to 11
09-09 17:18:04.150  1015  3283 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-09 17:18:04.150  3225  3301 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-09 17:18:04.150  3225  3301 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-09 17:18:04.150  3225  3301 D BluetoothAdapterService: updateAdapterState state is 11
09-09 17:18:04.150  3225  3301 D BluetoothAdapterService: Autoconnection is available 
09-09 17:18:04.150  3225  3301 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
09-09 17:18:04.150  3225  3301 D BtConfig.SecureMode: isSecureModeOn:false
09-09 17:18:04.150  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-09 17:18:04.150  3225  3301 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
09-09 17:18:04.150  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-09 17:18:04.150  3225  3301 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
09-09 17:18:04.150  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-09 17:18:04.150  3225  3301 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
09-09 17:18:04.150  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 17:18:04.150  3225  3301 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
09-09 17:18:04.150  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-09 17:18:04.150  3225  3301 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
09-09 17:18:04.150  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-09 17:18:04.150  3225  3301 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
09-09 17:18:04.150  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 17:18:04.150  3225  3301 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
09-09 17:18:04.150  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-09 17:18:04.150  3225  3301 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
09-09 17:18:04.150  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-09 17:18:04.150  3225  3301 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-09 17:18:04.150  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-09 17:18:04.150  3225  3301 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-09 17:18:04.150  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-09 17:18:04.150  3225  3301 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-09 17:18:04.150  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevSer,vice
09-09 17:18:04.150  3225  3301 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
09-09 17:18:04.150  3225  3301 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
09-09 17:18:04.150  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-09 17:18:04.150  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-09 17:18:04.150  3225  3301 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-09 17:18:04.160  1015  3283 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:04.160  1015  3283 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:04.160  1015  3283 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:18:04.160  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,09-09 17:18:04.160  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-09 17:18:04.160  3225  3225 D HeadsetService: Received start request. Starting profile...
09-09 17:18:04.160  3225  3225 D HeadsetService: start()
09-09 17:18:04.160  3225  3225 D HeadsetStateMachine: make
,09-09 17:18:04.160  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-09 17:18:04.160  1015  1015 I InputMethodManagerService: [BT Setting State] State =11
09-09 17:18:04.160  3225  3301 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-09 17:18:04.170  3225  3225 E HeadsetStateMachine: # of Max HF connection is 2
,09-09 17:18:04.170  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-09 17:18:04.170  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:18:04.180  1178  1178 D BluetoothTile:  getBluetoothState : 11
,09-09 17:18:04.180  1178  1704 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 17:18:04.180  1178  1704 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-09 17:18:04.180  2019  2019 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-09 17:18:04.180  4743  4743 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:18:04.180  1015  1135 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 17:18:04.180  1015  1466 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-09 17:18:04.180  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-09 17:18:04.190  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:18:04.190  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 17:18:04.190  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 17:18:04.190  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:18:04.190  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:04.190  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:18:04.190  1015  3280 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,09-09 17:18:04.190  1015  3280 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-09 17:18:04.190  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,09-09 17:18:04.190  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-09 17:18:04.200  3225  3301 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
09-09 17:18:04.200  1015  3280 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:04.200  1015  3280 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:04.200  1015  3280 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-09 17:18:04.200  1698  1698 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 17:18:04.200  1015  1135 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,09-09 17:18:04.200  1015  1135 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-09 17:18:04.200  1015  1135 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:18:04.200  1015  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:04.210  1015  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-09 17:18:04.210  1015  3282 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 17:18:04.210  1015  3282 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-09 17:18:04.210  1015  3282 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:18:04.210  1015  3282 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:04.210  1015  3282 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:18:04.210  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
09-09 17:18:04.210  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-09 17:18:04.210  3225  3301 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
09-09 17:18:04.210  3225  3225 I bluedroid: get_profile_interface handsfree
,09-09 17:18:04.220  1015  1501 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
09-09 17:18:04.220  1015  1501 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
09-09 17:18:04.220  1015  1501 W ActivityManager: userId = 0, bbcId = -10000,
09-09 17:18:04.220  1015  1501 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:04.220  1015  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:18:04.220  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,09-09 17:18:04.220  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-09 17:18:04.220  3225  3301 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-09 17:18:04.220  1015  1346 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:18:04.220  1015  1346 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-09 17:18:04.230  1015  1346 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:04.230  1015  1346 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:04.230  1015  1346 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
,09-09 17:18:04.230  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService,
09-09 17:18:04.230  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-09 17:18:04.230  1015  1505 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:18:04.230  3225  3301 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
09-09 17:18:04.230  1015  1505 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-09 17:18:04.230  4743  4743 D BluetoothNotiBroadcastReceiver: onReceive
,09-09 17:18:04.230  1015  1505 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:04.230  1015  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:04.230  1015  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:18:04.240  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,09-09 17:18:04.240  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-09 17:18:04.240  3225  3301 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-09 17:18:04.240  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:18:04.240  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-09 17:18:04.240  1015  1504 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:18:04.240  1015  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-09 17:18:04.240  1015  1504 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:04.240  1015  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:04.240  1015  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:18:04.240  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-09 17:18:04.240  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-09 17:18:04.240  3225  3301 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-09 17:18:04.240  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-09 17:18:04.240  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-09 17:18:04.240  3225  3225 E DualScoManager: Dual Sco Manager already instantiated
09-09 17:18:04.240  3225  3225 I DualScoManager: Set HeadsetServiceHelper
09-09 17:18:04.240  3225  3225 D BluetoothAtMessage: createCMTIContentObservers
,09-09 17:18:04.240  3225  3301 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-09 17:18:04.240  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-09 17:18:04.240  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-09 17:18:04.240  3225  3301 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-09 17:18:04.240  3225  3301 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-09 17:18:04.240  3225  3301 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-09 17:18:04.240  3225  3301 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,09-09 17:18:04.240  3225  3301 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-09 17:18:04.250  1015  1504 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,09-09 17:18:04.250  1015  1504 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-09 17:18:04.250  1015  1504 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 17:18:04.250  1015  1504 D SettingsProvider: selectionArgs: false
09-09 17:18:04.250  1015  1504 D SettingsProvider: selectionArgs: 1002
09-09 17:18:04.250  1015  1504 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 17:18:04.250  1015  1504 D SettingsProvider: ret = -1
,09-09 17:18:04.250  3225  8008 D HeadsetStateMachine: Enter Disconnected: -2
,09-09 17:18:04.250  3225  3225 D HeadsetService: mStartError = false
,09-09 17:18:04.260  3225  3225 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29627d18
,09-09 17:18:04.260  3225  8008 D HeadsetStateMachine: Clear mHeadsetBrsf
09-09 17:18:04.260  3225  3225 D A2dpService: Received start request. Starting profile...
09-09 17:18:04.260  3225  3225 D A2dpService: start()
09-09 17:18:04.260  3225  3225 I bluedroid: get_profile_interface avrcp
,09-09 17:18:04.260  3225  8008 D HeadsetStateMachine: map size, before remove : 0
09-09 17:18:04.260  3225  8008 D HeadsetStateMachine: map size, after remove: 0
,09-09 17:18:04.260  3225  3225 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-09 17:18:04.260  3225  3225 D Avrcp   : Initialize Media Controller
09-09 17:18:04.260  3225  3225 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,09-09 17:18:04.260  3225  3225 E Avrcp   : getActiveSessions
,09-09 17:18:04.260  3225  3225 D Avrcp   : pick active media Controller
,09-09 17:18:04.260  3225  3225 D Avrcp   : Get the active Media Controller 
,09-09 17:18:04.270  3225  3225 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-09 17:18:04.270  3225  3225 D A2dpStateMachine: make
,09-09 17:18:04.270  3225  8009 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-09 17:18:04.270  3225  3225 I bluedroid: get_profile_interface a2dp
,09-09 17:18:04.270  3225  8011 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-09 17:18:04.280  3225  3225 E bt-btif : warning : media task started media_task_refcnt 1 
09-09 17:18:04.280  3225  3225 D A2dpService: mStartError = false
09-09 17:18:04.280  3225  3225 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29627d18
09-09 17:18:04.280  3225  3225 D HeadsetStateMachine: Try to query the phonestate on bind
09-09 17:18:04.280  3225  3225 D HeadsetStateMachine: Proxy object connected
,09-09 17:18:04.280  1452  3379 I Telecom : BluetoothPhoneService: queryPhoneState
09-09 17:18:04.280  3225  8010 D A2dpStateMachine: Enter Disconnected: -2
09-09 17:18:04.280  1452  1452 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
09-09 17:18:04.280  1452  1452 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-09 17:18:04.280  3225  3225 D HidService: Received start request. Starting profile...
09-09 17:18:04.280  1452  3379 I Telecom : BluetoothPhoneService: Result of Message : true
09-09 17:18:04.280  3225  3225 D HidService: start()
09-09 17:18:04.280  3225  3225 I bluedroid: get_profile_interface hidhost
,09-09 17:18:04.280  3225  3225 D HidService: setHidService(): set to: null
,09-09 17:18:04.280  3225  3225 D HidService: mStartError = false
09-09 17:18:04.280  3225  3225 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29627d18
09-09 17:18:04.280  3225  3225 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
09-09 17:18:04.280  3225  8008 D HeadsetStateMachine: Disconnected process message: 11
09-09 17:18:04.280  3225  3225 D HealthService: Received start request. Starting profile...
09-09 17:18:04.280  3225  3225 D HealthService: start()
,09-09 17:18:04.280  3225  3225 I bluedroid: get_profile_interface health
09-09 17:18:04.280  3225  8009 D BluetoothMediaBrowser: no now playing list
09-09 17:18:04.280  3225  3225 D HealthService: mStartError = false
09-09 17:18:04.280  3225  3225 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29627d18
,09-09 17:18:04.280  3225  8009 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-09 17:18:04.280  3225  3225 D PanService: Received start request. Starting profile...
09-09 17:18:04.280  3225  3225 D PanService: start()
09-09 17:18:04.280  3225  3225 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-09 17:18:04.280  3225  3225 I bluedroid: get_profile_interface pan
09-09 17:18:04.280  3225  3225 D PanService: mStartError = false
09-09 17:18:04.280  3225  3225 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29627d18
09-09 17:18:04.280  3225  3225 D HeadsetPhoneState: sendDeviceDataStateChanged
09-09 17:18:04.280  3225  3225 D HeadsetPhoneState: Signal level : previous=0 curr=4
,09-09 17:18:04.280  3225  8008 D HeadsetStateMachine: Disconnected process message: 18
09-09 17:18:04.280  3225  3225 D BluetoothMapService: Received start request. Starting profile...
,09-09 17:18:04.280  3225  3225 D BluetoothMapService: start()
,09-09 17:18:04.290  3225  3225 D BluetoothMapService: mStartError = false
,09-09 17:18:04.290  3225  3225 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29627d18
,09-09 17:18:04.290  3225  3225 D SapService: Received start request. Starting profile...
,09-09 17:18:04.290  3225  3225 D SapService: start()
,09-09 17:18:04.290  3225  3225 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-09 17:18:04.290  3225  3225 I bluedroid: get_profile_interface sap
09-09 17:18:04.290  3225  3225 D SapService: mStartError = false
,09-09 17:18:04.290  3225  3225 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29627d18
09-09 17:18:04.290  3225  3225 E BluetoothAdapterService(694320408): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-09 17:18:04.290  3225  3225 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-09 17:18:04.290  3225  3225 E BluetoothAdapterService(694320408): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true,
09-09 17:18:04.290  3225  3225 E BluetoothAdapterService(694320408): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-09 17:18:04.290  3225  8008 D HeadsetStateMachine: Disconnected process message: 10
09-09 17:18:04.290  3225  8008 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-09 17:18:04.290  3225  8008 D HeadsetStateMachine: Disconnected process message: 11
,09-09 17:18:04.290  3225  3225 E BluetoothAdapterService(694320408): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-09 17:18:04.290  3225  3225 E BluetoothAdapterService(694320408): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-09 17:18:04.310  3225  3225 E BluetoothAdapterService(694320408): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-09 17:18:04.310  3225  3225 E BluetoothAdapterService(694320408): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-09 17:18:04.310  3225  3301 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-09 17:18:04.310  3225  3301 I bluedroid: enable
,09-09 17:18:04.320  3225  3304 E bt-btif : Calling BTA_HhEnable
,09-09 17:18:04.320  3225  3304 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,09-09 17:18:04.320  3225  3304 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,09-09 17:18:04.320  3225  3304 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-09 17:18:04.320  3225  3304 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
,09-09 17:18:04.320  3225  3304 E BluetoothServiceJni: populateRssiValuesNative
,09-09 17:18:04.320  3225  3304 I bluedroid: getModelRssiValues
09-09 17:18:04.320  3225  3304 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-09 17:18:04.320  3225  3304 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-09 17:18:04.320  1015  1015 D SettingsProvider: name = bluetooth_name
,09-09 17:18:04.320  3225  3304 D BluetoothAdapterProperties: Name is: Galaxy A3
,09-09 17:18:04.330  3225  3304 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-09 17:18:04.330  3225  3304 D BluetoothAdapterProperties: Scan Mode:20
09-09 17:18:04.330  3225  3304 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 17:18:04.330  3225  3304 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
09-09 17:18:04.330  3225  3304 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
09-09 17:18:04.330  3225  3304 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,09-09 17:18:04.330  3225  3304 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-09 17:18:04.330  3225  3304 E bt-btif : JVenable fails
,09-09 17:18:04.330  3225  3304 D bte_conf: Device ID record 1 : primary
09-09 17:18:04.330  3225  3304 D bte_conf:   vendorId            = 0075
09-09 17:18:04.330  3225  3304 D bte_conf:   vendorIdSource      = 0001
09-09 17:18:04.330  3225  3304 D bte_conf:   product             = 0100
09-09 17:18:04.330  3225  3304 D bte_conf:   version             = 0200
09-09 17:18:04.330  3225  3304 D bte_conf:   clientExecutableURL = 
09-09 17:18:04.330  3225  3304 D bte_conf:   serviceDescription  = 
09-09 17:18:04.330  3225  3304 D bte_conf:   documentationURL    = 
09-09 17:18:04.330  3225  3304 D bte_conf: bte_load_did_conf no section named DID2.
09-09 17:18:04.330  3225  3304 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
09-09 17:18:04.330  3225  3304 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-09 17:18:04.330  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:18:04.330  3225  3301 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-09 17:18:04.330  3225  3301 D BluetoothAdapterProperties: ScanMode =  20
09-09 17:18:04.330  3225  3301 D BluetoothAdapterProperties: State =  11
,09-09 17:18:04.330  1015  3282 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-09 17:18:04.340  3225  3301 D BluetoothAdapterProperties: Setting state to 12
,09-09 17:18:04.340  3225  3301 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-09 17:18:04.340  3225  3304 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-09 17:18:04.340  3225  3304 D BluetoothAdapterProperties: Scan Mode:21
09-09 17:18:04.340  3225  3304 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-09 17:18:04.340  1015  1505 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,09-09 17:18:04.340  1015  1505 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 17:18:04.340  1015  1505 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 17:18:04.340  1015  1505 D SettingsProvider: selectionArgs: false
09-09 17:18:04.340  1015  1505 D SettingsProvider: selectionArgs: 1002
09-09 17:18:04.340  1015  1505 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 17:18:04.340  1015  1505 D SettingsProvider: ret = -1
,09-09 17:18:04.340  3225  3301 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-09 17:18:04.340  3225  3301 D BluetoothAdapterService: updateAdapterState state is 12
,09-09 17:18:04.340  1015  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 17:18:04.340  1015  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-09 17:18:04.340  1015  1491 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:18:04.340  1015  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:04.340  1015  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:18:04.350  1452  1468 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 17:18:04.350  3225  3301 D BluetoothAdapterService: Autoconnection is available 
,09-09 17:18:04.350  3225  3301 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-09 17:18:04.350  1015  3283 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:18:04.350  3225  3301 D BluetoothAdapterService: starting service from this receiver
09-09 17:18:04.350  1015  3283 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
09-09 17:18:04.350  3225  3225 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-09 17:18:04.350  3225  3225 I BluetoothPbapService: Handler(): got msg=1
09-09 17:18:04.350  1015  1491 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-09 17:18:04.360  1015  3283 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:18:04.360  1015  3283 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:04.360  1015  3283 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 17:18:04.360  3225  3301 I BluetoothAdapterState: Entering On State from state = 11
,09-09 17:18:04.360  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:18:04.360  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:04.360  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:18:04.360  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:18:04.360  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:18:04.360  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:18:04.360  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:18:04.360  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:18:04.360  7319  7319 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 17:18:04.360  1015  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-09 17:18:04.360  1015  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 17:18:04.370  1015  1046 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:18:04.370  1015  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:04.370  1015  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-09 17:18:04.370  1452  1468 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 17:18:04.370  1681  1888 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 17:18:04.370  1681  1888 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 17:18:04.370  4743  4761 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-09 17:18:04.370  3225  8016 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-09 17:18:04.380  3225  8016 D BluetoothSocket: bindListen(): myUserId = 0
,09-09 17:18:04.380  3225  8016 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 17:18:04.380  3225  8016 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
,09-09 17:18:04.380  3225  8016 D BluetoothSocket: bindListen(), new LocalSocket 
,09-09 17:18:04.380  3225  8016 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 17:18:04.380  3225  8016 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@210e8828
09-09 17:18:04.380  3225  8016 D BluetoothSocket: channel: 19
09-09 17:18:04.380  3225  8016 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-09 17:18:04.520  1015  1046 I art     : Explicit concurrent mark sweep GC freed 68210(3MB) AllocSpace objects, 7(113KB) LOS objects, 33% free, 23MB/34MB, paused 2.416ms total 147.852ms
09-09 17:18:04.530  1015  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
09-09 17:18:04.530  1015  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-09 17:18:04.530  1015  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:04.530  1015  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:04.530  1015  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 17:18:04.530  1015  1046 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 17:18:04.530  1015  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 17:18:04.530  1015  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 17:18:04.530  1015  1046 E BluetoothHeadset: BluetoothHeadset service is binded
09-09 17:18:04.530  4743  4755 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 17:18:04.530  4743  4743 D BluetoothInputDevice: Proxy object connected
09-09 17:18:04.530  4743  4743 D HidProfile: Bluetooth service connected
09-09 17:18:04.530  4743  4755 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-09 17:18:04.530  1015  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-09 17:18:04.530  1015  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 17:18:04.530  1015  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:04.530  1015  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:04.530  1015  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 17:18:04.530  1452  1477 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 17:18:04.530  1452  1477 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 17:18:04.530  4743  4761 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 17:18:04.540  1015  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 17:18:04.540  1015  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 17:18:04.540  1015  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:04.540  1015  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:04.540  1015  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 17:18:04.540  4743  4761 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 17:18:04.540  4743  4743 D BluetoothA2dp: Proxy object connected
,09-09 17:18:04.540  4743  4743 D A2dpProfile: Bluetooth service connected
,09-09 17:18:04.540  1452  3379 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 17:18:04.540  1015  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 17:18:04.540  1015  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 17:18:04.540  1015  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:04.540  1015  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:04.540  1015  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-09 17:18:04.540  1452  3379 E BluetoothHeadset: BluetoothHeadset service is binded
09-09 17:18:04.540  1015  1046 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-09 17:18:04.540  1015  1046 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 17:18:04.540  1478  1503 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-09 17:18:04.540  1015  1046 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-09 17:18:04.540  1015  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3,
09-09 17:18:04.540  1015  1046 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:18:04.540  1015  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:04.540  1015  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
09-09 17:18:04.540  4743  4743 D HeadsetProfile: Bluetooth service connected
09-09 17:18:04.540  1478  1503 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 17:18:04.550  4743  4761 D BluetoothPan: Binding service...
,09-09 17:18:04.550  1015  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-09 17:18:04.550  1015  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-09 17:18:04.550  1015  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:04.550  1015  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:04.550  1015  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 17:18:04.550  1452  3379 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 17:18:04.550  4743  4743 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 17:18:04.550  1015  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 17:18:04.550  1015  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 17:18:04.550  1015  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:04.550  4743  4743 D PanProfile: Bluetooth service connected
09-09 17:18:04.550  1015  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:04.550  1015  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-09 17:18:04.550  1452  3379 E BluetoothHeadset: BluetoothHeadset service is binded
09-09 17:18:04.550  1015  1046 D BluetoothPan: Binding service...
,09-09 17:18:04.550  1015  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-09 17:18:04.550  1015  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-09 17:18:04.550  1015  1015 D BluetoothPan: BluetoothPAN Proxy object connected
,09-09 17:18:04.550  3225  3380 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 17:18:04.550  3225  3380 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 17:18:04.550  1478  3344 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 17:18:04.550  1478  3344 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 17:18:04.560  7947  7959 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-09 17:18:04.560  7947  7959 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 17:18:04.560  4743  7429 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 17:18:04.560  4743  7429 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 17:18:04.560  1698  4217 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 17:18:04.560  1698  4217 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-09 17:18:04.560  1015  1046 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 17:18:04.560  1015  1046 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-09 17:18:04.560  1015  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-09 17:18:04.560  1015  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 17:18:04.560  7319  7328 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 17:18:04.560  7319  7328 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-09 17:18:04.560  1178  1544 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 17:18:04.560  1178  1544 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 17:18:04.560  1015  1015 D BluetoothA2dp: Proxy object connected
,09-09 17:18:04.560  4743  8018 D BluetoothPbap: onBluetoothStateChange: up=true
,09-09 17:18:04.560  1015  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,09-09 17:18:04.560  1015  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-09 17:18:04.560  1015  1046 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:18:04.560  1015  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:04.560  1015  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 17:18:04.570  4743  4743 D BluetoothPbap: Proxy object connected
,09-09 17:18:04.570  1461  1486 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-09 17:18:04.570  1461  1486 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 17:18:04.570  4743  4743 D PbapServerProfile: Bluetooth service connected
09-09 17:18:04.570  4743  4755 D BluetoothMap: onBluetoothStateChange: up=true
,09-09 17:18:04.570  1015  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,09-09 17:18:04.570  1015  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-09 17:18:04.570  1015  1046 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:18:04.570  1015  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:04.570  1015  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 17:18:04.570  4743  7429 D Bluetoothsap: onBluetoothStateChange: up=true
09-09 17:18:04.570  4743  7429 D Bluetoothsap: Binding service...
,09-09 17:18:04.570  4743  7429 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-09 17:18:04.570  4743  4743 D BluetoothMap: Proxy object connected
09-09 17:18:04.570  4743  4743 D MapProfile: Bluetooth service connected
09-09 17:18:04.570  1015  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,09-09 17:18:04.570  1015  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
09-09 17:18:04.570  4743  4743 D BluetoothMap: getConnectedDevices()
,09-09 17:18:04.570  1015  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:04.570  1015  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:04.570  1015  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 17:18:04.570  4743  7429 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-09 17:18:04.570  3225  3366 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 17:18:04.570  3225  3366 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-09 17:18:04.580  4743  4743 D Bluetoothsap: BluetoothSAP Proxy object connected
09-09 17:18:04.580  4743  4743 D SapProfile: Bluetooth service connected
09-09 17:18:04.580  4743  4743 D Bluetoothsap: getConnectedDevices()
,09-09 17:18:04.580  1015  1046 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-09 17:18:04.580  1015  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 17:18:04.580  1015  1046 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:18:04.580  1015  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:04.580  1015  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:18:04.580  3225  3225 D BluetoothA2dp: Proxy object connected
09-09 17:18:04.580  3225  3225 D BluetoothAdapterService: Bluetooth A2dp source service connected
,09-09 17:18:04.580  1015  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,09-09 17:18:04.580  1015  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-09 17:18:04.580  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:18:04.580  1015  1015 I InputMethodManagerService: [BT Setting State] State =12
,09-09 17:18:04.580  1015  1015 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-09 17:18:04.590  1452  1452 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@375112bc, true
,09-09 17:18:04.590  1452  1452 D BluetoothHeadset: registerMessageListener
,09-09 17:18:04.590  4743  4743 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:18:04.590  1178  1178 D BluetoothTile:  onBluetoothStateChange:
,09-09 17:18:04.590  2019  2019 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-09 17:18:04.600  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-09 17:18:04.600  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:18:04.600  1178  1178 D BluetoothTile:  getBluetoothState : 12
,09-09 17:18:04.600  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:18:04.600  1015  1027 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 17:18:04.600  3225  3380 D HeadsetService: registerMessageListener
,09-09 17:18:04.600  1015  1466 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
09-09 17:18:04.600  3225  3380 D HeadsetService: registerMessageListener
,09-09 17:18:04.600  3225  8008 D HeadsetStateMachine: Disconnected process message: 70
09-09 17:18:04.600  3225  8008 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@379c5941
,09-09 17:18:04.600  1452  1452 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-09 17:18:04.600  1452  1452 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-09 17:18:04.600  1178  1704 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 17:18:04.610  4743  4743 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-09 17:18:04.610  4743  4743 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-09 17:18:04.610  4743  4743 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-09 17:18:04.610  4743  4743 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-09 17:18:04.610  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 17:18:04.610  1178  1704 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 17:18:04.610  1178  1704 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 17:18:04.610  1452  1452 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,09-09 17:18:04.610  1452  1452 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,09-09 17:18:04.610  1452  1452 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-09 17:18:04.610  3225  8019 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-09 17:18:04.610  3225  8008 D HeadsetStateMachine: Disconnected process message: 9
,09-09 17:18:04.610  3225  8008 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-09 17:18:04.620   282   699 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
09-09 17:18:04.620   282   699 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-09 17:18:04.620   282   699 V voice   : voice_set_parameters: exit with code(-2)
09-09 17:18:04.620   282   699 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-09 17:18:04.620   282   699 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-09 17:18:04.620   282   699 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-09 17:18:04.620   282   699 V audio_hw_primary: adev_set_parameters: exit
09-09 17:18:04.620  3225  8008 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-09 17:18:04.620  4743  4743 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 17:18:04.620  3225  8019 D BluetoothSocket: bindListen(): myUserId = 0
09-09 17:18:04.620  1015  3283 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-09 17:18:04.620  3225  8019 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 17:18:04.620  1015  3283 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-09 17:18:04.620  1015  3283 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:18:04.620  1015  3283 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 17:18:04.620  1015  3283 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-09 17:18:04.620  3225  8019 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
,09-09 17:18:04.620  3225  8019 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 17:18:04.630  3225  8019 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,09-09 17:18:04.630  3225  8019 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1a09fee6
,09-09 17:18:04.630  3225  8019 D BluetoothSocket: channel: 5
,09-09 17:18:04.630  1698  1698 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 17:18:04.630  4743  4743 D DockEventReceiver: finishStartingService: stopping service
,09-09 17:18:04.640  4743  4743 D BluetoothNotiBroadcastReceiver: onReceive
,09-09 17:18:04.640  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:18:04.640  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-09 17:18:04.650  3225  3225 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29627d18
,09-09 17:18:04.650  3225  3225 D BtConfig.SecureMode: isSecureModeOn:false
,09-09 17:18:04.650  1015  1346 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 17:18:04.650  1015  1346 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-09 17:18:04.650  1015  1346 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:18:04.650  1015  1346 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 17:18:04.650  1015  1346 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:18:04.670  1015  1501 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-09 17:18:04.670  3225  8024 D BluetoothSocket: bindListen(): myUserId = 0
09-09 17:18:04.670  3225  8024 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 17:18:04.670  3225  8024 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[86]}
,09-09 17:18:04.670  3225  8024 D BluetoothSocket: bindListen(), new LocalSocket 
,09-09 17:18:04.670  3225  8024 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 17:18:04.670  3225  8024 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@13e72372
,09-09 17:18:04.670  3225  8024 D BluetoothSocket: channel: 12
,09-09 17:18:04.670  3225  8024 I BtOppRfcommListener: Accept thread started.
,09-09 17:18:05.160  7319  7373 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
09-09 17:18:05.160  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:05.160  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:18:05.160  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:18:05.160  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:18:05.160  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:18:05.160  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:18:05.160  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:18:05.160  7319  7373 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:18:05.160  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 17:18:05.160  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2dbcc33e added. We now have 8 listener(s)
09-09 17:18:05.160  7319  7373 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 17:18:05.170  1015  1466 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-09 17:18:05.170  1015  1466 D WifiService: setWifiEnabled: false pid=7319, uid=10170
09-09 17:18:05.170  1015  1466 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-09 17:18:05.170  1015  1466 D SecContentProvider2: mCursor = null,
09-09 17:18:05.170  1015  1466 D SettingsProvider: name = wifi_on
09-09 17:18:05.170  7319  7373 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:18:05.170  1015  1244 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-09 17:18:05.180  1015  1244 D WifiService: setWifiEnabled: true pid=7319, uid=10170
09-09 17:18:05.170  1015  1244 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-09 17:18:05.180  1015  1244 W ActivityManager: Permission Denial: getCurrentUser() from pid=7319, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-09 17:18:05.170  1015  1244 D SecContentProvider2: mCursor = null
09-09 17:18:05.180  1015  1244 W WifiService: Failed getting userId using ActivityManagerNative
09-09 17:18:05.180  1015  1244 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7319, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-09 17:18:05.180  1015  1244 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-09 17:18:05.180  1015  1244 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-09 17:18:05.180  1015  1244 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-09 17:18:05.180  1015  1244 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-09 17:18:05.180  1015  1244 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-09 17:18:05.180  1015  1244 D SettingsProvider: name = wifi_on
,09-09 17:18:05.180  1015  1127 E WifiHW  : ##################### set firmware type 0 #####################
,09-09 17:18:05.500  1015  1044 D Tethering: interfaceAdded wlan0
,09-09 17:18:05.510  1015  1130 E Tethering: No numeric data,
09-09 17:18:05.510  1015  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-09 17:18:05.510  1015  1130 D Tethering: clearTetheredNotification()
,09-09 17:18:05.510  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:18:05.510  1015  1124 V NetworkStats: performPollLocked(flags=0x1)
,09-09 17:18:05.520  1015  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 17:18:05.520  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-09 17:18:05.520  1015  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-09 17:18:05.520  1178  1178 D HotspotTile: updateTetherState():false, false
,09-09 17:18:05.520  1015  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 17:18:05.520  1015  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 17:18:05.520  1015  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-09 17:18:05.520  1015  1124 V NetworkStats: performPollLocked() took 10ms
,09-09 17:18:05.520  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:18:05.520  1015  1130 D Tethering: InitialState.processMessage what=4
,09-09 17:18:05.530  1015  1130 E Tethering: No numeric data
,09-09 17:18:05.530  1015  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:18:05.530  1015  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:18:05.530  1015  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-09 17:18:05.530  1015  1130 D Tethering: clearTetheredNotification()
09-09 17:18:05.530  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:18:05.530  1015  1124 V NetworkStats: performPollLocked(flags=0x1)
09-09 17:18:05.530  1015  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 17:18:05.530  1015  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 17:18:05.540  1015  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 17:18:05.540  1015  1044 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 17:18:05.540  1015  1044 D Tethering: interfaceStatusChanged p2p0, false,
09-09 17:18:05.540  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 17:18:05.540  1178  1178 D HotspotTile: updateTetherState():false, false
,09-09 17:18:05.540  1015  1124 V NetworkStats: performPollLocked() took 11ms
09-09 17:18:05.540  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:18:05.540  1015  1044 D Tethering: interfaceAdded p2p0
09-09 17:18:05.540  1015  1044 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-09 17:18:05.550   277   966 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,09-09 17:18:05.550   277   966 D SoftapController: Softap fwReload - Ok,
09-09 17:18:05.550  1015  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:18:05.550  1015  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:18:05.550   277   966 D CommandListener: Setting iface cfg
09-09 17:18:05.550   277   966 D CommandListener: Trying to bring down wlan0
,09-09 17:18:05.550   277   966 D CommandListener: Clearing all IP addresses on wlan0,
,09-09 17:18:05.560  1015  1127 E WifiHW  : supplicant_name : p2p_supplicant
,09-09 17:18:05.560  1015  1127 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
09-09 17:18:05.560  1015  1127 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": Permission denied
,09-09 17:18:05.580  4743  4743 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-09 17:18:05.580  1015  1501 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 17:18:05.580  1015  1501 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 17:18:05.580  1015  1501 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:05.580  1015  1501 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:05.580  1015  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings,
,09-09 17:18:05.580  1605  1605 I Hs20UtilService: Starting #19
09-09 17:18:05.580  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:18:05.580  1605  1643 I Hs20UtilService: Message received 5011
,09-09 17:18:05.590  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-09 17:18:05.590  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 17:18:05.590  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 17:18:05.590  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-09 17:18:05.590  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:05.590  1178  1178 D HotspotTile: onReceive : 2, 0
09-09 17:18:05.590  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:05.590  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:05.590  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:05.590  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 17:18:05.590  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
09-09 17:18:05.590  7140  7140 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-09 17:18:05.590  7140  7140 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 17:18:05.590  7140  7140 D SecurityLogAgent: StateMachine : Current State = 1
09-09 17:18:05.590  7140  7140 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 17:18:05.600  1178  1704 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-09 17:18:05.600  8037  8037 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-09 17:18:05.600  8037  8037 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-09 17:18:05.600  8037  8037 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage,
,09-09 17:18:05.620  8037  8037 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
09-09 17:18:05.620   373   373 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 8037
09-09 17:18:05.620   373   373 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-09 17:18:05.620  8037  8037 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-09 17:18:05.620  8037  8037 I wpa_supplicant: ssSupport state is = 1
09-09 17:18:05.620  8037  8037 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-09 17:18:05.620  8037  8037 I SecureStorage: [INFO]: SPID(0x00000000)Processing data,
09-09 17:18:05.620   373   373 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 8037
09-09 17:18:05.620   373   373 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,09-09 17:18:05.740   287   287 E SMD     : DCD OFF,
,09-09 17:18:05.790   373   373 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,09-09 17:18:05.800  8037  8037 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed,
,09-09 17:18:05.840  8037  8037 I wpa_supplicant: Ctrl_iface: loading cred from phone,
09-09 17:18:05.840  8037  8037 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-09 17:18:05.860  8037  8037 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,09-09 17:18:05.860   373   373 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 8037
09-09 17:18:05.860   373   373 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-09 17:18:05.860  8037  8037 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
09-09 17:18:05.860  8037  8037 I wpa_supplicant: ssSupport state is = 1
09-09 17:18:05.860  8037  8037 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-09 17:18:05.860  8037  8037 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 17:18:05.860  8037  8037 E wpa_supplicant: SIM READ ERROR,
09-09 17:18:05.860  8037  8037 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 17:18:05.860  8037  8037 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-09 17:18:05.860  8037  8037 E wpa_supplicant: SIM READ ERROR
09-09 17:18:05.860  8037  8037 I wpa_supplicant: Blacklist: Clear (all) ,
09-09 17:18:05.860  8037  8037 I wpa_supplicant: wpa_default_ap_write_once
09-09 17:18:05.860  8037  8037 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
09-09 17:18:05.860  8037  8037 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 17:18:05.860  8037  8037 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory,
09-09 17:18:05.860  8037  8037 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-09 17:18:05.860  8037  8037 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 17:18:05.860  8037  8037 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-09 17:18:05.870  1015  1044 D Tethering: interfaceLinkStateChanged wlan0, false,
09-09 17:18:05.870  1015  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 17:18:05.870  1015  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-09 17:18:05.940  8037  8037 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-09 17:18:06.100  1015  3377 D SSRM:n  : SIOP:: AP = 340,
,09-09 17:18:06.120  8037  8037 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,09-09 17:18:06.120  8037  8037 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-09 17:18:06.130  8037  8037 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-09 17:18:06.130   373   373 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 8037
09-09 17:18:06.130   373   373 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,09-09 17:18:06.130  8037  8037 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
,09-09 17:18:06.130  8037  8037 I wpa_supplicant: ssSupport state is = 1
09-09 17:18:06.130  8037  8037 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-09 17:18:06.130  8037  8037 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,09-09 17:18:06.150  8037  8037 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,09-09 17:18:06.150  1015  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 17:18:06.150   373   373 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 8037,
09-09 17:18:06.150  1015  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-09 17:18:06.150   373   373 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-09 17:18:06.150  8037  8037 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
09-09 17:18:06.150  8037  8037 I wpa_supplicant: ssSupport state is = 1
,09-09 17:18:06.150  8037  8037 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 17:18:06.150  8037  8037 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-09 17:18:06.150  8037  8037 E wpa_supplicant: SIM READ ERROR
,09-09 17:18:06.150  8037  8037 I wpa_supplicant: wpa_default_ap_write_once
,09-09 17:18:06.150  8037  8037 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,09-09 17:18:06.150  8037  8037 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-09 17:18:06.150  1015  1044 D Tethering: interfaceLinkStateChanged p2p0, false
,09-09 17:18:06.150  1015  1044 D Tethering: interfaceStatusChanged p2p0, false
09-09 17:18:06.150  1015  1044 D Tethering: interfaceLinkStateChanged p2p0, false,
09-09 17:18:06.150  1015  1044 D Tethering: interfaceStatusChanged p2p0, false
,09-09 17:18:06.200  8037  8037 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-09 17:18:06.200  8037  8037 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-09 17:18:06.260  8037  8037 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
09-09 17:18:06.260  8037  8037 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-09 17:18:06.260  8037  8037 I wpa_supplicant: Skip scan - bUseNetwork false,
,09-09 17:18:06.520  1015  1044 D Tethering: interfaceLinkStateChanged p2p0, false,
09-09 17:18:06.520  1015  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 17:18:06.520  1015  1044 D Tethering: interfaceStatusChanged p2p0, false
,09-09 17:18:06.570  1015  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,09-09 17:18:06.570  1015  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
09-09 17:18:06.570  8037  8037 I wpa_supplicant: HOTSPOT20_ENABLE called
,09-09 17:18:06.570  8037  8037 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 17:18:06.570  8037  8037 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 17:18:06.570  8037  8037 E wpa_supplicant: SIM READ ERROR,
09-09 17:18:06.570  8037  8037 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 17:18:06.590  8037  8037 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-09 17:18:06.600  8037  8037 I wpa_supplicant: Skip scan - bUseNetwork false,
,09-09 17:18:06.600  1015  1127 D WifiConfigStore: Loading config and enabling all networks ,
,09-09 17:18:06.610  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
09-09 17:18:06.610  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 17:18:06.610  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
09-09 17:18:06.610  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:06.610  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 17:18:06.610  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:18:06.610  1178  1704 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-09 17:18:06.610  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:06.610  1178  1178 D HotspotTile: onReceive : 3, 0
,09-09 17:18:06.610  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:06.610  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 17:18:06.610  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,09-09 17:18:06.610  4743  4743 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-09 17:18:06.610  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:18:06.610  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:06.610  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:18:06.610  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:18:06.610  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:18:06.610  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:18:06.610  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:18:06.610  7319  7319 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:18:06.620  1015  1027 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 17:18:06.620  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-09 17:18:06.620  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:06.620  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 17:18:06.620  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 17:18:06.620  7319  7319 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 17:18:06.620  1015  1127 E WifiConfigStore: Not a HS20
,09-09 17:18:06.620  1605  1605 I Hs20UtilService: Starting #20
,09-09 17:18:06.620  1605  1643 I Hs20UtilService: Message received 5011
,09-09 17:18:06.630  1015  1127 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-09 17:18:06.630  7140  7140 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-09 17:18:06.630  7140  7140 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 17:18:06.630  7140  7140 D SecurityLogAgent: StateMachine : Current State = 1
,09-09 17:18:06.630  7140  7140 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 17:18:06.630  1015  1127 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-09 17:18:06.630  8037  8037 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-09 17:18:06.630  8037  8037 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-09 17:18:06.630  8037  8037 I wpa_supplicant: reset timer : RESET_TIMER 0
09-09 17:18:06.630  8037  8037 I wpa_supplicant: P2P: Current p2p state = IDLE
09-09 17:18:06.630  8037  8037 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-09 17:18:06.630  8037  8037 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-09 17:18:06.630  8037  8037 I wpa_supplicant: First Scan Start
,09-09 17:18:06.630  8037  8037 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-09 17:18:06.640  1015  1127 D WifiNative-wlan0: Setting external_sim to 1
,09-09 17:18:06.640  1015  1127 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 17:18:06.640  1015  1127 I WifiNative-HAL: startHal
09-09 17:18:06.640  1015  1127 E wifi    : getStaticLongField sWifiHalHandle 0x9f6cc88c
09-09 17:18:06.640  1015  1127 I WifiNative-HAL: Could not start hal
,09-09 17:18:06.640  7493  7493 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 17:18:06.640  1015  1127 E WifiNative-wlan0: do suspend true
,09-09 17:18:06.640  1015  1126 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-09 17:18:06.650  1015  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-09 17:18:06.650   277   966 D CommandListener: Setting iface cfg
09-09 17:18:06.650   277   966 D CommandListener: Trying to bring up p2p0
,09-09 17:18:06.650  1015  1126 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-09 17:18:06.650  1015  1126 D WifiP2pService: P2pEnablingState
09-09 17:18:06.650  1015  1126 D WifiP2pService: P2pEnablingState{ what=147457 }
,09-09 17:18:06.650  1015  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-09 17:18:06.650  1015  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-09 17:18:06.650  1015  1127 E WifiNative-wlan0: invaild command id : 215
,09-09 17:18:06.650  1015  1126 D WifiP2pService: P2p socket connection successful
09-09 17:18:06.650  1015  1126 D WifiP2pService: P2pEnabledState
09-09 17:18:06.650  1015  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-09 17:18:06.650  1015  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-09 17:18:06.650  1015  1127 E WifiNative-wlan0: invaild command id : 215
,09-09 17:18:06.650  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3
,09-09 17:18:06.650  1015  1150 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:18:06.650  1015  1150 I WifiNative-HAL: startHal
09-09 17:18:06.650  1015  1150 E wifi    : getStaticLongField sWifiHalHandle 0x9e58e9bc
09-09 17:18:06.650  1015  1150 I WifiNative-HAL: Could not start hal
09-09 17:18:06.650  1015  1150 E WifiScanningService: could not start HAL
09-09 17:18:06.650  1015  1015 D RttService: SCAN_AVAILABLE : 3
09-09 17:18:06.650  1015  1151 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 17:18:06.650  8037  8037 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-09 17:18:06.650  1015  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-09 17:18:06.650  8037  8037 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-09 17:18:06.650  1015  1129 E ConnectivityService: updateNetworkInfo()
,09-09 17:18:06.650  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-09 17:18:06.660  1015  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-09 17:18:06.660  1015  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 17:18:06.660  1015  1047 D WifiDisplayController: disconnect
09-09 17:18:06.660  1015  1047 D WifiDisplayController: updateConnection
09-09 17:18:06.660  1015  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 17:18:06.660  1015  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-09 17:18:06.660  8037  8037 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,09-09 17:18:06.660  1015  1127 E WifiStateMachine: Failed to set frequency band 0
,09-09 17:18:06.660  1015  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 17:18:06.660  1015  1127 D SecContentProvider2: mCursor = null
,09-09 17:18:06.660  1015  1126 D WifiNative-p2p0: p2pGetDeviceAddress
,09-09 17:18:06.660  1015  1126 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,09-09 17:18:06.660  4743  4743 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-09 17:18:06.660  1015  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:18:06.660  1015  1047 D WifiDisplayAdapter: onP2pDisconnected
09-09 17:18:06.660  1015  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 17:18:06.660  1015  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-09 17:18:06.660  4743  4743 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 17:18:06.660  1015  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 17:18:06.660  1015  1127 D SecContentProvider2: mCursor = null
,09-09 17:18:06.660  1178  1178 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-09 17:18:06.670  1015  3282 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-09 17:18:06.670  1178  1178 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-09 17:18:06.670  1015  1126 D WifiP2pService: DeviceAddress: 0a:75:42
,09-09 17:18:06.670  1015  1047 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
09-09 17:18:06.670  1015  1047 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
09-09 17:18:06.670  1015  1047 D WifiDisplayController:  primary type: 10-0050F204-5
09-09 17:18:06.670  1015  1047 D WifiDisplayController:  secondary type: null
09-09 17:18:06.670  1015  1047 D WifiDisplayController:  wps: 0
09-09 17:18:06.670  1015  1047 D WifiDisplayController:  grpcapab: 0
09-09 17:18:06.670  1015  1047 D WifiDisplayController:  devcapab: 0
09-09 17:18:06.670  1015  1047 D WifiDisplayController:  status: 3
09-09 17:18:06.670  1015  1047 D WifiDisplayController:  wfdInfo: null
09-09 17:18:06.670  1015  1047 D WifiDisplayController:  groupownerAddress: null
09-09 17:18:06.670  1015  1047 D WifiDisplayController:  GOdeviceName: null
09-09 17:18:06.670  1015  1047 D WifiDisplayController:  interfaceAddress: 
09-09 17:18:06.670  1015  1047 D WifiDisplayController:  SConnectInfo : null
,09-09 17:18:06.670  4743  4743 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 17:18:06.670  4743  4743 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-09 17:18:06.670  4743  4743 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 17:18:06.670  4743  4743 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 17:18:06.670  4743  4825 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 17:18:06.670  7875  7875 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 17:18:06.670  7875  7875 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-09 17:18:06.670  7875  7875 D FileShare-Client: Outbound.stopDelayTimer - 
,09-09 17:18:06.680  7478  7478 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 17:18:06.690  1015  1126 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-09 17:18:06.690  1015  1126 D WifiP2pService: InactiveState
,09-09 17:18:06.690  1015  1126 D WifiP2pService: InactiveState{ what=143376 }
,09-09 17:18:06.690  1015  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-09 17:18:06.690  8037  8037 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-09 17:18:06.690  1015  1126 D WifiP2pService: InactiveState{ what=143376 },
09-09 17:18:06.690  1015  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-09 17:18:07.200  7319  7373 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:18:07.200  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:07.200  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:18:07.200  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:18:07.200  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:18:07.200  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:18:07.200  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:18:07.200  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:18:07.200  7319  7373 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 17:18:07.200  7319  7373 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-09 17:18:07.200  7319  7373 D io.jxcore.node.LifeCycleMonitor: onActivityResumed,
,09-09 17:18:07.200  7319  7373 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1a884006 Bundle[{}]
,09-09 17:18:07.200  7319  7373 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-09 17:18:07.200  7319  7373 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-09 17:18:07.200  7319  7373 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-09 17:18:07.200  7319  7373 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-09 17:18:07.200  7319  7373 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-09 17:18:07.200  7319  7373 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-09 17:18:07.210  7319  7373 I System.out: Running OutgoingSocketThread
,09-09 17:18:07.210  7319  8046 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1490),
09-09 17:18:07.210  7319  8046 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47803
09-09 17:18:07.210  7319  8046 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-09 17:18:07.800  8037  8037 I wpa_supplicant: nl80211: Received scan results (25 BSSes),
,09-09 17:18:07.800  8037  8037 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
,09-09 17:18:07.800  1015  8043 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700',
,09-09 17:18:07.800  8037  8037 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,09-09 17:18:07.800  8037  8037 I wpa_supplicant: Trying to associate with  'G700'
,09-09 17:18:07.800  8037  8037 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING,
,09-09 17:18:07.800  8037  8037 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030,
,09-09 17:18:07.820  1015  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 17:18:07.820  1015  1127 D SecContentProvider2: mCursor = null
,09-09 17:18:08.140  8037  8037 E wpa_supplicant: Cmd 35605 not handled
,09-09 17:18:08.140  8037  8037 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-09 17:18:08.140  8037  8037 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,09-09 17:18:08.140  8037  8037 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-09 17:18:08.140  1015  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 17:18:08.140  1015  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 17:18:08.140  1015  1044 D Tethering: interfaceStatusChanged wlan0, false
09-09 17:18:08.140  8037  8037 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-09 17:18:08.140  8037  8037 I wpa_supplicant: Associated with F4.99.3E
09-09 17:18:08.140  8037  8037 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-09 17:18:08.140  8037  8037 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-09 17:18:08.140  8037  8037 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-09 17:18:08.140  1015  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 17:18:08.140  1015  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 17:18:08.140  1015  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-09 17:18:08.140  1015  1044 D Tethering: interfaceLinkStateChanged wlan0, true,
,09-09 17:18:08.140  1015  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-09 17:18:08.140  1015  1044 D Tethering: interfaceStatusChanged wlan0, true
09-09 17:18:08.150  1015  1130 E Tethering: No numeric data
,09-09 17:18:08.150  1015  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-09 17:18:08.150  1015  1130 D Tethering: clearTetheredNotification()
,09-09 17:18:08.150  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-09 17:18:08.150  1178  1178 D HotspotTile: updateTetherState():false, false
,09-09 17:18:08.150  1015  1124 V NetworkStats: performPollLocked(flags=0x1)
09-09 17:18:08.150  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:18:08.150  1015  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 17:18:08.150  1015  1127 D SecContentProvider2: mCursor = null
09-09 17:18:08.150  1015  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 17:18:08.160  1015  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 17:18:08.160  1015  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-09 17:18:08.160  1015  1127 D SecContentProvider2: mCursor = null
,09-09 17:18:08.160  1015  1124 V NetworkStats: performPollLocked() took 8ms
09-09 17:18:08.160  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:18:08.160  1015  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:18:08.160  1015  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:18:08.210  8037  8037 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-09 17:18:08.210  8037  8037 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,09-09 17:18:08.210  8037  8037 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-09 17:18:08.210  8037  8037 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,09-09 17:18:08.210  8037  8037 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 17:18:08.210  8037  8037 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-09 17:18:08.210  8037  8037 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-09 17:18:08.210  8037  8037 I wpa_supplicant: Blacklist: Clear (temp) 
09-09 17:18:08.210  8037  8037 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,09-09 17:18:08.210  1015  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-09 17:18:08.210  1015  1044 D Tethering: interfaceLinkStateChanged wlan0, true
09-09 17:18:08.210  1015  1044 D Tethering: interfaceStatusChanged wlan0, true
,09-09 17:18:08.210  1015  1127 D WifiNative-wlan0: callSECApiVoid - ID [50],
,09-09 17:18:08.210  7319  7373 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1491)
,09-09 17:18:08.210  7319  7373 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1491)
,09-09 17:18:08.220  1015  1127 E WifiConfigStore: setLastSelectedConfiguration -1
,09-09 17:18:08.220  7319  7373 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1496)
,09-09 17:18:08.220  7319  7373 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-09 17:18:08.220  7319  7373 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1497)
,09-09 17:18:08.220  1015  1127 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,09-09 17:18:08.220  1015  1129 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-09 17:18:08.230  1015  1129 E ConnectivityService: updateNetworkInfo()
09-09 17:18:08.230  1015  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 17:18:08.230  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-09 17:18:08.230  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 17:18:08.230  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 17:18:08.230  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:08.230  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:08.230  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:08.230  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:08.230  7319  7373 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:18:08.230  7319  7373 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cd0359f added. We now have 2 listener(s)
,09-09 17:18:08.230  1015  1505 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 17:18:08.230  1015  1505 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 17:18:08.230  1015  1505 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:08.230  1015  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 17:18:08.230  1015  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 17:18:08.230  1015  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 17:18:08.230  1605  1605 I Hs20UtilService: Starting #21
,09-09 17:18:08.240  1605  1643 I Hs20UtilService: Message received 5007
,09-09 17:18:08.240  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-09 17:18:08.240  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:18:08.240  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:18:08.240  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:18:08.240  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf776ec added. We now have 9 listener(s)
09-09 17:18:08.240  7319  7373 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 17:18:08.240  4743  4743 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-09 17:18:08.240  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 17:18:08.240  4743  4743 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 17:18:08.250  4743  4743 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 17:18:08.250  4743  4743 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-09 17:18:08.250  4743  4743 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 17:18:08.250  1015  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 17:18:08.250  4743  4743 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 17:18:08.250  4743  4825 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 17:18:08.250  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:18:08.260  7319  7373 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
,09-09 17:18:08.260  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:08.260  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:18:08.260  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:18:08.260  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:18:08.260  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:18:08.260  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
,09-09 17:18:08.260  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:18:08.260   277   966 D CommandListener: Setting iface cfg
,09-09 17:18:08.260  7319  7373 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:18:08.260  7319  7373 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 17:18:08.260  7319  7373 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:18:08.260  7319  7373 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c3dd54a added. We now have 3 listener(s)
,09-09 17:18:08.260  1015  1127 E WifiStateMachine: Start Dhcp Watchdog 3
,09-09 17:18:08.270  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:18:08.270  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:18:08.270  1015  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 17:18:08.270  1015  1127 D SecContentProvider2: mCursor = null
09-09 17:18:08.270  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-09 17:18:08.270  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:18:08.270  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:18:08.270  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:18:08.270  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e8c8cbb added. We now have 10 listener(s)
09-09 17:18:08.270  7319  7373 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:18:08.270  7319  7373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:18:08.270  7319  7373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:18:08.270  7319  7373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 17:18:08.270  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:18:08.270  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:08.270  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:18:08.270  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:18:08.270  7319  7373 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cd0359f removed from the list
09-09 17:18:08.270  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:08.270  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf776ec removed from the list
09-09 17:18:08.270  7319  7373 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:18:08.270  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:18:08.270  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:18:08.270  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:18:08.270  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:18:08.270  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:18:08.270  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:08.270  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf776ec not in the list
,09-09 17:18:08.270  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:08.270  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:18:08.280  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 17:18:08.280  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:18:08.280  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 17:18:08.280  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e8c8cbb removed from the list
,09-09 17:18:08.280  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 17:18:08.280  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:08.280  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:08.280  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:18:08.280  7319  7373 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c3dd54a removed from the list
,09-09 17:18:08.280  7319  7373 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 17:18:08.280  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-09 17:18:08.280  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 17:18:08.280  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-09 17:18:08.280  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:18:08.280  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:18:08.280  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:08.280  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:08.280  7319  7373 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@85b15d8 added. We now have 2 listener(s)
,09-09 17:18:08.290  1015  1127 E WifiNative-wlan0: do suspend false
,09-09 17:18:08.290  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-09 17:18:08.290  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:18:08.290  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:18:08.290  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:18:08.290  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c804d31 added. We now have 9 listener(s)
09-09 17:18:08.290  7319  7373 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:18:08.290  1015  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 17:18:08.290  1015  1127 D SecContentProvider2: mCursor = null
,09-09 17:18:08.290  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 17:18:08.290  1015  1126 D WifiP2pService: InactiveState{ what=143375 }
,09-09 17:18:08.290  1015  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-09 17:18:08.290  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:18:08.300  7319  7373 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:18:08.300  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:08.300  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:18:08.300  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:18:08.300  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:18:08.300  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:18:08.300  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:18:08.300  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:18:08.310  7319  7373 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 17:18:08.310  7319  7373 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 17:18:08.310  7319  7373 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:18:08.310  7319  7373 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ded3997 added. We now have 3 listener(s)
,09-09 17:18:08.310  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:18:08.310  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:18:08.310  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-09 17:18:08.310  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:18:08.310  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:18:08.310  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:18:08.310  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2757b784 added. We now have 10 listener(s)
09-09 17:18:08.310  7319  7373 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:18:08.310  7319  7373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:18:08.310  7319  7373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 17:18:08.310  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 17:18:08.310  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:18:08.310  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 17:18:08.310  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 17:18:08.320  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 17:18:08.320  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 17:18:08.320  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-09 17:18:08.320  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 17:18:08.320  7319  7373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 17:18:08.320  3225  7941 D BtGatt.GattService: registerClient() - UUID=fbaf8106-2c69-4e59-9741-934425651cbf
,09-09 17:18:08.370  3225  3304 D BtGatt.GattService: onClientRegistered() - UUID=fbaf8106-2c69-4e59-9741-934425651cbf, clientIf=6
,09-09 17:18:08.370  7319  7327 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-09 17:18:08.370  3225  3237 D BtGatt.GattService: start scan with filters
,09-09 17:18:08.370  3225  3351 D BtGatt.ScanManager: handling starting scan
,09-09 17:18:08.380  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 17:18:08.380  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 17:18:08.380  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 17:18:08.380  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 17:18:08.380  3225  3304 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-09 17:18:08.380  3225  3304 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 17:18:08.380  3225  3351 D BtGatt.ScanManager: allow scan with filters
09-09 17:18:08.380  3225  3351 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-09 17:18:08.380  3225  3351 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
,09-09 17:18:08.380  3225  3304 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-09 17:18:08.380  3225  3304 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:18:08.380  3225  3351 D BtGatt.ScanManager: Starting BLE batch scan
,09-09 17:18:08.380  3225  3351 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-09 17:18:08.380  7319  7373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 17:18:08.380  7319  7373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 17:18:08.380  7319  7319 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 17:18:08.380  3225  3304 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-09 17:18:08.390  3225  3304 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
09-09 17:18:08.390  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
,09-09 17:18:08.390  3225  3304 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-09 17:18:08.390  3225  3304 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:18:08.400  7319  7373 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-09 17:18:08.400  7319  7373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 17:18:08.400  7319  7373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 17:18:08.400  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:18:08.400  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 17:18:08.400  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-09 17:18:08.400  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-09 17:18:08.400  7319  7373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 17:18:08.400  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 17:18:08.400  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-09 17:18:08.400  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 17:18:08.410  3225  8017 D BtGatt.GattService: stopScan() - queue size =1
,09-09 17:18:08.410  3225  3351 D BtGatt.ScanManager: filter size is 1
,09-09 17:18:08.410  3225  3351 D BtGatt.ScanManager: delete FilterIndex - 6
,09-09 17:18:08.410  3225  3304 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-09 17:18:08.410  3225  3304 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:18:08.410  3225  3366 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-09 17:18:08.410  3225  3351 D BtGatt.ScanManager: stopping BLe Batch
,09-09 17:18:08.410  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:18:08.410  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 17:18:08.410  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 17:18:08.410  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 17:18:08.410  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 17:18:08.410  7319  7373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 17:18:08.410  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 17:18:08.410  7319  7373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 17:18:08.410  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 17:18:08.420  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:18:08.420  3225  3304 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-09 17:18:08.420  3225  3304 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:18:08.420  3225  3351 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-09 17:18:08.420  3225  3304 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-09 17:18:08.420  3225  3304 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:18:08.420  7319  7319 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:18:08.420  7319  7319 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:18:08.420  7319  7319 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 17:18:08.420  7319  7373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 17:18:08.420  7319  7373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:18:08.420  7319  7373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:18:08.420  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:18:08.420  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:08.420  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:18:08.420  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:18:08.420  7319  7373 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@85b15d8 removed from the list
09-09 17:18:08.420  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:08.420  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c804d31 removed from the list
09-09 17:18:08.420  7319  7373 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:18:08.420  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:18:08.420  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:08.420  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:18:08.430  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 17:18:08.430  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:18:08.430  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:08.430  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c804d31 not in the list
09-09 17:18:08.430  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:08.430  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:18:08.430  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 17:18:08.430  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 17:18:08.430  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 17:18:08.430  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2757b784 removed from the list
,09-09 17:18:08.430  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:18:08.430  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:18:08.430  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:18:08.430  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 17:18:08.430  7319  7373 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ded3997 removed from the list
09-09 17:18:08.430  7319  7373 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 17:18:08.430  7319  7373 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c5ac7f0 added. We now have 2 listener(s)
,09-09 17:18:08.430  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-09 17:18:08.440  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 17:18:08.440  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 17:18:08.440  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:18:08.440  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f327169 added. We now have 9 listener(s)
,09-09 17:18:08.440  7319  7373 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 17:18:08.440  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 17:18:08.440  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:18:08.450  7319  7373 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:18:08.450  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:08.450  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:18:08.450  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:18:08.450  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:18:08.450  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:18:08.450  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:18:08.450  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:18:08.450  7319  7373 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 17:18:08.450  7319  7373 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 17:18:08.450  7319  7373 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:18:08.450  7319  7373 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e37c48f added. We now have 3 listener(s)
,09-09 17:18:08.450  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:18:08.450  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:18:08.450  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-09 17:18:08.450  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:18:08.450  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:18:08.450  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:18:08.450  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@313c731c added. We now have 10 listener(s)
09-09 17:18:08.450  7319  7373 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:18:08.450  7319  7373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 17:18:08.450  7319  7373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:18:08.450  7319  7373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 17:18:08.450  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 17:18:08.450  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:18:08.450  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 17:18:08.460  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 17:18:08.460  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 17:18:08.460  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 17:18:08.470  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 17:18:08.470  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 17:18:08.470  7319  7373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 17:18:08.470  3225  3240 D BtGatt.GattService: registerClient() - UUID=96d1fa88-eeea-41a0-92f6-efee639ec62b
,09-09 17:18:08.500  8051  8051 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-09 17:18:08.500  8051  8051 I dhcpcd  : version 5.5.6 starting
,09-09 17:18:08.510  8051  8051 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-09 17:18:08.510  3225  3304 D BtGatt.GattService: onClientRegistered() - UUID=96d1fa88-eeea-41a0-92f6-efee639ec62b, clientIf=6
,09-09 17:18:08.510  7319  7328 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-09 17:18:08.510  3225  3380 D BtGatt.GattService: start scan with filters
09-09 17:18:08.510  3225  3351 D BtGatt.ScanManager: handling starting scan
09-09 17:18:08.510  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 17:18:08.510  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 17:18:08.510  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 17:18:08.510  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-09 17:18:08.510  3225  3304 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-09 17:18:08.510  3225  3304 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 17:18:08.510  3225  3351 D BtGatt.ScanManager: allow scan with filters
09-09 17:18:08.510  3225  3351 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-09 17:18:08.510  3225  3351 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
,09-09 17:18:08.520  3225  3304 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15,
09-09 17:18:08.520  3225  3304 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 17:18:08.520  3225  3351 D BtGatt.ScanManager: Starting BLE batch scan
09-09 17:18:08.520  3225  3351 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-09 17:18:08.520  3225  3304 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-09 17:18:08.520  3225  3304 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 17:18:08.530  7319  7373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 17:18:08.530  7319  7373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 17:18:08.530  7319  7319 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 17:18:08.530  3225  3304 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
09-09 17:18:08.530  3225  3304 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 17:18:08.530  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 17:18:08.530  7319  7373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:18:08.530  7319  7373 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-09 17:18:08.530  7319  7373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:18:08.530  7319  7373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:18:08.530  7319  7373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:18:08.530  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:18:08.530  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:08.530  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 17:18:08.530  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:18:08.530  7319  7373 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c5ac7f0 removed from the list
09-09 17:18:08.530  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:08.530  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f327169 removed from the list
09-09 17:18:08.530  7319  7373 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:18:08.530  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 17:18:08.540  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:08.540  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-09 17:18:08.540  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:08.540  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 17:18:08.540  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:18:08.540  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 17:18:08.540  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:08.540  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f327169 not in the list
09-09 17:18:08.540  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 17:18:08.540  7319  7373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 17:18:08.540  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 17:18:08.540  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 17:18:08.540  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 17:18:08.540  3225  7941 D BtGatt.GattService: stopScan() - queue size =1
,09-09 17:18:08.540  3225  3237 D BtGatt.GattService: unregisterClient() - clientIf=6
09-09 17:18:08.540  3225  3351 D BtGatt.ScanManager: filter size is 1
,09-09 17:18:08.540  3225  3351 D BtGatt.ScanManager: delete FilterIndex - 7
,09-09 17:18:08.550  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:18:08.550  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 17:18:08.550  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 17:18:08.550  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 17:18:08.550  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 17:18:08.550  3225  3304 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-09 17:18:08.550  3225  3304 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 17:18:08.550  3225  3351 D BtGatt.ScanManager: stopping BLe Batch
,09-09 17:18:08.550  7319  7373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 17:18:08.550  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
,09-09 17:18:08.550  7319  7373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
,09-09 17:18:08.550  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
09-09 17:18:08.550  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:08.550  7319  7319 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:18:08.550  7319  7319 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:18:08.550  7319  7319 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 17:18:08.550  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:18:08.550  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
,09-09 17:18:08.550  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:08.550  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@313c731c removed from the list
09-09 17:18:08.550  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:18:08.550  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:08.550  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:18:08.550  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:18:08.550  7319  7373 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e37c48f removed from the list
09-09 17:18:08.550  7319  7373 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:18:08.550  7319  7373 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@132ba508 added. We now have 2 listener(s)
09-09 17:18:08.550  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-09 17:18:08.550  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:18:08.550  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:18:08.550  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
09-09 17:18:08.550  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@220de4a1 added. We now have 9 listener(s)
09-09 17:18:08.550  7319  7373 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:18:08.550  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 17:18:08.560  3225  3304 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-09 17:18:08.560  3225  3304 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 17:18:08.560  3225  3351 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-09 17:18:08.560  3225  3304 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-09 17:18:08.560  3225  3304 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 17:18:08.560  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:18:08.570  7319  7373 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:18:08.570  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:08.570  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:18:08.570  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:18:08.570  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:18:08.570  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:18:08.570  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:18:08.570  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:18:08.570  8051  8051 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
09-09 17:18:08.570  8051  8051 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-09 17:18:08.570  8051  8051 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
09-09 17:18:08.570  8051  8051 I dhcpcd  : bssid match
,09-09 17:18:08.570  8051  8051 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,09-09 17:18:08.570  7319  7373 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:18:08.570  7319  7373 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 17:18:08.570  7319  7373 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:18:08.570  7319  7373 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16f9b687 added. We now have 3 listener(s)
,09-09 17:18:08.570  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:18:08.570  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:18:08.580  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-09 17:18:08.580  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 17:18:08.580  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 17:18:08.580  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:18:08.580  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@115a09b4 added. We now have 10 listener(s)
,09-09 17:18:08.580  7319  7373 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:18:08.580  7319  7373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 17:18:08.580  7319  7373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 17:18:08.580  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-09 17:18:08.580  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:18:08.580  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 17:18:08.580  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 17:18:08.590  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 17:18:08.590  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
,09-09 17:18:08.590  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 17:18:08.590  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-09 17:18:08.590  7319  7373 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 17:18:08.590  3225  3240 D BtGatt.GattService: registerClient() - UUID=d7b6ae24-02fa-462a-9a2e-301639a97ccb
,09-09 17:18:08.630  3225  3304 D BtGatt.GattService: onClientRegistered() - UUID=d7b6ae24-02fa-462a-9a2e-301639a97ccb, clientIf=6
,09-09 17:18:08.640  7319  7366 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-09 17:18:08.640  3225  3380 D BtGatt.GattService: start scan with filters
,09-09 17:18:08.640  3225  3351 D BtGatt.ScanManager: handling starting scan
,09-09 17:18:08.640  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 17:18:08.640  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 17:18:08.640  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 17:18:08.640  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 17:18:08.640  3225  3304 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-09 17:18:08.640  3225  3304 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:18:08.640  3225  3351 D BtGatt.ScanManager: allow scan with filters
,09-09 17:18:08.640  3225  3351 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-09 17:18:08.640  3225  3351 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
,09-09 17:18:08.640  3225  3304 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-09 17:18:08.640  3225  3304 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:18:08.650  3225  3351 D BtGatt.ScanManager: Starting BLE batch scan
,09-09 17:18:08.650  3225  3351 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-09 17:18:08.650  3225  3304 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-09 17:18:08.650  3225  3304 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:18:08.650  7319  7373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 17:18:08.650  7319  7319 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 17:18:08.650  3225  3304 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-09 17:18:08.650  7319  7373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 17:18:08.650  3225  3304 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:18:08.660  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 17:18:08.660  7319  7373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 17:18:08.660  7319  7373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 17:18:08.660  7319  7373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 17:18:08.660  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 17:18:08.660  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:18:08.660  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 17:18:08.660  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:18:08.660  7319  7373 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@132ba508 removed from the list
,09-09 17:18:08.660  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 17:18:08.660  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@220de4a1 removed from the list
,09-09 17:18:08.660  7319  7373 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:18:08.670  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 17:18:08.670  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:18:08.670  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,09-09 17:18:08.670  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:18:08.670  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 17:18:08.670  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 17:18:08.670  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 17:18:08.670  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 17:18:08.670  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@220de4a1 not in the list
09-09 17:18:08.670  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-09 17:18:08.670  7319  7373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 17:18:08.670  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 17:18:08.670  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-09 17:18:08.670  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 17:18:08.670  3225  3240 D BtGatt.GattService: stopScan() - queue size =1,
,09-09 17:18:08.670  3225  3351 D BtGatt.ScanManager: filter size is 1
,09-09 17:18:08.680  3225  3351 D BtGatt.ScanManager: delete FilterIndex - 8,
09-09 17:18:08.680  3225  3380 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-09 17:18:08.680  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:18:08.680  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 17:18:08.680  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 17:18:08.680  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 17:18:08.680  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 17:18:08.680  3225  3304 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-09 17:18:08.680  3225  3304 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:18:08.680  3225  3351 D BtGatt.ScanManager: stopping BLe Batch
09-09 17:18:08.680  7319  7373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
09-09 17:18:08.680  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 17:18:08.680  7319  7373 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 17:18:08.680  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 17:18:08.680  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:18:08.680  7319  7319 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:18:08.680  7319  7319 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:18:08.680  7319  7319 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 17:18:08.680  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:18:08.680  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:18:08.680  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:08.680  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@115a09b4 removed from the list
09-09 17:18:08.680  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:18:08.680  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:08.680  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:08.680  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:18:08.680  7319  7373 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16f9b687 removed from the list
,09-09 17:18:08.680  7319  7373 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 17:18:08.680  7319  7373 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a680d20 added. We now have 2 listener(s)
09-09 17:18:08.680  3225  3304 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-09 17:18:08.680  3225  3304 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 17:18:08.680  3225  3351 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-09 17:18:08.690  3225  3304 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-09 17:18:08.690  3225  3304 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:18:08.690  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-09 17:18:08.690  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:18:08.690  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 17:18:08.690  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:18:08.690  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@190d86d9 added. We now have 9 listener(s)
09-09 17:18:08.690  7319  7373 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 17:18:08.690  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 17:18:08.690  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:18:08.700  7319  7373 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:18:08.700  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:08.700  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:18:08.700  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:18:08.700  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:18:08.700  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:18:08.700  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:18:08.700  7319  7373 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:18:08.700  7319  7373 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 17:18:08.700  7319  7373 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 17:18:08.700  7319  7373 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:18:08.700  7319  7373 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4d8ef7f added. We now have 3 listener(s)
,09-09 17:18:08.700  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-09 17:18:08.700  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:18:08.700  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-09 17:18:08.700  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:18:08.700  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:18:08.700  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 17:18:08.700  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2490db4c added. We now have 10 listener(s)
,09-09 17:18:08.700  7319  7373 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:18:08.700  7319  7373 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:18:08.700  7319  7373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:18:08.700  7319  7373 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 17:18:08.700  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 17:18:08.700  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:08.700  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 17:18:08.700  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:18:08.700  7319  7373 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a680d20 removed from the list
,09-09 17:18:08.700  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:08.700  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@190d86d9 removed from the list
,09-09 17:18:08.700  7319  7373 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:18:08.700  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:18:08.700  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:08.700  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:18:08.700  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:18:08.700  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 17:18:08.700  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:08.700  7319  7373 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@190d86d9 not in the list
,09-09 17:18:08.700  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:08.700  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:08.710  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:18:08.710  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 17:18:08.710  7319  7373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:08.710  7319  7373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2490db4c removed from the list
,09-09 17:18:08.710  7319  7373 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:18:08.710  7319  7373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:08.710  7319  7373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-09 17:18:08.710  7319  7373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:18:08.710  7319  7373 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4d8ef7f removed from the list
,09-09 17:18:08.710  7319  7373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-09 17:18:08.710  7319  7373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-09 17:18:08.710  7319  7373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,09-09 17:18:08.710  7319  7373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:18:08.710  7319  7373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-09 17:18:08.710  7319  7373 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 17:18:08.710  7319  8059 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1504, name: My test thread name)
09-09 17:18:08.710  7319  8059 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1504, thread name: My test thread name)
09-09 17:18:08.710  7319  8059 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1504, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-09 17:18:08.710  7319  8060 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1506, name: My test thread name)
,09-09 17:18:08.710  7319  8060 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1506, thread name: My test thread name)
09-09 17:18:08.710  7319  8060 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1506, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-09 17:18:08.720  7319  7373 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-09 17:18:08.720  7319  7373 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-09 17:18:08.720  7319  7373 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-09 17:18:08.720  7319  7373 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-09 17:18:08.720  7319  7373 D com.test.thalitest.ThaliTestRunner: Total duration: 23327 ms
09-09 17:18:08.720  7319  7373 I jxcore-log: *Native tests were executed*
09-09 17:18:08.720  7319  7373 I jxcore-log: 
09-09 17:18:08.720  7319  7373 I jxcore-log: Total number of executed tests:  80
09-09 17:18:08.720  7319  7373 I jxcore-log: 
09-09 17:18:08.720  7319  7373 I jxcore-log: Number of passed tests:  80
09-09 17:18:08.720  7319  7373 I jxcore-log: 
09-09 17:18:08.720  7319  7373 I jxcore-log: Number of failed tests:  0
09-09 17:18:08.720  7319  7373 I jxcore-log: 
09-09 17:18:08.720  7319  7373 I jxcore-log: Number of ignored tests:  0
09-09 17:18:08.720  7319  7373 I jxcore-log: 
09-09 17:18:08.720  7319  7373 I jxcore-log: Total duration:  23327
09-09 17:18:08.720  7319  7373 I jxcore-log: 
09-09 17:18:08.720  7319  7373 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-09 17:18:08.720  7319  7373 I jxcore-log: 
09-09 17:18:08.720  7319  7373 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:18:08.720  7319  7373 I jxcore-log: 
,09-09 17:18:08.730  7319  7373 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:18:08.730  7319  7373 I jxcore-log: 
09-09 17:18:08.730  7319  7373 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:18:08.730  7319  7373 I jxcore-log: 
09-09 17:18:08.730  7319  7373 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:18:08.730  7319  7373 I jxcore-log: 
09-09 17:18:08.730  7319  7373 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:18:08.730  7319  7373 I jxcore-log: 
09-09 17:18:08.730  7319  7319 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-09 17:18:08.730  7319  7373 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:18:08.730  7319  7373 I jxcore-log: 
,09-09 17:18:08.730  7319  7373 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
09-09 17:18:08.730  7319  7373 I jxcore-log: 
09-09 17:18:08.730  7319  7373 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 17:18:08.730  7319  7373 I jxcore-log: 
09-09 17:18:08.740  7319  7373 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 17:18:08.740  7319  7373 I jxcore-log: 
09-09 17:18:08.740  7319  7373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 17:18:08.740  7319  7373 I jxcore-log: 
09-09 17:18:08.740  7319  7373 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 17:18:08.740  7319  7373 I jxcore-log: 
09-09 17:18:08.740  7319  7373 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 17:18:08.740  7319  7373 I jxcore-log: 
,09-09 17:18:08.740  7319  7373 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 17:18:08.740  7319  7373 I jxcore-log: 
09-09 17:18:08.740  7319  7373 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 17:18:08.740  7319  7373 I jxcore-log: 
,09-09 17:18:08.740  7319  7373 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 17:18:08.740  7319  7373 I jxcore-log: 
,09-09 17:18:08.740   287   287 E SMD     : DCD OFF
09-09 17:18:08.740  7319  7373 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 17:18:08.740  7319  7373 I jxcore-log: 
09-09 17:18:08.740  7319  7373 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 17:18:08.740  7319  7373 I jxcore-log: 
,09-09 17:18:08.740  7319  7373 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 17:18:08.740  7319  7373 I jxcore-log: 
09-09 17:18:08.740  7319  7373 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 17:18:08.740  7319  7373 I jxcore-log: 
09-09 17:18:08.740  7319  7373 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 17:18:08.740  7319  7373 I jxcore-log: 
,09-09 17:18:08.740  7319  7373 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 17:18:08.740  7319  7373 I jxcore-log: 
,09-09 17:18:08.740  7319  7373 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 17:18:08.740  7319  7373 I jxcore-log: 
,09-09 17:18:08.740  7319  7373 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 17:18:08.740  7319  7373 I jxcore-log: 
,09-09 17:18:08.740  7319  7373 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 17:18:08.740  7319  7373 I jxcore-log: 
09-09 17:18:08.740  7319  7373 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
,09-09 17:18:08.740  7319  7373 I jxcore-log: 
,09-09 17:18:08.750  7319  7373 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 17:18:08.750  7319  7373 I jxcore-log: 
,09-09 17:18:08.750  7319  7373 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 17:18:08.750  7319  7373 I jxcore-log: 
,09-09 17:18:08.770  8051  8051 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
,09-09 17:18:08.800  8051  8051 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds,
,09-09 17:18:08.920  7319  7319 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
09-09 17:18:08.920  7319  7373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 17:18:08.920  7319  7373 I jxcore-log: 
,09-09 17:18:08.990  8061  8061 D AndroidRuntime: ,
09-09 17:18:08.990  8061  8061 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-09 17:18:08.990  8061  8061 D AndroidRuntime: CheckJNI is OFF,
09-09 17:18:08.990  8061  8061 D AndroidRuntime: readGMSProperty: start
09-09 17:18:08.990  8061  8061 D AndroidRuntime: readGMSProperty: already setted!!
09-09 17:18:08.990  8061  8061 D AndroidRuntime: propertySet: couldn't set property (it is from app),
09-09 17:18:08.990  8061  8061 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-09 17:18:08.990  8061  8061 D AndroidRuntime: readGMSProperty: end
09-09 17:18:08.990  8061  8061 D AndroidRuntime: addProductProperty: start
,09-09 17:18:09.050  7319  7319 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
09-09 17:18:09.050  7319  7373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 17:18:09.050  7319  7373 I jxcore-log: ,
,09-09 17:18:09.100  1015  1127 E WifiNative-wlan0: do suspend true,
,09-09 17:18:09.120  1015  1126 D WifiP2pService: InactiveState{ what=143375 }
09-09 17:18:09.130  8061  8061 E AffinityControl: AffinityControl: registerfunction enter
09-09 17:18:09.120  1015  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
09-09 17:18:09.130  1015  1127 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-09 17:18:09.130  1015  1127 E WifiStateMachine: VerifyingLinkState enter
,09-09 17:18:09.130  1015  1129 E ConnectivityService: updateNetworkInfo()
,09-09 17:18:09.130  1015  1129 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
09-09 17:18:09.130  1015  1129 D ConnectivityService: Adding iface wlan0 to network 504
,09-09 17:18:09.140  1015  1144 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
09-09 17:18:09.140  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-09 17:18:09.140  1015  1144 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-09 17:18:09.140  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 17:18:09.140  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 17:18:09.140  1015  1144 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-09 17:18:09.140  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:09.140  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:09.140  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:09.140  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:18:09.140  1015  1144 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-09 17:18:09.140  1015  1144 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-09 17:18:09.150  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
,09-09 17:18:09.150  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-09 17:18:09.150  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
,09-09 17:18:09.150  1015  3283 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 17:18:09.150  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:09.150  1015  3283 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-09 17:18:09.150  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:09.150  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:09.150  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:09.150  1015  3283 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:09.150  1015  3283 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:09.150  1015  3283 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-09 17:18:09.160  1605  1605 I Hs20UtilService: Starting #22
09-09 17:18:09.160  1605  1643 I Hs20UtilService: Message received 5007
09-09 17:18:09.160  8061  8061 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-09 17:18:09.160  4743  4743 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-09 17:18:09.160  4743  4743 I NearbySettings: MountReceiver.onReceive - Keep current state
09-09 17:18:09.160  1015  1127 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,09-09 17:18:09.170  1015  1129 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,09-09 17:18:09.170  1015  1129 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,09-09 17:18:09.170  1015  1129 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,09-09 17:18:09.170  1015  1129 E ConnectivityService: Unexpected mtu value: 0, wlan0,
09-09 17:18:09.170  1015  1129 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
09-09 17:18:09.170  1015  1129 D ConnectivityService: LTETest block dns file not exists
,09-09 17:18:09.180  1015  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:18:09.180  1015  1129 V NetworkStats: updateIfacesLocked()
09-09 17:18:09.180  1015  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 17:18:09.180  1015  1129 V NetworkStats: performPollLocked(flags=0x1)
09-09 17:18:09.180  1015  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 17:18:09.180  1015  1129 V NetworkStats: performPollLocked() took 4ms
09-09 17:18:09.180  1015  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:18:09.180  1015  1028 D PackageManager: START PACKAGE DELETE: observer{436908257}
09-09 17:18:09.180  1015  1028 D PackageManager: pkg{<packageName>}
09-09 17:18:09.180  1015  1028 D PackageManager: user{0}
09-09 17:18:09.180  1015  1028 D PackageManager: caller{2000}
09-09 17:18:09.180  1015  1028 D PackageManager: flags{2}
09-09 17:18:09.180  1015  1028 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-09 17:18:09.180  1015  1028 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
,09-09 17:18:09.180  1015  1028 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-09 17:18:09.180  1015  1127 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-09 17:18:09.180  7319  7319 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-09 17:18:09.180  1015  1028 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-09 17:18:09.180  1015  1028 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-09 17:18:09.180  7319  7373 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 17:18:09.180  7319  7373 I jxcore-log: 
,09-09 17:18:09.180  1015  1127 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-09 17:18:09.190  1015  1129 E ConnectivityService: updateNetworkInfo(),
09-09 17:18:09.190  1015  1129 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
09-09 17:18:09.190  1015  1129 E ConnectivityService: updateNetworkInfo(),
09-09 17:18:09.190  1015  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 17:18:09.190  1015  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:18:09.190  1015  1129 V NetworkStats: updateIfacesLocked()
09-09 17:18:09.190  1015  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 17:18:09.190  1015  1129 V NetworkStats: performPollLocked(flags=0x1)
09-09 17:18:09.190  1015  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-09 17:18:09.190  1015  1057 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,09-09 17:18:09.190  1015  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
09-09 17:18:09.190  1015  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-09 17:18:09.190  1015  1057 D ApplicationPolicy: getApplicationUninstallationEnabled
09-09 17:18:09.190  1015  1057 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-09 17:18:09.190  1015  1129 V NetworkStats: performPollLocked() took 3ms
09-09 17:18:09.190  1015  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:18:09.190  1015  1129 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
09-09 17:18:09.190  1015  8047 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:18:09.190  1015  1129 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
09-09 17:18:09.190  1015  8047 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
09-09 17:18:09.190  1015  8047 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:18:09.190  1015  8047 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,09-09 17:18:09.190  1015  8047 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 17:18:09.190   277   962 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-09 17:18:09.190   277   962 D Netd    : getNetworkForDns: using netid 504 for uid 1000
09-09 17:18:09.190  1015  1129 D ConnectivityService:    accepting network in place of null
09-09 17:18:09.190  1015  1127 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-09 17:18:09.190  1015  1126 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-09 17:18:09.190  1478  1478 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-09 17:18:09.190  1478  1478 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:18:09.190  1015  1129 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-09 17:18:09.190  1015  1057 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
09-09 17:18:09.190  1015  1129 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
09-09 17:18:09.200  1015  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 17:18:09.200  1015  1129 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
09-09 17:18:09.200  1015  1129 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
09-09 17:18:09.200  1015  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-09 17:18:09.200  1178  1677 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-09 17:18:09.230  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-09 17:18:09.240  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-09 17:18:09.240  1015  1015 I WifiTrafficPoller: mBoosterFLAG : 0
09-09 17:18:09.240  1015  1015 I WifiTrafficPoller: current booster mode : FullMode
,09-09 17:18:09.240  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-09 17:18:09.240  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 17:18:09.240  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 17:18:09.240  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:09.240  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:09.240  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:09.240  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:18:09.240  1015  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:18:09.240  1015  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:18:09.240  1015  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:18:09.250  1015  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:18:09.250  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 17:18:09.250  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-09 17:18:09.250  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:18:09.250  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:18:09.250  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:18:09.250  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:09.250  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-09 17:18:09.250  1015  1130 D Tethering: MasterInitialState.processMessage what=3
,09-09 17:18:09.250  1015  1124 V NetworkStats: updateIfacesLocked()
09-09 17:18:09.250  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit,
09-09 17:18:09.250  1015  1124 V NetworkStats: performPollLocked(flags=0x1)
09-09 17:18:09.250  1015  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 17:18:09.250  1015  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 17:18:09.250  1015  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:18:09.250  1015  1124 V NetworkStats: performPollLocked() took 3ms
09-09 17:18:09.250  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:18:09.250  1015  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:18:09.250  1015  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:18:09.260  1015  1125 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,09-09 17:18:09.260  1015  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:18:09.300  1015  8047 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-09 17:18:09.330  1178  1178 D StatusBar.NetworkController: EthernetConnected: false
09-09 17:18:09.330  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-09 17:18:09.330  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-09 17:18:09.330  1178  1178 D StatusBar.NetworkController: updateDataNetType()
,09-09 17:18:09.330  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-09 17:18:09.330  1178  1178 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-09 17:18:09.340  1178  1178 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-09 17:18:09.340  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 20 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
09-09 17:18:09.340  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
09-09 17:18:09.340  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
09-09 17:18:09.340  1015  1042 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
,09-09 17:18:09.340  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 17:18:09.340  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-09 17:18:09.340  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:09.340  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:09.340  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:09.340  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:18:09.340  1015  1042 I ActivityManager: Killing 7319:com.test.thalitest/u0a170 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-09 17:18:09.340  1015  1042 I ActivityManager:   Force finishing activity ActivityRecord{2bde6250 u0 com.test.thalitest/.MainActivity t163}
,09-09 17:18:09.350  1015  1346 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 17:18:09.350  1015  1346 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 17:18:09.350  1015  1346 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:18:09.350  1015  1346 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:09.350  1015  1346 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 17:18:09.350  1015  8047 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 15:18:09 GMT], X-Android-Received-Millis=[1473434289367], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473434289335]}
09-09 17:18:09.350  1015  8047 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-09 17:18:09.350  1015  8047 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,09-09 17:18:09.350  1015  1129 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
09-09 17:18:09.350  1015  1129 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
09-09 17:18:09.350  1015  1129 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
09-09 17:18:09.350  1015  1129 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,09-09 17:18:09.360  1015  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-09 17:18:09.360  1605  1605 I Hs20UtilService: Starting #23
09-09 17:18:09.360  1178  1677 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-09 17:18:09.360  1605  1643 I Hs20UtilService: Message received 5007
,09-09 17:18:09.360  1015  1042 D InputDispatcher: Focus left window: 7319
,09-09 17:18:09.360   257  1038 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
,09-09 17:18:09.360   257   443 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,09-09 17:18:09.380  1015  1042 D InputDispatcher: Focused application released
,09-09 17:18:09.380  1015  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-09 17:18:09.380  1015  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-09 17:18:09.380  1015  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:18:09.380  1015  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:18:09.390  1015  1057 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,09-09 17:18:09.390  4743  4743 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-09 17:18:09.390  4743  4743 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 17:18:09.390  4743  4743 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,09-09 17:18:09.390  1015  1057 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,09-09 17:18:09.400  4743  4743 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-09 17:18:09.400  4743  4743 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
09-09 17:18:09.400  4743  4743 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-09 17:18:09.410  1178  1178 D StatusBar.NetworkController: EthernetConnected: false
,09-09 17:18:09.410  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): 0
,09-09 17:18:09.410  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-09 17:18:09.410  1178  1178 D StatusBar.NetworkController: updateDataNetType()
,09-09 17:18:09.420  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-09 17:18:09.420  1178  1178 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-09 17:18:09.420  1178  1178 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,09-09 17:18:09.420  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 20 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
,09-09 17:18:09.420  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
,09-09 17:18:09.420  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,09-09 17:18:09.420  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 17:18:09.420  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-09 17:18:09.420  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:09.420  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:09.420  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:09.420  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:18:09.440  1015  1098 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-09 17:18:09.440  2820  2820 I art     : Explicit concurrent mark sweep GC freed 16616(991KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 815us total 45.163ms
,09-09 17:18:09.450  2019  2019 E SamsungIME: mOCRHelper is null
,09-09 17:18:09.450  1681  1914 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-09 17:18:09.470  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:18:09.470  1015  1124 V NetworkStats: removeUidsLocked() for UIDs [10170]
09-09 17:18:09.470  1015  1124 V NetworkStats: performPollLocked(flags=0x3)
,09-09 17:18:09.470  1015  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 17:18:09.470  1015  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 17:18:09.480  1015  1124 V NetworkStats: performPollLocked() took 9ms
09-09 17:18:09.480  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:18:09.490  1461  1461 D PersonaManager: isKioskContainerExistOnDevice
,09-09 17:18:09.490  1461  1461 D RegisteredServicesCache: empty dynamic service
,09-09 17:18:09.500  1015  1346 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 17:18:09.500  1015  1346 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 17:18:09.500  1015  1015 D RCPManagerService: PackageReceiver onReceive()
09-09 17:18:09.500  1015  1346 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:09.500  1015  1346 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:09.500  1015  1346 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 17:18:09.500  1605  1605 I Hs20UtilService: Starting #24
,09-09 17:18:09.500  1015  1015 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,09-09 17:18:09.510  1605  1643 I Hs20UtilService: Message received 5007
,09-09 17:18:09.510  4743  4743 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-09 17:18:09.510  4743  4743 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-09 17:18:09.510  1015  1015 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,09-09 17:18:09.510  1015  1015 I OTPFW   : PackageRemovalReceiver::onReceive Enter
09-09 17:18:09.510  1015  1015 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,09-09 17:18:09.520  1015  1346 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,09-09 17:18:09.520  1015  1028 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
09-09 17:18:09.520  1015  1028 D SecContentProvider2: mCursor = null
,09-09 17:18:09.520  1015  1466 D SecContentProvider2: uri = 15 selection = getToastGravity
09-09 17:18:09.520  1015  1466 D SecContentProvider2: mCursor = null
,09-09 17:18:09.520  1461  1461 D RegisteredComponentCache: Collect Tech packages for Knox
,09-09 17:18:09.520  1461  1461 D PersonaManager: isKioskContainerExistOnDevice
09-09 17:18:09.530  1015  1504 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
,09-09 17:18:09.530  1015  1504 D SecContentProvider2: mCursor = null
,09-09 17:18:09.530  1015  3280 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
09-09 17:18:09.530  1015  3280 D SecContentProvider2: mCursor = null
,09-09 17:18:09.530  1015  1015 I OTPFW   : ProvisionData::getAllEntries Enter
,09-09 17:18:09.530  1015  1015 E OTPFW   : ProvisionData::getAllEntries Table is empty
,09-09 17:18:09.530  1015  1135 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,09-09 17:18:09.530  1015  1135 D SecContentProvider2: mCursor = null
,09-09 17:18:09.530  1015  1244 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState,
09-09 17:18:09.540  1015  1244 D SecContentProvider2: mCursor = null
,09-09 17:18:09.550  1015  1505 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-09 17:18:09.550  2804  2804 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Sep 09 17:18:09 GMT+02:00 2016
,09-09 17:18:09.560  1015  1505 D SecContentProvider2: mCursor = null
,09-09 17:18:09.560  1015  1244 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-09 17:18:09.560  1015  1244 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-09 17:18:09.560  1015  1244 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:18:09.560  1015  1041 E libprocessgroup: failed to kill 1 processes for processgroup 7319
,09-09 17:18:09.570  1015  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:18:09.570  1015  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:18:09.570  1015  1244 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 17:18:09.570  1015  1244 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-09 17:18:09.570   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,09-09 17:18:09.580  1015  1027 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015
,09-09 17:18:09.580  2804  2804 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-09 17:18:09.590  1015  1135 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=22, mSplitNum[2]=32, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=42
,09-09 17:18:09.590  1015  1135 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,09-09 17:18:09.590  1015  1135 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,09-09 17:18:09.590  1015  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:09.590  1015  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:09.590  1015  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:09.590  1015  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:18:09.600  1178  1178 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! ,
,09-09 17:18:09.600  8099  8099 E Zygote  : MountEmulatedStorage(),
09-09 17:18:09.600  8099  8099 E Zygote  : v2
,09-09 17:18:09.610  8099  8099 I libpersona: KNOX_SDCARD checking this for 10090
,09-09 17:18:09.610  8099  8099 I libpersona: KNOX_SDCARD not a persona
,09-09 17:18:09.610  1015  1057 I art     : Explicit concurrent mark sweep GC freed 64201(4MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 23MB/35MB, paused 7.078ms total 205.079ms
,09-09 17:18:09.610  1015  1135 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8099 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
09-09 17:18:09.610  1015  1025 I art     : WaitForGcToComplete blocked for 83.373ms for cause HeapTrim
09-09 17:18:09.610  8099  8099 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 17:18:09.620  2804  2804 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-09 17:18:09.620  8099  8099 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 17:18:09.620  8099  8099 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 17:18:09.620  1015  1042 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,09-09 17:18:09.620  1015  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:18:09.620  1015  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:09.620  1015  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:09.620  1015  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:18:09.640  2804  2804 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-09 17:18:09.640  8111  8111 E Zygote  : MountEmulatedStorage()
09-09 17:18:09.640  8111  8111 E Zygote  : v2
09-09 17:18:09.640  8111  8111 I libpersona: KNOX_SDCARD checking this for 10052
09-09 17:18:09.640  8111  8111 I libpersona: KNOX_SDCARD not a persona
,09-09 17:18:09.650  8111  8111 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 17:18:09.650  8111  8111 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 17:18:09.650  8111  8111 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-09 17:18:09.650  1015  1042 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=8111 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,09-09 17:18:09.650  1015  1042 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
09-09 17:18:09.650  1015  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:09.650  1015  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:09.650  1015  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:09.650  1015  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:18:09.660  2804  2804 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-09 17:18:09.660  2804  8098 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-09 17:18:09.660  2804  8098 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,09-09 17:18:09.660  2804  8098 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,09-09 17:18:09.670  8099  8099 D TimaKeyStoreProvider: TimaSignature is unavailable,
,09-09 17:18:09.670  8099  8099 D ActivityThread: Added TimaKeyStore provider
,09-09 17:18:09.670  8126  8126 E Zygote  : MountEmulatedStorage()
09-09 17:18:09.670  8126  8126 I libpersona: KNOX_SDCARD checking this for 10098
09-09 17:18:09.670  8126  8126 E Zygote  : v2
09-09 17:18:09.670  8126  8126 I libpersona: KNOX_SDCARD not a persona
09-09 17:18:09.670  8126  8126 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 17:18:09.680  1015  1042 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=8126 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,09-09 17:18:09.680  1015  1346 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
09-09 17:18:09.680  1015  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:09.680  1015  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:09.680  1015  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:09.680  1015  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:09.680  8126  8126 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 17:18:09.680  2804  8098 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,09-09 17:18:09.680  8126  8126 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 17:18:09.700  8111  8111 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:18:09.700  1015  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-09 17:18:09.700  8111  8111 D ActivityThread: Added TimaKeyStore provider
,09-09 17:18:09.710  8141  8141 E Zygote  : MountEmulatedStorage()
09-09 17:18:09.710  8141  8141 I libpersona: KNOX_SDCARD checking this for 10032
09-09 17:18:09.710  8141  8141 E Zygote  : v2
09-09 17:18:09.710  8141  8141 I libpersona: KNOX_SDCARD not a persona
09-09 17:18:09.710  8141  8141 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 17:18:09.710  1015  1346 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=8141 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 17:18:09.710  8126  8126 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 17:18:09.710  8126  8126 D ActivityThread: Added TimaKeyStore provider
,09-09 17:18:09.710  8141  8141 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 17:18:09.720  8141  8141 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-09 17:18:09.760  8141  8141 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:18:09.760  8141  8141 D ActivityThread: Added TimaKeyStore provider
,09-09 17:18:09.760  2804  8098 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,09-09 17:18:09.760  1015  1057 D PackageManager: delete codoeFile: 
,09-09 17:18:09.770  8099  8099 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,09-09 17:18:09.780  8099  8099 D elm:15121: ELMEngine.ELMEngine( context ).
,09-09 17:18:09.780  8099  8099 D elm:15121: MDMBridge.setEnterpriseBridge(),
09-09 17:18:09.780  1015  1135 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
09-09 17:18:09.780  1015  1135 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,09-09 17:18:09.780  1015  1135 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:18:09.780  1015  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:09.780  1015  1057 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
09-09 17:18:09.780  1015  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,09-09 17:18:09.780  8099  8099 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,09-09 17:18:09.790  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,09-09 17:18:09.800  8099  8099 D elm:15121: ElmAgentService : onCreate()
,09-09 17:18:09.800  8099  8160 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
09-09 17:18:09.800  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:09.800  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:09.800  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:09.800  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:09.800  8099  8160 D elm:15121: MainReceiver.listeningToPackageRemoved()
09-09 17:18:09.800  8099  8160 D elm:15121: MDMBridge.getInstance()
09-09 17:18:09.800  8099  8160 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,09-09 17:18:09.800  8099  8160 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,09-09 17:18:09.800  1015  1015 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-09 17:18:09.810  1015  1015 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-09 17:18:09.810  1015  1057 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,09-09 17:18:09.810  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-09 17:18:09.810  1015  1015 V EnterpriseBillingPolicy: uID is 10170
09-09 17:18:09.810  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
09-09 17:18:09.810  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
09-09 17:18:09.810  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-09 17:18:09.810  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-09 17:18:09.810  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-09 17:18:09.810  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-09 17:18:09.810  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-09 17:18:09.810  8162  8162 E Zygote  : MountEmulatedStorage(),
09-09 17:18:09.810  8162  8162 E Zygote  : v2
,09-09 17:18:09.810  8162  8162 I libpersona: KNOX_SDCARD checking this for 1000
09-09 17:18:09.810  8162  8162 I libpersona: KNOX_SDCARD not a persona
,09-09 17:18:09.810  8162  8162 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-09 17:18:09.820  1015  1057 D PackageManager: result of delete: 1{436908257}
,09-09 17:18:09.820  8162  8162 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 17:18:09.820  8162  8162 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 17:18:09.820  2804  8098 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest,
,09-09 17:18:09.820  1015  1028 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=8162 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-09 17:18:09.820  1015  1028 I ActivityManager: Killing 7585:com.sec.android.soagent/u0a31 (adj 15): empty #21
09-09 17:18:09.830  1015  1015 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-09 17:18:09.830  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-09 17:18:09.830  1015  1015 V EnterpriseBillingPolicy: uID is 10170
09-09 17:18:09.830  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
09-09 17:18:09.830  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
09-09 17:18:09.830  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
,09-09 17:18:09.830  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-09 17:18:09.830  1015  1161 D TaskPersister: removeObsoleteFile: deleting file=163_task.xml
09-09 17:18:09.830  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-09 17:18:09.830  1015  3377 D SSRM:bc : MSG_TYPE_APP_REMOVED::
09-09 17:18:09.830  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
09-09 17:18:09.830  2804  8098 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
09-09 17:18:09.830  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
09-09 17:18:09.830  1015  1015 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
,09-09 17:18:09.840  1015  1041 D EnterpriseDeviceManagerService: Package has changed for user 0
,09-09 17:18:09.840  1015  1041 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
09-09 17:18:09.840  1015  1041 W TextServicesManagerService: no available spell checker services found
,09-09 17:18:09.840  8099  8099 D elm:15121: ElmAgentService : onDestroy().
09-09 17:18:09.840  1015  1491 I ActivityManager: Killing 7618:com.osp.app.signin/u0a36 (adj 15): empty #21
,09-09 17:18:09.860  1015  3283 I ActivityManager: Killing 7640:com.android.chrome/u0a77 (adj 15): empty #21
,09-09 17:18:09.860  1015  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 17:18:09.860  8141  8174 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
09-09 17:18:09.860  8141  8174 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-09 17:18:09.870  2804  2804 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
09-09 17:18:09.870  8061  8061 D AndroidRuntime: Shutting down VM
,09-09 17:18:09.880  1015  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 17:18:09.880  8162  8162 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:18:09.880  8162  8162 D ActivityThread: Added TimaKeyStore provider
,09-09 17:18:09.890  1015  3280 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-09 17:18:09.890  1015  3280 D BatteryService: level:93, scale:100, status:2, health:2, present:true, voltage: 4180, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-09 17:18:09.890  1015  3280 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-09 17:18:09.890  1015  3280 D BatteryService: stay LED for charging
,09-09 17:18:09.900  8141  8174 D SPPClientService: PushLog.txt file is not deleted.
09-09 17:18:09.900  8141  8174 D SPPClientService: PushLog.txt file is not deleted.
09-09 17:18:09.900  8141  8174 D SPPClientService: ============PushLog. stop!
09-09 17:18:09.900  1015  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 17:18:09.900  1015  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 17:18:09.910  1015  1491 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
09-09 17:18:09.910  1015  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
,09-09 17:18:09.910  1015  1491 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:09.910  1015  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:09.910  1015  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,09-09 17:18:09.910  1015  3283 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-09 17:18:09.920  1015  3283 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-09 17:18:09.920  1015  3283 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:09.920  1015  3283 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:18:09.920  1015  3283 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,09-09 17:18:09.920  1015  1135 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-09 17:18:09.920  1015  1135 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-09 17:18:09.920  1015  1135 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:18:09.920  1015  1135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:18:09.920  1015  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,09-09 17:18:09.920  1015  1491 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,09-09 17:18:09.930  1015  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:18:09.930  1015  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:18:09.930  1015  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:09.930  1015  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:18:09.940  8181  8181 E Zygote  : MountEmulatedStorage()
,09-09 17:18:09.940  8181  8181 E Zygote  : v2
09-09 17:18:09.940  8181  8181 I libpersona: KNOX_SDCARD checking this for 10039
09-09 17:18:09.940  8181  8181 I libpersona: KNOX_SDCARD not a persona
,09-09 17:18:09.940  8181  8181 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 17:18:09.940  1015  1491 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=8181 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,09-09 17:18:09.950  8181  8181 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-09 17:18:09.950  8181  8181 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 17:18:09.970  7918  7918 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,09-09 17:18:09.970  8181  8181 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:18:09.970  8181  8181 D ActivityThread: Added TimaKeyStore provider
,09-09 17:18:09.990  1015  1041 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,09-09 17:18:09.990  1015  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 17:18:09.990  1015  1244 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
,09-09 17:18:09.990  1015  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 17:18:10.000  1015  1244 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:18:10.000  1015  1244 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:18:10.000  1015  1244 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:10.000  1015  1244 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:18:10.000  8181  8181 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-09 17:18:10.000  8181  8181 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 17:18:10.000  8181  8181 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 17:18:10.000  8181  8181 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
09-09 17:18:10.000  8181  8181 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-09 17:18:10.000  8181  8181 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-09 17:18:10.000  8181  8181 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-09 17:18:10.020  8197  8197 E Zygote  : MountEmulatedStorage(),
09-09 17:18:10.020  1015  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-09 17:18:10.020  1015  1244 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=8197 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-09 17:18:10.030  8197  8197 E Zygote  : v2
09-09 17:18:10.030  8197  8197 I libpersona: KNOX_SDCARD checking this for 1000
09-09 17:18:10.030  8197  8197 I libpersona: KNOX_SDCARD not a persona
09-09 17:18:10.030  8197  8197 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 17:18:10.030  8197  8197 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 17:18:10.030  8197  8197 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 17:18:10.050  8197  8197 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:18:10.050  8197  8197 D ActivityThread: Added TimaKeyStore provider
,09-09 17:18:10.070  7918  7918 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
,09-09 17:18:10.070  7918  7918 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
,09-09 17:18:10.080  8061  8061 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-09 17:18:10.080  7981  8196 E SQLiteLog: (10) POSIX Error : 11 SQLite Error : 3850
,09-09 17:18:10.080  7981  8196 E SQLiteLog: (10) POSIX Error : 11 SQLite Error : 3850
,09-09 17:18:10.090  7981  8196 E SQLiteLog: (10) POSIX Error : 11 SQLite Error : 3850
,09-09 17:18:10.090  7918  7918 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
09-09 17:18:10.090  7918  7918 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,09-09 17:18:10.090  7918  7918 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
09-09 17:18:10.090  7918  7918 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
09-09 17:18:10.090  7918  7918 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
09-09 17:18:10.090  7918  7918 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
09-09 17:18:10.090  7918  7918 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
,09-09 17:18:10.090  7918  7918 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
09-09 17:18:10.090  7918  7918 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
09-09 17:18:10.090  7918  7918 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,09-09 17:18:10.090  7918  7918 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
09-09 17:18:10.090  7918  7918 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
,09-09 17:18:10.090  7918  7918 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
09-09 17:18:10.090  7918  7918 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
09-09 17:18:10.090  7918  7918 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
,09-09 17:18:10.090  7981  8196 E SQLiteLog: (10) POSIX Error : 11 SQLite Error : 3850
09-09 17:18:10.090  7918  7918 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
09-09 17:18:10.090  7918  7918 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,09-09 17:18:10.090  7918  7918 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
09-09 17:18:10.090  7918  7918 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
09-09 17:18:10.090  7918  7918 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
,09-09 17:18:10.090  7918  7918 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
09-09 17:18:10.090  7918  7918 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
,09-09 17:18:10.090  1015  1041 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-09 17:18:10.090  1015  1041 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 17:18:10.090  1015  1041 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-09 17:18:10.100  1015  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 17:18:10.100  7981  8196 E SQLiteLog: (10) POSIX Error : 11 SQLite Error : 3850
,09-09 17:18:10.100  1698  1698 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,09-09 17:18:10.100  1698  1698 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-09 17:18:10.110  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-09 17:18:10.110  7981  7981 I art     : Explicit concurrent mark sweep GC freed 405(33KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 4MB/6MB, paused 866us total 49.940ms
,09-09 17:18:10.110  8197  8197 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
,09-09 17:18:10.120  1015  1015 I MotionRecognitionService: Plugged
,09-09 17:18:10.120  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,09-09 17:18:10.120  1015  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 17:18:10.120  1015  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 17:18:10.120  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-09 17:18:10.120  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-09 17:18:10.120  1015  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-09 17:18:10.120  1015  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-09 17:18:10.120  1015  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 17:18:10.130  1015  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-09 17:18:10.130  1015  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-09 17:18:10.130  1435  1435 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-09 17:18:10.130  1435  1435 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,09-09 17:18:10.140  1015  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-09 17:18:10.140  1015  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-09 17:18:10.140  1015  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 17:18:10.150  1015  1057 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-09 17:18:10.150  1015  1057 D PackageManager: userId{-1}
09-09 17:18:10.150  1015  1057 D PackageManager: andCode{true}
,09-09 17:18:10.150  1015  1491 D ActivityManager: startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
,09-09 17:18:10.150  3225  3225 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-09 17:18:10.150  3225  8008 D HeadsetStateMachine: Disconnected process message: 10
09-09 17:18:10.150  1015  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,09-09 17:18:10.150  1015  1491 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:18:10.150  1015  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 17:18:10.150  1015  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,09-09 17:18:10.160  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
09-09 17:18:10.160  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,09-09 17:18:10.160  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
09-09 17:18:10.160  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
09-09 17:18:10.160  1178  1178 D SViewCoverView: level :93 plugged : 2
,09-09 17:18:10.160  1015  1244 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,09-09 17:18:10.160  1015  1244 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:10.160  1015  1244 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:10.160  1015  1244 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:10.160  1015  1244 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:18:10.180  8221  8221 E Zygote  : MountEmulatedStorage()
,09-09 17:18:10.180  8221  8221 E Zygote  : v2
09-09 17:18:10.180  8221  8221 I libpersona: KNOX_SDCARD checking this for 1000
,09-09 17:18:10.180  8221  8221 I libpersona: KNOX_SDCARD not a persona
09-09 17:18:10.180  8221  8221 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 17:18:10.180  8221  8221 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 17:18:10.180  8221  8221 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 17:18:10.190  1015  1244 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=8221 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-09 17:18:10.190  1015  1135 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
09-09 17:18:10.190  1015  1135 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,09-09 17:18:10.190  1015  1135 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:10.190  1015  1135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:18:10.190  1015  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,09-09 17:18:10.200  1015  1057 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-09 17:18:10.210  1015  1129 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,09-09 17:18:10.210  1015  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:10.210  1015  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:10.210  1015  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:10.210  1015  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:18:10.220  1871  8233 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-09 17:18:10.220  1871  8233 D AccountUtils: Clearing selected account for com.test.thalitest
,09-09 17:18:10.230  8221  8221 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:18:10.230  8221  8221 D ActivityThread: Added TimaKeyStore provider
,09-09 17:18:10.240  8241  8241 E Zygote  : MountEmulatedStorage()
09-09 17:18:10.240  8241  8241 I libpersona: KNOX_SDCARD checking this for 10003
09-09 17:18:10.240  8241  8241 E Zygote  : v2
09-09 17:18:10.240  8241  8241 I libpersona: KNOX_SDCARD not a persona
,09-09 17:18:10.240  1015  1057 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8241 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
09-09 17:18:10.240  8241  8241 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 17:18:10.240  1015  3283 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast,
09-09 17:18:10.240  8241  8241 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 17:18:10.240  1015  3283 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:10.240  1015  3283 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:10.240  1015  3283 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:10.240  1015  3283 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:18:10.240  8241  8241 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 17:18:10.260  8255  8255 E Zygote  : MountEmulatedStorage(),
09-09 17:18:10.260  8255  8255 E Zygote  : v2
09-09 17:18:10.260  8255  8255 I libpersona: KNOX_SDCARD checking this for 1000
09-09 17:18:10.260  8255  8255 I libpersona: KNOX_SDCARD not a persona
,09-09 17:18:10.260  8255  8255 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 17:18:10.260  8255  8255 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-09 17:18:10.260  8241  8241 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 17:18:10.260  8255  8255 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
09-09 17:18:10.260  8241  8241 D ActivityThread: Added TimaKeyStore provider
,09-09 17:18:10.260  1015  3283 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=8255 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-09 17:18:10.280  7918  7918 D BluetoothAdapter: cancelDiscovery
,09-09 17:18:10.280  1015  1041 D UsbSettingsManager: clearDefaults: com.test.thalitest
,09-09 17:18:10.280  1015  3282 D LocationManagerService: getProviders()=[passive, gps]
,09-09 17:18:10.280  1015  1041 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,09-09 17:18:10.290   303   303 I art     : Explicit concurrent mark sweep GC freed 8736(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 635us total 29.415ms
,09-09 17:18:10.300  7981  8196 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,09-09 17:18:10.300  8255  8255 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:18:10.300  8255  8255 D ActivityThread: Added TimaKeyStore provider
,09-09 17:18:10.310  1015  1041 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-09 17:18:10.310   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 600us total 18.635ms
,09-09 17:18:10.320  1015  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 17:18:10.320  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:10.320  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:18:10.320  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:18:10.320  1015  1346 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,09-09 17:18:10.320  1015  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:10.320  1015  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:10.320  1015  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:10.320  1015  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:18:10.330  8221  8274 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_REMOVED
,09-09 17:18:10.340  8221  8274 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,09-09 17:18:10.340   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 583us total 22.315ms
,09-09 17:18:10.340  3225  3302 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-09 17:18:10.350  8181  8181 D NearbySource: Nearby Source Create!
09-09 17:18:10.350  8181  8181 D NearbyContext: Nearby Context Create!
,09-09 17:18:10.360  8277  8277 E Zygote  : MountEmulatedStorage(),
09-09 17:18:10.360  8277  8277 E Zygote  : v2
,09-09 17:18:10.360  8277  8277 I libpersona: KNOX_SDCARD checking this for 10014
09-09 17:18:10.360  8277  8277 I libpersona: KNOX_SDCARD not a persona
,09-09 17:18:10.370  8277  8277 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-09 17:18:10.370  8277  8277 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 17:18:10.370  1015  1346 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8277 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
,09-09 17:18:10.370  3225  8017 D BluetoothAdapterProperties: mDiscovering is false
,09-09 17:18:10.370  3225  8017 E BluetoothAdapterService: This is not a scanning status. cancelDiscovery() will be not called.
09-09 17:18:10.370  8277  8277 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-09 17:18:10.380  7918  7918 D BluetoothAdapter: cancelDiscovery = true
,09-09 17:18:10.380  7918  7918 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
,09-09 17:18:10.390  1015  1504 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-09 17:18:10.390  1015  1028 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 17:18:10.390  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService; callingUser = 0; userId(target) = 0
,09-09 17:18:10.390  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:18:10.390  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:18:10.390  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:18:10.400  7918  7918 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,09-09 17:18:10.400  7918  7918 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-09 17:18:10.410  1015  1505 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,09-09 17:18:10.410  1015  1505 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,09-09 17:18:10.410  1015  1505 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:18:10.410  1015  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 17:18:10.410  1015  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,09-09 17:18:10.410  8277  8277 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 17:18:10.420   256   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
09-09 17:18:10.420  8277  8277 D ActivityThread: Added TimaKeyStore provider
09-09 17:18:10.420   256   530 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 17:18:10.420  7786  7795 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
09-09 17:18:10.420  7786  7795 D BadgeProvider: sendNotify, [notify] : null
09-09 17:18:10.420  7786  7795 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
09-09 17:18:10.420  7786  7795 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-09 17:18:10.420  7786  7795 D BadgeProvider: update, [UpdateCount] : 1
,09-09 17:18:10.420  8221  8221 D AcmsService: Enter Oncreate
09-09 17:18:10.420  8221  8221 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-09 17:18:10.420  8221  8221 D AcmsService: creating AcmsCore
09-09 17:18:10.420  8221  8221 D AcmsCore: AcmsCore.getAcmsCore() - Enter
09-09 17:18:10.420  8221  8221 D AcmsCore: AcmsCore
,09-09 17:18:10.420  8181  8181 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,09-09 17:18:10.420  8181  8181 D SLinkSource: Samsung link source created
09-09 17:18:10.420  1015  1135 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:10.420  1015  1135 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
09-09 17:18:10.420  1015  1135 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
09-09 17:18:10.430  1015  1135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:18:10.430  1015  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,09-09 17:18:10.430  1871  8233 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,09-09 17:18:10.430  7918  7918 E SQLiteLog: (10) unixWrite() File Descriptor : 26 gets errno : 9
,09-09 17:18:10.440  7918  7918 E SQLiteDatabase: Error inserting timestamp=1473434290392 message=Predictor: service stopped by removePlaceCategories()
09-09 17:18:10.440  7918  7918 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
09-09 17:18:10.440  7918  7918 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
09-09 17:18:10.440  7918  7918 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
09-09 17:18:10.440  7918  7918 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
09-09 17:18:10.440  7918  7918 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
09-09 17:18:10.440  7918  7918 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
09-09 17:18:10.440  7918  7918 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
09-09 17:18:10.440  7918  7918 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:110)
09-09 17:18:10.440  7918  7918 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
09-09 17:18:10.440  7918  7918 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 17:18:10.440  7918  7918 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 17:18:10.440  7918  7918 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-09 17:18:10.440  7918  7918 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 17:18:10.440  7918  7918 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:18:10.440  7918  7918 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:18:10.440  7918  7918 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 17:18:10.440  7918  7918 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 17:18:10.440  7918  7918 E UserAnalysis: It failed to insert to dump_log table
,09-09 17:18:10.440  8221  8221 D AcmsCore: init
09-09 17:18:10.440  8221  8221 D AcmsCore: Looper handler is not null
09-09 17:18:10.440  8221  8221 D AcmsCore: Post to AcmsCoreHandler
09-09 17:18:10.440  8221  8221 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-09 17:18:10.440  8221  8221 D AcmsServiceMonitor: Incrementing - Counter value: 1
09-09 17:18:10.440  8221  8221 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>1
,09-09 17:18:10.440  8221  8293 D AcmsCertificateMngr: AcmsCertificateMngr
09-09 17:18:10.440  8221  8293 D AcmsRevocationMngr: AcmsRevocationMngr
09-09 17:18:10.440  1015  1027 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
09-09 17:18:10.440  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.util.PreferenceService; callingUser = 0; userId(target) = 0
,09-09 17:18:10.450  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:18:10.450  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 17:18:10.450  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:18:10.460  8221  8221 D AcmsService: onStartCommand
,09-09 17:18:10.460  1015  1504 I ActivityManager: Killing 7658:com.google.android.apps.magazines/u0a110 (adj 15): empty #21
,09-09 17:18:10.460  1015  3280 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 17:18:10.470  8221  8221 D AcmsService: Action: android.intent.action.PACKAGE_REMOVED
09-09 17:18:10.470  8221  8221 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 1
09-09 17:18:10.470  8221  8221 D AcmsServiceMonitor: Incrementing - Counter value: 2
09-09 17:18:10.470  8221  8221 D AcmsService: Incremented Counter Value : onStartCommand
,09-09 17:18:10.470  1015  3280 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:10.470  1015  3280 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:18:10.470  1015  3280 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-09 17:18:10.470  8255  8255 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,09-09 17:18:10.470  1871  8288 E SQLiteLog: (28) failed to open "/data/data/com.google.android.gms/databases/metrics.db" with flag (131138) and mode_t (0) due to error (30)
,09-09 17:18:10.470  8111  8179 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,09-09 17:18:10.470  1015  1027 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,09-09 17:18:10.480  1015  1028 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
09-09 17:18:10.480  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,09-09 17:18:10.480  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:10.480  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:10.480  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,09-09 17:18:10.480  8221  8293 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,09-09 17:18:10.480  1015  1505 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 17:18:10.480  1015  1505 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,09-09 17:18:10.480  8221  8293 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.app.mirrorlink/databases/pkgnamedb" with flag (131138) and mode_t (0) due to error (30)
,09-09 17:18:10.490  1015  1505 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:10.490  1015  1505 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:18:10.490  1015  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:18:10.490  8221  8293 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.app.mirrorlink/databases/pkgnamedb'.
09-09 17:18:10.490  8221  8293 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 17:18:10.490  8221  8293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 17:18:10.490  8221  8293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-09 17:18:10.490  8221  8293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-09 17:18:10.490  8221  8293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-09 17:18:10.490  8221  8293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-09 17:18:10.490  8221  8293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-09 17:18:10.490  8221  8293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-09 17:18:10.490  8221  8293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-09 17:18:10.490  8221  8293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-09 17:18:10.490  8221  8293 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-09 17:18:10.490  8221  8293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 17:18:10.490  8221  8293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 17:18:10.490  8221  8293 E SQLiteDatabase: 	at com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide.onCreate(AcmsPkgNameProvide.java:61)
09-09 17:18:10.490  8221  8293 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
09-09 17:18:10.490  8221  8293 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
09-09 17:18:10.490  8221  8293 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
09-09 17:18:10.490  8221  8293 E SQLiteDatabase: 	at android.app.ActivityThread.acquireProvider(ActivityThread.java:5338)
09-09 17:18:10.490  8221  8293 E SQLiteDatabase: 	at android.app.ContextImpl$ApplicationContentResolver.acquireUnstableProvider(ContextImpl.java:2966)
09-09 17:18:10.490  8221  8293 E SQLiteDatabase: 	at android.content.ContentResolver.acquireUnstableProvider(ContentResolver.java:1495)
09-09 17:18:10.490  8221  8293 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:473)
09-09 17:18:10.490  8221  8293 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:433)
09-09 17:18:10.490  8221  8293 E SQLiteDatabase: 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.checkIfPkgNameExists(AppEntryInterface.java:71)
09-09 17:18:10.490  8221  8293 E SQLiteDatabase: 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.<init>(AppEntryInterface.java:56)
09-09 17:18:10.490  8221  8293 E SQLiteDatabase: 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.getAppEntryInterface(AppEntryInterface.java:64)
09-09 17:18:10.490  8221  8293 E SQLiteDatabase: 	at com.samsung.android.mirrorlink.acms.manager.AcmsRevocationMngr.<init>(AcmsRevocationMngr.java:119)
09-09 17:18:10.490  8221  8293 E SQLiteDatabase: 	at com.samsung.android.mirrorlink.acms.manager.AcmsRevocationMngr.getAcmsRevocationMngr(AcmsRevocationMngr.java:129)
09-09 17:18:10.490  8221  8293 E SQLiteDatabase: 	at com.samsung.android.mirrorlink.acms.manager.AcmsCertificateMngr.<init>(AcmsCertificateMngr.java:94)
09-09 17:18:10.490  8221  8293 E SQLiteDatabase: 	at com.samsung.android.mirror,link.acms.manager.AcmsCertificateMngr.getAcmsCertificateMngr(AcmsCertificateMngr.java:286)
09-09 17:18:10.490  8221  8293 E SQLiteDatabase: 	at com.samsung.android.mirrorlink.acms.api.AcmsCore$AcmsHandler.handleMessage(AcmsCore.java:139)
09-09 17:18:10.490  8221  8293 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:18:10.490  8221  8293 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-09 17:18:10.490  8221  8293 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-09 17:18:10.490  8221  8293 E AndroidRuntime: FATAL EXCEPTION: AcmsHandlerThread
09-09 17:18:10.490  8221  8293 E AndroidRuntime: Process: ACMS.Process, PID: 8221
09-09 17:18:10.490  8221  8293 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 17:18:10.490  8221  8293 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5705)
09-09 17:18:10.490  8221  8293 E AndroidRuntime: 	at android.app.ActivityThread.acquireProvider(ActivityThread.java:5338)
09-09 17:18:10.490  8221  8293 E AndroidRuntime: 	at android.app.ContextImpl$ApplicationContentResolver.acquireUnstableProvider(ContextImpl.java:2966)
09-09 17:18:10.490  8221  8293 E AndroidRuntime: 	at android.content.ContentResolver.acquireUnstableProvider(ContentResolver.java:1495)
09-09 17:18:10.490  8221  8293 E AndroidRuntime: 	at android.content.ContentResolver.query(ContentResolver.java:473)
09-09 17:18:10.490  8221  8293 E AndroidRuntime: 	at android.content.ContentResolver.query(ContentResolver.java:433)
09-09 17:18:10.490  8221  8293 E AndroidRuntime: 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.checkIfPkgNameExists(AppEntryInterface.java:71)
09-09 17:18:10.490  8221  8293 E AndroidRuntime: 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.<init>(AppEntryInterface.java:56)
09-09 17:18:10.490  8221  8293 E AndroidRuntime: 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.getAppEntryInterface(AppEntryInterface.java:64)
09-09 17:18:10.490  8221  8293 E AndroidRuntime: 	at com.samsung.android.mirrorlink.acms.manager.AcmsRevocationMngr.<init>(AcmsRevocationMngr.java:119)
09-09 17:18:10.490  8221  8293 E AndroidRuntime: 	at com.samsung.android.mirrorlink.acms.manager.AcmsRevocationMngr.getAcmsRevocationMngr(AcmsRevocationMngr.java:129)
09-09 17:18:10.490  8221  8293 E AndroidRuntime: 	at com.samsung.android.mirrorlink.acms.manager.AcmsCertificateMngr.<init>(AcmsCertificateMngr.java:94)
09-09 17:18:10.490  8221  8293 E AndroidRuntime: 	at com.samsung.android.mirrorlink.acms.manager.AcmsCertificateMngr.getAcmsCertificateMngr(AcmsCertificateMngr.java:286)
09-09 17:18:10.490  8221  8293 E AndroidRuntime: 	at com.samsung.android.mirrorlink.acms.api.AcmsCore$AcmsHandler.handleMessage(AcmsCore.java:139)
09-09 17:18:10.490  8221  8293 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:18:10.490  8221  8293 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
09-09 17:18:10.490  8221  8293 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 17:18:10.490  8221  8293 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 17:18:10.490  8221  8293 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 17:18:10.490  8221  8293 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-09 17:18:10.490  8221  8293 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-09 17:18:10.490  8221  8293 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-09 17:18:10.490  8221  8293 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-09 17:18:10.490  8221  8293 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-09 17:18:10.490  8221  8293 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-09 17:18:10.490  8221  8293 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-09 17:18:10.490  8221  8293 E AndroidRuntime: 	at android.database.sqlite.,SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-09 17:18:10.490  8221  8293 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-09 17:18:10.490  8221  8293 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 17:18:10.490  8221  8293 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 17:18:10.490  8221  8293 E AndroidRuntime: 	at com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide.onCreate(AcmsPkgNameProvide.java:61)
09-09 17:18:10.490  8221  8293 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
09-09 17:18:10.490  8221  8293 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
09-09 17:18:10.490  8221  8293 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
09-09 17:18:10.490  8221  8293 E AndroidRuntime: 	... 16 more
09-09 17:18:10.490  1871  8233 E SQLiteLog: (28) failed to open "/data/data/com.google.android.gms/databases/phenotype.db" with flag (131138) and mode_t (0) due to error (30)
,09-09 17:18:10.490  7981  8218 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
09-09 17:18:10.490  7981  8218 E SQLiteLog: (3850) statement aborts at 21: [DELETE FROM usage_log WHERE strftime('%s','now', '-40 days')*1000 - start_time >= 0] disk I/O error
,09-09 17:18:10.500  7981  8218 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
09-09 17:18:10.500  7981  8218 E SQLiteLog: (3850) statement aborts at 17: [DELETE FROM running_service_log WHERE strftime('%s','now', '-40 days')*1000 - captured_time >= 0] disk I/O error
,09-09 17:18:10.500  1015  1135 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 17:18:10.500  7981  8218 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
09-09 17:18:10.500  7981  8218 E SQLiteLog: (3850) statement aborts at 17: [DELETE FROM noti_info WHERE strftime('%s','now', '-40 days')*1000 - posted_date >= 0] disk I/O error
,09-09 17:18:10.500  1015  1135 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:10.500  1015  1135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:18:10.500  1015  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-09 17:18:10.500  7981  8218 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
09-09 17:18:10.500  7981  8218 E SQLiteLog: (3850) statement aborts at 17: [DELETE FROM screen_state_log WHERE strftime('%s','now', '-40 days')*1000 - time >= 0] disk I/O error
09-09 17:18:10.500  1015  1135 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
09-09 17:18:10.500  1015  1135 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,09-09 17:18:10.500  7981  8218 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
09-09 17:18:10.500  7981  8218 E SQLiteLog: (3850) statement aborts at 17: [DELETE FROM debug_log_info WHERE strftime('%s','now', '-20 days')*1000 - created_At >= 0] disk I/O error
09-09 17:18:10.500  1015  1135 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:10.500  1015  1135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:18:10.500  1015  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,09-09 17:18:10.500  7981  8218 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
09-09 17:18:10.500  7981  8218 E SQLiteLog: (3850) statement aborts at 3: [DELETE FROM system_env_info] disk I/O error
,09-09 17:18:10.500  7981  8218 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
09-09 17:18:10.500  7981  8218 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
09-09 17:18:10.500  1015  1028 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
09-09 17:18:10.500  1871  8233 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
09-09 17:18:10.500  1871  8233 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 17:18:10.500  1871  8233 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 17:18:10.500  1871  8233 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-09 17:18:10.500  1871  8233 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-09 17:18:10.500  1871  8233 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-09 17:18:10.500  1871  8233 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-09 17:18:10.500  1871  8233 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-09 17:18:10.500  1871  8233 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-09 17:18:10.500  1871  8233 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-09 17:18:10.500  1871  8233 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-09 17:18:10.500  1871  8233 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-09 17:18:10.500  1871  8233 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-09 17:18:10.500  1871  8233 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-09 17:18:10.500  1871  8233 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 17:18:10.500  1871  8233 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 17:18:10.500  1871  8233 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-09 17:18:10.500  1871  8233 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-09 17:18:10.500  1871  8233 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:18:10.500  1871  8233 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-09 17:18:10.500  1871  8233 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 17:18:10.500  1871  8233 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
09-09 17:18:10.500  1871  8233 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 17:18:10.500  1871  8233 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 17:18:10.500  1871  8233 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-09 17:18:10.500  1871  8233 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-09 17:18:10.500  1871  8233 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-09 17:18:10.500  1871  8233 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-09 17:18:10.5,00  1871  8233 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-09 17:18:10.500  1871  8233 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-09 17:18:10.500  1871  8233 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-09 17:18:10.500  1871  8233 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-09 17:18:10.500  1871  8233 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-09 17:18:10.500  1871  8233 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-09 17:18:10.500  1871  8233 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-09 17:18:10.500  1871  8233 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 17:18:10.500  1871  8233 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 17:18:10.500  1871  8233 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-09 17:18:10.500  1871  8233 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-09 17:18:10.500  1871  8233 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:18:10.500  1871  8233 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
09-09 17:18:10.500  1871  8233 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 17:18:10.500  7981  8218 E SQLiteDatabase: Error inserting name=this value=SmartManager LowpowerContextEngine
09-09 17:18:10.500  7981  8218 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 17:18:10.500  7981  8218 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
09-09 17:18:10.500  7981  8218 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
09-09 17:18:10.500  7981  8218 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
09-09 17:18:10.500  7981  8218 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
09-09 17:18:10.500  7981  8218 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
09-09 17:18:10.500  7981  8218 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
09-09 17:18:10.500  7981  8218 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f$b.a(DataStore.java:2487)
09-09 17:18:10.500  7981  8218 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.b(DataStore.java:1740)
09-09 17:18:10.500  7981  8218 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.g(LowpowerContextEngine.java:206)
09-09 17:18:10.500  7981  8218 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.e(LowpowerContextEngine.java:152)
09-09 17:18:10.500  7981  8218 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.<init>(LowpowerContextEngine.java:100)
09-09 17:18:10.500  7981  8218 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.a(LowpowerContextEngine.java:106)
09-09 17:18:10.500  7981  8218 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.b(LowpowerContextReceiver.java:133)
09-09 17:18:10.500  7981  8218 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:102)
09-09 17:18:10.500  7981  8218 E SQLiteDatabase: 	at com,.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:42)
09-09 17:18:10.500  7981  8218 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.q.run(LowpowerContextReceiver.java:52)
09-09 17:18:10.500  7981  8218 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 17:18:10.500  7981  8218 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 17:18:10.500  7981  8218 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-09 17:18:10.500  7981  8218 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 17:18:10.510  1871  8233 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
09-09 17:18:10.510  1015  1501 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname ACMS.Process
09-09 17:18:10.510  1015  1244 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
09-09 17:18:10.510  8221  8221 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
09-09 17:18:10.510  8255  8296 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
09-09 17:18:10.510  1015  1244 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:10.520  1015  1244 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:10.520  1015  1244 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:10.520  1015  1244 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:10.520  1871  8288 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
09-09 17:18:10.520  1871  8288 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 17:18:10.520  1871  8288 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 17:18:10.520  1871  8288 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-09 17:18:10.520  1871  8288 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-09 17:18:10.520  1871  8288 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-09 17:18:10.520  1871  8288 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-09 17:18:10.520  1871  8288 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-09 17:18:10.520  1871  8288 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-09 17:18:10.520  1871  8288 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-09 17:18:10.520  1871  8288 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-09 17:18:10.520  1871  8288 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-09 17:18:10.520  1871  8288 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-09 17:18:10.520  1871  8288 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 17:18:10.520  1871  8288 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 17:18:10.520  1871  8288 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
09-09 17:18:10.520  1871  8288 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
09-09 17:18:10.520  1871  8288 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
09-09 17:18:10.520  1871  8288 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
09-09 17:18:10.520  1871  8288 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-09 17:18:10.520  1871  8288 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:18:10.520  1871  8288 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-09 17:18:10.520  1871  8288 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 17:18:10.520  8255  8296 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
09-09 17:18:10.520  8255  8296 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 17:18:10.520  8255  8296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 17:18:10.520  8255  8296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-09 17:18:10.520  8255  8296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-09 17:18:10.520  8255  8296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-09 17:18:10.520  8255  8296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-09 17:18:10.520  8255  8296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-09 17:18:10.520  8255  8296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-09 17:18:10.520  8255  8296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-09 17:18:10.520  8255  8296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-09 17:18:10.520  8255  8296 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-09 17:18:10.520  8255  8296 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-09 17:18:10.520  8255  8296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 17:18:10.520  8255  8296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 17:18:10.520  8255  8296 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
09-09 17:18:10.520  8255  8296 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
09-09 17:18:10.520  8255  8296 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-09 17:18:10.520  8255  8296 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:18:10.520  8255  8296 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-09 17:18:10.520  8255  8296 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 17:18:10.520  8255  8296 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 17:18:10.520  8255  8296 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 17:18:10.520  8255  8296 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-09 17:18:10.520  8255  8296 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-09 17:18:10.520  8255  8296 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-09 17:18:10.520  8255  8296 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-09 17:18:10.520  8255  8296 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-09 17:18:10.520  8255  8296 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-09 17:18:10.520  8255  8296 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-09 17:18:10.520  8255  8296 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-09 17:18:10.520  1871  8288 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
09-09 17:18:10.520  1871  8288 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 17:18:10.520  1871  8288 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 17:18:10.520  1871  8288 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-09 17:18:10.520  1871  8288 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-09 17:18:10.520  1871  8288 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-09 17:18:10.520  1871  8288 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-09 17:18:10.520  1871  8288 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-09 17:18:10.520  1871  8288 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-09 17:18:10.520  1871  8288 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-09 17:18:10.520  1871  8288 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-09 17:18:10.520  1871  8288 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-09 17:18:10.520  1871  8288 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-09 17:18:10.520  1871  8288 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 17:18:10.520  1871  8288 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 17:18:10.520  1871  8288 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
09-09 17:18:10.520  1871  8288 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
09-09 17:18:10.520  1871  8288 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
09-09 17:18:10.520  1871  8288 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
09-09 17:18:10.520  1871  8288 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-09 17:18:10.520  1871  8288 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:18:10.520  1871  8288 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
09-09 17:18:10.520  1871  8288 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 17:18:10.520  8255  8296 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-09 17:18:10.520  8255  8296 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-09 17:18:10.520  8255  8296 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 17:18:10.520  8255  8296 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 17:18:10.520  8255  8296 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
09-09 17:18:10.520  8255  8296 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
09-09 17:18:10.520  8255  8296 W System.err: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-09 17:18:10.520  8255  8296 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:18:10.520  8255  8296 W System.err: 	at android.os.Looper.loop(Looper.java:145)
09-09 17:18:10.520  8255  8296 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 17:18:10.520  8221  8221 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.app.mirrorlink/databases/pkgnamedb" with flag (131138) and mode_t (0) due to error (30)
09-09 17:18:10.530  8221  8221 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.app.mirrorlink/databases/pkgnamedb'.
09-09 17:18:10.530  8221  8221 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 17:18:10.530  8221  8221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 17:18:10.530  8221  8221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-09 17:18:10.530  8221  8221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-09 17:18:10.530  8221  8221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-09 17:18:10.530  8221  8221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-09 17:18:10.530  8221  8221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-09 17:18:10.530  8221  8221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-09 17:18:10.530  8221  8221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-09 17:18:10.530  8221  8221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-09 17:18:10.530  8221  8221 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-09 17:18:10.530  8221  8221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 17:18:10.530  8221  8221 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 17:18:10.530  8221  8221 E SQLiteDatabase: 	at com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide.onCreate(AcmsPkgNameProvide.java:61)
09-09 17:18:10.530  8221  8221 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
09-09 17:18:10.530  8221  8221 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
09-09 17:18:10.530  8221  8221 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
09-09 17:18:10.530  8221  8221 E SQLiteDatabase: 	at android.app.ActivityThread.acquireProvider(ActivityThread.java:5338)
09-09 17:18:10.530  8221  8221 E SQLiteDatabase: 	at android.app.ContextImpl$ApplicationContentResolver.acquireUnstableProvider(ContextImpl.java:2966)
09-09 17:18:10.530  8221  8221 E SQLiteDatabase: 	at android.content.ContentResolver.acquireUnstableProvider(ContentResolver.java:1495)
09-09 17:18:10.530  8221  8221 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:473)
09-09 17:18:10.530  8221  8221 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:433)
09-09 17:18:10.530  8221  8221 E SQLiteDatabase: 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.checkIfPkgNameExists(AppEntryInterface.java:71)
09-09 17:18:10.530  8221  8221 E SQLiteDatabase: 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.<init>(AppEntryInterface.java:56)
09-09 17:18:10.530  8221  8221 E SQLiteDatabase: 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.getAppEntryInterface(AppEntryInterface.java:64)
09-09 17:18:10.530  8221  8221 E SQLiteDatabase: 	at com.samsung.android.mirrorlink.acms.api.AcmsService.handleStartIntent(AcmsService.java:95)
09-09 17:18:10.530  8221  8221 E SQLiteDatabase: 	at com.samsung.android.mirrorlink.acms.api.AcmsService.onStartCommand(AcmsService.java:77)
09-09 17:18:10.530  8221  8221 E SQLiteDatabase: 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3440)
09-09 17:18:10.530  8221  8221 E SQLiteDatabase: 	at android.app.ActivityThread.access$2200(ActivityThread.java:181)
09-09 17:18:10.530  8221  8221 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1580)
09-09 17:18:10.530  8221  8221 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:18:10.530  8221  8221 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-09 17:18:10.530  8221  8221 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 17:18:10.530  8221  8221 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:18:10.530  8221  8221 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:18:10.530  8221  8221 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 17:18:10.530  8221  8221 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 17:18:10.530  8221  8221 D AndroidRuntime: Shutting down VM
09-09 17:18:10.530  8221  8221 I Process : Sending signal. PID: 8221 SIG: 9
09-09 17:18:10.530  7981  8218 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
09-09 17:18:10.530  7981  8218 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
09-09 17:18:10.530  7981  8218 E SQLiteDatabase: Error inserting name=now value=Fri Sep 09 17:18:10 GMT+02:00 2016
09-09 17:18:10.530  7981  8218 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 17:18:10.530  7981  8218 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
09-09 17:18:10.530  7981  8218 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
09-09 17:18:10.530  7981  8218 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
09-09 17:18:10.530  7981  8218 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
09-09 17:18:10.530  7981  8218 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
09-09 17:18:10.530  7981  8218 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
09-09 17:18:10.530  7981  8218 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f$b.a(DataStore.java:2487)
09-09 17:18:10.530  7981  8218 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.b(DataStore.java:1740)
09-09 17:18:10.530  7981  8218 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.g(LowpowerContextEngine.java:207)
09-09 17:18:10.530  7981  8218 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.e(LowpowerContextEngine.java:152)
09-09 17:18:10.530  7981  8218 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.<init>(LowpowerContextEngine.java:100)
09-09 17:18:10.530  7981  8218 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.a(LowpowerContextEngine.java:106)
09-09 17:18:10.530  7981  8218 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.b(LowpowerContextReceiver.java:133)
09-09 17:18:10.530  7981  8218 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:102)
09-09 17:18:10.530  7981  8218 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:42)
09-09 17:18:10.530  7981  8218 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.q.run(LowpowerContextReceiver.java:52)
09-09 17:18:10.530  7981  8218 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 17:18:10.530  7981  8218 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 17:18:10.530  7981  8218 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-09 17:18:10.530  7981  8218 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 17:18:10.530  7981  8218 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
09-09 17:18:10.530  7981  8218 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
09-09 17:18:10.530  7981  8218 E SQLiteDatabase: Error inserting name=isSystemBuild value=false
09-09 17:18:10.530  7981  8218 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 17:18:10.530  7981  8218 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
09-09 17:18:10.530  7981  8218 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
09-09 17:18:10.530  7981  8218 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
09-09 17:18:10.530  7981  8218 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
09-09 17:18:10.530  7981  8218 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
09-09 17:18:10.530  7981  8218 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
09-09 17:18:10.530  7981  8218 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f$b.a(DataStore.java:2487)
09-09 17:18:10.530  7981  8218 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.b(DataStore.java:1740)
09-09 17:18:10.530  7981  8218 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.g(LowpowerContextEngine.java:208)
09-09 17:18:10.530  7981  8218 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.e(LowpowerContextEngine.java:152)
09-09 17:18:10.530  7981  8218 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.<init>(LowpowerContextEngine.java:100)
09-09 17:18:10.530  7981  8218 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.a(LowpowerContextEngine.java:106)
09-09 17:18:10.530  7981  8218 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.b(LowpowerContextReceiver.java:133)
09-09 17:18:10.530  7981  8218 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:102)
09-09 17:18:10.530  7981  8218 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:42)
09-09 17:18:10.530  7981  8218 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.q.run(LowpowerContextReceiver.java:52)
09-09 17:18:10.530  7981  8218 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 17:18:10.530  7981  8218 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 17:18:10.530  7981  8218 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-09 17:18:10.530  7981  8218 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
