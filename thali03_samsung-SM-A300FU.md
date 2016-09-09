#### Test 836273375fe617f_thali03_samsung-SM-A300FU Logs


```
--------- beginning of main,
09-09 13:40:58.644   317   317 I ServiceManager: Waiting for service AtCmdFwd...
09-09 13:40:58.904  6926  6926 D AndroidRuntime: 
09-09 13:40:58.904  6926  6926 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-09 13:40:58.904  6926  6926 D AndroidRuntime: CheckJNI is OFF
09-09 13:40:58.904  6926  6926 D AndroidRuntime: readGMSProperty: start
09-09 13:40:58.904  6926  6926 D AndroidRuntime: readGMSProperty: already setted!!
09-09 13:40:58.904  6926  6926 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-09 13:40:58.904  6926  6926 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-09 13:40:58.904  6926  6926 D AndroidRuntime: readGMSProperty: end
09-09 13:40:58.904  6926  6926 D AndroidRuntime: addProductProperty: start
09-09 13:40:59.044  6926  6926 E AffinityControl: AffinityControl: registerfunction enter
09-09 13:40:59.064  6926  6926 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-09 13:40:59.084  1014  1216 E PersonaManagerService: inState():  stateMachine is null !!
09-09 13:40:59.084  1014  1216 I PersonaManagerService: PersonaId don't exist
09-09 13:40:59.084  1014  1216 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-09 13:40:59.084  1014  1216 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
09-09 13:40:59.104  1014  1216 W ActivityManager: mDVFSHelper.acquire()
09-09 13:40:59.104  1014  1216 D FocusedStackFrame: Set to : 0
09-09 13:40:59.114  1014  1046 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-09 13:40:59.114  1014  1046 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-09 13:40:59.114  1014  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:40:59.114  1014  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:40:59.114  1014  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:40:59.114  1014  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:40:59.134  1014  1216 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6937 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-09 13:40:59.134  1014  1216 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
09-09 13:40:59.134  1014  1216 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-09 13:40:59.134  1014  1216 D InputDispatcher: Focused application set to: xxxx
09-09 13:40:59.134  1014  1216 D InputDispatcher: Focus left window: 1503
09-09 13:40:59.134  1014  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-09 13:40:59.134  1014  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-09 13:40:59.134  6937  6937 E Zygote  : MountEmulatedStorage()
09-09 13:40:59.134  6937  6937 E Zygote  : v2
09-09 13:40:59.134  6937  6937 I libpersona: KNOX_SDCARD checking this for 10170
09-09 13:40:59.134  6937  6937 I libpersona: KNOX_SDCARD not a persona
09-09 13:40:59.134  6926  6926 D AndroidRuntime: Shutting down VM
09-09 13:40:59.134   257   257 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
09-09 13:40:59.134  6937  6937 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 13:40:59.134  6937  6937 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 13:40:59.144  6937  6937 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-09 13:40:59.154  1014  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-09 13:40:59.154  1014  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
09-09 13:40:59.154  6937  6937 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:40:59.154  6937  6937 D ActivityThread: Added TimaKeyStore provider
09-09 13:40:59.164  1014  1027 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
09-09 13:40:59.164  1014  1014 V ActivityManager: Display changed displayId=0
09-09 13:40:59.164  1014  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-09 13:40:59.184  1014  1027 D PersonaManager: isKioskContainerExistOnDevice
09-09 13:40:59.194  1014  1014 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
09-09 13:40:59.224   257   449 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
09-09 13:40:59.224   257   446 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
09-09 13:40:59.224  1503  1503 V ActivityThread: updateVisibility : ActivityRecord{24756639 token=android.os.BinderProxy@1e5b49e5 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
09-09 13:40:59.224  1503  1503 D Launcher: onTrimMemory. Level: 20
09-09 13:40:59.284  6937  6937 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
09-09 13:40:59.304  6937  6937 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 5788-5790)
09-09 13:40:59.304  6937  6937 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-09 13:40:59.314  6937  6937 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1bc80a3b}
09-09 13:40:59.324  6937  6937 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-09 13:40:59.324  6937  6937 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
09-09 13:40:59.344  6926  6926 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-09 13:40:59.354  6937  6937 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
09-09 13:40:59.354  6937  6937 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-09 13:40:59.354  6937  6937 E SysUtils: ApplicationContext is null in ApplicationStatus
09-09 13:40:59.374  6937  6937 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-09 13:40:59.374  6937  6937 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-09 13:40:59.374  6937  6937 I Adreno-EGL: Build Date: 04/06/15 Mon
09-09 13:40:59.374  6937  6937 I Adreno-EGL: Local Branch: 
09-09 13:40:59.374  6937  6937 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-09 13:40:59.374  6937  6937 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-09 13:40:59.374  6937  6937 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
09-09 13:40:59.434  6937  6937 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 13:40:59.444  6937  6937 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
09-09 13:40:59.444  6937  6937 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
09-09 13:40:59.454  6937  6937 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
09-09 13:40:59.454  6937  6937 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
09-09 13:40:59.484  1014  1501 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-09 13:40:59.484  1014  1501 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4268, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-09 13:40:59.484  1014  1501 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-09 13:40:59.484  1014  1501 D BatteryService: stay LED for charging
09-09 13:40:59.484  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-09 13:40:59.494  1014  1014 I MotionRecognitionService: Plugged
09-09 13:40:59.494  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
09-09 13:40:59.494  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-09 13:40:59.494  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
09-09 13:40:59.494  1421  1421 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-09 13:40:59.494  1421  1421 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
09-09 13:40:59.504  2789  2789 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-09 13:40:59.504  2789  3002 D HeadsetStateMachine: Disconnected process message: 10
09-09 13:40:59.514  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-09 13:40:59.514  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-09 13:40:59.514  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-09 13:40:59.514  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
09-09 13:40:59.514  1174  1174 D SViewCoverView: level :100 plugged : 2
09-09 13:40:59.574  6937  6937 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-09 13:40:59.594  6937  6937 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-09 13:40:59.604  6937  6937 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-09 13:40:59.604  6937  6937 D PhoneWindow: *FMB* installDecor flags : -2139027200
09-09 13:40:59.604  6937  6937 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
09-09 13:40:59.614  6937  6937 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-09 13:40:59.614  6937  6937 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-09 13:40:59.634   287   287 E SMD     : DCD OFF
09-09 13:40:59.644   317   317 I ServiceManager: Waiting for service AtCmdFwd...
09-09 13:40:59.654  6937  6976 D OpenGLRenderer: Render dirty regions requested: true
09-09 13:40:59.664  1014  1216 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-09 13:40:59.664  1014  1216 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-09 13:40:59.664  1014  1216 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-09 13:40:59.664  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-09 13:40:59.664  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
09-09 13:40:59.664  6937  6964 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
09-09 13:40:59.674  6937  6937 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-09 13:40:59.674  6937  6937 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-09 13:40:59.694   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
09-09 13:40:59.694  1014  1502 D InputDispatcher: Focus entered window: 6937
09-09 13:40:59.704  1014  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-09 13:40:59.704  1014  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
09-09 13:40:59.704  6937  6937 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
09-09 13:40:59.704  6937  6976 I OpenGLRenderer: Initialized EGL, version 1.4
09-09 13:40:59.714  6937  6976 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
09-09 13:40:59.714  6937  6976 D OpenGLRenderer: Enabling debug mode 0
09-09 13:40:59.734  6937  6937 V ActivityThread: updateVisibility : ActivityRecord{3e958fb8 token=android.os.BinderProxy@cd412cc {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-09 13:40:59.774  1014  1216 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
09-09 13:40:59.774  1174  1174 D PanelView: There is/are notification(s) 
09-09 13:40:59.774  1014  6981 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
09-09 13:40:59.794  1014  1046 I ActivityManager: Displayed Component not be shown by security: +607ms (total +674ms)
09-09 13:40:59.794  1014  1046 W ActivityManager: mDVFSHelper.release()
09-09 13:40:59.794  1014  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1f191f90 u0 com.test.thalitest/.MainActivity t163} time:116287
09-09 13:40:59.804   257   446 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
09-09 13:40:59.804   257  1888 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
09-09 13:40:59.814  6937  6937 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
09-09 13:40:59.814  6937  6937 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@cd412cc time:116301
09-09 13:40:59.824  1868  1868 I SamsungIME: getCurrentCandidateView
09-09 13:40:59.934  6937  6937 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6937
09-09 13:40:59.934  1868  1868 D SamsungIME: Dismiss ExpandCandiate
09-09 13:40:59.994  1014  1094 V AlarmManager: waitForAlarm result :8
,09-09 13:41:00.084  1868  1868 I SamsungIME: getDebugLevel  : 0x4f4c
,09-09 13:41:00.104  1014  2887 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-09 13:41:00.124  1868  1868 I SamsungIME: getDebugLevel  : 0x4f4c
,09-09 13:41:00.134  6937  6937 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-09 13:41:00.144  1868  1868 I SamsungIME: KeybaordView init() : load resources
,09-09 13:41:00.164  1868  1868 I SamsungIME: getCurrentKeyboard
09-09 13:41:00.164  1868  1868 I SamsungIME: getTextKeyboard
,09-09 13:41:00.184  1868  1868 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-09 13:41:00.234  6937  6984 D jxcore_app_log: JniHelper::setJavaVM(0xb7c4f2b0), pthread_self() = -1205963048
,09-09 13:41:00.234  6937  6984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-09 13:41:00.234  6937  6984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-09 13:41:00.234  6937  6984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-09 13:41:00.234  6937  6984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-09 13:41:00.234  6937  6984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-09 13:41:00.234  6937  6984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20ec1c9 added. We now have 1 listener(s)
,09-09 13:41:00.244  6937  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,09-09 13:41:00.244  6937  6984 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-09 13:41:00.244  6937  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 13:41:00.244  6937  6984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 13:41:00.254  6937  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-09 13:41:00.254  6937  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-09 13:41:00.254  6937  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-09 13:41:00.254  6937  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
09-09 13:41:00.254  6937  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-09 13:41:00.254  6937  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-09 13:41:00.254  6937  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-09 13:41:00.254  6937  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-09 13:41:00.254  6937  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-09 13:41:00.254  6937  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-09 13:41:00.254  6937  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-09 13:41:00.254  6937  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-09 13:41:00.254  6937  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-09 13:41:00.254  6937  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-09 13:41:00.254  6937  6984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10e7c6fc added. We now have 1 listener(s)
09-09 13:41:00.254  6937  6984 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:41:00.254  6937  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:41:00.254  6937  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-09 13:41:00.264  6937  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-09 13:41:00.264  6937  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,09-09 13:41:00.264  6937  6984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-09 13:41:00.264  6937  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:00.264  6937  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
,09-09 13:41:00.274  6937  6984 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-09 13:41:00.274  6937  6984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:00.274  6937  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:00.274  6937  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:00.274  6937  6984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:00.274  6937  6984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:00.274  6937  6984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:00.274  6937  6984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:00.274  6937  6984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:00.274  6937  6984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-09 13:41:00.274  6937  6984 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:41:00.274  6937  6984 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-09 13:41:00.274  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:00.274  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:00.304  6937  6937 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-09 13:41:00.644   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 13:41:00.784  6937  6991 W jxcore-log: Initializing JXcore engine
09-09 13:41:00.784  6937  6991 W jxcore-log: JXcore engine is ready
,09-09 13:41:00.834  1977  1977 E audit   : type=1400 msg=audit(1473421260.834:205): avc:  denied  { ioctl } for  pid=6991 comm="Thread-1310" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-09 13:41:00.834  1977  1977 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
09-09 13:41:00.834  1977  1977 E audit   : type=1300 msg=audit(1473421260.834:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9f9bb8f8 items=0 ppid=305 ppcomm=main pid=6991 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1310" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-09 13:41:00.844  1977  1977 E audit   : type=1320 msg=audit(1473421260.834:205): 
,09-09 13:41:00.844  6937  6991 W jxcore-log: Starting JXcore engine
,09-09 13:41:00.954  6937  6991 W jxcore-log: Platform android,
09-09 13:41:00.954  6937  6991 W jxcore-log: 
09-09 13:41:00.954  6937  6991 W jxcore-log: Process ARCH arm
09-09 13:41:00.954  6937  6991 W jxcore-log: 
,09-09 13:41:01.154  6937  6991 I jxcore-log: JXcore Cordova bridge is ready!
09-09 13:41:01.154  6937  6991 I jxcore-log: 
09-09 13:41:01.154  6937  6991 W jxcore-log: JXcore engine is started
,09-09 13:41:01.154  6937  6984 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-09 13:41:01.164  6937  6937 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-09 13:41:01.644   317   317 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 13:41:02.224  5930  5930 D FactoryTest: Not factory mode
,09-09 13:41:02.234  5930  5930 D FactoryTest: Not factory mode. isFactoryMode() returend false
,09-09 13:41:02.234  5930  5930 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,09-09 13:41:02.234  5930  5930 D MTPRx   : still no open session command from host, so toast
,09-09 13:41:02.234  5930  5930 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
09-09 13:41:02.234  5930  5930 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
09-09 13:41:02.234  5930  5930 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:118726
09-09 13:41:02.234  1014  1026 E PersonaManagerService: inState():  stateMachine is null !!
,09-09 13:41:02.234  1014  1026 I PersonaManagerService: PersonaId don't exist
09-09 13:41:02.234  1014  1026 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,09-09 13:41:02.244  1014  1026 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-09 13:41:02.244  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:02.244  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:02.244  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,09-09 13:41:02.244  1014  1026 W ActivityManager: mDVFSHelper.acquire()
,09-09 13:41:02.264  1014  1026 D PersonaManager: isKioskContainerExistOnDevice
,09-09 13:41:02.274  1014  1026 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-09 13:41:02.274  1014  1026 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
09-09 13:41:02.274  1014  1026 D InputDispatcher: Focused application set to: xxxx,
09-09 13:41:02.274  1014  1026 D InputDispatcher: Focus left window: 6937
,09-09 13:41:02.274  5930  5930 E MTPRx   : started activity for popup
,09-09 13:41:02.274  1014  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-09 13:41:02.274  1014  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-09 13:41:02.294  5930  5930 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,09-09 13:41:02.294  5930  5930 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-09 13:41:02.294  5930  5930 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-09 13:41:02.294  5930  5930 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 13:41:02.304  5930  5930 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-09 13:41:02.304  5930  5930 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-09 13:41:02.324  5930  5930 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,09-09 13:41:02.334  1014  1328 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-09 13:41:02.334  1014  1328 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-09 13:41:02.334  1014  1328 D InputDispatcher: Focused application set to: xxxx
,09-09 13:41:02.334  1014  1328 D InputDispatcher: Focus entered window: 6937
,09-09 13:41:02.334  1014  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-09 13:41:02.334  1014  1558 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-09 13:41:02.334  1014  1558 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@f744a23 attribute=null, token = android.os.BinderProxy@13736e33
,09-09 13:41:02.344  1014  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-09 13:41:02.374  5930  5930 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,09-09 13:41:02.384  5930  5930 D PhoneWindow: *FMB* installDecor mIsFloating : true
09-09 13:41:02.384  5930  5930 D PhoneWindow: *FMB* installDecor flags : 8388610
,09-09 13:41:02.404  6937  6937 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-09 13:41:02.404  6937  6937 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,09-09 13:41:02.404  6937  6937 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-09 13:41:02.404  6937  6937 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,09-09 13:41:02.414  1014  1500 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-09 13:41:02.414  1014  1500 D KnoxTimeoutHandler: postActiveUserChange for user 0
,09-09 13:41:02.414  1014  1500 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-09 13:41:02.414  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-09 13:41:02.414  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
,09-09 13:41:02.424  6937  6937 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-09 13:41:02.424  6937  6937 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-09 13:41:02.424  6937  6937 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@cd412cc time:118916
,09-09 13:41:02.424  6937  6937 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3bb7f488 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@1582d76e, 16908290=android.view.AbsSavedState$1@1582d76e}, android:focusedViewId=100}]}]
,09-09 13:41:02.424  6937  6937 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-09 13:41:02.424  6937  6937 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-09 13:41:02.424  6937  6937 V ActivityThread: updateVisibility : ActivityRecord{3e958fb8 token=android.os.BinderProxy@cd412cc {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-09 13:41:02.424  6937  6937 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-09 13:41:02.434  1014  1556 D PersonaManager: isKioskContainerExistOnDevice
,09-09 13:41:02.634   287   287 E SMD     : DCD OFF,
,09-09 13:41:02.644   317   317 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,09-09 13:41:05.254  1014  1041 W ActivityManager: mDVFSHelper.release()
,09-09 13:41:05.634   287   287 E SMD     : DCD OFF
,09-09 13:41:07.364  1014  2857 D SSRM:n  : SIOP:: AP = 350
,09-09 13:41:07.644   317   317 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 13:41:08.634   287   287 E SMD     : DCD OFF,
,09-09 13:41:08.644   317   317 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 13:41:09.164  1014  1054 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-09 13:41:09.534  1014  1216 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-09 13:41:09.534  1014  1216 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4262, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-09 13:41:09.534  1014  1216 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,09-09 13:41:09.534  1014  1216 D BatteryService: stay LED for charging
09-09 13:41:09.534  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-09 13:41:09.534  1014  1014 I MotionRecognitionService: Plugged
09-09 13:41:09.534  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,09-09 13:41:09.544  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-09 13:41:09.544  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-09 13:41:09.544  1421  1421 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-09 13:41:09.544  1421  1421 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-09 13:41:09.554  2789  2789 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-09 13:41:09.554  2789  3002 D HeadsetStateMachine: Disconnected process message: 10
,09-09 13:41:09.564  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-09 13:41:09.564  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-09 13:41:09.574  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-09 13:41:09.574  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,09-09 13:41:09.574  1174  1174 D SViewCoverView: level :100 plugged : 2
,09-09 13:41:09.644   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 13:41:10.644   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 13:41:11.634   287   287 E SMD     : DCD OFF
,09-09 13:41:11.644   317   317 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 13:41:12.644   317   317 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,09-09 13:41:13.204  6937  6991 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-09 13:41:13.204  6937  6991 I jxcore-log: 
,09-09 13:41:13.204  6937  6991 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
09-09 13:41:13.204  6937  6991 I jxcore-log: 
,09-09 13:41:13.214  6937  6991 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-09 13:41:13.214  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:13.214  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:13.214  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:13.214  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:13.214  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:13.214  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:13.214  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:13.214  6937  6991 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,09-09 13:41:13.214  6937  6991 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-09 13:41:13.214  6937  6991 I jxcore-log: 
09-09 13:41:13.214  6937  6991 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
09-09 13:41:13.214  6937  6991 I jxcore-log: 
,09-09 13:41:13.854  6937  6991 I jxcore-log: Unit Test app is loaded,
09-09 13:41:13.854  6937  6991 I jxcore-log: 
,09-09 13:41:13.864  6937  6991 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:13.864  6937  6991 I jxcore-log: 
,09-09 13:41:13.864  6937  6937 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-09 13:41:13.874  6937  6991 D executeNativeTests: Running unit tests
09-09 13:41:13.874  6937  6991 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:41:13.874  6937  6991 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@136d6e0f added. We now have 2 listener(s)
09-09 13:41:13.884  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-09 13:41:13.884  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:13.884  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:41:13.884  6937  6991 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:41:13.884  6937  6991 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bba9e9c added. We now have 2 listener(s)
09-09 13:41:13.884  6937  6991 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:41:13.884  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:41:13.884  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:13.884  6937  6991 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:13.884  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:13.884  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:13.884  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:13.884  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:13.884  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:13.884  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:13.884  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:13.894  6937  6991 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:13.894  6937  6991 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:41:13.894  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:13.894  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:14.644   287   287 E SMD     : DCD OFF
,09-09 13:41:17.374  1014  2857 D SSRM:n  : SIOP:: AP = 340
,09-09 13:41:17.644   287   287 E SMD     : DCD OFF
,09-09 13:41:19.584  1014  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-09 13:41:19.584  1014  1027 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4290, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-09 13:41:19.594  1014  1027 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,09-09 13:41:19.594  1014  1027 D BatteryService: stay LED for charging
,09-09 13:41:19.594  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-09 13:41:19.594  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-09 13:41:19.594  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-09 13:41:19.604  1014  1014 I MotionRecognitionService: Plugged
09-09 13:41:19.604  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,09-09 13:41:19.604  1421  1421 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-09 13:41:19.604  1421  1421 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-09 13:41:19.614  2789  2789 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-09 13:41:19.614  2789  3002 D HeadsetStateMachine: Disconnected process message: 10
,09-09 13:41:19.624  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-09 13:41:19.624  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-09 13:41:19.624  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-09 13:41:19.624  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
09-09 13:41:19.624  1174  1174 D SViewCoverView: level :100 plugged : 2
,09-09 13:41:20.114  1014  2887 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-09 13:41:20.644   287   287 E SMD     : DCD OFF,
,09-09 13:41:21.764  1014  1325 E Watchdog: !@Sync 4,
,09-09 13:41:22.024  1014  1048 I PowerManagerService: [PWL] Off : 75s ago,
,09-09 13:41:22.644   317   317 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 13:41:23.644   287   287 E SMD     : DCD OFF,
,09-09 13:41:23.644   317   317 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 13:41:24.024  6937  6991 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 13:41:24.024  6937  6991 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@259782a added. We now have 3 listener(s)
,09-09 13:41:24.024  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-09 13:41:24.024  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:24.024  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 13:41:24.024  6937  6991 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 13:41:24.024  6937  6991 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d31261b added. We now have 3 listener(s)
09-09 13:41:24.024  6937  6991 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:41:24.024  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:41:24.034  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:24.034  6937  6991 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:24.034  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:24.034  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:24.034  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:24.034  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:24.034  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:24.034  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:24.034  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:24.034  6937  6991 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:24.034  6937  6991 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:41:24.034  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:24.044  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:24.044  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-09 13:41:24.044  6937  6991 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 13:41:24.044  6937  6991 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:41:24.044  6937  6991 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 13:41:24.054  6937  6991 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-09 13:41:24.054  6937  6991 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-09 13:41:24.054  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-09 13:41:24.054  6937  6991 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1,
09-09 13:41:24.054  6937  6991 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:41:24.054  6937  6991 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-09 13:41:24.054  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:24.054  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:24.054  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:24.054  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:41:24.054  6937  6991 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@259782a removed from the list
09-09 13:41:24.054  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:41:24.054  6937  6991 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d31261b removed from the list
09-09 13:41:24.054  6937  6991 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:24.054  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:24.054  6937  6991 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-09 13:41:24.054  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:41:24.054  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:24.054  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:24.054  6937  6991 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@259782a not in the list
09-09 13:41:24.054  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:41:24.054  6937  6991 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d31261b not in the list
09-09 13:41:24.054  6937  6991 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:24.054  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:24.054  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:24.064  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-09 13:41:24.064  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 13:41:24.064  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-09 13:41:24.064  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 13:41:24.064  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 13:41:24.064  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 13:41:24.064  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 13:41:24.064  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-09 13:41:24.064  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 13:41:24.064  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 13:41:24.064  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 13:41:24.064  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 13:41:24.064  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-09 13:41:24.064  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 13:41:24.064  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 13:41:24.064  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 13:41:24.064  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 13:41:24.064  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-09 13:41:24.064  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 13:41:24.064  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 13:41:24.064  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 13:41:24.064  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 13:41:24.064  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 13:41:24.064  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 13:41:24.064  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-09 13:41:24.064  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 13:41:24.064  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 13:41:24.064  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 13:41:24.064  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 13:41:24.064  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 13:41:24.064  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910],
09-09 13:41:24.064  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:24.064  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:24.064  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:24.064  6937  6991 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@259782a not in the list
09-09 13:41:24.064  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:24.064  6937  6991 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d31261b not in the list
,09-09 13:41:24.064  6937  6991 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:24.064  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:24.064  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:24.064  6937  6991 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-09 13:41:24.064  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:24.074  6937  6991 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:24.074  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:24.074  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:24.074  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:24.074  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:24.074  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:24.074  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:24.074  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:24.074  6937  6991 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
09-09 13:41:24.074  6937  6991 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:41:24.074  6937  6991 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-09 13:41:24.074  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-09 13:41:24.074  6937  6991 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 13:41:24.074  6937  6991 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-09 13:41:24.074  6937  6991 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:41:24.074  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:24.074  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:24.074  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-09 13:41:24.074  6937  6991 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 13:41:24.074  6937  6991 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-09 13:41:24.074  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:41:24.074  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-09 13:41:24.074  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:24.074  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 13:41:24.084  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:24.084  6937  6937 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-09 13:41:24.084  6937  6991 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 13:41:24.084  6937  7003 D BluetoothSocket: bindListen(): myUserId = 0
,09-09 13:41:24.084  6937  7003 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:41:24.084  6937  7003 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[107]}
,09-09 13:41:24.094  6937  7003 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 13:41:24.094  6937  7003 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 13:41:24.094  6937  7003 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@273208f7
09-09 13:41:24.094  6937  7003 D BluetoothSocket: channel: 6
09-09 13:41:24.094  6937  7003 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-09 13:41:24.094  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 13:41:24.094  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:41:24.094  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-09 13:41:24.094  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-09 13:41:24.094  6937  6991 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 08 EC A9 50 75 41
,09-09 13:41:24.094  6937  6991 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 8, -20, -87, 80, 117, 65]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:41:24.094  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 8, -20, -87, 80, 117, 65]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:41:24.094  6937  6991 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-09 13:41:24.104  2789  2851 D BtGatt.GattService: registerClient() - UUID=daea6a66-033f-40f5-9d50-539749d62dbb
,09-09 13:41:24.154  2789  2849 D BtGatt.GattService: onClientRegistered() - UUID=daea6a66-033f-40f5-9d50-539749d62dbb, clientIf=6,
09-09 13:41:24.154  6937  6945 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
09-09 13:41:24.154  2789  2962 D BtGatt.AdvertiseManager: message : 0
,09-09 13:41:24.154  2789  2962 D BtGatt.AdvertiseManager: number of adv instance running0
09-09 13:41:24.154  2789  2962 D BtGatt.AdvertiseManager: size of list is =0
,09-09 13:41:24.154  2789  2962 D BtGatt.AdvertiseManager: starting advertising
09-09 13:41:24.154  2789  2962 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-09 13:41:24.174  2789  2849 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-09 13:41:24.174  2789  2962 D BtGatt.AdvertiseManager: starting multi advertising
,09-09 13:41:24.174  2789  2849 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-09 13:41:24.174  2789  2962 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-09 13:41:24.174  2789  2962 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-09 13:41:24.174  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-09 13:41:24.184  6937  6991 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 13:41:24.184  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:41:24.184  6937  6937 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 13:41:24.184  6937  6991 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 13:41:24.194  6937  6937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-09 13:41:24.194  6937  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-09 13:41:24.194  6937  6937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-09 13:41:24.194  6937  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-09 13:41:24.194  6937  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-09 13:41:24.194  6937  6937 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:41:24.194  6937  6937 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:41:24.204  6937  6991 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 13:41:24.204  6937  6991 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-09 13:41:24.204  6937  6991 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-09 13:41:24.204  6937  6991 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-09 13:41:24.204  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 13:41:24.204  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-09 13:41:24.204  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-09 13:41:24.204  6937  6991 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1b1459cd, channel: 6, state: LISTENING
,09-09 13:41:24.204  6937  6991 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1b1459cd, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@273208f7, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3c94e282mSocket: android.net.LocalSocket@1af43d93 impl:android.net.LocalSocketImpl@177331d0 fd:FileDescriptor[107]
,09-09 13:41:24.204  6937  6991 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1af43d93 impl:android.net.LocalSocketImpl@177331d0 fd:FileDescriptor[107]
,09-09 13:41:24.204  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 13:41:24.204  6937  6991 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:41:24.204  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 13:41:24.204  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:41:24.204  6937  6991 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:41:24.204  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 13:41:24.204  6937  6937 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 13:41:24.204  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-09 13:41:24.214  6937  7003 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1b1459cd, channel: 6, state: CLOSED,
09-09 13:41:24.214  6937  7003 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 13:41:24.214  6937  7003 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-09 13:41:24.214  6937  7003 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-09 13:41:24.214  6937  6991 D BluetoothLeScanner: could not find callback wrapper
09-09 13:41:24.214  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 13:41:24.214  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-09 13:41:24.214  2789  2962 D BtGatt.AdvertiseManager: message : 1
,09-09 13:41:24.214  2789  2962 D BtGatt.AdvertiseManager: stop advertise for client 6,
09-09 13:41:24.214  2789  2962 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6
,09-09 13:41:24.214  2789  2962 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-09 13:41:24.224  2789  2849 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,09-09 13:41:24.224  2789  2849 D BtGatt.GattService: Client app is not null!
,09-09 13:41:24.224  2789  2806 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-09 13:41:24.224  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 13:41:24.224  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-09 13:41:24.224  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-09 13:41:24.224  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-09 13:41:24.234  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-09 13:41:24.234  6937  6991 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:41:24.234  6937  6991 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-09 13:41:24.234  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 13:41:24.234  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:41:24.234  6937  6937 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 13:41:24.234  6937  6937 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 13:41:24.234  6937  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:41:24.234  6937  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:41:24.244  6937  6937 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 13:41:24.244  6937  6937 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:41:24.244  6937  6991 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-09 13:41:24.244  6937  6991 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-09 13:41:24.244  6937  6991 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
09-09 13:41:24.244  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
,09-09 13:41:24.244  6937  6991 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:41:24.244  6937  6991 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-09 13:41:24.244  6937  6991 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:41:24.244  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:24.244  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-09 13:41:24.244  6937  6991 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 13:41:24.244  6937  6991 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-09 13:41:24.244  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:41:24.244  6937  6937 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 13:41:24.244  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-09 13:41:24.244  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:24.244  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 13:41:24.244  6937  6991 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 13:41:24.254  6937  7007 D BluetoothSocket: bindListen(): myUserId = 0
,09-09 13:41:24.254  6937  7007 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:41:24.254  6937  7007 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[107]}
,09-09 13:41:24.254  6937  7007 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 13:41:24.254  6937  7007 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,09-09 13:41:24.254  6937  7007 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@269b1fef
,09-09 13:41:24.254  6937  7007 D BluetoothSocket: channel: 6
09-09 13:41:24.254  6937  7007 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-09 13:41:24.264  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 13:41:24.264  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:41:24.264  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-09 13:41:24.264  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-09 13:41:24.264  6937  6991 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 08 EC A9 50 75 41
,09-09 13:41:24.264  6937  6991 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 8, -20, -87, 80, 117, 65]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-09 13:41:24.264  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 8, -20, -87, 80, 117, 65]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:41:24.264  6937  6991 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-09 13:41:24.264  2789  2912 D BtGatt.GattService: registerClient() - UUID=afb5b815-5158-4fb0-90ba-e15cd2c68584
,09-09 13:41:24.314  2789  2849 D BtGatt.GattService: onClientRegistered() - UUID=afb5b815-5158-4fb0-90ba-e15cd2c68584, clientIf=6
,09-09 13:41:24.314  6937  6945 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-09 13:41:24.314  2789  2962 D BtGatt.AdvertiseManager: message : 0
,09-09 13:41:24.314  2789  2962 D BtGatt.AdvertiseManager: number of adv instance running0
,09-09 13:41:24.314  2789  2962 D BtGatt.AdvertiseManager: size of list is =0
,09-09 13:41:24.314  2789  2962 D BtGatt.AdvertiseManager: starting advertising
,09-09 13:41:24.314  2789  2962 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-09 13:41:24.324  2789  2849 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-09 13:41:24.324  2789  2962 D BtGatt.AdvertiseManager: starting multi advertising
,09-09 13:41:24.334  2789  2849 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-09 13:41:24.334  2789  2962 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-09 13:41:24.334  2789  2962 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-09 13:41:24.334  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-09 13:41:24.334  6937  6991 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 13:41:24.334  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:41:24.344  6937  6937 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 13:41:24.344  6937  6937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-09 13:41:24.344  6937  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-09 13:41:24.344  6937  6937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-09 13:41:24.344  6937  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-09 13:41:24.344  6937  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-09 13:41:24.344  6937  6991 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 13:41:24.344  6937  6937 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:41:24.344  6937  6937 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:41:24.654   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 13:41:24.844  6937  6937 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-09 13:41:24.844  6937  6937 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-09 13:41:24.844  6937  6937 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 13:41:24.844  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:41:24.844  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 13:41:24.844  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 13:41:24.844  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 13:41:24.844  6937  6991 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@deff585, channel: 6, state: LISTENING
09-09 13:41:24.844  6937  6991 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@deff585, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@269b1fef, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@35d83fdamSocket: android.net.LocalSocket@d23cc0b impl:android.net.LocalSocketImpl@1beb6ae8 fd:FileDescriptor[107]
09-09 13:41:24.844  6937  6991 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@d23cc0b impl:android.net.LocalSocketImpl@1beb6ae8 fd:FileDescriptor[107]
,09-09 13:41:24.844  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 13:41:24.844  6937  7007 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@deff585, channel: 6, state: CLOSED
09-09 13:41:24.844  6937  7007 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 13:41:24.844  6937  7007 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 13:41:24.844  6937  7007 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 13:41:24.854  6937  6937 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-09 13:41:24.854  6937  6991 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:41:24.854  6937  6991 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@259782a not in the list
09-09 13:41:24.854  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:41:24.854  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:41:24.854  6937  6991 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:41:24.854  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:41:24.854  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-09 13:41:24.854  6937  6937 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 13:41:24.854  6937  6991 D BluetoothLeScanner: could not find callback wrapper
,09-09 13:41:24.854  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 13:41:24.854  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-09 13:41:24.854  2789  2962 D BtGatt.AdvertiseManager: message : 1
,09-09 13:41:24.854  2789  2962 D BtGatt.AdvertiseManager: stop advertise for client 6
,09-09 13:41:24.854  2789  2962 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6
,09-09 13:41:24.854  2789  2962 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-09 13:41:24.864  2789  2849 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,09-09 13:41:24.864  2789  2849 D BtGatt.GattService: Client app is not null!
,09-09 13:41:24.864  2789  2913 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-09 13:41:24.864  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 13:41:24.864  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-09 13:41:24.864  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-09 13:41:24.864  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-09 13:41:24.874  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-09 13:41:24.874  6937  6991 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:41:24.874  6937  6991 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-09 13:41:24.874  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 13:41:24.874  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:41:24.874  6937  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:41:24.874  6937  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:41:24.874  6937  6937 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:41:24.874  6937  6991 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d31261b not in the list
,09-09 13:41:24.874  6937  6991 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:41:24.874  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:24.884  6937  6991 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-09 13:41:24.884  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:24.884  6937  6991 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:24.884  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:24.884  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:24.884  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:24.884  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:24.884  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:24.884  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
,09-09 13:41:24.884  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:24.894  6937  6991 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:41:24.894  6937  6991 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:41:24.894  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:24.894  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:24.894  6937  6991 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
09-09 13:41:24.894  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
,09-09 13:41:24.904  6937  6991 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything,
,09-09 13:41:24.904  6937  6991 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-09 13:41:24.904  6937  6991 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-09 13:41:24.904  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:24.904  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-09 13:41:24.904  6937  6991 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true,
09-09 13:41:24.904  6937  6991 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 13:41:24.904  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:41:24.904  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true,
,09-09 13:41:24.904  6937  6937 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 13:41:24.904  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:24.904  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 13:41:24.914  6937  6991 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 13:41:24.914  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
09-09 13:41:24.914  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:41:24.914  6937  7010 D BluetoothSocket: bindListen(): myUserId = 0
09-09 13:41:24.914  6937  7010 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:41:24.924  6937  7010 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[107]},
09-09 13:41:24.924  6937  7010 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 13:41:24.924  6937  7010 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 13:41:24.924  6937  7010 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2c804d94
09-09 13:41:24.924  6937  7010 D BluetoothSocket: channel: 6
09-09 13:41:24.924  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-09 13:41:24.924  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-09 13:41:24.924  6937  7010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-09 13:41:24.924  6937  6991 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 08 EC A9 50 75 41
09-09 13:41:24.924  6937  6991 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 8, -20, -87, 80, 117, 65]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:41:24.924  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 8, -20, -87, 80, 117, 65]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:41:24.924  6937  6991 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-09 13:41:24.924  2789  2912 D BtGatt.GattService: registerClient() - UUID=70ea9d01-614c-4d49-970c-f1a5aa1f7b04
,09-09 13:41:24.964  2789  2849 D BtGatt.GattService: onClientRegistered() - UUID=70ea9d01-614c-4d49-970c-f1a5aa1f7b04, clientIf=6
,09-09 13:41:24.964  6937  6946 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-09 13:41:24.964  2789  2962 D BtGatt.AdvertiseManager: message : 0
,09-09 13:41:24.964  2789  2962 D BtGatt.AdvertiseManager: number of adv instance running0
,09-09 13:41:24.964  2789  2962 D BtGatt.AdvertiseManager: size of list is =0
,09-09 13:41:24.974  2789  2962 D BtGatt.AdvertiseManager: starting advertising
,09-09 13:41:24.974  2789  2962 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-09 13:41:24.974  2789  2849 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-09 13:41:24.984  2789  2962 D BtGatt.AdvertiseManager: starting multi advertising
,09-09 13:41:24.984  2789  2849 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-09 13:41:24.984  2789  2962 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-09 13:41:24.984  2789  2962 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-09 13:41:24.984  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-09 13:41:24.984  6937  6991 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 13:41:24.994  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:41:24.994  6937  6937 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 13:41:24.994  6937  6937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-09 13:41:24.994  6937  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-09 13:41:24.994  6937  6937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-09 13:41:24.994  6937  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-09 13:41:24.994  6937  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-09 13:41:25.004  6937  6991 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 13:41:25.004  6937  6937 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:41:25.004  6937  6937 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:41:25.004  6937  6991 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 13:41:25.004  6937  6991 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 13:41:25.004  6937  6991 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-09 13:41:25.004  6937  6991 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 13:41:25.004  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 13:41:25.004  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 13:41:25.004  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 13:41:25.004  6937  6991 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2cef032, channel: 6, state: LISTENING
09-09 13:41:25.004  6937  6991 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2cef032, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2c804d94, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@37f7b183mSocket: android.net.LocalSocket@1adeaf00 impl:android.net.LocalSocketImpl@2422b339 fd:FileDescriptor[107]
09-09 13:41:25.004  6937  6991 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1adeaf00 impl:android.net.LocalSocketImpl@2422b339 fd:FileDescriptor[107]
09-09 13:41:25.004  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 13:41:25.004  6937  6991 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:41:25.004  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 13:41:25.004  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:41:25.004  6937  6991 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:41:25.004  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:41:25.004  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-09 13:41:25.004  6937  7010 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2cef032, channel: 6, state: CLOSED
09-09 13:41:25.004  6937  7010 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 13:41:25.004  6937  7010 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 13:41:25.004  6937  7010 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 13:41:25.004  6937  6991 D BluetoothLeScanner: could not find callback wrapper
09-09 13:41:25.004  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 13:41:25.004  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-09 13:41:25.004  6937  6937 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 13:41:25.004  2789  2962 D BtGatt.AdvertiseManager: message : 1
09-09 13:41:25.004  2789  2962 D BtGatt.AdvertiseManager: stop advertise for client 6
09-09 13:41:25.004  2789  2962 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6
09-09 13:41:25.014  2789  2962 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
09-09 13:41:25.014  2789  2849 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
09-09 13:41:25.014  2789  2849 D BtGatt.GattService: Client app is not null!
09-09 13:41:25.014  2789  2803 D BtGatt.GattService: unregisterClient() - clientIf=6
09-09 13:41:25.014  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 13:41:25.024  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-09 13:41:25.024  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-09 13:41:25.024  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-09 13:41:25.024  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-09 13:41:25.024  6937  6991 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:41:25.024  6937  6991 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 13:41:25.024  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:41:25.024  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:25.024  6937  6937 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 13:41:25.024  6937  6937 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-09 13:41:25.024  6937  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:41:25.024  6937  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:41:25.024  6937  6937 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 13:41:25.024  6937  6937 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:41:25.034  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:25.034  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.034  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:25.034  6937  6991 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@259782a not in the list
09-09 13:41:25.034  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:25.034  6937  6991 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d31261b not in the list
09-09 13:41:25.034  6937  6991 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:25.034  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:25.034  6937  6991 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-09 13:41:25.034  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:25.034  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.044  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:25.044  6937  6991 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@259782a not in the list
09-09 13:41:25.044  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:25.044  6937  6991 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d31261b not in the list
09-09 13:41:25.044  6937  6991 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:25.044  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:41:25.044  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:25.044  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 13:41:25.044  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:25.044  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.044  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:25.044  6937  6991 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@259782a not in the list
09-09 13:41:25.044  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:25.044  6937  6991 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d31261b not in the list
09-09 13:41:25.044  6937  6991 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:25.044  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.044  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:25.044  6937  6991 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-09 13:41:25.044  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:25.044  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.044  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:25.044  6937  6991 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@259782a not in the list
09-09 13:41:25.044  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:25.044  6937  6991 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d31261b not in the list
09-09 13:41:25.044  6937  6991 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:25.044  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.044  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:25.044  6937  6991 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-09 13:41:25.044  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:25.044  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.044  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:25.044  6937  6991 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@259782a not in the list
09-09 13:41:25.044  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:25.044  6937  6991 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d31261b not in the list
09-09 13:41:25.044  6937  6991 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:25.044  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.044  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:25.054  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 13:41:25.054  6937  6991 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:41:25.054  6937  6991 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:41:25.054  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 13:41:25.054  6937  6991 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:41:25.054  6937  6991 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:41:25.054  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 13:41:25.054  6937  6991 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:41:25.054  6937  6991 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:41:25.054  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:25.054  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.054  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:25.054  6937  6991 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@259782a not in the list
09-09 13:41:25.054  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:25.054  6937  6991 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d31261b not in the list
09-09 13:41:25.054  6937  6991 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:25.054  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.054  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:25.054  6937  6991 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:41:25.054  6937  6991 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 13:41:25.054  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-09 13:41:25.054  6937  6991 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:41:25.054  6937  6991 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-09 13:41:25.054  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 13:41:25.054  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 13:41:25.054  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 13:41:25.054  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 13:41:25.054  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 13:41:25.054  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 13:41:25.054  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 13:41:25.054  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 13:41:25.054  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 13:41:25.054  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 13:41:25.054  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 13:41:25.054  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 13:41:25.054  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 13:41:25.054  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 13:41:25.054  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 13:41:25.054  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 13:41:25.054  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 13:41:25.054  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 13:41:25.054  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 13:41:25.054  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 13:41:25.054  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 13:41:25.054  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 13:41:25.054  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 13:41:25.054  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 13:41:25.054  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 13:41:25.054  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 13:41:25.054  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 13:41:25.054  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 13:41:25.054  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 13:41:25.054  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 13:41:25.054  6937  6991 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-09 13:41:25.054  6937  6991 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 13:41:25.054  6937  6991 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-09 13:41:25.054  6937  6991 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:41:25.054  6937  6991 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 13:41:25.054  6937  6991 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-09 13:41:25.054  6937  6991 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:41:25.054  6937  6991 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 13:41:25.054  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-09 13:41:25.064  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-09 13:41:25.064  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-09 13:41:25.064  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-09 13:41:25.064  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-09 13:41:25.064  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-09 13:41:25.064  6937  6991 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-09 13:41:25.064  6937  6991 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:41:25.064  6937  6991 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-09 13:41:25.064  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:25.064  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.064  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:25.064  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-09 13:41:25.064  6937  7014 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1410)
09-09 13:41:25.064  6937  6991 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@259782a not in the list
09-09 13:41:25.064  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:25.064  6937  6991 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d31261b not in the list
09-09 13:41:25.064  6937  6991 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:25.064  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.064  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:25.064  6937  6991 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-09 13:41:25.064  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:25.064  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.064  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:25.064  6937  6991 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@259782a not in the list
09-09 13:41:25.064  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:25.064  6937  6991 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d31261b not in the list
09-09 13:41:25.064  6937  6991 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:25.064  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.064  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:25.064  6937  7015 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1410
09-09 13:41:25.064  6937  6991 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-09 13:41:25.074  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:25.074  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.074  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:25.074  6937  6991 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@259782a not in the list
09-09 13:41:25.074  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:25.074  6937  6991 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d31261b not in the list
09-09 13:41:25.074  6937  6991 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:25.074  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.074  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:25.074  6937  6991 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-09 13:41:25.074  6937  6991 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-09 13:41:25.074  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 13:41:25.074  6937  6991 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-09 13:41:25.074  6937  6991 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 13:41:25.074  6937  6991 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-09 13:41:25.074  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 13:41:25.074  6937  6991 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-09 13:41:25.074  6937  6991 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 13:41:25.074  6937  6991 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 13:41:25.074  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 13:41:25.074  6937  6991 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-09 13:41:25.074  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:25.074  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.074  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:25.074  6937  6991 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@259782a not in the list
09-09 13:41:25.074  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:25.074  6937  6991 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d31261b not in the list
09-09 13:41:25.074  6937  6991 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:25.074  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.074  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:25.074  6937  6991 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-09 13:41:25.074  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:25.074  6937  7014 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
09-09 13:41:25.074  6937  7014 D BluetoothSocket: connect(): myUserId = 0
09-09 13:41:25.074  6937  7014 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:41:25.084  2789  2913 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:25.084  6937  7014 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[108]}
09-09 13:41:25.084  6937  6991 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:25.084  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:25.084  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:25.084  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:25.084  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:25.084  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:25.084  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:25.084  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:25.084  6937  6991 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:25.084  6937  6991 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:41:25.084  6937  6991 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
09-09 13:41:25.084  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
09-09 13:41:25.084  6937  6991 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:41:25.084  6937  6991 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-09 13:41:25.084  6937  6991 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:41:25.084  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:25.084  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:25.084  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 13:41:25.084  6937  6991 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 13:41:25.084  6937  6991 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 13:41:25.084  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:41:25.084  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-09 13:41:25.084  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:25.084  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:41:25.094  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:25.094  6937  6937 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 13:41:25.094  6937  6991 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 13:41:25.094  6937  7016 D BluetoothSocket: bindListen(): myUserId = 0
09-09 13:41:25.094  6937  7016 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:41:25.094  6937  7016 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[109]}
09-09 13:41:25.094  6937  7016 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 13:41:25.094  6937  7016 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 13:41:25.094  6937  7016 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@24f249f5
09-09 13:41:25.094  6937  7016 D BluetoothSocket: channel: 6
09-09 13:41:25.094  6937  7016 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-09 13:41:25.094  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 13:41:25.094  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 13:41:25.104  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-09 13:41:25.104  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-09 13:41:25.104  6937  6991 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 08 EC A9 50 75 41
09-09 13:41:25.104  6937  6991 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 8, -20, -87, 80, 117, 65]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:41:25.104  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 8, -20, -87, 80, 117, 65]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:41:25.104  6937  6991 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-09 13:41:25.104  2789  2806 D BtGatt.GattService: registerClient() - UUID=41cbaff7-595d-43de-8d30-0b4e50ba55e1
,09-09 13:41:25.144  2789  2849 D BtGatt.GattService: onClientRegistered() - UUID=41cbaff7-595d-43de-8d30-0b4e50ba55e1, clientIf=6
,09-09 13:41:25.144  6937  6946 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-09 13:41:25.144  2789  2962 D BtGatt.AdvertiseManager: message : 0
,09-09 13:41:25.144  2789  2962 D BtGatt.AdvertiseManager: number of adv instance running0
,09-09 13:41:25.144  2789  2962 D BtGatt.AdvertiseManager: size of list is =0
,09-09 13:41:25.154  2789  2962 D BtGatt.AdvertiseManager: starting advertising
,09-09 13:41:25.154  2789  2962 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-09 13:41:25.154  2789  2849 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-09 13:41:25.154  2789  2962 D BtGatt.AdvertiseManager: starting multi advertising
,09-09 13:41:25.154  2789  2849 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-09 13:41:25.154  2789  2962 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
09-09 13:41:25.154  2789  2962 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-09 13:41:25.154  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-09 13:41:25.154  6937  6991 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 13:41:25.164  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:41:25.164  6937  6937 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 13:41:25.164  6937  6937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-09 13:41:25.164  6937  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-09 13:41:25.164  6937  6937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-09 13:41:25.164  6937  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-09 13:41:25.164  6937  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-09 13:41:25.164  6937  6937 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:41:25.164  6937  6937 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:41:25.164  6937  6991 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 13:41:25.174  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
09-09 13:41:25.174  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 13:41:25.174  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 13:41:25.174  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 13:41:25.174  6937  6991 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@32c3cdfb, channel: 6, state: LISTENING
09-09 13:41:25.174  6937  6991 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@32c3cdfb, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@24f249f5, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@11435e18mSocket: android.net.LocalSocket@3eea9071 impl:android.net.LocalSocketImpl@2a481e56 fd:FileDescriptor[109]
,09-09 13:41:25.174  6937  6991 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3eea9071 impl:android.net.LocalSocketImpl@2a481e56 fd:FileDescriptor[109]
09-09 13:41:25.174  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 13:41:25.174  6937  6991 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:41:25.174  6937  6991 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@259782a not in the list
09-09 13:41:25.174  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:25.174  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:41:25.174  6937  6991 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:41:25.174  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 13:41:25.174  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 13:41:25.174  6937  6937 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 13:41:25.174  6937  7016 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@32c3cdfb, channel: 6, state: CLOSED
09-09 13:41:25.174  6937  7016 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 13:41:25.174  6937  7016 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 13:41:25.174  6937  7016 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-09 13:41:25.174  6937  6991 D BluetoothLeScanner: could not find callback wrapper
09-09 13:41:25.174  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 13:41:25.174  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-09 13:41:25.174  2789  2962 D BtGatt.AdvertiseManager: message : 1
,09-09 13:41:25.174  2789  2962 D BtGatt.AdvertiseManager: stop advertise for client 6
09-09 13:41:25.174  2789  2962 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6
,09-09 13:41:25.174  2789  2962 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-09 13:41:25.174  2789  2849 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,09-09 13:41:25.174  2789  2849 D BtGatt.GattService: Client app is not null!
,09-09 13:41:25.174  2789  2912 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-09 13:41:25.184  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 13:41:25.184  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-09 13:41:25.184  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-09 13:41:25.184  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-09 13:41:25.184  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-09 13:41:25.184  6937  6991 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:41:25.184  6937  6991 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 13:41:25.184  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 13:41:25.184  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:41:25.184  6937  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:41:25.184  6937  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:41:25.184  6937  6937 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-09 13:41:25.184  6937  6937 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:41:25.184  6937  6991 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d31261b not in the list
09-09 13:41:25.184  6937  6991 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:25.184  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:25.184  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:41:25.184  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:41:25.184  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:25.184  6937  6991 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@259782a not in the list
09-09 13:41:25.184  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:25.184  6937  6991 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d31261b not in the list
09-09 13:41:25.184  6937  6991 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:25.184  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:41:25.184  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:25.194  6937  6991 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-09 13:41:25.194  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:25.194  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-09 13:41:25.194  6937  6991 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 13:41:25.194  6937  6991 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 13:41:25.194  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:41:25.194  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 13:41:25.194  6937  6937 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 13:41:25.194  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:25.194  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 13:41:25.194  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 13:41:25.194  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 13:41:25.194  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:25.194  6937  6991 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:41:25.194  6937  6991 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@259782a not in the list
09-09 13:41:25.194  6937  6937 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 13:41:25.194  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:25.194  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:41:25.194  6937  6991 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:41:25.194  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:41:25.194  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.194  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:25.194  6937  7020 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 13:41:25.194  6937  7020 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 13:41:25.194  6937  6991 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:41:25.194  6937  6991 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d31261b not in the list
09-09 13:41:25.194  6937  6991 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:25.194  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.194  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:25.194  6937  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:41:25.194  6937  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:41:25.194  6937  6937 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 13:41:25.194  6937  6937 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false,, is advertising: false
09-09 13:41:25.194  6937  6991 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-09 13:41:25.194  6937  6991 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 13:41:25.194  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 13:41:25.194  6937  6991 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:41:25.194  6937  6991 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:41:25.194  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:25.194  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.194  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:25.194  6937  6991 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@259782a not in the list
09-09 13:41:25.194  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:25.194  6937  6991 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d31261b not in the list
09-09 13:41:25.194  6937  6991 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:25.194  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.194  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:25.204  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:41:25.204  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.204  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:25.204  6937  6991 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@259782a not in the list
09-09 13:41:25.204  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:25.204  6937  6991 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d31261b not in the list
,09-09 13:41:25.204  6937  6991 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:25.204  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.204  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:25.204  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:41:25.204  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.204  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:25.204  6937  6991 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@259782a not in the list
,09-09 13:41:25.204  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:25.204  6937  6991 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d31261b not in the list
09-09 13:41:25.204  6937  6991 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:25.204  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.204  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:25.204  6937  6991 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,09-09 13:41:25.204  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 13:41:25.204  6937  6991 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,09-09 13:41:25.204  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 13:41:25.204  6937  6991 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-09 13:41:25.204  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-09 13:41:25.204  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-09 13:41:25.204  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-09 13:41:25.214  6937  6991 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,09-09 13:41:25.214  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 13:41:25.214  6937  6991 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,09-09 13:41:25.214  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 13:41:25.214  6937  6991 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-09 13:41:25.214  6937  6991 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-09 13:41:25.214  6937  6991 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,09-09 13:41:25.214  6937  6991 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-09 13:41:25.214  6937  6991 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-09 13:41:25.214  6937  6991 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,09-09 13:41:25.214  6937  6991 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-09 13:41:25.214  6937  6991 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-09 13:41:25.214  6937  6991 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:41:25.214  6937  6991 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c1c43c4 added. We now have 3 listener(s)
,09-09 13:41:25.214  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-09 13:41:25.214  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:25.214  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:41:25.214  6937  6991 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:41:25.214  6937  6991 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1246c2ad added. We now have 3 listener(s)
09-09 13:41:25.214  6937  6991 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:41:25.224  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:41:25.224  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:25.224  6937  6991 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:25.224  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:25.224  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:25.224  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:25.224  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:25.224  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:25.224  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:25.224  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:25.224  6937  6991 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:41:25.224  6937  6991 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:41:25.234  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:25.234  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:25.234  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.234  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:25.234  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:41:25.234  6937  6991 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c1c43c4 removed from the list
09-09 13:41:25.234  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:25.234  6937  6991 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1246c2ad removed from the list
,09-09 13:41:25.234  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:25.234  6937  6991 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:25.234  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:25.234  6937  6991 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:41:25.234  6937  6991 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f780173 added. We now have 3 listener(s)
09-09 13:41:25.234  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-09 13:41:25.234  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:25.234  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:41:25.234  6937  6991 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:41:25.234  6937  6991 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187bd830 added. We now have 3 listener(s)
09-09 13:41:25.234  6937  6991 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:41:25.234  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:41:25.234  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:25.244  6937  6991 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:25.244  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:25.244  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:25.244  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:25.244  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:25.244  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:25.244  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:25.244  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:25.244  6937  6991 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:41:25.244  6937  6991 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:41:25.244  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:25.244  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:25.244  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:25.244  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:41:25.244  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:41:25.244  6937  6991 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f780173 removed from the list
09-09 13:41:25.244  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:25.244  6937  6991 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@187bd830 removed from the list
,09-09 13:41:25.244  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:25.244  6937  6991 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:41:25.254  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:25.254  6937  6991 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 13:41:25.254  6937  6991 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d14a22e added. We now have 3 listener(s)
,09-09 13:41:25.254  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-09 13:41:25.254  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:25.254  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 13:41:25.254  6937  6991 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:41:25.254  6937  6991 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c741cf added. We now have 3 listener(s)
,09-09 13:41:25.254  6937  6991 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:41:25.254  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:41:25.264  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:25.264  6937  6991 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:25.264  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:25.264  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:25.264  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:25.264  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:25.264  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:25.264  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:25.264  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true,
09-09 13:41:25.264  6937  6991 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:25.264  6937  6991 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:41:25.264  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-09 13:41:25.264  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:25.274  1014  1555 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-09 13:41:25.274  1014  1555 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-09 13:41:25.274  1014  1555 D SecContentProvider2: mCursor = null
09-09 13:41:25.274  1014  1555 D WifiService: setWifiEnabled: false pid=6937, uid=10170
,09-09 13:41:25.274  1014  1555 D SettingsProvider: name = wifi_on
,09-09 13:41:25.274  1014  1125 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-09 13:41:25.284  1369  1369 I wpa_supplicant: reset timer : RESET_TIMER 0
09-09 13:41:25.284  1369  1369 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
09-09 13:41:25.284  1369  1369 I wpa_supplicant: P2P: Current p2p state = IDLE
09-09 13:41:25.284  1369  1369 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-09 13:41:25.284  1014  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 13:41:25.304  1014  1125 E WifiNative-wlan0: do suspend true,
,09-09 13:41:25.464  1369  1369 I wpa_supplicant: Scan aborted because the firmware maybe busy.,
09-09 13:41:25.464  1369  1369 I wpa_supplicant: Therefore we will repeat the scan command after 1 seconds.
,09-09 13:41:25.464  1369  1369 I wpa_supplicant: wlan0: Setting scan request: 1 sec 0 usec
,09-09 13:41:25.464  1014  1124 D WifiP2pService: InactiveState{ what=143375 },
09-09 13:41:25.464  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-09 13:41:25.474  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-09 13:41:25.474  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-09 13:41:25.474  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:25.474  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:25.474  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:25.474  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:25.474   277  1002 D CommandListener: Clearing all IP addresses on wlan0
09-09 13:41:25.474  2635  2672 V NativeCrypto: Read error: ssl=0xb8162fb8: I/O error during system call, Connection timed out
,09-09 13:41:25.484  2635  2672 V NativeCrypto: SSL shutdown failed: ssl=0xb8162fb8: I/O error during system call, Broken pipe
,09-09 13:41:25.484  1014  1127 E ConnectivityService: updateNetworkInfo()
,09-09 13:41:25.484  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:25.484  1014  1127 E ConnectivityService: updateNetworkInfo()
09-09 13:41:25.484  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,09-09 13:41:25.494  1014  1556 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
09-09 13:41:25.494  1014  1783 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:25.494  1014  1783 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:25.494  1014  1783 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-09 13:41:25.494  1014  1783 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:25.494  1014  1783 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
09-09 13:41:25.494  1014  1783 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-09 13:41:25.494  1014  1783 I qtaguid : Tagging socket 358 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1014, getuid(): 1000
,09-09 13:41:25.494  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-09 13:41:25.514  1014  1783 I qtaguid : Untagging socket 358
09-09 13:41:25.514  1014  1783 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:41:25.524  1014  1124 D WifiP2pService: InactiveState{ what=131204 }
09-09 13:41:25.524  1014  1124 D WifiP2pService: P2pEnabledState{ what=131204 }
09-09 13:41:25.524  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 1
09-09 13:41:25.534  1014  1148 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:25.534  1014  1014 D RttService: SCAN_AVAILABLE : 1
09-09 13:41:25.534  1014  1149 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:25.534  1014  1125 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-09 13:41:25.534  1014  1502 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 13:41:25.534  1014  1502 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-09 13:41:25.534  1014  1502 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:25.534  1014  1502 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:25.534  1014  1502 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:41:25.534  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-09 13:41:25.544  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-09 13:41:25.544  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:41:25.544  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:41:25.544  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:25.544  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:25.544  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:25.544  1014  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:41:25.544  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:25.544  1014  1046 D WifiDisplayAdapter: onP2pDisconnected
,09-09 13:41:25.544  1609  1609 I Hs20UtilService: Starting #8
,09-09 13:41:25.554  1609  1661 I Hs20UtilService: Message received 5007
,09-09 13:41:25.554  1014  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 13:41:25.554  1014  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-09 13:41:25.554  4412  4412 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-09 13:41:25.554  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-09 13:41:25.564  4412  4412 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 13:41:25.564  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-09 13:41:25.564  4412  4412 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 13:41:25.564  4412  4412 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
,09-09 13:41:25.564  4412  4412 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 13:41:25.564  4412  4412 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 13:41:25.564  4412  4504 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-09 13:41:25.564  1014  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,09-09 13:41:25.564  1014  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 13:41:25.564  1014  1046 D WifiDisplayController: disconnect
09-09 13:41:25.564  1014  1046 D WifiDisplayController: updateConnection
09-09 13:41:25.564  1014  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,09-09 13:41:25.564  1014  1124 D WifiP2pService: P2pDisablingState
09-09 13:41:25.564  1014  1125 E WifiNative-wlan0: do suspend true
09-09 13:41:25.564  1014  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-09 13:41:25.564  1014  1124 D WifiP2pService: P2pDisablingState{ what=147458 }
09-09 13:41:25.564  1014  1124 D WifiP2pService: p2p socket connection lost
09-09 13:41:25.564  1014  1124 D WifiP2pService: P2pDisabledState
,09-09 13:41:25.574  1014  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-09 13:41:25.574  1014  1046 D WifiDisplayAdapter: onP2pDisconnected
09-09 13:41:25.574  1014  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 13:41:25.574  1014  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-09 13:41:25.574  1174  1174 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED,
,09-09 13:41:25.584  1014  1026 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0},
,09-09 13:41:25.584  1174  1174 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-09 13:41:25.584  1014  1555 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:25.584  1014  1555 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
09-09 13:41:25.584  1014  1555 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:25.584  1014  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,09-09 13:41:25.584  1014  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-09 13:41:25.584  1014  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-09 13:41:25.584  1014  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:25.584  1014  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:25.604  7028  7028 E Zygote  : MountEmulatedStorage()
,09-09 13:41:25.604  7028  7028 E Zygote  : v2
09-09 13:41:25.604  7028  7028 I libpersona: KNOX_SDCARD checking this for 10102
09-09 13:41:25.604  7028  7028 I libpersona: KNOX_SDCARD not a persona
09-09 13:41:25.604  1014  1555 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7028 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-09 13:41:25.604  7028  7028 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:41:25.604  7028  7028 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-09 13:41:25.604  7028  7028 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-09 13:41:25.624  1014  1124 D WifiP2pService: P2pDisabledState{ what=143375 }
09-09 13:41:25.624  1014  1124 D WifiP2pService: DefaultState{ what=143375 },
,09-09 13:41:25.624  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-09 13:41:25.624  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:41:25.624  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:41:25.634  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:25.634  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:25.634  7028  7028 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:41:25.634  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:25.634  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:25.634   277  1002 D CommandListener: Clearing all IP addresses on wlan0
,09-09 13:41:25.634   277   998 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-09 13:41:25.634   277   998 D Netd    : getNetworkForDns: using netid 0 for uid 1000
09-09 13:41:25.634  7028  7028 D ActivityThread: Added TimaKeyStore provider
09-09 13:41:25.634  1014  1127 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-09 13:41:25.634  1014  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:25.634  1014  1127 V NetworkStats: updateIfacesLocked()
09-09 13:41:25.634  1014  1127 V NetworkStats: performPollLocked(flags=0x1)
,09-09 13:41:25.634  1014  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:41:25.634  1014  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-09 13:41:25.634  1014  1783 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
09-09 13:41:25.634  1014  1783 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-09 13:41:25.634  1014  1127 V NetworkStats: performPollLocked() took 4ms
,09-09 13:41:25.634  1014  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:25.644  1369  1369 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-09 13:41:25.644  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-09 13:41:25.644   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 13:41:25.654  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-09 13:41:25.654  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:41:25.654  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:41:25.654  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:25.654  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:25.654  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:25.654  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:25.654  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:41:25.654  1014  1125 D SecContentProvider2: mCursor = null
,09-09 13:41:25.664  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-09 13:41:25.664  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:41:25.664  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-09 13:41:25.664  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:25.664  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:25.664  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:25.664  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:25.664  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:25.664  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
09-09 13:41:25.664  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:41:25.664  1174  1720 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-09 13:41:25.664  1174  1174 D HotspotTile: onReceive : 0, 0
09-09 13:41:25.664  4412  4412 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:41:25.664  1014  1127 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,09-09 13:41:25.664  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:25.664  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:25.664  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:25.664  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:25.664  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:25.664  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:41:25.664  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:25.664  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:25.664  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:25.664  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:25.674  7028  7028 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-09 13:41:25.674  1174  1688 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-09 13:41:25.674  1014  1127 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-09 13:41:25.674  1014  1124 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-09 13:41:25.674  1477  1477 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-09 13:41:25.674  1014  1127 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
09-09 13:41:25.674  1014  1127 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
09-09 13:41:25.674  1014  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 13:41:25.674  1014  1783 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:25.674  1477  1477 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-09 13:41:25.674  1014  1125 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-09 13:41:25.674  1014  1014 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-09 13:41:25.674  1014  1122 V NetworkStats: updateIfacesLocked()
09-09 13:41:25.674  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:25.674  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
,09-09 13:41:25.684  6937  6937 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:41:25.684  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:41:25.684  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 13:41:25.684  1014  1128 D Tethering: MasterInitialState.processMessage what=3
,09-09 13:41:25.684  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:25.684  1014  1122 V NetworkStats: performPollLocked() took 4ms
,09-09 13:41:25.684  1014  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-09 13:41:25.684  1014  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-09 13:41:25.684  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:25.684  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:25.684  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:25.684  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:41:25.684  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:25.684  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:25.684  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:25.684  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:41:25.694  1014  1127 D ConnectivityService: nai.networkMonitor.doQuit()
09-09 13:41:25.694  1014  1127 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-09 13:41:25.694  1014  1127 E ConnectivityService: updateNetworkInfo()
,09-09 13:41:25.694  1014  1127 E ConnectivityService: updateNetworkInfo()
09-09 13:41:25.694  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-09 13:41:25.694  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:25.694  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:25.694  1174  1174 D StatusBar.NetworkController: EthernetConnected: false
09-09 13:41:25.694  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-09 13:41:25.694  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-09 13:41:25.694  1174  1174 D StatusBar.NetworkController: updateDataNetType()
,09-09 13:41:25.694  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:25.694  1014  1123 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-09 13:41:25.694  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:25.694  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:25.694  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:25.704  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-09 13:41:25.704  1174  1174 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-09 13:41:25.704  1174  1174 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-09 13:41:25.704  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 21 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
09-09 13:41:25.704  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
09-09 13:41:25.704  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,09-09 13:41:25.704  6937  6937 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:41:25.704  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-09 13:41:25.704  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:41:25.704  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-09 13:41:25.704  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:25.704  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:25.704  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:25.704  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:25.714  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:25.714  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:25.714  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:25.714  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:41:25.714  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:25.714  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:25.714  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:25.714  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:41:25.714  6937  6937 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:41:25.714  6937  6937 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 13:41:25.764  1477  1477 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-09 13:41:25.764  1369  1369 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 13:41:25.764  1477  1477 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:41:25.774  1477  1477 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:41:25.774  1477  1477 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-09 13:41:25.774  1477  1477 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:41:25.774  1477  1477 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:41:25.774  1477  1477 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:41:25.774  1477  1477 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:41:25.774  1477  1477 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:41:25.784  1477  1477 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:41:25.784  1477  1477 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:41:25.784  1477  1477 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:41:25.784  1477  1477 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:41:25.784  1477  1477 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-09 13:41:25.784  1477  1477 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:41:25.784  1477  1477 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:41:25.784  1477  1477 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:41:25.794  1014  1557 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-09 13:41:25.794  1014  1557 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-09 13:41:25.794  1014  1557 D SecContentProvider2: mCursor = null
09-09 13:41:25.794  1477  1477 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:41:25.794  1477  1477 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:41:25.794  1014  1557 D WifiService: setWifiEnabled: true pid=6937, uid=10170
09-09 13:41:25.794  1014  1557 W ActivityManager: Permission Denial: getCurrentUser() from pid=6937, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-09 13:41:25.794  1477  1477 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:41:25.794  1477  1477 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:41:25.794  1477  1477 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:41:25.794  1477  1477 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:41:25.794  1477  1477 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:41:25.794  1014  1557 W WifiService: Failed getting userId using ActivityManagerNative
09-09 13:41:25.794  1014  1557 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6937, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-09 13:41:25.794  1014  1557 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-09 13:41:25.794  1014  1557 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-09 13:41:25.794  1014  1557 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-09 13:41:25.794  1014  1557 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-09 13:41:25.794  1014  1557 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-09 13:41:25.794  1014  1557 D SettingsProvider: name = wifi_on
,09-09 13:41:25.794  1477  1477 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:41:25.804  1477  1477 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:41:25.804  1477  1477 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:41:25.804  1477  1477 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:41:25.804  1477  1477 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:41:25.804  1477  1477 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:41:25.824  1369  1369 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-09 13:41:25.824  1014  1043 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 13:41:25.824  1014  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 13:41:25.824  1014  1043 D Tethering: interfaceStatusChanged p2p0, false
,09-09 13:41:25.904  7028  7068 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,09-09 13:41:25.904  7028  7068 I Babel_SMS: MmsConfig.loadMmsSettings
09-09 13:41:25.904  7028  7068 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
09-09 13:41:25.904  7028  7068 I Babel_SMS: MmsConfig.loadFromDatabase
,09-09 13:41:25.924  7028  7068 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
09-09 13:41:25.924  7028  7068 I Babel_SMS: MmsConfig.loadFromResources
,09-09 13:41:25.924  7028  7068 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-09 13:41:25.924  7028  7068 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,09-09 13:41:25.944  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:41:25.944  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:41:25.944  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
,09-09 13:41:25.944  1014  1128 D Tethering: InitialState.processMessage what=4
,09-09 13:41:25.944  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:41:25.944  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:41:25.944  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
09-09 13:41:25.944  1369  1369 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,09-09 13:41:25.944  1369  1369 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-09 13:41:25.944  1014  1128 E Tethering: No numeric data,
,09-09 13:41:25.954  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:41:25.944  1014  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 13:41:25.954  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
09-09 13:41:25.944  1014  1128 D Tethering: clearTetheredNotification()
09-09 13:41:25.954  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-09 13:41:25.944  1369  1369 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-09 13:41:25.954  1174  1174 D HotspotTile: updateTetherState():false, false
09-09 13:41:25.954  1369  1369 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-09 13:41:25.954  1014  1122 V NetworkStats: performPollLocked() took 3ms
09-09 13:41:25.954  1369  1369 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-09 13:41:25.954  1014  1213 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null,
09-09 13:41:25.954  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:41:25.954  1014  1213 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
09-09 13:41:25.954  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
09-09 13:41:25.954  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:25.954  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:41:25.954  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-09 13:41:25.954  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:25.954  1014  1213 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:25.954  1014  1213 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:25.954  1014  1213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-09 13:41:25.964  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:25.964  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:25.984  7028  7028 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:41:25.984  1014  2050 V SAMP_SPCM_test: CSC File load.. 
,09-09 13:41:25.994  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
09-09 13:41:25.994  7028  7028 I Babel_Crash: startup - clean
,09-09 13:41:25.994  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
,09-09 13:41:25.994  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
,09-09 13:41:25.994  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
09-09 13:41:25.994  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
09-09 13:41:25.994  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
,09-09 13:41:25.994  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
09-09 13:41:25.994  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
09-09 13:41:25.994  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
09-09 13:41:25.994  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
09-09 13:41:25.994  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
09-09 13:41:25.994  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
09-09 13:41:25.994  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
09-09 13:41:25.994  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
09-09 13:41:25.994  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
09-09 13:41:25.994  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
09-09 13:41:25.994  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
09-09 13:41:25.994  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
09-09 13:41:25.994  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
09-09 13:41:25.994  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
09-09 13:41:25.994  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under, uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
09-09 13:41:26.024  1014  2050 ,W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
09-09 13:41:26.024  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
09-09 13:41:26.034  1014  2050 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
09-09 13:41:26.044  1014  2050 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,09-09 13:41:26.064  4412  4412 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-09 13:41:26.064  4412  4412 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 13:41:26.074  4412  4412 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 13:41:26.074  4412  4412 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-09 13:41:26.074  4412  4412 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 13:41:26.074  4412  4412 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 13:41:26.074  4412  4504 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 13:41:26.074  1014  1328 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,09-09 13:41:26.074  1014  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:26.074  1014  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:26.074  1014  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:26.074  1014  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:26.094  7028  7028 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-09 13:41:26.094  7072  7072 E Zygote  : MountEmulatedStorage()
09-09 13:41:26.094  7072  7072 E Zygote  : v2
09-09 13:41:26.094  7072  7072 I libpersona: KNOX_SDCARD checking this for 10064
09-09 13:41:26.094  7072  7072 I libpersona: KNOX_SDCARD not a persona
,09-09 13:41:26.094  7072  7072 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 13:41:26.094  1014  1328 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7072 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:41:26.094  7072  7072 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-09 13:41:26.094  7072  7072 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:41:26.104  7028  7028 W AudioCapabilities: Unsupported mime audio/evrc,
09-09 13:41:26.104  7028  7028 W AudioCapabilities: Unsupported mime audio/qcelp
,09-09 13:41:26.114  7028  7028 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,09-09 13:41:26.114  7028  7028 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,09-09 13:41:26.124  7028  7028 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,09-09 13:41:26.124  7028  7028 W AudioCapabilities: Unsupported mime audio/x-ima
,09-09 13:41:26.124  7028  7028 W AudioCapabilities: Unsupported mime audio/qcelp
,09-09 13:41:26.124  7028  7028 W AudioCapabilities: Unsupported mime audio/evrc
,09-09 13:41:26.134  7072  7072 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:41:26.134  7072  7072 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:26.154  7072  7072 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-09 13:41:26.154  1369  1369 I wpa_supplicant: Blacklist: Clear (all) ,
,09-09 13:41:26.164  7028  7028 W VideoCapabilities: Unsupported mime video/wvc1
,09-09 13:41:26.164  7028  7028 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-09 13:41:26.174  7072  7072 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 13:41:26.174  7028  7028 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,09-09 13:41:26.174  7072  7072 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-09 13:41:26.174  7028  7028 W VideoCapabilities: Unsupported mime video/wvc1
,09-09 13:41:26.174  1014  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:26.174  7028  7028 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-09 13:41:26.184  7028  7028 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,09-09 13:41:26.184  7028  7028 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,09-09 13:41:26.184  7028  7028 W VideoCapabilities: Unsupported mime video/mp43
,09-09 13:41:26.184  1014  1014 I ApplicationPolicy: updateDataUsageMap
,09-09 13:41:26.204  7028  7028 W VideoCapabilities: Unsupported mime video/sorenson,
,09-09 13:41:26.204  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:26.204  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:26.204  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:26.204  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
,09-09 13:41:26.204  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true,
09-09 13:41:26.204  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:26.204  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:26.204  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:41:26.204  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:26.204  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:26.214  7028  7028 W VideoCapabilities: Unsupported mime video/mp4v-esdp
09-09 13:41:26.214  1369  1369 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-09 13:41:26.214  7072  7072 D FileShare-Client: Outbound.stopDelayTimer - 
,09-09 13:41:26.214  1014  1556 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,09-09 13:41:26.214  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:41:26.214  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:41:26.214  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
09-09 13:41:26.214  1014  1556 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:26.214  1014  1556 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:26.214  1014  1556 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:26.214  1014  1556 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:26.234  7087  7087 E Zygote  : MountEmulatedStorage()
,09-09 13:41:26.234  7087  7087 E Zygote  : v2
09-09 13:41:26.234  7087  7087 I libpersona: KNOX_SDCARD checking this for 10065
09-09 13:41:26.234  7087  7087 I libpersona: KNOX_SDCARD not a persona
,09-09 13:41:26.234  7087  7087 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-09 13:41:26.234  1014  1556 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7087 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:41:26.234  7087  7087 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 13:41:26.234  1014  1556 I ActivityManager: Killing 6580:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,09-09 13:41:26.234  7087  7087 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:41:26.244  7028  7028 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-09 13:41:26.264  7087  7087 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:41:26.264  7087  7087 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:26.284  7028  7028 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 13:41:26.284  7028  7028 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 13:41:26.284  7028  7028 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 13:41:26.294  7028  7028 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 13:41:26.294  7087  7087 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 13:41:26.294  1014  1027 I ActivityManager: Killing 6599:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,09-09 13:41:26.304  1014  1328 I ActivityManager: Killing 6616:com.wsomacp/u0a23 (adj 15): empty #21
,09-09 13:41:26.304  7028  7028 I vclib   : onServiceConnected
,09-09 13:41:26.304  1014  1026 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 13:41:26.304  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-09 13:41:26.304  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:26.304  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 13:41:26.304  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:41:26.314  1609  1609 I Hs20UtilService: Starting #9
,09-09 13:41:26.314  4412  4412 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-09 13:41:26.314  4412  4412 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-09 13:41:26.314  4412  4412 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 13:41:26.314  1609  1661 I Hs20UtilService: Message received 5007
,09-09 13:41:26.314  4412  4412 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-09 13:41:26.314  4412  4412 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 13:41:26.314  4412  4412 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-09 13:41:26.314  4412  4504 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 13:41:26.324  1014  1556 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 13:41:26.324  1014  1556 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:41:26.324  1014  1556 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:26.324  1014  1556 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:26.324  1014  1556 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:41:26.324  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,09-09 13:41:26.324  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-09 13:41:26.334  1609  1609 I Hs20UtilService: Starting #10
,09-09 13:41:26.334  7028  7028 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:26.334  1609  1661 I Hs20UtilService: Message received 5011
,09-09 13:41:26.334  6804  6804 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-09 13:41:26.334  6804  6804 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 13:41:26.334  6804  6804 D SecurityLogAgent: StateMachine : Current State = 1
,09-09 13:41:26.334  6804  6804 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 13:41:26.344  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-09 13:41:26.344  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 13:41:26.344  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-09 13:41:26.344  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:26.344  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:26.344  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:26.344  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:26.344  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:26.344  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:26.344  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,09-09 13:41:26.344  1174  1720 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-09 13:41:26.344  1174  1174 D HotspotTile: onReceive : 1, 0
,09-09 13:41:26.344  1748  2193 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:41:26.344  4412  4412 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:41:26.354  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:26.354  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:26.354  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:26.364  1014  1555 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:26.364  1014  1555 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:26.364  1014  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:41:26.364  1014  1040 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:26.384  1014  1094 V AlarmManager: waitForAlarm result :4
,09-09 13:41:26.534  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:26.534  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:26.534  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:41:26.544  1014  1014 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,09-09 13:41:26.544  1014  1014 V AlarmManagerEXT: <AppSync3 Whitelist>
,09-09 13:41:26.544  1014  1014 V AlarmManagerEXT: (AppSync) ### 0 added ###,
,09-09 13:41:26.544  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,09-09 13:41:26.544  1174  1174 D KeyguardUpdateMonitor: handleTimeUpdate
,09-09 13:41:26.554  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:26.554  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:26.554  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:41:26.554  1174  1174 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,09-09 13:41:26.554  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:26.554  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:26.554  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:41:26.554  1174  1174 D SecKeyguardClockView: HomeTimezone(): 1
,09-09 13:41:26.554  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:26.554  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:26.554  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:41:26.564  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:26.564  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:26.564  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:41:26.564  1174  1174 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-09 13:41:26.564  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:26.564  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:26.564  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:41:26.564  1174  1174 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
09-09 13:41:26.564  1174  1174 I KeyguardEffectViewController: *** don't update sliding image ***
,09-09 13:41:26.564  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:26.564  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:26.564  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:41:26.574  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:26.574  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:26.574  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:41:26.574  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:26.574  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:26.574  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:41:26.574  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:26.574  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:26.574  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:41:26.584  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:26.584  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:26.584  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:41:26.584  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:26.584  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:26.584  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:41:26.584  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:26.584  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:26.584  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:41:26.594  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:26.594  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:26.594  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:41:26.594  1014  1014 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-09 13:41:26.594  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:26.594  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:26.594  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:26.594  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:26.604  1014  1014 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7103 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
09-09 13:41:26.604  7103  7103 E Zygote  : MountEmulatedStorage()
09-09 13:41:26.604  7103  7103 I libpersona: KNOX_SDCARD checking this for 1000
09-09 13:41:26.604  7103  7103 E Zygote  : v2
09-09 13:41:26.604  7103  7103 I libpersona: KNOX_SDCARD not a persona,
09-09 13:41:26.604  7103  7103 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:41:26.614  7103  7103 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 13:41:26.614  7103  7103 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-09 13:41:26.614  1174  1174 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
09-09 13:41:26.614  1174  1174 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-09 13:41:26.624  1174  1174 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
09-09 13:41:26.624  1174  1174 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,09-09 13:41:26.634  1174  1174 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,09-09 13:41:26.644   287   287 E SMD     : DCD OFF
,09-09 13:41:26.644   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 13:41:26.644  7103  7103 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:41:26.644  7103  7103 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:26.664  7103  7103 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,09-09 13:41:26.674  7103  7103 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-09 13:41:26.674  7103  7103 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-09 13:41:26.684  7103  7103 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-09 13:41:26.684  7103  7103 I PCWCLIENTTRACE_PushUtil: sales region : global
09-09 13:41:26.684  7103  7103 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-09 13:41:26.684  7103  7103 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:26.684  1014  1027 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
09-09 13:41:26.684  1014  1027 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
09-09 13:41:26.684  1014  1027 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
09-09 13:41:26.684  1014  1027 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,09-09 13:41:26.684  1014  1027 I ActivityManager: Killing 6659:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
,09-09 13:41:26.694  7103  7118 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,09-09 13:41:26.694  1014  1014 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-09 13:41:26.694  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:26.694  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:26.694  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:26.694  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:26.704  7120  7120 E Zygote  : MountEmulatedStorage(),
,09-09 13:41:26.704  7120  7120 E Zygote  : v2
09-09 13:41:26.714  7120  7120 I libpersona: KNOX_SDCARD checking this for 10001
09-09 13:41:26.714  7120  7120 I libpersona: KNOX_SDCARD not a persona
,09-09 13:41:26.714  7120  7120 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:41:26.714  1014  1014 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7120 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
09-09 13:41:26.714  7120  7120 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 13:41:26.714  7120  7120 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:41:26.734  7120  7120 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:41:26.734  7120  7120 D ActivityThread: Added TimaKeyStore provider,
,09-09 13:41:26.784  1014  1557 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,09-09 13:41:26.784  1014  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:26.784  1014  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:26.784  1014  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:26.784  1014  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:26.804  7137  7137 E Zygote  : MountEmulatedStorage(),
09-09 13:41:26.804  7137  7137 E Zygote  : v2
09-09 13:41:26.804  7137  7137 I libpersona: KNOX_SDCARD checking this for 1000
09-09 13:41:26.804  7137  7137 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 13:41:26.804  7137  7137 I libpersona: KNOX_SDCARD not a persona
09-09 13:41:26.804  1014  1557 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7137 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-09 13:41:26.814  1014  1557 I ActivityManager: Killing 6683:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,09-09 13:41:26.814  7137  7137 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 13:41:26.814  7137  7137 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-09 13:41:26.844  7137  7137 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:41:26.844  7137  7137 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:26.884  7137  7137 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-09 13:41:26.984  1014  1043 D Tethering: interfaceRemoved wlan0
,09-09 13:41:26.984  1014  1043 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-09 13:41:27.014  7137  7137 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,09-09 13:41:27.024  7137  7137 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,09-09 13:41:27.024  7137  7137 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:27.024  7137  7137 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-09 13:41:27.024  7137  7137 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,09-09 13:41:27.024  7137  7137 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-09 13:41:27.024  1014  1557 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,09-09 13:41:27.024  1014  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:27.024  1014  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:27.024  1014  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:27.024  1014  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:27.044  1014  1557 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7152 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:41:27.044  1014  1557 I ActivityManager: Killing 6701:com.osp.app.signin/u0a36 (adj 15): empty #21
,09-09 13:41:27.044  7152  7152 E Zygote  : MountEmulatedStorage()
09-09 13:41:27.044  7152  7152 I libpersona: KNOX_SDCARD checking this for 10008
09-09 13:41:27.044  7152  7152 E Zygote  : v2
09-09 13:41:27.044  7152  7152 I libpersona: KNOX_SDCARD not a persona
,09-09 13:41:27.044  7152  7152 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:41:27.044  7152  7152 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 13:41:27.044  7152  7152 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-09 13:41:27.064  7152  7152 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:41:27.064  7152  7152 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:27.134  1014  1502 I ActivityManager: Killing 6374:com.android.mms/u0a41 (adj 15): empty #21
,09-09 13:41:27.134  1014  1026 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 13:41:27.134  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-09 13:41:27.134  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:27.134  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:27.144  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:27.154  1917  1917 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-09 13:41:27.164  1014  1555 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 13:41:27.164  1014  1555 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,09-09 13:41:27.164  1014  1555 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:27.164  1014  1555 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:27.164  1014  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:27.164  1917  4794 I iu.UploadsManager: num queued entries: 0
09-09 13:41:27.164  1917  4794 I iu.UploadsManager: num updated entries: 0
,09-09 13:41:27.164  1917  4794 I iu.SyncManager: NEXT; no task
,09-09 13:41:27.174  1917  1917 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 13:41:27.174  1917  1917 I Kids    : [GCoreUtils] Current gmscore version, 8115234 is smaller than the required version 8400000
,09-09 13:41:27.184  2917  2917 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Sep 09 13:41:27 GMT+02:00 2016
,09-09 13:41:27.184  1014  1555 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-09 13:41:27.184  1014  1555 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-09 13:41:27.184  1014  1555 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:27.184  1014  1555 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:27.184  1014  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-09 13:41:27.194  2917  2917 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-09 13:41:27.194  1014  1557 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,09-09 13:41:27.194  1014  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:27.194  1014  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:27.194  1014  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:27.194  1014  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:27.204  2917  2917 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
09-09 13:41:27.204  2917  2917 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
09-09 13:41:27.204  2917  2917 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
09-09 13:41:27.204  2917  7168 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
09-09 13:41:27.204  2917  7168 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-09 13:41:27.214  7169  7169 E Zygote  : MountEmulatedStorage()
09-09 13:41:27.214  7169  7169 E Zygote  : v2
09-09 13:41:27.214  7169  7169 I libpersona: KNOX_SDCARD checking this for 10031
09-09 13:41:27.214  7169  7169 I libpersona: KNOX_SDCARD not a persona
,09-09 13:41:27.214  7169  7169 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:41:27.214  1014  1557 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7169 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
09-09 13:41:27.214  2917  7168 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,09-09 13:41:27.214  7169  7169 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 13:41:27.214  2917  7168 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
09-09 13:41:27.214  7169  7169 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:41:27.224  2917  2917 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-09 13:41:27.244   305   305 I art     : Explicit concurrent mark sweep GC freed 8695(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 738us total 25.701ms
,09-09 13:41:27.254  7169  7169 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:41:27.254  7169  7169 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:27.264  1014  1216 D CountryDetector: No listener is left
,09-09 13:41:27.264   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 649us total 18.373ms
,09-09 13:41:27.264  1014  1043 D Tethering: interfaceRemoved p2p0
09-09 13:41:27.264  1014  1043 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-09 13:41:27.284   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 625us total 18.872ms
,09-09 13:41:27.294  7169  7169 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,09-09 13:41:27.294  1014  1556 I ActivityManager: Killing 6720:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,09-09 13:41:27.314  1014  1557 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-09 13:41:27.314  1014  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:27.314  1014  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:27.314  1014  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:27.314  1014  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:27.314  3494  7184 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,09-09 13:41:27.324  3494  7184 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
09-09 13:41:27.324  3494  7184 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
09-09 13:41:27.324  3494  7184 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
09-09 13:41:27.324  3494  7184 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-09 13:41:27.334  7185  7185 E Zygote  : MountEmulatedStorage(),
,09-09 13:41:27.334  7185  7185 E Zygote  : v2
09-09 13:41:27.334  7185  7185 I libpersona: KNOX_SDCARD checking this for 10032,
09-09 13:41:27.334  7185  7185 I libpersona: KNOX_SDCARD not a persona
,09-09 13:41:27.334  7185  7185 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-09 13:41:27.344  7185  7185 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 13:41:27.344  1014  1557 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7185 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:41:27.344  7185  7185 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-09 13:41:27.374  7185  7185 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:41:27.374  7185  7185 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:27.394  1014  2857 D SSRM:n  : SIOP:: AP = 340
,09-09 13:41:27.434  7185  7200 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
09-09 13:41:27.434  7185  7200 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-09 13:41:27.434  7185  7185 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,09-09 13:41:27.434  1014  1216 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,09-09 13:41:27.434  1014  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:27.434  1014  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:27.434  1014  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:27.434  1014  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:27.444  7185  7200 D SPPClientService: PushLog.txt file is not deleted.
,09-09 13:41:27.444  7185  7200 D SPPClientService: PushLog.txt file is not deleted.
09-09 13:41:27.444  7185  7200 D SPPClientService: ============PushLog. stop!
,09-09 13:41:27.454  7202  7202 E Zygote  : MountEmulatedStorage()
,09-09 13:41:27.454  7202  7202 E Zygote  : v2
09-09 13:41:27.454  7202  7202 I libpersona: KNOX_SDCARD checking this for 10036
,09-09 13:41:27.454  1014  1216 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7202 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 13:41:27.454  7202  7202 I libpersona: KNOX_SDCARD not a persona
09-09 13:41:27.454  1014  1216 I ActivityManager: Killing 6736:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,09-09 13:41:27.454  7202  7202 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:41:27.454  1014  1557 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
09-09 13:41:27.454  1014  1557 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,09-09 13:41:27.454  1014  1557 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:27.454  1014  1557 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-09 13:41:27.454  1014  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,09-09 13:41:27.454  7202  7202 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 13:41:27.454  7202  7202 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,09-09 13:41:27.474  7202  7202 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:41:27.474  7202  7202 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:27.484  7185  7209 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,09-09 13:41:27.504  7202  7202 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@19b9a5c3
,09-09 13:41:27.514  7202  7202 I SA      : [SSP] onCreated
,09-09 13:41:27.524  7202  7202 I SA      : [TPM] There is no property file
,09-09 13:41:27.524  7202  7202 I SA      : [SCU] isHaveSA() - false
,09-09 13:41:27.534  7202  7202 I SA      : [TPM] getModelProperty : null
,09-09 13:41:27.534  7202  7202 I SA      : [TPM] getCSCProperty : null
,09-09 13:41:27.534  7202  7202 I SA      : [DM] FLOATING AMOLED FEATURE: true
09-09 13:41:27.534  7202  7202 I SA      : [DM] PRODUCT AMOLED FEATURE: false
09-09 13:41:27.534  7202  7202 I SA      : [DM] TFT FEATURE: false
,09-09 13:41:27.534  7202  7202 I SA      : [DM] init START
,09-09 13:41:27.544  7202  7202 I SA      : [DM] This device is not a Vodafone
,09-09 13:41:27.544  7202  7202 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,09-09 13:41:27.544  7202  7202 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,09-09 13:41:27.544  7202  7202 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,09-09 13:41:27.544  7202  7202 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
09-09 13:41:27.544  7202  7202 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
09-09 13:41:27.544  7202  7202 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,09-09 13:41:27.544  7202  7202 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,09-09 13:41:27.554  7202  7202 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-09 13:41:27.554  7202  7202 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,09-09 13:41:27.554  7202  7202 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,09-09 13:41:27.554  7202  7202 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,09-09 13:41:27.554  7202  7202 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,09-09 13:41:27.554  7202  7202 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,09-09 13:41:27.554  7202  7202 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,09-09 13:41:27.554  7202  7202 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,09-09 13:41:27.554  7202  7202 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
09-09 13:41:27.554  7202  7202 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,09-09 13:41:27.554  7202  7202 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
09-09 13:41:27.554  7202  7202 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,09-09 13:41:27.554  7202  7202 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75),
09-09 13:41:27.554  7202  7202 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,09-09 13:41:27.554  7202  7202 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
09-09 13:41:27.554  7202  7202 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,09-09 13:41:27.564  7202  7202 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
09-09 13:41:27.564  7202  7202 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
09-09 13:41:27.564  7202  7202 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,09-09 13:41:27.564  7202  7202 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
09-09 13:41:27.564  7202  7202 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,09-09 13:41:27.574  7202  7202 I SA      : [SCU] isHaveSA() - false
09-09 13:41:27.574  7202  7202 I SA      : support phone number id : false
09-09 13:41:27.574  7202  7202 I SA      : [DM] Supports Ref Jpn : true
,09-09 13:41:27.574  7202  7202 I SA      : [DM] init END
09-09 13:41:27.574  7202  7202 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,09-09 13:41:27.574  7202  7202 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ],
09-09 13:41:27.574  7202  7202 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-09 13:41:27.584  7202  7202 I SA      : [SLFUCHKMGR] constructor called
,09-09 13:41:27.584  7202  7202 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-09 13:41:27.584  7202  7202 I SA      : [OR] == isSIMCardReady false ==
,09-09 13:41:27.594  7202  7202 I SA      : [SCU] == networkStateCheck == false
09-09 13:41:27.594  7202  7202 I SA      : [OR] onReceive END
,09-09 13:41:27.594  1014  1500 I ActivityManager: Killing 6751:com.sec.esdk.elm/u0a90 (adj 15): empty #21
,09-09 13:41:27.604  1224  1224 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:27.604  1788  1788 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-09 13:41:27.614  2680  2692 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,09-09 13:41:27.614  1788  1788 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,09-09 13:41:27.614  1788  1788 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,09-09 13:41:27.614  1788  1788 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,09-09 13:41:27.614  1788  1788 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-09 13:41:27.624  1788  1788 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-09 13:41:27.624  1788  1788 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,09-09 13:41:27.624  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,09-09 13:41:27.624  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:27.624  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:27.624  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:27.624  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:27.644  7224  7224 E Zygote  : MountEmulatedStorage(),
09-09 13:41:27.644  1014  1027 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7224 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 13:41:27.644  7224  7224 E Zygote  : v2
09-09 13:41:27.644  7224  7224 I libpersona: KNOX_SDCARD checking this for 10077
09-09 13:41:27.644  7224  7224 I libpersona: KNOX_SDCARD not a persona,
09-09 13:41:27.644  7224  7224 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:41:27.644  7224  7224 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-09 13:41:27.644   317   317 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-09 13:41:27.654  7224  7224 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL,
,09-09 13:41:27.664  7224  7224 D TimaKeyStoreProvider: TimaSignature is unavailable,
,09-09 13:41:27.674  7224  7224 D ActivityThread: Added TimaKeyStore provider,
,09-09 13:41:27.804  1014  1328 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,09-09 13:41:27.804  1014  1328 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-09 13:41:27.804  1014  1328 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:27.804  1014  1328 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:27.804  1014  1328 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-09 13:41:27.814  1014  1026 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,09-09 13:41:27.814  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:27.814  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:27.814  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:27.814  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:27.834  7242  7242 E Zygote  : MountEmulatedStorage(),
09-09 13:41:27.834  7242  7242 E Zygote  : v2,
09-09 13:41:27.834  7242  7242 I libpersona: KNOX_SDCARD checking this for 10110
09-09 13:41:27.834  7242  7242 I libpersona: KNOX_SDCARD not a persona
,09-09 13:41:27.834  7242  7242 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:41:27.834  7242  7242 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-09 13:41:27.834  7242  7242 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,09-09 13:41:27.844  1014  1026 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7242 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 13:41:27.844  1014  1502 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
09-09 13:41:27.844  1014  1502 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-09 13:41:27.844  1014  1502 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:27.844  1014  1502 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:27.844  1014  1502 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
09-09 13:41:27.844  7028  7241 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-09 13:41:27.864  1014  1500 I ActivityManager: Killing 6836:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,09-09 13:41:27.864  7242  7242 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:41:27.864  7242  7242 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:27.924  1014  1328 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-09 13:41:27.984   256   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-09 13:41:27.984   256   525 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:41:27.984  7242  7260 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-09 13:41:27.994   256   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-09 13:41:27.994   256   525 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:41:27.994  7242  7260 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-09 13:41:27.994  7242  7242 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-09 13:41:27.994  7242  7242 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-09 13:41:27.994  7242  7242 I GAv4    :   adb logcat -s GAv4
,09-09 13:41:28.004   256   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-09 13:41:28.004   256   525 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:41:28.004  7242  7261 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-09 13:41:28.004   256   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-09 13:41:28.004   256   525 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:41:28.004  7242  7261 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-09 13:41:28.014  7242  7242 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-09 13:41:28.014  1014  1558 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-09 13:41:28.024  7242  7242 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-09 13:41:28.034  7242  7263 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-09 13:41:28.074  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-09 13:41:28.074  1014  1125 E WifiHW  : ##################### set firmware type 0 #####################
,09-09 13:41:28.224  1014  1500 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:41:28.224  1014  1500 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:28.224  7242  7242 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,09-09 13:41:28.224  1014  1500 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:28.224  1014  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-09 13:41:28.244  7242  7242 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 4730-4732)
,09-09 13:41:28.244  7242  7242 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-09 13:41:28.244  7242  7242 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1a8b5f8a}
09-09 13:41:28.244  7242  7242 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-09 13:41:28.244  7242  7242 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-09 13:41:28.274  7242  7242 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,09-09 13:41:28.274  7242  7242 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 13:41:28.274  7242  7242 E SysUtils: ApplicationContext is null in ApplicationStatus,
,09-09 13:41:28.294  7242  7242 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-09 13:41:28.294  7242  7242 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-09 13:41:28.294  7242  7242 I Adreno-EGL: Build Date: 04/06/15 Mon
09-09 13:41:28.294  7242  7242 I Adreno-EGL: Local Branch: 
09-09 13:41:28.294  7242  7242 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-09 13:41:28.294  7242  7242 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-09 13:41:28.294  7242  7242 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-09 13:41:28.354  7242  7242 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-09 13:41:28.364  7242  7297 W cr.media: Requires BLUETOOTH permission
,09-09 13:41:28.364  7242  7242 I NSApplication: Starting up...
,09-09 13:41:28.364  1014  1026 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-09 13:41:28.374  1014  1027 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-09 13:41:28.374  1014  1558 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,09-09 13:41:28.374  1014  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-09 13:41:28.374  1014  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:28.374  1014  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:28.374  1014  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:28.394  7302  7302 E Zygote  : MountEmulatedStorage(),
09-09 13:41:28.394  1014  1558 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7302 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
09-09 13:41:28.394  1014  1558 I ActivityManager: Killing 6853:com.qualcomm.timeservice/1000 (adj 15): empty #21
,09-09 13:41:28.394  7302  7302 E Zygote  : v2
09-09 13:41:28.394  7302  7302 I libpersona: KNOX_SDCARD checking this for 10117
09-09 13:41:28.394  7302  7302 I libpersona: KNOX_SDCARD not a persona
,09-09 13:41:28.394  7302  7302 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:41:28.404  7302  7302 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-09 13:41:28.404  7302  7302 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-09 13:41:28.434  7302  7302 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:41:28.434  7302  7302 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:28.444  7302  7302 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 13:41:28.454  1014  1043 D Tethering: interfaceAdded wlan0,
,09-09 13:41:28.454  1014  1128 E Tethering: No numeric data
,09-09 13:41:28.454  1014  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-09 13:41:28.454  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:41:28.454  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:41:28.454  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
,09-09 13:41:28.454  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:28.454  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
,09-09 13:41:28.464  1014  1128 D Tethering: clearTetheredNotification()
,09-09 13:41:28.464  1014  1128 D Tethering: InitialState.processMessage what=4
09-09 13:41:28.464  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 13:41:28.464  1174  1174 D HotspotTile: updateTetherState():false, false
09-09 13:41:28.464  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:41:28.464  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-09 13:41:28.464  1014  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 13:41:28.464  1014  1043 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 13:41:28.464  1014  1043 D Tethering: interfaceStatusChanged p2p0, false
,09-09 13:41:28.464   277  1002 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,09-09 13:41:28.464   277  1002 D SoftapController: Softap fwReload - Ok
09-09 13:41:28.464  1014  1128 E Tethering: No numeric data
09-09 13:41:28.464  1014  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 13:41:28.464  1014  1128 D Tethering: clearTetheredNotification()
09-09 13:41:28.464  1014  1122 V NetworkStats: performPollLocked() took 6ms
09-09 13:41:28.464  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:28.464  1014  1043 D Tethering: interfaceAdded p2p0
09-09 13:41:28.464  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
09-09 13:41:28.464  1014  1043 D Tethering: p2p0 is not a tetherable iface, ignoring,
09-09 13:41:28.464  1174  1174 D HotspotTile: updateTetherState():false, false
09-09 13:41:28.464   277  1002 D CommandListener: Setting iface cfg
09-09 13:41:28.464  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
09-09 13:41:28.464  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:28.464   277  1002 D CommandListener: Trying to bring down wlan0
09-09 13:41:28.464  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:41:28.464  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-09 13:41:28.464   277  1002 D CommandListener: Clearing all IP addresses on wlan0
09-09 13:41:28.464  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:28.464  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:28.474  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:28.474  1014  1122 V NetworkStats: performPollLocked() took 4ms
09-09 13:41:28.474  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:28.474  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:28.474  1014  1125 E WifiHW  : supplicant_name : p2p_supplicant
,09-09 13:41:28.524  7318  7318 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-09 13:41:28.524  7318  7318 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-09 13:41:28.524  7318  7318 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-09 13:41:28.554  7318  7318 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,09-09 13:41:28.554   378   378 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7318,
09-09 13:41:28.554   378   378 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
09-09 13:41:28.554  7318  7318 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running,
09-09 13:41:28.554  7318  7318 I wpa_supplicant: ssSupport state is = 1
09-09 13:41:28.554  7318  7318 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
,09-09 13:41:28.554  7318  7318 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,09-09 13:41:28.554   378   378 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7318,
09-09 13:41:28.554   378   378 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,09-09 13:41:28.574  1014  1125 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-09 13:41:28.594  4412  4412 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
09-09 13:41:28.594  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-09 13:41:28.594  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:41:28.594  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-09 13:41:28.594  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:28.594  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:28.594  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:28.594  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:28.594  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:28.594  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:28.594  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
09-09 13:41:28.594  1174  1720 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-09 13:41:28.594  1174  1174 D HotspotTile: onReceive : 2, 0
,09-09 13:41:28.594  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-09 13:41:28.604  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:28.604  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-09 13:41:28.734   378   378 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0,
,09-09 13:41:28.734  7318  7318 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed,
,09-09 13:41:28.794  7318  7318 I wpa_supplicant: Ctrl_iface: loading cred from phone,
09-09 13:41:28.794  7318  7318 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-09 13:41:28.804  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast,
09-09 13:41:28.804  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:28.804  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:28.804  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:28.804  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:28.804  7318  7318 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
09-09 13:41:28.804   378   378 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7318
09-09 13:41:28.804   378   378 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-09 13:41:28.804  7318  7318 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-09 13:41:28.804  7318  7318 I wpa_supplicant: ssSupport state is = 1
09-09 13:41:28.814  7318  7318 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-09 13:41:28.814  7318  7318 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 13:41:28.814  7318  7318 E wpa_supplicant: SIM READ ERROR
09-09 13:41:28.814  7318  7318 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 13:41:28.814  7318  7318 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-09 13:41:28.814  7318  7318 E wpa_supplicant: SIM READ ERROR
09-09 13:41:28.814  7318  7318 I wpa_supplicant: Blacklist: Clear (all) 
09-09 13:41:28.814  7318  7318 I wpa_supplicant: wpa_default_ap_write_once
09-09 13:41:28.814  7318  7318 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-09 13:41:28.814  7318  7318 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 13:41:28.814  7318  7318 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-09 13:41:28.814  7318  7318 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 13:41:28.814  7318  7318 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-09 13:41:28.814  7327  7327 E Zygote  : MountEmulatedStorage()
,09-09 13:41:28.814  7327  7327 E Zygote  : v2
09-09 13:41:28.814  7327  7327 I libpersona: KNOX_SDCARD checking this for 10121
09-09 13:41:28.814  7318  7318 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-09 13:41:28.814  7327  7327 I libpersona: KNOX_SDCARD not a persona
,09-09 13:41:28.814  7327  7327 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:41:28.814  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:41:28.814  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:41:28.814  1014  1027 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7327 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
09-09 13:41:28.814  1014  1043 D Tethering: interfaceStatusChanged wlan0, false,
,09-09 13:41:28.824  1014  1027 I ActivityManager: Killing 6816:com.android.providers.calendar/u0a37 (adj 15): empty #21
,09-09 13:41:28.824  7327  7327 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 13:41:28.824  7327  7327 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:41:28.834  7327  7327 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:41:28.834  7327  7327 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:28.854  7327  7327 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 13:41:28.854  7327  7327 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-09 13:41:28.854  7327  7327 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-09 13:41:28.864  7318  7318 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-09 13:41:28.864  7327  7327 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:28.864  7327  7327 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,09-09 13:41:28.874  7327  7327 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-09 13:41:28.874  1014  1558 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast,
09-09 13:41:28.874  1014  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:28.874  1014  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:28.874  1014  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:28.874  1014  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,09-09 13:41:28.884  7345  7345 E Zygote  : MountEmulatedStorage()
,09-09 13:41:28.884  7345  7345 E Zygote  : v2
09-09 13:41:28.884  7345  7345 I libpersona: KNOX_SDCARD checking this for 10141
09-09 13:41:28.884  7345  7345 I libpersona: KNOX_SDCARD not a persona
,09-09 13:41:28.884  7345  7345 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-09 13:41:28.894  1014  1558 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7345 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,09-09 13:41:28.894  1014  1558 I ActivityManager: Killing 6767:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,09-09 13:41:28.894  7345  7345 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 13:41:28.894  7345  7345 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:41:28.914  7345  7345 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:41:28.914  7345  7345 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:28.934  7345  7345 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,09-09 13:41:28.934  7345  7345 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 13:41:28.934  7345  7345 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 13:41:28.934  7345  7345 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-09 13:41:29.004  7318  7318 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,09-09 13:41:29.004  7318  7318 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage,
,09-09 13:41:29.014  1014  1502 D RCPManagerService: exchangeData() failure , invalid userId,
,09-09 13:41:29.024  7318  7318 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
09-09 13:41:29.024   378   378 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7318
,09-09 13:41:29.024   378   378 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C,
09-09 13:41:29.024  7318  7318 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-09 13:41:29.024  7318  7318 I wpa_supplicant: ssSupport state is = 1
,09-09 13:41:29.034  7318  7318 I wpa_supplicant: Ctrl_iface: loading cred from phone,
09-09 13:41:29.034  7318  7318 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-09 13:41:29.054  7318  7318 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
09-09 13:41:29.054  1014  1026 D RCPManagerService: exchangeData() failure , invalid userId
09-09 13:41:29.054   378   378 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7318
09-09 13:41:29.054   378   378 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-09 13:41:29.054  7318  7318 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-09 13:41:29.054  7318  7318 I wpa_supplicant: ssSupport state is = 1
09-09 13:41:29.054  7318  7318 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 13:41:29.054  7318  7318 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 13:41:29.054  7318  7318 E wpa_supplicant: SIM READ ERROR
09-09 13:41:29.054  7318  7318 I wpa_supplicant: wpa_default_ap_write_once
09-09 13:41:29.054  7318  7318 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-09 13:41:29.054  7318  7318 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-09 13:41:29.054  1014  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 13:41:29.054  1014  1043 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 13:41:29.054  1014  1043 D Tethering: interfaceStatusChanged p2p0, false
,09-09 13:41:29.054  1014  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 13:41:29.054  1014  1043 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 13:41:29.054  1014  1043 D Tethering: interfaceStatusChanged p2p0, false
,09-09 13:41:29.084  1014  1558 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 13:41:29.094  1014  1213 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 13:41:29.114  7318  7318 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
,09-09 13:41:29.114  7318  7318 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-09 13:41:29.134  1014  1501 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,09-09 13:41:29.144  1014  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:29.144  1014  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:29.144  1014  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:29.144  1014  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:29.154  1014  1502 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 13:41:29.154  7369  7369 E Zygote  : MountEmulatedStorage()
,09-09 13:41:29.154  7369  7369 I libpersona: KNOX_SDCARD checking this for 10068
09-09 13:41:29.154  7369  7369 E Zygote  : v2
09-09 13:41:29.154  7369  7369 I libpersona: KNOX_SDCARD not a persona
09-09 13:41:29.154  7369  7369 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:41:29.154  1014  1501 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7369 uid=10068 gids={50068, 9997} abi=armeabi-v7a
09-09 13:41:29.154  7369  7369 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-09 13:41:29.154  7369  7369 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-09 13:41:29.164  1014  1556 D RCPManagerService: exchangeData() failure , invalid userId,
,09-09 13:41:29.184  7369  7369 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:41:29.184  7369  7369 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:29.194  7318  7318 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
09-09 13:41:29.194  7318  7318 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-09 13:41:29.194  7318  7318 I wpa_supplicant: Skip scan - bUseNetwork false
,09-09 13:41:29.194  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
,09-09 13:41:29.204  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-09 13:41:29.204  7318  7318 I wpa_supplicant: HOTSPOT20_ENABLE called
09-09 13:41:29.204  7318  7318 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-09 13:41:29.204  7318  7318 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 13:41:29.204  7318  7318 E wpa_supplicant: SIM READ ERROR,
09-09 13:41:29.204  7318  7318 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 13:41:29.224  7318  7318 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-09 13:41:29.244  7369  7369 D BadgeProvider: onCreate
,09-09 13:41:29.244  7369  7369 D BadgeProvider: DatabaseHelper
,09-09 13:41:29.254  1014  1216 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 13:41:29.264  7318  7318 I wpa_supplicant: Skip scan - bUseNetwork false
,09-09 13:41:29.264  1014  1502 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast,
09-09 13:41:29.264  1014  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:29.264  1014  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:29.264  1014  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,09-09 13:41:29.264  1014  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:29.274  7369  7382 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge',
,09-09 13:41:29.274  7386  7386 E Zygote  : MountEmulatedStorage()
09-09 13:41:29.274  7386  7386 E Zygote  : v2
09-09 13:41:29.274  7386  7386 I libpersona: KNOX_SDCARD checking this for 10009
09-09 13:41:29.274  7386  7386 I libpersona: KNOX_SDCARD not a persona
,09-09 13:41:29.274  7386  7386 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:41:29.284  7386  7386 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-09 13:41:29.284  7386  7386 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
09-09 13:41:29.284  1014  1502 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7386 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,09-09 13:41:29.284  1014  1502 I ActivityManager: Killing 6635:com.android.defcontainer/u0a3 (adj 15): empty #21,
09-09 13:41:29.284  1014  1502 I ActivityManager: Killing 6783:com.android.calendar/u0a131 (adj 15): empty #22
,09-09 13:41:29.294  1014  1125 D WifiConfigStore: Loading config and enabling all networks 
,09-09 13:41:29.304  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-09 13:41:29.304  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:29.304  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:41:29.304  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:41:29.304  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:29.304  1174  1720 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-09 13:41:29.304  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:29.304  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:29.304  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:29.304  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:29.304  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,09-09 13:41:29.314  4412  4412 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:41:29.314  1174  1174 D HotspotTile: onReceive : 3, 0
,09-09 13:41:29.314  7369  7384 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
09-09 13:41:29.314  7369  7384 D BadgeProvider: sendNotify, [notify] : null
09-09 13:41:29.314  7369  7384 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
09-09 13:41:29.314  7369  7384 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-09 13:41:29.314  7369  7384 D BadgeProvider: update, [UpdateCount] : 1
,09-09 13:41:29.314  1014  1125 E WifiConfigStore: Not a HS20
,09-09 13:41:29.324  1014  1125 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-09 13:41:29.324  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:29.324  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:29.324  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:29.324  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:29.324  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:29.324  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:29.324  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:29.324  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:41:29.324  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-09 13:41:29.324  7318  7318 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-09 13:41:29.324  7318  7318 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-09 13:41:29.324  7318  7318 I wpa_supplicant: reset timer : RESET_TIMER 0
09-09 13:41:29.324  7318  7318 I wpa_supplicant: P2P: Current p2p state = IDLE
09-09 13:41:29.324  7318  7318 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-09 13:41:29.324  7318  7318 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-09 13:41:29.324  7318  7318 I wpa_supplicant: First Scan Start
09-09 13:41:29.324  7318  7318 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
09-09 13:41:29.334  1503  1503 D Launcher.Model: reloadBadges entered.
,09-09 13:41:29.334  7386  7386 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:41:29.334  7386  7386 D ActivityThread: Added TimaKeyStore provider
09-09 13:41:29.334  6937  6937 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:41:29.334  1014  1125 D WifiNative-wlan0: Setting external_sim to 1
,09-09 13:41:29.334  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:29.334  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:29.334  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:29.334  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:41:29.334  6937  6991 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d14a22e removed from the list
09-09 13:41:29.334  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:29.334  6937  6991 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c741cf removed from the list
,09-09 13:41:29.334  6937  6991 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:29.334  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:29.334  7028  7028 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:41:29.354  1014  1125 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 13:41:29.354  1014  1125 I WifiNative-HAL: startHal
09-09 13:41:29.354  1014  1125 E wifi    : getStaticLongField sWifiHalHandle 0x9ebf688c
09-09 13:41:29.354  1014  1125 I WifiNative-HAL: Could not start hal
,09-09 13:41:29.354  6937  6991 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 13:41:29.354  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:29.354  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:29.354  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:29.354  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:29.354  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:29.354  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:29.354  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:29.354  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:41:29.354  1014  1125 E WifiNative-wlan0: do suspend true
,09-09 13:41:29.354  1014  1124 D WifiP2pService: P2pDisabledState{ what=131203 }
09-09 13:41:29.354  6937  6991 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e2a9a65 added. We now have 3 listener(s)
,09-09 13:41:29.364   277  1002 D CommandListener: Setting iface cfg
09-09 13:41:29.364   277  1002 D CommandListener: Trying to bring up p2p0
,09-09 13:41:29.364  1014  1124 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-09 13:41:29.364  1014  1124 D WifiP2pService: P2pEnablingState
09-09 13:41:29.364  1014  1124 D WifiP2pService: P2pEnablingState{ what=147457 }
09-09 13:41:29.364  1014  1124 D WifiP2pService: P2p socket connection successful
09-09 13:41:29.364  1014  1124 D WifiP2pService: P2pEnabledState
,09-09 13:41:29.364  6937  6937 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:41:29.364  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-09 13:41:29.364  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 3
09-09 13:41:29.364  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
09-09 13:41:29.374  1014  1148 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:29.374  1014  1127 E ConnectivityService: updateNetworkInfo()
09-09 13:41:29.374  1014  1148 I WifiNative-HAL: startHal
09-09 13:41:29.374  1014  1148 E wifi    : getStaticLongField sWifiHalHandle 0x9dbb69bc
09-09 13:41:29.374  1014  1148 I WifiNative-HAL: Could not start hal
09-09 13:41:29.374  1014  1148 E WifiScanningService: could not start HAL
09-09 13:41:29.374  1014  1014 D RttService: SCAN_AVAILABLE : 3
09-09 13:41:29.374  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-09 13:41:29.374  1014  1149 D RttService: DefaultState got{ when=-2ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:29.374  1014  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-09 13:41:29.374  1014  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 13:41:29.374  1014  1046 D WifiDisplayController: disconnect
09-09 13:41:29.374  1014  1046 D WifiDisplayController: updateConnection
09-09 13:41:29.374  1014  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 13:41:29.374  1014  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-09 13:41:29.374  1014  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-09 13:41:29.374  1014  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-09 13:41:29.374  1014  1125 E WifiNative-wlan0: invaild command id : 215
09-09 13:41:29.374  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-09 13:41:29.374  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:29.374  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:41:29.374  6937  6991 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:41:29.374  6937  6991 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24cb33a added. We now have 3 listener(s)
09-09 13:41:29.374  6937  6991 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:41:29.374  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:41:29.374  1014  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:41:29.374  1014  1046 D WifiDisplayAdapter: onP2pDisconnected
09-09 13:41:29.374  1014  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 13:41:29.374  1014  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-09 13:41:29.384  7318  7318 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-09 13:41:29.384  1174  1174 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-09 13:41:29.384  7318  7318 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-09 13:41:29.384  1014  1216 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-09 13:41:29.384  1174  1174 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-09 13:41:29.384  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:29.394  7318  7318 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,09-09 13:41:29.394  1014  1125 E WifiStateMachine: Failed to set frequency band 0
09-09 13:41:29.394  1014  1124 D WifiNative-p2p0: p2pGetDeviceAddress
,09-09 13:41:29.394  1014  1124 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
09-09 13:41:29.394  1014  1124 D WifiP2pService: DeviceAddress: 0a:75:42
09-09 13:41:29.394  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:41:29.394  1014  1125 D SecContentProvider2: mCursor = null
,09-09 13:41:29.394  1014  1046 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
09-09 13:41:29.394  1014  1046 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
09-09 13:41:29.394  1014  1046 D WifiDisplayController:  primary type: 10-0050F204-5
09-09 13:41:29.394  1014  1046 D WifiDisplayController:  secondary type: null
09-09 13:41:29.394  1014  1046 D WifiDisplayController:  wps: 0
09-09 13:41:29.394  1014  1046 D WifiDisplayController:  grpcapab: 0
09-09 13:41:29.394  1014  1046 D WifiDisplayController:  devcapab: 0
09-09 13:41:29.394  1014  1046 D WifiDisplayController:  status: 3
09-09 13:41:29.394  1014  1046 D WifiDisplayController:  wfdInfo: null
09-09 13:41:29.394  1014  1046 D WifiDisplayController:  groupownerAddress: null
09-09 13:41:29.394  1014  1046 D WifiDisplayController:  GOdeviceName: null
09-09 13:41:29.394  1014  1046 D WifiDisplayController:  interfaceAddress: 
09-09 13:41:29.394  1014  1046 D WifiDisplayController:  SConnectInfo : null
,09-09 13:41:29.394  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:41:29.394  1014  1125 D SecContentProvider2: mCursor = null
09-09 13:41:29.394  6937  6991 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:29.394  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:29.394  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:29.394  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:29.394  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:29.394  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:29.394  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:29.394  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:41:29.404  6937  6991 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:41:29.404  6937  6991 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:41:29.404  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:29.404  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:29.404  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:29.404  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:41:29.404  6937  6991 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e2a9a65 removed from the list
09-09 13:41:29.404  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:29.404  6937  6991 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24cb33a removed from the list
09-09 13:41:29.404  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:29.404  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:29.404  6937  6991 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:29.404  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:29.404  6937  6991 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 13:41:29.404  6937  6991 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d67d48 added. We now have 3 listener(s)
,09-09 13:41:29.414  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-09 13:41:29.414  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:29.414  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:41:29.414  6937  6991 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:41:29.414  6937  6991 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e2f77e1 added. We now have 3 listener(s)
09-09 13:41:29.414  6937  6991 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:41:29.414  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:41:29.414  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:29.424  6937  6991 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:29.424  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:29.424  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:29.424  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:29.424  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:29.424  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:29.424  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:29.424  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:41:29.434  1014  1124 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-09 13:41:29.434  1014  1124 D WifiP2pService: InactiveState
09-09 13:41:29.434  1014  1124 D WifiP2pService: InactiveState{ what=143376 }
09-09 13:41:29.434  1014  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-09 13:41:29.434  6937  6991 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:41:29.434  6937  6991 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:41:29.434  6937  6991 D BluetoothAdapter: disable()
09-09 13:41:29.434  7318  7318 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-09 13:41:29.434  1014  1124 D WifiP2pService: InactiveState{ what=143376 }
,09-09 13:41:29.434  1014  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-09 13:41:29.444  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-09 13:41:29.444  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:29.444  1014  1500 D SettingsProvider: name = bluetooth_on
,09-09 13:41:29.454  1014  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 13:41:29.454  1014  1043 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 13:41:29.454  1014  1043 D Tethering: interfaceStatusChanged p2p0, false
,09-09 13:41:29.454  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,09-09 13:41:29.454  1014  1027 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,09-09 13:41:29.464  2789  2846 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
09-09 13:41:29.464  2789  2846 D BluetoothAdapterProperties: Setting state to 13
09-09 13:41:29.464  2789  2846 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-09 13:41:29.464  2789  2846 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-09 13:41:29.464  2789  2846 D BluetoothAdapterService: updateAdapterState state is 13
,09-09 13:41:29.464  1014  1556 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,09-09 13:41:29.464  1014  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:41:29.464  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-09 13:41:29.464  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:29.464  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:29.464  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:29.474  2789  2789 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
09-09 13:41:29.474  2789  2846 D BluetoothAdapterService: Autoconnection is available 
09-09 13:41:29.474  2789  2846 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-09 13:41:29.474  2789  2846 D BluetoothAdapterService: terminating service from this receiver
,09-09 13:41:29.474  2789  2789 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@17d34a18, channel: 19, state: LISTENING
09-09 13:41:29.474  2789  2789 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@17d34a18, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@f847c32, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2c1a0c71mSocket: android.net.LocalSocket@747ea56 impl:android.net.LocalSocketImpl@17892ad7 fd:FileDescriptor[80]
09-09 13:41:29.474  2789  2789 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@747ea56 impl:android.net.LocalSocketImpl@17892ad7 fd:FileDescriptor[80]
,09-09 13:41:29.474  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-09 13:41:29.474  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:29.474  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:29.474  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 13:41:29.474  4412  4412 D BluetoothPbap: Proxy object disconnected
09-09 13:41:29.474  4412  4412 D PbapServerProfile: Bluetooth service disconnected
,09-09 13:41:29.474  1014  1555 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,09-09 13:41:29.474  2789  2846 D BluetoothAdapterProperties: onBluetoothDisable()
,09-09 13:41:29.474  2789  2846 D BluetoothAdapterProperties: mDiscovering is false
,09-09 13:41:29.484  1014  1557 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-09 13:41:29.484  2789  2846 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-09 13:41:29.484  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:41:29.484  1014  1014 I InputMethodManagerService: [BT Setting State] State =13
,09-09 13:41:29.494  1174  1174 D BluetoothTile:  onBluetoothStateChange:
,09-09 13:41:29.494  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-09 13:41:29.494  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:41:29.494  1174  1174 D BluetoothTile:  getBluetoothState : 13
,09-09 13:41:29.494  1174  1720 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 13:41:29.504  1174  1720 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 13:41:29.504  1174  1720 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-09 13:41:29.504  1868  1868 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-09 13:41:29.504  1014  1500 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 13:41:29.514  1014  1213 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-09 13:41:29.514  1014  1026 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 13:41:29.514  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:41:29.514  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-09 13:41:29.514  4412  4412 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:41:29.514  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:29.514  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:29.514  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:41:29.514  6937  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:29.514  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:29.514  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:29.514  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:29.514  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:29.514  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:29.514  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:29.514  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:29.514  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:41:29.524  1609  1609 I Hs20UtilService: Starting #11
,09-09 13:41:29.524  6937  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:29.524  6937  6937 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:41:29.524  1609  1661 I Hs20UtilService: Message received 5011
,09-09 13:41:29.524  6937  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:29.524  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:29.524  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:29.524  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:29.524  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:29.524  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:29.524  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:29.524  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:29.524  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:41:29.524  2789  2849 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-09 13:41:29.524  2789  2849 D BluetoothAdapterProperties: Scan Mode:20
,09-09 13:41:29.534  6937  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:41:29.534  6937  6937 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:41:29.534  2789  2846 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-09 13:41:29.534  2789  2846 E bt-btif : HAL bt_hal_cbacks->log_collector_cb
,09-09 13:41:29.534  2789  2846 E bt-btif : cmd socket is not created
,09-09 13:41:29.534  2789  2852 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
09-09 13:41:29.534  2789  5334 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-09 13:41:29.534  6937  7014 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@21d39bc7, channel: -1, state: INIT
,09-09 13:41:29.534  6804  6804 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-09 13:41:29.534  1014  1558 I art     : Explicit concurrent mark sweep GC freed 82616(4MB) AllocSpace objects, 26(464KB) LOS objects, 33% free, 23MB/34MB, paused 2.629ms total 196.333ms
09-09 13:41:29.534  6804  6804 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 13:41:29.534  6804  6804 D SecurityLogAgent: StateMachine : Current State = 1
,09-09 13:41:29.534  6804  6804 D SecurityLogAgent: StateMachine : Changed Current State = 1
09-09 13:41:29.534  2789  2846 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-09 13:41:29.534  6937  7014 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@21d39bc7, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@237a25f4, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@214ab11dmSocket: android.net.LocalSocket@8326f92 impl:android.net.LocalSocketImpl@38642d63 fd:FileDescriptor[108]
09-09 13:41:29.534  6937  7014 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@8326f92 impl:android.net.LocalSocketImpl@38642d63 fd:FileDescriptor[108]
,09-09 13:41:29.534  6937  7014 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1410)
,09-09 13:41:29.544  6937  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:41:29.544  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:29.544  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:29.544  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:29.544  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:29.544  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:29.544  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:29.544  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:29.544  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:41:29.544  6937  6937 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:29.544  6937  6937 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:41:29.544  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:29.544  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:29.554  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:29.554  2789  2852 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-09 13:41:29.554  2789  2852 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-09 13:41:29.554  2789  2852 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-09 13:41:29.554  2789  2852 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 13:41:29.554  2789  2852 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 13:41:29.554  2789  2852 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-09 13:41:29.574  2789  2789 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@8f1fead, channel: 5, state: LISTENING
,09-09 13:41:29.574  2789  2789 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@8f1fead, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@39ec4d83, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@317055e2mSocket: android.net.LocalSocket@15cb9d73 impl:android.net.LocalSocketImpl@b9d4430 fd:FileDescriptor[82]
,09-09 13:41:29.574  2789  2789 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@15cb9d73 impl:android.net.LocalSocketImpl@b9d4430 fd:FileDescriptor[82]
09-09 13:41:29.574   277   998 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-09 13:41:29.574   277   998 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,09-09 13:41:29.584  2789  2789 I BtOppRfcommListener: stopping Accept Thread
,09-09 13:41:29.584  2789  2789 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@9dcd8a9, channel: 12, state: LISTENING
09-09 13:41:29.584  2789  2789 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@9dcd8a9, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3ce205f5, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@38c1ee2emSocket: android.net.LocalSocket@26b89dcf impl:android.net.LocalSocketImpl@19ca735c fd:FileDescriptor[85]
,09-09 13:41:29.584  2789  2789 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@26b89dcf impl:android.net.LocalSocketImpl@19ca735c fd:FileDescriptor[85]
,09-09 13:41:29.584  2789  5334 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-09 13:41:29.584  1014  1556 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 13:41:29.584  1014  1556 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-09 13:41:29.584  1014  1556 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:29.584  1014  1556 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:29.584  1014  1556 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-09 13:41:29.584  1609  1609 I Hs20UtilService: Starting #12
09-09 13:41:29.584  2789  2789 V BluetoothOppManager: cleanUp...
09-09 13:41:29.584  1609  1661 I Hs20UtilService: Message received 5011
09-09 13:41:29.584  1014  1501 I ActivityManager: Killing 6878:com.android.vending/u0a26 (adj 15): empty #21
,09-09 13:41:29.594  6804  6804 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-09 13:41:29.594  6804  6804 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 13:41:29.594  6804  6804 D SecurityLogAgent: StateMachine : Current State = 1
09-09 13:41:29.594  6804  6804 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 13:41:29.604  1014  1558 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 13:41:29.604  1014  1558 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:41:29.604  1014  1558 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:29.604  1014  1558 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:29.604  1014  1558 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:41:29.604  1609  1609 I Hs20UtilService: Starting #13
09-09 13:41:29.604  1609  1661 I Hs20UtilService: Message received 5011
,09-09 13:41:29.604  1014  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,09-09 13:41:29.604  1014  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-09 13:41:29.604  1014  1125 E WifiNative-wlan0: invaild command id : 215
,09-09 13:41:29.614  6804  6804 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-09 13:41:29.614  6804  6804 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 13:41:29.614  6804  6804 D SecurityLogAgent: StateMachine : Current State = 1
09-09 13:41:29.614  6804  6804 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 13:41:29.614  4412  4412 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-09 13:41:29.614  4412  4412 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-09 13:41:29.614  4412  4412 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 13:41:29.624  4412  4412 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-09 13:41:29.624  4412  4412 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 13:41:29.624  4412  4412 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 13:41:29.624  4412  4504 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 13:41:29.624  7072  7072 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
09-09 13:41:29.624  7072  7072 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-09 13:41:29.624  7072  7072 D FileShare-Client: Outbound.stopDelayTimer - 
09-09 13:41:29.624  7087  7087 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 13:41:29.634  1014  1026 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-09 13:41:29.634  1014  1026 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4266, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-09 13:41:29.634  1014  1026 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-09 13:41:29.634  4412  4412 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 13:41:29.644  1014  1026 D BatteryService: stay LED for charging
09-09 13:41:29.644  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-09 13:41:29.644  1014  1014 I MotionRecognitionService: Plugged
,09-09 13:41:29.644  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,09-09 13:41:29.644  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-09 13:41:29.644  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-09 13:41:29.644   287   287 E SMD     : DCD OFF
,09-09 13:41:29.644  1421  1421 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-09 13:41:29.644  1421  1421 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-09 13:41:29.654  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-09 13:41:29.654  2789  2789 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-09 13:41:29.654  2789  3002 D HeadsetStateMachine: Disconnected process message: 10
,09-09 13:41:29.654  1014  1555 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-09 13:41:29.654  1014  1555 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-09 13:41:29.654  1014  1555 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:29.654  1014  1555 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:29.654  1014  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-09 13:41:29.664  2635  2635 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 13:41:29.674  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-09 13:41:29.674  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-09 13:41:29.674  4412  4412 D DockEventReceiver: finishStartingService: stopping service
09-09 13:41:29.674  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
09-09 13:41:29.674  1174  1174 D SViewCoverView: level :100 plugged : 2
,09-09 13:41:29.674  4412  4412 D BluetoothNotiBroadcastReceiver: onReceive
,09-09 13:41:29.674  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:29.674  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-09 13:41:29.674  1014  1026 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast,
,09-09 13:41:29.674  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:29.684  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:29.684  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:29.684  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:29.694  7414  7414 E Zygote  : MountEmulatedStorage()
09-09 13:41:29.694  7414  7414 E Zygote  : v2
09-09 13:41:29.694  7414  7414 I libpersona: KNOX_SDCARD checking this for 10055
09-09 13:41:29.694  7414  7414 I libpersona: KNOX_SDCARD not a persona
09-09 13:41:29.694  7414  7414 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:41:29.694  1014  1026 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7414 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,09-09 13:41:29.694  7414  7414 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 13:41:29.694  7414  7414 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-09 13:41:29.714  7414  7414 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:41:29.714  7414  7414 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:29.734  2789  2846 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-09 13:41:29.734  2789  2846 D BtConfig.SecureMode: isSecureModeOn:false
09-09 13:41:29.734  2789  2846 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-09 13:41:29.734  2789  2846 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
09-09 13:41:29.734  2789  2846 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
09-09 13:41:29.734  2789  2846 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-09 13:41:29.734  2789  2846 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-09 13:41:29.734  2789  2846 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-09 13:41:29.734  1014  1328 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:41:29.734  1014  1328 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-09 13:41:29.734  1014  1328 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:29.734  1014  1328 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 13:41:29.734  1014  1328 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:29.744  2789  2846 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,09-09 13:41:29.744  2789  2846 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-09 13:41:29.744  2789  2846 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
09-09 13:41:29.744  1014  1502 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 13:41:29.744  2789  2789 D HeadsetService: Received stop request...Stopping profile...
09-09 13:41:29.744  7414  7414 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-09 13:41:29.744  1014  1502 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 13:41:29.744  1014  1502 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:29.744  1014  1502 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:29.744  1014  1502 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:29.744  2789  2789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@126ad8ca
,09-09 13:41:29.744  2789  2846 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,09-09 13:41:29.744  2789  2846 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-09 13:41:29.744  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-09 13:41:29.754  4412  4412 D HeadsetProfile: Bluetooth service disconnected
,09-09 13:41:29.754  2789  2789 D A2dpService: Received stop request...Stopping profile...
09-09 13:41:29.754  2789  3018 D A2dpStateMachine: Exit Disconnected: -1
,09-09 13:41:29.754  2789  2846 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-09 13:41:29.754  1014  1328 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 13:41:29.754  1014  1328 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-09 13:41:29.754  1014  1328 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:29.754  1014  1328 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 13:41:29.754  1014  1328 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:29.754  2789  2846 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
09-09 13:41:29.754  2789  2846 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-09 13:41:29.754  2789  2846 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-09 13:41:29.754  1014  1556 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 13:41:29.764  1014  1556 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-09 13:41:29.764  1014  1556 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:29.764  1014  1556 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 13:41:29.764  1014  1556 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:29.764  2789  2789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@126ad8ca
,09-09 13:41:29.764  1014  1014 D BluetoothA2dp: Proxy object disconnected,
,09-09 13:41:29.764  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-09 13:41:29.764  2789  2846 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
09-09 13:41:29.764  2789  2846 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-09 13:41:29.764  4412  4412 D BluetoothA2dp: Proxy object disconnected
09-09 13:41:29.764  1014  1328 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 13:41:29.764  4412  4412 D A2dpProfile: Bluetooth service disconnected
09-09 13:41:29.764  1014  1328 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-09 13:41:29.764  2789  2846 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-09 13:41:29.764  1014  1328 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:29.764  1014  1328 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:29.764  1014  1328 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:29.764  2789  2846 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
09-09 13:41:29.764  2789  2846 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-09 13:41:29.764  2789  2846 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
09-09 13:41:29.764  1014  1502 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:41:29.764  1014  1502 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-09 13:41:29.764  1014  1502 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:29.764  1014  1502 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:29.764  1014  1502 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:29.774  2789  2846 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
09-09 13:41:29.774  2789  2846 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-09 13:41:29.774  2789  2846 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-09 13:41:29.774  1014  1500 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:41:29.774  1014  1500 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-09 13:41:29.774  1014  1500 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:29.774  1014  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:29.774  1014  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:29.774  2789  2846 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-09 13:41:29.774  2789  2846 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-09 13:41:29.774  2789  2846 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-09 13:41:29.774  2789  2846 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-09 13:41:29.774  2789  2846 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-09 13:41:29.774  2789  2846 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,09-09 13:41:29.774  2789  2846 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-09 13:41:29.774  2789  2846 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-09 13:41:29.774  2789  2846 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-09 13:41:29.774  2789  2846 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
,09-09 13:41:29.774  2789  2846 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-09 13:41:29.774  2789  2846 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-09 13:41:29.774  2789  2846 D BluetoothAdapterState: Stopping profile services that were post enabled
,09-09 13:41:29.774  2789  2789 E BluetoothAdapterService(308992202): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-09 13:41:29.774  2789  2789 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 13:41:29.774  2789  2789 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-09 13:41:29.784  7414  7414 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,09-09 13:41:29.784  2789  2789 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-09 13:41:29.784  2789  2789 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 13:41:29.784  7414  7414 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-09 13:41:29.784  7414  7414 D UserAnalysis: Create SecureDbHelper
,09-09 13:41:29.784  2789  2789 D HidService: Received stop request...Stopping profile...
,09-09 13:41:29.784  2789  2789 D HidService: Stopping Bluetooth HidService
09-09 13:41:29.784  2789  2789 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-09 13:41:29.784  2789  2789 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-09 13:41:29.784  2789  2789 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-09 13:41:29.784  2789  2789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@126ad8ca
09-09 13:41:29.784  2789  2789 E BluetoothAdapterService(308992202): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-09 13:41:29.784  2789  2789 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 13:41:29.784  2789  2789 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-09 13:41:29.784  4412  4412 D BluetoothInputDevice: Proxy object disconnected
09-09 13:41:29.784  2789  2789 D HealthService: Received stop request...Stopping profile...
09-09 13:41:29.784  4412  4412 D HidProfile: Bluetooth service disconnected
09-09 13:41:29.784  2789  2789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@126ad8ca
,09-09 13:41:29.784  2789  2789 D BluetoothA2dp: Proxy object disconnected
09-09 13:41:29.784  2789  2789 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-09 13:41:29.784  2789  3021 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,09-09 13:41:29.784  2789  2789 I GKI_LINUX: GKI_exit_task 2 done
09-09 13:41:29.784  2789  2789 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,09-09 13:41:29.784  2789  2789 D PanService: Received stop request...Stopping profile...
09-09 13:41:29.784  2789  2789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@126ad8ca
,09-09 13:41:29.794  1014  1014 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 13:41:29.794  4412  4412 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 13:41:29.794  2789  2789 D BluetoothMapService: Received stop request...Stopping profile...
09-09 13:41:29.794  4412  4412 D PanProfile: Bluetooth service disconnected
,09-09 13:41:29.794  7414  7414 D IntelligenceServiceApplication: onCreate()
,09-09 13:41:29.794  2789  2789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@126ad8ca
,09-09 13:41:29.794  1014  1558 I ActivityManager: Killing 6158:com.samsung.android.sm/1000 (adj 15): empty #21
,09-09 13:41:29.804  2789  2789 D SapService: Received stop request...Stopping profile...
09-09 13:41:29.804  2789  2789 D SapService: Stopping Bluetooth SapService
09-09 13:41:29.804  2789  2789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@126ad8ca
,09-09 13:41:29.804  7414  7414 D IntelligenceServiceApplication: no applications having user consent for prediction
,09-09 13:41:29.804  2789  2789 E BluetoothAdapterService(308992202): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-09 13:41:29.804  2789  2789 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-09 13:41:29.804  2789  2789 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 13:41:29.804  2789  2789 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-09 13:41:29.804  2789  2789 E BluetoothAdapterService(308992202): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-09 13:41:29.804  2789  2789 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-09 13:41:29.804  2789  2789 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 13:41:29.804  2789  2789 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-09 13:41:29.804  2789  2789 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-09 13:41:29.804  2789  2789 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-09 13:41:29.804  2789  2789 E BluetoothAdapterService(308992202): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-09 13:41:29.804  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
09-09 13:41:29.804  2789  2789 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-09 13:41:29.804  2789  2789 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 13:41:29.804  2789  2789 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-09 13:41:29.804  2789  2789 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 13:41:29.804  2789  2789 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-09 13:41:29.804  4412  4412 D BluetoothMap: Proxy object disconnected
09-09 13:41:29.804  4412  4412 D MapProfile: Bluetooth service disconnected
,09-09 13:41:29.804  4412  4412 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-09 13:41:29.804  4412  4412 D SapProfile: Bluetooth service disconnected
,09-09 13:41:29.804  7414  7414 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,09-09 13:41:29.814  2789  2789 E BluetoothAdapterService(308992202): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-09 13:41:29.814  2789  2789 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-09 13:41:29.814  2789  2789 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-09 13:41:29.814  2789  2789 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,09-09 13:41:29.814  2789  2789 E BluetoothAdapterService(308992202): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-09 13:41:29.814  2789  2789 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,09-09 13:41:29.814  2789  2789 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-09 13:41:29.814  2789  2789 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
09-09 13:41:29.814  1014  1557 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-09 13:41:29.814  1014  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:29.814  7414  7414 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
09-09 13:41:29.814  1014  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:29.814  1014  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:29.814  1014  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:29.834  7430  7430 E Zygote  : MountEmulatedStorage(),
,09-09 13:41:29.834  7430  7430 I libpersona: KNOX_SDCARD checking this for 10105
,09-09 13:41:29.834  7430  7430 E Zygote  : v2
09-09 13:41:29.834  7430  7430 I libpersona: KNOX_SDCARD not a persona
09-09 13:41:29.834  7430  7430 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:41:29.834  1014  1557 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7430 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
09-09 13:41:29.834  7430  7430 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 13:41:29.834  7430  7430 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-09 13:41:29.834  2789  2846 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
09-09 13:41:29.834  2789  2846 D BluetoothAdapterProperties: Setting state to 10
09-09 13:41:29.834  2789  2846 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-09 13:41:29.834  2789  2846 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-09 13:41:29.834  2789  2846 D BluetoothAdapterService: updateAdapterState state is 10
09-09 13:41:29.834  2789  2846 D BluetoothAdapterService: Autoconnection is available 
09-09 13:41:29.834  2789  2846 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-09 13:41:29.834  2789  2846 I BluetoothAdapterState: Entering OffState
,09-09 13:41:29.834  1748  1962 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 13:41:29.834  1748  1962 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 13:41:29.844  2789  2913 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 13:41:29.844  2789  2913 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 13:41:29.844  4412  4422 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 13:41:29.844  4412  4422 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 13:41:29.844  4412  4421 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-09 13:41:29.844  2789  2851 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 13:41:29.844  6937  6945 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 13:41:29.844  6937  6945 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 13:41:29.844  6937  6945 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-09 13:41:29.844  6937  6945 D BluetoothLeAdvertiser: Exit stop advertising
09-09 13:41:29.844  6937  6945 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-09 13:41:29.844  6937  6945 D BluetoothLeScanner: Exiting stopAllScan
,09-09 13:41:29.844  1014  1045 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-09 13:41:29.854  1460  1489 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 13:41:29.854  1460  1489 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 13:41:29.854  4412  4422 D BluetoothMap: onBluetoothStateChange: up=false
,09-09 13:41:29.854  1174  3070 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 13:41:29.854  1174  3070 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 13:41:29.854  2635  2648 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 13:41:29.854  2635  2648 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 13:41:29.854  4412  5408 D Bluetoothsap: onBluetoothStateChange: up=false
,09-09 13:41:29.854  4412  5408 D Bluetoothsap: Unbinding service...
09-09 13:41:29.854  4412  4422 D BluetoothPbap: onBluetoothStateChange: up=false
,09-09 13:41:29.854  4412  4421 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-09 13:41:29.854  1452  1473 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 13:41:29.854  1452  1473 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 13:41:29.854  1477  1491 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 13:41:29.854  1477  1491 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 13:41:29.854  1014  1045 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 13:41:29.854  1014  1045 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 13:41:29.864   305   305 I art     : Explicit concurrent mark sweep GC freed 8689(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 601us total 26.434ms
,09-09 13:41:29.864  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:29.864  1014  1014 I InputMethodManagerService: [BT Setting State] State =10
09-09 13:41:29.864  1014  1014 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-09 13:41:29.864  7430  7430 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:41:29.864  7430  7430 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:29.864  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-09 13:41:29.864  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:29.864  1174  1174 D BluetoothTile:  getBluetoothState : 10
,09-09 13:41:29.864  1868  1868 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0,
,09-09 13:41:29.874   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 576us total 16.871ms
,09-09 13:41:29.884  4412  4412 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:41:29.884  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:29.884  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:29.884  1014  1558 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 13:41:29.884  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:29.884  1014  1502 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-09 13:41:29.884  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-09 13:41:29.894   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 639us total 18.994ms
,09-09 13:41:29.964  6937  6991 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:29.964  6937  6991 D BluetoothAdapter: enable()
,09-09 13:41:29.964  1014  1558 W ActivityManager: Permission Denial: getCurrentUser() from pid=6937, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-09 13:41:29.974  1014  1558 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-09 13:41:29.974  1014  1558 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6937, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-09 13:41:29.974  1014  1558 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-09 13:41:29.974  1014  1558 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
09-09 13:41:29.974  1014  1558 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-09 13:41:29.974  1014  1558 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-09 13:41:29.974  1014  1558 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
09-09 13:41:29.974  1014  1558 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-09 13:41:29.974  1014  1558 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-09 13:41:29.974  1014  1558 D SettingsProvider: name = bluetooth_on
,09-09 13:41:29.974  1014  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-09 13:41:29.974  1014  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-09 13:41:29.984  1014  1045 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-09 13:41:29.984  2789  2846 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-09 13:41:29.984  2789  2846 D BluetoothAdapterProperties: Setting state to 11
09-09 13:41:29.984  2789  2846 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-09 13:41:29.984  2789  2846 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-09 13:41:29.984  2789  2846 D BluetoothAdapterService: updateAdapterState state is 11
,09-09 13:41:29.984  2789  2846 D BluetoothAdapterService: Autoconnection is available 
09-09 13:41:29.984  2789  2846 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-09 13:41:29.984  2789  2846 D BtConfig.SecureMode: isSecureModeOn:false
09-09 13:41:29.984  2789  2846 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-09 13:41:29.984  2789  2846 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
,09-09 13:41:29.984  2789  2846 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-09 13:41:29.984  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:29.984  2789  2846 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
09-09 13:41:29.984  2789  2846 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-09 13:41:29.984  2789  2846 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
09-09 13:41:29.984  2789  2846 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 13:41:29.984  2789  2846 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
09-09 13:41:29.984  2789  2846 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-09 13:41:29.984  2789  2846 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
09-09 13:41:29.984  2789  2846 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-09 13:41:29.984  2789  2846 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
09-09 13:41:29.984  2789  2846 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 13:41:29.984  2789  2846 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
09-09 13:41:29.984  2789  2846 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-09 13:41:29.984  2789  2846 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
09-09 13:41:29.984  2789  2846 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-09 13:41:29.984  2789  2846 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-09 13:41:29.984  2789  2846 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-09 13:41:29.984  2789  2846 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-09 13:41:29.984  2789  2846 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-09 13:41:29.984  2789  2846 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-09 13:41:29.984  2789  2846 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-09 13:41:29.984  2789  2846 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
09-09 13:41:29.984  2789  2846 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
09-09 13:41:29.984  2789  2846 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-09 13:41:29.984  2789  2846 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-09 13:41:29.984  2789  2846 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-09 13:41:29.984  1014  1014 I InputMethodManagerService: [BT Setting State] State =11
,09-09 13:41:29.994  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-09 13:41:29.994  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:29.994  1174  1174 D BluetoothTile:  getBluetoothState : 11
,09-09 13:41:29.994   256   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-09 13:41:29.994   256   525 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:41:29.994  1868  1868 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-09 13:41:29.994  7430  7448 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-09 13:41:30.004  1174  1720 D BluetoothTile:  handleUpdatestate:false name:null
09-09 13:41:30.004  1174  1720 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-09 13:41:30.004  4412  4412 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:41:30.004  1014  1502 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:41:30.004  1014  1502 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-09 13:41:30.004  1014  1213 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 13:41:30.004  1014  1213 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-09 13:41:30.004  1014  1502 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:30.004  1014  1502 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:30.004  1014  1502 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:30.004   256   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-09 13:41:30.014  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:30.014   256   525 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:41:30.014  7430  7448 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-09 13:41:30.014  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 13:41:30.014  2789  2846 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
09-09 13:41:30.014  2789  2846 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-09 13:41:30.014  2789  2846 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-09 13:41:30.014  1014  1216 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:41:30.014  1014  1216 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 13:41:30.014  2789  2789 D HeadsetService: Received start request. Starting profile...
,09-09 13:41:30.014  2789  2789 D HeadsetService: start()
09-09 13:41:30.014  2789  2789 D HeadsetStateMachine: make
,09-09 13:41:30.014  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:30.014  1014  1216 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:30.014  1014  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:30.014  1014  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:30.014  2789  2846 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
09-09 13:41:30.014  2789  2846 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 13:41:30.014  2789  2846 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-09 13:41:30.014  1014  1558 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 13:41:30.024  1014  1558 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-09 13:41:30.024  2789  2789 E HeadsetStateMachine: # of Max HF connection is 2
09-09 13:41:30.024  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:30.024  1014  1558 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:30.024  1014  1558 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:30.024  1014  1558 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:30.024  2789  2846 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
09-09 13:41:30.024  2789  2846 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-09 13:41:30.024  2789  2846 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
09-09 13:41:30.024  1014  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:41:30.024  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-09 13:41:30.024  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:30.024  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:30.024  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:30.034  2789  2846 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
09-09 13:41:30.034  1014  1328 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
09-09 13:41:30.034  2789  2846 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-09 13:41:30.034  1014  1328 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
09-09 13:41:30.034  2789  2846 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
09-09 13:41:30.034  1014  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 13:41:30.034  1014  1328 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:30.034  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-09 13:41:30.034  1014  1328 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:30.034  1014  1213 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
09-09 13:41:30.034  1014  1328 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-09 13:41:30.034  1014  1213 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
09-09 13:41:30.034  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-09 13:41:30.034  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:30.034  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:30.034  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 13:41:30.034  1014  1213 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:30.034  1014  1213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 13:41:30.034  1014  1213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
09-09 13:41:30.034  2789  2789 I bluedroid: get_profile_interface handsfree
,09-09 13:41:30.044  2789  2846 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,09-09 13:41:30.044  2789  2846 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 13:41:30.044  2789  2846 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService,
,09-09 13:41:30.044  1014  1502 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:41:30.044  1014  1502 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-09 13:41:30.044  1014  1502 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:30.044  1014  1502 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:30.044  1014  1502 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:30.044  2789  2846 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService,
09-09 13:41:30.044  2789  2846 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-09 13:41:30.044  2789  2846 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-09 13:41:30.044  1014  1558 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:41:30.044  1014  1558 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-09 13:41:30.044  1014  1558 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:30.054  1014  1558 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:30.054  1014  1558 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:30.054  2789  2846 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-09 13:41:30.054  2789  2846 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-09 13:41:30.054  2789  2846 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-09 13:41:30.054  2789  2846 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-09 13:41:30.054  2789  2846 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-09 13:41:30.054  2789  2846 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-09 13:41:30.054  2789  2846 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService,
,09-09 13:41:30.054  2789  2846 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-09 13:41:30.054  2789  2846 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-09 13:41:30.054  2789  2846 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-09 13:41:30.054  2789  2846 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-09 13:41:30.054  2789  2846 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-09 13:41:30.054  2789  2846 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-09 13:41:30.054  2789  2789 E DualScoManager: Dual Sco Manager already instantiated
09-09 13:41:30.054  2789  2789 I DualScoManager: Set HeadsetServiceHelper
09-09 13:41:30.054  2789  2789 D BluetoothAtMessage: createCMTIContentObservers
,09-09 13:41:30.054  1014  1557 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
09-09 13:41:30.054  1014  1557 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 13:41:30.054  1014  1557 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-09 13:41:30.054  1014  1557 D SettingsProvider: selectionArgs: false
09-09 13:41:30.054  1014  1557 D SettingsProvider: selectionArgs: 1002
,09-09 13:41:30.054  1014  1557 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 13:41:30.054  1014  1557 D SettingsProvider: ret = -1
,09-09 13:41:30.064  2789  7454 D HeadsetStateMachine: Enter Disconnected: -2
,09-09 13:41:30.064  2789  2789 D HeadsetService: mStartError = false
09-09 13:41:30.064  2789  2789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@126ad8ca
,09-09 13:41:30.064  2789  2789 D A2dpService: Received start request. Starting profile...
09-09 13:41:30.064  2789  2789 D A2dpService: start()
09-09 13:41:30.064  2789  2789 I bluedroid: get_profile_interface avrcp
,09-09 13:41:30.064  2789  7454 D HeadsetStateMachine: Clear mHeadsetBrsf
09-09 13:41:30.064  2789  7454 D HeadsetStateMachine: map size, before remove : 0
09-09 13:41:30.064  2789  7454 D HeadsetStateMachine: map size, after remove: 0
,09-09 13:41:30.064  2789  2789 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-09 13:41:30.064  2789  2789 D Avrcp   : Initialize Media Controller
09-09 13:41:30.064  2789  2789 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,09-09 13:41:30.074  2789  2789 E Avrcp   : getActiveSessions
09-09 13:41:30.074  2789  2789 D Avrcp   : pick active media Controller
09-09 13:41:30.074  2789  2789 D Avrcp   : Get the active Media Controller 
,09-09 13:41:30.074  2789  2789 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-09 13:41:30.074  2789  2789 D A2dpStateMachine: make
,09-09 13:41:30.084  2789  7455 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-09 13:41:30.084  2789  2789 I bluedroid: get_profile_interface a2dp
,09-09 13:41:30.084  2789  7457 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-09 13:41:30.084  2789  2789 E bt-btif : warning : media task started media_task_refcnt 1 
,09-09 13:41:30.084  2789  2789 D A2dpService: mStartError = false
09-09 13:41:30.084  2789  2789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@126ad8ca
,09-09 13:41:30.084  2789  7456 D A2dpStateMachine: Enter Disconnected: -2
,09-09 13:41:30.084  2789  2789 D HidService: Received start request. Starting profile...
09-09 13:41:30.084  2789  2789 D HidService: start()
09-09 13:41:30.084  2789  2789 I bluedroid: get_profile_interface hidhost
09-09 13:41:30.084  2789  2789 D HidService: setHidService(): set to: null
09-09 13:41:30.084  2789  2789 D HidService: mStartError = false
09-09 13:41:30.084  2789  2789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@126ad8ca
,09-09 13:41:30.094  2789  2789 D HealthService: Received start request. Starting profile...
09-09 13:41:30.094  2789  2789 D HealthService: start()
,09-09 13:41:30.094  2789  2789 I bluedroid: get_profile_interface health
,09-09 13:41:30.094  2789  2789 D HealthService: mStartError = false
09-09 13:41:30.094  2789  2789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@126ad8ca
,09-09 13:41:30.094  2789  2789 D HeadsetStateMachine: Try to query the phonestate on bind
,09-09 13:41:30.104  1452  1473 I Telecom : BluetoothPhoneService: queryPhoneState
,09-09 13:41:30.104  1452  1452 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
09-09 13:41:30.104  1452  1452 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-09 13:41:30.104  1452  1473 I Telecom : BluetoothPhoneService: Result of Message : true
,09-09 13:41:30.104  2789  7455 D BluetoothMediaBrowser: no now playing list
09-09 13:41:30.104  2789  2789 D HeadsetStateMachine: Proxy object connected
09-09 13:41:30.104  2789  7455 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-09 13:41:30.104  2789  2789 D PanService: Received start request. Starting profile...
09-09 13:41:30.104  2789  2789 D PanService: start()
09-09 13:41:30.104  2789  2789 D BluetoothPanServiceJni: initializeNative(L110): pan
09-09 13:41:30.104  2789  2789 I bluedroid: get_profile_interface pan
09-09 13:41:30.104  2789  2789 D PanService: mStartError = false
09-09 13:41:30.104  2789  2789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@126ad8ca
,09-09 13:41:30.104  2789  2789 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-09 13:41:30.104  2789  7454 D HeadsetStateMachine: Disconnected process message: 11
,09-09 13:41:30.104  2789  2789 D BluetoothMapService: Received start request. Starting profile...
09-09 13:41:30.104  2789  2789 D BluetoothMapService: start()
,09-09 13:41:30.104  2789  2789 D BluetoothMapService: mStartError = false
09-09 13:41:30.104  2789  2789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@126ad8ca
,09-09 13:41:30.104  2789  2789 D SapService: Received start request. Starting profile...
09-09 13:41:30.104  2789  2789 D SapService: start()
09-09 13:41:30.104  2789  2789 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-09 13:41:30.104  2789  2789 I bluedroid: get_profile_interface sap
09-09 13:41:30.104  2789  2789 D SapService: mStartError = false
09-09 13:41:30.104  2789  2789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@126ad8ca
09-09 13:41:30.104  2789  2789 D HeadsetPhoneState: sendDeviceDataStateChanged
09-09 13:41:30.104  2789  2789 D HeadsetPhoneState: Signal level : previous=0 curr=4
09-09 13:41:30.104  2789  2789 E BluetoothAdapterService(308992202): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-09 13:41:30.104  2789  2789 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-09 13:41:30.104  2789  2789 E BluetoothAdapterService(308992202): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-09 13:41:30.104  2789  2789 E BluetoothAdapterService(308992202): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-09 13:41:30.104  2789  2789 E BluetoothAdapterService(308992202): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,09-09 13:41:30.104  2789  7454 D HeadsetStateMachine: Disconnected process message: 18
09-09 13:41:30.114  2789  7454 D HeadsetStateMachine: Disconnected process message: 10
,09-09 13:41:30.114  2789  7454 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-09 13:41:30.114  2789  2789 E BluetoothAdapterService(308992202): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-09 13:41:30.114  2789  7454 D HeadsetStateMachine: Disconnected process message: 11
,09-09 13:41:30.124  2789  2789 E BluetoothAdapterService(308992202): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-09 13:41:30.124  2789  2789 E BluetoothAdapterService(308992202): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-09 13:41:30.134  2789  2846 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
09-09 13:41:30.134  2789  2846 I bluedroid: enable
,09-09 13:41:30.134  2789  2849 E bt-btif : Calling BTA_HhEnable
,09-09 13:41:30.134  2789  2849 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
09-09 13:41:30.134  2789  2849 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
09-09 13:41:30.134  2789  2849 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
09-09 13:41:30.134  2789  2849 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
09-09 13:41:30.134  2789  2849 E BluetoothServiceJni: populateRssiValuesNative
09-09 13:41:30.134  2789  2849 I bluedroid: getModelRssiValues
09-09 13:41:30.134  2789  2849 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-09 13:41:30.134  2789  2849 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-09 13:41:30.134  2789  2849 D BluetoothAdapterProperties: Name is: Galaxy A3
,09-09 13:41:30.134  1014  1014 D SettingsProvider: name = bluetooth_name
,09-09 13:41:30.144  2789  2849 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-09 13:41:30.144  2789  2849 D BluetoothAdapterProperties: Scan Mode:20
09-09 13:41:30.144  2789  2849 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 13:41:30.144  2789  2849 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
09-09 13:41:30.144  2789  2849 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
09-09 13:41:30.144  2789  2849 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,09-09 13:41:30.144  2789  2849 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-09 13:41:30.144  2789  2849 E bt-btif : JVenable fails
,09-09 13:41:30.144  2789  2849 D bte_conf: Device ID record 1 : primary
09-09 13:41:30.144  2789  2849 D bte_conf:   vendorId            = 0075
09-09 13:41:30.144  2789  2849 D bte_conf:   vendorIdSource      = 0001
09-09 13:41:30.144  2789  2849 D bte_conf:   product             = 0100
09-09 13:41:30.144  2789  2849 D bte_conf:   version             = 0200
09-09 13:41:30.144  2789  2849 D bte_conf:   clientExecutableURL = 
09-09 13:41:30.144  2789  2849 D bte_conf:   serviceDescription  = 
09-09 13:41:30.144  2789  2849 D bte_conf:   documentationURL    = 
09-09 13:41:30.144  2789  2849 D bte_conf: bte_load_did_conf no section named DID2.
09-09 13:41:30.144  2789  2849 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
09-09 13:41:30.144  2789  2849 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-09 13:41:30.144  2789  2846 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-09 13:41:30.144  2789  2846 D BluetoothAdapterProperties: ScanMode =  20
09-09 13:41:30.144  2789  2846 D BluetoothAdapterProperties: State =  11
,09-09 13:41:30.144  1014  1027 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-09 13:41:30.144  2789  2846 D BluetoothAdapterProperties: Setting state to 12
,09-09 13:41:30.144  2789  2846 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-09 13:41:30.144  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:30.144  2789  2849 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-09 13:41:30.154  2789  2849 D BluetoothAdapterProperties: Scan Mode:21
09-09 13:41:30.154  2789  2849 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-09 13:41:30.154  1014  1501 D SettingsProvider: name = bluetooth_a2dp_sink_mode
09-09 13:41:30.154  1014  1501 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 13:41:30.154  1014  1501 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 13:41:30.154  1014  1501 D SettingsProvider: selectionArgs: false
09-09 13:41:30.154  1014  1501 D SettingsProvider: selectionArgs: 1002
09-09 13:41:30.154  1014  1501 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 13:41:30.154  1014  1501 D SettingsProvider: ret = -1
,09-09 13:41:30.154  2789  2846 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-09 13:41:30.154  2789  2846 D BluetoothAdapterService: updateAdapterState state is 12
,09-09 13:41:30.154  1014  1557 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:41:30.154  1014  1557 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-09 13:41:30.154  1014  1557 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:30.154  1014  1557 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:30.154  1014  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:30.154  2789  2846 D BluetoothAdapterService: Autoconnection is available 
09-09 13:41:30.154  2789  2846 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-09 13:41:30.154  2789  2846 D BluetoothAdapterService: starting service from this receiver
09-09 13:41:30.154  1014  1501 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:41:30.154  1748  1761 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 13:41:30.154  1014  1501 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
09-09 13:41:30.154  1748  1761 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 13:41:30.154  1014  1045 D BluetoothPan: Binding service...
09-09 13:41:30.154  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:30.154  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:30.154  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:30.154  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:30.154  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:30.154  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:30.154  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:30.154  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:41:30.154  1014  1501 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:30.154  1014  1501 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:30.154  1014  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:30.154  2789  2846 I BluetoothAdapterState: Entering On State from state = 11
09-09 13:41:30.154  1014  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-09 13:41:30.154  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-09 13:41:30.154  2789  2803 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 13:41:30.154  2789  2803 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 13:41:30.164  6937  6937 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:41:30.164  4412  4421 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 13:41:30.164  4412  4421 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-09 13:41:30.164  4412  5408 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-09 13:41:30.164  1014  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
09-09 13:41:30.164  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-09 13:41:30.164  2789  2789 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
09-09 13:41:30.164  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:30.164  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:30.164  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-09 13:41:30.164  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:30.164  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:30.164  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:30.164  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:30.164  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:30.164  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:30.164  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:30.164  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:41:30.164  2789  2912 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 13:41:30.164  2789  2912 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-09 13:41:30.174  6937  6937 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:41:30.174  1014  1045 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-09 13:41:30.174  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 13:41:30.174  6937  6937 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-09 13:41:30.174  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:30.174  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:30.174  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:30.174  6937  6946 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-09 13:41:30.174  6937  6946 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 13:41:30.174  1014  1014 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 13:41:30.174  1014  1045 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 13:41:30.174  2789  2789 I BluetoothPbapService: Handler(): got msg=1
,09-09 13:41:30.174  1014  1045 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-09 13:41:30.174  1014  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-09 13:41:30.174  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-09 13:41:30.184  6937  6937 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-09 13:41:30.184  1014  1558 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-09 13:41:30.184  1477  2483 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 13:41:30.184  1014  1045 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 13:41:30.184  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-09 13:41:30.184  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:30.184  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:30.184  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:30.184  1477  2483 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 13:41:30.184  1014  1014 D BluetoothA2dp: Proxy object connected
,09-09 13:41:30.184  4412  4412 D BluetoothInputDevice: Proxy object connected
09-09 13:41:30.184  4412  4412 D HidProfile: Bluetooth service connected
09-09 13:41:30.184  2789  7469 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-09 13:41:30.194  4412  4421 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 13:41:30.194  2789  2789 D BluetoothA2dp: Proxy object connected
09-09 13:41:30.194  2789  2789 D BluetoothAdapterService: Bluetooth A2dp source service connected
,09-09 13:41:30.194  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
,09-09 13:41:30.194  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:30.194  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:30.194  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:30.194  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:30.194  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:30.194  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:30.194  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:41:30.194  1014  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-09 13:41:30.194  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-09 13:41:30.194  2789  7469 D BluetoothSocket: bindListen(): myUserId = 0
09-09 13:41:30.194  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:30.194  2789  7469 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:41:30.194  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:30.194  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:30.194  4412  4421 E BluetoothHeadset: BluetoothHeadset service is binded
09-09 13:41:30.194  1460  1494 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 13:41:30.194  1460  1494 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 13:41:30.204  4412  4422 D BluetoothMap: onBluetoothStateChange: up=true
09-09 13:41:30.204  4412  4412 D HeadsetProfile: Bluetooth service connected
,09-09 13:41:30.204  6937  6937 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:41:30.204  1014  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,09-09 13:41:30.204  2789  7469 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
,09-09 13:41:30.204  2789  7469 D BluetoothSocket: bindListen(), new LocalSocket 
,09-09 13:41:30.204  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:30.204  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
09-09 13:41:30.204  2789  7469 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 13:41:30.204  2789  7469 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@69b3dfd
09-09 13:41:30.204  2789  7469 D BluetoothSocket: channel: 19
,09-09 13:41:30.204  2789  7469 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
09-09 13:41:30.204  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:30.204  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:30.204  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:30.204  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:30.204  1174  1190 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 13:41:30.204  1174  1190 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-09 13:41:30.204  4412  4412 D BluetoothMap: Proxy object connected
,09-09 13:41:30.204  4412  5408 D BluetoothPan: Binding service...
,09-09 13:41:30.214  4412  4412 D MapProfile: Bluetooth service connected
09-09 13:41:30.214  4412  4412 D BluetoothMap: getConnectedDevices()
,09-09 13:41:30.214  1014  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,09-09 13:41:30.214  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-09 13:41:30.214  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:30.214  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:30.214  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:30.214  2635  4062 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 13:41:30.214  2635  4062 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 13:41:30.214  1452  1461 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 13:41:30.214  1014  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 13:41:30.214  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 13:41:30.214  4412  4412 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 13:41:30.214  4412  4412 D PanProfile: Bluetooth service connected
09-09 13:41:30.214  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:30.214  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:30.214  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
09-09 13:41:30.214  1452  1461 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 13:41:30.214  1452  1461 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 13:41:30.224  1014  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 13:41:30.224  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 13:41:30.224  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:30.224  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:30.224  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
09-09 13:41:30.224  1452  1461 E BluetoothHeadset: BluetoothHeadset service is binded
09-09 13:41:30.224  4412  4421 D Bluetoothsap: onBluetoothStateChange: up=true
09-09 13:41:30.224  4412  4421 D Bluetoothsap: Binding service...
,09-09 13:41:30.224  4412  4421 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-09 13:41:30.224  1014  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,09-09 13:41:30.224  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-09 13:41:30.224  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:30.224  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:30.224  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:30.234  4412  4421 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-09 13:41:30.234  4412  4422 D BluetoothPbap: onBluetoothStateChange: up=true
,09-09 13:41:30.234  4412  4412 D Bluetoothsap: BluetoothSAP Proxy object connected
09-09 13:41:30.234  4412  4412 D SapProfile: Bluetooth service connected
09-09 13:41:30.234  4412  4412 D Bluetoothsap: getConnectedDevices()
,09-09 13:41:30.234  1014  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-09 13:41:30.234  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-09 13:41:30.234  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:30.234  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:30.234  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:30.234  4412  4421 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 13:41:30.234  4412  4421 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-09 13:41:30.234  7430  7430 D StrictMode: StrictMode policy violation; ~duration=218 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at java.io.File.exists(File.java:363)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 13:41:30.234  7430  7430 D StrictMode: StrictMode policy violation; ~duration=217 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 13:41:30.234  1014  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-09 13:41:30.234  7430  7430 D StrictMode: StrictMode policy violation; ~duration=215 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 13:41:30.234  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-09 13:41:30.234  7430  7430 D StrictMode: StrictMode policy violation; ~duration=214 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.q.e.b(PG:170)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 13:41:30.234  7430  7430 D StrictMode: StrictMode policy violation; ~duration=212 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.q.k.c(PG:18147)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.q.k.d(PG:583)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.q.e.b(PG:170)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 13:41:30.234  7430  7430 D StrictMode: StrictMode policy violation; ~duration=178 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at java.io.File.exists(File.java:363)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 13:41:30.234  7430  7430 D StrictMode: StrictMode policy violation; ~duration=177 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at java.io.File.exists(File.java:363)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 13:41:30.234  7430  7430 D StrictMode: StrictMode policy violation; ~duration=176 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at java.io.File.lastModified(File.java:571)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 13:41:30.234  7430  7430 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 13:41:30.234  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:30.234  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:30.234  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-09 13:41:30.234  1452  1461 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 13:41:30.234  1452  1461 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-09 13:41:30.234  4412  4412 D BluetoothPbap: Proxy object connected
09-09 13:41:30.234  4412  4412 D PbapServerProfile: Bluetooth service connected
09-09 13:41:30.234  1014  1557 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:30.234  1014  1557 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:30.234  1014  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
09-09 13:41:30.234  1452  1473 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-09 13:41:30.244  1014  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 13:41:30.244  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-09 13:41:30.244  4412  4412 D BluetoothA2dp: Proxy object connected
09-09 13:41:30.244  4412  4412 D A2dpProfile: Bluetooth service connected
09-09 13:41:30.244  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:30.244  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:30.244  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
09-09 13:41:30.244  1452  1473 E BluetoothHeadset: BluetoothHeadset service is binded
09-09 13:41:30.244  1477  3489 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 13:41:30.244  1477  3489 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-09 13:41:30.244  1014  1045 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 13:41:30.244  1014  1045 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-09 13:41:30.244  1014  1045 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-09 13:41:30.244  1014  1502 I ActivityManager: Killing 7103:com.sec.pcw.device/1000 (adj 15): empty #21
09-09 13:41:30.254  1014  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 13:41:30.254  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-09 13:41:30.254  1014  1045 E BluetoothHeadset: BluetoothHeadset service is binded
09-09 13:41:30.254  1014  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-09 13:41:30.254  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
09-09 13:41:30.254  4412  4412 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-09 13:41:30.254  1452  1452 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@20ec1c9, true
09-09 13:41:30.254  1452  1452 D BluetoothHeadset: registerMessageListener
09-09 13:41:30.254  1174  1174 D BluetoothTile:  onBluetoothStateChange:
09-09 13:41:30.264  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-09 13:41:30.264  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:30.264  1174  1174 D BluetoothTile:  getBluetoothState : 12
09-09 13:41:30.264  1868  1868 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
09-09 13:41:30.264  1174  1720 D BluetoothTile:  handleUpdatestate:false name:null
09-09 13:41:30.264  1014  1213 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-09 13:41:30.264  1014  1213 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
09-09 13:41:30.274  1014  1213 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:30.274  1014  1213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:30.274  1014  1213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
09-09 13:41:30.274  1174  1720 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 13:41:30.274  2789  2806 D HeadsetService: registerMessageListener
09-09 13:41:30.274  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:30.274  2789  2806 D HeadsetService: registerMessageListener
09-09 13:41:30.274  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:30.274  1014  1014 I InputMethodManagerService: [BT Setting State] State =12
09-09 13:41:30.274  1014  1014 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
09-09 13:41:30.274  2789  7454 D HeadsetStateMachine: Disconnected process message: 70
09-09 13:41:30.274  2789  7454 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@baaaaf2
09-09 13:41:30.274  1452  1452 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-09 13:41:30.274  1452  1452 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-09 13:41:30.274  2789  7472 D BluetoothMapMasInstance: set MAP SDP message type : 1
09-09 13:41:30.284  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:30.284  1452  1452 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-09 13:41:30.284  1452  1452 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
09-09 13:41:30.284  1452  1452 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
09-09 13:41:30.284  2635  2635 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 13:41:30.294  4412  4412 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:30.294  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:30.294  2789  7472 D BluetoothSocket: bindListen(): myUserId = 0
09-09 13:41:30.294  1014  1328 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-09 13:41:30.294  2789  7472 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:41:30.294  2789  7472 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
09-09 13:41:30.294  1014  1027 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
09-09 13:41:30.294  2789  7472 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 13:41:30.294  1174  1720 D BluetoothTile:  handleUpdatestate:false name:null
09-09 13:41:30.294  2789  7472 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 13:41:30.294  2789  7472 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@20ecb543
09-09 13:41:30.294  2789  7472 D BluetoothSocket: channel: 5
09-09 13:41:30.294  2789  7454 D HeadsetStateMachine: Disconnected process message: 9
09-09 13:41:30.294  2789  7454 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
09-09 13:41:30.294  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-09 13:41:30.294   282   282 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
09-09 13:41:30.294   282   282 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-09 13:41:30.294   282   282 V voice   : voice_set_parameters: exit with code(-2)
09-09 13:41:30.294   282   282 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-09 13:41:30.294   282   282 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-09 13:41:30.294   282   282 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-09 13:41:30.294   282   282 V audio_hw_primary: adev_set_parameters: exit
09-09 13:41:30.294  4412  4412 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-09 13:41:30.294  4412  4412 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-09 13:41:30.294  4412  4412 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-09 13:41:30.294  2789  7454 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
09-09 13:41:30.294  4412  4412 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
09-09 13:41:30.304  4412  4412 D DockEventReceiver: finishStartingService: stopping service
09-09 13:41:30.304  4412  4412 D BluetoothNotiBroadcastReceiver: onReceive
09-09 13:41:30.314  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:30.314  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-09 13:41:30.324  7430  7461 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-09 13:41:30.324  2635  2635 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 13:41:30.334  4412  4412 D BluetoothNotiBroadcastReceiver: onReceive
,09-09 13:41:30.334  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:30.334  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-09 13:41:30.354  1014  1216 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:41:30.354  1014  1216 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:30.354  1014  1216 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:30.354  1014  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-09 13:41:30.364  4412  4412 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 13:41:30.364  1014  1555 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-09 13:41:30.364  1014  1555 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-09 13:41:30.364  1014  1555 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:30.364  1014  1555 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:30.364  1014  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-09 13:41:30.374  2635  2635 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 13:41:30.374  4412  4412 D DockEventReceiver: finishStartingService: stopping service
,09-09 13:41:30.374  4412  4412 D BluetoothNotiBroadcastReceiver: onReceive
,09-09 13:41:30.384  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:41:30.384  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-09 13:41:30.384  2789  2789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@126ad8ca
,09-09 13:41:30.384  2789  2789 D BtConfig.SecureMode: isSecureModeOn:false
,09-09 13:41:30.394  1014  1557 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 13:41:30.394  1014  1557 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-09 13:41:30.394  1014  1557 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:30.394  1014  1557 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 13:41:30.394  1014  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:30.404  1014  1216 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-09 13:41:30.414  2789  7481 D BluetoothSocket: bindListen(): myUserId = 0
09-09 13:41:30.414  2789  7481 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:41:30.414  2789  7481 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[86]}
,09-09 13:41:30.414  2789  7481 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 13:41:30.414  2789  7481 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 13:41:30.414  2789  7481 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3d9b629f
09-09 13:41:30.414  2789  7481 D BluetoothSocket: channel: 12
09-09 13:41:30.414  2789  7481 I BtOppRfcommListener: Accept thread started.
,09-09 13:41:30.494  6937  6991 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:30.494  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:30.494  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:30.494  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:30.494  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:41:30.494  6937  6991 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d67d48 removed from the list
09-09 13:41:30.494  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:30.494  6937  6991 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e2f77e1 removed from the list
09-09 13:41:30.494  6937  6991 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:30.494  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:30.494  6937  6991 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:41:30.494  6937  6991 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60dad60 added. We now have 3 listener(s)
,09-09 13:41:30.494  2789  2852 W bt-sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
,09-09 13:41:30.494  2789  2852 E bt-btif : DISCOVERY_COMP_EVT slot id:7, failed to find channle,                                       status:1, scn:0
,09-09 13:41:30.494  2789  2852 W bt-btif : invalid rfc slot id: 7
,09-09 13:41:30.504  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-09 13:41:30.504  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:30.504  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:41:30.504  6937  6991 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:41:30.504  6937  6991 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36e64219 added. We now have 3 listener(s)
09-09 13:41:30.504  6937  6991 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:41:30.504  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:41:30.514  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:30.514  7318  7318 I wpa_supplicant: nl80211: Received scan results (3 BSSes)
09-09 13:41:30.514  7318  7318 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-09 13:41:30.514  7318  7318 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-09 13:41:30.514  7318  7318 I wpa_supplicant: Trying to associate with  'G700'
09-09 13:41:30.514  7318  7318 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
09-09 13:41:30.514  1014  7385 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
09-09 13:41:30.514  7318  7318 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,09-09 13:41:30.524  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-09 13:41:30.524  1014  1125 D SecContentProvider2: mCursor = null
,09-09 13:41:30.534  6937  6991 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:30.534  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:30.534  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:30.534  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:30.534  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:30.534  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:30.534  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:30.534  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:41:30.534  6937  6991 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:41:30.534  6937  6991 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:41:30.534  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:30.544  1014  1027 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-09 13:41:30.544  1014  1027 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-09 13:41:30.544  1014  1027 D SecContentProvider2: mCursor = null
,09-09 13:41:30.544  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:30.544  1014  1027 D WifiService: setWifiEnabled: false pid=6937, uid=10170
,09-09 13:41:30.544  1014  1027 D SettingsProvider: name = wifi_on
,09-09 13:41:30.564  1014  1124 D WifiP2pService: InactiveState{ what=131204 }
09-09 13:41:30.564  1014  1124 D WifiP2pService: P2pEnabledState{ what=131204 }
,09-09 13:41:30.564  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 1
,09-09 13:41:30.564  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-09 13:41:30.564  1014  1127 E ConnectivityService: updateNetworkInfo()
,09-09 13:41:30.564  1014  1014 D RttService: SCAN_AVAILABLE : 1
,09-09 13:41:30.564  1014  1149 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 13:41:30.574  1014  1148 D WifiScanningService: DefaultState got{ when=-5ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 13:41:30.574  1014  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:41:30.574  1014  1046 D WifiDisplayAdapter: onP2pDisconnected
09-09 13:41:30.574  1014  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 13:41:30.574  1014  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-09 13:41:30.584  4412  4412 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-09 13:41:30.584  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-09 13:41:30.584  4412  4412 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 13:41:30.584  1014  1124 D WifiP2pService: P2pDisablingState
,09-09 13:41:30.584  1014  1124 D WifiP2pService: P2pDisablingState{ what=147458 }
09-09 13:41:30.584  1014  1124 D WifiP2pService: p2p socket connection lost
,09-09 13:41:30.584  1014  1124 D WifiP2pService: P2pDisabledState
09-09 13:41:30.584  1014  1127 E ConnectivityService: updateNetworkInfo()
,09-09 13:41:30.584  4412  4412 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 13:41:30.584  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-09 13:41:30.594  1014  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,09-09 13:41:30.594  1014  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false,
09-09 13:41:30.594  1014  1046 D WifiDisplayController: disconnect
,09-09 13:41:30.594  1014  1046 D WifiDisplayController: updateConnection
09-09 13:41:30.594   277  1002 D CommandListener: Clearing all IP addresses on wlan0
09-09 13:41:30.594  1014  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 13:41:30.594  4412  4412 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-09 13:41:30.594  1014  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-09 13:41:30.594  4412  4412 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 13:41:30.594  1014  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-09 13:41:30.594  4412  4412 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-09 13:41:30.594  1014  1046 D WifiDisplayAdapter: onP2pDisconnected
09-09 13:41:30.594  4412  4504 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-09 13:41:30.594  1014  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 13:41:30.594  1014  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-09 13:41:30.594  1174  1174 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-09 13:41:30.594  1014  1026 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 13:41:30.594  1174  1174 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-09 13:41:30.604  7072  7072 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 13:41:30.604  7072  7072 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-09 13:41:30.604  7072  7072 D FileShare-Client: Outbound.stopDelayTimer - 
,09-09 13:41:30.604  7318  7318 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-09 13:41:30.604  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-09 13:41:30.614  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-09 13:41:30.614  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 13:41:30.614  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
09-09 13:41:30.614  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:30.614  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:30.614  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:30.614  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:30.614  7087  7087 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 13:41:30.624  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-09 13:41:30.624  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-09 13:41:30.624  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-09 13:41:30.624  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:30.624  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:30.624  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-09 13:41:30.624  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-09 13:41:30.624  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:30.624  1174  1720 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-09 13:41:30.624  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,09-09 13:41:30.634  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:30.634  1174  1174 D HotspotTile: onReceive : 0, 0
,09-09 13:41:30.634  4412  4412 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
,09-09 13:41:30.634  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:30.634  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:30.634  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:30.634  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:41:30.634  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:30.634  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:30.634  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:30.634  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:41:30.644  6937  6937 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:41:30.644  4412  4412 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-09 13:41:30.644  4412  4412 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 13:41:30.644  4412  4412 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 13:41:30.644  4412  4412 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-09 13:41:30.644  4412  4412 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 13:41:30.644  4412  4412 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-09 13:41:30.644  4412  4504 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 13:41:30.654  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:30.654  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:30.654  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:30.654  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:41:30.654  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:30.654  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:30.654  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:30.654  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:41:30.654  7072  7072 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 13:41:30.654  7072  7072 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-09 13:41:30.654  7072  7072 D FileShare-Client: Outbound.stopDelayTimer - 
09-09 13:41:30.654  6937  6937 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:41:30.664  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:30.664  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:30.664  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:30.664  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:41:30.664  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:30.664  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:30.664  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:30.664  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:41:30.664  6937  6937 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:41:30.664  7087  7087 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 13:41:30.674  1014  1027 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 13:41:30.674  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:41:30.674  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:30.674  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:30.674  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:41:30.684  1609  1609 I Hs20UtilService: Starting #14
,09-09 13:41:30.684  1609  1661 I Hs20UtilService: Message received 5007
,09-09 13:41:30.684  4412  4412 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-09 13:41:30.684  4412  4412 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 13:41:30.684  4412  4412 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 13:41:30.684  4412  4412 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-09 13:41:30.684  4412  4412 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-09 13:41:30.684  4412  4412 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 13:41:30.684  4412  4504 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 13:41:30.694  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:41:30.694  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:41:30.694  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
,09-09 13:41:30.694  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:41:30.694  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:41:30.694  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
,09-09 13:41:30.694  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-09 13:41:30.704  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, true
09-09 13:41:30.704  1014  1043 D Tethering: interfaceStatusChanged wlan0, true
09-09 13:41:30.704  1014  1216 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 13:41:30.704  1014  1216 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:41:30.704  1014  1216 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:30.704  1014  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:30.704  1014  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:41:30.704  1014  1128 E Tethering: No numeric data
,09-09 13:41:30.704  1014  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-09 13:41:30.704  1014  1128 D Tethering: clearTetheredNotification()
,09-09 13:41:30.704  1609  1609 I Hs20UtilService: Starting #15
09-09 13:41:30.704  1609  1661 I Hs20UtilService: Message received 5011
,09-09 13:41:30.704  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
,09-09 13:41:30.704  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:30.704  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-09 13:41:30.704  1174  1174 D HotspotTile: updateTetherState():false, false
,09-09 13:41:30.714  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:41:30.714  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 13:41:30.714  1014  1122 V NetworkStats: performPollLocked() took 7ms,
09-09 13:41:30.714  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:30.714  6804  6804 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-09 13:41:30.714  6804  6804 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 13:41:30.714  6804  6804 D SecurityLogAgent: StateMachine : Current State = 1
09-09 13:41:30.714  6804  6804 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 13:41:30.714  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:30.714  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:30.784  7318  7318 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 13:41:30.844  1014  1043 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 13:41:30.844  1014  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-09 13:41:30.844  1014  1043 D Tethering: interfaceStatusChanged p2p0, false
09-09 13:41:30.844  7318  7318 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-09 13:41:30.864  7318  7318 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=00.00.00 reason=3 locally_generated=1
09-09 13:41:30.864  7318  7318 I wpa_supplicant: wlan0: State: ASSOCIATING -> DISCONNECTED
09-09 13:41:30.864  7318  7318 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=00.00.00 SSID=4E47373030
09-09 13:41:30.864  7318  7318 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-09 13:41:30.864  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:41:30.864  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:41:30.864  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
,09-09 13:41:30.864  1014  1128 D Tethering: InitialState.processMessage what=4
09-09 13:41:30.874  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:41:30.874  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-09 13:41:30.874  1014  1043 D Tethering: interfaceStatusChanged wlan0, false,
09-09 13:41:30.874  1014  1128 E Tethering: No numeric data
09-09 13:41:30.874  1014  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0,
,09-09 13:41:30.874  1014  1128 D Tethering: clearTetheredNotification()
,09-09 13:41:30.874  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
09-09 13:41:30.874  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit,
09-09 13:41:30.874  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-09 13:41:30.874  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:41:30.874  1174  1174 D HotspotTile: updateTetherState():false, false
09-09 13:41:30.874  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 13:41:30.884  1014  1122 V NetworkStats: performPollLocked() took 5ms
09-09 13:41:30.884  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:30.884  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:30.884  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:31.084  6937  6991 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:31.084  1014  1500 D WifiService: setWifiEnabled: true pid=6937, uid=10170,
09-09 13:41:31.084  1014  1500 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-09 13:41:31.084  1014  1500 W ActivityManager: Permission Denial: getCurrentUser() from pid=6937, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-09 13:41:31.084  1014  1500 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-09 13:41:31.084  1014  1500 D SecContentProvider2: mCursor = null
,09-09 13:41:31.084  1014  1500 W WifiService: Failed getting userId using ActivityManagerNative
09-09 13:41:31.084  1014  1500 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6937, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-09 13:41:31.084  1014  1500 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-09 13:41:31.084  1014  1500 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-09 13:41:31.084  1014  1500 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-09 13:41:31.084  1014  1500 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-09 13:41:31.084  1014  1500 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-09 13:41:31.084  1014  1500 D SettingsProvider: name = wifi_on
,09-09 13:41:31.134  7318  7318 I wpa_supplicant: Blacklist: Clear (all) ,
,09-09 13:41:31.244  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:41:31.244  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:41:31.244  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
09-09 13:41:31.244  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:41:31.244  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:41:31.244  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
,09-09 13:41:31.244  7318  7318 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
,09-09 13:41:31.354  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0,
,09-09 13:41:31.354  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21],
,09-09 13:41:31.354  7028  7028 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:41:31.364  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-09 13:41:31.364  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 13:41:31.374  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,09-09 13:41:31.374  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:31.374  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:31.374  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:31.374  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:31.374  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:31.374  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:31.374  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,09-09 13:41:31.374  1174  1720 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-09 13:41:31.374  1174  1174 D HotspotTile: onReceive : 1, 0
,09-09 13:41:31.374  4412  4412 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:41:31.374  1748  2193 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:41:31.374  1014  1094 V AlarmManager: waitForAlarm result :4
,09-09 13:41:31.384  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:31.384  1014  1328 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 13:41:31.384  1014  1328 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:41:31.384  1014  1328 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:31.384  1014  1328 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 13:41:31.384  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:31.384  1014  1328 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:41:31.384  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:31.394  1609  1609 I Hs20UtilService: Starting #16
,09-09 13:41:31.394  6804  6804 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-09 13:41:31.394  1609  1661 I Hs20UtilService: Message received 5011
,09-09 13:41:31.394  6804  6804 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-09 13:41:31.394  6804  6804 D SecurityLogAgent: StateMachine : Current State = 1
,09-09 13:41:31.394  6804  6804 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 13:41:31.424  1014  1041 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:31.424  1014  1041 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 13:41:31.424  1014  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,09-09 13:41:32.024  1014  1043 D Tethering: interfaceRemoved wlan0
,09-09 13:41:32.024  1014  1043 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-09 13:41:32.214  1014  1043 D Tethering: interfaceRemoved p2p0
,09-09 13:41:32.214  1014  1043 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-09 13:41:32.654   287   287 E SMD     : DCD OFF,
,09-09 13:41:32.984  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-09 13:41:32.984  1014  1125 E WifiHW  : ##################### set firmware type 0 #####################,
,09-09 13:41:33.324  1014  1043 D Tethering: interfaceAdded wlan0
,09-09 13:41:33.334  1014  1128 E Tethering: No numeric data
,09-09 13:41:33.334  1014  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-09 13:41:33.334  1014  1128 D Tethering: clearTetheredNotification()
,09-09 13:41:33.334  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit,
09-09 13:41:33.334  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
09-09 13:41:33.344  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated,
,09-09 13:41:33.344  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 13:41:33.344  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-09 13:41:33.344  1174  1174 D HotspotTile: updateTetherState():false, false
09-09 13:41:33.344  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:41:33.344  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-09 13:41:33.344  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
09-09 13:41:33.344  1014  1122 V NetworkStats: performPollLocked() took 7ms
09-09 13:41:33.344  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:33.344  1014  1128 D Tethering: InitialState.processMessage what=4
09-09 13:41:33.344  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:33.344  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:33.354  1014  1128 E Tethering: No numeric data
09-09 13:41:33.354  1014  1043 D Tethering: interfaceAdded p2p0
,09-09 13:41:33.354  1014  1043 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-09 13:41:33.354  1014  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-09 13:41:33.354  1014  1128 D Tethering: clearTetheredNotification()
,09-09 13:41:33.354  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 13:41:33.354  1174  1174 D HotspotTile: updateTetherState():false, false
09-09 13:41:33.364  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:33.364  1014  1122 V NetworkStats: performPollLocked(flags=0x1),
09-09 13:41:33.364  1014  1043 D Tethering: interfaceLinkStateChanged p2p0, false
,09-09 13:41:33.364  1014  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 13:41:33.364  1014  1043 D Tethering: interfaceStatusChanged p2p0, false
,09-09 13:41:33.364  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:41:33.364  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 13:41:33.364  1014  1122 V NetworkStats: performPollLocked() took 9ms,
09-09 13:41:33.364  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:33.374   277  1002 I WifiHW  : wifi_change_fw_path(): fwpath = sta
09-09 13:41:33.374   277  1002 D SoftapController: Softap fwReload - Ok
,09-09 13:41:33.374   277  1002 D CommandListener: Setting iface cfg
09-09 13:41:33.374   277  1002 D CommandListener: Trying to bring down wlan0
09-09 13:41:33.374  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:33.374  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:33.374   277  1002 D CommandListener: Clearing all IP addresses on wlan0
,09-09 13:41:33.374  1014  1125 E WifiHW  : supplicant_name : p2p_supplicant
,09-09 13:41:33.424  7496  7496 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,09-09 13:41:33.424  7496  7496 I wpa_supplicant: Successfully initialized wpa_supplicant
09-09 13:41:33.424  7496  7496 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-09 13:41:33.444  7496  7496 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
09-09 13:41:33.444   378   378 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7496
09-09 13:41:33.444   378   378 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-09 13:41:33.444  7496  7496 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-09 13:41:33.444  7496  7496 I wpa_supplicant: ssSupport state is = 1
09-09 13:41:33.444  7496  7496 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-09 13:41:33.444  7496  7496 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-09 13:41:33.444   378   378 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7496
09-09 13:41:33.444   378   378 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,09-09 13:41:33.484  1014  1125 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
,09-09 13:41:33.494  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-09 13:41:33.494  4412  4412 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:41:33.494  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:41:33.494  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-09 13:41:33.494  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:33.494  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:33.494  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:33.494  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:33.494  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:33.494  1174  1720 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-09 13:41:33.494  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:33.494  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,09-09 13:41:33.504  1174  1174 D HotspotTile: onReceive : 2, 0
,09-09 13:41:33.504  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:33.504  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-09 13:41:33.504  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:33.504  1014  1328 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 13:41:33.504  1014  1328 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:41:33.514  1014  1328 W ActivityManager: userId = 0, bbcId = -10000,
09-09 13:41:33.514  1014  1328 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:33.514  1014  1328 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-09 13:41:33.514  1609  1609 I Hs20UtilService: Starting #17
09-09 13:41:33.514  1609  1661 I Hs20UtilService: Message received 5011
,09-09 13:41:33.524  6804  6804 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-09 13:41:33.524  6804  6804 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 13:41:33.524  6804  6804 D SecurityLogAgent: StateMachine : Current State = 1
09-09 13:41:33.524  6804  6804 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 13:41:33.624   378   378 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,09-09 13:41:33.624  7496  7496 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed,
,09-09 13:41:33.674  7496  7496 I wpa_supplicant: Ctrl_iface: loading cred from phone,
09-09 13:41:33.674  7496  7496 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-09 13:41:33.684  7496  7496 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-09 13:41:33.684   378   378 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7496
,09-09 13:41:33.684   378   378 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-09 13:41:33.684  7496  7496 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-09 13:41:33.684  7496  7496 I wpa_supplicant: ssSupport state is = 1
09-09 13:41:33.684  7496  7496 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-09 13:41:33.684  7496  7496 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 13:41:33.684  7496  7496 E wpa_supplicant: SIM READ ERROR
09-09 13:41:33.684  7496  7496 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 13:41:33.684  7496  7496 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 13:41:33.684  7496  7496 E wpa_supplicant: SIM READ ERROR
,09-09 13:41:33.684  7496  7496 I wpa_supplicant: Blacklist: Clear (all) 
09-09 13:41:33.684  7496  7496 I wpa_supplicant: wpa_default_ap_write_once
09-09 13:41:33.684  7496  7496 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-09 13:41:33.684  7496  7496 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 13:41:33.684  7496  7496 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory,
09-09 13:41:33.684  7496  7496 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 13:41:33.684  7496  7496 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-09 13:41:33.684  7496  7496 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,09-09 13:41:33.694  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
09-09 13:41:33.694  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:41:33.694  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
,09-09 13:41:33.784  7496  7496 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-09 13:41:33.994  7496  7496 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,09-09 13:41:33.994  7496  7496 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,09-09 13:41:34.004  7496  7496 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-09 13:41:34.004   378   378 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7496
09-09 13:41:34.004   378   378 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-09 13:41:34.004  7496  7496 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
09-09 13:41:34.004  7496  7496 I wpa_supplicant: ssSupport state is = 1
09-09 13:41:34.014  7496  7496 I wpa_supplicant: Ctrl_iface: loading cred from phone
,09-09 13:41:34.014  7496  7496 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-09 13:41:34.024  7496  7496 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-09 13:41:34.024   378   378 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7496
09-09 13:41:34.024   378   378 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
09-09 13:41:34.024  7496  7496 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-09 13:41:34.024  7496  7496 I wpa_supplicant: ssSupport state is = 1
,09-09 13:41:34.024  7496  7496 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
,09-09 13:41:34.024  7496  7496 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-09 13:41:34.024  1014  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-09 13:41:34.024  7496  7496 E wpa_supplicant: SIM READ ERROR
09-09 13:41:34.034  1014  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-09 13:41:34.024  7496  7496 I wpa_supplicant: wpa_default_ap_write_once
09-09 13:41:34.024  7496  7496 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,09-09 13:41:34.024  7496  7496 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-09 13:41:34.024  1014  1043 D Tethering: interfaceLinkStateChanged p2p0, false
,09-09 13:41:34.024  1014  1043 D Tethering: interfaceStatusChanged p2p0, false
09-09 13:41:34.034  1014  1043 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 13:41:34.034  1014  1043 D Tethering: interfaceStatusChanged p2p0, false
,09-09 13:41:34.074  7496  7496 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-09 13:41:34.074  7496  7496 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-09 13:41:34.134  7496  7496 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
09-09 13:41:34.134  7496  7496 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-09 13:41:34.134  7496  7496 I wpa_supplicant: Skip scan - bUseNetwork false,
,09-09 13:41:34.144  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
,09-09 13:41:34.144  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21],
09-09 13:41:34.144  7496  7496 I wpa_supplicant: HOTSPOT20_ENABLE called
09-09 13:41:34.144  7496  7496 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-09 13:41:34.144  7496  7496 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 13:41:34.144  7496  7496 E wpa_supplicant: SIM READ ERROR
,09-09 13:41:34.144  7496  7496 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 13:41:34.154  7496  7496 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-09 13:41:34.164  7496  7496 I wpa_supplicant: Skip scan - bUseNetwork false
09-09 13:41:34.164  1014  1125 D WifiConfigStore: Loading config and enabling all networks 
,09-09 13:41:34.174  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-09 13:41:34.174  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:41:34.174  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:41:34.174  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:34.174  4412  4412 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:34.174  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:34.174  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:34.174  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-09 13:41:34.174  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:34.174  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:34.174  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,09-09 13:41:34.174  1174  1720 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-09 13:41:34.184  1174  1174 D HotspotTile: onReceive : 3, 0
,09-09 13:41:34.184  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:34.184  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:34.184  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:34.184  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:34.184  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:34.184  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:34.184  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:34.184  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:41:34.184  1014  1027 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 13:41:34.194  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:41:34.194  6937  6937 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:41:34.194  1014  1125 E WifiConfigStore: Not a HS20
,09-09 13:41:34.194  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:34.194  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 13:41:34.194  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:41:34.194  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:34.194  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:34.194  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:34.194  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:34.194  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:34.194  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:34.194  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:34.194  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:41:34.194  1014  1125 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-09 13:41:34.194  6937  6937 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:41:34.204  1609  1609 I Hs20UtilService: Starting #18
,09-09 13:41:34.204  1609  1661 I Hs20UtilService: Message received 5011
,09-09 13:41:34.204  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,09-09 13:41:34.204  7496  7496 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-09 13:41:34.204  7496  7496 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-09 13:41:34.204  7496  7496 I wpa_supplicant: reset timer : RESET_TIMER 0
09-09 13:41:34.204  7496  7496 I wpa_supplicant: P2P: Current p2p state = IDLE
09-09 13:41:34.204  7496  7496 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-09 13:41:34.204  7496  7496 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-09 13:41:34.204  7496  7496 I wpa_supplicant: First Scan Start
,09-09 13:41:34.204  7496  7496 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-09 13:41:34.204  1014  1125 D WifiNative-wlan0: Setting external_sim to 1
,09-09 13:41:34.204  6804  6804 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-09 13:41:34.204  1014  1125 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 13:41:34.204  1014  1125 I WifiNative-HAL: startHal
09-09 13:41:34.204  1014  1125 E wifi    : getStaticLongField sWifiHalHandle 0x9ebf688c
09-09 13:41:34.204  1014  1125 I WifiNative-HAL: Could not start hal
,09-09 13:41:34.204  6804  6804 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-09 13:41:34.204  6804  6804 D SecurityLogAgent: StateMachine : Current State = 1
,09-09 13:41:34.204  7028  7028 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:34.204  6804  6804 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 13:41:34.214  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:34.214  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,09-09 13:41:34.214  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:34.214  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:34.214  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:34.214  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:34.214  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:34.214  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:41:34.214  1014  1125 E WifiNative-wlan0: do suspend true
,09-09 13:41:34.214  1014  1124 D WifiP2pService: P2pDisabledState{ what=131203 }
09-09 13:41:34.214   277  1002 D CommandListener: Setting iface cfg
09-09 13:41:34.214   277  1002 D CommandListener: Trying to bring up p2p0
09-09 13:41:34.214  6937  6937 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:41:34.214  1014  1124 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-09 13:41:34.214  1014  1124 D WifiP2pService: P2pEnablingState
09-09 13:41:34.214  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-09 13:41:34.214  1014  1124 D WifiP2pService: P2pEnablingState{ what=147457 }
09-09 13:41:34.214  1014  1124 D WifiP2pService: P2p socket connection successful
09-09 13:41:34.224  1014  1124 D WifiP2pService: P2pEnabledState
,09-09 13:41:34.224  1014  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-09 13:41:34.224  1014  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-09 13:41:34.224  1014  1125 E WifiNative-wlan0: invaild command id : 215
,09-09 13:41:34.224  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 3
,09-09 13:41:34.224  1014  1148 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:34.224  1014  1148 I WifiNative-HAL: startHal
09-09 13:41:34.224  1014  1148 E wifi    : getStaticLongField sWifiHalHandle 0x9dbb69bc
09-09 13:41:34.224  1014  1148 I WifiNative-HAL: Could not start hal
09-09 13:41:34.224  1014  1148 E WifiScanningService: could not start HAL
09-09 13:41:34.224  1014  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-09 13:41:34.224  1014  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-09 13:41:34.224  1014  1125 E WifiNative-wlan0: invaild command id : 215
,09-09 13:41:34.224  1014  1014 D RttService: SCAN_AVAILABLE : 3
09-09 13:41:34.224  1014  1149 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 13:41:34.224  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-09 13:41:34.224  1014  1127 E ConnectivityService: updateNetworkInfo()
09-09 13:41:34.224  7496  7496 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-09 13:41:34.224  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-09 13:41:34.224  7496  7496 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-09 13:41:34.224  1014  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true,
,09-09 13:41:34.234  1014  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 13:41:34.234  1014  1046 D WifiDisplayController: disconnect
09-09 13:41:34.234  1014  1046 D WifiDisplayController: updateConnection
,09-09 13:41:34.234  7496  7496 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
09-09 13:41:34.234  1014  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false,
09-09 13:41:34.234  1014  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 13:41:34.234  1014  1125 E WifiStateMachine: Failed to set frequency band 0
,09-09 13:41:34.234  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:41:34.234  1014  1125 D SecContentProvider2: mCursor = null
09-09 13:41:34.234  1174  1174 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-09 13:41:34.234  1014  1027 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 13:41:34.234  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:41:34.234  1174  1174 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-09 13:41:34.234  1014  1125 D SecContentProvider2: mCursor = null
,09-09 13:41:34.244  1014  1124 D WifiNative-p2p0: p2pGetDeviceAddress
09-09 13:41:34.244  1014  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:41:34.244  1014  1124 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
09-09 13:41:34.244  1014  1046 D WifiDisplayAdapter: onP2pDisconnected
09-09 13:41:34.244  1014  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 13:41:34.244  1014  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-09 13:41:34.244  4412  4412 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-09 13:41:34.244  4412  4412 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 13:41:34.244  1014  1124 D WifiP2pService: DeviceAddress: 0a:75:42
09-09 13:41:34.244  1014  1046 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
09-09 13:41:34.244  1014  1046 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
09-09 13:41:34.244  1014  1046 D WifiDisplayController:  primary type: 10-0050F204-5
09-09 13:41:34.244  1014  1046 D WifiDisplayController:  secondary type: null
09-09 13:41:34.244  1014  1046 D WifiDisplayController:  wps: 0
09-09 13:41:34.244  1014  1046 D WifiDisplayController:  grpcapab: 0
09-09 13:41:34.244  1014  1046 D WifiDisplayController:  devcapab: 0
09-09 13:41:34.244  1014  1046 D WifiDisplayController:  status: 3
09-09 13:41:34.244  1014  1046 D WifiDisplayController:  wfdInfo: null
09-09 13:41:34.244  1014  1046 D WifiDisplayController:  groupownerAddress: null
09-09 13:41:34.244  1014  1046 D WifiDisplayController:  GOdeviceName: null
09-09 13:41:34.244  1014  1046 D WifiDisplayController:  interfaceAddress: 
,09-09 13:41:34.244  1014  1046 D WifiDisplayController:  SConnectInfo : null
09-09 13:41:34.244  4412  4412 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 13:41:34.244  4412  4412 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-09 13:41:34.244  4412  4412 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-09 13:41:34.244  4412  4412 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 13:41:34.254  4412  4504 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 13:41:34.254  7072  7072 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 13:41:34.254  7072  7072 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-09 13:41:34.254  7072  7072 D FileShare-Client: Outbound.stopDelayTimer - 
,09-09 13:41:34.264  1014  1124 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-09 13:41:34.264  1014  1124 D WifiP2pService: InactiveState
,09-09 13:41:34.264  1014  1124 D WifiP2pService: InactiveState{ what=143376 }
09-09 13:41:34.264  1014  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
09-09 13:41:34.264  7496  7496 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-09 13:41:34.264  7087  7087 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
09-09 13:41:34.264  1014  1124 D WifiP2pService: InactiveState{ what=143376 }
09-09 13:41:34.264  1014  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-09 13:41:34.344  1014  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-09 13:41:34.344  1014  1043 D Tethering: interfaceLinkStateChanged p2p0, false
,09-09 13:41:34.344  1014  1043 D Tethering: interfaceStatusChanged p2p0, false
,09-09 13:41:34.604  6937  6991 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:34.604  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:41:34.604  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:41:34.604  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:34.604  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 13:41:34.604  6937  6991 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60dad60 removed from the list
09-09 13:41:34.604  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:41:34.604  6937  6991 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36e64219 removed from the list
09-09 13:41:34.604  6937  6991 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:41:34.604  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:34.614  6937  7504 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-09 13:41:34.614  6937  7504 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-09 13:41:34.974  1014  1094 V AlarmManager: waitForAlarm result :4
,09-09 13:41:34.984   277   998 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-09 13:41:34.984   277   998 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,09-09 13:41:34.994  1014  1041 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:34.994  1014  1041 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 13:41:34.994  1014  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,09-09 13:41:35.124   277   998 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
09-09 13:41:35.124   277   998 D Netd    : getNetworkForDns: using netid 0 for uid 10170
,09-09 13:41:35.124  6937  7508 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-09 13:41:35.124  6937  7508 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-09 13:41:35.124  6937  7508 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:41:35.124  6937  7508 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:41:35.124  6937  7508 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-09 13:41:35.124  6937  7504 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-09 13:41:35.124  6937  7504 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-09 13:41:35.124  6937  7512 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1470, name: IncomingSocketThread/Receiver)
,09-09 13:41:35.124  6937  7512 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1470, thread name: IncomingSocketThread/Receiver)
09-09 13:41:35.124  6937  7512 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-09 13:41:35.134  6937  7512 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1470, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-09 13:41:35.134  6937  7511 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1469, name: IncomingSocketThread/Sender)
,09-09 13:41:35.134  6937  7504 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 13:41:35.134  6937  7504 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 13:41:35.134  6937  7504 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-09 13:41:35.134  6937  7513 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1471, name: OutgoingSocketThread/Sender)
,09-09 13:41:35.134  6937  7514 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1472, name: OutgoingSocketThread/Receiver)
,09-09 13:41:35.134  6937  7514 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1472, thread name: OutgoingSocketThread/Receiver)
09-09 13:41:35.134  6937  7514 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-09 13:41:35.134  6937  7514 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1472, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-09 13:41:35.424  7496  7496 I wpa_supplicant: nl80211: Received scan results (29 BSSes)
09-09 13:41:35.424  7496  7496 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-09 13:41:35.424  7496  7496 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,09-09 13:41:35.424  7496  7496 I wpa_supplicant: Trying to associate with  'G700'
09-09 13:41:35.424  7496  7496 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
09-09 13:41:35.424  7496  7496 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
09-09 13:41:35.434  1014  7501 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-09 13:41:35.454  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:41:35.454  1014  1125 D SecContentProvider2: mCursor = null
,09-09 13:41:35.484  2789  2847 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-09 13:41:35.544  7496  7496 E wpa_supplicant: Cmd 35605 not handled
,09-09 13:41:35.544  7496  7496 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-09 13:41:35.544  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:41:35.544  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:41:35.544  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
09-09 13:41:35.544  7496  7496 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-09 13:41:35.544  7496  7496 I wpa_supplicant: Associated with F4.99.3E
,09-09 13:41:35.544  7496  7496 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,09-09 13:41:35.544  7496  7496 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-09 13:41:35.544  7496  7496 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-09 13:41:35.544  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:41:35.544  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:41:35.544  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
09-09 13:41:35.544  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:41:35.544  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:41:35.544  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
,09-09 13:41:35.544  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, true
09-09 13:41:35.544  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-09 13:41:35.544  1014  1043 D Tethering: interfaceStatusChanged wlan0, true
,09-09 13:41:35.554  1014  1128 E Tethering: No numeric data
,09-09 13:41:35.554  1014  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-09 13:41:35.554  1014  1128 D Tethering: clearTetheredNotification()
,09-09 13:41:35.554  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
,09-09 13:41:35.554  7496  7496 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-09 13:41:35.554  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:35.554  7496  7496 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
09-09 13:41:35.554  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:41:35.554  1014  1125 D SecContentProvider2: mCursor = null
,09-09 13:41:35.554  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:41:35.554  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-09 13:41:35.554  7496  7496 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-09 13:41:35.554  7496  7496 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,09-09 13:41:35.554  7496  7496 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 13:41:35.554  7496  7496 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,09-09 13:41:35.564  7496  7496 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-09 13:41:35.564  7496  7496 I wpa_supplicant: Blacklist: Clear (temp) 
,09-09 13:41:35.564  7496  7496 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-09 13:41:35.564  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 13:41:35.564  1174  1174 D HotspotTile: updateTetherState():false, false
,09-09 13:41:35.564  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, true
,09-09 13:41:35.564  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-09 13:41:35.564  1014  1043 D Tethering: interfaceStatusChanged wlan0, true
09-09 13:41:35.564  1014  1122 V NetworkStats: performPollLocked() took 11ms
09-09 13:41:35.564  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:35.564  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:35.564  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:35.574  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:41:35.574  1014  1125 D SecContentProvider2: mCursor = null
,09-09 13:41:35.574  1014  1125 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-09 13:41:35.584  1014  1125 E WifiConfigStore: setLastSelectedConfiguration -1
,09-09 13:41:35.594  1014  1125 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,09-09 13:41:35.594  1014  1127 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
,09-09 13:41:35.594  1014  1127 E ConnectivityService: updateNetworkInfo()
09-09 13:41:35.594  1014  1502 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 13:41:35.594  1014  1502 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:41:35.594  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:35.594  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-09 13:41:35.594  1014  1502 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:35.594  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:41:35.594  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:41:35.594  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:35.594  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:35.594  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:35.594  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:35.594  1014  1502 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 13:41:35.594  1014  1502 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:41:35.594  1014  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 13:41:35.594  1609  1609 I Hs20UtilService: Starting #19
09-09 13:41:35.594  1609  1661 I Hs20UtilService: Message received 5007
,09-09 13:41:35.604  4412  4412 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-09 13:41:35.604  4412  4412 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-09 13:41:35.604  4412  4412 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-09 13:41:35.604  4412  4412 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-09 13:41:35.604  4412  4412 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 13:41:35.604  4412  4412 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-09 13:41:35.604  4412  4504 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 13:41:35.614  1014  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 13:41:35.614  6937  6991 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-09 13:41:35.614  6937  6991 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-09 13:41:35.624  6937  6991 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3bb7f488 Bundle[{}]
,09-09 13:41:35.624   277  1002 D CommandListener: Setting iface cfg
,09-09 13:41:35.624  6937  6991 I io.jxcore.node.LifeCycleMonitor: start: OK
09-09 13:41:35.624  6937  6991 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-09 13:41:35.624  6937  6991 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-09 13:41:35.624  6937  6991 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-09 13:41:35.624  6937  6991 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-09 13:41:35.624  6937  6991 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-09 13:41:35.624  1014  1125 E WifiStateMachine: Start Dhcp Watchdog 2
,09-09 13:41:35.634  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-09 13:41:35.634  1014  1125 D SecContentProvider2: mCursor = null
,09-09 13:41:35.634  6937  7518 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-09 13:41:35.634  6937  7518 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-09 13:41:35.644  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-09 13:41:35.644  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 13:41:35.644  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-09 13:41:35.644  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:35.644  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:35.644  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:35.644  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:35.654   287   287 E SMD     : DCD OFF,
,09-09 13:41:35.654  1014  1125 E WifiNative-wlan0: do suspend false
,09-09 13:41:35.654  1014  1124 D WifiP2pService: InactiveState{ what=143375 }
,09-09 13:41:35.654  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
09-09 13:41:35.654  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:41:35.654  1014  1125 D SecContentProvider2: mCursor = null
,09-09 13:41:35.874  7521  7521 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-09 13:41:35.874  7521  7521 I dhcpcd  : version 5.5.6 starting
,09-09 13:41:35.884  7521  7521 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-09 13:41:35.934  7521  7521 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
09-09 13:41:35.934  7521  7521 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-09 13:41:35.934  7521  7521 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E),
09-09 13:41:35.934  7521  7521 I dhcpcd  : bssid match
,09-09 13:41:35.934  7521  7521 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,09-09 13:41:36.004  7521  7521 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
,09-09 13:41:36.064  7521  7521 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds,
,09-09 13:41:36.134  6937  7537 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-09 13:41:36.134  6937  7537 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-09 13:41:36.134  6937  7537 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:41:36.134  6937  7537 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:41:36.134  6937  7539 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1483, name: IncomingSocketThread/Sender)
09-09 13:41:36.134  6937  7518 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-09 13:41:36.134  6937  7518 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-09 13:41:36.134  6937  7518 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:41:36.134  6937  7518 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:41:36.134  6937  7540 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1485, name: OutgoingSocketThread/Sender)
09-09 13:41:36.144  6937  7518 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-09 13:41:36.144  6937  7541 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1486, name: OutgoingSocketThread/Receiver)
,09-09 13:41:36.144  6937  7537 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-09 13:41:36.144  6937  7541 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1486, thread name: OutgoingSocketThread/Receiver)
09-09 13:41:36.144  6937  7541 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-09 13:41:36.144  6937  7541 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1486, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207,
09-09 13:41:36.144  6937  7542 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1484, name: IncomingSocketThread/Receiver)
09-09 13:41:36.144  6937  7542 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1484, thread name: IncomingSocketThread/Receiver)
09-09 13:41:36.144  6937  7542 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-09 13:41:36.144  6937  7542 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1484, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-09 13:41:36.264  1014  1125 E WifiNative-wlan0: do suspend true
,09-09 13:41:36.294  1014  1124 D WifiP2pService: InactiveState{ what=143375 }
,09-09 13:41:36.294  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-09 13:41:36.294  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-09 13:41:36.294  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 13:41:36.294  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-09 13:41:36.294  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:36.294  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:36.294  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:36.304  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:36.304  1014  1125 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-09 13:41:36.304  1014  1125 E WifiStateMachine: VerifyingLinkState enter
,09-09 13:41:36.304  1014  1127 E ConnectivityService: updateNetworkInfo()
,09-09 13:41:36.304  1014  1127 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,09-09 13:41:36.304  1014  1127 D ConnectivityService: Adding iface wlan0 to network 503
,09-09 13:41:36.314  1014  1142 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter,
09-09 13:41:36.314  1014  1142 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-09 13:41:36.314  1014  1142 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-09 13:41:36.314  1014  1142 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-09 13:41:36.314  1014  1142 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-09 13:41:36.334  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-09 13:41:36.344  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:41:36.344  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:41:36.344  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:36.344  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:36.344  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:36.344  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:36.344  1014  1125 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
09-09 13:41:36.344  1014  1500 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 13:41:36.344  1014  1500 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:41:36.344  1014  1127 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 503
,09-09 13:41:36.344  1014  1500 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:36.344  1014  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:36.344  1014  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:41:36.344  1609  1609 I Hs20UtilService: Starting #20
,09-09 13:41:36.354  1014  1127 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
09-09 13:41:36.354  1014  1127 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
09-09 13:41:36.354  1609  1661 I Hs20UtilService: Message received 5007
09-09 13:41:36.354  1014  1127 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-09 13:41:36.354  4412  4412 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-09 13:41:36.354  1014  1127 D ConnectivityService: Setting Dns servers for network 503 to [/192.168.1.1]
,09-09 13:41:36.354  1014  1127 D ConnectivityService: LTETest block dns file not exists
,09-09 13:41:36.364  4412  4412 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-09 13:41:36.364  1014  1127 V NetworkStats: updateIfacesLocked()
09-09 13:41:36.364  1014  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:36.364  1014  1127 V NetworkStats: performPollLocked(flags=0x1)
,09-09 13:41:36.364  1014  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:41:36.364  1014  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 13:41:36.374  1014  1127 V NetworkStats: performPollLocked() took 10ms
09-09 13:41:36.374  1014  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:36.384  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:36.384  1014  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
09-09 13:41:36.384  1014  1127 E ConnectivityService: updateNetworkInfo()
,09-09 13:41:36.384  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:36.384  1014  1127 E ConnectivityService: updateNetworkInfo()
09-09 13:41:36.384  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-09 13:41:36.384  1014  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:36.384  1014  1127 V NetworkStats: updateIfacesLocked()
09-09 13:41:36.384  1014  1127 V NetworkStats: performPollLocked(flags=0x1)
,09-09 13:41:36.394  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-09 13:41:36.394  1014  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:41:36.394  1014  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 13:41:36.394  1014  1127 V NetworkStats: performPollLocked() took 5ms
09-09 13:41:36.394  1014  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:36.404  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-09 13:41:36.404  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 13:41:36.404  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:41:36.404  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:36.404  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:36.404  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:36.404  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:36.404  1014  1127 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
09-09 13:41:36.404  1014  1127 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
,09-09 13:41:36.404  1014  1501 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 13:41:36.404  1014  1501 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:36.404  1014  1501 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-09 13:41:36.414  1014  1501 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:36.414  1014  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-09 13:41:36.414  1014  7516 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler },
09-09 13:41:36.414  1014  7516 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
09-09 13:41:36.414  1014  7516 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:36.414  1014  7516 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,09-09 13:41:36.414  1014  1125 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-09 13:41:36.414  1014  1125 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-09 13:41:36.414  1609  1609 I Hs20UtilService: Starting #21
,09-09 13:41:36.414  1014  7516 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-09 13:41:36.414  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-09 13:41:36.414  1014  1014 I WifiTrafficPoller: mBoosterFLAG : 0
09-09 13:41:36.414  1014  1014 I WifiTrafficPoller: current booster mode : FullMode
,09-09 13:41:36.414   277   998 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-09 13:41:36.414   277   998 D Netd    : getNetworkForDns: using netid 503 for uid 1000
,09-09 13:41:36.414  1014  1127 D ConnectivityService:    accepting network in place of null
,09-09 13:41:36.414  1014  1125 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-09 13:41:36.414  1014  1124 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-09 13:41:36.414  1014  1127 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-09 13:41:36.414  1014  1127 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
09-09 13:41:36.424  1477  1477 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-09 13:41:36.424  1014  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 13:41:36.424  1477  1477 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-09 13:41:36.424  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:41:36.424  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-09 13:41:36.424  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:36.424  1609  1661 I Hs20UtilService: Message received 5007
,09-09 13:41:36.424  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:36.424  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:36.424  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:36.424  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:36.434  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:36.434  4412  4412 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-09 13:41:36.434  4412  4412 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 13:41:36.434  4412  4412 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
09-09 13:41:36.434  1014  1127 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,09-09 13:41:36.444  1014  1014 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE,
09-09 13:41:36.444  1014  1128 D Tethering: MasterInitialState.processMessage what=3
,09-09 13:41:36.444  1014  1122 V NetworkStats: updateIfacesLocked()
09-09 13:41:36.444  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:36.444  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
,09-09 13:41:36.444  4412  4412 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-09 13:41:36.444  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:41:36.444  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-09 13:41:36.444  1014  1127 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,09-09 13:41:36.444  4412  4412 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
09-09 13:41:36.444  4412  4412 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-09 13:41:36.444  1014  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-09 13:41:36.444  1174  1688 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-09 13:41:36.444  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:36.444  1014  1122 V NetworkStats: performPollLocked() took 7ms
09-09 13:41:36.444  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:36.454  1174  1174 D StatusBar.NetworkController: EthernetConnected: false
09-09 13:41:36.454  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-09 13:41:36.454  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-09 13:41:36.454  1174  1174 D StatusBar.NetworkController: updateDataNetType()
,09-09 13:41:36.454  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:36.454  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:36.454  1014  1123 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,09-09 13:41:36.454  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:36.454  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-09 13:41:36.454  1174  1174 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-09 13:41:36.454  1174  1174 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-09 13:41:36.454  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 21 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
09-09 13:41:36.454  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
09-09 13:41:36.454  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
09-09 13:41:36.454  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:41:36.454  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-09 13:41:36.454  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:36.454  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:36.454  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:36.454  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:36.464  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:36.464  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:36.464  1014  1555 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 13:41:36.464  1014  1555 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:41:36.464  1014  1555 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:36.464  1014  1555 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 13:41:36.464  1014  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:41:36.474  1609  1609 I Hs20UtilService: Starting #22
,09-09 13:41:36.474  1609  1661 I Hs20UtilService: Message received 5007
09-09 13:41:36.474  4412  4412 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-09 13:41:36.474  4412  4412 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-09 13:41:36.484  1014  1557 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,09-09 13:41:36.484  1014  1501 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
,09-09 13:41:36.484  1014  1501 D SecContentProvider2: mCursor = null
,09-09 13:41:36.484  1014  1555 D SecContentProvider2: uri = 15 selection = getToastGravity
,09-09 13:41:36.484  1014  1555 D SecContentProvider2: mCursor = null
,09-09 13:41:36.484  1014  1558 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
,09-09 13:41:36.484  1014  1558 D SecContentProvider2: mCursor = null
,09-09 13:41:36.494  1014  1027 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
,09-09 13:41:36.494  1014  1027 D SecContentProvider2: mCursor = null
,09-09 13:41:36.494  1014  1216 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,09-09 13:41:36.494  1014  1216 D SecContentProvider2: mCursor = null
,09-09 13:41:36.494  1014  1026 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
,09-09 13:41:36.494  1014  1026 D SecContentProvider2: mCursor = null
,09-09 13:41:36.514  1014  7516 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-09 13:41:36.524   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,09-09 13:41:36.534  1014  1555 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1014
,09-09 13:41:36.534  1174  1174 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-09 13:41:36.564  1014  7516 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 11:41:36 GMT], X-Android-Received-Millis=[1473421296575], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473421296549]}
09-09 13:41:36.564  1014  7516 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-09 13:41:36.564  1014  7516 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,09-09 13:41:36.564  1014  1127 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 503]
09-09 13:41:36.564  1014  1127 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
09-09 13:41:36.564  1014  1127 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
09-09 13:41:36.564  1014  1127 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
09-09 13:41:36.564  1014  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-09 13:41:36.574  1174  1688 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-09 13:41:36.574  1174  1174 D StatusBar.NetworkController: EthernetConnected: false
,09-09 13:41:36.574  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-09 13:41:36.574  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-09 13:41:36.574  1174  1174 D StatusBar.NetworkController: updateDataNetType()
,09-09 13:41:36.584  1174  1174 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-09 13:41:36.584  1174  1174 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-09 13:41:36.584  1174  1174 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,09-09 13:41:36.584  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 21 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
,09-09 13:41:36.584  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
,09-09 13:41:36.584  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,09-09 13:41:36.584  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 13:41:36.584  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,09-09 13:41:36.584  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:36.594  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:36.594  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:36.594  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:36.644  6937  6991 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1495)
,09-09 13:41:36.644  6937  6991 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-09 13:41:36.644  6937  6991 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1496)
,09-09 13:41:36.644  6937  6991 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 13:41:36.644  6937  6991 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21e23cbf added. We now have 3 listener(s)
,09-09 13:41:36.654  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-09 13:41:36.654  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:36.654  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:41:36.654  6937  6991 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 13:41:36.654  6937  6991 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16903f8c added. We now have 3 listener(s)
09-09 13:41:36.654  6937  6991 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:41:36.654  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:41:36.664  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:36.664  6937  6991 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:36.664  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:36.664  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:36.664  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:36.664  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:36.664  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:36.664  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:36.664  6937  6991 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:36.664  6937  6991 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:41:36.664  6937  6991 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:41:36.674  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:36.674  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:36.674  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:41:36.674  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:36.674  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:41:36.674  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:41:36.674  6937  6991 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21e23cbf removed from the list
09-09 13:41:36.674  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:41:36.684  6937  6991 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16903f8c removed from the list
,09-09 13:41:36.684  6937  6991 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:41:36.684  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:36.684  6937  6991 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
,09-09 13:41:36.684  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
,09-09 13:41:36.684  6937  6991 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:41:36.684  6937  6991 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-09 13:41:36.684  6937  6991 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:41:36.684  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:36.694  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-09 13:41:36.694  6937  6991 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 13:41:36.694  6937  6991 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 13:41:36.694  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:41:36.694  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-09 13:41:36.694  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:36.694  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 13:41:36.694  6937  6937 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-09 13:41:36.694  6937  7561 D BluetoothSocket: bindListen(): myUserId = 0
,09-09 13:41:36.694  6937  7561 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:41:36.704  6937  7561 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[111]},
09-09 13:41:36.704  6937  7561 D BluetoothSocket: bindListen(), new LocalSocket ,
09-09 13:41:36.704  6937  7561 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 13:41:36.704  6937  7561 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1107e5db
09-09 13:41:36.704  6937  7561 D BluetoothSocket: channel: 6
,09-09 13:41:36.704  6937  7561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-09 13:41:36.704  6937  6991 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 13:41:36.714  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 13:41:36.714  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:41:36.714  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-09 13:41:36.714  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-09 13:41:36.714  6937  6991 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 08 EC A9 50 75 41
09-09 13:41:36.714  6937  6991 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 8, -20, -87, 80, 117, 65]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-09 13:41:36.714  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 8, -20, -87, 80, 117, 65]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-09 13:41:36.714  6937  6991 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-09 13:41:36.724  2789  2806 D BtGatt.GattService: registerClient() - UUID=537108af-f378-4403-b946-a870ce960779
,09-09 13:41:36.744  6937  6948 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1b1459cd, channel: 6, state: CLOSED
,09-09 13:41:36.744  6937  6948 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@deff585, channel: 6, state: CLOSED
,09-09 13:41:36.754  6937  6948 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2cef032, channel: 6, state: CLOSED
,09-09 13:41:36.754  6937  6948 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@32c3cdfb, channel: 6, state: CLOSED
,09-09 13:41:36.754  6937  6948 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@21d39bc7, channel: -1, state: CLOSED
,09-09 13:41:36.764  2789  2849 D BtGatt.GattService: onClientRegistered() - UUID=537108af-f378-4403-b946-a870ce960779, clientIf=6
,09-09 13:41:36.774  6937  6945 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-09 13:41:36.774  2789  2962 D BtGatt.AdvertiseManager: message : 0
,09-09 13:41:36.774  2789  2962 D BtGatt.AdvertiseManager: number of adv instance running0
,09-09 13:41:36.774  2789  2962 D BtGatt.AdvertiseManager: size of list is =0
,09-09 13:41:36.774  2789  2962 D BtGatt.AdvertiseManager: starting advertising
,09-09 13:41:36.774  2789  2962 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-09 13:41:36.784  2789  2849 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-09 13:41:36.784  2789  2962 D BtGatt.AdvertiseManager: starting multi advertising
,09-09 13:41:36.784  2789  2849 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-09 13:41:36.784  2789  2962 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-09 13:41:36.794  2789  2962 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-09 13:41:36.794  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-09 13:41:36.794  6937  6991 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 13:41:36.794  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:41:36.794  6937  6937 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 13:41:36.794  6937  6937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-09 13:41:36.794  6937  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-09 13:41:36.794  6937  6937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-09 13:41:36.794  6937  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-09 13:41:36.794  6937  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-09 13:41:36.804  6937  6937 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:41:36.804  6937  6937 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:41:36.944  1014  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:36.954  1014  1040 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:36.964  1014  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-09 13:41:36.964  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:36.964  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:36.964  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:36.964  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:36.984  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:36.984  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:36.984  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:36.984  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:36.984  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:36.984  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:36.984  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:36.984  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:36.984  6937  6937 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:41:36.984  7564  7564 E Zygote  : MountEmulatedStorage()
09-09 13:41:36.984  7564  7564 E Zygote  : v2
09-09 13:41:36.984  7564  7564 I libpersona: KNOX_SDCARD checking this for 1000,
09-09 13:41:36.984  7564  7564 I libpersona: KNOX_SDCARD not a persona
,09-09 13:41:36.994  7564  7564 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-09 13:41:36.994  1014  1041 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7564 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-09 13:41:36.994  7564  7564 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 13:41:36.994  6937  6937 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:36.994  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:36.994  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:36.994  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:36.994  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:36.994  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:36.994  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:36.994  6937  6937 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:36.994  7564  7564 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:41:37.004  6937  6937 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:41:37.024  7564  7564 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:41:37.024  7564  7564 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:37.054  7564  7564 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,09-09 13:41:37.054  7564  7564 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,09-09 13:41:37.054  7564  7564 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-09 13:41:37.064  7564  7564 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-09 13:41:37.064  7564  7564 I PCWCLIENTTRACE_PushUtil: sales region : global
,09-09 13:41:37.064  7564  7564 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,09-09 13:41:37.074  7564  7564 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:37.074  1014  1026 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
09-09 13:41:37.074  1014  1026 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
09-09 13:41:37.074  1014  1026 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
09-09 13:41:37.074  1014  1026 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,09-09 13:41:37.074  1014  1026 I ActivityManager: Killing 7120:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,09-09 13:41:37.184  7137  7137 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:37.184  7137  7137 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-09 13:41:37.184  7137  7137 I DIAGMON_AGENT: ./extraInfo: "NG700"
09-09 13:41:37.184  7137  7137 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,09-09 13:41:37.304  6937  6937 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-09 13:41:37.304  6937  6937 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-09 13:41:37.304  6937  6937 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 13:41:37.314  7152  7152 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,09-09 13:41:37.314  7152  7152 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,09-09 13:41:37.314  7152  7152 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,09-09 13:41:37.324  7152  7152 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,09-09 13:41:37.334  1014  1216 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 13:41:37.334  1014  1216 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-09 13:41:37.334  1014  1216 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:37.334  1014  1216 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:37.334  1014  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:37.354   277   998 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-09 13:41:37.354   277   998 D Netd    : getNetworkForDns: using netid 503 for uid 10011
,09-09 13:41:37.354  1917  1917 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-09 13:41:37.364  1014  1502 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 13:41:37.364  1014  1502 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
09-09 13:41:37.364  1917  4794 I iu.UploadsManager: num queued entries: 0
,09-09 13:41:37.364  1917  4794 I iu.UploadsManager: num updated entries: 0
,09-09 13:41:37.364  1917  4794 I iu.SyncManager: NEXT; no task
,09-09 13:41:37.364  1014  1502 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:37.364  1014  1502 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:37.364  1014  1502 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:37.374  1917  1917 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 13:41:37.374  1917  1917 I Kids    : [GCoreUtils] Current gmscore version, 8115234 is smaller than the required version 8400000
,09-09 13:41:37.384  2917  2917 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Sep 09 13:41:37 GMT+02:00 2016
,09-09 13:41:37.384  1014  1502 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-09 13:41:37.384  1014  1502 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-09 13:41:37.384  1014  1502 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:37.384  1014  1502 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:37.384  1014  1502 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-09 13:41:37.394  2917  2917 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-09 13:41:37.404  2917  2917 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-09 13:41:37.404  2917  2917 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
09-09 13:41:37.404  1014  1557 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
09-09 13:41:37.404  1014  1557 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,09-09 13:41:37.404  1014  1557 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:37.414  1014  1557 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:37.414  1014  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,09-09 13:41:37.414  1014  2857 D SSRM:n  : SIOP:: AP = 340
,09-09 13:41:37.414  2917  2917 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-09 13:41:37.424  2917  7586 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-09 13:41:37.424  2917  7586 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-09 13:41:37.434  2917  7586 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,09-09 13:41:37.434  2917  7586 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().START
,09-09 13:41:37.444  2917  7586 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().START 
,09-09 13:41:37.444  1014  1127 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,09-09 13:41:37.444  2917  7586 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().END 
,09-09 13:41:37.444  2917  7586 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,09-09 13:41:37.454  2917  2917 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-09 13:41:37.464  3494  7592 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,09-09 13:41:37.464  3494  7592 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
09-09 13:41:37.464  3494  7592 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-09 13:41:37.474  7185  7185 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,09-09 13:41:37.474  7202  7202 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,09-09 13:41:37.474  7202  7202 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
09-09 13:41:37.474  7202  7202 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-09 13:41:37.484  7202  7202 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,09-09 13:41:37.484  7202  7202 I SA      : [OR] == isSIMCardReady false ==
,09-09 13:41:37.484  7202  7202 I SA      : [SCU] == networkStateCheck == true
,09-09 13:41:37.484  7202  7202 I SA      : [DM] getCountryCodeFromCSC : PL
,09-09 13:41:37.484  7202  7202 I SA      : isChinaCountryCode : false
09-09 13:41:37.494  7202  7202 I SA      : [SCU] is ChinestModel Data Restricted   : false
09-09 13:41:37.494  7202  7202 I SA      : [OR] == networkStateCheck true ==
,09-09 13:41:37.494  7202  7202 I SA      : [OR] GetMyCountryZoneTask
,09-09 13:41:37.494  7202  7202 I SA      : [OR] onReceive END
,09-09 13:41:37.494  3494  7592 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,09-09 13:41:37.494  3494  7592 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,09-09 13:41:37.494  3494  7592 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,09-09 13:41:37.504  3494  7592 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
09-09 13:41:37.504  3494  7592 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
09-09 13:41:37.504  1224  1224 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:37.504  7202  7593 I SA      : [SRS] prepareGetMyCountryZone
09-09 13:41:37.504  1014  1216 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
09-09 13:41:37.504  1014  1216 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,09-09 13:41:37.504  3494  7592 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
09-09 13:41:37.504  1014  1216 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:37.504  1014  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:37.504  1014  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,09-09 13:41:37.504  3494  7592 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,09-09 13:41:37.504  3494  7592 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,09-09 13:41:37.514  1788  1788 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-09 13:41:37.514  7202  7593 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,09-09 13:41:37.514  7202  7593 I SA      : [SSP] query invoked
,09-09 13:41:37.514  3494  7592 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,09-09 13:41:37.514  1014  1502 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
09-09 13:41:37.514  1014  1502 D SecContentProvider2: mCursor = null
,09-09 13:41:37.524  7202  7593 I SA      : [TPMU] GetMccFromDB : null
,09-09 13:41:37.524  2680  2692 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,09-09 13:41:37.524  1788  1788 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,09-09 13:41:37.524  1788  1788 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
09-09 13:41:37.524  1788  1788 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
09-09 13:41:37.524  1788  1788 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-09 13:41:37.524  7202  7593 I SA      : [SCU] getMccFromPreferece mcc = 260
09-09 13:41:37.524  7202  7593 I SA      : [LBE] isSupportCheckDomainRegion : false
09-09 13:41:37.524  7202  7593 I SA      : [TPM] isNoProxy(default) : true
,09-09 13:41:37.534  3494  7592 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,09-09 13:41:37.534  1788  1788 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-09 13:41:37.534  1788  1788 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,09-09 13:41:37.534  7202  7593 E File    : fail readDirectory() errno=2
,09-09 13:41:37.554  1014  1213 D ActivityManager: startService callerProcessName:com.android.chrome, calleePkgName: com.android.chrome
,09-09 13:41:37.554  1014  1213 D ActivityManager: retrieveServiceLocked(): component = com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService; callingUser = 0; userId(target) = 0
,09-09 13:41:37.554  1014  1213 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:37.554  1014  1213 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 13:41:37.554  1014  1213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.chrome, destAppInfo.processName = com.android.chrome
,09-09 13:41:37.564  1014  1027 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,09-09 13:41:37.564  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-09 13:41:37.564  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:37.564  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:37.564  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-09 13:41:37.594  7327  7327 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:37.594  7327  7327 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
09-09 13:41:37.594  7327  7327 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-09 13:41:37.604  7028  7598 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
09-09 13:41:37.604  7028  7598 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-09 13:41:37.604  7028  7598 I System.out: (HTTPLog)-Static: isShipBuild true
09-09 13:41:37.604  7028  7598 I System.out: (HTTPLog)-Thread-1300-876130693: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
09-09 13:41:37.604  7028  7598 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:41:37.604   277   998 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-09 13:41:37.604   277   998 D Netd    : getNetworkForDns: using netid 503 for uid 10102
09-09 13:41:37.604  1014  1558 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 13:41:37.614  7386  7386 D WaitQueueForNetworkActivate: notifyNetworkActivated
,09-09 13:41:37.644  7028  7598 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-09 13:41:37.694  1014  1500 I art     : Explicit concurrent mark sweep GC freed 79520(4MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 23MB/34MB, paused 7.414ms total 162.904ms
,09-09 13:41:37.714  7028  7598 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-09 13:41:37.804  1014  1556 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,09-09 13:41:37.804  1014  1556 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,09-09 13:41:37.804  1014  1556 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:37.804  1014  1556 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-09 13:41:37.804  1014  1556 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,09-09 13:41:37.814  7386  7386 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,09-09 13:41:37.814  7386  7386 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,09-09 13:41:37.814  7386  7386 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
09-09 13:41:37.814  7386  7386 D InitializeManagerStateMachine: exit::IDLE
09-09 13:41:37.814  7386  7386 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,09-09 13:41:37.814  1014  1557 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:37.824  1014  1557 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:37.824  1014  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,09-09 13:41:37.824  7386  7386 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
09-09 13:41:37.824  7386  7386 D InitializeManagerStateMachine: exit::NETWORK_CHECK
09-09 13:41:37.824  7386  7386 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
09-09 13:41:37.824  7386  7386 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
09-09 13:41:37.824  7386  7386 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
09-09 13:41:37.824  7386  7386 D InitializeManagerStateMachine: entry::SUCCESS
09-09 13:41:37.824  7386  7386 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,09-09 13:41:37.824  7386  7386 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
09-09 13:41:37.824  7386  7386 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,09-09 13:41:37.824  7386  7386 D InitializeManagerStateMachine: exit::SUCCESS
09-09 13:41:37.824  7386  7386 D InitializeManagerStateMachine: entry::IDLE
,09-09 13:41:37.974  7202  7593 I SA      : [RC New] Execute method=[GET] start
,09-09 13:41:37.984  1014  1127 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
09-09 13:41:37.984  1014  1127 V NetworkStats: updateIfacesLocked()
09-09 13:41:37.984  1014  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:37.984  1014  1127 V NetworkStats: performPollLocked(flags=0x1)
09-09 13:41:37.984  1014  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-09 13:41:37.984  1014  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-09 13:41:37.984  1014  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:37.984  1014  1127 V NetworkStats: performPollLocked() took 4ms
09-09 13:41:37.984  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:37.984  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:37.994  1014  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503],
09-09 13:41:37.994  1174  1688 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-09 13:41:37.994  1014  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503],
,09-09 13:41:37.994  1174  1688 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295,
,09-09 13:41:38.004  7202  7593 I SA      : [RC New] Security=[true]
,09-09 13:41:38.004  7202  7593 I System.out: Thread-1341(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,09-09 13:41:38.004  7202  7593 I System.out: Thread-1341(ApacheHTTPLog):isSBSettingEnabled false
09-09 13:41:38.004  7202  7593 I System.out: Thread-1341(ApacheHTTPLog):isShipBuild true
09-09 13:41:38.004  7202  7593 I System.out: Thread-1341(ApacheHTTPLog):SMARTBONDING_ENABLED is false
09-09 13:41:38.004  7202  7593 I System.out: Thread-1341(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,09-09 13:41:38.004   277   998 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-09 13:41:38.004   277   998 D Netd    : getNetworkForDns: using netid 503 for uid 10036
,09-09 13:41:38.614  7202  7593 I SA      : [RC New] [v2liruge] api execute + 612
,09-09 13:41:38.614  7202  7593 I SA      : [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,09-09 13:41:38.624  7202  7593 I System.out: AsyncTask #1 calls detatch()
,09-09 13:41:38.624  7202  7593 I SA      : [ODM] saveOpenData( GEO_IP, PL )
,09-09 13:41:38.634  7202  7593 I SA      : [OCP] update openData : PL
,09-09 13:41:38.634  7202  7593 I SA      : [TPMU] getNetworkMcc : 260
,09-09 13:41:38.644  7202  7593 I SA      : [SCU] saveMccToPreferece Start
,09-09 13:41:38.644  7202  7593 I SA      : [SCU] RegionMCC : 260
,09-09 13:41:38.644  7202  7593 I SA      : [SSP] query invoked
,09-09 13:41:38.644  7202  7593 I SA      : [TPMU] GetMccFromDB : null
,09-09 13:41:38.644  7202  7593 I SA      : [SCU] getMccFromPreferece mcc = 260
,09-09 13:41:38.644  7202  7593 I SA      : [SCU] saveMccToPreferece End
,09-09 13:41:38.644  7202  7593 I SA      : [RC New] executeRequest [v2liruge] end. 677
09-09 13:41:38.644  7202  7593 I SA      : [RC New] Execute end
,09-09 13:41:38.644  7202  7202 I SA      : [OR] GetMyCountryZoneTask mcc = 260
09-09 13:41:38.644  7202  7202 I SA      : [OR] GetMyCountryZoneTask Success
,09-09 13:41:38.654   287   287 E SMD     : DCD OFF
,09-09 13:41:39.414  1014  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,09-09 13:41:39.694  1014  1557 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
09-09 13:41:39.694  1014  1557 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4283, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-09 13:41:39.694  1014  1557 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
09-09 13:41:39.694  1014  1557 D BatteryService: stay LED for charging,
09-09 13:41:39.694  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
,09-09 13:41:39.704  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
09-09 13:41:39.704  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
09-09 13:41:39.704  1014  1014 I MotionRecognitionService: Plugged
09-09 13:41:39.704  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,09-09 13:41:39.704  1421  1421 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-09 13:41:39.704  1421  1421 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-09 13:41:39.724  2789  2789 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-09 13:41:39.724  2789  7454 D HeadsetStateMachine: Disconnected process message: 10
,09-09 13:41:39.734  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-09 13:41:39.734  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-09 13:41:39.734  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-09 13:41:39.734  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,09-09 13:41:39.734  1174  1174 D SViewCoverView: level :100 plugged : 2
,09-09 13:41:40.014   257   449 I SurfaceFlinger: id=14 Removed Uoast (8/9)
,09-09 13:41:40.014   257  1037 I SurfaceFlinger: id=14 Removed Uoast (-2/9)
,09-09 13:41:40.024  1014  1213 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1014) eventTime = 156510
,09-09 13:41:40.024  1014  1213 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1014 (0x0)
,09-09 13:41:40.024  1014  1213 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1014, ws=WorkSource{10049}) (elapsedTime=3493)
,09-09 13:41:40.104  1014  2887 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-09 13:41:40.124  7521  7521 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,09-09 13:41:40.304  6937  6991 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything,
09-09 13:41:40.304  6937  6991 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 13:41:40.304  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 13:41:40.304  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 13:41:40.304  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown,
09-09 13:41:40.304  6937  6991 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3af51b51, channel: 6, state: LISTENING
09-09 13:41:40.304  6937  6991 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3af51b51, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1107e5db, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3a557fb6mSocket: android.net.LocalSocket@201504b7 impl:android.net.LocalSocketImpl@2cecf424 fd:FileDescriptor[111]
09-09 13:41:40.304  6937  6991 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@201504b7 impl:android.net.LocalSocketImpl@2cecf424 fd:FileDescriptor[111]
09-09 13:41:40.304  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:40.304  6937  6991 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:41:40.304  6937  7561 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3af51b51, channel: 6, state: CLOSED
09-09 13:41:40.304  6937  7561 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 13:41:40.304  6937  7561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 13:41:40.304  6937  7561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 13:41:40.304  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 13:41:40.304  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:41:40.304  6937  6991 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:41:40.304  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:41:40.304  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 13:41:40.304  6937  6937 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-09 13:41:40.314  6937  6991 D BluetoothLeScanner: could not find callback wrapper,
09-09 13:41:40.314  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 13:41:40.314  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-09 13:41:40.314  2789  2962 D BtGatt.AdvertiseManager: message : 1
,09-09 13:41:40.314  2789  2962 D BtGatt.AdvertiseManager: stop advertise for client 6
09-09 13:41:40.314  2789  2962 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6
,09-09 13:41:40.314  2789  2962 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-09 13:41:40.324  2789  2849 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0,
09-09 13:41:40.324  2789  2849 D BtGatt.GattService: Client app is not null!,
,09-09 13:41:40.324  2789  2913 D BtGatt.GattService: unregisterClient() - clientIf=6,
,09-09 13:41:40.324  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 13:41:40.334  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-09 13:41:40.334  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-09 13:41:40.334  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-09 13:41:40.334  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-09 13:41:40.334  6937  6991 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:41:40.334  6937  6991 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-09 13:41:40.334  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 13:41:40.334  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:40.334  6937  6937 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 13:41:40.334  6937  6937 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 13:41:40.334  6937  6937 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-09 13:41:40.334  6937  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:41:40.334  6937  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:41:40.334  6937  6937 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:41:40.344  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:40.344  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:40.344  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:40.344  6937  6991 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21e23cbf not in the list
09-09 13:41:40.344  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:40.344  6937  6991 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16903f8c not in the list
09-09 13:41:40.344  6937  6991 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:40.344  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:40.344  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:40.344  6937  6991 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:41:40.344  6937  6991 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:41:40.344  6937  6991 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 13:41:40.344  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 13:41:40.344  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:40.344  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 13:41:40.344  6937  6991 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 13:41:40.354  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 13:41:40.354  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:41:40.354  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 13:41:40.354  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-09 13:41:40.354  6937  6991 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 13:41:40.364  2789  2913 D BtGatt.GattService: registerClient() - UUID=6da2aa7d-6b8c-4576-8eb9-46c4f18310c6
,09-09 13:41:40.404  2789  2849 D BtGatt.GattService: onClientRegistered() - UUID=6da2aa7d-6b8c-4576-8eb9-46c4f18310c6, clientIf=6
,09-09 13:41:40.404  6937  6945 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-09 13:41:40.404  2789  2912 D BtGatt.GattService: start scan with filters
,09-09 13:41:40.414  2789  2971 D BtGatt.ScanManager: handling starting scan
,09-09 13:41:40.414  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
09-09 13:41:40.414  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 13:41:40.414  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-09 13:41:40.414  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 13:41:40.424  2789  2971 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@126ad8ca
,09-09 13:41:40.424  2789  2849 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-09 13:41:40.424  2789  2849 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 13:41:40.424  6937  6991 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 13:41:40.424  2789  2971 D BtGatt.ScanManager: allow scan with filters
,09-09 13:41:40.424  2789  2971 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-09 13:41:40.434  2789  2971 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-09 13:41:40.434  6937  6991 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 13:41:40.434  6937  6937 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 13:41:40.434  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:41:40.444  2789  2849 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-09 13:41:40.444  2789  2849 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 13:41:40.444  2789  2971 D BtGatt.ScanManager: Starting BLE batch scan
09-09 13:41:40.444  2789  2971 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-09 13:41:40.444  2789  2849 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-09 13:41:40.444  2789  2849 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 13:41:40.454  2789  2849 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-09 13:41:40.454  2789  2849 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 13:41:40.474  1014  1216 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,09-09 13:41:40.474  1014  1216 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,09-09 13:41:40.474  1014  1216 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:40.474  1014  1216 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-09 13:41:40.474  1014  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,09-09 13:41:40.934  6937  6937 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false,
09-09 13:41:40.934  6937  6937 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:41:40.934  6937  6937 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 13:41:40.954  1014  1094 V AlarmManager: waitForAlarm result :4
,09-09 13:41:40.954  2789  2789 D BtGatt.ScanManager: awakened up at time 157445
,09-09 13:41:40.954  2789  2789 D BtGatt.ScanManager: awakened up at time 157449
,09-09 13:41:40.964  2789  2971 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-09 13:41:40.964  2789  2849 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-09 13:41:40.974  2789  2849 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 13:41:41.474  1014  1094 V AlarmManager: waitForAlarm result :4
,09-09 13:41:41.474  2789  2789 D BtGatt.ScanManager: awakened up at time 157963,
09-09 13:41:41.474  2789  2789 D BtGatt.ScanManager: awakened up at time 157966
09-09 13:41:41.474  2789  2971 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6,
,09-09 13:41:41.484  2789  2849 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-09 13:41:41.484  2789  2849 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 13:41:41.654   287   287 E SMD     : DCD OFF,
,09-09 13:41:41.984  1014  1094 V AlarmManager: waitForAlarm result :4
,09-09 13:41:41.994  2789  2789 D BtGatt.ScanManager: awakened up at time 158481
,09-09 13:41:41.994  2789  2789 D BtGatt.ScanManager: awakened up at time 158485
,09-09 13:41:41.994  2789  2971 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-09 13:41:42.004  2789  2849 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-09 13:41:42.004  2789  2849 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 13:41:42.084  7564  7564 I PCWCLIENTTRACE_SYSTEMReceiver: mConnectivityHandler : connected
,09-09 13:41:42.094  7564  7611 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
,09-09 13:41:42.124  7564  7611 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
,09-09 13:41:42.124  7564  7611 I ReactiveServiceManager: Supported : 1
,09-09 13:41:42.124  1014  1555 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x2040
,09-09 13:41:42.124  1014  1555 D QSEECOMAPI: : App is not loaded in QSEE
,09-09 13:41:42.144  1014  1555 D QSEECOMAPI: : Loaded image: APP id = 12
,09-09 13:41:42.154  1014  1555 D QSEECOMAPI: : QSEECom_dealloc_memory 
,09-09 13:41:42.154  1014  1555 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 12
,09-09 13:41:42.154  1014  1555 E terrier : handleString: Failed to handle string(-4)
,09-09 13:41:42.154  1014  1555 E terrier : Java_com_android_server_ReactiveService_GetString: error code = [-4]
,09-09 13:41:42.154  7564  7611 D PCWCLIENTTRACE_SecurePreferencesJNI: getString is null
09-09 13:41:42.154  7564  7611 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
,09-09 13:41:42.154  7564  7611 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-09 13:41:42.154  7564  7611 I PCWCLIENTTRACE_PushUtil: sales region : global
,09-09 13:41:42.154  7564  7611 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-09 13:41:42.154  7564  7611 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
,09-09 13:41:42.504  1014  1094 V AlarmManager: waitForAlarm result :4
,09-09 13:41:42.504  2789  2789 D BtGatt.ScanManager: awakened up at time 158999
,09-09 13:41:42.514  2789  2789 D BtGatt.ScanManager: awakened up at time 159002
,09-09 13:41:42.514  2789  2971 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-09 13:41:42.514  2789  2849 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-09 13:41:42.524  2789  2849 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 13:41:42.654   317   317 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 13:41:43.024  1014  1094 V AlarmManager: waitForAlarm result :4
,09-09 13:41:43.024  2789  2789 D BtGatt.ScanManager: awakened up at time 159514
,09-09 13:41:43.024  2789  2789 D BtGatt.ScanManager: awakened up at time 159517
,09-09 13:41:43.034  2789  2971 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-09 13:41:43.034  2789  2849 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-09 13:41:43.034  2789  2849 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 13:41:43.444  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:41:43.444  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:43.444  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:41:43.444  6937  6991 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21e23cbf not in the list
,09-09 13:41:43.444  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:43.444  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-09 13:41:43.444  6937  6991 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:41:43.444  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 13:41:43.444  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-09 13:41:43.444  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 13:41:43.444  2789  2913 D BtGatt.GattService: stopScan() - queue size =1
,09-09 13:41:43.444  2789  2971 D BtGatt.ScanManager: filter size is 1
,09-09 13:41:43.444  2789  7471 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-09 13:41:43.454  2789  2971 D BtGatt.ScanManager: delete FilterIndex - 3
,09-09 13:41:43.454  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 13:41:43.454  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-09 13:41:43.454  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-09 13:41:43.454  2789  2849 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-09 13:41:43.454  2789  2849 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 13:41:43.454  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-09 13:41:43.454  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 13:41:43.454  2789  2971 D BtGatt.ScanManager: stopping BLe Batch
,09-09 13:41:43.464  6937  6991 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:41:43.464  2789  2849 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-09 13:41:43.464  2789  2849 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 13:41:43.464  2789  2971 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-09 13:41:43.464  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 13:41:43.464  2789  2849 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-09 13:41:43.464  2789  2849 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 13:41:43.464  6937  6991 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 13:41:43.464  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 13:41:43.474  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:43.474  6937  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:41:43.474  6937  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:41:43.474  6937  6937 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:41:43.474  6937  6991 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16903f8c not in the list
,09-09 13:41:43.474  6937  6991 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:41:43.474  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:43.474  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:43.474  6937  6991 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
,09-09 13:41:43.474  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
,09-09 13:41:43.484  6937  6991 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:41:43.484  6937  6991 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-09 13:41:43.484  6937  6991 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:41:43.484  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:43.484  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-09 13:41:43.484  6937  6991 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 13:41:43.484  6937  6991 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 13:41:43.484  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:41:43.484  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-09 13:41:43.484  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:43.484  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 13:41:43.484  6937  6937 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-09 13:41:43.484  6937  6991 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 13:41:43.494  6937  7613 D BluetoothSocket: bindListen(): myUserId = 0
,09-09 13:41:43.494  6937  7613 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:41:43.494  6937  7613 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[111]}
,09-09 13:41:43.494  6937  7613 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 13:41:43.494  6937  7613 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 13:41:43.494  6937  7613 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3680cf8e
09-09 13:41:43.494  6937  7613 D BluetoothSocket: channel: 6
09-09 13:41:43.494  6937  7613 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-09 13:41:43.494  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 13:41:43.494  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:41:43.504  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-09 13:41:43.504  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-09 13:41:43.504  6937  6991 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 08 EC A9 50 75 41
09-09 13:41:43.504  6937  6991 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 8, -20, -87, 80, 117, 65]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:41:43.504  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 8, -20, -87, 80, 117, 65]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:41:43.504  6937  6991 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-09 13:41:43.504  2789  2851 D BtGatt.GattService: registerClient() - UUID=e0d88c09-c5a1-4ae1-97fc-4a18842ef7af
,09-09 13:41:43.544  2789  2849 D BtGatt.GattService: onClientRegistered() - UUID=e0d88c09-c5a1-4ae1-97fc-4a18842ef7af, clientIf=6
,09-09 13:41:43.544  6937  6945 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-09 13:41:43.544  2789  2962 D BtGatt.AdvertiseManager: message : 0
,09-09 13:41:43.544  2789  2962 D BtGatt.AdvertiseManager: number of adv instance running0
,09-09 13:41:43.544  2789  2962 D BtGatt.AdvertiseManager: size of list is =0
,09-09 13:41:43.554  2789  2962 D BtGatt.AdvertiseManager: starting advertising
,09-09 13:41:43.554  2789  2962 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-09 13:41:43.554  2789  2849 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-09 13:41:43.564  2789  2962 D BtGatt.AdvertiseManager: starting multi advertising
,09-09 13:41:43.564  2789  2849 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-09 13:41:43.564  2789  2962 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-09 13:41:43.564  2789  2962 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-09 13:41:43.564  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-09 13:41:43.564  6937  6991 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 13:41:43.564  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:41:43.574  6937  6937 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 13:41:43.574  6937  6937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-09 13:41:43.574  6937  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-09 13:41:43.574  6937  6937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-09 13:41:43.574  6937  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-09 13:41:43.574  6937  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-09 13:41:43.574  6937  6937 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:41:43.574  6937  6937 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:41:43.654   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 13:41:44.084  6937  6937 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-09 13:41:44.084  6937  6937 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-09 13:41:44.084  6937  6937 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 13:41:44.124  7521  7521 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
,09-09 13:41:44.654   317   317 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 13:41:44.654   287   287 E SMD     : DCD OFF
,09-09 13:41:45.654   317   317 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 13:41:46.584  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
09-09 13:41:46.584  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 13:41:46.584  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-09 13:41:46.584  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 13:41:46.584  6937  6991 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1f68a3bc, channel: 6, state: LISTENING
09-09 13:41:46.584  6937  6991 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1f68a3bc, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3680cf8e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@20d92f45mSocket: android.net.LocalSocket@3d3e569a impl:android.net.LocalSocketImpl@2709fbcb fd:FileDescriptor[111]
09-09 13:41:46.584  6937  6991 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3d3e569a impl:android.net.LocalSocketImpl@2709fbcb fd:FileDescriptor[111],
09-09 13:41:46.584  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:46.584  6937  6991 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:41:46.584  6937  7613 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1f68a3bc, channel: 6, state: CLOSED
,09-09 13:41:46.584  6937  7613 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 13:41:46.584  6937  7613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 13:41:46.584  6937  7613 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 13:41:46.584  6937  6937 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-09 13:41:46.584  6937  6937 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 13:41:46.584  6937  6991 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21e23cbf not in the list
,09-09 13:41:46.584  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:46.584  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:41:46.584  6937  6991 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-09 13:41:46.584  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:41:46.584  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 13:41:46.584  6937  6991 D BluetoothLeScanner: could not find callback wrapper
,09-09 13:41:46.584  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 13:41:46.584  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-09 13:41:46.584  2789  2962 D BtGatt.AdvertiseManager: message : 1
09-09 13:41:46.584  2789  2962 D BtGatt.AdvertiseManager: stop advertise for client 6
,09-09 13:41:46.584  2789  2962 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6,
09-09 13:41:46.594  2789  2962 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
09-09 13:41:46.594  2789  2849 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0,
09-09 13:41:46.594  2789  2849 D BtGatt.GattService: Client app is not null!
09-09 13:41:46.594  2789  2913 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-09 13:41:46.604  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 13:41:46.604  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-09 13:41:46.604  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-09 13:41:46.604  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-09 13:41:46.604  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-09 13:41:46.604  6937  6991 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:41:46.604  6937  6991 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-09 13:41:46.604  6937  6991 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 13:41:46.604  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:46.614  6937  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:41:46.614  6937  6937 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:41:46.614  6937  6937 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:41:46.614  6937  6991 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16903f8c not in the list
,09-09 13:41:46.614  6937  6991 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:46.614  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:41:46.614  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:46.614  6937  6991 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:41:46.614  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:41:46.614  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:46.614  6937  6991 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21e23cbf not in the list
09-09 13:41:46.614  6937  6991 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:41:46.614  6937  6991 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16903f8c not in the list
09-09 13:41:46.614  6937  6991 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:41:46.614  6937  6991 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:46.614  6937  6991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:46.624  6937  6991 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-09 13:41:46.624  6937  6991 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-09 13:41:46.624  6937  6991 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,09-09 13:41:46.624  6937  6991 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 13:41:46.624  6937  6991 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-09 13:41:46.624  6937  6991 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 13:41:46.634  6937  7618 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1516, name: My test thread name)
,09-09 13:41:46.654   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 13:41:47.114  6937  6937 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 13:41:47.424  1014  2857 D SSRM:n  : SIOP:: AP = 330
,09-09 13:41:47.654   317   317 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-09 13:41:47.654   287   287 E SMD     : DCD OFF
,09-09 13:41:47.824  1014  1026 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,09-09 13:41:47.824  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,09-09 13:41:47.824  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:47.824  1014  1026 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,09-09 13:41:47.824  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,09-09 13:41:47.844  7386  7386 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE
,09-09 13:41:47.844  7386  7386 D PreloadUpdateManagerStateMachine: exit::IDLE
,09-09 13:41:47.844  7386  7386 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,09-09 13:41:47.844  7386  7386 D hcjo    : AutoUpdateTriggerManager:IDLE:setInterval:86400000
,09-09 13:41:47.854  7386  7386 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
,09-09 13:41:47.854  7386  7386 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,09-09 13:41:47.854  7386  7386 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
,09-09 13:41:47.854  7386  7386 D PreloadUpdateManagerStateMachine: entry::IDLE
,09-09 13:41:48.134  7521  7521 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
09-09 13:41:48.134  7521  7521 I dhcpcd  : wlan0: no IPv6 Routers available
,09-09 13:41:48.634  6937  6991 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 1516,
09-09 13:41:48.634  6937  6991 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 1516, name: My test thread name)
,09-09 13:41:48.634  6937  7619 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1517, name: My test thread name),
,09-09 13:41:48.634  6937  7619 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1517, thread name: My test thread name)
,09-09 13:41:48.634  6937  7619 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1517, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-09 13:41:48.634  6937  6991 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes,
,09-09 13:41:48.644  6937  7620 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1521, name: My test thread name)
,09-09 13:41:48.644  6937  7620 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 1521, thread name: My test thread name): Test exception.,
,09-09 13:41:48.644  6937  7620 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1521, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: testStartStop(io.jxcore.node.ConnectivityMonitorTest)
,09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: Proper state of WIFI is set when switched on
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: Expected: is <true>,
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner:      but: was <false>
,09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: Proper state of WIFI is set when switched on
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner:      but: was <false>
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectivityMonitorTest.testStartStop(ConnectivityMonitorTest.java:228)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunn,er: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:74)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$1.Receiver(RegisterExecuteUT.java:26)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.loopOnce(Native Method)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$6$1.run(jxcore.java:348)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:145)
09-09 13:41:48.644  6937  6991 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
,09-09 13:41:48.654  6937  6991 I jxcore-log: Total number of executed tests:  82
09-09 13:41:48.654  6937  6991 I jxcore-log: 
,09-09 13:41:48.654  6937  6991 I jxcore-log: Number of passed tests:  81
09-09 13:41:48.654  6937  6991 I jxcore-log: 
,09-09 13:41:48.654  6937  6991 I jxcore-log: Number of failed tests:  1
09-09 13:41:48.654  6937  6991 I jxcore-log: 
,09-09 13:41:48.654  6937  6991 I jxcore-log: Number of ignored tests:  0
09-09 13:41:48.654  6937  6991 I jxcore-log: 
,09-09 13:41:48.654  6937  6991 I jxcore-log: Total duration:  24629
09-09 13:41:48.654  6937  6991 I jxcore-log: 
,09-09 13:41:48.654  6937  6991 I jxcore-log: Failed to execute UT.
09-09 13:41:48.654  6937  6991 I jxcore-log: 
,09-09 13:41:48.654  6937  6991 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
09-09 13:41:48.654  6937  6991 I jxcore-log: 
,09-09 13:41:48.664  6937  6991 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:48.664  6937  6991 I jxcore-log: 
09-09 13:41:48.664  6937  6991 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:48.664  6937  6991 I jxcore-log: 
09-09 13:41:48.664  6937  6991 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:48.664  6937  6991 I jxcore-log: 
09-09 13:41:48.664  6937  7618 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1516, name: My test thread name), during the lifetime of the thread the total number of bytes read was 132 and the total number of bytes written 132
09-09 13:41:48.664  6937  6991 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-09 13:41:48.664  6937  6991 I jxcore-log: 
09-09 13:41:48.674  6937  6991 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:48.674  6937  6991 I jxcore-log: 
09-09 13:41:48.674  6937  6991 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:48.674  6937  6991 I jxcore-log: 
09-09 13:41:48.674  6937  6991 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:48.674  6937  6991 I jxcore-log: 
09-09 13:41:48.674  6937  6991 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:48.674  6937  6991 I jxcore-log: 
09-09 13:41:48.674  6937  6991 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:48.674  6937  6991 I jxcore-log: 
09-09 13:41:48.684  6937  6991 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:41:48.684  6937  6991 I jxcore-log: 
,09-09 13:41:48.684  6937  6991 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:41:48.684  6937  6991 I jxcore-log: 
,09-09 13:41:48.684  6937  6991 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:41:48.684  6937  6991 I jxcore-log: 
,09-09 13:41:48.684  6937  6991 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 13:41:48.684  6937  6991 I jxcore-log: 
,09-09 13:41:48.684  6937  6991 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:41:48.684  6937  6991 I jxcore-log: 
,09-09 13:41:48.684  6937  6991 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:41:48.684  6937  6991 I jxcore-log: 
,09-09 13:41:48.684  6937  6991 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:41:48.684  6937  6991 I jxcore-log: 
,09-09 13:41:48.694  6937  6991 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:41:48.694  6937  6991 I jxcore-log: 
,09-09 13:41:48.694  6937  6991 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 13:41:48.694  6937  6991 I jxcore-log: 
,09-09 13:41:48.694  6937  6991 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 13:41:48.694  6937  6991 I jxcore-log: 
,09-09 13:41:48.694  6937  6991 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 13:41:48.694  6937  6991 I jxcore-log: 
,09-09 13:41:48.694  6937  6991 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:41:48.694  6937  6991 I jxcore-log: 
,09-09 13:41:48.694  6937  6991 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:41:48.694  6937  6991 I jxcore-log: 
,09-09 13:41:48.694  6937  6991 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:41:48.694  6937  6991 I jxcore-log: 
,09-09 13:41:48.694  6937  6991 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:41:48.694  6937  6991 I jxcore-log: 
,09-09 13:41:48.704  6937  6991 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:41:48.704  6937  6991 I jxcore-log: 
,09-09 13:41:48.704  6937  6991 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:41:48.704  6937  6991 I jxcore-log: 
,09-09 13:41:48.704  6937  6991 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:41:48.704  6937  6991 I jxcore-log: 
,09-09 13:41:48.704  6937  6991 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:41:48.704  6937  6991 I jxcore-log: 
,09-09 13:41:48.704  6937  6991 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
09-09 13:41:48.704  6937  6991 I jxcore-log: 
,09-09 13:41:48.704  6937  6991 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:41:48.704  6937  6991 I jxcore-log: 
,09-09 13:41:48.704  6937  6991 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
09-09 13:41:48.704  6937  6991 I jxcore-log: 
,09-09 13:41:48.704  6937  6991 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:48.704  6937  6991 I jxcore-log: 
,09-09 13:41:48.704  6937  6991 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
09-09 13:41:48.704  6937  6991 I jxcore-log: 
,09-09 13:41:48.704  6937  6991 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
,09-09 13:41:48.704  6937  6991 I jxcore-log: 
,09-09 13:41:48.714  6937  6991 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
09-09 13:41:48.714  6937  6991 I jxcore-log: 
,09-09 13:41:48.714  6937  6991 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-09 13:41:48.714  6937  6991 I jxcore-log: 
,09-09 13:41:48.714  6937  6991 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
09-09 13:41:48.714  6937  6991 I jxcore-log: 
,09-09 13:41:48.924  7621  7621 D AndroidRuntime: ,
09-09 13:41:48.924  7621  7621 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-09 13:41:48.924  7621  7621 D AndroidRuntime: CheckJNI is OFF,
,09-09 13:41:48.924  7621  7621 D AndroidRuntime: readGMSProperty: start
09-09 13:41:48.924  7621  7621 D AndroidRuntime: readGMSProperty: already setted!!
09-09 13:41:48.924  7621  7621 D AndroidRuntime: propertySet: couldn't set property (it is from app)
,09-09 13:41:48.924  7621  7621 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-09 13:41:48.924  7621  7621 D AndroidRuntime: readGMSProperty: end
09-09 13:41:48.924  7621  7621 D AndroidRuntime: addProductProperty: start
,09-09 13:41:49.054  7621  7621 E AffinityControl: AffinityControl: registerfunction enter,
,09-09 13:41:49.084  7621  7621 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-09 13:41:49.104  1014  1556 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
09-09 13:41:49.104  1014  1556 D PackageManager: START PACKAGE DELETE: observer{640021268}
09-09 13:41:49.104  1014  1556 D PackageManager: pkg{<packageName>}
09-09 13:41:49.104  1014  1556 D PackageManager: user{0}
,09-09 13:41:49.104  1014  1556 D PackageManager: caller{2000}
09-09 13:41:49.104  1014  1556 D PackageManager: flags{2}
09-09 13:41:49.104  1014  1556 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-09 13:41:49.104  1014  1556 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-09 13:41:49.104  1014  1556 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-09 13:41:49.104  1014  1556 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2,
,09-09 13:41:49.104  1014  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0,
09-09 13:41:49.104  1014  1054 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-09 13:41:49.104  1014  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1,
09-09 13:41:49.104  1014  1054 D ApplicationPolicy: getApplicationUninstallationEnabled
09-09 13:41:49.104  1014  1054 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-09 13:41:49.114  1014  1054 D PackageManager: !@killApplicatoin: 10170, uninstall pkg,
,09-09 13:41:49.114  1014  1041 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
09-09 13:41:49.114  1014  1041 I ActivityManager: Killing 6937:com.test.thalitest/u0a170 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-09 13:41:49.124  1014  1041 I ActivityManager:   Force finishing activity ActivityRecord{1f191f90 u0 com.test.thalitest/.MainActivity t163}
,09-09 13:41:49.174  1014  1041 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-09 13:41:49.174  1014  1041 D InputDispatcher: Focus left window: 6937
09-09 13:41:49.174   257   446 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
,09-09 13:41:49.194  1014  1041 D InputDispatcher: Focused application released
09-09 13:41:49.204  1014  1046 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
09-09 13:41:49.204  1014  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-09 13:41:49.204  1014  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-09 13:41:49.284  1014  1054 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,09-09 13:41:49.294  1014  1054 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,09-09 13:41:49.314  6076  6076 I art     : Explicit concurrent mark sweep GC freed 2681(159KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 769us total 24.242ms
,09-09 13:41:49.334  1014  1097 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-09 13:41:49.344  1748  1983 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-09 13:41:49.344  1868  1868 E SamsungIME: mOCRHelper is null
,09-09 13:41:49.354  1014  1040 D EnterpriseDeviceManagerService: Package has changed for user 0
09-09 13:41:49.354  1014  1040 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,09-09 13:41:49.364  1014  1040 W TextServicesManagerService: no available spell checker services found
,09-09 13:41:49.374  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 13:41:49.374  1014  1122 V NetworkStats: removeUidsLocked() for UIDs [10170]
09-09 13:41:49.374  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:49.374  1014  1122 V NetworkStats: performPollLocked(flags=0x3)
,09-09 13:41:49.374  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:41:49.374  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 13:41:49.384  1014  1122 V NetworkStats: performPollLocked() took 10ms
09-09 13:41:49.384  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:49.384  1460  1460 D PersonaManager: isKioskContainerExistOnDevice
09-09 13:41:49.384  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:49.384  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:49.394  1460  1460 D RegisteredServicesCache: empty dynamic service
09-09 13:41:49.394  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 13:41:49.394  2917  2917 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Sep 09 13:41:49 GMT+02:00 2016
,09-09 13:41:49.394  1014  1027 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-09 13:41:49.394  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-09 13:41:49.394  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:49.394  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:49.394  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-09 13:41:49.404  2917  2917 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-09 13:41:49.414  1014  1213 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=22, mSplitNum[2]=32, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=42
,09-09 13:41:49.414  1014  1213 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,09-09 13:41:49.414  1014  1213 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,09-09 13:41:49.414  1014  1213 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:49.414  1014  1213 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:49.414  1014  1213 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:49.414  1014  1213 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:49.424  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 13:41:49.424  2917  2917 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-09 13:41:49.434  7633  7633 E Zygote  : MountEmulatedStorage()
,09-09 13:41:49.434  7633  7633 E Zygote  : v2
09-09 13:41:49.434  7633  7633 I libpersona: KNOX_SDCARD checking this for 10090
09-09 13:41:49.434  7633  7633 I libpersona: KNOX_SDCARD not a persona
,09-09 13:41:49.434  7633  7633 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:41:49.434  7633  7633 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-09 13:41:49.444  7633  7633 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 13:41:49.444  2917  2917 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-09 13:41:49.444  2917  2917 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-09 13:41:49.454  1014  1213 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7633 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,09-09 13:41:49.464  1014  1041 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,09-09 13:41:49.464  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:49.464  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:49.464  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:49.464  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:49.464  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,09-09 13:41:49.474  2917  7632 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-09 13:41:49.474  7648  7648 E Zygote  : MountEmulatedStorage()
09-09 13:41:49.474  7648  7648 E Zygote  : v2
09-09 13:41:49.474  7648  7648 I libpersona: KNOX_SDCARD checking this for 10052
09-09 13:41:49.474  7648  7648 I libpersona: KNOX_SDCARD not a persona
09-09 13:41:49.474  7648  7648 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-09 13:41:49.474  2917  7632 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,09-09 13:41:49.484  1014  1041 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7648 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,09-09 13:41:49.484  1014  1014 I art     : Explicit concurrent mark sweep GC freed 29823(2MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 23MB/34MB, paused 4.966ms total 190.184ms,
09-09 13:41:49.484  1014  1054 I art     : WaitForGcToComplete blocked for 181.544ms for cause Explicit
,09-09 13:41:49.484  7648  7648 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 13:41:49.484  7648  7648 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,09-09 13:41:49.494  1014  1026 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-09 13:41:49.494  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:49.494  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:49.494  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:49.494  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:49.494  2917  7632 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,09-09 13:41:49.494  7633  7633 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:41:49.494  7633  7633 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:49.504  2917  7632 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,09-09 13:41:49.504  7662  7662 E Zygote  : MountEmulatedStorage()
09-09 13:41:49.504  7662  7662 I libpersona: KNOX_SDCARD checking this for 10032
09-09 13:41:49.504  7662  7662 E Zygote  : v2
09-09 13:41:49.504  7662  7662 I libpersona: KNOX_SDCARD not a persona
09-09 13:41:49.504  7662  7662 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:41:49.514  1014  1027 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-09 13:41:49.514  1014  1027 D SecContentProvider2: mCursor = null
09-09 13:41:49.514  7662  7662 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 13:41:49.514  7662  7662 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
09-09 13:41:49.514  1014  1026 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7662 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:41:49.534  7648  7648 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:41:49.534  7648  7648 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:49.534  1014  1041 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,09-09 13:41:49.534  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:49.534  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:49.534  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:49.534  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:49.544  7678  7678 E Zygote  : MountEmulatedStorage(),
09-09 13:41:49.544  7678  7678 I libpersona: KNOX_SDCARD checking this for 10098
09-09 13:41:49.544  7678  7678 E Zygote  : v2
09-09 13:41:49.544  7678  7678 I libpersona: KNOX_SDCARD not a persona
09-09 13:41:49.554  7678  7678 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 13:41:49.554  7678  7678 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 13:41:49.554  7678  7678 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:41:49.564  7662  7662 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:41:49.564  7662  7662 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:49.574  1014  1041 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7678 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,09-09 13:41:49.584  1460  1460 D RegisteredComponentCache: Collect Tech packages for Knox
,09-09 13:41:49.584  7678  7678 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:41:49.584  7633  7633 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,09-09 13:41:49.584  7678  7678 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:49.594  1460  1460 D PersonaManager: isKioskContainerExistOnDevice
,09-09 13:41:49.594  7633  7633 D elm:15121: ELMEngine.ELMEngine( context ).
,09-09 13:41:49.594  7633  7633 D elm:15121: MDMBridge.setEnterpriseBridge()
,09-09 13:41:49.594  1014  1502 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
09-09 13:41:49.594  1014  1502 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,09-09 13:41:49.614  1014  1502 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:49.614  1014  1502 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:49.614  1014  1502 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,09-09 13:41:49.614  7633  7633 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,09-09 13:41:49.614  7633  7633 D elm:15121: ElmAgentService : onCreate()
,09-09 13:41:49.614  7633  7693 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
09-09 13:41:49.614  7633  7693 D elm:15121: MainReceiver.listeningToPackageRemoved()
09-09 13:41:49.614  7633  7693 D elm:15121: MDMBridge.getInstance()
09-09 13:41:49.614  7633  7693 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,09-09 13:41:49.624  7633  7693 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,09-09 13:41:49.644  1014  1216 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,09-09 13:41:49.644  1014  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:49.644  1014  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:49.644  1014  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:49.644  1014  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:49.664  7695  7695 E Zygote  : MountEmulatedStorage()
09-09 13:41:49.664  7695  7695 E Zygote  : v2
09-09 13:41:49.664  7695  7695 I libpersona: KNOX_SDCARD checking this for 1000
09-09 13:41:49.664  7695  7695 I libpersona: KNOX_SDCARD not a persona
,09-09 13:41:49.664  7695  7695 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:41:49.664  7695  7695 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 13:41:49.664  1014  1216 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7695 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-09 13:41:49.664  7695  7695 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 13:41:49.664  1014  1216 I ActivityManager: Killing 7369:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,09-09 13:41:49.664  2917  7632 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,09-09 13:41:49.684  7633  7633 D elm:15121: ElmAgentService : onDestroy().
,09-09 13:41:49.694  1014  1026 I ActivityManager: Killing 7414:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,09-09 13:41:49.714  1014  1557 I ActivityManager: Killing 7430:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,09-09 13:41:49.714  7695  7695 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:41:49.714  7695  7695 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:49.714  7662  7710 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
09-09 13:41:49.714  7662  7710 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-09 13:41:49.724  2917  7632 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,09-09 13:41:49.724  1014  1040 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,09-09 13:41:49.724  1014  1328 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
09-09 13:41:49.724  1014  1328 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
09-09 13:41:49.724  2917  7632 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,09-09 13:41:49.734  1014  1328 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:49.734  7662  7710 D SPPClientService: PushLog.txt file is not deleted.
09-09 13:41:49.734  7662  7710 D SPPClientService: PushLog.txt file is not deleted.
09-09 13:41:49.734  7662  7710 D SPPClientService: ============PushLog. stop!
,09-09 13:41:49.744  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 13:41:49.744  1014  1328 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 13:41:49.744  1014  1213 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-09 13:41:49.744  1014  1328 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,09-09 13:41:49.744  1014  1213 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4271, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-09 13:41:49.744  1014  1213 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,09-09 13:41:49.754  1014  1213 D BatteryService: stay LED for charging
,09-09 13:41:49.754  1014  1014 D RCPManagerService: PackageReceiver onReceive()
,09-09 13:41:49.754  1014  1014 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,09-09 13:41:49.754  1014  1054 I art     : Explicit concurrent mark sweep GC freed 5631(274KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 15.088ms total 274.312ms
,09-09 13:41:49.764  1014  1014 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,09-09 13:41:49.764  1014  1014 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,09-09 13:41:49.764  1014  1014 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,09-09 13:41:49.764  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 13:41:49.774  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,09-09 13:41:49.774  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:49.774  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:49.774  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:49.774  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:49.774  2917  2917 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-09 13:41:49.784  7713  7713 E Zygote  : MountEmulatedStorage()
09-09 13:41:49.784  7713  7713 I libpersona: KNOX_SDCARD checking this for 10039
09-09 13:41:49.784  7713  7713 E Zygote  : v2
09-09 13:41:49.784  7713  7713 I libpersona: KNOX_SDCARD not a persona
09-09 13:41:49.794  7713  7713 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:41:49.794  7713  7713 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 13:41:49.794  1014  1027 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7713 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
09-09 13:41:49.794  7713  7713 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:41:49.804  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 13:41:49.814  1014  1014 I OTPFW   : ProvisionData::getAllEntries Enter
,09-09 13:41:49.814  1014  1014 E OTPFW   : ProvisionData::getAllEntries Table is empty
,09-09 13:41:49.814  1014  1054 D PackageManager: delete codoeFile: 
,09-09 13:41:49.834  7713  7713 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:41:49.834  7713  7713 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:49.844  1014  1054 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest,
09-09 13:41:49.844  1014  1054 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,09-09 13:41:49.854  1014  1026 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
,09-09 13:41:49.854  1014  1054 D PackageManager: result of delete: 1{640021268}
,09-09 13:41:49.854  1014  1040 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-09 13:41:49.854  1014  1040 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:41:49.854  1014  1040 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-09 13:41:49.864  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 13:41:49.864  7621  7621 D AndroidRuntime: Shutting down VM
,09-09 13:41:49.864  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:49.864  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:49.864  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:49.864  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:49.874  7713  7713 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-09 13:41:49.874  7713  7713 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 13:41:49.874  7713  7713 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-09 13:41:49.874  7713  7713 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
09-09 13:41:49.874  7713  7713 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-09 13:41:49.874  7713  7713 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-09 13:41:49.874  7728  7728 E Zygote  : MountEmulatedStorage()
,09-09 13:41:49.874  7728  7728 E Zygote  : v2
09-09 13:41:49.874  7728  7728 I libpersona: KNOX_SDCARD checking this for 1000
09-09 13:41:49.874  7728  7728 I libpersona: KNOX_SDCARD not a persona
09-09 13:41:49.874  7728  7728 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:41:49.884  7728  7728 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-09 13:41:49.884  7713  7713 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-09 13:41:49.884  1014  1026 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7728 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-09 13:41:49.884  7728  7728 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:41:49.884  1014  1555 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,09-09 13:41:49.884  1014  1555 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-09 13:41:49.894  1014  1555 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:49.894  1014  1555 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:49.894  1014  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,09-09 13:41:49.894  1014  1054 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-09 13:41:49.894  1014  1054 D PackageManager: userId{-1}
09-09 13:41:49.894  1014  1054 D PackageManager: andCode{true}
,09-09 13:41:49.904  1014  1555 I ActivityManager: Killing 6804:com.samsung.android.securitylogagent/1000 (adj 15): empty #21
,09-09 13:41:49.904  7728  7728 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:41:49.904  7728  7728 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:49.924  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 13:41:49.924  1014  1054 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-09 13:41:49.924  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 13:41:49.934  1014  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:49.934  1014  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:49.934  1014  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:49.934  1014  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:49.934  7728  7728 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
,09-09 13:41:49.944  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-09 13:41:49.944  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-09 13:41:49.954  7743  7743 E Zygote  : MountEmulatedStorage(),
09-09 13:41:49.954  7743  7743 E Zygote  : v2
09-09 13:41:49.954  7743  7743 I libpersona: KNOX_SDCARD checking this for 10003
09-09 13:41:49.954  7743  7743 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-09 13:41:49.954  7743  7743 I libpersona: KNOX_SDCARD not a persona
,09-09 13:41:49.954  7743  7743 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 13:41:49.954  1014  1054 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7743 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-09 13:41:49.954  7743  7743 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:41:49.954  1014  1328 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-09 13:41:49.964  1014  1328 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:49.954  1014  1328 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
09-09 13:41:49.964  1014  1328 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:49.964  1014  1328 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,09-09 13:41:49.964  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 13:41:49.964  1014  1501 D ActivityManager: startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
,09-09 13:41:49.964  1014  1501 D ActivityManager: retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,09-09 13:41:49.974  1014  1501 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:49.974  1014  1501 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 13:41:49.974  1014  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,09-09 13:41:49.974  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-09 13:41:49.974  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-09 13:41:49.974  7743  7743 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:41:49.974  7743  7743 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:49.984  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 13:41:49.984  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-09 13:41:49.984  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 13:41:49.984  1014  1040 D UsbSettingsManager: clearDefaults: com.test.thalitest
,09-09 13:41:49.994  1014  1040 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,09-09 13:41:49.994  1014  1014 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,09-09 13:41:49.994  1014  1014 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-09 13:41:49.994  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-09 13:41:49.994  1014  1014 V EnterpriseBillingPolicy: uID is 10170
09-09 13:41:49.994  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
09-09 13:41:49.994  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-09 13:41:49.994  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-09 13:41:49.994  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-09 13:41:49.994  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-09 13:41:49.994  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-09 13:41:49.994  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
09-09 13:41:49.994  1014  1216 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,09-09 13:41:49.994  1014  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:49.994  1014  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:49.994  1014  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:49.994  1014  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:50.014  7762  7762 E Zygote  : MountEmulatedStorage()
09-09 13:41:50.014  7762  7762 I libpersona: KNOX_SDCARD checking this for 1000
09-09 13:41:50.014  7762  7762 E Zygote  : v2
09-09 13:41:50.014  7762  7762 I libpersona: KNOX_SDCARD not a persona
09-09 13:41:50.014  7762  7762 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 13:41:50.014  7762  7762 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 13:41:50.014  7762  7762 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:41:50.024  1014  1216 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=7762 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-09 13:41:50.024  1014  1014 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-09 13:41:50.024  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-09 13:41:50.024  1014  1014 V EnterpriseBillingPolicy: uID is 10170
09-09 13:41:50.024  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
09-09 13:41:50.024  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
09-09 13:41:50.024  1014  2857 D SSRM:bc : MSG_TYPE_APP_REMOVED::
09-09 13:41:50.024  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-09 13:41:50.024  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-09 13:41:50.024  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-09 13:41:50.024  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
09-09 13:41:50.024  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-09 13:41:50.034  1014  1216 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-09 13:41:50.034  1014  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:50.034  1014  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:50.034  1014  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:50.034  1014  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:50.044  7776  7776 E Zygote  : MountEmulatedStorage()
09-09 13:41:50.044  7776  7776 E Zygote  : v2
09-09 13:41:50.044  7776  7776 I libpersona: KNOX_SDCARD checking this for 10055
09-09 13:41:50.044  7776  7776 I libpersona: KNOX_SDCARD not a persona
,09-09 13:41:50.044  7776  7776 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:41:50.054  7776  7776 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 13:41:50.054  7776  7776 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:41:50.054  1014  1216 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=7776 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,09-09 13:41:50.064  7762  7762 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:41:50.064  7762  7762 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:50.064  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
09-09 13:41:50.064  1014  1027 I ActivityManager: Killing 7072:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
09-09 13:41:50.074  1014  1159 D TaskPersister: removeObsoleteFile: deleting file=163_task.xml
09-09 13:41:50.074  7621  7621 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
09-09 13:41:50.074  1014  1014 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
,09-09 13:41:50.084  7776  7776 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:41:50.094  7776  7776 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:50.094   305   305 I art     : Explicit concurrent mark sweep GC freed 8731(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 612us total 37.684ms
09-09 13:41:50.094  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-09 13:41:50.094  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-09 13:41:50.094  1421  1421 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-09 13:41:50.094  1421  1421 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-09 13:41:50.114  2789  2789 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-09 13:41:50.114  2789  7454 D HeadsetStateMachine: Disconnected process message: 10
,09-09 13:41:50.114   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 593us total 21.802ms,
,09-09 13:41:50.124  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-09 13:41:50.124  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-09 13:41:50.124  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-09 13:41:50.124  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
09-09 13:41:50.124  1174  1174 D SViewCoverView: level :100 plugged : 2
,09-09 13:41:50.134  1014  1213 I ActivityManager: Killing 7087:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #21
,09-09 13:41:50.134  7713  7713 D NearbySource: Nearby Source Create!
09-09 13:41:50.134  7713  7713 D NearbyContext: Nearby Context Create!
09-09 13:41:50.134   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 591us total 18.761ms
,09-09 13:41:50.144  2635  2635 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
09-09 13:41:50.144  2635  2635 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-09 13:41:50.164  1014  1501 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 13:41:50.164  1014  1501 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,09-09 13:41:50.164  1014  1501 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:50.164  1014  1501 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:50.164  1014  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:50.174  1917  7796 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-09 13:41:50.174  1917  7796 D AccountUtils: Clearing selected account for com.test.thalitest
,09-09 13:41:50.184   256   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
09-09 13:41:50.184   256   525 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:41:50.184  7713  7713 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,09-09 13:41:50.184  7713  7713 D SLinkSource: Samsung link source created
,09-09 13:41:50.184  7776  7776 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-09 13:41:50.204  7762  7798 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_REMOVED
,09-09 13:41:50.204  1014  1501 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:41:50.214  1014  1501 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:50.214  1014  1501 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:50.214  1014  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:50.214  1014  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:41:50.214  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:50.224  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:50.224  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:50.224  1014  1328 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
09-09 13:41:50.224  1014  1328 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,09-09 13:41:50.224  1014  1328 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:50.224  1014  1328 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:50.224  1014  1328 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,09-09 13:41:50.224  7762  7798 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,09-09 13:41:50.224  1014  1026 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,09-09 13:41:50.224  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,09-09 13:41:50.224  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:50.224  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:50.224  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,09-09 13:41:50.234  7762  7762 D AcmsService: Enter Oncreate
,09-09 13:41:50.234  7762  7762 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,09-09 13:41:50.234  1014  1014 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sm/databases/sm.db" with flag (131074) and mode_t (0) due to error (30)
09-09 13:41:50.234  7762  7762 D AcmsService: creating AcmsCore
,09-09 13:41:50.234  1014  1026 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 13:41:50.234  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService; callingUser = 0; userId(target) = 0
,09-09 13:41:50.234  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:50.244  7762  7762 D AcmsCore: AcmsCore.getAcmsCore() - Enter
09-09 13:41:50.244  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:50.244  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:50.244  7762  7762 D AcmsCore: AcmsCore
,09-09 13:41:50.244  1014  1014 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.sm/databases/sm.db'.
09-09 13:41:50.244  1014  1014 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 13:41:50.244  1014  1014 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 13:41:50.244  1014  1014 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-09 13:41:50.244  1014  1014 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-09 13:41:50.244  1014  1014 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-09 13:41:50.244  1014  1014 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-09 13:41:50.244  1014  1014 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-09 13:41:50.244  1014  1014 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-09 13:41:50.244  1014  1014 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-09 13:41:50.244  1014  1014 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-09 13:41:50.244  1014  1014 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:674)
09-09 13:41:50.244  1014  1014 E SQLiteDatabase: 	at com.android.server.LpnetManagerService$DBManager.dbOpen(LpnetManagerService.java:2300)
09-09 13:41:50.244  1014  1014 E SQLiteDatabase: 	at com.android.server.LpnetManagerService$2$1.run(LpnetManagerService.java:724)
09-09 13:41:50.244  1014  1014 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 13:41:50.244  1014  1014 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 13:41:50.244  1014  1014 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-09 13:41:50.244  1014  1014 E SQLiteDatabase: 	at com.android.server.SystemServer.run(SystemServer.java:445)
09-09 13:41:50.244  1014  1014 E SQLiteDatabase: 	at com.android.server.SystemServer.main(SystemServer.java:329)
09-09 13:41:50.244  1014  1014 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:50.244  1014  1014 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:41:50.244  1014  1014 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 13:41:50.244  1014  1014 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 13:41:50.244  1014  1014 E LpnetManagerService: Exception on handling DB : not an error (code 0): Could not open the database in read/write mode.
09-09 13:41:50.244  1014  1014 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 13:41:50.244  1014  1014 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 13:41:50.244  1014  1014 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-09 13:41:50.244  1014  1014 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-09 13:41:50.244  1014  1014 I MotionRecognitionService: Plugged
09-09 13:41:50.244  1014  1014 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-09 13:41:50.244  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
09-09 13:41:50.244  1014  1014 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-09 13:41:50.244  1014  1014 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
0,9-09 13:41:50.244  1014  1014 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-09 13:41:50.244  1014  1014 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-09 13:41:50.244  1014  1014 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-09 13:41:50.244  1014  1014 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:674)
09-09 13:41:50.244  1014  1014 W System.err: 	at com.android.server.LpnetManagerService$DBManager.dbOpen(LpnetManagerService.java:2300)
09-09 13:41:50.244  1014  1014 W System.err: 	at com.android.server.LpnetManagerService$2$1.run(LpnetManagerService.java:724)
09-09 13:41:50.244  1014  1014 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 13:41:50.244  1014  1014 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 13:41:50.244  1014  1014 W System.err: 	at android.os.Looper.loop(Looper.java:145)
09-09 13:41:50.244  1014  1014 W System.err: 	at com.android.server.SystemServer.run(SystemServer.java:445)
09-09 13:41:50.244  1014  1014 W System.err: 	at com.android.server.SystemServer.main(SystemServer.java:329)
09-09 13:41:50.244  1014  1014 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:50.244  1014  1014 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:41:50.244  1014  1014 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 13:41:50.244  1014  1014 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-09 13:41:50.254  7762  7762 D AcmsCore: init
,09-09 13:41:50.254  7762  7762 D AcmsCore: Looper handler is not null
,09-09 13:41:50.254  7762  7762 D AcmsCore: Post to AcmsCoreHandler
09-09 13:41:50.254  7762  7762 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-09 13:41:50.254  7762  7762 D AcmsServiceMonitor: Incrementing - Counter value: 1
09-09 13:41:50.254  7762  7762 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>1
,09-09 13:41:50.254  7762  7762 D AcmsService: onStartCommand
09-09 13:41:50.254  7762  7762 D AcmsService: Action: android.intent.action.PACKAGE_REMOVED
09-09 13:41:50.254  7762  7762 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 1
09-09 13:41:50.254  7762  7762 D AcmsServiceMonitor: Incrementing - Counter value: 2
09-09 13:41:50.254  7762  7762 D AcmsService: Incremented Counter Value : onStartCommand
,09-09 13:41:50.254  1014  1558 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
09-09 13:41:50.254  1014  1558 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,09-09 13:41:50.254  1014  1558 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:50.254  1014  1558 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:50.254  1014  1558 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,09-09 13:41:50.254  7762  7803 D AcmsCertificateMngr: AcmsCertificateMngr
,09-09 13:41:50.254  1014  1555 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,09-09 13:41:50.264  7762  7803 D AcmsRevocationMngr: AcmsRevocationMngr
,09-09 13:41:50.264  1917  7796 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,09-09 13:41:50.264  7762  7762 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,09-09 13:41:50.264  1014  1501 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
,09-09 13:41:50.264  1014  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:50.264  1014  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:50.264  1014  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:50.264  1014  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:50.274  7762  7762 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.app.mirrorlink/databases/pkgnamedb" with flag (131138) and mode_t (0) due to error (30)
,09-09 13:41:50.284  1917  1917 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,09-09 13:41:50.284  1917  1917 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded,
,09-09 13:41:50.284  7809  7809 E Zygote  : MountEmulatedStorage(),
09-09 13:41:50.284  7809  7809 I libpersona: KNOX_SDCARD checking this for 1000
09-09 13:41:50.284  7809  7809 E Zygote  : v2
09-09 13:41:50.284  7809  7809 I libpersona: KNOX_SDCARD not a persona
,09-09 13:41:50.284  7776  7776 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,09-09 13:41:50.284  7776  7776 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-09 13:41:50.284  7776  7776 D UserAnalysis: Create SecureDbHelper
,09-09 13:41:50.294  7762  7762 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.app.mirrorlink/databases/pkgnamedb'.
09-09 13:41:50.294  7762  7762 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 13:41:50.294  7762  7762 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 13:41:50.294  7762  7762 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-09 13:41:50.294  7762  7762 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-09 13:41:50.294  7762  7762 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-09 13:41:50.294  7762  7762 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-09 13:41:50.294  7762  7762 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-09 13:41:50.294  7762  7762 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-09 13:41:50.294  7762  7762 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-09 13:41:50.294  7762  7762 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-09 13:41:50.294  7762  7762 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-09 13:41:50.294  7762  7762 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 13:41:50.294  7762  7762 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 13:41:50.294  7762  7762 E SQLiteDatabase: 	at com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide.onCreate(AcmsPkgNameProvide.java:61)
09-09 13:41:50.294  7762  7762 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
09-09 13:41:50.294  7762  7762 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
09-09 13:41:50.294  7762  7762 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
09-09 13:41:50.294  7762  7762 E SQLiteDatabase: 	at android.app.ActivityThread.acquireProvider(ActivityThread.java:5338)
09-09 13:41:50.294  7762  7762 E SQLiteDatabase: 	at android.app.ContextImpl$ApplicationContentResolver.acquireUnstableProvider(ContextImpl.java:2966)
09-09 13:41:50.294  7762  7762 E SQLiteDatabase: 	at android.content.ContentResolver.acquireUnstableProvider(ContentResolver.java:1495)
09-09 13:41:50.294  7762  7762 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:473)
09-09 13:41:50.294  7762  7762 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:433)
09-09 13:41:50.294  7762  7762 E SQLiteDatabase: 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.checkIfPkgNameExists(AppEntryInterface.java:71)
09-09 13:41:50.294  7762  7762 E SQLiteDatabase: 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.<init>(AppEntryInterface.java:56)
09-09 13:41:50.294  7762  7762 E SQLiteDatabase: 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.getAppEntryInterface(AppEntryInterface.java:64)
09-09 13:41:50.294  7762  7762 E SQLiteDatabase: 	at com.samsung.android.mirrorlink.acms.api.AcmsService.handleStartIntent(AcmsService.java:95)
09-09 13:41:50.294  7762  7762 E SQLiteDatabase: 	at com.samsung.android.mirrorlink.acms.api.AcmsService.onStartCommand(AcmsService.java:77)
09-09 13:41:50.294  7762  7762 E SQLiteDatabase: 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3440)
09-09 13:41:50.294  7762  7762 E SQLiteDatabase: 	at android.app.ActivityThread.access$2200(ActivityThread.java:181)
09-09 13:41:50.294  7762,  7762 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1580)
09-09 13:41:50.294  7762  7762 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:41:50.294  7762  7762 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-09 13:41:50.294  7762  7762 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 13:41:50.294  7762  7762 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:50.294  7762  7762 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:41:50.294  7762  7762 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 13:41:50.294  7762  7762 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 13:41:50.294  1014  1501 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=7809 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-09 13:41:50.294  7762  7762 D AndroidRuntime: Shutting down VM
09-09 13:41:50.294  7762  7762 E AndroidRuntime: FATAL EXCEPTION: main
09-09 13:41:50.294  7762  7762 E AndroidRuntime: Process: ACMS.Process, PID: 7762
09-09 13:41:50.294  7762  7762 E AndroidRuntime: java.lang.RuntimeException: Unable to start service com.samsung.android.mirrorlink.acms.api.AcmsService@1d388ebe with Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService (has extras) }: java.lang.RuntimeException: Unable to get provider com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 13:41:50.294  7762  7762 E AndroidRuntime: 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3457)
09-09 13:41:50.294  7762  7762 E AndroidRuntime: 	at android.app.ActivityThread.access$2200(ActivityThread.java:181)
09-09 13:41:50.294  7762  7762 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1580)
09-09 13:41:50.294  7762  7762 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:41:50.294  7762  7762 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
09-09 13:41:50.294  7762  7762 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 13:41:50.294  7762  7762 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:50.294  7762  7762 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:41:50.294  7762  7762 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 13:41:50.294  7762  7762 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 13:41:50.294  7762  7762 E AndroidRuntime: Caused by: java.lang.RuntimeException: Unable to get provider com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 13:41:50.294  7762  7762 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5705)
09-09 13:41:50.294  7762  7762 E AndroidRuntime: 	at android.app.ActivityThread.acquireProvider(ActivityThread.java:5338)
09-09 13:41:50.294  7762  7762 E AndroidRuntime: 	at android.app.ContextImpl$ApplicationContentResolver.acquireUnstableProvider(ContextImpl.java:2966)
09-09 13:41:50.294  7762  7762 E AndroidRuntime: 	at android.content.ContentResolver.acquireUnstableProvider(ContentResolver.java:1495)
09-09 13:41:50.294  7762  7762 E AndroidRuntime: 	at android.content.ContentResolver.query(ContentResolver.java:473)
09-09 13:41:50.294  7762  7762 E AndroidRuntime: 	at android.content.ContentResolver.query(ContentResolver.java:433)
09-09 13:41:50.294  7762  7762 E AndroidRuntime: 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.checkIfPkgNameExists(AppEntryInterface.java:71)
09-09 13:41:50.294  7762  7762 E AndroidRuntime: 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.<init>(AppEntryInterface.java:56)
09-09 13:41:50.294  7762  7762 E AndroidRuntime: 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.getAppEntryInterface(AppEntryInterface.java:64)
09-09 13:41:50.294  7762  7762 E AndroidRuntime: 	at com.samsung.android.mirrorlink.acms.api.AcmsService.handleStartIntent(AcmsService.java:95)
09-09 13:41:50.294  7762  7762 E AndroidRuntime: 	at com.samsung.android.mirrorlink.acms.api.AcmsService.onStartCommand(AcmsService.java:77)
09-09 13:41:50.294  7762  7762 E AndroidRuntime: 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3440)
09-09 13:41:50.294  7762  7762 E AndroidRuntime: 	... 9 more
09-09 13:41:50.294  7762  7762 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Co,uld not open the database in read/write mode.
09-09 13:41:50.294  7762  7762 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 13:41:50.294  7762  7762 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-09 13:41:50.294  7762  7762 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-09 13:41:50.294  7762  7762 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-09 13:41:50.294  7762  7762 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-09 13:41:50.294  7762  7762 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-09 13:41:50.294  7762  7762 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-09 13:41:50.294  7762  7762 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-09 13:41:50.294  7762  7762 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-09 13:41:50.294  7762  7762 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-09 13:41:50.294  7762  7762 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 13:41:50.294  7762  7762 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 13:41:50.294  7762  7762 E AndroidRuntime: 	at com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide.onCreate(AcmsPkgNameProvide.java:61)
09-09 13:41:50.294  7762  7762 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
09-09 13:41:50.294  7762  7762 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
09-09 13:41:50.294  7762  7762 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
09-09 13:41:50.294  7762  7762 E AndroidRuntime: 	... 20 more
09-09 13:41:50.294  1014  1213 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
09-09 13:41:50.294  1014  1213 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:50.294  1014  1213 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.util.PreferenceService; callingUser = 0; userId(target) = 0
09-09 13:41:50.294  1014  1213 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:50.294  1014  1213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-09 13:41:50.294  7713  7713 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.gallery3d/databases/local.db" with flag (131138) and mode_t (0) due to error (30)
09-09 13:41:50.294  7809  7809 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:41:50.304  1014  1500 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:41:50.304  7809  7809 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 13:41:50.304  1014  1500 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:50.304  7809  7809 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:41:50.304  1014  1500 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:50.304  1014  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-09 13:41:50.304  1014  1501 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,09-09 13:41:50.304  7762  7803 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
09-09 13:41:50.304  7762  7803 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.app.mirrorlink/databases/pkgnamedb" with flag (131138) and mode_t (0) due to error (30)
,09-09 13:41:50.314  1014  1026 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms

```
