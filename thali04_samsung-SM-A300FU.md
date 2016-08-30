#### Test 828946826174a68_thali04_samsung-SM-A300FU Logs


```
--------- beginning of main
08-30 17:07:50.632  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-30 17:07:50.632  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
--------- beginning of system
08-30 17:07:50.632  1016  1498 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-30 17:07:50.632  1016  1498 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-30 17:07:50.632  1016  1498 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-30 17:07:50.632  1016  1498 D BatteryService: stay LED for fully charged
08-30 17:07:50.632  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-30 17:07:50.632  1016  1016 I MotionRecognitionService: Plugged
08-30 17:07:50.632  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
08-30 17:07:50.632  1431  1431 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-30 17:07:50.632  1431  1431 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-30 17:07:50.642  3155  3155 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-30 17:07:50.642  3155  3260 D HeadsetStateMachine: Disconnected process message: 10
08-30 17:07:50.662  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-30 17:07:50.662  1177  1177 D SViewCoverView: level :100 plugged : 2
08-30 17:07:50.662  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-30 17:07:50.662  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-30 17:07:50.662  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-30 17:07:51.002  6754  6754 D AndroidRuntime: 
08-30 17:07:51.002  6754  6754 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-30 17:07:51.012  6754  6754 D AndroidRuntime: CheckJNI is OFF
08-30 17:07:51.012  6754  6754 D AndroidRuntime: readGMSProperty: start
08-30 17:07:51.012  6754  6754 D AndroidRuntime: readGMSProperty: already setted!!
08-30 17:07:51.012  6754  6754 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-30 17:07:51.012  6754  6754 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-30 17:07:51.012  6754  6754 D AndroidRuntime: readGMSProperty: end
08-30 17:07:51.012  6754  6754 D AndroidRuntime: addProductProperty: start
08-30 17:07:51.162  6754  6754 E AffinityControl: AffinityControl: registerfunction enter
08-30 17:07:51.182  6754  6754 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-30 17:07:51.202  1016  2050 E PersonaManagerService: inState():  stateMachine is null !!
08-30 17:07:51.202  1016  2050 I PersonaManagerService: PersonaId don't exist
08-30 17:07:51.202  1016  2050 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-30 17:07:51.212  1016  2050 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-30 17:07:51.222  1016  2050 W ActivityManager: mDVFSHelper.acquire()
08-30 17:07:51.232   259   259 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
08-30 17:07:51.232   259   259 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
08-30 17:07:51.232  1016  2050 D FocusedStackFrame: Set to : 0
08-30 17:07:51.242  1016  2050 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:07:51.242  1016  2050 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:07:51.242  1016  2050 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:07:51.242  1016  2050 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:07:51.242  1016  1047 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-30 17:07:51.242  1016  1047 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-30 17:07:51.252  6765  6765 E Zygote  : MountEmulatedStorage()
08-30 17:07:51.252  6765  6765 I libpersona: KNOX_SDCARD checking this for 10171
08-30 17:07:51.252  6765  6765 E Zygote  : v2
08-30 17:07:51.252  6765  6765 I libpersona: KNOX_SDCARD not a persona
08-30 17:07:51.252  1016  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-30 17:07:51.252  1016  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-30 17:07:51.262   259   259 I SurfaceFlinger: id=12 createSurf (540x960),1 flag=404, uhalitest
08-30 17:07:51.262  6765  6765 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 17:07:51.262  6765  6765 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 17:07:51.262  6765  6765 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-30 17:07:51.262  1016  2050 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-30 17:07:51.262  1016  2050 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6765 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-30 17:07:51.262  1016  2050 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-30 17:07:51.262  1016  2050 D InputDispatcher: Focused application set to: xxxx
08-30 17:07:51.262  1016  2050 D InputDispatcher: Focus left window: 1499
08-30 17:07:51.272  6754  6754 D AndroidRuntime: Shutting down VM
08-30 17:07:51.292  6765  6765 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:07:51.292  6765  6765 D ActivityThread: Added TimaKeyStore provider
08-30 17:07:51.292  1016  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-30 17:07:51.292  1016  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
08-30 17:07:51.292  1016  1028 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-30 17:07:51.292  1016  1016 V ActivityManager: Display changed displayId=0
08-30 17:07:51.302  1016  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-30 17:07:51.312  1016  1028 D PersonaManager: isKioskContainerExistOnDevice
08-30 17:07:51.332  1016  1016 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-30 17:07:51.352   259  6007 I SurfaceFlinger: id=6 Removed Mauncher (5/9)
08-30 17:07:51.362  1499  1499 V ActivityThread: updateVisibility : ActivityRecord{88282f token=android.os.BinderProxy@29f0b216 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-30 17:07:51.362  1499  1499 D Launcher: onTrimMemory. Level: 20
08-30 17:07:51.432  6765  6765 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-30 17:07:51.452  6765  6765 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 6959-6961)
08-30 17:07:51.452  6765  6765 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-30 17:07:51.472  6754  6754 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-30 17:07:51.502  6765  6765 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3b6b9514}
08-30 17:07:51.502  6765  6765 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-30 17:07:51.502  6765  6765 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 17:07:51.552  6765  6765 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
08-30 17:07:51.552  6765  6765 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 17:07:51.562  6765  6765 E SysUtils: ApplicationContext is null in ApplicationStatus
08-30 17:07:51.582  6765  6765 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-30 17:07:51.582  6765  6765 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-30 17:07:51.582  6765  6765 I Adreno-EGL: Build Date: 04/06/15 Mon
08-30 17:07:51.582  6765  6765 I Adreno-EGL: Local Branch: 
08-30 17:07:51.582  6765  6765 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-30 17:07:51.582  6765  6765 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-30 17:07:51.582  6765  6765 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-30 17:07:51.632   296   296 E SMD     : DCD OFF
08-30 17:07:51.642  6765  6765 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 17:07:51.662  6765  6765 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-30 17:07:51.662  6765  6765 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-30 17:07:51.672  6765  6765 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-30 17:07:51.672  6765  6765 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-30 17:07:51.772  6765  6765 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 17:07:51.792  6765  6765 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-30 17:07:51.802  6765  6765 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-30 17:07:51.802  6765  6765 D PhoneWindow: *FMB* installDecor flags : -2139027200
08-30 17:07:51.802  6765  6765 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
08-30 17:07:51.812  6765  6765 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 17:07:51.812  6765  6765 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 17:07:51.822  1016  1042 W ActivityManager: Activity pause timeout for ActivityRecord{17b0c50d u0 com.test.thalitest/.MainActivity t2}
08-30 17:07:51.912  6765  6806 D OpenGLRenderer: Render dirty regions requested: true
08-30 17:07:51.922  1016  1536 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-30 17:07:51.922  1016  1536 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-30 17:07:51.922  1016  1536 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-30 17:07:51.922  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-30 17:07:51.922  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
08-30 17:07:51.922  6765  6793 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
08-30 17:07:51.922  6765  6765 V ActivityThread: updateVisibility : ActivityRecord{229f2d74 token=android.os.BinderProxy@24449161 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-30 17:07:51.932  6765  6765 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-30 17:07:51.932  6765  6765 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-30 17:07:51.942   259   259 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
08-30 17:07:51.952  1016  1029 D InputDispatcher: Focus entered window: 6765
08-30 17:07:51.962  1016  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-30 17:07:51.962  1016  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
08-30 17:07:51.962  6765  6765 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-30 17:07:51.962  6765  6806 I OpenGLRenderer: Initialized EGL, version 1.4
08-30 17:07:51.972  6765  6806 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-30 17:07:51.972  6765  6806 D OpenGLRenderer: Enabling debug mode 0
08-30 17:07:51.992  1016  2050 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-30 17:07:51.992  1016  6810 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-30 17:07:52.002  1177  1177 I StatusBar: Icon Only
08-30 17:07:52.002  1177  1177 D PanelView: There is/are notification(s) 
08-30 17:07:52.012  1016  1047 I ActivityManager: Displayed Component not be shown by security: +689ms (total +770ms)
08-30 17:07:52.012  1016  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{17b0c50d u0 com.test.thalitest/.MainActivity t2} time:107521
08-30 17:07:52.012  1016  1047 W ActivityManager: mDVFSHelper.release()
08-30 17:07:52.012  6765  6765 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-30 17:07:52.012   259   450 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
08-30 17:07:52.012   259  1038 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
08-30 17:07:52.012  6765  6765 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@24449161 time:107529
08-30 17:07:52.032  1866  1866 I SamsungIME: getCurrentCandidateView
08-30 17:07:52.102  6765  6765 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6765
08-30 17:07:52.152  1866  1866 D SamsungIME: Dismiss ExpandCandiate
,08-30 17:07:52.292  6765  6765 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 17:07:52.312  1866  1866 I SamsungIME: getDebugLevel  : 0x4f4c
,08-30 17:07:52.352  1866  1866 I SamsungIME: getDebugLevel  : 0x4f4c
,08-30 17:07:52.362  1866  1866 I SamsungIME: KeybaordView init() : load resources
,08-30 17:07:52.382  6765  6814 D jxcore_app_log: JniHelper::setJavaVM(0xb81032b0), pthread_self() = -1201075240
,08-30 17:07:52.382  1866  1866 I SamsungIME: getCurrentKeyboard
08-30 17:07:52.382  1866  1866 I SamsungIME: getTextKeyboard
,08-30 17:07:52.392  6765  6814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 17:07:52.392  6765  6814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 17:07:52.392  6765  6814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 17:07:52.392  6765  6814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 17:07:52.392  6765  6814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-30 17:07:52.392  6765  6814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f6a626a added. We now have 1 listener(s)
,08-30 17:07:52.392  6765  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,08-30 17:07:52.392  6765  6814 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-30 17:07:52.402  6765  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
08-30 17:07:52.402  6765  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 17:07:52.402  6765  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 17:07:52.402  6765  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 17:07:52.402  6765  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 17:07:52.402  6765  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
08-30 17:07:52.402  6765  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 17:07:52.402  6765  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 17:07:52.402  6765  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 17:07:52.402  6765  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 17:07:52.402  6765  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 17:07:52.402  6765  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 17:07:52.402  6765  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 17:07:52.402  6765  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 17:07:52.402  6765  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 17:07:52.402  6765  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 17:07:52.402  6765  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4394d1 added. We now have 1 listener(s)
,08-30 17:07:52.402  6765  6814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:07:52.412  6765  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 17:07:52.412  6765  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 17:07:52.412  6765  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-30 17:07:52.412  6765  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 17:07:52.412  6765  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-30 17:07:52.412  1866  1866 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-30 17:07:52.412  6765  6814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:07:52.412  6765  6814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,08-30 17:07:52.422  6765  6814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-30 17:07:52.422  6765  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:07:52.422  6765  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:07:52.422  6765  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:07:52.422  6765  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:07:52.422  6765  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:07:52.422  6765  6814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:07:52.422  6765  6814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:07:52.422  6765  6814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:07:52.422  6765  6814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 17:07:52.422  6765  6814 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 17:07:52.422  6765  6814 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-30 17:07:52.422  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:07:52.432  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:07:52.462  6765  6765 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 17:07:52.672  1016  1321 E Watchdog: !@Sync 3
,08-30 17:07:52.962  6765  6822 W jxcore-log: Initializing JXcore engine
08-30 17:07:52.962  6765  6822 W jxcore-log: JXcore engine is ready
,08-30 17:07:53.032  2010  2010 E audit   : type=1400 msg=audit(1472569673.032:205): avc:  denied  { ioctl } for  pid=6822 comm="Thread-1252" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3080 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-30 17:07:53.032  2010  2010 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-30 17:07:53.032  2010  2010 E audit   : type=1300 msg=audit(1472569673.032:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9e6fb8f8 items=0 ppid=323 ppcomm=main pid=6822 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1252" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-30 17:07:53.032  2010  2010 E audit   : type=1320 msg=audit(1472569673.032:205): 
,08-30 17:07:53.042  6765  6822 W jxcore-log: Starting JXcore engine
,08-30 17:07:53.152  6765  6822 W jxcore-log: Platform android
08-30 17:07:53.152  6765  6822 W jxcore-log: 
08-30 17:07:53.152  6765  6822 W jxcore-log: Process ARCH arm
08-30 17:07:53.152  6765  6822 W jxcore-log: 
,08-30 17:07:53.352  6765  6822 I jxcore-log: JXcore Cordova bridge is ready!,
08-30 17:07:53.352  6765  6822 I jxcore-log: 
08-30 17:07:53.352  6765  6822 W jxcore-log: JXcore engine is started
,08-30 17:07:53.362  6765  6814 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION,
,08-30 17:07:53.362  6765  6765 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41),
,08-30 17:07:53.662   333   333 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-30 17:07:53.662   333   333 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-30 17:07:54.632   296   296 E SMD     : DCD OFF
,08-30 17:07:57.292  1016  1049 I PowerManagerService: [PWL] Off : 50s ago
,08-30 17:07:57.492  1016  3331 D SSRM:n  : SIOP:: AP = 340
,08-30 17:07:57.632   296   296 E SMD     : DCD OFF
,08-30 17:07:58.662   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,08-30 17:07:59.662   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 17:07:59.982  1016  1095 V AlarmManager: waitForAlarm result :8
,08-30 17:08:00.172  5644  5644 D FactoryTest: Not factory mode
,08-30 17:08:00.172  5644  5644 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-30 17:08:00.172  5644  5644 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
08-30 17:08:00.172  5644  5644 D MTPRx   : still no open session command from host, so toast
,08-30 17:08:00.182  5644  5644 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 ,
,08-30 17:08:00.182  5644  5644 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-30 17:08:00.182  5644  5644 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:115696
,08-30 17:08:00.182  1016  2050 E PersonaManagerService: inState():  stateMachine is null !!
,08-30 17:08:00.182  1016  2050 I PersonaManagerService: PersonaId don't exist
,08-30 17:08:00.182  1016  2050 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-30 17:08:00.192  1016  2050 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-30 17:08:00.192  1016  2050 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:00.192  1016  2050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:00.192  1016  2050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-30 17:08:00.202  1016  2050 W ActivityManager: mDVFSHelper.acquire()
,08-30 17:08:00.222  1016  2050 D PersonaManager: isKioskContainerExistOnDevice
,08-30 17:08:00.222  1016  2050 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-30 17:08:00.222  1016  2050 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-30 17:08:00.222  1016  2050 D InputDispatcher: Focused application set to: xxxx
08-30 17:08:00.222  1016  2050 D InputDispatcher: Focus left window: 6765
,08-30 17:08:00.232  5644  5644 E MTPRx   : started activity for popup
,08-30 17:08:00.242  1016  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-30 17:08:00.242  1016  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-30 17:08:00.262  5644  5644 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-30 17:08:00.262  5644  5644 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-30 17:08:00.262  5644  5644 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-30 17:08:00.262  5644  5644 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 17:08:00.262  5644  5644 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 17:08:00.262  5644  5644 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 17:08:00.292  5644  5644 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-30 17:08:00.292  1016  1415 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-30 17:08:00.292  1016  1415 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-30 17:08:00.302  1016  1415 D InputDispatcher: Focused application set to: xxxx
,08-30 17:08:00.302  1016  1415 D InputDispatcher: Focus entered window: 6765
,08-30 17:08:00.302  1016  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-30 17:08:00.302  1016  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-30 17:08:00.302  1016  1134 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-30 17:08:00.312  1016  1134 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@3ffde634 attribute=null, token = android.os.BinderProxy@17537404
,08-30 17:08:00.362  5644  5644 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-30 17:08:00.362  5644  5644 D PhoneWindow: *FMB* installDecor mIsFloating : true
,08-30 17:08:00.372  5644  5644 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-30 17:08:00.392  6765  6765 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-30 17:08:00.392  6765  6765 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-30 17:08:00.392  6765  6765 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-30 17:08:00.392  6765  6765 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-30 17:08:00.392  1016  1028 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-30 17:08:00.392  1016  1028 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-30 17:08:00.392  1016  1028 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-30 17:08:00.392  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-30 17:08:00.392  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
,08-30 17:08:00.412  6765  6765 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-30 17:08:00.412  6765  6765 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-30 17:08:00.412  6765  6765 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@24449161 time:115922
,08-30 17:08:00.412  6765  6765 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3a7c942d Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@25878b0a, 16908290=android.view.AbsSavedState$1@25878b0a}, android:focusedViewId=100}]}]
08-30 17:08:00.412  6765  6765 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-30 17:08:00.412  6765  6765 V ActivityThread: updateVisibility : ActivityRecord{229f2d74 token=android.os.BinderProxy@24449161 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-30 17:08:00.412  6765  6765 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 17:08:00.412  6765  6765 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-30 17:08:00.422  1016  1134 D PersonaManager: isKioskContainerExistOnDevice
,08-30 17:08:00.642   296   296 E SMD     : DCD OFF
,08-30 17:08:00.662   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 17:08:00.692  1016  2050 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-30 17:08:00.692  1016  2050 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-30 17:08:00.692  1016  2050 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-30 17:08:00.692  1016  2050 D BatteryService: stay LED for fully charged
,08-30 17:08:00.692  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-30 17:08:00.692  1016  1016 I MotionRecognitionService: Plugged
,08-30 17:08:00.702  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-30 17:08:00.702  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-30 17:08:00.702  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-30 17:08:00.702  1431  1431 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-30 17:08:00.702  1431  1431 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-30 17:08:00.712  3155  3155 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-30 17:08:00.712  3155  3260 D HeadsetStateMachine: Disconnected process message: 10
,08-30 17:08:00.722  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
08-30 17:08:00.732  1177  1177 D SViewCoverView: level :100 plugged : 2
,08-30 17:08:00.732  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,08-30 17:08:00.732  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-30 17:08:00.732  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-30 17:08:01.292  1016  1056 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-30 17:08:01.662   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,08-30 17:08:02.662   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,08-30 17:08:03.202  1016  1042 W ActivityManager: mDVFSHelper.release()
,08-30 17:08:03.642   296   296 E SMD     : DCD OFF,
,08-30 17:08:03.662   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-30 17:08:04.492  1016  1095 V AlarmManager: waitForAlarm result :4
,08-30 17:08:04.512  1016  1095 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,08-30 17:08:04.522  1016  1016 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,08-30 17:08:04.522  1016  1016 V AlarmManagerEXT: <AppSync3 Whitelist>
,08-30 17:08:04.522  1016  1016 V AlarmManagerEXT: (AppSync) ### 0 added ###
,08-30 17:08:04.532  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-30 17:08:04.532  1177  1177 D KeyguardUpdateMonitor: handleTimeUpdate
,08-30 17:08:04.532  1969  1969 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-30 17:08:04.542  1177  1177 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-30 17:08:04.552  1177  1177 D SecKeyguardClockView: HomeTimezone(): 1
,08-30 17:08:04.552  1177  1177 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
08-30 17:08:04.552  1177  1177 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
08-30 17:08:04.552  1177  1177 I KeyguardEffectViewController: *** don't update sliding image ***
,08-30 17:08:04.552  1177  1177 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,08-30 17:08:04.712  1016  1514 I art     : Explicit concurrent mark sweep GC freed 33033(1863KB) AllocSpace objects, 20(320KB) LOS objects, 33% free, 24MB/36MB, paused 2.457ms total 152.340ms
,08-30 17:08:04.732  1016  1495 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 17:08:04.732  1016  1495 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,08-30 17:08:04.732  1016  1495 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:04.732  1016  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:04.732  1016  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:04.742  4791  4791 D ConnectivityManager: CallingUid : 10011, CallingPid : 4791
,08-30 17:08:04.742  1016  1514 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ],
08-30 17:08:04.742  1016  1128 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
08-30 17:08:04.742  1016  1128 D ConnectivityService: apparently satisfied.  currentScore=60
08-30 17:08:04.742  1016  1128 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
08-30 17:08:04.742  4791  6832 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290,
,08-30 17:08:04.752  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-30 17:08:04.752  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-30 17:08:04.752  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-30 17:08:04.772  1177  1177 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-30 17:08:04.822  4791  6833 W DriveInitializer: Background init thread started
,08-30 17:08:04.862   258   513 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-30 17:08:04.862   258   513 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 17:08:04.862  4791  6833 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-30 17:08:04.912  1016  2050 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 17:08:04.912  1016  2050 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-30 17:08:04.922  1016  2050 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:04.922  1016  2050 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:04.922  1016  2050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:04.932  1016  1498 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,08-30 17:08:04.942  1016  1498 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-30 17:08:04.942  4791  6833 W DriveInitializer: Background init thread ended
,08-30 17:08:04.962  1016  1029 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 17:08:04.962  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-30 17:08:04.962  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:04.962  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:04.962  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:04.982  4791  6841 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
08-30 17:08:04.982  4791  6841 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-30 17:08:05.012  1969  1969 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-30 17:08:05.052  1016  1042 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:05.052  1016  1042 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 17:08:05.052  1016  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:05.072  1969  1984 I art     : Explicit concurrent mark sweep GC freed 61349(3MB) AllocSpace objects, 12(192KB) LOS objects, 39% free, 10MB/17MB, paused 1.249ms total 78.359ms
,08-30 17:08:05.162  1016  1028 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 17:08:05.162  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-30 17:08:05.162  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:05.162  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 17:08:05.162  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:05.192  1016  1415 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 17:08:05.202  1016  1415 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,08-30 17:08:05.202  1016  1415 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:05.202  1016  1415 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:05.202  1016  1415 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:05.252  1016  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:08:05.252  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:05.252  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:05.252  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:05.262  1016  1415 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:08:05.272  1016  1415 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:05.272  1016  1415 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 17:08:05.272  1016  1415 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:05.342  1016  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:08:05.342  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:05.342  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:05.342  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
08-30 17:08:05.342  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-30 17:08:05.342  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:05.342  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:05.342  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:05.362  6846  6846 E Zygote  : MountEmulatedStorage()
,08-30 17:08:05.362  6846  6846 E Zygote  : v2
08-30 17:08:05.362  6846  6846 I libpersona: KNOX_SDCARD checking this for 10011
08-30 17:08:05.362  6846  6846 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:05.362  1016  1028 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6846 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
,08-30 17:08:05.372  6846  6846 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:08:05.372  6846  6846 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-30 17:08:05.372  6846  6846 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-30 17:08:05.402  6846  6846 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:05.402  6846  6846 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:05.422  6846  6846 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-30 17:08:05.422  6846  6846 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-30 17:08:05.462  6846  6846 I MultiDex: VM with version 2.1.0 has multidex support
,08-30 17:08:05.462  6846  6846 I MultiDex: install
08-30 17:08:05.462  6846  6846 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-30 17:08:05.492  6846  6846 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-30 17:08:05.552  6846  6846 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-30 17:08:05.552  6846  6846 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3a840e10: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-30 17:08:05.552  6846  6846 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-30 17:08:05.572  6846  6846 D ChimeraCfgMgr: Reading stored module config,
08-30 17:08:05.582  1016  1498 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
08-30 17:08:05.592  1016  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-30 17:08:05.602  6765  6822 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 17:08:05.602  6765  6822 I jxcore-log: 
08-30 17:08:05.602  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:05.602  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:05.602  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-30 17:08:05.602  6765  6822 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 17:08:05.602  6765  6822 I jxcore-log: 
08-30 17:08:05.612  1016  1514 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-30 17:08:05.612  1016  1514 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:05.612  1016  1514 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:05.612  1016  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-30 17:08:05.612  6765  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:08:05.612  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:05.612  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:05.612  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:05.612  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:05.612  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:08:05.612  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:08:05.612  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:08:05.612  6765  6822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 17:08:05.622  6765  6822 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 17:08:05.622  6765  6822 I jxcore-log: 
,08-30 17:08:05.622  6765  6822 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 17:08:05.622  6765  6822 I jxcore-log: 
,08-30 17:08:05.652  1969  1969 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=5e367c48-d344-4384-b4ad-f9f5042f1155
,08-30 17:08:05.682  6846  6864 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0,
,08-30 17:08:05.682  1016  1495 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-30 17:08:05.682  1016  1495 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-30 17:08:05.692  1016  1495 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:05.692  1016  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:05.692  1016  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:05.702  1969  1969 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-30 17:08:05.702  1969  1969 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-30 17:08:05.722  1016  1495 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:08:05.722  6846  6846 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-30 17:08:05.722  6846  6846 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-30 17:08:05.732  1016  1495 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:05.732  1016  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 17:08:05.732  1016  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:05.742  6846  6860 W art     : Suspending all threads took: 18.071ms
,08-30 17:08:05.752  6846  6860 I art     : Background partial concurrent mark sweep GC freed 1199(239KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 21.183ms total 73.914ms
,08-30 17:08:05.812   291   291 D WVCdm   : Instantiating CDM.
,08-30 17:08:05.812   291   702 I WVCdm   : CdmEngine::OpenSession
,08-30 17:08:05.812   291   702 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-30 17:08:05.852   291   702 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-30 17:08:05.862  4292  4353 I art     : Explicit concurrent mark sweep GC freed 1424(48KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 712us total 23.723ms
,08-30 17:08:05.872   291   702 W WVCdm   : Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,08-30 17:08:05.912  6846  6857 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-30 17:08:05.912  6846  6857 I System.out: (HTTPLog)-Static: isSBSettingEnabled false,
08-30 17:08:05.912  6846  6857 I System.out: (HTTPLog)-Static: isShipBuild true
08-30 17:08:05.912  6846  6857 I System.out: (HTTPLog)-Thread-1229-1046410109: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-30 17:08:05.912  6846  6857 I System.out: (HTTPLog)-Static: isSBSettingEnabled false,
,08-30 17:08:05.922   285  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-30 17:08:05.922   285  1011 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-30 17:08:05.932   291   702 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-30 17:08:05.932   291   291 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-30 17:08:05.932   291   291 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-30 17:08:05.932   291   291 I WVCdm   : CdmEngine::GenerateKeyRequest
,08-30 17:08:05.942   291   291 D WVCdm   : PrepareKeyRequest: nonce=1562605331
,08-30 17:08:05.952  1969  2145 W GCoreFlp: No location to return for getLastLocation()
,08-30 17:08:05.992  1016  1134 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:08:05.992  1016  1134 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:05.992  1016  1134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:05.992  1016  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:05.992  1016  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:08:06.002  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:06.002  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:06.002  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:06.002  1016  1498 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:08:06.002  1016  1498 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:06.002  1016  1498 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:06.002  1016  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:06.022  1969  2148 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-30 17:08:06.032  4791  6842 D UdcContextInitService: registered all accounts: true
,08-30 17:08:06.042  1969  2170 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-30 17:08:06.072  1016  3359 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-30 17:08:06.092  6846  6857 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-30 17:08:06.092  6846  6857 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6846, getuid(): 10011
,08-30 17:08:06.202  1016  2050 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-30 17:08:06.202  1016  2050 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-30 17:08:06.202  1016  2050 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:06.202  1016  2050 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:06.202  1016  2050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:06.372  6765  6822 D executeNativeTests: Running unit tests
,08-30 17:08:06.462  6765  6822 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:08:06.462  6765  6822 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33172d6b added. We now have 2 listener(s)
,08-30 17:08:06.462  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-30 17:08:06.462  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:08:06.462  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:08:06.462  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:08:06.462  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7720c8 added. We now have 2 listener(s)
08-30 17:08:06.462  6765  6822 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:08:06.462  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 17:08:06.472  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:08:06.472  6765  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:08:06.472  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:06.472  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:06.472  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:06.472  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:06.472  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:08:06.472  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:08:06.472  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:08:06.472  6765  6822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 17:08:06.472  6765  6822 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 17:08:06.472  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:06.482  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-30 17:08:06.482  6765  6822 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 17:08:06.482  6765  6822 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 17:08:06.482  6765  6822 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-30 17:08:06.482  6765  6822 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 17:08:06.482  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 17:08:06.482  6765  6822 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 17:08:06.482  6765  6822 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-30 17:08:06.482  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:06.482  6765  6822 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 17:08:06.482  6765  6822 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 17:08:06.482  6765  6822 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:06.482  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:06.482  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.482  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:08:06.482  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:08:06.482  6765  6822 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33172d6b removed from the list
08-30 17:08:06.482  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:06.482  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7720c8 removed from the list
08-30 17:08:06.482  6765  6822 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:06.482  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.482  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.482  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:06.482  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 17:08:06.482  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:06.482  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:06.482  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7720c8 not in the list
,08-30 17:08:06.492  6765  6822 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-30 17:08:06.492  6765  6822 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:06.492  6765  6822 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:06.492  6765  6822 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:06.492  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:06.492  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.492  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.492  6765  6822 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33172d6b not in the list
08-30 17:08:06.492  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:06.492  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7720c8 not in the list
08-30 17:08:06.492  6765  6822 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:06.492  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.492  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.492  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.492  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:06.492  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:06.492  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:06.492  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:06.492  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7720c8 not in the list
08-30 17:08:06.492  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 17:08:06.492  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 17:08:06.492  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 17:08:06.492  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 17:08:06.492  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 17:08:06.492  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 17:08:06.492  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 17:08:06.492  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 17:08:06.502  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 17:08:06.502  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 17:08:06.502  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 17:08:06.502  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 17:08:06.502  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 17:08:06.502  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 17:08:06.502  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 17:08:06.502  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 17:08:06.502  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 17:08:06.502  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 17:08:06.502  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 17:08:06.502  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 17:08:06.502  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 17:08:06.502  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 17:08:06.502  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 17:08:06.502  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 17:08:06.502  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 17:08:06.502  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 17:08:06.502  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 17:08:06.502  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 17:08:06.502  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 17:08:06.502  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 17:08:06.502  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 17:08:06.502  6765  6822 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:06.502  6765  6822 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:06.502  6765  6822 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:06.502  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:06.502  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.502  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.502  6765  6822 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33172d6b not in the list
08-30 17:08:06.502  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:06.502  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7720c8 not in the list
08-30 17:08:06.502  6765  6822 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:06.502  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.502  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.502  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.502  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.502  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:06.502  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:06.502  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:06.502  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7720c8 not in the list
08-30 17:08:06.502  6765  6822 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 17:08:06.502  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:08:06.502  6765  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:08:06.502  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:06.502  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:06.502  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:06.502  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:06.502  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:08:06.502  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:08:06.502  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:08:06.512  6765  6822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 17:08:06.512  6765  6822 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:08:06.512  6765  6822 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:08:06.512  6765  6822 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 17:08:06.512  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 17:08:06.512  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:08:06.512  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 17:08:06.512  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:06.512  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:06.512  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 17:08:06.522  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 17:08:06.532  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 17:08:06.532  6765  6822 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-30 17:08:06.532  6765  6822 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-30 17:08:06.532  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 17:08:06.532  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 17:08:06.532  6765  6822 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 17:08:06.542  3155  3173 D BtGatt.GattService: registerClient() - UUID=4ded3504-f2ee-4fe4-9f38-8cb12c761908
,08-30 17:08:06.582  3155  3252 D BtGatt.GattService: onClientRegistered() - UUID=4ded3504-f2ee-4fe4-9f38-8cb12c761908, clientIf=6
,08-30 17:08:06.592  6765  6777 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-30 17:08:06.592  3155  3342 D BtGatt.GattService: start scan with filters
,08-30 17:08:06.592  3155  3258 D BtGatt.ScanManager: handling starting scan
,08-30 17:08:06.592  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 17:08:06.592  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 17:08:06.592  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 17:08:06.592  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 17:08:06.592  3155  3258 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336d367
,08-30 17:08:06.602  3155  3252 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-30 17:08:06.602  3155  3252 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:08:06.602  3155  3258 D BtGatt.ScanManager: allow scan with filters
,08-30 17:08:06.602  3155  3258 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-30 17:08:06.602  3155  3258 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-30 17:08:06.602  6765  6822 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 17:08:06.602  3155  3252 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-30 17:08:06.602  3155  3252 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:08:06.602  6765  6822 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 17:08:06.602  6765  6765 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 17:08:06.602  3155  3258 D BtGatt.ScanManager: Starting BLE batch scan
,08-30 17:08:06.602  3155  3258 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-30 17:08:06.602  3155  3252 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-30 17:08:06.612  3155  3252 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:08:06.612  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 17:08:06.612  3155  3252 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-30 17:08:06.612  3155  3252 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:08:06.612  6765  6822 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 17:08:06.612  6765  6822 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 17:08:06.612  6765  6822 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 17:08:06.612  6765  6822 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 17:08:06.612  6765  6822 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 17:08:06.622  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.622  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 17:08:06.622  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 17:08:06.622  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 17:08:06.622  6765  6822 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 17:08:06.622  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 17:08:06.622  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-30 17:08:06.622  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 17:08:06.622  3155  3341 D BtGatt.GattService: stopScan() - queue size =1
,08-30 17:08:06.622  3155  3342 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-30 17:08:06.622  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:08:06.622  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 17:08:06.622  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 17:08:06.622  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 17:08:06.622  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 17:08:06.622  3155  3258 D BtGatt.ScanManager: filter size is 1
08-30 17:08:06.622  3155  3258 D BtGatt.ScanManager: delete FilterIndex - 3
08-30 17:08:06.622  6765  6822 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 17:08:06.622  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
08-30 17:08:06.622  6765  6822 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
08-30 17:08:06.622  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 17:08:06.622  3155  3252 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-30 17:08:06.622  3155  3252 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:08:06.622  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:08:06.632  3155  3258 D BtGatt.ScanManager: stopping BLe Batch
08-30 17:08:06.632  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:06.632  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.632  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-30 17:08:06.632  6765  6822 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33172d6b not in the list
08-30 17:08:06.632  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:06.632  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7720c8 not in the list
08-30 17:08:06.632  6765  6822 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:06.632  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:06.632  6765  6765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:08:06.632  6765  6765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:08:06.632  6765  6765 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 17:08:06.632  6765  6822 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-30 17:08:06.632  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:08:06.632  3155  3252 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-30 17:08:06.632  3155  3252 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:08:06.632  3155  3258 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-30 17:08:06.632  6765  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:08:06.632  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:06.632  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:06.632  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:06.632  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:06.632  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:08:06.632  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:08:06.632  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:08:06.632  3155  3252 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-30 17:08:06.632  3155  3252 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:08:06.642  6765  6822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 17:08:06.642  6765  6822 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:08:06.642  6765  6822 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:08:06.642  6765  6822 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 17:08:06.642  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 17:08:06.642  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:08:06.642  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 17:08:06.642   296   296 E SMD     : DCD OFF,
,08-30 17:08:06.642  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:06.642  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 17:08:06.642  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:06.652  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 17:08:06.652  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 17:08:06.652  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 17:08:06.652  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 17:08:06.652  6765  6822 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 17:08:06.652  3155  3163 D BtGatt.GattService: registerClient() - UUID=590867a7-e3a8-464d-83ca-4871a197962d
,08-30 17:08:06.702  3155  3252 D BtGatt.GattService: onClientRegistered() - UUID=590867a7-e3a8-464d-83ca-4871a197962d, clientIf=6
,08-30 17:08:06.702  6765  6779 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-30 17:08:06.702  3155  3173 D BtGatt.GattService: start scan with filters
,08-30 17:08:06.702  3155  3258 D BtGatt.ScanManager: handling starting scan
,08-30 17:08:06.702  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 17:08:06.702  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 17:08:06.702  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 17:08:06.702  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 17:08:06.702  3155  3252 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-30 17:08:06.702  3155  3252 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:08:06.702  3155  3258 D BtGatt.ScanManager: allow scan with filters
08-30 17:08:06.702  3155  3258 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-30 17:08:06.702  3155  3258 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-30 17:08:06.702  3155  3252 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-30 17:08:06.702  3155  3252 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:08:06.702  3155  3258 D BtGatt.ScanManager: Starting BLE batch scan
08-30 17:08:06.702  3155  3258 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-30 17:08:06.712  3155  3252 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-30 17:08:06.712  3155  3252 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:08:06.712  6765  6822 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 17:08:06.712  6765  6765 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 17:08:06.712  6765  6822 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 17:08:06.712  3155  3252 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-30 17:08:06.712  3155  3252 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:08:06.712  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 17:08:06.722  6765  6822 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 17:08:06.722  6765  6822 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 17:08:06.722  6765  6822 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 17:08:06.722  6765  6822 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 17:08:06.722  6765  6822 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 17:08:06.722  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.722  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 17:08:06.722  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-30 17:08:06.722  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 17:08:06.722  6765  6822 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 17:08:06.722  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 17:08:06.722  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 17:08:06.722  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 17:08:06.722  3155  3342 D BtGatt.GattService: stopScan() - queue size =1
,08-30 17:08:06.722  3155  3258 D BtGatt.ScanManager: filter size is 1
,08-30 17:08:06.722  3155  3258 D BtGatt.ScanManager: delete FilterIndex - 4
,08-30 17:08:06.722  3155  3252 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-30 17:08:06.722  3155  3252 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:08:06.722  3155  3163 D BtGatt.GattService: unregisterClient() - clientIf=6
08-30 17:08:06.722  3155  3258 D BtGatt.ScanManager: stopping BLe Batch
08-30 17:08:06.732  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:08:06.732  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 17:08:06.732  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 17:08:06.732  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 17:08:06.732  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 17:08:06.732  6765  6822 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 17:08:06.732  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 17:08:06.732  6765  6822 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 17:08:06.732  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 17:08:06.732  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 17:08:06.732  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 17:08:06.732  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.732  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:08:06.732  6765  6822 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33172d6b not in the list,
08-30 17:08:06.732  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:06.732  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7720c8 not in the list
08-30 17:08:06.732  6765  6822 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:06.732  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.732  6765  6765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:08:06.732  6765  6765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 17:08:06.732  6765  6765 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 17:08:06.732  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.732  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.732  3155  3252 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-30 17:08:06.732  3155  3252 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:08:06.732  3155  3258 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-30 17:08:06.732  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:06.732  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:06.732  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:06.732  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7720c8 not in the list
,08-30 17:08:06.732  3155  3252 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-30 17:08:06.732  3155  3252 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:08:06.732  6765  6822 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-30 17:08:06.742  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:08:06.742  6765  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:08:06.742  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:06.742  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:06.742  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:06.742  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:06.742  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:08:06.742  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:08:06.742  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:08:06.742  6765  6822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 17:08:06.742  6765  6822 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:08:06.742  6765  6822 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:08:06.742  6765  6822 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 17:08:06.742  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 17:08:06.742  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:08:06.742  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 17:08:06.742  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:06.752  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 17:08:06.752  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:06.752  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 17:08:06.752  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 17:08:06.762  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
08-30 17:08:06.762  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 17:08:06.762  6765  6822 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 17:08:06.772  3155  3173 D BtGatt.GattService: registerClient() - UUID=5b97f7b7-5de0-4801-8ba0-1f5bb5d93ff8,
,08-30 17:08:06.812  3155  3252 D BtGatt.GattService: onClientRegistered() - UUID=5b97f7b7-5de0-4801-8ba0-1f5bb5d93ff8, clientIf=6
,08-30 17:08:06.812  6765  6811 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-30 17:08:06.812  3155  3342 D BtGatt.GattService: start scan with filters
,08-30 17:08:06.812  3155  3258 D BtGatt.ScanManager: handling starting scan
,08-30 17:08:06.812  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 17:08:06.812  3155  3252 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-30 17:08:06.812  3155  3252 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:08:06.812  3155  3258 D BtGatt.ScanManager: allow scan with filters
08-30 17:08:06.812  3155  3258 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-30 17:08:06.812  3155  3258 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-30 17:08:06.812  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-30 17:08:06.812  3155  3252 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-30 17:08:06.812  3155  3252 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:08:06.812  3155  3258 D BtGatt.ScanManager: Starting BLE batch scan
08-30 17:08:06.812  3155  3258 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-30 17:08:06.822  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-30 17:08:06.822  3155  3252 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-30 17:08:06.822  3155  3252 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:08:06.822  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 17:08:06.822  3155  3252 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-30 17:08:06.822  3155  3252 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:08:06.822  6765  6822 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 17:08:06.822  6765  6765 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 17:08:06.822  6765  6822 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 17:08:06.832  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 17:08:06.832  6765  6822 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 17:08:06.832  6765  6822 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:06.832  6765  6822 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 17:08:06.832  6765  6822 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 17:08:06.832  6765  6822 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 17:08:06.832  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.832  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 17:08:06.832  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-30 17:08:06.832  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 17:08:06.832  6765  6822 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 17:08:06.832  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 17:08:06.832  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 17:08:06.832  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 17:08:06.832  3155  3173 D BtGatt.GattService: stopScan() - queue size =1
,08-30 17:08:06.832  3155  3258 D BtGatt.ScanManager: filter size is 1
,08-30 17:08:06.832  3155  3258 D BtGatt.ScanManager: delete FilterIndex - 5
08-30 17:08:06.832  3155  3342 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-30 17:08:06.842  3155  3252 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-30 17:08:06.842  3155  3252 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:08:06.842  3155  3258 D BtGatt.ScanManager: stopping BLe Batch
,08-30 17:08:06.842  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:08:06.842  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 17:08:06.842  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 17:08:06.842  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 17:08:06.842  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 17:08:06.842  6765  6822 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 17:08:06.842  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 17:08:06.842  6765  6822 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 17:08:06.842  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 17:08:06.842  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 17:08:06.842  3155  3252 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-30 17:08:06.842  3155  3252 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:08:06.842  3155  3258 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-30 17:08:06.842  6765  6765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:08:06.842  6765  6822 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:06.842  6765  6822 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 17:08:06.842  6765  6822 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:06.842  6765  6822 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:06.842  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:06.842  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.842  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:08:06.842  6765  6822 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33172d6b not in the list
08-30 17:08:06.842  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:06.842  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7720c8 not in the list
08-30 17:08:06.842  6765  6822 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:06.842  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:06.842  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.842  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:06.842  3155  3252 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-30 17:08:06.842  3155  3252 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:08:06.842  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:06.842  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:06.842  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:06.842  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7720c8 not in the list
,08-30 17:08:06.842  6765  6765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:08:06.842  6765  6822 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-30 17:08:06.842  6765  6765 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 17:08:06.842  6765  6822 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:06.842  6765  6822 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:06.842  6765  6822 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:06.842  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:06.852  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.852  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.852  6765  6822 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33172d6b not in the list
08-30 17:08:06.852  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:06.852  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7720c8 not in the list
08-30 17:08:06.852  6765  6822 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:06.852  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.852  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.852  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.852  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:06.852  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 17:08:06.852  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:06.852  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:06.852  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7720c8 not in the list
,08-30 17:08:06.852  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-30 17:08:06.852  6765  6822 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:06.852  6765  6822 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:06.852  6765  6822 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:06.852  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 17:08:06.852  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.852  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.852  6765  6822 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33172d6b not in the list
08-30 17:08:06.852  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:06.852  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7720c8 not in the list
08-30 17:08:06.852  6765  6822 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:06.852  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.852  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.852  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.852  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.852  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 17:08:06.852  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:06.852  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:06.852  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7720c8 not in the list
08-30 17:08:06.852  6765  6822 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-30 17:08:06.852  6765  6822 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:06.852  6765  6822 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:06.852  6765  6822 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:06.852  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:06.852  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.852  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.852  6765  6822 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33172d6b not in the list
08-30 17:08:06.852  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:06.852  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7720c8 not in the list
08-30 17:08:06.852  6765  6822 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:06.852  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.852  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.852  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.852  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.852  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:06.852  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:06.852  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:06.852  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7720c8 not in the list
08-30 17:08:06.852  6765  6822 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-30 17:08:06.852  6765  6822 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:06.852  6765  6822 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:06.852  6765  6822 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:06.852  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:06.852  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.852  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.852  6765  6822 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33172d6b not in the list
08-30 17:08:06.852  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:06.852  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7720c8 not in the list
08-30 17:08:06.852  6765  6822 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:06.852  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.852  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.852  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.852  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.862  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:06.862  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:06.862  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:06.862  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7720c8 not in the list
08-30 17:08:06.862  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 17:08:06.862  6765  6822 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 17:08:06.862  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 17:08:06.862  6765  6822 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 17:08:06.862  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 17:08:06.862  6765  6822 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 17:08:06.862  6765  6822 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 17:08:06.862  6765  6822 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:06.862  6765  6822 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:06.862  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:06.862  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.862  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:06.862  6765  6822 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33172d6b not in the list
08-30 17:08:06.862  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:06.862  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7720c8 not in the list
08-30 17:08:06.862  6765  6822 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:06.862  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.862  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.862  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.862  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.862  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:06.862  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:06.862  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:06.862  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7720c8 not in the list
08-30 17:08:06.862  6765  6822 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 17:08:06.862  6765  6822 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 17:08:06.862  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 17:08:06.862  6765  6822 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 17:08:06.862  6765  6822 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-30 17:08:06.862  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 17:08:06.862  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 17:08:06.862  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 17:08:06.862  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 17:08:06.862  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 17:08:06.862  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 17:08:06.862  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 17:08:06.862  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 17:08:06.862  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 17:08:06.862  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 17:08:06.862  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08,-30 17:08:06.862  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 17:08:06.862  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 17:08:06.862  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 17:08:06.862  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 17:08:06.862  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 17:08:06.862  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 17:08:06.862  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 17:08:06.862  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 17:08:06.862  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 17:08:06.862  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 17:08:06.862  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 17:08:06.862  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 17:08:06.862  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 17:08:06.862  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 17:08:06.862  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-30 17:08:06.862  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 17:08:06.862  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 17:08:06.862  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 17:08:06.862  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 17:08:06.862  6765  6822 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,08-30 17:08:06.862  6765  6822 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 17:08:06.862  6765  6822 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-30 17:08:06.862  6765  6822 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 17:08:06.862  6765  6822 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 17:08:06.862  6765  6822 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-30 17:08:06.862  6765  6822 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-30 17:08:06.862  6765  6822 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 17:08:06.862  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-30 17:08:06.872  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-30 17:08:06.872  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-30 17:08:06.872  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-30 17:08:06.872  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-30 17:08:06.872  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-30 17:08:06.872  6765  6822 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,08-30 17:08:06.872  6765  6822 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 17:08:06.872  6765  6822 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-30 17:08:06.872  6765  6822 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:06.872  6765  6822 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:06.872  6765  6822 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:06.872  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:06.872  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.872  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.872  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-30 17:08:06.872  6765  6878 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1316)
08-30 17:08:06.872  6765  6822 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33172d6b not in the list
08-30 17:08:06.872  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:06.872  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7720c8 not in the list
08-30 17:08:06.872  6765  6822 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:06.872  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.872  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.872  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.872  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:06.872  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:06.872  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:06.872  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:06.872  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7720c8 not in the list
08-30 17:08:06.872  6765  6879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1316
,08-30 17:08:06.872  6765  6822 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-30 17:08:06.872  6765  6822 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:06.872  6765  6822 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:06.872  6765  6822 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 17:08:06.872  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:06.872  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.872  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.872  6765  6822 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33172d6b not in the list
08-30 17:08:06.872  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:06.872  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7720c8 not in the list
08-30 17:08:06.872  6765  6822 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:06.872  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.872  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.872  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.872  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:06.872  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:06.882  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:06.882  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:06.882  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7720c8 not in the list
,08-30 17:08:06.882  6765  6822 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-30 17:08:06.882  6765  6822 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:06.882  6765  6822 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:06.882  6765  6822 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:06.882  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:06.882  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.882  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.882  6765  6822 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33172d6b not in the list
08-30 17:08:06.882  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:06.882  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7720c8 not in the list
08-30 17:08:06.882  6765  6822 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:06.882  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.882  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.882  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.882  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:06.882  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:06.882  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 17:08:06.882  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:06.882  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7720c8 not in the list
,08-30 17:08:06.882  6765  6822 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-30 17:08:06.882  6765  6822 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-30 17:08:06.882  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 17:08:06.882  6765  6822 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-30 17:08:06.882  6765  6822 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 17:08:06.882  6765  6822 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-30 17:08:06.882  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 17:08:06.882  6765  6822 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-30 17:08:06.882  6765  6822 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 17:08:06.882  6765  6822 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 17:08:06.882  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 17:08:06.882  6765  6822 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-30 17:08:06.882  6765  6822 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:06.882  6765  6822 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 17:08:06.882  6765  6822 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:06.882  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:06.882  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.882  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.882  6765  6822 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33172d6b not in the list
08-30 17:08:06.882  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:06.882  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7720c8 not in the list
08-30 17:08:06.882  6765  6822 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:06.882  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:08:06.882  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.882  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.882  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.882  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:06.882  6765  6878 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
08-30 17:08:06.882  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:06.882  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:06.882  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7720c8 not in the list
08-30 17:08:06.882  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:06.882  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.882  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.882  6765  6822 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33172d6b not in the list
08-30 17:08:06.882  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:06.882  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7720c8 not in the list
08-30 17:08:06.882  6765  6822 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:06.882  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.882  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.882  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:06.882  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7720c8 not in the list
,08-30 17:08:06.882  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:06.882  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.882  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.882  6765  6822 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33172d6b not in the list
,08-30 17:08:06.882  6765  6878 D BluetoothSocket: connect(): myUserId = 0
08-30 17:08:06.882  6765  6822 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:06.882  6765  6878 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 17:08:06.882  6765  6822 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:06.882  6765  6822 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:06.882  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:06.882  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.882  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.882  6765  6822 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33172d6b not in the list
08-30 17:08:06.882  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:06.882  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7720c8 not in the list
08-30 17:08:06.882  6765  6822 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:06.882  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.882  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.882  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.882  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.882  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 17:08:06.882  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:06.882  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:06.882  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7720c8 not in the list
08-30 17:08:06.892  3155  3341 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:08:06.892  6765  6822 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 17:08:06.892  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:08:06.892  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 17:08:06.892  6765  6878 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[105]}
08-30 17:08:06.892  6765  6822 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 17:08:06.892  6765  6822 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 17:08:06.892  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 17:08:06.892  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 17:08:06.892  6765  6765 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 17:08:06.892  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:06.892  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 17:08:06.892  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 17:08:06.892  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 17:08:06.892  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.892  6765  6822 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 17:08:06.892  6765  6765 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 17:08:06.892  6765  6822 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33172d6b not in the list
08-30 17:08:06.892  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:06.892  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 17:08:06.892  6765  6822 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 17:08:06.892  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 17:08:06.892  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.892  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:06.892  6765  6822 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 17:08:06.892  6765  6765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:08:06.892  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7720c8 not in the list
08-30 17:08:06.892  6765  6822 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:06.892  6765  6765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 17:08:06.892  6765  6765 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 17:08:06.892  6765  6822 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:06.892  6765  6822 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:06.892  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:06.892  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.892  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.892  6765  6822 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33172d6b not in the list
08-30 17:08:06.892  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:06.892  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7720c8 not in the list
08-30 17:08:06.892  6765  6822 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:06.892  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.892  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.892  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.892  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.892  6765  6880 D BluetoothSocket: bindListen(): myUserId = 0
08-30 17:08:06.892  6765  6880 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 17:08:06.892  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-30 17:08:06.892  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:06.892  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:06.892  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7720c8 not in the list
08-30 17:08:06.892  6765  6822 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-30 17:08:06.892  6765  6822 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 17:08:06.892  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 17:08:06.892  6765  6822 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-30 17:08:06.892  6765  6822 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:06.892  6765  6822 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:06.892  6765  6822 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:06.892  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:06.892  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.892  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.892  6765  6822 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33172d6b not in the list
,08-30 17:08:06.892  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:06.892  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7720c8 not in the list
08-30 17:08:06.892  6765  6822 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:06.892  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.892  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.892  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.892  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.902  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:06.902  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 17:08:06.902  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:06.902  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7720c8 not in the list
,08-30 17:08:06.902  6765  6880 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
08-30 17:08:06.902  6765  6880 D BluetoothSocket: bindListen(), new LocalSocket 
08-30 17:08:06.902  6765  6880 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-30 17:08:06.902  6765  6880 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@e21566a
08-30 17:08:06.902  6765  6880 D BluetoothSocket: channel: 6
08-30 17:08:06.902  6765  6880 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2c82475b, channel: 6, state: LISTENING
08-30 17:08:06.902  6765  6880 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2c82475b, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@e21566a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@30984bf8mSocket: android.net.LocalSocket@11ce18d1 impl:android.net.LocalSocketImpl@22f66f36 fd:FileDescriptor[106]
08-30 17:08:06.902  6765  6880 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@11ce18d1 impl:android.net.LocalSocketImpl@22f66f36 fd:FileDescriptor[106]
08-30 17:08:06.902  6765  6880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-30 17:08:06.902  6765  6880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 17:08:06.902  6765  6880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 17:08:06.902  6765  6765 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 17:08:06.902  6765  6822 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:06.902  6765  6822 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:06.902  6765  6822 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:06.902  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:06.902  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.902  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.902  6765  6822 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33172d6b not in the list
08-30 17:08:06.902  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:06.902  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7720c8 not in the list
08-30 17:08:06.902  6765  6822 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:06.902  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.902  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.902  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.902  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:06.902  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:06.902  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:06.902  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:06.902  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7720c8 not in the list
08-30 17:08:06.902  6765  6822 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:06.902  6765  6822 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:06.902  6765  6822 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:06.902  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:06.902  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.902  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.902  6765  6822 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33172d6b not in the list
,08-30 17:08:06.902  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:06.902  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7720c8 not in the list
08-30 17:08:06.902  6765  6822 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:06.902  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.902  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.902  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:06.902  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:06.902  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:06.902  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:06.902  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:06.902  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7720c8 not in the list
08-30 17:08:06.902  6765  6822 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-30 17:08:06.902  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 17:08:06.902  6765  6822 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-30 17:08:06.902  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 17:08:06.902  6765  6822 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-30 17:08:06.902  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-30 17:08:06.912  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 17:08:06.912  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-30 17:08:06.912  6765  6822 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-30 17:08:06.912  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 17:08:06.912  6765  6822 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-30 17:08:06.912  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 17:08:06.912  6765  6822 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-30 17:08:06.912  6765  6822 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-30 17:08:06.912  6765  6822 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-30 17:08:06.912  6765  6822 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-30 17:08:06.912  6765  6822 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-30 17:08:06.912  6765  6822 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-30 17:08:06.912  6765  6822 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-30 17:08:06.912  6765  6822 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-30 17:08:06.912  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:08:06.912  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3293fe37 added. We now have 2 listener(s)
08-30 17:08:06.912  6765  6822 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:08:06.912  6765  6822 D BluetoothAdapter: enable()
,08-30 17:08:06.912  6765  6822 D BluetoothAdapter: enable(): BT is already enabled..!
,08-30 17:08:06.912  1016  1497 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-30 17:08:06.912  1016  1497 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-30 17:08:06.912  1016  1497 D SecContentProvider2: mCursor = null
,08-30 17:08:06.912  1016  1497 D WifiService: setWifiEnabled: true pid=6765, uid=10171
,08-30 17:08:06.922  1016  1497 W ActivityManager: Permission Denial: getCurrentUser() from pid=6765, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-30 17:08:06.922  1016  1497 W WifiService: Failed getting userId using ActivityManagerNative
08-30 17:08:06.922  1016  1497 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6765, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-30 17:08:06.922  1016  1497 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-30 17:08:06.922  1016  1497 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-30 17:08:06.922  1016  1497 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-30 17:08:06.922  1016  1497 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-30 17:08:06.922  1016  1497 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-30 17:08:06.922  1016  1497 D SettingsProvider: name = wifi_on
,08-30 17:08:06.922  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-30 17:08:06.922  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@36022fa4 added. We now have 3 listener(s)
08-30 17:08:06.922  6765  6822 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:08:06.932  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 17:08:06.932  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@264a710d added. We now have 4 listener(s)
08-30 17:08:06.932  6765  6822 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:08:06.932  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 17:08:06.932  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@393248c2 added. We now have 5 listener(s)
08-30 17:08:06.932  6765  6822 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:08:06.932  1016  1495 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-30 17:08:06.932  1016  1495 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-30 17:08:06.932  1016  1495 D SecContentProvider2: mCursor = null
,08-30 17:08:06.932  1016  1495 D WifiService: setWifiEnabled: false pid=6765, uid=10171
,08-30 17:08:06.932  1016  1495 D SettingsProvider: name = wifi_on
,08-30 17:08:06.942  1016  1126 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-30 17:08:06.942  6765  6822 D BluetoothAdapter: disable()
08-30 17:08:06.942  1347  1347 I wpa_supplicant: reset timer : RESET_TIMER 0
08-30 17:08:06.942  1347  1347 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-30 17:08:06.942  1016  1028 D SettingsProvider: name = bluetooth_on
08-30 17:08:06.942  1347  1347 I wpa_supplicant: P2P: Current p2p state = IDLE
,08-30 17:08:06.942  1347  1347 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds,
,08-30 17:08:06.952  1016  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,08-30 17:08:06.962  3155  3249 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-30 17:08:06.962  3155  3249 D BluetoothAdapterProperties: Setting state to 13
08-30 17:08:06.962  3155  3249 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 17:08:06.962  3155  3249 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-30 17:08:06.962  3155  3249 D BluetoothAdapterService: updateAdapterState state is 13
,08-30 17:08:06.962  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:08:06.962  1016  1415 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 17:08:06.962  1016  1415 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-30 17:08:06.962  1016  1415 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:06.962  1016  1415 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:06.962  1016  1415 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:06.972  1016  1126 E WifiNative-wlan0: do suspend true
,08-30 17:08:06.972  3155  3155 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-30 17:08:06.972  3155  3249 D BluetoothAdapterService: Autoconnection is available 
,08-30 17:08:06.972  3155  3249 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-30 17:08:06.972  3155  3249 D BluetoothAdapterService: terminating service from this receiver
,08-30 17:08:06.972  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-30 17:08:06.972  3155  3155 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@286fdde6, channel: 19, state: LISTENING
08-30 17:08:06.972  3155  3155 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@286fdde6, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@a9b7b0e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1321bf27mSocket: android.net.LocalSocket@2cc675d4 impl:android.net.LocalSocketImpl@3e5ef37d fd:FileDescriptor[74]
08-30 17:08:06.972  3155  3155 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2cc675d4 impl:android.net.LocalSocketImpl@3e5ef37d fd:FileDescriptor[74]
,08-30 17:08:06.972  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:06.972  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:06.972  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:06.972  3155  3249 D BluetoothAdapterProperties: onBluetoothDisable()
,08-30 17:08:06.972  3155  3249 D BluetoothAdapterProperties: mDiscovering is false
,08-30 17:08:06.982  1016  1514 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-30 17:08:06.982  3155  3249 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-30 17:08:06.982  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 17:08:06.982  6765  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:08:06.982  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:06.982  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:06.982  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:06.982  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:08:06.982  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:08:06.982  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:08:06.982  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:08:06.982  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 17:08:06.982  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:08:06.982  1016  1016 I InputMethodManagerService: [BT Setting State] State =13
08-30 17:08:06.982  6765  6822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 17:08:06.982  6765  6822 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 17:08:06.982  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:06.992  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:06.992  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-30 17:08:06.992  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-30 17:08:06.992  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:08:06.992  1177  1177 D BluetoothTile:  getBluetoothState : 13,
,08-30 17:08:07.002  1177  1755 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 17:08:07.002  1866  1866 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 17:08:07.002  1177  1755 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 17:08:07.002  1016  1497 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 17:08:07.002  1016  1028 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-30 17:08:07.002  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-30 17:08:07.002  1177  1755 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-30 17:08:07.012  1016  1042 D ActivityManager: startProcessLocked calleePkgName: com.android.settings, hostingType: broadcast
,08-30 17:08:07.012  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:07.012  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:07.012  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:07.012  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:07.012  6765  6765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 17:08:07.012  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:07.012  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:07.012  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:07.012  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:07.012  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:08:07.012  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:08:07.012  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:08:07.012  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:08:07.012  6765  6765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 17:08:07.012  6765  6765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 17:08:07.012  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:07.022  6883  6883 E Zygote  : MountEmulatedStorage(),
08-30 17:08:07.022  1016  1042 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6883 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-30 17:08:07.022  6883  6883 E Zygote  : v2,
08-30 17:08:07.022  6883  6883 I libpersona: KNOX_SDCARD checking this for 1000
08-30 17:08:07.022  6883  6883 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 17:08:07.022  6883  6883 I libpersona: KNOX_SDCARD not a persona
08-30 17:08:07.022  6883  6883 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 17:08:07.032  1016  1536 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 17:08:07.032  1016  1536 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-30 17:08:07.032  6883  6883 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:08:07.032  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-30 17:08:07.032  1016  1536 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:07.032  1016  1536 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:07.032  1016  1536 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:07.032  3155  3252 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-30 17:08:07.032  3155  3252 D BluetoothAdapterProperties: Scan Mode:20
08-30 17:08:07.032  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:07.032  3155  3249 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-30 17:08:07.032  3155  3249 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
08-30 17:08:07.042  3155  3249 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-30 17:08:07.042  3155  3249 E bt-btif : cmd socket is not created
08-30 17:08:07.042  3155  3273 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-30 17:08:07.042  3155  3273 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-30 17:08:07.042  3155  5218 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 17:08:07.042  3155  3273 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 17:08:07.042  3155  3273 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 17:08:07.042  3155  3273 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-30 17:08:07.042  6765  6878 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1804a210, channel: -1, state: INIT
08-30 17:08:07.042  6765  6878 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1804a210, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@bba1109, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@25602f0emSocket: android.net.LocalSocket@2b1e7d2f impl:android.net.LocalSocketImpl@2779cf3c fd:FileDescriptor[105]
08-30 17:08:07.042  6765  6878 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2b1e7d2f impl:android.net.LocalSocketImpl@2779cf3c fd:FileDescriptor[105]
08-30 17:08:07.042  3155  3249 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 17:08:07.042  6765  6878 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1316)
,08-30 17:08:07.042  3155  3155 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@c4bf272, channel: 5, state: LISTENING
08-30 17:08:07.042  3155  3155 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@c4bf272, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1e85d92f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@166126c3mSocket: android.net.LocalSocket@1eff1b40 impl:android.net.LocalSocketImpl@6c4a79 fd:FileDescriptor[76]
08-30 17:08:07.042  3155  3155 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1eff1b40 impl:android.net.LocalSocketImpl@6c4a79 fd:FileDescriptor[76]
08-30 17:08:07.042  3155  3155 I BtOppRfcommListener: stopping Accept Thread
08-30 17:08:07.042  3155  3155 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3f62c3be, channel: 12, state: LISTENING
08-30 17:08:07.042  3155  3155 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3f62c3be, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@10825441, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@37a56c1fmSocket: android.net.LocalSocket@175aab6c impl:android.net.LocalSocketImpl@135e1535 fd:FileDescriptor[80]
08-30 17:08:07.042  3155  3155 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@175aab6c impl:android.net.LocalSocketImpl@135e1535 fd:FileDescriptor[80]
,08-30 17:08:07.052  3155  5218 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-30 17:08:07.052  3155  3155 V BluetoothOppManager: cleanUp...
,08-30 17:08:07.062  6883  6883 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:07.062  6883  6883 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:07.082  6883  6883 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-30 17:08:07.082  6883  6883 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-30 17:08:07.082  6883  6883 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-30 17:08:07.082  6883  6883 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 17:08:07.082  6883  6883 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 17:08:07.082  6883  6883 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 17:08:07.122  6883  6883 D MySettingsProvider: DatabaseHelper(Context context):DATABASE_VERSION=1
,08-30 17:08:07.122  6883  6883 E SQLiteLog: (283) recovered 10 frames from WAL file /data/data/com.android.settings/databases/mysettings.db-wal
,08-30 17:08:07.122  6883  6883 D MySettingsProvider: onCreate():(mDB == null)? false:true  =true
,08-30 17:08:07.152  6883  6883 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 17:08:07.152  1016  1497 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-30 17:08:07.152  1016  1497 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-30 17:08:07.152  1016  1497 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:07.152  1016  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:07.152  1016  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-30 17:08:07.182  1016  1536 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-30 17:08:07.182  1016  1536 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-30 17:08:07.182  1016  1536 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:07.182  1016  1536 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:07.182  1016  1536 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:07.182  6883  6883 D LocalBluetoothProfileManager: PANU : true
,08-30 17:08:07.192  6883  6883 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,08-30 17:08:07.192  1016  1415 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-30 17:08:07.192  1016  1415 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-30 17:08:07.192  1016  1415 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:07.192  1016  1415 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 17:08:07.192  1016  1415 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-30 17:08:07.192  6883  6883 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-30 17:08:07.192  6883  6883 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-30 17:08:07.192  6883  6883 D DockEventReceiver: finishStartingService: stopping service
,08-30 17:08:07.202  6883  6883 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 17:08:07.202  6883  6883 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 17:08:07.202  6883  6883 D PanProfile: Bluetooth service connected
,08-30 17:08:07.202  6883  6883 D Bluetoothsap: BluetoothSAP Proxy object connected
08-30 17:08:07.202  6883  6883 D SapProfile: Bluetooth service connected
,08-30 17:08:07.202  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:08:07.202  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-30 17:08:07.202  6883  6883 D Bluetoothsap: getConnectedDevices()
,08-30 17:08:07.202  1016  1028 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-30 17:08:07.202  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:07.202  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:07.202  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:07.202  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:07.222  6906  6906 E Zygote  : MountEmulatedStorage()
,08-30 17:08:07.222  6906  6906 E Zygote  : v2
08-30 17:08:07.222  6906  6906 I libpersona: KNOX_SDCARD checking this for 10055
08-30 17:08:07.222  6906  6906 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:07.222  6906  6906 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 17:08:07.222  1016  1028 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6906 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a,
,08-30 17:08:07.222  6906  6906 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 17:08:07.222  1016  1415 I ActivityManager: Killing 6473:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-30 17:08:07.222  6906  6906 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:08:07.242  3155  3273 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-30 17:08:07.242  3155  3273 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 17:08:07.242  3155  3273 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 17:08:07.242  3155  3273 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 17:08:07.242  3155  3273 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-30 17:08:07.242  3155  3273 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 17:08:07.242  3155  3273 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-30 17:08:07.242  3155  3273 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 17:08:07.242  3155  3273 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 17:08:07.242  3155  3273 W bt-btif : ag scb idx 1 not allocated
08-30 17:08:07.242  3155  3273 W bt-btif : ag scb idx 2 not allocated
08-30 17:08:07.242  3155  3273 E bt-btif : BTA AG is already disabled, ignoring ...,
08-30 17:08:07.242  3155  3315 I bt_userial_mct: exiting userial_read_thread
08-30 17:08:07.242  3155  3315 D bt_userial_mct: Leaving userial_evt_read_thread()
08-30 17:08:07.242  3155  3252 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-30 17:08:07.242  3155  3275 I bt_vendor: hw_epilog_process
,08-30 17:08:07.242  3155  3252 D bt_userial_mct: userial_close
08-30 17:08:07.242  3155  3252 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-30 17:08:07.252  6906  6906 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:07.252  6906  6906 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:07.272  6906  6906 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-30 17:08:07.302  6906  6906 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-30 17:08:07.302  6906  6906 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-30 17:08:07.302  6906  6906 D UserAnalysis: Create SecureDbHelper
,08-30 17:08:07.312  6906  6906 D IntelligenceServiceApplication: onCreate()
,08-30 17:08:07.312  1016  1134 I ActivityManager: Killing 6366:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,08-30 17:08:07.322  1016  1134 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-30 17:08:07.322  6906  6906 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-30 17:08:07.322  1016  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:07.322  1016  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:07.322  1016  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:07.322  1016  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:07.342  6922  6922 E Zygote  : MountEmulatedStorage()
08-30 17:08:07.342  6922  6922 E Zygote  : v2
08-30 17:08:07.342  6922  6922 I libpersona: KNOX_SDCARD checking this for 10105
08-30 17:08:07.342  6922  6922 I libpersona: KNOX_SDCARD not a persona
08-30 17:08:07.342  6922  6922 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 17:08:07.342  1016  1134 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6922 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-30 17:08:07.342  1016  1514 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
08-30 17:08:07.342  6922  6922 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 17:08:07.342  6922  6922 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-30 17:08:07.352  6906  6906 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.,
,08-30 17:08:07.352  6906  6906 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-30 17:08:07.362  1016  1125 D WifiP2pService: InactiveState{ what=143375 }
,08-30 17:08:07.362  1016  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-30 17:08:07.362   285  1015 D CommandListener: Clearing all IP addresses on wlan0
,08-30 17:08:07.372  1969  3051 V NativeCrypto: Read error: ssl=0xb85faeb8: I/O error during system call, Connection timed out
08-30 17:08:07.372  6846  6857 V NativeCrypto: SSL handshake aborted: ssl=0xb8597a78: I/O error during system call, Connection timed out
08-30 17:08:07.372  6846  6857 I qtaguid : Untagging socket 30
,08-30 17:08:07.372  1969  3051 V NativeCrypto: SSL shutdown failed: ssl=0xb85faeb8: I/O error during system call, Broken pipe
,08-30 17:08:07.372  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:08:07.372  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-30 17:08:07.372  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:07.372  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:07.372  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:07.372  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:07.372  1969  3051 E GCM     : Wifi connection closed with errorCode 20
08-30 17:08:07.372  1016  1128 E ConnectivityService: updateNetworkInfo()
08-30 17:08:07.372  1016  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 17:08:07.372  1016  1128 E ConnectivityService: updateNetworkInfo()
08-30 17:08:07.372  1016  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,08-30 17:08:07.372  1016  1126 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-30 17:08:07.382  1016  1125 D WifiP2pService: InactiveState{ what=131204 }
08-30 17:08:07.382  1016  1125 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-30 17:08:07.382  1016  1125 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-30 17:08:07.382  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-30 17:08:07.382  6846  6857 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 17:08:07.382  6846  6857 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-30 17:08:07.382  6846  6857 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6846, getuid(): 10011
,08-30 17:08:07.392  1016  1016 D WifiScanningService: SCAN_AVAILABLE : 1
08-30 17:08:07.392  1016  1149 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:07.392  1016  1016 D RttService: SCAN_AVAILABLE : 1
08-30 17:08:07.392  1016  1150 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:07.392  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:08:07.392  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 17:08:07.392  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:07.392  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:07.392  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:07.392  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:07.392  1016  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:08:07.392  1016  1047 D WifiDisplayAdapter: onP2pDisconnected
,08-30 17:08:07.392  6765  6765 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 17:08:07.402  1016  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED,
08-30 17:08:07.402  1016  1016 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED,
08-30 17:08:07.402  1016  1125 D WifiP2pService: P2pDisablingState
08-30 17:08:07.402  1016  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-30 17:08:07.402  1016  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
08-30 17:08:07.402  1016  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,08-30 17:08:07.402  1016  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 17:08:07.402  1016  1047 D WifiDisplayController: disconnect
08-30 17:08:07.402  1016  1047 D WifiDisplayController: updateConnection
08-30 17:08:07.402  1016  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 17:08:07.402  1016  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-30 17:08:07.402  6922  6922 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:07.412  6922  6922 D ActivityThread: Added TimaKeyStore provider,
08-30 17:08:07.412  1016  1125 D WifiP2pService: P2pDisablingState{ what=147458 }
08-30 17:08:07.412  1016  1126 E WifiNative-wlan0: do suspend true,
08-30 17:08:07.412  1016  1125 D WifiP2pService: p2p socket connection lost
08-30 17:08:07.412  1016  1125 D WifiP2pService: P2pDisabledState
08-30 17:08:07.412  1016  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-30 17:08:07.412  1016  1047 D WifiDisplayAdapter: onP2pDisconnected
08-30 17:08:07.412  1016  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-30 17:08:07.412  1016  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
08-30 17:08:07.412  1016  1134 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,08-30 17:08:07.412  1016  1125 D WifiP2pService: P2pDisabledState{ what=143375 }
08-30 17:08:07.412  1016  1125 D WifiP2pService: DefaultState{ what=143375 }
,08-30 17:08:07.412  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-30 17:08:07.422  1016  1497 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-30 17:08:07.422  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-30 17:08:07.422  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:08:07.422  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 17:08:07.422  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:07.422  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:07.422  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:07.422  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:07.432  1016  1728 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-18ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 17:08:07.432  1016  1728 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-18ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 17:08:07.432  1016  1728 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-30 17:08:07.432  1016  1728 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:07.432  1016  1728 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
08-30 17:08:07.432  1016  1728 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 17:08:07.432  1016  1728 I qtaguid : Tagging socket 328 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1016, getuid(): 1000
,08-30 17:08:07.442  1016  1728 I qtaguid : Untagging socket 328
08-30 17:08:07.442  1016  1728 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 17:08:07.472  3155  3252 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off,
08-30 17:08:07.472  3155  3252 I bt_vendor: bluetooth satus is on
,08-30 17:08:07.472  3155  3252 I bt_vendor: bt-vendor : resetting BT status
08-30 17:08:07.472  3155  3252 I bt_vendor: Starting hciattach daemon,
08-30 17:08:07.472  3155  3252 I bt_vendor: try to set false
08-30 17:08:07.472  3155  3252 I bt_vendor: Starting hciattach daemon
08-30 17:08:07.472  3155  3252 I bt_vendor: try to set false
08-30 17:08:07.472  3155  3252 I bt_vendor: cleanup,
,08-30 17:08:07.472  3155  3273 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-30 17:08:07.472  3155  3252 I GKI_LINUX: GKI_exit_task 0 done
08-30 17:08:07.472  3155  3252 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-30 17:08:07.472  3155  3249 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-30 17:08:07.472  3155  3249 D BtConfig.SecureMode: isSecureModeOn:false
08-30 17:08:07.472  3155  3249 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-30 17:08:07.472  3155  3249 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService,
08-30 17:08:07.472  3155  3249 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-30 17:08:07.472  3155  3249 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-30 17:08:07.472  1016  1495 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:07.472  1016  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-30 17:08:07.472  1016  1495 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:07.472  1016  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:07.472  1016  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 17:08:07.472  3155  3249 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,08-30 17:08:07.472  3155  3249 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-30 17:08:07.472  3155  3155 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 17:08:07.482  3155  3249 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-30 17:08:07.482  1016  1514 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 17:08:07.482  3155  3155 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 17:08:07.482  1016  1514 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-30 17:08:07.482  3155  3155 D BtGatt.GattService: stop()
08-30 17:08:07.482  3155  3155 D BtGatt.AdvertiseManager: advertise clients cleared
,08-30 17:08:07.482  1016  1514 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:07.482  1016  1514 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:07.482  1016  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 17:08:07.482  3155  3249 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,08-30 17:08:07.482  3155  3249 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-30 17:08:07.482   285  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-30 17:08:07.482   285  1011 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-30 17:08:07.482   285  1015 D CommandListener: Clearing all IP addresses on wlan0
,08-30 17:08:07.482  6846  6857 I qtaguid : Untagging socket 30
,08-30 17:08:07.482  1016  1728 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,08-30 17:08:07.482  1016  1728 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-30 17:08:07.482  1016  1128 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,08-30 17:08:07.482  3155  3155 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336d367
08-30 17:08:07.482  3155  3249 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-30 17:08:07.482  1016  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:07.482  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 17:08:07.492  3155  3155 D HeadsetService: Received stop request...Stopping profile...
,08-30 17:08:07.492  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:07.492  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:07.492  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 17:08:07.492  1016  1128 V NetworkStats: updateIfacesLocked()
08-30 17:08:07.492  1016  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:07.492  1016  1128 V NetworkStats: performPollLocked(flags=0x1)
,08-30 17:08:07.492  3155  3249 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-30 17:08:07.492  6846  6857 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 17:08:07.492  3155  3249 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-30 17:08:07.492  6846  6857 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-30 17:08:07.492  6846  6857 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6846, getuid(): 10011
08-30 17:08:07.492  1016  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 17:08:07.492  1016  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 17:08:07.492  3155  3249 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-30 17:08:07.492  6846  6857 I qtaguid : Untagging socket 30
,08-30 17:08:07.492  6846  6857 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 17:08:07.492  6846  6857 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-30 17:08:07.492  1347  1347 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
08-30 17:08:07.492  6846  6857 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6846, getuid(): 10011
,08-30 17:08:07.492  6846  6857 I qtaguid : Untagging socket 30
,08-30 17:08:07.502  1016  1128 V NetworkStats: performPollLocked() took 9ms
08-30 17:08:07.502  1016  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:07.502  6846  6857 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 17:08:07.502  6846  6857 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-30 17:08:07.502  6846  6857 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6846, getuid(): 10011
,08-30 17:08:07.502  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-30 17:08:07.502  6846  6857 I qtaguid : Untagging socket 30
,08-30 17:08:07.502  6846  6857 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 17:08:07.502  6846  6857 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-30 17:08:07.502  6846  6857 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6846, getuid(): 10011
,08-30 17:08:07.502  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:08:07.502  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 17:08:07.502  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:07.502  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:07.502  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:07.502  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:07.502  3155  3155 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336d367
08-30 17:08:07.512  1016  1134 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 17:08:07.512  1016  1134 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-30 17:08:07.512  6846  6857 I qtaguid : Untagging socket 30
08-30 17:08:07.512  1016  1134 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:07.512  6846  6857 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 17:08:07.512  1016  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:07.512  1016  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 17:08:07.512  6846  6857 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-30 17:08:07.512  6846  6857 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6846, getuid(): 10011
,08-30 17:08:07.512  3155  3249 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-30 17:08:07.512  3155  3249 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-30 17:08:07.512  1016  3331 D SSRM:n  : SIOP:: AP = 370
,08-30 17:08:07.512  1016  1128 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
08-30 17:08:07.512  3155  3249 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-30 17:08:07.512  1177  1732 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-30 17:08:07.512  4791  6832 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-30 17:08:07.512  1016  1728 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 17:08:07.512  1016  1128 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 17:08:07.512  1016  1125 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-30 17:08:07.512  1016  1128 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-30 17:08:07.512  1016  1128 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-30 17:08:07.512  6846  6857 I qtaguid : Untagging socket 30
,08-30 17:08:07.522  1016  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-30 17:08:07.522  1473  1473 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-30 17:08:07.522  1473  1473 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 17:08:07.522  1016  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-30 17:08:07.522  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:07.522  1016  1016 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-30 17:08:07.522  1016  1498 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:07.522  1016  1498 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-30 17:08:07.522  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:07.522  1016  1126 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-30 17:08:07.522  1016  1498 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:07.522  1016  1498 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:07.522  1016  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:07.522  3155  3249 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-30 17:08:07.522  3155  3249 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-30 17:08:07.532  3155  3249 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-30 17:08:07.532  1016  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 17:08:07.532  1016  1126 D SecContentProvider2: mCursor = null
,08-30 17:08:07.532  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 17:08:07.532  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-30 17:08:07.532  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:07.532  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:07.542  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:07.542  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:07.542  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 17:08:07.542  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-30 17:08:07.542  1177  1755 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-30 17:08:07.542  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-30 17:08:07.542  1016  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 17:08:07.542  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-30 17:08:07.542  1177  1177 D HotspotTile: onReceive : 0, 0
,08-30 17:08:07.542  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:07.542  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:07.542  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:07.542  1016  1128 D ConnectivityService: nai.networkMonitor.doQuit()
08-30 17:08:07.542  1016  1128 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
,08-30 17:08:07.542  3155  3249 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-30 17:08:07.542  3155  3249 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 17:08:07.542  1016  1128 E ConnectivityService: updateNetworkInfo()
08-30 17:08:07.542  3155  3249 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-30 17:08:07.552  1016  1128 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 17:08:07.552  1016  1128 E ConnectivityService: updateNetworkInfo()
,08-30 17:08:07.552  1016  1016 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,08-30 17:08:07.552  1016  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-30 17:08:07.552  1016  1129 D Tethering: MasterInitialState.processMessage what=3
08-30 17:08:07.552  6765  6765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:07.552  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:07.552  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:07.552  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:07.552  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:08:07.552  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:08:07.552  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:07.552  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:07.552  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:08:07.552  6765  6765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:07.552  6765  6765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:08:07.552  1016  1123 V NetworkStats: updateIfacesLocked()
08-30 17:08:07.552  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:07.552  1016  1123 V NetworkStats: performPollLocked(flags=0x1)
,08-30 17:08:07.552  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 17:08:07.552  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 17:08:07.552  6765  6765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 17:08:07.552  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
08-30 17:08:07.552  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-30 17:08:07.552  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-30 17:08:07.552  1177  1177 D StatusBar.NetworkController: updateDataNetType()
08-30 17:08:07.552  1177  1177 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-30 17:08:07.562  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:07.562  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:07.562  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:07.562  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:08:07.562  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:08:07.562  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:07.562  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:07.562  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:08:07.562  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-30 17:08:07.562  6765  6765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 17:08:07.562  6765  6765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:08:07.562  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:07.562  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:07.562  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:07.562  1016  1124 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,08-30 17:08:07.562  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-30 17:08:07.562  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,08-30 17:08:07.562  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,08-30 17:08:07.562  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:08:07.562  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-30 17:08:07.562  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:07.562  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:07.562  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:07.562  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:07.562  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:07.562  1016  1497 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 17:08:07.562  1016  1497 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-30 17:08:07.572  1016  1497 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:07.572  1016  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:07.572  1016  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 17:08:07.572  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:07.572  1016  1123 V NetworkStats: performPollLocked() took 15ms
,08-30 17:08:07.572  3155  3249 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-30 17:08:07.572  3155  3249 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-30 17:08:07.572  3155  3249 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-30 17:08:07.582  1347  1347 I wpa_supplicant: Blacklist: Clear (all) 
,08-30 17:08:07.582  1016  1514 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 17:08:07.582  1016  1514 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-30 17:08:07.582  1016  1514 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:07.582  1016  1514 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:07.582  1016  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:07.582  3155  3249 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-30 17:08:07.582  3155  3249 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-30 17:08:07.582  3155  3249 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-30 17:08:07.582  3155  3249 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,08-30 17:08:07.582  3155  3249 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:08:07.582  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:07.582  3155  3249 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:08:07.582  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:07.582  3155  3249 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-30 17:08:07.582  3155  3249 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-30 17:08:07.592  3155  3249 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,08-30 17:08:07.592  3155  3249 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-30 17:08:07.592  3155  3249 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-30 17:08:07.592  3155  3249 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,08-30 17:08:07.592  3155  3155 E BluetoothAdapterService(53924711): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,08-30 17:08:07.592  3155  3249 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-30 17:08:07.592  3155  3155 D A2dpService: Received stop request...Stopping profile...
,08-30 17:08:07.592  3155  3265 D A2dpStateMachine: Exit Disconnected: -1
,08-30 17:08:07.602  3155  3155 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336d367
,08-30 17:08:07.602  3155  3155 E BluetoothAdapterService(53924711): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,08-30 17:08:07.602  3155  3155 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-30 17:08:07.602  3155  3155 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-30 17:08:07.602  3155  3155 D HidService: Received stop request...Stopping profile...
08-30 17:08:07.602  3155  3155 D HidService: Stopping Bluetooth HidService
08-30 17:08:07.602  3155  3155 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 17:08:07.602  3155  3155 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-30 17:08:07.602  3155  3155 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 17:08:07.602  3155  3155 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336d367
,08-30 17:08:07.602  1016  1016 D BluetoothA2dp: Proxy object disconnected
08-30 17:08:07.602  1016  1016 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-30 17:08:07.612  3155  3155 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 17:08:07.612  3155  3155 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-30 17:08:07.612  3155  3155 D HealthService: Received stop request...Stopping profile...
,08-30 17:08:07.612  3155  3155 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336d367
,08-30 17:08:07.612  3155  3155 D PanService: Received stop request...Stopping profile...
08-30 17:08:07.612  3155  3155 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336d367
,08-30 17:08:07.612  3155  3155 D BluetoothMapService: Received stop request...Stopping profile...
,08-30 17:08:07.612  6883  6883 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 17:08:07.612  6883  6883 D PanProfile: Bluetooth service disconnected
,08-30 17:08:07.622  1016  1016 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-30 17:08:07.622  1347  1347 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-30 17:08:07.622  1016  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 17:08:07.622  3155  3155 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336d367
,08-30 17:08:07.622  1016  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-30 17:08:07.622  1016  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-30 17:08:07.632   291   665 I WVCdm   : CdmEngine::CloseSession
,08-30 17:08:07.632  3155  3155 D SapService: Received stop request...Stopping profile...
08-30 17:08:07.632  3155  3155 D SapService: Stopping Bluetooth SapService
08-30 17:08:07.632  3155  3155 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336d367
,08-30 17:08:07.632  3155  3155 E BluetoothAdapterService(53924711): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-30 17:08:07.632  3155  3155 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 17:08:07.632  3155  3155 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-30 17:08:07.632  3155  3155 D BluetoothA2dp: Proxy object disconnected
08-30 17:08:07.632  3155  3155 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-30 17:08:07.632  3155  3155 E BluetoothAdapterService(53924711): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-30 17:08:07.632  3155  3155 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 17:08:07.632  3155  3155 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-30 17:08:07.632  3155  3266 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-30 17:08:07.632  3155  3155 I GKI_LINUX: GKI_exit_task 2 done
,08-30 17:08:07.632  3155  3155 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-30 17:08:07.642   291   665 I WVCdm   : L3 Terminate.
,08-30 17:08:07.642  3155  3155 E BluetoothAdapterService(53924711): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
,08-30 17:08:07.642  3155  3155 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-30 17:08:07.642  3155  3155 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-30 17:08:07.642  3155  3155 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 17:08:07.642  3155  3155 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-30 17:08:07.642  6883  6883 D Bluetoothsap: BluetoothSAP Proxy object disconnected
,08-30 17:08:07.642  6883  6883 D SapProfile: Bluetooth service disconnected
,08-30 17:08:07.642  3155  3155 E BluetoothAdapterService(53924711): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-30 17:08:07.642  3155  3155 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 17:08:07.642  3155  3155 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-30 17:08:07.642  3155  3155 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 17:08:07.642  3155  3155 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-30 17:08:07.652  1347  1347 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-30 17:08:07.652  1347  1347 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-30 17:08:07.652  1347  1347 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-30 17:08:07.652  1347  1347 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-30 17:08:07.652  1347  1347 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-30 17:08:07.652  3155  3155 E BluetoothAdapterService(53924711): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,08-30 17:08:07.652  3155  3155 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-30 17:08:07.652  3155  3155 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-30 17:08:07.652  3155  3155 E BluetoothAdapterService(53924711): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-30 17:08:07.652  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, false
,08-30 17:08:07.652  3155  3155 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-30 17:08:07.652  3155  3155 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-30 17:08:07.652  1016  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-30 17:08:07.652  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-30 17:08:07.652  1016  1129 D Tethering: InitialState.processMessage what=4
,08-30 17:08:07.662  3155  3249 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-30 17:08:07.662  3155  3249 D BluetoothAdapterProperties: Setting state to 10
08-30 17:08:07.662  3155  3249 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-30 17:08:07.662  3155  3249 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-30 17:08:07.662  3155  3249 D BluetoothAdapterService: updateAdapterState state is 10
,08-30 17:08:07.662   258   513 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-30 17:08:07.662   258   513 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 17:08:07.662  1177  3339 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 17:08:07.662  1016  1129 E Tethering: No numeric data
,08-30 17:08:07.662  1016  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 17:08:07.662  1016  1129 D Tethering: clearTetheredNotification()
08-30 17:08:07.662  1177  3339 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 17:08:07.662  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 17:08:07.662  1016  1044 D Tethering: interfaceStatusChanged wlan0, false
08-30 17:08:07.662  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-30 17:08:07.662  6765  6777 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 17:08:07.662  6765  6777 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 17:08:07.662  6765  6777 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-30 17:08:07.662  6765  6777 D BluetoothLeAdvertiser: Exit stop advertising
08-30 17:08:07.662  6765  6777 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-30 17:08:07.662  6765  6777 D BluetoothLeScanner: Exiting stopAllScan
,08-30 17:08:07.662  1449  1458 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 17:08:07.662  1449  1458 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 17:08:07.662  3155  3249 D BluetoothAdapterService: Autoconnection is available 
,08-30 17:08:07.662  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 17:08:07.662  1016  1044 D Tethering: interfaceStatusChanged wlan0, false,
08-30 17:08:07.672  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-30 17:08:07.672  3155  3249 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-30 17:08:07.672  3155  3249 I BluetoothAdapterState: Entering OffState
,08-30 17:08:07.672  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 17:08:07.672  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 17:08:07.672  1016  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-30 17:08:07.672  6922  6946 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-30 17:08:07.672  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:07.672  1016  1123 V NetworkStats: performPollLocked(flags=0x1)
,08-30 17:08:07.672  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 17:08:07.672  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 17:08:07.672   258   513 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-30 17:08:07.672   258   513 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 17:08:07.672  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-30 17:08:07.672  1177  1177 D HotspotTile: updateTetherState():false, false
,08-30 17:08:07.682  1016  1123 V NetworkStats: performPollLocked() took 3ms
08-30 17:08:07.682  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:07.682  6922  6946 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-30 17:08:07.682  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:07.682  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:07.682  1969  3046 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 17:08:07.682  1969  3046 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 17:08:07.682  6883  6891 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 17:08:07.682  6883  6891 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 17:08:07.682  6883  6891 D Bluetoothsap: onBluetoothStateChange: up=false
08-30 17:08:07.682  6883  6891 D Bluetoothsap: Unbinding service...
,08-30 17:08:07.692  3155  3342 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 17:08:07.692  3155  3342 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 17:08:07.692  1016  1046 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 17:08:07.692  3155  3173 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 17:08:07.692  1459  1485 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 17:08:07.692  1459  1485 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 17:08:07.702  1473  1774 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 17:08:07.702  1473  1774 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 17:08:07.702  1016  1046 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 17:08:07.702  1016  1046 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 17:08:07.702  1016  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-30 17:08:07.702   273   273 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb71637c8
08-30 17:08:07.702   273   273 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
08-30 17:08:07.702   273   273 I rmt_storage: wakelock acquired: 1, error no: 42
08-30 17:08:07.702   273   301 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1223280504)
,08-30 17:08:07.742  1016  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-30 17:08:07.772  1473  1473 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 17:08:07.772  1473  1473 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 17:08:07.772  1473  1473 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 17:08:07.782  1473  1473 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 17:08:07.782  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:08:07.782  1016  1016 I InputMethodManagerService: [BT Setting State] State =10
08-30 17:08:07.782  1016  1016 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-30 17:08:07.782  1473  1473 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 17:08:07.782  1473  1473 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 17:08:07.792  1177  1177 D BluetoothAdapter: 392681414: getState() :  mService = null. Returning STATE_OFF
08-30 17:08:07.792  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-30 17:08:07.792  1177  1755 D BluetoothAdapter: 392681414: getState() :  mService = null. Returning STATE_OFF
,08-30 17:08:07.792  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:08:07.792  1177  1177 D BluetoothTile:  getBluetoothState : 10
08-30 17:08:07.792  1177  1755 D BluetoothAdapter: 392681414: getState() :  mService = null. Returning STATE_OFF
,08-30 17:08:07.792  1177  1177 D BluetoothAdapter: 392681414: getState() :  mService = null. Returning STATE_OFF
08-30 17:08:07.792  1177  1177 D BluetoothAdapter: 392681414: getState() :  mService = null. Returning STATE_OFF
08-30 17:08:07.792  1016  2050 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 17:08:07.792  1016  1514 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-30 17:08:07.792  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-30 17:08:07.792  1969  2153 D BluetoothAdapter: 870300143: getState() :  mService = null. Returning STATE_OFF
08-30 17:08:07.792  1969  2153 D BluetoothAdapter: 870300143: getState() :  mService = null. Returning STATE_OFF
,08-30 17:08:07.792  1347  1347 I wpa_supplicant: Blacklist: Clear (all) 
08-30 17:08:07.792  1866  1866 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 17:08:07.802  6883  6883 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:08:07.802  6765  6765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:07.802  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:07.802  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:07.802  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:07.802  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:08:07.802  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:08:07.802  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:07.802  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:07.802  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:08:07.802  1016  1134 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 17:08:07.802  1016  1134 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-30 17:08:07.802  1473  1473 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 17:08:07.802  1473  1473 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 17:08:07.802  1473  1473 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 17:08:07.802  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:07.802  1016  1134 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:07.802  1016  1134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 17:08:07.802  1016  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:07.812  3155  3252 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-30 17:08:07.812  3155  3155 I GKI_LINUX: GKI_exit_task 1 done
08-30 17:08:07.812  3155  3155 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-30 17:08:07.812  3155  3155 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-30 17:08:07.812  1473  1473 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 17:08:07.812  1473  1473 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 17:08:07.812  1473  1473 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 17:08:07.812  1473  1473 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 17:08:07.822  3155  3155 I art     : System.exit called, status: 0
08-30 17:08:07.822  3155  3155 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 17:08:07.822  1473  1473 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 17:08:07.822  1473  1473 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 17:08:07.822  1473  1473 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 17:08:07.822  1473  1473 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 17:08:07.822  1473  1473 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 17:08:07.822  1473  1473 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 17:08:07.832  1473  1473 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 17:08:07.832  1473  1473 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 17:08:07.832  1016  1323 I art     : Explicit concurrent mark sweep GC freed 41206(2MB) AllocSpace objects, 4(112KB) LOS objects, 33% free, 24MB/36MB, paused 3.392ms total 196.439ms
,08-30 17:08:07.832  1473  1473 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 17:08:07.832  1473  1473 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 17:08:07.842   273   301 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
,08-30 17:08:07.842   273   301 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
08-30 17:08:07.842   273   301 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1223280504) wakelock released: 1, error no: 0
08-30 17:08:07.842   273   301 I rmt_storage: 
,08-30 17:08:07.842  1347  1347 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-30 17:08:07.842   273   273 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb71637c8
,08-30 17:08:07.842  1473  1473 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-30 17:08:07.842  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, false
,08-30 17:08:07.842  1016  1044 D Tethering: interfaceStatusChanged wlan0, false
08-30 17:08:07.842  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-30 17:08:07.852  1016  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-30 17:08:07.852  1016  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-30 17:08:07.862  1473  1473 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 17:08:07.862  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:08:07.862  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-30 17:08:07.862  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:07.862  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:07.862  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:07.862  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:07.862  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 17:08:07.862  1177  1755 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-30 17:08:07.862  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-30 17:08:07.862  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-30 17:08:07.862  1473  1473 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-30 17:08:07.862  1177  1177 D HotspotTile: onReceive : 1, 0
08-30 17:08:07.862  1969  2153 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 17:08:07.872  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:07.872  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:07.872  1473  1473 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 17:08:07.872  1473  1473 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 17:08:07.872  1473  1473 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-30 17:08:07.872  1473  1473 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 17:08:07.892  6922  6922 D StrictMode: StrictMode policy violation; ~duration=322 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at java.io.File.exists(File.java:363)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 17:08:07.892  6922  6922 D StrictMode: StrictMode policy violation; ~duration=314 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 17:08:07.892  6922  6922 D StrictMode: StrictMode policy violation; ~duration=312 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 17:08:07.892  6922  6922 D StrictMode: StrictMode policy violation; ~duration=310 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.q.e.b(PG:170)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 17:08:07.892  6922  6922 D StrictMode: StrictMode policy violation; ~duration=308 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.q.k.d(PG:583)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.q.e.b(PG:170)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 17:08:07.902  1016  1415 I ActivityManager: Killing 6501:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
08-30 17:08:07.892  6922  6922 D StrictMode: StrictMode policy violation; ~duration=269 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at java.io.File.exists(File.java:363)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 17:08:07.902  1016  2050 I ActivityManager: Process com.android.bluetooth (pid 3155)(adj 0) has died(32,719)
08-30 17:08:07.892  6922  6922 D StrictMode: StrictMode policy violation; ~duration=268 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at java.io.File.exists(File.java:363)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 17:08:07.922  1016  1415 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 17:08:07.892  6922  6922 D StrictMode: StrictMode policy violation; ~duration=267 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 17:08:07.892  6922  6922 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 17:08:07.922  1016  1415 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-30 17:08:07.902  1969  1969 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-30 17:08:07.912  1969  1969 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-30 17:08:07.922  1016  1415 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:07.922  1016  1415 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:07.922  1016  1415 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-30 17:08:07.922  1595  1595 I Hs20UtilService: Starting #8
08-30 17:08:07.922  6978  6978 I dex2oat : ----------------------------------------------------
08-30 17:08:07.922  6978  6978 I dex2oat : <SS>: S T A R T I N G . . .
08-30 17:08:07.922  6978  6978 I dex2oat : <SS>: Zip is absent. Canceled.
08-30 17:08:07.922  6978  6978 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=30 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
08-30 17:08:07.922  1595  1633 I Hs20UtilService: Message received 5007
08-30 17:08:07.932  6883  6883 D NearbySettings: MountReceiver.onReceive - Create HandlerThread
08-30 17:08:07.932  6883  6883 D NearbySettings: MountReceiver.onReceive - Start HandlerThread
08-30 17:08:07.932  6883  6883 D NearbySettings: MountReceiver.onReceive - Create mPrefHandler
08-30 17:08:07.942  6883  6883 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-30 17:08:07.942  6883  6883 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 17:08:07.942  6883  6883 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-30 17:08:07.952  6883  6883 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-30 17:08:07.952  6883  6883 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 17:08:07.952  6883  6883 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-30 17:08:07.952  6883  6981 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-30 17:08:07.972  6922  6957 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-30 17:08:07.972  6883  6883 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-30 17:08:07.972  6883  6883 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-30 17:08:07.972  6883  6883 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-30 17:08:07.982  6883  6883 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-30 17:08:07.982  6883  6883 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 17:08:07.982  6883  6883 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-30 17:08:07.982  6883  6981 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-30 17:08:07.982  1016  1028 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
08-30 17:08:07.982  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:07.982  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:07.982  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:07.982  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:07.992  6987  6987 E Zygote  : MountEmulatedStorage()
,08-30 17:08:08.002  6987  6987 E Zygote  : v2
08-30 17:08:08.002  6987  6987 I libpersona: KNOX_SDCARD checking this for 10064
08-30 17:08:08.002  6987  6987 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:08.002  1016  1028 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6987 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 17:08:08.002  6987  6987 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:08:08.002  6987  6987 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-30 17:08:08.002  6987  6987 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:08:08.022  6987  6987 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:08.022  6987  6987 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:08.032  6987  6987 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-30 17:08:08.042  1016  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:08:08.052  1016  1016 I ApplicationPolicy: updateDataUsageMap
,08-30 17:08:08.052  1016  1041 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:08:08.062  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:08.062  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:08.072  6987  6987 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 17:08:08.082  6987  6987 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-30 17:08:08.102  6978  6978 I dex2oat : dex2oat took 177.622ms (threads: 4)
,08-30 17:08:08.102  1016  1415 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:08:08.112  1016  1415 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:08.112  1016  1415 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:08.112  1016  1415 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-30 17:08:08.112  6846  6857 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-30 17:08:08.112  6846  6857 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-30 17:08:08.112  6846  6857 I Adreno-EGL: Build Date: 04/06/15 Mon
08-30 17:08:08.112  6846  6857 I Adreno-EGL: Local Branch: 
08-30 17:08:08.112  6846  6857 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-30 17:08:08.112  6846  6857 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-30 17:08:08.112  6846  6857 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-30 17:08:08.132  6987  6987 D FileShare-Client: Outbound.stopDelayTimer - 
,08-30 17:08:08.132  1016  1514 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-30 17:08:08.132  1016  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:08.132  1016  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:08.132  1016  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:08.132  1016  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:08.152  7004  7004 E Zygote  : MountEmulatedStorage()
,08-30 17:08:08.152  7004  7004 E Zygote  : v2
08-30 17:08:08.152  7004  7004 I libpersona: KNOX_SDCARD checking this for 10065
08-30 17:08:08.152  7004  7004 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:08.152  7004  7004 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-30 17:08:08.152  1016  1514 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7004 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 17:08:08.152  1016  1514 I ActivityManager: Killing 6532:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-30 17:08:08.152  7004  7004 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 17:08:08.152  7004  7004 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:08:08.172  7004  7004 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:08.172  7004  7004 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:08.192  7004  7004 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 17:08:08.202  1016  1497 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:08.202  1016  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:08.202  1016  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,08-30 17:08:08.202  1016  1497 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-30 17:08:08.212   291   702 I WVCdm   : CdmEngine::OpenSession
08-30 17:08:08.212   291   702 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
08-30 17:08:08.212  1016  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:08.212  1016  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:08.212  1016  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:08.212  1016  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:08.212   291   702 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-30 17:08:08.222  7020  7020 E Zygote  : MountEmulatedStorage(),
08-30 17:08:08.222  7020  7020 E Zygote  : v2
08-30 17:08:08.222  7020  7020 I libpersona: KNOX_SDCARD checking this for 10102
08-30 17:08:08.222  7020  7020 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:08.222  7020  7020 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:08:08.222  7020  7020 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-30 17:08:08.222  1016  1497 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7020 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-30 17:08:08.232  7020  7020 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-30 17:08:08.232  1016  1497 I ActivityManager: Killing 6551:com.samsung.android.sm/1000 (adj 15): empty #21
,08-30 17:08:08.232   291   702 W WVCdm   : Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,08-30 17:08:08.252  7020  7020 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:08.252  7020  7020 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:08.262  7020  7020 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-30 17:08:08.282   291   702 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-30 17:08:08.282   291   702 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-30 17:08:08.282   291   702 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-30 17:08:08.282   291   702 I WVCdm   : CdmEngine::GenerateKeyRequest
,08-30 17:08:08.292   291   702 D WVCdm   : PrepareKeyRequest: nonce=374827550
,08-30 17:08:08.382  1016  1044 D Tethering: interfaceRemoved wlan0
,08-30 17:08:08.382  1016  1044 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-30 17:08:08.442  7020  7040 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-30 17:08:08.442  7020  7040 I Babel_SMS: MmsConfig.loadMmsSettings
,08-30 17:08:08.442  7020  7040 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-30 17:08:08.442  7020  7040 I Babel_SMS: MmsConfig.loadFromDatabase
,08-30 17:08:08.472  7020  7040 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-30 17:08:08.472  7020  7040 I Babel_SMS: MmsConfig.loadFromResources
,08-30 17:08:08.472  7020  7040 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-30 17:08:08.472  7020  7040 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-30 17:08:08.492  1016  1495 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-30 17:08:08.492  1016  1495 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-30 17:08:08.492  1016  1495 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:08.492  1016  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 17:08:08.492  1016  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-30 17:08:08.512  7020  7020 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 17:08:08.522  7020  7020 I Babel_Crash: startup - clean
,08-30 17:08:08.522  1016  1044 D Tethering: interfaceRemoved p2p0
,08-30 17:08:08.522  1016  1044 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-30 17:08:08.552  1016  1536 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-30 17:08:08.552  1016  1536 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 17:08:08.552  1016  1536 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:08.552  1016  1536 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 17:08:08.552  1016  1536 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 17:08:08.552  1595  1595 I Hs20UtilService: Starting #9
,08-30 17:08:08.552  1595  1633 I Hs20UtilService: Message received 5007
,08-30 17:08:08.552  6883  6883 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-30 17:08:08.552  6883  6883 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 17:08:08.562  6883  6883 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 17:08:08.562  6883  6883 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-30 17:08:08.562  6883  6883 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 17:08:08.562  6883  6883 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-30 17:08:08.562  6883  6981 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 17:08:08.572  1016  2050 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 17:08:08.572  1016  2050 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 17:08:08.572  1016  2050 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:08.572  1016  2050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 17:08:08.572  1016  2050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 17:08:08.572  7020  7020 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 17:08:08.572  1595  1595 I Hs20UtilService: Starting #10
,08-30 17:08:08.572  1595  1633 I Hs20UtilService: Message received 5011
,08-30 17:08:08.572  7020  7020 W AudioCapabilities: Unsupported mime audio/evrc
,08-30 17:08:08.572  6569  6569 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-30 17:08:08.572  7020  7020 W AudioCapabilities: Unsupported mime audio/qcelp
,08-30 17:08:08.572  6569  6569 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-30 17:08:08.572  6569  6569 D SecurityLogAgent: StateMachine : Current State = 1
,08-30 17:08:08.582  7020  7020 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-30 17:08:08.582  6569  6569 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-30 17:08:08.582  7020  7020 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-30 17:08:08.592  1016  1497 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:08.592  1016  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:08.592  1016  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:08:08.592  7020  7020 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-30 17:08:08.592  7020  7020 W AudioCapabilities: Unsupported mime audio/x-ima
,08-30 17:08:08.592  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:08.592  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:08.592  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:08:08.592  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:08.592  7020  7020 W AudioCapabilities: Unsupported mime audio/qcelp
08-30 17:08:08.592  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:08.592  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:08:08.602  7020  7020 W AudioCapabilities: Unsupported mime audio/evrc
,08-30 17:08:08.602  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:08.602  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:08.602  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:08:08.602  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:08.602  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:08.602  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:08:08.612  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:08.612  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:08.612  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:08:08.612  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:08.612  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:08.612  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:08:08.612  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:08.612  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:08.612  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:08:08.622  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:08.622  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:08.622  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:08:08.622  7020  7020 W VideoCapabilities: Unsupported mime video/wvc1
,08-30 17:08:08.622  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:08.622  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:08.622  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:08:08.622  7020  7020 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-30 17:08:08.622  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:08.622  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:08.622  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:08:08.632  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:08.632  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:08.632  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:08:08.632  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:08.632  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:08.632  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:08:08.632  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:08.632  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:08.632  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:08:08.642  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:08.642  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:08.642  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:08:08.652  6883  6883 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 17:08:08.652  1016  1415 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-30 17:08:08.652  1016  1415 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-30 17:08:08.652  1016  1415 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:08.652  1016  1415 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:08.652  1016  1415 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-30 17:08:08.652  7020  7020 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-30 17:08:08.662  6883  6883 D DockEventReceiver: finishStartingService: stopping service
,08-30 17:08:08.662  7020  7020 W VideoCapabilities: Unsupported mime video/wvc1
,08-30 17:08:08.662  6883  6883 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 17:08:08.662  7020  7020 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-30 17:08:08.662  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:08.672  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-30 17:08:08.672   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 17:08:08.672  1016  1497 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-30 17:08:08.672  7020  7020 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-30 17:08:08.672  1016  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:08.672  7020  7020 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-30 17:08:08.672  1016  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:08.672  1016  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:08.672  1016  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:08.672  7020  7020 W VideoCapabilities: Unsupported mime video/mp43,
,08-30 17:08:08.682  7044  7044 E Zygote  : MountEmulatedStorage(),
,08-30 17:08:08.692  7044  7044 E Zygote  : v2
08-30 17:08:08.692  7044  7044 I libpersona: KNOX_SDCARD checking this for 1002
08-30 17:08:08.692  7044  7044 I libpersona: KNOX_SDCARD not a persona
08-30 17:08:08.692  7044  7044 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:08:08.692  7020  7020 W VideoCapabilities: Unsupported mime video/sorenson
,08-30 17:08:08.692  1016  1497 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7044 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-30 17:08:08.692  7044  7044 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 17:08:08.692  7044  7044 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:08:08.702  7020  7020 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-30 17:08:08.712  7044  7044 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:08.722  7044  7044 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:08.722  7020  7020 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-30 17:08:08.732  7044  7044 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-30 17:08:08.732  7044  7044 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 17:08:08.742  7020  7020 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 17:08:08.742  7020  7020 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 17:08:08.752  7020  7020 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 17:08:08.752  7020  7020 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 17:08:08.752  1016  1323 I ActivityManager: Killing 6601:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-30 17:08:08.762  7044  7044 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-30 17:08:08.762  7020  7020 I vclib   : onServiceConnected
,08-30 17:08:08.802  7044  7044 D BtSettings.ProfileConfig: Adding GattService
,08-30 17:08:08.802  7044  7044 D BtSettings.ProfileConfig: Adding HeadsetService
08-30 17:08:08.802  7044  7044 D BtSettings.ProfileConfig: Adding A2dpService
08-30 17:08:08.802  7044  7044 D BtSettings.ProfileConfig: Adding HidService
,08-30 17:08:08.802  7044  7044 D BtSettings.ProfileConfig: Adding HealthService
08-30 17:08:08.802  7044  7044 D BtSettings.ProfileConfig: Adding PanService
08-30 17:08:08.802  7044  7044 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-30 17:08:08.802  7044  7044 D BtSettings.ProfileConfig: Adding SapService
08-30 17:08:08.802  7044  7044 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-30 17:08:08.802  7044  7044 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-30 17:08:08.802  7044  7044 D BtSettings.ProfileConfig: Adding SapClientService
08-30 17:08:08.802  7044  7044 D BtSettings.ProfileConfig: Adding HidDevService
,08-30 17:08:08.802  7044  7044 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-30 17:08:08.802  1016  1497 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-30 17:08:08.802  1016  1497 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:08.802  1016  1497 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-30 17:08:08.802  1016  1497 D SettingsProvider: selectionArgs: false
08-30 17:08:08.802  1016  1497 D SettingsProvider: selectionArgs: 1002
08-30 17:08:08.802  1016  1497 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-30 17:08:08.802  1016  1497 D SettingsProvider: ret = -1
,08-30 17:08:08.802  1016  1498 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-30 17:08:08.802  1016  1498 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:08.802  1016  1498 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:08.802  1016  1498 D SettingsProvider: selectionArgs: false
08-30 17:08:08.802  1016  1498 D SettingsProvider: selectionArgs: 1002
08-30 17:08:08.802  1016  1498 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:08.802  1016  1498 D SettingsProvider: ret = -1
,08-30 17:08:08.812  1016  1029 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-30 17:08:08.812  1016  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:08.812  1016  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-30 17:08:08.812  1016  1029 D SettingsProvider: selectionArgs: false
08-30 17:08:08.812  1016  1029 D SettingsProvider: selectionArgs: 1002
08-30 17:08:08.812  1016  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:08.812  1016  1029 D SettingsProvider: ret = -1
,08-30 17:08:08.812  1016  1514 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,08-30 17:08:08.812  1016  1514 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:08.812  1016  1514 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:08.812  1016  1514 D SettingsProvider: selectionArgs: false
,08-30 17:08:08.812  1016  1514 D SettingsProvider: selectionArgs: 1002
,08-30 17:08:08.812  1016  1514 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:08.812  1016  1514 D SettingsProvider: ret = -1
,08-30 17:08:08.812  1016  1536 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-30 17:08:08.812  1016  1536 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:08.812  1016  1536 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:08.812  1016  1536 D SettingsProvider: selectionArgs: false
08-30 17:08:08.812  1016  1536 D SettingsProvider: selectionArgs: 1002
08-30 17:08:08.812  1016  1536 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:08.812  1016  1536 D SettingsProvider: ret = -1
,08-30 17:08:08.812  1016  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-30 17:08:08.812  1016  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:08.812  1016  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-30 17:08:08.812  1016  1028 D SettingsProvider: selectionArgs: false
08-30 17:08:08.812  1016  1028 D SettingsProvider: selectionArgs: 1002
08-30 17:08:08.812  1016  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:08.812  1016  1028 D SettingsProvider: ret = -1
,08-30 17:08:08.812  1016  1323 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-30 17:08:08.812  1016  1323 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:08.812  1016  1323 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:08.812  1016  1323 D SettingsProvider: selectionArgs: false
08-30 17:08:08.812  1016  1323 D SettingsProvider: selectionArgs: 1002
08-30 17:08:08.812  1016  1323 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:08.812  1016  1323 D SettingsProvider: ret = -1
,08-30 17:08:08.812  1016  1415 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-30 17:08:08.812  1016  1415 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:08.812  1016  1415 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:08.812  1016  1415 D SettingsProvider: selectionArgs: false
08-30 17:08:08.812  1016  1415 D SettingsProvider: selectionArgs: 1002
08-30 17:08:08.812  1016  1415 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:08.812  1016  1415 D SettingsProvider: ret = -1
,08-30 17:08:08.812  1016  2050 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,08-30 17:08:08.812  1016  2050 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:08.812  1016  2050 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:08.812  1016  2050 D SettingsProvider: selectionArgs: false
,08-30 17:08:08.812  1016  2050 D SettingsProvider: selectionArgs: 1002
,08-30 17:08:08.812  1016  2050 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:08.812  1016  2050 D SettingsProvider: ret = -1
08-30 17:08:08.822  1016  1134 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:08:08.822  1016  1134 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-30 17:08:08.822  1016  1134 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:08.822  1016  1134 D SettingsProvider: selectionArgs: false
08-30 17:08:08.822  1016  1134 D SettingsProvider: selectionArgs: 1002
08-30 17:08:08.822  1016  1134 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:08.822  1016  1134 D SettingsProvider: ret = -1
,08-30 17:08:08.822  1016  1495 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-30 17:08:08.822  1016  1495 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:08.822  1016  1495 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:08.822  1016  1495 D SettingsProvider: selectionArgs: false
,08-30 17:08:08.822  1016  1495 D SettingsProvider: selectionArgs: 1002
08-30 17:08:08.822  1016  1495 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:08.822  1016  1495 D SettingsProvider: ret = -1
,08-30 17:08:08.822  1016  1497 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-30 17:08:08.822  1016  1497 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:08.822  1016  1497 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-30 17:08:08.822  1016  1497 D SettingsProvider: selectionArgs: false
08-30 17:08:08.822  1016  1497 D SettingsProvider: selectionArgs: 1002
08-30 17:08:08.822  1016  1497 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-30 17:08:08.822  1016  1497 D SettingsProvider: ret = -1
,08-30 17:08:08.832  1016  1029 I ActivityManager: Killing 6619:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,08-30 17:08:08.832  1969  1969 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-30 17:08:08.832  1016  1415 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 17:08:08.832  1016  1415 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-30 17:08:08.832  1016  1415 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:08.832  1016  1415 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:08.832  1016  1415 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:08.842  1969  1969 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-30 17:08:08.842  1969  7060 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-30 17:08:08.852  1016  1495 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:08:08.852  1016  1495 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:08.852  1016  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:08.852  1016  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:08.862  1016  1536 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
,08-30 17:08:08.862  1016  1536 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:08.862  1016  1536 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-30 17:08:08.862  1016  1536 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:08.862  1016  1536 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-30 17:08:08.862  1595  1595 I Hs20UtilService: Starting #11
,08-30 17:08:08.862  1595  1633 I Hs20UtilService: Message received 5011
,08-30 17:08:08.862  6569  6569 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-30 17:08:08.862  6569  6569 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-30 17:08:08.862  6569  6569 D SecurityLogAgent: StateMachine : Current State = 1
08-30 17:08:08.862  6569  6569 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 17:08:08.882  1016  1028 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-30 17:08:08.882  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:08.882  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:08.882  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:08.882  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:08.892  1016  1028 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7061 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-30 17:08:08.892  7061  7061 E Zygote  : MountEmulatedStorage(),
,08-30 17:08:08.892  7061  7061 E Zygote  : v2
08-30 17:08:08.892  7061  7061 I libpersona: KNOX_SDCARD checking this for 1000
08-30 17:08:08.892  7061  7061 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:08.892  7061  7061 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-30 17:08:08.902  7061  7061 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 17:08:08.902  7061  7061 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:08:08.922   323   323 I art     : Explicit concurrent mark sweep GC freed 8713(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 601us total 27.371ms
,08-30 17:08:08.922  7061  7061 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:08.922  7061  7061 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:08.932   323   323 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 588us total 16.623ms
,08-30 17:08:08.942  1969  1969 I art     : Explicit concurrent mark sweep GC freed 37796(2MB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 11MB/18MB, paused 1.654ms total 74.741ms
,08-30 17:08:08.952  7061  7061 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-30 17:08:08.952  7061  7061 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-30 17:08:08.952  7061  7061 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-30 17:08:08.952  1016  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:08:08.952   323   323 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 599us total 18.362ms
08-30 17:08:08.962  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:08.962  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 17:08:08.962  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:08.962  1969  7060 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-30 17:08:08.972  7061  7061 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-30 17:08:08.972  7061  7061 I PCWCLIENTTRACE_PushUtil: sales region : global
08-30 17:08:08.972  7061  7061 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-30 17:08:08.972  7061  7061 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:08:08.972  7061  7076 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-30 17:08:08.972  1016  1495 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
,08-30 17:08:08.972  1016  1495 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-30 17:08:08.982  1016  1016 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-30 17:08:08.982  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:08.982  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:08.982  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:08.982  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:09.002  7078  7078 E Zygote  : MountEmulatedStorage(),
,08-30 17:08:09.002  7078  7078 E Zygote  : v2
08-30 17:08:09.002  7078  7078 I libpersona: KNOX_SDCARD checking this for 10001
08-30 17:08:09.002  7078  7078 I libpersona: KNOX_SDCARD not a persona,
,08-30 17:08:09.002  7078  7078 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:08:09.002  1016  1016 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7078 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 17:08:09.002  7078  7078 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 17:08:09.002  7078  7078 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:08:09.002  1016  1042 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
08-30 17:08:09.002  1800  1800 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-30 17:08:09.012  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:09.012  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:09.012  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:09.012  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:09.022  7093  7093 E Zygote  : MountEmulatedStorage(),
08-30 17:08:09.022  7093  7093 E Zygote  : v2
08-30 17:08:09.022  7093  7093 I libpersona: KNOX_SDCARD checking this for 10121
08-30 17:08:09.022  7093  7093 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:09.022  1016  1042 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7093 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
08-30 17:08:09.022  7093  7093 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:08:09.022  1016  1495 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
08-30 17:08:09.022  7093  7093 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 17:08:09.022  7078  7078 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:08:09.022  1016  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:09.022  7093  7093 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 17:08:09.022  1016  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:09.022  7078  7078 D ActivityThread: Added TimaKeyStore provider
08-30 17:08:09.022  1016  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:09.022  1016  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:09.042  7103  7103 E Zygote  : MountEmulatedStorage(),
08-30 17:08:09.042  7103  7103 I libpersona: KNOX_SDCARD checking this for 10031
08-30 17:08:09.042  7103  7103 E Zygote  : v2
08-30 17:08:09.042  7103  7103 I libpersona: KNOX_SDCARD not a persona
08-30 17:08:09.042  7103  7103 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-30 17:08:09.042  1016  1495 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7103 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,08-30 17:08:09.052  7103  7103 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 17:08:09.052  7103  7103 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:08:09.052  7093  7093 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:09.062  7093  7093 D ActivityThread: Added TimaKeyStore provider
08-30 17:08:09.062  2598  2606 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 6
,08-30 17:08:09.072  1800  1800 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-30 17:08:09.072  1800  1800 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,08-30 17:08:09.072  1800  1800 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
08-30 17:08:09.072  1800  1800 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-30 17:08:09.072  7093  7093 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 17:08:09.072  7103  7103 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:09.072  7103  7103 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:09.082  7093  7093 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-30 17:08:09.082  7093  7093 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 17:08:09.082  1800  1800 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-30 17:08:09.092  1800  1800 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-30 17:08:09.092  1016  1029 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
08-30 17:08:09.092  7093  7093 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:08:09.092  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:09.092  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:09.092  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:09.092  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:09.102  7123  7123 E Zygote  : MountEmulatedStorage()
08-30 17:08:09.102  7123  7123 E Zygote  : v2
08-30 17:08:09.102  7123  7123 I libpersona: KNOX_SDCARD checking this for 10077
08-30 17:08:09.102  7123  7123 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:09.102  7123  7123 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:08:09.112  1016  1029 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7123 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 17:08:09.112  7123  7123 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 17:08:09.112  7093  7093 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
08-30 17:08:09.112  7123  7123 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-30 17:08:09.112  7093  7093 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-30 17:08:09.122  1016  1498 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-30 17:08:09.122  1016  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:09.122  1016  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:09.122  1016  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:09.122  1016  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:09.122  7103  7103 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-30 17:08:09.132  7123  7123 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:09.132  7123  7123 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:09.142  7138  7138 E Zygote  : MountEmulatedStorage()
08-30 17:08:09.142  7138  7138 E Zygote  : v2
08-30 17:08:09.142  7138  7138 I libpersona: KNOX_SDCARD checking this for 10141
08-30 17:08:09.142  7138  7138 I libpersona: KNOX_SDCARD not a persona
08-30 17:08:09.142  1016  1498 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7138 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,08-30 17:08:09.142  7138  7138 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 17:08:09.142  1016  1498 I ActivityManager: Killing 6635:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,08-30 17:08:09.152  7138  7138 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 17:08:09.152  7138  7138 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:08:09.152  1016  1498 I ActivityManager: Killing 6578:com.android.providers.calendar/u0a37 (adj 15): empty #21
,08-30 17:08:09.172  1016  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
08-30 17:08:09.172  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:09.172  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:09.172  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:09.172  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:09.182  7138  7138 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:09.182  7138  7138 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:09.182  2755  7153 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-30 17:08:09.182  2755  7153 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-30 17:08:09.182  2755  7153 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-30 17:08:09.182  2755  7153 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,08-30 17:08:09.182  2755  7153 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-30 17:08:09.192  7156  7156 E Zygote  : MountEmulatedStorage()
08-30 17:08:09.192  1016  1029 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7156 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 17:08:09.192  7156  7156 E Zygote  : v2
08-30 17:08:09.192  7156  7156 I libpersona: KNOX_SDCARD checking this for 10032
08-30 17:08:09.192  7156  7156 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:09.192  7156  7156 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:08:09.202  7156  7156 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 17:08:09.202  7156  7156 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-30 17:08:09.212  7138  7138 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
08-30 17:08:09.212  7138  7138 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 17:08:09.212  7138  7138 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 17:08:09.212  7138  7138 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-30 17:08:09.222  1016  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-30 17:08:09.232  7156  7156 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:09.232  7156  7156 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:09.242  1016  1498 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-30 17:08:09.242  1016  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:09.242  1016  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:09.242  1016  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:09.242  1016  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:09.262  7171  7171 E Zygote  : MountEmulatedStorage(),
08-30 17:08:09.262  7171  7171 E Zygote  : v2
08-30 17:08:09.262  7171  7171 I libpersona: KNOX_SDCARD checking this for 1000
08-30 17:08:09.262  7171  7171 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:09.262  7171  7171 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:08:09.262  7171  7171 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-30 17:08:09.262  1016  1498 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7171 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-30 17:08:09.262  1016  1498 I ActivityManager: Killing 6657:com.qualcomm.timeservice/1000 (adj 15): empty #21
,08-30 17:08:09.272  7171  7171 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-30 17:08:09.292  7171  7171 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:09.302  7171  7171 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:09.332  1016  1536 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 17:08:09.362  7156  7186 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-30 17:08:09.362  1016  1498 D RCPManagerService: exchangeData() failure , invalid userId
08-30 17:08:09.362  7156  7186 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-30 17:08:09.372  7156  7186 D SPPClientService: PushLog.txt file is not deleted.
08-30 17:08:09.372  7156  7186 D SPPClientService: PushLog.txt file is not deleted.
08-30 17:08:09.372  7156  7186 D SPPClientService: ============PushLog. stop!
,08-30 17:08:09.382  7171  7171 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-30 17:08:09.392  7156  7156 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-30 17:08:09.392  1016  1415 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-30 17:08:09.392  1016  1415 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:09.392  1016  1415 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:09.392  1016  1415 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:09.392  1016  1415 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:09.412  7191  7191 E Zygote  : MountEmulatedStorage()
,08-30 17:08:09.412  7191  7191 E Zygote  : v2
08-30 17:08:09.412  7191  7191 I libpersona: KNOX_SDCARD checking this for 10036,
08-30 17:08:09.412  7191  7191 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:09.412  7191  7191 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-30 17:08:09.412  7191  7191 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-30 17:08:09.422  1016  1415 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7191 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 17:08:09.422  1016  1415 I ActivityManager: Killing 6077:com.android.mms/u0a41 (adj 15): empty #21
,08-30 17:08:09.422  7191  7191 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,08-30 17:08:09.422  1016  1323 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,08-30 17:08:09.422  1016  1323 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,08-30 17:08:09.422  1016  1323 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:09.422  1016  1323 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-30 17:08:09.422  1016  1323 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-30 17:08:09.442  7191  7191 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:09.442  7191  7191 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:09.462  7156  7201 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-30 17:08:09.472  1016  1028 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 17:08:09.482  1016  1029 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 17:08:09.512  7191  7191 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@3f59727c
,08-30 17:08:09.522  1016  1536 D CountryDetector: No listener is left
,08-30 17:08:09.532  7191  7191 I SA      : [SSP] onCreated
,08-30 17:08:09.542  1016  1498 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,08-30 17:08:09.542  1016  1498 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-30 17:08:09.542  1016  1498 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:09.552  1016  1498 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:09.552  1016  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-30 17:08:09.552  1016  1134 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-30 17:08:09.552  1016  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:09.552  1016  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:09.552  1016  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:09.552  1016  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:09.562  1016  1134 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7215 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,08-30 17:08:09.562  7215  7215 E Zygote  : MountEmulatedStorage()
08-30 17:08:09.562  7215  7215 E Zygote  : v2
08-30 17:08:09.562  7215  7215 I libpersona: KNOX_SDCARD checking this for 10068
08-30 17:08:09.562  7215  7215 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:09.562  1016  2050 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-30 17:08:09.572  7215  7215 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 17:08:09.572  1016  2050 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:09.572  1016  2050 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:09.572  1016  2050 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:09.572  1016  2050 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:09.572  7215  7215 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 17:08:09.572  7215  7215 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-30 17:08:09.592  7191  7191 I SA      : [TPM] There is no property file
,08-30 17:08:09.592  7232  7232 E Zygote  : MountEmulatedStorage()
08-30 17:08:09.592  7232  7232 E Zygote  : v2
08-30 17:08:09.592  7232  7232 I libpersona: KNOX_SDCARD checking this for 10110
08-30 17:08:09.592  7232  7232 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:09.602  7232  7232 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:08:09.602  7191  7191 I SA      : [SCU] isHaveSA() - false
,08-30 17:08:09.602  7171  7171 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-30 17:08:09.602  7232  7232 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 17:08:09.602  7232  7232 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-30 17:08:09.602  7191  7191 I SA      : [TPM] getModelProperty : null
08-30 17:08:09.602  7191  7191 I SA      : [TPM] getCSCProperty : null
,08-30 17:08:09.602  7215  7215 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:08:09.602  7215  7215 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:09.612  7191  7191 I SA      : [DM] FLOATING AMOLED FEATURE: true
,08-30 17:08:09.612  7191  7191 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-30 17:08:09.612  7191  7191 I SA      : [DM] TFT FEATURE: false
,08-30 17:08:09.612  7171  7171 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-30 17:08:09.612  7171  7171 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:08:09.612  7171  7171 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-30 17:08:09.612  7171  7171 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
08-30 17:08:09.612  1016  2050 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7232 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 17:08:09.612  7171  7171 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-30 17:08:09.612  7191  7191 I SA      : [DM] init START
,08-30 17:08:09.612  1016  2050 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-30 17:08:09.622  1016  2050 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:09.622  1016  2050 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:09.622  1016  2050 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:09.622  1016  2050 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:09.622  7191  7191 I SA      : [DM] This device is not a Vodafone
,08-30 17:08:09.632  1016  1495 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 17:08:09.632  7232  7232 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:09.632  1016  2050 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7247 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 17:08:09.632  7232  7232 D ActivityThread: Added TimaKeyStore provider
08-30 17:08:09.632  1016  2050 I ActivityManager: Killing 6676:com.sec.esdk.elm/u0a90 (adj 15): empty #21
,08-30 17:08:09.642  7247  7247 E Zygote  : MountEmulatedStorage()
08-30 17:08:09.642  7247  7247 I libpersona: KNOX_SDCARD checking this for 10008
08-30 17:08:09.642  1016  1028 D RCPManagerService: exchangeData() failure , invalid userId
08-30 17:08:09.642  7247  7247 I libpersona: KNOX_SDCARD not a persona
08-30 17:08:09.642  7247  7247 E Zygote  : v2
,08-30 17:08:09.642  7247  7247 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 17:08:09.642  1016  1415 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-30 17:08:09.642  1016  1415 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-30 17:08:09.642  1016  1415 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:09.642  1016  1415 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:09.642  1016  1415 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-30 17:08:09.642   296   296 E SMD     : DCD OFF,
,08-30 17:08:09.652  7247  7247 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 17:08:09.652  7247  7247 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-30 17:08:09.652  7191  7191 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-30 17:08:09.652  7191  7191 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,08-30 17:08:09.652  7191  7191 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,08-30 17:08:09.652  7191  7191 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,08-30 17:08:09.652  7191  7191 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,08-30 17:08:09.662  7020  7214 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
08-30 17:08:09.662   323   323 I art     : Explicit concurrent mark sweep GC freed 8684(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 615us total 25.822ms
,08-30 17:08:09.662  7191  7191 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
08-30 17:08:09.662  7191  7191 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
08-30 17:08:09.662  7191  7191 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 17:08:09.662  7191  7191 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
08-30 17:08:09.662  7191  7191 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
08-30 17:08:09.662  7191  7191 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
08-30 17:08:09.662  7191  7191 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
08-30 17:08:09.662  7191  7191 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
08-30 17:08:09.662  7191  7191 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,08-30 17:08:09.672  7191  7191 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
08-30 17:08:09.672  7191  7191 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
08-30 17:08:09.672  7191  7191 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
08-30 17:08:09.682  7191  7191 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
08-30 17:08:09.682  7191  7191 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
08-30 17:08:09.682   333   333 I ServiceManager: Waiting for service AtCmdFwd...
08-30 17:08:09.682   323   323 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 587us total 17.300ms
,08-30 17:08:09.682  7247  7247 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:08:09.682  7247  7247 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:09.682  7191  7191 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-30 17:08:09.682  7191  7191 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
08-30 17:08:09.682  7191  7191 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-30 17:08:09.682  7191  7191 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,08-30 17:08:09.682  7191  7191 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
08-30 17:08:09.682  7191  7191 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,08-30 17:08:09.682  7191  7191 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
08-30 17:08:09.682  7191  7191 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
,08-30 17:08:09.682  7191  7191 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-30 17:08:09.692  1016  1029 I ActivityManager: Killing 6692:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,08-30 17:08:09.692  7191  7191 I SA      : [SCU] isHaveSA() - false
08-30 17:08:09.692  7191  7191 I SA      : support phone number id : false
08-30 17:08:09.692  7191  7191 I SA      : [DM] Supports Ref Jpn : true
,08-30 17:08:09.692  7191  7191 I SA      : [DM] init END
,08-30 17:08:09.692  7191  7191 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-30 17:08:09.692   323   323 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 581us total 16.671ms
,08-30 17:08:09.702  7191  7191 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-30 17:08:09.702  7191  7191 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-30 17:08:09.702  7138  7197 W art     : Verification of void com.android.email.activity.MessageListItemOuterContainer.<init>(android.content.Context) took 113.725ms
,08-30 17:08:09.732  7191  7191 I SA      : [SLFUCHKMGR] constructor called
,08-30 17:08:09.742  7215  7215 D BadgeProvider: onCreate
,08-30 17:08:09.742  7215  7215 D BadgeProvider: DatabaseHelper
,08-30 17:08:09.752  7191  7191 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-30 17:08:09.752  7191  7191 I SA      : [OR] == isSIMCardReady false ==
,08-30 17:08:09.762  1016  1495 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 17:08:09.762  7191  7191 I SA      : [SCU] == networkStateCheck == false
08-30 17:08:09.762  7191  7191 I SA      : [OR] onReceive END
,08-30 17:08:09.762  7215  7230 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-30 17:08:09.772  1016  1029 I ActivityManager: Killing 6517:com.android.calendar/u0a131 (adj 15): empty #21
,08-30 17:08:09.782  1225  1225 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:08:09.782  1016  1498 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 17:08:09.782  7215  7224 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-30 17:08:09.782  1499  1499 D Launcher.Model: reloadBadges entered.
08-30 17:08:09.782  7215  7224 D BadgeProvider: sendNotify, [notify] : null
08-30 17:08:09.782  7215  7224 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-30 17:08:09.782  7215  7224 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-30 17:08:09.782  7215  7224 D BadgeProvider: update, [UpdateCount] : 1
,08-30 17:08:09.792  1016  2050 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-30 17:08:09.792  1016  2050 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:09.792  1016  2050 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:09.792  1016  2050 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:09.792  1016  2050 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:09.802  7266  7266 E Zygote  : MountEmulatedStorage()
,08-30 17:08:09.802  7266  7266 E Zygote  : v2
,08-30 17:08:09.812  7266  7266 I libpersona: KNOX_SDCARD checking this for 10009
08-30 17:08:09.812  7266  7266 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:09.812  7266  7266 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:08:09.812  7266  7266 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 17:08:09.812  7266  7266 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
08-30 17:08:09.812  1016  2050 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7266 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,08-30 17:08:09.812  1016  2050 I ActivityManager: Killing 6024:com.android.defcontainer/u0a3 (adj 15): empty #21
08-30 17:08:09.812  1016  2050 I ActivityManager: Killing 6713:com.google.android.gms:car/u0a11 (adj 15): empty #22
,08-30 17:08:09.832  7266  7266 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:09.832  7266  7266 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:09.862  2868  2868 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 30 17:08:09 GMT+02:00 2016
,08-30 17:08:09.862  1016  1495 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-30 17:08:09.862  1016  1495 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-30 17:08:09.862  1016  1495 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:09.862  1016  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:09.862  1016  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-30 17:08:09.862   291   291 I WVCdm   : CdmEngine::CloseSession
,08-30 17:08:09.872  1016  1514 I ActivityManager: Killing 5842:com.android.vending/u0a26 (adj 15): empty #21
,08-30 17:08:09.872   291   291 I WVCdm   : L3 Terminate.
,08-30 17:08:09.872  2868  2868 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-30 17:08:09.872  2868  2868 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-30 17:08:09.882  2868  2868 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-30 17:08:09.882  2868  2868 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-30 17:08:09.892  2868  7282 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-30 17:08:09.892  2868  7282 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-30 17:08:09.892  2868  7282 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-30 17:08:09.902  2868  7282 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-30 17:08:09.902  2868  2868 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-30 17:08:09.932  1016  1498 I ActivityManager: Killing 6987:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,08-30 17:08:09.952  1016  2050 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 17:08:09.952  1016  2050 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-30 17:08:09.952  1016  2050 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:09.952  1016  2050 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:09.952  1016  2050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:09.962  1016  2050 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-30 17:08:09.962  4791  7284 I iu.SyncManager: SYNC; picasa accounts
,08-30 17:08:09.962  1016  2050 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-30 17:08:09.962  1016  2050 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:09.962  1016  2050 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:09.962  1016  2050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:09.982  1016  1134 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-30 17:08:09.992  1016  1495 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-30 17:08:09.992  1016  1495 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-30 17:08:09.992  1016  1495 D SecContentProvider2: mCursor = null
,08-30 17:08:09.992  1016  1495 D WifiService: setWifiEnabled: true pid=6765, uid=10171
08-30 17:08:09.992  4791  4791 D NetworkLogImpl: Loaded NetworkSpeedPredictor
08-30 17:08:09.992  1016  1495 W ActivityManager: Permission Denial: getCurrentUser() from pid=6765, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-30 17:08:09.992  1016  1495 W WifiService: Failed getting userId using ActivityManagerNative
08-30 17:08:09.992  1016  1495 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6765, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-30 17:08:09.992  1016  1495 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-30 17:08:09.992  1016  1495 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-30 17:08:09.992  1016  1495 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-30 17:08:09.992  1016  1495 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-30 17:08:09.992  1016  1495 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-30 17:08:09.992  1016  1495 D SettingsProvider: name = wifi_on
,08-30 17:08:10.002  1016  1126 E WifiHW  : ##################### set firmware type 0 #####################
,08-30 17:08:10.002  1969  6844 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-30 17:08:10.002  1969  6844 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 17:08:10.002  1969  6844 I System.out: (HTTPLog)-Static: isShipBuild true
08-30 17:08:10.002  1969  6844 I System.out: (HTTPLog)-Thread-267-236658558: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-30 17:08:10.002  1969  6844 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 17:08:10.012   285  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-30 17:08:10.012   285  1011 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-30 17:08:10.012  1969  6844 W GLSUser : [AppCertManager] IOException while requesting key: 
,08-30 17:08:10.032  1016  1134 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,08-30 17:08:10.032  1016  1134 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-30 17:08:10.032  1016  1323 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-30 17:08:10.042  1016  1134 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-30 17:08:10.052  1969  2170 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-30 17:08:10.062  1969  2170 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-30 17:08:10.082  1969  2170 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-30 17:08:06.148+0200, stopTime=2016-08-30 17:08:10.094+0200, duration=3946ms
,08-30 17:08:10.082  1969  7290 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 17:08:10.082   285  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
,08-30 17:08:10.082   285  1011 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-30 17:08:10.102  1969  1969 E ctxmgr  : [BaseServerTask]Server task (FetchAclSet) got error response.
,08-30 17:08:10.122  1969  2170 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-30 17:08:10.132  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-30 17:08:10.182  7232  7232 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-30 17:08:10.182  7232  7232 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-30 17:08:10.182  7232  7232 I GAv4    :   adb logcat -s GAv4
,08-30 17:08:10.182   258   513 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-30 17:08:10.182   258   513 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 17:08:10.182  7232  7299 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-30 17:08:10.192   258   513 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-30 17:08:10.192   258   513 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 17:08:10.192  7232  7299 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-30 17:08:10.202   258   513 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-30 17:08:10.202   258   513 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 17:08:10.202  7232  7301 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-30 17:08:10.202   258   513 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-30 17:08:10.202   258   513 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 17:08:10.202  7232  7301 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-30 17:08:10.212  7232  7232 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-30 17:08:10.212  1016  1029 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-30 17:08:10.232  7232  7232 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-30 17:08:10.242  7232  7302 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-30 17:08:10.402  1016  1044 D Tethering: interfaceAdded wlan0
,08-30 17:08:10.412  1016  1129 E Tethering: No numeric data
,08-30 17:08:10.412  1016  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-30 17:08:10.422  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 17:08:10.412  1016  1129 D Tethering: clearTetheredNotification()
08-30 17:08:10.422  1016  1123 V NetworkStats: performPollLocked(flags=0x1)
08-30 17:08:10.422  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 17:08:10.422  1016  1044 D Tethering: interfaceStatusChanged wlan0, false
08-30 17:08:10.422  1016  1129 D Tethering: InitialState.processMessage what=4
08-30 17:08:10.422  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:10.422  1016  1044 D Tethering: interfaceAdded p2p0
08-30 17:08:10.422  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 17:08:10.422  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-30 17:08:10.422  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-30 17:08:10.422  1177  1177 D HotspotTile: updateTetherState():false, false
,08-30 17:08:10.422  1016  1123 V NetworkStats: performPollLocked() took 8ms
08-30 17:08:10.422   285  1015 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-30 17:08:10.422  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:10.422   285  1015 D SoftapController: Softap fwReload - Ok
,08-30 17:08:10.432  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:10.432  1016  1129 E Tethering: No numeric data
,08-30 17:08:10.432  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:10.432  1016  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 17:08:10.432  1016  1129 D Tethering: clearTetheredNotification()
,08-30 17:08:10.432   285  1015 D CommandListener: Setting iface cfg
08-30 17:08:10.432   285  1015 D CommandListener: Trying to bring down wlan0
,08-30 17:08:10.432  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:10.432  1016  1123 V NetworkStats: performPollLocked(flags=0x1)
,08-30 17:08:10.432  1016  1044 D Tethering: p2p0 is not a tetherable iface, ignoring
08-30 17:08:10.432  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 17:08:10.432  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 17:08:10.432   285  1015 D CommandListener: Clearing all IP addresses on wlan0
,08-30 17:08:10.432  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-30 17:08:10.432  1177  1177 D HotspotTile: updateTetherState():false, false
,08-30 17:08:10.432  1016  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 17:08:10.432  1016  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-30 17:08:10.432  1016  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-30 17:08:10.432  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:10.432  1016  1123 V NetworkStats: performPollLocked() took 7ms
,08-30 17:08:10.442  1016  1126 E WifiHW  : supplicant_name : p2p_supplicant
,08-30 17:08:10.442  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:10.442  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:10.442  1016  1126 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-30 17:08:10.442  1016  1126 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,08-30 17:08:10.442  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:08:10.442  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-30 17:08:10.442  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:10.442  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:10.442  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:10.442  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:10.452  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 17:08:10.452  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 17:08:10.452  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-30 17:08:10.452  1177  1755 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-30 17:08:10.452  1177  1177 D HotspotTile: onReceive : 2, 0
,08-30 17:08:10.452  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:10.462  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-30 17:08:10.462  1016  1415 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:08:10.472  1016  1415 W ActivityManager: userId = 0, bbcId = -10000,
08-30 17:08:10.482  1016  1415 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:10.482  1016  1415 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-30 17:08:10.502  7323  7323 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-30 17:08:10.502  7323  7323 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-30 17:08:10.512  7323  7323 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-30 17:08:10.522  7232  7232 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-30 17:08:10.552  7323  7323 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
08-30 17:08:10.552  7232  7232 I cr.library_loader: Time to load native libraries: 9 ms (timestamps 6056-6065)
08-30 17:08:10.552  7232  7232 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-30 17:08:10.552   371   371 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7323
08-30 17:08:10.552   371   371 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C,
08-30 17:08:10.552  7323  7323 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-30 17:08:10.552  7323  7323 I wpa_supplicant: ssSupport state is = 1
08-30 17:08:10.552  7323  7323 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-30 17:08:10.552  7323  7323 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-30 17:08:10.552   371   371 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7323
08-30 17:08:10.552   371   371 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,08-30 17:08:10.562  7232  7232 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1321bf27},
08-30 17:08:10.562  7232  7232 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-30 17:08:10.562  7232  7232 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-30 17:08:10.582  7232  7232 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-30 17:08:10.582  7232  7232 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 17:08:10.582  7232  7232 E SysUtils: ApplicationContext is null in ApplicationStatus,
,08-30 17:08:10.602  7232  7232 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
08-30 17:08:10.602  7232  7232 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-30 17:08:10.602  7232  7232 I Adreno-EGL: Build Date: 04/06/15 Mon
08-30 17:08:10.602  7232  7232 I Adreno-EGL: Local Branch: 
08-30 17:08:10.602  7232  7232 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-30 17:08:10.602  7232  7232 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-30 17:08:10.602  7232  7232 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-30 17:08:10.682   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,08-30 17:08:10.712   371   371 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,08-30 17:08:10.712  7323  7323 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed,
,08-30 17:08:10.732  7232  7339 W cr.media: Requires BLUETOOTH permission
,08-30 17:08:10.752  1016  1536 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-30 17:08:10.762  7232  7232 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-30 17:08:10.772  7323  7323 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-30 17:08:10.772  7323  7323 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-30 17:08:10.772  7232  7232 I NSApplication: Starting up...,
,08-30 17:08:10.772  1016  1514 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
08-30 17:08:10.782  1016  1495 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-30 17:08:10.782  7323  7323 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-30 17:08:10.782   371   371 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7323
08-30 17:08:10.782   371   371 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-30 17:08:10.782  7323  7323 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running,
08-30 17:08:10.782  7323  7323 I wpa_supplicant: ssSupport state is = 1
08-30 17:08:10.782  7323  7323 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-30 17:08:10.782  7323  7323 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 17:08:10.782  7323  7323 E wpa_supplicant: SIM READ ERROR
08-30 17:08:10.782  7323  7323 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 17:08:10.782  7323  7323 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-30 17:08:10.782  7323  7323 E wpa_supplicant: SIM READ ERROR
08-30 17:08:10.782  7323  7323 I wpa_supplicant: Blacklist: Clear (all) 
08-30 17:08:10.792  7323  7323 I wpa_supplicant: wpa_default_ap_write_once
08-30 17:08:10.792  7323  7323 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-30 17:08:10.792  7323  7323 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 17:08:10.792  7323  7323 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-30 17:08:10.792  7323  7323 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 17:08:10.792  7323  7323 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 17:08:10.792  1016  1028 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-30 17:08:10.792  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-30 17:08:10.792  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:10.792  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:10.792  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:10.792  7323  7323 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 17:08:10.792  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 17:08:10.792  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 17:08:10.792  1016  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-30 17:08:10.802  7345  7345 E Zygote  : MountEmulatedStorage()
08-30 17:08:10.802  7345  7345 E Zygote  : v2
08-30 17:08:10.802  7345  7345 I libpersona: KNOX_SDCARD checking this for 10117
08-30 17:08:10.802  7345  7345 I libpersona: KNOX_SDCARD not a persona
08-30 17:08:10.802  7345  7345 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 17:08:10.802  7345  7345 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 17:08:10.812  7345  7345 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-30 17:08:10.812  1016  1028 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7345 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-30 17:08:10.812  1016  1028 I ActivityManager: Killing 7004:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #21
,08-30 17:08:10.822  7323  7323 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-30 17:08:10.832  7345  7345 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:10.842  7345  7345 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:10.852  7345  7345 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 17:08:11.022  7323  7323 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-30 17:08:11.032  7323  7323 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-30 17:08:11.042  7323  7323 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-30 17:08:11.042   371   371 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7323
08-30 17:08:11.042   371   371 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,08-30 17:08:11.042  7323  7323 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running,
08-30 17:08:11.042  7323  7323 I wpa_supplicant: ssSupport state is = 1
,08-30 17:08:11.042  7323  7323 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-30 17:08:11.042  7323  7323 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-30 17:08:11.052  7323  7323 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-30 17:08:11.052   371   371 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7323
08-30 17:08:11.052   371   371 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C,
08-30 17:08:11.052  7323  7323 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-30 17:08:11.052  7323  7323 I wpa_supplicant: ssSupport state is = 1
08-30 17:08:11.052  7323  7323 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 17:08:11.052  7323  7323 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 17:08:11.052  7323  7323 E wpa_supplicant: SIM READ ERROR
08-30 17:08:11.052  7323  7323 I wpa_supplicant: wpa_default_ap_write_once
08-30 17:08:11.052  7323  7323 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-30 17:08:11.052  7323  7323 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 17:08:11.062  1016  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 17:08:11.062  1016  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-30 17:08:11.062  1016  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
08-30 17:08:11.062  1016  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 17:08:11.062  1016  1044 D Tethering: interfaceStatusChanged p2p0, false
08-30 17:08:11.062  1016  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-30 17:08:11.172  7323  7323 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-30 17:08:11.172  7323  7323 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-30 17:08:11.232  1016  1415 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-30 17:08:11.232  1016  1415 I ActivityManager: Killing 6883:com.android.settings/1000 (adj 15): empty #21
,08-30 17:08:11.242  1016  2050 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-30 17:08:11.242  1016  2050 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 17:08:11.242  1016  2050 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:11.242  1016  2050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:11.242  1016  2050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-30 17:08:11.252  1595  1595 I Hs20UtilService: Starting #12
08-30 17:08:11.252  1595  1633 I Hs20UtilService: Message received 5011
08-30 17:08:11.252  7323  7323 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
08-30 17:08:11.252  7323  7323 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-30 17:08:11.252  7323  7323 I wpa_supplicant: Skip scan - bUseNetwork false
,08-30 17:08:11.252  6569  6569 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-30 17:08:11.252  6569  6569 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-30 17:08:11.252  6569  6569 D SecurityLogAgent: StateMachine : Current State = 1
08-30 17:08:11.252  6569  6569 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 17:08:11.412  1016  1044 D Tethering: interfaceLinkStateChanged p2p0, false
,08-30 17:08:11.412  1016  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-30 17:08:11.412  1016  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-30 17:08:11.452  1016  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-30 17:08:11.452  1016  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-30 17:08:11.452  7323  7323 I wpa_supplicant: HOTSPOT20_ENABLE called
08-30 17:08:11.452  7323  7323 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 17:08:11.452  7323  7323 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 17:08:11.452  7323  7323 E wpa_supplicant: SIM READ ERROR
08-30 17:08:11.452  7323  7323 I wpa_supplicant: Blacklist: Clear (all) 
,08-30 17:08:11.492  7323  7323 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-30 17:08:11.492  7323  7323 I wpa_supplicant: Skip scan - bUseNetwork false,
08-30 17:08:11.492  1016  1126 D WifiConfigStore: Loading config and enabling all networks ,
,08-30 17:08:11.492  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:08:11.492  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 17:08:11.492  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:11.492  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-30 17:08:11.492  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:11.492  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-30 17:08:11.492  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 17:08:11.492  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-30 17:08:11.492  1177  1755 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-30 17:08:11.492  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-30 17:08:11.502  1177  1177 D HotspotTile: onReceive : 3, 0
,08-30 17:08:11.502  6765  6765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:11.502  1016  1126 E WifiConfigStore: Not a HS20
,08-30 17:08:11.502  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:11.502  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:11.502  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:11.502  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:11.502  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:08:11.502  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:11.502  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:11.502  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:08:11.502  1016  1126 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-30 17:08:11.502  6765  6765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:11.502  6765  6765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:08:11.502  6765  6765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 17:08:11.502  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:11.502  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:11.502  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:11.502  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:11.502  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:08:11.502  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:11.502  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:11.502  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:08:11.502  6765  6765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:11.502  6765  6765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:08:11.512  1016  1126 D WifiNative-wlan0: callSECApiInt - ID [65]
08-30 17:08:11.512  1016  2050 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 17:08:11.512  1016  2050 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 17:08:11.512  1016  2050 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:11.512  1016  2050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:11.512  1016  2050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 17:08:11.512  1016  1126 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-30 17:08:11.512  7323  7323 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-30 17:08:11.512  7323  7323 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-30 17:08:11.512  7323  7323 I wpa_supplicant: reset timer : RESET_TIMER 0
08-30 17:08:11.512  7323  7323 I wpa_supplicant: P2P: Current p2p state = IDLE
08-30 17:08:11.512  7323  7323 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-30 17:08:11.512  7323  7323 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-30 17:08:11.512  7323  7323 I wpa_supplicant: First Scan Start
08-30 17:08:11.512  7323  7323 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-30 17:08:11.522  1595  1595 I Hs20UtilService: Starting #13
,08-30 17:08:11.522  1595  1633 I Hs20UtilService: Message received 5011
,08-30 17:08:11.522  1016  1126 D WifiNative-wlan0: Setting external_sim to 1
,08-30 17:08:11.522  1016  1126 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 17:08:11.522  1016  1126 I WifiNative-HAL: startHal
08-30 17:08:11.522  1016  1126 E wifi    : getStaticLongField sWifiHalHandle 0x9eeb988c
08-30 17:08:11.522  1016  1126 I WifiNative-HAL: Could not start hal
,08-30 17:08:11.522  7020  7020 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 17:08:11.522  6569  6569 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-30 17:08:11.522  6569  6569 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-30 17:08:11.522  6569  6569 D SecurityLogAgent: StateMachine : Current State = 1
08-30 17:08:11.522  6569  6569 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 17:08:11.522  1016  1126 E WifiNative-wlan0: do suspend true
,08-30 17:08:11.532  1016  1125 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-30 17:08:11.532   285  1015 D CommandListener: Setting iface cfg
08-30 17:08:11.532   285  1015 D CommandListener: Trying to bring up p2p0
,08-30 17:08:11.532  1016  1125 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-30 17:08:11.532  1016  1125 D WifiP2pService: P2pEnablingState
08-30 17:08:11.532  1016  1125 D WifiP2pService: P2pEnablingState{ what=147457 }
08-30 17:08:11.532  1016  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-30 17:08:11.532  1016  1016 D WifiScanningService: SCAN_AVAILABLE : 3
08-30 17:08:11.532  1016  1016 D RttService: SCAN_AVAILABLE : 3
,08-30 17:08:11.532  1016  1149 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:11.532  1016  1149 I WifiNative-HAL: startHal
08-30 17:08:11.532  1016  1149 E wifi    : getStaticLongField sWifiHalHandle 0x9ddba9bc
08-30 17:08:11.532  1016  1149 I WifiNative-HAL: Could not start hal
08-30 17:08:11.532  1016  1149 E WifiScanningService: could not start HAL
08-30 17:08:11.532  1016  1150 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 17:08:11.542  1016  1125 D WifiP2pService: P2p socket connection successful
,08-30 17:08:11.542  7323  7323 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-30 17:08:11.542  1016  1125 D WifiP2pService: P2pEnabledState
,08-30 17:08:11.542  7323  7323 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-30 17:08:11.542  1016  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-30 17:08:11.542  1016  1016 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED,
,08-30 17:08:11.542  7323  7323 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-30 17:08:11.542  1016  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true,
08-30 17:08:11.542  1016  1126 E WifiStateMachine: Failed to set frequency band 0
08-30 17:08:11.542  1016  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-30 17:08:11.542  1016  1128 E ConnectivityService: updateNetworkInfo()
08-30 17:08:11.542  1016  1047 D WifiDisplayController: disconnect
08-30 17:08:11.542  1016  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-30 17:08:11.542  1016  1047 D WifiDisplayController: updateConnection
08-30 17:08:11.542  1016  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-30 17:08:11.542  1016  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 17:08:11.542  1016  1126 E WifiNative-wlan0: invaild command id : 215
,08-30 17:08:11.542  1016  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-30 17:08:11.542  1016  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 17:08:11.542  1016  1126 D SecContentProvider2: mCursor = null
,08-30 17:08:11.552  1016  1125 D WifiNative-p2p0: p2pGetDeviceAddress
08-30 17:08:11.552  1016  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:08:11.552  1016  1125 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
08-30 17:08:11.552  1016  1047 D WifiDisplayAdapter: onP2pDisconnected
,08-30 17:08:11.552  1016  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-30 17:08:11.552  1016  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
08-30 17:08:11.552  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-30 17:08:11.552  1016  1415 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0},
08-30 17:08:11.552  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-30 17:08:11.552  1016  1042 D ActivityManager: startProcessLocked calleePkgName: com.android.settings, hostingType: broadcast,
,08-30 17:08:11.552  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-30 17:08:11.552  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:11.552  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:11.552  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:11.572  7374  7374 E Zygote  : MountEmulatedStorage()
,08-30 17:08:11.572  7374  7374 I libpersona: KNOX_SDCARD checking this for 1000
08-30 17:08:11.572  7374  7374 E Zygote  : v2
08-30 17:08:11.572  7374  7374 I libpersona: KNOX_SDCARD not a persona
08-30 17:08:11.572  7374  7374 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:08:11.572  1016  1042 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.nearby.MountReceiver: pid=7374 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-30 17:08:11.572  7374  7374 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 17:08:11.572  7374  7374 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 17:08:11.572  1016  1125 D WifiP2pService: DeviceAddress: 0a:76:28
08-30 17:08:11.572  1016  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 17:08:11.572  1016  1126 D SecContentProvider2: mCursor = null
,08-30 17:08:11.572  1016  1047 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-30 17:08:11.572  1016  1047 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-30 17:08:11.572  1016  1047 D WifiDisplayController:  primary type: 10-0050F204-5
08-30 17:08:11.572  1016  1047 D WifiDisplayController:  secondary type: null
08-30 17:08:11.572  1016  1047 D WifiDisplayController:  wps: 0
08-30 17:08:11.572  1016  1047 D WifiDisplayController:  grpcapab: 0
08-30 17:08:11.572  1016  1047 D WifiDisplayController:  devcapab: 0
08-30 17:08:11.572  1016  1047 D WifiDisplayController:  status: 3
08-30 17:08:11.572  1016  1047 D WifiDisplayController:  wfdInfo: null
08-30 17:08:11.572  1016  1047 D WifiDisplayController:  groupownerAddress: null
08-30 17:08:11.572  1016  1047 D WifiDisplayController:  GOdeviceName: null
08-30 17:08:11.572  1016  1047 D WifiDisplayController:  interfaceAddress: 
08-30 17:08:11.572  1016  1047 D WifiDisplayController:  SConnectInfo : null
,08-30 17:08:11.592  1016  1125 D WifiP2pService: sending p2p persistent groups changed broadcast,
,08-30 17:08:11.592  1016  1125 D WifiP2pService: InactiveState
08-30 17:08:11.592  1016  1125 D WifiP2pService: InactiveState{ what=143376 }
,08-30 17:08:11.592  1016  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-30 17:08:11.592  7323  7323 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
08-30 17:08:11.592  1016  1125 D WifiP2pService: InactiveState{ what=143376 }
08-30 17:08:11.592  1016  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-30 17:08:11.602  7374  7374 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:11.602  7374  7374 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:11.612  7374  7374 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-30 17:08:11.622  7374  7374 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-30 17:08:11.622  7374  7374 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-30 17:08:11.622  7374  7374 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 17:08:11.622  7374  7374 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 17:08:11.622  7374  7374 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 17:08:11.652  7374  7374 D MySettingsProvider: DatabaseHelper(Context context):DATABASE_VERSION=1
,08-30 17:08:11.652  7374  7374 E SQLiteLog: (283) recovered 10 frames from WAL file /data/data/com.android.settings/databases/mysettings.db-wal
,08-30 17:08:11.652  7374  7374 D MySettingsProvider: onCreate():(mDB == null)? false:true  =true
,08-30 17:08:11.682   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 17:08:11.682  7374  7374 D NearbySettings: MountReceiver.onReceive - Create HandlerThread
,08-30 17:08:11.682  7374  7374 D NearbySettings: MountReceiver.onReceive - Start HandlerThread
08-30 17:08:11.682  7374  7374 D NearbySettings: MountReceiver.onReceive - Create mPrefHandler
,08-30 17:08:11.682  7374  7374 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-30 17:08:11.682  7374  7374 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 17:08:11.692  7374  7374 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 17:08:11.692  7374  7374 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-30 17:08:11.692  7374  7374 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-30 17:08:11.692  7374  7374 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-30 17:08:11.692  1016  1415 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-30 17:08:11.692  1016  1415 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:11.692  1016  1415 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:11.692  7374  7390 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-30 17:08:11.692  1016  1415 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:11.692  1016  1415 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:11.712  7393  7393 E Zygote  : MountEmulatedStorage()
,08-30 17:08:11.712  7393  7393 I libpersona: KNOX_SDCARD checking this for 10064
08-30 17:08:11.712  7393  7393 E Zygote  : v2
08-30 17:08:11.712  7393  7393 I libpersona: KNOX_SDCARD not a persona
08-30 17:08:11.712  7393  7393 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:08:11.712  1016  1415 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7393 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 17:08:11.712  7393  7393 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 17:08:11.712  1016  1415 I ActivityManager: Killing 6906:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
08-30 17:08:11.712  7393  7393 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:08:11.742  7393  7393 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:11.742  7393  7393 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:11.752  7393  7393 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-30 17:08:11.762  7393  7393 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 17:08:11.772  7393  7393 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-30 17:08:11.802  7393  7393 D FileShare-Client: Outbound.stopDelayTimer - 
,08-30 17:08:11.802  1016  1497 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-30 17:08:11.802  1016  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:11.802  1016  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:11.802  1016  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:11.802  1016  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:11.812  7408  7408 E Zygote  : MountEmulatedStorage()
,08-30 17:08:11.812  7408  7408 E Zygote  : v2
08-30 17:08:11.812  7408  7408 I libpersona: KNOX_SDCARD checking this for 10065
08-30 17:08:11.812  7408  7408 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:11.822  1016  1497 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7408 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-30 17:08:11.822  7408  7408 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 17:08:11.822  1016  1497 I ActivityManager: Killing 7044:com.android.bluetooth/1002 (adj 15): empty #21
,08-30 17:08:11.822  7408  7408 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 17:08:11.822  7408  7408 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:08:11.842  7408  7408 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:11.842  7408  7408 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:11.862  7408  7408 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 17:08:11.872  1016  1323 I ActivityManager: Killing 6922:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,08-30 17:08:12.302  1016  1514 I art     : Explicit concurrent mark sweep GC freed 44134(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/36MB, paused 2.383ms total 153.371ms
,08-30 17:08:12.312  1969  2170 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,08-30 17:08:12.312  1969  2170 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,08-30 17:08:12.642   296   296 E SMD     : DCD OFF
,08-30 17:08:12.682   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,08-30 17:08:12.762  7323  7323 I wpa_supplicant: nl80211: Received scan results (21 BSSes)
,08-30 17:08:12.762  7323  7323 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-30 17:08:12.762  7323  7323 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-30 17:08:12.762  7323  7323 I wpa_supplicant: Trying to associate with  'G700'
08-30 17:08:12.762  7323  7323 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,08-30 17:08:12.762  7323  7323 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-30 17:08:12.762  1016  7371 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-30 17:08:12.772  1016  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 17:08:12.772  1016  1126 D SecContentProvider2: mCursor = null
,08-30 17:08:12.882  7323  7323 E wpa_supplicant: Cmd 35605 not handled
,08-30 17:08:12.882  7323  7323 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-30 17:08:12.882  7323  7323 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,08-30 17:08:12.882  7323  7323 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-30 17:08:12.882  7323  7323 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-30 17:08:12.882  7323  7323 I wpa_supplicant: Associated with F4.99.3E
08-30 17:08:12.882  7323  7323 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-30 17:08:12.882  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 17:08:12.882  7323  7323 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-30 17:08:12.882  1016  1044 D Tethering: interfaceStatusChanged wlan0, false
08-30 17:08:12.882  7323  7323 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-30 17:08:12.882  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-30 17:08:12.882  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 17:08:12.882  1016  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-30 17:08:12.882  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-30 17:08:12.882  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, true
,08-30 17:08:12.882  1016  1044 D Tethering: interfaceStatusChanged wlan0, true
,08-30 17:08:12.882  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-30 17:08:12.882  1016  1129 E Tethering: No numeric data
,08-30 17:08:12.882  1016  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-30 17:08:12.882  1016  1129 D Tethering: clearTetheredNotification()
,08-30 17:08:12.892  1016  1123 V NetworkStats: performPollLocked(flags=0x1)
08-30 17:08:12.892  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:12.892  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-30 17:08:12.892  1177  1177 D HotspotTile: updateTetherState():false, false
,08-30 17:08:12.892  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 17:08:12.892  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 17:08:12.892  7323  7323 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-30 17:08:12.892  7323  7323 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-30 17:08:12.892  7323  7323 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE,
08-30 17:08:12.892  1016  1123 V NetworkStats: performPollLocked() took 8ms
08-30 17:08:12.892  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:12.902  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:12.902  7323  7323 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-30 17:08:12.902  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:12.902  7323  7323 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-30 17:08:12.902  7323  7323 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,08-30 17:08:12.902  7323  7323 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-30 17:08:12.902  7323  7323 I wpa_supplicant: Blacklist: Clear (temp) 
,08-30 17:08:12.902  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-30 17:08:12.902  7323  7323 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-30 17:08:12.902  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, true
08-30 17:08:12.902  1016  1044 D Tethering: interfaceStatusChanged wlan0, true
08-30 17:08:12.902  1016  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-30 17:08:12.902  1016  1126 D SecContentProvider2: mCursor = null
,08-30 17:08:12.912  1016  1126 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-30 17:08:12.912  1016  1126 E WifiConfigStore: setLastSelectedConfiguration -1
,08-30 17:08:12.922  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
,08-30 17:08:12.922  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-30 17:08:12.922  1016  1126 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-30 17:08:12.922  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-30 17:08:12.922  1016  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 17:08:12.922  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:12.922  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:12.922  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:12.922  1016  1128 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-30 17:08:12.922  1016  1128 E ConnectivityService: updateNetworkInfo()
08-30 17:08:12.922  1016  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 17:08:12.922  1016  1415 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 17:08:12.922  1016  1415 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-30 17:08:12.932  1016  1415 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:12.932  1016  1415 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:12.932  1016  1415 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 17:08:12.932  7374  7374 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-30 17:08:12.932  7374  7374 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 17:08:12.932  7374  7374 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-30 17:08:12.942  1595  1595 I Hs20UtilService: Starting #14
,08-30 17:08:12.942  7374  7374 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-30 17:08:12.942  7374  7374 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 17:08:12.942  7374  7374 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-30 17:08:12.942  1595  1633 I Hs20UtilService: Message received 5007
08-30 17:08:12.942  1016  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 17:08:12.942  7374  7390 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 17:08:12.952   285  1015 D CommandListener: Setting iface cfg,
,08-30 17:08:12.952  1016  1126 E WifiStateMachine: Start Dhcp Watchdog 2
,08-30 17:08:12.962  1016  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-30 17:08:12.962  1016  1126 D SecContentProvider2: mCursor = null
,08-30 17:08:12.962  1016  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-30 17:08:12.962  1016  1126 D SecContentProvider2: mCursor = null
,08-30 17:08:12.972  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 17:08:12.972  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-30 17:08:12.972  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:12.972  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:12.972  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:12.972  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:12.982  1016  1126 E WifiNative-wlan0: do suspend false
,08-30 17:08:12.982  1016  1125 D WifiP2pService: InactiveState{ what=143375 }
,08-30 17:08:12.982  1016  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 17:08:12.982  1016  1126 D SecContentProvider2: mCursor = null
,08-30 17:08:12.992  1016  1125 D WifiP2pService: P2pEnabledState{ what=143375 },
,08-30 17:08:13.012  1016  1028 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-30 17:08:13.012  1016  1028 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-30 17:08:13.012  1016  1028 D SecContentProvider2: mCursor = null
,08-30 17:08:13.012  1016  1028 D WifiService: setWifiEnabled: false pid=6765, uid=10171,
08-30 17:08:13.012  1016  1028 D SettingsProvider: name = wifi_on
,08-30 17:08:13.012  1016  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 17:08:13.022  1016  1126 E WifiNative-wlan0: do suspend true,
,08-30 17:08:13.052  1016  1125 D WifiP2pService: InactiveState{ what=143375 },
08-30 17:08:13.052  1016  1125 D WifiP2pService: P2pEnabledState{ what=143375 },
,08-30 17:08:13.052  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-30 17:08:13.052  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-30 17:08:13.052  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:13.052  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,08-30 17:08:13.052  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:13.052  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:13.062   285  1015 D CommandListener: Clearing all IP addresses on wlan0
,08-30 17:08:13.062  1016  1128 E ConnectivityService: updateNetworkInfo(),
,08-30 17:08:13.062  1016  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-30 17:08:13.062   285  1015 E Netd    : no such netId 503
08-30 17:08:13.062  1016  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
08-30 17:08:13.062  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-30 17:08:13.072  1016  1128 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '78 network destroy 503' failed with '400 78 destroyNetwork() failed (Machine is not on the network)'
08-30 17:08:13.072  1016  1128 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-30 17:08:13.072  1016  1128 V NetworkStats: updateIfacesLocked()
08-30 17:08:13.072  1016  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:13.072  1016  1128 V NetworkStats: performPollLocked(flags=0x1)
08-30 17:08:13.072  1016  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 17:08:13.072  1016  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 17:08:13.072  1016  1128 V NetworkStats: performPollLocked() took 5ms
08-30 17:08:13.072  1016  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:13.082  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-30 17:08:13.082  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 17:08:13.082  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:13.082  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:13.082  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:13.082  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:13.082  1016  1126 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 17:08:13.082  1016  1125 D WifiP2pService: InactiveState{ what=131204 }
08-30 17:08:13.082  1016  7424 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:13.082  1016  1125 D WifiP2pService: P2pEnabledState{ what=131204 }
08-30 17:08:13.082  1016  7424 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-30 17:08:13.082  1016  1415 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 17:08:13.082  1016  1128 D ConnectivityService: nai.networkMonitor.doQuit()
08-30 17:08:13.082  1016  1415 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-30 17:08:13.082  1016  1128 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-30 17:08:13.082  1016  1128 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
08-30 17:08:13.082  1016  1415 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:13.082  1016  1128 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-30 17:08:13.082  1016  1415 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:13.082  1016  1415 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 17:08:13.092  1016  1125 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-30 17:08:13.092  1016  1016 D WifiScanningService: SCAN_AVAILABLE : 1
08-30 17:08:13.092  1016  1149 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:13.092  1595  1595 I Hs20UtilService: Starting #15
08-30 17:08:13.092  1016  1016 D RttService: SCAN_AVAILABLE : 1
,08-30 17:08:13.092  1016  1150 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:13.092  1595  1633 I Hs20UtilService: Message received 5007
08-30 17:08:13.092  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:13.092  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:13.092  1016  1128 E ConnectivityService: updateNetworkInfo()
08-30 17:08:13.092  1016  1128 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-30 17:08:13.092  1016  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:08:13.092  1016  1047 D WifiDisplayAdapter: onP2pDisconnected
08-30 17:08:13.092  1016  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-30 17:08:13.092  1016  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-30 17:08:13.102  7374  7374 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-30 17:08:13.102  7374  7374 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-30 17:08:13.102  1016  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-30 17:08:13.102  1016  1128 E ConnectivityService: updateNetworkInfo()
,08-30 17:08:13.102  1016  1125 D WifiP2pService: P2pDisablingState
,08-30 17:08:13.102  1016  1125 D WifiP2pService: P2pDisablingState{ what=147458 }
08-30 17:08:13.102  7374  7374 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-30 17:08:13.102  1016  1125 D WifiP2pService: p2p socket connection lost
,08-30 17:08:13.102  1016  1126 E WifiNative-wlan0: do suspend true
08-30 17:08:13.102  1016  1125 D WifiP2pService: P2pDisabledState
,08-30 17:08:13.112  1016  1016 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-30 17:08:13.112  7374  7374 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED,
08-30 17:08:13.112  1016  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-30 17:08:13.112  7374  7374 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 17:08:13.112  1016  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-30 17:08:13.112  7374  7374 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-30 17:08:13.112  1016  1047 D WifiDisplayController: disconnect
08-30 17:08:13.112  7374  7390 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-30 17:08:13.112  1016  1047 D WifiDisplayController: updateConnection
08-30 17:08:13.112  1016  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 17:08:13.112  1016  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-30 17:08:13.112  1016  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-30 17:08:13.112  1016  1047 D WifiDisplayAdapter: onP2pDisconnected
08-30 17:08:13.112  1016  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-30 17:08:13.112  1016  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-30 17:08:13.112  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-30 17:08:13.112  1016  1495 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-30 17:08:13.112  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-30 17:08:13.122  7374  7374 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-30 17:08:13.122  7374  7374 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 17:08:13.122  7374  7374 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 17:08:13.132  7374  7374 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-30 17:08:13.132  7374  7374 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-30 17:08:13.132  7374  7374 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-30 17:08:13.132  7374  7390 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 17:08:13.132  7393  7393 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 17:08:13.132  7393  7393 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-30 17:08:13.132  7393  7393 D FileShare-Client: Outbound.stopDelayTimer - 
,08-30 17:08:13.142  7408  7408 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 17:08:13.152  1016  1125 D WifiP2pService: P2pDisabledState{ what=143375 },
08-30 17:08:13.152  1016  1125 D WifiP2pService: DefaultState{ what=143375 }
,08-30 17:08:13.152   285  1015 D CommandListener: Clearing all IP addresses on wlan0
,08-30 17:08:13.152  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 17:08:13.152  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-30 17:08:13.152  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:13.152  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:13.152  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:13.152  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:13.162  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-30 17:08:13.162  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 17:08:13.162  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-30 17:08:13.172  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:13.172  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:13.172  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:13.172  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:13.172  1016  1536 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 17:08:13.172  1016  1536 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 17:08:13.172  7323  7323 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
08-30 17:08:13.172  1016  1536 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:13.172  1016  1536 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:13.172  1016  1536 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 17:08:13.172  1595  1595 I Hs20UtilService: Starting #16
,08-30 17:08:13.172  1016  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 17:08:13.172  1016  1126 D SecContentProvider2: mCursor = null
,08-30 17:08:13.182  1595  1633 I Hs20UtilService: Message received 5007
,08-30 17:08:13.182  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:08:13.182  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-30 17:08:13.182  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:13.182  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:13.182  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:13.182  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:13.182  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 17:08:13.182  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-30 17:08:13.182  1177  1755 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-30 17:08:13.182  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-30 17:08:13.182  1177  1177 D HotspotTile: onReceive : 0, 0
,08-30 17:08:13.182  6765  6765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 17:08:13.182  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:13.182  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:13.182  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:13.182  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:08:13.182  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:08:13.182  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:13.182  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:13.182  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:08:13.182  6765  6765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:13.182  6765  6765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:08:13.182  6765  6765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 17:08:13.182  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:13.182  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:13.182  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:13.182  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:08:13.182  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:08:13.182  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:13.182  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:13.182  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:08:13.192  6765  6765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:13.192  6765  6765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:08:13.192  7374  7374 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-30 17:08:13.192  7374  7374 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 17:08:13.192  7374  7374 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 17:08:13.192  7374  7374 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED,
,08-30 17:08:13.202  7374  7374 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 17:08:13.202  7374  7374 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-30 17:08:13.202  7427  7427 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
08-30 17:08:13.202  7374  7390 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 17:08:13.202  7427  7427 I dhcpcd  : version 5.5.6 starting,
,08-30 17:08:13.202  1016  1415 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 17:08:13.202  7427  7427 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
08-30 17:08:13.202  1016  1415 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
08-30 17:08:13.212  1016  1415 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:13.212  1016  1415 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:13.212  1016  1415 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 17:08:13.212  1595  1595 I Hs20UtilService: Starting #17
08-30 17:08:13.212  6569  6569 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-30 17:08:13.212  6569  6569 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-30 17:08:13.212  6569  6569 D SecurityLogAgent: StateMachine : Current State = 1
08-30 17:08:13.212  6569  6569 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 17:08:13.212  1595  1633 I Hs20UtilService: Message received 5011
,08-30 17:08:13.252  7427  7427 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,08-30 17:08:13.252  7427  7427 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
,08-30 17:08:13.252  7427  7427 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,08-30 17:08:13.252  7427  7427 I dhcpcd  : bssid match
,08-30 17:08:13.252  7427  7427 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,08-30 17:08:13.302  7323  7323 I wpa_supplicant: Blacklist: Clear (all) 
,08-30 17:08:13.312  7427  7427 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
,08-30 17:08:13.372  7323  7323 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-30 17:08:13.372  1016  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 17:08:13.372  1016  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-30 17:08:13.372  1016  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-30 17:08:13.402  7323  7323 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1,
08-30 17:08:13.402  7323  7323 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-30 17:08:13.402  7323  7323 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-30 17:08:13.402  7323  7323 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-30 17:08:13.402  7323  7323 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-30 17:08:13.402  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, false,
,08-30 17:08:13.402  1016  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-30 17:08:13.402  1016  1129 D Tethering: InitialState.processMessage what=4,
,08-30 17:08:13.402  1016  1129 E Tethering: No numeric data
,08-30 17:08:13.412  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-30 17:08:13.412  1016  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 17:08:13.412  1016  1129 D Tethering: clearTetheredNotification()
,08-30 17:08:13.412  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-30 17:08:13.412  1177  1177 D HotspotTile: updateTetherState():false, false
,08-30 17:08:13.412  1016  1123 V NetworkStats: performPollLocked(flags=0x1)
,08-30 17:08:13.412  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:13.412  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-30 17:08:13.412  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 17:08:13.422  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, false
,08-30 17:08:13.422  1016  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-30 17:08:13.422  1016  1123 V NetworkStats: performPollLocked() took 8ms
,08-30 17:08:13.422  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-30 17:08:13.422  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:13.422  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 17:08:13.422  1016  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-30 17:08:13.422  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 17:08:13.422  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:13.422  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:13.482  7427  7427 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds,
,08-30 17:08:13.572  7323  7323 I wpa_supplicant: Blacklist: Clear (all) 
,08-30 17:08:13.622  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, false,
08-30 17:08:13.622  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 17:08:13.622  1016  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-30 17:08:13.622  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 17:08:13.622  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 17:08:13.622  1016  1044 D Tethering: interfaceStatusChanged wlan0, false
08-30 17:08:13.622  7323  7323 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-30 17:08:13.692   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-30 17:08:13.732  7020  7020 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
08-30 17:08:13.732  1016  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-30 17:08:13.732  1016  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-30 17:08:13.732  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
,08-30 17:08:13.732  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-30 17:08:13.732  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null,
,08-30 17:08:13.732  1177  1755 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi,
,08-30 17:08:13.732  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,08-30 17:08:13.742  1177  1177 D HotspotTile: onReceive : 1, 0,
,08-30 17:08:13.732  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,08-30 17:08:13.732  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:13.732  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:13.732  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 17:08:13.732  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-30 17:08:13.742  1969  2153 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:13.742  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:13.742  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:13.752  1016  1415 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-30 17:08:13.752  1016  1415 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 17:08:13.752  1016  1415 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:13.752  1016  1415 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:13.752  1016  1415 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 17:08:13.752  1595  1595 I Hs20UtilService: Starting #18,
,08-30 17:08:13.752  1595  1633 I Hs20UtilService: Message received 5011
,08-30 17:08:13.762  6569  6569 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-30 17:08:13.762  6569  6569 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-30 17:08:13.762  6569  6569 D SecurityLogAgent: StateMachine : Current State = 1
,08-30 17:08:13.762  6569  6569 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 17:08:13.972  1016  1028 I ActivityManager: Killing 7061:com.sec.pcw.device/1000 (adj 15): empty #21
,08-30 17:08:14.382   285  1009 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,08-30 17:08:14.382  1016  1044 D Tethering: interfaceRemoved wlan0
,08-30 17:08:14.382  1016  1044 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-30 17:08:14.512  1016  1044 D Tethering: interfaceRemoved p2p0
,08-30 17:08:14.512  1016  1044 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-30 17:08:14.922  1016  2050 I ActivityManager: Killing 7078:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,08-30 17:08:15.372  1016  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-30 17:08:15.662   296   296 E SMD     : DCD OFF
,08-30 17:08:16.012  6765  6822 D BluetoothAdapter: enable()
,08-30 17:08:16.012  1016  1323 W ActivityManager: Permission Denial: getCurrentUser() from pid=6765, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-30 17:08:16.012  1016  1323 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-30 17:08:16.012  1016  1323 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6765, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-30 17:08:16.012  1016  1323 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-30 17:08:16.012  1016  1323 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-30 17:08:16.012  1016  1323 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-30 17:08:16.012  1016  1323 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-30 17:08:16.012  1016  1323 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-30 17:08:16.012  1016  1323 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-30 17:08:16.012  1016  1323 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 17:08:16.022  1016  1323 D SettingsProvider: name = bluetooth_on
,08-30 17:08:16.022  1016  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-30 17:08:16.022  1016  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 17:08:16.022  1016  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,08-30 17:08:16.022  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-30 17:08:16.032  1016  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:16.032  1016  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-30 17:08:16.032  1016  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:16.032  1016  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-30 17:08:16.052  1016  1046 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7457 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a,
,08-30 17:08:16.052  7457  7457 E Zygote  : MountEmulatedStorage(),
,08-30 17:08:16.052  7457  7457 E Zygote  : v2,
08-30 17:08:16.052  7457  7457 I libpersona: KNOX_SDCARD checking this for 1002
,08-30 17:08:16.052  7457  7457 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:16.062  7457  7457 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-30 17:08:16.062  7457  7457 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-30 17:08:16.062  7457  7457 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-30 17:08:16.092  7457  7457 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:16.102  7457  7457 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:16.112  7457  7457 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-30 17:08:16.112  7457  7457 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 17:08:16.142  7457  7457 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-30 17:08:16.182  7457  7457 D BtSettings.ProfileConfig: Adding GattService
,08-30 17:08:16.182  7457  7457 D BtSettings.ProfileConfig: Adding HeadsetService
08-30 17:08:16.192  7457  7457 D BtSettings.ProfileConfig: Adding A2dpService
,08-30 17:08:16.192  7457  7457 D BtSettings.ProfileConfig: Adding HidService
08-30 17:08:16.192  7457  7457 D BtSettings.ProfileConfig: Adding HealthService
08-30 17:08:16.192  7457  7457 D BtSettings.ProfileConfig: Adding PanService
,08-30 17:08:16.192  7457  7457 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-30 17:08:16.192  7457  7457 D BtSettings.ProfileConfig: Adding SapService
08-30 17:08:16.192  7457  7457 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-30 17:08:16.192  7457  7457 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-30 17:08:16.192  7457  7457 D BtSettings.ProfileConfig: Adding SapClientService
08-30 17:08:16.192  7457  7457 D BtSettings.ProfileConfig: Adding HidDevService
08-30 17:08:16.192  7457  7457 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******,
,08-30 17:08:16.192  1016  2050 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService,
08-30 17:08:16.192  1016  2050 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-30 17:08:16.192  1016  2050 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-30 17:08:16.192  1016  2050 D SettingsProvider: selectionArgs: false
08-30 17:08:16.192  1016  2050 D SettingsProvider: selectionArgs: 1002
08-30 17:08:16.192  1016  2050 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-30 17:08:16.192  1016  2050 D SettingsProvider: ret = -1
,08-30 17:08:16.192  1016  1536 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,08-30 17:08:16.192  1016  1536 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-30 17:08:16.192  1016  1536 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:16.192  1016  1536 D SettingsProvider: selectionArgs: false
08-30 17:08:16.192  1016  1536 D SettingsProvider: selectionArgs: 1002,
08-30 17:08:16.192  1016  1536 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:16.192  1016  1536 D SettingsProvider: ret = -1
,08-30 17:08:16.202  1016  1134 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-30 17:08:16.202  1016  1134 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-30 17:08:16.202  1016  1134 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:16.202  1016  1134 D SettingsProvider: selectionArgs: false
08-30 17:08:16.202  1016  1134 D SettingsProvider: selectionArgs: 1002
,08-30 17:08:16.202  1016  1134 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:16.202  1016  1134 D SettingsProvider: ret = -1
,08-30 17:08:16.202  1016  1029 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,08-30 17:08:16.202  1016  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:16.202  1016  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
08-30 17:08:16.202  1016  1029 D SettingsProvider: selectionArgs: false
08-30 17:08:16.202  1016  1029 D SettingsProvider: selectionArgs: 1002
,08-30 17:08:16.202  1016  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-30 17:08:16.202  1016  1029 D SettingsProvider: ret = -1
,08-30 17:08:16.202  1016  1497 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService,
08-30 17:08:16.202  1016  1497 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:16.202  1016  1497 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:16.202  1016  1497 D SettingsProvider: selectionArgs: false
08-30 17:08:16.202  1016  1497 D SettingsProvider: selectionArgs: 1002,
,08-30 17:08:16.202  1016  1497 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
08-30 17:08:16.202  1016  1497 D SettingsProvider: ret = -1
08-30 17:08:16.202  1016  1323 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService,
08-30 17:08:16.202  1016  1323 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
08-30 17:08:16.202  1016  1323 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:16.202  1016  1323 D SettingsProvider: selectionArgs: false
08-30 17:08:16.202  1016  1323 D SettingsProvider: selectionArgs: 1002
,08-30 17:08:16.202  1016  1323 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:16.202  1016  1323 D SettingsProvider: ret = -1
08-30 17:08:16.202  1016  1495 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-30 17:08:16.202  1016  1495 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
08-30 17:08:16.202  1016  1495 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:16.202  1016  1495 D SettingsProvider: selectionArgs: false
08-30 17:08:16.202  1016  1495 D SettingsProvider: selectionArgs: 1002
,08-30 17:08:16.202  1016  1495 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:16.202  1016  1495 D SettingsProvider: ret = -1
08-30 17:08:16.202  1016  1514 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-30 17:08:16.202  1016  1514 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:16.202  1016  1514 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:16.212  1016  1514 D SettingsProvider: selectionArgs: false
08-30 17:08:16.212  1016  1514 D SettingsProvider: selectionArgs: 1002
,08-30 17:08:16.212  1016  1514 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:16.212  1016  1514 D SettingsProvider: ret = -1,
08-30 17:08:16.212  1016  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-30 17:08:16.212  1016  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:16.212  1016  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:16.212  1016  1028 D SettingsProvider: selectionArgs: false
,08-30 17:08:16.212  1016  1028 D SettingsProvider: selectionArgs: 1002
08-30 17:08:16.212  1016  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:16.212  1016  1028 D SettingsProvider: ret = -1
08-30 17:08:16.212  1016  1498 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:08:16.212  1016  1498 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:16.212  1016  1498 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-30 17:08:16.212  1016  1498 D SettingsProvider: selectionArgs: false
08-30 17:08:16.212  1016  1498 D SettingsProvider: selectionArgs: 1002
08-30 17:08:16.212  1016  1498 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
08-30 17:08:16.212  1016  1498 D SettingsProvider: ret = -1
08-30 17:08:16.212  1016  1415 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-30 17:08:16.212  1016  1415 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
08-30 17:08:16.212  1016  1415 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:16.212  1016  1415 D SettingsProvider: selectionArgs: false
08-30 17:08:16.212  1016  1415 D SettingsProvider: selectionArgs: 1002
08-30 17:08:16.212  1016  1415 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-30 17:08:16.212  1016  1415 D SettingsProvider: ret = -1
08-30 17:08:16.212  1016  2050 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-30 17:08:16.212  1016  2050 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:16.212  1016  2050 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-30 17:08:16.212  1016  2050 D SettingsProvider: selectionArgs: false
08-30 17:08:16.212  1016  2050 D SettingsProvider: selectionArgs: 1002
08-30 17:08:16.212  1016  2050 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:16.212  1016  2050 D SettingsProvider: ret = -1
,08-30 17:08:16.242  7457  7457 D BluetoothAdapterState: make
,08-30 17:08:16.252  7457  7457 I bluedroid: init
,08-30 17:08:16.252  7457  7472 I BluetoothAdapterState: Entering OffState
,08-30 17:08:16.262  7457  7457 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf,
,08-30 17:08:16.262  7457  7457 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-30 17:08:16.262  7457  7457 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 17:08:16.262  7457  7457 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-30 17:08:16.262  7457  7457 E bt-btif : btif_fetch_local_ble_random_bdaddr
08-30 17:08:16.262  7457  7457 I bluedroid: get_profile_interface socket
08-30 17:08:16.262  7457  7457 I bluedroid: get_profile_interface map_client
,08-30 17:08:16.262  7457  7457 D BluetoothAdapterService: checkAddrForIOP: Loading from conf,
,08-30 17:08:16.272  7457  7475 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-30 17:08:16.272  7457  7475 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-30 17:08:16.272  7457  7457 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:08:16.282  7457  7475 E BluetoothServiceJni: populateRssiValuesNative
,08-30 17:08:16.282  7457  7475 I bluedroid: getModelRssiValues
08-30 17:08:16.282  7457  7475 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-30 17:08:16.282  7457  7475 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
08-30 17:08:16.282  1016  1415 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-30 17:08:16.282  1016  1415 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 17:08:16.282  1016  1415 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:16.282  1016  1415 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:16.282  1016  1415 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:16.282  7457  7475 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-30 17:08:16.282  1016  1016 D SettingsProvider: name = bluetooth_name
,08-30 17:08:16.282  7457  7469 I bluedroid: config_hci_snoop_log
,08-30 17:08:16.282  1016  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,08-30 17:08:16.292  1016  1046 D BluetoothManagerService: Ble is always on enable gatt
,08-30 17:08:16.292  1016  1046 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-30 17:08:16.292  1016  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-30 17:08:16.292  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-30 17:08:16.292  1016  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 17:08:16.292  1016  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 17:08:16.302  7457  7457 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-30 17:08:16.302  1016  1046 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-30 17:08:16.312  7457  7472 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-30 17:08:16.312  7457  7472 D BluetoothAdapterProperties: Setting state to 11
,08-30 17:08:16.312  7457  7472 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-30 17:08:16.312  7457  7472 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-30 17:08:16.312  7457  7472 D BluetoothAdapterService: updateAdapterState state is 11
,08-30 17:08:16.312  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:08:16.312  1016  1016 I InputMethodManagerService: [BT Setting State] State =11
,08-30 17:08:16.322  7457  7472 D BluetoothAdapterService: Autoconnection is available 
08-30 17:08:16.322  7457  7472 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-30 17:08:16.322  1866  1866 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 17:08:16.322  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-30 17:08:16.322  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:16.322  1177  1177 D BluetoothTile:  getBluetoothState : 11
,08-30 17:08:16.332  7457  7472 D BluetoothSecureManager: getInstant: null
,08-30 17:08:16.332  7457  7472 D BluetoothSecureManager: calling getMethod for getService
08-30 17:08:16.332  7457  7472 D BluetoothSecureManager: calling getService
08-30 17:08:16.332  7457  7472 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@3156b75
,08-30 17:08:16.332  1016  1498 D BluetoothSecureManagerService: isSecureModeEnabled
08-30 17:08:16.332  1016  1498 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-30 17:08:16.332  1016  1536 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-30 17:08:16.332  7457  7472 D BtConfig.SecureMode: isSecureModeOn:false
08-30 17:08:16.332  7457  7472 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-30 17:08:16.332  1016  2050 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-30 17:08:16.332  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 17:08:16.332  7457  7472 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-30 17:08:16.332  7457  7472 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-30 17:08:16.332  7457  7472 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-30 17:08:16.332  7457  7472 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-30 17:08:16.332  1177  1755 D BluetoothTile:  handleUpdatestate:false name:null
08-30 17:08:16.332  1177  1755 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-30 17:08:16.332  7457  7472 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-30 17:08:16.332  7457  7472 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-30 17:08:16.332  7457  7472 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-30 17:08:16.332  7457  7472 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-30 17:08:16.332  7457  7472 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-30 17:08:16.332  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-30 17:08:16.332  7457  7472 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-30 17:08:16.332  7457  7472 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-30 17:08:16.332  7457  7472 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-30 17:08:16.342  7457  7472 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-30 17:08:16.342  7457  7472 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-30 17:08:16.342  7457  7472 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-30 17:08:16.342  7457  7472 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-30 17:08:16.342  7457  7472 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
,08-30 17:08:16.342  7457  7472 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-30 17:08:16.342  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:16.342  7457  7472 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:08:16.342  7457  7472 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-30 17:08:16.342  1016  1415 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 17:08:16.342  1016  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-30 17:08:16.342  1016  1415 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-30 17:08:16.342  7457  7472 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-30 17:08:16.342  7457  7472 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-30 17:08:16.342  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:16.342  7457  7472 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-30 17:08:16.342  1016  1415 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:16.342  1016  1415 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 17:08:16.352  1016  1415 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:16.352  7457  7472 D BluetoothBondStateMachine: make
,08-30 17:08:16.352  7374  7374 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 17:08:16.362  7457  7472 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,08-30 17:08:16.362  7457  7472 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-30 17:08:16.362  7457  7472 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-30 17:08:16.362  1016  1514 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:16.362  1016  1514 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-30 17:08:16.362  7457  7478 I BluetoothBondStateMachine: StableState(): Entering Off State
08-30 17:08:16.362  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:16.362  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
08-30 17:08:16.362  1016  1514 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:16.362  1016  1514 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:16.362  1016  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:16.362  1016  1495 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
08-30 17:08:16.362  7457  7457 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 17:08:16.362  7457  7457 D BtGatt.GattService: Received start request. Starting profile...
08-30 17:08:16.362  7457  7457 D BtGatt.GattService: start()
08-30 17:08:16.362  7457  7472 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,08-30 17:08:16.362  7457  7472 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-30 17:08:16.362  7457  7472 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-30 17:08:16.362  7457  7457 D BtGatt.GattService: start()
08-30 17:08:16.362  7457  7457 I bluedroid: get_profile_interface gatt
,08-30 17:08:16.362  7457  7457 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336d367
08-30 17:08:16.362  1016  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:16.362  7457  7457 D BtGatt.AdvertiseManager: advertise manager created
,08-30 17:08:16.362  1016  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:16.362  1016  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:16.362  1016  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:16.372  7480  7480 E Zygote  : MountEmulatedStorage()
,08-30 17:08:16.372  7480  7480 I libpersona: KNOX_SDCARD checking this for 10055
08-30 17:08:16.372  7480  7480 E Zygote  : v2
08-30 17:08:16.372  7480  7480 I libpersona: KNOX_SDCARD not a persona
08-30 17:08:16.372  7480  7480 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:08:16.382  7480  7480 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-30 17:08:16.382  1016  1495 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7480 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
08-30 17:08:16.382  7480  7480 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-30 17:08:16.382  1016  1497 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 17:08:16.382  1016  1497 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-30 17:08:16.382  1016  1497 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:16.382  1016  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:16.382  1016  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:16.392  7457  7472 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService,
08-30 17:08:16.392  7457  7472 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-30 17:08:16.392  1016  2050 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:16.392  7457  7472 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-30 17:08:16.392  1016  2050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 17:08:16.392  1016  2050 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:16.392  1016  2050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:16.392  1016  2050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:16.392  7457  7457 D BtGatt.GattService: mStartError = false
08-30 17:08:16.392  7457  7457 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336d367
,08-30 17:08:16.402  7457  7472 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-30 17:08:16.402  7457  7472 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 17:08:16.402  7457  7472 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-30 17:08:16.402  7457  7457 D HeadsetService: Received start request. Starting profile...
08-30 17:08:16.402  7457  7457 D HeadsetService: start()
,08-30 17:08:16.402  7457  7457 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-30 17:08:16.402  7457  7457 D HeadsetStateMachine: make
08-30 17:08:16.402  1016  1536 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:16.402  1016  1536 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-30 17:08:16.402  1016  1536 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:16.412  1016  1536 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:16.412  1016  1536 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 17:08:16.412  7457  7457 E HeadsetStateMachine: # of Max HF connection is 2
08-30 17:08:16.412  7457  7472 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-30 17:08:16.412  1016  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:16.412  7457  7472 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-30 17:08:16.412  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-30 17:08:16.412  7457  7472 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-30 17:08:16.412  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:16.412  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:16.412  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:16.412  7480  7480 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:16.412  7480  7480 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:16.412  7457  7472 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-30 17:08:16.412  7457  7472 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-30 17:08:16.412  1016  1497 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-30 17:08:16.412  7457  7472 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-30 17:08:16.412  1016  1497 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-30 17:08:16.412  1016  1497 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:16.412  1016  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:16.412  1016  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-30 17:08:16.422  1016  1495 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:16.422  1016  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-30 17:08:16.422  1016  1495 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:16.422  1016  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:16.422  1016  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:16.422  7457  7472 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-30 17:08:16.422  7457  7472 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-30 17:08:16.422  7457  7472 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-30 17:08:16.422  1016  1497 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-30 17:08:16.422  1016  1497 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-30 17:08:16.422  1016  1497 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:16.422  1016  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:16.422  1016  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-30 17:08:16.422  7457  7457 I bluedroid: get_profile_interface handsfree
08-30 17:08:16.422  1016  1514 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 17:08:16.432  1016  1514 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-30 17:08:16.432  1016  1514 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:16.432  1016  1514 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:16.432  1016  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:16.432  7457  7472 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-30 17:08:16.432  7457  7472 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-30 17:08:16.432  7457  7472 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-30 17:08:16.432  1016  1536 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:16.432  1016  1536 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-30 17:08:16.432  1016  1536 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:16.432  1016  1536 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:16.432  1016  1536 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:16.432  7457  7472 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-30 17:08:16.432  7457  7472 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-30 17:08:16.432  7457  7472 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-30 17:08:16.432  7457  7472 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:08:16.432  7457  7472 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:08:16.432  7457  7472 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:08:16.432  7457  7472 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-30 17:08:16.432  7457  7472 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-30 17:08:16.432  7457  7472 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-30 17:08:16.432  7457  7472 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-30 17:08:16.432  7457  7472 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-30 17:08:16.432  7457  7472 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-30 17:08:16.432  7457  7472 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-30 17:08:16.452  7457  7457 I DualScoManager: Instantiating Dual Sco Manager
,08-30 17:08:16.452  7457  7457 I DualScoManager: Set HeadsetServiceHelper
,08-30 17:08:16.452  7480  7480 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
08-30 17:08:16.452  7457  7457 D BluetoothAtMessage: createCMTIContentObservers
08-30 17:08:16.452  1016  1415 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-30 17:08:16.452  1016  1415 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:16.452  1016  1415 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:16.452  1016  1415 D SettingsProvider: selectionArgs: false
08-30 17:08:16.452  1016  1415 D SettingsProvider: selectionArgs: 1002
08-30 17:08:16.452  1016  1415 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:16.452  1016  1415 D SettingsProvider: ret = -1
,08-30 17:08:16.452  7457  7494 D HeadsetStateMachine: Enter Disconnected: -2
,08-30 17:08:16.452  7457  7457 D HeadsetService: mStartError = false
08-30 17:08:16.452  7457  7457 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336d367
,08-30 17:08:16.452  7457  7494 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-30 17:08:16.462  7457  7494 D HeadsetStateMachine: map size, before remove : 0
08-30 17:08:16.462  7457  7494 D HeadsetStateMachine: map size, after remove: 0
08-30 17:08:16.462  7457  7457 E BluetoothAdapterService(53924711): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-30 17:08:16.462  7457  7457 D A2dpService: Received start request. Starting profile...
,08-30 17:08:16.462  7457  7457 D A2dpService: start()
,08-30 17:08:16.462  7457  7457 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-30 17:08:16.462  7457  7457 I bluedroid: get_profile_interface avrcp
,08-30 17:08:16.472  7457  7457 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-30 17:08:16.472  7457  7457 D Avrcp   : Initialize Media Controller
,08-30 17:08:16.472  7457  7457 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-30 17:08:16.472  7457  7457 E Avrcp   : getActiveSessions
08-30 17:08:16.472  7457  7457 D Avrcp   : pick active media Controller
08-30 17:08:16.472  7457  7457 D Avrcp   : Get the active Media Controller 
,08-30 17:08:16.482  7480  7480 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-30 17:08:16.482  7480  7480 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-30 17:08:16.482  7480  7480 D UserAnalysis: Create SecureDbHelper
,08-30 17:08:16.482  7457  7457 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-30 17:08:16.492  7457  7500 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-30 17:08:16.492  7457  7457 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 17:08:16.492  7457  7457 D A2dpStateMachine: make
,08-30 17:08:16.492  7480  7480 D IntelligenceServiceApplication: onCreate()
,08-30 17:08:16.492  7457  7457 I bluedroid: get_profile_interface a2dp
,08-30 17:08:16.492  7457  7502 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-30 17:08:16.492  7457  7457 E bt-btif : warning : media task started media_task_refcnt 1 
,08-30 17:08:16.492  7457  7457 D A2dpService: mStartError = false
08-30 17:08:16.492  7457  7457 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336d367
08-30 17:08:16.492  7457  7501 D A2dpStateMachine: Enter Disconnected: -2
,08-30 17:08:16.502  7457  7457 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 17:08:16.502  1016  1514 I ActivityManager: Killing 7093:com.samsung.android.sconnect/u0a121 (adj 15): empty #21,
08-30 17:08:16.502  7480  7480 D IntelligenceServiceApplication: no applications having user consent for prediction
08-30 17:08:16.502  7457  7457 D HidService: Received start request. Starting profile...
,08-30 17:08:16.502  7457  7457 D HidService: start()
08-30 17:08:16.502  7457  7457 I bluedroid: get_profile_interface hidhost
08-30 17:08:16.502  7457  7457 D HidService: setHidService(): set to: null
08-30 17:08:16.502  7457  7457 D HidService: mStartError = false,
08-30 17:08:16.502  7457  7457 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336d367
08-30 17:08:16.502  7457  7457 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-30 17:08:16.502  7457  7457 D HealthService: Received start request. Starting profile...
08-30 17:08:16.502  7457  7457 D HealthService: start()
,08-30 17:08:16.512  1016  1495 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-30 17:08:16.512  7457  7457 I bluedroid: get_profile_interface health
08-30 17:08:16.512  7457  7457 D HealthService: mStartError = false
08-30 17:08:16.512  7457  7457 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336d367
08-30 17:08:16.512  7480  7480 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-30 17:08:16.512  7457  7457 D HeadsetStateMachine: Try to query the phonestate on bind
08-30 17:08:16.512  1449  3259 I Telecom : BluetoothPhoneService: queryPhoneState
,08-30 17:08:16.512  7457  7500 D BluetoothMediaBrowser: no now playing list
08-30 17:08:16.512  1449  1449 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-30 17:08:16.512  7457  7457 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-30 17:08:16.512  1449  1449 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-30 17:08:16.512  7457  7500 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
08-30 17:08:16.512  1449  3259 I Telecom : BluetoothPhoneService: Result of Message : true
08-30 17:08:16.512  7457  7457 D PanService: Received start request. Starting profile...
08-30 17:08:16.512  7457  7457 D PanService: start()
08-30 17:08:16.512  7457  7457 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 17:08:16.512  7457  7457 I bluedroid: get_profile_interface pan
08-30 17:08:16.512  7457  7457 D PanService: mStartError = false
08-30 17:08:16.512  7457  7457 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336d367
08-30 17:08:16.512  7457  7457 D HeadsetStateMachine: Proxy object connected
,08-30 17:08:16.522  7480  7480 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-30 17:08:16.522  7457  7457 D BluetoothMapService: Received start request. Starting profile...
08-30 17:08:16.522  7457  7457 D BluetoothMapService: start()
,08-30 17:08:16.522  7457  7457 D BluetoothMapService: mStartError = false
08-30 17:08:16.522  7457  7457 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336d367
08-30 17:08:16.522  7457  7457 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-30 17:08:16.522  7457  7494 D HeadsetStateMachine: Disconnected process message: 11
08-30 17:08:16.522  7457  7457 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-30 17:08:16.522  7457  7457 D SapService: Received start request. Starting profile...
08-30 17:08:16.522  7457  7457 D SapService: start()
08-30 17:08:16.522  7457  7457 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-30 17:08:16.522  7457  7457 I bluedroid: get_profile_interface sap
08-30 17:08:16.522  7457  7457 D SapService: mStartError = false
08-30 17:08:16.522  7457  7457 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336d367
08-30 17:08:16.522  7457  7457 D HeadsetPhoneState: sendDeviceDataStateChanged
08-30 17:08:16.522  7457  7494 D HeadsetStateMachine: Disconnected process message: 18
08-30 17:08:16.522  7457  7457 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-30 17:08:16.522  7457  7457 E BluetoothAdapterService(53924711): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-30 17:08:16.522  7457  7457 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-30 17:08:16.522  7457  7457 D BluetoothA2dp: Proxy object connected
08-30 17:08:16.522  7457  7457 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-30 17:08:16.522  7457  7457 E BluetoothAdapterService(53924711): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-30 17:08:16.522  7457  7457 E BluetoothAdapterService(53924711): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-30 17:08:16.522  7457  7494 D HeadsetStateMachine: Disconnected process message: 10
,08-30 17:08:16.522  7457  7494 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 17:08:16.522  7457  7494 D HeadsetStateMachine: Disconnected process message: 11
08-30 17:08:16.522  7457  7457 E BluetoothAdapterService(53924711): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,08-30 17:08:16.532  1016  1028 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-30 17:08:16.532  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:16.532  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:16.532  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:16.532  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:16.552  7508  7508 E Zygote  : MountEmulatedStorage()
08-30 17:08:16.552  7508  7508 E Zygote  : v2
08-30 17:08:16.552  7508  7508 I libpersona: KNOX_SDCARD checking this for 10105
08-30 17:08:16.552  7508  7508 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:16.552  7508  7508 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:08:16.552  7508  7508 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 17:08:16.552  1016  1028 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7508 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-30 17:08:16.562  7508  7508 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-30 17:08:16.562  7457  7457 E BluetoothAdapterService(53924711): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-30 17:08:16.582  7457  7457 E BluetoothAdapterService(53924711): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-30 17:08:16.582  7457  7457 E BluetoothAdapterService(53924711): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-30 17:08:16.592  7457  7472 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-30 17:08:16.592  7457  7472 I bluedroid: enable
,08-30 17:08:16.592  7457  7472 I bt_hci_bdroid: init
08-30 17:08:16.592  7457  7523 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-30 17:08:16.592  7508  7508 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:16.592  7508  7508 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:16.592  7457  7472 I bt_vendor: bt-vendor : init
,08-30 17:08:16.592  7457  7472 I bt_vendor: bt-vendor : get_bt_soc_type
08-30 17:08:16.592  7457  7472 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-30 17:08:16.592  7457  7472 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
,08-30 17:08:16.592  7457  7472 D bt_userial_mct: userial_init
,08-30 17:08:16.602  7457  7472 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-30 17:08:16.602  7457  7472 I bt_vendor: Starting hciattach daemon
08-30 17:08:16.602  7457  7472 I bt_vendor: try to set false
,08-30 17:08:16.602  7457  7472 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-30 17:08:16.602  7457  7472 I bt_vendor: Starting hciattach daemon
08-30 17:08:16.602  7457  7472 I bt_vendor: try to set true
,08-30 17:08:16.622  7529  7529 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-30 17:08:16.682  7535  7535 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-30 17:08:16.692  7538  7538 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-30 17:08:16.702  7540  7540 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-30 17:08:16.712  7541  7541 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-30 17:08:16.722  7542  7542 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 17:08:16.722  7543  7543 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-30 17:08:16.772   258   513 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-30 17:08:16.772   258   513 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 17:08:16.772  7508  7546 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-30 17:08:16.782   258   513 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-30 17:08:16.782   258   513 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 17:08:16.782  7508  7546 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-30 17:08:16.932  7508  7508 D StrictMode: StrictMode policy violation; ~duration=152 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at java.io.File.exists(File.java:363)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-30 17:08:16.932  7508  7508 D StrictMode: StrictMode policy violation; ~duration=151 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 17:08:16.932  7508  7508 D StrictMode: StrictMode policy violation; ~duration=150 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gm,m.map.m.e.a(PG:1515)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 17:08:16.932  7508  7508 D StrictMode: StrictMode policy violation; ~duration=146 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.q.e.b(PG:170)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08,-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 17:08:16.932  7508  7508 D StrictMode: StrictMode policy violation; ~duration=144 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.q.k.d(PG:583)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.q.e.b(PG:170)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 17:08:16.932  7508  7508 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at java.io.File.exists(File.java:363)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 17:08:16.932  7508  7508 D StrictMode: StrictMode policy violation; ~duration=122 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at java.io.File.exists(File.java:363)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 17:08:16.932  7508  7508 D StrictMode: StrictMode policy violation; ~duration=122 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 17:08:16.932  7508  7508 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 17:08:16.942  1016  1029 I ActivityManager: Killing 7103:com.sec.android.soagent/u0a31 (adj 15): empty #21
08-30 17:08:16.942  1969  1969 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-30 17:08:16.952  1969  1969 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-30 17:08:17.012  7508  7557 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.,
,08-30 17:08:17.022  7558  7558 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
,08-30 17:08:17.032  7559  7559 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-30 17:08:17.032  1016  2050 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
08-30 17:08:17.032  1016  2050 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:17.032  1016  2050 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
08-30 17:08:17.032  1016  2050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-30 17:08:17.072  7457  7472 I bt_vendor: bluetooth satus is on
,08-30 17:08:17.072  7457  7526 D bt_userial_mct: userial_open(port:0)
08-30 17:08:17.072  7457  7526 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-30 17:08:17.072  7457  7526 I bt_vendor: Done intiailizing UART
,08-30 17:08:17.072  7457  7526 I bt_vendor: Done intiailizing UART
,08-30 17:08:17.072  7457  7526 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
08-30 17:08:17.072  7457  7526 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-30 17:08:17.072  7457  7563 D bt_userial_mct: Entering userial_read_thread()
,08-30 17:08:17.072  7457  7523 I         : BTE_InitTraceLevels -- TRC_HCI
,08-30 17:08:17.072  7457  7523 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 17:08:17.072  7457  7523 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-30 17:08:17.072  7457  7523 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 17:08:17.072  7457  7523 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-30 17:08:17.082  7457  7523 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 17:08:17.082  7457  7523 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 17:08:17.082  7457  7523 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 17:08:17.082  7457  7523 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 17:08:17.082  7457  7523 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 17:08:17.082  7457  7523 I         : BTE_InitTraceLevels -- TRC_SAP
08-30 17:08:17.082  7457  7523 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 17:08:17.082  7457  7523 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 17:08:17.082  7457  7523 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 17:08:17.082  7457  7523 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 17:08:17.082  7457  7523 I         : BTE_InitTraceLevels -- TRC_BTIF
08-30 17:08:17.082  7457  7523 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-30 17:08:17.172  7457  7523 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-30 17:08:17.182  7457  7523 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa4310ed1 
,08-30 17:08:17.182  7457  7523 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa4310ed1 
,08-30 17:08:17.192  7457  7475 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-30 17:08:17.192  7457  7475 E bt-btif : Calling BTA_HhEnable
,08-30 17:08:17.202  7457  7475 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-30 17:08:17.202  7457  7475 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-30 17:08:17.202  7457  7475 E BluetoothServiceJni: populateRssiValuesNative
08-30 17:08:17.202  7457  7475 I bluedroid: getModelRssiValues
,08-30 17:08:17.202  7457  7475 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-30 17:08:17.202  7457  7475 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-30 17:08:17.202  1016  1016 D SettingsProvider: name = bluetooth_name
,08-30 17:08:17.202  7457  7475 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-30 17:08:17.212  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:17.212  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:17.212  7457  7475 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-30 17:08:17.212  7457  7475 D BluetoothAdapterProperties: Scan Mode:20
,08-30 17:08:17.212  7457  7475 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 17:08:17.212  7457  7475 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
,08-30 17:08:17.222  7457  7475 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,08-30 17:08:17.222  7457  7475 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,08-30 17:08:17.222  7457  7475 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,08-30 17:08:17.222  7457  7475 E bt-btif : btif_sock_init: !vhci_init
,08-30 17:08:17.222  7457  7475 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-30 17:08:17.222  7457  7475 D IOP_DB_BT: db_open: db_open : handle 2966167568l, read 13894 bytes onto local cache
,08-30 17:08:17.222  7457  7475 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-30 17:08:17.222  7457  7563 E bt_mct  : hci lib postload completed
,08-30 17:08:17.222  7457  7475 D IOP_DB_BT: db_query: result 1
08-30 17:08:17.222  7457  7475 I         : iop_db_open: iop_db_open status 0
,08-30 17:08:17.222  7457  7475 D bte_conf: Device ID record 1 : primary
08-30 17:08:17.222  7457  7475 D bte_conf:   vendorId            = 0075
08-30 17:08:17.222  7457  7475 D bte_conf:   vendorIdSource      = 0001
08-30 17:08:17.222  7457  7475 D bte_conf:   product             = 0100
08-30 17:08:17.222  7457  7475 D bte_conf:   version             = 0200
08-30 17:08:17.222  7457  7475 D bte_conf:   clientExecutableURL = 
08-30 17:08:17.222  7457  7475 D bte_conf:   serviceDescription  = 
08-30 17:08:17.222  7457  7475 D bte_conf:   documentationURL    = 
08-30 17:08:17.222  7457  7475 D bte_conf: bte_load_did_conf no section named DID2.
,08-30 17:08:17.222  7457  7475 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-30 17:08:17.232  7457  7472 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-30 17:08:17.232  7457  7472 D BluetoothAdapterProperties: ScanMode =  20
,08-30 17:08:17.232  7457  7472 D BluetoothAdapterProperties: State =  11
,08-30 17:08:17.232  1016  1514 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-30 17:08:17.232  7457  7472 D BluetoothAdapterProperties: Setting state to 12
,08-30 17:08:17.232  7457  7472 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-30 17:08:17.232  7457  7475 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-30 17:08:17.232  7457  7475 D BluetoothAdapterProperties: Scan Mode:21
08-30 17:08:17.232  7457  7475 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 17:08:17.232  1016  1498 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-30 17:08:17.242  1016  1498 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-30 17:08:17.242  1016  1498 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:17.242  1016  1498 D SettingsProvider: selectionArgs: false
08-30 17:08:17.242  1016  1498 D SettingsProvider: selectionArgs: 1002
08-30 17:08:17.242  1016  1498 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:17.242  1016  1498 D SettingsProvider: ret = -1
,08-30 17:08:17.242  7457  7472 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-30 17:08:17.242  7457  7472 D BluetoothAdapterService: updateAdapterState state is 12
,08-30 17:08:17.242  1016  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 17:08:17.242  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-30 17:08:17.252  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:17.252  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:17.252  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:17.252  7457  7472 D BluetoothAdapterService: Autoconnection is available 
,08-30 17:08:17.252  7457  7472 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
,08-30 17:08:17.252  7457  7472 D BluetoothAdapterService: starting service from this receiver
,08-30 17:08:17.252  7457  7471 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 17:08:17.262  1016  1497 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 17:08:17.262  1016  1497 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-30 17:08:17.262  1177  1200 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 17:08:17.262  1177  1200 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 17:08:17.262  6765  6811 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 17:08:17.262  6765  6811 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 17:08:17.262  1016  1497 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:17.262  1016  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:17.262  1016  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:17.272  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:17.272  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:17.272  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:17.272  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:08:17.272  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:17.272  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:17.272  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:17.272  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:08:17.272  7457  7472 I BluetoothAdapterState: Entering On State from state = 11
,08-30 17:08:17.272  1449  1457 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 17:08:17.272  1449  1457 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 17:08:17.272  6765  6765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:08:17.272  1449  1458 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:08:17.272  1016  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-30 17:08:17.272  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 17:08:17.282  1016  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:17.282  1016  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:17.282  1016  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:17.282  1449  1458 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 17:08:17.282  1016  1046 D BluetoothPan: Binding service...
,08-30 17:08:17.282  1016  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-30 17:08:17.282  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-30 17:08:17.282  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:17.282  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:17.282  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:17.282  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:08:17.282  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:17.282  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:17.282  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:17.282  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:08:17.282  1969  3046 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 17:08:17.282  1969  3046 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 17:08:17.282  7457  7566 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 17:08:17.282  7457  7566 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 17:08:17.282  7508  7518 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 17:08:17.282  7508  7518 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 17:08:17.282  1016  1046 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 17:08:17.282  7457  7457 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-30 17:08:17.282  1016  1046 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:08:17.292  1016  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-30 17:08:17.292  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 17:08:17.292  1016  1016 D BluetoothA2dp: Proxy object connected
,08-30 17:08:17.292  6765  6765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:08:17.292  1449  3259 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:08:17.292  1016  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-30 17:08:17.292  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 17:08:17.292  1016  1046 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:17.292  1016  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:17.292  1016  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:17.292  1449  3259 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 17:08:17.302  1473  1862 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:08:17.302  1016  1046 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-30 17:08:17.302  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 17:08:17.302  1016  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:17.302  1016  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:17.302  1016  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:17.302  1473  1862 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 17:08:17.302  7457  7457 I BluetoothPbapService: Handler(): got msg=1
,08-30 17:08:17.302  1016  1016 D BluetoothPan: BluetoothPAN Proxy object connected
,08-30 17:08:17.312  1016  1514 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-30 17:08:17.312  1449  1458 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:08:17.312  1016  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 17:08:17.312  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 17:08:17.312  1016  1046 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:17.312  1016  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:17.312  1016  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:17.312  1449  1458 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 17:08:17.312  1459  1472 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 17:08:17.312  1459  1472 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 17:08:17.312  7457  7568 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-30 17:08:17.312  1473  1489 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 17:08:17.322  1473  1489 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 17:08:17.322  1016  1046 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-30 17:08:17.322  1016  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 17:08:17.322  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 17:08:17.322  1016  1046 E BluetoothHeadset: BluetoothHeadset service is binded
08-30 17:08:17.322  1016  1046 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 17:08:17.322  1016  1046 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 17:08:17.322  1016  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-30 17:08:17.322  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-30 17:08:17.322  7457  7568 D BluetoothSocket: bindListen(): myUserId = 0
08-30 17:08:17.322  7457  7568 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 17:08:17.322  1177  1177 D BluetoothTile:  onBluetoothStateChange:
08-30 17:08:17.332  1449  1449 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@3461c855, true
08-30 17:08:17.332  1449  1449 D BluetoothHeadset: registerMessageListener
08-30 17:08:17.332  1866  1866 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
08-30 17:08:17.332  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-30 17:08:17.332  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:17.332  1177  1177 D BluetoothTile:  getBluetoothState : 12
,08-30 17:08:17.342  1177  1755 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 17:08:17.342  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:17.342  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-30 17:08:17.342  1016  1497 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 17:08:17.342  1016  1497 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-30 17:08:17.342  1016  1497 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:17.342  1016  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:17.342  1016  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:17.352  7457  7469 D HeadsetService: registerMessageListener
,08-30 17:08:17.352  1177  1755 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 17:08:17.352  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:17.352  1016  1016 I InputMethodManagerService: [BT Setting State] State =12
08-30 17:08:17.352  1016  1016 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-30 17:08:17.352  7457  7469 D HeadsetService: registerMessageListener
,08-30 17:08:17.352  7457  7494 D HeadsetStateMachine: Disconnected process message: 70
08-30 17:08:17.352  7457  7494 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@16e30d09
,08-30 17:08:17.362  7457  7569 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-30 17:08:17.362  7374  7374 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 17:08:17.362  1449  1449 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-30 17:08:17.362  1449  1449 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-30 17:08:17.362  7457  7568 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
,08-30 17:08:17.362  7457  7568 D BluetoothSocket: bindListen(), new LocalSocket 
08-30 17:08:17.362  7457  7568 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,08-30 17:08:17.362  7457  7568 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@a9b7b0e
,08-30 17:08:17.362  7457  7568 D BluetoothSocket: channel: 19
08-30 17:08:17.362  7457  7568 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-30 17:08:17.362  1016  1536 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 17:08:17.362  1016  1323 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-30 17:08:17.372  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 17:08:17.372  1449  1449 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-30 17:08:17.372  1449  1449 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-30 17:08:17.372  1449  1449 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
08-30 17:08:17.372  1016  1514 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-30 17:08:17.372  1016  1514 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-30 17:08:17.372  1177  1755 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 17:08:17.372  1016  1514 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:17.372  1016  1514 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:17.372  1016  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-30 17:08:17.382  7457  7569 D BluetoothSocket: bindListen(): myUserId = 0
08-30 17:08:17.382  7457  7569 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 17:08:17.382  7457  7494 D HeadsetStateMachine: Disconnected process message: 9
,08-30 17:08:17.382  7457  7494 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-30 17:08:17.392  7457  7569 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
08-30 17:08:17.392  7457  7569 D BluetoothSocket: bindListen(), new LocalSocket 
08-30 17:08:17.392  7457  7569 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-30 17:08:17.392  7457  7569 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1e85d92f
,08-30 17:08:17.392   291   702 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-30 17:08:17.392   291   702 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-30 17:08:17.392   291   702 V voice   : voice_set_parameters: exit with code(-2)
08-30 17:08:17.392   291   702 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-30 17:08:17.392   291   702 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-30 17:08:17.392   291   702 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-30 17:08:17.392   291   702 V audio_hw_primary: adev_set_parameters: exit
08-30 17:08:17.392  7457  7494 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-30 17:08:17.402  7457  7569 D BluetoothSocket: channel: 5
,08-30 17:08:17.412  7374  7374 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-30 17:08:17.422  7374  7374 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:08:17.422  1016  1498 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-30 17:08:17.422  1016  1498 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 17:08:17.422  1016  1498 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:17.422  1016  1498 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 17:08:17.422  1016  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:17.422  7374  7374 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-30 17:08:17.422  7374  7374 E BluetoothHeadset: BTStateChangeCB is registed
,08-30 17:08:17.432  7374  7374 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:08:17.432  1016  1028 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-30 17:08:17.432  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 17:08:17.432  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:17.432  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:17.432  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:17.432  7374  7374 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 17:08:17.432  7374  7374 D BluetoothMap: Create BluetoothMap proxy object,
,08-30 17:08:17.442  1016  1029 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,08-30 17:08:17.442  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-30 17:08:17.442  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:17.442  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:17.442  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:17.452  1016  1323 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,08-30 17:08:17.452  1016  1323 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-30 17:08:17.452  1016  1323 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:17.452  1016  1323 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:17.462  1016  1323 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:17.462  7374  7374 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,08-30 17:08:17.462  1016  1028 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-30 17:08:17.462  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-30 17:08:17.472  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:17.472  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:17.472  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:17.472  7374  7374 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-30 17:08:17.472  1016  1029 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-30 17:08:17.472  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-30 17:08:17.472  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:17.472  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:17.472  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:17.482  1016  1415 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-30 17:08:17.482  1016  1415 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-30 17:08:17.482  1016  1415 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:17.482  1016  1415 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:17.482  1016  1415 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:17.482  7374  7374 D LocalBluetoothProfileManager: PANU : true
,08-30 17:08:17.482  7374  7374 W LocalBluetoothProfileManager: Warning: SAP profile was previously added.
,08-30 17:08:17.482  7374  7374 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-30 17:08:17.492  7374  7374 D DockEventReceiver: finishStartingService: stopping service
,08-30 17:08:17.492  7374  7374 D BluetoothNotiBroadcastReceiver: onReceive
08-30 17:08:17.492  7374  7374 D BluetoothA2dp: Proxy object connected
08-30 17:08:17.492  7374  7374 D A2dpProfile: Bluetooth service connected
,08-30 17:08:17.502  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:08:17.502  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-30 17:08:17.502  7374  7374 D HeadsetProfile: Bluetooth service connected
,08-30 17:08:17.502  7374  7374 D BluetoothMap: Proxy object connected
,08-30 17:08:17.502  7374  7374 D MapProfile: Bluetooth service connected
08-30 17:08:17.502  7374  7374 D BluetoothMap: getConnectedDevices()
,08-30 17:08:17.512  7374  7374 D BluetoothPbap: Proxy object connected
,08-30 17:08:17.512  7374  7374 D PbapServerProfile: Bluetooth service connected
08-30 17:08:17.512  7374  7374 D Bluetoothsap: BluetoothSAP Proxy object connected
08-30 17:08:17.512  7374  7374 D SapProfile: Bluetooth service connected
08-30 17:08:17.512  7374  7374 D Bluetoothsap: getConnectedDevices()
,08-30 17:08:17.512  7374  7374 D BluetoothInputDevice: Proxy object connected
,08-30 17:08:17.512  7374  7374 D HidProfile: Bluetooth service connected
,08-30 17:08:17.512  7457  7457 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336d367
,08-30 17:08:17.512  7457  7457 D BtConfig.SecureMode: isSecureModeOn:false
,08-30 17:08:17.512  1016  1495 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:17.512  1016  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-30 17:08:17.512  1016  1495 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:17.522  1016  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 17:08:17.522  1016  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:17.532  1969  1969 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-30 17:08:17.532  1016  1323 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 17:08:17.532  1016  1323 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-30 17:08:17.542  7374  7374 D BluetoothPan: BluetoothPAN Proxy object connected
,08-30 17:08:17.542  7374  7374 D PanProfile: Bluetooth service connected
08-30 17:08:17.542  1016  1323 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:17.542  1016  1323 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:17.542  1016  1323 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:17.552  1969  7577 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-30 17:08:17.552  1969  1969 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-30 17:08:17.552  1016  1495 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:08:17.562  1016  1495 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:17.562  1016  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:17.562  1016  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:17.562  1016  3331 D SSRM:n  : SIOP:: AP = 370
,08-30 17:08:17.572  1016  2050 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-30 17:08:17.582  1016  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:08:17.582  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:17.582  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:17.582  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:17.592  1969  7577 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-30 17:08:17.592  7457  7581 D BluetoothSocket: bindListen(): myUserId = 0
,08-30 17:08:17.592  7457  7581 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 17:08:17.592  7457  7581 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
,08-30 17:08:17.592  7457  7581 D BluetoothSocket: bindListen(), new LocalSocket 
08-30 17:08:17.592  7457  7581 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,08-30 17:08:17.592  7457  7581 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@10825441
08-30 17:08:17.592  7457  7581 D BluetoothSocket: channel: 12
08-30 17:08:17.592  7457  7581 I BtOppRfcommListener: Accept thread started.
,08-30 17:08:18.662   296   296 E SMD     : DCD OFF,
,08-30 17:08:19.032  6765  6822 D BluetoothAdapter: disable()
,08-30 17:08:19.032  1016  1029 D SettingsProvider: name = bluetooth_on
,08-30 17:08:19.042  7457  7472 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-30 17:08:19.042  7457  7472 D BluetoothAdapterProperties: Setting state to 13
08-30 17:08:19.042  7457  7472 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 17:08:19.042  7457  7472 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-30 17:08:19.042  7457  7472 D BluetoothAdapterService: updateAdapterState state is 13
08-30 17:08:19.042  1016  1415 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:19.042  1016  1415 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-30 17:08:19.042  1016  1415 W ActivityManager: userId = 0, bbcId = -10000,
08-30 17:08:19.042  1016  1415 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:19.042  1016  1415 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:19.042  7457  7457 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-30 17:08:19.042  7457  7472 D BluetoothAdapterService: Autoconnection is available 
08-30 17:08:19.042  7457  7472 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-30 17:08:19.042  7457  7472 D BluetoothAdapterService: terminating service from this receiver
08-30 17:08:19.042  7457  7457 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@286fdde6, channel: 19, state: LISTENING
08-30 17:08:19.042  7457  7457 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@286fdde6, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@a9b7b0e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1321bf27mSocket: android.net.LocalSocket@2cc675d4 impl:android.net.LocalSocketImpl@3e5ef37d fd:FileDescriptor[74]
08-30 17:08:19.042  7457  7457 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2cc675d4 impl:android.net.LocalSocketImpl@3e5ef37d fd:FileDescriptor[74]
,08-30 17:08:19.042  1016  1536 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-30 17:08:19.052  1016  1536 W ActivityManager: userId = 0, bbcId = -10000,
08-30 17:08:19.052  1016  1536 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:19.052  1016  1536 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
,08-30 17:08:19.052  7457  7472 D BluetoothAdapterProperties: onBluetoothDisable()
,08-30 17:08:19.052  7457  7472 D BluetoothAdapterProperties: mDiscovering is false
,08-30 17:08:19.052  1016  1028 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled,
,08-30 17:08:19.052  7457  7472 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true,
,08-30 17:08:19.062  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:08:19.062  1016  1016 I InputMethodManagerService: [BT Setting State] State =13
,08-30 17:08:19.062  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-30 17:08:19.062  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-30 17:08:19.072  1177  1755 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 17:08:19.072  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:08:19.072  1177  1755 D BluetoothTile:  handleUpdatestate:false name:null
08-30 17:08:19.072  1177  1177 D BluetoothTile:  getBluetoothState : 13
,08-30 17:08:19.072  1866  1866 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 17:08:19.072  1016  1514 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 17:08:19.082  1016  1029 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false,
,08-30 17:08:19.082  7374  7374 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:19.082  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 17:08:19.082  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-30 17:08:19.082  1177  1755 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-30 17:08:19.082  6765  6765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 17:08:19.082  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:19.082  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:19.082  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:19.082  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:08:19.082  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:08:19.082  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:19.082  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:19.082  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:08:19.082  1016  1536 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 17:08:19.082  1016  1536 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-30 17:08:19.082  6765  6765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 17:08:19.082  6765  6765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:08:19.092  1016  1536 W ActivityManager: userId = 0, bbcId = -10000,
08-30 17:08:19.092  1016  1536 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:19.092  1016  1536 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,08-30 17:08:19.092  7457  7475 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-30 17:08:19.092  7457  7475 D BluetoothAdapterProperties: Scan Mode:20
,08-30 17:08:19.092  6765  6765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 17:08:19.092  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:19.092  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:19.092  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:19.092  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:08:19.092  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:08:19.092  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:19.092  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:19.092  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:08:19.092  7457  7472 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-30 17:08:19.092  7457  7472 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
08-30 17:08:19.092  7457  7472 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
08-30 17:08:19.102  6765  6765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:19.102  6765  6765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:08:19.102  7457  7472 E bt-btif : cmd socket is not created
08-30 17:08:19.102  7457  7472 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-30 17:08:19.102  7457  7581 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-30 17:08:19.102  7457  7523 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
,08-30 17:08:19.102  7457  7523 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-30 17:08:19.102  7457  7523 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 17:08:19.102  7457  7523 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-30 17:08:19.102  7457  7523 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-30 17:08:19.102  7374  7374 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 17:08:19.112  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:19.112  7457  7457 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@c4bf272, channel: 5, state: LISTENING
08-30 17:08:19.112  7457  7457 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@c4bf272, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1e85d92f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@166126c3mSocket: android.net.LocalSocket@1eff1b40 impl:android.net.LocalSocketImpl@6c4a79 fd:FileDescriptor[76]
08-30 17:08:19.112  7457  7457 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1eff1b40 impl:android.net.LocalSocketImpl@6c4a79 fd:FileDescriptor[76]
08-30 17:08:19.112  7457  7457 I BtOppRfcommListener: stopping Accept Thread
08-30 17:08:19.112  7457  7457 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3f62c3be, channel: 12, state: LISTENING
,08-30 17:08:19.112  7457  7457 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3f62c3be, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@10825441, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@37a56c1fmSocket: android.net.LocalSocket@175aab6c impl:android.net.LocalSocketImpl@135e1535 fd:FileDescriptor[79]
,08-30 17:08:19.112  7457  7457 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@175aab6c impl:android.net.LocalSocketImpl@135e1535 fd:FileDescriptor[79]
,08-30 17:08:19.112  7457  7581 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-30 17:08:19.112  1016  1029 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-30 17:08:19.112  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-30 17:08:19.112  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:19.112  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:19.112  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:19.112  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-30 17:08:19.122  7374  7374 D BluetoothPbap: Proxy object disconnected
08-30 17:08:19.122  7374  7374 D PbapServerProfile: Bluetooth service disconnected
,08-30 17:08:19.132  7457  7457 V BluetoothOppManager: cleanUp...
,08-30 17:08:19.132  7374  7374 D DockEventReceiver: finishStartingService: stopping service
,08-30 17:08:19.132  7374  7374 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 17:08:19.132  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:08:19.132  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-30 17:08:19.152  1969  1969 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-30 17:08:19.162  1969  1969 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-30 17:08:19.312  7457  7523 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-30 17:08:19.312  7457  7523 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 17:08:19.312  7457  7523 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 17:08:19.312  7457  7523 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 17:08:19.312  7457  7523 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 17:08:19.312  7457  7523 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 17:08:19.312  7457  7523 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 17:08:19.312  7457  7523 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 17:08:19.312  7457  7523 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 17:08:19.312  7457  7523 W bt-btif : ag scb idx 1 not allocated
08-30 17:08:19.312  7457  7523 W bt-btif : ag scb idx 2 not allocated
08-30 17:08:19.312  7457  7523 E bt-btif : BTA AG is already disabled, ignoring ...
08-30 17:08:19.312  7457  7563 I bt_userial_mct: exiting userial_read_thread
08-30 17:08:19.312  7457  7563 D bt_userial_mct: Leaving userial_evt_read_thread()
08-30 17:08:19.312  7457  7475 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-30 17:08:19.312  7457  7526 I bt_vendor: hw_epilog_process
08-30 17:08:19.312  7457  7475 D bt_userial_mct: userial_close
08-30 17:08:19.312  7457  7475 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-30 17:08:20.512  7457  7475 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-30 17:08:20.512  7457  7475 I bt_vendor: bluetooth satus is on
08-30 17:08:20.512  7457  7475 I bt_vendor: bt-vendor : resetting BT status
08-30 17:08:20.512  7457  7475 I bt_vendor: Starting hciattach daemon
08-30 17:08:20.512  7457  7475 I bt_vendor: try to set false
,08-30 17:08:20.512  7457  7475 I bt_vendor: Starting hciattach daemon
08-30 17:08:20.512  7457  7475 I bt_vendor: try to set false
,08-30 17:08:20.522  7457  7475 I bt_vendor: cleanup
08-30 17:08:20.522  7457  7523 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-30 17:08:20.522  7457  7475 I GKI_LINUX: GKI_exit_task 0 done
08-30 17:08:20.522  7457  7475 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-30 17:08:20.522  7457  7472 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-30 17:08:20.522  1016  2050 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:20.522  7457  7472 D BtConfig.SecureMode: isSecureModeOn:false
08-30 17:08:20.522  1016  2050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-30 17:08:20.522  7457  7472 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-30 17:08:20.522  1016  1495 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:20.522  7457  7472 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-30 17:08:20.522  1016  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-30 17:08:20.522  7457  7472 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-30 17:08:20.522  7457  7472 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-30 17:08:20.522  1016  2050 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:20.522  1016  2050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:20.522  1016  2050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 17:08:20.522  7457  7472 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService,
08-30 17:08:20.522  7457  7472 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-30 17:08:20.522  7457  7472 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-30 17:08:20.522  7457  7457 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 17:08:20.522  7457  7457 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 17:08:20.522  7457  7457 D BtGatt.GattService: stop()
08-30 17:08:20.522  7457  7457 D BtGatt.AdvertiseManager: advertise clients cleared
08-30 17:08:20.532  1016  1495 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:20.532  1016  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:20.532  1016  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 17:08:20.532  7457  7472 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-30 17:08:20.532  7457  7472 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-30 17:08:20.532  7457  7457 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336d367
08-30 17:08:20.532  7457  7472 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-30 17:08:20.532  7457  7457 D HeadsetService: Received stop request...Stopping profile...
08-30 17:08:20.532  1016  1514 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:20.532  1016  1514 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 17:08:20.532  1016  1514 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:20.532  1016  1514 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:20.532  1016  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:20.532  7457  7457 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336d367
,08-30 17:08:20.532  7457  7472 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-30 17:08:20.542  7457  7472 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 17:08:20.542  7457  7472 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-30 17:08:20.542  1016  1016 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-30 17:08:20.542  1016  1323 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:20.542  7374  7374 D HeadsetProfile: Bluetooth service disconnected
08-30 17:08:20.542  1016  1323 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-30 17:08:20.542  1016  1323 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:20.542  1016  1323 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 17:08:20.542  1016  1323 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:20.542  7457  7472 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-30 17:08:20.542  7457  7472 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-30 17:08:20.542  7457  7472 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-30 17:08:20.542  1016  1536 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:20.542  1016  1536 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-30 17:08:20.542  1016  1536 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:20.542  1016  1536 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 17:08:20.542  1016  1536 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 17:08:20.542  7457  7472 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-30 17:08:20.542  7457  7472 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-30 17:08:20.542  7457  7472 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-30 17:08:20.552  1016  1498 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:20.552  1016  1498 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-30 17:08:20.552  1016  1498 W ActivityManager: userId = 0, bbcId = -10000,
08-30 17:08:20.552  1016  1498 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:20.552  1016  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
,08-30 17:08:20.552  7457  7472 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-30 17:08:20.552  7457  7472 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 17:08:20.552  7457  7472 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-30 17:08:20.552  1016  1497 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:20.552  1016  1497 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-30 17:08:20.552  1016  1497 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:20.552  1016  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:20.552  1016  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:20.552  7457  7472 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService,
08-30 17:08:20.552  7457  7472 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-30 17:08:20.552  7457  7472 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-30 17:08:20.562  1016  1134 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:20.562  1016  1134 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-30 17:08:20.562  1016  1134 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:20.562  1016  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 17:08:20.562  1016  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:20.562  7457  7472 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-30 17:08:20.562  7457  7472 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-30 17:08:20.562  7457  7472 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-30 17:08:20.562  7457  7472 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:08:20.562  7457  7472 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:08:20.562  7457  7472 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:08:20.562  7457  7472 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-30 17:08:20.562  7457  7472 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-30 17:08:20.562  7457  7472 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-30 17:08:20.562  7457  7472 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-30 17:08:20.562  7457  7472 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-30 17:08:20.562  7457  7472 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-30 17:08:20.562  7457  7472 D BluetoothAdapterState: Stopping profile services that were post enabled
08-30 17:08:20.562  7457  7457 E BluetoothAdapterService(53924711): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-30 17:08:20.562  7457  7457 D A2dpService: Received stop request...Stopping profile...
,08-30 17:08:20.562  7457  7501 D A2dpStateMachine: Exit Disconnected: -1
,08-30 17:08:20.562  7457  7457 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336d367
,08-30 17:08:20.572  7457  7457 E BluetoothAdapterService(53924711): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,08-30 17:08:20.572  1016  1016 D BluetoothA2dp: Proxy object disconnected
08-30 17:08:20.572  1016  1016 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-30 17:08:20.572  7457  7457 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 17:08:20.572  7457  7457 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-30 17:08:20.572  7457  7457 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-30 17:08:20.572  7457  7457 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-30 17:08:20.572  7374  7374 D BluetoothA2dp: Proxy object disconnected
08-30 17:08:20.572  7374  7374 D A2dpProfile: Bluetooth service disconnected
,08-30 17:08:20.572  7457  7457 D HidService: Received stop request...Stopping profile...
,08-30 17:08:20.572  7457  7457 D HidService: Stopping Bluetooth HidService
,08-30 17:08:20.572  7457  7457 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 17:08:20.572  7457  7457 W bt-btif : cleanup: HH disabling or disabled already, status = 0
,08-30 17:08:20.572  7457  7457 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 17:08:20.572  7457  7457 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336d367
,08-30 17:08:20.582  7457  7457 D HealthService: Received stop request...Stopping profile...
,08-30 17:08:20.582  7457  7457 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336d367
08-30 17:08:20.582  7374  7374 D BluetoothInputDevice: Proxy object disconnected
08-30 17:08:20.582  7374  7374 D HidProfile: Bluetooth service disconnected
,08-30 17:08:20.582  7457  7457 D PanService: Received stop request...Stopping profile...
,08-30 17:08:20.582  7457  7457 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336d367
,08-30 17:08:20.582  1016  1016 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-30 17:08:20.582  7457  7457 D BluetoothMapService: Received stop request...Stopping profile...
,08-30 17:08:20.592  7374  7374 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 17:08:20.592  7374  7374 D PanProfile: Bluetooth service disconnected
,08-30 17:08:20.592  7457  7457 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336d367
,08-30 17:08:20.592  7457  7457 D SapService: Received stop request...Stopping profile...
,08-30 17:08:20.592  7457  7457 D SapService: Stopping Bluetooth SapService
,08-30 17:08:20.592  7457  7457 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336d367
,08-30 17:08:20.592  7457  7457 E BluetoothAdapterService(53924711): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-30 17:08:20.592  7457  7457 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 17:08:20.592  7457  7457 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-30 17:08:20.592  7457  7457 D BluetoothA2dp: Proxy object disconnected
08-30 17:08:20.592  7457  7457 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-30 17:08:20.592  7457  7502 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-30 17:08:20.602  7457  7457 I GKI_LINUX: GKI_exit_task 2 done
08-30 17:08:20.602  7457  7457 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-30 17:08:20.602  7457  7457 E BluetoothAdapterService(53924711): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-30 17:08:20.602  7457  7457 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 17:08:20.602  7457  7457 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-30 17:08:20.602  7457  7457 E BluetoothAdapterService(53924711): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-30 17:08:20.602  7457  7457 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 17:08:20.602  7457  7457 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-30 17:08:20.602  7457  7457 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 17:08:20.602  7457  7457 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-30 17:08:20.602  7457  7457 E BluetoothAdapterService(53924711): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-30 17:08:20.602  7457  7457 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 17:08:20.602  7457  7457 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-30 17:08:20.602  7457  7457 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 17:08:20.602  7457  7457 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 17:08:20.602  7374  7374 D BluetoothMap: Proxy object disconnected
08-30 17:08:20.602  7374  7374 D MapProfile: Bluetooth service disconnected
,08-30 17:08:20.602  7374  7374 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-30 17:08:20.602  7374  7374 D SapProfile: Bluetooth service disconnected
,08-30 17:08:20.602  7457  7457 E BluetoothAdapterService(53924711): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,08-30 17:08:20.602  7457  7457 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-30 17:08:20.602  7457  7457 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-30 17:08:20.602  7457  7457 E BluetoothAdapterService(53924711): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-30 17:08:20.602  7457  7457 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-30 17:08:20.602  7457  7457 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-30 17:08:20.602  7457  7472 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-30 17:08:20.602  7457  7472 D BluetoothAdapterProperties: Setting state to 10
08-30 17:08:20.602  7457  7472 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-30 17:08:20.602  7457  7472 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-30 17:08:20.602  7457  7472 D BluetoothAdapterService: updateAdapterState state is 10
,08-30 17:08:20.602  7457  7472 D BluetoothAdapterService: Autoconnection is available 
08-30 17:08:20.602  7457  7472 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-30 17:08:20.602  7457  7471 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 17:08:20.612  7457  7472 I BluetoothAdapterState: Entering OffState
,08-30 17:08:20.612  1177  1213 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 17:08:20.612  1177  1213 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 17:08:20.612  6765  6777 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 17:08:20.612  6765  6777 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 17:08:20.612  6765  6777 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-30 17:08:20.612  6765  6777 D BluetoothLeAdvertiser: Exit stop advertising
08-30 17:08:20.612  6765  6777 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-30 17:08:20.612  6765  6777 D BluetoothLeScanner: Exiting stopAllScan
08-30 17:08:20.612  7374  7382 D BluetoothPbap: onBluetoothStateChange: up=false
,08-30 17:08:20.612  1449  1457 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 17:08:20.612  1449  1457 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 17:08:20.612  7374  7592 D Bluetoothsap: onBluetoothStateChange: up=false
,08-30 17:08:20.612  7374  7592 D Bluetoothsap: Unbinding service...
,08-30 17:08:20.612  7374  7384 D BluetoothMap: onBluetoothStateChange: up=false
,08-30 17:08:20.622  1969  1984 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 17:08:20.622  1969  1984 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 17:08:20.622  7457  7570 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 17:08:20.622  7457  7570 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 17:08:20.622  7508  7525 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 17:08:20.622  7508  7525 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 17:08:20.622  1016  1046 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 17:08:20.622  7374  7382 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 17:08:20.622  7374  7382 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 17:08:20.622  7374  7592 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 17:08:20.622  1459  1472 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 17:08:20.622  1459  1472 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 17:08:20.622  1473  1774 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 17:08:20.622  1473  1774 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 17:08:20.632  7374  7382 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-30 17:08:20.632  1016  1046 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 17:08:20.632  1016  1046 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 17:08:20.632  1016  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-30 17:08:20.632  1016  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-30 17:08:20.642  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:08:20.642  1016  1016 I InputMethodManagerService: [BT Setting State] State =10
08-30 17:08:20.642  1016  1016 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-30 17:08:20.642  1177  1177 D BluetoothAdapter: 392681414: getState() :  mService = null. Returning STATE_OFF
,08-30 17:08:20.642  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-30 17:08:20.652  1177  1755 D BluetoothAdapter: 392681414: getState() :  mService = null. Returning STATE_OFF
,08-30 17:08:20.652  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:08:20.652  1177  1177 D BluetoothTile:  getBluetoothState : 10
,08-30 17:08:20.652  1177  1755 D BluetoothAdapter: 392681414: getState() :  mService = null. Returning STATE_OFF
,08-30 17:08:20.652  1177  1177 D BluetoothAdapter: 392681414: getState() :  mService = null. Returning STATE_OFF
,08-30 17:08:20.652  1177  1177 D BluetoothAdapter: 392681414: getState() :  mService = null. Returning STATE_OFF
,08-30 17:08:20.652  1016  1536 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 17:08:20.652  1016  1323 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-30 17:08:20.652  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-30 17:08:20.662  1866  1866 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 17:08:20.662  1969  2153 D BluetoothAdapter: 870300143: getState() :  mService = null. Returning STATE_OFF
08-30 17:08:20.662  1969  2153 D BluetoothAdapter: 870300143: getState() :  mService = null. Returning STATE_OFF
,08-30 17:08:20.662  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:20.662  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:20.662  7374  7374 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:08:20.662  1016  1028 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 17:08:20.662  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-30 17:08:20.672  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:20.672  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 17:08:20.672  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:20.672  7374  7374 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 17:08:20.672  7457  7475 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-30 17:08:20.672  7457  7457 I GKI_LINUX: GKI_exit_task 1 done
08-30 17:08:20.672  7457  7457 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-30 17:08:20.672  7457  7457 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-30 17:08:20.672  1016  1497 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-30 17:08:20.672  1016  1497 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-30 17:08:20.682  1016  1497 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:20.682  1016  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:20.682  1016  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-30 17:08:20.682  7457  7457 I art     : System.exit called, status: 0
,08-30 17:08:20.682  7457  7457 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 17:08:20.682  7374  7374 D DockEventReceiver: finishStartingService: stopping service
,08-30 17:08:20.692  7374  7374 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 17:08:20.692  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:20.692  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-30 17:08:20.812  1016  1323 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-30 17:08:20.812  1016  1323 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-30 17:08:20.812  1016  1323 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-30 17:08:20.812  1016  1323 D BatteryService: stay LED for fully charged
08-30 17:08:20.812  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-30 17:08:20.812  1016  1016 I MotionRecognitionService: Plugged,
08-30 17:08:20.812  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-30 17:08:20.812  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-30 17:08:20.812  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-30 17:08:20.822  1431  1431 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-30 17:08:20.822  1431  1431 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-30 17:08:20.832  1016  1497 I ActivityManager: Process com.android.bluetooth (pid 7457)(adj 0) has died(36,722)
,08-30 17:08:20.842  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-30 17:08:20.842  1177  1177 D SViewCoverView: level :100 plugged : 2
,08-30 17:08:20.842  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-30 17:08:20.852  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-30 17:08:20.852  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-30 17:08:20.852  1969  1969 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-30 17:08:20.852  1016  1514 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 17:08:20.852  1016  1514 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-30 17:08:20.852  1016  1514 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:20.852  1016  1514 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:20.852  1016  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:20.862  1969  7599 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-30 17:08:20.862  1969  1969 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-30 17:08:20.872  1016  1497 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:08:20.872  1016  1497 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:20.872  1016  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:20.872  1016  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:20.882  1969  7599 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-30 17:08:21.652   296   296 E SMD     : DCD OFF
,08-30 17:08:22.052  6765  6822 D io.jxcore.node.ConnectivityMonitor: stop,
08-30 17:08:22.052  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:22.302  1016  1049 I PowerManagerService: [PWL] Off : 75s ago,
08-30 17:08:22.302  1016  1049 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-30 17:08:22.302  1016  1049 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1,
08-30 17:08:22.302  1016  1049 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1016, ws=null) (elapsedTime=14747)
,08-30 17:08:22.682  1016  1321 E Watchdog: !@Sync 4,
,08-30 17:08:23.692   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,08-30 17:08:24.662   296   296 E SMD     : DCD OFF,
,08-30 17:08:24.692   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,08-30 17:08:25.052  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
,08-30 17:08:25.052  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3069b4c5 added. We now have 6 listener(s)
,08-30 17:08:25.052  6765  6822 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:08:25.052  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 17:08:25.052  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@27742e1a added. We now have 7 listener(s)
08-30 17:08:25.052  6765  6822 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:08:25.052  6765  6822 I System.out: IsBluetoothEnabled,
,08-30 17:08:25.052  6765  6822 D BluetoothAdapter: disable()
,08-30 17:08:25.052  1016  1495 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.,
,08-30 17:08:25.052  6765  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:25.062  6765  6822 D BluetoothAdapter: enable()
,08-30 17:08:25.062  1016  1134 W ActivityManager: Permission Denial: getCurrentUser() from pid=6765, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-30 17:08:25.062  1016  1134 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-30 17:08:25.062  1016  1134 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6765, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-30 17:08:25.062  1016  1134 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-30 17:08:25.062  1016  1134 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-30 17:08:25.062  1016  1134 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-30 17:08:25.062  1016  1134 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-30 17:08:25.062  1016  1134 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-30 17:08:25.062  1016  1134 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 17:08:25.062  1016  1134 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 17:08:25.062  1016  1134 D SettingsProvider: name = bluetooth_on,
,08-30 17:08:25.072  1016  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-30 17:08:25.072  1016  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 17:08:25.072  1016  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,08-30 17:08:25.072  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2,
08-30 17:08:25.072  1016  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:25.072  1016  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:25.072  1016  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:25.072  1016  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:25.092  1016  1046 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7604 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a,
,08-30 17:08:25.092  7604  7604 E Zygote  : MountEmulatedStorage()
08-30 17:08:25.092  7604  7604 E Zygote  : v2
08-30 17:08:25.092  7604  7604 I libpersona: KNOX_SDCARD checking this for 1002
,08-30 17:08:25.092  7604  7604 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:25.092  7604  7604 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-30 17:08:25.102  7604  7604 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-30 17:08:25.102  7604  7604 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-30 17:08:25.132  7604  7604 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:25.132  7604  7604 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:25.162  7604  7604 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-30 17:08:25.162  7604  7604 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 17:08:25.182  7604  7604 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-30 17:08:25.212  7604  7604 D BtSettings.ProfileConfig: Adding GattService
,08-30 17:08:25.212  7604  7604 D BtSettings.ProfileConfig: Adding HeadsetService
08-30 17:08:25.212  7604  7604 D BtSettings.ProfileConfig: Adding A2dpService
,08-30 17:08:25.212  7604  7604 D BtSettings.ProfileConfig: Adding HidService
08-30 17:08:25.212  7604  7604 D BtSettings.ProfileConfig: Adding HealthService
08-30 17:08:25.212  7604  7604 D BtSettings.ProfileConfig: Adding PanService
08-30 17:08:25.212  7604  7604 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-30 17:08:25.212  7604  7604 D BtSettings.ProfileConfig: Adding SapService
08-30 17:08:25.212  7604  7604 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-30 17:08:25.212  7604  7604 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-30 17:08:25.212  7604  7604 D BtSettings.ProfileConfig: Adding SapClientService
08-30 17:08:25.212  7604  7604 D BtSettings.ProfileConfig: Adding HidDevService
,08-30 17:08:25.222  7604  7604 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-30 17:08:25.222  1016  1514 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-30 17:08:25.222  1016  1514 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:25.222  1016  1514 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-30 17:08:25.222  1016  1514 D SettingsProvider: selectionArgs: false
08-30 17:08:25.222  1016  1514 D SettingsProvider: selectionArgs: 1002
,08-30 17:08:25.222  1016  1514 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:25.222  1016  1514 D SettingsProvider: ret = -1
,08-30 17:08:25.222  1016  1495 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-30 17:08:25.222  1016  1495 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:25.222  1016  1495 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:25.222  1016  1495 D SettingsProvider: selectionArgs: false
08-30 17:08:25.222  1016  1495 D SettingsProvider: selectionArgs: 1002
08-30 17:08:25.222  1016  1495 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:25.222  1016  1495 D SettingsProvider: ret = -1
,08-30 17:08:25.222  1016  1415 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-30 17:08:25.222  1016  1415 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:25.222  1016  1415 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:25.222  1016  1415 D SettingsProvider: selectionArgs: false
08-30 17:08:25.222  1016  1415 D SettingsProvider: selectionArgs: 1002
,08-30 17:08:25.222  1016  1415 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:25.222  1016  1415 D SettingsProvider: ret = -1
,08-30 17:08:25.222  1016  1029 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-30 17:08:25.222  1016  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:25.222  1016  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:25.222  1016  1029 D SettingsProvider: selectionArgs: false
08-30 17:08:25.222  1016  1029 D SettingsProvider: selectionArgs: 1002
08-30 17:08:25.222  1016  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:25.222  1016  1029 D SettingsProvider: ret = -1
,08-30 17:08:25.222  1016  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-30 17:08:25.222  1016  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:25.222  1016  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:25.222  1016  1028 D SettingsProvider: selectionArgs: false
,08-30 17:08:25.222  1016  1028 D SettingsProvider: selectionArgs: 1002
08-30 17:08:25.222  1016  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:25.222  1016  1028 D SettingsProvider: ret = -1
,08-30 17:08:25.222  1016  1134 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
,08-30 17:08:25.222  1016  1134 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:25.222  1016  1134 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:25.222  1016  1134 D SettingsProvider: selectionArgs: false
,08-30 17:08:25.222  1016  1134 D SettingsProvider: selectionArgs: 1002
,08-30 17:08:25.232  1016  1134 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:25.232  1016  1134 D SettingsProvider: ret = -1
,08-30 17:08:25.232  1016  2050 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-30 17:08:25.232  1016  2050 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:25.232  1016  2050 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-30 17:08:25.232  1016  2050 D SettingsProvider: selectionArgs: false
08-30 17:08:25.232  1016  2050 D SettingsProvider: selectionArgs: 1002
08-30 17:08:25.232  1016  2050 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:25.232  1016  2050 D SettingsProvider: ret = -1
08-30 17:08:25.232  1016  1323 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-30 17:08:25.232  1016  1323 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-30 17:08:25.232  1016  1323 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:25.232  1016  1323 D SettingsProvider: selectionArgs: false
08-30 17:08:25.232  1016  1323 D SettingsProvider: selectionArgs: 1002
08-30 17:08:25.232  1016  1323 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:25.232  1016  1323 D SettingsProvider: ret = -1
,08-30 17:08:25.232  1016  1497 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-30 17:08:25.232  1016  1497 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:25.232  1016  1497 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:25.232  1016  1497 D SettingsProvider: selectionArgs: false
08-30 17:08:25.232  1016  1497 D SettingsProvider: selectionArgs: 1002
,08-30 17:08:25.232  1016  1497 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:25.232  1016  1497 D SettingsProvider: ret = -1
,08-30 17:08:25.232  1016  1536 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:08:25.232  1016  1536 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:25.232  1016  1536 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-30 17:08:25.232  1016  1536 D SettingsProvider: selectionArgs: false
08-30 17:08:25.232  1016  1536 D SettingsProvider: selectionArgs: 1002
08-30 17:08:25.232  1016  1536 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:25.232  1016  1536 D SettingsProvider: ret = -1
08-30 17:08:25.232  1016  1498 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,08-30 17:08:25.232  1016  1498 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:25.232  1016  1498 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-30 17:08:25.232  1016  1498 D SettingsProvider: selectionArgs: false
08-30 17:08:25.232  1016  1498 D SettingsProvider: selectionArgs: 1002
08-30 17:08:25.232  1016  1498 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:25.232  1016  1498 D SettingsProvider: ret = -1
,08-30 17:08:25.232  1016  1514 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-30 17:08:25.232  1016  1514 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:25.232  1016  1514 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:25.232  1016  1514 D SettingsProvider: selectionArgs: false
,08-30 17:08:25.232  1016  1514 D SettingsProvider: selectionArgs: 1002
08-30 17:08:25.232  1016  1514 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:25.232  1016  1514 D SettingsProvider: ret = -1
,08-30 17:08:25.252  7604  7604 D BluetoothAdapterState: make,
,08-30 17:08:25.252  7604  7604 I bluedroid: init
08-30 17:08:25.252  7604  7619 I BluetoothAdapterState: Entering OffState
,08-30 17:08:25.252  7604  7604 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-30 17:08:25.252  7604  7604 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-30 17:08:25.252  7604  7604 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 17:08:25.252  7604  7604 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-30 17:08:25.252  7604  7604 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-30 17:08:25.252  7604  7604 I bluedroid: get_profile_interface socket
08-30 17:08:25.252  7604  7604 I bluedroid: get_profile_interface map_client
,08-30 17:08:25.252  7604  7622 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-30 17:08:25.262  7604  7604 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-30 17:08:25.262  7604  7622 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-30 17:08:25.262  7604  7622 E BluetoothServiceJni: populateRssiValuesNative
08-30 17:08:25.262  7604  7622 I bluedroid: getModelRssiValues
08-30 17:08:25.262  7604  7622 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-30 17:08:25.262  7604  7622 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-30 17:08:25.262  7604  7622 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-30 17:08:25.262  1016  1016 D SettingsProvider: name = bluetooth_name
,08-30 17:08:25.272  7604  7604 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:08:25.272  1016  1495 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-30 17:08:25.272  1016  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 17:08:25.272  1016  1495 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:25.272  1016  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:25.272  1016  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:25.272  7604  7612 I bluedroid: config_hci_snoop_log
,08-30 17:08:25.272  1016  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-30 17:08:25.272  1016  1046 D BluetoothManagerService: Ble is always on enable gatt
,08-30 17:08:25.272  1016  1046 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-30 17:08:25.282  1016  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-30 17:08:25.282  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-30 17:08:25.282  1016  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 17:08:25.282  1016  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 17:08:25.282  7604  7604 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-30 17:08:25.282  1016  1046 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-30 17:08:25.292  1016  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-30 17:08:25.292  7604  7619 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-30 17:08:25.292  7604  7619 D BluetoothAdapterProperties: Setting state to 11
08-30 17:08:25.292  7604  7619 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-30 17:08:25.292  7604  7619 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-30 17:08:25.292  7604  7619 D BluetoothAdapterService: updateAdapterState state is 11
,08-30 17:08:25.292  7604  7619 D BluetoothAdapterService: Autoconnection is available 
,08-30 17:08:25.292  7604  7619 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-30 17:08:25.292  7604  7619 D BluetoothSecureManager: getInstant: null
,08-30 17:08:25.292  7604  7619 D BluetoothSecureManager: calling getMethod for getService
,08-30 17:08:25.292  7604  7619 D BluetoothSecureManager: calling getService
,08-30 17:08:25.292  7604  7619 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@b1c72ac
,08-30 17:08:25.302  1016  1536 D BluetoothSecureManagerService: isSecureModeEnabled
,08-30 17:08:25.302  1016  1536 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-30 17:08:25.302  7604  7619 D BtConfig.SecureMode: isSecureModeOn:false
08-30 17:08:25.302  7604  7619 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-30 17:08:25.302  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:08:25.302  1016  1016 I InputMethodManagerService: [BT Setting State] State =11
,08-30 17:08:25.312  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-30 17:08:25.312  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:25.312  1177  1177 D BluetoothTile:  getBluetoothState : 11
,08-30 17:08:25.312  1866  1866 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 17:08:25.312  7604  7619 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-30 17:08:25.312  7604  7619 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-30 17:08:25.312  7604  7619 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-30 17:08:25.312  7604  7619 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-30 17:08:25.312  7604  7619 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-30 17:08:25.312  7604  7619 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-30 17:08:25.312  7374  7374 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:08:25.312  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:25.312  7604  7619 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-30 17:08:25.312  7604  7619 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-30 17:08:25.312  7604  7619 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-30 17:08:25.312  7604  7619 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-30 17:08:25.312  7604  7619 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-30 17:08:25.312  7604  7619 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-30 17:08:25.312  7604  7619 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-30 17:08:25.312  7604  7619 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-30 17:08:25.322  7604  7619 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-30 17:08:25.322  7604  7619 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-30 17:08:25.322  1016  1323 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-30 17:08:25.322  7604  7619 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-30 17:08:25.322  7604  7619 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-30 17:08:25.322  7604  7619 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:08:25.322  7604  7619 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-30 17:08:25.322  1016  1029 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-30 17:08:25.322  1016  1415 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 17:08:25.322  1016  1415 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-30 17:08:25.322  7604  7619 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-30 17:08:25.322  7604  7619 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-30 17:08:25.322  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-30 17:08:25.322  1016  1415 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:25.322  1016  1415 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:25.322  1016  1415 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-30 17:08:25.322  7604  7619 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-30 17:08:25.322  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-30 17:08:25.322  1177  1755 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 17:08:25.332  1177  1755 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-30 17:08:25.332  7374  7374 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 17:08:25.332  7604  7619 D BluetoothBondStateMachine: make
,08-30 17:08:25.332  7604  7619 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-30 17:08:25.332  7604  7619 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-30 17:08:25.332  7604  7619 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-30 17:08:25.332  1016  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
,08-30 17:08:25.332  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:25.332  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-30 17:08:25.332  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:25.332  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 17:08:25.332  7604  7625 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 17:08:25.332  7604  7619 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-30 17:08:25.332  7604  7619 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-30 17:08:25.332  7604  7619 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-30 17:08:25.342  7604  7604 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 17:08:25.342  7604  7604 D BtGatt.GattService: Received start request. Starting profile...
08-30 17:08:25.342  7604  7604 D BtGatt.GattService: start()
08-30 17:08:25.342  7604  7604 D BtGatt.GattService: start()
08-30 17:08:25.342  7604  7604 I bluedroid: get_profile_interface gatt
,08-30 17:08:25.342  7604  7604 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336d367
08-30 17:08:25.342  7604  7604 D BtGatt.AdvertiseManager: advertise manager created
,08-30 17:08:25.342  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:25.342  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-30 17:08:25.342  1016  2050 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 17:08:25.342  1016  2050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-30 17:08:25.342  1016  2050 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:25.342  1016  2050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:25.342  1016  2050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:25.352  7604  7619 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-30 17:08:25.352  7604  7619 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-30 17:08:25.352  7604  7619 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-30 17:08:25.352  1016  1415 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 17:08:25.352  1016  1415 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 17:08:25.352  1016  1415 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:25.352  1016  1415 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:25.352  1016  1415 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:25.352  7604  7604 D BtGatt.GattService: mStartError = false
08-30 17:08:25.352  7604  7604 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336d367
,08-30 17:08:25.352  7604  7619 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-30 17:08:25.352  7604  7619 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 17:08:25.362  7604  7619 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-30 17:08:25.362  7604  7604 D HeadsetService: Received start request. Starting profile...
08-30 17:08:25.362  7604  7604 D HeadsetService: start()
,08-30 17:08:25.362  1016  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 17:08:25.362  7604  7604 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 17:08:25.362  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-30 17:08:25.362  7604  7604 D HeadsetStateMachine: make
,08-30 17:08:25.362  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:25.362  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:25.362  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:25.362  7604  7619 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-30 17:08:25.362  7604  7619 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-30 17:08:25.362  7604  7619 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-30 17:08:25.362  1016  1495 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:25.362  1016  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-30 17:08:25.362  7604  7604 E HeadsetStateMachine: # of Max HF connection is 2
08-30 17:08:25.362  1016  1495 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:25.362  1016  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:25.362  1016  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 17:08:25.372  7604  7619 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-30 17:08:25.372  7604  7619 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-30 17:08:25.372  7604  7619 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-30 17:08:25.372  1016  1498 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 17:08:25.372  1016  1498 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-30 17:08:25.372  1016  1498 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:25.372  1016  1498 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:25.372  1016  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:25.372  1016  2050 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-30 17:08:25.372  1016  2050 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-30 17:08:25.372  7604  7619 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-30 17:08:25.372  7604  7619 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 17:08:25.372  7604  7619 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-30 17:08:25.382  1016  2050 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:25.382  1016  2050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:25.382  1016  2050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-30 17:08:25.382  1016  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:25.382  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-30 17:08:25.382  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:25.382  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:25.382  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:25.382  1016  1514 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-30 17:08:25.382  7604  7619 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-30 17:08:25.382  1016  1514 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-30 17:08:25.382  7604  7619 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-30 17:08:25.382  1016  1514 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:25.382  1016  1514 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:25.382  1016  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-30 17:08:25.382  7604  7619 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-30 17:08:25.382  7604  7604 I bluedroid: get_profile_interface handsfree
,08-30 17:08:25.392  1016  2050 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 17:08:25.392  1016  2050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-30 17:08:25.392  1016  2050 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:25.392  1016  2050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:25.392  1016  2050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:25.392  7604  7619 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-30 17:08:25.392  7604  7619 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-30 17:08:25.392  7604  7619 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-30 17:08:25.392  7604  7619 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:08:25.392  7604  7619 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:08:25.392  7604  7619 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:08:25.392  7604  7619 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-30 17:08:25.392  7604  7619 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-30 17:08:25.392  7604  7619 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-30 17:08:25.392  7604  7619 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-30 17:08:25.392  7604  7619 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-30 17:08:25.392  7604  7619 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-30 17:08:25.392  7604  7619 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-30 17:08:25.402  7604  7604 I DualScoManager: Instantiating Dual Sco Manager
,08-30 17:08:25.402  7604  7604 I DualScoManager: Set HeadsetServiceHelper
,08-30 17:08:25.412  7604  7604 D BluetoothAtMessage: createCMTIContentObservers
,08-30 17:08:25.412  1016  1498 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-30 17:08:25.412  1016  1498 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:25.412  1016  1498 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:25.412  1016  1498 D SettingsProvider: selectionArgs: false
,08-30 17:08:25.412  1016  1498 D SettingsProvider: selectionArgs: 1002
08-30 17:08:25.412  1016  1498 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-30 17:08:25.412  1016  1498 D SettingsProvider: ret = -1
,08-30 17:08:25.412  7604  7628 D HeadsetStateMachine: Enter Disconnected: -2
,08-30 17:08:25.412  7604  7604 D HeadsetService: mStartError = false
,08-30 17:08:25.412  7604  7604 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336d367
,08-30 17:08:25.412  7604  7604 E BluetoothAdapterService(53924711): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-30 17:08:25.422  7604  7604 D A2dpService: Received start request. Starting profile...
,08-30 17:08:25.422  7604  7604 D A2dpService: start()
,08-30 17:08:25.422  7604  7604 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-30 17:08:25.422  7604  7604 I bluedroid: get_profile_interface avrcp
,08-30 17:08:25.422  7604  7628 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-30 17:08:25.422  7604  7628 D HeadsetStateMachine: map size, before remove : 0
08-30 17:08:25.422  7604  7628 D HeadsetStateMachine: map size, after remove: 0
,08-30 17:08:25.432  7604  7604 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-30 17:08:25.432  7604  7604 D Avrcp   : Initialize Media Controller
,08-30 17:08:25.432  7604  7604 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-30 17:08:25.432  7604  7604 E Avrcp   : getActiveSessions
,08-30 17:08:25.432  7604  7604 D Avrcp   : pick active media Controller
08-30 17:08:25.432  7604  7604 D Avrcp   : Get the active Media Controller 
,08-30 17:08:25.442  7604  7604 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-30 17:08:25.452  7604  7632 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
08-30 17:08:25.452  7604  7604 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 17:08:25.452  7604  7604 D A2dpStateMachine: make
,08-30 17:08:25.452  7604  7604 I bluedroid: get_profile_interface a2dp
,08-30 17:08:25.452  7604  7634 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-30 17:08:25.452  7604  7604 E bt-btif : warning : media task started media_task_refcnt 1 
,08-30 17:08:25.452  7604  7604 D A2dpService: mStartError = false
08-30 17:08:25.452  7604  7604 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336d367
08-30 17:08:25.452  7604  7633 D A2dpStateMachine: Enter Disconnected: -2
08-30 17:08:25.452  7604  7604 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 17:08:25.452  7604  7604 D HidService: Received start request. Starting profile...
08-30 17:08:25.452  7604  7604 D HidService: start()
08-30 17:08:25.452  7604  7604 I bluedroid: get_profile_interface hidhost
08-30 17:08:25.452  7604  7604 D HidService: setHidService(): set to: null
08-30 17:08:25.452  7604  7604 D HidService: mStartError = false
08-30 17:08:25.452  7604  7604 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336d367
,08-30 17:08:25.452  7604  7604 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-30 17:08:25.462  7604  7604 D HealthService: Received start request. Starting profile...
08-30 17:08:25.462  7604  7604 D HealthService: start()
08-30 17:08:25.462  7604  7632 D BluetoothMediaBrowser: no now playing list
08-30 17:08:25.462  7604  7632 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-30 17:08:25.462  7604  7604 I bluedroid: get_profile_interface health
,08-30 17:08:25.462  7604  7604 D HealthService: mStartError = false
08-30 17:08:25.462  7604  7604 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336d367
,08-30 17:08:25.462  7604  7604 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-30 17:08:25.462  7604  7604 D PanService: Received start request. Starting profile...
08-30 17:08:25.462  7604  7604 D PanService: start()
08-30 17:08:25.462  7604  7604 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 17:08:25.462  7604  7604 I bluedroid: get_profile_interface pan
,08-30 17:08:25.462  7604  7604 D PanService: mStartError = false
08-30 17:08:25.462  7604  7604 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336d367
,08-30 17:08:25.462  7604  7604 D HeadsetStateMachine: Try to query the phonestate on bind
08-30 17:08:25.462  1449  1457 I Telecom : BluetoothPhoneService: queryPhoneState
,08-30 17:08:25.462  1449  1449 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-30 17:08:25.462  1449  1449 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-30 17:08:25.472  1449  1457 I Telecom : BluetoothPhoneService: Result of Message : true
,08-30 17:08:25.472  7604  7604 D BluetoothMapService: Received start request. Starting profile...
08-30 17:08:25.472  7604  7604 D BluetoothMapService: start()
,08-30 17:08:25.482  1969  1969 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-30 17:08:25.482  7604  7604 D BluetoothMapService: mStartError = false
,08-30 17:08:25.482  7604  7604 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336d367
08-30 17:08:25.482  7604  7604 D HeadsetStateMachine: Proxy object connected
08-30 17:08:25.482  7604  7604 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-30 17:08:25.482  7604  7628 D HeadsetStateMachine: Disconnected process message: 11
,08-30 17:08:25.482  7604  7604 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-30 17:08:25.482  7604  7604 D SapService: Received start request. Starting profile...
08-30 17:08:25.482  7604  7604 D SapService: start()
08-30 17:08:25.482  7604  7604 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-30 17:08:25.482  7604  7604 I bluedroid: get_profile_interface sap
08-30 17:08:25.482  7604  7604 D SapService: mStartError = false
08-30 17:08:25.482  7604  7604 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336d367
08-30 17:08:25.482  7604  7604 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-30 17:08:25.482  7604  7604 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-30 17:08:25.482  7604  7604 E BluetoothAdapterService(53924711): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,08-30 17:08:25.482  7604  7604 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-30 17:08:25.482  7604  7604 D BluetoothA2dp: Proxy object connected
08-30 17:08:25.482  7604  7604 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-30 17:08:25.482  7604  7604 E BluetoothAdapterService(53924711): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-30 17:08:25.482  7604  7604 E BluetoothAdapterService(53924711): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-30 17:08:25.492  7604  7628 D HeadsetStateMachine: Disconnected process message: 18
08-30 17:08:25.492  7604  7628 D HeadsetStateMachine: Disconnected process message: 10
,08-30 17:08:25.492  7604  7628 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 17:08:25.492  7604  7628 D HeadsetStateMachine: Disconnected process message: 11
,08-30 17:08:25.492  1969  1969 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-30 17:08:25.492  7604  7604 E BluetoothAdapterService(53924711): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-30 17:08:25.492  7604  7604 E BluetoothAdapterService(53924711): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-30 17:08:25.522  7604  7604 E BluetoothAdapterService(53924711): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-30 17:08:25.522  7604  7604 E BluetoothAdapterService(53924711): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-30 17:08:25.522  7604  7619 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-30 17:08:25.522  7604  7619 I bluedroid: enable
,08-30 17:08:25.522  7604  7619 I bt_hci_bdroid: init
,08-30 17:08:25.522  7604  7619 I bt_vendor: bt-vendor : init
08-30 17:08:25.522  7604  7619 I bt_vendor: bt-vendor : get_bt_soc_type
08-30 17:08:25.522  7604  7619 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-30 17:08:25.522  7604  7619 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-30 17:08:25.522  7604  7619 D bt_userial_mct: userial_init
,08-30 17:08:25.532  7604  7619 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-30 17:08:25.532  7604  7638 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-30 17:08:25.532  7604  7619 I bt_vendor: Starting hciattach daemon
08-30 17:08:25.532  7604  7619 I bt_vendor: try to set false
,08-30 17:08:25.542  7604  7619 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-30 17:08:25.542  7604  7619 I bt_vendor: Starting hciattach daemon
08-30 17:08:25.542  7604  7619 I bt_vendor: try to set true
,08-30 17:08:25.562  7643  7643 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-30 17:08:25.612  7649  7649 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-30 17:08:25.622  7650  7650 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-30 17:08:25.642  7652  7652 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-30 17:08:25.652  7653  7653 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-30 17:08:25.662  7654  7654 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-30 17:08:25.672  7655  7655 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-30 17:08:25.682   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,08-30 17:08:25.902  7658  7658 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 ,
,08-30 17:08:25.912  7659  7659 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-30 17:08:25.952  7604  7619 I bt_vendor: bluetooth satus is on,
08-30 17:08:25.952  7604  7640 D bt_userial_mct: userial_open(port:0)
08-30 17:08:25.952  7604  7640 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-30 17:08:25.952  7604  7640 I bt_vendor: Done intiailizing UART
,08-30 17:08:25.952  7604  7640 I bt_vendor: Done intiailizing UART,
08-30 17:08:25.952  7604  7640 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
08-30 17:08:25.952  7604  7640 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-30 17:08:25.952  7604  7638 I         : BTE_InitTraceLevels -- TRC_HCI
,08-30 17:08:25.952  7604  7638 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 17:08:25.952  7604  7638 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 17:08:25.952  7604  7638 I         : BTE_InitTraceLevels -- TRC_AVDT,
08-30 17:08:25.952  7604  7638 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 17:08:25.952  7604  7638 I         : BTE_InitTraceLevels -- TRC_A2D
,08-30 17:08:25.952  7604  7638 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 17:08:25.952  7604  7638 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 17:08:25.962  7604  7661 D bt_userial_mct: Entering userial_read_thread()
,08-30 17:08:25.962  7604  7638 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 17:08:25.962  7604  7638 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 17:08:25.962  7604  7638 I         : BTE_InitTraceLevels -- TRC_SAP
08-30 17:08:25.962  7604  7638 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 17:08:25.962  7604  7638 I         : BTE_InitTraceLevels -- TRC_GATT
,08-30 17:08:25.962  7604  7638 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 17:08:25.962  7604  7638 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 17:08:25.962  7604  7638 I         : BTE_InitTraceLevels -- TRC_BTIF
08-30 17:08:25.962  7604  7638 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-30 17:08:26.052  7604  7638 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-30 17:08:26.052  7604  7638 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa420ced1 
,08-30 17:08:26.052  7604  7638 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa420ced1 
,08-30 17:08:26.072  7604  7622 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-30 17:08:26.072  1016  3359 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-30 17:08:26.072  7604  7622 E bt-btif : Calling BTA_HhEnable
,08-30 17:08:26.072  7604  7622 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-30 17:08:26.072  7604  7622 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-30 17:08:26.072  7604  7622 E BluetoothServiceJni: populateRssiValuesNative
,08-30 17:08:26.082  7604  7622 I bluedroid: getModelRssiValues
08-30 17:08:26.082  7604  7622 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-30 17:08:26.082  7604  7622 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-30 17:08:26.082  1016  1016 D SettingsProvider: name = bluetooth_name
,08-30 17:08:26.082  7604  7622 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-30 17:08:26.092  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-30 17:08:26.092  7604  7622 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-30 17:08:26.092  7604  7622 D BluetoothAdapterProperties: Scan Mode:20
08-30 17:08:26.092  7604  7622 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 17:08:26.092  7604  7622 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
08-30 17:08:26.092  7604  7622 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-30 17:08:26.092  7604  7622 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-30 17:08:26.092  7604  7622 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-30 17:08:26.092  7604  7622 E bt-btif : btif_sock_init: !vhci_init
08-30 17:08:26.092  7604  7622 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
08-30 17:08:26.092  7604  7622 D IOP_DB_BT: db_open: db_open : handle 3028647952l, read 13894 bytes onto local cache
08-30 17:08:26.092  7604  7622 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
08-30 17:08:26.092  7604  7622 D IOP_DB_BT: db_query: result 1
08-30 17:08:26.092  7604  7622 I         : iop_db_open: iop_db_open status 0
,08-30 17:08:26.092  7604  7622 D bte_conf: Device ID record 1 : primary
08-30 17:08:26.092  7604  7622 D bte_conf:   vendorId            = 0075
,08-30 17:08:26.092  7604  7622 D bte_conf:   vendorIdSource      = 0001
,08-30 17:08:26.092  7604  7661 E bt_mct  : hci lib postload completed
,08-30 17:08:26.092  7604  7622 D bte_conf:   product             = 0100
08-30 17:08:26.092  7604  7622 D bte_conf:   version             = 0200
08-30 17:08:26.092  7604  7622 D bte_conf:   clientExecutableURL = 
,08-30 17:08:26.102  7604  7622 D bte_conf:   serviceDescription  = 
08-30 17:08:26.102  7604  7622 D bte_conf:   documentationURL    = 
08-30 17:08:26.102  7604  7622 D bte_conf: bte_load_did_conf no section named DID2.
,08-30 17:08:26.102  7604  7622 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-30 17:08:26.102  7604  7619 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-30 17:08:26.102  7604  7619 D BluetoothAdapterProperties: ScanMode =  20
,08-30 17:08:26.102  7604  7619 D BluetoothAdapterProperties: State =  11
,08-30 17:08:26.102  1016  1323 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-30 17:08:26.102  7604  7619 D BluetoothAdapterProperties: Setting state to 12
08-30 17:08:26.102  7604  7619 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-30 17:08:26.112  7604  7622 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-30 17:08:26.112  7604  7622 D BluetoothAdapterProperties: Scan Mode:21
08-30 17:08:26.112  7604  7622 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 17:08:26.112  1016  1415 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-30 17:08:26.112  1016  1415 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-30 17:08:26.112  1016  1415 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:26.112  1016  1415 D SettingsProvider: selectionArgs: false
08-30 17:08:26.112  1016  1415 D SettingsProvider: selectionArgs: 1002
08-30 17:08:26.112  1016  1415 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:26.112  1016  1415 D SettingsProvider: ret = -1
,08-30 17:08:26.112  7604  7619 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-30 17:08:26.112  7604  7619 D BluetoothAdapterService: updateAdapterState state is 12
,08-30 17:08:26.112  1016  1514 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 17:08:26.112  1016  1514 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-30 17:08:26.112  1016  1514 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:26.112  1016  1514 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:26.112  1016  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:26.122  7604  7619 D BluetoothAdapterService: Autoconnection is available 
08-30 17:08:26.122  7604  7619 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-30 17:08:26.122  7604  7619 D BluetoothAdapterService: starting service from this receiver
,08-30 17:08:26.122  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:26.122  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:26.122  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:26.122  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:08:26.122  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:26.122  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:26.122  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:26.122  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:08:26.122  1016  1415 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:26.122  1016  1415 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-30 17:08:26.122  1016  1415 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:26.122  1016  1415 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:26.122  1016  1415 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 17:08:26.122  1177  4611 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 17:08:26.122  1177  4611 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 17:08:26.122  7374  7382 D BluetoothPan: Binding service...
,08-30 17:08:26.122  7604  7619 I BluetoothAdapterState: Entering On State from state = 11
,08-30 17:08:26.122  6765  6765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:08:26.142  7604  7604 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-30 17:08:26.292  1016  1046 I art     : Explicit concurrent mark sweep GC freed 52781(2MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 24MB/36MB, paused 2.359ms total 166.424ms
08-30 17:08:26.292  1016  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-30 17:08:26.292  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-30 17:08:26.292  1016  1046 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:26.292  1016  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:26.292  1016  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:26.292  6765  6779 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 17:08:26.292  6765  6779 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 17:08:26.292  7604  7623 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 17:08:26.292  7604  7623 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 17:08:26.292  7374  7382 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 17:08:26.302  1016  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-30 17:08:26.302  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-30 17:08:26.302  1016  1046 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:26.302  1016  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:26.302  1016  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:26.302  1449  3259 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 17:08:26.302  1449  3259 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 17:08:26.302  7604  7612 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 17:08:26.302  7604  7604 I BluetoothPbapService: Handler(): got msg=1
,08-30 17:08:26.302  1016  1497 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy,
,08-30 17:08:26.302  1449  1458 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:08:26.302  1016  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 17:08:26.302  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 17:08:26.312  1016  1046 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:26.312  1016  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:26.312  1016  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:26.312  1449  1458 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 17:08:26.312  7374  7592 D Bluetoothsap: onBluetoothStateChange: up=true
08-30 17:08:26.312  7374  7592 D Bluetoothsap: Binding service...
,08-30 17:08:26.312  7374  7374 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 17:08:26.312  7374  7374 D PanProfile: Bluetooth service connected
,08-30 17:08:26.312  7604  7667 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-30 17:08:26.312  7374  7592 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-30 17:08:26.322  7374  7374 D BluetoothPbap: Proxy object connected
,08-30 17:08:26.322  7374  7374 D PbapServerProfile: Bluetooth service connected
,08-30 17:08:26.322  7604  7667 D BluetoothSocket: bindListen(): myUserId = 0
08-30 17:08:26.322  1016  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-30 17:08:26.322  7604  7667 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 17:08:26.322  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0,
08-30 17:08:26.322  1016  1046 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:26.322  1016  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:26.322  1016  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:26.322  7374  7592 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-30 17:08:26.322  7374  7382 D BluetoothMap: onBluetoothStateChange: up=true
,08-30 17:08:26.322  7374  7374 D Bluetoothsap: BluetoothSAP Proxy object connected
08-30 17:08:26.322  7374  7374 D SapProfile: Bluetooth service connected
08-30 17:08:26.322  7374  7374 D Bluetoothsap: getConnectedDevices()
,08-30 17:08:26.322  1016  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-30 17:08:26.322  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-30 17:08:26.322  1016  1046 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:26.322  1016  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 17:08:26.322  1016  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-30 17:08:26.322  7604  7667 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
,08-30 17:08:26.332  1016  1046 D BluetoothPan: Binding service...
08-30 17:08:26.332  7604  7667 D BluetoothSocket: bindListen(), new LocalSocket 
08-30 17:08:26.332  7604  7667 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-30 17:08:26.332  7604  7667 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@16e30d09
08-30 17:08:26.332  1016  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-30 17:08:26.332  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-30 17:08:26.332  7604  7667 D BluetoothSocket: channel: 19
08-30 17:08:26.332  7604  7667 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-30 17:08:26.332  1016  1016 D BluetoothPan: BluetoothPAN Proxy object connected
,08-30 17:08:26.332  1969  1991 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 17:08:26.332  1969  1991 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 17:08:26.332  7374  7374 D BluetoothMap: Proxy object connected
08-30 17:08:26.332  7374  7374 D MapProfile: Bluetooth service connected
08-30 17:08:26.332  7508  7518 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 17:08:26.332  7508  7518 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 17:08:26.332  1016  1046 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 17:08:26.332  7374  7374 D BluetoothMap: getConnectedDevices()
08-30 17:08:26.332  1016  1046 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-30 17:08:26.332  1016  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-30 17:08:26.332  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-30 17:08:26.332  1016  1016 D BluetoothA2dp: Proxy object connected
,08-30 17:08:26.332  1449  3259 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:08:26.332  1016  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 17:08:26.332  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 17:08:26.332  1016  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:26.332  1016  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:26.332  1016  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:26.332  1449  3259 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 17:08:26.342  1473  1862 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:08:26.342  1016  1046 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-30 17:08:26.342  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 17:08:26.342  1016  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:26.342  1016  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:26.342  1016  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:26.342  1473  1862 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 17:08:26.342  1449  1458 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:08:26.342  1016  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-30 17:08:26.342  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 17:08:26.352  1016  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:26.352  1016  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:26.352  1016  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:26.352  1449  1458 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 17:08:26.352  7374  7592 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 17:08:26.352  7374  7592 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 17:08:26.352  7374  7666 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 17:08:26.352  7374  7666 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:08:26.352  1016  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-30 17:08:26.352  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 17:08:26.352  1016  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:26.352  1016  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:26.352  1016  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:26.352  1459  1472 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 17:08:26.352  1459  1472 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 17:08:26.352  7374  7374 D BluetoothA2dp: Proxy object connected
08-30 17:08:26.352  7374  7374 D A2dpProfile: Bluetooth service connected
08-30 17:08:26.362  1473  1483 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 17:08:26.362  1473  1483 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 17:08:26.362  1016  1046 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-30 17:08:26.362  1016  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 17:08:26.362  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-30 17:08:26.362  1016  1046 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 17:08:26.362  7374  7384 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:08:26.362  1016  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 17:08:26.362  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 17:08:26.362  1016  1046 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:26.362  1016  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:26.362  1016  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:26.362  7374  7384 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 17:08:26.362  7374  7382 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-30 17:08:26.362  7374  7374 D HeadsetProfile: Bluetooth service connected
,08-30 17:08:26.362  1016  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-30 17:08:26.362  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-30 17:08:26.362  1016  1046 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:26.362  1016  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:26.362  1016  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:26.372  1016  1046 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 17:08:26.372  1016  1046 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 17:08:26.372  1016  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-30 17:08:26.372  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-30 17:08:26.372  7374  7374 D BluetoothInputDevice: Proxy object connected
08-30 17:08:26.372  7374  7374 D HidProfile: Bluetooth service connected
,08-30 17:08:26.372  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:26.372  1016  1016 I InputMethodManagerService: [BT Setting State] State =12
08-30 17:08:26.372  1016  1016 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-30 17:08:26.372  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-30 17:08:26.382  1866  1866 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 17:08:26.382  1449  1449 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@1f6a626a, true
,08-30 17:08:26.382  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:26.382  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-30 17:08:26.382  1449  1449 D BluetoothHeadset: registerMessageListener
08-30 17:08:26.382  1177  1177 D BluetoothTile:  getBluetoothState : 12
,08-30 17:08:26.382  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:26.382  1177  1755 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 17:08:26.392  1177  1755 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 17:08:26.392  1016  1514 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 17:08:26.392  1016  1514 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-30 17:08:26.392  1016  1514 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:26.392  1016  1514 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:26.392  1016  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:26.392  7374  7374 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:08:26.392  1016  1498 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 17:08:26.392  1016  1028 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-30 17:08:26.392  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 17:08:26.392  7604  7664 D HeadsetService: registerMessageListener
,08-30 17:08:26.392  7604  7664 D HeadsetService: registerMessageListener
,08-30 17:08:26.392  7604  7628 D HeadsetStateMachine: Disconnected process message: 70
08-30 17:08:26.392  7604  7628 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@a9b7b0e
,08-30 17:08:26.392  1177  1755 D BluetoothTile:  handleUpdatestate:false name:null
08-30 17:08:26.392  1449  1449 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-30 17:08:26.392  1449  1449 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-30 17:08:26.402  7374  7374 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-30 17:08:26.402  7374  7374 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-30 17:08:26.402  1449  1449 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-30 17:08:26.402  1449  1449 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-30 17:08:26.402  1449  1449 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
08-30 17:08:26.402  7374  7374 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-30 17:08:26.402  7374  7374 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-30 17:08:26.402  7604  7669 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-30 17:08:26.402  7604  7628 D HeadsetStateMachine: Disconnected process message: 9
08-30 17:08:26.402  7604  7628 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-30 17:08:26.412   291   665 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-30 17:08:26.412   291   665 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-30 17:08:26.412   291   665 V voice   : voice_set_parameters: exit with code(-2)
08-30 17:08:26.412   291   665 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-30 17:08:26.412   291   665 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-30 17:08:26.412   291   665 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-30 17:08:26.412   291   665 V audio_hw_primary: adev_set_parameters: exit
,08-30 17:08:26.412  7604  7628 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-30 17:08:26.412  7374  7374 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 17:08:26.412  7604  7669 D BluetoothSocket: bindListen(): myUserId = 0
,08-30 17:08:26.412  7604  7669 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 17:08:26.412  1016  1029 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-30 17:08:26.412  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-30 17:08:26.412  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:26.412  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:26.412  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-30 17:08:26.422  7604  7669 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
08-30 17:08:26.422  7604  7669 D BluetoothSocket: bindListen(), new LocalSocket 
08-30 17:08:26.422  7604  7669 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-30 17:08:26.422  7604  7669 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1e85d92f
,08-30 17:08:26.422  7604  7669 D BluetoothSocket: channel: 5
,08-30 17:08:26.422  7374  7374 D DockEventReceiver: finishStartingService: stopping service
,08-30 17:08:26.422  7374  7374 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 17:08:26.432  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:08:26.432  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-30 17:08:26.442  7604  7604 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336d367
,08-30 17:08:26.442  7604  7604 D BtConfig.SecureMode: isSecureModeOn:false
,08-30 17:08:26.442  1016  1497 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 17:08:26.442  1016  1497 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-30 17:08:26.442  1016  1497 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:26.442  1016  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:26.442  1016  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:26.462  1969  1969 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-30 17:08:26.462  1016  1497 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 17:08:26.462  1016  1497 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-30 17:08:26.462  1016  1497 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:26.462  1016  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 17:08:26.462  1016  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:26.472  1969  7675 D EasyUnlockInitService: Handling intent for initializer IntentService.
08-30 17:08:26.472  1969  1969 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-30 17:08:26.472  1016  2050 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:08:26.472  1016  2050 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:26.472  1016  1029 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-30 17:08:26.482  1016  2050 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:26.482  1016  2050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:26.482  7604  7679 D BluetoothSocket: bindListen(): myUserId = 0
08-30 17:08:26.482  7604  7679 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 17:08:26.492  7604  7679 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
08-30 17:08:26.492  7604  7679 D BluetoothSocket: bindListen(), new LocalSocket 
08-30 17:08:26.492  7604  7679 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-30 17:08:26.492  7604  7679 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@10825441
,08-30 17:08:26.492  7604  7679 D BluetoothSocket: channel: 12
08-30 17:08:26.492  7604  7679 I BtOppRfcommListener: Accept thread started.
,08-30 17:08:26.492  1016  2050 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:08:26.492  1016  2050 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:26.492  1016  2050 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:26.492  1016  2050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:26.502  1969  7675 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-30 17:08:26.692   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 17:08:27.082  6765  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:27.082  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:27.082  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:27.082  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:08:27.082  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:27.082  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:27.082  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:27.082  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:08:27.082  6765  6822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:08:27.082  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 17:08:27.082  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@349fbd4b added. We now have 8 listener(s)
,08-30 17:08:27.082  6765  6822 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:08:27.092  1016  1323 D SecContentProvider: uri = 18 selection = isWifiEnabled,
08-30 17:08:27.092  1016  1323 D WifiService: setWifiEnabled: false pid=6765, uid=10171
08-30 17:08:27.092  1016  1323 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-30 17:08:27.092  1016  1323 D SecContentProvider2: mCursor = null
08-30 17:08:27.092  1016  1323 D SettingsProvider: name = wifi_on
,08-30 17:08:27.092  6765  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:27.102  1016  1028 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-30 17:08:27.102  1016  1028 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-30 17:08:27.102  1016  1028 D SecContentProvider2: mCursor = null
,08-30 17:08:27.102  1016  1028 D WifiService: setWifiEnabled: true pid=6765, uid=10171
,08-30 17:08:27.102  1016  1028 W ActivityManager: Permission Denial: getCurrentUser() from pid=6765, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-30 17:08:27.102  1016  1028 W WifiService: Failed getting userId using ActivityManagerNative
08-30 17:08:27.102  1016  1028 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6765, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-30 17:08:27.102  1016  1028 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-30 17:08:27.102  1016  1028 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-30 17:08:27.102  1016  1028 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-30 17:08:27.102  1016  1028 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-30 17:08:27.102  1016  1028 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-30 17:08:27.102  1016  1028 D SettingsProvider: name = wifi_on
,08-30 17:08:27.112  1016  1126 E WifiHW  : ##################### set firmware type 0 #####################
,08-30 17:08:27.252  1016  2056 V SAMP_SPCM_test: CSC File load.. 
,08-30 17:08:27.262  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,08-30 17:08:27.262  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
08-30 17:08:27.262  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
,08-30 17:08:27.262  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
08-30 17:08:27.262  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
08-30 17:08:27.262  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
,08-30 17:08:27.262  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
08-30 17:08:27.262  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
,08-30 17:08:27.262  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
08-30 17:08:27.262  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
08-30 17:08:27.262  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
08-30 17:08:27.262  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
08-30 17:08:27.262  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
08-30 17:08:27.262  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
08-30 17:08:27.262  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
08-30 17:08:27.262  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
08-30 17:08:27.262  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
08-30 17:08:27.262  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
08-30 17:08:27.262  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
08-30 17:08:27.262  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
08-30 17:08:27.262  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,08-30 17:08:27.292  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,08-30 17:08:27.302  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
08-30 17:08:27.302  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
08-30 17:08:27.302  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
08-30 17:08:27.302  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
08-30 17:08:27.302  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
08-30 17:08:27.302  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
08-30 17:08:27.302  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
08-30 17:08:27.302  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
08-30 17:08:27.302  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
08-30 17:08:27.302  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
08-30 17:08:27.302  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
08-30 17:08:27.302  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
08-30 17:08:27.302  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
08-30 17:08:27.302  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
08-30 17:08:27.302  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
08-30 17:08:27.302  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
08-30 17:08:27.302  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
08-30 17:08:27.302  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
08-30 17:08:27.302  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-30 17:08:27.302  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-30 17:08:27.312  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password,
08-30 17:08:27.312  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
08-30 17:08:27.312  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
08-30 17:08:27.312  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
08-30 17:08:27.312  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
,08-30 17:08:27.312  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
08-30 17:08:27.312  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
08-30 17:08:27.312  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
08-30 17:08:27.312  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
08-30 17:08:27.312  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
,08-30 17:08:27.312  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
08-30 17:08:27.312  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
08-30 17:08:27.312  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
08-30 17:08:27.312  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
08-30 17:08:27.312  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
,08-30 17:08:27.312  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
08-30 17:08:27.312  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
08-30 17:08:27.312  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
08-30 17:08:27.312  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
08-30 17:08:27.312  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
08-30 17:08:27.312  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
,08-30 17:08:27.312  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
08-30 17:08:27.312  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
08-30 17:08:27.312  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
08-30 17:08:27.312  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
,08-30 17:08:27.312  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
08-30 17:08:27.312  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
08-30 17:08:27.312  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
,08-30 17:08:27.312  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
08-30 17:08:27.312  1016  2056 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
08-30 17:08:27.312  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
,08-30 17:08:27.312  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-30 17:08:27.312  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
,08-30 17:08:27.312  1016  2056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:27.312  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
08-30 17:08:27.312  1016  2056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:27.312  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
,08-30 17:08:27.312  1016  2056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:27.312  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
08-30 17:08:27.312  1016  2056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:27.312  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
08-30 17:08:27.312  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-30 17:08:27.312  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
08-30 17:08:27.312  1016  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,08-30 17:08:27.322  7685  7685 E Zygote  : MountEmulatedStorage()
08-30 17:08:27.322  7685  7685 E Zygote  : v2
08-30 17:08:27.322  7685  7685 I libpersona: KNOX_SDCARD checking this for 1000
08-30 17:08:27.322  7685  7685 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:27.322  1016  2056 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=7685 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-30 17:08:27.322  7685  7685 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:08:27.332  7685  7685 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 17:08:27.332  7685  7685 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:08:27.352  7685  7685 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:27.352  7685  7685 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:27.362  7685  7685 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-30 17:08:27.402  1016  2056 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,08-30 17:08:27.472  1016  1044 D Tethering: interfaceAdded wlan0
,08-30 17:08:27.472  1016  1129 E Tethering: No numeric data
,08-30 17:08:27.472  1016  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-30 17:08:27.482  1016  1129 D Tethering: clearTetheredNotification()
,08-30 17:08:27.482  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:27.482  1016  1123 V NetworkStats: performPollLocked(flags=0x1)
,08-30 17:08:27.482  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-30 17:08:27.482  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-30 17:08:27.492  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-30 17:08:27.492  1177  1177 D HotspotTile: updateTetherState():false, false
,08-30 17:08:27.492  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 17:08:27.492  1016  1044 D Tethering: interfaceStatusChanged wlan0, false
08-30 17:08:27.492  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 17:08:27.492  1016  1129 D Tethering: InitialState.processMessage what=4
08-30 17:08:27.492  1016  1044 D Tethering: interfaceAdded p2p0
08-30 17:08:27.492  1016  1123 V NetworkStats: performPollLocked() took 12ms
08-30 17:08:27.492  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:27.502  1016  1129 E Tethering: No numeric data
,08-30 17:08:27.502  1016  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 17:08:27.502  1016  1129 D Tethering: clearTetheredNotification()
,08-30 17:08:27.502  1016  1044 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-30 17:08:27.502  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:27.502  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:27.512  1016  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 17:08:27.512  1016  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-30 17:08:27.512  1016  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-30 17:08:27.512   285  1015 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-30 17:08:27.512  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:27.512  1016  1123 V NetworkStats: performPollLocked(flags=0x1)
,08-30 17:08:27.512   285  1015 D SoftapController: Softap fwReload - Ok
08-30 17:08:27.512  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-30 17:08:27.512  1177  1177 D HotspotTile: updateTetherState():false, false
,08-30 17:08:27.512  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 17:08:27.512  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 17:08:27.522   285  1015 D CommandListener: Setting iface cfg,
08-30 17:08:27.522   285  1015 D CommandListener: Trying to bring down wlan0
,08-30 17:08:27.522   285  1015 D CommandListener: Clearing all IP addresses on wlan0
,08-30 17:08:27.522  1016  1123 V NetworkStats: performPollLocked() took 8ms
,08-30 17:08:27.522  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:27.522  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:27.522  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:27.522  1016  1126 E WifiHW  : supplicant_name : p2p_supplicant
08-30 17:08:27.532  1016  1126 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-30 17:08:27.532  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:08:27.532  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-30 17:08:27.532  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:27.532  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:27.532  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:27.532  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:27.542  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 17:08:27.542  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-30 17:08:27.542  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 17:08:27.542  1177  1755 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-30 17:08:27.542  1177  1177 D HotspotTile: onReceive : 2, 0
08-30 17:08:27.552  1016  1415 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 17:08:27.552  1016  1415 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-30 17:08:27.552  1016  1415 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:27.552  1016  1415 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:27.552  1016  1415 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-30 17:08:27.552  1595  1595 I Hs20UtilService: Starting #19
08-30 17:08:27.552  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:27.552  1595  1633 I Hs20UtilService: Message received 5011
08-30 17:08:27.552  6569  6569 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-30 17:08:27.552  6569  6569 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-30 17:08:27.552  6569  6569 D SecurityLogAgent: StateMachine : Current State = 1
08-30 17:08:27.552  6569  6569 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-30 17:08:27.572  7708  7708 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-30 17:08:27.572  7708  7708 I wpa_supplicant: Successfully initialized wpa_supplicant
08-30 17:08:27.572  7708  7708 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
08-30 17:08:27.582  1016  3331 D SSRM:n  : SIOP:: AP = 340
,08-30 17:08:27.582  7708  7708 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,08-30 17:08:27.592   371   371 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7708
08-30 17:08:27.592   371   371 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,08-30 17:08:27.592  7708  7708 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-30 17:08:27.592  7708  7708 I wpa_supplicant: ssSupport state is = 1
08-30 17:08:27.592  7708  7708 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-30 17:08:27.592  7708  7708 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-30 17:08:27.592   371   371 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7708
08-30 17:08:27.592   371   371 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-30 17:08:27.652   296   296 E SMD     : DCD OFF,
,08-30 17:08:27.682   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 17:08:27.752   371   371 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,08-30 17:08:27.752  7708  7708 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed,
,08-30 17:08:27.802  7708  7708 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-30 17:08:27.802  7708  7708 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-30 17:08:27.812  7708  7708 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,08-30 17:08:27.812   371   371 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7708,
08-30 17:08:27.812   371   371 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-30 17:08:27.812  7708  7708 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-30 17:08:27.812  7708  7708 I wpa_supplicant: ssSupport state is = 1
08-30 17:08:27.812  7708  7708 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-30 17:08:27.812  7708  7708 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 17:08:27.812  7708  7708 E wpa_supplicant: SIM READ ERROR
08-30 17:08:27.812  7708  7708 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 17:08:27.812  7708  7708 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-30 17:08:27.812  7708  7708 E wpa_supplicant: SIM READ ERROR
08-30 17:08:27.812  7708  7708 I wpa_supplicant: Blacklist: Clear (all) 
08-30 17:08:27.812  7708  7708 I wpa_supplicant: wpa_default_ap_write_once
08-30 17:08:27.812  7708  7708 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-30 17:08:27.812  7708  7708 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-30 17:08:27.812  7708  7708 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-30 17:08:27.812  7708  7708 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 17:08:27.812  7708  7708 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-30 17:08:27.812  7708  7708 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-30 17:08:27.822  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, false,
08-30 17:08:27.822  1016  1044 D Tethering: interfaceStatusChanged wlan0, false
08-30 17:08:27.822  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-30 17:08:27.872  7708  7708 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-30 17:08:28.052  7708  7708 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-30 17:08:28.052  7708  7708 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-30 17:08:28.062  7708  7708 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,08-30 17:08:28.072   371   371 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7708
08-30 17:08:28.072   371   371 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-30 17:08:28.072  7708  7708 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-30 17:08:28.072  7708  7708 I wpa_supplicant: ssSupport state is = 1,
08-30 17:08:28.072  7708  7708 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-30 17:08:28.072  7708  7708 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-30 17:08:28.082  7708  7708 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-30 17:08:28.082   371   371 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7708
08-30 17:08:28.082   371   371 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-30 17:08:28.082  7708  7708 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
08-30 17:08:28.082  7708  7708 I wpa_supplicant: ssSupport state is = 1
08-30 17:08:28.082  7708  7708 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 17:08:28.082  7708  7708 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-30 17:08:28.082  7708  7708 E wpa_supplicant: SIM READ ERROR
08-30 17:08:28.082  7708  7708 I wpa_supplicant: wpa_default_ap_write_once
08-30 17:08:28.082  7708  7708 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-30 17:08:28.082  7708  7708 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 17:08:28.082  1016  1044 D Tethering: interfaceLinkStateChanged p2p0, false,
08-30 17:08:28.082  1016  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
,08-30 17:08:28.082  1016  1044 D Tethering: interfaceStatusChanged p2p0, false
08-30 17:08:28.092  1016  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-30 17:08:28.092  1016  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 17:08:28.092  1016  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-30 17:08:28.132  7708  7708 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-30 17:08:28.132  7708  7708 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-30 17:08:28.192  7708  7708 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-30 17:08:28.192  7708  7708 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-30 17:08:28.192  7708  7708 I wpa_supplicant: Skip scan - bUseNetwork false
,08-30 17:08:28.202  1016  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
08-30 17:08:28.202  1016  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-30 17:08:28.202  7708  7708 I wpa_supplicant: HOTSPOT20_ENABLE called,
08-30 17:08:28.212  7708  7708 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-30 17:08:28.212  7708  7708 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 17:08:28.212  7708  7708 E wpa_supplicant: SIM READ ERROR,
08-30 17:08:28.212  7708  7708 I wpa_supplicant: Blacklist: Clear (all) 
,08-30 17:08:28.222  7708  7708 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-30 17:08:28.232  7708  7708 I wpa_supplicant: Skip scan - bUseNetwork false,
08-30 17:08:28.232  1016  1126 D WifiConfigStore: Loading config and enabling all networks 
,08-30 17:08:28.232  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 17:08:28.242  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 17:08:28.242  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:28.242  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:28.242  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:28.242  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:28.242  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 17:08:28.242  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-30 17:08:28.242  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-30 17:08:28.242  1177  1755 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-30 17:08:28.242  1177  1177 D HotspotTile: onReceive : 3, 0
,08-30 17:08:28.252  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:28.252  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:28.252  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:28.252  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:28.252  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:28.252  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:28.252  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:28.252  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:08:28.252  1016  1126 E WifiConfigStore: Not a HS20
,08-30 17:08:28.252  1016  1126 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-30 17:08:28.252  6765  6765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:08:28.252  1016  1126 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-30 17:08:28.252  1016  1498 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-30 17:08:28.262  1016  1498 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 17:08:28.262  1016  1498 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:28.262  1016  1498 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 17:08:28.262  1016  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 17:08:28.262  1016  1126 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-30 17:08:28.262  7708  7708 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-30 17:08:28.262  7708  7708 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-30 17:08:28.262  7708  7708 I wpa_supplicant: reset timer : RESET_TIMER 0
08-30 17:08:28.262  7708  7708 I wpa_supplicant: P2P: Current p2p state = IDLE
08-30 17:08:28.262  7708  7708 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-30 17:08:28.262  7708  7708 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-30 17:08:28.262  7708  7708 I wpa_supplicant: First Scan Start
,08-30 17:08:28.262  7708  7708 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-30 17:08:28.262  1016  1126 D WifiNative-wlan0: Setting external_sim to 1
,08-30 17:08:28.262  7020  7020 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 17:08:28.262  1016  1126 D WifiStateMachine: Setting OUI to DA-A1-19
,08-30 17:08:28.262  1016  1126 I WifiNative-HAL: startHal
08-30 17:08:28.262  1016  1126 E wifi    : getStaticLongField sWifiHalHandle 0x9eeb988c
08-30 17:08:28.262  1016  1126 I WifiNative-HAL: Could not start hal
,08-30 17:08:28.272  1595  1595 I Hs20UtilService: Starting #20
,08-30 17:08:28.272  1595  1633 I Hs20UtilService: Message received 5011
,08-30 17:08:28.272  6569  6569 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-30 17:08:28.272  6569  6569 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-30 17:08:28.272  6569  6569 D SecurityLogAgent: StateMachine : Current State = 1
,08-30 17:08:28.272  6569  6569 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 17:08:28.272  1016  1126 E WifiNative-wlan0: do suspend true
,08-30 17:08:28.272  1016  1125 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-30 17:08:28.282   285  1015 D CommandListener: Setting iface cfg
08-30 17:08:28.282   285  1015 D CommandListener: Trying to bring up p2p0
,08-30 17:08:28.282  1016  1125 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-30 17:08:28.282  1016  1125 D WifiP2pService: P2pEnablingState
,08-30 17:08:28.282  1016  1125 D WifiP2pService: P2pEnablingState{ what=147457 }
,08-30 17:08:28.282  1016  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-30 17:08:28.282  1016  1125 D WifiP2pService: P2p socket connection successful
,08-30 17:08:28.282  1016  1125 D WifiP2pService: P2pEnabledState
,08-30 17:08:28.282  1016  1016 D WifiScanningService: SCAN_AVAILABLE : 3
,08-30 17:08:28.282  1016  1149 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 17:08:28.282  1016  1016 D RttService: SCAN_AVAILABLE : 3
08-30 17:08:28.282  1016  1150 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:28.282  1016  1149 I WifiNative-HAL: startHal
08-30 17:08:28.282  1016  1149 E wifi    : getStaticLongField sWifiHalHandle 0x9ddba9bc
,08-30 17:08:28.282  1016  1149 I WifiNative-HAL: Could not start hal
08-30 17:08:28.282  1016  1149 E WifiScanningService: could not start HAL
,08-30 17:08:28.282  7708  7708 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-30 17:08:28.292  7708  7708 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-30 17:08:28.292  7708  7708 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,08-30 17:08:28.292  1016  1126 E WifiStateMachine: Failed to set frequency band 0
,08-30 17:08:28.292  1016  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-30 17:08:28.292  1016  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-30 17:08:28.292  1016  1126 E WifiNative-wlan0: invaild command id : 215
,08-30 17:08:28.292  1016  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 17:08:28.292  1016  1126 D SecContentProvider2: mCursor = null
08-30 17:08:28.292  1016  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-30 17:08:28.292  1016  1016 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-30 17:08:28.292  1016  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 17:08:28.292  1016  1126 D SecContentProvider2: mCursor = null
,08-30 17:08:28.292  1016  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-30 17:08:28.292  1016  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 17:08:28.292  1016  1047 D WifiDisplayController: disconnect
08-30 17:08:28.292  1016  1047 D WifiDisplayController: updateConnection
08-30 17:08:28.292  1016  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 17:08:28.292  1016  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-30 17:08:28.292  1016  1128 E ConnectivityService: updateNetworkInfo()
,08-30 17:08:28.302  1016  1125 D WifiNative-p2p0: p2pGetDeviceAddress
08-30 17:08:28.302  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-30 17:08:28.302  1016  1125 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
08-30 17:08:28.302  1016  1323 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-30 17:08:28.302  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-30 17:08:28.302  1016  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:08:28.302  1016  1047 D WifiDisplayAdapter: onP2pDisconnected
08-30 17:08:28.302  1016  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-30 17:08:28.302  1016  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-30 17:08:28.302  7374  7374 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE,
08-30 17:08:28.302  7374  7374 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-30 17:08:28.302  1016  1125 D WifiP2pService: DeviceAddress: 0a:76:28
,08-30 17:08:28.302  7374  7374 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED,
08-30 17:08:28.302  1016  1047 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-30 17:08:28.302  1016  1047 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-30 17:08:28.302  1016  1047 D WifiDisplayController:  primary type: 10-0050F204-5
08-30 17:08:28.302  1016  1047 D WifiDisplayController:  secondary type: null
08-30 17:08:28.302  1016  1047 D WifiDisplayController:  wps: 0
08-30 17:08:28.302  1016  1047 D WifiDisplayController:  grpcapab: 0
08-30 17:08:28.302  1016  1047 D WifiDisplayController:  devcapab: 0
08-30 17:08:28.302  1016  1047 D WifiDisplayController:  status: 3
08-30 17:08:28.302  1016  1047 D WifiDisplayController:  wfdInfo: null
08-30 17:08:28.302  1016  1047 D WifiDisplayController:  groupownerAddress: null
08-30 17:08:28.302  1016  1047 D WifiDisplayController:  GOdeviceName: null
08-30 17:08:28.302  1016  1047 D WifiDisplayController:  interfaceAddress: 
08-30 17:08:28.302  1016  1047 D WifiDisplayController:  SConnectInfo : null
08-30 17:08:28.302  7374  7374 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-30 17:08:28.302  7374  7374 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 17:08:28.302  7374  7374 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-30 17:08:28.302  7374  7390 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 17:08:28.312  7393  7393 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 17:08:28.312  7393  7393 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-30 17:08:28.312  7393  7393 D FileShare-Client: Outbound.stopDelayTimer - 
,08-30 17:08:28.322  7408  7408 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 17:08:28.332  1016  1125 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-30 17:08:28.332  1016  1125 D WifiP2pService: InactiveState
,08-30 17:08:28.332  1016  1125 D WifiP2pService: InactiveState{ what=143376 }
,08-30 17:08:28.332  1016  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-30 17:08:28.332  7708  7708 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-30 17:08:28.332  1016  1125 D WifiP2pService: InactiveState{ what=143376 }
,08-30 17:08:28.332  1016  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-30 17:08:28.482  1016  1044 D Tethering: interfaceLinkStateChanged p2p0, false
,08-30 17:08:28.482  1016  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-30 17:08:28.482  1016  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-30 17:08:28.692   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,08-30 17:08:29.122  6765  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:29.122  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:29.122  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:29.122  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:29.122  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:29.122  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:29.122  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:29.122  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:08:29.122  6765  6822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:08:29.132  6765  6822 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-30 17:08:29.132  6765  6822 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-30 17:08:29.132  6765  6822 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3a7c942d Bundle[{}]
,08-30 17:08:29.142  6765  6822 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-30 17:08:29.142  6765  6822 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-30 17:08:29.142  6765  6822 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-30 17:08:29.142  6765  6822 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-30 17:08:29.142  6765  6822 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-30 17:08:29.142  6765  6822 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-30 17:08:29.152  6765  6822 I System.out: Running OutgoingSocketThread
,08-30 17:08:29.152  6765  7715 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1346)
,08-30 17:08:29.152  6765  7715 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 42097
,08-30 17:08:29.152  6765  7715 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-30 17:08:29.552  7708  7708 I wpa_supplicant: nl80211: Received scan results (30 BSSes),
08-30 17:08:29.552  7708  7708 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-30 17:08:29.552  7708  7708 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,08-30 17:08:29.552  7708  7708 I wpa_supplicant: Trying to associate with  'G700'
08-30 17:08:29.552  7708  7708 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-30 17:08:29.552  7708  7708 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-30 17:08:29.552  1016  7713 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700',
,08-30 17:08:29.562  1016  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-30 17:08:29.562  1016  1126 D SecContentProvider2: mCursor = null
,08-30 17:08:29.682  7708  7708 E wpa_supplicant: Cmd 35605 not handled
,08-30 17:08:29.682  7708  7708 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED,
08-30 17:08:29.682  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 17:08:29.682  7708  7708 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030,
08-30 17:08:29.682  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 17:08:29.682  7708  7708 I wpa_supplicant: Associated with F4.99.3E
08-30 17:08:29.682  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-30 17:08:29.682  7708  7708 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-30 17:08:29.682  7708  7708 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-30 17:08:29.682  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 17:08:29.682  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-30 17:08:29.682  1016  1044 D Tethering: interfaceStatusChanged wlan0, false,
08-30 17:08:29.682  7708  7708 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-30 17:08:29.682  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, false
,08-30 17:08:29.682  1016  1044 D Tethering: interfaceStatusChanged wlan0, false
08-30 17:08:29.682  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 17:08:29.682  1016  1044 D Tethering: interfaceStatusChanged wlan0, false
08-30 17:08:29.682  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, true
,08-30 17:08:29.682  1016  1044 D Tethering: interfaceStatusChanged wlan0, true
,08-30 17:08:29.682  1016  1129 E Tethering: No numeric data
,08-30 17:08:29.682  1016  1123 V NetworkStats: performPollLocked(flags=0x1)
08-30 17:08:29.682  1016  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-30 17:08:29.682  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-30 17:08:29.682  1016  1129 D Tethering: clearTetheredNotification()
08-30 17:08:29.682  1177  1177 D HotspotTile: updateTetherState():false, false
08-30 17:08:29.682  7708  7708 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e,
08-30 17:08:29.682  7708  7708 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-30 17:08:29.682  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:29.682  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-30 17:08:29.682  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-30 17:08:29.692  7708  7708 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-30 17:08:29.692  7708  7708 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-30 17:08:29.692  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:29.692  1016  1123 V NetworkStats: performPollLocked() took 7ms
08-30 17:08:29.692  7708  7708 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 17:08:29.692  7708  7708 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-30 17:08:29.692  7708  7708 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,08-30 17:08:29.692  7708  7708 I wpa_supplicant: Blacklist: Clear (temp) 
08-30 17:08:29.692  7708  7708 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-30 17:08:29.692  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, true
,08-30 17:08:29.692  1016  1044 D Tethering: interfaceStatusChanged wlan0, true
,08-30 17:08:29.692  1016  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-30 17:08:29.692  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-30 17:08:29.692  1016  1126 D SecContentProvider2: mCursor = null
08-30 17:08:29.702  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:29.702  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:29.702  1016  1126 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-30 17:08:29.712  1016  1126 E WifiConfigStore: setLastSelectedConfiguration -1
,08-30 17:08:29.712  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 17:08:29.712  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-30 17:08:29.712  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:29.712  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:29.712  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:29.712  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:29.712  1016  1126 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-30 17:08:29.722  1016  1128 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-30 17:08:29.722  1016  1128 E ConnectivityService: updateNetworkInfo()
08-30 17:08:29.722  1016  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-30 17:08:29.722  1016  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 17:08:29.722  1016  1134 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-30 17:08:29.722  1016  1134 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-30 17:08:29.722  1016  1134 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:29.722  1016  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:29.722  1016  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 17:08:29.722  1595  1595 I Hs20UtilService: Starting #21
,08-30 17:08:29.722  1595  1633 I Hs20UtilService: Message received 5007
,08-30 17:08:29.722  7374  7374 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-30 17:08:29.732  1016  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 17:08:29.732  7374  7374 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 17:08:29.732  7374  7374 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 17:08:29.732  7374  7374 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-30 17:08:29.732  7374  7374 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 17:08:29.732  7374  7374 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-30 17:08:29.732  7374  7390 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 17:08:29.742   285  1015 D CommandListener: Setting iface cfg,
,08-30 17:08:29.752  1016  1126 E WifiStateMachine: Start Dhcp Watchdog 3
,08-30 17:08:29.752  1016  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-30 17:08:29.752  1016  1126 D SecContentProvider2: mCursor = null
,08-30 17:08:29.752  1016  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-30 17:08:29.752  1016  1126 D SecContentProvider2: mCursor = null
,08-30 17:08:29.762  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-30 17:08:29.762  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
08-30 17:08:29.762  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:29.762  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:29.762  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:29.762  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:29.772  1016  1126 E WifiNative-wlan0: do suspend false,
,08-30 17:08:29.772  1016  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 17:08:29.772  1016  1125 D WifiP2pService: InactiveState{ what=143375 }
08-30 17:08:29.772  1016  1126 D SecContentProvider2: mCursor = null
08-30 17:08:29.772  1016  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-30 17:08:29.982  7718  7718 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-30 17:08:29.992  7718  7718 I dhcpcd  : version 5.5.6 starting
,08-30 17:08:29.992  7718  7718 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-30 17:08:30.052  7718  7718 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-30 17:08:30.052  7718  7718 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-30 17:08:30.052  7718  7718 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-30 17:08:30.052  7718  7718 I dhcpcd  : bssid match
08-30 17:08:30.052  7718  7718 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,08-30 17:08:30.102  7718  7718 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1,
,08-30 17:08:30.152  6765  6822 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1347),
08-30 17:08:30.152  6765  6822 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1347)
08-30 17:08:30.152  6765  6822 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1352)
08-30 17:08:30.152  6765  6822 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-30 17:08:30.152  6765  6822 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1353)
08-30 17:08:30.152  6765  6822 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:08:30.152  6765  6822 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6b2a328 added. We now have 2 listener(s)
08-30 17:08:30.162  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-30 17:08:30.162  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:08:30.162  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:08:30.162  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:08:30.162  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b5d841 added. We now have 9 listener(s)
08-30 17:08:30.162  6765  6822 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-30 17:08:30.162  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 17:08:30.162  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:08:30.172  7718  7718 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
,08-30 17:08:30.172  6765  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:08:30.172  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:30.172  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:30.172  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,08-30 17:08:30.172  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:30.172  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:30.172  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:30.172  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:08:30.182  6765  6822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:08:30.182  6765  6822 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:08:30.182  6765  6822 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:08:30.182  6765  6822 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3daae327 added. We now have 3 listener(s)
08-30 17:08:30.182  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:30.182  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-30 17:08:30.182  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-30 17:08:30.182  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:08:30.182  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:08:30.182  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:08:30.182  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a22c9d4 added. We now have 10 listener(s)
08-30 17:08:30.182  6765  6822 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:08:30.182  6765  6822 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 17:08:30.182  6765  6822 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:30.182  6765  6822 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 17:08:30.182  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:30.182  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:30.182  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 17:08:30.182  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:08:30.182  6765  6822 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6b2a328 removed from the list
08-30 17:08:30.182  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-30 17:08:30.182  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b5d841 removed from the list
08-30 17:08:30.182  6765  6822 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:30.182  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,08-30 17:08:30.192  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:08:30.192  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:30.192  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:30.192  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:30.192  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:30.192  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b5d841 not in the list
08-30 17:08:30.192  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:30.192  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:30.192  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:30.192  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:30.192  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:30.192  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a22c9d4 removed from the list
08-30 17:08:30.192  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:30.192  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:30.192  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:30.192  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:08:30.192  6765  6822 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3daae327 removed from the list
08-30 17:08:30.192  6765  6822 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-30 17:08:30.192  6765  6822 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3846b77d added. We now have 2 listener(s)
,08-30 17:08:30.192  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27",
,08-30 17:08:30.192  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:08:30.192  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:08:30.192  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 17:08:30.192  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29b26672 added. We now have 9 listener(s)
08-30 17:08:30.192  6765  6822 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:08:30.192  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 17:08:30.202  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:08:30.202  6765  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:08:30.202  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:30.202  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:30.202  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:30.202  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:30.202  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:30.202  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:30.202  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:08:30.202  6765  6822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:08:30.202  6765  6822 D io.jxcore.node.ConnectivityMonitor: start: OK,
08-30 17:08:30.202  6765  6822 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:08:30.202  6765  6822 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37ccaf40 added. We now have 3 listener(s)
,08-30 17:08:30.212  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:30.212  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:30.212  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-30 17:08:30.212  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:08:30.212  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:08:30.212  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:08:30.212  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b0c4e79 added. We now have 10 listener(s)
08-30 17:08:30.212  6765  6822 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:08:30.212  6765  6822 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:08:30.212  6765  6822 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 17:08:30.212  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false,
08-30 17:08:30.212  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:08:30.212  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 17:08:30.212  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 17:08:30.222  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 17:08:30.222  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 17:08:30.222  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 17:08:30.222  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 17:08:30.222  6765  6822 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 17:08:30.232  7604  7612 D BtGatt.GattService: registerClient() - UUID=39375217-412f-4282-bb8f-0ad9d746c77c
,08-30 17:08:30.272  7604  7622 D BtGatt.GattService: onClientRegistered() - UUID=39375217-412f-4282-bb8f-0ad9d746c77c, clientIf=6
,08-30 17:08:30.272  6765  6811 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-30 17:08:30.272  7604  7664 D BtGatt.GattService: start scan with filters
08-30 17:08:30.272  7604  7627 D BtGatt.ScanManager: handling starting scan
08-30 17:08:30.272  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 17:08:30.272  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 17:08:30.272  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 17:08:30.272  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 17:08:30.282  7604  7627 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@336d367
,08-30 17:08:30.282  7604  7622 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-30 17:08:30.282  7604  7622 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:08:30.282  7604  7627 D BtGatt.ScanManager: allow scan with filters
08-30 17:08:30.282  7604  7627 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-30 17:08:30.282  7604  7627 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-30 17:08:30.282  7604  7622 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-30 17:08:30.282  7604  7622 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:08:30.282  6765  6822 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 17:08:30.282  7604  7627 D BtGatt.ScanManager: Starting BLE batch scan
08-30 17:08:30.282  7604  7627 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-30 17:08:30.282  6765  6765 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 17:08:30.282  6765  6822 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 17:08:30.282  7604  7622 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-30 17:08:30.282  7604  7622 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:08:30.282  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
,08-30 17:08:30.292  7604  7622 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-30 17:08:30.292  7604  7622 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:08:30.292  6765  6822 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-30 17:08:30.292  6765  6822 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:30.292  6765  6822 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 17:08:30.292  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:30.292  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 17:08:30.292  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 17:08:30.292  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 17:08:30.292  6765  6822 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 17:08:30.302  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 17:08:30.302  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 17:08:30.302  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 17:08:30.302  7604  7668 D BtGatt.GattService: stopScan() - queue size =1
,08-30 17:08:30.302  7604  7627 D BtGatt.ScanManager: filter size is 1,
08-30 17:08:30.302  7604  7612 D BtGatt.GattService: unregisterClient() - clientIf=6
08-30 17:08:30.302  7604  7627 D BtGatt.ScanManager: delete FilterIndex - 3,
08-30 17:08:30.302  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
08-30 17:08:30.302  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 17:08:30.302  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
,08-30 17:08:30.302  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 17:08:30.302  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 17:08:30.302  7604  7622 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-30 17:08:30.302  7604  7622 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:08:30.302  7604  7627 D BtGatt.ScanManager: stopping BLe Batch
,08-30 17:08:30.302  6765  6822 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 17:08:30.302  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 17:08:30.302  6765  6822 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 17:08:30.302  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 17:08:30.302  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 17:08:30.302  7604  7622 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-30 17:08:30.302  7604  7622 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:08:30.302  7604  7627 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-30 17:08:30.312  6765  6765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:08:30.312  6765  6765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:08:30.312  6765  6765 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 17:08:30.312  7604  7622 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-30 17:08:30.312  7604  7622 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:08:30.322  6765  6822 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:30.322  6765  6822 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:30.322  6765  6822 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:30.322  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:30.322  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:30.322  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:08:30.322  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:08:30.322  6765  6822 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3846b77d removed from the list
08-30 17:08:30.322  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:30.322  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29b26672 removed from the list
08-30 17:08:30.322  6765  6822 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:30.322  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:30.322  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:08:30.322  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:30.322  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:30.322  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:30.322  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:30.322  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29b26672 not in the list
08-30 17:08:30.322  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:30.322  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:30.322  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:30.322  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:30.322  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:30.322  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b0c4e79 removed from the list
08-30 17:08:30.322  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:30.322  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:30.322  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:30.322  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:08:30.322  6765  6822 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37ccaf40 removed from the list
,08-30 17:08:30.322  6765  6822 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:08:30.322  6765  6822 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21fa5935 added. We now have 2 listener(s)
,08-30 17:08:30.332  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-30 17:08:30.332  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:08:30.332  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:08:30.332  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:08:30.332  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c451ca added. We now have 9 listener(s)
08-30 17:08:30.332  6765  6822 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:08:30.332  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 17:08:30.332  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-30 17:08:30.332  6765  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:08:30.332  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:30.332  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:30.332  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:30.332  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:30.332  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:30.332  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:30.332  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:08:30.342  6765  6822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
08-30 17:08:30.342  6765  6822 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:08:30.342  6765  6822 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:08:30.342  6765  6822 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15692658 added. We now have 3 listener(s)
08-30 17:08:30.342  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27",
08-30 17:08:30.342  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:08:30.342  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:08:30.342  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:08:30.342  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@278453b1 added. We now have 10 listener(s)
08-30 17:08:30.342  6765  6822 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:08:30.342  6765  6822 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:08:30.342  6765  6822 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:08:30.342  6765  6822 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 17:08:30.342  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 17:08:30.342  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:08:30.342  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
,08-30 17:08:30.352  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 17:08:30.352  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,08-30 17:08:30.352  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 17:08:30.362  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 17:08:30.362  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true,
08-30 17:08:30.362  6765  6822 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 17:08:30.372  7604  7668 D BtGatt.GattService: registerClient() - UUID=be82e6b4-6a52-45a0-bf8e-e5a59630fff1
,08-30 17:08:30.382  1016  1126 E WifiNative-wlan0: do suspend true,
,08-30 17:08:30.382  1016  1042 W ProcessCpuTracker: Skipping unknown process pid 7738
,08-30 17:08:30.382  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:30.392  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-30 17:08:30.402  1016  1125 D WifiP2pService: InactiveState{ what=143375 },
08-30 17:08:30.402  1016  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-30 17:08:30.412  1016  1126 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-30 17:08:30.412  1016  1126 E WifiStateMachine: VerifyingLinkState enter
,08-30 17:08:30.412  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:08:30.412  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-30 17:08:30.412  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:30.412  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:30.412  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:30.412  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:30.412  7604  7622 D BtGatt.GattService: onClientRegistered() - UUID=be82e6b4-6a52-45a0-bf8e-e5a59630fff1, clientIf=6,
08-30 17:08:30.412  6765  6811 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-30 17:08:30.412  7604  7615 D BtGatt.GattService: start scan with filters
,08-30 17:08:30.412  1016  1128 E ConnectivityService: updateNetworkInfo()
,08-30 17:08:30.412  7604  7627 D BtGatt.ScanManager: handling starting scan
08-30 17:08:30.412  1016  1128 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
08-30 17:08:30.412  1016  1128 D ConnectivityService: Adding iface wlan0 to network 504
08-30 17:08:30.412  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 17:08:30.412  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 17:08:30.412  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 17:08:30.412  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
,08-30 17:08:30.422  7604  7622 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-30 17:08:30.422  7604  7622 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:08:30.422  7604  7627 D BtGatt.ScanManager: allow scan with filters
,08-30 17:08:30.422  7604  7627 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-30 17:08:30.422  7604  7627 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
08-30 17:08:30.422  7604  7622 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-30 17:08:30.422  7604  7622 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:08:30.422  7604  7627 D BtGatt.ScanManager: Starting BLE batch scan
08-30 17:08:30.422  7604  7627 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-30 17:08:30.422  1016  1143 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,08-30 17:08:30.422  1016  1143 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-30 17:08:30.432  7604  7622 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-30 17:08:30.432  7604  7622 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,08-30 17:08:30.432  1016  1143 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-30 17:08:30.432  1016  1143 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-30 17:08:30.432  1016  1143 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-30 17:08:30.432  7604  7622 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-30 17:08:30.432  7604  7622 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:08:30.432  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 17:08:30.442  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 17:08:30.442  1016  1128 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
08-30 17:08:30.442  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:30.442  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:30.442  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:30.442  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:30.442  1016  1128 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,08-30 17:08:30.442  1016  1498 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 17:08:30.442  6765  6822 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 17:08:30.442  1016  1498 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-30 17:08:30.442  6765  6822 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 17:08:30.442  6765  6765 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 17:08:30.442  1016  1128 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,08-30 17:08:30.442  1016  1498 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:30.442  1016  1498 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 17:08:30.442  1016  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-30 17:08:30.442  1016  1126 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,08-30 17:08:30.442  1016  1128 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-30 17:08:30.442  1016  1128 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
08-30 17:08:30.442  1016  1128 D ConnectivityService: LTETest block dns file not exists
,08-30 17:08:30.452  1595  1595 I Hs20UtilService: Starting #22
,08-30 17:08:30.452  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 17:08:30.452  1595  1633 I Hs20UtilService: Message received 5007
,08-30 17:08:30.452  7374  7374 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-30 17:08:30.452  1016  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:30.452  1016  1128 V NetworkStats: updateIfacesLocked()
08-30 17:08:30.452  1016  1128 V NetworkStats: performPollLocked(flags=0x1)
,08-30 17:08:30.452  7374  7374 I NearbySettings: MountReceiver.onReceive - Keep current state
08-30 17:08:30.452  1016  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 17:08:30.452  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-30 17:08:30.452  1016  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 17:08:30.462  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:08:30.462  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 17:08:30.462  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:30.462  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:30.462  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:30.462  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:30.462  1016  1128 V NetworkStats: performPollLocked() took 12ms
08-30 17:08:30.462  1016  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:30.472  6765  6822 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:08:30.472  6765  6822 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-30 17:08:30.472  6765  6822 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 17:08:30.472  6765  6822 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:30.472  6765  6822 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:30.472  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:30.472  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:30.472  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 17:08:30.472  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:08:30.472  6765  6822 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21fa5935 removed from the list
08-30 17:08:30.472  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:30.472  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c451ca removed from the list
08-30 17:08:30.472  6765  6822 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:30.472  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:08:30.472  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:30.472  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-30 17:08:30.472  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:30.472  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:08:30.472  1016  1128 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-30 17:08:30.472  1016  1128 E ConnectivityService: updateNetworkInfo()
08-30 17:08:30.472  1016  1128 E ConnectivityService: updateNetworkInfo()
,08-30 17:08:30.472  1016  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 17:08:30.472  1016  1128 V NetworkStats: updateIfacesLocked()
08-30 17:08:30.472  1016  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:30.472  1016  1128 V NetworkStats: performPollLocked(flags=0x1)
,08-30 17:08:30.472  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:30.472  1016  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 17:08:30.472  1016  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 17:08:30.472  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:30.472  1016  1126 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 17:08:30.472  1016  1126 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-30 17:08:30.472  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 17:08:30.472  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:30.472  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:30.472  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-30 17:08:30.482  1016  1016 I WifiTrafficPoller: mBoosterFLAG : 0
08-30 17:08:30.482  1016  1016 I WifiTrafficPoller: current booster mode : FullMode
,08-30 17:08:30.482  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c451ca not in the list
08-30 17:08:30.482  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 17:08:30.482  6765  6822 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 17:08:30.482  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 17:08:30.482  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 17:08:30.482  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 17:08:30.482  1016  1128 V NetworkStats: performPollLocked() took 7ms
08-30 17:08:30.482  1016  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:30.482  7604  7668 D BtGatt.GattService: stopScan() - queue size =1
,08-30 17:08:30.482  7604  7627 D BtGatt.ScanManager: filter size is 1
,08-30 17:08:30.482  7604  7627 D BtGatt.ScanManager: delete FilterIndex - 4
08-30 17:08:30.482  7604  7615 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-30 17:08:30.482  7604  7622 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-30 17:08:30.482  7604  7622 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:08:30.482  7604  7627 D BtGatt.ScanManager: stopping BLe Batch
,08-30 17:08:30.482  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:08:30.482  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 17:08:30.482  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 17:08:30.482  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 17:08:30.482  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 17:08:30.482  6765  6822 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 17:08:30.482  7604  7622 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-30 17:08:30.482  7604  7622 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:08:30.492  7604  7627 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-30 17:08:30.492  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
08-30 17:08:30.492  6765  6822 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 17:08:30.492  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 17:08:30.492  7604  7622 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-30 17:08:30.492  7604  7622 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:08:30.492  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:08:30.492  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-30 17:08:30.492  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:30.492  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:30.492  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:30.492  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:30.492  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:30.502  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:30.502  1016  1028 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 17:08:30.502  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:30.502  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-30 17:08:30.502  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:30.502  6765  6765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:08:30.502  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@278453b1 removed from the list
08-30 17:08:30.502  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:30.502  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:30.502  6765  6765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:08:30.502  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:30.502  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:08:30.502  6765  6765 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 17:08:30.502  6765  6822 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15692658 removed from the list
08-30 17:08:30.502  6765  6822 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:08:30.502  6765  6822 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fd979ed added. We now have 2 listener(s)
,08-30 17:08:30.502  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:30.502  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:30.502  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 17:08:30.502  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:30.502  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:30.502  1016  1128 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-30 17:08:30.502  1016  7716 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:30.502  1016  1128 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-30 17:08:30.502  1016  7716 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-30 17:08:30.502  1016  7716 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:30.502  1016  7716 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,08-30 17:08:30.502  1016  7716 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 17:08:30.502   285  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-30 17:08:30.502  1016  1128 D ConnectivityService:    accepting network in place of null
08-30 17:08:30.502   285  1011 D Netd    : getNetworkForDns: using netid 504 for uid 1000
08-30 17:08:30.502  1595  1595 I Hs20UtilService: Starting #23
08-30 17:08:30.502  1595  1633 I Hs20UtilService: Message received 5007
,08-30 17:08:30.502  1016  1125 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-30 17:08:30.502  1016  1126 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-30 17:08:30.502  1473  1473 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-30 17:08:30.502  1473  1473 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 17:08:30.502  1016  1128 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-30 17:08:30.502  1016  1128 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-30 17:08:30.502  1016  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-30 17:08:30.512  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-30 17:08:30.512  1016  1128 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
08-30 17:08:30.512  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:08:30.512  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:08:30.512  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:08:30.512  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d0d5022 added. We now have 9 listener(s)
08-30 17:08:30.512  6765  6822 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:08:30.512  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 17:08:30.512  1016  1016 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-30 17:08:30.512  1016  1129 D Tethering: MasterInitialState.processMessage what=3,
08-30 17:08:30.512  7374  7374 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-30 17:08:30.512  1016  1128 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-30 17:08:30.512  7374  7374 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-30 17:08:30.512  1016  1123 V NetworkStats: updateIfacesLocked()
,08-30 17:08:30.512  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:30.512  1016  1123 V NetworkStats: performPollLocked(flags=0x1)
08-30 17:08:30.512  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 17:08:30.512  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 17:08:30.522  1016  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-30 17:08:30.522  7374  7374 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,08-30 17:08:30.522  1177  1732 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 17:08:30.522  7374  7374 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-30 17:08:30.522  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:30.522  1016  1123 V NetworkStats: performPollLocked() took 9ms
,08-30 17:08:30.522  7374  7374 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
08-30 17:08:30.522  7374  7374 I NearbySettings: MountReceiver.onReceive - Keep current state
08-30 17:08:30.522  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:08:30.522  4791  6832 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-30 17:08:30.522  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
08-30 17:08:30.522  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-30 17:08:30.522  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-30 17:08:30.522  1177  1177 D StatusBar.NetworkController: updateDataNetType()
08-30 17:08:30.522  1177  1177 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-30 17:08:30.522  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-30 17:08:30.532  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:30.532  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:30.532  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:30.532  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:30.532  1016  1124 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,08-30 17:08:30.532  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-30 17:08:30.532  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-30 17:08:30.532  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-30 17:08:30.532  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:08:30.532  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-30 17:08:30.532  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:30.532  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:30.532  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:30.532  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:30.542  6765  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:08:30.542  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:30.542  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:30.542  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:30.542  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:30.542  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:08:30.542  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:08:30.542  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:08:30.542  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:30.542  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:30.542  6765  6822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 17:08:30.542  6765  6822 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:08:30.542  6765  6822 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:08:30.542  6765  6822 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0a6870 added. We now have 3 listener(s)
08-30 17:08:30.542  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-30 17:08:30.542  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:08:30.542  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:08:30.542  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:08:30.542  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e0c7e9 added. We now have 10 listener(s)
08-30 17:08:30.542  6765  6822 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:08:30.542  6765  6822 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:08:30.542  6765  6822 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-30 17:08:30.542  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 17:08:30.542  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:08:30.542  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 17:08:30.542  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-30 17:08:30.552  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:30.552  1016  2050 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 17:08:30.552  1016  2050 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-30 17:08:30.552  1016  2050 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:30.552  1016  2050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:30.552  1016  2050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 17:08:30.552  1595  1595 I Hs20UtilService: Starting #24
,08-30 17:08:30.552  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 17:08:30.552  7374  7374 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-30 17:08:30.552  7374  7374 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-30 17:08:30.562  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 17:08:30.562  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 17:08:30.562  1595  1633 I Hs20UtilService: Message received 5007
,08-30 17:08:30.562  1016  1497 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-30 17:08:30.572  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 17:08:30.572  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 17:08:30.572  6765  6822 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 17:08:30.572  7604  7664 D BtGatt.GattService: registerClient() - UUID=286c3652-7416-4bfe-8dec-fd7f129602ca
,08-30 17:08:30.572  1016  1536 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
,08-30 17:08:30.572  1016  1536 D SecContentProvider2: mCursor = null
,08-30 17:08:30.572  1016  1323 D SecContentProvider2: uri = 15 selection = getToastGravity
,08-30 17:08:30.572  1016  1323 D SecContentProvider2: mCursor = null
,08-30 17:08:30.572  1016  2050 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
,08-30 17:08:30.572  1016  2050 D SecContentProvider2: mCursor = null
,08-30 17:08:30.582  1016  1514 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
,08-30 17:08:30.582  1016  1514 D SecContentProvider2: mCursor = null
,08-30 17:08:30.582  1016  1497 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,08-30 17:08:30.582  1016  1497 D SecContentProvider2: mCursor = null
,08-30 17:08:30.582  1016  1498 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
,08-30 17:08:30.582  1016  1498 D SecContentProvider2: mCursor = null,
,08-30 17:08:30.612   259   259 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,08-30 17:08:30.612  7604  7622 D BtGatt.GattService: onClientRegistered() - UUID=286c3652-7416-4bfe-8dec-fd7f129602ca, clientIf=6,
08-30 17:08:30.612  6765  6811 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-30 17:08:30.612  7604  7668 D BtGatt.GattService: start scan with filters,
08-30 17:08:30.612  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
08-30 17:08:30.612  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-30 17:08:30.612  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 17:08:30.612  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 17:08:30.612  7604  7627 D BtGatt.ScanManager: handling starting scan,
,08-30 17:08:30.612  7604  7622 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-30 17:08:30.612  7604  7622 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:08:30.612  6765  6822 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 17:08:30.612  6765  6822 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 17:08:30.612  7604  7627 D BtGatt.ScanManager: allow scan with filters
08-30 17:08:30.612  7604  7627 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-30 17:08:30.612  7604  7627 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
08-30 17:08:30.612  6765  6765 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 17:08:30.622  7604  7622 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-30 17:08:30.622  7604  7622 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:08:30.622  7604  7627 D BtGatt.ScanManager: Starting BLE batch scan
08-30 17:08:30.622  7604  7627 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-30 17:08:30.622  7604  7622 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
08-30 17:08:30.622  7604  7622 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:08:30.622  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 17:08:30.622  7604  7622 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-30 17:08:30.622  7604  7622 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:08:30.622  1016  2050 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1016
,08-30 17:08:30.632  6765  6822 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 17:08:30.632  6765  6822 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-30 17:08:30.632  6765  6822 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
,08-30 17:08:30.632  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:30.632  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:30.632  1177  1177 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-30 17:08:30.632  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 17:08:30.632  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 17:08:30.632  6765  6822 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fd979ed removed from the list
08-30 17:08:30.632  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:30.632  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d0d5022 removed from the list
08-30 17:08:30.632  6765  6822 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:30.632  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:08:30.632  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:08:30.632  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-30 17:08:30.632  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:30.632  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:08:30.632  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:30.632  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 17:08:30.632  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:30.632  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d0d5022 not in the list
08-30 17:08:30.632  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 17:08:30.632  6765  6822 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 17:08:30.632  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 17:08:30.632  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-30 17:08:30.632  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 17:08:30.632  7604  7615 D BtGatt.GattService: stopScan() - queue size =1
08-30 17:08:30.632  7604  7623 D BtGatt.GattService: unregisterClient() - clientIf=6
08-30 17:08:30.632  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:08:30.632  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 17:08:30.632  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-30 17:08:30.632  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 17:08:30.632  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 17:08:30.642  7604  7627 D BtGatt.ScanManager: filter size is 1
08-30 17:08:30.642  7604  7627 D BtGatt.ScanManager: delete FilterIndex - 5
,08-30 17:08:30.642  6765  6822 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 17:08:30.642  7604  7622 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-30 17:08:30.642  7604  7622 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:08:30.642  7604  7627 D BtGatt.ScanManager: stopping BLe Batch
08-30 17:08:30.642  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 17:08:30.642  6765  6822 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 17:08:30.642  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 17:08:30.642  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:30.642  7604  7622 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-30 17:08:30.642  7604  7622 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:08:30.642  7604  7627 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-30 17:08:30.642  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:30.642  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:30.642  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:30.642  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e0c7e9 removed from the list
08-30 17:08:30.642  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:30.642  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:30.642  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:30.642  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:08:30.642  6765  6765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:08:30.642  6765  6822 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0a6870 removed from the list
08-30 17:08:30.642  6765  6765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:08:30.642  6765  6765 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 17:08:30.642  6765  6822 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:08:30.642  6765  6822 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3df4f9a5 added. We now have 2 listener(s)
08-30 17:08:30.642  7604  7622 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-30 17:08:30.642  7604  7622 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:08:30.652  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-30 17:08:30.652  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:08:30.652  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:08:30.652  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 17:08:30.652  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ffcc17a added. We now have 9 listener(s)
08-30 17:08:30.652  6765  6822 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:08:30.652  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 17:08:30.652  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:08:30.652  6765  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:08:30.652  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:30.652  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:30.652  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:30.652  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:30.652  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:08:30.652  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:08:30.652  6765  6822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:08:30.662  6765  6822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 17:08:30.662  6765  6822 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:08:30.662  6765  6822 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:08:30.662  6765  6822 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21ed588 added. We now have 3 listener(s)
,08-30 17:08:30.662   296   296 E SMD     : DCD OFF
,08-30 17:08:30.662  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-30 17:08:30.662  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:08:30.662  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:08:30.662  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:08:30.662  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b608b21 added. We now have 10 listener(s)
08-30 17:08:30.662  6765  6822 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:08:30.662  6765  6822 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:30.662  6765  6822 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:30.662  6765  6822 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:30.662  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:30.662  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:30.662  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:08:30.662  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:08:30.662  6765  6822 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3df4f9a5 removed from the list
08-30 17:08:30.662  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:30.662  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ffcc17a removed from the list
08-30 17:08:30.662  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:30.662  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:30.662  6765  6822 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:30.662  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:30.662  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:30.662  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:30.662  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:30.662  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:30.662  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:30.662  6765  6822 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ffcc17a not in the list
08-30 17:08:30.662  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:30.662  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:30.662  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:30.662  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:30.662  6765  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:30.662  6765  6822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b608b21 removed from the list
08-30 17:08:30.662  6765  6822 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:30.662  6765  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:30.662  6765  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:30.662  6765  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:08:30.662  6765  6822 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21ed588 removed from the list
08-30 17:08:30.662  6765  6822 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-30 17:08:30.662  6765  6822 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 17:08:30.662  6765  6822 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-30 17:08:30.662  6765  6822 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:08:30.662  6765  6822 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-30 17:08:30.662  6765  6822 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 17:08:30.672  6765  7756 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1360, name: My test thread name)
08-30 17:08:30.672  6765  7756 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1360, thread name: My test thread name)
08-30 17:08:30.672  6765  7756 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1360, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-30 17:08:30.672  6765  7757 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1362, name: My test thread name)
,08-30 17:08:30.672  6765  7757 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1362, thread name: My test thread name)
08-30 17:08:30.672  6765  7757 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1362, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-30 17:08:30.682  6765  6822 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-30 17:08:30.682  6765  6822 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-30 17:08:30.682  6765  6822 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,08-30 17:08:30.682  6765  6822 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-30 17:08:30.682  6765  6822 D com.test.thalitest.ThaliTestRunner: Total duration: 24218 ms
,08-30 17:08:30.682  6765  6822 I jxcore-log: *Native tests were executed*
08-30 17:08:30.682  6765  6822 I jxcore-log: 
,08-30 17:08:30.682  6765  6822 I jxcore-log: Total number of executed tests:  80
08-30 17:08:30.682  6765  6822 I jxcore-log: 
,08-30 17:08:30.682  6765  6822 I jxcore-log: Number of passed tests:  80
08-30 17:08:30.682  6765  6822 I jxcore-log: 
,08-30 17:08:30.682  6765  6822 I jxcore-log: Number of failed tests:  0
08-30 17:08:30.682  6765  6822 I jxcore-log: 
,08-30 17:08:30.682  6765  6822 I jxcore-log: Number of ignored tests:  0
08-30 17:08:30.682  6765  6822 I jxcore-log: 
,08-30 17:08:30.682  6765  6822 I jxcore-log: Total duration:  24218
08-30 17:08:30.682  6765  6822 I jxcore-log: 
,08-30 17:08:30.682  6765  6822 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-30 17:08:30.682  6765  6822 I jxcore-log: 
,08-30 17:08:30.692  6765  6822 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:08:30.692  6765  6822 I jxcore-log: 
08-30 17:08:30.692  6765  6822 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:08:30.692  6765  6822 I jxcore-log: 
08-30 17:08:30.692  6765  6822 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:08:30.692  6765  6822 I jxcore-log: 
08-30 17:08:30.702  6765  6822 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:08:30.702  6765  6822 I jxcore-log: 
08-30 17:08:30.702  6765  6822 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:08:30.702  6765  6822 I jxcore-log: 
08-30 17:08:30.702  6765  6822 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:08:30.702  6765  6822 I jxcore-log: 
08-30 17:08:30.702  6765  6765 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-30 17:08:30.702  6765  6822 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:08:30.702  6765  6822 I jxcore-log: 
08-30 17:08:30.702  6765  6822 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 17:08:30.702  6765  6822 I jxcore-log: 
08-30 17:08:30.702  6765  6822 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 17:08:30.702  6765  6822 I jxcore-log: 
08-30 17:08:30.702  6765  6822 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 17:08:30.702  6765  6822 I jxcore-log: 
08-30 17:08:30.702  6765  6822 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 17:08:30.702  6765  6822 I jxcore-log: 
08-30 17:08:30.702  6765  6822 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 17:08:30.702  6765  6822 I jxcore-log: 
08-30 17:08:30.712  6765  6822 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 17:08:30.712  6765  6822 I jxcore-log: 
08-30 17:08:30.712  6765  6822 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 17:08:30.712  6765  6822 I jxcore-log: 
08-30 17:08:30.712  6765  6822 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 17:08:30.712  6765  6822 I jxcore-log: 
08-30 17:08:30.712  6765  6822 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 17:08:30.712  6765  6822 I jxcore-log: 
08-30 17:08:30.712  6765  6822 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 17:08:30.712  6765  6822 I jxcore-log: 
08-30 17:08:30.712  6765  6822 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 17:08:30.712  6765  6822 I jxcore-log: 
08-30 17:08:30.712  6765  6822 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 17:08:30.712  6765  6822 I jxcore-log: 
08-30 17:08:30.712  6765  6822 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 17:08:30.712  6765  6822 I jxcore-log: 
08-30 17:08:30.712  6765  6822 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 17:08:30.712  6765  6822 I jxcore-log: 
,08-30 17:08:30.712  6765  6822 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 17:08:30.712  6765  6822 I jxcore-log: 
08-30 17:08:30.712  6765  6822 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 17:08:30.712  6765  6822 I jxcore-log: ,
08-30 17:08:30.712  6765  6822 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 17:08:30.712  6765  6822 I jxcore-log: 
,08-30 17:08:30.712  6765  6822 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 17:08:30.712  6765  6822 I jxcore-log: 
08-30 17:08:30.712  6765  6822 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:08:30.712  6765  6822 I jxcore-log: ,
08-30 17:08:30.712  6765  6822 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:08:30.712  6765  6822 I jxcore-log: 
,08-30 17:08:30.812  6765  6765 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 17:08:30.822  6765  6822 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 17:08:30.822  6765  6822 I jxcore-log: 
,08-30 17:08:30.862  1016  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-30 17:08:30.872  1016  1029 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4323, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-30 17:08:30.872  1016  1029 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-30 17:08:30.872  1016  1029 D BatteryService: stay LED for fully charged
,08-30 17:08:30.872  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-30 17:08:30.872  1016  1016 I MotionRecognitionService: Plugged
,08-30 17:08:30.872  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-30 17:08:30.872  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-30 17:08:30.872  1431  1431 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-30 17:08:30.872  1431  1431 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-30 17:08:30.872  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-30 17:08:30.882  7604  7604 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-30 17:08:30.882  7604  7628 D HeadsetStateMachine: Disconnected process message: 10
,08-30 17:08:30.892  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-30 17:08:30.892  1177  1177 D SViewCoverView: level :100 plugged : 2
,08-30 17:08:30.902  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
08-30 17:08:30.902  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-30 17:08:30.902  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-30 17:08:30.962  7758  7758 D AndroidRuntime: ,
08-30 17:08:30.962  7758  7758 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-30 17:08:30.972  7758  7758 D AndroidRuntime: CheckJNI is OFF,
08-30 17:08:30.972  7758  7758 D AndroidRuntime: readGMSProperty: start
08-30 17:08:30.972  7758  7758 D AndroidRuntime: readGMSProperty: already setted!!
08-30 17:08:30.972  7758  7758 D AndroidRuntime: propertySet: couldn't set property (it is from app)
,08-30 17:08:30.972  7758  7758 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-30 17:08:30.972  7758  7758 D AndroidRuntime: readGMSProperty: end
08-30 17:08:30.972  7758  7758 D AndroidRuntime: addProductProperty: start
,08-30 17:08:31.002  6765  6765 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 17:08:31.002  6765  6822 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 17:08:31.002  6765  6822 I jxcore-log: 
,08-30 17:08:31.012  1016  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,08-30 17:08:31.022  1016  1041 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:08:31.042  1016  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
08-30 17:08:31.042  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:31.042  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:31.042  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:31.042  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:31.042  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:31.042  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:08:31.042  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:08:31.042  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:08:31.052  6765  6765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 17:08:31.052  6765  6822 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:08:31.052  6765  6822 I jxcore-log: 
,08-30 17:08:31.052  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:31.052  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:31.052  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:31.052  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:31.072  7766  7766 E Zygote  : MountEmulatedStorage(),
08-30 17:08:31.072  1016  1042 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7766 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
08-30 17:08:31.072  7766  7766 E Zygote  : v2
08-30 17:08:31.072  7766  7766 I libpersona: KNOX_SDCARD checking this for 1000
08-30 17:08:31.072  7766  7766 I libpersona: KNOX_SDCARD not a persona,
,08-30 17:08:31.072  7766  7766 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-30 17:08:31.082  7766  7766 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-30 17:08:31.082  7766  7766 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-30 17:08:31.082  1016  1323 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-30 17:08:31.082  1016  1323 D SecContentProvider2: mCursor = null
,08-30 17:08:31.092   323   323 I art     : Explicit concurrent mark sweep GC freed 8689(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 614us total 19.948ms,
,08-30 17:08:31.112   323   323 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 588us total 16.978ms
,08-30 17:08:31.112  7758  7758 E AffinityControl: AffinityControl: registerfunction enter
,08-30 17:08:31.122  7766  7766 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:08:31.122  7766  7766 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:31.122   323   323 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 585us total 16.590ms
,08-30 17:08:31.142  7758  7758 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,08-30 17:08:31.142  7766  7766 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true,
08-30 17:08:31.142  6765  6765 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-30 17:08:31.142  7766  7766 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-30 17:08:31.142  7766  7766 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
08-30 17:08:31.142  6765  6822 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
,08-30 17:08:31.142  6765  6822 I jxcore-log: 
,08-30 17:08:31.162  7766  7766 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true,
08-30 17:08:31.162  7766  7766 I PCWCLIENTTRACE_PushUtil: sales region : global
08-30 17:08:31.162  1016  1536 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
08-30 17:08:31.162  7766  7766 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-30 17:08:31.162  1016  1536 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!,
08-30 17:08:31.162  7766  7766 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
08-30 17:08:31.162  1016  1536 I ActivityManager: Killing 7171:com.sec.android.diagmonagent/1000 (adj 15): empty #21
,08-30 17:08:31.172  1016  2050 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-30 17:08:31.172  1016  2050 D PackageManager: START PACKAGE DELETE: observer{271925736}
08-30 17:08:31.172  1016  2050 D PackageManager: pkg{<packageName>}
08-30 17:08:31.172  1016  2050 D PackageManager: user{0}
08-30 17:08:31.172  1016  2050 D PackageManager: caller{2000}
08-30 17:08:31.172  1016  2050 D PackageManager: flags{2}
08-30 17:08:31.172  1016  2050 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-30 17:08:31.172  1016  2050 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,08-30 17:08:31.172  1016  2050 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-30 17:08:31.172  1016  2050 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-30 17:08:31.172  1016  1042 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-30 17:08:31.172  1800  1800 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
08-30 17:08:31.172  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:31.172  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:31.172  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:31.172  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:31.182  1016  1056 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-30 17:08:31.182  1016  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-30 17:08:31.182  1016  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-30 17:08:31.182  1016  1056 D ApplicationPolicy: getApplicationUninstallationEnabled
08-30 17:08:31.182  1016  1056 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-30 17:08:31.182  1016  1056 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
,08-30 17:08:31.192  7784  7784 E Zygote  : MountEmulatedStorage(),
08-30 17:08:31.192  7784  7784 E Zygote  : v2
08-30 17:08:31.192  7784  7784 I libpersona: KNOX_SDCARD checking this for 10121
08-30 17:08:31.192  7784  7784 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:31.192  7784  7784 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:08:31.192  1016  1042 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7784 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a,
08-30 17:08:31.192  7784  7784 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 17:08:31.192  7784  7784 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 17:08:31.202  1016  1042 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
08-30 17:08:31.202  1016  1042 I ActivityManager: Killing 6765:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-30 17:08:31.232  7784  7784 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:08:31.232  7784  7784 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:31.292  1016  1056 W PackageSettings: Skipping PackageSetting{1a580864 com.example.hello/10168} due to missing metadata
,08-30 17:08:31.322  1016  1042 I ActivityManager:   Force finishing activity ActivityRecord{17b0c50d u0 com.test.thalitest/.MainActivity t2}
,08-30 17:08:31.322  1016  1042 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-30 17:08:31.342  1016  1042 D InputDispatcher: Focus left window: 6765
08-30 17:08:31.342   259   450 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
08-30 17:08:31.342   259  1038 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-30 17:08:31.352  1016  1042 D InputDispatcher: Focused application released
,08-30 17:08:31.352  1016  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-30 17:08:31.352  1016  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-30 17:08:31.362  1016  1415 W WindowManager: Failed looking up window
08-30 17:08:31.362  1016  1415 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@17537404 does not exist
08-30 17:08:31.362  1016  1415 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:11074)
08-30 17:08:31.362  1016  1415 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:11065)
08-30 17:08:31.362  1016  1415 W WindowManager: 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1644)
08-30 17:08:31.362  1016  1415 W WindowManager: 	at android.os.BinderProxy.sendDeathNotice(Binder.java:551)
,08-30 17:08:31.362  1016  1415 I WindowState: WIN DEATH: null
,08-30 17:08:31.362  1016  1042 D FocusedStackFrame: Set to : 0
,08-30 17:08:31.362  1016  1042 W ActivityManager: mDVFSHelper.acquire()
,08-30 17:08:31.372  1016  1042 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false,
,08-30 17:08:31.382  1016  1016 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-30 17:08:31.382  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:31.382  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:31.382  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:31.382  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:31.392  7800  7800 E Zygote  : MountEmulatedStorage(),
,08-30 17:08:31.392  7800  7800 E Zygote  : v2
08-30 17:08:31.392  7800  7800 I libpersona: KNOX_SDCARD checking this for 10001
08-30 17:08:31.392  2598  3262 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 15
08-30 17:08:31.392  7800  7800 I libpersona: KNOX_SDCARD not a persona,
08-30 17:08:31.392  7800  7800 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:08:31.402  7800  7800 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-30 17:08:31.402  7800  7800 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-30 17:08:31.402  1016  1016 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7800 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 17:08:31.412  1499  1499 D Launcher: onRestart, Launcher: 911425283
,08-30 17:08:31.412  1016  1495 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,08-30 17:08:31.412  1016  1495 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,08-30 17:08:31.412  1016  1495 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:31.412  1016  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:31.412  1016  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,08-30 17:08:31.412  1016  1056 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,08-30 17:08:31.422  7800  7800 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:31.422  7800  7800 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:31.422  7784  7784 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 17:08:31.422  7784  7784 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-30 17:08:31.422  7784  7784 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 17:08:31.462  1016  1056 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-30 17:08:31.482  1499  1499 D Launcher: onStart, Launcher: 911425283
08-30 17:08:31.482  1499  1499 D Launcher.HomeView: onStart
,08-30 17:08:31.482  1499  1499 D Launcher: onResume, Launcher: 911425283
,08-30 17:08:31.482  1016  1498 D SettingsProvider: name = kids_home_mode
08-30 17:08:31.482  1016  1498 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:31.482  1016  1498 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:31.482  1016  1498 D SettingsProvider: selectionArgs: false
08-30 17:08:31.482  1016  1536 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
08-30 17:08:31.482  1016  1498 D SettingsProvider: selectionArgs: 10006
08-30 17:08:31.482  1016  1498 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:31.482  1016  1498 D SettingsProvider: ret = -1
,08-30 17:08:31.482  1499  1499 D Launcher.HomeView: onResume
,08-30 17:08:31.492  1800  1800 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-30 17:08:31.492  1800  1800 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
08-30 17:08:31.492  1800  1800 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,08-30 17:08:31.492  1800  1800 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-30 17:08:31.492  1016  1536 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:31.492  1016  1536 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:31.492  1016  1536 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:31.492  1016  1536 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:31.492  7784  7784 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:08:31.502  7816  7816 E Zygote  : MountEmulatedStorage()
08-30 17:08:31.502  7816  7816 E Zygote  : v2
08-30 17:08:31.502  7816  7816 I libpersona: KNOX_SDCARD checking this for 10031
08-30 17:08:31.502  7816  7816 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:31.502  7816  7816 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:08:31.502  1016  1536 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7816 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,08-30 17:08:31.512  1499  1499 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-30 17:08:31.512  7816  7816 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 17:08:31.512  4791  4791 I art     : Explicit concurrent mark sweep GC freed 22483(1365KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 12MB/21MB, paused 1.343ms total 85.575ms
,08-30 17:08:31.512  7816  7816 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 17:08:31.512  1016  1128 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-30 17:08:31.522  2635  2635 I art     : Explicit concurrent mark sweep GC freed 19823(1131KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 1.041ms total 97.340ms
,08-30 17:08:31.572  7816  7816 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:31.572  7816  7816 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:31.582  1016  1098 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 17:08:31.592  1866  1866 E SamsungIME: mOCRHelper is null
,08-30 17:08:31.592  1969  2148 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-30 17:08:31.602  1016  1123 V NetworkStats: removeUidsLocked() for UIDs [10171]
,08-30 17:08:31.602  1473  1473 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-30 17:08:31.602  1016  1123 V NetworkStats: performPollLocked(flags=0x3)
08-30 17:08:31.602  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:31.602  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-30 17:08:31.612  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 17:08:31.612  1016  1123 V NetworkStats: performPollLocked() took 12ms
,08-30 17:08:31.632  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:31.632  1016  1041 D EnterpriseDeviceManagerService: Package has changed for user 0
08-30 17:08:31.632  1016  1041 W TextServicesManagerService: no available spell checker services found
08-30 17:08:31.632  1016  1041 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-30 17:08:31.642  1800  1800 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-30 17:08:31.642  1499  1499 D MenuAppsGridFragment: onResume
,08-30 17:08:31.642  1499  1499 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-30 17:08:31.642  7784  7784 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-30 17:08:31.642  1800  1800 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-30 17:08:31.642  1499  1499 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-30 17:08:31.652  1459  1459 D PersonaManager: isKioskContainerExistOnDevice
,08-30 17:08:31.662  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:31.672  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:31.672  1016  1536 I ActivityManager: Killing 7156:com.sec.spp.push/u0a32 (adj 15): empty #21
,08-30 17:08:31.672  1016  1514 D ActivityManager: handle home activity for 0
,08-30 17:08:31.672  1016  1514 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
,08-30 17:08:31.672  1016  1514 D KnoxTimeoutHandler: post home show event for user 0
,08-30 17:08:31.672  1016  1514 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-30 17:08:31.672  1016  1514 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-30 17:08:31.672  1016  1514 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-30 17:08:31.682  1459  1459 D RegisteredServicesCache: empty dynamic service
,08-30 17:08:31.682  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 17:08:31.682  1499  1499 D Launcher.HomeView: onPause
,08-30 17:08:31.682  1499  1499 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-30 17:08:31.692  7784  7784 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-30 17:08:31.702  1016  1514 D ActivityManager: startService callerProcessName:com.android.chrome, calleePkgName: com.android.chrome
,08-30 17:08:31.702  1016  1016 I art     : Explicit concurrent mark sweep GC freed 76999(4MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 25MB/37MB, paused 11.011ms total 248.600ms
,08-30 17:08:31.702  1016  1514 D ActivityManager: retrieveServiceLocked(): component = com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService; callingUser = 0; userId(target) = 0
,08-30 17:08:31.702  1016  1514 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:31.702  1016  1514 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:31.702  1016  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.chrome, destAppInfo.processName = com.android.chrome
,08-30 17:08:31.702  1016  1056 I art     : WaitForGcToComplete blocked for 234.379ms for cause Explicit
,08-30 17:08:31.722   259   259 I SurfaceFlinger: id=15 createSurf (540x960),1 flag=4, Mauncher
,08-30 17:08:31.722  1016  1495 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 17:08:31.722  1016  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-30 17:08:31.722  1016  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-30 17:08:31.722  1016  1415 D InputDispatcher: Focus entered window: 1499
,08-30 17:08:31.722  1459  1459 D RegisteredComponentCache: Collect Tech packages for Knox
,08-30 17:08:31.732  1016  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-30 17:08:31.732  1016  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-30 17:08:31.732  1499  1499 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-30 17:08:31.732  1016  1497 D RCPManagerService: exchangeData() failure , invalid userId
08-30 17:08:31.732  1459  1459 D PersonaManager: isKioskContainerExistOnDevice
,08-30 17:08:31.742  1016  1134 D PersonaManager: isKioskContainerExistOnDevice
,08-30 17:08:31.752  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 17:08:31.752  1499  1499 V ActivityThread: updateVisibility : ActivityRecord{88282f token=android.os.BinderProxy@29f0b216 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
08-30 17:08:31.752  1499  1499 D Launcher.HomeView: onStop
,08-30 17:08:31.752  1016  1323 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-30 17:08:31.762  1016  1028 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-30 17:08:31.762  1016  1028 D SecContentProvider2: mCursor = null
,08-30 17:08:31.762  1016  7716 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-30 17:08:31.782  1016  7838 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-30 17:08:31.792  1016  1323 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6765 uid 10171
,08-30 17:08:31.792  1016  7799 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-30 17:08:31.792  1016  7799 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-30 17:08:31.792  1016  7799 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:31.792  1016  7799 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:31.792  1016  7799 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-30 17:08:31.802  1016  1028 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-30 17:08:31.802  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:31.802  7266  7266 D WaitQueueForNetworkActivate: notifyNetworkActivated
08-30 17:08:31.802  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:31.802  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:31.802  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:31.812  1866  1866 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-30 17:08:31.812  7841  7841 I libpersona: KNOX_SDCARD checking this for 1000
08-30 17:08:31.812  7841  7841 E Zygote  : MountEmulatedStorage()
08-30 17:08:31.812  7841  7841 I libpersona: KNOX_SDCARD not a persona
08-30 17:08:31.812  7841  7841 E Zygote  : v2,
08-30 17:08:31.812  7841  7841 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:08:31.812  7841  7841 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-30 17:08:31.822  7841  7841 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:08:31.822  1016  1028 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7841 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,08-30 17:08:31.822  1016  1016 D RCPManagerService: PackageReceiver onReceive(),
08-30 17:08:31.822  1016  1016 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-30 17:08:31.832  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-30 17:08:31.832  7020  7840 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-30 17:08:31.832  7020  7840 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 17:08:31.832  7020  7840 I System.out: (HTTPLog)-Static: isShipBuild true
08-30 17:08:31.832  7020  7840 I System.out: (HTTPLog)-Thread-1270-230964022: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-30 17:08:31.832  7020  7840 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 17:08:31.842  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 17:08:31.842   285  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
,08-30 17:08:31.842   285  1011 D Netd    : getNetworkForDns: using netid 504 for uid 10102
,08-30 17:08:31.842  1016  1016 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,08-30 17:08:31.852  1016  1016 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,08-30 17:08:31.852  1016  1016 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
08-30 17:08:31.852  7841  7841 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:08:31.852  7841  7841 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:31.852  1016  1047 W ActivityManager: mDVFSHelper.release()
08-30 17:08:31.852  1016  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2d098f92 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:147368
,08-30 17:08:31.872  1016  1016 I OTPFW   : ProvisionData::getAllEntries Enter
,08-30 17:08:31.872  1016  1016 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-30 17:08:31.912  1016  1134 I ActivityManager: Killing 7191:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-30 17:08:31.932  1016  1514 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-30 17:08:31.942  1016  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:31.942  1016  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:31.942  2755  7861 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-30 17:08:31.942  2755  7861 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
08-30 17:08:31.942  1016  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:31.942  2755  7861 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-30 17:08:31.942  1016  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:31.962  1016  1056 I art     : Explicit concurrent mark sweep GC freed 13895(1079KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 24MB/36MB, paused 5.896ms total 248.308ms
,08-30 17:08:31.962  7862  7862 E Zygote  : MountEmulatedStorage(),
,08-30 17:08:31.962  7862  7862 E Zygote  : v2
08-30 17:08:31.962  7862  7862 I libpersona: KNOX_SDCARD checking this for 10032
08-30 17:08:31.962  7862  7862 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:31.962  7862  7862 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 17:08:31.962  1016  1514 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7862 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 17:08:31.972  7862  7862 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 17:08:31.972  7862  7862 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-30 17:08:31.982  7841  7841 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-30 17:08:31.992  2755  7861 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,08-30 17:08:32.002  2755  7861 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,08-30 17:08:32.002  2755  7861 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,08-30 17:08:32.002  2755  7861 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,08-30 17:08:32.002  2755  7861 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,08-30 17:08:32.012  2755  7861 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,08-30 17:08:32.012  2755  7861 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,08-30 17:08:32.012  2755  7861 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,08-30 17:08:32.012  7862  7862 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:32.012  7862  7862 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:32.032  1016  1041 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-30 17:08:32.042  2755  7861 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,08-30 17:08:32.052  2755  7861 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-30 17:08:32.072  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 17:08:32.102  7604  7620 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-30 17:08:32.112  7862  7878 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-30 17:08:32.112  7862  7862 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,08-30 17:08:32.122  7862  7878 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-30 17:08:32.122  1016  7799 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-30 17:08:32.122  1016  7799 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:32.122  1016  7799 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:32.122  1016  7799 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:32.122  1016  7799 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:32.122  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 17:08:32.132  7862  7878 D SPPClientService: PushLog.txt file is not deleted.
08-30 17:08:32.132  7862  7878 D SPPClientService: PushLog.txt file is not deleted.
08-30 17:08:32.132  7862  7878 D SPPClientService: ============PushLog. stop!
,08-30 17:08:32.132  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 17:08:32.142  7880  7880 E Zygote  : MountEmulatedStorage()
08-30 17:08:32.142  7880  7880 E Zygote  : v2
08-30 17:08:32.142  7880  7880 I libpersona: KNOX_SDCARD checking this for 10036
08-30 17:08:32.142  7880  7880 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:32.142  7880  7880 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 17:08:32.142  1016  1041 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-30 17:08:32.142  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-30 17:08:32.142  1016  1041 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 17:08:32.142  7880  7880 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 17:08:32.142  1016  1041 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 17:08:32.142  7880  7880 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-30 17:08:32.142  1016  7799 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7880 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 17:08:32.152  1016  7799 I ActivityManager: Killing 7215:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-30 17:08:32.182  7880  7880 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:32.182  7880  7880 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:32.182  1016  1016 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-30 17:08:32.182  1016  1016 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-30 17:08:32.182  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-30 17:08:32.182  1016  1016 V EnterpriseBillingPolicy: uID is 10171
08-30 17:08:32.182  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
08-30 17:08:32.182  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-30 17:08:32.182  7841  7841 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
08-30 17:08:32.182  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-30 17:08:32.182  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-30 17:08:32.182  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-30 17:08:32.182  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-30 17:08:32.182  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-30 17:08:32.182  1016  1016 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-30 17:08:32.192  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-30 17:08:32.192  1016  1016 V EnterpriseBillingPolicy: uID is 10171
08-30 17:08:32.192  1016  3331 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-30 17:08:32.192  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
08-30 17:08:32.192  1016  1160 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
08-30 17:08:32.192  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-30 17:08:32.192  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-30 17:08:32.192  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-30 17:08:32.192  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-30 17:08:32.192  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-30 17:08:32.192  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-30 17:08:32.192  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-30 17:08:32.192  1016  1016 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
08-30 17:08:32.192  1016  1016 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
08-30 17:08:32.192  1016  1016 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
08-30 17:08:32.192  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
08-30 17:08:32.192  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-30 17:08:32.192  1016  1016 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
,08-30 17:08:32.192  1177  1177 I StatusBar: Icon Only
,08-30 17:08:32.192  1177  1177 D PanelView: There is/are notification(s) 
,08-30 17:08:32.202  7841  7841 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-30 17:08:32.202  7841  7841 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:08:32.202  7841  7841 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-30 17:08:32.202  7841  7841 I DIAGMON_AGENT: ./extraInfo: "NG700"
,08-30 17:08:32.212  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 17:08:32.212  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-30 17:08:32.212  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-30 17:08:32.212  7841  7841 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,08-30 17:08:32.212  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 17:08:32.222  1016  1514 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
08-30 17:08:32.222  1016  1514 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,08-30 17:08:32.222  1016  1514 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:32.222  1016  1514 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-30 17:08:32.222  1016  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,08-30 17:08:32.232  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-30 17:08:32.232  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-30 17:08:32.232  1016  1415 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 17:08:32.232  1016  1415 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-30 17:08:32.232  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-30 17:08:32.232  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-30 17:08:32.242  1016  1415 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:32.242  1016  1415 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:32.242  1016  1415 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:32.242  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 17:08:32.242  7880  7880 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@3f59727c
08-30 17:08:32.242  1016  1056 D PackageManager: delete codoeFile: 
,08-30 17:08:32.242  1016  1041 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-30 17:08:32.242  1016  1041 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-30 17:08:32.252  1016  1056 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
08-30 17:08:32.252  1016  1056 I AASA_removePackage: UID=10171 Target=com.test.thalitest
,08-30 17:08:32.252  1016  1056 D PackageManager: result of delete: 1{271925736}
,08-30 17:08:32.262  7880  7880 I SA      : [SSP] onCreated
,08-30 17:08:32.262  7758  7758 D AndroidRuntime: Shutting down VM
08-30 17:08:32.262  7266  7266 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,08-30 17:08:32.272   285  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-30 17:08:32.272   285  1011 D Netd    : getNetworkForDns: using netid 504 for uid 10011
,08-30 17:08:32.272  1016  1056 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-30 17:08:32.272  1016  1056 D PackageManager: userId{-1}
08-30 17:08:32.272  1016  1056 D PackageManager: andCode{true}
,08-30 17:08:32.272  1016  1056 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-30 17:08:32.272  7266  7266 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,08-30 17:08:32.272  7266  7266 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,08-30 17:08:32.272  7266  7266 D InitializeManagerStateMachine: exit::IDLE
08-30 17:08:32.272  7266  7266 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,08-30 17:08:32.282  7266  7266 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
08-30 17:08:32.282  7266  7266 D InitializeManagerStateMachine: exit::NETWORK_CHECK
08-30 17:08:32.282  7266  7266 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
08-30 17:08:32.282  7266  7266 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
08-30 17:08:32.282  7266  7266 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
08-30 17:08:32.282  7266  7266 D InitializeManagerStateMachine: entry::SUCCESS
08-30 17:08:32.282  7266  7266 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,08-30 17:08:32.282  4791  4791 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
08-30 17:08:32.282  1016  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:32.282  1016  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:32.282  1016  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:32.282  1016  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:32.292  7900  7900 E Zygote  : MountEmulatedStorage()
08-30 17:08:32.292  7900  7900 E Zygote  : v2
08-30 17:08:32.292  7900  7900 I libpersona: KNOX_SDCARD checking this for 10003
08-30 17:08:32.292  7900  7900 I libpersona: KNOX_SDCARD not a persona
08-30 17:08:32.292  7900  7900 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:08:32.292  1016  1056 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7900 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-30 17:08:32.292  7880  7880 I SA      : [TPM] There is no property file
08-30 17:08:32.292  7900  7900 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 17:08:32.302  7880  7880 I SA      : [SCU] isHaveSA() - false
,08-30 17:08:32.302  7266  7266 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
08-30 17:08:32.302  7266  7266 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,08-30 17:08:32.302  4791  7284 I iu.UploadsManager: num queued entries: 0
,08-30 17:08:32.302  7900  7900 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:08:32.302  4791  7284 I iu.UploadsManager: num updated entries: 0
08-30 17:08:32.302  7266  7266 D InitializeManagerStateMachine: exit::SUCCESS
08-30 17:08:32.302  7266  7266 D InitializeManagerStateMachine: entry::IDLE
,08-30 17:08:32.302  4791  7284 I iu.SyncManager: NEXT; no task
08-30 17:08:32.312  7880  7880 I SA      : [TPM] getModelProperty : null
08-30 17:08:32.312  7880  7880 I SA      : [TPM] getCSCProperty : null
,08-30 17:08:32.312  7880  7880 I SA      : [DM] FLOATING AMOLED FEATURE: true
08-30 17:08:32.312  7880  7880 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-30 17:08:32.312  7880  7880 I SA      : [DM] TFT FEATURE: false
,08-30 17:08:32.322  7880  7880 I SA      : [DM] init START
,08-30 17:08:32.322  7880  7880 I SA      : [DM] This device is not a Vodafone
,08-30 17:08:32.332  7880  7880 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-30 17:08:32.332  7880  7880 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
08-30 17:08:32.332  7880  7880 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,08-30 17:08:32.332  7880  7880 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
08-30 17:08:32.332  7880  7880 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
08-30 17:08:32.332  7880  7880 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
08-30 17:08:32.332  7880  7880 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
08-30 17:08:32.332  7880  7880 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 17:08:32.332  7880  7880 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
08-30 17:08:32.332  7880  7880 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
08-30 17:08:32.332  7880  7880 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-30 17:08:32.332  7880  7880 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
08-30 17:08:32.332  7880  7880 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,08-30 17:08:32.332  7880  7880 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
08-30 17:08:32.332  7880  7880 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
08-30 17:08:32.332  7880  7880 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
08-30 17:08:32.332  7880  7880 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
08-30 17:08:32.332  7880  7880 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
08-30 17:08:32.332  7880  7880 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-30 17:08:32.332  7880  7880 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-30 17:08:32.342  7880  7880 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
08-30 17:08:32.342  7880  7880 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-30 17:08:32.342  7880  7880 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-30 17:08:32.342  7880  7880 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
08-30 17:08:32.342  7880  7880 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,08-30 17:08:32.342  7880  7880 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,08-30 17:08:32.342  7880  7880 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
08-30 17:08:32.342  7880  7880 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-30 17:08:32.342  1499  1499 I Choreographer: Skipped 31 frames!  The application may be doing too much work on its main thread.
,08-30 17:08:32.342  7900  7900 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:08:32.342  1499  1499 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@29f0b216 time:147856
08-30 17:08:32.342  7900  7900 D ActivityThread: Added TimaKeyStore provider
08-30 17:08:32.342  7880  7880 I SA      : [SCU] isHaveSA() - false
08-30 17:08:32.342  7880  7880 I SA      : support phone number id : false
08-30 17:08:32.342  7880  7880 I SA      : [DM] Supports Ref Jpn : true
08-30 17:08:32.342  7880  7880 I SA      : [DM] init END
08-30 17:08:32.342  7880  7880 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-30 17:08:32.352  7880  7880 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
08-30 17:08:32.352  7880  7880 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-30 17:08:32.352  7880  7880 I SA      : [SLFUCHKMGR] constructor called
,08-30 17:08:32.362  7880  7880 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-30 17:08:32.362  7880  7880 I SA      : [OR] == isSIMCardReady false ==
,08-30 17:08:32.362  7880  7880 I SA      : [SCU] == networkStateCheck == true
,08-30 17:08:32.372  7880  7880 I SA      : [DM] getCountryCodeFromCSC : PL
08-30 17:08:32.372  7880  7880 I SA      : isChinaCountryCode : false
08-30 17:08:32.372  7880  7880 I SA      : [SCU] is ChinestModel Data Restricted   : false
08-30 17:08:32.372  7880  7880 I SA      : [OR] == networkStateCheck true ==
,08-30 17:08:32.372  1016  1536 I ActivityManager: Killing 6846:com.google.android.gms.unstable/u0a11 (adj 15): empty #21
,08-30 17:08:32.382  7880  7880 I SA      : [OR] GetMyCountryZoneTask
,08-30 17:08:32.382  7880  7880 I SA      : [OR] onReceive END
,08-30 17:08:32.382  1016  2050 I ActivityManager: Killing 7480:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,08-30 17:08:32.392  7247  7247 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,08-30 17:08:32.392  1225  1225 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:08:32.392  1016  1514 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,08-30 17:08:32.392  1016  1514 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,08-30 17:08:32.392  7247  7247 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,08-30 17:08:32.392  1016  1514 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:32.392  1016  1514 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:32.392  1016  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
08-30 17:08:32.392  7247  7247 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,08-30 17:08:32.402  7247  7247 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,08-30 17:08:32.402  7880  7921 I SA      : [SRS] prepareGetMyCountryZone
08-30 17:08:32.402  1016  1029 I ActivityManager: Killing 7508:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,08-30 17:08:32.412  1016  1029 I ActivityManager: Killing 7685:com.samsung.android.sm/1000 (adj 15): empty #21
,08-30 17:08:32.422  2868  2868 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 30 17:08:32 GMT+02:00 2016
08-30 17:08:32.422  1016  1514 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-30 17:08:32.422  1016  1514 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-30 17:08:32.422  1016  1514 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:32.422  1016  1514 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:32.422  1016  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-30 17:08:32.422  1016  1495 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
,08-30 17:08:32.422  1016  1495 D SecContentProvider2: mCursor = null
,08-30 17:08:32.422  7880  7921 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-30 17:08:32.422  7880  7921 I SA      : [SSP] query invoked
,08-30 17:08:32.422  2868  2868 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-30 17:08:32.432  1016  1497 I splitIntent: Queue : background intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart  false.
,08-30 17:08:32.432  2868  2868 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-30 17:08:32.432  7880  7921 I SA      : [TPMU] GetMccFromDB : null
08-30 17:08:32.432  7880  7921 I SA      : [SCU] getMccFromPreferece mcc = 260
08-30 17:08:32.432  7880  7921 I SA      : [LBE] isSupportCheckDomainRegion : false
08-30 17:08:32.432  7880  7921 I SA      : [TPM] isNoProxy(default) : true
,08-30 17:08:32.432  2868  2868 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-30 17:08:32.432  2868  2868 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-30 17:08:32.442  2868  7925 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-30 17:08:32.442  2868  2868 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 30 17:08:32 GMT+02:00 2016
,08-30 17:08:32.442  1016  1029 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-30 17:08:32.442  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-30 17:08:32.442  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:32.442  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:32.442  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-30 17:08:32.442  2868  7925 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-30 17:08:32.442  2868  2868 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-30 17:08:32.442  1016  1134 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=31, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=41
,08-30 17:08:32.442  1016  1134 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-30 17:08:32.442  1016  1134 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-30 17:08:32.442  2868  7925 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
08-30 17:08:32.442  1016  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:32.442  7880  7921 E File    : fail readDirectory() errno=2
08-30 17:08:32.442  1016  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:32.442  1016  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:32.442  1016  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:32.452  2868  7925 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().START
,08-30 17:08:32.452  2868  7925 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().START 
,08-30 17:08:32.462  7926  7926 E Zygote  : MountEmulatedStorage()
08-30 17:08:32.462  7926  7926 I libpersona: KNOX_SDCARD checking this for 10090
08-30 17:08:32.462  7926  7926 E Zygote  : v2
08-30 17:08:32.462  7926  7926 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:32.462  7926  7926 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:08:32.462  7926  7926 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 17:08:32.462  1016  1134 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7926 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
08-30 17:08:32.462  7926  7926 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:08:32.472  2868  7925 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().END 
,08-30 17:08:32.472  1016  1042 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,08-30 17:08:32.472  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-30 17:08:32.472  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:32.472  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:32.472  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:32.472  7758  7758 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
08-30 17:08:32.472  2868  7925 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-30 17:08:32.482  1016  1415 I TactileAssist: enable value -1
08-30 17:08:32.482  1016  1415 I TactileAssist: internal enable value -1
08-30 17:08:32.482  1016  1415 I TactileAssist: intensity value -1
08-30 17:08:32.482  1016  1415 I TactileAssist: saveAppList value true
,08-30 17:08:32.482  1016  1415 I TactileAssist: List of disabled apps :
,08-30 17:08:32.492  7938  7938 E Zygote  : MountEmulatedStorage()
,08-30 17:08:32.492  7938  7938 E Zygote  : v2
08-30 17:08:32.492  7938  7938 I libpersona: KNOX_SDCARD checking this for 1000
08-30 17:08:32.492  7938  7938 I libpersona: KNOX_SDCARD not a persona,
,08-30 17:08:32.492  7938  7938 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:08:32.492  1016  1042 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7938 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-30 17:08:32.492  1016  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
,08-30 17:08:32.492  7938  7938 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 17:08:32.492  7926  7926 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:08:32.502  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:32.502  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:32.502  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:32.502  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:32.502  7926  7926 D ActivityThread: Added TimaKeyStore provider
08-30 17:08:32.502  7938  7938 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:08:32.522  7955  7955 E Zygote  : MountEmulatedStorage(),
08-30 17:08:32.522  7955  7955 E Zygote  : v2
08-30 17:08:32.522  7955  7955 I libpersona: KNOX_SDCARD checking this for 1000
08-30 17:08:32.522  7955  7955 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:32.522  7955  7955 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:08:32.522  1016  1042 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=7955 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
08-30 17:08:32.522  7955  7955 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 17:08:32.532  7938  7938 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:08:32.532  7955  7955 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 17:08:32.532  7938  7938 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:32.532  2868  7925 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-30 17:08:32.532  2868  7925 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,08-30 17:08:32.542  7020  7840 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-30 17:08:32.542  2868  7925 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,08-30 17:08:32.552  1016  7716 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 15:08:32 GMT], X-Android-Received-Millis=[1472569712561], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472569712319]}
08-30 17:08:32.552  1016  7716 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-30 17:08:32.552  1016  7716 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-30 17:08:32.552  1016  1128 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
08-30 17:08:32.552  1016  1128 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-30 17:08:32.552  1016  1128 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-30 17:08:32.552  1016  1128 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,08-30 17:08:32.552  1177  1732 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 17:08:32.552  1016  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-30 17:08:32.552  4791  6832 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-30 17:08:32.552  2868  7925 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,08-30 17:08:32.552  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
08-30 17:08:32.552  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-30 17:08:32.552  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-30 17:08:32.552  1177  1177 D StatusBar.NetworkController: updateDataNetType()
08-30 17:08:32.552  1177  1177 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-30 17:08:32.552  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-30 17:08:32.562  7955  7955 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:08:32.562  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-30 17:08:32.562  7955  7955 D ActivityThread: Added TimaKeyStore provider
08-30 17:08:32.562  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-30 17:08:32.562  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,08-30 17:08:32.562  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:08:32.562  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-30 17:08:32.562  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:32.562  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:32.562  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:32.562  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:32.572  7926  7926 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-30 17:08:32.582  7926  7926 D elm:15121: ELMEngine.ELMEngine( context ).
,08-30 17:08:32.582  7926  7926 D elm:15121: MDMBridge.setEnterpriseBridge()
,08-30 17:08:32.582  1016  1134 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-30 17:08:32.582  1016  1134 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-30 17:08:32.582  1016  1134 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:32.582  1016  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:32.582  1016  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-30 17:08:32.592  7926  7926 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
08-30 17:08:32.592  7938  7938 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,08-30 17:08:32.592  7926  7926 D elm:15121: ElmAgentService : onCreate()
08-30 17:08:32.592  7926  7972 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,08-30 17:08:32.592  1016  1495 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
,08-30 17:08:32.592  1016  1495 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,08-30 17:08:32.592  1016  1495 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:32.592  1016  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:32.592  1016  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,08-30 17:08:32.602  7926  7972 D elm:15121: MainReceiver.listeningToPackageRemoved()
08-30 17:08:32.602  7926  7972 D elm:15121: MDMBridge.getInstance()
,08-30 17:08:32.602  7926  7972 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
08-30 17:08:32.602  7926  7972 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-30 17:08:32.602  1016  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,08-30 17:08:32.602  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:32.612  7766  7766 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-30 17:08:32.612  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:32.612  7955  7955 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
08-30 17:08:32.612  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:32.612  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:32.612  7766  7766 I PCWCLIENTTRACE_PushUtil: sales region : global
08-30 17:08:32.612  7766  7766 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,08-30 17:08:32.612  7766  7766 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,08-30 17:08:32.632  7975  7975 E Zygote  : MountEmulatedStorage()
08-30 17:08:32.632  7975  7975 E Zygote  : v2
08-30 17:08:32.632  7975  7975 I libpersona: KNOX_SDCARD checking this for 10048
08-30 17:08:32.632  7975  7975 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:32.632  1016  1029 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7975 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a
08-30 17:08:32.632  7975  7975 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:08:32.632  2868  7925 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-30 17:08:32.632  7975  7975 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-30 17:08:32.632  1016  1514 D SecContentProvider2: uri = -1 selection = getSealedState
08-30 17:08:32.632  1016  1514 D SecContentProvider2: mCursor = null
08-30 17:08:32.632  7975  7975 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-30 17:08:32.632  7955  7955 I PopupuiReceiver_KNOX: getSealedState : true
08-30 17:08:32.642  7926  7926 D elm:15121: ElmAgentService : onDestroy().
08-30 17:08:32.642  1016  1536 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
08-30 17:08:32.642  1016  1536 D SecContentProvider2: mCursor = null
08-30 17:08:32.642  7955  7955 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
,08-30 17:08:32.642  1016  7799 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
08-30 17:08:32.642  1016  7799 D SecContentProvider2: mCursor = null
,08-30 17:08:32.642  1016  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,08-30 17:08:32.642  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:32.642  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:32.642  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:32.642  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:32.652  7955  7955 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
08-30 17:08:32.652  7955  7955 D PopupuiReceiver: Action package removed
,08-30 17:08:32.652   323   323 I art     : Explicit concurrent mark sweep GC freed 8695(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 597us total 24.959ms
,08-30 17:08:32.662  2868  7925 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-30 17:08:32.662  7975  7975 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:32.662  7975  7975 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:32.662  2868  7925 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,08-30 17:08:32.672   323   323 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 582us total 16.510ms,
,08-30 17:08:32.692   323   323 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 576us total 16.478ms,
,08-30 17:08:32.702  7990  7990 E Zygote  : MountEmulatedStorage(),
08-30 17:08:32.702  7990  7990 E Zygote  : v2
08-30 17:08:32.702  7990  7990 I libpersona: KNOX_SDCARD checking this for 1000
08-30 17:08:32.702  7990  7990 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:32.702  7990  7990 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:08:32.712  7990  7990 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 17:08:32.712  1016  1029 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7990 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-30 17:08:32.712  7990  7990 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:08:32.722  1016  1029 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,08-30 17:08:32.722  2868  2868 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
08-30 17:08:32.722  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:32.722  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:32.722  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:32.722  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:32.732  7990  7990 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:32.732  7990  7990 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:32.732  8005  8005 E Zygote  : MountEmulatedStorage()
08-30 17:08:32.732  8005  8005 I libpersona: KNOX_SDCARD checking this for 10029
08-30 17:08:32.732  8005  8005 E Zygote  : v2
08-30 17:08:32.732  8005  8005 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:32.742  8005  8005 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:08:32.742  8005  8005 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 17:08:32.742  8005  8005 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 17:08:32.742  1016  1029 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=8005 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,08-30 17:08:32.752  1016  1029 I ActivityManager: Killing 6569:com.samsung.android.securitylogagent/1000 (adj 15): empty #21
,08-30 17:08:32.752  1016  1029 I ActivityManager: Killing 7393:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
08-30 17:08:32.752  1016  7799 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,08-30 17:08:32.752  1016  7799 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:32.752  1016  7799 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:32.752  1016  7799 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:32.752  1016  7799 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:32.762  8005  8005 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:32.762  8005  8005 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:32.772  7990  7990 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-30 17:08:32.772  7975  7975 D Compatibility: onReceive() it will make start service
08-30 17:08:32.772  8020  8020 E Zygote  : MountEmulatedStorage()
08-30 17:08:32.772  8020  8020 E Zygote  : v2
08-30 17:08:32.772  8020  8020 I libpersona: KNOX_SDCARD checking this for 10145
08-30 17:08:32.772  8020  8020 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:32.772  8020  8020 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51

```
