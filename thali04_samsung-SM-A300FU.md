#### Test 83627337ab51778_thali04_samsung-SM-A300FU Logs


```
--------- beginning of system
,09-09 13:35:17.983  1015  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-09 13:35:17.983  1015  1027 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-09 13:35:17.983  1015  1027 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-09 13:35:17.983  1015  1027 D BatteryService: stay LED for fully charged
09-09 13:35:17.983  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-09 13:35:17.983  1015  1015 I MotionRecognitionService: Plugged
09-09 13:35:17.983  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
--------- beginning of main
09-09 13:35:17.993  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-09 13:35:17.993  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
09-09 13:35:17.993  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-09 13:35:17.993  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
09-09 13:35:18.003  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-09 13:35:18.003  3179  3179 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-09 13:35:18.003  3179  3282 D HeadsetStateMachine: Disconnected process message: 10
09-09 13:35:18.013  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-09 13:35:18.013  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-09 13:35:18.013  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
09-09 13:35:18.013  1177  1177 D SViewCoverView: level :100 plugged : 2
09-09 13:35:18.253  6720  6720 D AndroidRuntime: 
09-09 13:35:18.253  6720  6720 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-09 13:35:18.253  6720  6720 D AndroidRuntime: CheckJNI is OFF
09-09 13:35:18.253  6720  6720 D AndroidRuntime: readGMSProperty: start
09-09 13:35:18.253  6720  6720 D AndroidRuntime: readGMSProperty: already setted!!
09-09 13:35:18.253  6720  6720 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-09 13:35:18.253  6720  6720 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-09 13:35:18.253  6720  6720 D AndroidRuntime: readGMSProperty: end
09-09 13:35:18.253  6720  6720 D AndroidRuntime: addProductProperty: start
09-09 13:35:18.413  6720  6720 E AffinityControl: AffinityControl: registerfunction enter
09-09 13:35:18.433  6720  6720 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-09 13:35:18.443  1015  1570 E PersonaManagerService: inState():  stateMachine is null !!
09-09 13:35:18.443  1015  1570 I PersonaManagerService: PersonaId don't exist
09-09 13:35:18.443  1015  1570 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-09 13:35:18.453  1015  1570 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-09 13:35:18.463  1015  1570 W ActivityManager: mDVFSHelper.acquire()
09-09 13:35:18.473   257   257 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
09-09 13:35:18.473   257   257 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
09-09 13:35:18.483  1015  1570 D FocusedStackFrame: Set to : 0
09-09 13:35:18.493  1015  1570 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:18.493  1015  1570 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:18.493  1015  1570 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:18.493  1015  1570 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:18.503  1015  1045 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-09 13:35:18.503  1015  1045 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-09 13:35:18.503  1015  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-09 13:35:18.503  1015  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-09 13:35:18.503   257   257 I SurfaceFlinger: id=12 createSurf (540x960),1 flag=404, uhalitest
09-09 13:35:18.503  6731  6731 E Zygote  : MountEmulatedStorage()
09-09 13:35:18.503  6731  6731 I libpersona: KNOX_SDCARD checking this for 10171
09-09 13:35:18.503  6731  6731 E Zygote  : v2
09-09 13:35:18.503  6731  6731 I libpersona: KNOX_SDCARD not a persona
09-09 13:35:18.513  6731  6731 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 13:35:18.513  1015  1570 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
09-09 13:35:18.513  1015  1570 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6731 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-09 13:35:18.513  1015  1570 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-09 13:35:18.513  6731  6731 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 13:35:18.513  6731  6731 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-09 13:35:18.513  1015  1570 D InputDispatcher: Focused application set to: xxxx
09-09 13:35:18.513  1015  1570 D InputDispatcher: Focus left window: 1478
09-09 13:35:18.513  6720  6720 D AndroidRuntime: Shutting down VM
09-09 13:35:18.523  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-09 13:35:18.523  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
09-09 13:35:18.533  6731  6731 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:35:18.533  6731  6731 D ActivityThread: Added TimaKeyStore provider
09-09 13:35:18.543  1015  1027 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
09-09 13:35:18.553  1015  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-09 13:35:18.553  1015  1015 V ActivityManager: Display changed displayId=0
09-09 13:35:18.563  1015  1027 D PersonaManager: isKioskContainerExistOnDevice
09-09 13:35:18.583  1015  1015 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
09-09 13:35:18.603   257  1152 I SurfaceFlinger: id=7 Removed Mauncher (5/9)
09-09 13:35:18.603   257   451 I SurfaceFlinger: id=7 Removed Mauncher (-2/9)
09-09 13:35:18.603  1478  1478 V ActivityThread: updateVisibility : ActivityRecord{1098c1d8 token=android.os.BinderProxy@368c9fc {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
09-09 13:35:18.603  1478  1478 D Launcher: onTrimMemory. Level: 20
09-09 13:35:18.693  6731  6731 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
09-09 13:35:18.723  6720  6720 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-09 13:35:18.733  6731  6731 I cr.library_loader: Time to load native libraries: 12 ms (timestamps 6890-6902)
09-09 13:35:18.733  6731  6731 I cr.library_loader: Expected native library version number "", actual native library version number "",
,09-09 13:35:18.753  6731  6731 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {282c78bf}
,09-09 13:35:18.753  6731  6731 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-09 13:35:18.753  6731  6731 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-09 13:35:18.783  6731  6731 I cr.BrowserStartup: Initializing chromium process, singleProcess=true,
,09-09 13:35:18.783  6731  6731 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,09-09 13:35:18.793  6731  6731 E SysUtils: ApplicationContext is null in ApplicationStatus,
,09-09 13:35:18.823  6731  6731 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-09 13:35:18.823  6731  6731 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-09 13:35:18.823  6731  6731 I Adreno-EGL: Build Date: 04/06/15 Mon
09-09 13:35:18.823  6731  6731 I Adreno-EGL: Local Branch: 
09-09 13:35:18.823  6731  6731 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-09 13:35:18.823  6731  6731 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-09 13:35:18.823  6731  6731 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-09 13:35:18.863   290   290 E SMD     : DCD OFF
,09-09 13:35:18.903  6731  6731 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-09 13:35:18.923  6731  6731 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
09-09 13:35:18.923  6731  6731 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,09-09 13:35:18.933  6731  6731 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,09-09 13:35:18.933  6731  6731 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,09-09 13:35:19.043  6731  6731 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 13:35:19.053  6731  6731 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-09 13:35:19.063  6731  6731 D PhoneWindow: *FMB* installDecor mIsFloating : false
,09-09 13:35:19.063  6731  6731 D PhoneWindow: *FMB* installDecor flags : -2139027200
,09-09 13:35:19.073  1015  1040 W ActivityManager: Activity pause timeout for ActivityRecord{3122d884 u0 com.test.thalitest/.MainActivity t2}
,09-09 13:35:19.073  6731  6731 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-09 13:35:19.083  6731  6731 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 13:35:19.083  6731  6731 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 13:35:19.123  6731  6770 D OpenGLRenderer: Render dirty regions requested: true
,09-09 13:35:19.123  1015  1486 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-09 13:35:19.123  1015  1486 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-09 13:35:19.123  1015  1486 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-09 13:35:19.123  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-09 13:35:19.123  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
,09-09 13:35:19.133  6731  6759 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,09-09 13:35:19.143  6731  6731 V ActivityThread: updateVisibility : ActivityRecord{355429f token=android.os.BinderProxy@2bb427c0 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true,
,09-09 13:35:19.143  6731  6731 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null,
09-09 13:35:19.143  6731  6731 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,09-09 13:35:19.153   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,09-09 13:35:19.163  1015  3173 D InputDispatcher: Focus entered window: 6731,
,09-09 13:35:19.173  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-09 13:35:19.173  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-09 13:35:19.173  6731  6731 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! ,
09-09 13:35:19.173  6731  6770 I OpenGLRenderer: Initialized EGL, version 1.4
09-09 13:35:19.173  6731  6770 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
09-09 13:35:19.173  6731  6770 D OpenGLRenderer: Enabling debug mode 0
,09-09 13:35:19.203  1015  1477 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-09 13:35:19.203  1177  1177 I StatusBar: Icon Only
,09-09 13:35:19.203  1177  1177 D PanelView: There is/are notification(s) 
,09-09 13:35:19.203  1015  6776 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-09 13:35:19.223  1015  1045 I ActivityManager: Displayed Component not be shown by security: +651ms (total +732ms),
09-09 13:35:19.223  1015  1045 W ActivityManager: mDVFSHelper.release()
09-09 13:35:19.223  1015  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3122d884 u0 com.test.thalitest/.MainActivity t2} time:107392
,09-09 13:35:19.223  6731  6731 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
09-09 13:35:19.233  6731  6731 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2bb427c0 time:107400
,09-09 13:35:19.233   257   448 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
09-09 13:35:19.233   257  1152 I SurfaceFlinger: id=12 Removed uhalitest (-2/9),
,09-09 13:35:19.243  2026  2026 I SamsungIME: getCurrentCandidateView
,09-09 13:35:19.353  2026  2026 D SamsungIME: Dismiss ExpandCandiate
,09-09 13:35:19.423  6731  6731 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6731
,09-09 13:35:19.513  2026  2026 I SamsungIME: getDebugLevel  : 0x4f4c
,09-09 13:35:19.563  2026  2026 I SamsungIME: getDebugLevel  : 0x4f4c
,09-09 13:35:19.593  2026  2026 I SamsungIME: KeybaordView init() : load resources
,09-09 13:35:19.613  2026  2026 I SamsungIME: getCurrentKeyboard
,09-09 13:35:19.613  2026  2026 I SamsungIME: getTextKeyboard
,09-09 13:35:19.633  6731  6731 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-09 13:35:19.633  2026  2026 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-09 13:35:19.713  6731  6779 D jxcore_app_log: JniHelper::setJavaVM(0xb809d2b0), pthread_self() = -1201496784
,09-09 13:35:19.713  6731  6779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-09 13:35:19.713  6731  6779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-09 13:35:19.713  6731  6779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-09 13:35:19.713  6731  6779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-09 13:35:19.713  6731  6779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-09 13:35:19.723  6731  6779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3255806d added. We now have 1 listener(s)
,09-09 13:35:19.723  6731  6779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,09-09 13:35:19.723  6731  6779 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-09 13:35:19.723  6731  6779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 13:35:19.723  6731  6779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 13:35:19.733  6731  6779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-09 13:35:19.733  6731  6779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-09 13:35:19.733  6731  6779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-09 13:35:19.733  6731  6779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
09-09 13:35:19.733  6731  6779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-09 13:35:19.733  6731  6779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-09 13:35:19.733  6731  6779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-09 13:35:19.733  6731  6779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-09 13:35:19.733  6731  6779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-09 13:35:19.733  6731  6779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-09 13:35:19.733  6731  6779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-09 13:35:19.733  6731  6779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-09 13:35:19.733  6731  6779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-09 13:35:19.733  6731  6779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-09 13:35:19.733  6731  6779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d0100f0 added. We now have 1 listener(s)
,09-09 13:35:19.733  6731  6779 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:35:19.743  6731  6779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:35:19.743  6731  6779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-09 13:35:19.743  6731  6779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-09 13:35:19.743  6731  6779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-09 13:35:19.743  6731  6779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-09 13:35:19.743  6731  6779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:35:19.743  6731  6779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,09-09 13:35:19.753  6731  6779 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-09 13:35:19.753  6731  6779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:19.753  6731  6779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:19.753  6731  6779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:19.753  6731  6779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:19.753  6731  6779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:19.753  6731  6779 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:19.753  6731  6779 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:19.753  6731  6779 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:35:19.753  6731  6779 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-09 13:35:19.753  6731  6779 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:35:19.753  6731  6779 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-09 13:35:19.753  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:19.763  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:19.783  6731  6731 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-09 13:35:20.023  1015  1301 E Watchdog: !@Sync 3
,09-09 13:35:20.303  6731  6786 W jxcore-log: Initializing JXcore engine
09-09 13:35:20.303  6731  6786 W jxcore-log: JXcore engine is ready
,09-09 13:35:20.363  1983  1983 E audit   : type=1400 msg=audit(1473420920.363:205): avc:  denied  { ioctl } for  pid=6786 comm="Thread-1245" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-09 13:35:20.363  1983  1983 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
09-09 13:35:20.363  1983  1983 E audit   : type=1300 msg=audit(1473420920.363:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9f1fb8f8 items=0 ppid=307 ppcomm=main pid=6786 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1245" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-09 13:35:20.363  1983  1983 E audit   : type=1320 msg=audit(1473420920.363:205): 
,09-09 13:35:20.373  6731  6786 W jxcore-log: Starting JXcore engine
,09-09 13:35:20.483  6731  6786 W jxcore-log: Platform android
09-09 13:35:20.483  6731  6786 W jxcore-log: 
09-09 13:35:20.483  6731  6786 W jxcore-log: Process ARCH arm
09-09 13:35:20.483  6731  6786 W jxcore-log: 
,09-09 13:35:20.683  6731  6786 I jxcore-log: JXcore Cordova bridge is ready!
09-09 13:35:20.683  6731  6786 I jxcore-log: 
,09-09 13:35:20.683  6731  6786 W jxcore-log: JXcore engine is started
,09-09 13:35:20.693  6731  6779 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-09 13:35:20.693  6731  6731 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41),
,09-09 13:35:20.893   325   325 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6,
09-09 13:35:20.893   325   325 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-09 13:35:21.263  1015  1533 I art     : Explicit concurrent mark sweep GC freed 27910(1474KB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 24MB/37MB, paused 2.477ms total 144.374ms
,09-09 13:35:21.863   290   290 E SMD     : DCD OFF,
,09-09 13:35:23.553  1015  3363 D SSRM:n  : SIOP:: AP = 340
,09-09 13:35:23.633  1015  1047 I PowerManagerService: [PWL] Off : 50s ago
,09-09 13:35:24.863   290   290 E SMD     : DCD OFF
,09-09 13:35:25.893   325   325 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 13:35:26.033  5622  5622 D FactoryTest: Not factory mode
,09-09 13:35:26.033  5622  5622 D FactoryTest: Not factory mode. isFactoryMode() returend false
,09-09 13:35:26.033  5622  5622 D MTPRx   : DRIVER_TIME_OUT 60s lapsed,
,09-09 13:35:26.033  5622  5622 D MTPRx   : still no open session command from host, so toast,
,09-09 13:35:26.043  5622  5622 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 ,
09-09 13:35:26.043  5622  5622 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,09-09 13:35:26.043  5622  5622 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:114212
,09-09 13:35:26.043  1015  1486 E PersonaManagerService: inState():  stateMachine is null !!
09-09 13:35:26.043  1015  1486 I PersonaManagerService: PersonaId don't exist,
09-09 13:35:26.043  1015  1486 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,09-09 13:35:26.043  1015  1486 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
,09-09 13:35:26.053  1015  1486 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:26.053  1015  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:26.053  1015  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,09-09 13:35:26.053  1015  1486 W ActivityManager: mDVFSHelper.acquire()
,09-09 13:35:26.073  1015  1486 D PersonaManager: isKioskContainerExistOnDevice
,09-09 13:35:26.073  1015  1486 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-09 13:35:26.073  1015  1486 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-09 13:35:26.073  1015  1486 D InputDispatcher: Focused application set to: xxxx
,09-09 13:35:26.073  1015  1486 D InputDispatcher: Focus left window: 6731
,09-09 13:35:26.083  5622  5622 E MTPRx   : started activity for popup
,09-09 13:35:26.093  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-09 13:35:26.093  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-09 13:35:26.103  5622  5622 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,09-09 13:35:26.103  5622  5622 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,09-09 13:35:26.103  5622  5622 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-09 13:35:26.113  5622  5622 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 13:35:26.113  5622  5622 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-09 13:35:26.113  5622  5622 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-09 13:35:26.133  5622  5622 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,09-09 13:35:26.133  1015  1533 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-09 13:35:26.133  1015  1533 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-09 13:35:26.133  1015  1533 D InputDispatcher: Focused application set to: xxxx
,09-09 13:35:26.143  1015  1533 D InputDispatcher: Focus entered window: 6731
,09-09 13:35:26.143  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-09 13:35:26.143  1015  1376 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-09 13:35:26.143  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-09 13:35:26.153  1015  1376 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@11c5c967 attribute=null, token = android.os.BinderProxy@eacd477
,09-09 13:35:26.193  5622  5622 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,09-09 13:35:26.203  5622  5622 D PhoneWindow: *FMB* installDecor mIsFloating : true
,09-09 13:35:26.203  5622  5622 D PhoneWindow: *FMB* installDecor flags : 8388610
,09-09 13:35:26.223  6731  6731 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-09 13:35:26.223  6731  6731 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,09-09 13:35:26.223  6731  6731 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-09 13:35:26.233  6731  6731 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,09-09 13:35:26.233  1015  1571 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-09 13:35:26.233  1015  1571 D KnoxTimeoutHandler: postActiveUserChange for user 0
,09-09 13:35:26.233  1015  1571 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-09 13:35:26.233  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
09-09 13:35:26.233  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,09-09 13:35:26.243  6731  6731 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-09 13:35:26.243  6731  6731 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-09 13:35:26.253  6731  6731 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2bb427c0 time:114420
,09-09 13:35:26.253  6731  6731 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@9472fbc Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@37e7fb8d, 16908290=android.view.AbsSavedState$1@37e7fb8d}, android:focusedViewId=100}]}]
,09-09 13:35:26.253  6731  6731 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-09 13:35:26.253  6731  6731 V ActivityThread: updateVisibility : ActivityRecord{355429f token=android.os.BinderProxy@2bb427c0 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-09 13:35:26.253  6731  6731 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-09 13:35:26.253  6731  6731 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-09 13:35:26.263  1015  1027 D PersonaManager: isKioskContainerExistOnDevice
,09-09 13:35:26.893   325   325 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 13:35:27.863   290   290 E SMD     : DCD OFF
,09-09 13:35:27.893   325   325 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 13:35:28.033  1015  1477 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-09 13:35:28.033  1015  1477 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-09 13:35:28.033  1015  1477 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-09 13:35:28.033  1015  1477 D BatteryService: stay LED for fully charged
,09-09 13:35:28.033  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-09 13:35:28.043  1015  1015 I MotionRecognitionService: Plugged
09-09 13:35:28.043  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,09-09 13:35:28.043  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-09 13:35:28.043  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-09 13:35:28.043  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-09 13:35:28.043  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-09 13:35:28.053  3179  3179 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-09 13:35:28.053  3179  3282 D HeadsetStateMachine: Disconnected process message: 10
,09-09 13:35:28.073  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-09 13:35:28.073  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-09 13:35:28.073  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-09 13:35:28.073  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,09-09 13:35:28.073  1177  1177 D SViewCoverView: level :100 plugged : 2
,09-09 13:35:28.513  1015  1054 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-09 13:35:28.893   325   325 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 13:35:29.053  1015  1040 W ActivityManager: mDVFSHelper.release(),
,09-09 13:35:29.893   325   325 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 13:35:30.863   290   290 E SMD     : DCD OFF,
,09-09 13:35:30.893   325   325 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,09-09 13:35:31.833  1015  1093 V AlarmManager: waitForAlarm result :4,
,09-09 13:35:31.843  1015  1093 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,09-09 13:35:31.863  1963  1963 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,09-09 13:35:31.893  1015  1571 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 13:35:31.893  1015  1571 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,09-09 13:35:31.893  1015  1571 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:31.893  1015  1571 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 13:35:31.893  1015  1571 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:31.973  4748  4748 D ConnectivityManager: CallingUid : 10011, CallingPid : 4748
,09-09 13:35:31.973  1015  1486 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-09 13:35:31.973  1015  1126 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
09-09 13:35:31.973  1015  1126 D ConnectivityService: apparently satisfied.  currentScore=60
,09-09 13:35:31.973  1015  1126 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
09-09 13:35:31.973  4748  6795 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-09 13:35:32.023  4748  6796 W DriveInitializer: Background init thread started
,09-09 13:35:32.053   256   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
09-09 13:35:32.053   256   531 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:35:32.063  4748  6796 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,09-09 13:35:32.103  1015  1132 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 13:35:32.103  1015  1132 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,09-09 13:35:32.103  1015  1132 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:32.103  1015  1132 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:32.103  1015  1132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:32.143  1015  1570 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,09-09 13:35:32.143  1015  1570 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,09-09 13:35:32.143  1015  1569 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 13:35:32.143  1015  1569 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,09-09 13:35:32.143  1015  1569 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:32.143  1015  1569 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:32.143  1015  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:32.173  4748  6796 W DriveInitializer: Background init thread ended
,09-09 13:35:32.183  1963  1963 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-09 13:35:32.193  4748  6804 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
09-09 13:35:32.193  4748  6804 D SchedPeriodicTask: Scheduled AdAttestation task.
,09-09 13:35:32.223  1015  1040 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:32.223  1015  1040 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:32.223  1015  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:32.333  1015  1486 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 13:35:32.333  1015  1486 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,09-09 13:35:32.333  1015  1486 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:32.333  1015  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:32.333  1015  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:32.363  1015  1569 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 13:35:32.363  1015  1569 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,09-09 13:35:32.373  1015  1569 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:32.373  1015  1569 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:32.373  1015  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:32.413  1015  3173 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:35:32.423  1015  3173 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:32.423  1015  3173 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:32.423  1015  3173 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:32.443  1015  1571 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:35:32.443  1015  1571 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:32.443  1015  1571 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:32.443  1015  1571 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:32.503  1015  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:35:32.503  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:32.503  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:32.503  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-09 13:35:32.503  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:32.503  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:32.503  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:32.503  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:32.523  6809  6809 E Zygote  : MountEmulatedStorage(),
,09-09 13:35:32.523  6809  6809 E Zygote  : v2
09-09 13:35:32.523  6809  6809 I libpersona: KNOX_SDCARD checking this for 10011,
09-09 13:35:32.523  6809  6809 I libpersona: KNOX_SDCARD not a persona
,09-09 13:35:32.523  1015  1028 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6809 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,09-09 13:35:32.533  6809  6809 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 13:35:32.533  6809  6809 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 13:35:32.533  6809  6809 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-09 13:35:32.553  6809  6809 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:35:32.553  6809  6809 D ActivityThread: Added TimaKeyStore provider
,09-09 13:35:32.573  6809  6809 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-09 13:35:32.583  6809  6809 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-09 13:35:32.623  6809  6809 I MultiDex: VM with version 2.1.0 has multidex support
09-09 13:35:32.623  6809  6809 I MultiDex: install
09-09 13:35:32.623  6809  6809 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-09 13:35:32.653  6809  6809 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-09 13:35:32.713  6809  6809 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-09 13:35:32.713  6809  6809 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@4b037ab: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
09-09 13:35:32.713  6809  6809 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-09 13:35:32.733  6809  6809 D ChimeraCfgMgr: Reading stored module config
,09-09 13:35:32.753  1015  1533 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,09-09 13:35:32.763  1015  1569 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:35:32.763  1015  1569 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:32.763  1015  1569 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:32.763  1015  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:32.773  1015  1376 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:35:32.773  1015  1376 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:32.773  1015  1376 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:32.773  1015  1376 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:32.803  6809  6823 I art     : Background sticky concurrent mark sweep GC freed 20968(1026KB) AllocSpace objects, 3(133KB) LOS objects, 3% free, 7MB/7MB, paused 7.539ms total 53.424ms
,09-09 13:35:32.823  1015  1323 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
09-09 13:35:32.823  1015  1323 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
09-09 13:35:32.823  1963  1963 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=280f93c2-cc08-434e-bf1f-b329b0f50b29
,09-09 13:35:32.823  1015  1323 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:32.823  1015  1323 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 13:35:32.823  1015  1323 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:32.833  1963  1963 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-09 13:35:32.843  1963  1963 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-09 13:35:32.853  6809  6826 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,09-09 13:35:32.863  6809  6809 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-09 13:35:32.863  6809  6809 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-09 13:35:32.893  1015  1571 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:35:32.893  1015  1571 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:32.893  1015  1571 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:32.893  1015  1571 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:32.943   285  1576 D WVCdm   : Instantiating CDM.
,09-09 13:35:32.943   285   676 I WVCdm   : CdmEngine::OpenSession
09-09 13:35:32.943   285   676 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,09-09 13:35:32.963   285   676 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,09-09 13:35:32.983   285   676 W WVCdm   : Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,09-09 13:35:33.023  4334  4342 I art     : Explicit concurrent mark sweep GC freed 1417(48KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 678us total 28.023ms
,09-09 13:35:33.043   285   676 I WVCdm   : CdmEngine::QueryKeyControlInfo
,09-09 13:35:33.043   285   285 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,09-09 13:35:33.043   285   285 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
09-09 13:35:33.043   285   285 I WVCdm   : CdmEngine::GenerateKeyRequest
,09-09 13:35:33.053   285   285 D WVCdm   : PrepareKeyRequest: nonce=3192988951
,09-09 13:35:33.063  6809  6822 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
09-09 13:35:33.063  6809  6822 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:35:33.063  6809  6822 I System.out: (HTTPLog)-Static: isShipBuild true
09-09 13:35:33.063  6809  6822 I System.out: (HTTPLog)-Thread-1225-707126348: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
09-09 13:35:33.063  6809  6822 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:35:33.063   280  1009 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-09 13:35:33.063   280  1009 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,09-09 13:35:33.103  1963  2149 W GCoreFlp: No location to return for getLastLocation()
,09-09 13:35:33.113  6809  6822 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-09 13:35:33.113  6809  6822 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6809, getuid(): 10011
,09-09 13:35:33.163  1015  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:35:33.163  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:33.163  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 13:35:33.163  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:33.173  1015  1571 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:35:33.173  1015  1571 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:33.173  1015  1571 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 13:35:33.173  1015  1571 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:33.183  1015  1376 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:35:33.183  1015  1376 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:33.183  1015  1376 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:33.183  1015  1376 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:33.213  4748  6805 D UdcContextInitService: registered all accounts: true
,09-09 13:35:33.213  1963  2154 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-09 13:35:33.223  1015  3382 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-09 13:35:33.223  1963  2173 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,09-09 13:35:33.363  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-09 13:35:33.363  6731  6786 I jxcore-log: 
,09-09 13:35:33.363  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-09 13:35:33.363  6731  6786 I jxcore-log: 
,09-09 13:35:33.373  6731  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:33.373  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:33.373  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:33.373  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:33.373  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:33.373  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:33.373  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:33.373  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:35:33.373  6731  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:35:33.373  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-09 13:35:33.373  6731  6786 I jxcore-log: 
,09-09 13:35:33.373  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-09 13:35:33.373  6731  6786 I jxcore-log: 
,09-09 13:35:33.393  1015  1376 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,09-09 13:35:33.403  1015  1376 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-09 13:35:33.403  6809  6822 I qtaguid : Untagging socket 30
,09-09 13:35:33.403  1015  1376 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:33.403  1015  1376 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:33.403  1015  1376 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:33.573  1015  3363 D SSRM:n  : SIOP:: AP = 350
,09-09 13:35:33.863   290   290 E SMD     : DCD OFF,
,09-09 13:35:33.913  6838  6838 I dex2oat : ----------------------------------------------------
09-09 13:35:33.913  6838  6838 I dex2oat : <SS>: S T A R T I N G . . .
09-09 13:35:33.913  6838  6838 I dex2oat : <SS>: Zip is absent. Canceled.
,09-09 13:35:33.913  6838  6838 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=44 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-09 13:35:33.953  6838  6838 I dex2oat : dex2oat took 46.573ms (threads: 4)
,09-09 13:35:33.973  6809  6822 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-09 13:35:33.973  6809  6822 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-09 13:35:33.973  6809  6822 I Adreno-EGL: Build Date: 04/06/15 Mon
09-09 13:35:33.973  6809  6822 I Adreno-EGL: Local Branch: 
09-09 13:35:33.973  6809  6822 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-09 13:35:33.973  6809  6822 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-09 13:35:33.973  6809  6822 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-09 13:35:34.053  6809  6822 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-09 13:35:34.053  6809  6822 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-09 13:35:34.053  6809  6822 I Adreno-EGL: Build Date: 04/06/15 Mon
09-09 13:35:34.053  6809  6822 I Adreno-EGL: Local Branch: 
09-09 13:35:34.053  6809  6822 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-09 13:35:34.053  6809  6822 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-09 13:35:34.053  6809  6822 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-09 13:35:34.093  6809  6822 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-09 13:35:34.093  6809  6822 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-09 13:35:34.093  6809  6822 I Adreno-EGL: Build Date: 04/06/15 Mon
09-09 13:35:34.093  6809  6822 I Adreno-EGL: Local Branch: 
09-09 13:35:34.093  6809  6822 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-09 13:35:34.093  6809  6822 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-09 13:35:34.093  6809  6822 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-09 13:35:34.093  6731  6786 I jxcore-log: Unit Test app is loaded
09-09 13:35:34.093  6731  6786 I jxcore-log: 
,09-09 13:35:34.103  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:35:34.103  6731  6786 I jxcore-log: 
,09-09 13:35:34.103  6731  6731 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-09 13:35:34.113  6731  6786 D executeNativeTests: Running unit tests
,09-09 13:35:34.113  6731  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:35:34.113  6731  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18794142 added. We now have 2 listener(s)
,09-09 13:35:34.113  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-09 13:35:34.113  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 13:35:34.113  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:35:34.113  6731  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 13:35:34.123  6731  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@188f1553 added. We now have 2 listener(s)
09-09 13:35:34.123  6731  6786 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:35:34.123  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:35:34.123  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:35:34.123  6731  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:34.123  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:34.123  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:34.123  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:34.123  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:34.123  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:34.123  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:34.123  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:35:34.133  6731  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:34.133  6731  6786 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:35:34.133  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:34.133  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:34.323  1015  1323 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,09-09 13:35:34.323  1015  1323 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,09-09 13:35:34.323  1015  1323 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:34.323  1015  1323 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:34.323  1015  1323 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:34.403  1963  6807 I art     : Explicit concurrent mark sweep GC freed 52424(2MB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 11MB/18MB, paused 1.299ms total 65.946ms
,09-09 13:35:34.423  1963  6807 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,09-09 13:35:34.423  1963  6807 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:35:34.423  1963  6807 I System.out: (HTTPLog)-Static: isShipBuild true
,09-09 13:35:34.423  1963  6807 I System.out: (HTTPLog)-Thread-261-16178917: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
09-09 13:35:34.423  1963  6807 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:35:34.423   280  1009 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-09 13:35:34.423   280  1009 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,09-09 13:35:34.433  1963  6807 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-09 13:35:34.433  1963  6807 I qtaguid : Tagging socket 60 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1963, getuid(): 10011
,09-09 13:35:34.473  1963  6807 I qtaguid : Tagging socket 63 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1963, getuid(): 10011
,09-09 13:35:34.623  1963  2173 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-09 13:35:34.633   285  1576 I WVCdm   : CdmEngine::CloseSession
,09-09 13:35:34.633  1963  2173 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,09-09 13:35:34.633  1963  2173 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-09-09 13:35:33.326+0200, stopTime=2016-09-09 13:35:34.647+0200, duration=1321ms
,09-09 13:35:34.633   285  1576 I WVCdm   : L3 Terminate.
,09-09 13:35:34.643  1963  6853 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:35:34.643   280  1009 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-09 13:35:34.643   280  1009 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,09-09 13:35:34.643  1963  6853 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-09 13:35:34.643  1963  6853 I qtaguid : Tagging socket 65 with tag 1000310500000000{268448005,0} for uid 10011, pid: 1963, getuid(): 10011
,09-09 13:35:34.683  1963  6853 I qtaguid : Tagging socket 68 with tag 1000310500000000{268448005,0} for uid 10011, pid: 1963, getuid(): 10011
,09-09 13:35:34.693  1015  1539 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,09-09 13:35:34.923  1963  6853 I qtaguid : Untagging socket 65
,09-09 13:35:34.963  1015  1533 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 13:35:34.963  1015  1533 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,09-09 13:35:34.973  1015  1533 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:34.973  1015  1533 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 13:35:34.973  1015  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:35.003  1963  2173 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,09-09 13:35:35.063  1015  3173 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:35:35.063  1015  3173 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:35.063  1015  3173 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 13:35:35.063  1015  3173 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:35.093  1015  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:35:35.093  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:35.093  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 13:35:35.093  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:35.153  1015  1132 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:35:35.153  1015  1132 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:35.153  1015  1132 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:35.153  1015  1132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:35.153  1963  6858 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-09 13:35:35.153  1963  6856 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-09 13:35:35.153  1015  1539 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:35:35.153  1015  1539 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:35.163  1015  1539 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 13:35:35.163  1015  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:35.183  1015  1570 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:35:35.183  1015  1570 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:35.183  1015  1570 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:35.183  1015  1570 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:35.183  1963  6858 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-09 13:35:35.183  1963  6856 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-09 13:35:35.183  1015  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:35:35.183  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:35.183  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:35.183  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:35.213  1015  3173 W ActivityManager: userId = 0, bbcId = -10000,
09-09 13:35:35.213  1015  3173 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-09 13:35:35.213  1015  3173 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:35.213  1015  3173 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-09 13:35:35.213  1963  6858 E CommitToConfigurationOperation: Malformed snapshot token (size): 
09-09 13:35:35.213  1963  6856 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-09 13:35:35.213  1963  6856 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,09-09 13:35:35.213  1963  6856 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-09 13:35:35.263  1015  1323 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-09 13:35:35.303  1963  6856 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:35:35.313   280  1009 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-09 13:35:35.313   280  1009 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,09-09 13:35:35.313  1963  6856 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-09 13:35:35.313  1963  6856 I qtaguid : Tagging socket 77 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1963, getuid(): 10011
,09-09 13:35:35.363  1963  6856 I qtaguid : Tagging socket 80 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1963, getuid(): 10011
,09-09 13:35:35.653  1015  1323 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-09 13:35:35.663  1963  6856 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:35:35.663  1963  6856 I qtaguid : Tagging socket 77 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1963, getuid(): 10011
,09-09 13:35:35.813  1015  1569 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-09 13:35:35.823  1963  6856 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:35:35.823  1963  6856 I qtaguid : Tagging socket 77 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 1963, getuid(): 10011
,09-09 13:35:35.903   325   325 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 13:35:35.963  1015  1028 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-09 13:35:36.063  1963  6856 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:35:36.073  1963  6856 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-09 13:35:36.073  1963  6856 I qtaguid : Tagging socket 76 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1963, getuid(): 10011
,09-09 13:35:36.103  1963  6856 I qtaguid : Tagging socket 83 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1963, getuid(): 10011
,09-09 13:35:36.303  1963  6856 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:35:36.303  1963  6856 I qtaguid : Tagging socket 77 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1963, getuid(): 10011
,09-09 13:35:36.763  1963  6852 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:35:36.763  1963  6852 I qtaguid : Tagging socket 65 with tag 1000310200000000{268448002,0} for uid 10011, pid: 1963, getuid(): 10011
,09-09 13:35:36.863   290   290 E SMD     : DCD OFF,
,09-09 13:35:36.893   325   325 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 13:35:36.963  1963  6852 I qtaguid : Untagging socket 65
,09-09 13:35:36.963  1963  2173 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,09-09 13:35:37.153  1015  1533 I art     : Explicit concurrent mark sweep GC freed 32096(1746KB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 24MB/36MB, paused 2.374ms total 159.597ms
,09-09 13:35:37.153  1015  1533 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,09-09 13:35:37.903   325   325 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 13:35:38.103  1015  1570 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-09 13:35:38.103  1015  1570 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-09 13:35:38.103  1015  1570 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
09-09 13:35:38.103  1015  1570 D BatteryService: stay LED for fully charged
,09-09 13:35:38.103  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-09 13:35:38.103  1015  1015 I MotionRecognitionService: Plugged
,09-09 13:35:38.103  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
09-09 13:35:38.113  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-09 13:35:38.113  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
09-09 13:35:38.113  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-09 13:35:38.113  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-09 13:35:38.133  3179  3179 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
09-09 13:35:38.133  3179  3282 D HeadsetStateMachine: Disconnected process message: 10
,09-09 13:35:38.143  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-09 13:35:38.143  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-09 13:35:38.143  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-09 13:35:38.143  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,09-09 13:35:38.143  1177  1177 D SViewCoverView: level :100 plugged : 2
,09-09 13:35:38.903   325   325 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 13:35:39.313  1015  1571 I ActivityManager: Killing 6430:com.google.android.apps.plus/u0a117 (adj 15): empty #21,
,09-09 13:35:39.873   290   290 E SMD     : DCD OFF
,09-09 13:35:39.893   325   325 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 13:35:40.903   325   325 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-09 13:35:42.873   290   290 E SMD     : DCD OFF
,09-09 13:35:43.613  1015  3363 D SSRM:n  : SIOP:: AP = 330
,09-09 13:35:44.253  6731  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 13:35:44.253  6731  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ac9a0f9 added. We now have 3 listener(s)
,09-09 13:35:44.253  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-09 13:35:44.253  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:35:44.253  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:35:44.253  6731  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:35:44.253  6731  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@107b983e added. We now have 3 listener(s)
09-09 13:35:44.253  6731  6786 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:35:44.253  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:35:44.253  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:35:44.263  6731  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:44.263  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:44.263  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:44.263  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:44.263  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:44.263  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:44.263  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:44.263  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:35:44.263  6731  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:35:44.263  6731  6786 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:35:44.263  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:44.263  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:44.273  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-09 13:35:44.273  6731  6786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:35:44.273  6731  6786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:35:44.273  6731  6786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 13:35:44.273  6731  6786 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-09 13:35:44.273  6731  6786 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 13:35:44.273  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 13:35:44.273  6731  6786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:35:44.273  6731  6786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:35:44.273  6731  6786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-09 13:35:44.273  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:44.273  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:44.273  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:35:44.273  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:35:44.273  6731  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ac9a0f9 removed from the list
09-09 13:35:44.273  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:44.273  6731  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@107b983e removed from the list
09-09 13:35:44.273  6731  6786 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:44.273  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:44.273  6731  6786 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-09 13:35:44.273  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:44.273  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:44.273  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:44.273  6731  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ac9a0f9 not in the list
09-09 13:35:44.273  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:35:44.273  6731  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@107b983e not in the list
09-09 13:35:44.273  6731  6786 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:44.273  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:44.273  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:44.283  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-09 13:35:44.283  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 13:35:44.283  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-09 13:35:44.283  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 13:35:44.283  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 13:35:44.283  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-09 13:35:44.283  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 13:35:44.283  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 13:35:44.283  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 13:35:44.283  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 13:35:44.283  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 13:35:44.283  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 13:35:44.283  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 13:35:44.283  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 13:35:44.283  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 13:35:44.283  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 13:35:44.283  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 13:35:44.283  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 13:35:44.283  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 13:35:44.283  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 13:35:44.283  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 13:35:44.283  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 13:35:44.283  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 13:35:44.283  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 13:35:44.283  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 13:35:44.283  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 13:35:44.283  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 13:35:44.283  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 13:35:44.283  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 13:35:44.283  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 13:35:44.283  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 13:35:44.283  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:44.283  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist ,in the list - probably already removed
09-09 13:35:44.283  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:44.283  6731  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ac9a0f9 not in the list
09-09 13:35:44.283  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:44.283  6731  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@107b983e not in the list
09-09 13:35:44.283  6731  6786 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:44.283  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:44.283  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:44.283  6731  6786 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-09 13:35:44.283  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:35:44.293  6731  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:44.293  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:44.293  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:44.293  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:44.293  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:44.293  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:44.293  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:44.293  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:35:44.293  6731  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:44.293  6731  6786 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:35:44.293  6731  6786 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-09 13:35:44.293  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-09 13:35:44.293  6731  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:35:44.293  6731  6786 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-09 13:35:44.293  6731  6786 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:35:44.293  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:35:44.293  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 13:35:44.293  6731  6786 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 13:35:44.293  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:44.303  6731  6786 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 13:35:44.303  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:35:44.303  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-09 13:35:44.303  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:35:44.303  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:35:44.303  6731  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 13:35:44.303  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:44.303  6731  6731 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 13:35:44.303  6731  6865 D BluetoothSocket: bindListen(): myUserId = 0
09-09 13:35:44.303  6731  6865 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:35:44.313  6731  6865 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[105]}
09-09 13:35:44.313  6731  6865 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 13:35:44.313  6731  6865 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 13:35:44.313  6731  6865 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3494fa4a
09-09 13:35:44.313  6731  6865 D BluetoothSocket: channel: 6
09-09 13:35:44.313  6731  6865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-09 13:35:44.323  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 13:35:44.323  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 13:35:44.323  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-09 13:35:44.323  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-09 13:35:44.323  6731  6786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 08 EC A9 50 76 27
09-09 13:35:44.323  6731  6786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 8, -20, -87, 80, 118, 39]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:35:44.323  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 8, -20, -87, 80, 118, 39]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:35:44.323  6731  6786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-09 13:35:44.353  3179  3372 D BtGatt.GattService: registerClient() - UUID=6a300a91-f159-47ac-9a3f-09561702ac18
,09-09 13:35:44.393  3179  3275 D BtGatt.GattService: onClientRegistered() - UUID=6a300a91-f159-47ac-9a3f-09561702ac18, clientIf=6
,09-09 13:35:44.403  6731  6744 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-09 13:35:44.403  3179  3278 D BtGatt.AdvertiseManager: message : 0
,09-09 13:35:44.403  3179  3278 D BtGatt.AdvertiseManager: number of adv instance running0
,09-09 13:35:44.403  3179  3278 D BtGatt.AdvertiseManager: size of list is =0
,09-09 13:35:44.403  3179  3278 D BtGatt.AdvertiseManager: starting advertising
,09-09 13:35:44.403  3179  3278 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-09 13:35:44.423  3179  3275 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-09 13:35:44.423  3179  3278 D BtGatt.AdvertiseManager: starting multi advertising
,09-09 13:35:44.423  3179  3275 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-09 13:35:44.423  3179  3278 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-09 13:35:44.423  3179  3278 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-09 13:35:44.423  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-09 13:35:44.433  6731  6786 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 13:35:44.433  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:35:44.433  6731  6731 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 13:35:44.433  6731  6786 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 13:35:44.433  6731  6731 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-09 13:35:44.433  6731  6731 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-09 13:35:44.433  6731  6731 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-09 13:35:44.433  6731  6731 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-09 13:35:44.443  6731  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-09 13:35:44.443  6731  6731 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:35:44.443  6731  6731 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:35:44.943  6731  6786 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 13:35:44.943  6731  6786 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 13:35:44.943  6731  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything,
,09-09 13:35:44.943  6731  6786 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 13:35:44.943  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 13:35:44.943  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-09 13:35:44.943  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 13:35:44.943  6731  6786 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3a5b42d8, channel: 6, state: LISTENING
09-09 13:35:44.943  6731  6786 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3a5b42d8, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3494fa4a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@32497631mSocket: android.net.LocalSocket@26307116 impl:android.net.LocalSocketImpl@12190a97 fd:FileDescriptor[105]
09-09 13:35:44.943  6731  6786 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@26307116 impl:android.net.LocalSocketImpl@12190a97 fd:FileDescriptor[105]
09-09 13:35:44.943  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 13:35:44.943  6731  6786 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:35:44.943  6731  6865 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3a5b42d8, channel: 6, state: CLOSED
09-09 13:35:44.943  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 13:35:44.943  6731  6865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 13:35:44.943  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:35:44.943  6731  6865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 13:35:44.943  6731  6865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 13:35:44.943  6731  6786 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:35:44.943  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:35:44.943  6731  6731 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 13:35:44.943  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 13:35:44.943  6731  6786 D BluetoothLeScanner: could not find callback wrapper
09-09 13:35:44.943  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 13:35:44.943  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-09 13:35:44.943  3179  3278 D BtGatt.AdvertiseManager: message : 1
09-09 13:35:44.943  3179  3278 D BtGatt.AdvertiseManager: stop advertise for client 6
09-09 13:35:44.943  3179  3278 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6
09-09 13:35:44.953  3179  3278 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-09 13:35:44.953  3179  3275 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0,
09-09 13:35:44.953  3179  3275 D BtGatt.GattService: Client app is not null!
09-09 13:35:44.953  3179  3189 D BtGatt.GattService: unregisterClient() - clientIf=6,
,09-09 13:35:44.953  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 13:35:44.953  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-09 13:35:44.953  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-09 13:35:44.953  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-09 13:35:44.953  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-09 13:35:44.963  6731  6786 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:35:44.963  6731  6786 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 13:35:44.963  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 13:35:44.963  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:35:44.963  6731  6731 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 13:35:44.963  6731  6731 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 13:35:44.963  6731  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:35:44.963  6731  6731 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-09 13:35:44.963  6731  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:35:44.963  6731  6731 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-09 13:35:44.973  6731  6731 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:35:44.973  6731  6786 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-09 13:35:44.973  6731  6786 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-09 13:35:44.973  6731  6786 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
09-09 13:35:44.973  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
,09-09 13:35:44.973  6731  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:35:44.973  6731  6786 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-09 13:35:44.973  6731  6786 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-09 13:35:44.973  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:35:44.973  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-09 13:35:44.973  6731  6786 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-09 13:35:44.973  6731  6786 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 13:35:44.973  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:35:44.973  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-09 13:35:44.973  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:35:44.973  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 13:35:44.983  6731  6731 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-09 13:35:44.983  6731  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 13:35:44.983  6731  6870 D BluetoothSocket: bindListen(): myUserId = 0
,09-09 13:35:44.993  6731  6870 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:35:44.993  6731  6870 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[105]}
,09-09 13:35:44.993  6731  6870 D BluetoothSocket: bindListen(), new LocalSocket 
,09-09 13:35:44.993  6731  6870 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,09-09 13:35:44.993  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 13:35:44.993  6731  6870 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@23a88a2
,09-09 13:35:44.993  6731  6870 D BluetoothSocket: channel: 6,
,09-09 13:35:44.993  6731  6870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...,
,09-09 13:35:44.993  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:35:45.003  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-09 13:35:45.003  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-09 13:35:45.003  6731  6786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 08 EC A9 50 76 27
,09-09 13:35:45.003  6731  6786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 8, -20, -87, 80, 118, 39]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-09 13:35:45.003  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 8, -20, -87, 80, 118, 39]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-09 13:35:45.003  6731  6786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-09 13:35:45.003  3179  3189 D BtGatt.GattService: registerClient() - UUID=3ab381c0-0048-447b-a85d-a64fedef9ba9
,09-09 13:35:45.053  3179  3275 D BtGatt.GattService: onClientRegistered() - UUID=3ab381c0-0048-447b-a85d-a64fedef9ba9, clientIf=6
,09-09 13:35:45.053  6731  6739 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-09 13:35:45.053  3179  3278 D BtGatt.AdvertiseManager: message : 0
09-09 13:35:45.053  3179  3278 D BtGatt.AdvertiseManager: number of adv instance running0
,09-09 13:35:45.053  3179  3278 D BtGatt.AdvertiseManager: size of list is =0
,09-09 13:35:45.053  3179  3278 D BtGatt.AdvertiseManager: starting advertising
09-09 13:35:45.053  3179  3278 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-09 13:35:45.063  3179  3275 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,09-09 13:35:45.063  3179  3278 D BtGatt.AdvertiseManager: starting multi advertising
,09-09 13:35:45.063  3179  3275 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-09 13:35:45.063  3179  3278 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-09 13:35:45.063  3179  3278 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-09 13:35:45.063  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-09 13:35:45.063  6731  6786 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 13:35:45.073  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:35:45.073  6731  6731 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 13:35:45.073  6731  6731 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-09 13:35:45.073  6731  6731 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-09 13:35:45.073  6731  6731 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-09 13:35:45.073  6731  6731 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-09 13:35:45.073  6731  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-09 13:35:45.073  6731  6731 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:35:45.073  6731  6731 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:35:45.083  6731  6786 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 13:35:45.083  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:35:45.083  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 13:35:45.083  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 13:35:45.083  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 13:35:45.083  6731  6786 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2e9394f0, channel: 6, state: LISTENING
09-09 13:35:45.083  6731  6786 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2e9394f0, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@23a88a2, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2dd7ba69mSocket: android.net.LocalSocket@15dc8cee impl:android.net.LocalSocketImpl@2fecb58f fd:FileDescriptor[105]
09-09 13:35:45.083  6731  6786 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@15dc8cee impl:android.net.LocalSocketImpl@2fecb58f fd:FileDescriptor[105]
09-09 13:35:45.083  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 13:35:45.083  6731  6786 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:35:45.083  6731  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ac9a0f9 not in the list
09-09 13:35:45.083  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:45.083  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:35:45.083  6731  6786 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:35:45.083  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:35:45.083  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 13:35:45.083  6731  6731 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-09 13:35:45.083  6731  6870 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2e9394f0, channel: 6, state: CLOSED
09-09 13:35:45.083  6731  6870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 13:35:45.083  6731  6870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 13:35:45.083  6731  6870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 13:35:45.083  6731  6786 D BluetoothLeScanner: could not find callback wrapper
09-09 13:35:45.083  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 13:35:45.083  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-09 13:35:45.083  3179  3278 D BtGatt.AdvertiseManager: message : 1
09-09 13:35:45.083  3179  3278 D BtGatt.AdvertiseManager: stop advertise for client 6
09-09 13:35:45.083  3179  3278 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6
09-09 13:35:45.083  3179  3278 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-09 13:35:45.083  3179  3275 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,09-09 13:35:45.083  3179  3275 D BtGatt.GattService: Client app is not null!
,09-09 13:35:45.093  3179  3372 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-09 13:35:45.093  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 13:35:45.093  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-09 13:35:45.093  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-09 13:35:45.093  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-09 13:35:45.093  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-09 13:35:45.093  6731  6786 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:35:45.093  6731  6786 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-09 13:35:45.093  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 13:35:45.093  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:35:45.103  6731  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
09-09 13:35:45.103  6731  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:35:45.103  6731  6731 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 13:35:45.103  6731  6731 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:35:45.103  6731  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@107b983e not in the list
09-09 13:35:45.103  6731  6786 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:45.103  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:45.103  6731  6786 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-09 13:35:45.103  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:35:45.103  6731  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:45.103  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:45.103  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:45.103  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:45.103  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:45.103  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:45.103  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:45.103  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:35:45.113  6731  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:35:45.113  6731  6786 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:35:45.113  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:45.113  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:45.113  6731  6786 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
,09-09 13:35:45.113  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
,09-09 13:35:45.123  6731  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 13:35:45.123  6731  6786 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-09 13:35:45.123  6731  6786 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-09 13:35:45.123  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:35:45.123  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-09 13:35:45.123  6731  6786 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true,
09-09 13:35:45.123  6731  6786 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 13:35:45.123  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:35:45.123  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-09 13:35:45.123  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
09-09 13:35:45.123  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:35:45.123  6731  6731 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-09 13:35:45.133  6731  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 13:35:45.133  6731  6873 D BluetoothSocket: bindListen(): myUserId = 0
09-09 13:35:45.133  6731  6873 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:35:45.133  6731  6873 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[105]}
09-09 13:35:45.133  6731  6873 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 13:35:45.133  6731  6873 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 13:35:45.133  6731  6873 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@26891bab
09-09 13:35:45.133  6731  6873 D BluetoothSocket: channel: 6
09-09 13:35:45.133  6731  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-09 13:35:45.133  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 13:35:45.133  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:35:45.143  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-09 13:35:45.143  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-09 13:35:45.143  6731  6786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 08 EC A9 50 76 27
,09-09 13:35:45.143  6731  6786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 8, -20, -87, 80, 118, 39]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-09 13:35:45.143  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 8, -20, -87, 80, 118, 39]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:35:45.143  6731  6786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-09 13:35:45.143  3179  3372 D BtGatt.GattService: registerClient() - UUID=06e22d7c-2501-4b9b-ade0-cd129bc56282
,09-09 13:35:45.183  3179  3275 D BtGatt.GattService: onClientRegistered() - UUID=06e22d7c-2501-4b9b-ade0-cd129bc56282, clientIf=6
,09-09 13:35:45.183  6731  6739 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-09 13:35:45.193  3179  3278 D BtGatt.AdvertiseManager: message : 0
,09-09 13:35:45.193  3179  3278 D BtGatt.AdvertiseManager: number of adv instance running0
,09-09 13:35:45.193  3179  3278 D BtGatt.AdvertiseManager: size of list is =0
,09-09 13:35:45.193  3179  3278 D BtGatt.AdvertiseManager: starting advertising
,09-09 13:35:45.193  3179  3278 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-09 13:35:45.203  3179  3275 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-09 13:35:45.203  3179  3278 D BtGatt.AdvertiseManager: starting multi advertising
,09-09 13:35:45.213  3179  3275 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-09 13:35:45.213  3179  3278 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-09 13:35:45.213  3179  3278 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-09 13:35:45.213  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-09 13:35:45.213  6731  6786 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 13:35:45.213  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:35:45.213  6731  6731 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 13:35:45.213  6731  6731 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-09 13:35:45.213  6731  6731 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-09 13:35:45.213  6731  6731 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-09 13:35:45.223  6731  6786 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 13:35:45.223  6731  6731 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-09 13:35:45.223  6731  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-09 13:35:45.223  6731  6731 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:35:45.223  6731  6731 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:35:45.723  6731  6786 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-09 13:35:45.723  6731  6786 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 13:35:45.723  6731  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-09 13:35:45.723  6731  6786 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 13:35:45.723  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 13:35:45.723  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 13:35:45.723  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 13:35:45.723  6731  6786 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@34f34da1, channel: 6, state: LISTENING
09-09 13:35:45.723  6731  6786 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@34f34da1, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@26891bab, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@18c54bc6mSocket: android.net.LocalSocket@a3bc787 impl:android.net.LocalSocketImpl@2ba946b4 fd:FileDescriptor[105]
09-09 13:35:45.723  6731  6786 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@a3bc787 impl:android.net.LocalSocketImpl@2ba946b4 fd:FileDescriptor[105]
09-09 13:35:45.723  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 13:35:45.723  6731  6786 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:35:45.723  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 13:35:45.723  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:35:45.723  6731  6786 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:35:45.723  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:35:45.723  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-09 13:35:45.723  6731  6731 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 13:35:45.723  6731  6873 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@34f34da1, channel: 6, state: CLOSED
09-09 13:35:45.723  6731  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 13:35:45.723  6731  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 13:35:45.723  6731  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-09 13:35:45.723  6731  6786 D BluetoothLeScanner: could not find callback wrapper
09-09 13:35:45.723  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 13:35:45.723  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-09 13:35:45.723  3179  3278 D BtGatt.AdvertiseManager: message : 1
,09-09 13:35:45.723  3179  3278 D BtGatt.AdvertiseManager: stop advertise for client 6
,09-09 13:35:45.723  3179  3278 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6
,09-09 13:35:45.733  3179  3278 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-09 13:35:45.733  3179  3275 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,09-09 13:35:45.733  3179  3275 D BtGatt.GattService: Client app is not null!
,09-09 13:35:45.743  3179  3280 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-09 13:35:45.743  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 13:35:45.743  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-09 13:35:45.743  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-09 13:35:45.743  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-09 13:35:45.743  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-09 13:35:45.743  6731  6786 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:35:45.743  6731  6786 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-09 13:35:45.743  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 13:35:45.743  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:35:45.753  6731  6731 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 13:35:45.753  6731  6731 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 13:35:45.753  6731  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:35:45.753  6731  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:35:45.753  6731  6731 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-09 13:35:45.753  6731  6731 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-09 13:35:45.753  6731  6731 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:35:45.753  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:35:45.753  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:35:45.753  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:35:45.753  6731  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ac9a0f9 not in the list
09-09 13:35:45.753  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:35:45.753  6731  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@107b983e not in the list
09-09 13:35:45.763  6731  6786 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:45.763  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:45.763  6731  6786 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-09 13:35:45.763  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:35:45.763  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:45.763  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:45.763  6731  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ac9a0f9 not in the list
09-09 13:35:45.763  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:35:45.763  6731  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@107b983e not in the list
09-09 13:35:45.763  6731  6786 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:45.763  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:35:45.763  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:45.763  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-09 13:35:45.763  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:35:45.763  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:45.763  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:45.763  6731  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ac9a0f9 not in the list
,09-09 13:35:45.763  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:45.763  6731  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@107b983e not in the list
09-09 13:35:45.763  6731  6786 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:35:45.763  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:45.763  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:45.773  6731  6786 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-09 13:35:45.773  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:45.773  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:35:45.773  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:45.773  6731  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ac9a0f9 not in the list
,09-09 13:35:45.773  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:35:45.773  6731  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@107b983e not in the list
,09-09 13:35:45.773  6731  6786 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:45.773  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-09 13:35:45.773  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:45.773  6731  6786 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-09 13:35:45.773  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:35:45.773  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:45.773  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:45.773  6731  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ac9a0f9 not in the list
09-09 13:35:45.773  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:45.773  6731  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@107b983e not in the list
09-09 13:35:45.773  6731  6786 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:45.773  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:35:45.773  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:45.773  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 13:35:45.773  6731  6786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:35:45.773  6731  6786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:35:45.773  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 13:35:45.773  6731  6786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1,
,09-09 13:35:45.773  6731  6786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:35:45.773  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 13:35:45.773  6731  6786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 13:35:45.773  6731  6786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:35:45.773  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:45.773  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:45.773  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:45.773  6731  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ac9a0f9 not in the list
09-09 13:35:45.773  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:45.773  6731  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@107b983e not in the list,
,09-09 13:35:45.773  6731  6786 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:35:45.773  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:45.773  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:45.773  6731  6786 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:35:45.773  6731  6786 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 13:35:45.773  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-09 13:35:45.773  6731  6786 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:35:45.773  6731  6786 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer,
09-09 13:35:45.773  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 13:35:45.773  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 13:35:45.773  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 13:35:45.773  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310],
09-09 13:35:45.773  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 13:35:45.773  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-09 13:35:45.773  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 13:35:45.773  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 13:35:45.773  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 13:35:45.773  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-09 13:35:45.773  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 13:35:45.773  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 13:35:45.773  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 13:35:45.773  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-09 13:35:45.773  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 13:35:45.773  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 13:35:45.773  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 13:35:45.773  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 13:35:45.773  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-09 13:35:45.773  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 13:35:45.773  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 13:35:45.773  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 13:35:45.773  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 13:35:45.773  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 13:35:45.773  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 13:35:45.773  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 13:35:45.773  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 13:35:45.773  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 13:35:45.773  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 13:35:45.773  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 13:35:45.773  6731  6786 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-09 13:35:45.773  6731  6786 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 13:35:45.773  6731  6786 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-09 13:35:45.773  6731  6786 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:35:45.773  6731  6786 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 13:35:45.773  6731  6786 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-09 13:35:45.773  6731  6786 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:35:45.773  6731  6786 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 13:35:45.773  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-09 13:35:45.783  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-09 13:35:45.783  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-09 13:35:45.783  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-09 13:35:45.783  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-09 13:35:45.783  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-09 13:35:45.783  6731  6786 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-09 13:35:45.783  6731  6786 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:35:45.783  6731  6786 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,09-09 13:35:45.783  6731  6877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1345)
09-09 13:35:45.783  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:45.783  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:45.783  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:45.783  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-09 13:35:45.783  6731  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ac9a0f9 not in the list
09-09 13:35:45.783  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:35:45.783  6731  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@107b983e not in the list
09-09 13:35:45.783  6731  6786 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:45.783  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:45.783  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:45.783  6731  6786 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-09 13:35:45.783  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:45.783  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:45.783  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:45.783  6731  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ac9a0f9 not in the list
09-09 13:35:45.783  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:45.783  6731  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@107b983e not in the list
,09-09 13:35:45.783  6731  6786 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:45.783  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:45.783  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:45.793  6731  6786 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-09 13:35:45.793  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:35:45.793  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:45.793  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:45.793  6731  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ac9a0f9 not in the list
09-09 13:35:45.793  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:45.793  6731  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@107b983e not in the list
09-09 13:35:45.793  6731  6786 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:45.793  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:45.793  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:45.793  6731  6786 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,09-09 13:35:45.793  6731  6786 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-09 13:35:45.793  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 13:35:45.793  6731  6786 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-09 13:35:45.793  6731  6786 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 13:35:45.793  6731  6786 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-09 13:35:45.793  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 13:35:45.793  6731  6786 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,09-09 13:35:45.793  6731  6786 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 13:35:45.793  6731  6786 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 13:35:45.793  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 13:35:45.793  6731  6786 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-09 13:35:45.793  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:45.793  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:45.793  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:45.793  6731  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ac9a0f9 not in the list
,09-09 13:35:45.793  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:45.793  6731  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@107b983e not in the list
09-09 13:35:45.793  6731  6786 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:45.793  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:45.793  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:45.793  6731  6786 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-09 13:35:45.793  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:35:45.793  6731  6878 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1345
,09-09 13:35:45.803  6731  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:45.803  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:45.803  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:45.803  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:45.803  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:45.803  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:45.803  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:45.803  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:35:45.803  6731  6877 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
,09-09 13:35:45.803  6731  6877 D BluetoothSocket: connect(): myUserId = 0
09-09 13:35:45.803  6731  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:45.803  6731  6786 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:35:45.803  6731  6786 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
09-09 13:35:45.803  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
09-09 13:35:45.803  6731  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:35:45.803  6731  6786 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-09 13:35:45.803  6731  6786 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:35:45.803  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:35:45.803  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 13:35:45.803  6731  6786 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 13:35:45.803  6731  6786 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 13:35:45.803  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:45.803  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:35:45.803  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-09 13:35:45.803  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:35:45.803  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 13:35:45.813  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:45.813  6731  6731 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 13:35:45.813  6731  6877 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:35:45.813  6731  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 13:35:45.813  6731  6879 D BluetoothSocket: bindListen(): myUserId = 0
,09-09 13:35:45.813  6731  6879 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:35:45.813  3179  3190 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 13:35:45.813  6731  6877 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
,09-09 13:35:45.813  6731  6879 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[107]}
,09-09 13:35:45.813  6731  6879 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 13:35:45.813  6731  6879 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 13:35:45.813  6731  6879 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@36ee1a20
,09-09 13:35:45.813  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 13:35:45.823  6731  6879 D BluetoothSocket: channel: 6
09-09 13:35:45.823  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:35:45.823  6731  6879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-09 13:35:45.823  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-09 13:35:45.823  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-09 13:35:45.823  6731  6786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 08 EC A9 50 76 27
,09-09 13:35:45.823  6731  6786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 8, -20, -87, 80, 118, 39]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:35:45.823  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 8, -20, -87, 80, 118, 39]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:35:45.823  6731  6786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-09 13:35:45.823  3179  3190 D BtGatt.GattService: registerClient() - UUID=a1f61a93-5bb5-4035-8dbc-9fcce4652bf5
,09-09 13:35:45.863  3179  3275 D BtGatt.GattService: onClientRegistered() - UUID=a1f61a93-5bb5-4035-8dbc-9fcce4652bf5, clientIf=6
,09-09 13:35:45.863  6731  6739 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-09 13:35:45.873  3179  3278 D BtGatt.AdvertiseManager: message : 0
,09-09 13:35:45.873  3179  3278 D BtGatt.AdvertiseManager: number of adv instance running0
,09-09 13:35:45.873  3179  3278 D BtGatt.AdvertiseManager: size of list is =0
,09-09 13:35:45.873   290   290 E SMD     : DCD OFF
,09-09 13:35:45.873  3179  3278 D BtGatt.AdvertiseManager: starting advertising
,09-09 13:35:45.873  3179  3278 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-09 13:35:45.873  3179  3275 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-09 13:35:45.883  3179  3278 D BtGatt.AdvertiseManager: starting multi advertising
,09-09 13:35:45.883  3179  3275 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-09 13:35:45.883  3179  3278 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-09 13:35:45.883  3179  3278 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-09 13:35:45.883  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-09 13:35:45.883  6731  6786 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 13:35:45.883  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:35:45.883  6731  6731 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 13:35:45.883  6731  6731 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-09 13:35:45.893  6731  6786 I io.jxcore.node.ConnectionHelper: start: OK
09-09 13:35:45.893  6731  6731 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-09 13:35:45.893  6731  6731 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-09 13:35:45.893  6731  6731 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-09 13:35:45.893  6731  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-09 13:35:45.893  6731  6731 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:35:45.893  6731  6731 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:35:45.893  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:45.893  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 13:35:45.893  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-09 13:35:45.893  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 13:35:45.893  6731  6786 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1f7c0d9e, channel: 6, state: LISTENING
,09-09 13:35:45.893  6731  6786 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1f7c0d9e, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@36ee1a20, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1a2c207fmSocket: android.net.LocalSocket@37eab84c impl:android.net.LocalSocketImpl@29dfd095 fd:FileDescriptor[107]
,09-09 13:35:45.893  6731  6786 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@37eab84c impl:android.net.LocalSocketImpl@29dfd095 fd:FileDescriptor[107]
,09-09 13:35:45.893  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 13:35:45.893  6731  6786 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:35:45.893  6731  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ac9a0f9 not in the list
,09-09 13:35:45.893  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:45.893  6731  6731 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-09 13:35:45.893  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
09-09 13:35:45.893  6731  6786 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:35:45.893  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
09-09 13:35:45.893  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 13:35:45.893  6731  6879 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1f7c0d9e, channel: 6, state: CLOSED,
09-09 13:35:45.893  6731  6879 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 13:35:45.893  6731  6879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-09 13:35:45.893  6731  6879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 13:35:45.893  6731  6786 D BluetoothLeScanner: could not find callback wrapper
,09-09 13:35:45.893  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
09-09 13:35:45.893  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-09 13:35:45.893  3179  3278 D BtGatt.AdvertiseManager: message : 1
09-09 13:35:45.903  3179  3278 D BtGatt.AdvertiseManager: stop advertise for client 6
,09-09 13:35:45.903  3179  3278 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6
09-09 13:35:45.903  3179  3278 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-09 13:35:45.903  3179  3275 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
09-09 13:35:45.903  3179  3275 D BtGatt.GattService: Client app is not null!
,09-09 13:35:45.903  3179  3280 D BtGatt.GattService: unregisterClient() - clientIf=6
09-09 13:35:45.913  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 13:35:45.913  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-09 13:35:45.913  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-09 13:35:45.913  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-09 13:35:45.913  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-09 13:35:45.913  6731  6786 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:35:45.913  6731  6786 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-09 13:35:45.913  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 13:35:45.913  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:35:45.913  6731  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:35:45.913  6731  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:35:45.913  6731  6731 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 13:35:45.913  6731  6731 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:35:45.913  6731  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@107b983e not in the list
09-09 13:35:45.913  6731  6786 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:45.913  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:45.923  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:45.923  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:45.923  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:45.923  6731  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ac9a0f9 not in the list
09-09 13:35:45.923  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:45.923  6731  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@107b983e not in the list
09-09 13:35:45.923  6731  6786 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:45.923  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:45.923  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:45.923  6731  6786 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-09 13:35:45.923  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:35:45.923  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-09 13:35:45.923  6731  6786 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 13:35:45.923  6731  6786 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 13:35:45.923  6731  6731 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 13:35:45.923  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:35:45.923  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 13:35:45.923  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:45.923  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 13:35:45.923  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 13:35:45.923  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 13:35:45.923  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:45.923  6731  6786 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:35:45.923  6731  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ac9a0f9 not in the list
09-09 13:35:45.923  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:35:45.923  6731  6731 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 13:35:45.923  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:35:45.923  6731  6786 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:35:45.923  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:35:45.923  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:45.923  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:45.923  6731  6883 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 13:35:45.923  6731  6883 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-09 13:35:45.923  6731  6786 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:35:45.923  6731  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@107b983e not in the list
09-09 13:35:45.923  6731  6786 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:45.923  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:45.923  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:45.923  6731  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:35:45.923  6731  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:35:45.923  6731  6731 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 13:35:45.923  6731  6731 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:35:45.923  6731  6786 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-09 13:35:45.923  6731  6786 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 13:35:45.923  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 13:35:45.923  6731  6786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:35:45.923  6731  6786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-09 13:35:45.923  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:45.923  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:45.923  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:45.923  6731  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ac9a0f9 not in the list
09-09 13:35:45.923  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:45.923  6731  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@107b983e not in the list
09-09 13:35:45.923  6731  6786 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:45.923  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:45.923  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:45.933  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:45.933  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:45.933  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:45.933  6731  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ac9a0f9 not in the list
09-09 13:35:45.933  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:45.933  6731  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@107b983e not in the list
09-09 13:35:45.933  6731  6786 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:45.933  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:45.933  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:45.933  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:45.933  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:45.933  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:45.933  6731  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ac9a0f9 not in the list
09-09 13:35:45.943  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:45.943  6731  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@107b983e not in the list
09-09 13:35:45.943  6731  6786 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:45.943  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:45.943  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:45.943  6731  6786 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-09 13:35:45.943  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 13:35:45.943  6731  6786 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-09 13:35:45.943  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 13:35:45.943  6731  6786 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-09 13:35:45.943  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 13:35:45.943  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 13:35:45.943  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-09 13:35:45.943  6731  6786 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-09 13:35:45.943  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 13:35:45.943  6731  6786 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-09 13:35:45.943  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 13:35:45.943  6731  6786 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-09 13:35:45.943  6731  6786 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-09 13:35:45.943  6731  6786 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-09 13:35:45.943  6731  6786 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-09 13:35:45.943  6731  6786 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-09 13:35:45.943  6731  6786 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-09 13:35:45.943  6731  6786 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-09 13:35:45.943  6731  6786 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-09 13:35:45.943  6731  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:35:45.943  6731  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c6c459b added. We now have 3 listener(s)
09-09 13:35:45.953  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-09 13:35:45.953  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:35:45.953  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:35:45.953  6731  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:35:45.953  6731  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38310d38 added. We now have 3 listener(s)
09-09 13:35:45.953  6731  6786 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:35:45.953  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:35:45.953  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:35:45.953  6731  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:45.953  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:45.953  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:45.953  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:45.953  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:45.953  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:45.953  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:45.953  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:35:45.963  6731  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:45.963  6731  6786 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:35:45.963  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:45.963  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:45.963  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:45.963  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:45.963  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:35:45.963  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:35:45.963  6731  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c6c459b removed from the list
09-09 13:35:45.963  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:45.963  6731  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38310d38 removed from the list
09-09 13:35:45.963  6731  6786 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:45.963  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:45.973  6731  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:35:45.973  6731  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f5e3276 added. We now have 3 listener(s)
09-09 13:35:45.973  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-09 13:35:45.973  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:35:45.973  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:35:45.973  6731  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:35:45.973  6731  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bbfa077 added. We now have 3 listener(s)
09-09 13:35:45.973  6731  6786 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:35:45.973  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:35:45.973  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:35:45.983  6731  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:45.983  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:45.983  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:45.983  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:45.983  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:45.983  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:45.983  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:45.983  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:35:45.983  6731  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:45.983  6731  6786 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:35:45.983  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:45.983  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:45.983  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:35:45.983  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:35:45.983  6731  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f5e3276 removed from the list
09-09 13:35:45.983  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:45.983  6731  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bbfa077 removed from the list
09-09 13:35:45.983  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:45.983  6731  6786 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:45.983  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:45.983  6731  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:35:45.983  6731  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@354a7d4d added. We now have 3 listener(s)
09-09 13:35:45.983  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:45.983  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-09 13:35:45.983  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:35:45.983  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:35:45.983  6731  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:35:45.983  6731  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19730002 added. We now have 3 listener(s)
09-09 13:35:45.983  6731  6786 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:35:45.993  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:35:45.993  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:35:45.993  6731  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:45.993  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:45.993  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:45.993  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:45.993  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:45.993  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:45.993  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:45.993  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:35:45.993  6731  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:45.993  6731  6786 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:35:46.003  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-09 13:35:46.003  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:46.003  1015  1132 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-09 13:35:46.003  1015  1132 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-09 13:35:46.003  1015  1132 D SecContentProvider2: mCursor = null
,09-09 13:35:46.013  1015  1132 D WifiService: setWifiEnabled: false pid=6731, uid=10171
,09-09 13:35:46.013  1015  1132 D SettingsProvider: name = wifi_on
,09-09 13:35:46.013  1015  1124 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-09 13:35:46.023  1375  1375 I wpa_supplicant: reset timer : RESET_TIMER 0
09-09 13:35:46.023  1375  1375 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-09 13:35:46.023  1375  1375 I wpa_supplicant: P2P: Current p2p state = IDLE
,09-09 13:35:46.023  1375  1375 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds,
,09-09 13:35:46.023  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,09-09 13:35:46.053  1015  1124 E WifiNative-wlan0: do suspend true,
,09-09 13:35:46.203  1015  1123 D WifiP2pService: InactiveState{ what=143375 },
09-09 13:35:46.203  1015  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-09 13:35:46.203  1375  1375 I wpa_supplicant: nl80211: Received scan results (21 BSSes),
,09-09 13:35:46.203  1015  1123 D WifiP2pService: InactiveState{ what=147461 },
09-09 13:35:46.203  1015  1123 D WifiP2pService: P2pEnabledState{ what=147461 }
,09-09 13:35:46.203  1015  1123 D WifiP2pService: DefaultState{ what=147461 }
,09-09 13:35:46.213  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-09 13:35:46.213  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,09-09 13:35:46.213  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:46.213  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:35:46.213  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:35:46.213  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:46.223   280  1013 D CommandListener: Clearing all IP addresses on wlan0
09-09 13:35:46.223  1963  3019 V NativeCrypto: Read error: ssl=0xb8594768: I/O error during system call, Connection timed out
,09-09 13:35:46.233  1015  1126 E ConnectivityService: updateNetworkInfo()
,09-09 13:35:46.233  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:35:46.233  1015  1126 E ConnectivityService: updateNetworkInfo()
09-09 13:35:46.233  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,09-09 13:35:46.233  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-09 13:35:46.233  1963  3019 V NativeCrypto: SSL shutdown failed: ssl=0xb8594768: I/O error during system call, Broken pipe
,09-09 13:35:46.243  1963  3019 E GCM     : Wifi connection closed with errorCode 20
,09-09 13:35:46.243  1015  1376 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,09-09 13:35:46.253  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:35:46.253  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:35:46.253  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:35:46.253  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:46.253  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:35:46.253  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:35:46.263  1015  1123 D WifiP2pService: InactiveState{ what=131204 }
09-09 13:35:46.263  1015  1123 D WifiP2pService: P2pEnabledState{ what=131204 }
09-09 13:35:46.263  1015  1744 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-16ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:46.263  1015  1123 D WifiP2pService: sending p2p connection changed broadcast: FAILED
09-09 13:35:46.263  1015  1744 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-16ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:46.263  1015  1744 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
,09-09 13:35:46.263  1015  1744 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:46.263  1015  1744 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,09-09 13:35:46.273  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1
09-09 13:35:46.273  1015  1147 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 13:35:46.273  1015  1744 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-09 13:35:46.273  1015  1744 I qtaguid : Tagging socket 337 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1015, getuid(): 1000
09-09 13:35:46.273  1015  1015 D RttService: SCAN_AVAILABLE : 1
09-09 13:35:46.273  1015  1148 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 13:35:46.273  1015  1027 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 13:35:46.273  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-09 13:35:46.273  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:46.273  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:46.273  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-09 13:35:46.273  1636  1636 I Hs20UtilService: Starting #8
,09-09 13:35:46.273  1636  1705 I Hs20UtilService: Message received 5007
,09-09 13:35:46.283  1015  1744 I qtaguid : Untagging socket 337
,09-09 13:35:46.283  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:35:46.283  1015  1744 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:35:46.283  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
09-09 13:35:46.283  1015  1376 D ActivityManager: startProcessLocked calleePkgName: com.android.settings, hostingType: broadcast
,09-09 13:35:46.283  1015  1376 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:46.283  1015  1376 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:46.283  1015  1376 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:46.283  1015  1376 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:46.303  1015  1376 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.nearby.MountReceiver: pid=6889 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-09 13:35:46.303  1015  1124 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-09 13:35:46.303  1015  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-09 13:35:46.303  1015  1123 D WifiP2pService: P2pDisablingState
09-09 13:35:46.313  1015  1123 D WifiP2pService: P2pDisablingState{ what=147458 }
09-09 13:35:46.313  1015  1123 D WifiP2pService: p2p socket connection lost
,09-09 13:35:46.313  1015  1123 D WifiP2pService: P2pDisabledState
,09-09 13:35:46.313  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-09 13:35:46.313  6889  6889 E Zygote  : MountEmulatedStorage()
09-09 13:35:46.313  6889  6889 E Zygote  : v2
09-09 13:35:46.313  6889  6889 I libpersona: KNOX_SDCARD checking this for 1000
09-09 13:35:46.313  6889  6889 I libpersona: KNOX_SDCARD not a persona
,09-09 13:35:46.313  1015  1124 E WifiNative-wlan0: do suspend true
09-09 13:35:46.313  6889  6889 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 13:35:46.313  6889  6889 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 13:35:46.323  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 13:35:46.323  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
09-09 13:35:46.323  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-09 13:35:46.323  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 13:35:46.323  1015  1045 D WifiDisplayController: disconnect
09-09 13:35:46.323  1015  1045 D WifiDisplayController: updateConnection
09-09 13:35:46.323  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 13:35:46.323  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-09 13:35:46.323  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
09-09 13:35:46.323  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 13:35:46.323  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
09-09 13:35:46.323  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-09 13:35:46.323  6889  6889 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:35:46.323  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-09 13:35:46.333  1015  3173 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-09 13:35:46.333  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-09 13:35:46.353  6889  6889 D TimaKeyStoreProvider: TimaSignature is unavailable,
09-09 13:35:46.353  6889  6889 D ActivityThread: Added TimaKeyStore provider
,09-09 13:35:46.373  6889  6889 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,09-09 13:35:46.373  6889  6889 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-09 13:35:46.373  6889  6889 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-09 13:35:46.373  6889  6889 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:35:46.373  6889  6889 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 13:35:46.373  6889  6889 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-09 13:35:46.373  1015  1123 D WifiP2pService: P2pDisabledState{ what=143375 }
,09-09 13:35:46.373  1015  1123 D WifiP2pService: DefaultState{ what=143375 }
,09-09 13:35:46.383  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:35:46.383  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:35:46.383  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:46.383  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:46.383  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:46.383  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:46.383   280  1009 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-09 13:35:46.383   280  1009 D Netd    : getNetworkForDns: using netid 0 for uid 1000
09-09 13:35:46.383  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:46.383  1015  1126 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-09 13:35:46.383  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:35:46.383  1015  1126 V NetworkStats: updateIfacesLocked()
09-09 13:35:46.383  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-09 13:35:46.383  1015  1126 V NetworkStats: performPollLocked(flags=0x1)
09-09 13:35:46.383   280  1013 D CommandListener: Clearing all IP addresses on wlan0
,09-09 13:35:46.393  1375  1375 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
09-09 13:35:46.393  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:46.393  1015  1126 V NetworkStats: performPollLocked() took 8ms
,09-09 13:35:46.393  1015  1744 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
09-09 13:35:46.393  1015  1744 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,09-09 13:35:46.393  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-09 13:35:46.393  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-09 13:35:46.393  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:35:46.393  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:46.393  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:46.393  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:46.393  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:35:46.403  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:46.403  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:46.403  6889  6889 D MySettingsProvider: DatabaseHelper(Context context):DATABASE_VERSION=1,
09-09 13:35:46.403  1015  1126 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,09-09 13:35:46.403  1177  1602 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,09-09 13:35:46.403  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:35:46.403  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-09 13:35:46.403  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:46.403  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:46.403  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:46.403  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:35:46.403  6889  6889 E SQLiteLog: (283) recovered 10 frames from WAL file /data/data/com.android.settings/databases/mysettings.db-wal,
09-09 13:35:46.403  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:35:46.413  1177  1607 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-09 13:35:46.403  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
09-09 13:35:46.413  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:35:46.413  1015  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-09 13:35:46.413  1177  1177 D HotspotTile: onReceive : 0, 0,
09-09 13:35:46.413  4748  6795 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-09 13:35:46.413  1015  1744 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler },
09-09 13:35:46.413  6889  6889 D MySettingsProvider: onCreate():(mDB == null)? false:true  =true
09-09 13:35:46.413  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:35:46.413  1015  1124 D SecContentProvider2: mCursor = null
,09-09 13:35:46.413  1015  1126 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ],
09-09 13:35:46.413  1015  1123 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-09 13:35:46.413  1015  1126 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} },
,09-09 13:35:46.413  1454  1454 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-09 13:35:46.413  1015  1126 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
09-09 13:35:46.413  1454  1454 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:35:46.423  1015  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 13:35:46.423  1015  1124 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-09 13:35:46.423  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:46.423  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:46.423  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:46.423  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:35:46.423  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:46.423  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:35:46.423  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:35:46.423  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:35:46.423  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-09 13:35:46.423  1015  1127 D Tethering: MasterInitialState.processMessage what=3
,09-09 13:35:46.433  1015  1121 V NetworkStats: updateIfacesLocked()
09-09 13:35:46.433  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:46.433  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
,09-09 13:35:46.433  6731  6731 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:35:46.433  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:35:46.433  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 13:35:46.433  1015  1121 V NetworkStats: performPollLocked() took 6ms
09-09 13:35:46.433  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:46.433  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
09-09 13:35:46.433  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-09 13:35:46.433  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-09 13:35:46.433  1177  1177 D StatusBar.NetworkController: updateDataNetType()
09-09 13:35:46.433  1177  1177 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-09 13:35:46.433  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-09 13:35:46.433  1015  1126 D ConnectivityService: nai.networkMonitor.doQuit()
09-09 13:35:46.433  1015  1126 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-09 13:35:46.433  1015  1126 E ConnectivityService: updateNetworkInfo()
09-09 13:35:46.433  1015  1126 E ConnectivityService: updateNetworkInfo()
09-09 13:35:46.433  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-09 13:35:46.443  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:46.443  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:46.443  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:46.443  1015  1122 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-09 13:35:46.443  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:46.443  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:46.443  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:46.443  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:46.443  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:46.443  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:46.443  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:35:46.443  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:46.443  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:35:46.443  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:35:46.443  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:35:46.443  1015  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-09 13:35:46.443  6731  6731 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:35:46.443  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-09 13:35:46.443  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-09 13:35:46.443  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-09 13:35:46.443  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:35:46.443  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-09 13:35:46.443  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:46.443  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:46.443  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:35:46.443  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:35:46.453  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:46.453  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:46.453  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:46.453  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:35:46.453  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:46.453  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:35:46.453  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:35:46.453  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:35:46.453  6889  6889 D NearbySettings: MountReceiver.onReceive - Create HandlerThread
09-09 13:35:46.453  6889  6889 D NearbySettings: MountReceiver.onReceive - Start HandlerThread
09-09 13:35:46.453  6889  6889 D NearbySettings: MountReceiver.onReceive - Create mPrefHandler
,09-09 13:35:46.453  6731  6731 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:35:46.453  6731  6731 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 13:35:46.453  6889  6889 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-09 13:35:46.463  6889  6889 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 13:35:46.463  6889  6889 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 13:35:46.473  6889  6889 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-09 13:35:46.473  6889  6889 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 13:35:46.473  6889  6889 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 13:35:46.473  6889  6908 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 13:35:46.473  1015  1477 I ActivityManager: Killing 6337:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,09-09 13:35:46.493  1015  1477 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:46.493  1015  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:46.493  1015  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
09-09 13:35:46.493  1015  1477 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,09-09 13:35:46.493  1015  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:46.493  1015  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:46.493  1015  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:46.493  1015  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:46.503  6911  6911 E Zygote  : MountEmulatedStorage()
09-09 13:35:46.503  6911  6911 E Zygote  : v2
09-09 13:35:46.503  6911  6911 I libpersona: KNOX_SDCARD checking this for 10102
,09-09 13:35:46.503  6911  6911 I libpersona: KNOX_SDCARD not a persona
,09-09 13:35:46.503  6911  6911 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:35:46.503  1015  1477 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6911 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-09 13:35:46.513  6911  6911 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 13:35:46.513  6911  6911 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-09 13:35:46.523  1015  1533 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-09 13:35:46.523  1015  1533 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-09 13:35:46.523  1015  1533 D SecContentProvider2: mCursor = null
,09-09 13:35:46.523  1015  1533 D WifiService: setWifiEnabled: true pid=6731, uid=10171
09-09 13:35:46.523  1015  1533 W ActivityManager: Permission Denial: getCurrentUser() from pid=6731, uid=10171 requires android.permission.INTERACT_ACROSS_USERS,
09-09 13:35:46.533  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-09 13:35:46.533  1375  1375 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 13:35:46.533  1015  1533 W WifiService: Failed getting userId using ActivityManagerNative
09-09 13:35:46.533  1015  1533 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6731, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-09 13:35:46.533  1015  1533 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-09 13:35:46.533  1015  1533 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-09 13:35:46.533  1015  1533 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-09 13:35:46.533  1015  1533 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-09 13:35:46.533  1015  1533 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-09 13:35:46.533  1015  1533 D SettingsProvider: name = wifi_on
,09-09 13:35:46.533  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:35:46.533  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:35:46.543  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-09 13:35:46.543  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:35:46.543  6911  6911 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:35:46.543  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-09 13:35:46.543  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-09 13:35:46.543  6911  6911 D ActivityThread: Added TimaKeyStore provider
,09-09 13:35:46.543  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:35:46.553  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
,09-09 13:35:46.553  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:35:46.553  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:35:46.553  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-09 13:35:46.553  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:35:46.553  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-09 13:35:46.553  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-09 13:35:46.563  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:35:46.563  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:35:46.563  6911  6911 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-09 13:35:46.563  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:35:46.563  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:35:46.563  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:35:46.563  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:35:46.573  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-09 13:35:46.573  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:35:46.573  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:35:46.573  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:35:46.573  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-09 13:35:46.573  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-09 13:35:46.573  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-09 13:35:46.573  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:35:46.573  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:35:46.603  1375  1375 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-09 13:35:46.603  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-09 13:35:46.603  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 13:35:46.603  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-09 13:35:46.683  1375  1375 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,09-09 13:35:46.683  1375  1375 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-09 13:35:46.683  1375  1375 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-09 13:35:46.683  1375  1375 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-09 13:35:46.683  1375  1375 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-09 13:35:46.683  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:35:46.683  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:35:46.683  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-09 13:35:46.683  1015  1127 D Tethering: InitialState.processMessage what=4
,09-09 13:35:46.683  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-09 13:35:46.683  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
,09-09 13:35:46.693  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-09 13:35:46.693  1015  1127 E Tethering: No numeric data
,09-09 13:35:46.693  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-09 13:35:46.693  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
,09-09 13:35:46.693  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-09 13:35:46.693  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
09-09 13:35:46.693  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:46.693  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 13:35:46.693  1177  1177 D HotspotTile: updateTetherState():false, false
,09-09 13:35:46.703  1015  1127 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 13:35:46.703  1015  1127 D Tethering: clearTetheredNotification()
09-09 13:35:46.703  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-09 13:35:46.703  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 13:35:46.703  1015  1121 V NetworkStats: performPollLocked() took 6ms
,09-09 13:35:46.703  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:46.703  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:46.703  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:46.743   272   272 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7c197c8
09-09 13:35:46.743   272   272 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
,09-09 13:35:46.743   272   272 I rmt_storage: wakelock acquired: 1, error no: 42,
09-09 13:35:46.743   272   308 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1212050120)
,09-09 13:35:46.803   272   308 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
09-09 13:35:46.803   272   308 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
09-09 13:35:46.803   272   308 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1212050120) wakelock released: 1, error no: 0
09-09 13:35:46.803   272   308 I rmt_storage: 
,09-09 13:35:46.803   272   272 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb7c197c8
,09-09 13:35:46.833  6911  6949 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
09-09 13:35:46.833  6911  6949 I Babel_SMS: MmsConfig.loadMmsSettings
09-09 13:35:46.833  6911  6949 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
09-09 13:35:46.833  6911  6949 I Babel_SMS: MmsConfig.loadFromDatabase
,09-09 13:35:46.853  6911  6949 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
09-09 13:35:46.853  6911  6949 I Babel_SMS: MmsConfig.loadFromResources
,09-09 13:35:46.853  6911  6949 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
09-09 13:35:46.853  6911  6949 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,09-09 13:35:46.863  1015  1028 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
09-09 13:35:46.863  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,09-09 13:35:46.863  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:46.863  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:46.863  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-09 13:35:46.883  6911  6911 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:35:46.883  6911  6911 I Babel_Crash: startup - clean,
,09-09 13:35:46.913  1375  1375 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 13:35:46.913  6889  6889 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-09 13:35:46.913  6889  6889 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 13:35:46.913  6889  6889 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 13:35:46.913  6889  6889 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-09 13:35:46.913  6889  6889 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 13:35:46.913  6889  6889 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 13:35:46.923  6889  6908 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 13:35:46.923  1015  3173 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,09-09 13:35:46.923  1015  3173 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:46.923  1015  3173 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:46.923  1015  3173 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:46.923  1015  3173 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:46.923  1015  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:35:46.923  6911  6911 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 13:35:46.933  6911  6911 W AudioCapabilities: Unsupported mime audio/evrc
,09-09 13:35:46.933  6911  6911 W AudioCapabilities: Unsupported mime audio/qcelp,
,09-09 13:35:46.933  6911  6911 W AudioCapabilities: Unsupported mime audio/mpeg-L1,
09-09 13:35:46.933  6911  6911 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,09-09 13:35:46.933  6911  6911 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,09-09 13:35:46.943  6952  6952 E Zygote  : MountEmulatedStorage()
09-09 13:35:46.943  6952  6952 E Zygote  : v2
09-09 13:35:46.943  6952  6952 I libpersona: KNOX_SDCARD checking this for 10064
09-09 13:35:46.943  6952  6952 I libpersona: KNOX_SDCARD not a persona
,09-09 13:35:46.943  6952  6952 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:35:46.943  6952  6952 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 13:35:46.943  6952  6952 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:35:46.953  1015  3173 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6952 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 13:35:46.953  6911  6911 W AudioCapabilities: Unsupported mime audio/x-ima,
,09-09 13:35:46.953  6911  6911 W AudioCapabilities: Unsupported mime audio/qcelp
,09-09 13:35:46.953  6911  6911 W AudioCapabilities: Unsupported mime audio/evrc
,09-09 13:35:46.953  1015  1015 I ApplicationPolicy: updateDataUsageMap
,09-09 13:35:46.963  1375  1375 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
09-09 13:35:46.963  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:35:46.963  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:35:46.963  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
09-09 13:35:46.983  1015  1039 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE,
,09-09 13:35:46.983  6911  6911 W VideoCapabilities: Unsupported mime video/wvc1
,09-09 13:35:46.983  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:46.983  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:46.983  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:46.983  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:35:46.983  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:46.983  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:35:46.983  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:35:46.983  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:35:46.983  6911  6911 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-09 13:35:46.993  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
09-09 13:35:46.993  1015  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-09 13:35:47.003  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:47.003  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:47.003  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:47.003  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:35:47.003  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:47.003  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:35:47.003  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:35:47.003  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:35:47.003  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:47.003  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:35:47.003  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-09 13:35:47.003  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:47.003  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:47.003  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:47.003  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:35:47.003  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:35:47.003  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
09-09 13:35:47.003  1177  1607 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-09 13:35:47.003  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:35:47.003  1963  2161 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:35:47.013  1177  1177 D HotspotTile: onReceive : 1, 0
,09-09 13:35:47.013  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:47.013  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:47.013  6952  6952 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:35:47.013  6952  6952 D ActivityThread: Added TimaKeyStore provider
09-09 13:35:47.013  6911  6911 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
09-09 13:35:47.013  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:47.013  6911  6911 W VideoCapabilities: Unsupported mime video/wvc1
,09-09 13:35:47.023  6911  6911 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-09 13:35:47.023  6911  6911 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
09-09 13:35:47.023  6911  6911 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
09-09 13:35:47.023  6911  6911 W VideoCapabilities: Unsupported mime video/mp43
09-09 13:35:47.023  6952  6952 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-09 13:35:47.033  6911  6911 W VideoCapabilities: Unsupported mime video/sorenson
,09-09 13:35:47.033  6911  6911 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-09 13:35:47.043  6952  6952 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 13:35:47.053  6911  6911 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-09 13:35:47.053  6952  6952 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-09 13:35:47.073  6911  6911 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 13:35:47.073  6911  6911 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-09 13:35:47.073  6911  6911 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 13:35:47.083  6911  6911 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 13:35:47.083  1015  1533 I ActivityManager: Killing 6463:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,09-09 13:35:47.083  6911  6911 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:35:47.083  6952  6952 D FileShare-Client: Outbound.stopDelayTimer - 
,09-09 13:35:47.083  1015  1569 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,09-09 13:35:47.093  1015  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:47.093  1015  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:47.093  1015  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:47.093  1015  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:47.093  6911  6911 I vclib   : onServiceConnected,
,09-09 13:35:47.103  6968  6968 E Zygote  : MountEmulatedStorage(),
09-09 13:35:47.103  6968  6968 E Zygote  : v2
09-09 13:35:47.103  6968  6968 I libpersona: KNOX_SDCARD checking this for 10065
09-09 13:35:47.103  6968  6968 I libpersona: KNOX_SDCARD not a persona
,09-09 13:35:47.103  1015  1569 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6968 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:35:47.103  6968  6968 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 13:35:47.103  1015  1569 I ActivityManager: Killing 6510:com.samsung.android.sm/1000 (adj 15): empty #21
,09-09 13:35:47.113  6968  6968 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 13:35:47.113  6968  6968 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:35:47.133  6968  6968 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:35:47.133  6968  6968 D ActivityThread: Added TimaKeyStore provider
,09-09 13:35:47.153  6968  6968 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 13:35:47.163  1015  1539 I ActivityManager: Killing 6494:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,09-09 13:35:47.163  1015  1533 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 13:35:47.163  1015  1533 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:35:47.163  1015  1533 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:47.163  1015  1533 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:47.163  1015  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:35:47.173  1636  1636 I Hs20UtilService: Starting #9
,09-09 13:35:47.173  6889  6889 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-09 13:35:47.173  6889  6889 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 13:35:47.173  6889  6889 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-09 13:35:47.173  1636  1705 I Hs20UtilService: Message received 5007
,09-09 13:35:47.173  6889  6889 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-09 13:35:47.173  6889  6889 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 13:35:47.173  6889  6889 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 13:35:47.173  6889  6908 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 13:35:47.183  1015  1569 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 13:35:47.183  1015  1569 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:35:47.183  1015  1569 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:47.183  1015  1569 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 13:35:47.183  1015  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:35:47.183  1636  1636 I Hs20UtilService: Starting #10
,09-09 13:35:47.193  1636  1705 I Hs20UtilService: Message received 5011
09-09 13:35:47.193  6542  6542 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-09 13:35:47.193  6542  6542 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 13:35:47.193  6542  6542 D SecurityLogAgent: StateMachine : Current State = 1
,09-09 13:35:47.193  6542  6542 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 13:35:47.193  1015  1571 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:47.203  1015  1571 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:47.203  1015  1571 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:47.413  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:47.413  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:47.413  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:47.423  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:47.423  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:47.423  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:47.423  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:47.423  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:47.423  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:47.423  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:47.423  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:47.423  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:47.423  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:47.423  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:47.423  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:47.433  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:47.433  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:47.433  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:47.433  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:47.433  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:47.433  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:47.433  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:47.433  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:47.433  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:47.433  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:47.433  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:47.433  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:47.443  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:47.443  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:47.443  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:47.443  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:47.443  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:47.443  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:47.443  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:47.443  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:47.443  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:47.443  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:47.443  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:47.443  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:47.453  1015  1015 W ActivityManager: userId = 0, bbcId = -10000,
09-09 13:35:47.453  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:47.453  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:47.453  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast,
,09-09 13:35:47.453  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:47.453  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:47.453  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:47.453  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:47.463  6983  6983 E Zygote  : MountEmulatedStorage(),
09-09 13:35:47.463  1015  1015 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6983 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-09 13:35:47.463  6983  6983 E Zygote  : v2
09-09 13:35:47.463  6983  6983 I libpersona: KNOX_SDCARD checking this for 1000
,09-09 13:35:47.463  6983  6983 I libpersona: KNOX_SDCARD not a persona
09-09 13:35:47.473  6983  6983 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:35:47.473  6983  6983 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 13:35:47.473  6983  6983 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:35:47.493  6983  6983 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:35:47.493  6983  6983 D ActivityThread: Added TimaKeyStore provider
,09-09 13:35:47.503  1015  1042 D Tethering: interfaceRemoved wlan0
09-09 13:35:47.503  1015  1042 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-09 13:35:47.513  6983  6983 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,09-09 13:35:47.513  6983  6983 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-09 13:35:47.513  6983  6983 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-09 13:35:47.533  6983  6983 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-09 13:35:47.533  6983  6983 I PCWCLIENTTRACE_PushUtil: sales region : global
09-09 13:35:47.533  6983  6983 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-09 13:35:47.533  6983  6983 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:35:47.533  1015  1486 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
,09-09 13:35:47.533  1015  1486 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,09-09 13:35:47.533  6983  6998 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,09-09 13:35:47.543  1015  1486 I ActivityManager: Killing 6562:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,09-09 13:35:47.553  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-09 13:35:47.553  1788  1788 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-09 13:35:47.553  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:47.553  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:47.553  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:47.553  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:47.563  7000  7000 E Zygote  : MountEmulatedStorage()
,09-09 13:35:47.563  7000  7000 E Zygote  : v2
09-09 13:35:47.563  7000  7000 I libpersona: KNOX_SDCARD checking this for 10121,
09-09 13:35:47.563  7000  7000 I libpersona: KNOX_SDCARD not a persona
,09-09 13:35:47.563  7000  7000 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-09 13:35:47.563  1015  1040 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7000 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,09-09 13:35:47.563  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-09 13:35:47.573  7000  7000 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 13:35:47.573  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:47.573  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:47.573  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:47.573  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-09 13:35:47.573  7000  7000 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:35:47.583  7000  7000 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:35:47.583  7013  7013 E Zygote  : MountEmulatedStorage(),
09-09 13:35:47.583  7013  7013 E Zygote  : v2
09-09 13:35:47.583  7013  7013 I libpersona: KNOX_SDCARD checking this for 10001
09-09 13:35:47.583  7013  7013 I libpersona: KNOX_SDCARD not a persona
,09-09 13:35:47.583  7013  7013 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:35:47.593  7000  7000 D ActivityThread: Added TimaKeyStore provider,
,09-09 13:35:47.593  7013  7013 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-09 13:35:47.593  1015  1015 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7013 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 13:35:47.593  1015  1486 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
09-09 13:35:47.593  7013  7013 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:35:47.593  1015  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:47.593  1015  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:47.593  1015  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:47.593  1015  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:47.613  7026  7026 E Zygote  : MountEmulatedStorage()
09-09 13:35:47.613  7026  7026 E Zygote  : v2
09-09 13:35:47.613  7026  7026 I libpersona: KNOX_SDCARD checking this for 10031
09-09 13:35:47.613  7026  7026 I libpersona: KNOX_SDCARD not a persona
,09-09 13:35:47.613  7026  7026 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-09 13:35:47.613  7026  7026 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 13:35:47.613  7026  7026 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:35:47.613  7013  7013 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:35:47.613  7013  7013 D ActivityThread: Added TimaKeyStore provider
09-09 13:35:47.613  1015  1486 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7026 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,09-09 13:35:47.633  2485  2499 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,09-09 13:35:47.633  1788  1788 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,09-09 13:35:47.633  1788  1788 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,09-09 13:35:47.633  1788  1788 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
09-09 13:35:47.633  1788  1788 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-09 13:35:47.643  7000  7000 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 13:35:47.643  1015  1042 D Tethering: interfaceRemoved p2p0
,09-09 13:35:47.643  1015  1042 E Tethering: attempting to remove unknown iface (p2p0), ignoring
09-09 13:35:47.643  7000  7000 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-09 13:35:47.643  7000  7000 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-09 13:35:47.643  7026  7026 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:35:47.643  1788  1788 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-09 13:35:47.643  7026  7026 D ActivityThread: Added TimaKeyStore provider
,09-09 13:35:47.643  1788  1788 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,09-09 13:35:47.653  1015  1571 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,09-09 13:35:47.653  1015  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:47.653  1015  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:47.653  1015  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:47.653  1015  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:47.653  7000  7000 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:35:47.673  7045  7045 E Zygote  : MountEmulatedStorage()
,09-09 13:35:47.673  7045  7045 E Zygote  : v2
09-09 13:35:47.673  7045  7045 I libpersona: KNOX_SDCARD checking this for 10077
09-09 13:35:47.673  7045  7045 I libpersona: KNOX_SDCARD not a persona
,09-09 13:35:47.673  7045  7045 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:35:47.673  7000  7000 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
09-09 13:35:47.673  1015  1571 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7045 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 13:35:47.683  7045  7045 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 13:35:47.683  1015  1533 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
09-09 13:35:47.683  7045  7045 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
09-09 13:35:47.683  1015  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:47.683  7000  7000 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
09-09 13:35:47.683  1015  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:47.683  7026  7026 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
09-09 13:35:47.683  1015  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:47.683  1015  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:47.703  7045  7045 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:35:47.703  7045  7045 D ActivityThread: Added TimaKeyStore provider
09-09 13:35:47.703   307   307 I art     : Explicit concurrent mark sweep GC freed 8693(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 622us total 24.287ms
,09-09 13:35:47.713   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 573us total 16.284ms,
,09-09 13:35:47.733   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 569us total 16.373ms,
,09-09 13:35:47.743  7062  7062 E Zygote  : MountEmulatedStorage(),
09-09 13:35:47.743  7062  7062 E Zygote  : v2
09-09 13:35:47.743  7062  7062 I libpersona: KNOX_SDCARD checking this for 10141
,09-09 13:35:47.743  7062  7062 I libpersona: KNOX_SDCARD not a persona
09-09 13:35:47.743  1015  1533 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7062 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,09-09 13:35:47.743  7062  7062 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:35:47.743  1015  1533 I ActivityManager: Killing 6578:com.osp.app.signin/u0a36 (adj 15): empty #21
,09-09 13:35:47.753  7062  7062 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 13:35:47.753  7062  7062 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 13:35:47.753  1015  1027 I ActivityManager: Killing 6595:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,09-09 13:35:47.773  7062  7062 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:35:47.773  1015  1539 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
09-09 13:35:47.773  7062  7062 D ActivityThread: Added TimaKeyStore provider
,09-09 13:35:47.773  1015  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:47.773  1015  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:47.773  1015  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:47.773  1015  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:47.783  2777  7077 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,09-09 13:35:47.783  2777  7077 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
09-09 13:35:47.783  2777  7077 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
09-09 13:35:47.783  2777  7077 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
09-09 13:35:47.783  2777  7077 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-09 13:35:47.793  7078  7078 E Zygote  : MountEmulatedStorage()
,09-09 13:35:47.793  7078  7078 E Zygote  : v2
09-09 13:35:47.793  7078  7078 I libpersona: KNOX_SDCARD checking this for 10032
09-09 13:35:47.793  7078  7078 I libpersona: KNOX_SDCARD not a persona
,09-09 13:35:47.793  7078  7078 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:35:47.803  7078  7078 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 13:35:47.803  1015  1539 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7078 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 13:35:47.803  7078  7078 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-09 13:35:47.803  1015  1539 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast,
,09-09 13:35:47.803  1015  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:47.803  1015  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:47.803  1015  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:47.803  1015  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:47.823  7078  7078 D TimaKeyStoreProvider: TimaSignature is unavailable,
,09-09 13:35:47.823  7078  7078 D ActivityThread: Added TimaKeyStore provider
09-09 13:35:47.823  7090  7090 E Zygote  : MountEmulatedStorage()
09-09 13:35:47.823  7090  7090 E Zygote  : v2,
09-09 13:35:47.823  7090  7090 I libpersona: KNOX_SDCARD checking this for 1000
09-09 13:35:47.823  7090  7090 I libpersona: KNOX_SDCARD not a persona
09-09 13:35:47.833  7090  7090 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:35:47.833  7090  7090 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 13:35:47.833  1015  1539 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7090 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-09 13:35:47.833  1015  1539 I ActivityManager: Killing 6531:com.android.providers.calendar/u0a37 (adj 15): empty #21
09-09 13:35:47.833  7090  7090 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:35:47.863  7090  7090 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:35:47.863  7090  7090 D ActivityThread: Added TimaKeyStore provider
09-09 13:35:47.863  7062  7062 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,09-09 13:35:47.873  7062  7062 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:35:47.873  7062  7062 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 13:35:47.873  7062  7062 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-09 13:35:47.903  7078  7110 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,09-09 13:35:47.903  7078  7110 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-09 13:35:47.903  7078  7078 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,09-09 13:35:47.903  1015  1477 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,09-09 13:35:47.913  1015  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:47.913  1015  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:47.913  1015  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:47.913  1015  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:47.913  7090  7090 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-09 13:35:47.923  1015  1477 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7112 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:35:47.923  7112  7112 E Zygote  : MountEmulatedStorage()
09-09 13:35:47.923  1015  1477 I ActivityManager: Killing 6614:com.qualcomm.timeservice/1000 (adj 15): empty #21
,09-09 13:35:47.933  7112  7112 E Zygote  : v2
09-09 13:35:47.933  7112  7112 I libpersona: KNOX_SDCARD checking this for 10036
09-09 13:35:47.933  7112  7112 I libpersona: KNOX_SDCARD not a persona
09-09 13:35:47.933  7112  7112 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-09 13:35:47.933  1015  1477 D RCPManagerService: exchangeData() failure , invalid userId
09-09 13:35:47.933  1015  1571 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
09-09 13:35:47.933  1015  1571 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
09-09 13:35:47.933  1015  1571 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:47.933  1015  1571 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-09 13:35:47.933  1015  1571 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
09-09 13:35:47.933  7112  7112 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 13:35:47.943  7078  7110 D SPPClientService: PushLog.txt file is not deleted.
,09-09 13:35:47.943  7078  7110 D SPPClientService: PushLog.txt file is not deleted.
09-09 13:35:47.943  7078  7110 D SPPClientService: ============PushLog. stop!
,09-09 13:35:47.943  7112  7112 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,09-09 13:35:47.953  1015  1539 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 13:35:47.963  7112  7112 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:35:47.963  7112  7112 D ActivityThread: Added TimaKeyStore provider
,09-09 13:35:47.983  7078  7118 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,09-09 13:35:48.013  1015  1539 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 13:35:48.023  7112  7112 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@108257c7,
,09-09 13:35:48.033  1015  1486 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 13:35:48.033  7112  7112 I SA      : [SSP] onCreated
,09-09 13:35:48.053  7112  7112 I SA      : [TPM] There is no property file,
09-09 13:35:48.053  1015  3173 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
09-09 13:35:48.053  1015  3173 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-09 13:35:48.053  1015  3173 W ActivityManager: userId = 0, bbcId = -10000,
09-09 13:35:48.053  1015  3173 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:48.053  1015  3173 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
09-09 13:35:48.053  7112  7112 I SA      : [SCU] isHaveSA() - false,
09-09 13:35:48.053  7090  7090 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
09-09 13:35:48.053  7112  7112 I SA      : [TPM] getModelProperty : null
09-09 13:35:48.053  7112  7112 I SA      : [TPM] getCSCProperty : null
,09-09 13:35:48.063  7112  7112 I SA      : [DM] FLOATING AMOLED FEATURE: true
09-09 13:35:48.063  7112  7112 I SA      : [DM] PRODUCT AMOLED FEATURE: false
09-09 13:35:48.063  7112  7112 I SA      : [DM] TFT FEATURE: false
,09-09 13:35:48.063  1015  1539 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,09-09 13:35:48.063  1015  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:48.063  1015  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:48.063  1015  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:48.063  1015  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:48.063  7112  7112 I SA      : [DM] init START
,09-09 13:35:48.073  7112  7112 I SA      : [DM] This device is not a Vodafone
,09-09 13:35:48.073  7140  7140 E Zygote  : MountEmulatedStorage()
,09-09 13:35:48.073  7140  7140 E Zygote  : v2
09-09 13:35:48.073  7140  7140 I libpersona: KNOX_SDCARD checking this for 10110
09-09 13:35:48.073  7140  7140 I libpersona: KNOX_SDCARD not a persona
,09-09 13:35:48.073  7140  7140 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 13:35:48.073  7090  7090 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,09-09 13:35:48.073  7090  7090 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:35:48.083  7090  7090 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-09 13:35:48.083  7090  7090 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,09-09 13:35:48.083  7090  7090 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
09-09 13:35:48.083  1015  1539 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7140 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 13:35:48.083  7140  7140 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 13:35:48.083  7140  7140 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-09 13:35:48.083  1015  1539 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
09-09 13:35:48.083  7112  7112 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
09-09 13:35:48.083  7112  7112 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75),
09-09 13:35:48.083  7112  7112 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
09-09 13:35:48.083  1015  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:48.083  7112  7112 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
09-09 13:35:48.083  1015  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:48.083  7112  7112 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
09-09 13:35:48.083  1015  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:48.083  7112  7112 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
09-09 13:35:48.083  1015  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-09 13:35:48.083  7112  7112 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
09-09 13:35:48.093  7112  7112 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 13:35:48.093  7112  7112 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
09-09 13:35:48.093  7112  7112 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
09-09 13:35:48.093  7112  7112 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
09-09 13:35:48.093  7112  7112 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
09-09 13:35:48.093  7112  7112 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
09-09 13:35:48.093  7112  7112 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
09-09 13:35:48.093  7112  7112 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
09-09 13:35:48.093  7112  7112 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
09-09 13:35:48.093  7112  7112 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
09-09 13:35:48.093  7112  7112 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
09-09 13:35:48.093  7112  7112 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
09-09 13:35:48.093  7112  7112 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
09-09 13:35:48.093  7112  7112 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
09-09 13:35:48.093  7112  7112 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
09-09 13:35:48.093  7112  7112 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
09-09 13:35:48.093  7112  7112 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
09-09 13:35:48.093  7112  7112 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
09-09 13:35:48.093  7112  7112 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
09-09 13:35:48.093  7112  7112 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
09-09 13:35:48.093  7112  7112 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,09-09 13:35:48.103  7152  7152 E Zygote  : MountEmulatedStorage()
09-09 13:35:48.103  7152  7152 I libpersona: KNOX_SDCARD checking this for 10008
09-09 13:35:48.103  7152  7152 E Zygote  : v2
09-09 13:35:48.103  7152  7152 I libpersona: KNOX_SDCARD not a persona
09-09 13:35:48.103  7152  7152 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:35:48.103  1015  1570 D RCPManagerService: exchangeData() failure , invalid userId
09-09 13:35:48.103  1015  1539 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7152 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 13:35:48.103  7112  7112 I SA      : [SCU] isHaveSA() - false
09-09 13:35:48.103  7112  7112 I SA      : support phone number id : false
09-09 13:35:48.103  7112  7112 I SA      : [DM] Supports Ref Jpn : true
09-09 13:35:48.103  7112  7112 I SA      : [DM] init END
09-09 13:35:48.103  7112  7112 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,09-09 13:35:48.113  7140  7140 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:35:48.113  1015  1539 I ActivityManager: Killing 6038:com.android.mms/u0a41 (adj 15): empty #21
09-09 13:35:48.113  7112  7112 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
09-09 13:35:48.113  7112  7112 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
09-09 13:35:48.113  7140  7140 D ActivityThread: Added TimaKeyStore provider
,09-09 13:35:48.113  7152  7152 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 13:35:48.113  1015  1569 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
09-09 13:35:48.113  7152  7152 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-09 13:35:48.123  1015  3173 D RCPManagerService: exchangeData() failure , invalid userId
09-09 13:35:48.123  1015  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:48.123  1015  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:48.123  1015  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:48.123  1015  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:48.133  7112  7112 I SA      : [SLFUCHKMGR] constructor called,
09-09 13:35:48.133  7152  7152 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:35:48.143  7152  7152 D ActivityThread: Added TimaKeyStore provider,
,09-09 13:35:48.143  7174  7174 E Zygote  : MountEmulatedStorage()
09-09 13:35:48.143  7174  7174 I libpersona: KNOX_SDCARD checking this for 10068
,09-09 13:35:48.143  7174  7174 E Zygote  : v2
09-09 13:35:48.143  7174  7174 I libpersona: KNOX_SDCARD not a persona
,09-09 13:35:48.143  7174  7174 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:35:48.143  1015  1569 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7174 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,09-09 13:35:48.143  1015  1132 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
09-09 13:35:48.143  1015  1132 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-09 13:35:48.153  7174  7174 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 13:35:48.153  1015  1132 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:48.153  1015  1132 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:48.153  1015  1132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
09-09 13:35:48.153  7112  7112 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-09 13:35:48.153  7112  7112 I SA      : [OR] == isSIMCardReady false ==
,09-09 13:35:48.153  7174  7174 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-09 13:35:48.153  7112  7112 I SA      : [SCU] == networkStateCheck == false
09-09 13:35:48.153  7112  7112 I SA      : [OR] onReceive END
,09-09 13:35:48.163  1015  1539 I ActivityManager: Killing 6640:com.sec.esdk.elm/u0a90 (adj 15): empty #21
,09-09 13:35:48.173  6911  7138 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-09 13:35:48.173  1221  1221 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:35:48.183  7174  7174 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:35:48.183  7174  7174 D ActivityThread: Added TimaKeyStore provider
09-09 13:35:48.193  1015  1533 I ActivityManager: Killing 6657:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,09-09 13:35:48.193  1015  1132 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-09 13:35:48.193  1015  1132 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4318, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-09 13:35:48.193  1015  1132 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-09 13:35:48.193  1015  1132 D BatteryService: stay LED for fully charged
09-09 13:35:48.193  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-09 13:35:48.203  1015  1571 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 13:35:48.203  1015  1015 I MotionRecognitionService: Plugged
09-09 13:35:48.203  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,09-09 13:35:48.213  1015  1027 D CountryDetector: No listener is left
,09-09 13:35:48.213  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-09 13:35:48.213  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-09 13:35:48.213  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-09 13:35:48.213  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-09 13:35:48.223  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-09 13:35:48.223  7174  7174 D BadgeProvider: onCreate
,09-09 13:35:48.223  7174  7174 D BadgeProvider: DatabaseHelper
,09-09 13:35:48.233  3179  3179 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-09 13:35:48.233  3179  3282 D HeadsetStateMachine: Disconnected process message: 10
,09-09 13:35:48.243  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-09 13:35:48.243  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-09 13:35:48.243  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
09-09 13:35:48.243  1177  1177 D SViewCoverView: level :100 plugged : 2
,09-09 13:35:48.263  7174  7182 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,09-09 13:35:48.273  1015  3173 I ActivityManager: Killing 6478:com.android.calendar/u0a131 (adj 15): empty #21
,09-09 13:35:48.273  2922  2922 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Sep 09 13:35:48 GMT+02:00 2016
,09-09 13:35:48.273  1015  1570 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-09 13:35:48.273  1015  1570 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
09-09 13:35:48.273  1015  1570 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:48.283  1015  1570 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:48.283  1015  1570 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-09 13:35:48.283  7174  7182 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
09-09 13:35:48.283  7174  7182 D BadgeProvider: sendNotify, [notify] : null
09-09 13:35:48.283  7174  7182 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
09-09 13:35:48.283  7174  7182 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-09 13:35:48.283  7174  7182 D BadgeProvider: update, [UpdateCount] : 1
,09-09 13:35:48.283  2922  2922 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-09 13:35:48.283  1478  1478 D Launcher.Model: reloadBadges entered.
,09-09 13:35:48.293  1015  1028 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 13:35:48.293  1015  1571 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,09-09 13:35:48.293  1015  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:48.293  1015  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:48.293  1015  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:48.293  1015  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:48.303  2922  2922 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-09 13:35:48.303  2922  2922 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-09 13:35:48.303  2922  2922 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-09 13:35:48.303  2922  7189 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-09 13:35:48.313  2922  7189 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-09 13:35:48.313  7190  7190 E Zygote  : MountEmulatedStorage()
,09-09 13:35:48.313  7190  7190 E Zygote  : v2
09-09 13:35:48.313  7190  7190 I libpersona: KNOX_SDCARD checking this for 10009
09-09 13:35:48.313  7190  7190 I libpersona: KNOX_SDCARD not a persona
,09-09 13:35:48.313  7190  7190 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:35:48.313  7190  7190 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 13:35:48.313  1015  1571 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7190 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,09-09 13:35:48.313  7190  7190 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-09 13:35:48.323  1015  1571 I ActivityManager: Killing 6675:com.google.android.gms:car/u0a11 (adj 15): empty #21
,09-09 13:35:48.323  2922  7189 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,09-09 13:35:48.323  2922  7189 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,09-09 13:35:48.323  2922  2922 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-09 13:35:48.333  1015  1132 I ActivityManager: Killing 5999:com.android.defcontainer/u0a3 (adj 15): empty #21
,09-09 13:35:48.343  7190  7190 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:35:48.343  7190  7190 D ActivityThread: Added TimaKeyStore provider
,09-09 13:35:48.353  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-09 13:35:48.353  1015  1124 E WifiHW  : ##################### set firmware type 0 #####################
,09-09 13:35:48.423  1015  1570 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
09-09 13:35:48.423  1015  1570 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,09-09 13:35:48.423  1015  1376 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,09-09 13:35:48.423  1015  1539 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,09-09 13:35:48.443  1015  1533 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-09 13:35:48.493  1015  1477 I ActivityManager: Killing 5810:com.android.vending/u0a26 (adj 15): empty #21
,09-09 13:35:48.503  1015  1571 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 13:35:48.503  1015  1571 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-09 13:35:48.503  1015  1571 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:48.503  1015  1571 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 13:35:48.503  1015  1571 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:48.523  4748  7207 I iu.SyncManager: SYNC; picasa accounts
,09-09 13:35:48.533  4748  4748 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,09-09 13:35:48.603   256   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-09 13:35:48.603   256   531 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:35:48.603  7140  7213 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-09 13:35:48.603   256   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-09 13:35:48.603   256   531 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:35:48.613  7140  7213 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-09 13:35:48.633  1015  1047 I PowerManagerService: [PWL] Off : 75s ago
,09-09 13:35:48.633  1015  1047 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
09-09 13:35:48.633  1015  1047 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,09-09 13:35:48.633  1015  1047 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=3179, ws=null) (elapsedTime=2900)
09-09 13:35:48.633  1015  1047 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1015, ws=null) (elapsedTime=2195)
,09-09 13:35:48.633   256   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-09 13:35:48.633   256   531 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:35:48.643  7140  7218 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-09 13:35:48.643   256   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-09 13:35:48.643   256   531 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:35:48.643  7140  7218 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-09 13:35:48.653  7140  7140 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-09 13:35:48.653  7140  7140 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-09 13:35:48.653  7140  7140 I GAv4    :   adb logcat -s GAv4
,09-09 13:35:48.673  7140  7140 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-09 13:35:48.673  1015  1570 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-09 13:35:48.683  7140  7140 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-09 13:35:48.693  7140  7220 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-09 13:35:48.733  1015  1042 D Tethering: interfaceAdded wlan0
,09-09 13:35:48.743  1015  1127 E Tethering: No numeric data,
09-09 13:35:48.743  1015  1127 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-09 13:35:48.743  1015  1127 D Tethering: clearTetheredNotification()
,09-09 13:35:48.743  1015  1121 V NetworkStats: performPollLocked(flags=0x1),
09-09 13:35:48.743  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:48.743  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 13:35:48.743  1177  1177 D HotspotTile: updateTetherState():false, false
,09-09 13:35:48.743  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:35:48.743  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 13:35:48.743  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-09 13:35:48.743  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:35:48.743  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-09 13:35:48.743  1015  1127 D Tethering: InitialState.processMessage what=4
,09-09 13:35:48.743  1015  1121 V NetworkStats: performPollLocked() took 6ms
09-09 13:35:48.753  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:48.753  1015  1127 E Tethering: No numeric data
,09-09 13:35:48.753  1015  1127 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 13:35:48.753  1015  1127 D Tethering: clearTetheredNotification()
,09-09 13:35:48.753  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:48.753  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:48.753  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
09-09 13:35:48.753  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:48.753  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 13:35:48.753  1177  1177 D HotspotTile: updateTetherState():false, false
,09-09 13:35:48.753  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-09 13:35:48.753  1015  1042 D Tethering: interfaceAdded p2p0
09-09 13:35:48.753  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 13:35:48.753  1015  1042 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-09 13:35:48.763  1015  1121 V NetworkStats: performPollLocked() took 7ms
,09-09 13:35:48.763  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:48.763  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:48.763  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:48.763  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 13:35:48.763  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 13:35:48.763  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-09 13:35:48.763   280  1013 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,09-09 13:35:48.763   280  1013 D SoftapController: Softap fwReload - Ok
,09-09 13:35:48.773   280  1013 D CommandListener: Setting iface cfg
09-09 13:35:48.773   280  1013 D CommandListener: Trying to bring down wlan0
,09-09 13:35:48.773   280  1013 D CommandListener: Clearing all IP addresses on wlan0
,09-09 13:35:48.773  1015  1124 E WifiHW  : supplicant_name : p2p_supplicant
,09-09 13:35:48.773  1015  1124 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-09 13:35:48.773  1015  1124 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,09-09 13:35:48.783  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 13:35:48.783  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-09 13:35:48.783  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:48.783  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:48.783  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:48.783  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:35:48.783  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:35:48.783  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
09-09 13:35:48.783  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:35:48.783  1177  1607 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-09 13:35:48.783  1177  1177 D HotspotTile: onReceive : 2, 0
,09-09 13:35:48.793  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:48.793  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:48.793  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-09 13:35:48.833  7223  7223 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,09-09 13:35:48.833  7223  7223 I wpa_supplicant: Successfully initialized wpa_supplicant
09-09 13:35:48.833  7223  7223 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-09 13:35:48.853  7223  7223 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
09-09 13:35:48.853   364   364 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7223
09-09 13:35:48.853   364   364 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
,09-09 13:35:48.853  7223  7223 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-09 13:35:48.853  7223  7223 I wpa_supplicant: ssSupport state is = 1
09-09 13:35:48.853  7223  7223 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-09 13:35:48.853  7223  7223 I SecureStorage: [INFO]: SPID(0x00000000)Processing data,
09-09 13:35:48.853   364   364 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7223
09-09 13:35:48.853   364   364 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106,
,09-09 13:35:48.873   290   290 E SMD     : DCD OFF
,09-09 13:35:48.963  1015  1323 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:35:48.963  1015  1323 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:48.963  1015  1323 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:48.963  1015  1323 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-09 13:35:48.993  7140  7140 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,09-09 13:35:49.013  7140  7140 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 7185-7187)
09-09 13:35:49.013  7140  7140 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-09 13:35:49.033  7140  7140 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3440599e}
,09-09 13:35:49.033  7140  7140 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-09 13:35:49.033  7140  7140 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-09 13:35:49.043   364   364 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,09-09 13:35:49.043  7223  7223 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,09-09 13:35:49.053  7140  7140 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,09-09 13:35:49.053  7140  7140 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 13:35:49.053  7140  7140 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-09 13:35:49.063  7140  7140 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-09 13:35:49.063  7140  7140 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-09 13:35:49.063  7140  7140 I Adreno-EGL: Build Date: 04/06/15 Mon
09-09 13:35:49.063  7140  7140 I Adreno-EGL: Local Branch: 
09-09 13:35:49.063  7140  7140 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
,09-09 13:35:49.063  7140  7140 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-09 13:35:49.063  7140  7140 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-09 13:35:49.093  7223  7223 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-09 13:35:49.093  7223  7223 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-09 13:35:49.103  7223  7223 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
09-09 13:35:49.103   364   364 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7223
09-09 13:35:49.103   364   364 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-09 13:35:49.103  7223  7223 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-09 13:35:49.103  7223  7223 I wpa_supplicant: ssSupport state is = 1
,09-09 13:35:49.113  7223  7223 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-09 13:35:49.113  7223  7223 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 13:35:49.113  7223  7223 E wpa_supplicant: SIM READ ERROR
09-09 13:35:49.113  7223  7223 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 13:35:49.113  7223  7223 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 13:35:49.113  7223  7223 E wpa_supplicant: SIM READ ERROR
09-09 13:35:49.113  7223  7223 I wpa_supplicant: Blacklist: Clear (all) 
09-09 13:35:49.113  7223  7223 I wpa_supplicant: wpa_default_ap_write_once
09-09 13:35:49.113  7223  7223 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-09 13:35:49.113  7223  7223 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 13:35:49.113  7223  7223 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-09 13:35:49.113  7223  7223 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 13:35:49.113  7223  7223 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 13:35:49.113  7223  7223 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-09 13:35:49.113  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-09 13:35:49.123  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:35:49.123  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-09 13:35:49.133  7140  7252 W cr.media: Requires BLUETOOTH permission
,09-09 13:35:49.143  7140  7140 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-09 13:35:49.163  7140  7140 I NSApplication: Starting up...
,09-09 13:35:49.163  1015  1486 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-09 13:35:49.163  1015  1539 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-09 13:35:49.173  1015  3173 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,09-09 13:35:49.173  1015  3173 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:49.173  1015  3173 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:49.173  1015  3173 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:49.173  1015  3173 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:49.183  7223  7223 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-09 13:35:49.193  7257  7257 E Zygote  : MountEmulatedStorage()
,09-09 13:35:49.193  7257  7257 I libpersona: KNOX_SDCARD checking this for 10117
09-09 13:35:49.193  7257  7257 E Zygote  : v2
09-09 13:35:49.193  7257  7257 I libpersona: KNOX_SDCARD not a persona
,09-09 13:35:49.193  7257  7257 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 13:35:49.193  1015  3173 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7257 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-09 13:35:49.193  1015  3173 I ActivityManager: Killing 6809:com.google.android.gms.unstable/u0a11 (adj 15): empty #21
,09-09 13:35:49.203  7257  7257 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 13:35:49.203  7257  7257 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-09 13:35:49.233  7257  7257 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:35:49.233  7257  7257 D ActivityThread: Added TimaKeyStore provider
,09-09 13:35:49.253  7257  7257 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 13:35:49.343  7223  7223 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-09 13:35:49.343  7223  7223 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-09 13:35:49.353  7223  7223 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,09-09 13:35:49.363   364   364 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7223
09-09 13:35:49.363   364   364 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-09 13:35:49.363  7223  7223 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-09 13:35:49.363  7223  7223 I wpa_supplicant: ssSupport state is = 1
,09-09 13:35:49.363  7223  7223 I wpa_supplicant: Ctrl_iface: loading cred from phone,
09-09 13:35:49.363  7223  7223 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-09 13:35:49.373  7223  7223 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
09-09 13:35:49.373   364   364 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7223
09-09 13:35:49.373   364   364 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,09-09 13:35:49.373  7223  7223 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-09 13:35:49.373  7223  7223 I wpa_supplicant: ssSupport state is = 1
09-09 13:35:49.373  7223  7223 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 13:35:49.373  7223  7223 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 13:35:49.373  7223  7223 E wpa_supplicant: SIM READ ERROR
09-09 13:35:49.373  7223  7223 I wpa_supplicant: wpa_default_ap_write_once
,09-09 13:35:49.373  7223  7223 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
09-09 13:35:49.373  7223  7223 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-09 13:35:49.383  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 13:35:49.383  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 13:35:49.383  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
09-09 13:35:49.383  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
09-09 13:35:49.383  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 13:35:49.383  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-09 13:35:49.503  7223  7223 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
09-09 13:35:49.503  7223  7223 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-09 13:35:49.593  7223  7223 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
,09-09 13:35:49.603  7223  7223 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-09 13:35:49.603  7223  7223 I wpa_supplicant: Skip scan - bUseNetwork false
,09-09 13:35:49.653  1015  1323 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,09-09 13:35:49.653  1015  1323 I ActivityManager: Killing 6952:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,09-09 13:35:49.663  1015  1132 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 13:35:49.663  1015  1132 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:35:49.663  1015  1132 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:49.673  1015  1132 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:49.673  1015  1132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:35:49.673  1636  1636 I Hs20UtilService: Starting #11
,09-09 13:35:49.673  1636  1705 I Hs20UtilService: Message received 5011
,09-09 13:35:49.673  6542  6542 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-09 13:35:49.673  6542  6542 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 13:35:49.673  6542  6542 D SecurityLogAgent: StateMachine : Current State = 1
,09-09 13:35:49.673  6542  6542 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 13:35:49.683  1015  1376 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 13:35:49.683  1015  1376 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:35:49.683  1015  1376 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:49.683  1015  1376 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 13:35:49.683  1015  1376 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:35:49.693  1636  1636 I Hs20UtilService: Starting #12,
09-09 13:35:49.693  1636  1705 I Hs20UtilService: Message received 5011
,09-09 13:35:49.693  6542  6542 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-09 13:35:49.693  6542  6542 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 13:35:49.693  6542  6542 D SecurityLogAgent: StateMachine : Current State = 1
,09-09 13:35:49.693  6542  6542 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 13:35:49.743  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-09 13:35:49.743  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 13:35:49.743  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-09 13:35:49.783  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
,09-09 13:35:49.783  1015  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21],
09-09 13:35:49.783  7223  7223 I wpa_supplicant: HOTSPOT20_ENABLE called
09-09 13:35:49.783  7223  7223 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 13:35:49.783  7223  7223 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-09 13:35:49.783  7223  7223 E wpa_supplicant: SIM READ ERROR
09-09 13:35:49.783  7223  7223 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 13:35:49.813  7223  7223 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-09 13:35:49.823  7223  7223 I wpa_supplicant: Skip scan - bUseNetwork false
,09-09 13:35:49.823  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 13:35:49.823  1015  1124 D WifiConfigStore: Loading config and enabling all networks 
09-09 13:35:49.823  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:35:49.823  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:49.823  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:35:49.823  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:35:49.823  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:35:49.823  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:35:49.823  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,09-09 13:35:49.833  1177  1607 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-09 13:35:49.833  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:35:49.833  1177  1177 D HotspotTile: onReceive : 3, 0
,09-09 13:35:49.833  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:49.833  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:49.833  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:49.833  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:49.833  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:49.833  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:35:49.833  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:35:49.833  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:35:49.833  1015  1124 E WifiConfigStore: Not a HS20
,09-09 13:35:49.843  1015  1124 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-09 13:35:49.843  6731  6731 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:35:49.843  1015  1027 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 13:35:49.843  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:35:49.843  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:49.843  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:49.843  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-09 13:35:49.843  1015  1124 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-09 13:35:49.843  1636  1636 I Hs20UtilService: Starting #13
,09-09 13:35:49.843  1636  1705 I Hs20UtilService: Message received 5011
,09-09 13:35:49.843  1015  1124 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-09 13:35:49.843  7223  7223 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-09 13:35:49.843  7223  7223 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-09 13:35:49.843  7223  7223 I wpa_supplicant: reset timer : RESET_TIMER 0
09-09 13:35:49.843  7223  7223 I wpa_supplicant: P2P: Current p2p state = IDLE
09-09 13:35:49.843  7223  7223 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-09 13:35:49.843  7223  7223 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-09 13:35:49.843  7223  7223 I wpa_supplicant: First Scan Start
09-09 13:35:49.843  7223  7223 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-09 13:35:49.853  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:49.853  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:49.853  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:49.853  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:49.853  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:49.853  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:35:49.853  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:35:49.853  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:35:49.853  6731  6731 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:35:49.853  6542  6542 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-09 13:35:49.853  6542  6542 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 13:35:49.853  6542  6542 D SecurityLogAgent: StateMachine : Current State = 1
09-09 13:35:49.853  6542  6542 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 13:35:49.853  1015  1124 D WifiNative-wlan0: Setting external_sim to 1
,09-09 13:35:49.853  1015  1124 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 13:35:49.853  1015  1124 I WifiNative-HAL: startHal
09-09 13:35:49.853  1015  1124 E wifi    : getStaticLongField sWifiHalHandle 0x9d66f88c
09-09 13:35:49.853  1015  1124 I WifiNative-HAL: Could not start hal
,09-09 13:35:49.863  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:49.863  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:49.863  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:49.863  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:49.863  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:49.863  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:35:49.863  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:35:49.863  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:35:49.863  1015  1124 E WifiNative-wlan0: do suspend true
,09-09 13:35:49.863  1015  1123 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-09 13:35:49.863  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
09-09 13:35:49.863  6911  6911 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:35:49.863  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3
,09-09 13:35:49.863  1015  1015 D RttService: SCAN_AVAILABLE : 3
,09-09 13:35:49.863  1015  1148 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:49.863  1015  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-09 13:35:49.863  1015  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-09 13:35:49.863  1015  1124 E WifiNative-wlan0: invaild command id : 215
09-09 13:35:49.863   280  1013 D CommandListener: Setting iface cfg
09-09 13:35:49.863   280  1013 D CommandListener: Trying to bring up p2p0
,09-09 13:35:49.863  1015  1147 D WifiScanningService: DefaultState got{ when=-3ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:49.863  1015  1147 I WifiNative-HAL: startHal
09-09 13:35:49.863  1015  1147 E wifi    : getStaticLongField sWifiHalHandle 0x9e6199bc
09-09 13:35:49.863  1015  1147 I WifiNative-HAL: Could not start hal
09-09 13:35:49.863  1015  1147 E WifiScanningService: could not start HAL
,09-09 13:35:49.873  6731  6731 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:35:49.873  1015  1123 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-09 13:35:49.873  7223  7223 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-09 13:35:49.873  1015  1123 D WifiP2pService: P2pEnablingState
,09-09 13:35:49.873  7223  7223 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-09 13:35:49.873  1015  1123 D WifiP2pService: P2pEnablingState{ what=147457 }
09-09 13:35:49.873  1015  1123 D WifiP2pService: P2p socket connection successful
,09-09 13:35:49.873  1015  1123 D WifiP2pService: P2pEnabledState
09-09 13:35:49.873  7223  7223 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,09-09 13:35:49.873  1015  1124 E WifiStateMachine: Failed to set frequency band 0
,09-09 13:35:49.873  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:35:49.873  1015  1124 D SecContentProvider2: mCursor = null
,09-09 13:35:49.873  1015  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-09 13:35:49.873  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:35:49.873  1015  1124 D SecContentProvider2: mCursor = null
,09-09 13:35:49.873  1015  1126 E ConnectivityService: updateNetworkInfo()
,09-09 13:35:49.883  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-09 13:35:49.883  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-09 13:35:49.883  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 13:35:49.883  1015  1123 D WifiNative-p2p0: p2pGetDeviceAddress
09-09 13:35:49.883  1015  1045 D WifiDisplayController: disconnect
09-09 13:35:49.883  1015  1045 D WifiDisplayController: updateConnection
,09-09 13:35:49.883  1015  1123 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
09-09 13:35:49.883  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 13:35:49.883  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 13:35:49.883  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:35:49.883  6889  6889 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-09 13:35:49.883  6889  6889 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-09 13:35:49.883  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
,09-09 13:35:49.883  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 13:35:49.883  1015  1123 D WifiP2pService: DeviceAddress: 0a:76:28
09-09 13:35:49.883  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-09 13:35:49.893  6889  6889 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 13:35:49.893  6889  6889 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED,
09-09 13:35:49.893  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-09 13:35:49.893  6889  6889 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 13:35:49.893  1015  1477 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-09 13:35:49.893  6889  6889 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 13:35:49.893  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-09 13:35:49.893  6889  6908 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-09 13:35:49.893  1015  1045 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
09-09 13:35:49.893  1015  1045 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
09-09 13:35:49.893  1015  1045 D WifiDisplayController:  primary type: 10-0050F204-5
09-09 13:35:49.893  1015  1045 D WifiDisplayController:  secondary type: null
09-09 13:35:49.893  1015  1045 D WifiDisplayController:  wps: 0
09-09 13:35:49.893  1015  1045 D WifiDisplayController:  grpcapab: 0
09-09 13:35:49.893  1015  1045 D WifiDisplayController:  devcapab: 0
09-09 13:35:49.893  1015  1045 D WifiDisplayController:  status: 3
09-09 13:35:49.893  1015  1045 D WifiDisplayController:  wfdInfo: null
09-09 13:35:49.893  1015  1045 D WifiDisplayController:  groupownerAddress: null
09-09 13:35:49.893  1015  1045 D WifiDisplayController:  GOdeviceName: null
09-09 13:35:49.893  1015  1045 D WifiDisplayController:  interfaceAddress: ,
09-09 13:35:49.893  1015  1045 D WifiDisplayController:  SConnectInfo : null
09-09 13:35:49.893  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,09-09 13:35:49.893  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:49.893  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:49.893  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:49.893  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:49.913  7286  7286 E Zygote  : MountEmulatedStorage()
09-09 13:35:49.913  7286  7286 E Zygote  : v2
09-09 13:35:49.913  7286  7286 I libpersona: KNOX_SDCARD checking this for 10064
09-09 13:35:49.913  7286  7286 I libpersona: KNOX_SDCARD not a persona
09-09 13:35:49.913  1015  1123 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-09 13:35:49.913  7286  7286 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:35:49.913  7286  7286 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-09 13:35:49.913  1015  1028 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7286 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 13:35:49.913  7286  7286 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 13:35:49.923  1015  1123 D WifiP2pService: InactiveState
,09-09 13:35:49.923  1015  1123 D WifiP2pService: InactiveState{ what=143376 }
09-09 13:35:49.923  1015  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-09 13:35:49.923  7223  7223 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-09 13:35:49.923  1015  1123 D WifiP2pService: InactiveState{ what=143376 }
09-09 13:35:49.923  1015  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-09 13:35:49.933  7286  7286 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:35:49.933  7286  7286 D ActivityThread: Added TimaKeyStore provider,
,09-09 13:35:49.953  7286  7286 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-09 13:35:49.963  7286  7286 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 13:35:49.963  7286  7286 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-09 13:35:49.993  7286  7286 D FileShare-Client: Outbound.stopDelayTimer - ,
,09-09 13:35:49.993  6968  6968 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 13:35:50.003  1015  1027 I ActivityManager: Killing 6983:com.sec.pcw.device/1000 (adj 15): empty #21
,09-09 13:35:50.023  1015  1301 E Watchdog: !@Sync 4
,09-09 13:35:50.053  6731  6786 D BluetoothAdapter: enable()
,09-09 13:35:50.053  6731  6786 D BluetoothAdapter: enable(): BT is already enabled..!
,09-09 13:35:50.903   325   325 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 13:35:51.393  7223  7223 I wpa_supplicant: nl80211: Received scan results (13 BSSes),
09-09 13:35:51.393  7223  7223 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-09 13:35:51.393  7223  7223 I wpa_supplicant: Trying to associate with SSID '4E47373030',
09-09 13:35:51.393  7223  7223 I wpa_supplicant: Trying to associate with  'G700'
09-09 13:35:51.393  7223  7223 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
09-09 13:35:51.393  7223  7223 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030,
,09-09 13:35:51.403  1015  7283 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-09 13:35:51.423  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:35:51.423  1015  1124 D SecContentProvider2: mCursor = null
,09-09 13:35:51.653  7223  7223 E wpa_supplicant: Cmd 35605 not handled
,09-09 13:35:51.653  7223  7223 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-09 13:35:51.653  7223  7223 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
09-09 13:35:51.653  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:35:51.653  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:35:51.653  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
09-09 13:35:51.653  7223  7223 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-09 13:35:51.653  7223  7223 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-09 13:35:51.653  7223  7223 I wpa_supplicant: Associated with F4.99.3E
09-09 13:35:51.663  7223  7223 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-09 13:35:51.663  7223  7223 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-09 13:35:51.663  7223  7223 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-09 13:35:51.663  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:35:51.663  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
,09-09 13:35:51.663  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-09 13:35:51.663  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
09-09 13:35:51.663  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:35:51.663  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-09 13:35:51.663  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-09 13:35:51.663  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, true
09-09 13:35:51.663  1015  1042 D Tethering: interfaceStatusChanged wlan0, true
,09-09 13:35:51.663  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:35:51.663  1015  1124 D SecContentProvider2: mCursor = null
09-09 13:35:51.663  1015  1127 E Tethering: No numeric data
,09-09 13:35:51.663  1015  1127 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-09 13:35:51.663  1015  1127 D Tethering: clearTetheredNotification()
,09-09 13:35:51.673  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
,09-09 13:35:51.673  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:51.673  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-09 13:35:51.673  1177  1177 D HotspotTile: updateTetherState():false, false
,09-09 13:35:51.673  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-09 13:35:51.673  1015  1124 D SecContentProvider2: mCursor = null
09-09 13:35:51.673  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:35:51.673  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-09 13:35:51.673  1015  1121 V NetworkStats: performPollLocked() took 7ms
09-09 13:35:51.683  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:51.683  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit,
09-09 13:35:51.683  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:51.763  7223  7223 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-09 13:35:51.763  7223  7223 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,09-09 13:35:51.763  7223  7223 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,09-09 13:35:51.763  7223  7223 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030,
09-09 13:35:51.763  7223  7223 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-09 13:35:51.763  7223  7223 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED,
09-09 13:35:51.763  7223  7223 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,09-09 13:35:51.763  7223  7223 I wpa_supplicant: Blacklist: Clear (temp) 
09-09 13:35:51.763  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-09 13:35:51.763  7223  7223 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-09 13:35:51.763  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, true
,09-09 13:35:51.763  1015  1042 D Tethering: interfaceStatusChanged wlan0, true
,09-09 13:35:51.773  1015  1124 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-09 13:35:51.773  1015  1124 E WifiConfigStore: setLastSelectedConfiguration -1
,09-09 13:35:51.783  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 13:35:51.783  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-09 13:35:51.783  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:35:51.783  1015  1124 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-09 13:35:51.783  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:51.783  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:51.783  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:35:51.783  1015  1126 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-09 13:35:51.783  1015  1126 E ConnectivityService: updateNetworkInfo()
09-09 13:35:51.783  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-09 13:35:51.793  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
09-09 13:35:51.793  1015  1323 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 13:35:51.793  1015  1323 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:51.793  1015  1323 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-09 13:35:51.793  1015  1323 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:51.793  1015  1323 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:35:51.793  1636  1636 I Hs20UtilService: Starting #14
,09-09 13:35:51.793  1636  1705 I Hs20UtilService: Message received 5007
,09-09 13:35:51.803  6889  6889 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-09 13:35:51.803  6889  6889 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 13:35:51.803  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 13:35:51.803  6889  6889 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 13:35:51.803  6889  6889 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED,
,09-09 13:35:51.803  6889  6889 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 13:35:51.803  6889  6889 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-09 13:35:51.803  6889  6908 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 13:35:51.813   280  1013 D CommandListener: Setting iface cfg,
,09-09 13:35:51.813  1015  1124 E WifiStateMachine: Start Dhcp Watchdog 2
,09-09 13:35:51.823  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-09 13:35:51.823  1015  1124 D SecContentProvider2: mCursor = null
,09-09 13:35:51.833  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 13:35:51.833  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-09 13:35:51.833  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:35:51.833  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:35:51.833  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:51.833  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:35:51.833  1015  1124 E WifiNative-wlan0: do suspend false
,09-09 13:35:51.843  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:35:51.843  1015  1123 D WifiP2pService: InactiveState{ what=143375 }
09-09 13:35:51.843  1015  1124 D SecContentProvider2: mCursor = null
09-09 13:35:51.843  1015  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-09 13:35:51.883   290   290 E SMD     : DCD OFF,
,09-09 13:35:51.903   325   325 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 13:35:52.053  7304  7304 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-09 13:35:52.063  7304  7304 I dhcpcd  : version 5.5.6 starting
,09-09 13:35:52.063  7304  7304 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-09 13:35:52.123  7304  7304 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
09-09 13:35:52.123  7304  7304 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-09 13:35:52.123  7304  7304 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E),
,09-09 13:35:52.123  7304  7304 I dhcpcd  : bssid match
,09-09 13:35:52.123  7304  7304 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,09-09 13:35:52.243  7304  7304 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1,
,09-09 13:35:52.303  7304  7304 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds,
,09-09 13:35:52.443  1015  1124 E WifiNative-wlan0: do suspend true
,09-09 13:35:52.553  1015  1123 D WifiP2pService: InactiveState{ what=143375 }
,09-09 13:35:52.563  1015  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-09 13:35:52.563  1015  1124 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-09 13:35:52.563  1015  1124 E WifiStateMachine: VerifyingLinkState enter
,09-09 13:35:52.563  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 13:35:52.563  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-09 13:35:52.563  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:35:52.563  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:35:52.573  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:35:52.573  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:52.573  1015  1126 E ConnectivityService: updateNetworkInfo()
,09-09 13:35:52.573  1015  1126 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
09-09 13:35:52.573  1015  1126 D ConnectivityService: Adding iface wlan0 to network 503
,09-09 13:35:52.583  1015  1141 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter,
09-09 13:35:52.583  1015  1141 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-09 13:35:52.583  1015  1141 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-09 13:35:52.583  1015  1141 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-09 13:35:52.583  1015  1141 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-09 13:35:52.583  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-09 13:35:52.583  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:35:52.593  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:52.593  1015  1132 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
09-09 13:35:52.593  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:52.593  1015  1132 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
09-09 13:35:52.593  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:52.593  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-09 13:35:52.603  1015  1132 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:52.603  1015  1132 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 13:35:52.603  1015  1132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:35:52.603  1636  1636 I Hs20UtilService: Starting #15
,09-09 13:35:52.613  6889  6889 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-09 13:35:52.613  6889  6889 I NearbySettings: MountReceiver.onReceive - Keep current state,
,09-09 13:35:52.613  1636  1705 I Hs20UtilService: Message received 5007
,09-09 13:35:52.613  1015  1124 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,09-09 13:35:52.633  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-09 13:35:52.633  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:35:52.633  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:35:52.633  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:52.633  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:52.633  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:52.633  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:35:52.643  1015  1126 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 503
,09-09 13:35:52.643  1015  1126 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,09-09 13:35:52.653  1015  1126 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
09-09 13:35:52.653  1015  1126 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-09 13:35:52.653  1015  1126 D ConnectivityService: Setting Dns servers for network 503 to [/192.168.1.1]
,09-09 13:35:52.653  1015  1126 D ConnectivityService: LTETest block dns file not exists
09-09 13:35:52.653  1015  1124 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-09 13:35:52.653  1015  1486 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
09-09 13:35:52.653  1015  1486 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:52.653  1015  1486 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:35:52.653  1015  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:52.653  1015  1126 V NetworkStats: updateIfacesLocked()
09-09 13:35:52.653  1015  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-09 13:35:52.653  1015  1126 V NetworkStats: performPollLocked(flags=0x1)
09-09 13:35:52.653  1015  1124 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-09 13:35:52.653  1636  1636 I Hs20UtilService: Starting #16
09-09 13:35:52.653  1636  1705 I Hs20UtilService: Message received 5007
09-09 13:35:52.653  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:52.653  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling,
09-09 13:35:52.653  1015  1015 I WifiTrafficPoller: mBoosterFLAG : 0
09-09 13:35:52.653  1015  1015 I WifiTrafficPoller: current booster mode : FullMode
09-09 13:35:52.663  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:35:52.663  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 13:35:52.663  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-09 13:35:52.663  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-09 13:35:52.663  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:52.663  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:52.663  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:52.663  1015  1126 V NetworkStats: performPollLocked() took 12ms,
09-09 13:35:52.663  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:52.663  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:52.673  6889  6889 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-09 13:35:52.673  6889  6889 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 13:35:52.673  6889  6889 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 13:35:52.673  1015  1126 E ConnectivityService: updateNetworkInfo()
09-09 13:35:52.673  1015  1126 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
09-09 13:35:52.673  1015  1126 E ConnectivityService: updateNetworkInfo(),
09-09 13:35:52.673  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:35:52.673  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:52.673  1015  1126 V NetworkStats: updateIfacesLocked()
09-09 13:35:52.673  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:52.673  1015  1126 V NetworkStats: performPollLocked(flags=0x1)
09-09 13:35:52.673  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:52.673  6889  6889 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-09 13:35:52.673  6889  6889 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 13:35:52.673  6889  6889 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-09 13:35:52.683  6889  6908 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-09 13:35:52.683  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:35:52.683  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 13:35:52.683  1015  1126 V NetworkStats: performPollLocked() took 5ms
09-09 13:35:52.683  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:52.683  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:52.683  1015  1126 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
09-09 13:35:52.683  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:52.683  1015  1126 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
09-09 13:35:52.683  1015  7302 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:52.683  1015  7302 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
09-09 13:35:52.683  1015  7302 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:52.683  1015  7302 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,09-09 13:35:52.683  1015  7302 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-09 13:35:52.693   280  1009 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-09 13:35:52.693   280  1009 D Netd    : getNetworkForDns: using netid 503 for uid 1000
09-09 13:35:52.693  1015  1126 D ConnectivityService:    accepting network in place of null
09-09 13:35:52.693  1015  1124 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-09 13:35:52.693  1015  1123 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-09 13:35:52.693  1454  1454 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-09 13:35:52.693  1454  1454 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:35:52.693  1015  1477 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 13:35:52.693  1015  1126 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-09 13:35:52.693  1015  1477 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-09 13:35:52.693  1015  1126 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
09-09 13:35:52.693  1015  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-09 13:35:52.693  1015  1477 W ActivityManager: userId = 0, bbcId = -10000,
09-09 13:35:52.693  1015  1126 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
09-09 13:35:52.693  1015  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:52.693  1015  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-09 13:35:52.693  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-09 13:35:52.693  1015  1127 D Tethering: MasterInitialState.processMessage what=3
09-09 13:35:52.693  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:52.693  1015  1121 V NetworkStats: updateIfacesLocked()
09-09 13:35:52.693  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
,09-09 13:35:52.703  1636  1636 I Hs20UtilService: Starting #17,
,09-09 13:35:52.703  1015  1126 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
09-09 13:35:52.703  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:35:52.703  1015  1121 V NetworkStats: performPollLocked() took 4ms
09-09 13:35:52.703  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-09 13:35:52.703  1636  1705 I Hs20UtilService: Message received 5007
09-09 13:35:52.703  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
09-09 13:35:52.703  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
,09-09 13:35:52.703  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-09 13:35:52.703  1177  1177 D StatusBar.NetworkController: updateDataNetType()
09-09 13:35:52.703  1177  1177 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-09 13:35:52.703  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-09 13:35:52.703  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:52.703  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:52.703  1015  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-09 13:35:52.703  1015  1122 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-09 13:35:52.703  6889  6889 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-09 13:35:52.703  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:52.703  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:52.703  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:52.703  6889  6889 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-09 13:35:52.703  1177  1602 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-09 13:35:52.703  4748  6795 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-09 13:35:52.703  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:52.703  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:52.703  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-09 13:35:52.703  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-09 13:35:52.713  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-09 13:35:52.713  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:35:52.713  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-09 13:35:52.713  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:52.713  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:52.713  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:52.713  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:35:52.713  1015  1323 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,09-09 13:35:52.713  1015  1132 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
09-09 13:35:52.713  1015  1132 D SecContentProvider2: mCursor = null
09-09 13:35:52.713  1015  1571 D SecContentProvider2: uri = 15 selection = getToastGravity
09-09 13:35:52.713  1015  1571 D SecContentProvider2: mCursor = null
,09-09 13:35:52.713  1015  1028 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
09-09 13:35:52.713  1015  1028 D SecContentProvider2: mCursor = null
,09-09 13:35:52.723  1015  1027 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
09-09 13:35:52.723  1015  1027 D SecContentProvider2: mCursor = null
,09-09 13:35:52.723  1015  1477 D SecContentProvider2: uri = 15 selection = getToastEnabledState,
09-09 13:35:52.723  1015  1477 D SecContentProvider2: mCursor = null
,09-09 13:35:52.723  1015  1486 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
09-09 13:35:52.723  1015  1486 D SecContentProvider2: mCursor = null
,09-09 13:35:52.753   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,09-09 13:35:52.773  1015  1132 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015
,09-09 13:35:52.773  1177  1177 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-09 13:35:52.913   325   325 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 13:35:52.993  3179  3298 W bt-sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-09 13:35:52.993  3179  3298 E bt-btif : DISCOVERY_COMP_EVT slot id:7, failed to find channle,                                       status:1, scn:0
,09-09 13:35:52.993  3179  3364 W bt-btif : invalid rfc slot id: 7
,09-09 13:35:53.003  6731  6877 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@374c4b50, channel: -1, state: INIT,
,09-09 13:35:53.003  6731  6877 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@374c4b50, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1a4ea149, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@30151a4emSocket: android.net.LocalSocket@d54276f impl:android.net.LocalSocketImpl@3fb2cc7c fd:FileDescriptor[106]
,09-09 13:35:53.003  6731  6877 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@d54276f impl:android.net.LocalSocketImpl@3fb2cc7c fd:FileDescriptor[106]
,09-09 13:35:53.003  6731  6877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1345),
,09-09 13:35:53.193  1015  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:35:53.213  1015  1039 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:35:53.223  1015  3382 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-09 13:35:53.233  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-09 13:35:53.233  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:53.233  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:53.233  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:53.233  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:53.243  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:53.243  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:53.243  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:53.243  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:53.243  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:53.243  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:53.243  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:53.243  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:35:53.243  6731  6731 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:35:53.253  7338  7338 E Zygote  : MountEmulatedStorage()
09-09 13:35:53.253  7338  7338 E Zygote  : v2
09-09 13:35:53.253  7338  7338 I libpersona: KNOX_SDCARD checking this for 1000
09-09 13:35:53.253  7338  7338 I libpersona: KNOX_SDCARD not a persona
,09-09 13:35:53.253  7338  7338 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:35:53.253  1015  1040 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7338 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-09 13:35:53.253  7338  7338 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 13:35:53.263  7338  7338 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:35:53.263  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:53.263  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:53.263  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:53.263  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:53.263  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:53.263  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:53.263  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:53.263  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:35:53.273  6731  6731 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:35:53.273   307   307 I art     : Explicit concurrent mark sweep GC freed 8684(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 610us total 22.160ms
,09-09 13:35:53.283  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:53.283  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:53.283  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:53.283  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:53.283  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:53.283  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:53.283  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:53.283  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:35:53.283  6731  6731 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:35:53.283  7338  7338 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:35:53.283  7338  7338 D ActivityThread: Added TimaKeyStore provider
,09-09 13:35:53.293   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 599us total 16.745ms
,09-09 13:35:53.313   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 614us total 16.893ms
,09-09 13:35:53.323  7338  7338 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
09-09 13:35:53.323  7338  7338 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-09 13:35:53.323  7338  7338 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-09 13:35:53.463  1015  1028 I art     : Explicit concurrent mark sweep GC freed 91241(5MB) AllocSpace objects, 8(176KB) LOS objects, 33% free, 24MB/37MB, paused 2.462ms total 160.200ms
,09-09 13:35:53.463  1015  1028 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-09 13:35:53.463  1015  1028 D SecContentProvider2: mCursor = null
,09-09 13:35:53.473  7338  7338 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-09 13:35:53.473  7338  7338 I PCWCLIENTTRACE_PushUtil: sales region : global
,09-09 13:35:53.473  7338  7338 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-09 13:35:53.473  7338  7338 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:35:53.473  1015  1569 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
,09-09 13:35:53.473  1015  1569 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,09-09 13:35:53.473  1015  1569 I ActivityManager: Killing 7000:com.samsung.android.sconnect/u0a121 (adj 15): empty #21
,09-09 13:35:53.493  1015  1539 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,09-09 13:35:53.493  1015  1539 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,09-09 13:35:53.493  1015  1539 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:53.493  1015  1539 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:53.493  1015  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,09-09 13:35:53.503  1788  1788 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-09 13:35:53.503  1015  1040 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.samsung.android.sconnect/com.samsung.android.sconnect.periph.PeriphStartReceiver}
09-09 13:35:53.503  1015  1040 W BroadcastQueue: android.os.DeadObjectException
09-09 13:35:53.503  1015  1040 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-09 13:35:53.503  1015  1040 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
09-09 13:35:53.503  1015  1040 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
09-09 13:35:53.503  1015  1040 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
09-09 13:35:53.503  1015  1040 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
09-09 13:35:53.503  1015  1040 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:195)
09-09 13:35:53.503  1015  1040 W BroadcastQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:35:53.503  1015  1040 W BroadcastQueue: 	at android.os.Looper.loop(Looper.java:145)
09-09 13:35:53.503  1015  1040 W BroadcastQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 13:35:53.503  1015  1040 W BroadcastQueue: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-09 13:35:53.503  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-09 13:35:53.503  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:53.503  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:53.503  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:53.503  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:53.523  7354  7354 E Zygote  : MountEmulatedStorage()
09-09 13:35:53.523  7354  7354 I libpersona: KNOX_SDCARD checking this for 10121
09-09 13:35:53.523  7354  7354 E Zygote  : v2
09-09 13:35:53.523  7354  7354 I libpersona: KNOX_SDCARD not a persona
,09-09 13:35:53.523  7354  7354 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:35:53.523  7354  7354 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 13:35:53.523  1015  1040 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7354 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
09-09 13:35:53.523  7354  7354 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:35:53.533  7090  7090 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE,
09-09 13:35:53.533  1015  3173 W ActivityManager: Spurious death for ProcessRecord{20494f25 7354:com.samsung.android.sconnect/u0a121}, curProc for 7000: null
09-09 13:35:53.533  7090  7090 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-09 13:35:53.533  7090  7090 I DIAGMON_AGENT: ./extraInfo: "NG700"
09-09 13:35:53.533  7090  7090 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,09-09 13:35:53.543  2485  2495 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,09-09 13:35:53.553  7354  7354 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:35:53.553  7354  7354 D ActivityThread: Added TimaKeyStore provider
,09-09 13:35:53.563  1788  1788 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,09-09 13:35:53.563  1788  1788 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
09-09 13:35:53.563  1788  1788 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
09-09 13:35:53.563  1788  1788 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-09 13:35:53.563  1788  1788 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-09 13:35:53.573  1788  1788 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,09-09 13:35:53.573  2777  7371 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,09-09 13:35:53.573  2777  7371 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,09-09 13:35:53.573  2777  7371 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-09 13:35:53.583  7078  7078 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,09-09 13:35:53.583  7354  7354 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 13:35:53.583  7354  7354 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-09 13:35:53.583  7354  7354 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-09 13:35:53.593  1015  3173 D ActivityManager: startService callerProcessName:com.android.chrome, calleePkgName: com.android.chrome
09-09 13:35:53.593  1015  3173 D ActivityManager: retrieveServiceLocked(): component = com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService; callingUser = 0; userId(target) = 0
,09-09 13:35:53.593  7112  7112 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,09-09 13:35:53.593  7112  7112 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
09-09 13:35:53.593  7112  7112 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
09-09 13:35:53.593  1015  3173 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:53.593  1015  3173 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
09-09 13:35:53.593  1015  3173 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.chrome, destAppInfo.processName = com.android.chrome
,09-09 13:35:53.593  1015  7302 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-09 13:35:53.593  1015  1039 W libprocessgroup: failed to open /acct/uid_10121/pid_7000/cgroup.procs: No such file or directory
,09-09 13:35:53.603  7112  7112 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-09 13:35:53.603  7112  7112 I SA      : [OR] == isSIMCardReady false ==
,09-09 13:35:53.603  7112  7112 I SA      : [SCU] == networkStateCheck == true
,09-09 13:35:53.603  7354  7354 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:35:53.613  1015  3173 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
09-09 13:35:53.613  1015  3173 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-09 13:35:53.613  7354  7354 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,09-09 13:35:53.613  1015  3173 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:53.613  1015  3173 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:53.613  1015  3173 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-09 13:35:53.623  7112  7112 I SA      : [DM] getCountryCodeFromCSC : PL
09-09 13:35:53.623  7112  7112 I SA      : isChinaCountryCode : false
09-09 13:35:53.623  7112  7112 I SA      : [SCU] is ChinestModel Data Restricted   : false
09-09 13:35:53.623  7112  7112 I SA      : [OR] == networkStateCheck true ==
,09-09 13:35:53.623  2777  7371 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,09-09 13:35:53.623  2777  7371 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,09-09 13:35:53.623  2777  7371 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,09-09 13:35:53.633  2777  7371 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,09-09 13:35:53.633  7354  7354 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-09 13:35:53.633  2777  7371 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,09-09 13:35:53.633  2777  7371 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,09-09 13:35:53.633  2777  7371 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,09-09 13:35:53.633  7112  7112 I SA      : [OR] GetMyCountryZoneTask
,09-09 13:35:53.633  7112  7112 I SA      : [OR] onReceive END
09-09 13:35:53.633  2777  7371 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,09-09 13:35:53.643  1015  3363 D SSRM:n  : SIOP:: AP = 340
,09-09 13:35:53.643  1015  1569 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 13:35:53.643  6911  7374 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
09-09 13:35:53.643  6911  7374 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-09 13:35:53.643  6911  7374 I System.out: (HTTPLog)-Static: isShipBuild true
09-09 13:35:53.643  6911  7374 I System.out: (HTTPLog)-Thread-1246-827766377: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
09-09 13:35:53.643  6911  7374 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:35:53.643  1015  1539 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 13:35:53.643  1015  7302 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 11:35:53 GMT], X-Android-Received-Millis=[1473420953663], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473420953632]}
,09-09 13:35:53.643  1015  1126 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 503]
09-09 13:35:53.643  1015  7302 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-09 13:35:53.643  1015  1126 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
09-09 13:35:53.643  1015  7302 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-09 13:35:53.643  1015  1126 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
09-09 13:35:53.643  1015  1126 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
09-09 13:35:53.663  1015  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-09 13:35:53.663  1177  1602 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-09 13:35:53.663   280  1009 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-09 13:35:53.663   280  1009 D Netd    : getNetworkForDns: using netid 503 for uid 10102
,09-09 13:35:53.663  4748  6795 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-09 13:35:53.663  2777  7371 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,09-09 13:35:53.663  1221  1221 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:35:53.663  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
09-09 13:35:53.663  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-09 13:35:53.663  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-09 13:35:53.663  1177  1177 D StatusBar.NetworkController: updateDataNetType()
09-09 13:35:53.663  1177  1177 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-09 13:35:53.663  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-09 13:35:53.663  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-09 13:35:53.663  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,09-09 13:35:53.663  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-09 13:35:53.663  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:35:53.663  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-09 13:35:53.663  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:53.663  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:53.663  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:53.663  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:53.663  1015  1028 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
09-09 13:35:53.663  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,09-09 13:35:53.673  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:53.673  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:53.673  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
09-09 13:35:53.673  7112  7376 I SA      : [SRS] prepareGetMyCountryZone
,09-09 13:35:53.673  7112  7376 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,09-09 13:35:53.673  7112  7376 I SA      : [SSP] query invoked
,09-09 13:35:53.683  7112  7376 I SA      : [TPMU] GetMccFromDB : null
,09-09 13:35:53.683  1015  1539 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
09-09 13:35:53.683  1015  1539 D SecContentProvider2: mCursor = null
,09-09 13:35:53.693  7112  7376 I SA      : [SCU] getMccFromPreferece mcc = 260
09-09 13:35:53.693  7112  7376 I SA      : [LBE] isSupportCheckDomainRegion : false
,09-09 13:35:53.693  7112  7376 I SA      : [TPM] isNoProxy(default) : true
,09-09 13:35:53.693  2777  7371 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,09-09 13:35:53.693  6911  7374 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-09 13:35:53.703  1015  1126 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,09-09 13:35:53.713  7112  7376 E File    : fail readDirectory() errno=2
,09-09 13:35:53.723  7190  7190 D WaitQueueForNetworkActivate: notifyNetworkActivated
,09-09 13:35:53.743  7152  7152 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,09-09 13:35:53.753  7152  7152 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
09-09 13:35:53.753  6911  7374 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-09 13:35:53.753  7152  7152 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,09-09 13:35:53.753  7152  7152 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,09-09 13:35:53.763  2922  2922 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Sep 09 13:35:53 GMT+02:00 2016
,09-09 13:35:53.763  1015  1486 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-09 13:35:53.763  1015  1486 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-09 13:35:53.763  1015  1486 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:53.763  1015  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:53.763  1015  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-09 13:35:53.773  2922  2922 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-09 13:35:53.773  2922  2922 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-09 13:35:53.773  2922  2922 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-09 13:35:53.783  2922  2922 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-09 13:35:53.783  2922  7385 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-09 13:35:53.783  2922  7385 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-09 13:35:53.783  2922  7385 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,09-09 13:35:53.793  2922  7385 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().START
,09-09 13:35:53.793  2922  7385 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().START 
,09-09 13:35:53.803  2922  7385 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().END 
,09-09 13:35:53.803  2922  7385 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,09-09 13:35:53.803  2922  2922 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-09 13:35:53.903   325   325 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 13:35:53.963  1015  1027 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,09-09 13:35:53.963  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,09-09 13:35:53.963  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:53.963  1015  1027 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-09 13:35:53.963  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,09-09 13:35:53.973  1015  1533 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 13:35:53.973  1015  1533 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-09 13:35:53.973  1015  1533 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:53.973  1015  1533 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:53.973  1015  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:53.983   280  1009 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-09 13:35:53.983   280  1009 D Netd    : getNetworkForDns: using netid 503 for uid 10011
09-09 13:35:53.983  4748  4748 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-09 13:35:53.983  7190  7190 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,09-09 13:35:53.983  7190  7190 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,09-09 13:35:53.983  7190  7190 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,09-09 13:35:53.983  7190  7190 D InitializeManagerStateMachine: exit::IDLE
09-09 13:35:53.983  7190  7190 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,09-09 13:35:53.993  7190  7190 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
09-09 13:35:53.993  7190  7190 D InitializeManagerStateMachine: exit::NETWORK_CHECK
09-09 13:35:53.993  7190  7190 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
09-09 13:35:53.993  7190  7190 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
09-09 13:35:53.993  7190  7190 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
09-09 13:35:53.993  7190  7190 D InitializeManagerStateMachine: entry::SUCCESS
09-09 13:35:53.993  7190  7190 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,09-09 13:35:53.993  4748  7207 I iu.UploadsManager: num queued entries: 0
09-09 13:35:53.993  7190  7190 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
09-09 13:35:53.993  7190  7190 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,09-09 13:35:53.993  4748  7207 I iu.UploadsManager: num updated entries: 0
,09-09 13:35:53.993  4748  7207 I iu.SyncManager: NEXT; no task
,09-09 13:35:54.003  7190  7190 D InitializeManagerStateMachine: exit::SUCCESS
09-09 13:35:54.003  7190  7190 D InitializeManagerStateMachine: entry::IDLE
,09-09 13:35:54.013  1015  1323 I ActivityManager: Killing 7174:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,09-09 13:35:54.023  1015  1132 I splitIntent: Queue : backgroundsplit_2 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,09-09 13:35:54.123  1963  7387 I qtaguid : Tagging socket 47 with tag 1000040700000000{268436487,0} for uid -1, pid: 1963, getuid(): 10011
,09-09 13:35:54.163  7112  7376 I SA      : [RC New] Execute method=[GET] start
,09-09 13:35:54.203  7112  7376 I SA      : [RC New] Security=[true]
,09-09 13:35:54.203  7112  7376 I System.out: Thread-1296(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,09-09 13:35:54.213  7112  7376 I System.out: Thread-1296(ApacheHTTPLog):isSBSettingEnabled false
,09-09 13:35:54.213  7112  7376 I System.out: Thread-1296(ApacheHTTPLog):isShipBuild true
,09-09 13:35:54.213  7112  7376 I System.out: Thread-1296(ApacheHTTPLog):SMARTBONDING_ENABLED is false
09-09 13:35:54.213  7112  7376 I System.out: Thread-1296(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,09-09 13:35:54.213   280  1009 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-09 13:35:54.213   280  1009 D Netd    : getNetworkForDns: using netid 503 for uid 10036
,09-09 13:35:54.303  1015  1040 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:54.303  1015  1040 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 13:35:54.303  1015  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,09-09 13:35:54.313  1015  2021 V SAMP_SPCM_test: CSC File load.. 
,09-09 13:35:54.343  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
09-09 13:35:54.343  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
09-09 13:35:54.343  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
09-09 13:35:54.343  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
09-09 13:35:54.343  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
09-09 13:35:54.343  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
09-09 13:35:54.343  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
09-09 13:35:54.343  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
09-09 13:35:54.343  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
09-09 13:35:54.343  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
09-09 13:35:54.343  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
09-09 13:35:54.343  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
09-09 13:35:54.343  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
09-09 13:35:54.343  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
09-09 13:35:54.343  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
09-09 13:35:54.343  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
09-09 13:35:54.343  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
09-09 13:35:54.343  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
09-09 13:35:54.343  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
09-09 13:35:54.343  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
09-09 13:35:54.343  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,09-09 13:35:54.383  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,09-09 13:35:54.383  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
,09-09 13:35:54.383  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
,09-09 13:35:54.383  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
09-09 13:35:54.383  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
09-09 13:35:54.383  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
,09-09 13:35:54.383  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
09-09 13:35:54.383  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
,09-09 13:35:54.383  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
09-09 13:35:54.383  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
,09-09 13:35:54.383  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
09-09 13:35:54.383  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
,09-09 13:35:54.383  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
09-09 13:35:54.383  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
,09-09 13:35:54.383  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
,09-09 13:35:54.393  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
09-09 13:35:54.393  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
,09-09 13:35:54.393  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
09-09 13:35:54.393  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
,09-09 13:35:54.393  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
09-09 13:35:54.393  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,09-09 13:35:54.403  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
,09-09 13:35:54.403  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
,09-09 13:35:54.403  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
09-09 13:35:54.403  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
,09-09 13:35:54.403  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
09-09 13:35:54.403  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
09-09 13:35:54.403  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
09-09 13:35:54.403  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
09-09 13:35:54.403  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
09-09 13:35:54.403  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
09-09 13:35:54.403  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
09-09 13:35:54.403  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
09-09 13:35:54.403  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
09-09 13:35:54.403  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
09-09 13:35:54.403  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
09-09 13:35:54.403  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
09-09 13:35:54.403  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
09-09 13:35:54.403  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
09-09 13:35:54.403  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
09-09 13:35:54.403  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
09-09 13:35:54.403  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
09-09 13:35:54.403  1015  2021 W DeviceAdminInfo: Unknow,n tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
09-09 13:35:54.403  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
09-09 13:35:54.403  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
09-09 13:35:54.403  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
09-09 13:35:54.403  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
09-09 13:35:54.403  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
09-09 13:35:54.403  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
09-09 13:35:54.403  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
09-09 13:35:54.403  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
09-09 13:35:54.403  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
09-09 13:35:54.403  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
09-09 13:35:54.403  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
09-09 13:35:54.403  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
09-09 13:35:54.403  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
09-09 13:35:54.403  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
09-09 13:35:54.403  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
09-09 13:35:54.403  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
09-09 13:35:54.403  1015  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,09-09 13:35:54.413  1015  2021 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
,09-09 13:35:54.413  1015  2021 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:54.413  1015  2021 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:54.413  1015  2021 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:54.413  1015  2021 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:54.423  7392  7392 E Zygote  : MountEmulatedStorage(),
09-09 13:35:54.423  7392  7392 I libpersona: KNOX_SDCARD checking this for 1000
09-09 13:35:54.423  7392  7392 E Zygote  : v2
09-09 13:35:54.423  7392  7392 I libpersona: KNOX_SDCARD not a persona
,09-09 13:35:54.423  7392  7392 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-09 13:35:54.433  1015  2021 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=7392 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-09 13:35:54.433  7392  7392 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 13:35:54.433  7392  7392 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:35:54.453  7392  7392 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:35:54.463  7392  7392 D ActivityThread: Added TimaKeyStore provider
,09-09 13:35:54.473  7392  7392 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-09 13:35:54.503  1015  1015 I ActivityManager: Killing 6542:com.samsung.android.securitylogagent/1000 (adj 15): empty #21
,09-09 13:35:54.503  1015  2021 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,09-09 13:35:54.883   290   290 E SMD     : DCD OFF,
,09-09 13:35:54.883  7112  7376 I SA      : [RC New] [v2liruge] api execute + 678
,09-09 13:35:54.883  7112  7376 I SA      : [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,09-09 13:35:54.883  7112  7376 I System.out: AsyncTask #1 calls detatch()
,09-09 13:35:54.893  7112  7376 I SA      : [ODM] saveOpenData( GEO_IP, PL ),
,09-09 13:35:54.903  7112  7376 I SA      : [OCP] update openData : PL,
09-09 13:35:54.903   325   325 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 13:35:54.903  7112  7376 I SA      : [TPMU] getNetworkMcc : ,
,09-09 13:35:54.913  7112  7376 I SA      : [SCU] saveMccToPreferece Start
,09-09 13:35:54.913  7112  7376 I SA      : [SCU] RegionMCC : 260
,09-09 13:35:54.913  7112  7376 I SA      : [SSP] query invoked
,09-09 13:35:54.913  7112  7376 I SA      : [TPMU] GetMccFromDB : null
,09-09 13:35:54.913  7112  7376 I SA      : [SCU] getMccFromPreferece mcc = 260
,09-09 13:35:54.913  7112  7376 I SA      : [SCU] saveMccToPreferece End
,09-09 13:35:54.923  7112  7376 I SA      : [RC New] executeRequest [v2liruge] end. 752
,09-09 13:35:54.923  7112  7376 I SA      : [RC New] Execute end
09-09 13:35:54.923  7112  7112 I SA      : [OR] GetMyCountryZoneTask mcc = 260
09-09 13:35:54.923  7112  7112 I SA      : [OR] GetMyCountryZoneTask Success
,09-09 13:35:55.073  6731  7301 E io.jxcore.node.ConnectivityMonitorTest: BT state didn't change after 5s!
,09-09 13:35:55.073  6731  6786 D BluetoothAdapter: disable()
,09-09 13:35:55.073  1015  3173 D SettingsProvider: name = bluetooth_on
,09-09 13:35:55.083  3179  3271 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF,
09-09 13:35:55.083  3179  3271 D BluetoothAdapterProperties: Setting state to 13
09-09 13:35:55.083  3179  3271 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-09 13:35:55.083  3179  3271 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-09 13:35:55.083  3179  3271 D BluetoothAdapterService: updateAdapterState state is 13
,09-09 13:35:55.093  1015  1569 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:35:55.093  1015  1569 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-09 13:35:55.093  1015  1569 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:55.093  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:55.093  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:55.093  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:35:55.093  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:35:55.093  6731  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@354a7d4d removed from the list
09-09 13:35:55.093  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:55.093  6731  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19730002 removed from the list
09-09 13:35:55.093  6731  6786 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:55.093  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:55.093  1015  1569 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:55.093  1015  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:55.093  3179  3271 D BluetoothAdapterService: Autoconnection is available 
,09-09 13:35:55.093  3179  3271 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
,09-09 13:35:55.093  3179  3271 D BluetoothAdapterService: terminating service from this receiver
,09-09 13:35:55.103  1015  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-09 13:35:55.103  3179  3179 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-09 13:35:55.103  3179  3179 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3440599e, channel: 19, state: LISTENING
,09-09 13:35:55.103  3179  3179 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3440599e, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@11d5c9a1, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@8e87c7fmSocket: android.net.LocalSocket@2a25e44c impl:android.net.LocalSocketImpl@1c798c95 fd:FileDescriptor[74],
09-09 13:35:55.103  3179  3179 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2a25e44c impl:android.net.LocalSocketImpl@1c798c95 fd:FileDescriptor[74],
,09-09 13:35:55.103  1015  1477 W ActivityManager: userId = 0, bbcId = -10000,
09-09 13:35:55.103  1015  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 13:35:55.103  1015  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
,09-09 13:35:55.103  3179  3271 D BluetoothAdapterProperties: onBluetoothDisable(),
09-09 13:35:55.103  3179  3271 D BluetoothAdapterProperties: mDiscovering is false
,09-09 13:35:55.113  1015  1323 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-09 13:35:55.113  3179  3271 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-09 13:35:55.113  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:35:55.113  1015  1015 I InputMethodManagerService: [BT Setting State] State =13
,09-09 13:35:55.123  6731  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:35:55.123  6731  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d570905 added. We now have 3 listener(s)
,09-09 13:35:55.123  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,09-09 13:35:55.123  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-09 13:35:55.133  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:35:55.133  1177  1177 D BluetoothTile:  getBluetoothState : 13
,09-09 13:35:55.133  1177  1607 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 13:35:55.133  1177  1607 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 13:35:55.133  2026  2026 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-09 13:35:55.133  1015  1539 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 13:35:55.133  1015  1477 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-09 13:35:55.133  1177  1607 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-09 13:35:55.133  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 13:35:55.143  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-09 13:35:55.143  6731  6731 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:35:55.143  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:55.143  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:55.143  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:55.143  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:55.143  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:35:55.143  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:55.143  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:55.143  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:35:55.153  1015  1323 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 13:35:55.153  1015  1323 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0,
,09-09 13:35:55.153  6731  6731 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:35:55.153  6731  6731 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:55.153  3179  3275 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-09 13:35:55.153  3179  3275 D BluetoothAdapterProperties: Scan Mode:20
,09-09 13:35:55.153  1015  1323 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:55.153  1015  1323 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:55.153  1015  1323 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:55.163  3179  3271 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-09 13:35:55.163  3179  3271 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,09-09 13:35:55.163  3179  3271 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,09-09 13:35:55.163  3179  3271 E bt-btif : cmd socket is not created
09-09 13:35:55.163  3179  3298 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
09-09 13:35:55.163  3179  3298 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-09 13:35:55.163  6731  6731 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:35:55.163  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:55.163  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:55.163  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:55.163  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:55.163  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:35:55.163  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:55.163  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:55.163  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:35:55.163  3179  5212 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 13:35:55.163  3179  3271 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-09 13:35:55.163  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-09 13:35:55.163  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:35:55.163  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:35:55.163  6731  6731 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:35:55.163  6731  6731 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:55.163  6731  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:35:55.163  6731  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21ac8d5a added. We now have 3 listener(s)
09-09 13:35:55.163  6731  6786 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:35:55.163  3179  3298 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 13:35:55.163  3179  3298 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 13:35:55.163  3179  3298 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-09 13:35:55.163  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:35:55.173  6889  6889 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 13:35:55.173  1015  1376 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-09 13:35:55.173  1015  1376 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-09 13:35:55.173  1015  1376 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:55.173  1015  1376 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:55.173  1015  1376 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-09 13:35:55.173  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:55.183  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:35:55.183  3179  3179 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@38d471aa, channel: 5, state: LISTENING
09-09 13:35:55.183  3179  3179 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@38d471aa, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@efc17c6, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@92619bmSocket: android.net.LocalSocket@30f2f938 impl:android.net.LocalSocketImpl@18b35d11 fd:FileDescriptor[76]
09-09 13:35:55.183  3179  3179 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@30f2f938 impl:android.net.LocalSocketImpl@18b35d11 fd:FileDescriptor[76]
,09-09 13:35:55.183  3179  3179 I BtOppRfcommListener: stopping Accept Thread
09-09 13:35:55.183  3179  3179 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@36dffe76, channel: 12, state: LISTENING
09-09 13:35:55.183  3179  3179 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@36dffe76, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@218e8620, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@222b7c77mSocket: android.net.LocalSocket@77a70e4 impl:android.net.LocalSocketImpl@31dfb94d fd:FileDescriptor[79]
09-09 13:35:55.183  3179  3179 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@77a70e4 impl:android.net.LocalSocketImpl@31dfb94d fd:FileDescriptor[79]
,09-09 13:35:55.183  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:55.183  3179  5212 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-09 13:35:55.183  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:35:55.183  6731  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:55.183  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:55.183  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:55.183  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:55.183  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:35:55.183  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:55.183  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:55.183  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:35:55.193  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:35:55.193  6731  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:55.193  6731  6786 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:35:55.193  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:55.193  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:55.193  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:35:55.193  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 13:35:55.193  6731  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d570905 removed from the list
09-09 13:35:55.193  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:55.193  3179  3179 V BluetoothOppManager: cleanUp...
09-09 13:35:55.193  6731  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21ac8d5a removed from the list
,09-09 13:35:55.193  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:55.193  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:55.193  6731  6786 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:55.193  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:55.203  6731  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:35:55.203  6731  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@179e3468 added. We now have 3 listener(s)
,09-09 13:35:55.203  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-09 13:35:55.203  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 13:35:55.203  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 13:35:55.213  6731  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:35:55.213  6731  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c43081 added. We now have 3 listener(s)
09-09 13:35:55.213  6731  6786 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:35:55.213  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:35:55.213  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:35:55.213  1015  1533 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-09 13:35:55.213  1015  1533 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-09 13:35:55.213  1015  1533 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:55.213  1015  1533 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:55.213  1015  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:55.213  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:35:55.213  6731  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:55.213  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:55.213  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:55.213  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:55.213  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:35:55.213  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:55.213  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:55.213  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:35:55.223  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:35:55.223  6731  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:55.223  6731  6786 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:35:55.223  6731  6786 D BluetoothAdapter: disable()
09-09 13:35:55.223  6889  6889 D LocalBluetoothProfileManager: PANU : true
,09-09 13:35:55.223  1015  1028 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,09-09 13:35:55.223  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:55.223  6889  6889 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,09-09 13:35:55.223  1015  1571 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,09-09 13:35:55.223  1015  1571 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-09 13:35:55.233  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:55.233  1015  1571 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:55.233  1015  1571 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:55.233  1015  1571 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:55.233  6889  6889 D Bluetoothsap: bindService called to Bluetooth SAP Service
09-09 13:35:55.233  6889  6889 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-09 13:35:55.233  6731  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:55.233  6731  6786 D BluetoothAdapter: enable()
,09-09 13:35:55.243  1015  1571 W ActivityManager: Permission Denial: getCurrentUser() from pid=6731, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,09-09 13:35:55.243  1015  1571 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-09 13:35:55.243  1015  1571 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6731, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-09 13:35:55.243  1015  1571 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-09 13:35:55.243  1015  1571 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
09-09 13:35:55.243  1015  1571 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-09 13:35:55.243  1015  1571 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-09 13:35:55.243  1015  1571 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-09 13:35:55.243  1015  1571 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-09 13:35:55.243  1015  1571 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-09 13:35:55.243  1015  1571 D SettingsProvider: name = bluetooth_on
,09-09 13:35:55.253  6889  6889 D DockEventReceiver: finishStartingService: stopping service
,09-09 13:35:55.253  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-09 13:35:55.253  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-09 13:35:55.253  1015  1044 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-09 13:35:55.253  3179  3271 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = USER_TURN_ON, isTurningOn=false, isTurningOff=true
09-09 13:35:55.253  3179  3271 I BluetoothAdapterState: CURRENT_STATE=PENDING: Deferring request USER_TURN_ON
,09-09 13:35:55.253  6889  6889 D BluetoothNotiBroadcastReceiver: onReceive
,09-09 13:35:55.253  6889  6889 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 13:35:55.253  6889  6889 D PanProfile: Bluetooth service connected
,09-09 13:35:55.253  6889  6889 D Bluetoothsap: BluetoothSAP Proxy object connected
09-09 13:35:55.253  6889  6889 D SapProfile: Bluetooth service connected
09-09 13:35:55.263  6889  6889 D Bluetoothsap: getConnectedDevices()
,09-09 13:35:55.263  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:35:55.263  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-09 13:35:55.263  1015  1323 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-09 13:35:55.263  1015  1323 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:55.263  1015  1323 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:55.263  1015  1323 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:55.263  1015  1323 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:55.283  7420  7420 E Zygote  : MountEmulatedStorage(),
09-09 13:35:55.283  7420  7420 E Zygote  : v2
09-09 13:35:55.283  7420  7420 I libpersona: KNOX_SDCARD checking this for 10055,
09-09 13:35:55.283  7420  7420 I libpersona: KNOX_SDCARD not a persona
,09-09 13:35:55.283  7420  7420 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:35:55.283  7420  7420 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-09 13:35:55.283  1015  1323 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7420 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
09-09 13:35:55.283  7420  7420 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:35:55.303  7420  7420 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:35:55.303  7420  7420 D ActivityThread: Added TimaKeyStore provider
,09-09 13:35:55.333  7420  7420 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-09 13:35:55.363  7420  7420 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,09-09 13:35:55.363  7420  7420 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-09 13:35:55.363  7420  7420 D UserAnalysis: Create SecureDbHelper
,09-09 13:35:55.363  3179  3298 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-09 13:35:55.363  3179  3298 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 13:35:55.363  3179  3298 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 13:35:55.363  3179  3298 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-09 13:35:55.363  3179  3298 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 13:35:55.363  3179  3298 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 13:35:55.363  3179  3298 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-09 13:35:55.363  3179  3358 I bt_userial_mct: exiting userial_read_thread
09-09 13:35:55.363  3179  3298 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 13:35:55.363  3179  3298 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 13:35:55.363  3179  3298 W bt-btif : ag scb idx 1 not allocated
09-09 13:35:55.363  3179  3298 W bt-btif : ag scb idx 2 not allocated
09-09 13:35:55.363  3179  3298 E bt-btif : BTA AG is already disabled, ignoring ...
,09-09 13:35:55.373  3179  3358 D bt_userial_mct: Leaving userial_evt_read_thread()
,09-09 13:35:55.373  3179  3275 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
,09-09 13:35:55.373  3179  3300 I bt_vendor: hw_epilog_process
,09-09 13:35:55.373  3179  3275 D bt_userial_mct: userial_close
09-09 13:35:55.373  3179  3275 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-09 13:35:55.373  7420  7420 D IntelligenceServiceApplication: onCreate()
,09-09 13:35:55.373  1015  1569 I ActivityManager: Killing 7286:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,09-09 13:35:55.383  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-09 13:35:55.383  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-09 13:35:55.383  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:55.383  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:55.383  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:55.393  7420  7420 D IntelligenceServiceApplication: no applications having user consent for prediction
,09-09 13:35:55.393  7437  7437 E Zygote  : MountEmulatedStorage(),
09-09 13:35:55.393  7437  7437 I libpersona: KNOX_SDCARD checking this for 10105
09-09 13:35:55.393  7437  7437 E Zygote  : v2
,09-09 13:35:55.393  7437  7437 I libpersona: KNOX_SDCARD not a persona
09-09 13:35:55.403  7437  7437 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:35:55.403  7437  7437 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-09 13:35:55.403  7437  7437 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
09-09 13:35:55.403  1015  1028 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7437 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
09-09 13:35:55.403  1015  1571 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-09 13:35:55.403  7420  7420 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.,
,09-09 13:35:55.413  7420  7420 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-09 13:35:55.423  7437  7437 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:35:55.423  7437  7437 D ActivityThread: Added TimaKeyStore provider
,09-09 13:35:55.543   256   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-09 13:35:55.543   256   531 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:35:55.543  7437  7456 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-09 13:35:55.543   256   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-09 13:35:55.543   256   531 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:35:55.543  7437  7456 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-09 13:35:55.653  1015  1146 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.
,09-09 13:35:55.683  3179  3275 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,09-09 13:35:55.683  3179  3275 I bt_vendor: bluetooth satus is on
09-09 13:35:55.683  3179  3275 I bt_vendor: bt-vendor : resetting BT status
09-09 13:35:55.683  3179  3275 I bt_vendor: Starting hciattach daemon
,09-09 13:35:55.683  3179  3275 I bt_vendor: try to set false
,09-09 13:35:55.683  3179  3275 I bt_vendor: Starting hciattach daemon
,09-09 13:35:55.683  3179  3275 I bt_vendor: try to set false
,09-09 13:35:55.683  3179  3275 I bt_vendor: cleanup
,09-09 13:35:55.683  3179  3298 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-09 13:35:55.683  3179  3275 I GKI_LINUX: GKI_exit_task 0 done
09-09 13:35:55.683  3179  3275 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,09-09 13:35:55.683  3179  3271 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,09-09 13:35:55.683  3179  3271 D BtConfig.SecureMode: isSecureModeOn:false
,09-09 13:35:55.683  3179  3271 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-09 13:35:55.683  3179  3271 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,09-09 13:35:55.683  3179  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-09 13:35:55.693  3179  3271 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-09 13:35:55.693  1015  1323 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 13:35:55.693  1015  1323 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-09 13:35:55.693  1015  1323 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:55.693  1015  1323 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 13:35:55.693  1015  1323 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:55.693  3179  3271 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-09 13:35:55.693  3179  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-09 13:35:55.693  3179  3271 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-09 13:35:55.693  1015  3173 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 13:35:55.693  1015  3173 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-09 13:35:55.693  1015  3173 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:55.693  1015  3173 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:55.693  1015  3173 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:55.703  3179  3179 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 13:35:55.703  3179  3271 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,09-09 13:35:55.703  3179  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-09 13:35:55.703  3179  3179 D BtGatt.GattService: Received stop request...Stopping profile...
,09-09 13:35:55.703  3179  3179 D BtGatt.GattService: stop()
,09-09 13:35:55.703  3179  3179 D BtGatt.AdvertiseManager: advertise clients cleared
,09-09 13:35:55.703  3179  3179 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ce19ede,
,09-09 13:35:55.703  3179  3179 D HeadsetService: Received stop request...Stopping profile...
,09-09 13:35:55.703  3179  3271 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService,
,09-09 13:35:55.703  1015  3173 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:35:55.703  1015  3173 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 13:35:55.713  3179  3179 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ce19ede,
,09-09 13:35:55.713  1015  3173 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:55.713  1015  3173 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:55.713  1015  3173 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:55.713  7437  7437 D StrictMode: StrictMode policy violation; ~duration=166 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at java.io.File.exists(File.java:363)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 13:35:55.713  7437  7437 D StrictMode: StrictMode policy violation; ~duration=165 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 13:35:55.713  7437  7437 D StrictMode: StrictMode policy violation; ~duration=164 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 13:35:55.713  7437  7437 D StrictMode: StrictMode policy violation; ~duration=163 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.q.e.b(PG:170)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 13:35:55.713  7437  7437 D StrictMode: StrictMode policy violation; ~duration=160 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.q.k.c(PG:18147)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.q.k.d(PG:583)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.q.e.b(PG:170)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 13:35:55.713  7437  7437 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at java.io.File.exists(File.java:363)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 13:35:55.713  7437  7437 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at java.io.File.exists(File.java:363)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 13:35:55.713  7437  7437 D StrictMode: StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at java.io.File.lastModified(File.java:571)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 13:35:55.713  7437  7437 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 13:35:55.713  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-09 13:35:55.713  3179  3271 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-09 13:35:55.713  3179  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 13:35:55.723  3179  3271 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
09-09 13:35:55.723  1015  1028 I ActivityManager: Killing 6968:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #21
09-09 13:35:55.723  1015  1533 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:35:55.723  1015  1533 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-09 13:35:55.723  1963  1963 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
09-09 13:35:55.723  1015  1533 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:55.723  1015  1533 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:55.723  1015  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 13:35:55.723  3179  3271 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-09 13:35:55.723  3179  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-09 13:35:55.723  3179  3271 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
09-09 13:35:55.733  1015  3173 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:35:55.733  1015  3173 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
09-09 13:35:55.733  1015  3173 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:55.733  1015  3173 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:55.733  1015  3173 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 13:35:55.733  3179  3271 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-09 13:35:55.733  3179  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-09 13:35:55.733  3179  3271 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
09-09 13:35:55.733  1963  1963 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
09-09 13:35:55.733  1015  1323 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:35:55.733  1015  1323 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-09 13:35:55.733  1015  1323 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:55.733  1015  1323 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:55.733  1015  1323 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 13:35:55.733  3179  3271 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-09 13:35:55.733  3179  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 13:35:55.733  3179  3271 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
09-09 13:35:55.733  1015  1533 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:35:55.733  1015  1533 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
09-09 13:35:55.743  1015  1533 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:55.743  1015  1533 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:55.743  1015  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 13:35:55.743  3179  3271 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-09 13:35:55.743  3179  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-09 13:35:55.743  3179  3271 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
09-09 13:35:55.743  1015  1539 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:35:55.743  1015  1539 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
09-09 13:35:55.743  1015  1539 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:55.743  1015  1539 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:55.743  1015  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 13:35:55.743  3179  3271 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-09 13:35:55.743  3179  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-09 13:35:55.743  3179  3271 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-09 13:35:55.743  3179  3271 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-09 13:35:55.743  3179  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-09 13:35:55.743  3179  3271 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-09 13:35:55.743  3179  3271 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-09 13:35:55.743  3179  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-09 13:35:55.743  3179  3271 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-09 13:35:55.743  3179  3271 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-09 13:35:55.743  3179  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-09 13:35:55.743  3179  3271 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-09 13:35:55.743  3179  3271 D BluetoothAdapterState: Stopping profile services that were post enabled
09-09 13:35:55.743  3179  3179 E BluetoothAdapterService(1021419230): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
09-09 13:35:55.743  3179  3179 E BluetoothAdapterService(1021419230): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-09 13:35:55.743  3179  3179 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 13:35:55.753  3179  3179 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-09 13:35:55.753  3179  3179 D A2dpService: Received stop request...Stopping profile...
09-09 13:35:55.753  3179  3290 D A2dpStateMachine: Exit Disconnected: -1
,09-09 13:35:55.753  3179  3179 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ce19ede
09-09 13:35:55.753  1015  1015 D BluetoothA2dp: Proxy object disconnected
09-09 13:35:55.753  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-09 13:35:55.763  3179  3179 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-09 13:35:55.763  3179  3179 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 13:35:55.763  3179  3179 D HidService: Received stop request...Stopping profile...
09-09 13:35:55.763  3179  3179 D HidService: Stopping Bluetooth HidService
09-09 13:35:55.763  3179  3179 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-09 13:35:55.763  3179  3179 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-09 13:35:55.763  3179  3179 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-09 13:35:55.763  3179  3179 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ce19ede
09-09 13:35:55.763  3179  3179 D HealthService: Received stop request...Stopping profile...
09-09 13:35:55.763  3179  3179 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ce19ede
09-09 13:35:55.773  3179  3179 D PanService: Received stop request...Stopping profile...
09-09 13:35:55.773  3179  3179 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ce19ede
09-09 13:35:55.773  6889  6889 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 13:35:55.773  6889  6889 D PanProfile: Bluetooth service disconnected
09-09 13:35:55.773  1015  1015 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 13:35:55.773  3179  3179 D BluetoothMapService: Received stop request...Stopping profile...
09-09 13:35:55.773  3179  3179 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ce19ede
09-09 13:35:55.773  3179  3179 D SapService: Received stop request...Stopping profile...
09-09 13:35:55.773  3179  3179 D SapService: Stopping Bluetooth SapService
09-09 13:35:55.773  3179  3179 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ce19ede
09-09 13:35:55.783  3179  3179 E BluetoothAdapterService(1021419230): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-09 13:35:55.783  3179  3179 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 13:35:55.783  3179  3179 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-09 13:35:55.783  3179  3179 D BluetoothA2dp: Proxy object disconnected
09-09 13:35:55.783  3179  3179 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-09 13:35:55.783  3179  3291 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-09 13:35:55.783  6889  6889 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-09 13:35:55.783  6889  6889 D SapProfile: Bluetooth service disconnected
09-09 13:35:55.783  3179  3179 I GKI_LINUX: GKI_exit_task 2 done
09-09 13:35:55.783  3179  3179 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-09 13:35:55.783  3179  3179 E BluetoothAdapterService(1021419230): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-09 13:35:55.783  3179  3179 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 13:35:55.783  3179  3179 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-09 13:35:55.783  3179  3179 E BluetoothAdapterService(1021419230): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-09 13:35:55.783  3179  3179 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 13:35:55.783  3179  3179 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-09 13:35:55.783  3179  3179 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-09 13:35:55.783  3179  3179 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 13:35:55.783  3179  3179 E BluetoothAdapterService(1021419230): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-09 13:35:55.783  3179  3179 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 13:35:55.783  3179  3179 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-09 13:35:55.783  3179  3179 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 13:35:55.783  3179  3179 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-09 13:35:55.783  3179  3179 E BluetoothAdapterService(1021419230): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-09 13:35:55.783  3179  3179 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-09 13:35:55.783  3179  3179 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
09-09 13:35:55.783  3179  3179 E BluetoothAdapterService(1021419230): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-09 13:35:55.783  3179  3179 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-09 13:35:55.783  3179  3179 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
09-09 13:35:55.783  3179  3271 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
09-09 13:35:55.783  3179  3271 D BluetoothAdapterProperties: Setting state to 10
09-09 13:35:55.793  3179  3271 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-09 13:35:55.793  3179  3271 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-09 13:35:55.793  3179  3271 D BluetoothAdapterService: updateAdapterState state is 10
09-09 13:35:55.793  3179  3271 D BluetoothAdapterService: Autoconnection is available 
09-09 13:35:55.793  3179  3271 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-09 13:35:55.793  3179  3271 I BluetoothAdapterState: Entering OffState
09-09 13:35:55.793  6889  6901 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 13:35:55.793  6889  6901 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 13:35:55.793  3179  3271 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
09-09 13:35:55.793  3179  3271 D BluetoothAdapterProperties: Setting state to 11
09-09 13:35:55.793  3179  3271 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-09 13:35:55.793  3179  3271 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-09 13:35:55.793  3179  3271 D BluetoothAdapterService: updateAdapterState state is 11
,09-09 13:35:55.793  3179  3271 D BluetoothAdapterService: Autoconnection is available 
09-09 13:35:55.793  3179  3271 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
09-09 13:35:55.793  3179  3271 D BtConfig.SecureMode: isSecureModeOn:false
,09-09 13:35:55.793  3179  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-09 13:35:55.793  3179  3271 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 10
09-09 13:35:55.793  3179  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-09 13:35:55.793  3179  3271 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
09-09 13:35:55.793  3179  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-09 13:35:55.793  3179  3271 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
09-09 13:35:55.793  3179  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 13:35:55.793  3179  3271 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
09-09 13:35:55.793  3179  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-09 13:35:55.793  3179  3271 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
09-09 13:35:55.793  3179  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-09 13:35:55.793  3179  3271 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
09-09 13:35:55.793  3179  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 13:35:55.793  3179  3271 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
09-09 13:35:55.793  3179  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-09 13:35:55.793  3179  3271 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
09-09 13:35:55.793  3179  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-09 13:35:55.793  3179  3271 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-09 13:35:55.793  3179  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-09 13:35:55.793  3179  3271 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-09 13:35:55.793  3179  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-09 13:35:55.793  3179  3271 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-09 13:35:55.793  3179  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-09 13:35:55.793  3179  3271 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
09-09 13:35:55.793  3179  3271 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-09 13:35:55.793  3179  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-09 13:35:55.793  3179  3271 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
09-09 13:35:55.793  1015  1477 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:35:55.793  1963  2158 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 13:35:55.793  1015  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
09-09 13:35:55.793  1963  2158 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 13:35:55.793  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 13:35:55.793  1015  1044 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 13:35:55.793  1015  1477 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:55.793  1015  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:55.793  1015  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:55.793  3179  3271 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-09 13:35:55.793  6889  6904 D Bluetoothsap: onBluetoothStateChange: up=false
09-09 13:35:55.793  3179  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-09 13:35:55.793  3179  3271 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-09 13:35:55.793  6889  6904 D Bluetoothsap: Unbinding service...
09-09 13:35:55.793  1015  3173 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 13:35:55.793  1015  3173 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-09 13:35:55.803  3179  3179 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 13:35:55.803  7437  7466 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-09 13:35:55.803  3179  3179 D BtGatt.GattService: Received start request. Starting profile...
09-09 13:35:55.803  3179  3179 D BtGatt.GattService: start()
09-09 13:35:55.803  3179  3179 D BtGatt.GattService: start()
09-09 13:35:55.803  3179  3179 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ce19ede
09-09 13:35:55.803  3179  3179 D BtGatt.AdvertiseManager: advertise manager created
,09-09 13:35:55.803  1015  3173 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:55.803  1015  3173 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:55.803  1015  3173 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:55.803  3179  3271 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-09 13:35:55.803  3179  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-09 13:35:55.803  3179  3271 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-09 13:35:55.803  1015  1376 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:35:55.803  1015  1376 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 13:35:55.803  1015  1376 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:55.803  1015  1376 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:55.803  1015  1376 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:55.813  3179  3271 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,09-09 13:35:55.813  3179  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 13:35:55.813  3179  3271 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-09 13:35:55.813  1015  1571 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:35:55.813  1015  1571 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-09 13:35:55.813  1177  1413 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 13:35:55.813  1015  1571 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:55.813  3179  3179 D BtGatt.GattService: mStartError = false
09-09 13:35:55.813  3179  3179 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ce19ede
,09-09 13:35:55.813  1177  1413 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 13:35:55.813  1015  1571 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:55.813  1015  1571 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 13:35:55.813  3179  3179 D HeadsetService: Received start request. Starting profile...
,09-09 13:35:55.813  3179  3179 D HeadsetService: start()
09-09 13:35:55.813  3179  3179 D HeadsetStateMachine: make
09-09 13:35:55.813  3179  3190 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-09 13:35:55.813  3179  3271 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,09-09 13:35:55.813  3179  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-09 13:35:55.813  3179  3271 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
09-09 13:35:55.813  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 13:35:55.813  1015  1477 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:35:55.813  1015  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-09 13:35:55.813  1440  1647 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 13:35:55.813  1440  1647 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 13:35:55.813  1015  1477 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:55.813  1015  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:55.813  1015  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:55.823  3179  3179 E HeadsetStateMachine: # of Max HF connection is 2
,09-09 13:35:55.823  3179  3271 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-09 13:35:55.823  3179  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-09 13:35:55.823  3179  3271 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-09 13:35:55.823  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:35:55.823  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-09 13:35:55.823  6731  6739 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 13:35:55.823  6731  6739 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 13:35:55.823  6731  6739 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-09 13:35:55.823  6731  6739 D BluetoothLeAdvertiser: Exit stop advertising
09-09 13:35:55.823  6731  6739 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-09 13:35:55.823  6731  6739 D BluetoothLeScanner: Exiting stopAllScan
,09-09 13:35:55.823  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:55.823  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:55.823  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:55.823  1015  1570 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:35:55.823  1015  1570 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:55.823  3179  3271 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-09 13:35:55.823  3179  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 13:35:55.823  3179  3271 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-09 13:35:55.833  1015  1570 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:55.833  1015  1570 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
09-09 13:35:55.833  1015  1027 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
09-09 13:35:55.833  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-09 13:35:55.833  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:55.833  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:55.833  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-09 13:35:55.833  1015  1539 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:35:55.833  1015  1539 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-09 13:35:55.833  1015  1539 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:55.833  1015  1539 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:55.833  1015  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:55.833  1015  1477 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
09-09 13:35:55.833  1015  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-09 13:35:55.833  3179  3271 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-09 13:35:55.833  3179  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-09 13:35:55.833  3179  3271 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
09-09 13:35:55.833  1015  1477 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:55.833  1015  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:55.833  1015  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
09-09 13:35:55.833  3179  3179 I bluedroid: get_profile_interface handsfree
09-09 13:35:55.833  1015  3173 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:35:55.833  1015  3173 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-09 13:35:55.843  3179  3280 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 13:35:55.843  3179  3280 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 13:35:55.843  1015  3173 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:55.843  1015  3173 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:55.843  1015  3173 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 13:35:55.843  1430  1443 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 13:35:55.843  1430  1443 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 13:35:55.843  3179  3271 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-09 13:35:55.843  3179  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-09 13:35:55.843  3179  3271 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-09 13:35:55.843  3179  3271 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-09 13:35:55.843  3179  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-09 13:35:55.843  3179  3271 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-09 13:35:55.843  3179  3271 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-09 13:35:55.843  3179  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-09 13:35:55.843  3179  3271 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-09 13:35:55.843  3179  3271 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-09 13:35:55.843  3179  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-09 13:35:55.843  3179  3271 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-09 13:35:55.843  3179  3271 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-09 13:35:55.843  1454  1704 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 13:35:55.843  1454  1704 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 13:35:55.853  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-09 13:35:55.853  1015  1015 I InputMethodManagerService: [BT Setting State] State =10
09-09 13:35:55.853  1015  1015 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-09 13:35:55.853  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-09 13:35:55.853  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:35:55.853  1177  1177 D BluetoothTile:  getBluetoothState : 10
,09-09 13:35:55.863  2026  2026 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-09 13:35:55.863  1015  1569 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 13:35:55.863  1015  1028 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-09 13:35:55.863  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-09 13:35:55.863  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:55.873  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:55.873  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:55.873  6889  6889 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:35:55.873  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:35:55.873  1015  1015 I InputMethodManagerService: [BT Setting State] State =11
,09-09 13:35:55.873  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-09 13:35:55.873  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:35:55.873  1177  1177 D BluetoothTile:  getBluetoothState : 11
,09-09 13:35:55.883  2026  2026 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-09 13:35:55.883  1015  1132 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 13:35:55.883  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:55.883  3179  3179 E DualScoManager: Dual Sco Manager already instantiated
09-09 13:35:55.883  3179  3179 I DualScoManager: Set HeadsetServiceHelper
09-09 13:35:55.883  3179  3179 D BluetoothAtMessage: createCMTIContentObservers
,09-09 13:35:55.883  1015  1027 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
09-09 13:35:55.883  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-09 13:35:55.883  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 13:35:55.883  1015  1027 D SettingsProvider: selectionArgs: false
09-09 13:35:55.883  1015  1027 D SettingsProvider: selectionArgs: 1002
09-09 13:35:55.883  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 13:35:55.883  1015  1027 D SettingsProvider: ret = -1
09-09 13:35:55.883  1015  1477 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 13:35:55.883  1015  1132 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-09 13:35:55.883  1015  1323 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-09 13:35:55.883  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-09 13:35:55.883  3179  7469 D HeadsetStateMachine: Enter Disconnected: -2
,09-09 13:35:55.893  1015  1132 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:55.893  1015  1132 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:55.893  1015  1132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:55.893  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:55.893  1177  1607 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 13:35:55.893  1177  1607 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-09 13:35:55.893  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-09 13:35:55.893  3179  3179 D HeadsetService: mStartError = false
09-09 13:35:55.893  3179  3179 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ce19ede
,09-09 13:35:55.893  1015  1533 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 13:35:55.893  3179  3179 D A2dpService: Received start request. Starting profile...
09-09 13:35:55.893  1015  1533 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
09-09 13:35:55.893  3179  3179 D A2dpService: start()
09-09 13:35:55.893  3179  3179 I bluedroid: get_profile_interface avrcp
09-09 13:35:55.893  3179  7469 D HeadsetStateMachine: Clear mHeadsetBrsf
09-09 13:35:55.893  3179  7469 D HeadsetStateMachine: map size, before remove : 0
09-09 13:35:55.893  3179  7469 D HeadsetStateMachine: map size, after remove: 0
,09-09 13:35:55.893  1015  1533 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:55.893  1015  1533 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:55.893  1015  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:55.903  6889  6889 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:35:55.903  3179  3179 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-09 13:35:55.903  3179  3179 D Avrcp   : Initialize Media Controller
09-09 13:35:55.903  3179  3179 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,09-09 13:35:55.903  3179  3179 E Avrcp   : getActiveSessions
09-09 13:35:55.903  3179  3179 D Avrcp   : pick active media Controller
09-09 13:35:55.903  3179  3179 D Avrcp   : Get the active Media Controller 
,09-09 13:35:55.903   325   325 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-09 13:35:55.903  6889  6889 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 13:35:55.913  3179  3179 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-09 13:35:55.913  3179  3179 D A2dpStateMachine: make
,09-09 13:35:55.913  1015  1376 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-09 13:35:55.913  1015  1376 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-09 13:35:55.913  3179  7472 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
09-09 13:35:55.913  1015  1376 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:55.913  1015  1376 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:55.913  1015  1376 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
09-09 13:35:55.913  3179  3179 I bluedroid: get_profile_interface a2dp
,09-09 13:35:55.913  3179  7475 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-09 13:35:55.913  3179  3179 E bt-btif : warning : media task started media_task_refcnt 1 
,09-09 13:35:55.913  3179  3179 D A2dpService: mStartError = false
09-09 13:35:55.913  3179  3179 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ce19ede
09-09 13:35:55.913  3179  7474 D A2dpStateMachine: Enter Disconnected: -2
09-09 13:35:55.913  3179  3179 E BluetoothAdapterService(1021419230): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,09-09 13:35:55.913  3179  3179 D HidService: Received start request. Starting profile...
09-09 13:35:55.913  3179  3179 D HidService: start()
09-09 13:35:55.913  3179  3179 I bluedroid: get_profile_interface hidhost
09-09 13:35:55.913  3179  3179 D HidService: setHidService(): set to: null
09-09 13:35:55.913  3179  3179 D HidService: mStartError = false
09-09 13:35:55.913  3179  3179 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ce19ede
,09-09 13:35:55.913  3179  3179 D HealthService: Received start request. Starting profile...
09-09 13:35:55.923  3179  3179 D HealthService: start()
,09-09 13:35:55.923  3179  3179 I bluedroid: get_profile_interface health
09-09 13:35:55.923  3179  3179 D HealthService: mStartError = false
09-09 13:35:55.923  3179  3179 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ce19ede
,09-09 13:35:55.923  3179  3179 D PanService: Received start request. Starting profile...
,09-09 13:35:55.923  3179  3179 D PanService: start()
09-09 13:35:55.923  3179  3179 D BluetoothPanServiceJni: initializeNative(L110): pan
09-09 13:35:55.923  3179  3179 I bluedroid: get_profile_interface pan
09-09 13:35:55.923  3179  3179 D PanService: mStartError = false
09-09 13:35:55.923  3179  3179 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ce19ede
09-09 13:35:55.923  3179  3179 D HeadsetStateMachine: Try to query the phonestate on bind
,09-09 13:35:55.923  1430  1443 I Telecom : BluetoothPhoneService: queryPhoneState
,09-09 13:35:55.923  1430  1430 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,09-09 13:35:55.923  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-09 13:35:55.923  1430  1443 I Telecom : BluetoothPhoneService: Result of Message : true
,09-09 13:35:55.933  3179  3179 D BluetoothMapService: Received start request. Starting profile...,
09-09 13:35:55.933  3179  3179 D BluetoothMapService: start()
,09-09 13:35:55.933  6889  6889 D DockEventReceiver: finishStartingService: stopping service
,09-09 13:35:55.933  3179  3179 D BluetoothMapService: mStartError = false
09-09 13:35:55.933  3179  3179 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ce19ede
,09-09 13:35:55.933  3179  3179 D HeadsetStateMachine: Proxy object connected
09-09 13:35:55.933  3179  3179 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-09 13:35:55.933  3179  7469 D HeadsetStateMachine: Disconnected process message: 11
,09-09 13:35:55.933  3179  3179 D SapService: Received start request. Starting profile...
,09-09 13:35:55.933  3179  3179 D SapService: start()
09-09 13:35:55.933  3179  3179 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-09 13:35:55.933  3179  3179 I bluedroid: get_profile_interface sap
09-09 13:35:55.933  3179  3179 D SapService: mStartError = false
09-09 13:35:55.933  3179  3179 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ce19ede
09-09 13:35:55.933  3179  3179 D HeadsetPhoneState: sendDeviceDataStateChanged
09-09 13:35:55.933  3179  3179 D HeadsetPhoneState: Signal level : previous=0 curr=0
09-09 13:35:55.933  3179  3179 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-09 13:35:55.933  3179  3179 E BluetoothAdapterService(1021419230): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-09 13:35:55.933  3179  3179 E BluetoothAdapterService(1021419230): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
,09-09 13:35:55.933  3179  3179 E BluetoothAdapterService(1021419230): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-09 13:35:55.933  3179  3179 E BluetoothAdapterService(1021419230): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-09 13:35:55.933  3179  3179 E BluetoothAdapterService(1021419230): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
09-09 13:35:55.933  3179  7469 D HeadsetStateMachine: Disconnected process message: 18
09-09 13:35:55.933  3179  7469 D HeadsetStateMachine: Disconnected process message: 10
09-09 13:35:55.933  3179  7469 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-09 13:35:55.933  3179  7469 D HeadsetStateMachine: Disconnected process message: 11
,09-09 13:35:55.943  6889  6889 D BluetoothNotiBroadcastReceiver: onReceive
,09-09 13:35:55.943  3179  7472 D BluetoothMediaBrowser: no now playing list
09-09 13:35:55.943  3179  7472 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-09 13:35:55.953  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:35:55.953  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-09 13:35:55.953  3179  3179 E BluetoothAdapterService(1021419230): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
09-09 13:35:55.953  3179  3179 E BluetoothAdapterService(1021419230): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-09 13:35:55.963  3179  3271 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-09 13:35:55.963  3179  3271 I bluedroid: enable
09-09 13:35:55.963  3179  3271 I bt_hci_bdroid: init
,09-09 13:35:55.963  3179  7483 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,09-09 13:35:55.973  3179  3271 I bt_vendor: bt-vendor : init
09-09 13:35:55.973  3179  3271 I bt_vendor: bt-vendor : get_bt_soc_type
09-09 13:35:55.973  3179  3271 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-09 13:35:55.973  3179  3271 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
09-09 13:35:55.973  3179  3271 D bt_userial_mct: userial_init
09-09 13:35:55.973  3179  3271 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-09 13:35:55.973  3179  3271 I bt_vendor: Starting hciattach daemon
09-09 13:35:55.973  3179  3271 I bt_vendor: try to set false
,09-09 13:35:55.973  3179  3271 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-09 13:35:55.973  3179  3271 I bt_vendor: Starting hciattach daemon
09-09 13:35:55.973  3179  3271 I bt_vendor: try to set true
,09-09 13:35:55.983  1963  1963 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-09 13:35:55.983  1015  1570 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 13:35:55.983  1015  1570 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-09 13:35:55.993  1015  1570 W ActivityManager: userId = 0, bbcId = -10000,
,09-09 13:35:55.993  1015  1570 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:55.993  1015  1570 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:55.993  7491  7491 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-09 13:35:55.993  1963  7492 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-09 13:35:56.003  1015  3173 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:35:56.003  1963  1963 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.,
09-09 13:35:56.003  1015  3173 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:56.003  1015  3173 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 13:35:56.003  1015  3173 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:56.023  6889  6889 D BluetoothNotiBroadcastReceiver: onReceive
,09-09 13:35:56.023  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED,
09-09 13:35:56.023  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-09 13:35:56.033  1015  1132 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,09-09 13:35:56.043  1015  1132 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:56.043  1015  1132 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:56.043  1015  1132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:56.043  7498  7498 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,09-09 13:35:56.053  7499  7499 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-09 13:35:56.053  1963  7492 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,09-09 13:35:56.063  1963  1963 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-09 13:35:56.073  1963  1963 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
09-09 13:35:56.073  7501  7501 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-09 13:35:56.073  7502  7502 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,09-09 13:35:56.083  7503  7503 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-09 13:35:56.093  7504  7504 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,09-09 13:35:56.243   257  1152 I SurfaceFlinger: id=14 Removed Uoast (8/9)
,09-09 13:35:56.243   257   451 I SurfaceFlinger: id=14 Removed Uoast (-2/9)
,09-09 13:35:56.243  1015  1486 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1015) eventTime = 144416
,09-09 13:35:56.243  1015  1486 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015 (0x0)
,09-09 13:35:56.253  1015  1486 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1015, ws=WorkSource{10049}) (elapsedTime=3480)
,09-09 13:35:56.283  7304  7304 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
09-09 13:35:56.283  7304  7304 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
,09-09 13:35:56.303  7507  7507 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
,09-09 13:35:56.313  7508  7508 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-09 13:35:56.323  3179  3271 I bt_vendor: bluetooth satus is on,
09-09 13:35:56.323  3179  7487 D bt_userial_mct: userial_open(port:0)
09-09 13:35:56.323  3179  7487 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
09-09 13:35:56.323  3179  7487 I bt_vendor: Done intiailizing UART
,09-09 13:35:56.333  3179  7487 I bt_vendor: Done intiailizing UART
09-09 13:35:56.333  3179  7487 I bt_userial_mct: CMD=73, EVT=73, ACL_Out=74, ACL_In=74
09-09 13:35:56.333  3179  7487 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-09 13:35:56.333  3179  7510 D bt_userial_mct: Entering userial_read_thread()
,09-09 13:35:56.333  3179  7483 E bt-att  : DIS already initalized
,09-09 13:35:56.333  3179  7483 I         : BTE_InitTraceLevels -- TRC_HCI
,09-09 13:35:56.333  3179  7483 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-09 13:35:56.333  3179  7483 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-09 13:35:56.333  3179  7483 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-09 13:35:56.333  3179  7483 I         : BTE_InitTraceLevels -- TRC_AVRC
09-09 13:35:56.333  3179  7483 I         : BTE_InitTraceLevels -- TRC_A2D
09-09 13:35:56.333  3179  7483 I         : BTE_InitTraceLevels -- TRC_BNEP
09-09 13:35:56.333  3179  7483 I         : BTE_InitTraceLevels -- TRC_BTM,
09-09 13:35:56.333  3179  7483 I         : BTE_InitTraceLevels -- TRC_GAP
09-09 13:35:56.333  3179  7483 I         : BTE_InitTraceLevels -- TRC_PAN
,09-09 13:35:56.333  3179  7483 I         : BTE_InitTraceLevels -- TRC_SAP
09-09 13:35:56.333  3179  7483 I         : BTE_InitTraceLevels -- TRC_SDP
,09-09 13:35:56.333  3179  7483 I         : BTE_InitTraceLevels -- TRC_GATT
09-09 13:35:56.333  3179  7483 I         : BTE_InitTraceLevels -- TRC_SMP
09-09 13:35:56.333  3179  7483 I         : BTE_InitTraceLevels -- TRC_BTAPP,
09-09 13:35:56.333  3179  7483 I         : BTE_InitTraceLevels -- TRC_BTIF
09-09 13:35:56.333  3179  7483 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,09-09 13:35:56.423  3179  7483 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,09-09 13:35:56.423  3179  7483 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa42d7ed1 
,09-09 13:35:56.423  3179  7483 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa42d7ed1 
,09-09 13:35:56.433  3179  3275 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,09-09 13:35:56.443  3179  3275 E bt-btif : Calling BTA_HhEnable
,09-09 13:35:56.443  3179  3275 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-09 13:35:56.443  3179  3275 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,09-09 13:35:56.443  3179  3275 E BluetoothServiceJni: populateRssiValuesNative
,09-09 13:35:56.443  3179  3275 I bluedroid: getModelRssiValues
09-09 13:35:56.443  3179  3275 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,09-09 13:35:56.443  3179  3275 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-09 13:35:56.443  1015  1015 D SettingsProvider: name = bluetooth_name
,09-09 13:35:56.453  3179  3275 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,09-09 13:35:56.453  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:56.453  3179  3275 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-09 13:35:56.453  3179  3275 D BluetoothAdapterProperties: Scan Mode:20
09-09 13:35:56.453  3179  3275 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 13:35:56.453  3179  3275 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
,09-09 13:35:56.453  3179  3275 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
09-09 13:35:56.453  3179  3275 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
09-09 13:35:56.453  3179  3275 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-09 13:35:56.453  3179  3275 E bt-btif : btif_sock_init: !vhci_init
,09-09 13:35:56.463  3179  7510 E bt_mct  : hci lib postload completed
09-09 13:35:56.463  3179  3275 D bte_conf: Device ID record 1 : primary
09-09 13:35:56.463  3179  3275 D bte_conf:   vendorId            = 0075
09-09 13:35:56.463  3179  3275 D bte_conf:   vendorIdSource      = 0001
09-09 13:35:56.463  3179  3275 D bte_conf:   product             = 0100
09-09 13:35:56.463  3179  3275 D bte_conf:   version             = 0200
09-09 13:35:56.463  3179  3275 D bte_conf:   clientExecutableURL = 
09-09 13:35:56.463  3179  3275 D bte_conf:   serviceDescription  = 
09-09 13:35:56.463  3179  3275 D bte_conf:   documentationURL    = 
09-09 13:35:56.463  3179  3275 D bte_conf: bte_load_did_conf no section named DID2.
09-09 13:35:56.463  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:56.463  3179  3271 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-09 13:35:56.463  3179  3271 D BluetoothAdapterProperties: ScanMode =  20
09-09 13:35:56.463  3179  3271 D BluetoothAdapterProperties: State =  11
,09-09 13:35:56.463  1015  1533 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-09 13:35:56.473  3179  3271 D BluetoothAdapterProperties: Setting state to 12
09-09 13:35:56.473  3179  3271 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-09 13:35:56.473  3179  3275 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-09 13:35:56.473  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:56.473  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:56.473  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:56.473  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:56.473  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:56.473  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:56.473  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:56.473  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:35:56.473  3179  3275 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-09 13:35:56.473  3179  3275 D BluetoothAdapterProperties: Scan Mode:21
,09-09 13:35:56.483  3179  3275 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-09 13:35:56.483  1015  1477 D SettingsProvider: name = bluetooth_a2dp_sink_mode
09-09 13:35:56.483  1015  1477 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 13:35:56.483  1015  1477 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 13:35:56.483  1015  1477 D SettingsProvider: selectionArgs: false
09-09 13:35:56.483  1015  1477 D SettingsProvider: selectionArgs: 1002
09-09 13:35:56.483  1015  1477 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 13:35:56.483  1015  1477 D SettingsProvider: ret = -1
,09-09 13:35:56.483  3179  3271 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-09 13:35:56.483  3179  3271 D BluetoothAdapterService: updateAdapterState state is 12
,09-09 13:35:56.483  1015  1486 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 13:35:56.483  1015  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-09 13:35:56.483  1015  1486 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:56.483  1015  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 13:35:56.483  1015  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:56.493  1015  1044 D BluetoothPan: Binding service...
,09-09 13:35:56.493  3179  3271 D BluetoothAdapterService: Autoconnection is available 
09-09 13:35:56.493  3179  3271 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-09 13:35:56.493  3179  3271 D BluetoothAdapterService: starting service from this receiver
,09-09 13:35:56.493  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-09 13:35:56.493  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-09 13:35:56.493  6889  6904 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 13:35:56.493  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:35:56.493  6889  6904 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 13:35:56.503  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-09 13:35:56.503  7437  7447 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 13:35:56.503  7437  7447 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-09 13:35:56.503  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:56.503  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:56.503  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 13:35:56.503  3179  3179 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
09-09 13:35:56.503  6731  6731 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:35:56.503  1963  1976 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 13:35:56.503  1963  1976 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 13:35:56.503  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 13:35:56.503  1015  1044 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-09 13:35:56.503  6889  6901 D Bluetoothsap: onBluetoothStateChange: up=true
09-09 13:35:56.503  6889  6901 D Bluetoothsap: Binding service...
,09-09 13:35:56.503  3179  3271 I BluetoothAdapterState: Entering On State from state = 11
,09-09 13:35:56.503  1015  1015 D BluetoothPan: BluetoothPAN Proxy object connected
,09-09 13:35:56.513  3179  3179 I BluetoothPbapService: Handler(): got msg=1
,09-09 13:35:56.513  1015  1570 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-09 13:35:56.513  6731  6731 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-09 13:35:56.523  6731  6731 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-09 13:35:56.523  3179  7513 V BluetoothPbapService: PBAP Service initSocket try: 0
09-09 13:35:56.523  6889  6901 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-09 13:35:56.523  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-09 13:35:56.523  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-09 13:35:56.523  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:56.523  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:56.523  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:56.523  6889  6901 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-09 13:35:56.523  1015  1044 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 13:35:56.523  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-09 13:35:56.523  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 13:35:56.533  1015  1044 E BluetoothHeadset: BluetoothHeadset service is binded
09-09 13:35:56.533  6889  6904 D BluetoothPan: Binding service...
,09-09 13:35:56.533  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:56.533  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:56.533  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:56.533  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:56.533  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:56.533  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:56.533  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:56.533  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:35:56.533  3179  7513 D BluetoothSocket: bindListen(): myUserId = 0
09-09 13:35:56.533  3179  7513 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:35:56.533  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-09 13:35:56.533  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-09 13:35:56.533  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:56.533  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:56.533  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:56.543  1177  1413 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 13:35:56.543  1177  1413 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 13:35:56.543  3179  7513 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[81]}
09-09 13:35:56.543  3179  7513 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 13:35:56.543  3179  7513 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 13:35:56.543  3179  7513 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@31a6f2c8
,09-09 13:35:56.543  3179  7513 D BluetoothSocket: channel: 19
09-09 13:35:56.543  3179  3280 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 13:35:56.543  3179  7513 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-09 13:35:56.543  6889  6889 D Bluetoothsap: BluetoothSAP Proxy object connected
09-09 13:35:56.543  3179  3280 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-09 13:35:56.543  6889  6889 D SapProfile: Bluetooth service connected
09-09 13:35:56.543  6889  6889 D Bluetoothsap: getConnectedDevices()
09-09 13:35:56.543  6731  6731 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:35:56.543  1015  1044 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-09 13:35:56.543  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 13:35:56.543  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:56.543  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:56.543  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:56.543  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 13:35:56.553  1015  1044 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-09 13:35:56.553  3179  3179 D BluetoothA2dp: Proxy object connected
09-09 13:35:56.553  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-09 13:35:56.553  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-09 13:35:56.553  3179  3179 D BluetoothAdapterService: Bluetooth A2dp source service connected
,09-09 13:35:56.553  1015  1015 D BluetoothA2dp: Proxy object connected
09-09 13:35:56.553  1440  1647 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 13:35:56.553  1440  1647 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 13:35:56.553  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:56.553  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:56.553  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:56.553  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:56.553  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:56.553  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:56.553  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:56.553  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:35:56.553  6889  6889 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 13:35:56.553  6889  6889 D PanProfile: Bluetooth service connected
,09-09 13:35:56.553  1430  1453 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 13:35:56.553  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 13:35:56.553  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 13:35:56.553  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:56.553  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:56.553  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:56.563  1430  1453 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 13:35:56.563  6731  6744 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-09 13:35:56.563  6731  6744 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 13:35:56.563  6731  6731 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:35:56.563  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:56.563  1454  1830 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 13:35:56.563  1015  1044 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-09 13:35:56.563  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 13:35:56.563  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:56.563  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 13:35:56.563  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:56.573  1454  1830 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 13:35:56.573  1430  1443 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 13:35:56.573  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-09 13:35:56.573  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 13:35:56.573  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:56.573  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:56.573  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:56.573  1430  1443 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 13:35:56.573  3179  3280 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-09 13:35:56.573  3179  3280 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 13:35:56.573  1430  3281 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-09 13:35:56.573  1430  3281 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 13:35:56.583  1430  1453 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 13:35:56.583  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-09 13:35:56.583  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 13:35:56.583  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:56.583  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:56.583  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:56.583  1430  1453 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 13:35:56.583  1454  1476 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 13:35:56.583  1454  1476 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-09 13:35:56.583  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-09 13:35:56.583  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-09 13:35:56.583  1015  1027 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,09-09 13:35:56.583  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,09-09 13:35:56.583  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:56.583  1015  1027 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-09 13:35:56.593  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,09-09 13:35:56.593  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:35:56.603  1015  1015 I InputMethodManagerService: [BT Setting State] State =12
09-09 13:35:56.603  1015  1015 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-09 13:35:56.603  1430  1430 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@39dc6084, true
,09-09 13:35:56.603  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,09-09 13:35:56.603  1430  1430 D BluetoothHeadset: registerMessageListener
,09-09 13:35:56.613  2026  2026 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-09 13:35:56.613  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-09 13:35:56.613  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:35:56.613  1177  1177 D BluetoothTile:  getBluetoothState : 12
,09-09 13:35:56.613  6889  6889 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:35:56.613  1177  1607 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 13:35:56.623  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:56.623  1015  1486 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 13:35:56.623  1015  1486 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-09 13:35:56.623  3179  3280 D HeadsetService: registerMessageListener
,09-09 13:35:56.623  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:56.623  3179  3280 D HeadsetService: registerMessageListener
09-09 13:35:56.623  1177  1607 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 13:35:56.623  3179  7469 D HeadsetStateMachine: Disconnected process message: 70
09-09 13:35:56.623  1015  1486 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:56.623  3179  7469 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@10be7f61
09-09 13:35:56.623  1015  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:56.623  1015  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:56.623  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:56.633  1430  1430 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-09 13:35:56.633  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-09 13:35:56.633  1177  1607 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 13:35:56.633  3179  7519 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-09 13:35:56.633  1430  1430 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-09 13:35:56.633  1430  1430 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,09-09 13:35:56.633  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-09 13:35:56.633  1015  1533 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-09 13:35:56.633  6889  6889 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-09 13:35:56.643  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-09 13:35:56.643  1015  1486 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
09-09 13:35:56.643  3179  7519 D BluetoothSocket: bindListen(): myUserId = 0
09-09 13:35:56.643  3179  7519 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:35:56.643  3179  7469 D HeadsetStateMachine: Disconnected process message: 9
09-09 13:35:56.643  3179  7519 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[83]}
09-09 13:35:56.643  3179  7519 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 13:35:56.643  3179  7519 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 13:35:56.643  3179  7519 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@11f1fa86
,09-09 13:35:56.643  3179  7469 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6,
,09-09 13:35:56.643  3179  7519 D BluetoothSocket: channel: 5
,09-09 13:35:56.653   285   285 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
09-09 13:35:56.653   285   285 V voice   : voice_set_parameters: enter: A2dpSuspended=false,
09-09 13:35:56.653   285   285 V voice   : voice_set_parameters: exit with code(-2)
09-09 13:35:56.653   285   285 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-09 13:35:56.653   285   285 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-09 13:35:56.653   285   285 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter,
09-09 13:35:56.653   285   285 V audio_hw_primary: adev_set_parameters: exit
09-09 13:35:56.653  3179  7469 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-09 13:35:56.653  6889  6889 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-09 13:35:56.653  1015  1569 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-09 13:35:56.653  1015  1569 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 13:35:56.653  1015  1569 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:56.663  1015  1569 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:56.663  1015  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:56.663  6889  6889 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-09 13:35:56.663  6889  6889 E BluetoothHeadset: BTStateChangeCB is registed
,09-09 13:35:56.663  6889  6889 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 13:35:56.663  1015  1571 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-09 13:35:56.663  1015  1571 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 13:35:56.673  1015  1571 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:56.673  1015  1571 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:56.673  1015  1571 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:56.673  6889  6889 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 13:35:56.673  6889  6889 D BluetoothMap: Create BluetoothMap proxy object
,09-09 13:35:56.673  1015  1533 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
09-09 13:35:56.673  1015  1533 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-09 13:35:56.673  1015  1533 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:56.673  1015  1533 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:56.673  1015  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:56.683  1015  1132 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-09 13:35:56.683  1015  1132 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-09 13:35:56.683  1015  1132 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:56.683  1015  1132 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:56.683  1015  1132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:56.683  6889  6889 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
,09-09 13:35:56.683  1015  1569 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
09-09 13:35:56.683  1015  1569 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-09 13:35:56.683  1015  1569 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:56.683  1015  1569 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:56.683  1015  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:56.703  6889  6889 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 13:35:56.703  1015  1571 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-09 13:35:56.703  1015  1571 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-09 13:35:56.703  1015  1571 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:56.703  1015  1571 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 13:35:56.703  1015  1571 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-09 13:35:56.703  6889  6889 D BluetoothA2dp: Proxy object connected
,09-09 13:35:56.703  6889  6889 D A2dpProfile: Bluetooth service connected
,09-09 13:35:56.713  6889  6889 D HeadsetProfile: Bluetooth service connected
,09-09 13:35:56.713  6889  6889 D BluetoothMap: Proxy object connected
,09-09 13:35:56.713  6889  6889 D MapProfile: Bluetooth service connected
09-09 13:35:56.713  6889  6889 D BluetoothMap: getConnectedDevices()
,09-09 13:35:56.713  6889  6889 D BluetoothPbap: Proxy object connected
,09-09 13:35:56.713  6889  6889 D PbapServerProfile: Bluetooth service connected
09-09 13:35:56.713  6889  6889 D BluetoothInputDevice: Proxy object connected
09-09 13:35:56.713  6889  6889 D HidProfile: Bluetooth service connected
,09-09 13:35:56.723  6889  6889 D DockEventReceiver: finishStartingService: stopping service
,09-09 13:35:56.723  6889  6889 D BluetoothNotiBroadcastReceiver: onReceive
,09-09 13:35:56.723  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:35:56.723  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-09 13:35:56.733  3179  3179 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ce19ede
,09-09 13:35:56.733  3179  3179 D BtConfig.SecureMode: isSecureModeOn:false
,09-09 13:35:56.733  1015  1571 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 13:35:56.733  1015  1571 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-09 13:35:56.743  1015  1571 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:56.743  1015  1571 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:56.743  1015  1571 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:35:56.743  1015  1126 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-09 13:35:56.743  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:56.743  1015  1126 V NetworkStats: updateIfacesLocked()
09-09 13:35:56.743  1015  1126 V NetworkStats: performPollLocked(flags=0x1)
,09-09 13:35:56.743  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:35:56.743  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 13:35:56.753  1963  1963 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-09 13:35:56.753  1015  1126 V NetworkStats: performPollLocked() took 9ms
09-09 13:35:56.753  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:56.753  1015  1126 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,09-09 13:35:56.753  1015  1126 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
09-09 13:35:56.753  1177  1602 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-09 13:35:56.753  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:56.753  1015  1132 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 13:35:56.753  1015  1132 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
09-09 13:35:56.753  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:56.753  4748  6795 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-09 13:35:56.763  1177  1602 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-09 13:35:56.763  1015  1027 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
09-09 13:35:56.763  1015  1132 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:56.763  1015  1132 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:56.763  1015  1132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:56.763  4748  6795 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-09 13:35:56.763  6731  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:56.763  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:35:56.763  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:56.763  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:35:56.763  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 13:35:56.763  6731  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@179e3468 removed from the list
09-09 13:35:56.763  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:56.763  6731  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c43081 removed from the list
09-09 13:35:56.763  6731  6786 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:56.763  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:56.763  6731  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:35:56.763  6731  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f239567 added. We now have 3 listener(s)
,09-09 13:35:56.773  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-09 13:35:56.773  1963  1963 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
09-09 13:35:56.773  1963  7528 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-09 13:35:56.773  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:35:56.773  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:35:56.773  6731  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:35:56.773  6731  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e562f14 added. We now have 3 listener(s)
09-09 13:35:56.773  6731  6786 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:35:56.773  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:35:56.773  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:35:56.783  3179  7529 D BluetoothSocket: bindListen(): myUserId = 0
09-09 13:35:56.783  3179  7529 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:35:56.783  3179  7529 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[85]}
09-09 13:35:56.783  3179  7529 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 13:35:56.783  3179  7529 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 13:35:56.783  3179  7529 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@5e33912
,09-09 13:35:56.783  3179  7529 D BluetoothSocket: channel: 12
09-09 13:35:56.783  3179  7529 I BtOppRfcommListener: Accept thread started.
09-09 13:35:56.783  1015  1323 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:35:56.783  1015  1323 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:56.783  1015  1323 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:56.783  1015  1323 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:56.783  6731  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:56.783  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:56.783  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:56.783  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:56.783  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:56.783  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:56.783  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:56.783  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:35:56.793  6731  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:35:56.793  6731  6786 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:35:56.793  1015  3173 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-09 13:35:56.793  1015  3173 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-09 13:35:56.793  1015  3173 D SecContentProvider2: mCursor = null
,09-09 13:35:56.793  1015  3173 D WifiService: setWifiEnabled: false pid=6731, uid=10171
,09-09 13:35:56.793  1015  3173 D SettingsProvider: name = wifi_on
,09-09 13:35:56.793  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:56.803  1963  7528 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,09-09 13:35:56.803  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:56.803  1015  1124 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-09 13:35:56.803  7223  7223 I wpa_supplicant: reset timer : RESET_TIMER 0
09-09 13:35:56.803  7223  7223 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-09 13:35:56.803  7223  7223 I wpa_supplicant: P2P: Current p2p state = IDLE
,09-09 13:35:56.813  7223  7223 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-09 13:35:56.813  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 13:35:56.823  1015  1124 E WifiNative-wlan0: do suspend true,
,09-09 13:35:56.943   280  1013 D CommandListener: Clearing all IP addresses on wlan0,
09-09 13:35:56.943  1015  1123 D WifiP2pService: InactiveState{ what=143375 }
09-09 13:35:56.943  1963  7390 V NativeCrypto: Read error: ssl=0xb871acc8: I/O error during system call, Connection timed out
09-09 13:35:56.943  1015  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-09 13:35:56.953  1963  7390 V NativeCrypto: SSL shutdown failed: ssl=0xb871acc8: I/O error during system call, Broken pipe
,09-09 13:35:56.953  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:35:56.953  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-09 13:35:56.953  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:56.953  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:56.953  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:56.953  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:56.953  1015  1126 E ConnectivityService: updateNetworkInfo()
09-09 13:35:56.953  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-09 13:35:56.963  1015  1126 E ConnectivityService: updateNetworkInfo()
09-09 13:35:56.963  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 3
09-09 13:35:56.963  1015  1123 D WifiP2pService: InactiveState{ what=131204 }
09-09 13:35:56.963  1015  1123 D WifiP2pService: P2pEnabledState{ what=131204 }
09-09 13:35:56.963  1015  1124 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-09 13:35:56.963  1015  1123 D WifiP2pService: sending p2p connection changed broadcast: FAILED
09-09 13:35:56.963  1963  7390 E GCM     : Wifi connection closed with errorCode 20
,09-09 13:35:56.963  1015  1028 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 503]) by 10011
09-09 13:35:56.963  1015  7302 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:56.963  1015  7302 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:56.963  1015  7302 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
,09-09 13:35:56.963  1015  7302 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:56.963  1015  7302 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
09-09 13:35:56.963  1015  7302 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-09 13:35:56.963  1015  7302 I qtaguid : Tagging socket 376 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1015, getuid(): 1000
09-09 13:35:56.963  1015  7302 I qtaguid : Untagging socket 376
09-09 13:35:56.963  1015  7302 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-09 13:35:56.973  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-09 13:35:56.973  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-09 13:35:56.973  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-09 13:35:56.973  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:56.973  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:56.973  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:56.973  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:56.983  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1
,09-09 13:35:56.983  1015  1147 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:56.983  1015  1015 D RttService: SCAN_AVAILABLE : 1
,09-09 13:35:56.983  1015  1148 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 13:35:56.983  1015  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-09 13:35:56.993  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-09 13:35:56.993  1015  1124 E WifiNative-wlan0: do suspend true
09-09 13:35:56.993  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
09-09 13:35:56.993  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
,09-09 13:35:56.993  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
09-09 13:35:56.993  1015  1123 D WifiP2pService: P2pDisablingState
09-09 13:35:56.993  1015  1123 D WifiP2pService: P2pDisablingState{ what=147458 }
,09-09 13:35:56.993  1015  1123 D WifiP2pService: p2p socket connection lost
09-09 13:35:56.993  1015  1123 D WifiP2pService: P2pDisabledState
,09-09 13:35:56.993  1015  1123 D WifiP2pService: P2pDisabledState{ what=143375 }
,09-09 13:35:56.993  1015  1123 D WifiP2pService: DefaultState{ what=143375 }
09-09 13:35:56.993  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-09 13:35:56.993  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-09 13:35:56.993  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 13:35:56.993  1015  1045 D WifiDisplayController: disconnect
09-09 13:35:56.993  1015  1045 D WifiDisplayController: updateConnection
09-09 13:35:56.993  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,09-09 13:35:56.993  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 13:35:57.003  1015  1132 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 13:35:57.003  1015  1132 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:35:57.003  1015  1132 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:57.003  1015  1132 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:57.003  1015  1132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:35:57.003  1636  1636 I Hs20UtilService: Starting #18
,09-09 13:35:57.003  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:35:57.003  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:35:57.003  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:57.003  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:57.003  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:57.003  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:57.003  1636  1705 I Hs20UtilService: Message received 5007
,09-09 13:35:57.013   280  1009 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-09 13:35:57.013   280  1009 D Netd    : getNetworkForDns: using netid 0 for uid 1000
09-09 13:35:57.013  6889  6889 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-09 13:35:57.013  6889  6889 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 13:35:57.013   280  1013 D CommandListener: Clearing all IP addresses on wlan0
,09-09 13:35:57.013  6889  6889 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-09 13:35:57.013  1015  1126 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-09 13:35:57.013  1015  1126 V NetworkStats: updateIfacesLocked()
,09-09 13:35:57.013  1015  1126 V NetworkStats: performPollLocked(flags=0x1)
09-09 13:35:57.013  1015  7302 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
09-09 13:35:57.013  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-09 13:35:57.013  1015  7302 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-09 13:35:57.013  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
09-09 13:35:57.013  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 13:35:57.013  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-09 13:35:57.013  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit,
,09-09 13:35:57.013  6889  6889 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-09 13:35:57.013  6889  6889 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 13:35:57.013  6889  6889 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-09 13:35:57.013  6889  6908 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-09 13:35:57.013  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-09 13:35:57.013  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-09 13:35:57.013  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-09 13:35:57.013  1015  1569 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-09 13:35:57.023  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-09 13:35:57.023  1015  1126 V NetworkStats: performPollLocked() took 10ms
09-09 13:35:57.023  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:57.023  1015  1126 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
,09-09 13:35:57.023  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-09 13:35:57.023  7223  7223 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-09 13:35:57.033  1177  1602 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-09 13:35:57.033  1015  1126 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:35:57.033  1015  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-09 13:35:57.033  1015  1126 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
09-09 13:35:57.033  1015  7302 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:57.033  1015  1126 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=false
09-09 13:35:57.033  4748  6795 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-09 13:35:57.033  1015  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 13:35:57.033  1015  1123 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-09 13:35:57.033  1454  1454 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-09 13:35:57.033  1454  1454 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-09 13:35:57.033  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:57.043  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:57.043  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:35:57.043  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-09 13:35:57.043  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:57.043  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:57.043  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:57.043  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:35:57.043  6889  6889 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-09 13:35:57.043  6889  6889 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 13:35:57.043  1015  1126 D ConnectivityService: nai.networkMonitor.doQuit()
09-09 13:35:57.043  1015  1126 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-09 13:35:57.043  1015  1126 E ConnectivityService: updateNetworkInfo()
,09-09 13:35:57.043  1015  1126 E ConnectivityService: updateNetworkInfo()
09-09 13:35:57.043  1015  1124 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-09 13:35:57.043  6889  6889 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-09 13:35:57.043  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-09 13:35:57.043  1015  1127 D Tethering: MasterInitialState.processMessage what=3
,09-09 13:35:57.053  1015  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-09 13:35:57.053  1015  1121 V NetworkStats: updateIfacesLocked()
09-09 13:35:57.053  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:57.053  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
,09-09 13:35:57.053  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:35:57.053  1015  1124 D SecContentProvider2: mCursor = null
09-09 13:35:57.053  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-09 13:35:57.053  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 13:35:57.053  1177  1177 D StatusBar.NetworkController: EthernetConnected: false,
09-09 13:35:57.053  1015  1122 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-09 13:35:57.053  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-09 13:35:57.053  1015  1121 V NetworkStats: performPollLocked() took 5ms
09-09 13:35:57.053  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-09 13:35:57.053  1177  1177 D StatusBar.NetworkController: updateDataNetType()
09-09 13:35:57.053  1177  1177 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-09 13:35:57.053  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-09 13:35:57.053  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:57.053  6889  6889 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-09 13:35:57.053  6889  6889 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 13:35:57.053  6889  6889 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-09 13:35:57.053  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:57.053  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:57.053  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:57.053  6889  6908 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-09 13:35:57.053  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:57.063  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-09 13:35:57.063  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-09 13:35:57.063  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-09 13:35:57.063  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:35:57.063  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:35:57.063  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:57.063  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:57.063  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:57.063  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:57.063  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:35:57.063  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:35:57.063  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-09 13:35:57.063  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:57.063  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:57.063  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:57.063  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:57.063  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:35:57.063  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
09-09 13:35:57.063  1177  1177 D HotspotTile: onReceive : 0, 0
09-09 13:35:57.063  1177  1607 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-09 13:35:57.063  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:57.063  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:57.063  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:57.063  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:35:57.063  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:57.063  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null,
09-09 13:35:57.063  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:35:57.063  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:35:57.073  6731  6731 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:35:57.073  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:57.073  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:57.073  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:57.073  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:35:57.073  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:57.073  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:35:57.073  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:35:57.073  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false,
,09-09 13:35:57.073  6731  6731 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:35:57.073  1015  1569 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,09-09 13:35:57.083  1015  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:57.083  1015  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:57.083  1015  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:57.083  1015  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:57.083  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:57.083  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:57.083  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:57.083  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:35:57.083  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:57.083  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:35:57.083  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:35:57.083  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:35:57.083  6731  6731 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:35:57.093  7537  7537 E Zygote  : MountEmulatedStorage()
,09-09 13:35:57.093  7537  7537 E Zygote  : v2
09-09 13:35:57.093  7537  7537 I libpersona: KNOX_SDCARD checking this for 10064
09-09 13:35:57.093  7537  7537 I libpersona: KNOX_SDCARD not a persona
,09-09 13:35:57.093  7537  7537 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:35:57.093  7537  7537 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-09 13:35:57.093  7537  7537 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 13:35:57.093  1015  1569 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7537 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:35:57.103  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:57.103  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:57.123  7537  7537 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:35:57.123  7537  7537 D ActivityThread: Added TimaKeyStore provider
,09-09 13:35:57.133  7223  7223 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 13:35:57.153  7537  7537 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-09 13:35:57.163  7537  7537 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 13:35:57.163  7537  7537 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-09 13:35:57.173  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:35:57.173  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:35:57.173  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:35:57.183  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:35:57.183  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:35:57.183  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:35:57.183  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:35:57.183  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:35:57.183  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:35:57.193  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-09 13:35:57.193  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:35:57.193  7223  7223 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING ,
09-09 13:35:57.193  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-09 13:35:57.193  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:35:57.193  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 13:35:57.193  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 13:35:57.193  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-09 13:35:57.193  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:35:57.193  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:35:57.193  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:35:57.203  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:35:57.203  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-09 13:35:57.203  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:35:57.203  7537  7537 D FileShare-Client: Outbound.stopDelayTimer - 
09-09 13:35:57.203  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:35:57.203  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-09 13:35:57.203  1015  1539 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,09-09 13:35:57.203  1015  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-09 13:35:57.203  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-09 13:35:57.203  1015  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:57.203  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:35:57.203  1015  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:57.203  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-09 13:35:57.203  1015  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:57.203  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:35:57.203  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:35:57.203  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:35:57.213  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
09-09 13:35:57.213  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:35:57.213  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-09 13:35:57.223  1015  1539 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7565 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 13:35:57.223  7565  7565 E Zygote  : MountEmulatedStorage()
09-09 13:35:57.223  7565  7565 I libpersona: KNOX_SDCARD checking this for 10065
09-09 13:35:57.223  7565  7565 E Zygote  : v2
09-09 13:35:57.223  7565  7565 I libpersona: KNOX_SDCARD not a persona
09-09 13:35:57.223  7565  7565 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:35:57.223  7565  7565 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 13:35:57.223  7565  7565 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:35:57.233  7223  7223 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
09-09 13:35:57.233  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:35:57.233  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:35:57.233  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
09-09 13:35:57.233  7223  7223 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-09 13:35:57.233  7223  7223 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-09 13:35:57.233  7223  7223 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-09 13:35:57.233  7223  7223 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
09-09 13:35:57.233  1015  1127 D Tethering: InitialState.processMessage what=4
,09-09 13:35:57.233  1015  1127 E Tethering: No numeric data
09-09 13:35:57.233  1015  1127 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 13:35:57.233  1015  1127 D Tethering: clearTetheredNotification()
,09-09 13:35:57.233  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:35:57.233  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:35:57.233  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-09 13:35:57.233  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:57.233  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
09-09 13:35:57.233  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:35:57.233  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:35:57.233  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
09-09 13:35:57.233  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 13:35:57.233  1177  1177 D HotspotTile: updateTetherState():false, false
09-09 13:35:57.233  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:35:57.233  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 13:35:57.243  7565  7565 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:35:57.243  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:57.243  1015  1121 V NetworkStats: performPollLocked() took 4ms
,09-09 13:35:57.243  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:57.243  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:57.243  7565  7565 D ActivityThread: Added TimaKeyStore provider
,09-09 13:35:57.263  7565  7565 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 13:35:57.263  1015  1570 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:57.263  1015  1570 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:57.263  1015  1570 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,09-09 13:35:57.273  1015  1486 I ActivityManager: Killing 7338:com.sec.pcw.device/1000 (adj 15): empty #21
,09-09 13:35:57.273  1015  1533 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 13:35:57.273  1015  1533 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:35:57.273  1015  1533 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:57.273  1015  1533 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:57.273  1015  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:35:57.273  1636  1636 I Hs20UtilService: Starting #19
09-09 13:35:57.273  1636  1705 I Hs20UtilService: Message received 5007
,09-09 13:35:57.283  6889  6889 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-09 13:35:57.283  6889  6889 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 13:35:57.283  6889  6889 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 13:35:57.283  6889  6889 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-09 13:35:57.283  6889  6889 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 13:35:57.283  6889  6889 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 13:35:57.283  6889  6908 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 13:35:57.293  1015  1569 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 13:35:57.293  1015  1569 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:35:57.293  1015  1569 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:57.293  1015  1569 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:57.293  1015  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-09 13:35:57.293  1636  1636 I Hs20UtilService: Starting #20
09-09 13:35:57.293  1636  1705 I Hs20UtilService: Message received 5011
,09-09 13:35:57.293  1015  1323 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,09-09 13:35:57.293  1015  1323 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:57.293  1015  1323 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:57.293  1015  1323 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:57.293  1015  1323 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:57.313  7582  7582 E Zygote  : MountEmulatedStorage()
,09-09 13:35:57.313  7582  7582 E Zygote  : v2
09-09 13:35:57.313  7582  7582 I libpersona: KNOX_SDCARD checking this for 1000
09-09 13:35:57.313  7582  7582 I libpersona: KNOX_SDCARD not a persona
,09-09 13:35:57.313  1015  1323 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=7582 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
09-09 13:35:57.313  6731  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:57.313  7582  7582 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:35:57.313  1015  1571 D SecContentProvider: uri = 18 selection = isWifiEnabled,
09-09 13:35:57.313  1015  1571 D WifiService: setWifiEnabled: true pid=6731, uid=10171
09-09 13:35:57.313  1015  1571 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-09 13:35:57.313  1015  1571 W ActivityManager: Permission Denial: getCurrentUser() from pid=6731, uid=10171 requires android.permission.INTERACT_ACROSS_USERS,
09-09 13:35:57.313  1015  1571 D SecContentProvider2: mCursor = null
09-09 13:35:57.313  7582  7582 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 13:35:57.313  1015  1571 W WifiService: Failed getting userId using ActivityManagerNative
09-09 13:35:57.313  1015  1571 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6731, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-09 13:35:57.313  1015  1571 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-09 13:35:57.313  1015  1571 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-09 13:35:57.313  1015  1571 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-09 13:35:57.313  1015  1571 W WifiService: ,	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-09 13:35:57.313  1015  1571 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-09 13:35:57.313  1015  1571 D SettingsProvider: name = wifi_on,
09-09 13:35:57.313  7582  7582 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:35:57.353  7582  7582 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:35:57.353  7582  7582 D ActivityThread: Added TimaKeyStore provider
,09-09 13:35:57.383  7582  7582 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-09 13:35:57.383  7582  7582 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-09 13:35:57.383  7582  7582 D SecurityLogAgent: StateMachine : Current State = 1
,09-09 13:35:57.383  7582  7582 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 13:35:57.383  1015  1323 I ActivityManager: Killing 7013:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,09-09 13:35:57.393  1015  3173 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:57.393  1015  3173 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:57.393  1015  3173 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:57.393  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:57.393  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:57.393  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:57.403  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:57.403  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:57.403  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:57.403  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:57.403  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 13:35:57.403  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:57.413  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:57.413  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:57.413  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:57.413  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:57.413  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:57.413  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:57.413  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:57.413  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:57.413  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:57.423  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:57.423  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:57.423  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:57.423  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:57.423  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:57.423  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:57.423  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:57.423  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:57.423  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:57.433  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:57.433  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:57.433  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:57.433  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:57.433  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:57.433  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:57.433  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:57.433  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:57.433  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:57.443  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:57.443  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:57.443  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:57.443  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:57.443  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:57.443  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:35:57.543  7223  7223 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 13:35:57.543  1015  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:35:57.543  1015  1015 I ApplicationPolicy: updateDataUsageMap
,09-09 13:35:57.553  1015  1039 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:35:57.563  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:57.573  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-09 13:35:57.573  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:57.573  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:57.573  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:57.573  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:57.573  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:57.573  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:57.593  7600  7600 E Zygote  : MountEmulatedStorage()
09-09 13:35:57.593  7600  7600 E Zygote  : v2
09-09 13:35:57.593  7600  7600 I libpersona: KNOX_SDCARD checking this for 1000
09-09 13:35:57.593  7600  7600 I libpersona: KNOX_SDCARD not a persona
,09-09 13:35:57.593  7600  7600 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:35:57.603  1015  1040 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7600 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,09-09 13:35:57.603  7600  7600 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-09 13:35:57.613  7600  7600 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:35:57.633  7600  7600 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:35:57.633  7600  7600 D ActivityThread: Added TimaKeyStore provider
,09-09 13:35:57.663  7600  7600 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,09-09 13:35:57.663  7600  7600 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,09-09 13:35:57.663  7600  7600 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-09 13:35:57.673  7600  7600 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true,
09-09 13:35:57.673  7600  7600 I PCWCLIENTTRACE_PushUtil: sales region : global
09-09 13:35:57.673  7600  7600 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-09 13:35:57.673  7600  7600 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
09-09 13:35:57.673  7223  7223 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
,09-09 13:35:57.673  1015  1533 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
09-09 13:35:57.673  1015  1533 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,09-09 13:35:57.683  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:35:57.683  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:35:57.683  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-09 13:35:57.683  7600  7615 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,09-09 13:35:57.683  1015  1533 I ActivityManager: Killing 7026:com.sec.android.soagent/u0a31 (adj 15): empty #21
,09-09 13:35:57.693  1788  1788 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-09 13:35:57.693  7354  7354 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:35:57.693  7354  7354 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
09-09 13:35:57.693  7354  7354 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-09 13:35:57.703  2485  2499 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,09-09 13:35:57.713  1015  1323 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 13:35:57.713  1788  1788 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,09-09 13:35:57.713  1788  1788 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,09-09 13:35:57.713  1015  1027 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 13:35:57.713  1788  1788 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,09-09 13:35:57.713  1788  1788 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-09 13:35:57.723  1788  1788 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-09 13:35:57.723  1788  1788 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,09-09 13:35:57.733  1015  1571 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 13:35:57.733  1015  1571 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-09 13:35:57.733  1015  1571 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:57.733  1015  1571 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:57.733  1015  1571 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:35:57.753  4748  4748 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-09 13:35:57.753  1015  1571 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,09-09 13:35:57.753  1015  1571 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-09 13:35:57.753  1015  1571 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:57.753  1015  1571 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:35:57.753  1015  1571 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-09 13:35:57.763  4748  7207 I iu.UploadsManager: num queued entries: 0
09-09 13:35:57.763  4748  7207 I iu.UploadsManager: num updated entries: 0
,09-09 13:35:57.763  4748  7207 I iu.SyncManager: NEXT; no task
,09-09 13:35:57.773  6911  7617 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-09 13:35:57.783  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
09-09 13:35:57.783  1015  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-09 13:35:57.783  6911  6911 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:35:57.783  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:35:57.783  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-09 13:35:57.783  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:57.783  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:57.783  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:57.783  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:35:57.793  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:35:57.793  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,09-09 13:35:57.793  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:35:57.793  1177  1607 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-09 13:35:57.793  1177  1177 D HotspotTile: onReceive : 1, 0
09-09 13:35:57.793  1963  2161 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:35:57.793  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:57.803  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:57.803  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:57.803  2777  7619 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,09-09 13:35:57.803  2777  7619 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,09-09 13:35:57.803  2777  7619 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,09-09 13:35:57.803  2777  7619 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,09-09 13:35:57.803  2777  7619 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-09 13:35:57.813  7078  7078 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,09-09 13:35:57.813  7112  7112 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,09-09 13:35:57.813  7112  7112 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,09-09 13:35:57.813  7112  7112 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-09 13:35:57.823  1015  1028 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,09-09 13:35:57.823  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,09-09 13:35:57.823  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:57.823  1015  1028 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-09 13:35:57.823  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,09-09 13:35:57.823  7112  7112 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,09-09 13:35:57.823  7112  7112 I SA      : [OR] == isSIMCardReady false ==
,09-09 13:35:57.833  7112  7112 I SA      : [SCU] == networkStateCheck == false
09-09 13:35:57.833  7112  7112 I SA      : [OR] onReceive END
,09-09 13:35:57.833  7078  7620 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,09-09 13:35:57.833  1221  1221 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:35:57.883   290   290 E SMD     : DCD OFF
,09-09 13:35:58.033  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-09 13:35:58.033  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:58.033  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:58.033  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:35:58.033  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:35:58.043  7621  7621 E Zygote  : MountEmulatedStorage(),
09-09 13:35:58.043  1015  1015 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7621 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 13:35:58.043  7621  7621 E Zygote  : v2,
09-09 13:35:58.043  7621  7621 I libpersona: KNOX_SDCARD checking this for 10001
09-09 13:35:58.043  7621  7621 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:35:58.043  7621  7621 I libpersona: KNOX_SDCARD not a persona
,09-09 13:35:58.043  7621  7621 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-09 13:35:58.053  7621  7621 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:35:58.073  7621  7621 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:35:58.073  7621  7621 D ActivityThread: Added TimaKeyStore provider
,09-09 13:35:58.123  7090  7090 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:35:58.123  7090  7090 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-09 13:35:58.123  7090  7090 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,09-09 13:35:58.123  7090  7090 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-09 13:35:58.133  1015  1477 I ActivityManager: Killing 7392:com.samsung.android.sm/1000 (adj 15): empty #21
,09-09 13:35:58.143  2922  2922 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Sep 09 13:35:58 GMT+02:00 2016
,09-09 13:35:58.143  1015  3173 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-09 13:35:58.143  1015  3173 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-09 13:35:58.143  1015  3173 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:58.143  1015  3173 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:58.143  1015  3173 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-09 13:35:58.153  2922  2922 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-09 13:35:58.153  1015  1028 I splitIntent: Queue : background intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart  false.
,09-09 13:35:58.153  2922  2922 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
09-09 13:35:58.153  1015  1533 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 13:35:58.153  1015  1533 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:35:58.153  1015  1533 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:35:58.153  1015  1533 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:58.153  1015  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:35:58.153  1636  1636 I Hs20UtilService: Starting #21
,09-09 13:35:58.153  2922  2922 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-09 13:35:58.153  1636  1705 I Hs20UtilService: Message received 5011
,09-09 13:35:58.163  7582  7582 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-09 13:35:58.163  7582  7582 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 13:35:58.163  7582  7582 D SecurityLogAgent: StateMachine : Current State = 1
09-09 13:35:58.163  7582  7582 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 13:35:58.163  2922  2922 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-09 13:35:58.163  2922  7638 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-09 13:35:58.173  2922  7638 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-09 13:35:58.173  2922  7638 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,09-09 13:35:58.173  2922  7638 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END,
,09-09 13:35:58.173  2922  2922 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-09 13:35:58.243  1015  1533 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-09 13:35:58.243  1015  1533 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-09 13:35:58.243  1015  1533 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-09 13:35:58.243  1015  1533 D BatteryService: stay LED for fully charged
,09-09 13:35:58.243  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-09 13:35:58.243  1015  1015 I MotionRecognitionService: Plugged
09-09 13:35:58.243  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,09-09 13:35:58.243  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-09 13:35:58.243  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-09 13:35:58.243  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
09-09 13:35:58.243  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-09 13:35:58.273  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-09 13:35:58.273  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-09 13:35:58.273  3179  3179 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-09 13:35:58.273  3179  7469 D HeadsetStateMachine: Disconnected process message: 10
09-09 13:35:58.273  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-09 13:35:58.273  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
09-09 13:35:58.273  1177  1177 D SViewCoverView: level :100 plugged : 2
,09-09 13:35:58.423  1015  1477 I art     : Explicit concurrent mark sweep GC freed 64835(3MB) AllocSpace objects, 4(112KB) LOS objects, 33% free, 24MB/37MB, paused 2.482ms total 164.218ms
,09-09 13:35:58.423  1015  1042 D Tethering: interfaceRemoved wlan0
09-09 13:35:58.423  1015  1042 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-09 13:35:58.583  1015  1042 D Tethering: interfaceRemoved p2p0
,09-09 13:35:58.583  1015  1042 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-09 13:35:59.443  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-09 13:35:59.443  1015  1124 E WifiHW  : ##################### set firmware type 0 #####################
,09-09 13:35:59.783  1015  1042 D Tethering: interfaceAdded wlan0
,09-09 13:35:59.783  1015  1127 E Tethering: No numeric data
,09-09 13:35:59.783  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
,09-09 13:35:59.793  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:59.793  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-09 13:35:59.793  1177  1177 D HotspotTile: updateTetherState():false, false
09-09 13:35:59.793  1015  1127 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-09 13:35:59.793  1015  1127 D Tethering: clearTetheredNotification()
,09-09 13:35:59.793  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-09 13:35:59.793  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 13:35:59.803  1015  1121 V NetworkStats: performPollLocked() took 9ms,
09-09 13:35:59.803  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:59.803  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:59.803  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:59.803  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:35:59.803  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:35:59.803  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
09-09 13:35:59.803  1015  1127 D Tethering: InitialState.processMessage what=4
,09-09 13:35:59.803  1015  1127 E Tethering: No numeric data
09-09 13:35:59.803  1015  1127 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 13:35:59.803  1015  1127 D Tethering: clearTetheredNotification()
09-09 13:35:59.813  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
09-09 13:35:59.813  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:59.813  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:35:59.813  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 13:35:59.813  1015  1042 D Tethering: interfaceAdded p2p0
,09-09 13:35:59.813  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-09 13:35:59.813  1177  1177 D HotspotTile: updateTetherState():false, false
,09-09 13:35:59.823   280  1013 I WifiHW  : wifi_change_fw_path(): fwpath = sta,
09-09 13:35:59.823  1015  1042 D Tethering: p2p0 is not a tetherable iface, ignoring
09-09 13:35:59.823   280  1013 D SoftapController: Softap fwReload - Ok
,09-09 13:35:59.823  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 13:35:59.823  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 13:35:59.823  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-09 13:35:59.823   280  1013 D CommandListener: Setting iface cfg
,09-09 13:35:59.823  1015  1121 V NetworkStats: performPollLocked() took 17ms
09-09 13:35:59.823  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:35:59.823   280  1013 D CommandListener: Trying to bring down wlan0
,09-09 13:35:59.833   280  1013 D CommandListener: Clearing all IP addresses on wlan0
,09-09 13:35:59.833  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:59.833  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:35:59.833  1015  1124 E WifiHW  : supplicant_name : p2p_supplicant
,09-09 13:35:59.843  1015  1124 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-09 13:35:59.843  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 13:35:59.843  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-09 13:35:59.843  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:59.843  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:59.843  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:35:59.843  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:35:59.853  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:35:59.853  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
09-09 13:35:59.853  1177  1607 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-09 13:35:59.853  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:35:59.853  1177  1177 D HotspotTile: onReceive : 2, 0
,09-09 13:35:59.863  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:59.863  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:59.863  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-09 13:35:59.863  1015  1486 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 13:35:59.863  1015  1486 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-09 13:35:59.863  1015  1486 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:35:59.863  1015  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:35:59.863  1015  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:35:59.873  1636  1636 I Hs20UtilService: Starting #22
09-09 13:35:59.873  1636  1705 I Hs20UtilService: Message received 5011
,09-09 13:35:59.873  7582  7582 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-09 13:35:59.873  7582  7582 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 13:35:59.873  7582  7582 D SecurityLogAgent: StateMachine : Current State = 1
09-09 13:35:59.873  7582  7582 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 13:35:59.893  7648  7648 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-09 13:35:59.893  7648  7648 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-09 13:35:59.893  7648  7648 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-09 13:35:59.903  7648  7648 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,09-09 13:35:59.913   364   364 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7648
09-09 13:35:59.913   364   364 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-09 13:35:59.913  7648  7648 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-09 13:35:59.913  7648  7648 I wpa_supplicant: ssSupport state is = 1
09-09 13:35:59.913  7648  7648 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-09 13:35:59.913  7648  7648 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-09 13:35:59.913   364   364 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7648
09-09 13:35:59.913   364   364 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,09-09 13:35:59.983  1015  1093 V AlarmManager: waitForAlarm result :8,
,09-09 13:36:00.063   364   364 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,09-09 13:36:00.073  7648  7648 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,09-09 13:36:00.113  7648  7648 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-09 13:36:00.113  7648  7648 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-09 13:36:00.123  7648  7648 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,09-09 13:36:00.123   364   364 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7648,
09-09 13:36:00.123   364   364 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-09 13:36:00.123  7648  7648 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-09 13:36:00.123  7648  7648 I wpa_supplicant: ssSupport state is = 1
09-09 13:36:00.123  7648  7648 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 13:36:00.123  7648  7648 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-09 13:36:00.123  7648  7648 E wpa_supplicant: SIM READ ERROR
09-09 13:36:00.123  7648  7648 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 13:36:00.123  7648  7648 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 13:36:00.123  7648  7648 E wpa_supplicant: SIM READ ERROR
09-09 13:36:00.123  7648  7648 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 13:36:00.123  7648  7648 I wpa_supplicant: wpa_default_ap_write_once
09-09 13:36:00.123  7648  7648 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-09 13:36:00.123  7648  7648 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 13:36:00.123  7648  7648 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-09 13:36:00.123  7648  7648 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 13:36:00.123  7648  7648 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
,09-09 13:36:00.133  7648  7648 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-09 13:36:00.133  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
09-09 13:36:00.133  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-09 13:36:00.133  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-09 13:36:00.213  7648  7648 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-09 13:36:00.373  7648  7648 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,09-09 13:36:00.373  7648  7648 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,09-09 13:36:00.383  7648  7648 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,09-09 13:36:00.383   364   364 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7648
09-09 13:36:00.383   364   364 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
09-09 13:36:00.393  7648  7648 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-09 13:36:00.393  7648  7648 I wpa_supplicant: ssSupport state is = 1
,09-09 13:36:00.393  7648  7648 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-09 13:36:00.393  7648  7648 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-09 13:36:00.403  7648  7648 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-09 13:36:00.403   364   364 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7648
09-09 13:36:00.403   364   364 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,09-09 13:36:00.403  7648  7648 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-09 13:36:00.403  7648  7648 I wpa_supplicant: ssSupport state is = 1
09-09 13:36:00.403  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 13:36:00.403  7648  7648 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 13:36:00.403  7648  7648 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 13:36:00.403  7648  7648 E wpa_supplicant: SIM READ ERROR
09-09 13:36:00.403  7648  7648 I wpa_supplicant: wpa_default_ap_write_once
09-09 13:36:00.403  7648  7648 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-09 13:36:00.403  7648  7648 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-09 13:36:00.403  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 13:36:00.403  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-09 13:36:00.413  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
09-09 13:36:00.413  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
,09-09 13:36:00.413  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-09 13:36:00.463  7648  7648 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-09 13:36:00.463  7648  7648 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-09 13:36:00.503  7648  7648 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,09-09 13:36:00.503  7648  7648 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-09 13:36:00.503  7648  7648 I wpa_supplicant: Skip scan - bUseNetwork false
,09-09 13:36:00.513  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
09-09 13:36:00.513  1015  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-09 13:36:00.513  7648  7648 I wpa_supplicant: HOTSPOT20_ENABLE called
,09-09 13:36:00.513  7648  7648 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 13:36:00.513  7648  7648 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 13:36:00.513  7648  7648 E wpa_supplicant: SIM READ ERROR
09-09 13:36:00.513  7648  7648 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 13:36:00.523  7648  7648 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-09 13:36:00.533  7648  7648 I wpa_supplicant: Skip scan - bUseNetwork false
09-09 13:36:00.533  1015  1124 D WifiConfigStore: Loading config and enabling all networks 
,09-09 13:36:00.533  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:36:00.533  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:36:00.533  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:00.533  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:00.533  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:00.533  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:36:00.543  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:36:00.543  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
09-09 13:36:00.543  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:36:00.543  1177  1607 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-09 13:36:00.543  1177  1177 D HotspotTile: onReceive : 3, 0
,09-09 13:36:00.553  1015  1027 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 13:36:00.553  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:36:00.553  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:36:00.553  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:36:00.553  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:36:00.553  1015  1124 E WifiConfigStore: Not a HS20
09-09 13:36:00.553  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:00.553  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:00.553  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:36:00.553  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:00.553  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:00.553  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:36:00.553  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:36:00.553  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:36:00.553  1015  1124 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-09 13:36:00.553  1636  1636 I Hs20UtilService: Starting #23
,09-09 13:36:00.563  1015  1124 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-09 13:36:00.563  6731  6731 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:36:00.563  1015  1124 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-09 13:36:00.563  7648  7648 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-09 13:36:00.563  7648  7648 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-09 13:36:00.563  7648  7648 I wpa_supplicant: reset timer : RESET_TIMER 0
09-09 13:36:00.563  7648  7648 I wpa_supplicant: P2P: Current p2p state = IDLE
09-09 13:36:00.563  7648  7648 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-09 13:36:00.563  7648  7648 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-09 13:36:00.563  7648  7648 I wpa_supplicant: First Scan Start
,09-09 13:36:00.563  7648  7648 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
09-09 13:36:00.563  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:00.563  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:00.563  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:36:00.563  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:00.563  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:00.563  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:36:00.563  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:36:00.563  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:36:00.563  1636  1705 I Hs20UtilService: Message received 5011
,09-09 13:36:00.563  1015  1124 D WifiNative-wlan0: Setting external_sim to 1
09-09 13:36:00.563  7582  7582 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-09 13:36:00.563  7582  7582 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 13:36:00.563  7582  7582 D SecurityLogAgent: StateMachine : Current State = 1
09-09 13:36:00.563  7582  7582 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 13:36:00.573  1015  1124 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 13:36:00.573  1015  1124 I WifiNative-HAL: startHal
09-09 13:36:00.573  1015  1124 E wifi    : getStaticLongField sWifiHalHandle 0x9d66f88c
09-09 13:36:00.573  1015  1124 I WifiNative-HAL: Could not start hal
,09-09 13:36:00.573  6911  6911 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:36:00.573  6731  6731 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:36:00.573  1015  1124 E WifiNative-wlan0: do suspend true
,09-09 13:36:00.573  1015  1123 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-09 13:36:00.573   280  1013 D CommandListener: Setting iface cfg
09-09 13:36:00.573   280  1013 D CommandListener: Trying to bring up p2p0
,09-09 13:36:00.573  1015  1123 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-09 13:36:00.573  1015  1123 D WifiP2pService: P2pEnablingState
09-09 13:36:00.573  1015  1123 D WifiP2pService: P2pEnablingState{ what=147457 }
09-09 13:36:00.573  1015  1123 D WifiP2pService: P2p socket connection successful
,09-09 13:36:00.573  1015  1123 D WifiP2pService: P2pEnabledState
,09-09 13:36:00.583  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:00.583  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:00.583  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:36:00.583  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:00.583  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:00.583  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:36:00.583  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:36:00.583  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:36:00.583  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-09 13:36:00.583  6731  6731 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:36:00.583  1015  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-09 13:36:00.583  1015  1126 E ConnectivityService: updateNetworkInfo()
09-09 13:36:00.583  1015  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-09 13:36:00.583  1015  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-09 13:36:00.583  1015  1124 E WifiNative-wlan0: invaild command id : 215
,09-09 13:36:00.583  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3
,09-09 13:36:00.593  7648  7648 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-09 13:36:00.593  7648  7648 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-09 13:36:00.593  1015  1015 D RttService: SCAN_AVAILABLE : 3
09-09 13:36:00.593  1015  1147 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:00.593  1015  1147 I WifiNative-HAL: startHal
09-09 13:36:00.593  1015  1147 E wifi    : getStaticLongField sWifiHalHandle 0x9e6199bc
09-09 13:36:00.593  1015  1147 I WifiNative-HAL: Could not start hal
09-09 13:36:00.593  1015  1147 E WifiScanningService: could not start HAL
,09-09 13:36:00.593  7648  7648 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
09-09 13:36:00.593  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-09 13:36:00.593  1015  1124 E WifiStateMachine: Failed to set frequency band 0
,09-09 13:36:00.593  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,09-09 13:36:00.593  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 13:36:00.593  1015  1045 D WifiDisplayController: disconnect
09-09 13:36:00.593  1015  1045 D WifiDisplayController: updateConnection,
09-09 13:36:00.593  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 13:36:00.593  1015  1148 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 13:36:00.593  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 13:36:00.593  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:36:00.593  1015  1124 D SecContentProvider2: mCursor = null
,09-09 13:36:00.603  1015  1123 D WifiNative-p2p0: p2pGetDeviceAddress
,09-09 13:36:00.603  1015  1123 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
,09-09 13:36:00.603  6889  6889 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-09 13:36:00.603  6889  6889 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-09 13:36:00.603  6889  6889 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 13:36:00.603  6889  6889 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED,
09-09 13:36:00.603  6889  6889 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 13:36:00.603  6889  6889 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 13:36:00.603  6889  6908 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-09 13:36:00.603  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:36:00.603  1015  1124 D SecContentProvider2: mCursor = null
,09-09 13:36:00.603  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:36:00.603  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
09-09 13:36:00.603  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 13:36:00.603  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
09-09 13:36:00.613  1015  1123 D WifiP2pService: DeviceAddress: 0a:76:28
,09-09 13:36:00.613  1015  1045 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
09-09 13:36:00.613  1015  1045 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
09-09 13:36:00.613  1015  1045 D WifiDisplayController:  primary type: 10-0050F204-5
09-09 13:36:00.613  1015  1045 D WifiDisplayController:  secondary type: null
09-09 13:36:00.613  1015  1045 D WifiDisplayController:  wps: 0
09-09 13:36:00.613  1015  1045 D WifiDisplayController:  grpcapab: 0
09-09 13:36:00.613  1015  1045 D WifiDisplayController:  devcapab: 0
09-09 13:36:00.613  1015  1045 D WifiDisplayController:  status: 3
09-09 13:36:00.613  1015  1045 D WifiDisplayController:  wfdInfo: null
09-09 13:36:00.613  1015  1045 D WifiDisplayController:  groupownerAddress: null
09-09 13:36:00.613  1015  1045 D WifiDisplayController:  GOdeviceName: null
09-09 13:36:00.613  1015  1045 D WifiDisplayController:  interfaceAddress: 
09-09 13:36:00.613  1015  1045 D WifiDisplayController:  SConnectInfo : null
,09-09 13:36:00.613  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-09 13:36:00.613  1015  1132 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-09 13:36:00.613  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-09 13:36:00.613  7537  7537 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 13:36:00.613  7537  7537 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-09 13:36:00.613  7537  7537 D FileShare-Client: Outbound.stopDelayTimer - 
,09-09 13:36:00.623  7565  7565 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 13:36:00.633  1015  1123 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-09 13:36:00.633  1015  1123 D WifiP2pService: InactiveState
,09-09 13:36:00.633  1015  1123 D WifiP2pService: InactiveState{ what=143376 }
,09-09 13:36:00.633  1015  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-09 13:36:00.633  7648  7648 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-09 13:36:00.633  1015  1123 D WifiP2pService: InactiveState{ what=143376 },
,09-09 13:36:00.633  1015  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-09 13:36:00.803  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false,
09-09 13:36:00.803  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 13:36:00.803  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-09 13:36:00.833  6731  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:36:00.833  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:36:00.833  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:36:00.833  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:36:00.843  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:36:00.843  6731  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f239567 removed from the list
09-09 13:36:00.843  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:00.843  6731  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e562f14 removed from the list
,09-09 13:36:00.843  6731  6786 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:00.843  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:36:00.853  6731  7655 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-09 13:36:00.853  6731  7655 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-09 13:36:00.893   290   290 E SMD     : DCD OFF,
,09-09 13:36:01.123  3179  3272 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-09 13:36:01.353   280  1009 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-09 13:36:01.353   280  1009 D Netd    : getNetworkForDns: using netid 0 for uid 10171
,09-09 13:36:01.353  6731  7655 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-09 13:36:01.353  6731  7655 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-09 13:36:01.353  6731  7655 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 13:36:01.353  6731  7655 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 13:36:01.353  6731  7655 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-09 13:36:01.363  6731  7661 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1407, name: OutgoingSocketThread/Receiver)
,09-09 13:36:01.363  6731  7661 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1407, thread name: OutgoingSocketThread/Receiver)
09-09 13:36:01.363  6731  7661 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-09 13:36:01.363  6731  7661 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1407, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-09 13:36:01.363  6731  7657 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-09 13:36:01.363  6731  7657 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-09 13:36:01.363  6731  7660 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1406, name: OutgoingSocketThread/Sender)
,09-09 13:36:01.363  6731  7657 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes,
09-09 13:36:01.363  6731  7657 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 13:36:01.363  6731  7657 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-09 13:36:01.363  6731  7662 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1408, name: IncomingSocketThread/Sender)
09-09 13:36:01.363  6731  7663 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1409, name: IncomingSocketThread/Receiver)
,09-09 13:36:01.363  6731  7663 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1409, thread name: IncomingSocketThread/Receiver)
,09-09 13:36:01.363  6731  7663 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-09 13:36:01.363  6731  7663 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1409, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-09 13:36:01.763  7648  7648 I wpa_supplicant: nl80211: Received scan results (26 BSSes)
,09-09 13:36:01.763  7648  7648 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-09 13:36:01.763  7648  7648 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-09 13:36:01.763  7648  7648 I wpa_supplicant: Trying to associate with  'G700'
09-09 13:36:01.763  7648  7648 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
09-09 13:36:01.763  7648  7648 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,09-09 13:36:01.763  1015  7653 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-09 13:36:01.773  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-09 13:36:01.773  1015  1124 D SecContentProvider2: mCursor = null
,09-09 13:36:01.803  1015  1323 I ActivityManager: Killing 4334:com.google.process.gapps/u0a11 (adj 15): empty #21
,09-09 13:36:01.853  6731  6786 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-09 13:36:01.853  6731  6786 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-09 13:36:01.853  6731  6786 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@9472fbc Bundle[{}]
,09-09 13:36:01.853  6731  6786 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-09 13:36:01.853  6731  6786 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-09 13:36:01.853  6731  6786 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-09 13:36:01.863  6731  6786 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-09 13:36:01.863  6731  6786 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-09 13:36:01.863  6731  6786 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-09 13:36:01.883  7648  7648 E wpa_supplicant: Cmd 35605 not handled
,09-09 13:36:01.893  6731  7664 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-09 13:36:01.893  6731  7664 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-09 13:36:01.893  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-09 13:36:01.893  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:36:01.893  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-09 13:36:01.893  7648  7648 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,09-09 13:36:01.893  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:36:01.893  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:36:01.893  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-09 13:36:01.893  7648  7648 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-09 13:36:01.893  7648  7648 I wpa_supplicant: Associated with F4.99.3E
,09-09 13:36:01.893  7648  7648 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,09-09 13:36:01.893  7648  7648 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-09 13:36:01.893  7648  7648 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-09 13:36:01.893  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-09 13:36:01.893  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, true
09-09 13:36:01.893  1015  1042 D Tethering: interfaceStatusChanged wlan0, true
,09-09 13:36:01.903  1015  1127 E Tethering: No numeric data
,09-09 13:36:01.903  1015  1127 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0,
09-09 13:36:01.903  1015  1127 D Tethering: clearTetheredNotification()
,09-09 13:36:01.903  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
09-09 13:36:01.903  6731  6741 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3a5b42d8, channel: 6, state: CLOSED
09-09 13:36:01.903  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 13:36:01.903  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:36:01.903  1177  1177 D HotspotTile: updateTetherState():false, false
09-09 13:36:01.903  7648  7648 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-09 13:36:01.903  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-09 13:36:01.903  7648  7648 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
09-09 13:36:01.903  6731  6741 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2e9394f0, channel: 6, state: CLOSED
09-09 13:36:01.903  7648  7648 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-09 13:36:01.903  7648  7648 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
09-09 13:36:01.903  7648  7648 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-09 13:36:01.903  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:36:01.903  7648  7648 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-09 13:36:01.903  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 13:36:01.903  7648  7648 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-09 13:36:01.903  7648  7648 I wpa_supplicant: Blacklist: Clear (temp) 
09-09 13:36:01.903  7648  7648 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-09 13:36:01.903  6731  6741 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@34f34da1, channel: 6, state: CLOSED
09-09 13:36:01.903  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, true
09-09 13:36:01.903  1015  1042 D Tethering: interfaceStatusChanged wlan0, true
09-09 13:36:01.903  6731  6741 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1f7c0d9e, channel: 6, state: CLOSED
09-09 13:36:01.913  6731  6741 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@374c4b50, channel: -1, state: CLOSED
09-09 13:36:01.913  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:36:01.913  1015  1124 D SecContentProvider2: mCursor = null
,09-09 13:36:01.913  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:36:01.913  1015  1121 V NetworkStats: performPollLocked() took 10ms
,09-09 13:36:01.913  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:36:01.913  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:36:01.923  1015  1124 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-09 13:36:01.923  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 13:36:01.923  1015  1124 E WifiConfigStore: setLastSelectedConfiguration -1
09-09 13:36:01.923  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:36:01.923  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:36:01.933  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:01.933  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:01.933  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:36:01.933  1015  1124 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,09-09 13:36:01.933  1015  1126 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
,09-09 13:36:01.933  1015  1126 E ConnectivityService: updateNetworkInfo()
,09-09 13:36:01.933  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-09 13:36:01.933  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 13:36:01.943  1015  1477 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 13:36:01.943  1015  1477 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:36:01.943  1015  1477 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:36:01.943  1015  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:36:01.943  1015  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:36:01.943  1636  1636 I Hs20UtilService: Starting #24
,09-09 13:36:01.943  1636  1705 I Hs20UtilService: Message received 5007
,09-09 13:36:01.943  6889  6889 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-09 13:36:01.943  6889  6889 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 13:36:01.953  6889  6889 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 13:36:01.953  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 13:36:01.953  6889  6889 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-09 13:36:01.953  6889  6889 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-09 13:36:01.953  6889  6889 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 13:36:01.953  6889  6908 V NearbySettings: MountReceiver.mPrefHandler - 7002,
,09-09 13:36:01.963   280  1013 D CommandListener: Setting iface cfg,
,09-09 13:36:01.963  1015  1124 E WifiStateMachine: Start Dhcp Watchdog 3
,09-09 13:36:01.973  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-09 13:36:01.973  1015  1124 D SecContentProvider2: mCursor = null
,09-09 13:36:01.973  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-09 13:36:01.973  1015  1124 D SecContentProvider2: mCursor = null
,09-09 13:36:01.983  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 13:36:01.983  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-09 13:36:01.983  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:36:01.983  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:36:01.983  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:36:01.983  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:36:01.993  1015  1124 E WifiNative-wlan0: do suspend false
,09-09 13:36:01.993  1015  1123 D WifiP2pService: InactiveState{ what=143375 }
,09-09 13:36:01.993  1015  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-09 13:36:02.003  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:36:02.003  1015  1124 D SecContentProvider2: mCursor = null
,09-09 13:36:02.213  7668  7668 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-09 13:36:02.213  7668  7668 I dhcpcd  : version 5.5.6 starting
,09-09 13:36:02.223  7668  7668 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-09 13:36:02.273  7668  7668 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
09-09 13:36:02.273  7668  7668 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-09 13:36:02.283  7668  7668 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
09-09 13:36:02.283  7668  7668 I dhcpcd  : bssid match
09-09 13:36:02.283  7668  7668 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,09-09 13:36:02.353  7668  7668 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
,09-09 13:36:02.383  6731  7664 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-09 13:36:02.383  6731  7664 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-09 13:36:02.383  6731  7664 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 13:36:02.383  6731  7664 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 13:36:02.383  6731  7664 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-09 13:36:02.383  6731  7675 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-09 13:36:02.393  6731  7675 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-09 13:36:02.393  6731  7678 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1421, name: OutgoingSocketThread/Receiver)
,09-09 13:36:02.393  6731  7675 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:36:02.393  6731  7678 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1421, thread name: OutgoingSocketThread/Receiver)
09-09 13:36:02.393  6731  7678 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-09 13:36:02.393  6731  7678 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1421, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-09 13:36:02.393  6731  7675 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 13:36:02.393  6731  7675 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-09 13:36:02.393  6731  7677 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1420, name: OutgoingSocketThread/Sender)
,09-09 13:36:02.393  6731  7679 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1422, name: IncomingSocketThread/Sender)
,09-09 13:36:02.393  6731  7680 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1423, name: IncomingSocketThread/Receiver)
,09-09 13:36:02.393  6731  7680 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1423, thread name: IncomingSocketThread/Receiver)
,09-09 13:36:02.393  6731  7680 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-09 13:36:02.393  6731  7680 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1423, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-09 13:36:02.463  7668  7668 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
,09-09 13:36:02.813  1015  1124 E WifiNative-wlan0: do suspend true
,09-09 13:36:02.843  1015  1123 D WifiP2pService: InactiveState{ what=143375 }
,09-09 13:36:02.843  1015  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-09 13:36:02.843  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 13:36:02.843  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-09 13:36:02.843  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:36:02.843  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:36:02.853  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:02.853  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:36:02.853  1015  1124 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-09 13:36:02.853  1015  1124 E WifiStateMachine: VerifyingLinkState enter
,09-09 13:36:02.853  1015  1126 E ConnectivityService: updateNetworkInfo()
,09-09 13:36:02.853  1015  1126 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
09-09 13:36:02.853  1015  1126 D ConnectivityService: Adding iface wlan0 to network 504
09-09 13:36:02.863  1015  1141 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
09-09 13:36:02.863  1015  1141 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-09 13:36:02.863  1015  1141 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-09 13:36:02.863  1015  1141 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-09 13:36:02.863  1015  1141 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-09 13:36:02.863  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-09 13:36:02.863  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:36:02.873  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:36:02.873  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:02.873  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:02.873  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:36:02.883  1015  1124 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,09-09 13:36:02.883  1015  1569 W ActivityManager: userId = 0, bbcId = -10000,
09-09 13:36:02.883  1015  1569 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 13:36:02.883  1015  1569 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
09-09 13:36:02.883  1015  1569 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-09 13:36:02.883  1015  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:36:02.893  1636  1636 I Hs20UtilService: Starting #25
,09-09 13:36:02.893  6731  6786 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1432),
,09-09 13:36:02.893  6731  6786 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-09 13:36:02.893  6731  6786 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1433)
,09-09 13:36:02.893  1636  1705 I Hs20UtilService: Message received 5007
,09-09 13:36:02.903  6731  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:36:02.903  6731  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f6db2 added. We now have 3 listener(s)
,09-09 13:36:02.903  1015  1126 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,09-09 13:36:02.903  1015  1126 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,09-09 13:36:02.903  1015  1126 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,09-09 13:36:02.913  6889  6889 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-09 13:36:02.913  6889  6889 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-09 13:36:02.913  1015  1124 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-09 13:36:02.913  1015  1124 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-09 13:36:02.913  1015  1126 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-09 13:36:02.913  1015  1126 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
09-09 13:36:02.913  1015  1126 D ConnectivityService: LTETest block dns file not exists
,09-09 13:36:02.913  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-09 13:36:02.923  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-09 13:36:02.923  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:36:02.923  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:36:02.923  6731  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:36:02.923  6731  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@114a2103 added. We now have 3 listener(s)
09-09 13:36:02.923  6731  6786 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:36:02.923  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:36:02.923  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 13:36:02.923  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:36:02.923  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:02.923  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:02.923  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:02.923  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:36:02.933  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-09 13:36:02.933  1015  1015 I WifiTrafficPoller: mBoosterFLAG : 0
,09-09 13:36:02.933  1015  1015 I WifiTrafficPoller: current booster mode : FullMode
,09-09 13:36:02.933  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:36:02.933  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-09 13:36:02.933  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:02.933  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:02.933  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:02.933  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:36:02.943  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:36:02.943  1015  1126 V NetworkStats: updateIfacesLocked()
,09-09 13:36:02.943  1015  1126 V NetworkStats: performPollLocked(flags=0x1)
09-09 13:36:02.943  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:36:02.953  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-09 13:36:02.953  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 13:36:02.963  1015  1126 V NetworkStats: performPollLocked() took 14ms
09-09 13:36:02.963  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:36:02.963  6731  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:36:02.963  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:02.963  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:36:02.963  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:02.963  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:02.963  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:36:02.963  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:36:02.963  6731  6786 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:36:02.963  6731  6786 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:36:02.963  1015  1533 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 13:36:02.963  6731  6786 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:36:02.963  1015  1533 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:36:02.963  1015  1533 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:36:02.963  1015  1533 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:36:02.963  1015  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:36:02.963  1636  1636 I Hs20UtilService: Starting #26
,09-09 13:36:02.973  1636  1705 I Hs20UtilService: Message received 5007
,09-09 13:36:02.973  6889  6889 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-09 13:36:02.973  6889  6889 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 13:36:02.973  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:02.973  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:36:02.973  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:02.973  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:36:02.973  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:36:02.973  6731  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f6db2 removed from the list
09-09 13:36:02.973  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:02.973  6731  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@114a2103 removed from the list
,09-09 13:36:02.973  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:36:02.973  6731  6786 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:02.973  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:02.973  6889  6889 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 13:36:02.973  1015  1126 E ConnectivityService: updateNetworkInfo()
09-09 13:36:02.973  1015  1126 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
09-09 13:36:02.973  1015  1126 E ConnectivityService: updateNetworkInfo()
09-09 13:36:02.973  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:36:02.973  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:36:02.973  1015  1126 V NetworkStats: updateIfacesLocked()
09-09 13:36:02.973  1015  1126 V NetworkStats: performPollLocked(flags=0x1)
,09-09 13:36:02.973  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:36:02.973  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 13:36:02.973  6889  6889 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-09 13:36:02.983  6889  6889 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 13:36:02.983  6889  6889 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-09 13:36:02.983  6889  6908 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 13:36:02.983  1015  1126 V NetworkStats: performPollLocked() took 3ms
09-09 13:36:02.983  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:36:02.983  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:36:02.983  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:36:02.983  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:36:02.983  1015  1126 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
09-09 13:36:02.983  1015  7666 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:02.983  1015  1126 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
09-09 13:36:02.983  1015  7666 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
09-09 13:36:02.983  1015  7666 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:02.983  1015  7666 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,09-09 13:36:02.983  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:36:02.983  1015  7666 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:36:02.983  6731  6786 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
09-09 13:36:02.983  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
09-09 13:36:02.983  6731  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:36:02.983  6731  6786 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-09 13:36:02.983  6731  6786 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:36:02.983  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:36:02.983   280  1009 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-09 13:36:02.983  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 13:36:02.983   280  1009 D Netd    : getNetworkForDns: using netid 504 for uid 1000
,09-09 13:36:02.983  6731  6786 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true,
09-09 13:36:02.983  6731  6786 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-09 13:36:02.983  6731  6731 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 13:36:02.993  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:36:02.993  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-09 13:36:02.993  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:36:02.993  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 13:36:02.993  1015  1126 D ConnectivityService:    accepting network in place of null
,09-09 13:36:02.993  1015  1124 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,09-09 13:36:02.993  1015  1123 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-09 13:36:02.993  1454  1454 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-09 13:36:02.993  1454  1454 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-09 13:36:02.993  1015  1126 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-09 13:36:02.993  1015  1126 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
09-09 13:36:02.993  1015  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-09 13:36:03.003  1015  1126 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,09-09 13:36:03.003  1015  1126 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,09-09 13:36:03.003  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,09-09 13:36:03.003  1015  1127 D Tethering: MasterInitialState.processMessage what=3
09-09 13:36:03.003  6731  7707 D BluetoothSocket: bindListen(): myUserId = 0
09-09 13:36:03.003  1015  1121 V NetworkStats: updateIfacesLocked()
09-09 13:36:03.003  6731  7707 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:36:03.003  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
09-09 13:36:03.003  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:36:03.003  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:36:03.003  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 13:36:03.013  1015  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-09 13:36:03.013  1015  1571 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 13:36:03.013  1015  1571 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-09 13:36:03.013  1015  1121 V NetworkStats: performPollLocked() took 5ms
09-09 13:36:03.013  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:36:03.013  1177  1602 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 13:36:03.013  4748  6795 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 13:36:03.013  1015  1571 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:36:03.013  1015  1571 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:36:03.013  1015  1571 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:36:03.013  6731  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 13:36:03.013  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
,09-09 13:36:03.013  6731  7707 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[109]}
09-09 13:36:03.013  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-09 13:36:03.013  6731  7707 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 13:36:03.013  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-09 13:36:03.013  6731  7707 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 13:36:03.013  1177  1177 D StatusBar.NetworkController: updateDataNetType(),
09-09 13:36:03.013  1177  1177 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-09 13:36:03.013  1015  1122 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-09 13:36:03.013  6731  7707 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2f22b2fe
09-09 13:36:03.013  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-09 13:36:03.013  1636  1636 I Hs20UtilService: Starting #27
09-09 13:36:03.013  6731  7707 D BluetoothSocket: channel: 6
09-09 13:36:03.013  6731  7707 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-09 13:36:03.013  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:36:03.013  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:36:03.013  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:36:03.013  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit,
,09-09 13:36:03.023  1636  1705 I Hs20UtilService: Message received 5007
09-09 13:36:03.023  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:36:03.023  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:36:03.023  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 13:36:03.023  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:36:03.023  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-09 13:36:03.023  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-09 13:36:03.023  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,09-09 13:36:03.023  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:36:03.023  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-09 13:36:03.023  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:03.023  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:03.023  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:03.023  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:03.023  6889  6889 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-09 13:36:03.033  6889  6889 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-09 13:36:03.033  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-09 13:36:03.033  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-09 13:36:03.033  6731  6786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 08 EC A9 50 76 27
,09-09 13:36:03.033  6731  6786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 8, -20, -87, 80, 118, 39]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:36:03.033  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 8, -20, -87, 80, 118, 39]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:36:03.033  6731  6786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-09 13:36:03.033  3179  7516 D BtGatt.GattService: registerClient() - UUID=5104117d-a368-42bd-bf1c-262ce6eb569d
,09-09 13:36:03.033  1015  1486 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0,
,09-09 13:36:03.043  1015  1323 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
09-09 13:36:03.043  1015  1323 D SecContentProvider2: mCursor = null
,09-09 13:36:03.043  1015  1027 D SecContentProvider2: uri = 15 selection = getToastGravity
09-09 13:36:03.043  1015  1027 D SecContentProvider2: mCursor = null
,09-09 13:36:03.043  1015  1570 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
09-09 13:36:03.043  1015  1570 D SecContentProvider2: mCursor = null
09-09 13:36:03.043  1015  1571 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset,
09-09 13:36:03.043  1015  1571 D SecContentProvider2: mCursor = null
,09-09 13:36:03.043  1015  1028 D SecContentProvider2: uri = 15 selection = getToastEnabledState
09-09 13:36:03.043  1015  1028 D SecContentProvider2: mCursor = null
,09-09 13:36:03.043  1015  1376 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
09-09 13:36:03.043  1015  1376 D SecContentProvider2: mCursor = null
,09-09 13:36:03.073   257   257 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=4, Uoast
,09-09 13:36:03.073  3179  3275 D BtGatt.GattService: onClientRegistered() - UUID=5104117d-a368-42bd-bf1c-262ce6eb569d, clientIf=5
,09-09 13:36:03.083  6731  6744 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-09 13:36:03.083  3179  7467 D BtGatt.AdvertiseManager: message : 0
,09-09 13:36:03.083  3179  7467 D BtGatt.AdvertiseManager: number of adv instance running0
,09-09 13:36:03.083  3179  7467 D BtGatt.AdvertiseManager: size of list is =0
,09-09 13:36:03.083  1015  1323 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015
,09-09 13:36:03.083  3179  7467 D BtGatt.AdvertiseManager: starting advertising
09-09 13:36:03.083  3179  7467 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-09 13:36:03.093  3179  3275 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-09 13:36:03.093  3179  7467 D BtGatt.AdvertiseManager: starting multi advertising
,09-09 13:36:03.093  3179  3275 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-09 13:36:03.093  3179  7467 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-09 13:36:03.093  3179  7467 D BtGatt.AdvertiseManager: clientIf: 5, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-09 13:36:03.093  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-09 13:36:03.093  6731  6786 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 13:36:03.103  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:36:03.103  1177  1177 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-09 13:36:03.103  6731  6731 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:36:03.103  6731  6731 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-09 13:36:03.103  6731  6731 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-09 13:36:03.103  6731  6731 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-09 13:36:03.103  6731  6731 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-09 13:36:03.103  6731  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-09 13:36:03.103  1015  7666 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-09 13:36:03.103  6731  6731 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:36:03.103  6731  6731 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:36:03.153  1015  7666 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 11:36:03 GMT], X-Android-Received-Millis=[1473420963168], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473420963142]}
,09-09 13:36:03.153  1015  7666 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-09 13:36:03.153  1015  7666 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,09-09 13:36:03.153  1015  1126 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
09-09 13:36:03.153  1015  1126 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
09-09 13:36:03.153  1015  1126 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
09-09 13:36:03.153  1015  1126 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,09-09 13:36:03.163  1177  1602 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-09 13:36:03.163  1015  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-09 13:36:03.163  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
,09-09 13:36:03.163  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
,09-09 13:36:03.163  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-09 13:36:03.163  1177  1177 D StatusBar.NetworkController: updateDataNetType()
,09-09 13:36:03.163  1177  1177 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-09 13:36:03.163  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-09 13:36:03.163  4748  6795 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-09 13:36:03.163  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,09-09 13:36:03.173  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-09 13:36:03.173  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,09-09 13:36:03.173  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:36:03.173  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-09 13:36:03.173  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:03.173  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:03.173  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:36:03.173  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:36:03.503  1015  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:36:03.523  1015  1039 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:36:03.523  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:03.523  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:03.523  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:36:03.523  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:03.523  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:03.523  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:03.523  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:03.523  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:36:03.533  6731  6731 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:36:03.533  7600  7600 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-09 13:36:03.533  7600  7600 I PCWCLIENTTRACE_PushUtil: sales region : global
09-09 13:36:03.533  7600  7600 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-09 13:36:03.533  7600  7600 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:36:03.533  1015  1376 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
,09-09 13:36:03.533  1015  1376 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
09-09 13:36:03.543  6731  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:03.543  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:03.543  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:36:03.543  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:03.543  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:03.543  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:03.543  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:03.543  6731  6731 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:36:03.543  6731  6731 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:36:03.553  1788  1788 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-09 13:36:03.553  7354  7354 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:36:03.563  1015  1323 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,09-09 13:36:03.563  1015  1323 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:03.563  1015  1323 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:03.563  1015  1323 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:03.563  1015  1323 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:03.563  7354  7354 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
09-09 13:36:03.563  7354  7354 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-09 13:36:03.583  2485  2495 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 11
09-09 13:36:03.583  7713  7713 E Zygote  : MountEmulatedStorage()
,09-09 13:36:03.583  7713  7713 E Zygote  : v2
09-09 13:36:03.583  7713  7713 I libpersona: KNOX_SDCARD checking this for 10031
09-09 13:36:03.583  7713  7713 I libpersona: KNOX_SDCARD not a persona
,09-09 13:36:03.583  1015  1323 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7713 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a,
,09-09 13:36:03.583  1015  1571 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
09-09 13:36:03.583  1015  1571 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,09-09 13:36:03.583  7713  7713 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-09 13:36:03.583  1015  1571 W ActivityManager: userId = 0, bbcId = -10000,
09-09 13:36:03.583  1015  1571 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:36:03.583  1015  1571 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,09-09 13:36:03.583  1788  1788 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
09-09 13:36:03.593  1788  1788 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
09-09 13:36:03.593  1788  1788 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
09-09 13:36:03.593  1788  1788 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
09-09 13:36:03.593  7713  7713 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 13:36:03.593  7090  7090 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:03.593  7090  7090 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-09 13:36:03.593  7090  7090 I DIAGMON_AGENT: ./extraInfo: "NG700"
09-09 13:36:03.593  7090  7090 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
09-09 13:36:03.593  7713  7713 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:36:03.603  1788  1788 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-09 13:36:03.613  6731  6731 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-09 13:36:03.613  1015  1539 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 13:36:03.613  6731  6731 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-09 13:36:03.613  6731  6731 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 13:36:03.613  1015  1486 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 13:36:03.613  1788  1788 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,09-09 13:36:03.613  7713  7713 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:36:03.613  7713  7713 D ActivityThread: Added TimaKeyStore provider
,09-09 13:36:03.633  7190  7190 D WaitQueueForNetworkActivate: notifyNetworkActivated
09-09 13:36:03.633  1015  1477 D ActivityManager: startService callerProcessName:com.android.chrome, calleePkgName: com.android.chrome
09-09 13:36:03.633  1015  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService; callingUser = 0; userId(target) = 0
,09-09 13:36:03.633  1015  1477 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:36:03.633  1015  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:36:03.633  1015  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.chrome, destAppInfo.processName = com.android.chrome
,09-09 13:36:03.633  1015  1132 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,09-09 13:36:03.633  1015  1132 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,09-09 13:36:03.643  1015  1132 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:36:03.643  1015  1132 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-09 13:36:03.643  1015  1132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,09-09 13:36:03.653  7190  7190 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,09-09 13:36:03.653  7190  7190 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,09-09 13:36:03.653  7190  7190 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
09-09 13:36:03.653  7190  7190 D InitializeManagerStateMachine: exit::IDLE
09-09 13:36:03.653  7190  7190 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,09-09 13:36:03.653  7190  7190 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
09-09 13:36:03.653  7190  7190 D InitializeManagerStateMachine: exit::NETWORK_CHECK
09-09 13:36:03.653  7190  7190 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
09-09 13:36:03.653  7190  7190 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
09-09 13:36:03.653  7190  7190 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
09-09 13:36:03.653  7190  7190 D InitializeManagerStateMachine: entry::SUCCESS
09-09 13:36:03.653  7190  7190 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,09-09 13:36:03.653  1015  1533 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 13:36:03.653  1015  1533 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-09 13:36:03.653  1015  1533 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:36:03.653  1015  1533 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:36:03.653  1015  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:36:03.663  1015  1323 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
09-09 13:36:03.663  7190  7190 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
09-09 13:36:03.663  7190  7190 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,09-09 13:36:03.663  1015  1323 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-09 13:36:03.663  7190  7190 D InitializeManagerStateMachine: exit::SUCCESS
09-09 13:36:03.663  7190  7190 D InitializeManagerStateMachine: entry::IDLE
,09-09 13:36:03.663  1015  3363 D SSRM:n  : SIOP:: AP = 340
,09-09 13:36:03.663  1015  1323 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:36:03.663  1015  1323 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:36:03.663  1015  1323 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-09 13:36:03.673   280  1009 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-09 13:36:03.673   280  1009 D Netd    : getNetworkForDns: using netid 504 for uid 10011
,09-09 13:36:03.673  6911  7731 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:36:03.683  4748  4748 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-09 13:36:03.683  4748  7207 I iu.UploadsManager: num queued entries: 0
,09-09 13:36:03.683  4748  7207 I iu.UploadsManager: num updated entries: 0
,09-09 13:36:03.683  6911  7731 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:36:03.693  4748  7207 I iu.SyncManager: NEXT; no task
,09-09 13:36:03.693   280  1009 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-09 13:36:03.693   280  1009 D Netd    : getNetworkForDns: using netid 504 for uid 10102
,09-09 13:36:03.723  7152  7152 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,09-09 13:36:03.723  2777  7735 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,09-09 13:36:03.723  2777  7735 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,09-09 13:36:03.723  2777  7735 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-09 13:36:03.733  7152  7152 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,09-09 13:36:03.733  7152  7152 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
09-09 13:36:03.733  7078  7078 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,09-09 13:36:03.733  7152  7152 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
09-09 13:36:03.733  6911  7731 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-09 13:36:03.733  7112  7112 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,09-09 13:36:03.733  7112  7112 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,09-09 13:36:03.733  7112  7112 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-09 13:36:03.743  2922  2922 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Sep 09 13:36:03 GMT+02:00 2016
,09-09 13:36:03.743  1015  1486 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-09 13:36:03.743  1015  1486 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-09 13:36:03.743  1015  1486 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:36:03.743  1015  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:36:03.743  1015  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-09 13:36:03.743  7112  7112 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,09-09 13:36:03.743  7112  7112 I SA      : [OR] == isSIMCardReady false ==
,09-09 13:36:03.743  7112  7112 I SA      : [SCU] == networkStateCheck == true
,09-09 13:36:03.753  7112  7112 I SA      : [DM] getCountryCodeFromCSC : PL
09-09 13:36:03.753  7112  7112 I SA      : isChinaCountryCode : false
09-09 13:36:03.753  7112  7112 I SA      : [SCU] is ChinestModel Data Restricted   : false
09-09 13:36:03.753  7112  7112 I SA      : [OR] == networkStateCheck true ==
09-09 13:36:03.753  7112  7112 I SA      : [OR] GetMyCountryZoneTask
,09-09 13:36:03.753  7112  7112 I SA      : [OR] onReceive END
,09-09 13:36:03.753  2922  2922 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-09 13:36:03.753  1221  1221 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:36:03.753  2922  2922 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-09 13:36:03.763  2922  2922 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
09-09 13:36:03.763  1015  1486 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
09-09 13:36:03.763  7112  7736 I SA      : [SRS] prepareGetMyCountryZone
,09-09 13:36:03.763  1015  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,09-09 13:36:03.763  2777  7735 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,09-09 13:36:03.763  1015  1486 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:36:03.763  1015  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:36:03.763  1015  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,09-09 13:36:03.763  2777  7735 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,09-09 13:36:03.763  2777  7735 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
09-09 13:36:03.763  1015  1570 I splitIntent: Queue : backgroundsplit_0 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,09-09 13:36:03.763  2777  7735 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,09-09 13:36:03.763  2777  7735 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,09-09 13:36:03.763  2922  2922 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-09 13:36:03.763  2777  7735 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,09-09 13:36:03.773  2777  7735 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,09-09 13:36:03.773  7112  7736 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,09-09 13:36:03.773  7112  7736 I SA      : [SSP] query invoked
09-09 13:36:03.773  2777  7735 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
09-09 13:36:03.773  2922  7737 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-09 13:36:03.773  2922  7737 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-09 13:36:03.773  7112  7736 I SA      : [TPMU] GetMccFromDB : null
09-09 13:36:03.773  7112  7736 I SA      : [SCU] getMccFromPreferece mcc = 260
09-09 13:36:03.773  7112  7736 I SA      : [LBE] isSupportCheckDomainRegion : false
09-09 13:36:03.773  7112  7736 I SA      : [TPM] isNoProxy(default) : true
09-09 13:36:03.773  7112  7736 I SA      : [RC New] Execute method=[GET] start
,09-09 13:36:03.773  2777  7735 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,09-09 13:36:03.783  2922  7737 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,09-09 13:36:03.783  2922  7737 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().START
09-09 13:36:03.783  1015  1323 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
09-09 13:36:03.783  1015  1323 D SecContentProvider2: mCursor = null
,09-09 13:36:03.783  2922  7737 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().START 
,09-09 13:36:03.793  2777  7735 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,09-09 13:36:03.793  2922  7737 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().END 
,09-09 13:36:03.793  2922  7737 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,09-09 13:36:03.793  6911  7731 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-09 13:36:03.793  2922  2922 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-09 13:36:03.793  1015  1376 I ActivityManager: Killing 7420:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,09-09 13:36:03.823  7112  7736 I SA      : [RC New] Security=[true]
,09-09 13:36:03.823  7112  7736 I System.out: Thread-1298(ApacheHTTPLog):isSBSettingEnabled false
09-09 13:36:03.823  7112  7736 I System.out: Thread-1298(ApacheHTTPLog):isShipBuild true
09-09 13:36:03.823  7112  7736 I System.out: Thread-1298(ApacheHTTPLog):SMARTBONDING_ENABLED is false
09-09 13:36:03.823  7112  7736 I System.out: Thread-1298(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,09-09 13:36:03.823   280  1009 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-09 13:36:03.823   280  1009 D Netd    : getNetworkForDns: using netid 504 for uid 10036
,09-09 13:36:03.823  1963  7730 I qtaguid : Tagging socket 47 with tag 1000040700000000{268436487,0} for uid -1, pid: 1963, getuid(): 10011
,09-09 13:36:03.883   290   290 E SMD     : DCD OFF,
,09-09 13:36:03.963  1015  1569 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,09-09 13:36:03.963  1015  1569 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,09-09 13:36:03.973  1015  1569 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:36:03.973  1015  1569 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-09 13:36:03.973  1015  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,09-09 13:36:03.983  1015  1040 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:36:03.983  1015  1040 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 13:36:03.983  1015  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,09-09 13:36:04.003  1015  1126 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 503] cleared because we found a replacement network
,09-09 13:36:04.003  7190  7190 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE
,09-09 13:36:04.003  7190  7190 D PreloadUpdateManagerStateMachine: exit::IDLE
09-09 13:36:04.003  7190  7190 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,09-09 13:36:04.013  7190  7190 D hcjo    : AutoUpdateTriggerManager:REQUEST2:requestInterval
,09-09 13:36:04.043  7190  7190 I Volley  : RestApi Request Add : 2307
,09-09 13:36:04.053  7190  7190 E File    : fail readDirectory() errno=2
,09-09 13:36:04.073  1015  1126 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-09 13:36:04.073  1015  1126 V NetworkStats: updateIfacesLocked()
,09-09 13:36:04.073  1015  1126 V NetworkStats: performPollLocked(flags=0x1)
09-09 13:36:04.073  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:36:04.073  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-09 13:36:04.073  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 13:36:04.083  1015  1126 V NetworkStats: performPollLocked() took 7ms
,09-09 13:36:04.083  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:36:04.083  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:36:04.083  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:36:04.083  1015  1126 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,09-09 13:36:04.083  1177  1602 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-09 13:36:04.093  1015  1126 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,09-09 13:36:04.093  1177  1602 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-09 13:36:04.093  4748  6795 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-09 13:36:04.093  4748  6795 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-09 13:36:04.513  7190  7742 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,09-09 13:36:04.513  7190  7742 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:36:04.513  7190  7742 I System.out: (HTTPLog)-Static: isShipBuild true
09-09 13:36:04.513  7190  7742 I System.out: (HTTPLog)-Thread-1316-582370483: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,09-09 13:36:04.513  7190  7742 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:36:04.513   280  1009 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-09 13:36:04.513   280  1009 D Netd    : getNetworkForDns: using netid 504 for uid 10009
,09-09 13:36:04.583  7190  7742 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-09 13:36:04.583  7190  7742 I qtaguid : Tagging socket 26 with tag 79a327ee00000000{2040735726,0} for uid -1, pid: 7190, getuid(): 10009
,09-09 13:36:04.683  7190  7742 I qtaguid : Untagging socket 26
,09-09 13:36:04.703  7190  7190 D hcjo    : AutoUpdateTriggerManager:REQUEST2:setInterval:86400000
09-09 13:36:04.703  7190  7190 D hcjo    : AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime
,09-09 13:36:04.733  7190  7190 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:TIMED_OUT,
09-09 13:36:04.733  7190  7190 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
,09-09 13:36:04.733  7190  7190 D PreloadUpdateManagerStateMachine: entry::REQ_UPDATE_CHECK
,09-09 13:36:04.743  7190  7190 I Volley  : RestApi Request Add : 2315
,09-09 13:36:04.743  7190  7743 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:36:04.753  7190  7743 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-09 13:36:04.753  7190  7743 I qtaguid : Tagging socket 28 with tag 79a327ee00000000{2040735726,0} for uid -1, pid: 7190, getuid(): 10009
,09-09 13:36:05.223  7190  7743 I qtaguid : Untagging socket 28
,09-09 13:36:05.223  7190  7190 D PreloadUpdateManagerStateMachine: execute::REQ_UPDATE_CHECK:REQUEST_SUCCESS
,09-09 13:36:05.223  7190  7190 D PreloadUpdateManagerStateMachine: exit::REQ_UPDATE_CHECK
09-09 13:36:05.223  7190  7190 D PreloadUpdateManagerStateMachine: entry::NOTIFY_NOTIFICATION
09-09 13:36:05.223  7190  7190 D PreloadUpdateManagerStateMachine: exit::NOTIFY_NOTIFICATION
09-09 13:36:05.223  7190  7190 D PreloadUpdateManagerStateMachine: entry::FINISH
,09-09 13:36:05.233  7190  7190 D PreloadUpdateManagerStateMachine: exit::FINISH
,09-09 13:36:05.233  7190  7190 D PreloadUpdateManagerStateMachine: entry::IDLE,
,09-09 13:36:05.433  7112  7736 I SA      : [RC New] [v2liruge] api execute + 1602
,09-09 13:36:05.433  7112  7736 I SA      : [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,09-09 13:36:05.433  7112  7736 I System.out: AsyncTask #2 calls detatch()
,09-09 13:36:05.433  7112  7736 I SA      : [ODM] saveOpenData( GEO_IP, PL )
,09-09 13:36:05.433  7112  7736 I SA      : [OCP] update openData : PL
09-09 13:36:05.433  7112  7736 I SA      : [TPMU] getNetworkMcc : 
09-09 13:36:05.433  7112  7736 I SA      : [SCU] saveMccToPreferece Start
09-09 13:36:05.433  7112  7736 I SA      : [SCU] RegionMCC : 260
09-09 13:36:05.433  7112  7736 I SA      : [SSP] query invoked
09-09 13:36:05.433  7112  7736 I SA      : [TPMU] GetMccFromDB : null
09-09 13:36:05.433  7112  7736 I SA      : [SCU] getMccFromPreferece mcc = 260
09-09 13:36:05.433  7112  7736 I SA      : [SCU] saveMccToPreferece End
09-09 13:36:05.433  7112  7736 I SA      : [RC New] executeRequest [v2liruge] end. 1663
09-09 13:36:05.433  7112  7736 I SA      : [RC New] Execute end
09-09 13:36:05.433  7112  7112 I SA      : [OR] GetMyCountryZoneTask mcc = 260
09-09 13:36:05.443  7112  7112 I SA      : [OR] GetMyCountryZoneTask Success
,09-09 13:36:05.953  1015  1146 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.
,09-09 13:36:06.473  7668  7668 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,09-09 13:36:06.563   257   448 I SurfaceFlinger: id=15 Removed Uoast (8/9)
,09-09 13:36:06.563   257   451 I SurfaceFlinger: id=15 Removed Uoast (-2/9)
,09-09 13:36:06.563  1015  1477 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1015) eventTime = 154736
,09-09 13:36:06.563  1015  1477 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015 (0x0)
,09-09 13:36:06.573  1015  1477 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1015, ws=WorkSource{10049}) (elapsedTime=3484)
,09-09 13:36:06.603  6731  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything,
09-09 13:36:06.603  6731  6786 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 13:36:06.603  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 13:36:06.603  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 13:36:06.603  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 13:36:06.603  6731  6786 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@9804cac, channel: 6, state: LISTENING
09-09 13:36:06.603  6731  6786 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@9804cac, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2f22b2fe, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1c053d75mSocket: android.net.LocalSocket@473010a impl:android.net.LocalSocketImpl@704ad7b fd:FileDescriptor[109]
09-09 13:36:06.603  6731  6786 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@473010a impl:android.net.LocalSocketImpl@704ad7b fd:FileDescriptor[109]
09-09 13:36:06.603  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:36:06.603  6731  6786 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:36:06.603  6731  7707 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@9804cac, channel: 6, state: CLOSED,
09-09 13:36:06.603  6731  7707 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 13:36:06.603  6731  7707 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 13:36:06.603  6731  7707 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 13:36:06.603  6731  6731 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-09 13:36:06.603  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 13:36:06.603  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:36:06.603  6731  6786 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:36:06.603  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:36:06.603  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 13:36:06.613  6731  6786 D BluetoothLeScanner: could not find callback wrapper
09-09 13:36:06.613  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 13:36:06.613  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-09 13:36:06.613  3179  7467 D BtGatt.AdvertiseManager: message : 1
09-09 13:36:06.613  3179  7467 D BtGatt.AdvertiseManager: stop advertise for client 5
09-09 13:36:06.613  3179  7467 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf5
09-09 13:36:06.613  3179  7467 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-09 13:36:06.623  3179  3275 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-09 13:36:06.623  3179  3275 D BtGatt.GattService: Client app is not null!
,09-09 13:36:06.623  3179  7518 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 13:36:06.623  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 13:36:06.623  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-09 13:36:06.623  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-09 13:36:06.623  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-09 13:36:06.623  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-09 13:36:06.623  6731  6786 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:36:06.623  6731  6786 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 13:36:06.623  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 13:36:06.623  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:36:06.633  6731  6731 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 13:36:06.633  6731  6731 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 13:36:06.633  6731  6731 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-09 13:36:06.633  6731  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:36:06.633  6731  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:36:06.633  6731  6731 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:36:06.633  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:36:06.633  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:06.633  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:36:06.633  6731  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f6db2 not in the list
09-09 13:36:06.633  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:36:06.633  6731  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@114a2103 not in the list
,09-09 13:36:06.633  6731  6786 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:06.633  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:36:06.633  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:36:06.633  6731  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 13:36:06.633  6731  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 13:36:06.633  6731  6786 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 13:36:06.643  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 13:36:06.643  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:36:06.643  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 13:36:06.643  6731  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 13:36:06.653  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 13:36:06.653  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:36:06.653  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 13:36:06.653  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-09 13:36:06.663  6731  6786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 13:36:06.663  3179  7518 D BtGatt.GattService: registerClient() - UUID=0ecf9336-be90-462d-8ec5-7e928d6ea1d0
,09-09 13:36:06.703  3179  3275 D BtGatt.GattService: onClientRegistered() - UUID=0ecf9336-be90-462d-8ec5-7e928d6ea1d0, clientIf=5
,09-09 13:36:06.703  6731  6744 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-09 13:36:06.713  3179  7516 D BtGatt.GattService: start scan with filters
,09-09 13:36:06.713  3179  7468 D BtGatt.ScanManager: handling starting scan
,09-09 13:36:06.713  3179  7468 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ce19ede
,09-09 13:36:06.713  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 13:36:06.713  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-09 13:36:06.713  3179  3275 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-09 13:36:06.713  3179  3275 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:36:06.713  3179  7468 D BtGatt.ScanManager: allow scan with filters
,09-09 13:36:06.713  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 13:36:06.723  3179  7468 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-09 13:36:06.723  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 13:36:06.723  6731  6786 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 13:36:06.723  3179  7468 D BtGatt.ScanManager: set filter index= 3 for clientIf= 5
,09-09 13:36:06.723  6731  6786 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 13:36:06.723  6731  6731 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 13:36:06.723  3179  3275 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-09 13:36:06.723  3179  3275 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:36:06.723  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:36:06.733  3179  7468 D BtGatt.ScanManager: Starting BLE batch scan
09-09 13:36:06.733  3179  7468 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-09 13:36:06.733  3179  3275 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-09 13:36:06.733  3179  3275 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:36:06.733  1015  1571 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
09-09 13:36:06.733  1015  1571 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,09-09 13:36:06.733  1015  1571 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:36:06.733  1015  1571 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-09 13:36:06.733  1015  1571 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,09-09 13:36:06.733  3179  3275 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-09 13:36:06.733  3179  3275 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:36:06.883   290   290 E SMD     : DCD OFF
,09-09 13:36:07.233  6731  6731 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-09 13:36:07.233  6731  6731 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 13:36:07.233  6731  6731 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 13:36:07.233  1015  1093 V AlarmManager: waitForAlarm result :4
,09-09 13:36:07.243  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,09-09 13:36:07.243  3179  3179 D BtGatt.ScanManager: awakened up at time 155417
,09-09 13:36:07.253  1177  1177 D KeyguardUpdateMonitor: handleTimeUpdate
,09-09 13:36:07.253  3179  7468 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 13:36:07.253  3179  3275 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-09 13:36:07.253  3179  3275 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:36:07.263  1177  1177 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,09-09 13:36:07.263  1177  1177 D SecKeyguardClockView: HomeTimezone(): 1,
09-09 13:36:07.273  1177  1177 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
09-09 13:36:07.273  1177  1177 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,09-09 13:36:07.273  1177  1177 I KeyguardEffectViewController: *** don't update sliding image ***
,09-09 13:36:07.283  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-09 13:36:07.313  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-09 13:36:07.313  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-09 13:36:07.323  1177  1177 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,09-09 13:36:07.333  1177  1177 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-09 13:36:07.753  1015  1093 V AlarmManager: waitForAlarm result :4
,09-09 13:36:07.763  3179  3179 D BtGatt.ScanManager: awakened up at time 155931
,09-09 13:36:07.763  3179  7468 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 13:36:07.763  3179  3275 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,09-09 13:36:07.773  3179  3275 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
09-09 13:36:07.773  3179  3275 D BtGatt.GattService: current time is 155940338272
09-09 13:36:07.773  3179  3275 D BtGatt.GattService: Batch record : [-111, 106, -71, 88, -82, -32, 1, 0, -99, 65, 1, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -41, -99, 80, -91, 54, 55, -87, 70, -64, -77, -5, 2, 2, -25, 21, -21, -17, 89, -11, 28, 6, 8, 116, 105, 102, 55, 50, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 81, 34, 97, 112, -14, -5, 1, -128, -72, -122, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -56, 116, 70, 79, 58, 115, 1, -128, -63, 19, 1, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -112, -25, -60, -2, -84, -17, 0, -2, 14, 103, -92, -100, 125, 1, -128, -63, 24, 1, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 124, -7, 14, 52, -118, -96, 0]
,09-09 13:36:07.773  3179  3275 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -41, -99, 80, -91, 54, 55, -87, 70, -64, -77, -5, 2, 2, -25, 21, -21, -17, 89, -11, 6, 8, 116, 105, 102, 55, 50, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
09-09 13:36:07.773  3179  3275 D ScanRecord: parseFromBytes
09-09 13:36:07.773  3179  3275 D ScanRecord: first manudata for manu ID
09-09 13:36:07.773  3179  3275 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-09 13:36:07.773  3179  3275 D ScanRecord: parseFromBytes
09-09 13:36:07.773  3179  3275 D ScanRecord: first manudata for manu ID
09-09 13:36:07.783  3179  3275 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -112, -25, -60, -2, -84, -17]
09-09 13:36:07.783  3179  3275 D ScanRecord: parseFromBytes
09-09 13:36:07.783  3179  3275 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 124, -7, 14, 52, -118, -96]
09-09 13:36:07.783  3179  3275 D ScanRecord: parseFromBytes
09-09 13:36:07.783  3179  3275 D BtGatt.GattService: result: ScanResult{mDevice=73:3A:4F:46:74:C8, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[5, -112, -25, -60, -2, -84, -17]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-63, mTimestampNanos=142190736553}
09-09 13:36:07.783  3179  3275 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
09-09 13:36:07.783  3179  3275 D BtGatt.GattService: result: ScanResult{mDevice=FB:F2:70:61:22:51, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-72, mTimestampNanos=149240736553}
09-09 13:36:07.783  3179  3275 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
09-09 13:36:07.783  3179  3275 D BtGatt.GattService: result: ScanResult{mDevice=7D:9C:A4:67:0E:FE, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[5, 124, -7, 14, 52, -118, -96]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-63, mTimestampNanos=141940736553}
09-09 13:36:07.783  3179  3275 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
09-09 13:36:07.783  3179  3275 D BtGatt.GattService: result: ScanResult{mDevice=E0:AE:58:B9:6A:91, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[00001804-0000-1000-8000-00805f9b34fb, bec26202-a8d8-4a94-80fc-9ac1de37daa6], mManufacturerSpecificData={249=[1, -41, -99, 80, -91, 54, 55, -87, 70, -64, -77, -5, 2, 2, -25, 21, -21, -17, 89, -11]}, mServiceData={}, mTxPowerLevel=0, mDeviceName=tif72], mRssi=-99, mTimestampNanos=139890736553}
09-09 13:36:07.783  3179  3275 D BtGatt.GattService: filter: BluetoothLeScanFilter [,mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
09-09 13:36:07.783  6731  6744 D ScanRecord: parseFromBytes
09-09 13:36:07.783  6731  6744 D ScanRecord: parseFromBytes
09-09 13:36:07.783  6731  6744 D ScanRecord: first manudata for manu ID,
09-09 13:36:07.783  6731  6744 D ScanRecord: parseFromBytes
09-09 13:36:07.783  6731  6744 D ScanRecord: parseFromBytes
09-09 13:36:07.783  6731  6744 D ScanRecord: first manudata for manu ID,
,09-09 13:36:07.783  6731  6731 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 90:E7:C4:FE:AC:EF 5], added - the peer count is 1,
09-09 13:36:07.783  6731  6731 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:34:8A:A0 5], added - the peer count is 2
09-09 13:36:07.783  6731  6731 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 90:E7:C4:FE:AC:EF 5], Bluetooth address: 90:E7:C4:FE:AC:EF, device name: '', device address: '',
09-09 13:36:07.783  6731  6731 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:34:8A:A0 5], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: '', device address: ''
,09-09 13:36:08.273  1015  1093 V AlarmManager: waitForAlarm result :4
,09-09 13:36:08.273  3179  3179 D BtGatt.ScanManager: awakened up at time 156444
,09-09 13:36:08.273  3179  7468 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 13:36:08.293  3179  3275 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=9
09-09 13:36:08.293  3179  3275 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:36:08.293  3179  3275 D BtGatt.GattService: current time is 156460787698
,09-09 13:36:08.293  3179  3275 D BtGatt.GattService: Batch record : [-2, 14, 103, -92, -100, 125, 1, -128, -64, -42, 1, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 124, -7, 14, 52, -118, -96, 0, 71, -122, -77, 84, 69, -12, 1, -128, -72, 77, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -74, -71, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -74, -33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -72, 7, 1, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -80, 40, 1, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -80, 79, 1, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 50, -35, 86, -77, -92, -11, 1, -128, -96, -59, 1, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80,, -12, -76, -5, 2, 2, -37, 21, -22, 114, -52, -26, 0, -56, 116, 70, 79, 58, 115, 1, -128, -63, -40, 1, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -112, -25, -60, -2, -84, -17, 0]
09-09 13:36:08.293  3179  3275 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 124, -7, 14, 52, -118, -96]
09-09 13:36:08.293  3179  3275 D ScanRecord: parseFromBytes
,09-09 13:36:08.293  3179  3275 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-09 13:36:08.293  3179  3275 D ScanRecord: parseFromBytes
09-09 13:36:08.293  3179  3275 D ScanRecord: first manudata for manu ID
09-09 13:36:08.293  3179  3275 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113],
09-09 13:36:08.293  3179  3275 D ScanRecord: parseFromBytes
09-09 13:36:08.293  3179  3275 D ScanRecord: first manudata for manu ID
09-09 13:36:08.293  3179  3275 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6],
09-09 13:36:08.293  3179  3275 D ScanRecord: parseFromBytes
09-09 13:36:08.293  3179  3275 D ScanRecord: first manudata for manu ID
09-09 13:36:08.293  3179  3275 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-09 13:36:08.293  3179  3275 D ScanRecord: parseFromBytes
09-09 13:36:08.293  3179  3275 D ScanRecord: first manudata for manu ID
09-09 13:36:08.293  3179  3275 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,09-09 13:36:08.293  3179  3275 D ScanRecord: parseFromBytes
09-09 13:36:08.293  3179  3275 D ScanRecord: first manudata for manu ID,
09-09 13:36:08.293  3179  3275 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-09 13:36:08.293  3179  3275 D ScanRecord: parseFromBytes
09-09 13:36:08.293  3179  3275 D ScanRecord: first manudata for manu ID
09-09 13:36:08.293  3179  3275 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, -12, -76, -5, 2, 2, -37, 21, -22, 114, -52, -26]
,09-09 13:36:08.293  3179  3275 D ScanRecord: parseFromBytes
09-09 13:36:08.293  3179  3275 D ScanRecord: first manudata for manu ID
09-09 13:36:08.293  3179  3275 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -112, -25, -60, -2, -84, -17]
,09-09 13:36:08.293  3179  3275 D ScanRecord: parseFromBytes
09-09 13:36:08.293  3179  3275 D BtGatt.GattService: result: ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[-46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-74, mTimestampNanos=145311295198}
09-09 13:36:08.293  3179  3275 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 13:36:08.293  3179  3275 D BtGatt.GattService: result: ScanResult{mDevice=F5:A4:B3:56:DD:32, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[00001804-0000-1000-8000-00805f9b34fb], mManufacturerSpecificData={249=[1, 52, -97, 83, -21, -49, 113, -115, -80, -12, -76, -5, 2, 2, -37, 21, -22, 114, -52, -26]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-96, mTimestampNanos=133811295198}
09-09 13:36:08.293  3179  3275 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
09-09 13:36:08.293  3179  3275 D BtGatt.GattService: result: ScanResult{mDevice=E3:EC:A5:91:D5:74, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-80, mTimestampNanos=141661295198}
,09-09 13:36:08.293  3179  3275 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
09-09 13:36:08.293  3179  3275 D BtGatt.GattService: result: ScanResult{mDevice=D2:74:8F:0E:D1:25, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-74, mTimestampNanos=147211295198}
09-09 13:36:08.293  3179  3275 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 13:36:08.293  3179  3275 D BtGatt.GattService: result: ScanResult{mDevice=C8:16:A4:7E:61:23, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-80, mTimestampNanos=139711295198}
09-09 13:36:08.293  3179  3275 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
09-09 13:36:08.293  3179  3275 D BtGatt.GattService: result: ScanResult{mDevice=73:3A:4F:46:74:C8, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[5, -112, -25, -60, -2, -84, -17]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-63, mTimestampNanos=132861295198},
09-09 13:36:08.293  3179  3275 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 13:36:08.293  3179  3275 D BtGatt.GattService: result: ScanResult{mDevice=FB:F2:70:61:22:51, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-72, mTimestampNanos=143311295198}
09-09 13:36:08.293  3179  3275 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
09-09 13:36:08.293  3179  3275 D BtGatt.GattService: result: ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-72, mTimestampNanos=152611295198}
09-09 13:36:08.293  3179  3275 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
09-09 13:36:08.293  3179  3275 D BtGatt.GattService: result: ScanResult{mDevice=7D:9C:A4:67:0E:FE, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[5, 124, -7, 14, 52, -118, -96]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-64, mTimestampNanos=132961295198}
,09-09 13:36:08.293  3179  3275 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
09-09 13:36:08.293  6731  6739 D ScanRecord: parseFromBytes
09-09 13:36:08.293  6731  6739 D ScanRecord: first manudata for manu ID
09-09 13:36:08.293  6731  6739 D ScanRecord: parseFromBytes
09-09 13:36:08.293  6731  6739 D ScanRecord: first manudata for manu ID
09-09 13:36:08.293  6731  6739 D ScanRecord: parseFromBytes
09-09 13:36:08.293  6731  6739 D ScanRecord: first manudata for manu ID
,09-09 13:36:08.293  6731  6739 D ScanRecord: parseFromBytes
09-09 13:36:08.293  6731  6739 D ScanRecord: first manudata for manu ID
09-09 13:36:08.293  6731  6739 D ScanRecord: parseFromBytes
09-09 13:36:08.293  6731  6739 D ScanRecord: first manudata for manu ID
09-09 13:36:08.293  6731  6739 D ScanRecord: parseFromBytes
09-09 13:36:08.293  6731  6739 D ScanRecord: parseFromBytes
09-09 13:36:08.293  6731  6739 D ScanRecord: first manudata for manu ID
,09-09 13:36:08.293  6731  6739 D ScanRecord: parseFromBytes
09-09 13:36:08.293  6731  6739 D ScanRecord: first manudata for manu ID
09-09 13:36:08.293  6731  6739 D ScanRecord: parseFromBytes
09-09 13:36:08.293  6731  6731 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> 90:E7:C4:FE:AC:EF 5] updated - the peer count is 2
09-09 13:36:08.303  6731  6731 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> 7C:F9:0E:34:8A:A0 5] updated - the peer count is 2
,09-09 13:36:08.303  1015  3173 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-09 13:36:08.303  1015  3173 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-09 13:36:08.303  1015  3173 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-09 13:36:08.303  1015  3173 D BatteryService: stay LED for fully charged
09-09 13:36:08.303  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-09 13:36:08.313  1015  1015 I MotionRecognitionService: Plugged
,09-09 13:36:08.313  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,09-09 13:36:08.323  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-09 13:36:08.323  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
09-09 13:36:08.323  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-09 13:36:08.323  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-09 13:36:08.323  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-09 13:36:08.333  3179  3179 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-09 13:36:08.333  3179  7469 D HeadsetStateMachine: Disconnected process message: 10
09-09 13:36:08.333  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-09 13:36:08.333  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-09 13:36:08.333  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,09-09 13:36:08.333  1177  1177 D SViewCoverView: level :100 plugged : 2
,09-09 13:36:08.543  7600  7600 I PCWCLIENTTRACE_SYSTEMReceiver: mConnectivityHandler : connected
,09-09 13:36:08.553  7600  7753 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
,09-09 13:36:08.583  7600  7753 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
,09-09 13:36:08.593  7600  7753 I ReactiveServiceManager: Supported : 1
,09-09 13:36:08.593  1015  1570 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x2040
,09-09 13:36:08.593  1015  1570 D QSEECOMAPI: : App is not loaded in QSEE
,09-09 13:36:08.613  1015  1570 D QSEECOMAPI: : Loaded image: APP id = 11
,09-09 13:36:08.623  1015  1570 D QSEECOMAPI: : QSEECom_dealloc_memory 
,09-09 13:36:08.623  1015  1570 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 11
,09-09 13:36:08.623  1015  1570 E terrier : handleString: Failed to handle string(-4)
,09-09 13:36:08.623  1015  1570 E terrier : Java_com_android_server_ReactiveService_GetString: error code = [-4]
,09-09 13:36:08.623  7600  7753 D PCWCLIENTTRACE_SecurePreferencesJNI: getString is null
09-09 13:36:08.623  7600  7753 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
,09-09 13:36:08.623  7600  7753 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-09 13:36:08.623  7600  7753 I PCWCLIENTTRACE_PushUtil: sales region : global
09-09 13:36:08.623  7600  7753 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,09-09 13:36:08.623  7600  7753 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
,09-09 13:36:08.793  1015  1093 V AlarmManager: waitForAlarm result :4
,09-09 13:36:08.793  3179  3179 D BtGatt.ScanManager: awakened up at time 156964
,09-09 13:36:08.793  3179  7468 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 13:36:08.803  3179  3275 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,09-09 13:36:08.803  3179  3275 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:36:08.803  3179  3275 D BtGatt.GattService: current time is 156975470198
,09-09 13:36:08.803  3179  3275 D BtGatt.GattService: Batch record : [-2, 14, 103, -92, -100, 125, 1, -128, -64, -47, 1, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 124, -7, 14, 52, -118, -96, 0]
,09-09 13:36:08.803  3179  3275 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 124, -7, 14, 52, -118, -96]
,09-09 13:36:08.813  3179  3275 D ScanRecord: parseFromBytes
,09-09 13:36:08.813  3179  3275 D BtGatt.GattService: result: ScanResult{mDevice=7D:9C:A4:67:0E:FE, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[5, 124, -7, 14, 52, -118, -96]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-64, mTimestampNanos=133726761136}
,09-09 13:36:08.813  3179  3275 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 13:36:08.813  6731  6744 D ScanRecord: parseFromBytes
,09-09 13:36:08.813  6731  6731 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> 7C:F9:0E:34:8A:A0 5] updated - the peer count is 2
,09-09 13:36:09.303  1015  1093 V AlarmManager: waitForAlarm result :4
,09-09 13:36:09.303  3179  3179 D BtGatt.ScanManager: awakened up at time 157479
,09-09 13:36:09.313  3179  7468 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 13:36:09.313  3179  3275 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-09 13:36:09.313  3179  3275 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:36:09.753  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:36:09.753  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:09.753  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:36:09.753  6731  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f6db2 not in the list
09-09 13:36:09.753  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:09.753  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:36:09.753  6731  6786 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:36:09.753  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:36:09.753  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 13:36:09.753  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 13:36:09.753  3179  3190 D BtGatt.GattService: stopScan() - queue size =1
,09-09 13:36:09.753  3179  3372 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 13:36:09.753  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 13:36:09.753  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
,09-09 13:36:09.753  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
09-09 13:36:09.753  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 13:36:09.753  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-09 13:36:09.753  3179  7468 D BtGatt.ScanManager: filter size is 1
09-09 13:36:09.753  3179  7468 D BtGatt.ScanManager: delete FilterIndex - 3
,09-09 13:36:09.753  6731  6786 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:36:09.753  3179  3275 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-09 13:36:09.753  3179  3275 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 13:36:09.753  3179  7468 D BtGatt.ScanManager: stopping BLe Batch
09-09 13:36:09.753  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 13:36:09.753  6731  6786 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 13:36:09.753  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 13:36:09.753  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:36:09.753  6731  6786 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
09-09 13:36:09.753  3179  3275 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-09 13:36:09.753  3179  3275 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 13:36:09.753  3179  7468 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 13:36:09.753  6731  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:36:09.753  6731  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:36:09.753  6731  6731 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:36:09.753  3179  3275 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-09 13:36:09.753  3179  3275 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 13:36:09.753  6731  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@114a2103 not in the list
09-09 13:36:09.753  6731  6786 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:09.753  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:36:09.753  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
09-09 13:36:09.753  6731  6786 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
09-09 13:36:09.753  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
09-09 13:36:09.763  6731  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:36:09.763  6731  6786 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-09 13:36:09.763  6731  6786 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:36:09.763  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:36:09.763  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-09 13:36:09.763  6731  6786 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 13:36:09.763  6731  6786 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-09 13:36:09.763  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:36:09.763  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-09 13:36:09.763  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:36:09.763  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 13:36:09.763  6731  6731 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-09 13:36:09.763  6731  7756 D BluetoothSocket: bindListen(): myUserId = 0
,09-09 13:36:09.773  6731  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 13:36:09.773  6731  7756 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:36:09.773  6731  7756 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[109]}
09-09 13:36:09.773  6731  7756 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 13:36:09.773  6731  7756 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 13:36:09.773  6731  7756 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@18dfd7ae
09-09 13:36:09.773  6731  7756 D BluetoothSocket: channel: 6
09-09 13:36:09.773  6731  7756 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-09 13:36:09.773  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 13:36:09.773  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:36:09.783  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-09 13:36:09.783  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-09 13:36:09.783  6731  6786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 08 EC A9 50 76 27
09-09 13:36:09.783  6731  6786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 8, -20, -87, 80, 118, 39]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:36:09.783  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 8, -20, -87, 80, 118, 39]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:36:09.783  6731  6786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...,
,09-09 13:36:09.783  3179  3189 D BtGatt.GattService: registerClient() - UUID=c05ca53c-8f63-43c3-a388-db87b0f25747
,09-09 13:36:09.823  3179  3275 D BtGatt.GattService: onClientRegistered() - UUID=c05ca53c-8f63-43c3-a388-db87b0f25747, clientIf=5
,09-09 13:36:09.823  6731  6739 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-09 13:36:09.823  3179  7467 D BtGatt.AdvertiseManager: message : 0
,09-09 13:36:09.823  3179  7467 D BtGatt.AdvertiseManager: number of adv instance running0
,09-09 13:36:09.823  3179  7467 D BtGatt.AdvertiseManager: size of list is =0
,09-09 13:36:09.833  3179  7467 D BtGatt.AdvertiseManager: starting advertising
,09-09 13:36:09.833  3179  7467 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-09 13:36:09.843  3179  3275 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-09 13:36:09.843  3179  7467 D BtGatt.AdvertiseManager: starting multi advertising
,09-09 13:36:09.843  3179  3275 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-09 13:36:09.843  3179  7467 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-09 13:36:09.843  3179  7467 D BtGatt.AdvertiseManager: clientIf: 5, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-09 13:36:09.843  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-09 13:36:09.853  6731  6786 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 13:36:09.853  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:36:09.853  6731  6731 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 13:36:09.853  6731  6731 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-09 13:36:09.853  6731  6731 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-09 13:36:09.853  6731  6731 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-09 13:36:09.853  6731  6731 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-09 13:36:09.853  6731  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-09 13:36:09.863  6731  6731 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:36:09.863  6731  6731 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:36:09.893   290   290 E SMD     : DCD OFF
,09-09 13:36:10.363  6731  6731 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-09 13:36:10.363  6731  6731 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-09 13:36:10.363  6731  6731 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 13:36:10.473  7668  7668 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
,09-09 13:36:10.903   325   325 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 13:36:11.903   325   325 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 13:36:12.893   290   290 E SMD     : DCD OFF,
,09-09 13:36:12.913   325   325 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 13:36:13.263  1015  3382 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-09 13:36:13.363  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:36:13.363  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-09 13:36:13.363  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 13:36:13.363  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown,
09-09 13:36:13.363  6731  6786 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@78638dc, channel: 6, state: LISTENING
09-09 13:36:13.363  6731  6786 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@78638dc, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@18dfd7ae, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2fa16de5mSocket: android.net.LocalSocket@1b55c0ba impl:android.net.LocalSocketImpl@e17eb6b fd:FileDescriptor[109]
09-09 13:36:13.363  6731  6786 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1b55c0ba impl:android.net.LocalSocketImpl@e17eb6b fd:FileDescriptor[109]
09-09 13:36:13.363  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:36:13.363  6731  7756 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@78638dc, channel: 6, state: CLOSED
09-09 13:36:13.363  6731  6786 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:36:13.363  6731  7756 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 13:36:13.363  6731  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f6db2 not in the list
09-09 13:36:13.363  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:13.363  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:36:13.363  6731  6786 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:36:13.363  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:36:13.363  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 13:36:13.363  6731  6731 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 13:36:13.363  6731  7756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 13:36:13.363  6731  7756 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 13:36:13.363  6731  6786 D BluetoothLeScanner: could not find callback wrapper
09-09 13:36:13.363  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 13:36:13.363  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-09 13:36:13.363  3179  7467 D BtGatt.AdvertiseManager: message : 1
09-09 13:36:13.363  3179  7467 D BtGatt.AdvertiseManager: stop advertise for client 5
09-09 13:36:13.363  3179  7467 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf5
09-09 13:36:13.373  3179  7467 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-09 13:36:13.373  3179  3275 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-09 13:36:13.373  3179  3275 D BtGatt.GattService: Client app is not null!
,09-09 13:36:13.373  3179  3190 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 13:36:13.383  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 13:36:13.383  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-09 13:36:13.383  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-09 13:36:13.383  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-09 13:36:13.383  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-09 13:36:13.383  6731  6786 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:36:13.383  6731  6786 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-09 13:36:13.383  6731  6786 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 13:36:13.383  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:36:13.393  6731  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:36:13.393  6731  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:36:13.393  6731  6731 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-09 13:36:13.393  6731  6731 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:36:13.393  6731  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@114a2103 not in the list
,09-09 13:36:13.393  6731  6786 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:36:13.393  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:36:13.393  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:36:13.393  6731  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:36:13.393  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:36:13.393  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:36:13.393  6731  6786 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f6db2 not in the list
,09-09 13:36:13.393  6731  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:36:13.403  6731  6786 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@114a2103 not in the list
,09-09 13:36:13.403  6731  6786 D io.jxcore.node.ConnectivityMonitor: stop,
09-09 13:36:13.403  6731  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:13.403  6731  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:13.403  6731  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-09 13:36:13.403  6731  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-09 13:36:13.403  6731  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-09 13:36:13.403  6731  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 13:36:13.403  6731  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-09 13:36:13.403  6731  6786 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 13:36:13.413  6731  7759 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1453, name: My test thread name)
,09-09 13:36:13.653  1015  1132 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,09-09 13:36:13.653  1015  1132 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,09-09 13:36:13.663  1015  1132 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:36:13.663  1015  1132 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-09 13:36:13.663  1015  1132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,09-09 13:36:13.673  7190  7190 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE,
,09-09 13:36:13.673  7190  7190 D PreloadUpdateManagerStateMachine: exit::IDLE
09-09 13:36:13.673  7190  7190 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,09-09 13:36:13.673  7190  7190 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
,09-09 13:36:13.673  7190  7190 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,09-09 13:36:13.673  7190  7190 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
,09-09 13:36:13.673  7190  7190 D PreloadUpdateManagerStateMachine: entry::IDLE
,09-09 13:36:13.683  1015  3363 D SSRM:n  : SIOP:: AP = 320
,09-09 13:36:13.893  6731  6731 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 13:36:13.903   325   325 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 13:36:14.483  7668  7668 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,09-09 13:36:14.483  7668  7668 I dhcpcd  : wlan0: no IPv6 Routers available
,09-09 13:36:14.913   325   325 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 13:36:15.413  6731  6786 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 1453,
,09-09 13:36:15.413  6731  6786 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 1453, name: My test thread name)
,09-09 13:36:15.413  6731  7762 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1454, name: My test thread name)
,09-09 13:36:15.413  6731  7762 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1454, thread name: My test thread name)
09-09 13:36:15.413  6731  7762 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1454, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22,
,09-09 13:36:15.413  6731  6786 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 13:36:15.413  6731  7763 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1458, name: My test thread name)
,09-09 13:36:15.413  6731  7763 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 1458, thread name: My test thread name): Test exception.
,09-09 13:36:15.423  6731  7763 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1458, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: testStartStop(io.jxcore.node.ConnectivityMonitorTest)
,09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: Proper state of BT is set when switched on
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: Expected: is <false>
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner:      but: was <true>
,09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: Proper state of BT is set when switched on
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: Expected: is <false>
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner:      but: was <true>
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectivityMonitorTest.testStartStop(ConnectivityMonitorTest.java:262)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner,: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:74)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$1.Receiver(RegisterExecuteUT.java:26)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.loopOnce(Native Method)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$6$1.run(jxcore.java:348)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:145)
09-09 13:36:15.423  6731  6786 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
,09-09 13:36:15.423  6731  6786 I jxcore-log: Total number of executed tests:  82
09-09 13:36:15.423  6731  6786 I jxcore-log: 
,09-09 13:36:15.423  6731  6786 I jxcore-log: Number of passed tests:  81
09-09 13:36:15.423  6731  6786 I jxcore-log: 
,09-09 13:36:15.423  6731  6786 I jxcore-log: Number of failed tests:  1
09-09 13:36:15.423  6731  6786 I jxcore-log: 
,09-09 13:36:15.433  6731  6786 I jxcore-log: Number of ignored tests:  0
09-09 13:36:15.433  6731  6786 I jxcore-log: 
,09-09 13:36:15.433  6731  6786 I jxcore-log: Total duration:  31174
09-09 13:36:15.433  6731  6786 I jxcore-log: 
,09-09 13:36:15.433  6731  6786 I jxcore-log: Failed to execute UT.
09-09 13:36:15.433  6731  6786 I jxcore-log: 
,09-09 13:36:15.433  6731  6786 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
09-09 13:36:15.433  6731  6786 I jxcore-log: 
,09-09 13:36:15.433  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:15.433  6731  6786 I jxcore-log: 
09-09 13:36:15.433  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:15.433  6731  6786 I jxcore-log: 
09-09 13:36:15.443  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:15.443  6731  6786 I jxcore-log: 
09-09 13:36:15.443  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-09 13:36:15.443  6731  6786 I jxcore-log: 
09-09 13:36:15.443  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:15.443  6731  6786 I jxcore-log: 
09-09 13:36:15.443  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-09 13:36:15.443  6731  6786 I jxcore-log: 
09-09 13:36:15.453  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:15.453  6731  6786 I jxcore-log: 
09-09 13:36:15.453  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:15.453  6731  6786 I jxcore-log: 
09-09 13:36:15.453  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:15.453  6731  6786 I jxcore-log: 
09-09 13:36:15.453  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:15.453  6731  6786 I jxcore-log: 
09-09 13:36:15.453  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:36:15.453  6731  6786 I jxcore-log: 
09-09 13:36:15.453  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:36:15.453  6731  6786 I jxcore-log: 
09-09 13:36:15.453  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:36:15.453  6731  6786 I jxcore-log: 
09-09 13:36:15.463  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 13:36:15.463  6731  6786 I jxcore-log: 
09-09 13:36:15.463  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:36:15.463  6731  6786 I jxcore-log: 
09-09 13:36:15.463  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:36:15.463  6731  6786 I jxcore-log: 
09-09 13:36:15.463  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:36:15.463  6731  6786 I jxcore-log: 
,09-09 13:36:15.463  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:15.463  6731  6786 I jxcore-log: 
,09-09 13:36:15.463  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:15.463  6731  6786 I jxcore-log: 
,09-09 13:36:15.463  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:15.463  6731  6786 I jxcore-log: 
,09-09 13:36:15.473  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:15.473  6731  6786 I jxcore-log: 
,09-09 13:36:15.473  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:15.473  6731  6786 I jxcore-log: 
,09-09 13:36:15.473  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:15.473  6731  6786 I jxcore-log: 
,09-09 13:36:15.473  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:15.473  6731  6786 I jxcore-log: 
,09-09 13:36:15.473  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
09-09 13:36:15.473  6731  6786 I jxcore-log: 
09-09 13:36:15.473  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:15.473  6731  6786 I jxcore-log: 
,09-09 13:36:15.473  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:15.473  6731  6786 I jxcore-log: ,
,09-09 13:36:15.473  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:15.473  6731  6786 I jxcore-log: 
,09-09 13:36:15.473  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:36:15.473  6731  6786 I jxcore-log: 
,09-09 13:36:15.473  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:36:15.473  6731  6786 I jxcore-log: 
,09-09 13:36:15.473  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:36:15.473  6731  6786 I jxcore-log: 
,09-09 13:36:15.473  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:36:15.473  6731  6786 I jxcore-log: 
,09-09 13:36:15.483  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:36:15.483  6731  6786 I jxcore-log: 
,09-09 13:36:15.483  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:36:15.483  6731  6786 I jxcore-log: 
,09-09 13:36:15.483  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:36:15.483  6731  6786 I jxcore-log: 
,09-09 13:36:15.483  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
,09-09 13:36:15.483  6731  6786 I jxcore-log: 
,09-09 13:36:15.483  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:15.483  6731  6786 I jxcore-log: 
,09-09 13:36:15.483  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-09 13:36:15.483  6731  6786 I jxcore-log: 
,09-09 13:36:15.483  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
09-09 13:36:15.483  6731  6786 I jxcore-log: 
,09-09 13:36:15.483  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state,
09-09 13:36:15.483  6731  6786 I jxcore-log: 
,09-09 13:36:15.483  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-09 13:36:15.483  6731  6786 I jxcore-log: 
,09-09 13:36:15.483  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-09 13:36:15.483  6731  6786 I jxcore-log: 
,09-09 13:36:15.483  6731  6786 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 13:36:15.483  6731  6786 I jxcore-log: 
,09-09 13:36:15.583  6731  7759 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1453, name: My test thread name), during the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165,
,09-09 13:36:15.753  7764  7764 D AndroidRuntime: ,
09-09 13:36:15.753  7764  7764 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-09 13:36:15.753  7764  7764 D AndroidRuntime: CheckJNI is OFF,
09-09 13:36:15.753  7764  7764 D AndroidRuntime: readGMSProperty: start
09-09 13:36:15.753  7764  7764 D AndroidRuntime: readGMSProperty: already setted!!,
09-09 13:36:15.753  7764  7764 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-09 13:36:15.753  7764  7764 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-09 13:36:15.753  7764  7764 D AndroidRuntime: readGMSProperty: end
09-09 13:36:15.753  7764  7764 D AndroidRuntime: addProductProperty: start
,09-09 13:36:15.883  7764  7764 E AffinityControl: AffinityControl: registerfunction enter,
,09-09 13:36:15.893   290   290 E SMD     : DCD OFF,
,09-09 13:36:15.913   325   325 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,09-09 13:36:15.913  7764  7764 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,09-09 13:36:15.923  1015  1376 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
09-09 13:36:15.923  1015  1376 D PackageManager: START PACKAGE DELETE: observer{1049492290}
09-09 13:36:15.923  1015  1376 D PackageManager: pkg{<packageName>}
09-09 13:36:15.923  1015  1376 D PackageManager: user{0}
09-09 13:36:15.923  1015  1376 D PackageManager: caller{2000}
09-09 13:36:15.923  1015  1376 D PackageManager: flags{2}
09-09 13:36:15.923  1015  1376 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true,
09-09 13:36:15.923  1015  1376 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-09 13:36:15.923  1015  1376 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-09 13:36:15.923  1015  1376 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-09 13:36:15.933  1015  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0,
09-09 13:36:15.933  1015  1054 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-09 13:36:15.933  1015  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,09-09 13:36:15.943  1015  1054 D ApplicationPolicy: getApplicationUninstallationEnabled,
09-09 13:36:15.943  1015  1054 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-09 13:36:15.943  1015  1054 D PackageManager: !@killApplicatoin: 10171, uninstall pkg,
,09-09 13:36:15.953  1015  1040 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
,09-09 13:36:15.953  1015  1040 I ActivityManager: Killing 6731:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-09 13:36:16.043  1015  1054 W PackageSettings: Skipping PackageSetting{39a16ec8 com.example.hello/10168} due to missing metadata
,09-09 13:36:16.053  1015  1570 I WindowState: WIN DEATH: Window{335ce8e4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-09 13:36:16.053   257   451 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
,09-09 13:36:16.053   257   451 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,09-09 13:36:16.053  1015  1570 D InputDispatcher: Focus left window: 6731
,09-09 13:36:16.083  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-09 13:36:16.083  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-09 13:36:16.093  1015  1040 I ActivityManager:   Force finishing activity ActivityRecord{3122d884 u0 com.test.thalitest/.MainActivity t2}
,09-09 13:36:16.103  1015  1040 D InputDispatcher: Focused application released
,09-09 13:36:16.113  1015  1040 D FocusedStackFrame: Set to : 0
,09-09 13:36:16.113  1015  1040 W ActivityManager: mDVFSHelper.acquire()
,09-09 13:36:16.123  1015  1040 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,09-09 13:36:16.123  1015  1028 W ActivityManager: Spurious death for ProcessRecord{3c0e4753 6731:com.test.thalitest/u0a171}, curProc for 6731: null
,09-09 13:36:16.123  1015  1054 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,09-09 13:36:16.133  1015  1054 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,09-09 13:36:16.173  2640  2640 I art     : Explicit concurrent mark sweep GC freed 20538(1175KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 799us total 38.376ms
,09-09 13:36:16.173  1478  1478 D Launcher: onRestart, Launcher: 744803050
,09-09 13:36:16.193  1015  1096 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-09 13:36:16.203  1963  2154 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-09 13:36:16.203  4748  4748 I art     : Explicit concurrent mark sweep GC freed 4124(159KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 12MB/17MB, paused 1.259ms total 70.463ms
,09-09 13:36:16.213  2026  2026 E SamsungIME: mOCRHelper is null
,09-09 13:36:16.223  1015  1121 V NetworkStats: removeUidsLocked() for UIDs [10171]
,09-09 13:36:16.223  1454  1454 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-09 13:36:16.223  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:36:16.223  1015  1121 V NetworkStats: performPollLocked(flags=0x3)
,09-09 13:36:16.223  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:36:16.223  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 13:36:16.233  1015  1121 V NetworkStats: performPollLocked() took 11ms
,09-09 13:36:16.233  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:36:16.243  1478  1478 D Launcher: onStart, Launcher: 744803050
09-09 13:36:16.243  1478  1478 D Launcher.HomeView: onStart
,09-09 13:36:16.243  1478  1478 D Launcher: onResume, Launcher: 744803050
,09-09 13:36:16.243  1015  1486 D SettingsProvider: name = kids_home_mode
09-09 13:36:16.243  1015  1486 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 13:36:16.243  1015  1486 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 13:36:16.243  1015  1486 D SettingsProvider: selectionArgs: false
09-09 13:36:16.243  1015  1486 D SettingsProvider: selectionArgs: 10006
09-09 13:36:16.243  1015  1486 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 13:36:16.243  1015  1486 D SettingsProvider: ret = -1
,09-09 13:36:16.243  1478  1478 D Launcher.HomeView: onResume
,09-09 13:36:16.253  2922  2922 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Sep 09 13:36:16 GMT+02:00 2016
,09-09 13:36:16.253  1015  1539 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-09 13:36:16.253  1015  1539 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-09 13:36:16.253  1015  1539 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:36:16.253  1015  1539 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:36:16.253  1015  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-09 13:36:16.253  1015  1039 D EnterpriseDeviceManagerService: Package has changed for user 0
09-09 13:36:16.253  1015  1039 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
09-09 13:36:16.253  1015  1039 W TextServicesManagerService: no available spell checker services found
,09-09 13:36:16.263  1440  1440 D PersonaManager: isKioskContainerExistOnDevice
,09-09 13:36:16.263  1440  1440 D RegisteredServicesCache: empty dynamic service
,09-09 13:36:16.263  1478  1478 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,09-09 13:36:16.263  2922  2922 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-09 13:36:16.263  1478  1478 D MenuAppsGridFragment: onResume
,09-09 13:36:16.273  1015  1569 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=31, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=41
,09-09 13:36:16.273  1015  1569 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,09-09 13:36:16.273  1478  1478 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,09-09 13:36:16.273  1478  1478 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,09-09 13:36:16.273  1015  1569 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,09-09 13:36:16.273  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 13:36:16.283  1015  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:16.283  1015  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:16.283  1015  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:16.283  1015  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:16.283  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 13:36:16.293  2922  2922 I KLMS-2.5.123: : KLMSIntentService(): onCreate(),
,09-09 13:36:16.303  7778  7778 E Zygote  : MountEmulatedStorage(),
09-09 13:36:16.303  7778  7778 I libpersona: KNOX_SDCARD checking this for 10090
09-09 13:36:16.303  7778  7778 E Zygote  : v2
09-09 13:36:16.303  7778  7778 I libpersona: KNOX_SDCARD not a persona
,09-09 13:36:16.303  7778  7778 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-09 13:36:16.303  7778  7778 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-09 13:36:16.303  7778  7778 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:36:16.313  1015  1569 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7778 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,09-09 13:36:16.313  1015  1533 D ActivityManager: handle home activity for 0
09-09 13:36:16.313  1015  1533 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
09-09 13:36:16.313  1015  1533 D KnoxTimeoutHandler: post home show event for user 0
09-09 13:36:16.313  1015  1533 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-09 13:36:16.313  1015  1533 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-09 13:36:16.313  1015  1533 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-09 13:36:16.313  1478  1478 D Launcher.HomeView: onPause
09-09 13:36:16.313  1478  1478 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,09-09 13:36:16.323  2922  2922 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-09 13:36:16.323  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:36:16.323  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:36:16.333  1440  1440 D RegisteredComponentCache: Collect Tech packages for Knox
09-09 13:36:16.333   307   307 I art     : Explicit concurrent mark sweep GC freed 8693(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 846us total 28.314ms
,09-09 13:36:16.333   257   257 I SurfaceFlinger: id=16 createSurf (540x960),1 flag=4, Mauncher
,09-09 13:36:16.343  1015  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-09 13:36:16.343  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,09-09 13:36:16.343  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:16.343  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:16.343  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:16.343  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:16.343  1015  1015 I art     : Explicit concurrent mark sweep GC freed 80038(5MB) AllocSpace objects, 14(224KB) LOS objects, 33% free, 25MB/37MB, paused 8.701ms total 207.071ms
,09-09 13:36:16.343  1015  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-09 13:36:16.353  1015  1054 I art     : WaitForGcToComplete blocked for 186.755ms for cause Explicit
,09-09 13:36:16.353  2922  2922 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-09 13:36:16.353   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 654us total 21.312ms
,09-09 13:36:16.373   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 572us total 16.208ms
,09-09 13:36:16.373  1015  1569 D InputDispatcher: Focus entered window: 1478
,09-09 13:36:16.373  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-09 13:36:16.373  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
09-09 13:36:16.373  1478  1478 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-09 13:36:16.383  7778  7778 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:36:16.383  7778  7778 D ActivityThread: Added TimaKeyStore provider
,09-09 13:36:16.383  2922  7777 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-09 13:36:16.383  1015  1028 I TactileAssist: enable value -1
09-09 13:36:16.383  1015  1028 I TactileAssist: internal enable value -1
09-09 13:36:16.383  1015  1028 I TactileAssist: intensity value -1
09-09 13:36:16.383  1015  1028 I TactileAssist: saveAppList value true
09-09 13:36:16.383  7793  7793 E Zygote  : MountEmulatedStorage()
09-09 13:36:16.383  7793  7793 I libpersona: KNOX_SDCARD checking this for 1000
09-09 13:36:16.383  7793  7793 E Zygote  : v2
09-09 13:36:16.383  7793  7793 I libpersona: KNOX_SDCARD not a persona
,09-09 13:36:16.383  7793  7793 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:36:16.383  7793  7793 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 13:36:16.383  1015  1533 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-09 13:36:16.383  1015  1533 D SecContentProvider2: mCursor = null
,09-09 13:36:16.393  1015  1040 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7793 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-09 13:36:16.393  7793  7793 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:36:16.393  1015  1028 I TactileAssist: List of disabled apps :
,09-09 13:36:16.393  1440  1440 D PersonaManager: isKioskContainerExistOnDevice
09-09 13:36:16.393  2922  7777 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,09-09 13:36:16.413  1015  1027 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-09 13:36:16.413  1015  1027 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6731 uid 10171
,09-09 13:36:16.413  1015  7805 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-09 13:36:16.413  2922  7777 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,09-09 13:36:16.423  1015  1015 D RCPManagerService: PackageReceiver onReceive()
,09-09 13:36:16.423  2026  2026 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,09-09 13:36:16.433  1015  1015 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,09-09 13:36:16.433  2922  7777 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,09-09 13:36:16.433  7793  7793 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:36:16.433  7793  7793 D ActivityThread: Added TimaKeyStore provider
,09-09 13:36:16.443  1015  1015 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
09-09 13:36:16.443  1015  1015 I OTPFW   : PackageRemovalReceiver::onReceive Enter
09-09 13:36:16.443  1015  1015 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,09-09 13:36:16.443  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 13:36:16.443  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
09-09 13:36:16.443  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-09 13:36:16.443  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:16.443  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:16.443  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:16.443  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:16.463  7812  7812 E Zygote  : MountEmulatedStorage()
,09-09 13:36:16.463  7812  7812 E Zygote  : v2
09-09 13:36:16.463  7812  7812 I libpersona: KNOX_SDCARD checking this for 1000
,09-09 13:36:16.463  7812  7812 I libpersona: KNOX_SDCARD not a persona
,09-09 13:36:16.463  7812  7812 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-09 13:36:16.463  1015  1040 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=7812 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-09 13:36:16.473  7812  7812 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-09 13:36:16.473  7812  7812 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:36:16.473  1015  1015 I OTPFW   : ProvisionData::getAllEntries Enter
,09-09 13:36:16.483  1015  1015 E OTPFW   : ProvisionData::getAllEntries Table is empty
,09-09 13:36:16.493  1015  1045 W ActivityManager: mDVFSHelper.release()
09-09 13:36:16.493  1015  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2229eea5 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:164664
,09-09 13:36:16.503  1015  1323 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,09-09 13:36:16.513  1015  1323 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:16.513  1015  1323 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:16.513  1015  1323 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:16.513  1015  1323 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:16.523  7778  7778 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) },
,09-09 13:36:16.533  7778  7778 D elm:15121: ELMEngine.ELMEngine( context ).
,09-09 13:36:16.533  7827  7827 E Zygote  : MountEmulatedStorage()
09-09 13:36:16.533  7827  7827 I libpersona: KNOX_SDCARD checking this for 10048
09-09 13:36:16.533  7827  7827 E Zygote  : v2
09-09 13:36:16.533  7827  7827 I libpersona: KNOX_SDCARD not a persona
09-09 13:36:16.533  7827  7827 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 13:36:16.533  7778  7778 D elm:15121: MDMBridge.setEnterpriseBridge(),
,09-09 13:36:16.533  7812  7812 D TimaKeyStoreProvider: TimaSignature is unavailable,
09-09 13:36:16.533  1015  1323 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7827 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a
09-09 13:36:16.533  7827  7827 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 13:36:16.533  7812  7812 D ActivityThread: Added TimaKeyStore provider
09-09 13:36:16.533  7827  7827 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
09-09 13:36:16.533  1015  1132 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
09-09 13:36:16.533  1015  1132 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,09-09 13:36:16.533  1015  1132 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:36:16.533  1015  1132 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:36:16.533  1015  1132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
09-09 13:36:16.543  2922  7777 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,09-09 13:36:16.543  7778  7778 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,09-09 13:36:16.553  7778  7778 D elm:15121: ElmAgentService : onCreate()
,09-09 13:36:16.553  7778  7835 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,09-09 13:36:16.553  7778  7835 D elm:15121: MainReceiver.listeningToPackageRemoved()
,09-09 13:36:16.553  7778  7835 D elm:15121: MDMBridge.getInstance()
,09-09 13:36:16.563  7793  7793 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,09-09 13:36:16.563  1015  1533 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
09-09 13:36:16.563  1015  1533 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,09-09 13:36:16.563  1015  1533 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:36:16.563  1015  1533 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:36:16.563  1015  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
09-09 13:36:16.563  7778  7835 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,09-09 13:36:16.573  2922  7777 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,09-09 13:36:16.573  7827  7827 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:36:16.573  7827  7827 D ActivityThread: Added TimaKeyStore provider
,09-09 13:36:16.573  7778  7835 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,09-09 13:36:16.573  2922  7777 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,09-09 13:36:16.573  1015  1477 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,09-09 13:36:16.583  1015  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:16.583  1015  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:16.583  1015  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:16.583  1015  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:16.593  7812  7812 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED,
,09-09 13:36:16.593  7844  7844 E Zygote  : MountEmulatedStorage()
09-09 13:36:16.593  7844  7844 E Zygote  : v2
09-09 13:36:16.593  7844  7844 I libpersona: KNOX_SDCARD checking this for 1000
09-09 13:36:16.593  7844  7844 I libpersona: KNOX_SDCARD not a persona
,09-09 13:36:16.603  1015  1477 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7844 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
09-09 13:36:16.603  7844  7844 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-09 13:36:16.603  2922  2922 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-09 13:36:16.613  1015  1570 D SecContentProvider2: uri = -1 selection = getSealedState,
09-09 13:36:16.613  1015  1570 D SecContentProvider2: mCursor = null,
,09-09 13:36:16.613  7812  7812 I PopupuiReceiver_KNOX: getSealedState : true
,09-09 13:36:16.613  7844  7844 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-09 13:36:16.613  1015  1570 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages,
09-09 13:36:16.613  1015  1570 D SecContentProvider2: mCursor = null
09-09 13:36:16.613  7812  7812 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
09-09 13:36:16.613  1015  1132 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
09-09 13:36:16.613  1015  1132 D SecContentProvider2: mCursor = null
,09-09 13:36:16.623  7844  7844 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
09-09 13:36:16.623  7812  7812 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
09-09 13:36:16.623  7812  7812 D PopupuiReceiver: Action package removed
,09-09 13:36:16.623  1015  1376 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,09-09 13:36:16.623  1015  1376 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:16.623  1015  1376 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:16.623  1015  1376 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:16.623  1015  1376 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:16.643  7844  7844 D TimaKeyStoreProvider: TimaSignature is unavailable,
09-09 13:36:16.643  7854  7854 E Zygote  : MountEmulatedStorage()
,09-09 13:36:16.643  7854  7854 E Zygote  : v2
09-09 13:36:16.643  7854  7854 I libpersona: KNOX_SDCARD checking this for 10145
09-09 13:36:16.643  7854  7854 I libpersona: KNOX_SDCARD not a persona
,09-09 13:36:16.643  7844  7844 D ActivityThread: Added TimaKeyStore provider
,09-09 13:36:16.643  7854  7854 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-09 13:36:16.653  7854  7854 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 13:36:16.653  7854  7854 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:36:16.653  1015  1376 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7854 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 13:36:16.653  1015  1376 I ActivityManager: Killing 7437:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,09-09 13:36:16.663  1015  1054 I art     : Explicit concurrent mark sweep GC freed 12129(766KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 24MB/37MB, paused 5.855ms total 318.473ms
,09-09 13:36:16.673  7778  7778 D elm:15121: ElmAgentService : onDestroy().
,09-09 13:36:16.673  1015  1039 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,09-09 13:36:16.683  7827  7827 D Compatibility: onReceive() it will make start service
,09-09 13:36:16.683  7854  7854 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:36:16.683  1015  1028 I ActivityManager: Killing 7582:com.samsung.android.securitylogagent/1000 (adj 15): empty #21
,09-09 13:36:16.683  7854  7854 D ActivityThread: Added TimaKeyStore provider
,09-09 13:36:16.693  1015  1028 I ActivityManager: Killing 7537:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,09-09 13:36:16.693  1015  1027 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
,09-09 13:36:16.693  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,09-09 13:36:16.693  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:36:16.693  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:36:16.693  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,09-09 13:36:16.703  1015  1323 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,09-09 13:36:16.703  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-09 13:36:16.703  1015  1323 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:16.703  1015  1323 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:16.703  1015  1323 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:16.703  1015  1323 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:16.703  7844  7844 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-09 13:36:16.713  7827  7875 D Compatibility: onHandleIntent()
,09-09 13:36:16.713  7827  7875 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10171, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,09-09 13:36:16.713  7876  7876 E Zygote  : MountEmulatedStorage()
09-09 13:36:16.713  7876  7876 I libpersona: KNOX_SDCARD checking this for 10052
09-09 13:36:16.713  7876  7876 E Zygote  : v2
09-09 13:36:16.713  7876  7876 I libpersona: KNOX_SDCARD not a persona
09-09 13:36:16.713  7876  7876 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:36:16.723  1015  1323 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7876 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
09-09 13:36:16.723  7876  7876 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 13:36:16.723  7876  7876 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-09 13:36:16.733  1015  3173 D PersonaManager: isKioskContainerExistOnDevice
,09-09 13:36:16.733  7827  7875 D Compatibility: found: 2
,09-09 13:36:16.743  1015  1054 D PackageManager: delete codoeFile: 
,09-09 13:36:16.753  7827  7875 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,09-09 13:36:16.753  7827  7875 D Compatibility: skipping ResolveInfo{1c0dcd1d com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
09-09 13:36:16.753  7827  7875 D Compatibility: considering ResolveInfo{27cd5b92 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
09-09 13:36:16.753  7827  7875 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,09-09 13:36:16.763  7827  7875 D Compatibility: enabling receiver ResolveInfo{2942a963 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,09-09 13:36:16.763  1015  1054 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
,09-09 13:36:16.763  1015  1054 I AASA_removePackage: UID=10171 Target=com.test.thalitest
,09-09 13:36:16.763  1015  1054 D PackageManager: result of delete: 1{1049492290}
,09-09 13:36:16.763  7876  7876 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:36:16.773  7876  7876 D ActivityThread: Added TimaKeyStore provider
,09-09 13:36:16.773  7844  7844 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,09-09 13:36:16.773  7827  7875 D Compatibility: enabling receiver ResolveInfo{6907960 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,09-09 13:36:16.773  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 13:36:16.783  7854  7854 D ThemeInfoUtil: getCurrentFestivalName is [null]
09-09 13:36:16.783  7854  7854 D ThemeInfoUtil: isCurrentFestival = false
,09-09 13:36:16.783  7764  7764 D AndroidRuntime: Shutting down VM
,09-09 13:36:16.783  1015  1486 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
09-09 13:36:16.783  1015  1486 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,09-09 13:36:16.783  1015  1539 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
09-09 13:36:16.783  7827  7875 D Compatibility: enabling receiver ResolveInfo{10bf1e19 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,09-09 13:36:16.793  1015  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:16.793  1015  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:16.793  1015  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:16.793  1015  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:16.793  1015  1015 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,09-09 13:36:16.803  7892  7892 E Zygote  : MountEmulatedStorage()
09-09 13:36:16.803  7892  7892 I libpersona: KNOX_SDCARD checking this for 10148
09-09 13:36:16.803  7892  7892 E Zygote  : v2
09-09 13:36:16.803  7892  7892 I libpersona: KNOX_SDCARD not a persona
09-09 13:36:16.803  7892  7892 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:36:16.803  7892  7892 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 13:36:16.803  7892  7892 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:36:16.803  1015  1539 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7892 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
09-09 13:36:16.813  7827  7875 D Compatibility: enabling receiver ResolveInfo{3ce19ede com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
09-09 13:36:16.813  1015  1015 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-09 13:36:16.813  1015  1539 I ActivityManager: Killing 7565:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #21
,09-09 13:36:16.813  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-09 13:36:16.813  1015  1015 V EnterpriseBillingPolicy: uID is 10171
09-09 13:36:16.813  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
09-09 13:36:16.813  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
09-09 13:36:16.813  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-09 13:36:16.813  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-09 13:36:16.813  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-09 13:36:16.813  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
09-09 13:36:16.813  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-09 13:36:16.813  1015  1570 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,09-09 13:36:16.813  7827  7875 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,09-09 13:36:16.823  1015  1570 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:16.823  1015  1570 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:16.823  1015  1570 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:16.823  1015  1570 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:16.833  1015  1054 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest},
09-09 13:36:16.833  1015  1054 D PackageManager: userId{-1}
09-09 13:36:16.833  1015  1054 D PackageManager: andCode{true}
,09-09 13:36:16.833  7892  7892 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:36:16.833  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 13:36:16.833  7892  7892 D ActivityThread: Added TimaKeyStore provider
,09-09 13:36:16.833  7903  7903 E Zygote  : MountEmulatedStorage(),
09-09 13:36:16.843  1015  1570 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7903 uid=10087 gids={50087, 9997, 1028, 3003, 1015} abi=armeabi-v7a
09-09 13:36:16.843  1015  1039 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-09 13:36:16.843  1015  1039 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:36:16.843  1015  1039 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
09-09 13:36:16.843  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-09 13:36:16.843  7903  7903 E Zygote  : v2
09-09 13:36:16.843  7903  7903 I libpersona: KNOX_SDCARD checking this for 10087
09-09 13:36:16.843  7903  7903 I libpersona: KNOX_SDCARD not a persona
,09-09 13:36:16.843  7903  7903 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 13:36:16.843  1015  1570 I ActivityManager: Killing 7600:com.sec.pcw.device/1000 (adj 15): empty #21
,09-09 13:36:16.843  7903  7903 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 13:36:16.843  7903  7903 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-09 13:36:16.853  1015  1477 I ActivityManager: Killing 7354:com.samsung.android.sconnect/u0a121 (adj 15): empty #21
,09-09 13:36:16.853  1015  1015 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-09 13:36:16.853  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-09 13:36:16.853  1015  1015 V EnterpriseBillingPolicy: uID is 10171
09-09 13:36:16.853  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
09-09 13:36:16.853  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-09 13:36:16.853  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-09 13:36:16.853  1015  3363 D SSRM:bc : MSG_TYPE_APP_REMOVED::
09-09 13:36:16.853  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-09 13:36:16.853  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-09 13:36:16.853  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
09-09 13:36:16.853  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-09 13:36:16.863  1015  1054 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-09 13:36:16.863  1015  1015 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
09-09 13:36:16.863  1015  1015 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
09-09 13:36:16.863  1015  1015 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
09-09 13:36:16.863  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
09-09 13:36:16.863  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-09 13:36:16.863  1015  1015 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
,09-09 13:36:16.863  1177  1177 I StatusBar: Icon Only
09-09 13:36:16.863  1177  1177 D PanelView: There is/are notification(s) 
,09-09 13:36:16.873  1015  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:16.873  1015  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:16.873  1015  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:16.873  1015  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:16.883  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-09 13:36:16.883  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 13:36:16.893  7922  7922 E Zygote  : MountEmulatedStorage(),
09-09 13:36:16.893  7922  7922 I libpersona: KNOX_SDCARD checking this for 10003
09-09 13:36:16.893  7922  7922 E Zygote  : v2
,09-09 13:36:16.893  7922  7922 I libpersona: KNOX_SDCARD not a persona
09-09 13:36:16.893  7922  7922 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:36:16.893  7922  7922 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-09 13:36:16.893  1015  1054 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7922 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-09 13:36:16.903  1015  1159 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml,
,09-09 13:36:16.903  7922  7922 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:36:16.903  7892  7892 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,09-09 13:36:16.913  7903  7903 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:36:16.913  7903  7903 D ActivityThread: Added TimaKeyStore provider
09-09 13:36:16.913  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-09 13:36:16.913  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-09 13:36:16.923  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 13:36:16.923  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-09 13:36:16.923  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-09 13:36:16.923  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-09 13:36:16.923  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-09 13:36:16.933  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 13:36:16.933  1015  1533 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
09-09 13:36:16.933  1015  1533 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,09-09 13:36:16.933  1015  1533 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:36:16.933  1015  1533 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:36:16.933  1015  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,09-09 13:36:16.933  7922  7922 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:36:16.933  1015  1486 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-09 13:36:16.933  1015  1486 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
09-09 13:36:16.933  7922  7922 D ActivityThread: Added TimaKeyStore provider
09-09 13:36:16.933  1015  1486 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:36:16.933  1015  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:36:16.933  1015  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,09-09 13:36:16.943  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-09 13:36:16.943  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:16.943  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:16.943  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:16.943  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:16.953  7938  7938 E Zygote  : MountEmulatedStorage()
,09-09 13:36:16.963  7938  7938 E Zygote  : v2
09-09 13:36:16.963  7938  7938 I libpersona: KNOX_SDCARD checking this for 1000
09-09 13:36:16.963  7938  7938 I libpersona: KNOX_SDCARD not a persona
,09-09 13:36:16.963  7938  7938 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:36:16.963  7938  7938 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 13:36:16.963  7938  7938 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:36:16.963  1015  1015 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7938 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
09-09 13:36:16.973  1015  1039 D UsbSettingsManager: clearDefaults: com.test.thalitest
09-09 13:36:16.973  1015  1570 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
09-09 13:36:16.973  1015  3173 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,09-09 13:36:16.973  1015  1570 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:16.973  1015  1570 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:16.973  1015  1570 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:16.973  1015  1570 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:16.973  1015  1039 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,09-09 13:36:16.993  7764  7764 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-09 13:36:16.993  7952  7952 E Zygote  : MountEmulatedStorage()
09-09 13:36:16.993  7952  7952 I libpersona: KNOX_SDCARD checking this for 10152
09-09 13:36:16.993  7952  7952 E Zygote  : v2
09-09 13:36:16.993  7952  7952 I libpersona: KNOX_SDCARD not a persona
09-09 13:36:16.993  7952  7952 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:36:16.993  1015  1570 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7952 uid=10152 gids={50152, 9997} abi=armeabi-v7a
09-09 13:36:16.993  7938  7938 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:36:16.993  7952  7952 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-09 13:36:16.993  7938  7938 D ActivityThread: Added TimaKeyStore provider
09-09 13:36:16.993  1015  1028 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-09 13:36:16.993  7952  7952 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 13:36:16.993  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
09-09 13:36:16.993  1015  1028 W ActivityManager: userId = 0, bbcId = -10000,
09-09 13:36:16.993  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:36:16.993  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,09-09 13:36:17.003  1015  1570 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,09-09 13:36:17.013  1015  1569 I ActivityManager: Killing 7621:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,09-09 13:36:17.023  1015  1571 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-09 13:36:17.023   307   307 I art     : Explicit concurrent mark sweep GC freed 8727(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 680us total 29.969ms
,09-09 13:36:17.023  1015  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:17.023  1015  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:17.023  1015  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:17.023  1015  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:17.033  7952  7952 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:36:17.033  7952  7952 D ActivityThread: Added TimaKeyStore provider
,09-09 13:36:17.043   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 676us total 17.924ms,
,09-09 13:36:17.063   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 623us total 19.059ms
,09-09 13:36:17.063  7938  7938 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
09-09 13:36:17.063  7938  7938 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-09 13:36:17.063  7938  7938 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-09 13:36:17.073  1015  1571 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=7972 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,09-09 13:36:17.083  7972  7972 E Zygote  : MountEmulatedStorage()
09-09 13:36:17.083  7972  7972 I libpersona: KNOX_SDCARD checking this for 10055
09-09 13:36:17.083  7972  7972 E Zygote  : v2
,09-09 13:36:17.083  7972  7972 I libpersona: KNOX_SDCARD not a persona
09-09 13:36:17.083  7972  7972 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:36:17.083  7972  7972 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 13:36:17.083  7972  7972 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:36:17.093  1015  1571 I ActivityManager: Killing 7090:com.sec.android.diagmonagent/1000 (adj 15): empty #21,
,09-09 13:36:17.123  1478  1478 I Choreographer: Skipped 40 frames!  The application may be doing too much work on its main thread.
,09-09 13:36:17.123  1478  1478 V ActivityThread: updateVisibility : ActivityRecord{1098c1d8 token=android.os.BinderProxy@368c9fc {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
09-09 13:36:17.123  1478  1478 D Launcher.HomeView: onStop
,09-09 13:36:17.123  1478  1478 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@368c9fc time:165294
,09-09 13:36:17.123  7938  7938 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-09 13:36:17.123  7938  7938 I PCWCLIENTTRACE_PushUtil: sales region : global
09-09 13:36:17.133  7938  7938 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-09 13:36:17.133  7938  7938 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,09-09 13:36:17.133  1015  1486 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,09-09 13:36:17.133  1015  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:17.133  1015  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:17.133  1015  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:17.133  1015  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:17.143  7972  7972 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:36:17.143  7972  7972 D ActivityThread: Added TimaKeyStore provider
,09-09 13:36:17.153  7952  7952 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
09-09 13:36:17.153  7952  7952 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,09-09 13:36:17.163  7952  7952 I TapandpayWidget:Utils: Clear T&P info.
09-09 13:36:17.163  7988  7988 E Zygote  : MountEmulatedStorage()
09-09 13:36:17.163  7988  7988 E Zygote  : v2
09-09 13:36:17.163  7988  7988 I libpersona: KNOX_SDCARD checking this for 10029
09-09 13:36:17.163  7988  7988 I libpersona: KNOX_SDCARD not a persona
09-09 13:36:17.163  7988  7988 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 13:36:17.163  7988  7988 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 13:36:17.163  1015  1486 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7988 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
09-09 13:36:17.163  7988  7988 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 13:36:17.163  1015  1486 I ActivityManager: Killing 7062:com.android.email/u0a141 (adj 15): empty #21
09-09 13:36:17.173  7952  7952 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
,09-09 13:36:17.173  1015  1323 I ActivityManager: Killing 7713:com.sec.android.soagent/u0a31 (adj 15): empty #21
,09-09 13:36:17.183  1015  1028 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 13:36:17.183  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chimera.GmsIntentOperationService; callingUser = 0; userId(target) = 0
,09-09 13:36:17.183  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:36:17.183  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:36:17.183  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:36:17.183  7988  7988 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:36:17.183  7988  7988 D ActivityThread: Added TimaKeyStore provider
,09-09 13:36:17.213  1963  1963 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
09-09 13:36:17.213  1963  1963 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-09 13:36:17.213  1963  1963 D AndroidRuntime: Shutting down VM
,09-09 13:36:17.223  1015  1571 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gsf
,09-09 13:36:17.223  1015  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:17.223  1015  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:17.223  1015  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:36:17.223  1015  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:36:17.233  7972  7972 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()

```
